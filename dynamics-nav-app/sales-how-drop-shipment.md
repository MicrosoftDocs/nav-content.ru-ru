---
title: "Практическое руководство. Выполнение прямых поставок"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: a726c8c24d8f843b33b4df4d85ad2b5eab3790e7
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="2ed7e-102">Практическое руководство. Выполнение прямых поставок</span><span class="sxs-lookup"><span data-stu-id="2ed7e-102">How to: Make Drop Shipments</span></span>
<span data-ttu-id="2ed7e-103">Прямая поставка — это поставка товаров одним из ваших поставщиков непосредственно одному из ваших клиентов.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="2ed7e-104">Когда заказ на продажу отмечен для прямой поставки и вы создаете заказ на покупку, указав клиента в поле **Код клиента (покупателя)**,</span><span class="sxs-lookup"><span data-stu-id="2ed7e-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="2ed7e-105">можно связать эти два документа, дав таким образом поставщику инструкцию для поставки непосредственно в адрес клиента.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="2ed7e-106">Создание заказа на продажу по прямой поставке</span><span class="sxs-lookup"><span data-stu-id="2ed7e-106">To create a sales order for drop shipment</span></span>
<span data-ttu-id="2ed7e-107">Для подготовки прямой поставки следует создать заказы на продажу для товара, как обычно, но необходимо указать в строке продажи, что продажа требует прямой поставки.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="2ed7e-108">Создайте заказ на продажу для товара.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-108">Create a sales order for an item.</span></span> <span data-ttu-id="2ed7e-109">Дополнительные сведения см. в разделе [Практическое руководство. Продажа продукции](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="2ed7e-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="2ed7e-110">В строке заказа на продажу для товара с прямой поставкой установите флажок **Прямая поставка**.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="2ed7e-111">Создание заказа на покупку для прямой поставки</span><span class="sxs-lookup"><span data-stu-id="2ed7e-111">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="2ed7e-112">Для подготовки прямой поставки для продаваемого товара следует создать обычный заказ на покупку, но необходимо указать в заказе на покупку, что он должен быть доставлен клиенту, а не вам.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="2ed7e-113">Создайте заказ покупки.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-113">Create a purchase order.</span></span> <span data-ttu-id="2ed7e-114">Не заполняйте никакие поля в строках.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-114">Do not fill any fields on the lines.</span></span> <span data-ttu-id="2ed7e-115">Дополнительные сведения см. в разделе [Практическое руководство. Регистрация покупок](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="2ed7e-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="2ed7e-116">В поле **Код клиента (покупателя)**</span><span class="sxs-lookup"><span data-stu-id="2ed7e-116">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="2ed7e-117">выберите клиента, которому осуществляется продажа.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-117">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="2ed7e-118">Выберите действие **Прямые поставки**, затем выберите действие **Получить заказ на продажу**.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="2ed7e-119">В окне **Список продаж** выберите заказ на продажу, который был подготовлен в разделе "Создание заказа на продажу по прямой поставке".</span><span class="sxs-lookup"><span data-stu-id="2ed7e-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="2ed7e-120">Выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-120">Choose the **OK** button.</span></span>

<span data-ttu-id="2ed7e-121">Информация строки в заказе на продажу будет вставлена в строки заказа на покупку.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-121">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="2ed7e-122">Теперь можно проинструктировать поставщика, чтобы он отгрузил товары клиенту, например, переслав заказ на покупку в виде файла PDF.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="2ed7e-123">Просмотр связанного заказа на покупку из заказа на продажу</span><span class="sxs-lookup"><span data-stu-id="2ed7e-123">To view the linked purchase order from the sales order</span></span>
1. <span data-ttu-id="2ed7e-124">Выберите строку заказа на продажу с прямой поставкой, выберите действие **Заказ**, выберите действие **Прямая поставка**, затем выберите действие **Заказ на покупку**.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

<span data-ttu-id="2ed7e-125">Открывается связанный заказ на покупку.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-125">The linked purchase order opens.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="2ed7e-126">Учет прямой поставки</span><span class="sxs-lookup"><span data-stu-id="2ed7e-126">To post a drop shipment</span></span>
<span data-ttu-id="2ed7e-127">Пока поставщик отгрузит товар, можно будет учесть заказ на продажу как отгруженный.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-127">When the vendor has shipped the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="2ed7e-128">Можно также учесть заказ на покупку, но только с параметром **Получить**, пока не будет выставлен счет по заказу на продажу.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>
1. <span data-ttu-id="2ed7e-129">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Заказы на продажу**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="2ed7e-130">Откройте заказ на продажу, созданный в разделе "Создание заказа на продажу по прямой поставке".</span><span class="sxs-lookup"><span data-stu-id="2ed7e-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="2ed7e-131">В поле **Кол-во для отгрузки** укажите, какое количество из заказа следует доставить, полное или частичное количество по заказу.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
3. <span data-ttu-id="2ed7e-132">Выберите действие **Учесть** или **Учесть и отправить**.</span><span class="sxs-lookup"><span data-stu-id="2ed7e-132">Choose the **Post** or **Post and Send** action.</span></span>
4. <span data-ttu-id="2ed7e-133">Выберите вариант **Отгрузить** (чтобы счет был выставлен позже) или вариант **Отгрузить и выставить счет** (чтобы счет был выставлен незамедлительно).</span><span class="sxs-lookup"><span data-stu-id="2ed7e-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="2ed7e-134">См. также</span><span class="sxs-lookup"><span data-stu-id="2ed7e-134">See Also</span></span>
<span data-ttu-id="2ed7e-135">[Практическое руководство. Продажа продукции](sales-how-sell-products.md)  </span><span class="sxs-lookup"><span data-stu-id="2ed7e-135">[How to: Sell Products](sales-how-sell-products.md)  </span></span>  
[<span data-ttu-id="2ed7e-136">Практическое руководство. Регистрация покупок</span><span class="sxs-lookup"><span data-stu-id="2ed7e-136">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="2ed7e-137">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="2ed7e-137">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="2ed7e-138">[Управление запасами](inventory-manage-inventory.md)    </span><span class="sxs-lookup"><span data-stu-id="2ed7e-138">[Manage Inventory](inventory-manage-inventory.md)    </span></span>  
[<span data-ttu-id="2ed7e-139">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="2ed7e-139">Work with Dynamics NAV</span></span>](ui-work-product.md)

