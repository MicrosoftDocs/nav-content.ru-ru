---
title: "Анализ фактических сумм в сравнении с суммами бюджета"
description: "Далее описывается порядок анализа фактических сумм в с равнении с суммами бюджета."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bi, power BI, analysis, KPI
ms.date: 06/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: da2cdce3ada29fff98ceb875414f750a8af51855
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-analyze-actual-amounts-versus-budgeted-amounts"></a><span data-ttu-id="0093f-103">Практическое руководство. Анализ фактических сумм в с равнении с суммами бюджета</span><span class="sxs-lookup"><span data-stu-id="0093f-103">How to: Analyze Actual Amounts Versus Budgeted Amounts</span></span>
<span data-ttu-id="0093f-104">В процессе сбора, анализа и предоставления доступа к данным своей организации вы просматриваете фактические суммы в сравнении с суммами бюджета для всех счетов и для различных периодов.</span><span class="sxs-lookup"><span data-stu-id="0093f-104">As a part of gathering, analyzing, and sharing your company data, you view actual amounts compared to budgeted amounts for all accounts and for several periods.</span></span>

<span data-ttu-id="0093f-105">Чтобы проанализировать суммы бюджетов, сначала нужно создать бюджеты.</span><span class="sxs-lookup"><span data-stu-id="0093f-105">To analyze budgeted amounts, you must first create budgets.</span></span> <span data-ttu-id="0093f-106">Дополнительные сведения см. в разделе [Практическое руководство. Создание бюджетов](finance-how-create-budgets.md).</span><span class="sxs-lookup"><span data-stu-id="0093f-106">For more information, see [How to: Create Budgets](finance-how-create-budgets.md).</span></span>

## <a name="to-view-a-budget"></a><span data-ttu-id="0093f-107">Просмотр бюджета</span><span class="sxs-lookup"><span data-stu-id="0093f-107">To view a budget</span></span>
<span data-ttu-id="0093f-108">Для бюджета с измерениями операции можно фильтровать и просматривать конкретные бюджеты.</span><span class="sxs-lookup"><span data-stu-id="0093f-108">In a budget with dimensions, you can filter the entries and see specific budgets.</span></span>

1. <span data-ttu-id="0093f-109">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Бюджеты ГК**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="0093f-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **G/L Budgets**, and then choose the related link.</span></span>
2. <span data-ttu-id="0093f-110">В окне **Бюджеты ГК** откройте бюджет, который требуется посмотреть.</span><span class="sxs-lookup"><span data-stu-id="0093f-110">In the **G/L Budgets** window, open the budget that you want to view.</span></span>  
3. <span data-ttu-id="0093f-111">В верхней части окна заполните поля соответствующим образом, чтобы определить, что в нем отображается.</span><span class="sxs-lookup"><span data-stu-id="0093f-111">At the top of the window, fill in the fields as necessary to define what is shown.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   <span data-ttu-id="0093f-112">Если выбрано значение **Период** в поле **Показывать в строках** или **Показывать в столбцах**, необходимо заполнить поле **Просмотр по**.</span><span class="sxs-lookup"><span data-stu-id="0093f-112">If you have selected **Period** in either the **Show as Lines** or the **Show as Columns** field, then you must fill in the **View by** field.</span></span> <span data-ttu-id="0093f-113">Если значение **Период** в полях **Показывать в строках** или **Показывать в столбцах** не выбрано, тогда необходимо ввести соответствующий период в поле **Фильтр по дате**.</span><span class="sxs-lookup"><span data-stu-id="0093f-113">If you have not selected **Period** in either the **Show as Lines** or **Show as Columns** field, then enter the appropriate period in **Date Filter** field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="0093f-114">В расчет будут включены только те операции бюджета Главной книги, для которых на экспресс-вкладке **Фильтры** были указаны коды фильтра.</span><span class="sxs-lookup"><span data-stu-id="0093f-114">Only entries from the general ledger budget with the filter codes that you enter on the **Filters** FastTab are included in the calculation.</span></span> <span data-ttu-id="0093f-115">Операции бюджетирования с другими кодами фильтра либо без них включаться в расчет не будут.</span><span class="sxs-lookup"><span data-stu-id="0093f-115">Budget entries with other filter codes or without any filter codes are not included.</span></span> <span data-ttu-id="0093f-116">Пока в окне стоит фильтр, бюджет отражает только операции с кодами фильтра.</span><span class="sxs-lookup"><span data-stu-id="0093f-116">As long as the filter remains on the window, the budget only displays the budget entries with these filter codes.</span></span>  

> [!TIP]  
>   <span data-ttu-id="0093f-117">Если требуется изменить бюджет, можно изменить операции бюджетирования.</span><span class="sxs-lookup"><span data-stu-id="0093f-117">If you want to modify the budget, you can modify the budget entries.</span></span> <span data-ttu-id="0093f-118">Выберите сумму для просмотра базовых операций бюджета Главной книги.</span><span class="sxs-lookup"><span data-stu-id="0093f-118">Choose an amount to view the underlying general ledger budget entries.</span></span>

## <a name="to-view-actual-and-budgeted-amounts-for-all-accounts"></a><span data-ttu-id="0093f-119">Просмотр фактических сумм и сумм бюджета по всем счетам</span><span class="sxs-lookup"><span data-stu-id="0093f-119">To view actual and budgeted amounts for all accounts</span></span>  
<span data-ttu-id="0093f-120">Бюджеты главной книги и их сравнение с фактическими цифрами можно просмотреть в разных областях [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="0093f-120">You can view general ledger budgets and compare them with actual figures in several areas of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

1. <span data-ttu-id="0093f-121">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **План счетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="0093f-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0093f-122">В окне **План счетов** выберите действие **Сальдо/бюджет ГК**.</span><span class="sxs-lookup"><span data-stu-id="0093f-122">In the **Chart of Accounts** window, choose the **G/L Balance/Budget** action.</span></span>
3. <span data-ttu-id="0093f-123">В верхней части окна заполните поля соответствующим образом, чтобы определить, что в нем отображается.</span><span class="sxs-lookup"><span data-stu-id="0093f-123">At the top of the window, fill in the fields as necessary to define what is shown.</span></span>  
4. <span data-ttu-id="0093f-124">Чтобы просмотреть спецификацию, формирующую показанную сумму, выберите поле.</span><span class="sxs-lookup"><span data-stu-id="0093f-124">To see a specification that makes up the amount shown, choose the field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="0093f-125">Фильтры, настроенные в верхней части окна, применяются к операциям главной книги и к бюджетным операциям.</span><span class="sxs-lookup"><span data-stu-id="0093f-125">The filters you set in the window header will be applied to general ledger entries and also budget entries.</span></span>

<span data-ttu-id="0093f-126">В столбцах слева содержится план счетов.</span><span class="sxs-lookup"><span data-stu-id="0093f-126">The leftmost columns contain the chart of accounts.</span></span> <span data-ttu-id="0093f-127">Из пяти столбцов в крайней справа части, первые четыре показывают для каждого счета фактические и бюджетные суммы по дебету и по кредиту.</span><span class="sxs-lookup"><span data-stu-id="0093f-127">Of the five columns on the rightmost side, the first four columns show actual and budgeted debit and credit amounts for each account.</span></span> <span data-ttu-id="0093f-128">В пятом столбце показано соотношение между фактическими и бюджетными суммами для счета главной книги.</span><span class="sxs-lookup"><span data-stu-id="0093f-128">The fifth column shows the proportional relationship between the actual and the budgeted amounts on the general ledger account.</span></span>  

> [!TIP]  
>   <span data-ttu-id="0093f-129">Используйте поле **Просмотр как** в окне **Сальдо/бюджет ГК** для выбора продолжительности периода.</span><span class="sxs-lookup"><span data-stu-id="0093f-129">Use the **View by** field in the **G/L Balance/Budget** window to select the period length.</span></span> <span data-ttu-id="0093f-130">Используйте поле **Просмотр как** для выбора способа подсчета сумм: **Оборот** или **Сальдо на дату**.</span><span class="sxs-lookup"><span data-stu-id="0093f-130">Use the **View as** field to select the way the amounts will be calculated, **Net Change** or **Balance at Date**.</span></span> <span data-ttu-id="0093f-131">Выберите действие **Предыдущий период** или **Следующий период**, чтобы изменить период.</span><span class="sxs-lookup"><span data-stu-id="0093f-131">Choose the **Previous Period** or **Next Period** action to change the period.</span></span>  

## <a name="to-view-actual-and-budgeted-amounts-for-several-periods"></a><span data-ttu-id="0093f-132">Просмотр фактических сумм и сумм бюджета по нескольким периодам</span><span class="sxs-lookup"><span data-stu-id="0093f-132">To view actual and budgeted amounts for several periods</span></span>  
<span data-ttu-id="0093f-133">Вместо просмотра фактических и бюджетных сумм по всем счетам в рамках одного периода, можно просмотреть данные по одному счету для нескольких периодов.</span><span class="sxs-lookup"><span data-stu-id="0093f-133">Instead of viewing the actual and budgeted amounts for all accounts within a single period, you can view a number of periods for a single account.</span></span>  

1. <span data-ttu-id="0093f-134">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **План счетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="0093f-134">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0093f-135">В окне **План счетов**, выберите соответствующий счет главной книги, а затем действие **Сальдо/бюджет по счету ГК**.</span><span class="sxs-lookup"><span data-stu-id="0093f-135">In the **Chart of Accounts** window, select the relevant general ledger account, and then choose the **G/L Account Balance/Budget** action.</span></span>  
3. <span data-ttu-id="0093f-136">В верхней части окна заполните поля соответствующим образом, чтобы определить, что в нем отображается.</span><span class="sxs-lookup"><span data-stu-id="0093f-136">At the top of the window, fill in the fields as necessary to define what is shown.</span></span>   
4. <span data-ttu-id="0093f-137">Чтобы просмотреть спецификацию показанной суммы, выберите поле.</span><span class="sxs-lookup"><span data-stu-id="0093f-137">To see a specification of an amount shown, choose the field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="0093f-138">См. также</span><span class="sxs-lookup"><span data-stu-id="0093f-138">See Also</span></span>
<span data-ttu-id="0093f-139">[Бизнес-аналитика](bi.md)
[Практическое руководство. Работа с финансовыми отчетами](bi-how-work-account-schedule.md)</span><span class="sxs-lookup"><span data-stu-id="0093f-139">[Business Intelligence](bi.md)
[How to: Work with Account Schedules](bi-how-work-account-schedule.md)</span></span>  
[<span data-ttu-id="0093f-140">Финансы</span><span class="sxs-lookup"><span data-stu-id="0093f-140">Finance</span></span>](finance.md)  
[<span data-ttu-id="0093f-141">Настройка финансов</span><span class="sxs-lookup"><span data-stu-id="0093f-141">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="0093f-142">Главная книга и план счетов</span><span class="sxs-lookup"><span data-stu-id="0093f-142">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
<span data-ttu-id="0093f-143">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="0093f-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

