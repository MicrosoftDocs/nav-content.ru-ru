---
title: "Подача отчетов об НДС в налоговые органы"
description: "Узнайте, как подготовить отчеты по НДС с продаж за указанный период или с продаж и покупок, и подать этот отчет в налоговый орган."
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: VAT, tax, report, EC sales list, statement
ms.date: 07/17/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b4a0bad8b703591622081a42d7615145965c4957
ms.contentlocale: ru-ru
ms.lasthandoff: 10/23/2017

---

# <a name="how-to-report-vat-to-a-tax-authority"></a>Практическое руководство. Подача отчета об НДС в налоговые органы
В этом разделе описываются отчеты в [!INCLUDE[d365fin](includes/d365fin_md.md)], которые можно использовать для подачи сведений о суммах налога на добавленную стоимость (НДС) для продаж и покупок в налоговые органы региона.

При этом можно пользоваться следующими отчетами:

* В отчете **Список продаж EC** списка продаж в ЕС перечисляются суммы налога на добавленную стоимость (НДС), который был собран по продажам клиентам, зарегистрированным для НДС, в странах Европейского Союза (ЕС).  
* Отчет **Возврат НДС** содержит НДС для продаж и покупок клиентам во всех странах, в которых используется НДС.

Если требуется просмотреть полную историю операций с НДС, каждая проводка, имеющая отношение к НДС, создает операцию на странице **Операции НДС**. Эти операции используются для расчета суммы расчетов по НДС, то есть суммы оплаты и возврата, для конкретного промежутка времени. Для просмотра операций с НДС выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Операции НДС**, затем выберите связанную ссылку.

## <a name="about-the-ec-sales-list-report"></a>Об отчете "Список продаж EC"
В Великобритании все организации, которые продают товары и услуги клиентам, зарегистрированным для НДС, включая клиентов в других странах Европейского Союза (ЕС), должны подавать электронную версию списка продаж ЕС в формате XML через веб-сайт HMRC (Her Majesty's Revenue and Customs). Список продаж ЕС применим только к странам-членам ЕС.

Отчет содержит одну строку для каждого типа транзакций с клиентом и отображает общую сумму для каждого типа транзакций. Есть три типа транзакций, которые могут входить в отчет:  

* Товары B2B  
* Услуги B2B  
* Товары B2B с триангуляцией  

Товары и услуги B2B определяет, что вы продали товар или услугу, и задаются параметром **Сервис ЕС** в настройке учета НДС. Товары B2B с триангуляцией показывают, что вы участвовали в торговле с посредником и задаются параметром **Торговля вне ЕС** в документах продажи, таких как заказы на продажу, счета, кредит-ноты и т. д.  

После проверки отчета в налоговом органе, они отправят сообщение электронной почты контактному лицу вашей компании. В [!INCLUDE[d365fin](includes/d365fin_md.md)] контактное лицо указывается на странице **Информация об организации**. Перед отправкой отчета убедитесь, что выбрано контактное лицо.

## <a name="about-the-vat-return-report"></a>Об отчете о возврате НДС
Используйте этот отчет для представления документов по НДС для покупки и продажи, например заказов на покупку и продажу, счетов и кредит-нот. Информация в отчете отображена в том же формате, что и в форме декларации из таможенных и налоговых органов.  

НДС рассчитывается на основании настройки учета НДС и учетных групп НДС, настроенных ранее.

Для возврата НДС можно указать включаемые операции:

* Отправлять только открытые транзакции либо открытые и закрытые. Это удобно, например, если готовится окончательный ежегодный возврат НДС.
* Отправка только операций из указанных периодов или также включение операций из предыдущих периодов. Это удобно для обновления возврата НДС, который уже был отправлен, например, если поставщик поздно отправил счет.    

## <a name="to-connect-to-your-tax-authoritys-web-service"></a>Подключение к веб-службе налогового органа
[!INCLUDE[d365fin](includes/d365fin_md.md)] предоставляет служебные подключения к веб-сайтами налоговых органов. Например, если организация расположена в Великобритании, то можно включить подключение к сервису **GovTalk** для отправки отчетов "Список продаж ЕС" и "Возврат НДС" в электронном виде. Если вы хотите отправить отчет вручную, например путем ввода данных на веб-сайте налогового органа, это не требуется.   

Для подачи отчетности по НДС в налоговый орган в электронном необходимо подключить [!INCLUDE[d365fin](includes/d365fin_md.md)] к веб-службе налогового органа. Для этого нужно настроить учетную запись в налоговом органе. После настройки этой учетной записи вы можете создать подключение к службе через [!INCLUDE[d365fin](includes/d365fin_md.md)].

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Подключения к службе**, а затем выберите соответствующую ссылку.
2. Заполните обязательные поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    > [!NOTE]  
>   Рекомендуется проверить подключение. Чтобы это сделать, установите флажок **Тестовый режим**, затем подготовьте и отправьте отчет по НДС, как описано в разделе _Подготовка и отправка отчета по НДС_. В тестовом режиме служба проверяет, может ли налоговый орган принимать ваш отчет, и статус отчета покажет, была ли тестовая передача успешной. Важно помнить, что это не фактическая передача. Чтобы по-настоящему отправить отчет, необходимо снять флажок **Тестовый режим**, затем повторить процесс отправки.

## <a name="to-set-up-vat-reports-in-included365finincludesd365finmdmd"></a>Настройка отчетов по НДС в [!INCLUDE[d365fin](includes/d365fin_md.md)]
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка отчета по НДС**, затем выберите связанную ссылку.  
2. Чтобы разрешить пользователям изменять и повторно отправлять этот отчет, установите флажок **Изменить отправленные отчеты**.  
3. Выберите серию номеров для использования для каждого отчета.  

## <a name="to-prepare-and-submit-a-vat-report"></a>Подготовка и отправка отчета по НДС
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Список продаж EC** или **Возврат НДС** для использования, затем выберите связанную ссылку.  
2. Выберите **Создать**, а затем заполните обязательные поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Для генерации содержимого отчета выберите действие **Предложить строки**.  

    > [!NOTE]  
>   В отчете "Список продаж EC" можно просмотреть транзакции, включенные в строки отчета, перед отправкой отчета. Для этого выберите строку, а затем выберите действие **Показать операции НДС**.  
4. Для проверки и подготовки отчета к отправке выберите действие **Выпустить**.  

    >  [!NOTE]  
>   [!INCLUDE[d365fin](includes/d365fin_md.md)] проверяет, настроен ли отчет правильно. Если обнаружены ошибки, они будут показаны в разделе **Ошибки и предупреждения**, чтобы вы знали, что требуется исправить. Обычно если сообщение связано с отсутствующей настройкой в [!INCLUDE[d365fin](includes/d365fin_md.md)], можно нажать сообщение для открытия страницы, содержащей информацию, которую нужно исправить.  
5. Для отправки отчета выберите действие **Отправить**.  

После отправки отчета [!INCLUDE[d365fin](includes/d365fin_md.md)] следит за службой и фиксирует ваши коммуникации. Поле **Состояние** указывается, на каком этапе находится обработка отчета. Например, после обработки отчета налоговыми органами состояние отчета изменяется на **Успешно**. Если налоговый орган нашел ошибку в отправленном отчете, отчет будет иметь состояние **Ошибка**. Ошибки можно просмотреть в разделе **Ошибки и предупреждения**, исправить их, а затем подать отчет заново. Чтобы просмотреть список всех отчетов "Список продаж ЕС", перейдите на страницу **Отчеты по списку продаж EC**.  

## <a name="viewing-communications-with-your-tax-authority"></a>Просмотр взаимодействий с налоговыми органами
В некоторых странах при отправке отчета вы обмениваетесь сообщениями с налоговыми органами. Вы можете просмотреть первое и последнее отправленное или полученное сообщение с помощью действий **Загрузить сообщение отправки** и **Загрузить сообщение отклика**.  

## <a name="submitting-vat-reports-manually"></a>Отправка отчетов по НДС вручную
Если используется другой способ подачи отчета, например путем экспорта XML и его отправки на веб-сайт налогового органа, можно потом выбрать **Отметить как отправленное**, чтобы закрыть отчетный период. При отметке отчета как отправленного, он становится недоступным для редактирования. Если необходимо изменить отчет после его отметки как отправленного, его нужно повторно открыть.

## <a name="vat-settlement"></a>Зачет НДС
Необходимо периодически предоставлять в налоговые органы данные о чистой сумме НДС. Если требуется часто выполнять зачет НДС, можно выполнить пакетное задание **Вычисление и учет зачета НДС**, чтобы закрыть открытые операции НДС и передать суммы НДС по продажам и покупкам на счет расчетов по НДС.

При переносе сумм НДС на счет расчетов счет НДС по покупкам кредитуется, а счет НДС по продажам дебетуется на суммы, рассчитанные для указанного периода. Чистая сумма кредитуется или дебетуется, если сумма НДС по покупкам больше, по счету расчетов по НДС. Расчетную сумму можно сразу учесть, либо сначала распечатать тестовый отчет.

>    [!NOTE]  
>    Если при использовании пакетного задания **Вычисление и учет зачета НДС** не указаны параметры **НДС бизнес-группа** и **НДС товарная группа**, включаются операции со всеми кодами бизнес-групп и товарных групп.

## <a name="configuring-your-own-vat-reports"></a>Настройка собственных отчетов об НДС
Вы можете использовать готовый отчет "Список продаж в ЕС" или создать собственные отчеты. При этом создается несколько модулей codeunit. Если требуется помощью, обратитесь к партнеру Майкрософт.  

В следующей таблице описываются модули codeunit, которые необходимо создать для отчета.

| Модуль Codeunit | Что должен делать |
|----|-----|
|Предложить строки| Получить сведения из таблицы операций НДС и показать их в строках отчета по НДС.|
|Содержимое | Контролировать формат отчета. Например, выбрать между JSON и XML. Используемый формат зависит от требований веб-службы налогового органа. |
|Отправка | Определяет как и когда подается отчет на основе требований налоговых органов. |
|Обработчик отклика | Обработка отклика от налогового органа. Например, он может отправить сообщение электронной контактному лицу в вашей организации. |
|Отмена | Отправить отмену отчета по НДС, который ранее был подан в налоговый орган. |

> [!NOTE]  
>   При создании модулей codeunit для отчета следует следить за значением поля **Версия отчета по НДС**. Это поле должно отражать версию отчета, которая требуется налоговыми органами. Например, в этом поле можно ввести **2017** для указания того, что отчет соответствует требованиям, действующим в этом году. Чтобы узнать текущую версию, обратитесь в свой налоговый орган.  

## <a name="see-also"></a>См. также
[Настройка методов расчета и учета налога на добавленную стоимость](finance-setup-vat.md)  
[Практическое руководство. Работа с НДС по продажам и покупкам](finance-work-with-vat.md)  
[Настройка продаж](sales-setup-sales.md)  
[Практическое руководство. Выставление счетов продажи](sales-setup-sales.md)  
