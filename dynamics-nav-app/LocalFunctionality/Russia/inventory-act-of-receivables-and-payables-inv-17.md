---
title: "Акт инвентаризации расчетов с клиентами и платежей ИНВ-17"
description: "Функция \"Акт инвентаризации расчетов с клиентами и платежей\" позволяет выполнить инвентаризацию долгов и обязательств и напечатать отчеты в различных форматах."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: f0c8bd36fb13d93397fd173c54a962eb6f5395f1
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="inventory-act-of-receivables-and-payables-inv-17"></a><span data-ttu-id="9552e-103">Акт инвентаризации расчетов с клиентами и платежей ИНВ-17</span><span class="sxs-lookup"><span data-stu-id="9552e-103">Inventory Act of Receivables And Payables INV-17</span></span>
<span data-ttu-id="9552e-104">Функция "Акт инвентаризации расчетов с клиентами и платежей" позволяет выполнить инвентаризацию долгов и обязательств и напечатать отчеты в следующих форматах:</span><span class="sxs-lookup"><span data-stu-id="9552e-104">The inventory act of receivables and payables feature enables you to prepare an inventory of debts and liabilities, and print reports in the following formats:</span></span>  

- <span data-ttu-id="9552e-105">ИНВ-17</span><span class="sxs-lookup"><span data-stu-id="9552e-105">INV-17</span></span>  
- <span data-ttu-id="9552e-106">Приложение к ИНВ-17</span><span class="sxs-lookup"><span data-stu-id="9552e-106">Supplement to INV-17</span></span>  

## <a name="setting-up-a-number-series-for-inventory-acts"></a><span data-ttu-id="9552e-107">Настройка серии номеров для актов инвентаризации</span><span class="sxs-lookup"><span data-stu-id="9552e-107">Setting Up a Number Series for Inventory Acts</span></span>  
<span data-ttu-id="9552e-108">Ниже приводится процедура настройки серии номеров для актов инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="9552e-108">The following procedure shows how to set up a number series for inventory acts.</span></span>  

1. <span data-ttu-id="9552e-109">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка ГК**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9552e-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9552e-110">В окне **Настройка ГК** заполните поле **Серия ном. актов инв. расч. с контрагентами**.</span><span class="sxs-lookup"><span data-stu-id="9552e-110">In the **General Ledger Setup** window, fill in the **Contractor Invent. Act Nos.** field.</span></span>   

## <a name="inventory-act-processing"></a><span data-ttu-id="9552e-111">Обработка актов инвентаризации</span><span class="sxs-lookup"><span data-stu-id="9552e-111">Inventory Act Processing</span></span>  
<span data-ttu-id="9552e-112">Можно создать и обработать акты инвентаризации счетов контрагентов.</span><span class="sxs-lookup"><span data-stu-id="9552e-112">You can create and process inventory acts of contractors' accounts.</span></span> <span data-ttu-id="9552e-113">Также эти акты можно напечатать.</span><span class="sxs-lookup"><span data-stu-id="9552e-113">You can print inventory acts.</span></span>  

### <a name="creating-an-inventory-act-card"></a><span data-ttu-id="9552e-114">Создание карточки акта инвентаризации</span><span class="sxs-lookup"><span data-stu-id="9552e-114">Creating an Inventory Act Card</span></span>  
<span data-ttu-id="9552e-115">Ниже приводится процедура создания карточки акта инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="9552e-115">The following procedure shows how to create an inventory act card.</span></span>  

1.  <span data-ttu-id="9552e-116">Выберите действие **Главная книга**, выберите действие **Анализ и отчетность**, затем выберите действие **Акты инв. расч. с контрагентами**.</span><span class="sxs-lookup"><span data-stu-id="9552e-116">Choose the **General Ledger** action, choose the **Analysis & Reporting** action, and then choose the **Contractor Invent. Act.** action.</span></span>
2.  <span data-ttu-id="9552e-117">В окне **Карточка Товары Фин. Счет** введите сведения в следующие поля:</span><span class="sxs-lookup"><span data-stu-id="9552e-117">In the **Inventory Account Card** window, enter information in the following fields:</span></span>  

    |<span data-ttu-id="9552e-118">Поле</span><span class="sxs-lookup"><span data-stu-id="9552e-118">Field</span></span>|<span data-ttu-id="9552e-119">Описанием</span><span class="sxs-lookup"><span data-stu-id="9552e-119">Description</span></span>|  
    |-----------|-----------------|  
    |<span data-ttu-id="9552e-120">**Номер**</span><span class="sxs-lookup"><span data-stu-id="9552e-120">**No.**</span></span>|<span data-ttu-id="9552e-121">В этом поле отображается номер акта, и оно заполняется автоматически из серии номеров.</span><span class="sxs-lookup"><span data-stu-id="9552e-121">This field displays the number of the act, and is filled in automatically from the number series.</span></span>|  
    |<span data-ttu-id="9552e-122">**Дата акта**</span><span class="sxs-lookup"><span data-stu-id="9552e-122">**Act Date**</span></span>|<span data-ttu-id="9552e-123">В этом поле отображается дата акта, и оно заполняется рабочей датой.</span><span class="sxs-lookup"><span data-stu-id="9552e-123">This field displays the act date, and is filled in with the work date.</span></span>|  
    |<span data-ttu-id="9552e-124">**Дата инвентаризации**</span><span class="sxs-lookup"><span data-stu-id="9552e-124">**Inventory Date**</span></span>|<span data-ttu-id="9552e-125">В этом поле отображается дата инвентаризации, и оно заполняется рабочей датой.</span><span class="sxs-lookup"><span data-stu-id="9552e-125">This field displays the date of inventory, and is filled with the work date.</span></span> <span data-ttu-id="9552e-126">Долги и обязательства будут рассчитываться на эту дату.</span><span class="sxs-lookup"><span data-stu-id="9552e-126">Debts and liabilities will be calculated on this date.</span></span>|  
    |<span data-ttu-id="9552e-127">**Основание Документа Тип**</span><span class="sxs-lookup"><span data-stu-id="9552e-127">**Reason Document Type**</span></span>|<span data-ttu-id="9552e-128">Выберите тип основания документа из следующих:</span><span class="sxs-lookup"><span data-stu-id="9552e-128">Select the type of reason document from the following:</span></span><br /><br /> <span data-ttu-id="9552e-129">-   **Заказ**</span><span class="sxs-lookup"><span data-stu-id="9552e-129">-   **Order**</span></span><br /><span data-ttu-id="9552e-130">-   **Постановление**;</span><span class="sxs-lookup"><span data-stu-id="9552e-130">-   **Resolution**</span></span><br /><span data-ttu-id="9552e-131">-   **Распоряжение**.</span><span class="sxs-lookup"><span data-stu-id="9552e-131">-   **Regulation**</span></span>|  

3.  <span data-ttu-id="9552e-132">Выберите действие **Добавить строки**.</span><span class="sxs-lookup"><span data-stu-id="9552e-132">Choose the **Add Lines** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="9552e-133">Нельзя задавать фильтры.</span><span class="sxs-lookup"><span data-stu-id="9552e-133">You must not set filters.</span></span>  

 <span data-ttu-id="9552e-134">Создаются долги и обязательства для поставщиков и клиентов, а также строки.</span><span class="sxs-lookup"><span data-stu-id="9552e-134">Debts and liabilities for vendors and customers are calculated, and lines are created.</span></span> <span data-ttu-id="9552e-135">Для каждого клиента и поставщика рассчитываются и отображаются в отдельной строке общая сумма долгов и обязательств на дату инвентаризации (учитывая группы учета).</span><span class="sxs-lookup"><span data-stu-id="9552e-135">For each customer and vendor, the total debt and the total liability amount (taking posting groups into account) on the inventory date are calculated, and shown in a separate line.</span></span> <span data-ttu-id="9552e-136">Поля строк описаны в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="9552e-136">The line fields are listed in the following table.</span></span>  

|<span data-ttu-id="9552e-137">Поле</span><span class="sxs-lookup"><span data-stu-id="9552e-137">Field</span></span>|<span data-ttu-id="9552e-138">Описанием</span><span class="sxs-lookup"><span data-stu-id="9552e-138">Description</span></span>|  
|-----------|-----------------|  
|<span data-ttu-id="9552e-139">**Контрагент Тип**</span><span class="sxs-lookup"><span data-stu-id="9552e-139">**Contractor Type**</span></span>|<span data-ttu-id="9552e-140">В этом поле отображается тип контрагента (клиент, поставщик).</span><span class="sxs-lookup"><span data-stu-id="9552e-140">This field displays the contractor type (Customer, Vendor).</span></span>|  
|<span data-ttu-id="9552e-141">**Контрагент Но.**</span><span class="sxs-lookup"><span data-stu-id="9552e-141">**Contractor No.**</span></span>|<span data-ttu-id="9552e-142">В этом поле отображается номер, соответствующий контрагенту.</span><span class="sxs-lookup"><span data-stu-id="9552e-142">This field displays the number corresponding to the contractor.</span></span>|  
|<span data-ttu-id="9552e-143">**Контрагент Название**</span><span class="sxs-lookup"><span data-stu-id="9552e-143">**Contractor Name**</span></span>|<span data-ttu-id="9552e-144">В этом поле показано имя контрагента.</span><span class="sxs-lookup"><span data-stu-id="9552e-144">This field displays the name of the contractor.</span></span>|  
|<span data-ttu-id="9552e-145">**Учетная Группа, Фин. Счет Но.**</span><span class="sxs-lookup"><span data-stu-id="9552e-145">**Posting Group, G/L Account No.**</span></span>|<span data-ttu-id="9552e-146">В данном поле отображается группа учета и фин. счет расчетов с клиентами или поставщиками, для которого рассчитывается сумма долгов или обязательств.</span><span class="sxs-lookup"><span data-stu-id="9552e-146">This field displays the posting group and the receivables or payables account for which the debt or liability amount is calculated.</span></span>|  
|<span data-ttu-id="9552e-147">**Категория**</span><span class="sxs-lookup"><span data-stu-id="9552e-147">**Category**</span></span>|<span data-ttu-id="9552e-148">В этом поле отображается сумма категории (долги, обязательства).</span><span class="sxs-lookup"><span data-stu-id="9552e-148">This field displays the amount category (Debts, Liabilities).</span></span>|  
|<span data-ttu-id="9552e-149">**Общая сумма**</span><span class="sxs-lookup"><span data-stu-id="9552e-149">**Total Amount**</span></span>|<span data-ttu-id="9552e-150">В этом поле отображается общая сумма долгов и обязательств.</span><span class="sxs-lookup"><span data-stu-id="9552e-150">This field displays the total amount of debts or liabilities.</span></span>|  
|<span data-ttu-id="9552e-151">**Подтвержденная сумма**</span><span class="sxs-lookup"><span data-stu-id="9552e-151">**Confirmed Amount**</span></span>|<span data-ttu-id="9552e-152">В этом поле отображается общая сумма долгов и обязательств по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9552e-152">This field displays the total amount of debts or liabilities by default.</span></span>|  

### <a name="changing-separate-lines-in-an-inventory-act"></a><span data-ttu-id="9552e-153">Изменение отдельных строк акта инвентаризации</span><span class="sxs-lookup"><span data-stu-id="9552e-153">Changing Separate Lines in an Inventory Act</span></span>  
<span data-ttu-id="9552e-154">Ниже приводится процедура изменения отдельных строк акта инвентаризации в окне **Карточка Товары Фин. Счет**.</span><span class="sxs-lookup"><span data-stu-id="9552e-154">The following procedure shows how to change individual lines in an inventory act in the **Inventory Account Card** window.</span></span>  

1. <span data-ttu-id="9552e-155">Укажите, один из следующих вариантов для суммы (или части суммы):</span><span class="sxs-lookup"><span data-stu-id="9552e-155">Specify whether the amount (or part of the amount) is one of the following:</span></span>  

- <span data-ttu-id="9552e-156">Подтверждена контрагентом</span><span class="sxs-lookup"><span data-stu-id="9552e-156">Confirmed by contractor</span></span>  
- <span data-ttu-id="9552e-157">Не подтверждена</span><span class="sxs-lookup"><span data-stu-id="9552e-157">Not confirmed</span></span>  
- <span data-ttu-id="9552e-158">Просрочено</span><span class="sxs-lookup"><span data-stu-id="9552e-158">Overdue</span></span>  

2. <span data-ttu-id="9552e-159">Если сумма не подтверждена, введите неподтвержденную сумму в поле **Неподтвержденная сумма**.</span><span class="sxs-lookup"><span data-stu-id="9552e-159">If the amount is not confirmed, enter the amount that is not confirmed in the **Not Confirmed Amount** field.</span></span>
3. <span data-ttu-id="9552e-160">Если сумма просрочена, введите сумму в поле **С истекшим сроком исковой давности**.</span><span class="sxs-lookup"><span data-stu-id="9552e-160">If the amount is overdue, enter the overdue amount in the **Overdue Amount** field.</span></span>  
3. <span data-ttu-id="9552e-161">Чтобы исправить строку с неправильной суммой (например, если некоторые документы не учтены или не применены), выберите действие **Добавить строки**.</span><span class="sxs-lookup"><span data-stu-id="9552e-161">To correct a line that has an incorrect amount (for instance, if some documents are not posted, or not applied), choose the **Add Lines** action.</span></span>  
5.  <span data-ttu-id="9552e-162">Выберите код поставщика или клиента, затем выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="9552e-162">Select the vendor or customer code, and then choose the **OK** button.</span></span>  

<span data-ttu-id="9552e-163">Сумма долгов и обязательств для выбранного поставщика или клиента пересчитывается, и строки вставляются в документ.</span><span class="sxs-lookup"><span data-stu-id="9552e-163">The debts and liabilities amount for the selected vendor or customer is recalculated and the lines are inserted in the document.</span></span>  

## <a name="printing-the-inv-17-form-and-the-supplement-to-inv-17-form"></a><span data-ttu-id="9552e-164">Печать формы ИНВ-17 и формы Приложение в ИНВ-17</span><span class="sxs-lookup"><span data-stu-id="9552e-164">Printing the INV-17 form and the Supplement to INV-17 form</span></span>  
 <span data-ttu-id="9552e-165">Ниже приводится процедура печати формы ИНВ-17 и формы Приложение к ИНВ-17.</span><span class="sxs-lookup"><span data-stu-id="9552e-165">The following procedure shows how to print the INV-17 form and the Supplement to INV-17 form.</span></span>  

1.  <span data-ttu-id="9552e-166">В окне **Карточка Товары Фин. Счет** выберите действие **Выпустить**.</span><span class="sxs-lookup"><span data-stu-id="9552e-166">In the **Inventory Account Card** window, choose the **Release** action.</span></span>  
3.  <span data-ttu-id="9552e-167">Выберите действие **Акт**, затем выберите действие **Подписи**.</span><span class="sxs-lookup"><span data-stu-id="9552e-167">Choose the **Act** action, and then choose the **Signatures** action.</span></span>  
4.  <span data-ttu-id="9552e-168">Выберите следующие поля:</span><span class="sxs-lookup"><span data-stu-id="9552e-168">Select the following fields:</span></span>  

- <span data-ttu-id="9552e-169">**Председатель**</span><span class="sxs-lookup"><span data-stu-id="9552e-169">**Chairman**</span></span>  
- <span data-ttu-id="9552e-170">**Член комиссии 1**</span><span class="sxs-lookup"><span data-stu-id="9552e-170">**Member1**</span></span>  
- <span data-ttu-id="9552e-171">**Член комиссии 2**</span><span class="sxs-lookup"><span data-stu-id="9552e-171">**Member2**</span></span>  
- <span data-ttu-id="9552e-172">**Член комиссии 3**</span><span class="sxs-lookup"><span data-stu-id="9552e-172">**Member3**</span></span>  
- <span data-ttu-id="9552e-173">**Бухгалтер**</span><span class="sxs-lookup"><span data-stu-id="9552e-173">**Accountant**</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="9552e-174">Все выбранные подписи будут отображены в соответствующих полях.</span><span class="sxs-lookup"><span data-stu-id="9552e-174">All selected signatures will be reflected in the appropriate fields.</span></span>  

5.  <span data-ttu-id="9552e-175">Выберите действие **Печать**, затем выберите действие **Акт инвентаризации ИНВ-17** для печати акта инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="9552e-175">Choose the **Print** action, and then choose the **Invent. Act INV-17** action to print the inventory act.</span></span>  
6.  <span data-ttu-id="9552e-176">Выберите действие **Печать**, затем выберите действие **Приложение к Акту инвентаризации ИНВ-17** для печати приложения к акту инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="9552e-176">Choose the **Print** action, and then choose the **Supplement to Invent. Act INV-17** action to print the supplement to the inventory act.</span></span>  

## <a name="see-also"></a><span data-ttu-id="9552e-177">См. также</span><span class="sxs-lookup"><span data-stu-id="9552e-177">See Also</span></span>  
 <span data-ttu-id="9552e-178">[Отчеты по платежам (Россия)](russian-payables-reports.md) </span><span class="sxs-lookup"><span data-stu-id="9552e-178">[Russian Payables Reports](russian-payables-reports.md) </span></span>  
 [<span data-ttu-id="9552e-179">Отчеты по расчетам с клиентами (Россия)</span><span class="sxs-lookup"><span data-stu-id="9552e-179">Russian Receivables Reports</span></span>](russian-receivables-reports.md)

