---
title: "Определение и распределение затрат"
description: "Распределения затрат перемещают затраты и доходы между типами затрат, местами возникновения затрат и объектами затрат. Можно определить любое необходимое число распределений."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f7c34e8f4c57e2effc03b8dcd2a722d7bdbb4692
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="defining-and-allocating-costs"></a><span data-ttu-id="39854-104">Определение и распределение затрат</span><span class="sxs-lookup"><span data-stu-id="39854-104">Defining and Allocating Costs</span></span>
<span data-ttu-id="39854-105">Распределения затрат перемещают затраты и доходы между типами затрат, местами возникновения затрат и объектами затрат.</span><span class="sxs-lookup"><span data-stu-id="39854-105">Cost allocations move costs and revenues between cost types, cost centers, and cost objects.</span></span> <span data-ttu-id="39854-106">Можно определить любое необходимое число распределений.</span><span class="sxs-lookup"><span data-stu-id="39854-106">You can define as many allocations as you need.</span></span> <span data-ttu-id="39854-107">Каждое распределение состоит из:</span><span class="sxs-lookup"><span data-stu-id="39854-107">Each allocation consists of:</span></span>  

-   <span data-ttu-id="39854-108">Источник распределения.</span><span class="sxs-lookup"><span data-stu-id="39854-108">An allocation source.</span></span>  
-   <span data-ttu-id="39854-109">Одно или несколько назначений распределения.</span><span class="sxs-lookup"><span data-stu-id="39854-109">One or more allocation targets.</span></span>  

<span data-ttu-id="39854-110">Источник распределения задает затраты, которые должны быть распределены, а цели распределения определяют, куда затраты должны быть распределены.</span><span class="sxs-lookup"><span data-stu-id="39854-110">The allocation source establishes which costs must be allocated, and the allocation targets determine where the costs must be allocated.</span></span> <span data-ttu-id="39854-111">Например, источником распределения затрат могут быть расходы за электричество и отопление.</span><span class="sxs-lookup"><span data-stu-id="39854-111">For example, an allocation source can be the costs for the Electricity and Heating cost type.</span></span> <span data-ttu-id="39854-112">Вы назначаете все расходы на электричество и отопление трем местам возникновения затрат: мастерской, производству и продажам.</span><span class="sxs-lookup"><span data-stu-id="39854-112">You allocate all electricity and heating costs to three cost centers: Workshop, Production, and Sales.</span></span> <span data-ttu-id="39854-113">Эти места возникновения затрат являются целями распределения.</span><span class="sxs-lookup"><span data-stu-id="39854-113">These cost centers are your allocation targets.</span></span>  

<span data-ttu-id="39854-114">Для каждого источника распределения указываются уровень распределения, период действия и вариант в качестве идентификатора группировки.</span><span class="sxs-lookup"><span data-stu-id="39854-114">For each allocation source, you define an allocation level, a validity period, and a variant as grouping identifier.</span></span> <span data-ttu-id="39854-115">Можно использовать пакетное задание для установки фильтров и выбора определений распределения и последующего автоматического распределения затрат.</span><span class="sxs-lookup"><span data-stu-id="39854-115">You can use a batch job to set filters to select allocation definitions and then run cost allocations automatically.</span></span>  

<span data-ttu-id="39854-116">Для каждой цели распределения определяется база распределения.</span><span class="sxs-lookup"><span data-stu-id="39854-116">For each allocation target, you define an allocation base.</span></span> <span data-ttu-id="39854-117">База распределения может быть статической или динамической.</span><span class="sxs-lookup"><span data-stu-id="39854-117">The allocation base can be either static or dynamic.</span></span>  

-   <span data-ttu-id="39854-118">Статическое распределение основано на конкретном значении, таком как площадь в квадратных метрах или заданное соотношение распределения (например, 5:2: 4).</span><span class="sxs-lookup"><span data-stu-id="39854-118">Static allocation bases are based on a definite value, such as square footage or an established allocation ratio, such as 5:2:4.</span></span>  
-   <span data-ttu-id="39854-119">Базы динамического распределения зависят от изменяемых значений, таких как количество сотрудников в месте возникновения затрат или доход от продажи объекта затрат за определенный период времени.</span><span class="sxs-lookup"><span data-stu-id="39854-119">Dynamic allocation bases depend on changeable values, such as the number of employees in a cost center or sales revenue of a cost object throughout a certain time period.</span></span>  

<span data-ttu-id="39854-120">В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.</span><span class="sxs-lookup"><span data-stu-id="39854-120">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="39854-121">По</span><span class="sxs-lookup"><span data-stu-id="39854-121">To</span></span>|<span data-ttu-id="39854-122">Ссылка</span><span class="sxs-lookup"><span data-stu-id="39854-122">See</span></span>|  
|--------|---------|  
|<span data-ttu-id="39854-123">Настройте источник распределения и его целевые объекты.</span><span class="sxs-lookup"><span data-stu-id="39854-123">Set up allocation source and its targets.</span></span>|[<span data-ttu-id="39854-124">Практическое руководство. Настройка источника и целей распределения</span><span class="sxs-lookup"><span data-stu-id="39854-124">How to: Set Up Allocation Source and Targets</span></span>](finance-how-to-set-up-allocation-source-and-targets.md)|  
|<span data-ttu-id="39854-125">Настройте различные фильтры для базы динамического распределения.</span><span class="sxs-lookup"><span data-stu-id="39854-125">Set up various filters for dynamic allocation bases.</span></span>|[<span data-ttu-id="39854-126">Настройка фильтров для базы динамического распределения</span><span class="sxs-lookup"><span data-stu-id="39854-126">Setting Filters for Dynamic Allocation Bases</span></span>](finance-setting-filters-for-dynamic-allocation-bases.md)|  
|<span data-ttu-id="39854-127">См. пример того, как определять статическое распределение.</span><span class="sxs-lookup"><span data-stu-id="39854-127">See an example of how to define a static allocation.</span></span>|[<span data-ttu-id="39854-128">Пример сценария. Определение статических распределений на основе отношения распределений</span><span class="sxs-lookup"><span data-stu-id="39854-128">Scenario Example: Defining Static Allocations Based on Allocation Ratio</span></span>](finance-scenario-example-defining-static-allocations-based-on-allocation-ratio.md)|  
|<span data-ttu-id="39854-129">См. пример того, как определять динамическое распределение.</span><span class="sxs-lookup"><span data-stu-id="39854-129">See an example of how to define a dynamic allocation.</span></span>|[<span data-ttu-id="39854-130">Пример сценария. Определение динамических распределений на основе проданных товаров</span><span class="sxs-lookup"><span data-stu-id="39854-130">Scenario Example: Defining Dynamic Allocations Based on Items Sold</span></span>](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md)|  

## <a name="see-also"></a><span data-ttu-id="39854-131">См. также</span><span class="sxs-lookup"><span data-stu-id="39854-131">See Also</span></span>  
 <span data-ttu-id="39854-132">[Настройка учета затрат](finance-set-up-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="39854-132">[Setting Up Cost Accounting](finance-set-up-cost-accounting.md) </span></span>  
 <span data-ttu-id="39854-133">[Перемещение и операции учета затрат](finance-transfer-and-post-cost-entries.md) </span><span class="sxs-lookup"><span data-stu-id="39854-133">[Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md) </span></span>  
 <span data-ttu-id="39854-134">[Учет по затратам](finance-manage-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="39854-134">[Accounting for Costs](finance-manage-cost-accounting.md) </span></span>  
 <span data-ttu-id="39854-135">[Терминология в учете затрат](finance-terminology-in-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="39854-135">[Terminology in Cost Accounting](finance-terminology-in-cost-accounting.md) </span></span>  
 [<span data-ttu-id="39854-136">Об учете затрат</span><span class="sxs-lookup"><span data-stu-id="39854-136">About Cost Accounting</span></span>](finance-about-cost-accounting.md)

