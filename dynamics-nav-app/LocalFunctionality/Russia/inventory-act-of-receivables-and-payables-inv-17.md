---
title: "Акт инвентаризации расчетов с клиентами и платежей ИНВ-17"
description: "Функция \"Акт инвентаризации расчетов с клиентами и платежей\" позволяет выполнить инвентаризацию долгов и обязательств и напечатать отчеты в различных форматах."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: f0c8bd36fb13d93397fd173c54a962eb6f5395f1
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="inventory-act-of-receivables-and-payables-inv-17"></a>Акт инвентаризации расчетов с клиентами и платежей ИНВ-17
Функция "Акт инвентаризации расчетов с клиентами и платежей" позволяет выполнить инвентаризацию долгов и обязательств и напечатать отчеты в следующих форматах:  

- ИНВ-17  
- Приложение к ИНВ-17  

## <a name="setting-up-a-number-series-for-inventory-acts"></a>Настройка серии номеров для актов инвентаризации  
Ниже приводится процедура настройки серии номеров для актов инвентаризации.  

1. Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка ГК**, а затем выберите связанную ссылку.  
2. В окне **Настройка ГК** заполните поле **Серия ном. актов инв. расч. с контрагентами**.   

## <a name="inventory-act-processing"></a>Обработка актов инвентаризации  
Можно создать и обработать акты инвентаризации счетов контрагентов. Также эти акты можно напечатать.  

### <a name="creating-an-inventory-act-card"></a>Создание карточки акта инвентаризации  
Ниже приводится процедура создания карточки акта инвентаризации.  

1.  Выберите действие **Главная книга**, выберите действие **Анализ и отчетность**, затем выберите действие **Акты инв. расч. с контрагентами**.
2.  В окне **Карточка Товары Фин. Счет** введите сведения в следующие поля:  

    |Поле|Описанием|  
    |-----------|-----------------|  
    |**Номер**|В этом поле отображается номер акта, и оно заполняется автоматически из серии номеров.|  
    |**Дата акта**|В этом поле отображается дата акта, и оно заполняется рабочей датой.|  
    |**Дата инвентаризации**|В этом поле отображается дата инвентаризации, и оно заполняется рабочей датой. Долги и обязательства будут рассчитываться на эту дату.|  
    |**Основание Документа Тип**|Выберите тип основания документа из следующих:<br /><br /> -   **Заказ**<br />-   **Постановление**;<br />-   **Распоряжение**.|  

3.  Выберите действие **Добавить строки**.  

    > [!NOTE]  
    >  Нельзя задавать фильтры.  

 Создаются долги и обязательства для поставщиков и клиентов, а также строки. Для каждого клиента и поставщика рассчитываются и отображаются в отдельной строке общая сумма долгов и обязательств на дату инвентаризации (учитывая группы учета). Поля строк описаны в следующей таблице.  

|Поле|Описанием|  
|-----------|-----------------|  
|**Контрагент Тип**|В этом поле отображается тип контрагента (клиент, поставщик).|  
|**Контрагент Но.**|В этом поле отображается номер, соответствующий контрагенту.|  
|**Контрагент Название**|В этом поле показано имя контрагента.|  
|**Учетная Группа, Фин. Счет Но.**|В данном поле отображается группа учета и фин. счет расчетов с клиентами или поставщиками, для которого рассчитывается сумма долгов или обязательств.|  
|**Категория**|В этом поле отображается сумма категории (долги, обязательства).|  
|**Общая сумма**|В этом поле отображается общая сумма долгов и обязательств.|  
|**Подтвержденная сумма**|В этом поле отображается общая сумма долгов и обязательств по умолчанию.|  

### <a name="changing-separate-lines-in-an-inventory-act"></a>Изменение отдельных строк акта инвентаризации  
Ниже приводится процедура изменения отдельных строк акта инвентаризации в окне **Карточка Товары Фин. Счет**.  

1. Укажите, один из следующих вариантов для суммы (или части суммы):  

- Подтверждена контрагентом  
- Не подтверждена  
- Просрочено  

2. Если сумма не подтверждена, введите неподтвержденную сумму в поле **Неподтвержденная сумма**.
3. Если сумма просрочена, введите сумму в поле **С истекшим сроком исковой давности**.  
3. Чтобы исправить строку с неправильной суммой (например, если некоторые документы не учтены или не применены), выберите действие **Добавить строки**.  
5.  Выберите код поставщика или клиента, затем выберите кнопку **ОК**.  

Сумма долгов и обязательств для выбранного поставщика или клиента пересчитывается, и строки вставляются в документ.  

## <a name="printing-the-inv-17-form-and-the-supplement-to-inv-17-form"></a>Печать формы ИНВ-17 и формы Приложение в ИНВ-17  
 Ниже приводится процедура печати формы ИНВ-17 и формы Приложение к ИНВ-17.  

1.  В окне **Карточка Товары Фин. Счет** выберите действие **Выпустить**.  
3.  Выберите действие **Акт**, затем выберите действие **Подписи**.  
4.  Выберите следующие поля:  

- **Председатель**  
- **Член комиссии 1**  
- **Член комиссии 2**  
- **Член комиссии 3**  
- **Бухгалтер**  

    > [!NOTE]  
    >  Все выбранные подписи будут отображены в соответствующих полях.  

5.  Выберите действие **Печать**, затем выберите действие **Акт инвентаризации ИНВ-17** для печати акта инвентаризации.  
6.  Выберите действие **Печать**, затем выберите действие **Приложение к Акту инвентаризации ИНВ-17** для печати приложения к акту инвентаризации.  

## <a name="see-also"></a>См. также  
 [Отчеты по платежам (Россия)](russian-payables-reports.md)   
 [Отчеты по расчетам с клиентами (Россия)](russian-receivables-reports.md)
