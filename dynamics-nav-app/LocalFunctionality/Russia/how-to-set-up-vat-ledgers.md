---
title: "Как настраивать книги НДС"
description: "Книги НДС используются для хранения сведений о НДС в транзакциях, связанных с товарами и услугами в России или с товарами, импортированными в Россию. Можно создать и сохранять различные виды книг НДС."
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
ms.openlocfilehash: c4631297198d276ba2aa75cc985b05272d4fe813
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-vat-ledgers"></a><span data-ttu-id="0b124-104">Практическое руководство. Настройка книг НДС</span><span class="sxs-lookup"><span data-stu-id="0b124-104">How to: Set Up VAT Ledgers</span></span>
<span data-ttu-id="0b124-105">Книги НДС используются для хранения сведений о НДС в транзакциях, связанных с товарами и услугами в России или с товарами, импортированными в Россию.</span><span class="sxs-lookup"><span data-stu-id="0b124-105">VAT ledgers are used to store details about VAT in transactions that involve goods and services in Russia or goods imported into Russia.</span></span> <span data-ttu-id="0b124-106">Можно создать и сохранять различные виды книг НДС.</span><span class="sxs-lookup"><span data-stu-id="0b124-106">You can create and store different kinds of VAT ledgers.</span></span> <span data-ttu-id="0b124-107">Например, можно создавать книги НДС для следующих целей:</span><span class="sxs-lookup"><span data-stu-id="0b124-107">For example, you can create VAT ledgers for:</span></span>  

- <span data-ttu-id="0b124-108">Продажи различным группам клиентов.</span><span class="sxs-lookup"><span data-stu-id="0b124-108">Sales to different groups of customers.</span></span>  
- <span data-ttu-id="0b124-109">Разницы сумма продаж и предоплаты.</span><span class="sxs-lookup"><span data-stu-id="0b124-109">Sales amount differences and prepayments.</span></span>  
- <span data-ttu-id="0b124-110">Покупки у разных групп поставщиков.</span><span class="sxs-lookup"><span data-stu-id="0b124-110">Purchases from different vendor groups.</span></span>  

<span data-ttu-id="0b124-111">Чтобы использовать книги НДС, необходимо указать соответствующие серии номеров.</span><span class="sxs-lookup"><span data-stu-id="0b124-111">To use VAT ledgers, you must specify the relevant number series.</span></span>  

## <a name="to-set-up-vat-ledgers"></a><span data-ttu-id="0b124-112">Настройка книг НДС</span><span class="sxs-lookup"><span data-stu-id="0b124-112">To set up VAT ledgers</span></span>  

1.  <span data-ttu-id="0b124-113">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка ГК**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="0b124-113">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="0b124-114">В окне **Настройка ГК** на экспресс-вкладке **Нумерация** заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="0b124-114">In the **General Ledger Setup** window, on the **Numbering** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="0b124-115">Поле</span><span class="sxs-lookup"><span data-stu-id="0b124-115">Field</span></span>|<span data-ttu-id="0b124-116">Описанием</span><span class="sxs-lookup"><span data-stu-id="0b124-116">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="0b124-117">**НДС - серия ном. книги покупок**</span><span class="sxs-lookup"><span data-stu-id="0b124-117">**VAT Purch. Ledger No. Series**</span></span>|<span data-ttu-id="0b124-118">Определяет серию номеров, которую требуется использовать для книг НДС в документах покупки.</span><span class="sxs-lookup"><span data-stu-id="0b124-118">Specifies the number series that you want to use for VAT ledgers for purchase documents.</span></span>|  
    |<span data-ttu-id="0b124-119">**НДС - серия ном. книги продаж**</span><span class="sxs-lookup"><span data-stu-id="0b124-119">**VAT Sales Ledger No. Series**</span></span>|<span data-ttu-id="0b124-120">Определяет серию номеров, которую требуется использовать для книг НДС в документах продажи.</span><span class="sxs-lookup"><span data-stu-id="0b124-120">Specifies the number series that you want to use for VAT ledgers for sales documents.</span></span>|  

     <span data-ttu-id="0b124-121">Необходимо обеспечить, чтобы документы покупки у поставщика было невозможно учесть без указания даты и номера счета.</span><span class="sxs-lookup"><span data-stu-id="0b124-121">You must ensure that vendor purchase documents cannot be posted without stating the invoice date and number.</span></span>  

3.  <span data-ttu-id="0b124-122">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Учетные группы поставщика**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="0b124-122">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.</span></span>  
4.  <span data-ttu-id="0b124-123">В окне **Учетные группы поставщика** для соответствующих учетных групп выберите поле **Счет-фактура обязательна**.</span><span class="sxs-lookup"><span data-stu-id="0b124-123">In the **Vendor Posting Groups** window, for the relevant posting groups, select the **VAT Invoice Mandatory** field.</span></span>  

    <span data-ttu-id="0b124-124">Затем необходимо настроить учет НДС.</span><span class="sxs-lookup"><span data-stu-id="0b124-124">Next, you must set up VAT posting.</span></span> <span data-ttu-id="0b124-125">Для каждой настройки учета НДС необходимо указать, должны ли операции, которые используют эту настройку, включаться в книги НДС.</span><span class="sxs-lookup"><span data-stu-id="0b124-125">For each VAT posting setup you must specify if entries that use the setup must be included in VAT ledgers.</span></span>  
5.  <span data-ttu-id="0b124-126">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка учета НДС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="0b124-126">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span></span>  
6.  <span data-ttu-id="0b124-127">В окне **Настройка учета НДС** для каждой настройки учета НДС заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="0b124-127">In the **VAT Posting Setup** window, for each VAT posting setup, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="0b124-128">Поле</span><span class="sxs-lookup"><span data-stu-id="0b124-128">Field</span></span>|<span data-ttu-id="0b124-129">Описанием</span><span class="sxs-lookup"><span data-stu-id="0b124-129">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="0b124-130">**Не Включать в Книгу НДС**</span><span class="sxs-lookup"><span data-stu-id="0b124-130">**Not Include into VAT Ledger**</span></span>|<span data-ttu-id="0b124-131">Указывает, должны ли операции, в которых используется настройка, включаться в книги НДС.</span><span class="sxs-lookup"><span data-stu-id="0b124-131">Specifies if entries that use the setup must be included in VAT ledgers.</span></span> <span data-ttu-id="0b124-132">Дополнительные сведения см. в пункте "Не включать в книгу НДС".</span><span class="sxs-lookup"><span data-stu-id="0b124-132">For more information, see Not Include into VAT Ledger.</span></span>|  
    |<span data-ttu-id="0b124-133">**Освоб. от НДС**</span><span class="sxs-lookup"><span data-stu-id="0b124-133">**VAT Exempt**</span></span>|<span data-ttu-id="0b124-134">Определяет, освобождены ли от НДС операции, использующие эту настройку учета.</span><span class="sxs-lookup"><span data-stu-id="0b124-134">Specifies if entries that use this posting setup are VAT exempt.</span></span> <span data-ttu-id="0b124-135">Дополнительные сведения см. в пункте "Освоб. от НДС".</span><span class="sxs-lookup"><span data-stu-id="0b124-135">For more information, see VAT Exempt.</span></span>|  

<span data-ttu-id="0b124-136">Теперь можно создать книги НДС для покупок и продаж.</span><span class="sxs-lookup"><span data-stu-id="0b124-136">Now, you can create VAT ledgers for purchases and sales.</span></span>  

## <a name="see-also"></a><span data-ttu-id="0b124-137">См. также</span><span class="sxs-lookup"><span data-stu-id="0b124-137">See Also</span></span>  
 [<span data-ttu-id="0b124-138">Практическое руководство. Подача отчета об НДС в налоговые органы</span><span class="sxs-lookup"><span data-stu-id="0b124-138">How to: Report VAT to Tax Authorities</span></span>](../../finance-how-report-vat.md)  
 <span data-ttu-id="0b124-139">[Практическое руководство. Регистрация НДС по заказам на покупку](how-to-register-vat-on-purchase-orders.md) </span><span class="sxs-lookup"><span data-stu-id="0b124-139">[How to: Register VAT on Purchase Orders](how-to-register-vat-on-purchase-orders.md) </span></span>  
 <span data-ttu-id="0b124-140">[Практическое руководство. Подготовка операций НДС к учету](how-to-prepare-vat-entries-for-posting.md) </span><span class="sxs-lookup"><span data-stu-id="0b124-140">[How to: Prepare VAT Entries for Posting](how-to-prepare-vat-entries-for-posting.md) </span></span>  
 <span data-ttu-id="0b124-141">[Практическое руководство. Создание книг НДС](how-to-create-vat-ledgers.md) </span><span class="sxs-lookup"><span data-stu-id="0b124-141">[How to: Create VAT Ledgers](how-to-create-vat-ledgers.md) </span></span>  
 [<span data-ttu-id="0b124-142">Практическое руководство. Создание дополнительных листов</span><span class="sxs-lookup"><span data-stu-id="0b124-142">How to: Create Additional Sheets</span></span>](how-to-create-additional-sheets.md)

