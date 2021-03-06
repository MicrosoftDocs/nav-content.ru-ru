---
title: "Электронные документы в Dynamics NAV"
description: "Введение в отправку и получение электронных документов в [!INCLUDE[d365fin](includes/d365fin_md.md)]."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/19/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5459a76797a948555a6a20009d57de96fe9eec7f
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="exchanging-data-electronically"></a>Электронный обмен данными
Можно использовать платформу обмена данными, чтобы обмениваться бизнес-документами, банковскими файлами, курсами обмена валют и другими файлами данных с бизнес-партнерами.

## <a name="electronic-documents"></a>Электронные документы
Вместо отправки файлов в виде вложений в сообщения электронной почты можно отправлять и получать бизнес-документы в электронном виде. Под электронным документом понимается документ в виде соответствующего стандарту файла, представляющего бизнес-документ (например, счет от поставщика), который может быть получен и преобразован в счет покупки в [!INCLUDE[d365fin](includes/d365fin_md.md)]. Обмен электронными документами между двумя торговыми партнерами выполняется внешним провайдером служб обмена документами. Универсальная версия [!INCLUDE[d365fin](includes/d365fin_md.md)] поддерживает отправку и получение электронных счетов и кредит-нот в формате PEPPOL, поддерживаемом крупнейшими поставщиками служб обмена документами. Крупный поставщик служб обмена документами заранее настроен и готов установке в вашей компании. Чтобы обеспечить поддержку других форматов электронных документов, необходимо создать новые определения обмена данными с помощью платформы обмена данными.  

Из файлов PDF или графических файлов, представляющих входящие документы, с помощью внешней службы OCR (оптического распознавания символов) можно создавать электронные документы, которые затем будут преобразовываться в записи документов в [!INCLUDE[d365fin](includes/d365fin_md.md)], аналогично электронным документам PEPPOL. Например, при получении от поставщика счета в формате PDF можно отправить его в службу OCR в окне **Входящие документы**. Спустя несколько секунд файл будет возвращен в виде электронного счета, который может быть преобразован в счет покупки для этого поставщика. Если вы отправляете файл в службу OCR по электронной почте, то новая запись входящего документа создается автоматически при получении назад электронного документа.  

Например, чтобы отправить счет продажи как электронный документ PEPPOL, следует выбрать параметр **Электронный документ** в диалоговом окне **Учет и отправка**. В этом окне также можно настроить профиль отправки документов клиента по умолчанию. Прежде всего, необходимо настроить различные основные данные – такие как информацию об организации, клиентах, товарах и единицах измерения. Они используются для определения бизнес-партнеров и товаров при преобразовании данных в полях [!INCLUDE[d365fin](includes/d365fin_md.md)] в элементы файла исходящего документа. Преобразование данных и отправка счета продажи PEPPOL выполняется соответствующим модулем codeunit и XMLport, представленными форматом электронных документов **PEPPOL**.  

Например, для получения счета от поставщика в формате электронного документа PEPPOL необходимо обработать документ в окне **Входящие документы**, преобразовав его в счет покупки в [!INCLUDE[d365fin](includes/d365fin_md.md)]. Можно настроить функцию очереди заданий для обработки таких файлов на регулярной основе либо запускать этот процесс вручную. Прежде всего, необходимо настроить различные основные данные – такие как информацию об организации, поставщиках, товарах и единицах измерения. Они используются для определения бизнес-партнеров и товаров при преобразовании данных в элементах файла исходящего документа в поля в [!INCLUDE[d365fin](includes/d365fin_md.md)]. Получение и преобразование счетов PEPPOL выполняются платформой обмена данными, представленной в определении обмена данными **PEPPOL — Счет**.  

 Например, чтобы получить счет в виде электронного документа OCR, его необходимо обработать как при получении электронного документа PEPPOL. Получение и преобразование электронных документов из OCR выполняется платформой обмена данными, представленной в определении обмена данными **OCR — Счет**.  

## <a name="bank-files"></a>Банковские файлы  
 Форматы файлов для обмена банковскими данными с ERP-системами варьируются в зависимости от поставщика файла и страны или региона. Универсальная версия [!INCLUDE[d365fin](includes/d365fin_md.md)] поддерживает импорт и экспорт банковских файлов SEPA и услугу преобразования банковских данных, предлагаемую внешним поставщиком – AMC Consult. Чтобы обеспечить поддержку других форматов электронных документов, следует использовать платформу обмена данными.  

Для экспорта кредитных переводов SEPA нажмите кнопку **Экспорт платежей в файл** в окне **Журнал платежей** и загрузите файл для обработки платежей в свой банк. Вначале необходимо задать различные основные данные – такие как банковский счет, поставщики и способы оплаты. Преобразование данных и экспорт банковских данных SEPA выполняется соответствующим модулем codeunit и XMLport, представленными в настройке банковского импорта и экспорта **Кредитные переводы SEPA**. Также можно настроить службу преобразования банковских данных для выполнения экспорта, представленную определением обмена данными **Служба преобразования банковских данных – кредитовый перевод**.  

Для экспорта команд для прямого дебита формата SEPA нажмите кнопку **Экспорт файла прямого дебетования** в окне **Коллекции прямого дебетования** и отправьте ее в свой банк для автоматического сбора указанных в ней платежей клиента. Вначале необходимо задать банковские счета, клиентов, поставщиков, мандаты прямого дебита и способы оплаты. Преобразование данных и экспорт банковских данных SEPA выполняется соответствующим модулем codeunit и XMLport, отраженными в настройке банковского импорта и экспорта **Прямой дебит SEPA**.  

Для импорта банковских выписок SEPA нужно нажать кнопку "Импорт банковских выписок" в окнах **Журнал выверки платежей** и **Выверка банковского счета**, после чего приложить каждую запись банковской выписки к платежам или записям банковской книги в ручном или автоматическом режиме. Необходимо сначала настроить банковские счета. Импорт и преобразование банковских данных SEPA выполняется платформой обмена данными, представленной в определении обмена данными **SEPA CAMT**. Также можно настроить службу преобразования банковских данных для выполнения импорта, представленную определением обмена данными **Служба преобразования банковских данных – банковские выписки**.  

 Кроме того, локальные версии [!INCLUDE[d365fin](includes/d365fin_md.md)] поддерживают разные другие форматы файлов для импорта и экспорта банковских данных, перечислений заработной платы и других данных. Дополнительные сведения см. раздел справки “Локальные функции” в версии [!INCLUDE[d365fin](includes/d365fin_md.md)] для вашей страны.  

## <a name="currency-exchange-rates"></a>Валютные курсы  
Для обновления валютных курсов можно использовать внешнюю службу. Служба, предоставляющая обновленные валютные курсы, разрешена определением обмена данными. Соответственно, окно **Карточка настройки обновления валютных курсов** представляет собой сжатый вид окна **Определение обмена данными** для рассматриваемого определения обмена данными.  

Для всего обмена данными в XML-файлах можно подготовить настройку обмена данными, загрузив связанный файл XML-схемы в окне **Средство просмотра схем XML**. Здесь можно выбрать элементы данных, которыми требуется обменяться с [!INCLUDE[d365fin](includes/d365fin_md.md)], а затем чего инициализировать определение обмена данными или сгенерировать XMLport.  

В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.  

|По|Ссылка|  
|--------|---------|  
|Дополнительные сведения о работе структуры обмена данными.|[О структуре обмена данными](across-about-the-data-exchange-framework.md)|  
|Подготовка к обмену данными в файле посредством повторного использования XML-схемы файла. Настройка определений обмена данными. Настройка основных данных для отправки электронного документа. Настройка различных полей импорта/экспорта банковских файлов.|[Настройка обмена данными](across-set-up-data-exchange.md)|  
|На основе определений обмена данными можно отправлять и получать счета PEPPOL, импортировать банковские выписки и экспортировать файлы банковских платежей.|[Обмен данными](across-exchange-data.md)|  

## <a name="see-also"></a>См. также  
[О структуре обмена данными](across-about-the-data-exchange-framework.md)  
[Практическое руководство. Использование XML-схем для определения обмена данными](across-how-to-use-xml-schemas-to-prepare-data-exchange-definitions.md)  
[Настройка обмена данными](across-set-up-data-exchange.md)  
[Обмен данными](across-exchange-data.md)  
[Входящие документы](across-income-documents.md)  
[Общие бизнес-функции](ui-across-business-areas.md)

