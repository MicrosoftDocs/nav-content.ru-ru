---
title: "Настройка предоплаты"
description: "Предоплата — это платежи, для которых выставление счетов и учет в заказах на предоплату при продажах или покупках осуществляется до окончательного выставления счетов. Может требоваться аванс перед началом производства товаров по заказу или платеж перед из отгрузкой клиенту. Благодаря функции предоплаты можно выставлять счета и собирать необходимые авансы от клиентов либо переводить авансы поставщикам. Таким образом, можно гарантировать учет всех платежей по счету."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 7219f32fee591134c2c239b0df959e000d63aeb3
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-prepayments"></a><span data-ttu-id="d7050-106">Практическое руководство. Настройка предоплаты</span><span class="sxs-lookup"><span data-stu-id="d7050-106">How to: Set Up Prepayments</span></span>
<span data-ttu-id="d7050-107">Если требуется, чтобы клиенты осуществляли платежи до отгрузки им заказов, или если аналогичное требование выдвигают поставщики в отношении вашей организации, можно использовать функцию предоплаты.</span><span class="sxs-lookup"><span data-stu-id="d7050-107">If you require your customers to submit payment before you ship an order to them, or if your vendor requires you to submit payment before they ship an order to you, you can use the Prepayment functionality.</span></span> <span data-ttu-id="d7050-108">Благодаря функции предоплаты можно выставлять счета и собирать необходимые авансы от клиентов либо переводить авансы поставщикам, а также обеспечивать учет всех частичных платежей для счета.</span><span class="sxs-lookup"><span data-stu-id="d7050-108">The functionality enables you to invoice and collect deposits required from customers or to remit deposits to vendors, and to ensure that all partial payments are posted against an invoice.</span></span> <span data-ttu-id="d7050-109">Дополнительные сведения в разделе [Практическое руководство. Создание счетов на предоплату](finance-how-to-create-prepayment-invoices.md).</span><span class="sxs-lookup"><span data-stu-id="d7050-109">For more information, see [How to: Create Prepayment Invoices](finance-how-to-create-prepayment-invoices.md).</span></span>

<span data-ttu-id="d7050-110">Прежде чем учитывать счета на предоплату, необходимо настроить учетные счета в главной книге и серии номеров для документов предоплаты.</span><span class="sxs-lookup"><span data-stu-id="d7050-110">Before you can post prepayment invoices, you have to set up the posting accounts in the general ledger, and you have to set up number series for prepayment documents.</span></span>  

<span data-ttu-id="d7050-111">Можно определить процент суммы строки, на которую будет выставлен счет на предоплату, для клиента или поставщика для всех или выбранных товаров.</span><span class="sxs-lookup"><span data-stu-id="d7050-111">You can define the percentage of the line amount that will be invoiced for prepayment, for a customer or vendor, for all items or selected items.</span></span> <span data-ttu-id="d7050-112">После завершения настройки можно сгенерировать счета на предоплату на основе заказов на продажу или покупку.</span><span class="sxs-lookup"><span data-stu-id="d7050-112">After you complete the setup, you can generate prepayment invoices from sales and purchase orders.</span></span> <span data-ttu-id="d7050-113">Для каждой строки продажи либо покупки можно использовать проценты по умолчанию, а также можно изменять требуемым образом суммы по счету.</span><span class="sxs-lookup"><span data-stu-id="d7050-113">You can use the default percentages for each sales or purchase line, or you can change the amounts on the invoice as needed.</span></span> <span data-ttu-id="d7050-114">Например, можно указать общую сумму для всего заказа.</span><span class="sxs-lookup"><span data-stu-id="d7050-114">For example, you can specify a total amount for the entire order.</span></span>  

<span data-ttu-id="d7050-115">Поскольку сумма предоплаты принадлежит покупателю до тех пор, пока он не получит товары или услуги, необходимо настроить счета Главной книги для хранения сумм предоплаты до момента учета окончательного счета.</span><span class="sxs-lookup"><span data-stu-id="d7050-115">Because the prepaid amount belongs to the buyer until they have received the goods or services, you need to set up general ledger accounts to hold the prepayment amounts until the final invoice is posted.</span></span> <span data-ttu-id="d7050-116">Предоплаты при продаже должны регистрироваться на счете пассивов до отгрузки товаров.</span><span class="sxs-lookup"><span data-stu-id="d7050-116">Sales prepayments must be recorded in a liabilities account until the items are shipped.</span></span> <span data-ttu-id="d7050-117">Предоплаты при покупке должны регистрироваться на счете активов до получения товаров.</span><span class="sxs-lookup"><span data-stu-id="d7050-117">Purchase prepayments must be recorded in an assets account until the items are received.</span></span> <span data-ttu-id="d7050-118">Кроме того, для каждого идентификатора НДС необходимо настроить отдельную ГК.</span><span class="sxs-lookup"><span data-stu-id="d7050-118">In addition, you must set up a separate general ledger account for each VAT identifier.</span></span>

## <a name="to-add-prepayment-accounts-to-the-general-posting-setup"></a><span data-ttu-id="d7050-119">Добавление счетов с предоплатой в общую настройку учета</span><span class="sxs-lookup"><span data-stu-id="d7050-119">To add prepayment accounts to the general posting setup</span></span>  

1. <span data-ttu-id="d7050-120">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Общая настройка учета**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d7050-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Posting Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7050-121">В окне **Общая настройка учета** заполните следующие поля:</span><span class="sxs-lookup"><span data-stu-id="d7050-121">In the **General Posting Setup** window, fill in the following fields:</span></span>  

    - <span data-ttu-id="d7050-122">**Счет предоплат при продаже**</span><span class="sxs-lookup"><span data-stu-id="d7050-122">**Sales Prepayments Account**</span></span>  
    - <span data-ttu-id="d7050-123">**Счет предоплат при покупке**</span><span class="sxs-lookup"><span data-stu-id="d7050-123">**Purch. Prepayments Account**</span></span>  

## <a name="to-set-up-number-series-for-prepayment-documents"></a><span data-ttu-id="d7050-124">Настройка серии номеров для документов предоплаты</span><span class="sxs-lookup"><span data-stu-id="d7050-124">To set up number series for prepayment documents</span></span>  

1. <span data-ttu-id="d7050-125">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка модуля "Продажи"**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d7050-125">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales & Receivables Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7050-126">В окне **Настройка модуля "Продажи"** заполните следующие поля:</span><span class="sxs-lookup"><span data-stu-id="d7050-126">In the **Sales & Receivables Setup** window, fill in the following fields:</span></span>  

   - <span data-ttu-id="d7050-127">**Серия номеров учт. счетов предопл.**</span><span class="sxs-lookup"><span data-stu-id="d7050-127">**Posted Prepmt. Inv. Nos.**</span></span>
   - <span data-ttu-id="d7050-128">**Серия номеров учт. кр.-нот предопл.**</span><span class="sxs-lookup"><span data-stu-id="d7050-128">**Posted Prepmt. Cr. Memo Nos.**</span></span>

1. <span data-ttu-id="d7050-129">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка модуля "Покупки"**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d7050-129">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7050-130">В окне **Настройка модуля "Покупки"** заполните следующие поля:</span><span class="sxs-lookup"><span data-stu-id="d7050-130">In the **Purchases & Payables Setup** window, fill in the following fields:</span></span>

    - <span data-ttu-id="d7050-131">**Серия номеров учт. счетов предопл.**</span><span class="sxs-lookup"><span data-stu-id="d7050-131">**Posted Prepmt. Inv. Nos.**</span></span>
    - <span data-ttu-id="d7050-132">**Серия номеров учт. кр.-нот предопл.**</span><span class="sxs-lookup"><span data-stu-id="d7050-132">**Posted Prepmt. Cr. Memo Nos.**</span></span>

> [!NOTE]  
>  <span data-ttu-id="d7050-133">Для счетов на предоплату и обычных счетов можно использовать как одинаковые, так и разные серии номеров.</span><span class="sxs-lookup"><span data-stu-id="d7050-133">You can use the same number series for prepayment invoices and regular invoices, or you can use different number series.</span></span> <span data-ttu-id="d7050-134">При использовании разных серий они не должны перекрываться, поскольку в этих сериях не должно быть одинаковых номеров.</span><span class="sxs-lookup"><span data-stu-id="d7050-134">If you use different series, they must not overlap because there must not be any numbers that exist in both series.</span></span>  

## <a name="to-set-up-prepayment-percentages-for-items-customers-and-vendors"></a><span data-ttu-id="d7050-135">Настройка процентных значений предоплаты для товаров, клиентов и поставщиков</span><span class="sxs-lookup"><span data-stu-id="d7050-135">To set up prepayment percentages for items, customers, and vendors</span></span>  
<span data-ttu-id="d7050-136">Процент предоплаты по умолчанию для товара можно настроить для всех клиентов, для конкретного клиента или для ценовой группы клиентов.</span><span class="sxs-lookup"><span data-stu-id="d7050-136">For an item, you can set up a default prepayment percentage for all customers, a specific customer, or a customer price group.</span></span>  

1. <span data-ttu-id="d7050-137">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Товары**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d7050-137">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7050-138">Выберите товар, затем выберите действие **Проценты предоплаты**.</span><span class="sxs-lookup"><span data-stu-id="d7050-138">Select an item, and then choose the **Prepayment Percentages** action.</span></span>  
3. <span data-ttu-id="d7050-139">В окне **Проценты предоплаты при продаже**, заполните требуемые поля.</span><span class="sxs-lookup"><span data-stu-id="d7050-139">In the **Sales Prepayment Percentages** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

<span data-ttu-id="d7050-140">Для клиента или поставщика можно настроить один и тот же процент предоплаты по умолчанию для всех товаров и всех типов строк продажи.</span><span class="sxs-lookup"><span data-stu-id="d7050-140">For a customer or vendor, you can set up one default prepayment percentage for all items and all types of sales lines.</span></span> <span data-ttu-id="d7050-141">Эта данные вводятся на карточке клиента или поставщика.</span><span class="sxs-lookup"><span data-stu-id="d7050-141">You enter this on the customer or vendor card.</span></span>

1. <span data-ttu-id="d7050-142">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Клиенты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d7050-142">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7050-143">Откройте карточку для клиента.</span><span class="sxs-lookup"><span data-stu-id="d7050-143">Open the card for a customer.</span></span>
3. <span data-ttu-id="d7050-144">Заполните поле **Предоплата (%)**.</span><span class="sxs-lookup"><span data-stu-id="d7050-144">Fill in the **Prepayment %** field.</span></span>
4. <span data-ttu-id="d7050-145">Повторите шаги для других клиентов или поставщиков.</span><span class="sxs-lookup"><span data-stu-id="d7050-145">Repeat the steps for other customers or for vendors.</span></span>  

### <a name="to-determine-which-prepayment-percentage-has-first-priority"></a><span data-ttu-id="d7050-146">Определение процента предоплаты с наивысшим приоритетом</span><span class="sxs-lookup"><span data-stu-id="d7050-146">To determine which prepayment percentage has first priority</span></span>  
<span data-ttu-id="d7050-147">В заказе может быть указан процент предоплаты в заголовке продажи и различные процентные значения для товаров в строках этого заказа.</span><span class="sxs-lookup"><span data-stu-id="d7050-147">An order may have a prepayment percentage on the sales header, and a different percentage for the items on the lines.</span></span> <span data-ttu-id="d7050-148">Для определения процента предоплаты, применяемого к каждой строке продажи, система выполняет поиск процента предоплаты в указанном ниже порядке и применяет первое найденное значение по умолчанию:</span><span class="sxs-lookup"><span data-stu-id="d7050-148">To determine which prepayment percentage applies to each sale line, the system looks for the prepayment percentage in the following order and will apply the first default that it finds:</span></span>  
1. <span data-ttu-id="d7050-149">Процент предоплаты для товара данной строки и клиента, для которого создан этот заказ.</span><span class="sxs-lookup"><span data-stu-id="d7050-149">A prepayment percentage for the item on the line and the customer that the order is for.</span></span>  
2. <span data-ttu-id="d7050-150">Процент предоплаты для товара данной строки и ценовой группы клиента, для которого создан этот заказ.</span><span class="sxs-lookup"><span data-stu-id="d7050-150">A prepayment percentage for the item on the line and the customer price group that the customer belongs to.</span></span>  
3. <span data-ttu-id="d7050-151">Процент предоплаты для товара данной строки для всех клиентов.</span><span class="sxs-lookup"><span data-stu-id="d7050-151">A prepayment percentage for the item on the line for all customers.</span></span>  
4. <span data-ttu-id="d7050-152">Процент предоплаты, указанный в заголовке продажи или покупки.</span><span class="sxs-lookup"><span data-stu-id="d7050-152">The prepayment percentage on the sales or purchase header.</span></span>  

<span data-ttu-id="d7050-153">Иными словами, процент предоплаты, указанный в карточке клиента, будет применяться только в том случае, если в настройке данного товара не указаны никакие проценты предоплаты.</span><span class="sxs-lookup"><span data-stu-id="d7050-153">In other words, the prepayment percentage on the customer card will only apply if there is no prepayment percentage set up for the item.</span></span> <span data-ttu-id="d7050-154">Однако если изменить содержимое поля **Предоплата (%)** в заголовке продаж или покупки после создания строк, процент предоплаты будет обновлен во всех строках.</span><span class="sxs-lookup"><span data-stu-id="d7050-154">However, if you change the contents of the **Prepayment Percentage** field on the sales or purchase header after you create the lines, the prepayment percentage on all of the lines will be updated.</span></span> <span data-ttu-id="d7050-155">Это облегчает создание заказа с фиксированным процентом предоплаты независимо от процента, заданного для этих товаров.</span><span class="sxs-lookup"><span data-stu-id="d7050-155">This makes it easy to create an order with a fixed prepayment percentage, regardless of the percentage set up on items.</span></span>

## <a name="see-also"></a><span data-ttu-id="d7050-156">См. также</span><span class="sxs-lookup"><span data-stu-id="d7050-156">See Also</span></span>  
[<span data-ttu-id="d7050-157">Выставление счетов на предоплату</span><span class="sxs-lookup"><span data-stu-id="d7050-157">Invoicing Prepayments</span></span>](finance-invoice-prepayments.md)  
[<span data-ttu-id="d7050-158">Пошаговое руководство. Настройка и выставление счетов на продажу</span><span class="sxs-lookup"><span data-stu-id="d7050-158">Walkthrough: Setting Up and Invoicing Sales Prepayments</span></span>](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[<span data-ttu-id="d7050-159">Финансы</span><span class="sxs-lookup"><span data-stu-id="d7050-159">Finance</span></span>](finance.md)  
<span data-ttu-id="d7050-160">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="d7050-160">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
