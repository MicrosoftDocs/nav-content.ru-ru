---
title: "Как отслеживать товары, трассируемые по товарам"
description: "Можно просмотреть, где использовался товар, для которого требуется трассировка, включая то, как и где он был получен или произведен, перемещен, продан, потреблен или возвращен. Также можно найти все текущие экземпляры определенного серийного номера или номера партии в базе данных. Функции, которые позволяют это сделать: \"Навигатор\" и \"Трассировка товаров\"."
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
ms.openlocfilehash: 80a7019c3ca8d2de03a4631b0ee3adb9a5964c99
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-trace-item-tracked-items"></a><span data-ttu-id="d0c98-105">Практическое руководство: отслеживание товаров, трассируемых по товарам</span><span class="sxs-lookup"><span data-stu-id="d0c98-105">How to: Trace Item-Tracked Items</span></span>
<span data-ttu-id="d0c98-106">Можно просмотреть, где использовался товар, для которого требуется трассировка, включая то, как и где он был получен или произведен, перемещен, продан, потреблен или возвращен.</span><span class="sxs-lookup"><span data-stu-id="d0c98-106">You can see where an item-tracked item was used, including how and when it was received or produced, transferred, sold, consumed, or returned.</span></span> <span data-ttu-id="d0c98-107">Также можно найти все текущие экземпляры определенного серийного номера или номера партии в базе данных.</span><span class="sxs-lookup"><span data-stu-id="d0c98-107">You can also find all current instances of a specific serial or lot number in the database.</span></span> <span data-ttu-id="d0c98-108">Функции, которые позволяют это сделать: "Навигатор" и "Трассировка товаров".</span><span class="sxs-lookup"><span data-stu-id="d0c98-108">You do this by using the Item Tracing and the Navigate features.</span></span>  

 <span data-ttu-id="d0c98-109">Эти функции могут быть особенно удобны в контроле качества, когда необходимо узнать, какие клиенты получили продукты с конкретным номером лота или из какого лота поступил дефектный компонент.</span><span class="sxs-lookup"><span data-stu-id="d0c98-109">These features can be particularly useful in quality control when you need to find out which customers received products with a particular lot number or when you need to find out which lot a defective component came from.</span></span>  

 <span data-ttu-id="d0c98-110">В окне **Трассировка товаров** можно выполнить трассировку вперед и назад согласно последовательности учтенных складских транзакций для серийного номера или номера партии.</span><span class="sxs-lookup"><span data-stu-id="d0c98-110">In the **Item Tracing** window, you can trace forwards and backwards in a sequence of posted inventory transactions for the serial or lot number.</span></span>  

 <span data-ttu-id="d0c98-111">В окне **Перейти** нельзя просматривать последовательность транзакций, но имеется возможность просмотреть все записи серийного номера или номера партии учтенных операций и открытых записей.</span><span class="sxs-lookup"><span data-stu-id="d0c98-111">In the **Navigate** window, you cannot see the sequence of transactions, but you can see all records of the serial or lot number, both posted entries and open records.</span></span>  

 <span data-ttu-id="d0c98-112">Эти две функции могут использоваться совместно путем переноса трассируемого серийного номера или номера партии в окно **Перейти** для завершения сценария полной трассировки.</span><span class="sxs-lookup"><span data-stu-id="d0c98-112">The two features can be used in combination by transferring a traced serial or lot number to the **Navigate** window to finish a complete trace scenario.</span></span> <span data-ttu-id="d0c98-113">Дополнительные сведения см. в разделе [Пошаговое руководство. Трассировка серийных номеров и номеров партии](walkthrough-tracing-serial-lot-numbers.md).</span><span class="sxs-lookup"><span data-stu-id="d0c98-113">For more information, see [Walkthrough: Tracing Serial-Lot Numbers](walkthrough-tracing-serial-lot-numbers.md).</span></span>  

## <a name="to-trace-item-tracked-items"></a><span data-ttu-id="d0c98-114">Трассировка товаров, трассируемых по товарам</span><span class="sxs-lookup"><span data-stu-id="d0c98-114">To trace item-tracked items</span></span>  

1.  <span data-ttu-id="d0c98-115">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Трассировка товаров**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d0c98-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Tracing**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d0c98-116">В полях фильтра в верхней части окна введите конкретные номера товаров или выполните фильтрацию по номерам товаров, для которых необходимо выполнить трассировку.</span><span class="sxs-lookup"><span data-stu-id="d0c98-116">In the filter fields at the top of the window, enter the specific item numbers or a filter on the item numbers that you would like to trace.</span></span>  
3.  <span data-ttu-id="d0c98-117">В поле **Показать компоненты** выберите, нужно ли также видеть, откуда поступили компоненты для товара.</span><span class="sxs-lookup"><span data-stu-id="d0c98-117">In the **Show Components** field, select whether you would like to also see where the components for the items came from.</span></span> <span data-ttu-id="d0c98-118">Для этого поля доступны следующие параметры.</span><span class="sxs-lookup"><span data-stu-id="d0c98-118">Your options in this field are as follows.</span></span>  

    |<span data-ttu-id="d0c98-119">Поле</span><span class="sxs-lookup"><span data-stu-id="d0c98-119">Field</span></span>|<span data-ttu-id="d0c98-120">Описанием</span><span class="sxs-lookup"><span data-stu-id="d0c98-120">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d0c98-121">**«Нет»**</span><span class="sxs-lookup"><span data-stu-id="d0c98-121">**No**</span></span>|<span data-ttu-id="d0c98-122">выберите этот вариант, если не компоненты отображать не требуется.</span><span class="sxs-lookup"><span data-stu-id="d0c98-122">Select this option if you do not want to see any components.</span></span>|  
    |<span data-ttu-id="d0c98-123">**Только с трассировкой**</span><span class="sxs-lookup"><span data-stu-id="d0c98-123">**Item-tracked Only**</span></span>|<span data-ttu-id="d0c98-124">выберите этот вариант, чтобы отображались только компоненты, имеющие номера лота или серийные номера.</span><span class="sxs-lookup"><span data-stu-id="d0c98-124">Select this option if you want to see only components that have lot or serial numbers.</span></span>|  
    |<span data-ttu-id="d0c98-125">**Все**</span><span class="sxs-lookup"><span data-stu-id="d0c98-125">**All**</span></span>|<span data-ttu-id="d0c98-126">выберите этот вариант, если необходимо видеть все компоненты.</span><span class="sxs-lookup"><span data-stu-id="d0c98-126">Select this option if you want to see all components.</span></span>|  

4.  <span data-ttu-id="d0c98-127">В поле **Метод трассировки** выберите метод, который необходимо использовать для трассировки товара.</span><span class="sxs-lookup"><span data-stu-id="d0c98-127">In the **Trace Method** field, select the method you would like to use for tracing the item.</span></span> <span data-ttu-id="d0c98-128">Возможны следующие варианты.</span><span class="sxs-lookup"><span data-stu-id="d0c98-128">The options are as follows</span></span>  

    |<span data-ttu-id="d0c98-129">Поле</span><span class="sxs-lookup"><span data-stu-id="d0c98-129">Field</span></span>|<span data-ttu-id="d0c98-130">Описанием</span><span class="sxs-lookup"><span data-stu-id="d0c98-130">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d0c98-131">**Потребление->Происхождение**</span><span class="sxs-lookup"><span data-stu-id="d0c98-131">**Usage->Origin**</span></span>|<span data-ttu-id="d0c98-132">Этот метод используется для трассировки товара, начиная с места его использования к месту, откуда он поступил на склад.</span><span class="sxs-lookup"><span data-stu-id="d0c98-132">This method traces the item starting from where it was used to where it came from.</span></span> <span data-ttu-id="d0c98-133">Например, если произведенный товар был продан клиенту, это отображается в окне **Трассировка товара**, причем сначала отображается строка расходной накладной продажи, которую затем можно развернуть, чтобы увидеть, из какого производственного заказа поступил этот товар.</span><span class="sxs-lookup"><span data-stu-id="d0c98-133">For instance, if a manufactured item was sold to a customer, the **Item Tracing** window shows this with the sales shipment line first, which you can then expand to see from which production order it came.</span></span>|  
    |<span data-ttu-id="d0c98-134">**Происхождение->потребление**</span><span class="sxs-lookup"><span data-stu-id="d0c98-134">**Origin->Usage**</span></span>|<span data-ttu-id="d0c98-135">этот метод используется для трассировки товара, начиная с места, откуда он поступил на склад, к месту его использования.</span><span class="sxs-lookup"><span data-stu-id="d0c98-135">This method traces the item starting from where it came into inventory to where it was used.</span></span> <span data-ttu-id="d0c98-136">Например, если произведенный товар был продан клиенту, это отображается в окне **Трассировка товара**, причем сначала отображается завершенный производственный заказ, который затем можно развернуть, чтобы увидеть строки расходной накладной продажи, в которой товар был использован.</span><span class="sxs-lookup"><span data-stu-id="d0c98-136">For instance, if a manufactured item was sold to a customer, the **Item Tracing** window shows this with the finished production order first, which you can then expand to see sale shipment lines where the item was used.</span></span>|  

5.  <span data-ttu-id="d0c98-137">Выберите действие **Трассировка**, чтобы выполнить трассировку.</span><span class="sxs-lookup"><span data-stu-id="d0c98-137">Choose the **Trace** action to run the trace.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="d0c98-138">Если одна и та же партия получена в нескольких транзакций, в окне **Трассировка товаров** могут не отражаться все транзакции.</span><span class="sxs-lookup"><span data-stu-id="d0c98-138">If you have received the same lot on more transactions, then the **Item Tracing** window may not show all transactions.</span></span> <span data-ttu-id="d0c98-139">Отображаются только примененные транзакции.</span><span class="sxs-lookup"><span data-stu-id="d0c98-139">Only applied transactions are shown.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="d0c98-140">Если дополнительная история транзакции возле строки трассировки товара уже отслежена другой строкой выше, значит флажок **Уже трассировано** установлен.</span><span class="sxs-lookup"><span data-stu-id="d0c98-140">If additional transaction history under an item tracing line has already been traced by another line above it, then the **Already Traced** check box is selected.</span></span> <span data-ttu-id="d0c98-141">Для обеспечения более простого вида такие основные строки не отображаются.</span><span class="sxs-lookup"><span data-stu-id="d0c98-141">To provide a simpler view, such underlying lines are not shown.</span></span>  
>   
>  <span data-ttu-id="d0c98-142">Для нахождения строк трассировки товара, где уже отслеживалась история транзакций, нажмите кнопку **Перейти к уже отслеженной истории**.</span><span class="sxs-lookup"><span data-stu-id="d0c98-142">To find the item tracing lines where the transaction history has already been traced, choose the **Go to Already Traced** button.</span></span> <span data-ttu-id="d0c98-143">Выбрана рассматриваемая строка трассировки товара, и все основные строки разворачиваются.</span><span class="sxs-lookup"><span data-stu-id="d0c98-143">The item tracing line in question is selected, and all underlying lines are expanded.</span></span>  

## <a name="to-find-item-tracked-items-with-navigate"></a><span data-ttu-id="d0c98-144">Поиск отслеживаемых товаров с помощью навигатора</span><span class="sxs-lookup"><span data-stu-id="d0c98-144">To find item-tracked items with Navigate</span></span>  

1.  <span data-ttu-id="d0c98-145">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Перейти**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d0c98-145">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Navigate**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d0c98-146">На экспресс-вкладке **Трассировка товаров** в полях **Серийный номер** и **Номер партии** введите номера трассировки товара, которые нужно трассировать.</span><span class="sxs-lookup"><span data-stu-id="d0c98-146">On the **Item Tracking** FastTab, in the **Serial No.** and **Lot No.** fields, enter the item tracking numbers that you want to trace.</span></span>  
3.  <span data-ttu-id="d0c98-147">Выберите действие **Найти** для обнаружения всех экземпляров серийного номера или номера партии в базе данных.</span><span class="sxs-lookup"><span data-stu-id="d0c98-147">Choose the **Find** action to find all instances of the serial or lot number in the database.</span></span>  

## <a name="see-also"></a><span data-ttu-id="d0c98-148">См. также</span><span class="sxs-lookup"><span data-stu-id="d0c98-148">See Also</span></span>  
[<span data-ttu-id="d0c98-149">Наличие</span><span class="sxs-lookup"><span data-stu-id="d0c98-149">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="d0c98-150">[Сведения о проектировании. Трассировка товаров](design-details-item-tracking.md)
[Сведения о проектировании. Отслеживание и резервирование товара](design-details-item-tracking-and-reservations.md)</span><span class="sxs-lookup"><span data-stu-id="d0c98-150">[Design Details: Item Tracking](design-details-item-tracking.md)
[Design Details - Item Tracking and Reservations](design-details-item-tracking-and-reservations.md)</span></span>  
[<span data-ttu-id="d0c98-151">Практическое руководство. Резервирование товаров</span><span class="sxs-lookup"><span data-stu-id="d0c98-151">How to: Reserve Items</span></span>](inventory-how-to-reserve-items.md)  
<span data-ttu-id="d0c98-152">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
[Пошаговое руководство. Трассировка серийных номеров и номеров партии](walkthrough-tracing-serial-lot-numbers.md)</span><span class="sxs-lookup"><span data-stu-id="d0c98-152">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
[Walkthrough: Tracing Serial-Lot Numbers](walkthrough-tracing-serial-lot-numbers.md)</span></span>
