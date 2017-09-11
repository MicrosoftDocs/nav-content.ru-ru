---
title: "Управление банковскими счетами."
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
ms.openlocfilehash: d97c3afba0e899768bda1b637c4f288db210d38c
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="manage-bank-accounts"></a><span data-ttu-id="f2e2a-102">Управление банковскими счетами.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-102">Manage Bank Accounts</span></span>
<span data-ttu-id="f2e2a-103">Через равные промежутки времени вы должны выверять банковские счета в Dynamics NAV с соответствующими банковскими транзакциями на счетах в вашем банке, а затем учитывать сальдо на своем банковскому счете.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-103">At regular intervals, you must reconcile your bank ledger entries in Dynamics NAV with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="f2e2a-104">Эту задачу можно выполнить в рамках обработки платежей, представленных в банковской выписке в **Журнале выверки платежей**.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-104">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="f2e2a-105">Кроме того, можно выполнить задачу отдельно от обработки платежей, в окне **Выверка банковского счета**, которое поддерживает книгу платежных документов.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-105">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="f2e2a-106">В обоих случаях вы заполняете окна путем импорт банковской выписки в Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-106">In both cases, you fill the windows by importing the bank statement into Dynamics NAV.</span></span>

<span data-ttu-id="f2e2a-107">Иногда необходимо переводить суммы между банковским счетом в Dynamics NAV для отражения переводов в банке.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-107">Sometimes, you need to transfer amounts between bank account in Dynamics NAV to reflect transfers at your bank.</span></span> <span data-ttu-id="f2e2a-108">Эта задача выполняется в окне **Финансовый журнал** разными способами в зависимости от валюты фондов.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-108">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="f2e2a-109">Прежде чем управлять банковскими счетами, следует настроить каждый банковский счет в качестве карточки банковского счета.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-109">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="f2e2a-110">Кроме того, необходимо настроить электронные службы, которые можно использовать для импорта банковских выписок и экспорта файлов платежей.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-110">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="f2e2a-111">Дополнительные сведения см. в разделе [Настройка банковских счетов](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="f2e2a-111">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="f2e2a-112">В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="f2e2a-113">Действие</span><span class="sxs-lookup"><span data-stu-id="f2e2a-113">To</span></span> |<span data-ttu-id="f2e2a-114">Ссылка</span><span class="sxs-lookup"><span data-stu-id="f2e2a-114">See</span></span> |
|---|----|
|<span data-ttu-id="f2e2a-115">Выверка банковских счетов в связи с обработкой платежей в окне **Журнал выверки платежей**.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-115">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span>|[<span data-ttu-id="f2e2a-116">Автоматическое применение платежей и выверка банковских счетов</span><span class="sxs-lookup"><span data-stu-id="f2e2a-116">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|<span data-ttu-id="f2e2a-117">Выверка банковских счетов, включая операции книги платежных документов, как отдельная задача в окне **Выверка банковского счета**.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-117">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span>|[<span data-ttu-id="f2e2a-118">Практическое руководство. Выверка банковских счетов по отдельности</span><span class="sxs-lookup"><span data-stu-id="f2e2a-118">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md)|
|<span data-ttu-id="f2e2a-119">Учет переводов между банковскими счетами в одной валюте или в различных валютах.</span><span class="sxs-lookup"><span data-stu-id="f2e2a-119">Post transfers between bank accounts in the same currency or in different currencies.</span></span>|[<span data-ttu-id="f2e2a-120">Практическое руководство. Перевод банковских средств</span><span class="sxs-lookup"><span data-stu-id="f2e2a-120">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md)
## <a name="see-also"></a><span data-ttu-id="f2e2a-121">См. также</span><span class="sxs-lookup"><span data-stu-id="f2e2a-121">See Also</span></span>  
[<span data-ttu-id="f2e2a-122">Настройка банка</span><span class="sxs-lookup"><span data-stu-id="f2e2a-122">Set Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="f2e2a-123">Управление дебиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="f2e2a-123">Manage Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="f2e2a-124">[Управление кредиторской задолженностью](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="f2e2a-124">[Manage Payables](payables-manage-payables.md)  </span></span>  
[<span data-ttu-id="f2e2a-125">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="f2e2a-125">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="f2e2a-126">Функции, доступные в различных деловых областях</span><span class="sxs-lookup"><span data-stu-id="f2e2a-126">Across Business Areas</span></span>](ui-across-business-areas.md)

