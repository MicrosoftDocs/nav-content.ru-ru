---
title: "Настройка расчета налоговых разниц"
description: "Расчет налоговых разниц необходимо настроить, если имеется налоговая разница в представлении операций с основными средствами, операций себестоимости товаров или финансовых операций в бухгалтерском и налоговом учете, для которых необходимо зафиксировать расходы, подлежащие списанию."
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
ms.openlocfilehash: 66ebee1c320206bc953d157a76aa556aaf19657e
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="setting-up-tax-difference-calculation"></a><span data-ttu-id="74e2e-103">Настройка расчета налоговых разниц</span><span class="sxs-lookup"><span data-stu-id="74e2e-103">Setting up Tax Difference Calculation</span></span>
<span data-ttu-id="74e2e-104">Расчет налоговых разниц необходимо настроить, если имеется налоговая разница в представлении операций с основными средствами, операций себестоимости товаров или финансовых операций в бухгалтерском и налоговом учете, для которых необходимо зафиксировать расходы, подлежащие списанию.</span><span class="sxs-lookup"><span data-stu-id="74e2e-104">Tax difference calculations must be set up if there is a tax difference for the presentation of fixed asset entries, item cost entries, or finance transactions in bookkeeping and tax accounting for which expenses to write off must be fixed.</span></span> <span data-ttu-id="74e2e-105">Чтобы настроить налоговую разницу, выберите действие **Настройка**, а затем выберите действие **Налоговые разницы**.</span><span class="sxs-lookup"><span data-stu-id="74e2e-105">To set tax difference, choose the **Setup** action, and then choose the **Tax Differences** action.</span></span>  

## <a name="setting-up-posting-groups"></a><span data-ttu-id="74e2e-106">Настройка учетных групп</span><span class="sxs-lookup"><span data-stu-id="74e2e-106">Setting Up Posting Groups</span></span>  
<span data-ttu-id="74e2e-107">В пункте меню **Группы Учета** необходимо указать финансовые счета из настроенного плана счетов, на которых будут учитываться финансовые транзакции с налоговыми разницами.</span><span class="sxs-lookup"><span data-stu-id="74e2e-107">In the menu sub-item **Posting Groups**, you must determine finance accounts from the set up chart of accounts, where finance transactions with tax differences are accounted for.</span></span>  

<span data-ttu-id="74e2e-108">В форме **Группы учета налоговой разницы** заполните поля, описанные в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="74e2e-108">In the **Tax Difference Posting Groups** form, enter the fields described in the following table.</span></span>  

|<span data-ttu-id="74e2e-109">Поле</span><span class="sxs-lookup"><span data-stu-id="74e2e-109">Field</span></span>|<span data-ttu-id="74e2e-110">Описанием</span><span class="sxs-lookup"><span data-stu-id="74e2e-110">Description</span></span>|  
|-------------|-----------------|  
|<span data-ttu-id="74e2e-111">**ОС Дата Учета**</span><span class="sxs-lookup"><span data-stu-id="74e2e-111">**FA Posting Date**</span></span>|<span data-ttu-id="74e2e-112">Введите дату транзакции.</span><span class="sxs-lookup"><span data-stu-id="74e2e-112">Enter the transaction date.</span></span>|  
|<span data-ttu-id="74e2e-113">**Номер документа:**</span><span class="sxs-lookup"><span data-stu-id="74e2e-113">**Document No.**</span></span>|<span data-ttu-id="74e2e-114">Введите номер документа, для которого создана текущая транзакция.</span><span class="sxs-lookup"><span data-stu-id="74e2e-114">Enter the document number that the current transaction is created with.</span></span>|  
|<span data-ttu-id="74e2e-115">**ОС Номер**</span><span class="sxs-lookup"><span data-stu-id="74e2e-115">**FA No.**</span></span>|<span data-ttu-id="74e2e-116">Введите код расходов будущих периодов, для которых создана текущая транзакция.</span><span class="sxs-lookup"><span data-stu-id="74e2e-116">Enter the code of the expense of the future period that the current transaction is created with.</span></span>|  
|<span data-ttu-id="74e2e-117">**Код Книги Амортизации**</span><span class="sxs-lookup"><span data-stu-id="74e2e-117">**Depreciation Book Code**</span></span>|<span data-ttu-id="74e2e-118">Введите код книги амортизации, для которой будет сформирована эта транзакция.</span><span class="sxs-lookup"><span data-stu-id="74e2e-118">Select the code of the depreciation book that the transaction will be formed with.</span></span>|  
|<span data-ttu-id="74e2e-119">**Тип учета ОС**</span><span class="sxs-lookup"><span data-stu-id="74e2e-119">**FA Posting Type**</span></span>|<span data-ttu-id="74e2e-120">Выберите тип для параметра **Транзакция**.</span><span class="sxs-lookup"><span data-stu-id="74e2e-120">Select the **Transaction** type.</span></span> <span data-ttu-id="74e2e-121">Доступные значения: **Покупка**, **Амортизация** и **Продажи**.</span><span class="sxs-lookup"><span data-stu-id="74e2e-121">The values are: **Purchase**, **Depreciation**, and **Sales**.</span></span>|  
|<span data-ttu-id="74e2e-122">**Описание**</span><span class="sxs-lookup"><span data-stu-id="74e2e-122">**Description**</span></span>|<span data-ttu-id="74e2e-123">Введите описание транзакции.</span><span class="sxs-lookup"><span data-stu-id="74e2e-123">Enter a description of the transaction.</span></span>|  
|<span data-ttu-id="74e2e-124">**Сумма**</span><span class="sxs-lookup"><span data-stu-id="74e2e-124">**Amount**</span></span>|<span data-ttu-id="74e2e-125">Введите сумму транзакции.</span><span class="sxs-lookup"><span data-stu-id="74e2e-125">Enter the amount of the transaction.</span></span>|  
|<span data-ttu-id="74e2e-126">**Сумма Амортиз. до Нормализации**</span><span class="sxs-lookup"><span data-stu-id="74e2e-126">**Depr. Amount w/o Normalization**</span></span>|<span data-ttu-id="74e2e-127">Отображает сумму амортизации до расчета норм списания расходов.</span><span class="sxs-lookup"><span data-stu-id="74e2e-127">Displays the depreciation amount before calculating norms of expenses to write off.</span></span>|  

<span data-ttu-id="74e2e-128">Если имеются строки журнала, которые необходимо нормализовать перед списанием расходов, эти журналы невозможно учесть без запуска периодического задания нормализации.</span><span class="sxs-lookup"><span data-stu-id="74e2e-128">If there are journal lines that must be normalized before writing off expenses, those journals cannot be posted without running a periodic job of normalizing.</span></span>  

<span data-ttu-id="74e2e-129">В следующей процедуре показан порядок обработки функции нормализации.</span><span class="sxs-lookup"><span data-stu-id="74e2e-129">The following procedure shows how to process a normalization function.</span></span>  

1.  <span data-ttu-id="74e2e-130">В окне **Журнал расходов будущих периодов** выберите **Расчет нормируемой амортизации**</span><span class="sxs-lookup"><span data-stu-id="74e2e-130">In the **Future Expenses Journal** window, choose the **Calculate Depreciation by Norm.**</span></span> <span data-ttu-id="74e2e-131">действие</span><span class="sxs-lookup"><span data-stu-id="74e2e-131">action</span></span>  
2.  <span data-ttu-id="74e2e-132">В окне **Расчет аморт. РБП по норм.** на экспресс-вкладке **Налоговая Разница** установите фильтр для налоговой разницы.</span><span class="sxs-lookup"><span data-stu-id="74e2e-132">In the **Calculate FE Depr. With Norm** window, on the **Tax Difference** FastTab, enter the filter for the tax difference.</span></span>  
3.  <span data-ttu-id="74e2e-133">На экспресс-вкладке **Параметры** введите учетный период, для которого выполняется расчет.</span><span class="sxs-lookup"><span data-stu-id="74e2e-133">On the **Options** FastTab, enter the accounting period for which the counting is done.</span></span>  
4.  <span data-ttu-id="74e2e-134">Для печати отчета выберите действие **Печать**.</span><span class="sxs-lookup"><span data-stu-id="74e2e-134">Choose the **Print** action to print the report.</span></span>  
5.  <span data-ttu-id="74e2e-135">Выполните операцию учета журнала расходов будущих периодов.</span><span class="sxs-lookup"><span data-stu-id="74e2e-135">Post the future expenses journal.</span></span>  

## <a name="see-also"></a><span data-ttu-id="74e2e-136">См. также</span><span class="sxs-lookup"><span data-stu-id="74e2e-136">See Also</span></span>  
 <span data-ttu-id="74e2e-137">[Налоговые регистры](tax-registers.md) </span><span class="sxs-lookup"><span data-stu-id="74e2e-137">[Tax Registers](tax-registers.md) </span></span>  
 <span data-ttu-id="74e2e-138">[Налоговые разницы](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span><span class="sxs-lookup"><span data-stu-id="74e2e-138">[Tax Differences](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span></span>  
 <span data-ttu-id="74e2e-139">[Регистры налоговых разниц](tax-difference-registers.md) </span><span class="sxs-lookup"><span data-stu-id="74e2e-139">[Tax Difference Registers](tax-difference-registers.md) </span></span>  
 <span data-ttu-id="74e2e-140">[Практическое руководство. Настройка юрисдикций нормы](how-to-set-up-norm-jurisdictions.md) </span><span class="sxs-lookup"><span data-stu-id="74e2e-140">[How to: Set Up Norm Jurisdictions](how-to-set-up-norm-jurisdictions.md) </span></span>  
 [<span data-ttu-id="74e2e-141">Практическое руководство. Учет налоговых разниц</span><span class="sxs-lookup"><span data-stu-id="74e2e-141">How to: Post Tax Differences</span></span>](how-to-post-tax-differences.md)

