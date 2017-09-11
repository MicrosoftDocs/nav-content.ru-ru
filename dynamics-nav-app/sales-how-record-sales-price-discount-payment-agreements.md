---
title: "Практическое руководство. Регистрация цен продажи и скидок"
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
ms.openlocfilehash: 80a0ac1edc994f44795f7f907a647b269578bc47
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a><span data-ttu-id="afaee-102">Практическое руководство. Регистрация цен продажи и скидок</span><span class="sxs-lookup"><span data-stu-id="afaee-102">How to: Record Sales Prices and Discounts</span></span>
<span data-ttu-id="afaee-103">Чтобы к документам продажи, созданным для клиентов, применялись согласованные правила и значения, необходимо определить различные соглашения в отношении цен и скидок, которые будут применяться при продаже товаров различным клиентам.</span><span class="sxs-lookup"><span data-stu-id="afaee-103">The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.</span></span>

<span data-ttu-id="afaee-104">В отношении цен, вы можете вводить в строки продаж определенную цену для определенного сочетания клиента, минимального количества, единицы измерения или даты начала/окончания.</span><span class="sxs-lookup"><span data-stu-id="afaee-104">Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="afaee-105">В отношении скидок, вы можете настроить и использовать два типа скидок продажи:</span><span class="sxs-lookup"><span data-stu-id="afaee-105">Concerning discounts, you can set up and use two types of sales discounts:</span></span>

|<span data-ttu-id="afaee-106">Тип скидки</span><span class="sxs-lookup"><span data-stu-id="afaee-106">Discount Type</span></span> |<span data-ttu-id="afaee-107">Описание</span><span class="sxs-lookup"><span data-stu-id="afaee-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="afaee-108">**Скидки строки продаж**</span><span class="sxs-lookup"><span data-stu-id="afaee-108">**Sales Line Discount**</span></span>|<span data-ttu-id="afaee-109">Сумма скидки, которая вводится в строки продаж для определенного сочетания клиента, минимального количества, единицы измерения или даты начала/окончания.</span><span class="sxs-lookup"><span data-stu-id="afaee-109">An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="afaee-110">Эта функция работает так же, как и для цен продажи.</span><span class="sxs-lookup"><span data-stu-id="afaee-110">This works in the same way as for sales prices.</span></span>|
|<span data-ttu-id="afaee-111">**Скидка по счету**</span><span class="sxs-lookup"><span data-stu-id="afaee-111">**Invoice Discount**</span></span>|<span data-ttu-id="afaee-112">Процентная скидка, которая вычитается из общей суммы документа, если сумма всех строк документа продажи превышает определенный минимум.</span><span class="sxs-lookup"><span data-stu-id="afaee-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.</span></span>|

<span data-ttu-id="afaee-113">Так как цены продажи и скидки по строкам продажи, зависят от комбинации товара и клиента, можно также выполнить эту настройку из карточки товара, в которой применяются правила и значения.</span><span class="sxs-lookup"><span data-stu-id="afaee-113">Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.</span></span>

## <a name="to-set-up-a-sales-price-for-a-customer"></a><span data-ttu-id="afaee-114">Настройка цены продажи для клиента</span><span class="sxs-lookup"><span data-stu-id="afaee-114">To set up a sales price for a customer</span></span>
1. <span data-ttu-id="afaee-115">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Клиенты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="afaee-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="afaee-116">Откройте соответствующую карточку клиента и выберите действие **Цены**.</span><span class="sxs-lookup"><span data-stu-id="afaee-116">Open the relevant customer card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="afaee-117">В поле **Тип продажи** будет стоять значение **Клиент**, а поле **Код продажи** будет содержать номер клиента.</span><span class="sxs-lookup"><span data-stu-id="afaee-117">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3. <span data-ttu-id="afaee-118">Заполните поля в строке по мере необходимости.</span><span class="sxs-lookup"><span data-stu-id="afaee-118">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="afaee-119">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="afaee-119">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="afaee-120">Заполните строку для каждой комбинации, которая предоставляет клиенту специальную цену.</span><span class="sxs-lookup"><span data-stu-id="afaee-120">Fill a line for each combination that will grant a special sales price to the customer.</span></span>

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a><span data-ttu-id="afaee-121">Настройка скидки строки продажи для клиента</span><span class="sxs-lookup"><span data-stu-id="afaee-121">To set up a sales line discount for a customer</span></span>
1. <span data-ttu-id="afaee-122">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Клиенты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="afaee-122">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="afaee-123">Откройте соответствующую карточку клиента и выберите действие **Скидки строки**.</span><span class="sxs-lookup"><span data-stu-id="afaee-123">Open the relevant customer card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="afaee-124">В поле **Тип продажи** будет стоять значение **Клиент**, а поле **Код продажи** будет содержать номер клиента.</span><span class="sxs-lookup"><span data-stu-id="afaee-124">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3.  <span data-ttu-id="afaee-125">Заполните поля в строке по мере необходимости.</span><span class="sxs-lookup"><span data-stu-id="afaee-125">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="afaee-126">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="afaee-126">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="afaee-127">Заполните строку для каждой комбинации, которая предоставляет клиенту скидку строки продажи.</span><span class="sxs-lookup"><span data-stu-id="afaee-127">Fill a line for each combination that will grant a sales line discount to the customer.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a><span data-ttu-id="afaee-128">Настройка скидки по счету для клиента</span><span class="sxs-lookup"><span data-stu-id="afaee-128">To set up an invoice discount for a customer</span></span>
<span data-ttu-id="afaee-129">После того, как принято решение, какие клиенты имеют право на скидки по счетам, укажите в карточках этих клиентов коды скидок по счетам и настройте условия для каждого кода.</span><span class="sxs-lookup"><span data-stu-id="afaee-129">When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="afaee-130">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Клиенты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="afaee-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="afaee-131">Откройте карточку клиента, который имеет право на получение скидок по счетам.</span><span class="sxs-lookup"><span data-stu-id="afaee-131">Open the customer card for a customer that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="afaee-132">В поле **Код скидки по счету** выберите код соответствующих условий скидки по счету, который будет использован программой для вычисления скидок по счету для клиента.</span><span class="sxs-lookup"><span data-stu-id="afaee-132">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.</span></span>

    <span data-ttu-id="afaee-133">**Примечание**. Коды скидок по счету представлены существующими карточками клиентов.</span><span class="sxs-lookup"><span data-stu-id="afaee-133">**Note**: Invoice discount codes are represented by existing customer cards.</span></span> <span data-ttu-id="afaee-134">Это позволяет быстро назначить условия скидки по счету клиентам, выбрав название другого клиента с такими же условиями.</span><span class="sxs-lookup"><span data-stu-id="afaee-134">This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.</span></span>

    <span data-ttu-id="afaee-135">Перейдите к настройке новых условий скидок по счету продажи.</span><span class="sxs-lookup"><span data-stu-id="afaee-135">Proceed to set up new the sales invoice discount terms.</span></span>
4. <span data-ttu-id="afaee-136">В окне **Карточка клиента** выберите действие **Скидки по счету**.</span><span class="sxs-lookup"><span data-stu-id="afaee-136">In the **Customer Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="afaee-137">Откроется окно **Клиент - скидки по счету**.</span><span class="sxs-lookup"><span data-stu-id="afaee-137">The **Cust. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="afaee-138">В поле **Код валюты** укажите код валюты, к которой относятся условия скидки по счету в строке.</span><span class="sxs-lookup"><span data-stu-id="afaee-138">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="afaee-139">Оставьте поле пустым, чтобы установить условия скидки по счету в местной валюте (руб.).</span><span class="sxs-lookup"><span data-stu-id="afaee-139">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="afaee-140">В поле **Минимальная сумма** введите минимальную сумму, которая должна быть на счете, чтобы для этого счета была установлена скидка.</span><span class="sxs-lookup"><span data-stu-id="afaee-140">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="afaee-141">В поле **Скидка (%)** введите скидку по счету в процентах от суммы счета.</span><span class="sxs-lookup"><span data-stu-id="afaee-141">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="afaee-142">Повторите шаги 5–7 для каждой валюты, в которой клиент будет получать отдельную скидку по счету.</span><span class="sxs-lookup"><span data-stu-id="afaee-142">Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.</span></span>

<span data-ttu-id="afaee-143">Скидка по счету теперь настроена и назначена соответствующему клиенту.</span><span class="sxs-lookup"><span data-stu-id="afaee-143">The invoice discount is now set up and assigned to the customer in question.</span></span> <span data-ttu-id="afaee-144">При выборе кода клиента в поле **Код скидки по счету** на других карточках клиентов этим клиентам назначается так же скидка по счету.</span><span class="sxs-lookup"><span data-stu-id="afaee-144">When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.</span></span>

## <a name="see-also"></a><span data-ttu-id="afaee-145">См. также</span><span class="sxs-lookup"><span data-stu-id="afaee-145">See Also</span></span>  
[<span data-ttu-id="afaee-146">Настройка продаж</span><span class="sxs-lookup"><span data-stu-id="afaee-146">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="afaee-147">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="afaee-147">Manage Sales</span></span>](sales-manage-sales.md)

