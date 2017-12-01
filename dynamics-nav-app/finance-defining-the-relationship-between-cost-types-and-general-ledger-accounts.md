---
title: "Определение отношения между типами затрат и счетами главной книги."
description: "Узнайте, как определять отношение между типом себестоимости и счетом ГК."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost types, general ledger
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: fcaeab6a164abf20011beec35ec004057098b360
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="defining-the-relationship-between-cost-types-and-general-ledger-accounts"></a><span data-ttu-id="c3e5b-103">Определение отношения между типами затрат и счетами главной книги.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-103">Defining the Relationship Between Cost Types and General Ledger Accounts</span></span>
<span data-ttu-id="c3e5b-104">Отношение между типом себестоимости и счетом главной книги создается в типе себестоимости и в счете главной книги.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-104">The relationship between the cost type and the general ledger account is created in the cost type and in the general ledger account.</span></span>  

* <span data-ttu-id="c3e5b-105">Поле **Диапазон счетов ГК** в таблице **Тип затрат** определяет, какие счета главной книги относятся к типу затрат.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-105">The **G/L Account Range** field in the **Cost Type** table establishes which general ledger accounts belong to a cost type.</span></span>  
* <span data-ttu-id="c3e5b-106">Поле **Номер типа затрат**</span><span class="sxs-lookup"><span data-stu-id="c3e5b-106">The **Cost Type No.**</span></span> <span data-ttu-id="c3e5b-107">в диаграмме счетов определяет, к какому типу затрат относится счет главной книги.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-107">field in the chart of accounts establishes which cost type a general ledger account belongs to.</span></span>  

<span data-ttu-id="c3e5b-108">Эти 2 поля заполняются автоматически при использовании функции **Извлечь типы затрат из плана счетов**.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-108">These two fields are filled automatically when you use the **Get Cost Types from Chart of Accounts** function.</span></span>  

## <a name="relationship-between-general-ledger-accounts-and-cost-types"></a><span data-ttu-id="c3e5b-109">Взаимосвязь между счетами главной книги и типами себестоимости.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-109">Relationship Between General Ledger Accounts and Cost Types</span></span>  
<span data-ttu-id="c3e5b-110">Существует отношение n:1 между счетами главной книги и типами себестоимости.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-110">There is an n:1 relationship between general ledger accounts and cost types.</span></span> <span data-ttu-id="c3e5b-111">Несколько счетов Главной книги может принадлежать к одному типу себестоимости, но каждый финансовый счет может принадлежать только к одному типу себестоимости.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-111">Several general ledger accounts can belong to one cost type, but each general ledger account belongs to only one cost type.</span></span> <span data-ttu-id="c3e5b-112">В следующей таблице описываются подробные сведения в отношении.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-112">The following table describes the details in the relationship.</span></span>  

|<span data-ttu-id="c3e5b-113">Связь</span><span class="sxs-lookup"><span data-stu-id="c3e5b-113">Relationship</span></span>|<span data-ttu-id="c3e5b-114">**Диапазон счетов ГК**</span><span class="sxs-lookup"><span data-stu-id="c3e5b-114">**G/L Account Range**</span></span>|<span data-ttu-id="c3e5b-115">**Номер типа затрат**</span><span class="sxs-lookup"><span data-stu-id="c3e5b-115">**Cost Type No.**</span></span>|  
|------------------|------------------------------------------------|-------------------------------------------|  
|<span data-ttu-id="c3e5b-116">Один счет Главной книги для каждого типа себестоимости</span><span class="sxs-lookup"><span data-stu-id="c3e5b-116">One general ledger account for each cost type</span></span>|<span data-ttu-id="c3e5b-117">Один счет Главной книги</span><span class="sxs-lookup"><span data-stu-id="c3e5b-117">One general ledger account</span></span>|<span data-ttu-id="c3e5b-118">Один тип себестоимости</span><span class="sxs-lookup"><span data-stu-id="c3e5b-118">One cost type</span></span>|  
|<span data-ttu-id="c3e5b-119">Несколько счетов Главной книги для одного типа себестоимости</span><span class="sxs-lookup"><span data-stu-id="c3e5b-119">Several general ledger accounts for one cost type</span></span>|<span data-ttu-id="c3e5b-120">Диапазон счетов Главной книги, например, 7110..7193 для каждого счета Главной книги</span><span class="sxs-lookup"><span data-stu-id="c3e5b-120">General ledger account range, for example, 7110..7193 for each general ledger account</span></span>|<span data-ttu-id="c3e5b-121">Для каждого счета Главной книги в диапазоне существует только один тип затрат</span><span class="sxs-lookup"><span data-stu-id="c3e5b-121">For each general ledger account in the range, there is only one cost type</span></span>|  
|<span data-ttu-id="c3e5b-122">Типы затрат без соответствующих счетов Главной книги</span><span class="sxs-lookup"><span data-stu-id="c3e5b-122">Cost types without corresponding general ledger accounts</span></span>|<Empty>||  
|<span data-ttu-id="c3e5b-123">Счета Главной книги для данных операций не будут перенесены</span><span class="sxs-lookup"><span data-stu-id="c3e5b-123">General ledger accounts whose entries will not be transferred</span></span>||<Empty>|  

## <a name="cost-types-without-a-relationship-to-the-general-ledger"></a><span data-ttu-id="c3e5b-124">Типы затрат без отношения с главной книгой</span><span class="sxs-lookup"><span data-stu-id="c3e5b-124">Cost Types Without a Relationship to the General Ledger</span></span>  
<span data-ttu-id="c3e5b-125">Тип затрат не может иметь связи со счетами Главной книги, если истинно одно из следующих условий:</span><span class="sxs-lookup"><span data-stu-id="c3e5b-125">A cost type may not have a relationship to general ledger accounts if one of the following conditions is true:</span></span>  

* <span data-ttu-id="c3e5b-126">Счета для операционного учета, например "Вычисляемый процент и амортизацию", принимают только расходы из операционного учета.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-126">Accounts for operational accounting, such as Calc. Interest and Depreciation, only take costs from the operational accounting.</span></span>  
* <span data-ttu-id="c3e5b-127">Такие типы затрат, как 9902, 9901 и 9903 в базе данных [!INCLUDE[d365fin](includes/d365fin_md.md)], используются как дебетовые и кредитовые счета для распределения.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-127">Helping cost types, such as cost types 9901, 9902, and 9903 in the [!INCLUDE[d365fin](includes/d365fin_md.md)] database, are used as credit and debit accounts for allocations.</span></span>  
* <span data-ttu-id="c3e5b-128">Вспомогательный счет, 9920 в базе данных [!INCLUDE[d365fin](includes/d365fin_md.md)], содержит фактические начисления, которые показывают разницу между себестоимостью и расходами из главной книги.</span><span class="sxs-lookup"><span data-stu-id="c3e5b-128">The helping account, 9920 in the [!INCLUDE[d365fin](includes/d365fin_md.md)] database, contains actual accruals that show the difference between costs and the expense from the general ledger.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c3e5b-129">См. также</span><span class="sxs-lookup"><span data-stu-id="c3e5b-129">See Also</span></span>  
[<span data-ttu-id="c3e5b-130">Учет по затратам</span><span class="sxs-lookup"><span data-stu-id="c3e5b-130">Accounting for Costs</span></span>](finance-manage-cost-accounting.md)  
<span data-ttu-id="c3e5b-131">[Настройка учета затрат](finance-set-up-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="c3e5b-131">[Setting Up Cost Accounting](finance-set-up-cost-accounting.md) </span></span>  
[<span data-ttu-id="c3e5b-132">Об учете затрат</span><span class="sxs-lookup"><span data-stu-id="c3e5b-132">About Cost Accounting</span></span>](finance-about-cost-accounting.md)  
<span data-ttu-id="c3e5b-133">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c3e5b-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

