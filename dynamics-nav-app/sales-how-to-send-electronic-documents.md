---
title: "Отправка электронных документов"
description: "Узнайте, как отправлять счета в электронном виде."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5920ed97f054b3e7882f40f2fceec76183800297
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-send-electronic-documents"></a>Практическое руководство. Отправка электронных документов
Универсальная версия [!INCLUDE[d365fin](includes/d365fin_md.md)] поддерживает отправку электронных счетов и кредит-нот в формате PEPPOL, поддерживаемом крупнейшими поставщиками служб обмена документами. Поставщик службы обмена документами обеспечивает перемещение электронных документов между торговыми партнерами. Чтобы обеспечить поддержку других форматов электронных документов, следует использовать платформу обмена данными.  

 В универсальной версии [!INCLUDE[d365fin](includes/d365fin_md.md)] служба обмена документами предварительно сконфигурирована и готова для настройки в вашей компании. Дополнительные сведения см. в разделе [Практическое руководство. Настройка службы обмена документами](across-how-to-set-up-a-document-exchange-service.md).  

 Для отправки счета продажи в виде электронного документа PEPPOL следует выбрать вариант **Электронный документ** в диалоговом окне **Учет и отправка**, в котором также можно задать его в качестве профиля отправки документов клиенту по умолчанию. Прежде всего, необходимо настроить различные основные данные – такие как информацию об организации, клиентах, товарах и единицах измерения. Они используются для определения бизнес-партнеров и товаров при преобразовании данных в полях в разделе [Практическое руководство. Настройка отправки и получения электронных документов](across-how-to-set-up-electronic-document-sending-and-receiving.md).  

### <a name="to-send-an-electronic-sales-invoice"></a>Отправка электронного счета продажи  

1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Счета продажи**, а затем выберите связанную ссылку.  

2.  Создайте новый счет продажи.  

3.  Когда счет продажи готов к выставлению, вкладке **Действия** в группе **Учет** выберите **Учет и отправка**.  

     Если в профиле клиент по умолчанию указано **Электронный документ**, он также будет указан в диалоговом окне **Подтверждение учета и отправки**; необходимо только нажать кнопку **Да** для отправки счета по электронной почте в выбранном в формате.  

4.  В диалоговом окне **Подтверждение учета и отправки** нажмите кнопку AssistEdit справа от поля **Кому отправить документ**.  

5.  В диалоговом окне **Кому отправить документ** в поле **Электронный документ** выберите **Через службу обмена документами**.  

6.  В поле **Формат** выберите **PEPPOL**.  

7.  Нажмите кнопку **ОК**. Откроется диалоговое окно **Подтверждение учета и отправки**. **Электронный документ (PEPPOL)** будет добавлен в поле **Кому отправить документ**.  

8.  Нажмите кнопку **Да**.  

     Счет продажи учтен и отправлен клиенту в виде электронного документа в формате PEPPOL.  

    > [!NOTE]  
    >  Можно также отправить учтенный счет на продажу в виде электронного документа. Процедура аналогична описанной в этом разделе для документов неучтенных продаж. В окне **Учтенный счет продажи** на вкладке **Действия** в группе **Общее** выберите **Журнал действий** для просмотра статуса электронного документа. Для получения дополнительных сведений см раздел **Журнал действий**.  

## <a name="see-also"></a>См. также  
[Практическое руководство. Выставление счетов продажи](sales-how-invoice-sales.md)  
[Практическое руководство. Настройка профилей отправки документов](sales-how-setup-document-send-profiles.md)  
[Практическое руководство. Настройка отправки и получения электронных документов](across-how-to-set-up-electronic-document-sending-and-receiving.md)  
[Практическое руководство. Настройка службы обмена документами](across-how-to-set-up-a-document-exchange-service.md)  
[Практическое руководство. Настройка определений обмена данными](across-how-to-set-up-data-exchange-definitions.md)  
[Электронный обмен данными](across-data-exchange.md)  
[Общие бизнес-функции](ui-across-business-areas.md)  

