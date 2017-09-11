---
title: "Создание платежей"
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
ms.openlocfilehash: 67d948dab76ca7533604025fb53b37aff84bbc11
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="make-payments"></a><span data-ttu-id="a4a5e-102">Создание платежей</span><span class="sxs-lookup"><span data-stu-id="a4a5e-102">Make Payments</span></span>
<span data-ttu-id="a4a5e-103">При учете выполнении платежей поставщикам вы учитываете соответствующие строки платежей в окне **Журнал платежей**.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-103">When you make payments to vendors, you post the related payment lines in the **Payment Journal** window.</span></span> <span data-ttu-id="a4a5e-104">С помощью функции **Предлож. оплаты поставщикам** вы можете находить платежей, подлежащие выполнению.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-104">You can use the **Suggest Vendor Payments** function to find payments that are due.</span></span> <span data-ttu-id="a4a5e-105">Для просмотра таких платежей можно также использовать отчет **Поставщик - сводка задолженности с распределением по срокам**.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-105">You can also use the **Vendor - Summary Aging** report to get an overview of due payments.</span></span>

<span data-ttu-id="a4a5e-106">Из журнала платежей можно распечатывать электронные платежные документы или записывать, когда платежные документы были выписаны.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-106">From the payment journal, you can print computer checks or record when checks are written.</span></span> <span data-ttu-id="a4a5e-107">Если в поле **Тип банковского платежа** выбрано значение **Компьютерный**, то все строки, представляющие платежные документы, должны печататься до учета строк журнала платежей.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-107">If you select **Computer Check** in the **Bank Payment Type** field, then any lines representing checks must be printed before the payment journal can be posted.</span></span>

<span data-ttu-id="a4a5e-108">При учете платежей вы можете экспортировать их в банковский файл для загрузки в банк в целях обработки.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-108">When the payments are posted, you can export them to a bank file for upload to your bank for processing.</span></span>

<span data-ttu-id="a4a5e-109">После выполнения всех платежей в банке их необходимо применить к соответствующим открытым операциям книги поставщиков.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-109">After the payments are made at your bank, you must apply them to their related open vendor ledger entries.</span></span> <span data-ttu-id="a4a5e-110">Это можно сделать вручную или путем импорта файла банковской выписки и применения платежей автоматически.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-110">You can do this manually or by importing a bank statement file and applying the payments automatically.</span></span> <span data-ttu-id="a4a5e-111">Дополнительные сведения см., например, в разделе [Автоматическое применение платежей и выверка банковских счетов](receivables-apply-payments-auto-reconcile-bank-accounts.md).</span><span class="sxs-lookup"><span data-stu-id="a4a5e-111">For more information, see, for example, [Apply Payments Automatically and Reconcile Bank Accounts](receivables-apply-payments-auto-reconcile-bank-accounts.md).</span></span>

<span data-ttu-id="a4a5e-112">В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="a4a5e-113">Действие</span><span class="sxs-lookup"><span data-stu-id="a4a5e-113">To</span></span> |<span data-ttu-id="a4a5e-114">Ссылка</span><span class="sxs-lookup"><span data-stu-id="a4a5e-114">See</span></span> |
|---|----|
|<span data-ttu-id="a4a5e-115">Используйте функцию для предложения оплат поставщикам в соответствии с выбранными критериями, такими как срок оплаты, доступность скидки и ваша ликвидность.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-115">Use a function to suggest vendor payments according to selected criteria, such as due date, discount eligibility, and your liquidity.</span></span>|[<span data-ttu-id="a4a5e-116">Практическое руководство. Предложение оплаты поставщикам</span><span class="sxs-lookup"><span data-stu-id="a4a5e-116">How to: Suggest Vendor Payments</span></span>](payables-how-suggest-vendor-payments.md)|
|<span data-ttu-id="a4a5e-117">Выписывайте чеки по платежам, в печатном виде или в электронном виде.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-117">Issue checks for payments, either as print-outs or as computer checks.</span></span> <span data-ttu-id="a4a5e-118">Аннулируйте чеки перед учетом или после него.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-118">Void checks before or after posting.</span></span>|[<span data-ttu-id="a4a5e-119">Практическое руководство. Работа с платежными документами</span><span class="sxs-lookup"><span data-stu-id="a4a5e-119">How to: Work With Checks</span></span>](payables-how-work-checks.md)|
|<span data-ttu-id="a4a5e-120">Экспортируйте платежи из окна **Журнал платежей** в файл банка, загружаемый в банк для обработки.</span><span class="sxs-lookup"><span data-stu-id="a4a5e-120">Export payments from the **Payment Journal** window to a bank file that you upload to your bank for processing.</span></span>|[<span data-ttu-id="a4a5e-121">Практическое руководство: экспорт оплат в файл банка</span><span class="sxs-lookup"><span data-stu-id="a4a5e-121">How to: Export Payments to a Bank File</span></span>](payables-how-export-payments-bank-file.md)|

## <a name="see-also"></a><span data-ttu-id="a4a5e-122">См. также</span><span class="sxs-lookup"><span data-stu-id="a4a5e-122">See Also</span></span>
[<span data-ttu-id="a4a5e-123">Управление кредиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="a4a5e-123">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="a4a5e-124">Управление закупками</span><span class="sxs-lookup"><span data-stu-id="a4a5e-124">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="a4a5e-125">Управление дебиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="a4a5e-125">Manage Receivables</span></span>](receivables-manage-receivables.md)

