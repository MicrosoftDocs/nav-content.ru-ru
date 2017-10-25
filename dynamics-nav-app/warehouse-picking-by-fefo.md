---
title: "Как включить подбор по методу FEFO"
description: "FEFO (First-Expired-First-Out) — это метод сортировки, который обеспечивает, чтобы наиболее старые товары (с наиболее ранними датами истечения срока) подбирались первыми."
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
ms.openlocfilehash: d3977cd235293d685490464e51aec16a95d01e9d
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-picking-items-by-fefo"></a><span data-ttu-id="16ba1-103">Практическое руководство. Включение подбора товаров по методу FEFO</span><span class="sxs-lookup"><span data-stu-id="16ba1-103">How to: Enable Picking Items by FEFO</span></span>
<span data-ttu-id="16ba1-104">FEFO (First-Expired-First-Out) — это метод сортировки, который обеспечивает, чтобы наиболее старые товары (с наиболее ранними датами истечения срока) подбирались первыми.</span><span class="sxs-lookup"><span data-stu-id="16ba1-104">First-Expired-First-Out (FEFO) is a sorting method that ensures that the oldest items, those with the earliest expiration dates, are picked first.</span></span>  

 <span data-ttu-id="16ba1-105">Эта функция работает только при выполнении следующих условий:</span><span class="sxs-lookup"><span data-stu-id="16ba1-105">This functionality only works when the following criteria are met:</span></span>  

-   <span data-ttu-id="16ba1-106">Товар должен иметь серийный номер или номер партии.</span><span class="sxs-lookup"><span data-stu-id="16ba1-106">The item must have a serial/lot number.</span></span>  
-   <span data-ttu-id="16ba1-107">В настройках кода трассировки товара необходимо выбрать поле **Трассировка по серийному номеру** или **Трассировка по номеру партии**.</span><span class="sxs-lookup"><span data-stu-id="16ba1-107">On the item’s item tracking code setup, the **SN-Specific Warehouse Tracking** field or the **Lot-Specific Warehouse Tracking** field must be selected.</span></span>  
-   <span data-ttu-id="16ba1-108">Товар необходимо учесть на складе со сроком годности.</span><span class="sxs-lookup"><span data-stu-id="16ba1-108">The item must be posted to inventory with an expiration date.</span></span>  
-   <span data-ttu-id="16ba1-109">В карточке склада необходимо установить флажок **Требуется подбор**.</span><span class="sxs-lookup"><span data-stu-id="16ba1-109">On the location card, the **Require Pick** check box must be selected.</span></span>  
-   <span data-ttu-id="16ba1-110">В карточке склада необходимо установить флажок **Выбрать по методу FEFO**.</span><span class="sxs-lookup"><span data-stu-id="16ba1-110">On the location card, the **Pick According to FEFO** check box must be selected.</span></span>  
-   <span data-ttu-id="16ba1-111">В карточке склада необходимо установить флажок **Ячейка обязательна**.</span><span class="sxs-lookup"><span data-stu-id="16ba1-111">On the location card, the **Bin Mandatory** check box must be selected.</span></span>  

 <span data-ttu-id="16ba1-112">Когда вся критерии будут соблюдены, пронумерованные по партии или серийному номеру товары, которые необходимо собрать, сортируются таким образом, что первыми следуют самые ранние элементы во всех выборках и движениях, за исключением товаров, для которых используется отслеживание по серийному номеру или номеру партии.</span><span class="sxs-lookup"><span data-stu-id="16ba1-112">When all the criteria are met, then serial/lot-numbered items to be picked are sorted with the oldest first in all picks and movements, except for items that use SN-specific or lot-specific tracking.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="16ba1-113">Если товары с серийным номером или номером партии используют специальную трассировку, эти номера является первым и следующим за ним, остальные не указанные серийные номера и номера партии перечислены согласно методу FEFO.</span><span class="sxs-lookup"><span data-stu-id="16ba1-113">If some serial/lot-numbered items use specific tracking, then those are respected first and under them, the remaining, non-specific, serial/lot numbers are listed according to FEFO.</span></span>  

 <span data-ttu-id="16ba1-114">Если срок годности двух товаров совпадает, программа выбирает товар с наименьшим серийным номером или номером партии.</span><span class="sxs-lookup"><span data-stu-id="16ba1-114">If two serial/lot-numbered items have the same expiration date, then the program selects the item with the lowest serial or lot number.</span></span> <span data-ttu-id="16ba1-115">Если серийные номера или номера партий совпадают, программа выбирает товар, который был зарегистрирован раньше.</span><span class="sxs-lookup"><span data-stu-id="16ba1-115">If the serial or lot numbers are the same, then the program selects the item that was registered first.</span></span>  

> [!NOTE]  
>  -   <span data-ttu-id="16ba1-116">При подборе товаров с серийными номерами или номерами партий на складах, настроенных для расширенного подбора и размещения, по методу FEFO подбираются только количества в ячейках типа *Подбор*.</span><span class="sxs-lookup"><span data-stu-id="16ba1-116">When picking serial/lot-numbered items in locations set up for directed put-away and pick, only quantities on bins of type *Pick* are picked according to FEFO.</span></span>  
> -   <span data-ttu-id="16ba1-117">Для включения перемещений согласно методу FEFO в окне **Перемещение запасов** или в окне **Журнал перемещений** необходимо оставить поле **Из ячейки** пустым.</span><span class="sxs-lookup"><span data-stu-id="16ba1-117">To enable movements according to FEFO, either in the **Inventory Movement** window or the **Movement Worksheet** window, you must leave the **From Bin** field empty.</span></span>  
> -   <span data-ttu-id="16ba1-118">Если выбрано поле **Строгий учет срока годности**, то только товары с не истекшим сроком годности будут включены в подбор.</span><span class="sxs-lookup"><span data-stu-id="16ba1-118">If the **Strict Expiration Posting** field is selected, then only items that are not expired will be included in the pick.</span></span> <span data-ttu-id="16ba1-119">Это верно, даже если не используется "Выбрать по методу FEFO".</span><span class="sxs-lookup"><span data-stu-id="16ba1-119">This applies even if you are not using Pick according to FEFO.</span></span>  

## <a name="see-also"></a><span data-ttu-id="16ba1-120">См. также</span><span class="sxs-lookup"><span data-stu-id="16ba1-120">See Also</span></span>  
<span data-ttu-id="16ba1-121">[Подбор товаров](warehouse-pick-items.md) </span><span class="sxs-lookup"><span data-stu-id="16ba1-121">[Picking Items](warehouse-pick-items.md) </span></span>  
<span data-ttu-id="16ba1-122">[Практическое руководство. Подбор товаров для складской отгрузки](warehouse-how-to-pick-items-for-warehouse-shipment.md) </span><span class="sxs-lookup"><span data-stu-id="16ba1-122">[How to: Pick Items for Warehouse Shipment](warehouse-how-to-pick-items-for-warehouse-shipment.md) </span></span>  
<span data-ttu-id="16ba1-123">[Практическое руководство. Подбор товаров с помощью подбора запасов](warehouse-how-to-pick-items-with-inventory-picks.md) </span><span class="sxs-lookup"><span data-stu-id="16ba1-123">[How to: Pick Items with Inventory Picks](warehouse-how-to-pick-items-with-inventory-picks.md) </span></span>  
[<span data-ttu-id="16ba1-124">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="16ba1-124">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
[<span data-ttu-id="16ba1-125">Наличие</span><span class="sxs-lookup"><span data-stu-id="16ba1-125">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="16ba1-126">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="16ba1-126">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

