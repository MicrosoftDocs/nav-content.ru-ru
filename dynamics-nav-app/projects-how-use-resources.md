---
title: "Регистрация и корректировка потребления ресурсов и цен"
description: "Описывается процедура регистрации потребления ресурсов, связанных с работой, для отслеживания и управления затратами, ценами и типами работ."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, capacity, staff
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3ee2af302aa75f091d85a2667e53d69ea8ed9ea8
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-use-resources-for-jobs"></a><span data-ttu-id="806bb-103">Практическое руководство. Использование ресурсов для работ</span><span class="sxs-lookup"><span data-stu-id="806bb-103">How to: Use Resources for Jobs</span></span>
<span data-ttu-id="806bb-104">Вы регистрируете потребления ресурсов в журнале работ, чтобы отслеживать затраты и цены, а также виды работ, которые связаны с работами.</span><span class="sxs-lookup"><span data-stu-id="806bb-104">You record the usage of resources in the job journal to keep track of costs, prices, and the work types that are linked to jobs.</span></span> <span data-ttu-id="806bb-105">Дополнительные сведения см. в разделе [Практическое руководство. Регистрация использования для работ](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="806bb-105">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

<span data-ttu-id="806bb-106">Использование ресурса также может учитываться в журнале ресурсов.</span><span class="sxs-lookup"><span data-stu-id="806bb-106">You can also post the usage of a resource in a resource journal.</span></span> <span data-ttu-id="806bb-107">Операции, учтенные в журнале ресурсов, не оказывают влияния на Главную книгу.</span><span class="sxs-lookup"><span data-stu-id="806bb-107">Entries posted in a resource journal have no effect on the general ledger.</span></span>

## <a name="to-assign-resources-to-jobs"></a><span data-ttu-id="806bb-108">Назначение ресурсов работам</span><span class="sxs-lookup"><span data-stu-id="806bb-108">To assign resources to jobs</span></span>
<span data-ttu-id="806bb-109">Ресурсы можно назначить работам, создав строки планирования работы для работы.</span><span class="sxs-lookup"><span data-stu-id="806bb-109">You assign resources to jobs by creating job planning lines for the job.</span></span> <span data-ttu-id="806bb-110">Дополнительные сведения см. в разделе [Практическое руководство. Создание работ](projects-how-create-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="806bb-110">For more information, see [How to: Create Jobs](projects-how-create-jobs.md).</span></span>

## <a name="to-record-resource-usage-for-a-job"></a><span data-ttu-id="806bb-111">Регистрация потребления ресурсов для работы</span><span class="sxs-lookup"><span data-stu-id="806bb-111">To record resource usage for a job</span></span>
1. <span data-ttu-id="806bb-112">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы работ**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="806bb-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Job Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="806bb-113">Откройте соответствующий раздел журнала работ, затем заполните поля, как требуется.</span><span class="sxs-lookup"><span data-stu-id="806bb-113">Open a relevant job journal batch, and then fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. <span data-ttu-id="806bb-114">Когда журнал будет готов, выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="806bb-114">When the journal is complete, choose the **Post** action.</span></span>

## <a name="to-adjust-resource-prices"></a><span data-ttu-id="806bb-115">Корректировка цен ресурсов</span><span class="sxs-lookup"><span data-stu-id="806bb-115">To adjust resource prices</span></span>
<span data-ttu-id="806bb-116">Для изменения стоимости или цен большого количества ресурсов рекомендуется воспользоваться пакетным заданием.</span><span class="sxs-lookup"><span data-stu-id="806bb-116">If you want to change costs or prices for a large number of resources, you can use a batch job.</span></span>  

1. <span data-ttu-id="806bb-117">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Коррекция цен/стоимостей ресурсов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="806bb-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Adjust Resource Costs/Prices**, and then choose the related link.</span></span>
2. <span data-ttu-id="806bb-118">Заполните поля в строке, как требуется, и нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="806bb-118">Fill in the fields on a line as necessary, and then choose the **OK** button.</span></span>

> [!NOTE]  
>   <span data-ttu-id="806bb-119">При выполнении этого пакетного задания не добавляются и не корректируются альтернативные стоимости или цены ресурсов.</span><span class="sxs-lookup"><span data-stu-id="806bb-119">This batch job does not create or adjust alternate costs or prices for resources.</span></span> <span data-ttu-id="806bb-120">Это меняет только содержимое поля в карточке ресурса для поля **Коррекция поля**, выбранного в пакетном задании.</span><span class="sxs-lookup"><span data-stu-id="806bb-120">It only changes the contents of the field on the resource card for the **Adjust Field** field that you selected in the batch job.</span></span> <span data-ttu-id="806bb-121">Коррекция вступит в силу сразу для всех ресурсов, поэтому проверьте коэффициенты перед запуском пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="806bb-121">The adjustment will take effect immediately for resources, so check your adjustment factors before you run the batch job.</span></span>

## <a name="to-get-resource-price-change-suggestions-based-on-existing-alternate-prices"></a><span data-ttu-id="806bb-122">Получения предложений по изменению цены ресурса на основе существующих альтернативных цен</span><span class="sxs-lookup"><span data-stu-id="806bb-122">To get resource price change suggestions based on existing alternate prices</span></span>
<span data-ttu-id="806bb-123">Если для некоторых ресурсов уже определены альтернативные цены, можно воспользоваться пакетным заданием для установления нескольких альтернативных цен ресурсов.</span><span class="sxs-lookup"><span data-stu-id="806bb-123">If you have already set up alternate resource price for some resources, you can use a batch job to set up multiple alternate resource prices.</span></span>

1. <span data-ttu-id="806bb-124">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Resource Price Changes**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="806bb-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Resource Price Changes**, and then choose the related link.</span></span>
2. <span data-ttu-id="806bb-125">Выберите действие **Предлож. изменения цен ресурсов (цена)**, затем заполните поля, как требуется.</span><span class="sxs-lookup"><span data-stu-id="806bb-125">Choose the **Suggest Res. Price Chg. (Price)** action, and then fill in the fields as necessary.</span></span>
3. <span data-ttu-id="806bb-126">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="806bb-126">Choose the **OK** button.</span></span>  
4. <span data-ttu-id="806bb-127">После выполнения пакетного задания окно **Изменение цен ресурсов** показывает результаты пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="806bb-127">When the batch job is finished, the **Resource Price Changes** window shows the results of the batch job.</span></span>

## <a name="to-get-resource-price-change-suggestions-based-on-standard-prices"></a><span data-ttu-id="806bb-128">Получение предложений по изменению цены ресурса на основе стандартных цен</span><span class="sxs-lookup"><span data-stu-id="806bb-128">To get resource price change suggestions based on standard prices</span></span>
<span data-ttu-id="806bb-129">Если требуется настроить несколько альтернативных цен ресурсов на основе стандартных цен из карточек ресурсов, можно воспользоваться пакетным заданием.</span><span class="sxs-lookup"><span data-stu-id="806bb-129">If you want to set up multiple alternate resource prices based on the standard prices on the resource cards, you can use a batch job.</span></span>  

1. <span data-ttu-id="806bb-130">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Resource Price Changes**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="806bb-130">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Resource Price Changes**, and then choose the related link.</span></span>
2. <span data-ttu-id="806bb-131">Выберите действие **Предлож. изменение цен ресурсов (рес.)**, затем заполните поля, как требуется.</span><span class="sxs-lookup"><span data-stu-id="806bb-131">Choose the **Suggest Res. Price Chg. (Res.)** action, and then fill in the fields as necessary.</span></span>  
3. <span data-ttu-id="806bb-132">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="806bb-132">Choose the **OK** button.</span></span>  
4. <span data-ttu-id="806bb-133">После выполнения пакетного задания откройте окно **Изменение цен ресурсов** для просмотра результатов пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="806bb-133">When the batch job is finished, open the **Resource Price Changes** window to see the results of the batch job.</span></span>

## <a name="to-get-resource-price-change-suggestions-based-on-alternate-prices"></a><span data-ttu-id="806bb-134">Получение предложений по изменению цены ресурса на основе альтернативных цен</span><span class="sxs-lookup"><span data-stu-id="806bb-134">To get resource price change suggestions based on alternate prices</span></span>
<span data-ttu-id="806bb-135">Если для некоторых ресурсов уже определены альтернативные цены, можно воспользоваться пакетным заданием для установления нескольких альтернативных цен ресурсов.</span><span class="sxs-lookup"><span data-stu-id="806bb-135">If you have already set up alternate resource price for some resources, you can use a batch job to set up multiple alternate resource prices.</span></span>

1. <span data-ttu-id="806bb-136">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Предлож. изменения цен ресурсов (цена)**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="806bb-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Suggest Res. Price Chg. (Price)**, and then choose the related link.</span></span>  
2. <span data-ttu-id="806bb-137">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="806bb-137">Fill in the fields as necessary.</span></span>
3. <span data-ttu-id="806bb-138">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="806bb-138">Choose the **OK** button.</span></span>  
4. <span data-ttu-id="806bb-139">После выполнения пакетного задания откройте окно **Изменение цен ресурсов** для просмотра результатов пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="806bb-139">When the batch job is finished, open the **Resource Price Changes** window to see the results of the batch job.</span></span>

## <a name="see-also"></a><span data-ttu-id="806bb-140">См. также</span><span class="sxs-lookup"><span data-stu-id="806bb-140">See Also</span></span>
[<span data-ttu-id="806bb-141">Управление проектами</span><span class="sxs-lookup"><span data-stu-id="806bb-141">Project Management</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="806bb-142">Финансы</span><span class="sxs-lookup"><span data-stu-id="806bb-142">Finance</span></span>](finance.md)  
<span data-ttu-id="806bb-143">[Покупки](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="806bb-143">[Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="806bb-144">[Продажи](sales-manage-sales.md)   </span><span class="sxs-lookup"><span data-stu-id="806bb-144">[Sales](sales-manage-sales.md)   </span></span>  
<span data-ttu-id="806bb-145">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="806bb-145">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

