---
title: "Как создавать счета на предоплату"
description: "Узнайте, как обрабатывать ситуации, в которых вы или ваш поставщик требует предоплату."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a5480e9a4ad332a5faf668cc53ea7a750cfa0e17
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-prepayment-invoices"></a><span data-ttu-id="e12d8-103">Практическое руководство. Создание счетов на предоплату</span><span class="sxs-lookup"><span data-stu-id="e12d8-103">How to: Create Prepayment Invoices</span></span>
<span data-ttu-id="e12d8-104">Если требуется, чтобы клиенты осуществляли платежи до отгрузки им заказов, или если аналогичное требование выдвигают поставщики в отношении вашей организации, можно использовать функцию предоплаты.</span><span class="sxs-lookup"><span data-stu-id="e12d8-104">If you require your customers to submit payment before you ship an order to them, or if your vendor requires you to submit payment before they ship an order to you, you can use the prepayment functionality.</span></span>  

<span data-ttu-id="e12d8-105">После создания заказов продажи или покупки можно создать счет на предоплату.</span><span class="sxs-lookup"><span data-stu-id="e12d8-105">After you create a sales or purchase order, you can create a prepayment invoice.</span></span> <span data-ttu-id="e12d8-106">Можно использовать процентные значения по умолчанию для каждой строки продажи или покупки, а также можно корректировать сумму по мере необходимости.</span><span class="sxs-lookup"><span data-stu-id="e12d8-106">You can use the default percentages for each sales or purchase line, or you can adjust the amount as necessary.</span></span> <span data-ttu-id="e12d8-107">Например, можно указать общую сумму для всего заказа.</span><span class="sxs-lookup"><span data-stu-id="e12d8-107">For example, you can specify a total amount for the entire order.</span></span>  

<span data-ttu-id="e12d8-108">В следующей процедуре описывается, как выставлять счета на предоплату для заказов на продажу.</span><span class="sxs-lookup"><span data-stu-id="e12d8-108">The following procedure describes how to invoice a prepayment for a sales orders.</span></span> <span data-ttu-id="e12d8-109">Действия для заказов на покупку аналогичны.</span><span class="sxs-lookup"><span data-stu-id="e12d8-109">The steps are similar for purchase orders.</span></span>  

## <a name="to-create-a-prepayment-invoice"></a><span data-ttu-id="e12d8-110">Процедура создания счета на предоплату</span><span class="sxs-lookup"><span data-stu-id="e12d8-110">To create a prepayment invoice</span></span>  
1. <span data-ttu-id="e12d8-111">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказы на продажу**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e12d8-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2. <span data-ttu-id="e12d8-112">Создайте новый заказ на продажу.</span><span class="sxs-lookup"><span data-stu-id="e12d8-112">Create a new sales order.</span></span> <span data-ttu-id="e12d8-113">Дополнительные сведения см. в разделе [Практическое руководство. Продажа продукции](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="e12d8-113">For more information, see [How to: sell Products](sales-how-sell-products.md).</span></span>  

    <span data-ttu-id="e12d8-114">На экспресс-вкладке **Предоплата** поле **Предоплата (%)** будет заполнено автоматически, если в карточке клиента указан процент предоплаты по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="e12d8-114">On the **Prepayment** FastTab, the **Prepayment %** field will be filled in automatically if there is a default prepayment percentage on the customer card.</span></span> <span data-ttu-id="e12d8-115">Содержимое этого поля можно изменить.</span><span class="sxs-lookup"><span data-stu-id="e12d8-115">You can change the contents of the field.</span></span> <span data-ttu-id="e12d8-116">Процент предоплаты копируется из заголовка только в те строки, куда не скопирован процент предоплаты по умолчанию для данного товара.</span><span class="sxs-lookup"><span data-stu-id="e12d8-116">The prepayment percentage is only copied from the header to lines that do not copy the default prepayment percentage from the item.</span></span>  

    <span data-ttu-id="e12d8-117">Если выбрано поле **Сжать предоплату**, строки будут объединены в счете, если:</span><span class="sxs-lookup"><span data-stu-id="e12d8-117">If the **Compress Prepayment** field is selected, lines will be combined on the invoice if:</span></span>  
    - <span data-ttu-id="e12d8-118">Они имеют один и тот же счет главной книги для учета предоплаты, что определяется общей настройкой учета.</span><span class="sxs-lookup"><span data-stu-id="e12d8-118">They have the same general ledger account for prepayments as determined by the general posting setup.</span></span>  
    - <span data-ttu-id="e12d8-119">Они имеют одинаковые измерения.</span><span class="sxs-lookup"><span data-stu-id="e12d8-119">They have the same dimensions.</span></span>  

    <span data-ttu-id="e12d8-120">Оставьте это поле пустым, если требуется определить счет на предоплату с отдельным строками для каждой строки заказа продажи, которая имеет процент предоплаты.</span><span class="sxs-lookup"><span data-stu-id="e12d8-120">Leave the field blank if you want to specify a prepayment invoice with one line for each sales order line that has a prepayment percentage.</span></span>  

3. <span data-ttu-id="e12d8-121">Заполните строки продажи.</span><span class="sxs-lookup"><span data-stu-id="e12d8-121">Fill in the sales lines.</span></span>  

    <span data-ttu-id="e12d8-122">Если для товаров был задан процент предоплаты по умолчанию, они автоматически копируются в поле **Предоплата (%)** данной строки.</span><span class="sxs-lookup"><span data-stu-id="e12d8-122">If default prepayment percentages have been set up for your items, they are automatically copied to the **Prepayment %** field on the line.</span></span> <span data-ttu-id="e12d8-123">В противном случае процент предоплаты копируется из заголовка.</span><span class="sxs-lookup"><span data-stu-id="e12d8-123">Otherwise, the prepayment percentage is copied from the header.</span></span> <span data-ttu-id="e12d8-124">Можно изменить содержимое поля **Предоплата (%)** в строке.</span><span class="sxs-lookup"><span data-stu-id="e12d8-124">You can change the contents of the **Prepayment %** field on the line.</span></span>  
4. <span data-ttu-id="e12d8-125">Если необходимо применить один и тот же процент предоплаты ко всему заказу, после заполнения строк измените поле **Предоплата (%)** в заголовке.</span><span class="sxs-lookup"><span data-stu-id="e12d8-125">If you want to apply one prepayment percentage to the entire order, change the **Prepayment %** field on the header after filling in the lines.</span></span>  
5. <span data-ttu-id="e12d8-126">Для просмотра общей суммы предоплаты выберите действие **Статистика**.</span><span class="sxs-lookup"><span data-stu-id="e12d8-126">To view the total prepayment amount, choose the **Statistics** action.</span></span>

    <span data-ttu-id="e12d8-127">Если необходимо скорректировать сумму предоплаты для данного заказа, можно изменить содержимое поля **Сумма предоплаты** в окне **Статистика заказов на продажу**.</span><span class="sxs-lookup"><span data-stu-id="e12d8-127">If you want to adjust the total prepayment amount for the order, you can change the contents of the **Prepayment Amount** field in the **Sales Order Statistics** window.</span></span>  

    <span data-ttu-id="e12d8-128">Если выбрано поле **Цены с учетом НДС**, а поле **Сумма предоплаты включая НДС** доступно для редактирования.</span><span class="sxs-lookup"><span data-stu-id="e12d8-128">If the **Prices Including VAT** field is selected, the **Prepayment Amount Incl. VAT** field is editable.</span></span>  

    <span data-ttu-id="e12d8-129">При изменении значения поля **Сумма предоплаты** данная сумма будет пропорционально распределяться между всеми строками, за исключением тех строк, у которых значение поля **Предоплата (%)** равно **0**.</span><span class="sxs-lookup"><span data-stu-id="e12d8-129">If you change the contents of the **Prepayment Amount** field, the amount will be distributed proportionately between all lines, except those that have **0** in the **Prepayment %** field.</span></span>  
6. <span data-ttu-id="e12d8-130">Чтобы напечатать тестовый отчет перед учетом счета на предоплату, выберите действие **Предоплата**, затем выберите действие **Тестовый отчет о предоплате**.</span><span class="sxs-lookup"><span data-stu-id="e12d8-130">To print a test report before posting the prepayment invoice, choose the **Prepayment** action, and then choose the **Prepayment Test Report** action.</span></span>  
7. <span data-ttu-id="e12d8-131">Чтобы учесть счет на предоплату, выберите действие **Предоплата**, затем выберите действие **Учет счета на предоплату**.</span><span class="sxs-lookup"><span data-stu-id="e12d8-131">To post the prepayment invoice, choose the **Prepayment** action, and then choose the **Post Prepayment Invoice** action.</span></span>  

    <span data-ttu-id="e12d8-132">Чтобы учесть и распечатать счет на предоплату, выберите действие **Учет и печать счета на предоплату**.</span><span class="sxs-lookup"><span data-stu-id="e12d8-132">To post and print the prepayment invoice, choose the **Post and Print Prepmt. Invoice** action.</span></span>  

<span data-ttu-id="e12d8-133">Для данного заказа можно создать дополнительные счета на предоплату.</span><span class="sxs-lookup"><span data-stu-id="e12d8-133">You can issue additional prepayment invoices for the order.</span></span> <span data-ttu-id="e12d8-134">Для этого необходимо увеличить сумму предоплаты в одной или нескольких строках, скорректировать дату в случае необходимости и учесть счет на предоплату.</span><span class="sxs-lookup"><span data-stu-id="e12d8-134">To do this, increase the prepayment amount on one or more lines, adjust the document date if necessary, and post the prepayment invoice.</span></span> <span data-ttu-id="e12d8-135">Новый счет будет создан на сумму разницы между суммами предоплаты, уже включенными в счет, и новой суммой предоплаты.</span><span class="sxs-lookup"><span data-stu-id="e12d8-135">A new invoice will be created for the difference between the prepayment amounts invoiced so far and the new prepayment amount.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e12d8-136">Если вы расположены в Северной Америке, вы не можете изменить процент предоплаты после учета счета на предоплату.</span><span class="sxs-lookup"><span data-stu-id="e12d8-136">If you are located in North America, you cannot change the prepayment percentage after the prepayment invoice has been posted.</span></span> <span data-ttu-id="e12d8-137">Это запрещено в североамериканской версии [!INCLUDE[d365fin](includes/d365fin_md.md)], поскольку в противном случае расчет налога будет неверным.</span><span class="sxs-lookup"><span data-stu-id="e12d8-137">This is prevented in the North American version of [!INCLUDE[d365fin](includes/d365fin_md.md)] because the calculation of sales tax will otherwise be incorrect.</span></span>  

 <span data-ttu-id="e12d8-138">Когда все готово для учета остатка по счету, его учет выполняется так же, как и учет любого счета, а сумма предоплаты автоматически вычитается из причитающейся суммы.</span><span class="sxs-lookup"><span data-stu-id="e12d8-138">When you are ready to post the rest of the invoice, post it as you would post any invoice, and the prepayment amount will automatically be deducted from the amount due.</span></span>  

## <a name="see-also"></a><span data-ttu-id="e12d8-139">См. также</span><span class="sxs-lookup"><span data-stu-id="e12d8-139">See Also</span></span>  
[<span data-ttu-id="e12d8-140">Выставление счетов на предоплату</span><span class="sxs-lookup"><span data-stu-id="e12d8-140">Invoicing Prepayments</span></span>](finance-invoice-prepayments.md)  
[<span data-ttu-id="e12d8-141">Пошаговое руководство. Настройка и выставление счетов на продажу</span><span class="sxs-lookup"><span data-stu-id="e12d8-141">Walkthrough: Setting Up and Invoicing Sales Prepayments</span></span>](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[<span data-ttu-id="e12d8-142">Финансы</span><span class="sxs-lookup"><span data-stu-id="e12d8-142">Finance</span></span>](finance.md)  
<span data-ttu-id="e12d8-143">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="e12d8-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

