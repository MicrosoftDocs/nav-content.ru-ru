---
title: "Учет НДС в продажах"
description: "Некоторые поля были добавлены в окно настройки учета НДС."
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
ms.openlocfilehash: eff5a4ce9d2b17e7ce19a50110c66cff1691d061
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="posting-vat-on-sales"></a><span data-ttu-id="60c2b-103">Учет НДС в продажах</span><span class="sxs-lookup"><span data-stu-id="60c2b-103">Posting VAT on Sales</span></span>
<span data-ttu-id="60c2b-104">В окно **Настройка учета НДС** (код 472) были добавлены следующие поля:</span><span class="sxs-lookup"><span data-stu-id="60c2b-104">The following fields have been added to the **VAT Posting Setup** window (ID 472):</span></span>  

|<span data-ttu-id="60c2b-105">Поле</span><span class="sxs-lookup"><span data-stu-id="60c2b-105">Field</span></span>|<span data-ttu-id="60c2b-106">Описанием</span><span class="sxs-lookup"><span data-stu-id="60c2b-106">Description</span></span>|  
|-----------|-----------------|  
|<span data-ttu-id="60c2b-107">**Тип Транз. НДС**</span><span class="sxs-lookup"><span data-stu-id="60c2b-107">**Trans. VAT Type**</span></span>|<span data-ttu-id="60c2b-108">Используется для определения правила извлечения НДС.</span><span class="sxs-lookup"><span data-stu-id="60c2b-108">Used to define the rule for extracting VAT.</span></span>|  
|<span data-ttu-id="60c2b-109">**Транз. НДС Фин. Счет Но.**</span><span class="sxs-lookup"><span data-stu-id="60c2b-109">**Trans. VAT Account**</span></span>|<span data-ttu-id="60c2b-110">Используется для указания счета регистрации суммы НДС от реализации и предоплат клиента, которая должна выплачиваться в федеральный бюджет.</span><span class="sxs-lookup"><span data-stu-id="60c2b-110">Used to specify an account to register the VAT amount from the gain and from the customer's prepayments to be paid to the federal budget.</span></span>|  
|<span data-ttu-id="60c2b-111">**Тип Суммы для Счета Фактуры**</span><span class="sxs-lookup"><span data-stu-id="60c2b-111">**Tax Invoice Amount Type**</span></span>|<span data-ttu-id="60c2b-112">Используется для выбора значения НДС.</span><span class="sxs-lookup"><span data-stu-id="60c2b-112">Used to select the value of VAT.</span></span> <span data-ttu-id="60c2b-113">В зависимости от значения в этом поле введенные суммы НДС используются в разных столбцах книг НДС покупок или продаж.</span><span class="sxs-lookup"><span data-stu-id="60c2b-113">Depending on the value in this field, VAT entry amounts are used in different columns of the VAT purchase or sales ledgers.</span></span>|  

<span data-ttu-id="60c2b-114">Указанные действия выполняются для каждой комбинации в учетной группе НДС продаж продукта и НДС продаж.</span><span class="sxs-lookup"><span data-stu-id="60c2b-114">The above actions are taken for each combination of the Sales VAT Product posting group and Sales VAT posting group.</span></span>  

<span data-ttu-id="60c2b-115">Для поля **Тип Транз. НДС** возможны следующие значения:</span><span class="sxs-lookup"><span data-stu-id="60c2b-115">In the **Trans. VAT Type** field, the following options are available:</span></span>  

- **<Blank>**  
- <span data-ttu-id="60c2b-116">**Сумма + налог**</span><span class="sxs-lookup"><span data-stu-id="60c2b-116">**Amount + Tax**</span></span>  
- <span data-ttu-id="60c2b-117">**Сумма + налог**</span><span class="sxs-lookup"><span data-stu-id="60c2b-117">**Amount & Tax**</span></span>  

<span data-ttu-id="60c2b-118">Для учета НДС выберите действие **Сумма + налог**.</span><span class="sxs-lookup"><span data-stu-id="60c2b-118">To account for VAT, choose the **Amount + Tax** action.</span></span>  

<span data-ttu-id="60c2b-119">Ниже приводится процедура создания бухгалтерских проводок.</span><span class="sxs-lookup"><span data-stu-id="60c2b-119">The following procedure shows how the accounting entries are created.</span></span>  

1.  <span data-ttu-id="60c2b-120">Введите в поле **Транз. НДС Фин. Счет Но.** значение "Субсчет 90-3, Налог на добавленную стоимость".</span><span class="sxs-lookup"><span data-stu-id="60c2b-120">In the **Trans. VAT Account No.** field, enter Subaccount 90-3, Gain VAT.</span></span>  
2.  <span data-ttu-id="60c2b-121">В поле **Счет НДС продаж** введите "Субсчет 68, Расчеты по налогам и сборам".</span><span class="sxs-lookup"><span data-stu-id="60c2b-121">In the **Sales VAT Account** field, enter Subaccount 68, VAT to Federal Budget.</span></span>

<span data-ttu-id="60c2b-122">Следующие бухгалтерские проводки создают различные настройки.</span><span class="sxs-lookup"><span data-stu-id="60c2b-122">The following accounting entries create the different settings.</span></span>  

|<span data-ttu-id="60c2b-123">Бухгалтерские проводки</span><span class="sxs-lookup"><span data-stu-id="60c2b-123">Accounting Entries</span></span>|<span data-ttu-id="60c2b-124">Параметры</span><span class="sxs-lookup"><span data-stu-id="60c2b-124">Settings</span></span>|  
|------------------------|--------------|  
|<span data-ttu-id="60c2b-125">**Сумма + налог**</span><span class="sxs-lookup"><span data-stu-id="60c2b-125">**Amount + Tax**</span></span>|<span data-ttu-id="60c2b-126">Дебет 62 Поступления и платежи - Кредит 90-1 выручка от продажи</span><span class="sxs-lookup"><span data-stu-id="60c2b-126">Debit 62 Payables and Receivables - Credit 90-1 Gain and Sales Amount Including VAT</span></span><br /><br /> <span data-ttu-id="60c2b-127">Дебет 90-3 Налог на добавленную стоимость</span><span class="sxs-lookup"><span data-stu-id="60c2b-127">Debit 90-3 Gain VAT</span></span><br /><br /> <span data-ttu-id="60c2b-128">Кредит 68 Расчеты по налогам и сборам</span><span class="sxs-lookup"><span data-stu-id="60c2b-128">Credit 68 VAT to Federal Budget</span></span><br /><br /> <span data-ttu-id="60c2b-129">Сумма НДС продаж</span><span class="sxs-lookup"><span data-stu-id="60c2b-129">Sales VAT Amount</span></span>|  
|<span data-ttu-id="60c2b-130">**Сумма + налог**</span><span class="sxs-lookup"><span data-stu-id="60c2b-130">**Amount & Tax**</span></span>|<span data-ttu-id="60c2b-131">Дебет 62 Поступления и платежи</span><span class="sxs-lookup"><span data-stu-id="60c2b-131">Debit 62 Payables and Receivables</span></span><br /><br /> <span data-ttu-id="60c2b-132">Кредит 90-1 Прибыль</span><span class="sxs-lookup"><span data-stu-id="60c2b-132">Credit 90-1 Gain</span></span><br /><br /> <span data-ttu-id="60c2b-133">Сумма Без НДС</span><span class="sxs-lookup"><span data-stu-id="60c2b-133">Amount Excluding VAT</span></span><br /><br /> <span data-ttu-id="60c2b-134">Дебет 62 Поступления и платежи</span><span class="sxs-lookup"><span data-stu-id="60c2b-134">Debit 62 Payables and Receivables</span></span><br /><br /> <span data-ttu-id="60c2b-135">Кредит 90-3 Налог на добавленную стоимость</span><span class="sxs-lookup"><span data-stu-id="60c2b-135">Credit 90-3 Gain VAT</span></span><br /><br /> <span data-ttu-id="60c2b-136">Сумма НДС продаж</span><span class="sxs-lookup"><span data-stu-id="60c2b-136">Sales VAT Amount</span></span><br /><br /> <span data-ttu-id="60c2b-137">Дебет 90-3 Налог на добавленную стоимость</span><span class="sxs-lookup"><span data-stu-id="60c2b-137">Debit 90-3 Gain VAT</span></span><br /><br /> <span data-ttu-id="60c2b-138">Кредит 68 Расчеты по налогам и сборам</span><span class="sxs-lookup"><span data-stu-id="60c2b-138">Credit 68 VAT to Budget</span></span><br /><br /> <span data-ttu-id="60c2b-139">Сумма НДС продаж</span><span class="sxs-lookup"><span data-stu-id="60c2b-139">Sales VAT amount</span></span>|  
|**<Blank>**|<span data-ttu-id="60c2b-140">Дебет 62 Поступления и платежи</span><span class="sxs-lookup"><span data-stu-id="60c2b-140">Debit 62 Payables and Receivables</span></span><br /><br /> <span data-ttu-id="60c2b-141">Кредит 90-1 Прибыль</span><span class="sxs-lookup"><span data-stu-id="60c2b-141">Credit 90-1 Gain</span></span><br /><br /> <span data-ttu-id="60c2b-142">Сумма Без НДС</span><span class="sxs-lookup"><span data-stu-id="60c2b-142">Amount Excluding VAT</span></span><br /><br /> <span data-ttu-id="60c2b-143">Дебет 62 Поступления и платежи</span><span class="sxs-lookup"><span data-stu-id="60c2b-143">Debit 62 Payables and Receivables</span></span><br /><br /> <span data-ttu-id="60c2b-144">Кредит 68 Расчеты по налогам и сборам</span><span class="sxs-lookup"><span data-stu-id="60c2b-144">Credit 68 VAT to Budget</span></span><br /><br /> <span data-ttu-id="60c2b-145">Сумма НДС продаж</span><span class="sxs-lookup"><span data-stu-id="60c2b-145">Sales VAT Amount</span></span>|  

## <a name="trans-vat-account-field"></a><span data-ttu-id="60c2b-146">Поле "Транз. НДС Фин. Счет Но."</span><span class="sxs-lookup"><span data-stu-id="60c2b-146">Trans. VAT Account Field</span></span>  
<span data-ttu-id="60c2b-147">В поле **НДС транз. счет ГК** введите субсчет 90-3, "Налог на добавленную стоимость", или субсчет 62, "НДС по предоплате".</span><span class="sxs-lookup"><span data-stu-id="60c2b-147">In the **Trans. VAT Account** field, enter Subaccount 90-3 Gain VAT or Subaccount 62 Prepayment VAT.</span></span> <span data-ttu-id="60c2b-148">Если это поле пустое, для учета будет использоваться счет из учетных групп клиентов из поля **Счет дебиторской задолженности**.</span><span class="sxs-lookup"><span data-stu-id="60c2b-148">If this field is blank, the postings use the account from the Customer posting groups from the **Receivables Account** field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="60c2b-149">См. также</span><span class="sxs-lookup"><span data-stu-id="60c2b-149">See Also</span></span>  
 [<span data-ttu-id="60c2b-150">Книги НДС</span><span class="sxs-lookup"><span data-stu-id="60c2b-150">VAT Ledgers</span></span>](vat-ledgers.md)

