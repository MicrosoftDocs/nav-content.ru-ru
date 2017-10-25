---
title: "Практическое руководство. Настройка предоплат поставщикам"
description: "Предоплаты — это авансовые платежи для заказов на покупку, которые оплачиваются до формирования окончательного счета. Например, может потребоваться оплатить поставщику 20 процентов суммы счета за производимый товар. Предоплаты позволяют отслеживать и регистрировать авансовые платежи по счетам покупки."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1c1c8cc7f32bc6d6499cca57ce2689064534dff7
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-vendor-prepayments"></a><span data-ttu-id="44c63-105">Практическое руководство. Настройка предоплат поставщикам</span><span class="sxs-lookup"><span data-stu-id="44c63-105">How to: Set Up Vendor Prepayments</span></span>
<span data-ttu-id="44c63-106">Предоплаты — это авансовые платежи для заказов на покупку, которые оплачиваются до формирования окончательного счета.</span><span class="sxs-lookup"><span data-stu-id="44c63-106">Prepayments are advance payments on purchase orders that are paid before the final invoice is issued.</span></span> <span data-ttu-id="44c63-107">Например, может потребоваться оплатить поставщику 20 процентов суммы счета за производимый товар.</span><span class="sxs-lookup"><span data-stu-id="44c63-107">For example, you may be required by a vendor to prepay 20 percent of the invoice amount on a manufactured item.</span></span> <span data-ttu-id="44c63-108">Предоплаты позволяют отслеживать и регистрировать авансовые платежи по счетам покупки.</span><span class="sxs-lookup"><span data-stu-id="44c63-108">Prepayments allow you track and record advance payments on purchase invoices.</span></span>  
  
### <a name="to-set-up-vendor-prepayments"></a><span data-ttu-id="44c63-109">Настройка предоплат поставщикам</span><span class="sxs-lookup"><span data-stu-id="44c63-109">To set up vendor prepayments</span></span>  
  
1.  <span data-ttu-id="44c63-110">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка модуля "Покупки"**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="44c63-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="44c63-111">На экспресс-вкладке **Нумерация** убедитесь, что серия номеров **Серия номеров учт. счетов предопл.** совпадает с **Серия номеров учт. счетов**.</span><span class="sxs-lookup"><span data-stu-id="44c63-111">On the **Numbering** FastTab, verify that the number series for the **Posted Prepmt. Inv. Nos.** is the same as the **Posted Invoice Nos.**.</span></span> <span data-ttu-id="44c63-112">Убедитесь также, что серия номеров для **Серия номеров учт. кр.-нот предопл.** совпадает с серией для **Серия номеров учт. кредит-нот**.</span><span class="sxs-lookup"><span data-stu-id="44c63-112">Also verify that the number series for **Posted Prepmt. Cr. Memo Nos.** is the same as the **Posted Credit Memo Nos.**.</span></span>  
  
3.  <span data-ttu-id="44c63-113">На экспресс-вкладке **Предоплата** введите следующие сведения.</span><span class="sxs-lookup"><span data-stu-id="44c63-113">On the **Prepayment** FastTab, enter the following information.</span></span>  
  
    |<span data-ttu-id="44c63-114">Поле</span><span class="sxs-lookup"><span data-stu-id="44c63-114">Field</span></span>|<span data-ttu-id="44c63-115">Описанием</span><span class="sxs-lookup"><span data-stu-id="44c63-115">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="44c63-116">**Испол. Аванс Счет Но.**</span><span class="sxs-lookup"><span data-stu-id="44c63-116">**Use Prepayment Account**</span></span>|<span data-ttu-id="44c63-117">Выберите это поле, чтобы учесть предоплаты поставщикам, используя специальный субсчет, указанный в поле **Счет ГК предоплаты** в окне **Учетные группы поставщика**.</span><span class="sxs-lookup"><span data-stu-id="44c63-117">Select to post prepayments using the special subaccount specified in the **Prepayment Account** field in the **Vendor Posting Groups** window.</span></span>|  
    |<span data-ttu-id="44c63-118">**Учт. разн. по предопл. - серия ном. док.**</span><span class="sxs-lookup"><span data-stu-id="44c63-118">**Posted PD Doc. Nos.**</span></span>|<span data-ttu-id="44c63-119">Введите код серии номеров, который требуется использовать для документов предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-119">Enter the code of the number series that you want to use for prepayment documents.</span></span>|  
    |<span data-ttu-id="44c63-120">**Разн. по предопл. - тип серии номеров док.**</span><span class="sxs-lookup"><span data-stu-id="44c63-120">**PD Doc. Nos. Type**</span></span>|<span data-ttu-id="44c63-121">Укажите, требуется ли использовать серию номеров или символ для идентификации документов предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-121">Select if you want to use a number series or symbol to identify prepayment documents.</span></span>|  
    |<span data-ttu-id="44c63-122">**Символ для док. разн. по предопл.**</span><span class="sxs-lookup"><span data-stu-id="44c63-122">**Symbol for PD Doc.**</span></span>|<span data-ttu-id="44c63-123">Введите символ, который будет печататься на документах предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-123">Enter a symbol to be printed on prepayment documents.</span></span>|  
    |<span data-ttu-id="44c63-124">**Разн. по предопл.: прибыль - знач. изм. условия**</span><span class="sxs-lookup"><span data-stu-id="44c63-124">**PD Gains Condition Dim Value**</span></span>|<span data-ttu-id="44c63-125">Введите код для измерения, которое используется для создания условной прибыли от предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-125">Enter the code for the dimension that is used to generate conditional prepayment gains.</span></span>|  
    |<span data-ttu-id="44c63-126">**Разн. по предопл.: убытки - знач. изм. условия**</span><span class="sxs-lookup"><span data-stu-id="44c63-126">**PD Losses Condition Dim Value**</span></span>|<span data-ttu-id="44c63-127">Введите код для измерения, которое используется для создания условного убытка от предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-127">Enter the code for the dimension that is used to generate conditional prepayment losses.</span></span>|  
    |<span data-ttu-id="44c63-128">**Разн. по предопл.: прибыль - знач. изм. вида**</span><span class="sxs-lookup"><span data-stu-id="44c63-128">**PD Gains Kind Dim Value**</span></span>|<span data-ttu-id="44c63-129">Введите код для измерения, которое используется для создания платежа с точки зрения прибыли от предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-129">Enter the code for the dimension that is used to generate payment in kind prepayment gains.</span></span>|  
    |<span data-ttu-id="44c63-130">**Разн. по предопл.: убытки - знач. изм. вида**</span><span class="sxs-lookup"><span data-stu-id="44c63-130">**PD Losses Kind Dim Value**</span></span>|<span data-ttu-id="44c63-131">Введите код для измерения, которое используется для создания платежа с точки зрения убытка от предоплаты.</span><span class="sxs-lookup"><span data-stu-id="44c63-131">Enter the code for the dimension that is used to generate payment in kind prepayment losses.</span></span>|  
  
4.  <span data-ttu-id="44c63-132">Откройте окно **Учетные группы поставщика**.</span><span class="sxs-lookup"><span data-stu-id="44c63-132">Open the **Vendor Posting Groups** window.</span></span>  
  
5.  <span data-ttu-id="44c63-133">В поле **Счет предоплаты** укажите счет главной книги, который должен использоваться для учета предоплаты поставщикам.</span><span class="sxs-lookup"><span data-stu-id="44c63-133">In the **Prepayment Account** field, specify the general ledger accounts that you want to use for posting vendor prepayments.</span></span>  
  
6.  <span data-ttu-id="44c63-134">Нажмите **Закрыть**, чтобы закрыть окно и сохранить введенные данные.</span><span class="sxs-lookup"><span data-stu-id="44c63-134">Choose **Close** to close the window and save your entries.</span></span>  
  
 <span data-ttu-id="44c63-135">Теперь вы можете отслеживать и регистрировать авансовые платежи по счетам покупки.</span><span class="sxs-lookup"><span data-stu-id="44c63-135">You can now track and record advance payments on purchase invoices.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="44c63-136">См. также</span><span class="sxs-lookup"><span data-stu-id="44c63-136">See Also</span></span>  
 <span data-ttu-id="44c63-137">[Пошаговое руководство. Настройка и выставление счетов на продажу](../../walkthrough-setting-up-and-invoicing-sales-prepayments.md) </span><span class="sxs-lookup"><span data-stu-id="44c63-137">[Walkthrough: Setting Up and Invoicing Sales Prepayments](../../walkthrough-setting-up-and-invoicing-sales-prepayments.md) </span></span>  
 <span data-ttu-id="44c63-138">[Предоплата по счету](invoice-prepayments.md) </span><span class="sxs-lookup"><span data-stu-id="44c63-138">[Invoice Prepayments](invoice-prepayments.md) </span></span>  
 <span data-ttu-id="44c63-139">[Настройка предоплаты](set-up-prepayments.md) </span><span class="sxs-lookup"><span data-stu-id="44c63-139">[Set Up Prepayments](set-up-prepayments.md) </span></span>  
 [<span data-ttu-id="44c63-140">Практическое руководство. Корректировка предоплат</span><span class="sxs-lookup"><span data-stu-id="44c63-140">How to: Correct Prepayments</span></span>](how-to-correct-prepayments.md)
