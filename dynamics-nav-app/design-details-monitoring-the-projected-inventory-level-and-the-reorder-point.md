---
title: "Сведения о проектировании — отслеживание уровня прогнозируемых запасов и точки дозаказа"
description: "Узнайте, как при планирование запасов различаются уровень прогнозируемых запасов и уровень прогнозируемых доступных запасов."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, supply, inventory, planning
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ef99b84a635a8403c62c38b8a66e77166bbf2883
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-monitoring-the-projected-inventory-level-and-the-reorder-point"></a><span data-ttu-id="f10c4-103">Сведения о проектировании: отслеживание уровня прогнозируемых запасов и точки дозаказа</span><span class="sxs-lookup"><span data-stu-id="f10c4-103">Design Details: Monitoring the Projected Inventory Level and the Reorder Point</span></span>
<span data-ttu-id="f10c4-104">Запасы — это тип поставки, но для планирования запасов система планирования разделяет два уровня запасов:</span><span class="sxs-lookup"><span data-stu-id="f10c4-104">Inventory is a type of supply, but for inventory planning, the planning system distinguishes between two inventory levels:</span></span>  

* <span data-ttu-id="f10c4-105">Прогнозируемые запасы</span><span class="sxs-lookup"><span data-stu-id="f10c4-105">Projected inventory</span></span>  
* <span data-ttu-id="f10c4-106">Прогнозируемые доступные запасы</span><span class="sxs-lookup"><span data-stu-id="f10c4-106">Projected available inventory</span></span>  

## <a name="projected-inventory"></a><span data-ttu-id="f10c4-107">Ожидаемые запасы</span><span class="sxs-lookup"><span data-stu-id="f10c4-107">Projected Inventory</span></span>  
<span data-ttu-id="f10c4-108">Изначально в начале процесса планирования прогнозируемые запасы представляют собой количество общих запасов, включая поставку и спрос в прошлом, даже если они не учтены.</span><span class="sxs-lookup"><span data-stu-id="f10c4-108">Initially, projected inventory is the quantity of gross inventory, including supply and demand in the past even if not posted, when starting the planning process.</span></span> <span data-ttu-id="f10c4-109">В будущем это становится изменяющимся прогнозируемым уровнем запасов, который поддерживается общими количествами из будущей поставки и спроса, поскольку они вводятся со временем (независимо от того, зарезервированы они или размещены иным способом).</span><span class="sxs-lookup"><span data-stu-id="f10c4-109">In the future, this becomes a moving projected inventory level that is maintained by gross quantities from future supply and demand because those are introduced along the time line (whether reserved or in other ways allocated).</span></span>  

<span data-ttu-id="f10c4-110">Прогнозируемые запасы используются системой планирования для мониторинга точки повторного запаса и определения количества повторного запаса при использовании политики повторного заказа "Макс. кол-во".</span><span class="sxs-lookup"><span data-stu-id="f10c4-110">The projected inventory is used by the planning system to monitor the reorder point and to determine the reorder quantity when using the Maximum Qty. reordering policy.</span></span>  

## <a name="projected-available-inventory"></a><span data-ttu-id="f10c4-111">Прогнозируемые доступные запасы</span><span class="sxs-lookup"><span data-stu-id="f10c4-111">Projected Available Inventory</span></span>  
<span data-ttu-id="f10c4-112">Прогнозируемые доступные запасы являются частью прогнозируемых запасов, которая на данный момент доступна для удовлетворения спроса.</span><span class="sxs-lookup"><span data-stu-id="f10c4-112">The projected available inventory is the part of the projected inventory that at a given point in time is available to fulfill demand.</span></span> <span data-ttu-id="f10c4-113">Прогнозируемые доступные запасы используются механизмом планирования при мониторинге уровня страхового запаса.</span><span class="sxs-lookup"><span data-stu-id="f10c4-113">The projected available inventory is used by the planning engine when monitoring the safety stock level.</span></span>  

<span data-ttu-id="f10c4-114">Прогнозируемые доступные запасы используются системой планирования для мониторинга уровня страховых запасов, поскольку страховые запасы всегда должны быть доступны для обслуживания неожиданного спроса.</span><span class="sxs-lookup"><span data-stu-id="f10c4-114">The projected available inventory is used by the planning system to monitor the safety stock level, since the safety stock must always be available to serve unexpected demand.</span></span>  

## <a name="time-buckets"></a><span data-ttu-id="f10c4-115">Горизонты планирования</span><span class="sxs-lookup"><span data-stu-id="f10c4-115">Time Buckets</span></span>  
<span data-ttu-id="f10c4-116">Обеспечение жесткого контроля прогнозируемых запасов очень важно для определения того, когда достигается или пересекается точка дозаказа, и для расчета правильного количества заказа при использовании политики дозаказа "Максимальное кол-во".</span><span class="sxs-lookup"><span data-stu-id="f10c4-116">Having a tight control of the projected inventory is crucial to detect when the reorder point is reached or crossed and to calculate the right order quantity when using the Maximum Qty. reordering policy.</span></span>  

<span data-ttu-id="f10c4-117">Как указано ранее, прогнозируемый уровень запасов рассчитывается в начале периода учета.</span><span class="sxs-lookup"><span data-stu-id="f10c4-117">As stated earlier, the projected inventory level is calculated at the start of the planning period.</span></span> <span data-ttu-id="f10c4-118">Это общий уровень, на котором не учитываются резервирования и похожие распределения.</span><span class="sxs-lookup"><span data-stu-id="f10c4-118">It is a gross level that does not consider reservations and similar allocations.</span></span> <span data-ttu-id="f10c4-119">Для мониторинга этого уровня запасов в последовательности планирования система отслеживает совокупные изменения за период времени или горизонт планирования.</span><span class="sxs-lookup"><span data-stu-id="f10c4-119">To monitor this inventory level during the planning sequence, the system monitors the aggregated changes over a period of time, a time bucket.</span></span> <span data-ttu-id="f10c4-120">Система гарантирует, что горизонт планирования равен хотя бы одному дню, поскольку это самая точная единица времени для события спроса или поставки.</span><span class="sxs-lookup"><span data-stu-id="f10c4-120">The system ensures that the time bucket is at least one day since it is the most precise unit of time for a demand or supply event.</span></span>  

## <a name="determining-the-projected-inventory-level"></a><span data-ttu-id="f10c4-121">Определение уровня прогнозируемых запасов</span><span class="sxs-lookup"><span data-stu-id="f10c4-121">Determining the Projected Inventory Level</span></span>  
<span data-ttu-id="f10c4-122">Следующая последовательность описывает определение прогнозируемого уровня запасов.</span><span class="sxs-lookup"><span data-stu-id="f10c4-122">The following sequence describes how the projected inventory level is determined:</span></span>  

* <span data-ttu-id="f10c4-123">Если событие поставки, например заказ на покупку, полностью спланировано, увеличиваются ожидаемые запасы в дату оплаты.</span><span class="sxs-lookup"><span data-stu-id="f10c4-123">When a supply event, such as a purchase order has been totally planned, it will increase the projected inventory on its due date.</span></span>  
* <span data-ttu-id="f10c4-124">Если событие спроса полностью удовлетворено, прогнозируемый расход склада не будет осуществляться сразу же.</span><span class="sxs-lookup"><span data-stu-id="f10c4-124">When a demand event has been fully satisfied, it will not decrease the projected inventory right away.</span></span> <span data-ttu-id="f10c4-125">Вместо этого учитывается напоминание об уменьшении, которое является внутренней записью, содержащей дату и количество вклада в прогнозируемые запасы.</span><span class="sxs-lookup"><span data-stu-id="f10c4-125">Instead, it posts a decrease reminder, which is an internal record that holds the date and quantity of the contribution to the projected inventory.</span></span>  
* <span data-ttu-id="f10c4-126">Если планируется последующее событие поставки и оно размещается на временной шкале, учтенные напоминания о расходе изучаются по одному до планируемой даты поставки. При этом обновляются ожидаемые запасы.</span><span class="sxs-lookup"><span data-stu-id="f10c4-126">When a subsequent supply event is planned and placed on the time line, the posted decrease reminders are investigated one by one up until the planned date of the supply while updating the projected inventory.</span></span> <span data-ttu-id="f10c4-127">Во время данного процесса уровень точки дозаказа внутреннего напоминания об увеличении может быть достигнут или пройден.</span><span class="sxs-lookup"><span data-stu-id="f10c4-127">During this process, the reorder point level of the internal increase reminder may be reached or crossed.</span></span>  
* <span data-ttu-id="f10c4-128">Если введен новый заказ на поставку, система проверяет, был ли он введен до текущей поставки.</span><span class="sxs-lookup"><span data-stu-id="f10c4-128">If a new supply order is introduced, the system checks if it is entered before the current supply.</span></span> <span data-ttu-id="f10c4-129">В этом случае новая поставка становится текущей поставкой, и процедура балансировки начинается снова.</span><span class="sxs-lookup"><span data-stu-id="f10c4-129">If it is, the new supply becomes current supply and the balancing procedure starts over.</span></span>  

<span data-ttu-id="f10c4-130">Далее этот принцип проиллюстрирован графически.</span><span class="sxs-lookup"><span data-stu-id="f10c4-130">The following shows a graphical illustration of this principle:</span></span>  

![](media/nav_app_supply_planning_2_projected_inventory.png "NAV_APP_supply_planning_2_projected_inventory")  

1. <span data-ttu-id="f10c4-131">Поставка **Sa** на 4 штуки (фиксированная) закрывает спрос **Da** на -3 штуки.</span><span class="sxs-lookup"><span data-stu-id="f10c4-131">Supply **Sa** of 4 (fixed) closes Demand **Da** of -3.</span></span>  
2. <span data-ttu-id="f10c4-132">CloseDemand: создается напоминание об уменьшении на -3 (не показано).</span><span class="sxs-lookup"><span data-stu-id="f10c4-132">CloseDemand: Create a decrease reminder of -3 (not shown).</span></span>  
3. <span data-ttu-id="f10c4-133">Поставка **Sa** закрыта с излишком 1 (спрос больше не существует).</span><span class="sxs-lookup"><span data-stu-id="f10c4-133">Supply **Sa** is closed with a surplus of 1 (no more demand exists).</span></span>  

     <span data-ttu-id="f10c4-134">В результате прогнозируемый уровень склада увеличивается до +4, а прогнозируемые **доступные** запасы равны -1.</span><span class="sxs-lookup"><span data-stu-id="f10c4-134">This increases the projected inventory level to +4, while the projected **available** inventory becomes -1.</span></span>  

4. <span data-ttu-id="f10c4-135">Следующая поставка **Sb** на 2 штуки (другой заказ) уже помещена на временную шкалу.</span><span class="sxs-lookup"><span data-stu-id="f10c4-135">The next supply **Sb** of 2 (another order) has already been placed on the timeline.</span></span>  
5. <span data-ttu-id="f10c4-136">Система проверяет, имеется ли напоминание об уменьшении, предшествующее **Sb** (если нет, никакие действия не предпринимаются).</span><span class="sxs-lookup"><span data-stu-id="f10c4-136">System checks if there is any decrease reminder preceding **Sb** (there is not, so no action is taken).</span></span>  
6. <span data-ttu-id="f10c4-137">Система закрывает поставку **Sb** (спрос больше существует) либо A: путем снижения количества до значения 0 (отмена), либо B: оставляя ее как есть.</span><span class="sxs-lookup"><span data-stu-id="f10c4-137">System closes supply **Sb** (no more demand exists)—either A: by reducing it to 0 (cancel) or B: by leaving as is.</span></span>  

     <span data-ttu-id="f10c4-138">Это увеличивает прогнозируемый уровень запаса (A: +0 => +4 or B: +2 = +6).</span><span class="sxs-lookup"><span data-stu-id="f10c4-138">This increases the projected inventory level (A: +0 => +4 or B: +2 = +6).</span></span>  

7. <span data-ttu-id="f10c4-139">Система выполняет окончательную проверку на наличие напоминания об уменьшении.</span><span class="sxs-lookup"><span data-stu-id="f10c4-139">System makes a final check: Is there any decrease reminder?</span></span> <span data-ttu-id="f10c4-140">Да, имеется один в дату **Da**.</span><span class="sxs-lookup"><span data-stu-id="f10c4-140">Yes, there is one on the date of **Da**.</span></span>  
8. <span data-ttu-id="f10c4-141">Система добавляет напоминание об уменьшении, равном -3, к прогнозируемому уровню запасов одним из двух способов: A: +4 -3 = 1 или B: +6 -3 = +3.</span><span class="sxs-lookup"><span data-stu-id="f10c4-141">System adds the decrease reminder of -3 reminder to the projected inventory level, either A: +4 -3 = 1 or B: +6 -3 = +3.</span></span>  
9. <span data-ttu-id="f10c4-142">В случае А система создает заказ с прямым планирование, начиная с даты **Da**.</span><span class="sxs-lookup"><span data-stu-id="f10c4-142">In case of A, the system creates a forward-scheduled order starting on date **Da**.</span></span>  

     <span data-ttu-id="f10c4-143">В случае B достигается точка дозаказа и создается новый заказ.</span><span class="sxs-lookup"><span data-stu-id="f10c4-143">In case of B, the reorder point is reached and a new order is created.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f10c4-144">См. также</span><span class="sxs-lookup"><span data-stu-id="f10c4-144">See Also</span></span>  
<span data-ttu-id="f10c4-145">[Сведения о проектировании: политики дозаказа](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="f10c4-145">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="f10c4-146">[Сведения о проектировании: параметры планирования](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="f10c4-146">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="f10c4-147">[Сведения о проектировании: обработка политик дозаказа](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="f10c4-147">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="f10c4-148">Сведения о проектировании: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="f10c4-148">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)

