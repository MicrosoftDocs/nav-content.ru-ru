---
title: "Финансовый оборот для товара"
description: "Указанные ниже страницы и отчеты позволяют создавать оборотную ведомость для товаров и материалов."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 5516e95b5a537a7bb49719efe79fc322ceb1993a
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="item-general-ledger-turnover"></a>Финансовый оборот для товара
Указанные ниже страницы и отчеты позволяют создавать оборотную ведомость для товаров и материалов.  

- Финансовый оборот для товара — страница 12449  
- Товар Оборот (Кол-во) - отчет 12469  
- Товар Оборот Памятка - отчет 12489  

## <a name="item-general-ledger-turnover-page-12449"></a>Страница финансового оборота для товара (12449)  
Окно **Финансовый оборот для товара** показывает оборот для товаров в количествах и затратах, сальдо на начало месяца, приход и расход, а также сальдо на конец месяца.  

Окно **Финансовый оборот для товара** обычно создается ежемесячно, а также может быть создана на дату инвентаризации. Данные в окне **Финансовый оборот для товара** сверяются с данными складского учета. Данные по затратам сверяются с чистыми изменениями и сальдо:  

- счета 41, Товары  
- счета 10, Материалы  

Чтобы открыть окно **Финансовый оборот для товара**  

1. Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Товары - оборотная ведомость по ГК**, а затем выберите связанную ссылку.
2. На экспресс-вкладке **Параметры** имеется возможность указать параметры форматирования, приведенные в следующей таблице.  

|Поле|Описанием|
|---|---|  
|**«Фильтр по дате»**|Введите период, для которого анализируются данные. Можно использовать кнопки, расположенные в нижнем левом углу окна, или указать период вручную.|  
|**Склад Фильтр**|Введите код склада, по которому необходимо отфильтровать сведения. Можно ввести до 10 символов, включая цифры и буквы.|  
|**Фильтр глобального измерения 1**|Введите значение фильтра для анализа в фильтре "Глобал. Измерение 1".|  
|**Фильтр глобального измерения 2**|Введите значение фильтра для анализа в фильтре "Глобал. Измерение 2".|  

Окно содержит поля со сведениями, перечисленными в следующей таблице. Значения в этих полях изменить нельзя.  

|Поле|Описание|  
|---|---|
|**Номер**|В этом поле отображается номер товара.|  
|**Описание**|В этом поле отображается описание товара.|  
|**Баз. Единица Измерения**|В этом поле отображается базовая единица измерения товара. Единица измерения указывается в карточке товара как базовая.|  
|**Количество на Начало**<br /><br /> **Количество на Конец**<br /><br /> **Расход Кол-во**<br /><br /> **Кредит Количество**|В этих полях содержатся сведения о количестве товара — количество товара на начало и на конец периода, а также приход и расход товара. Количество указывается в базовых единицах измерения.|  
|**Себестоимость на Начало**<br /><br /> **Затраты на Конец**<br /><br /> **Дебет Затраты**<br /><br /> **Кредит Затраты**|В этих полях содержатся сведения о себестоимости товара на начало и на конец периода, а также приход и расход в финансовых суммах. Значения в этих полях вычисляются на основе сумм себестоимости, учтенных в операции ГК.|  

Чтобы открыть выбранную карточку товара  

- Выберите кнопку **Товар**, а затем выберите **Карточка** (сочетание клавиш Shift+F5).  

Чтобы напечатать отчеты **Товар Оборот (Кол-во)** или **Товар Оборот Памятка**.  

- Выберите действие **Печать**, выберите действие **Оборотная ведомость (кол-во)** или **Оборот Памятка**.  

## <a name="item-turnover-qty-report-12469"></a>Отчет "Товар Оборот (Кол-во)" (12469)  
Для анализа чистых изменений и сальдо товаров и материалов можно напечатать отчет "Товар Оборот (Кол-во)" и экспортировать его в Microsoft Office Excel. В этом отчете печатаются следующие данные из окна "Финансовый оборот для товара":  

- Номер и описание товара  
- Сальдо в начале указанного периода (количество и себестоимость)  
- Приход (количество и себестоимость)  
- Расход (количество и себестоимость)  
- Сальдо в конце указанного периода (количество и себестоимость)  
- Единица измерения  

Ниже описана процедура доступа к отчету оборотной ведомости.  

1.  Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовый оборот для товара**, а затем выберите связанную ссылку.  
2.  Выберите действие **Печать**, а затем выберите действие **Оборотная ведомость (кол-во)**.  

Отчет "Оборот Листок" печатается ежемесячно и на дату инвентаризации, но может быть напечатан для любого данного периода.  

Экспресс-вкладка **Товар** страницы запроса содержит поля со сведениями, приведенными в следующей таблице.  

|Поле|Описанием|  
|---|---|
|**Номер**|Введите номер товара или диапазон номеров, чтобы напечатать финансовый оборот для одного товара или для группы товаров.|  
|**Склад Фильтр**|Введите код склада, для которого требуется фильтровать информацию, чтобы печатать окно "Финансовый оборот для товара" для одного или нескольких складов.<br /><br /> Можно ввести до 10 символов, включая цифры и буквы. Значение поля вводится автоматически в поле **Склад Фильтр**|  
|**«Фильтр по дате»**|Введите период, для которого печатается отчет.|  

На экспресс-вкладке **Параметры** имеется возможность указать параметры форматирования, приведенные в следующей таблице.  

|Параметр|Описанием|  
|---|---|
|**Точность округления**|Выберите необходимую точность округления:<br /><br /> 0,001, 0,01, 1 или 1000.|  
|**Заменять нулевые значения на пропуски**|Установите этот флажок, если необходимо заменять нулевые значения на пустые места.|  
|**Пропускать счета без оборотов**|Установите этот флажок, чтобы исключить из отчета счета с нулевым товарооборотом за данный период.|  
|**Пропускать счета с нулевым конечным сальдо**|Установите этот флажок, чтобы исключить из отчета счета с нулевым конечным сальдо в конце периода.|  
|**Пропускать нулевые строки**|Установите этот флажок, чтобы исключить из отчета строки с нулевым значением.|  
|**Единица Измерения**|Выберите единицу измерения для расчета количеств в отчете:<br /><br /> -   **Базовая**: в базовых единицах измерения<br />-   **Продажа**: в единицах измерения для продаж<br />-   **Покупка**: в единицах измерения для покупок|  
|**Печатать Кол-во**|Установите этот флажок, чтобы печатать количество, которое указано в отчете.|  
|**Печать Затраты**|Установите этот флажок, чтобы печатать затраты, которые указаны в отчете.|  
|**Экспорт в Excel**|Установите этот флажок для экспорта отчета в Microsoft Office Excel.|  

## <a name="item-turnover-checklist-report-12489"></a>Отчет Товар Оборот Памятка (12489)  
Отчет **Товар Оборот Памятка** обеспечивает учет ожидаемых затрат на товары и материалы, которые получены, но не оплачены.  

Отчет **Товар Оборот Памятка** печатает все сведения о товарах и материалах из отчета **Товар Оборот (Кол-во)** и, кроме того, печатает сальдо ожидаемой себестоимости:  

- Номер и описание товара  
- Сальдо в начале указанного периода (количество, ожидаемая себестоимость и сальдо)  
- Приход товара (количество, ожидаемая себестоимость и сальдо)  
- Расход товара (количество, ожидаемая себестоимость и сальдо)  
- Оборот в конце указанного периода (количество, ожидаемая себестоимость и сальдо)  
- Единица измерения  

Ниже описана процедура доступа к отчету "Оборот Памятка".  

1.  Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовый оборот для товара**, а затем выберите связанную ссылку.  
2.  Выберите действие **Печать**, а затем выберите действие **Оборот Памятка**.  

Отчет "Оборот Памятка" печатается ежемесячно и на дату инвентаризации, но может быть напечатан для любого заданного периода.  

Экспресс-вкладка **Товар** страницы запроса содержит поля со сведениями, приведенными в следующей таблице.  

|Поле|Описанием|  
|---|---|
|**Номер**|Введите номер товара или диапазон номеров, если необходимо напечатать отчет для одного товара или для группы товаров.|  
|**Код Товарной Категории**|Введите код товарной категории. Этот код определяет следующие значения по умолчанию:<br /><br /> -   Стандартная общая товарная группа<br />-   Стандартная учетная товарная группа<br />-   Стандартная НДС товарная группа<br />-   Стандартный метод учета себестоимости|  
|**Код Товарной Группы**|Введите код товарной группы, указывающий тип товара, к которому принадлежит товар (например, краска, инструменты, батареи).|  
|**Фильтр глобального измерения 1**|Введите значение фильтра для анализа в фильтре "Глобал. Измерение 1".|  
|**Фильтр глобального измерения 2**|Введите значение фильтра для анализа в фильтре "Глобал. Измерение 2".|  
|**«Фильтр по дате»**|Введите период, для которого печатается отчет. Данное поле является обязательным.|  

На экспресс-вкладке **Параметры** можно указать параметры форматирования, перечисленные в следующей таблице.  

|Параметр|Описанием|  
|---|---|
|**Точность округления**|Выберите необходимую точность округления:<br /><br /> 0,001, 0,01, 1 или 1000.|  
|**Заменять нулевые значения на пропуски**|Установите этот флажок, чтобы заменять нулевые значения на пустые места.|  
|**Пропускать счета без оборотов**|Установите этот флажок, чтобы исключить из отчета счета с нулевым товарооборотом за период.|  
|**Пропускать счета с нулевым конечным сальдо**|Установите этот флажок, чтобы исключить из отчета счета с нулевым конечным сальдо в конце периода.|  
|**Пропускать нулевые строки**|Установите этот флажок, чтобы исключить из отчета строки с нулевым значением.|  
|**Печатать горизонтальную сетку**|Установите этот флажок, чтобы печатать в отчете горизонтальную сетку.|  
|**Единица Измерения**|Выберите единицу измерения для расчета количеств в отчете:<br /><br /> -   **Базовая**: в базовых единицах измерения<br />-   **Продажа**: в единицах измерения для продаж<br />-   **Покупка**: в единицах измерения для покупок|  
|**Печатать Кол-во**|Установите этот флажок, чтобы печатать количество, которое указано в отчете.|  
|**Печать Затраты**|Установите этот флажок, чтобы печатать затраты, которые указаны в отчете.|  
|**Печатать Итоги по Группам**|Установите этот флажок, чтобы печатать предварительные итоги по группам.|  

## <a name="see-also"></a>См. также  
 [Акты обязательств по товару](item-obligatory-acts.md)
