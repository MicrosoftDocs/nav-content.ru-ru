---
title: "Сведения о проектировании — обработка заказов до даты начала планирования"
description: "В этом разделе описываются правила, которые применяются при планировании заказов в замороженной зоне."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: planning, frozen, design serial, lot
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 9b15856d89be0c0fba18381cea730a8a388986a3
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-dealing-with-orders-before-the-planning-starting-date"></a><span data-ttu-id="d46ad-103">Сведения о проектировании: обработка заказов до даты начала планирования</span><span class="sxs-lookup"><span data-stu-id="d46ad-103">Design Details: Dealing with Orders Before the Planning Starting Date</span></span>
<span data-ttu-id="d46ad-104">Чтобы избежать отображения невозможных и, следовательно, бесполезных предположений в плане поставок, система планирования учитывает период до начальной даты зоны заморозки, в которой ничего нельзя планировать.</span><span class="sxs-lookup"><span data-stu-id="d46ad-104">To avoid that a supply plan shows impossible and therefore useless suggestions, the planning system regards the period up until the planning starting date a frozen zone where nothing is planned for.</span></span> <span data-ttu-id="d46ad-105">Следующее правило применяется к замороженной зоне:</span><span class="sxs-lookup"><span data-stu-id="d46ad-105">The following rule applies to the frozen zone:</span></span>  
  
<span data-ttu-id="d46ad-106">Весь спрос и поставки до даты начала периода планирования будут считаться частью запасов или будут считаться отгруженными.</span><span class="sxs-lookup"><span data-stu-id="d46ad-106">All supply and demand before the starting date of the planning period will be considered a part of inventory or shipped.</span></span>  
  
<span data-ttu-id="d46ad-107">Соответственно, за некоторыми исключениями система планирования не будет предлагать какие-либо изменения в заказах на поставку в замороженной зоне, и связи трассировки заказа не будут создаваться или поддерживаться на данный период.</span><span class="sxs-lookup"><span data-stu-id="d46ad-107">Accordingly, the planning system will not, with a few exceptions, suggest any changes to supply orders in the frozen zone, and no order tracking links are created or maintained for that period.</span></span>  
  
<span data-ttu-id="d46ad-108">В этом правиле следующие исключения.</span><span class="sxs-lookup"><span data-stu-id="d46ad-108">The exceptions to this rule are as follows:</span></span>  
  
* <span data-ttu-id="d46ad-109">Если прогнозируемые доступные запасы, включая сумму спроса и поставки в замороженной зоне, меньше нуля.</span><span class="sxs-lookup"><span data-stu-id="d46ad-109">If the projected available inventory, including the sum of supply and demand in the frozen zone, is below zero.</span></span>  
* <span data-ttu-id="d46ad-110">Если требуются серийные номера/номера партий в заказах, записываемых задним числом.</span><span class="sxs-lookup"><span data-stu-id="d46ad-110">If serial/lot numbers are required on the backdated order(s).</span></span>  
* <span data-ttu-id="d46ad-111">Если набор поставки и спроса связан требованиями политики "заказ-в-заказ".</span><span class="sxs-lookup"><span data-stu-id="d46ad-111">If the supply-demand set is linked by an order-to-order policy.</span></span>  
  
<span data-ttu-id="d46ad-112">Если исходные доступные запасы ниже нуля, система планирования предложит экстренный заказ на поставку на день, предшествующий периоду планирования для обеспечения наличия отсутствующего количества.</span><span class="sxs-lookup"><span data-stu-id="d46ad-112">If the initial available inventory is below zero, the planning system suggests an emergency supply order on the day before the planning period to cover the missing quantity.</span></span> <span data-ttu-id="d46ad-113">Следовательно, прогнозируемые и доступные запасы всегда будут равны хотя бы нулю, когда начинается планирование будущего периода.</span><span class="sxs-lookup"><span data-stu-id="d46ad-113">Consequently, the projected and available inventory will always be at least zero when planning for the future period begins.</span></span> <span data-ttu-id="d46ad-114">Строка планирования для этого заказа на поставку отобразит предупреждающий значок аварийной ситуации с возможностью просмотра дополнительных сведений.</span><span class="sxs-lookup"><span data-stu-id="d46ad-114">The planning line for this supply order will display an Emergency warning icon and additional information is provided upon lookup.</span></span>  
  
## <a name="seriallot-numbers-and-order-to-order-links-are-exempt-from-the-frozen-zone"></a><span data-ttu-id="d46ad-115">Серийные номера или номера партий и связи "заказ-в-заказ" исключены из замороженной зоны</span><span class="sxs-lookup"><span data-stu-id="d46ad-115">Serial/Lot Numbers and Order-to-Order Links are Exempt from the Frozen Zone</span></span>  
<span data-ttu-id="d46ad-116">Если требуются серийные номера или номера партий либо существует связь "заказ-а-заказ", система планирования будет игнорировать замороженную зону и включит записанные задним числом количества, начиная с даты начала, а также, возможно, предложит корректирующие действия, если спрос и поставка не синхронизированы.</span><span class="sxs-lookup"><span data-stu-id="d46ad-116">If serial/lot numbers are required or an order-to-order link exists, the planning system will disregard the frozen zone and incorporate such quantities that are back-dated from the starting date and potentially suggest corrective actions if demand and supply is not synchronized.</span></span> <span data-ttu-id="d46ad-117">Коммерческое обоснование этого принципа следующее: конкретные наборы спроса и предложения должны совпадать, чтобы обеспечить удовлетворение спроса.</span><span class="sxs-lookup"><span data-stu-id="d46ad-117">The business reason for this principle is that such specific demand-supply sets must match to ensure that this specific demand is fulfilled.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="d46ad-118">См. также</span><span class="sxs-lookup"><span data-stu-id="d46ad-118">See Also</span></span>  
<span data-ttu-id="d46ad-119">[Сведения о проектировании: балансировка спроса и поставки](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="d46ad-119">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
<span data-ttu-id="d46ad-120">[Сведения о проектировании: основные понятия системы планирования](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="d46ad-120">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
[<span data-ttu-id="d46ad-121">Сведения о проектировании: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="d46ad-121">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
