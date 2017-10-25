---
title: "Сведения о проектировании — заказ"
description: "В этом разделе приведены сведения о ссылках \"заказ-в-заказ\" в среде изготовления на заказ."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, order
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7e8105795f4b2a45510fc50cfed4a8fadad8f1eb
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-order"></a><span data-ttu-id="014c0-103">Сведения о проектировании: заказ</span><span class="sxs-lookup"><span data-stu-id="014c0-103">Design Details: Order</span></span>
<span data-ttu-id="014c0-104">В среде изготовления продукции на заказ товар приобретается или производится исключительно для удовлетворения определенного спроса.</span><span class="sxs-lookup"><span data-stu-id="014c0-104">In a make-to-order environment, an item is purchased or produced to exclusively cover a specific demand.</span></span> <span data-ttu-id="014c0-105">Как правило, относится к товарам категории А. Мотивация для выбора такой политики повторного заказа — нерегулярный спрос, незначительное время подготовки или варьирование необходимых атрибутов.</span><span class="sxs-lookup"><span data-stu-id="014c0-105">Typically it relates to A-items, and the motivation for choosing the order reordering policy can be that the demand is infrequent, the lead-time is insignificant, or the required attributes vary.</span></span>  
  
<span data-ttu-id="014c0-106">Программа создает ссылку от заказа к заказу, которая действует как основное соединение между поставкой, заказом на поставку или запасом и спросом, который будет удовлетворен.</span><span class="sxs-lookup"><span data-stu-id="014c0-106">The program creates an order-to-order link, which acts as a preliminary connection between the supply, a supply order or inventory, and the demand that it is going to fulfill.</span></span>  
  
<span data-ttu-id="014c0-107">Помимо использования политики "Заказ" связь "заказ-в-заказ" можно применить во время планирования одним из следующих способов:</span><span class="sxs-lookup"><span data-stu-id="014c0-107">Apart from using the Order policy, the order-to-order link can be applied during planning in the following ways:</span></span>  
  
* <span data-ttu-id="014c0-108">При использовании политики производства на заказ для создания многоуровневых производственных заказов или заказов проектного типа (производство необходимых компонентов в одном производственном заказе).</span><span class="sxs-lookup"><span data-stu-id="014c0-108">When using the Make-to-Order manufacturing policy to create multi-level or project type production orders (producing needed components on the same production order).</span></span>  
* <span data-ttu-id="014c0-109">При использовании функции планирования заказов на продажу для создания производственного заказа из заказа на продажу.</span><span class="sxs-lookup"><span data-stu-id="014c0-109">When using the Sales Order Planning feature to create a production order from a sales order.</span></span>  
  
<span data-ttu-id="014c0-110">Даже если производственная организация считает себя организацией, которая изготавливает продукты на заказ, может иметь смысл использовать политику дозаказа "Партия на партию", если товары абсолютно стандартные без изменений атрибутов.</span><span class="sxs-lookup"><span data-stu-id="014c0-110">Even if a manufacturing company considers itself as a make-to-order environment, it might be best to use a Lot-for-Lot reordering policy if the items are pure standard without variation in attributes.</span></span> <span data-ttu-id="014c0-111">В результате, система будет использовать незапланированный запас и накапливать только заказы на продажу с одинаковой датой отгрузки или заказы на продажу в пределах указанного горизонта планирования.</span><span class="sxs-lookup"><span data-stu-id="014c0-111">As a result, the system will use unplanned inventory and only accumulates sales orders with the same shipment date or within a defined time bucket.</span></span>  
  
## <a name="order-to-order-links-and-past-due-dates"></a><span data-ttu-id="014c0-112">Связи "заказ-в-заказ" и просроченные даты</span><span class="sxs-lookup"><span data-stu-id="014c0-112">Order-to-Order Links and Past Due Dates</span></span>  
<span data-ttu-id="014c0-113">В отличие от большинства наборов спрос-предложение, связанные заказы с датами оплаты до даты начала планирования полностью планируются системой.</span><span class="sxs-lookup"><span data-stu-id="014c0-113">Unlike most supply-demand sets, linked orders with due dates before the planning starting date are fully planned for by the system.</span></span> <span data-ttu-id="014c0-114">Коммерческое обоснование этого исключения следующее: конкретные наборы спроса и предложения должны синхронизироваться вплоть до самого исполнения.</span><span class="sxs-lookup"><span data-stu-id="014c0-114">The business reason for this exception is that specific demand-supply sets must be synchronized through to execution.</span></span> <span data-ttu-id="014c0-115">Дополнительные сведения о замороженной зоне, применяемой к большинству типов цепочки спроса-поставки, см. в разделе [Сведения о проектировании: обработка заказов до даты начала планирования](design-details-dealing-with-orders-before-the-planning-starting-date.md).</span><span class="sxs-lookup"><span data-stu-id="014c0-115">For more information about the frozen zone that applies to most demand-supply types, see [Design Details: Dealing with Orders Before the Planning Starting Date](design-details-dealing-with-orders-before-the-planning-starting-date.md).</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="014c0-116">См. также</span><span class="sxs-lookup"><span data-stu-id="014c0-116">See Also</span></span>  
<span data-ttu-id="014c0-117">[Сведения о проектировании: политики дозаказа](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="014c0-117">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="014c0-118">[Сведения о проектировании: параметры планирования](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="014c0-118">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="014c0-119">[Сведения о проектировании: обработка политик дозаказа](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="014c0-119">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="014c0-120">Сведения о проектировании: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="014c0-120">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
