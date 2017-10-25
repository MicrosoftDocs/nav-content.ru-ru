---
title: "Сведения о проектировании — роль горизонта планирования"
description: "Цель горизонта планирования — сбор событий спроса в окне времени с целью составления совместного заказа на поставку."
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
ms.openlocfilehash: c05bb3ca1913b1f5d0abe0bfa26248d08e080ad6
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-the-role-of-the-time-bucket"></a><span data-ttu-id="a9b50-103">Сведения о проектировании: роль горизонта планирования</span><span class="sxs-lookup"><span data-stu-id="a9b50-103">Design Details: The Role of the Time Bucket</span></span>
<span data-ttu-id="a9b50-104">Цель горизонта планирования — сбор событий спроса в окне времени с целью составления совместного заказа на поставку.</span><span class="sxs-lookup"><span data-stu-id="a9b50-104">The purpose of the time bucket is to collect demand events within the time window in order to make a joint supply order.</span></span>  
  
 <span data-ttu-id="a9b50-105">Для политик дозаказа, в которых используется точка дозаказа, можно определить горизонт планирования.</span><span class="sxs-lookup"><span data-stu-id="a9b50-105">For reordering policies that use a reorder point, you can define a time bucket.</span></span> <span data-ttu-id="a9b50-106">Это обеспечивает аккумуляцию спроса в одном временном периоде до проверки влияния на прогнозируемые запасы и проверки прохождения точки повторного заказа.</span><span class="sxs-lookup"><span data-stu-id="a9b50-106">This ensures that demand within the same time period is accumulated before checking the impact on the projected inventory and whether the reorder point has been passed.</span></span> <span data-ttu-id="a9b50-107">Если точка дозаказа пройдена, планируется новый заказ на поставку на дату после даты конца периода, указанного в горизонте планирования.</span><span class="sxs-lookup"><span data-stu-id="a9b50-107">If the reorder point is passed, a new supply order is scheduled forward from the end of the period defined by the time bucket.</span></span> <span data-ttu-id="a9b50-108">Горизонты планирования начинаются в начальную дату планирования.</span><span class="sxs-lookup"><span data-stu-id="a9b50-108">The time buckets begin on the planning starting date.</span></span>  
  
 <span data-ttu-id="a9b50-109">Концепция горизонтов планирования отражает осуществляемый вручную процесс проверки уровня запасов на регулярной основе, а не для каждой транзакции.</span><span class="sxs-lookup"><span data-stu-id="a9b50-109">The time-bucketed concept reflects the manual process of checking the inventory level on a frequent basis rather than for each transaction.</span></span> <span data-ttu-id="a9b50-110">Пользователю требуется определить периодичность (горизонт планирования).</span><span class="sxs-lookup"><span data-stu-id="a9b50-110">The user needs to define the frequency (the time bucket).</span></span> <span data-ttu-id="a9b50-111">Например, пользователь объединяет все потребности в товарах для одного поставщика для размещения еженедельного заказа.</span><span class="sxs-lookup"><span data-stu-id="a9b50-111">For example, the user gathers all item needs from one vendor to place a weekly order.</span></span>  
  
 ![](media/nav_app_supply_planning_2_reorder_cycle.png "NAV_APP_supply_planning_2_reorder_cycle")  
  
 <span data-ttu-id="a9b50-112">Горизонт планирования, как правило, используется для того, чтобы избежать каскадного эффекта.</span><span class="sxs-lookup"><span data-stu-id="a9b50-112">The time bucket is generally used to avoid a cascade effect.</span></span> <span data-ttu-id="a9b50-113">Например, создается сбалансированная строка спроса и поставки, в которой отменяется преждевременный спрос.</span><span class="sxs-lookup"><span data-stu-id="a9b50-113">For example, a balanced row of demand and supply where an early demand is canceled, or a new one is created.</span></span> <span data-ttu-id="a9b50-114">Результатом будет перепланирование всех заказов на поставку (кроме последнего).</span><span class="sxs-lookup"><span data-stu-id="a9b50-114">The result would be that every supply order (except the last one) is rescheduled.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="a9b50-115">См. также</span><span class="sxs-lookup"><span data-stu-id="a9b50-115">See Also</span></span>  
 <span data-ttu-id="a9b50-116">[Сведения о проектировании: политики дозаказа](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="a9b50-116">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
 <span data-ttu-id="a9b50-117">[Сведения о проектировании: параметры планирования](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="a9b50-117">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
 <span data-ttu-id="a9b50-118">[Сведения о проектировании: обработка политик дозаказа](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="a9b50-118">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
 [<span data-ttu-id="a9b50-119">Сведения о проектировании: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="a9b50-119">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
