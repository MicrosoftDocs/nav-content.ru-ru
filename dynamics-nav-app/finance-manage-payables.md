---
title: "Управление расчетами с поставщиками"
description: "Обзор процессов управления кредиторской задолженностью в Dynamics NAV, в том числе платежами поставщикам, кредиторам, долгом и задолженностью."
documentationcenter: 
author: bholtorf
manager: edupont
editor: 
ms.prod: dynamics-nav-2018
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.search.keywords: vendor payment, creditor, debt, balance due, AP
ms.date: 06/02/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 40a62c2d03287b1e31cf71e12b63655fc8e377ad
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="managing-payables"></a><span data-ttu-id="2ac2f-103">Управление кредиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="2ac2f-103">Managing Payables</span></span>
<span data-ttu-id="2ac2f-104">В [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] есть все, что вам нужно для эффективного управления кредиторской задолженностью.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-104">[!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] has what you need to effectively manage accounts payable.</span></span>  

## <a name="payments"></a><span data-ttu-id="2ac2f-105">Оплаты</span><span class="sxs-lookup"><span data-stu-id="2ac2f-105">Payments</span></span>
<span data-ttu-id="2ac2f-106">Можно легко определить приоритеты платежей, учесть штрафы за просроченные платежи и обработать скидки в случае предоплаты.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-106">It's easy to prioritize payments, account for penalties for overdue payments, and handle discounts for early payments.</span></span>

<span data-ttu-id="2ac2f-107">Платежи можно записывать в финансовом журнале, а затем печатать платежные документы до учета журнала платежей.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-107">You can record payments in a general journal, and then print checks before posting the payment journal.</span></span>

<span data-ttu-id="2ac2f-108">Платежи можно применить для закрытия счетов при учете платежа или после его учета.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-108">You can apply payments to close invoices when you post the payment, or after you post the payment.</span></span> <span data-ttu-id="2ac2f-109">Параметр **Метод применения**, заданный для поставщика (в разделе **Карточка поставщика**) определяет, применяется ли платеж вручную или автоматически.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-109">The **Application Method** specified for the vendor (on the **Vendor Card**) determines whether you apply the payment manually, or automatically.</span></span> <span data-ttu-id="2ac2f-110">Всегда есть возможность применить транзакцию вручную.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-110">You can always apply transactions manually.</span></span> <span data-ttu-id="2ac2f-111">Однако, если в качестве метода применения для поставщика выбрано **Применить к самым старым**, и при этом не был задан документ, к которому должен быть применен платеж, этот платеж будет применен к самой ранней открытой операции для поставщика.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-111">However, if the application method for the vendor is **Apply to Oldest**, and you do not specify a document to apply the payment to, the payment is applied to the oldest open entry for the vendor.</span></span>

## <a name="suggest-vendor-payments"></a><span data-ttu-id="2ac2f-112">Предлож. оплаты поставщикам</span><span class="sxs-lookup"><span data-stu-id="2ac2f-112">Suggest Vendor Payments</span></span>
<span data-ttu-id="2ac2f-113">В [!INCLUDE[d365fin](includes/d365fin_md.md)] предлагаются различные виды оплат поставщикам, например оплаты, которые должны быть произведены быстро, или оплаты, для которых возможны скидки.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-113">[!INCLUDE[d365fin](includes/d365fin_md.md)] can suggest various payments to vendors, such as payments that will be due soon, or payments where a discount is available.</span></span> <span data-ttu-id="2ac2f-114">Предложение оплаты может принимать в расчет сумму, которая определена как сумма имеющихся фондов оплаты и как сумма, подходящая для скидок оплаты.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-114">The payment suggestion can consider an amount that you specify as available funds for payment, and eligibility for payment discounts.</span></span>

## <a name="issue-checks"></a><span data-ttu-id="2ac2f-115">Выпуск платежных документов</span><span class="sxs-lookup"><span data-stu-id="2ac2f-115">Issue Checks</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="2ac2f-116"> позволяет выпускать платежные документы для поставщиков вручную и в электронном виде.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-116"> lets you issue checks to vendors manually and electronically.</span></span> <span data-ttu-id="2ac2f-117">Оба способа доступны в окне **Журналы платежей**, в котором также можно аннулировать платежные документы и просмотреть операции с платежными документами.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-117">You do both in the **Payment Journals** window, where you can also void checks and view check ledger entries.</span></span>

## <a name="export-payments-to-a-bank-file"></a><span data-ttu-id="2ac2f-118">Экспорт платежей в банковский файл</span><span class="sxs-lookup"><span data-stu-id="2ac2f-118">Export Payments to a Bank File</span></span>
<span data-ttu-id="2ac2f-119">Когда все будет готово для осуществления платежей поставщику, в окне **Журнал платежей** можно экспортировать файл со сведениями о платежах из строк журнала.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-119">When you are ready to pay a vendor, from the **Payment Journal** window you can export a file with the payment information from the journal lines.</span></span> <span data-ttu-id="2ac2f-120">Затем можно отправить файл в электронный банк для обработки денежных переводов.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-120">You can then upload the file to your electronic bank to process the money transfers.</span></span>

<span data-ttu-id="2ac2f-121">Если не требуется учитывать строку журнала платежей для экспортированного платежа, например потому что ожидается подтверждение обработки транзакции банком, можно просто удалить строку журнала.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-121">If you do not want to post a payment journal line for an exported payment, for example because you are waiting for the bank to confirm the transaction, just delete the journal line.</span></span> <span data-ttu-id="2ac2f-122">Впоследствии при создании строки журнала платежей, чтобы оплатить оставшуюся сумму по счету, в поле **Общая сумма экспорта** можно просмотреть уже экспортированную сумму платежа.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-122">Later, when you create a payment journal line to pay the remaining amount on the invoice, the **Total Exported Amount** field shows how much of the payment amount has already been exported.</span></span> <span data-ttu-id="2ac2f-123">Кроме того, чтобы просмотреть подробные сведения об общей сумме экспорта, можно нажать кнопку **Операции регистров кредитовых переводов**.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-123">Also, you can find detailed information about the exported total by choosing the **Credit Transfer Reg. Entries** button.</span></span>

<span data-ttu-id="2ac2f-124">Если вы откладываете учет платежей до тех пор, пока банк не подтвердит обработку транзакций, существует два способа избежать случайного повторного экспорта платежей для открытых документов:</span><span class="sxs-lookup"><span data-stu-id="2ac2f-124">If you wait to post payments until after your bank confirms that it has processed transactions, there are two ways to avoid accidently re-exporting payments for open documents:</span></span>  

* <span data-ttu-id="2ac2f-125">В журнале платежей с предложенными строками платежей можно выполнить сортировку по столбцу **Экспортировано в файл платежей** или **Общая сумма экспорта**, а затем удалить предложения оплаты для открытых счетов, по которым уже выполнены платежи и для которых не требуется выполнять платежи.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-125">In a payment journal with suggested payment lines, sort on either the **Exported to Payment File** or **Total Exported Amount** columns, and then delete payment suggestions for open invoices for which payments have already been made and you do not want to make payments for.</span></span>

    <span data-ttu-id="2ac2f-126">**Примечание.** Может возникнуть необходимость добавить эти столбцы в список.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-126">**Note** You might have to add these columns to the list.</span></span> <span data-ttu-id="2ac2f-127">Дополнительные сведения см. в разделе [Персонализация пользователя](ui-user-personalization.md).</span><span class="sxs-lookup"><span data-stu-id="2ac2f-127">For more information, see [User Personalization](ui-user-personalization.md).</span></span>  
* <span data-ttu-id="2ac2f-128">Либо в пакетном задании **Предлож. оплаты поставщикам**, в котором указывается, какие платежи следует вставить в журнал платежей, можно указать, что не требуется вставлять строки журнала для платежей, которые уже были экспортированы, установив флажок **Пропустить экспортированные платежи**.</span><span class="sxs-lookup"><span data-stu-id="2ac2f-128">Alternatively, on the **Suggest Vendor Payments** batch job, where you specify the payments to include in the payment journal, you can specify not to insert journal lines for payments that have already been exported by choosing the **Skip Exported Payments** check box.</span></span>

## <a name="see-also"></a><span data-ttu-id="2ac2f-129">См. также</span><span class="sxs-lookup"><span data-stu-id="2ac2f-129">See Also</span></span>
[<span data-ttu-id="2ac2f-130">Способы оплаты</span><span class="sxs-lookup"><span data-stu-id="2ac2f-130">Payment Methods</span></span>](finance-payment-methods.md)  
[<span data-ttu-id="2ac2f-131">Финансы</span><span class="sxs-lookup"><span data-stu-id="2ac2f-131">Finance</span></span>](finance.md)  
<span data-ttu-id="2ac2f-132">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="2ac2f-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

