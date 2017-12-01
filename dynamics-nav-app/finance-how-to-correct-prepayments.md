---
title: "Как корректировать предоплаты"
description: "Можно скорректировать заказ после учета счета на предоплату по данному заказу. Можно добавить новые строки в заказ после выставления счета на предоплату, после чего можно учесть другой счет на предоплату, но невозможно удалить строку из заказа после того, как по этой строке был выставлен счет на предоплату."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 3bd8e6cfd4b0309d74340840e416979021a55393
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-correct-prepayments"></a><span data-ttu-id="6fda0-104">Практическое руководство. Корректировка предоплат</span><span class="sxs-lookup"><span data-stu-id="6fda0-104">How to: Correct Prepayments</span></span>
<span data-ttu-id="6fda0-105">Можно скорректировать заказ после учета счета на предоплату по данному заказу.</span><span class="sxs-lookup"><span data-stu-id="6fda0-105">You can make a correction to an order after you have posted a prepayment invoice for the order.</span></span> <span data-ttu-id="6fda0-106">Можно добавить новые строки в заказ после выставления счета на предоплату, после чего можно учесть другой счет на предоплату, но невозможно удалить строку из заказа после того, как по этой строке был выставлен счет на предоплату.</span><span class="sxs-lookup"><span data-stu-id="6fda0-106">You can add new lines to an order after issuing a prepayment, and then you can post another prepayment invoice, but you cannot delete a line from an order after a prepayment has been invoiced for the line.</span></span>  

## <a name="to-correct-a-prepayment"></a><span data-ttu-id="6fda0-107">Корректировка предоплаты</span><span class="sxs-lookup"><span data-stu-id="6fda0-107">To correct a prepayment</span></span>
<span data-ttu-id="6fda0-108">Приведенная ниже процедура показывает, как создать кредит-ноту предоплаты, чтобы отменить все предоплаты, по которым выставлены счета, для заказа на продажу.</span><span class="sxs-lookup"><span data-stu-id="6fda0-108">The following procedure shows how to issue a prepayment credit memo to cancel all invoiced prepayments for a sales order.</span></span>  
1. <span data-ttu-id="6fda0-109">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказы на продажу**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="6fda0-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6fda0-110">Откройте соответствующий заказ на продажу.</span><span class="sxs-lookup"><span data-stu-id="6fda0-110">Open the relevant sales order.</span></span>
3. <span data-ttu-id="6fda0-111">Выберите действие **Предоплата**, затем выберите **Учет кредит-ноты на предоплату** или **Учет и печать кредит-ноты на предоплату**.</span><span class="sxs-lookup"><span data-stu-id="6fda0-111">Choose the **Prepayment** action, and then choose the **Post Prepayment Credit Memo** action or the **Post and Print Prepmt. Cr. Memo** action.</span></span>  
4. <span data-ttu-id="6fda0-112">В окне **Кредит-нота продажи** исправьте соответствующие операции, как и для любой кредит-ноты продажи.</span><span class="sxs-lookup"><span data-stu-id="6fda0-112">In the **Sales Credit Memo** window, proceed to correct the relevant entries, as for any sales credit memo.</span></span> <span data-ttu-id="6fda0-113">Дополнительные сведения см. в разделе [Практическое руководство. Обработка возвратов продажи или отмен](sales-how-process-sales-returns-cancellations.md)</span><span class="sxs-lookup"><span data-stu-id="6fda0-113">For more information, see [How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).</span></span>     

    > [!NOTE]  
    > <span data-ttu-id="6fda0-114">Чтобы уменьшить сумму в поле **Сумма строки**, сначала необходимо увеличить процент предоплаты в данной строке, чтобы значение в поле **Сумма в строке предоплаты** не становилась меньше значения в поле **Сумм. предопл. для выст. счета**.</span><span class="sxs-lookup"><span data-stu-id="6fda0-114">To Reduce the amount in the **Line Amount** field, you must first increase the prepayment percentage on the line so that the value in the **Prepmt. Line Amount** field is not decreased below the value in the **Prepmt. Amt. Inv.** field.</span></span>

5. <span data-ttu-id="6fda0-115">Чтобы создать счет на предоплату для любых новых строк в кредит-ноте продажи, выберите действие **Предоплата**, затем выберите действие **Учет счета на предоплату** или **Учет и печать счета на предоплату**.</span><span class="sxs-lookup"><span data-stu-id="6fda0-115">To make a prepayment invoice for any new lines in the sales credit memo, choose the **Prepayment** action, and then choose the **Post Prepayment Invoice** action or the **Post and Print Prepmt. Invoice** action.</span></span>  
6. <span data-ttu-id="6fda0-116">Чтобы создать дополнительный счет на предоплату, увеличьте сумму предоплаты в одной или нескольких строках и выполните учет счета на предоплату.</span><span class="sxs-lookup"><span data-stu-id="6fda0-116">To issue an additional prepayment invoice, increase the prepayment amount on one or more lines and post the prepayment invoice.</span></span> <span data-ttu-id="6fda0-117">Новый счет будет создан на сумму разницы между суммами предоплаты, уже включенными в счет, и новыми суммами предоплаты.</span><span class="sxs-lookup"><span data-stu-id="6fda0-117">A new invoice will be created for the difference between the prepayment amounts invoiced and the new prepayment amounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6fda0-118">См. также</span><span class="sxs-lookup"><span data-stu-id="6fda0-118">See Also</span></span>  
[<span data-ttu-id="6fda0-119">Выставление счетов на предоплату</span><span class="sxs-lookup"><span data-stu-id="6fda0-119">Invoicing Prepayments</span></span>](finance-invoice-prepayments.md)  
[<span data-ttu-id="6fda0-120">Пошаговое руководство. Настройка и выставление счетов на продажу</span><span class="sxs-lookup"><span data-stu-id="6fda0-120">Walkthrough: Setting Up and Invoicing Sales Prepayments</span></span>](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[<span data-ttu-id="6fda0-121">Финансы</span><span class="sxs-lookup"><span data-stu-id="6fda0-121">Finance</span></span>](finance.md)  
<span data-ttu-id="6fda0-122">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="6fda0-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

