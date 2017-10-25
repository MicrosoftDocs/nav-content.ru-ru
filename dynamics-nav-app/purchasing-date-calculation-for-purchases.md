---
title: "Расчет даты для покупок"
description: "Программа автоматически вычисляет дату, когда следует заказать товар, чтобы иметь его на складе на определенную дату. Это дата, когда можно ожидать, что товары, заказанные на конкретную дату, будут доступны для подбора."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3f3f87311f0971b2901852a9aa0c766c6c806190
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="date-calculation-for-purchases"></a><span data-ttu-id="04f4a-104">Расчет даты для покупок</span><span class="sxs-lookup"><span data-stu-id="04f4a-104">Date Calculation for Purchases</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="04f4a-105"> автоматически вычисляет дату, когда следует заказать товар, чтобы иметь его на складе на определенную дату.</span><span class="sxs-lookup"><span data-stu-id="04f4a-105"> automatically calculates the date on which you must order an item to have it in inventory on a certain date.</span></span> <span data-ttu-id="04f4a-106">Это дата, когда можно ожидать, что товары, заказанные на конкретную дату, будут доступны для подбора.</span><span class="sxs-lookup"><span data-stu-id="04f4a-106">This is the date on which you can expect items ordered on a particular date to be available for picking.</span></span>  

<span data-ttu-id="04f4a-107">Если в заголовке заказа на покупку указана требуемая дата приемки, рассчитанная дата заказа является датой, на которую заказ должен быть размещен, чтобы товары вовремя поступили на склад.</span><span class="sxs-lookup"><span data-stu-id="04f4a-107">If you specify a requested receipt date on a purchase order header, then the calculated order date is the date on which the order must be placed to receive the items on the date that you requested.</span></span> <span data-ttu-id="04f4a-108">Затем дата, в которую товары будут в наличии для подбора, вычисляется и вводится в поле **Ожидаемая дата поставки**.</span><span class="sxs-lookup"><span data-stu-id="04f4a-108">Then, the date on which the items are available for picking is calculated and entered in the **Expected Receipt Date** field.</span></span>  

<span data-ttu-id="04f4a-109">Если требуемая дата приемки не указана, в качестве начальной точки расчета ожидаемой даты поставки товаров и даты, при наступлении которой товары станут доступны для подбора, используется дата заказа в строке документа.</span><span class="sxs-lookup"><span data-stu-id="04f4a-109">If you do not specify a requested receipt date, then the order date on the line is used as the starting point for calculating the date on which you can expect to receive the items and the date on which the items are available for picking.</span></span>  

## <a name="calculating-with-a-requested-receipt-date"></a><span data-ttu-id="04f4a-110">Вычисление с требуемой датой приемки</span><span class="sxs-lookup"><span data-stu-id="04f4a-110">Calculating with a Requested Receipt Date</span></span>  
<span data-ttu-id="04f4a-111">Если в строке заказа на покупку указана требуемая дата приемки, она будет использоваться как отправная точка для следующих расчетов.</span><span class="sxs-lookup"><span data-stu-id="04f4a-111">If there is a requested receipt date on the purchase order line, then that date is used as the starting point for the following calculations.</span></span>  

- <span data-ttu-id="04f4a-112">требуемая дата приемки - расчет времени упреждения = дата заказа</span><span class="sxs-lookup"><span data-stu-id="04f4a-112">requested receipt date - lead time calculation = order date</span></span>  
- <span data-ttu-id="04f4a-113">требуемая дата приемки + входящие - время обработки склада + страховой запас времени упреждения = Ожидаемая дата приемки</span><span class="sxs-lookup"><span data-stu-id="04f4a-113">requested receipt date + inbound whse. handling time + safety lead time = expected receipt date</span></span>  

<span data-ttu-id="04f4a-114">Если в заголовок заказа на покупку введена требуемая дата приемки, то она будет скопирована в соответствующее поле всех строк заказа.</span><span class="sxs-lookup"><span data-stu-id="04f4a-114">If you entered a requested receipt date on the purchase order header, then that date is copied to the corresponding field on all the lines.</span></span> <span data-ttu-id="04f4a-115">Эту дату можно изменить или удалить в любой строке.</span><span class="sxs-lookup"><span data-stu-id="04f4a-115">You can change this date on any of the lines, or you can remove the date on the line.</span></span>  

## <a name="calculating-without-a-requested-delivery-date"></a><span data-ttu-id="04f4a-116">Вычисление без требуемой даты доставки</span><span class="sxs-lookup"><span data-stu-id="04f4a-116">Calculating without a Requested Delivery Date</span></span>  
<span data-ttu-id="04f4a-117">При вводе строки заказа на покупку без требуемой даты доставки в поле **Дата заказа** в строке копируется дата из поля **Дата заказа** в заголовке заказа на покупку.</span><span class="sxs-lookup"><span data-stu-id="04f4a-117">If you enter a purchase order line without a requested delivery date, then the **Order Date** field on the line is filled with the date in the **Order Date** field on the purchase order header.</span></span> <span data-ttu-id="04f4a-118">Это может быть введенная вами дата или рабочая дата.</span><span class="sxs-lookup"><span data-stu-id="04f4a-118">This is either the date that you entered or the work date.</span></span> <span data-ttu-id="04f4a-119">Затем рассчитываются следующие даты для строки заказа на покупку с датой заказа в качестве начальной точки.</span><span class="sxs-lookup"><span data-stu-id="04f4a-119">The following dates are then calculated for the purchase order line, with the order date as the starting point.</span></span>  

- <span data-ttu-id="04f4a-120">дата заказа + расчет времени обработки заказа = плановая дата приемки.</span><span class="sxs-lookup"><span data-stu-id="04f4a-120">order date + lead time calculation = planned receipt date</span></span>  
- <span data-ttu-id="04f4a-121">требуемая дата поставки + вход. время обработки склада + страховой запас времени = ожидаемая дата приемки</span><span class="sxs-lookup"><span data-stu-id="04f4a-121">planned receipt date + inbound whse. handling time + safety lead time = expected receipt date</span></span>  

<span data-ttu-id="04f4a-122">В случае изменения даты заказа в строке, например из-за того, что товары недоступны у поставщика до более поздней даты, соответствующие даты в строке пересчитываются автоматически.</span><span class="sxs-lookup"><span data-stu-id="04f4a-122">If you change the order date on the line, such as when items are not available at your vendor until a later date, then the relevant dates on the line are automatically recalculated.</span></span>  

<span data-ttu-id="04f4a-123">В случае изменения даты заказа в заголовке документа, эта дата копируется в поле **Дата заказа** во всех строках, а все взаимосвязанные поля дат вычисляются заново.</span><span class="sxs-lookup"><span data-stu-id="04f4a-123">If you change the order date on the header, then that date is copied to the **Order Date** field on all the lines, and all the related date fields are then recalculated.</span></span>  

## <a name="see-also"></a><span data-ttu-id="04f4a-124">См. также</span><span class="sxs-lookup"><span data-stu-id="04f4a-124">See Also</span></span>  
 <span data-ttu-id="04f4a-125">[Расчет даты для продаж](sales-date-calculation-for-sales.md) </span><span class="sxs-lookup"><span data-stu-id="04f4a-125">[Date Calculation for Sales](sales-date-calculation-for-sales.md) </span></span>  
 [<span data-ttu-id="04f4a-126">Практическое руководство. Расчет сроков планирования заказов</span><span class="sxs-lookup"><span data-stu-id="04f4a-126">How to: Calculate Order Promising Dates</span></span>](sales-how-to-calculate-order-promising-dates.md)  
 <span data-ttu-id="04f4a-127">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="04f4a-127">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

