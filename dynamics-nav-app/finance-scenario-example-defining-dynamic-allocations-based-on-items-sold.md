---
title: "Пример сценария. Определение динамических распределений на основе проданных товаров"
description: "В этом разделе приведен пример, как определять распределения с помощью метода динамического распределения. В этом примере изменяется динамическое распределение себестоимости для места возникновения затрат ПРОДАЖИ с целью поддержки нового объекта затрат ИТ-ОБОРУДОВАНИЕ. Пакеты ИТ-ОБОРУДОВАНИЯ имеют номера товаров в диапазоне от 8904-W до 8924-W. Показатели продаж за прошлый год используются для расчета долей. Распределение учитывается по типу затрат 9903."
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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 32310933bb8eb483bd30270802c8943c55423a2f
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="scenario-example-defining-dynamic-allocations-based-on-items-sold"></a><span data-ttu-id="1c619-107">Пример сценария. Определение динамических распределений на основе проданных товаров</span><span class="sxs-lookup"><span data-stu-id="1c619-107">Scenario Example: Defining Dynamic Allocations Based on Items Sold</span></span>
<span data-ttu-id="1c619-108">В этом разделе приведен пример, как определять распределения с помощью метода динамического распределения.</span><span class="sxs-lookup"><span data-stu-id="1c619-108">This topic shows an example of how to define allocations by using the dynamic allocation method.</span></span> <span data-ttu-id="1c619-109">В этом примере изменяется динамическое распределение себестоимости для места возникновения затрат ПРОДАЖИ с целью поддержки нового объекта затрат ИТ-ОБОРУДОВАНИЕ.</span><span class="sxs-lookup"><span data-stu-id="1c619-109">In the example, you change the dynamic allocation of the costs for the SALES cost center to support the new cost object IT EQUIPMENT.</span></span> <span data-ttu-id="1c619-110">Пакеты ИТ-ОБОРУДОВАНИЯ имеют номера товаров в диапазоне от 8904-W до 8924-W.</span><span class="sxs-lookup"><span data-stu-id="1c619-110">IT EQUIPMENT packages have item numbers in the range from 8904-W to 8924-W.</span></span> <span data-ttu-id="1c619-111">Показатели продаж за прошлый год используются для расчета долей.</span><span class="sxs-lookup"><span data-stu-id="1c619-111">You use the previous year’s sales figures to calculate the share.</span></span> <span data-ttu-id="1c619-112">Распределение учитывается по типу затрат 9903.</span><span class="sxs-lookup"><span data-stu-id="1c619-112">The allocation is posted to the helping cost type 9903.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="1c619-113">В примере используются демонстрационные данные в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="1c619-113">The example uses the demo data in the [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

## <a name="to-define-dynamic-allocations-based-on-items-sold-in-the-previous-year"></a><span data-ttu-id="1c619-114">Определение динамических распределений на основе количества проданных товаров в предыдущем году</span><span class="sxs-lookup"><span data-stu-id="1c619-114">To define dynamic allocations based on items sold in the previous year</span></span>  

1.  <span data-ttu-id="1c619-115">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Распределение затрат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="1c619-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cost Allocations**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="1c619-116">В окне **Распределение затрат** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="1c619-116">In the **Cost Allocation** window, choose the **New** action.</span></span>  
3.  <span data-ttu-id="1c619-117">В поле **ИД** нажмите кнопку ВВОД или введите идентификатор.</span><span class="sxs-lookup"><span data-stu-id="1c619-117">In the **ID** field, press Enter or enter an ID.</span></span>  
4.  <span data-ttu-id="1c619-118">В поле **Уровень** введите **1**.</span><span class="sxs-lookup"><span data-stu-id="1c619-118">In the **Level** field, enter **1**.</span></span>  
5.  <span data-ttu-id="1c619-119">В полях **Действительно с** и **Действительно по** введите соответствующие даты.</span><span class="sxs-lookup"><span data-stu-id="1c619-119">In the **Valid From** and **Valid To** fields, enter appropriate dates.</span></span>  
6.  <span data-ttu-id="1c619-120">В поле **Код центра затрат** введите **ПРОДАЖИ**.</span><span class="sxs-lookup"><span data-stu-id="1c619-120">In the **Cost Center Code** field, enter **SALES**.</span></span>  
7.  <span data-ttu-id="1c619-121">В поле **Кредит по типу затрат** введите тип затрат **9903**.</span><span class="sxs-lookup"><span data-stu-id="1c619-121">In the **Credit to Cost Type** field, enter the cost type **9903**.</span></span>  
8.  <span data-ttu-id="1c619-122">В поле **Кредит по типу затрат** введите тип затрат **9903**.</span><span class="sxs-lookup"><span data-stu-id="1c619-122">In the **Target Cost Type** field, enter the cost type **9903**.</span></span>  
9. <span data-ttu-id="1c619-123">В поле **Целевой объект затрат** выберите **Создать**, чтобы создать новый объект затрат "ИТ-ОБОРУДОВАНИЕ" и заполните все нужные поля.</span><span class="sxs-lookup"><span data-stu-id="1c619-123">In the **Target Cost Object** field, choose **New** to create a new cost object IT EQUIPMENT and fill in fields as necessary.</span></span> <span data-ttu-id="1c619-124">Выберите **ИТ-ОБОРУДОВАНИЕ**.</span><span class="sxs-lookup"><span data-stu-id="1c619-124">Select **IT EQUIPMENT**.</span></span> <span data-ttu-id="1c619-125">Оставьте поле **Целевой центр затрат** пустым.</span><span class="sxs-lookup"><span data-stu-id="1c619-125">Leave the **Target Cost Center** field blank.</span></span>  
10. <span data-ttu-id="1c619-126">В поле **Тип назначения распределения** выберите **Все затраты**, чтобы определить способ распределения всех накопленных затрат.</span><span class="sxs-lookup"><span data-stu-id="1c619-126">In the **Allocation Target Type** field, select **All Costs** to define how all accumulated costs are allocated.</span></span>  
11. <span data-ttu-id="1c619-127">В поле **База** выберите базу распределения **Товаров продано (сумма)**.</span><span class="sxs-lookup"><span data-stu-id="1c619-127">In the **Base** field, select the allocation base **Items Sold (Amount)**.</span></span>  
12. <span data-ttu-id="1c619-128">В поле **Фильтр по номеру** введите **8904-W..8924-W**.</span><span class="sxs-lookup"><span data-stu-id="1c619-128">In the **No. Filter** field, enter **8904-W..8924-W**.</span></span>  
13. <span data-ttu-id="1c619-129">В поле **Код фильтра по дате** введите **Прошлый год**.</span><span class="sxs-lookup"><span data-stu-id="1c619-129">In the **Date Filter Code** field, enter **Last Year**.</span></span>  
14. <span data-ttu-id="1c619-130">Для расчета доли выберите действие **Вычислить ключ распределения**.</span><span class="sxs-lookup"><span data-stu-id="1c619-130">Choose the **Calculate Allocation Key** action to calculate the share.</span></span>  

    > [!IMPORTANT]  
    >  [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="1c619-131"> использует показатели продаж предыдущих лет для расчета акции стоимостью 1596,50 рублей со ста процентами для пакетов ИТ-ОБОРУДОВАНИЕ.</span><span class="sxs-lookup"><span data-stu-id="1c619-131"> uses the previous years’ sales figures to calculate a share of 1596.50 LCY with 100 percent for the IT EQUIPMENT packages.</span></span> <span data-ttu-id="1c619-132">Это означает, что все товары, проданные в прошлом году, будут распределены в объект затрат "ИТ-ОБОРУДОВАНИЕ".</span><span class="sxs-lookup"><span data-stu-id="1c619-132">This means that all of the items sold last year will be allocated to the cost object IT EQUIPMENT.</span></span>  

## <a name="see-also"></a><span data-ttu-id="1c619-133">См. также</span><span class="sxs-lookup"><span data-stu-id="1c619-133">See Also</span></span>  
 <span data-ttu-id="1c619-134">[Настройка фильтров для базы динамического распределения](finance-setting-filters-for-dynamic-allocation-bases.md) </span><span class="sxs-lookup"><span data-stu-id="1c619-134">[Setting Filters for Dynamic Allocation Bases](finance-setting-filters-for-dynamic-allocation-bases.md) </span></span>  
 <span data-ttu-id="1c619-135">[Практическое руководство. Настройка источника и целей распределения](finance-how-to-set-up-allocation-source-and-targets.md) </span><span class="sxs-lookup"><span data-stu-id="1c619-135">[How to: Set Up Allocation Source and Targets](finance-how-to-set-up-allocation-source-and-targets.md) </span></span>  
 <span data-ttu-id="1c619-136">[Определение и распределение затрат](finance-define-and-allocate-costs.md) </span><span class="sxs-lookup"><span data-stu-id="1c619-136">[Defining and Allocating Costs](finance-define-and-allocate-costs.md) </span></span>  
 <span data-ttu-id="1c619-137">[Терминология в учете затрат](finance-terminology-in-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="1c619-137">[Terminology in Cost Accounting](finance-terminology-in-cost-accounting.md) </span></span>  
 [<span data-ttu-id="1c619-138">Об учете затрат</span><span class="sxs-lookup"><span data-stu-id="1c619-138">About Cost Accounting</span></span>](finance-about-cost-accounting.md)

