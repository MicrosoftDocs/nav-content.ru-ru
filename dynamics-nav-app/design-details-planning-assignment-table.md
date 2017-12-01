---
title: "Сведения о проектировании — таблица \"Назначение произ. плана\""
description: "В этом разделе приведены сведения о том, что происходит при изменении способа планирования товара."
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
ms.openlocfilehash: f55f26556857a51b20ea8ae70070aa70147182fe
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-planning-assignment-table"></a><span data-ttu-id="5931a-103">Сведения о проектировании: таблица "Назначение произ. плана"</span><span class="sxs-lookup"><span data-stu-id="5931a-103">Design Details: Planning Assignment Table</span></span>
<span data-ttu-id="5931a-104">Все товары должны быть запланированы, однако нет необходимости вычислять план для товара, если не было изменений в цепочке спрос-поставка с момента последнего расчета плана.</span><span class="sxs-lookup"><span data-stu-id="5931a-104">All items should be planned for, however, there is no reason to calculate a plan for an item unless there has been a change in the demand or supply pattern since the last time a plan was calculated.</span></span>  
  
<span data-ttu-id="5931a-105">Если пользователь ввел новый или изменил существующий заказ на продажу, есть причина выполнить перерасчет плана.</span><span class="sxs-lookup"><span data-stu-id="5931a-105">If the user has entered a new sales order or changed an existing one, there is reason to recalculate the plan.</span></span> <span data-ttu-id="5931a-106">Другие причины включают изменение в прогнозе или требуемом количестве страхового запаса.</span><span class="sxs-lookup"><span data-stu-id="5931a-106">Other reasons include a change in forecast or the desired safety stock quantity.</span></span> <span data-ttu-id="5931a-107">Изменение спецификации путем добавления или удаления компонента, скорее всего, укажет на изменение, но только для товара компонента.</span><span class="sxs-lookup"><span data-stu-id="5931a-107">Changing a bill of material by adding or removing a component would most likely indicate a change, but for the component item only.</span></span>  
  
<span data-ttu-id="5931a-108">При использовании нескольких складов назначение выполняется на уровне товара для каждой комбинации складов.</span><span class="sxs-lookup"><span data-stu-id="5931a-108">For multiple locations, the assignment takes place at the level of item per location combination.</span></span> <span data-ttu-id="5931a-109">Например, если заказ на продажу создан только на одном складе, программа назначит для планирования товар на данном конкретном складе.</span><span class="sxs-lookup"><span data-stu-id="5931a-109">If, for example, a sales order has been created at only one location, the program will assign the item at that specific location for planning.</span></span>  
  
<span data-ttu-id="5931a-110">Причина выбора товаров для планирования — в производительности системы.</span><span class="sxs-lookup"><span data-stu-id="5931a-110">The reason for selecting items for planning is a matter of system performance.</span></span> <span data-ttu-id="5931a-111">Если цепочка спроса-поставки товара не была изменена, система планирования не предложит никаких действий.</span><span class="sxs-lookup"><span data-stu-id="5931a-111">If no change in an item’s demand-supply pattern has occurred, the planning system will not suggest any actions to be taken.</span></span> <span data-ttu-id="5931a-112">Без назначения планирования системе потребуется выполнять вычисления для всех элементов, чтобы определить, что можно планировать, а что истощит системные ресурсы.</span><span class="sxs-lookup"><span data-stu-id="5931a-112">Without the planning assignment, the system would have to perform the calculations for all items in order to find out what to plan for, and that would drain system resources.</span></span>  
  
<span data-ttu-id="5931a-113">В таблице **Назначение произ. плана** отслеживаются события спроса и поставки и назначаются соответствующие товары для планирования.</span><span class="sxs-lookup"><span data-stu-id="5931a-113">The **Planning Assignment** table monitors demand and supply events and assigns the appropriate items for planning.</span></span> <span data-ttu-id="5931a-114">Осуществляется мониторинг следующих событий.</span><span class="sxs-lookup"><span data-stu-id="5931a-114">The following events are monitored:</span></span>  
  
* <span data-ttu-id="5931a-115">Новый заказ на продажу, прогноз, компонент, заказ на покупку, производственный заказ, заказ на сборку или заказ на перемещение.</span><span class="sxs-lookup"><span data-stu-id="5931a-115">A new sales order, forecast, component, purchase order, production order, assembly order, or transfer order.</span></span>  
* <span data-ttu-id="5931a-116">Изменение товара, количества, склада, варианта или даты в заказе на продажу, прогнозе, компоненте, заказе на покупку, производственном заказе, заказе на сборку или заказе на перемещение.</span><span class="sxs-lookup"><span data-stu-id="5931a-116">Change of item, quantity, location, variant, or date on a sales order, forecast, component, purchase order, production order, assembly order, or transfer order.</span></span>  
* <span data-ttu-id="5931a-117">Отмена заказа на продажу, прогноза, компонента, заказа на покупку, производственного заказа, заказа на сборку или заказа на перемещение.</span><span class="sxs-lookup"><span data-stu-id="5931a-117">Cancellation of a sales order, forecast, component, purchase order, production order, assembly order, or transfer order.</span></span>  
* <span data-ttu-id="5931a-118">Потребление товаров, отличное от запланированного.</span><span class="sxs-lookup"><span data-stu-id="5931a-118">Consumption of items other than planned.</span></span>  
* <span data-ttu-id="5931a-119">Выход товаров, отличный от запланированного.</span><span class="sxs-lookup"><span data-stu-id="5931a-119">Output of items other than planned.</span></span>  
* <span data-ttu-id="5931a-120">Незапланированные изменения запасов.</span><span class="sxs-lookup"><span data-stu-id="5931a-120">Unplanned changes in inventory.</span></span>  
  
<span data-ttu-id="5931a-121">Для этих прямых смещений поставки и спроса система трассировки заказов и отправки сообщений о действиях ведет таблицу "Назначение произ. плана" и указывает причину планирования в виде сообщения о действии.</span><span class="sxs-lookup"><span data-stu-id="5931a-121">For these direct supply-demand displacements, the order tracking and action messaging system maintains the Planning Assignment table and states a planning reason as an action message.</span></span>  
  
<span data-ttu-id="5931a-122">Следующие изменения основных данных также вызывают дисбаланс планирования.</span><span class="sxs-lookup"><span data-stu-id="5931a-122">The following changes in master data can also cause a planning imbalance:</span></span>  
  
* <span data-ttu-id="5931a-123">Изменение статуса на "Сертифицировано" в заголовке производственной спецификации (для всех товаров с этим заголовком).</span><span class="sxs-lookup"><span data-stu-id="5931a-123">Change of status to Certified in the production BOM header (for all items using that header).</span></span>  
* <span data-ttu-id="5931a-124">Удаленная строка (дочерний элемент).</span><span class="sxs-lookup"><span data-stu-id="5931a-124">Deleted line (child item).</span></span>  
* <span data-ttu-id="5931a-125">Изменение статуса на "Сертифицировано" в заголовке маршрута (для всех товаров с этим маршрутом).</span><span class="sxs-lookup"><span data-stu-id="5931a-125">Change of status to Certified in the routing header (for all items using that routing).</span></span>  
* <span data-ttu-id="5931a-126">Изменения в следующих полях карточки товара.</span><span class="sxs-lookup"><span data-stu-id="5931a-126">Changes in the following item card fields.</span></span>  
* <span data-ttu-id="5931a-127">Количество страхового запаса или страховое время подготовки.</span><span class="sxs-lookup"><span data-stu-id="5931a-127">Safety Stock Quantity or Safety Lead Time.</span></span>  
* <span data-ttu-id="5931a-128">Рассчитанное время подготовки заказа.</span><span class="sxs-lookup"><span data-stu-id="5931a-128">Lead Time Calculation.</span></span>  
* <span data-ttu-id="5931a-129">Точка дозаказа.</span><span class="sxs-lookup"><span data-stu-id="5931a-129">Reorder Point.</span></span>  
* <span data-ttu-id="5931a-130">Номер производственной спецификации (и все дочерние объекты старой ссылки спецификации).</span><span class="sxs-lookup"><span data-stu-id="5931a-130">Production BOM No. (and all children of old BOM reference).</span></span>  
* <span data-ttu-id="5931a-131">Номер маршрута</span><span class="sxs-lookup"><span data-stu-id="5931a-131">Routing No.</span></span>  
* <span data-ttu-id="5931a-132">Политика дозаказа.</span><span class="sxs-lookup"><span data-stu-id="5931a-132">Reordering Policy.</span></span>  
  
<span data-ttu-id="5931a-133">В таких случаях новая функция управления назначением производственного плана поддерживает таблицу и указывает в качестве причины планирования значение "Оборот".</span><span class="sxs-lookup"><span data-stu-id="5931a-133">In these cases, a new function, Planning Assignment Management, maintains the table and states the planning reason as Net Change.</span></span>  
  
<span data-ttu-id="5931a-134">Следующие изменения не вызывают назначения производственного плана:</span><span class="sxs-lookup"><span data-stu-id="5931a-134">The following changes do not cause a planning assignment:</span></span>  
  
* <span data-ttu-id="5931a-135">Календари</span><span class="sxs-lookup"><span data-stu-id="5931a-135">Calendars</span></span>  
* <span data-ttu-id="5931a-136">Другие параметры планирования в карточке товаров</span><span class="sxs-lookup"><span data-stu-id="5931a-136">Other planning parameters on the item card</span></span>  
  
<span data-ttu-id="5931a-137">При вычислении MPS или MRP действуют следующие ограничения.</span><span class="sxs-lookup"><span data-stu-id="5931a-137">When calculating an MPS or an MRP, the following restrictions apply:</span></span>  
  
* <span data-ttu-id="5931a-138">MPS. Система планирования проверяет, что товар включает производственный прогноз или заказ на продажу.</span><span class="sxs-lookup"><span data-stu-id="5931a-138">MPS: The planning system checks that the item carries a production forecast or a sales order.</span></span> <span data-ttu-id="5931a-139">В противном случае товар не включается в план.</span><span class="sxs-lookup"><span data-stu-id="5931a-139">If not, the item is not included in the plan.</span></span>  
* <span data-ttu-id="5931a-140">MRP. Если система планирования обнаруживает, что товар пополняется из строки планирования MPS или заказа на поставку MPS, товар будет исключен из планирования.</span><span class="sxs-lookup"><span data-stu-id="5931a-140">MRP: If the planning system detects that the item is being replenished by an MPS planning line or MPS supply order, the item will be left out of the planning.</span></span> <span data-ttu-id="5931a-141">Однако включается любой спрос из соответствующих компонентов.</span><span class="sxs-lookup"><span data-stu-id="5931a-141">However, any demand from relevant components is included.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="5931a-142">См. также</span><span class="sxs-lookup"><span data-stu-id="5931a-142">See Also</span></span>  
<span data-ttu-id="5931a-143">[Сведения о проектировании: балансировка спроса и поставки](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="5931a-143">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
<span data-ttu-id="5931a-144">[Сведения о проектировании: обработка политик дозаказа](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="5931a-144">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
<span data-ttu-id="5931a-145">[Сведения о проектировании: перемещения при планировании](design-details-transfers-in-planning.md) </span><span class="sxs-lookup"><span data-stu-id="5931a-145">[Design Details: Transfers in Planning](design-details-transfers-in-planning.md) </span></span>  
[<span data-ttu-id="5931a-146">Сведения о проектировании: параметры планирования</span><span class="sxs-lookup"><span data-stu-id="5931a-146">Design Details: Planning Parameters</span></span>](design-details-planning-parameters.md)  

