---
title: "Книги НДС"
description: "Функция книги НДС позволяет создавать и печатать различные отчеты."
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
ms.openlocfilehash: eb5c13dab47cb8e88e607a193f7892cc948cb186
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="vat-ledgers"></a><span data-ttu-id="db32f-103">Книги НДС</span><span class="sxs-lookup"><span data-stu-id="db32f-103">VAT Ledgers</span></span>
<span data-ttu-id="db32f-104">Функция книги НДС позволяет создавать и печатать следующие окна:</span><span class="sxs-lookup"><span data-stu-id="db32f-104">The VAT ledger feature enables you to create and print the following windows:</span></span>  

- <span data-ttu-id="db32f-105">НДС Книга покупок</span><span class="sxs-lookup"><span data-stu-id="db32f-105">VAT Purchase Ledger</span></span>  
- <span data-ttu-id="db32f-106">НДС Книга продаж</span><span class="sxs-lookup"><span data-stu-id="db32f-106">VAT Sales Ledger</span></span>  
- <span data-ttu-id="db32f-107">Дополнительный лист НДС книги покупок</span><span class="sxs-lookup"><span data-stu-id="db32f-107">VAT Purchase Ledger Additional Sheet</span></span>  
- <span data-ttu-id="db32f-108">Дополнительный лист НДС книги продаж</span><span class="sxs-lookup"><span data-stu-id="db32f-108">VAT Sales Ledger Additional Sheet</span></span>  

## <a name="vat-purchase-ledgers-and-vat-sales-ledgers"></a><span data-ttu-id="db32f-109">"НДС - книги покупок" и "НДС - книги продаж"</span><span class="sxs-lookup"><span data-stu-id="db32f-109">VAT Purchase Ledgers and VAT Sales Ledgers</span></span>  
<span data-ttu-id="db32f-110">Перед созданием книг НДС необходимо настроить серию номеров и группы учета поставщиков.</span><span class="sxs-lookup"><span data-stu-id="db32f-110">Before you can create VAT ledgers, you must set up number series and vendor posting groups.</span></span> <span data-ttu-id="db32f-111">Также необходимо настроить учетные группы НДС для определения, как операции НДС должны быть включены в книги НДС.</span><span class="sxs-lookup"><span data-stu-id="db32f-111">You must also set up VAT posting groups to identify how VAT entries must be included in VAT ledgers.</span></span> <span data-ttu-id="db32f-112">Кроме того, для каждой настройки учета НДС следует определить, должны ли операции, которые используют эту настройку, включаться в книги НДС, а также освобождены ли эти операции от НДС.</span><span class="sxs-lookup"><span data-stu-id="db32f-112">Also, for each VAT posting setup, you must specify if entries that use the setup must be included in VAT ledgers, and if the entries are VAT exempt.</span></span> <span data-ttu-id="db32f-113">Дополнительные сведения см. в разделе [Практическое руководство. Настройка книг НДС](how-to-set-up-vat-ledgers.md).</span><span class="sxs-lookup"><span data-stu-id="db32f-113">For more information, see [How to: Set Up VAT Ledgers](how-to-set-up-vat-ledgers.md).</span></span>  

<span data-ttu-id="db32f-114">Можно создать любое количество книг НДС.</span><span class="sxs-lookup"><span data-stu-id="db32f-114">You can create and store any number of VAT ledgers.</span></span> <span data-ttu-id="db32f-115">Например, можно создать следующие:</span><span class="sxs-lookup"><span data-stu-id="db32f-115">For example, you can create the following:</span></span>  

- <span data-ttu-id="db32f-116">Книги продаж для различных групп клиентов.</span><span class="sxs-lookup"><span data-stu-id="db32f-116">Sales ledgers for different groups of customers.</span></span>  
- <span data-ttu-id="db32f-117">Дополнительные книги продаж для разниц суммы и предоплат.</span><span class="sxs-lookup"><span data-stu-id="db32f-117">Additional sales ledgers for amount differences and prepayments.</span></span>  
- <span data-ttu-id="db32f-118">Объединенные книги продаж для компании в целом.</span><span class="sxs-lookup"><span data-stu-id="db32f-118">Joint sales ledgers for the whole company.</span></span>  

<span data-ttu-id="db32f-119">Для создания книги НДС необходимо сначала определить тип книги НДС, а затем следует добавить строки в книгу НДС покупок или книгу НДС продаж с помощью пакетных заданий **Создание книги покупок** и **Создание книги продаж**.</span><span class="sxs-lookup"><span data-stu-id="db32f-119">To create a VAT ledger, first you must define a VAT ledger type, and then you must add lines to the VAT purchase ledger or VAT sales ledger by using the **Create VAT Purchase Ledger** and **Create VAT Sales Ledger** batch jobs.</span></span> <span data-ttu-id="db32f-120">После добавления строк в книгу НДС можно распечатать ее.</span><span class="sxs-lookup"><span data-stu-id="db32f-120">When you have added lines to the VAT ledger, you can print it.</span></span>  

<span data-ttu-id="db32f-121">Дополнительные сведения см. в разделе [Практическое руководство. Создание книг НДС](how-to-create-vat-ledgers.md).</span><span class="sxs-lookup"><span data-stu-id="db32f-121">For more information, see [How to: Create VAT Ledgers](how-to-create-vat-ledgers.md).</span></span>  

## <a name="marking-a-vat-purchase-ledger"></a><span data-ttu-id="db32f-122">Маркировка книги НДС покупок</span><span class="sxs-lookup"><span data-stu-id="db32f-122">Marking a VAT Purchase Ledger</span></span>  
<span data-ttu-id="db32f-123">НДС для документов покупки должен быть отражен в книге покупок.</span><span class="sxs-lookup"><span data-stu-id="db32f-123">The VAT for purchase documents must be reflected in the purchase ledger.</span></span> <span data-ttu-id="db32f-124">Возвраты от клиентов должны отражаться в книгах покупок.</span><span class="sxs-lookup"><span data-stu-id="db32f-124">Return orders of the customers must be reflected in purchase books.</span></span>  

<span data-ttu-id="db32f-125">В следующей процедуре показан порядок маркировки журнала "НДС Книга Покупок".</span><span class="sxs-lookup"><span data-stu-id="db32f-125">The following procedure shows how to mark a VAT purchase ledger.</span></span>  

1.  <span data-ttu-id="db32f-126">В окне **Возврат продажи** или **Кредит-нота продажи** установите флажок **Включить в НДС книгу покупок**.</span><span class="sxs-lookup"><span data-stu-id="db32f-126">In the **Sales Return Order** window or the **Sales Credit Memo** window, select the **Include in Purch. VAT Ledger** check box.</span></span>  

<span data-ttu-id="db32f-127">Эти маркированные документы будут отражены в книге покупок или книге продаж.</span><span class="sxs-lookup"><span data-stu-id="db32f-127">These marked documents will be reflected in the purchase book or in the sales book.</span></span> <span data-ttu-id="db32f-128">Возвраты маркируются по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="db32f-128">Sales return orders are marked by default.</span></span>  

## <a name="see-also"></a><span data-ttu-id="db32f-129">См. также</span><span class="sxs-lookup"><span data-stu-id="db32f-129">See Also</span></span>  
 <span data-ttu-id="db32f-130">[Практическое руководство. Настройка книг НДС](how-to-set-up-vat-ledgers.md) </span><span class="sxs-lookup"><span data-stu-id="db32f-130">[How to: Set Up VAT Ledgers](how-to-set-up-vat-ledgers.md) </span></span>  
 <span data-ttu-id="db32f-131">[Практическое руководство. Создание книг НДС](how-to-create-vat-ledgers.md) </span><span class="sxs-lookup"><span data-stu-id="db32f-131">[How to: Create VAT Ledgers](how-to-create-vat-ledgers.md) </span></span>  
 <span data-ttu-id="db32f-132">[Практическое руководство. Создание дополнительных листов](how-to-create-additional-sheets.md) </span><span class="sxs-lookup"><span data-stu-id="db32f-132">[How to: Create Additional Sheets](how-to-create-additional-sheets.md) </span></span>  
 <span data-ttu-id="db32f-133">[Учет НДС в продажах](posting-vat-on-sales.md) </span><span class="sxs-lookup"><span data-stu-id="db32f-133">[Posting VAT on Sales](posting-vat-on-sales.md) </span></span>  
 [<span data-ttu-id="db32f-134">Суммовая разница</span><span class="sxs-lookup"><span data-stu-id="db32f-134">Amount Difference</span></span>](assetId:///ecc3830d-d498-44a3-bdb6-79e094d620e9)

