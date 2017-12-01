---
title: "Налоговый Учет"
description: "В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно настроить и вести налоговые регистры для отслеживания подлежащих налогообложению прибылей и убытков."
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
ms.openlocfilehash: c28b21296f83076d8c057d839e8dab4df8bee62b
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="tax-accounting"></a><span data-ttu-id="e38dd-103">Налоговый Учет</span><span class="sxs-lookup"><span data-stu-id="e38dd-103">Tax Accounting</span></span>
<span data-ttu-id="e38dd-104">В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно настроить и вести налоговые регистры для отслеживания подлежащих налогообложению прибылей и убытков.</span><span class="sxs-lookup"><span data-stu-id="e38dd-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can set up and maintain tax registers to track taxable profits and losses.</span></span> <span data-ttu-id="e38dd-105">Это основано на следующих методах налогового учета:</span><span class="sxs-lookup"><span data-stu-id="e38dd-105">This is based on the following tax accounting principles:</span></span>  

- <span data-ttu-id="e38dd-106">Финансовая база данных используется для налогового учета.</span><span class="sxs-lookup"><span data-stu-id="e38dd-106">The financial database is used for tax accounting.</span></span>  
- <span data-ttu-id="e38dd-107">План счетов используется для отслеживания налогооблагаемых прибылей и убытков.</span><span class="sxs-lookup"><span data-stu-id="e38dd-107">The chart of accounts is used to track taxable profits and losses.</span></span>  
- <span data-ttu-id="e38dd-108">Доходы и расходы записываются с использованием отдельных субсчетов и измерений.</span><span class="sxs-lookup"><span data-stu-id="e38dd-108">Income and expenses are recorded using separate subaccounts and dimensions.</span></span>  
- <span data-ttu-id="e38dd-109">Транзакции и расходы основных средств для будущих периодов отслеживаются с использованием книги амортизации для налогового учета.</span><span class="sxs-lookup"><span data-stu-id="e38dd-109">Fixed asset transactions and expenses for future periods are tracked using the depreciation book for tax accounting.</span></span>  
- <span data-ttu-id="e38dd-110">Налоговые регистры группируются и суммируются ежемесячно.</span><span class="sxs-lookup"><span data-stu-id="e38dd-110">Tax registers are grouped and totaled monthly.</span></span> <span data-ttu-id="e38dd-111">В каждом регистре содержится 12 значений для налогового периода 12 месяцев.</span><span class="sxs-lookup"><span data-stu-id="e38dd-111">Each register has 12 values for a 12 month tax period.</span></span>  

<span data-ttu-id="e38dd-112">Поскольку [!INCLUDE[navnow](../../includes/navnow_md.md)] сохраняет историю всех транзакций, подробная информация из транзакций, которая изменяет налогооблагаемую прибыль, автоматически отслеживается.</span><span class="sxs-lookup"><span data-stu-id="e38dd-112">Because [!INCLUDE[navnow](../../includes/navnow_md.md)] keeps the history of all transactions, detailed information from a transaction that changes taxable profits is automatically tracked.</span></span> <span data-ttu-id="e38dd-113">Собранные сведения отображаются в налоговых регистрах в соответствии с принципами достоверности и законности налога.</span><span class="sxs-lookup"><span data-stu-id="e38dd-113">The information collected in tax registers meets the principles of tax reliability and tax validity.</span></span>  

## <a name="tax-registers"></a><span data-ttu-id="e38dd-114">Налоговые регистры</span><span class="sxs-lookup"><span data-stu-id="e38dd-114">Tax Registers</span></span>  
<span data-ttu-id="e38dd-115">Для отслеживания налогооблагаемых прибылей и убытков используются налоговые регистры двух типов.</span><span class="sxs-lookup"><span data-stu-id="e38dd-115">There are two types of tax registers that are used for tracking taxable profits and losses.</span></span>  

|<span data-ttu-id="e38dd-116">Тип налогового регистра</span><span class="sxs-lookup"><span data-stu-id="e38dd-116">Tax Register Type</span></span>|<span data-ttu-id="e38dd-117">Описанием</span><span class="sxs-lookup"><span data-stu-id="e38dd-117">Description</span></span>|  
|-----------------------|---------------------------------------|  
|<span data-ttu-id="e38dd-118">Аналитический налоговый регистр</span><span class="sxs-lookup"><span data-stu-id="e38dd-118">Analytic Tax Register</span></span>|<span data-ttu-id="e38dd-119">Аналитический регистр основан на операциях книги для налогооблагаемых транзакций.</span><span class="sxs-lookup"><span data-stu-id="e38dd-119">An analytic register is based on ledger entries for taxable transactions.</span></span> <span data-ttu-id="e38dd-120">Информация обеспечивает непрерывное отображение в хронологической последовательности бизнес-операций, что позволяет отслеживать налогооблагаемые прибыли и убытки на основе налоговых кодов.</span><span class="sxs-lookup"><span data-stu-id="e38dd-120">The information provides a continuous chronological reflection of business operations, which tracks taxable profits and losses based on tax codes.</span></span>|  
|<span data-ttu-id="e38dd-121">Синтетический налоговый регистр</span><span class="sxs-lookup"><span data-stu-id="e38dd-121">Synthetic Tax Register</span></span>|<span data-ttu-id="e38dd-122">Синтетический регистр основан на суммарной и расчетной информации из аналитического регистра или другого синтетического регистра.</span><span class="sxs-lookup"><span data-stu-id="e38dd-122">A synthetic register is based on summarized and calculated information from an analytic register or another synthetic register.</span></span>|  

<span data-ttu-id="e38dd-123">Транзакции обрабатываются с помощью определенных методов налогового учета, которые применяются к следующим типам налоговых регистров.</span><span class="sxs-lookup"><span data-stu-id="e38dd-123">Transactions are processed using specific tax accounting principles that are applied to the following types of tax registers.</span></span>  

|<span data-ttu-id="e38dd-124">Налоговый регистр</span><span class="sxs-lookup"><span data-stu-id="e38dd-124">Tax Register</span></span>|<span data-ttu-id="e38dd-125">Описанием</span><span class="sxs-lookup"><span data-stu-id="e38dd-125">Description</span></span>|  
|------------------|---------------------------------------|  
|<span data-ttu-id="e38dd-126">Операция главной книги</span><span class="sxs-lookup"><span data-stu-id="e38dd-126">General Ledger Entry</span></span>|<span data-ttu-id="e38dd-127">Аналитический регистр основан на операциях транзакций главной книги.</span><span class="sxs-lookup"><span data-stu-id="e38dd-127">An analytic register based on general ledger transaction entries.</span></span>|  
|<span data-ttu-id="e38dd-128">Операция по КП</span><span class="sxs-lookup"><span data-stu-id="e38dd-128">CV Entry</span></span>|<span data-ttu-id="e38dd-129">Группа аналитических регистров основана на информации, связанной с обязательствами дебиторов и кредиторов.</span><span class="sxs-lookup"><span data-stu-id="e38dd-129">A group of analytic registers based on information associated with debtor or creditor liabilities.</span></span>|  
|<span data-ttu-id="e38dd-130">Операция ОС</span><span class="sxs-lookup"><span data-stu-id="e38dd-130">Fixed Asset Entry</span></span>|<span data-ttu-id="e38dd-131">Группа аналитических регистров основана на налоговых данных для основных средств.</span><span class="sxs-lookup"><span data-stu-id="e38dd-131">A group of analytic registers based on tax data for fixed assets.</span></span> <span data-ttu-id="e38dd-132">Эта группа создается с использованием книги ОС и книги амортизации для налогового учета, которая не интегрирована с книгой финансового учета.</span><span class="sxs-lookup"><span data-stu-id="e38dd-132">This group is created by using a fixed asset ledger and a tax depreciation book that is not integrated with the financial accounting ledger.</span></span>|  
|<span data-ttu-id="e38dd-133">Операция товара</span><span class="sxs-lookup"><span data-stu-id="e38dd-133">Item Entry</span></span>|<span data-ttu-id="e38dd-134">Аналитический регистр основан на учтенных товарных операциях.</span><span class="sxs-lookup"><span data-stu-id="e38dd-134">An analytic register based on posted item transactions.</span></span>|  
|<span data-ttu-id="e38dd-135">Операция РБП</span><span class="sxs-lookup"><span data-stu-id="e38dd-135">Future Expense Entry</span></span>|<span data-ttu-id="e38dd-136">Группа аналитических регистров основана на налоговых данных для расходов будущих периодов.</span><span class="sxs-lookup"><span data-stu-id="e38dd-136">A group of analytic registers based on tax data for future expenses.</span></span> <span data-ttu-id="e38dd-137">Эта группа создается с использованием книги ОС и книги амортизации для налогового учета, которая не интегрирована с книгой финансового учета.</span><span class="sxs-lookup"><span data-stu-id="e38dd-137">This group is created by using a fixed asset ledger and a tax depreciation book that is not integrated with the financial accounting ledger.</span></span>|  
|<span data-ttu-id="e38dd-138">Накопление</span><span class="sxs-lookup"><span data-stu-id="e38dd-138">Accumulation</span></span>|<span data-ttu-id="e38dd-139">Синтетический регистр основан на расчетных алгоритмах, определенных при настройке налогового регистра.</span><span class="sxs-lookup"><span data-stu-id="e38dd-139">A synthetic register based on calculated algorithms defined during tax register set up.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="e38dd-140">См. также</span><span class="sxs-lookup"><span data-stu-id="e38dd-140">See Also</span></span>  
 <span data-ttu-id="e38dd-141">[Практическое руководство. Настройка налогового учета](how-to-set-up-tax-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="e38dd-141">[How to: Set Up Tax Accounting](how-to-set-up-tax-accounting.md) </span></span>  
 <span data-ttu-id="e38dd-142">[Налоговые регистры](tax-registers.md) </span><span class="sxs-lookup"><span data-stu-id="e38dd-142">[Tax Registers](tax-registers.md) </span></span>  
 <span data-ttu-id="e38dd-143">[Практическое руководство. Создание налоговых регистров](how-to-create-tax-registers.md) </span><span class="sxs-lookup"><span data-stu-id="e38dd-143">[How to: Create Tax Registers](how-to-create-tax-registers.md) </span></span>  
 <span data-ttu-id="e38dd-144">[Практическое руководство. Настройка секций налогового регистра](how-to-set-up-tax-register-sections.md) </span><span class="sxs-lookup"><span data-stu-id="e38dd-144">[How to: Set Up Tax Register Sections](how-to-set-up-tax-register-sections.md) </span></span>  
 <span data-ttu-id="e38dd-145">[Налоговые разницы](tax-differences.md) </span><span class="sxs-lookup"><span data-stu-id="e38dd-145">[Tax Differences](tax-differences.md) </span></span>  
 [<span data-ttu-id="e38dd-146">Налоговые отчеты</span><span class="sxs-lookup"><span data-stu-id="e38dd-146">Tax Reports</span></span>](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3)

