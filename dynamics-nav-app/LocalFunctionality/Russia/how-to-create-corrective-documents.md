---
title: "Практическое руководство. Создание корректирующих документов"
description: "В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно создавать корректирующие счета и кредит-ноты, чтобы отражать изменения в количестве или сумме счета."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 1a3fe117250deb443e76f2b3d63e6f99bd424af7
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-create-corrective-documents"></a><span data-ttu-id="61a46-103">Практическое руководство. Создание корректирующих документов</span><span class="sxs-lookup"><span data-stu-id="61a46-103">How to: Create Corrective Documents</span></span>
<span data-ttu-id="61a46-104">В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно создавать корректирующие счета и кредит-ноты, чтобы отражать изменения в количестве или сумме счета.</span><span class="sxs-lookup"><span data-stu-id="61a46-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can create corrective invoices and credit memos to reflect a change in the invoiced amount or quantity.</span></span>  

 <span data-ttu-id="61a46-105">Если вы обнаружили ошибку в выданном счете или кредит-ноте, вы также можете создать документ о пересмотре.</span><span class="sxs-lookup"><span data-stu-id="61a46-105">You can also create revision documents if you discover a mistake in an issued invoice or credit memo.</span></span>  

 <span data-ttu-id="61a46-106">Приведенная ниже процедура иллюстрирует порядок создания корректирующего счета продажи, но аналогичным образом можно создавать кредит-ноты продажи, счета покупки и кредит-ноты покупки.</span><span class="sxs-lookup"><span data-stu-id="61a46-106">The following procedure shows how to create a corrective sales invoice, but the same steps apply to sales credit memos, purchase invoices, and purchase credit memos.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="61a46-107">Нельзя создать корректирующие документы для сервисных документов.</span><span class="sxs-lookup"><span data-stu-id="61a46-107">You cannot create corrective documents for service documents.</span></span>  

## <a name="to-create-a-corrective-invoice"></a><span data-ttu-id="61a46-108">Создание корректирующего счета</span><span class="sxs-lookup"><span data-stu-id="61a46-108">To create a corrective invoice</span></span>  

1. <span data-ttu-id="61a46-109">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Корректирующие счета**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="61a46-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Corrective Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="61a46-110">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="61a46-110">Choose the **New** action.</span></span>
3. <span data-ttu-id="61a46-111">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="61a46-111">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](../../includes/tooltip-inline-tip_md.md)]

    <span data-ttu-id="61a46-112">Некоторые поля заполняются автоматически при выборе клиента.</span><span class="sxs-lookup"><span data-stu-id="61a46-112">Some fields are filled in automatically when you select a customer.</span></span> <span data-ttu-id="61a46-113">Другие поля нужно заполнить вручную.</span><span class="sxs-lookup"><span data-stu-id="61a46-113">Other fields you must fill in manually.</span></span> <span data-ttu-id="61a46-114">Следует убедиться, что значения полей таких полей как **Цены с учетом НДС**, **Код валюты**, соответствующие измерения и т. д. настроены в корректирующем документе так же, как в исходном счете.</span><span class="sxs-lookup"><span data-stu-id="61a46-114">You must make sure that the values of fields such as **Prices Including VAT** and **Currency Code**, relevant dimensions, and so on are the same in the corrective document as in the original invoice.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="61a46-115">На вкладке **Счет** заполните поле **Номер договора**,</span><span class="sxs-lookup"><span data-stu-id="61a46-115">On the **Invoicing** tab, fill in the **Agreement No.**</span></span> <span data-ttu-id="61a46-116">если вы настроили договор.</span><span class="sxs-lookup"><span data-stu-id="61a46-116">field if you have set up an agreement.</span></span> <span data-ttu-id="61a46-117">Дополнительные сведения см. в разделе [Практическое руководство. Настройка договоров с клиентами и поставщиками](how-to-set-up-customer-and-vendor-agreements.md).</span><span class="sxs-lookup"><span data-stu-id="61a46-117">For more information, see [How to: Set Up Customer and Vendor Agreements](how-to-set-up-customer-and-vendor-agreements.md).</span></span>  

3.  <span data-ttu-id="61a46-118">На экспресс-вкладке **НДС** заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="61a46-118">On the **VAT** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="61a46-119">Поле</span><span class="sxs-lookup"><span data-stu-id="61a46-119">Field</span></span>|<span data-ttu-id="61a46-120">Описанием</span><span class="sxs-lookup"><span data-stu-id="61a46-120">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="61a46-121">**Дополнительный лист книги НДС**</span><span class="sxs-lookup"><span data-stu-id="61a46-121">**Additional VAT Ledger Sheet**</span></span>|<span data-ttu-id="61a46-122">При необходимости включите этот данного в дополнительную книгу НДС.</span><span class="sxs-lookup"><span data-stu-id="61a46-122">Optionally, select to include this document in the additional VAT ledger.</span></span> <span data-ttu-id="61a46-123">Дополнительные сведения см. в разделе [Книги НДС](vat-ledgers.md).</span><span class="sxs-lookup"><span data-stu-id="61a46-123">For more information, see [VAT Ledgers](vat-ledgers.md).</span></span>|  
    |<span data-ttu-id="61a46-124">**Дата Корректируемого Документа**</span><span class="sxs-lookup"><span data-stu-id="61a46-124">**Corrected Document Date**</span></span>|<span data-ttu-id="61a46-125">Если вы выбрали поле **Дополнительный лист книги НДС**, укажите дату учета документа, который вы корректируете.</span><span class="sxs-lookup"><span data-stu-id="61a46-125">If you selected the **Additional VAT Ledger Sheet** field, specify the posting date of the document that you are correcting.</span></span><br /><br /> <span data-ttu-id="61a46-126">Это гарантирует, что исходный счет будет указан как отмененный в дополнительном листе книги НДС продаж в соответствующем отчетном периоде.</span><span class="sxs-lookup"><span data-stu-id="61a46-126">This ensures that the original invoice is listed as canceled in the additional sheet for the sales VAT book in the relevant report period.</span></span>|  
    |<span data-ttu-id="61a46-127">**Корректирующий документ**</span><span class="sxs-lookup"><span data-stu-id="61a46-127">**Corrective Document**</span></span>|<span data-ttu-id="61a46-128">Выберите, чтобы сделать это документ корректирующим.</span><span class="sxs-lookup"><span data-stu-id="61a46-128">Select to make this document a corrective document.</span></span>|  
    |<span data-ttu-id="61a46-129">**Тип корректирующего док.**</span><span class="sxs-lookup"><span data-stu-id="61a46-129">**Corrective Doc. Type**</span></span>|<span data-ttu-id="61a46-130">Выберите **Корректировка**, чтобы сделать этот документ корректировкой счета.</span><span class="sxs-lookup"><span data-stu-id="61a46-130">Choose **Correction** to make this a correction to an invoice.</span></span>|  
    |<span data-ttu-id="61a46-131">**Тип скорректированного док.**</span><span class="sxs-lookup"><span data-stu-id="61a46-131">**Corrected Doc. Type**</span></span>|<span data-ttu-id="61a46-132">Укажите тип исходного документа — счет или кредит-нота.</span><span class="sxs-lookup"><span data-stu-id="61a46-132">Specify if the original document was an invoice or a credit memo.</span></span>|  
    |<span data-ttu-id="61a46-133">**Номер скорректированного док.**</span><span class="sxs-lookup"><span data-stu-id="61a46-133">**Corrected Doc. No.**</span></span>|<span data-ttu-id="61a46-134">Укажите исходный документ.</span><span class="sxs-lookup"><span data-stu-id="61a46-134">Specify the original document.</span></span><br /><br /> <span data-ttu-id="61a46-135">В зависимости от значения поля **Тип скорректированного док.** можно выбрать учтенную кредит-ноту или учтенный счет.</span><span class="sxs-lookup"><span data-stu-id="61a46-135">Depending on the value of the **Corrected Doc. Type** field, you can select a posted invoice or a posted credit memo.</span></span>|  
    |<span data-ttu-id="61a46-136">**Номер редакции**</span><span class="sxs-lookup"><span data-stu-id="61a46-136">**Revision No.**</span></span>|<span data-ttu-id="61a46-137">При необходимости укажите номер редакции, если этот документ является редакцией корректирующего документа.</span><span class="sxs-lookup"><span data-stu-id="61a46-137">Optionally, specify a revision number if this document is a revision of a corrective document.</span></span>|  

4. <span data-ttu-id="61a46-138">Выберите действие **Получить строки корр. док.**.</span><span class="sxs-lookup"><span data-stu-id="61a46-138">Choose the **Get Corr. Doc. Lines** action.</span></span>  
5.  <span data-ttu-id="61a46-139">В окне **Строки счета продажи** выберите строки, которые нужно добавить в корректирующий документ, а затем нажмите кнопку **OK**.</span><span class="sxs-lookup"><span data-stu-id="61a46-139">In the **Sales Invoice Lines** window, select the lines that you want to add to the corrective documents, and then choose the **OK** button.</span></span>  
6.  <span data-ttu-id="61a46-140">В отобразившемся диалоговом окне укажите, относится корректировка к количеству или к цене.</span><span class="sxs-lookup"><span data-stu-id="61a46-140">In the dialog box that appears, specify if the correction if for quantity or price.</span></span>  
7.  <span data-ttu-id="61a46-141">Внесите соответствующие изменения в строки документа.</span><span class="sxs-lookup"><span data-stu-id="61a46-141">Make the appropriate changes to the document lines.</span></span> <span data-ttu-id="61a46-142">Например, чтобы изменить сумму счета, измените значение поля **Сумма (после)**.</span><span class="sxs-lookup"><span data-stu-id="61a46-142">For example, to change the invoiced amount, change the value of the **Amount (After)** field.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="61a46-143">Если строка документа относится к товару, можно изменить только значение поля **Сумма (после)**.</span><span class="sxs-lookup"><span data-stu-id="61a46-143">If the document line is for an item, you can only change the value of the **Amount (After)** field.</span></span> <span data-ttu-id="61a46-144">Если строка документа относится к товарной издержке, можно изменить значение поля **Количество (после)** и поля **Сумма (после)**.</span><span class="sxs-lookup"><span data-stu-id="61a46-144">If the document line is for an item charge, you can change the value of the **Quantity (After)** field and the **Amount (After)** field.</span></span>  

8.  <span data-ttu-id="61a46-145">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="61a46-145">Post the document.</span></span>  

    <span data-ttu-id="61a46-146">Учтенный документ будет включен в список учтенных счетов.</span><span class="sxs-lookup"><span data-stu-id="61a46-146">The posted document is included in the list of posted invoices.</span></span> <span data-ttu-id="61a46-147">Это означает, что его можно выбрать в поле **Номер скорректированного док.**,</span><span class="sxs-lookup"><span data-stu-id="61a46-147">This means that you can select it in the **Corrected Doc. No.**</span></span> <span data-ttu-id="61a46-148">если необходимо создать корректировку этого исправленного документа.</span><span class="sxs-lookup"><span data-stu-id="61a46-148">field if you must create a correction for this corrected document.</span></span>  

<span data-ttu-id="61a46-149">Приведенная ниже процедура иллюстрирует порядок создания пересмотра учтенного счета продажи, но аналогичным образом можно создавать кредит-ноты продажи, счета покупки и кредит-ноты покупки, а также корректирующие документы.</span><span class="sxs-lookup"><span data-stu-id="61a46-149">The following procedure describes how to create a revision for a posted sales invoice but the same steps apply to sales credit memos, purchase invoices, purchase credit memos, and corrective documents.</span></span>  

## <a name="to-create-a-revision-document-for-a-sales-invoice"></a><span data-ttu-id="61a46-150">Создание документа о пересмотре счета продажи</span><span class="sxs-lookup"><span data-stu-id="61a46-150">To create a revision document for a sales invoice</span></span>  

1.  <span data-ttu-id="61a46-151">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Счета**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="61a46-151">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Invoices**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="61a46-152">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="61a46-152">Choose the **New** action.</span></span>
3.  <span data-ttu-id="61a46-153">Выберите действие **Копировать документ**.</span><span class="sxs-lookup"><span data-stu-id="61a46-153">Choose the **Copy Document** action.</span></span>  
4.  <span data-ttu-id="61a46-154">В окне **Копировать документ продажи** заполните поля дли импорта информации из исходного счета продажи.</span><span class="sxs-lookup"><span data-stu-id="61a46-154">In the **Copy Sales Document** window, fill in the fields to import information from the original sales invoice.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="61a46-155">Выберите поле **Включать заголовок**.</span><span class="sxs-lookup"><span data-stu-id="61a46-155">Select the **Include Header** field.</span></span>  

5.  <span data-ttu-id="61a46-156">На экспресс-вкладке **НДС** заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="61a46-156">On the **VAT** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="61a46-157">Поле</span><span class="sxs-lookup"><span data-stu-id="61a46-157">Field</span></span>|<span data-ttu-id="61a46-158">Описанием</span><span class="sxs-lookup"><span data-stu-id="61a46-158">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="61a46-159">**Дополнительный лист книги НДС**</span><span class="sxs-lookup"><span data-stu-id="61a46-159">**Additional VAT Ledger Sheet**</span></span>|<span data-ttu-id="61a46-160">При необходимости включите этот данного в дополнительную книгу НДС.</span><span class="sxs-lookup"><span data-stu-id="61a46-160">Optionally, select to include this document in the additional VAT ledger.</span></span> <span data-ttu-id="61a46-161">Дополнительные сведения см. в разделе [Книги НДС](vat-ledgers.md).</span><span class="sxs-lookup"><span data-stu-id="61a46-161">For more information, see [VAT Ledgers](vat-ledgers.md).</span></span>|  
    |<span data-ttu-id="61a46-162">**Дата Корректируемого Документа**</span><span class="sxs-lookup"><span data-stu-id="61a46-162">**Corrected Document Date**</span></span>|<span data-ttu-id="61a46-163">Если вы выбрали поле **Дополнительный лист книги НДС**, укажите дату учета документа, который вы пересматриваете.</span><span class="sxs-lookup"><span data-stu-id="61a46-163">If you selected the **Additional VAT Ledger Sheet** field, specify the posting date of the document that you are revising.</span></span><br /><br /> <span data-ttu-id="61a46-164">Это гарантирует, что исходный счет будет указан как отмененный в дополнительном листе книги НДС продаж в соответствующем отчетном периоде.</span><span class="sxs-lookup"><span data-stu-id="61a46-164">This ensures that the original invoice is listed as canceled in the additional sheet for the sales VAT book in the relevant report period.</span></span>|  
    |<span data-ttu-id="61a46-165">**Корректирующий документ**</span><span class="sxs-lookup"><span data-stu-id="61a46-165">**Corrective Document**</span></span>|<span data-ttu-id="61a46-166">Выберите, чтобы сделать это документ корректирующим.</span><span class="sxs-lookup"><span data-stu-id="61a46-166">Select to make this document a corrective document.</span></span>|  
    |<span data-ttu-id="61a46-167">**Тип корректирующего док.**</span><span class="sxs-lookup"><span data-stu-id="61a46-167">**Corrective Doc. Type**</span></span>|<span data-ttu-id="61a46-168">Выберите **Редакция**, чтобы сделать этот документ пересмотренным.</span><span class="sxs-lookup"><span data-stu-id="61a46-168">Choose **Revision** to make this a revision document.</span></span>|  
    |<span data-ttu-id="61a46-169">**Тип скорректированного док.**</span><span class="sxs-lookup"><span data-stu-id="61a46-169">**Corrected Doc. Type**</span></span>|<span data-ttu-id="61a46-170">Укажите тип исходного документа — счет или кредит-нота.</span><span class="sxs-lookup"><span data-stu-id="61a46-170">Specify if the original document was an invoice or a credit memo.</span></span>|  
    |<span data-ttu-id="61a46-171">**Номер скорректированного док.**</span><span class="sxs-lookup"><span data-stu-id="61a46-171">**Corrected Doc. No.**</span></span>|<span data-ttu-id="61a46-172">Укажите исходный документ.</span><span class="sxs-lookup"><span data-stu-id="61a46-172">Specify the original document.</span></span><br /><br /> <span data-ttu-id="61a46-173">В зависимости от значения поля **Тип скорректированного док.** можно выбрать учтенную кредит-ноту или учтенный счет.</span><span class="sxs-lookup"><span data-stu-id="61a46-173">Depending on the value of the **Corrected Doc. Type** field, you can select a posted invoice or a posted credit memo.</span></span>|  
    |<span data-ttu-id="61a46-174">**Номер редакции**</span><span class="sxs-lookup"><span data-stu-id="61a46-174">**Revision No.**</span></span>|<span data-ttu-id="61a46-175">Укажите номер редакции.</span><span class="sxs-lookup"><span data-stu-id="61a46-175">Specify a revision number.</span></span><br /><br /> <span data-ttu-id="61a46-176">Номер редакции не используется в [!INCLUDE[navnow](../../includes/navnow_md.md)], но он указывается при печати документа.</span><span class="sxs-lookup"><span data-stu-id="61a46-176">The revision number is not used by [!INCLUDE[navnow](../../includes/navnow_md.md)], but it is included in the printed document.</span></span>|  

6.  <span data-ttu-id="61a46-177">Внесите соответствующие изменения в строки документа.</span><span class="sxs-lookup"><span data-stu-id="61a46-177">Make the relevant changes to the document lines.</span></span>  
7.  <span data-ttu-id="61a46-178">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="61a46-178">Post the document.</span></span>  

<span data-ttu-id="61a46-179">Учтенный документ будет включен в список учтенных счетов.</span><span class="sxs-lookup"><span data-stu-id="61a46-179">The posted document is included in the list of posted invoices.</span></span> <span data-ttu-id="61a46-180">Это означает, что его можно выбрать в поле **Номер скорректированного док.**,</span><span class="sxs-lookup"><span data-stu-id="61a46-180">This means that you can select it in the **Corrected Doc. No.**</span></span> <span data-ttu-id="61a46-181">если необходимо создать корректировку этого исправленного документа.</span><span class="sxs-lookup"><span data-stu-id="61a46-181">field if you must create a correction for this corrected document.</span></span>  

## <a name="see-also"></a><span data-ttu-id="61a46-182">См. также</span><span class="sxs-lookup"><span data-stu-id="61a46-182">See Also</span></span>  
 [<span data-ttu-id="61a46-183">Корректирующие документы</span><span class="sxs-lookup"><span data-stu-id="61a46-183">Corrective Documents</span></span>](corrective-documents.md)
