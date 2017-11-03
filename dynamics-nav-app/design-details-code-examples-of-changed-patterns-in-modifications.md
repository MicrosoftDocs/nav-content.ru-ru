---
title: "Сведения о проектировании — закрытие спроса и поставки"
description: "Если процедуры балансировки поставки выполнены, возможны три конечных ситуации."
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
ms.openlocfilehash: 337fdb4c625e17e72f4adb692cbf0f2729ae96b7
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="design-details-closing-demand-and-supply"></a><span data-ttu-id="1679a-103">Сведения о проектировании: закрытие спроса и поставки</span><span class="sxs-lookup"><span data-stu-id="1679a-103">Design Details: Closing Demand and Supply</span></span>
<span data-ttu-id="1679a-104">Если процедуры балансировки поставки выполнены, возможны три конечных ситуации.</span><span class="sxs-lookup"><span data-stu-id="1679a-104">When the supply balancing procedures have been performed, there are three possible end situations:</span></span>  

-   <span data-ttu-id="1679a-105">Требуемое количество и дата событий спроса удовлетворены, их планирование можно закрывать.</span><span class="sxs-lookup"><span data-stu-id="1679a-105">The required quantity and date of the demand events have been met and the planning for them can be closed.</span></span> <span data-ttu-id="1679a-106">Событие поставки все еще открыто и, возможно, сможет охватить следующий спрос, чтобы процедуру уравновешивания можно было заново начать с текущего события поставки и следующего спроса.</span><span class="sxs-lookup"><span data-stu-id="1679a-106">The supply event is still open and may be able to cover the next demand, so the balancing procedure can start over with the current supply event and the next demand.</span></span>  

-   <span data-ttu-id="1679a-107">Заказ на поставку невозможно изменить, чтобы покрыть весь спрос.</span><span class="sxs-lookup"><span data-stu-id="1679a-107">The supply order cannot be modified to cover all of the demand.</span></span> <span data-ttu-id="1679a-108">Событие спроса все еще открыто, некоторое неохваченное количество которого может быть покрыто следующим событием предложения.</span><span class="sxs-lookup"><span data-stu-id="1679a-108">The demand event is still open, with some uncovered quantity that may be covered by the next supply event.</span></span> <span data-ttu-id="1679a-109">Таким образом, текущее событие поставки закрыто, поэтому действие балансировки можно начинать с текущего события спроса и следующего события поставки.</span><span class="sxs-lookup"><span data-stu-id="1679a-109">Thus the current supply event is closed, so the balancing act can start over with the current demand and the next supply event.</span></span>  

-   <span data-ttu-id="1679a-110">Весь спрос удовлетворен, последующего спроса нет (либо спрос отсутствовал вовсе).</span><span class="sxs-lookup"><span data-stu-id="1679a-110">All of the demand has been covered; there is no subsequent demand (or there has been no demand at all).</span></span> <span data-ttu-id="1679a-111">Если существует излишняя поставка, можно уменьшить (или отменить) ее количество, а затем закрыть поставку.</span><span class="sxs-lookup"><span data-stu-id="1679a-111">If there is any surplus supply, it may be decreased (or canceled) and then closed.</span></span> <span data-ttu-id="1679a-112">Возможно, дополнительные события поставки будут существовать далее в цепочке, поэтому их также требуется отменить.</span><span class="sxs-lookup"><span data-stu-id="1679a-112">It is possible that additional supply events exist further along in the chain, and they should also be canceled.</span></span>  

 <span data-ttu-id="1679a-113">Наконец, система планирования создаст связь трассировки заказа между поставкой и спросом.</span><span class="sxs-lookup"><span data-stu-id="1679a-113">Last, the planning system will create an order tracking link between the supply and the demand.</span></span>  

## <a name="creating-the-planning-line-suggested-action"></a><span data-ttu-id="1679a-114">Создание строки планирования (предлагаемое действие)</span><span class="sxs-lookup"><span data-stu-id="1679a-114">Creating the Planning Line (Suggested Action)</span></span>  
 <span data-ttu-id="1679a-115">Если предлагается любое действие ("Создание", "Изменение кол-ва", "Перепланирование", "Перепланирование и изменение кол-ва" или "Отмена") для изменения заказа на поставку, система планирования создает строку планирования в журнале планирования.</span><span class="sxs-lookup"><span data-stu-id="1679a-115">If any action – New, Change Quantity, Reschedule, Reschedule and Change Quantity, or Cancel – is suggested to revise the supply order, the planning system creates a planning line in the planning worksheet.</span></span> <span data-ttu-id="1679a-116">Из-за планирования заказа строка планирования создается не только когда закрывается событие поставки, но и когда закрывается событие спроса, даже если событие поставки еще открыто и в него могут вноситься изменения при обработке следующего события спроса.</span><span class="sxs-lookup"><span data-stu-id="1679a-116">Due to order tracking, the planning line is created not only when the supply event is closed, but also if the demand event is closed, even though the supply event is still open and may be subject to additional changes when the next demand event is processed.</span></span> <span data-ttu-id="1679a-117">Это означает, что при создании впервые строка планирования снова может быть изменена.</span><span class="sxs-lookup"><span data-stu-id="1679a-117">This means that when first created, the planning line may be changed again.</span></span>  

 <span data-ttu-id="1679a-118">Для того чтобы уменьшить доступ к базе данных при обработке производственных заказов, можно поддерживать строку планирования на трех уровнях, пытаясь обеспечить наименее требовательный уровень обслуживания.</span><span class="sxs-lookup"><span data-stu-id="1679a-118">To minimize database access when handling production orders, the planning line can be maintained in three levels, while aiming to perform the least demanding maintenance level:</span></span>  

-   <span data-ttu-id="1679a-119">Создайте только строку планирования с текущим сроком оплаты и количеством, но без маршрута и компонентов.</span><span class="sxs-lookup"><span data-stu-id="1679a-119">Create only the planning line with the current due date and quantity but without the routing and components.</span></span>  

-   <span data-ttu-id="1679a-120">Включите маршрут: создается запланированный маршрут, включая расчет с дат и времени начала и окончания.</span><span class="sxs-lookup"><span data-stu-id="1679a-120">Include routing: the planned routing is laid out including calculation of starting and ending dates and times.</span></span> <span data-ttu-id="1679a-121">Это сложно с точки зрения доступа к базе данных.</span><span class="sxs-lookup"><span data-stu-id="1679a-121">This is demanding in terms of database accesses.</span></span> <span data-ttu-id="1679a-122">Определение конечных дат и сроков оплаты может потребовать вычисления этого значения, даже если событие поставки не было закрыто (в случае прямого планирования).</span><span class="sxs-lookup"><span data-stu-id="1679a-122">To determine the ending and due dates, it may be necessary to calculate this even if the supply event has not been closed (in the case of forward scheduling).</span></span>  

-   <span data-ttu-id="1679a-123">Включите развертывание спецификации: это может подождать до самого закрытия события.</span><span class="sxs-lookup"><span data-stu-id="1679a-123">Include BOM explosion: this can wait until just before the supply event is closed.</span></span>  

 <span data-ttu-id="1679a-124">Это завершает описание процедуры загрузки спроса и предложения, определения приоритетности и уравновешивания в системе планирования.</span><span class="sxs-lookup"><span data-stu-id="1679a-124">This concludes the descriptions of how demand and supply is loaded, prioritized, and balanced by the planning system.</span></span> <span data-ttu-id="1679a-125">При интеграции с этой операцией планирования поставок система должна гарантировать, что требуемый уровень запасов каждого запланированного товара будет поддерживаться в соответствии с политиками дозаказа.</span><span class="sxs-lookup"><span data-stu-id="1679a-125">In integration with this supply planning activity, the system must ensure that the required inventory level of each planned item is maintained according to its reordering policies.</span></span>  

## <a name="see-also"></a><span data-ttu-id="1679a-126">См. также</span><span class="sxs-lookup"><span data-stu-id="1679a-126">See Also</span></span>  
 <span data-ttu-id="1679a-127">[Сведения о проектировании: балансировка спроса и поставки](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="1679a-127">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
 <span data-ttu-id="1679a-128">[Сведения о проектировании: основные понятия системы планирования](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="1679a-128">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
 [<span data-ttu-id="1679a-129">Сведения о проектировании: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="1679a-129">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)

