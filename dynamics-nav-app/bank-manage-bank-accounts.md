---
title: "Управление банковскими счетами."
description: "Вы должны регулярно выверять операции банковских книг в Dynamics NAV с соответствующими банковскими транзакциями на банковских счетах."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reconcile
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2d8d3f24010181e35c491dcdacfbcf13a655014f
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="managing-bank-accounts"></a><span data-ttu-id="69699-103">Управление банковскими счетами</span><span class="sxs-lookup"><span data-stu-id="69699-103">Managing Bank Accounts</span></span>
<span data-ttu-id="69699-104">Через равные промежутки времени вы должны выверять банковские счета в [!INCLUDE[d365fin](includes/d365fin_md.md)] с соответствующими банковскими транзакциями на счетах в вашем банке, а затем учитывать сальдо на своем банковском счете.</span><span class="sxs-lookup"><span data-stu-id="69699-104">At regular intervals, you must reconcile your bank ledger entries in [!INCLUDE[d365fin](includes/d365fin_md.md)] with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="69699-105">Эту задачу можно выполнить в рамках обработки платежей, представленных в банковской выписке в **Журнале выверки платежей**.</span><span class="sxs-lookup"><span data-stu-id="69699-105">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="69699-106">Кроме того, можно выполнить задачу отдельно от обработки платежей, в окне **Выверка банковского счета**, которое поддерживает книгу платежных документов.</span><span class="sxs-lookup"><span data-stu-id="69699-106">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="69699-107">В обоих случаях вы заполняете окна путем импорта банковской выписки в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="69699-107">In both cases, you fill in the windows by importing the bank statement into [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

<span data-ttu-id="69699-108">Иногда необходимо переводить суммы между банковским счетом в [!INCLUDE[d365fin](includes/d365fin_md.md)] для отражения переводов в банке.</span><span class="sxs-lookup"><span data-stu-id="69699-108">Sometimes, you need to transfer amounts between bank account in [!INCLUDE[d365fin](includes/d365fin_md.md)] to reflect transfers at your bank.</span></span> <span data-ttu-id="69699-109">Эта задача выполняется в окне **Финансовый журнал** разными способами в зависимости от валюты фондов.</span><span class="sxs-lookup"><span data-stu-id="69699-109">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="69699-110">Прежде чем управлять банковскими счетами, следует настроить каждый банковский счет в качестве карточки банковского счета.</span><span class="sxs-lookup"><span data-stu-id="69699-110">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="69699-111">Кроме того, необходимо настроить электронные службы, которые можно использовать для импорта банковских выписок и экспорта файлов платежей.</span><span class="sxs-lookup"><span data-stu-id="69699-111">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="69699-112">Дополнительные сведения см. в разделе [Настройка банковских счетов](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="69699-112">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="69699-113">В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.</span><span class="sxs-lookup"><span data-stu-id="69699-113">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

| <span data-ttu-id="69699-114">Действие</span><span class="sxs-lookup"><span data-stu-id="69699-114">To</span></span> | <span data-ttu-id="69699-115">Ссылка</span><span class="sxs-lookup"><span data-stu-id="69699-115">See</span></span> |
| --- | --- |
| <span data-ttu-id="69699-116">Выверка банковских счетов в связи с обработкой платежей в окне **Журнал выверки платежей**.</span><span class="sxs-lookup"><span data-stu-id="69699-116">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span> |[<span data-ttu-id="69699-117">Автоматическое применение платежей и выверка банковских счетов</span><span class="sxs-lookup"><span data-stu-id="69699-117">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md) |
| <span data-ttu-id="69699-118">Выверка банковских счетов, включая операции книги платежных документов, как отдельная задача в окне **Выверка банковского счета**.</span><span class="sxs-lookup"><span data-stu-id="69699-118">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span> |[<span data-ttu-id="69699-119">Практическое руководство. Выверка банковских счетов по отдельности</span><span class="sxs-lookup"><span data-stu-id="69699-119">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md) |
| <span data-ttu-id="69699-120">Учет переводов между банковскими счетами в одной валюте или в различных валютах.</span><span class="sxs-lookup"><span data-stu-id="69699-120">Post transfers between bank accounts in the same currency or in different currencies.</span></span> |[<span data-ttu-id="69699-121">Практическое руководство. Перевод банковских средств</span><span class="sxs-lookup"><span data-stu-id="69699-121">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md) |

## <a name="see-also"></a><span data-ttu-id="69699-122">См. также</span><span class="sxs-lookup"><span data-stu-id="69699-122">See Also</span></span>
[<span data-ttu-id="69699-123">Настройка банковских операций</span><span class="sxs-lookup"><span data-stu-id="69699-123">Setting Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="69699-124">Управление дебиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="69699-124">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="69699-125">[Управление кредиторской задолженностью](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="69699-125">[Managing Payables](payables-manage-payables.md)  </span></span>  
<span data-ttu-id="69699-126">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="69699-126">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
[<span data-ttu-id="69699-127">Общие бизнес-функции</span><span class="sxs-lookup"><span data-stu-id="69699-127">General Business Functionality</span></span>](ui-across-business-areas.md)  

