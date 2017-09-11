---
title: "Как предложить оплаты поставщикам"
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
ms.openlocfilehash: 3ede5942798e34fd0e4b3ab8cc48ca94eed3d1a4
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="how-to-suggest-vendor-payments"></a><span data-ttu-id="88c55-102">Как предложить оплаты поставщикам</span><span class="sxs-lookup"><span data-stu-id="88c55-102">How to: Suggest Vendor Payments</span></span>
<span data-ttu-id="88c55-103">В окне **Журнал платежей** можно использовать функцию предложения строк платежей в соответствии с настройками, например, платежей, для которых скоро наступает крайний срок, или платежей, для которых доступна скидка.</span><span class="sxs-lookup"><span data-stu-id="88c55-103">In the **Payment Journal** window, you can use a function to suggest payment lines according to your settings, such as payments that are due soon or payments where a payment discount is available.</span></span>

<span data-ttu-id="88c55-104">Для достижения максимальной эффективности функции предложения оплаты поставщикам, необходимо сначала назначить приоритеты поставщикам.</span><span class="sxs-lookup"><span data-stu-id="88c55-104">To benefit fully from the Suggest Vendor Payments function, you must first prioritize your vendors.</span></span> <span data-ttu-id="88c55-105">Дополнительные сведения см. в разделе [Практическое руководство. Назначение приоритетов поставщикам](purchasing-how-prioritize-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="88c55-105">For more information, see [How to: Prioritize Vendors](purchasing-how-prioritize-vendors.md).</span></span>

<span data-ttu-id="88c55-106">Операции поставщика, которые не имеют отметки **На удержании**, не включаются в пакетное задание.</span><span class="sxs-lookup"><span data-stu-id="88c55-106">Vendor entries that are not marked **On Hold** are not included in the batch job.</span></span>  

<span data-ttu-id="88c55-107">**Внимание**. Если требуется воспользоваться скидками оплаты, и подходящая сумма уже введена, данная сумма будет использована сначала по просроченным операциям поставщиков с назначенными приоритетами в порядке приоритетов, а затем по просроченным операциям поставщиков, которым не назначены приоритеты, и, в конце концов, для открытых операций поставщиков, которые квалифицируются по скидкам оплаты в порядке номеров поставщиков.</span><span class="sxs-lookup"><span data-stu-id="88c55-107">**Important**: If you want to take advantage of payment discounts and have entered an available amount, the amount will be used for prioritized overdue vendor entries first in order of priority, and then for overdue vendor entries that are not prioritized, and finally for open vendor entries that qualify for payment discounts in order of vendor number.</span></span>

## <a name="to-use-the-suggest-vendor-payments-function"></a><span data-ttu-id="88c55-108">Использование функции предложения оплаты поставщикам</span><span class="sxs-lookup"><span data-stu-id="88c55-108">To use the Suggest Vendor Payments function</span></span>
1. <span data-ttu-id="88c55-109">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Журналы платежей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="88c55-109">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="88c55-110">Откройте соответствующий журнал, а затем выберите действие **Предлож. оплаты поставщикам**.</span><span class="sxs-lookup"><span data-stu-id="88c55-110">Open the relevant journal, and then choose the **Suggest Vendor Payments** action.</span></span>
3. <span data-ttu-id="88c55-111">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="88c55-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="88c55-112">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="88c55-112">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="88c55-113">Выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="88c55-113">Choose the **OK** button.</span></span>

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a><span data-ttu-id="88c55-114">Вставка срока оплаты в качестве даты учета в строках журнала платежей</span><span class="sxs-lookup"><span data-stu-id="88c55-114">To insert the due date as posting date on payment journal lines</span></span>
<span data-ttu-id="88c55-115">При использовании пакетного задания **Предлож. оплаты поставщикам** для создания строк платежей для поставщиков можно также заполнить два специальных поля, чтобы убедиться, что в созданных строках используется дата оплаты для вычисления даты учета.</span><span class="sxs-lookup"><span data-stu-id="88c55-115">When you use the **Suggest Vendor Payments** batch job to create payment lines for your vendors, you can fill two special fields to make sure that the generated lines use the due date to calculate the posting date.</span></span> <span data-ttu-id="88c55-116">Это поля **Рассчитать дату учета на основе срока оплаты примен. документа** и **Примен. смещения срока оплаты документа**.</span><span class="sxs-lookup"><span data-stu-id="88c55-116">These fields are **Calculate Posting Date from Applies-to-Doc Due Date** and **Applies-to-Doc Due Date Offset**.</span></span>

<span data-ttu-id="88c55-117">**Внимание**. Невозможно использовать поле **Рассчитать дату учета на основе срока оплаты примен. документа** вместе с полем **Найти скидки оплаты** или **Суммировать по поставщикам**.</span><span class="sxs-lookup"><span data-stu-id="88c55-117">**Important**: You cannot use the **Calculate Posting Date from Applies-to-Doc Due Date** field together with the **Find Payment Discounts** field or the **Summarize per Vendor** field.</span></span> <span data-ttu-id="88c55-118">Причина в том, что если дата учета основана на дате оплаты, некоторая скидка на оплату может вычисляться неверно, потому что дата учета следует после даты скидки по платежу.</span><span class="sxs-lookup"><span data-stu-id="88c55-118">The reason is that if the posting date is based on the due date, then some payment discount may not be calculated correctly, because the posting date could occur after the payment discount date.</span></span>
<span data-ttu-id="88c55-119">Кроме того, если расчетная дата учета уже прошла, дата учета будет изменена на рабочую дату и отобразится предупреждение.</span><span class="sxs-lookup"><span data-stu-id="88c55-119">Also, if the calculated posting date occurs in the past, then the posting date will be moved up to the work date, and a warning is displayed.</span></span>

<span data-ttu-id="88c55-120">Кроме того, можно вручную создать строки платежа с использованием срока оплаты для вычисления даты учета.</span><span class="sxs-lookup"><span data-stu-id="88c55-120">Alternatively, you can also manually create payment lines using the due date to calculate the posting date.</span></span> <span data-ttu-id="88c55-121">После применения операций книге поставщиков можно использовать действие **Расчет даты учета**.</span><span class="sxs-lookup"><span data-stu-id="88c55-121">After you have applied vendor ledger entries, you can use the **Calculate Posting Date** action.</span></span> <span data-ttu-id="88c55-122">Дата учета в строке журнала будет обновлена до срока оплаты соответствующего счета покупки.</span><span class="sxs-lookup"><span data-stu-id="88c55-122">This will update the posting date on the journal line with the due date of the related purchase invoice.</span></span> <span data-ttu-id="88c55-123">Дополнительные сведения см. в разделе [Практическое руководство. Применение транзакций платежей вручную](payables-how-apply-purchase-transactions-manually.md).</span><span class="sxs-lookup"><span data-stu-id="88c55-123">For more information, see [How to: Apply Purchase Transactions Manually](payables-how-apply-purchase-transactions-manually.md).</span></span>  

<span data-ttu-id="88c55-124">**Примечание**. Если счет покупки просрочен, в качестве даты учета устанавливается рабочая дата и цвет шрифта в строке меняется на красный.</span><span class="sxs-lookup"><span data-stu-id="88c55-124">**Note**: If the purchase invoice is overdue, then the posting date will be set to the work date, and the font on the line will change to red color.</span></span>

## <a name="see-also"></a><span data-ttu-id="88c55-125">См. также</span><span class="sxs-lookup"><span data-stu-id="88c55-125">See Also</span></span>
[<span data-ttu-id="88c55-126">Управление кредиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="88c55-126">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="88c55-127">Осуществление платежей</span><span class="sxs-lookup"><span data-stu-id="88c55-127">Make Payments</span></span>](payables-make-payments.md)  
[<span data-ttu-id="88c55-128">Работа с финансовыми журналами</span><span class="sxs-lookup"><span data-stu-id="88c55-128">Work with General Journals</span></span>](ui-work-general-journals.md)

