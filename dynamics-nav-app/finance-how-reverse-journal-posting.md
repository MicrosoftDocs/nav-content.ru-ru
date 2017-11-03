---
title: "Отмена учета путем учета сторнирующей операции"
description: "Если выполнен ошибочный учет в финансовом журнале, можно воспользоваться функцией сторнирования транзакции, чтобы отменить учет, сохранив корректный след аудита."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reimbursement
ms.date: 08/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 2970914c36f892a5610509e9dc4015d0fb159642
ms.contentlocale: ru-ru
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-reverse-postings"></a><span data-ttu-id="15798-103">Практическое руководство. Сторнирование учета</span><span class="sxs-lookup"><span data-stu-id="15798-103">How to: Reverse Postings</span></span>
<span data-ttu-id="15798-104">Что отменить ошибочную проводку в журнале, выберите операцию и создайте сторнирующую операцию (операции, идентичные исходным, но с противоположным знаком в поле суммы) с таким же номером документа и датой учета, что и у исходной операции.</span><span class="sxs-lookup"><span data-stu-id="15798-104">To undo an erroneous journal posting, you select the entry and create a reverse entry (entries identical to the original entry but with opposite sign in the amount field) with the same document number and posting date as the original entry.</span></span> <span data-ttu-id="15798-105">После сторнирования операции необходимо создать корректирующую запись.</span><span class="sxs-lookup"><span data-stu-id="15798-105">After reversing an entry, you must make the correct entry.</span></span>

<span data-ttu-id="15798-106">Можно сторнировать только те операции, которые были учтены из строки финансового журнала.</span><span class="sxs-lookup"><span data-stu-id="15798-106">You can only reverse entries that are posted from a general journal line.</span></span> <span data-ttu-id="15798-107">Операцию можно сторнировать только один раз.</span><span class="sxs-lookup"><span data-stu-id="15798-107">An entry can only be reversed once.</span></span>

<span data-ttu-id="15798-108">Дополнительные сведения об учете из финансового журнала, см. в разделе [Практическое руководство. Учет транзакций непосредственно в главной книге](finance-how-post-transactions-directly.md).</span><span class="sxs-lookup"><span data-stu-id="15798-108">For more information about posting from a general journal, see [How to: Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md).</span></span>

<span data-ttu-id="15798-109">В случае учета неправильного отрицательного количества, например если сделан заказ покупки с неправильным числом товаров, и принят к учету как полученный (но без выставления счета), то эту операцию можно отменить.</span><span class="sxs-lookup"><span data-stu-id="15798-109">If you have made an incorrect negative quantity posting, such as a purchase order with the wrong number of items and posted it as received but not invoiced, then you can undo the posting.</span></span>

<span data-ttu-id="15798-110">В случае учета неправильного положительного количества, например если сделан заказ возврата покупки с неправильным числом товаров, и принят к учету как отгруженный (но без выставления счета), то эту операцию можно отменить.</span><span class="sxs-lookup"><span data-stu-id="15798-110">If you have made an incorrect positive quantity posting, such as a purchase return order with the wrong number of items and posted it as shipped but not invoiced, then you can undo the posting.</span></span>   

## <a name="to-reverse-the-journal-posting-of-a-general-ledger-entry"></a><span data-ttu-id="15798-111">Сторнирование учета в журнале для операции главной книги</span><span class="sxs-lookup"><span data-stu-id="15798-111">To reverse the journal posting of a general ledger entry</span></span>
<span data-ttu-id="15798-112">Операции можно сторнировать из всех окон **Книга операций**.</span><span class="sxs-lookup"><span data-stu-id="15798-112">You can reverse entries from all **Ledger Entries** windows.</span></span> <span data-ttu-id="15798-113">Следующая процедура основана на окне **Операции главной книги**.</span><span class="sxs-lookup"><span data-stu-id="15798-113">The following procedure is based on the **General Ledger Entries** window.</span></span>
1. <span data-ttu-id="15798-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Операции главной книги**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="15798-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Entries**, and then choose the related link.</span></span>
2. <span data-ttu-id="15798-115">Выберите операцию, которую требуется сторнировать, а затем выберите **Сторнировать транзакцию**.</span><span class="sxs-lookup"><span data-stu-id="15798-115">Select the entry that you want to reverse, and then choose the **Reverse Transaction** action.</span></span> <span data-ttu-id="15798-116">Следует отметить, что операцию нужно выполнять из учтенной операции в журнале.</span><span class="sxs-lookup"><span data-stu-id="15798-116">Note that is must originate from a journal posting.</span></span>
3. <span data-ttu-id="15798-117">В окне **Сторнировать операции транзакции** выберите соответствующую операцию, а затем выберите действие **Сторнировать**.</span><span class="sxs-lookup"><span data-stu-id="15798-117">In the **Reverse Transaction Entries** window, select the relevant entry, and then choose the **Reverse** action.</span></span>
4. <span data-ttu-id="15798-118">Нажмите кнопку **Да** в сообщении подтверждения.</span><span class="sxs-lookup"><span data-stu-id="15798-118">Choose the **Yes** button on the confirmation message.</span></span>

## <a name="to-undo-a-quantity-posting-on-a-posted-purchase-receipt"></a><span data-ttu-id="15798-119">Отмена учета количества в учтенной приходной накладной покупки</span><span class="sxs-lookup"><span data-stu-id="15798-119">To undo a quantity posting on a posted purchase receipt</span></span>  

1.  <span data-ttu-id="15798-120">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Учтенные приходные накладные покупки**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="15798-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Receipts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="15798-121">Откройте учтенную приемку, которую нужно отменить.</span><span class="sxs-lookup"><span data-stu-id="15798-121">Open the posted receipt that you want to undo.</span></span>  
3.  <span data-ttu-id="15798-122">Выберите строку или строки, которые нужно отменить.</span><span class="sxs-lookup"><span data-stu-id="15798-122">Select the line or lines that you want to undo.</span></span>  
4.  <span data-ttu-id="15798-123">Выберите действие **Отменить прих. накладную**.</span><span class="sxs-lookup"><span data-stu-id="15798-123">Choose **Undo Receipt** action.</span></span>

    <span data-ttu-id="15798-124">Корректирующая строка вставляется под выбранной строкой приходной накладной.</span><span class="sxs-lookup"><span data-stu-id="15798-124">A corrective line is inserted under the selected receipt line.</span></span>  

    <span data-ttu-id="15798-125">Если количество получено в складской приемке, то в учтенную складскую приемку вставлена корректирующая строка.</span><span class="sxs-lookup"><span data-stu-id="15798-125">If the quantity was received in a warehouse receipt, then a corrective line is inserted in the posted warehouse receipt.</span></span>  

    <span data-ttu-id="15798-126">Значения в полях **Полученное кол-во** и **Получ. кол-во без выст. счета** в соответствующем заказе на покупку сводятся к нулю.</span><span class="sxs-lookup"><span data-stu-id="15798-126">The **Quantity Received** and **Qty. Rcd. Not Invoiced** fields on the related purchase order are set to zero.</span></span>

## <a name="to-undo-and-then-redo-a-quantity-posting-on-a-posted-return-shipment"></a><span data-ttu-id="15798-127">Отмена учета и последующий повторный учет количества в учтенной расходной накладной по возврату</span><span class="sxs-lookup"><span data-stu-id="15798-127">To undo and then redo a quantity posting on a posted return shipment</span></span>

1.  <span data-ttu-id="15798-128">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Учтенные возвр. расх. накладные**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="15798-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Return Shipments**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="15798-129">Откройте учтенную возвратную расходную накладную, которую нужно отменить.</span><span class="sxs-lookup"><span data-stu-id="15798-129">Open the posted return shipment that you want to undo.</span></span>
3. <span data-ttu-id="15798-130">Выберите строку или строки, которые нужно отменить.</span><span class="sxs-lookup"><span data-stu-id="15798-130">Select the line or lines you want to undo.</span></span>  

4.  <span data-ttu-id="15798-131">Выберите действие **Отменить возвр. расх. накладную**.</span><span class="sxs-lookup"><span data-stu-id="15798-131">Choose the **Undo Return Shipment** action.</span></span>  

    <span data-ttu-id="15798-132">В учтенный документ вставляется корректирующая строка, а поля **Отгруженное кол-во возвр.** и **Возврат, отгруженный без выст. счета** в заказе на возврат устанавливаются равными нулю.</span><span class="sxs-lookup"><span data-stu-id="15798-132">A corrective line is inserted in the posted document, and the **Return Qty. Shipped** and **Return Shpd. Not Invd.** fields on the return order are set to zero.</span></span>  

    <span data-ttu-id="15798-133">Теперь вернитесь в окно возврата покупки, чтобы переделать учет.</span><span class="sxs-lookup"><span data-stu-id="15798-133">Now go back to the purchase return order to redo the posting.</span></span>  

5.  <span data-ttu-id="15798-134">В окне **Учтенная возвр. расх. накладная** запомните номер в поле **Номер возврата**.</span><span class="sxs-lookup"><span data-stu-id="15798-134">In the **Posted Return Shipment** window, take a note of the number in the **Return Order No.**</span></span> <span data-ttu-id="15798-135">.</span><span class="sxs-lookup"><span data-stu-id="15798-135">field.</span></span>  
6.  <span data-ttu-id="15798-136">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Возвраты покупок**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="15798-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Orders**, and then choose the related link.</span></span>  
7.  <span data-ttu-id="15798-137">Откройте требуемый заказ на возврат, затем выберите действие **Открыть повторно**.</span><span class="sxs-lookup"><span data-stu-id="15798-137">Open the return order in question, and then choose the **Reopen** action.</span></span>  
8.  <span data-ttu-id="15798-138">Исправьте запись в поле **Кол-во** и снова выполните учет возврата покупки.</span><span class="sxs-lookup"><span data-stu-id="15798-138">Correct the entry in the **Quantity** field and post the purchase return order again.</span></span>  

## <a name="see-also"></a><span data-ttu-id="15798-139">См. также</span><span class="sxs-lookup"><span data-stu-id="15798-139">See Also</span></span>
<span data-ttu-id="15798-140">[Практическое руководство. Учет транзакций непосредственно в главной книге](finance-how-post-transactions-directly.md).</span><span class="sxs-lookup"><span data-stu-id="15798-140">[How to: Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md)</span></span>  
[<span data-ttu-id="15798-141">Работа с финансовыми журналами</span><span class="sxs-lookup"><span data-stu-id="15798-141">Working with General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="15798-142">Финансы</span><span class="sxs-lookup"><span data-stu-id="15798-142">Finance</span></span>](finance.md)  
<span data-ttu-id="15798-143">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="15798-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

