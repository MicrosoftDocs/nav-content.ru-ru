---
title: "Настройка округления счета"
description: "При создании счетов можно округлить их суммы. Кроме того, согласно местным правилам или стандартам может требоваться округление счетов определенным образом, например до суммы, кратной 0,05."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: c29ee413d6ebdc326022dfb385fc66344c964c54
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="set-up-invoice-rounding"></a><span data-ttu-id="a9f19-104">Настройка округления счета</span><span class="sxs-lookup"><span data-stu-id="a9f19-104">Set Up Invoice Rounding</span></span>
<span data-ttu-id="a9f19-105">Если при создании счетов требуется округлять их суммы, можно использовать функцию автоматического округления.</span><span class="sxs-lookup"><span data-stu-id="a9f19-105">If you need to round invoice amounts when you create invoices, you can use the automatic rounding function.</span></span> <span data-ttu-id="a9f19-106">При округлении счета в него добавляется дополнительная строка с суммой округления, которая учитывается вместе с другими строками счета.</span><span class="sxs-lookup"><span data-stu-id="a9f19-106">When an invoice is rounded, an extra line is added with the rounding amount and posted with the other invoice lines.</span></span>

> [!NOTE]  
>  <span data-ttu-id="a9f19-107">Согласно местным правилам или стандартам, может потребоваться округление счетов определенным образом, например до суммы, кратной 0,05.</span><span class="sxs-lookup"><span data-stu-id="a9f19-107">Local regulations or local custom may require the invoice to be rounded in a specific way, for example, to an amount divisible by 0.05.</span></span>  
  
<span data-ttu-id="a9f19-108">Для использования автоматического округления счетов необходимо выполнить следующие действия:</span><span class="sxs-lookup"><span data-stu-id="a9f19-108">To use automatic invoice rounding, you must:</span></span>  
  
* <span data-ttu-id="a9f19-109">задать счета главной книги, в которых будут учитываться разницы от округления;</span><span class="sxs-lookup"><span data-stu-id="a9f19-109">Specify the general ledger accounts to which rounding differences will be posted.</span></span>  
* <span data-ttu-id="a9f19-110">настроить правила округления счетов в локальной и иностранной валютах;</span><span class="sxs-lookup"><span data-stu-id="a9f19-110">Set up rules for rounding invoices in local currency and in foreign currency.</span></span>  
* <span data-ttu-id="a9f19-111">активировать функцию.</span><span class="sxs-lookup"><span data-stu-id="a9f19-111">Activate the function.</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="a9f19-112">В дополнение к функциям округления счетов, можно округлять суммы счетов с помощью функции округления цены и округления суммы.</span><span class="sxs-lookup"><span data-stu-id="a9f19-112">In addition to the invoice rounding features, you can round amounts on invoices by the unit-amount rounding feature and the amount rounding feature.</span></span>  
 
## <a name="how-to-set-up-general-ledger-accounts-for-invoice-rounding-differences"></a><span data-ttu-id="a9f19-113">Практическое руководство. Настройка счетов ГК для разницы округления счета</span><span class="sxs-lookup"><span data-stu-id="a9f19-113">How to: Set up general ledger accounts for invoice rounding differences</span></span>
<span data-ttu-id="a9f19-114">Для использования функции автоматического округления сумм в счетах следует настроить счета главной книги или счета, по которым будет производиться учет ошибок округления.</span><span class="sxs-lookup"><span data-stu-id="a9f19-114">To use the automatic invoice rounding function, you must set up the general ledger account or accounts where rounding differences will be posted.</span></span> <span data-ttu-id="a9f19-115">Перед этим необходимо настроить НДС товарные группы.</span><span class="sxs-lookup"><span data-stu-id="a9f19-115">Before you can do this, you must set up VAT product posting groups.</span></span> <span data-ttu-id="a9f19-116">Дополнительные сведения см. в разделе [Настройка НДС](finance-setup-vat.md).</span><span class="sxs-lookup"><span data-stu-id="a9f19-116">For more information, see [Set up VAT](finance-setup-vat.md).</span></span>  
  
### <a name="to-set-up-general-ledger-accounts-for-invoice-rounding-differences"></a><span data-ttu-id="a9f19-117">Настройка счетов главной книги для разницы округления счета</span><span class="sxs-lookup"><span data-stu-id="a9f19-117">To set up general ledger accounts for invoice rounding differences</span></span>  
1. <span data-ttu-id="a9f19-118">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **План счетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a9f19-118">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a9f19-119">Настройте счет на странице **План счетов** и назовите его **Округление счета** либо аналогичным образом.</span><span class="sxs-lookup"><span data-stu-id="a9f19-119">On the **Chart of Accounts** page, set up the account and name it **Invoice Rounding** or something similar.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="a9f19-120"> будет использовать название счета в качестве текста для округляемых счетов.</span><span class="sxs-lookup"><span data-stu-id="a9f19-120"> will use the account name as text for invoices that are rounded.</span></span>  
3. <span data-ttu-id="a9f19-121">В зависимости от того, используется ли НДС или налог с продаж, в поле **Налог товарная группа** или **НДС товарная группа** выберите учетную группу для округленных сумм.</span><span class="sxs-lookup"><span data-stu-id="a9f19-121">Depending on whether you use VAT or sales tax, in the **Tax Prod. Posting Group** or **VAT Prod. Posting Group** fields, choose a posting group for rounded amounts.</span></span> <span data-ttu-id="a9f19-122">Можно настроить новый код группы, который будет использоваться для округления счетов.</span><span class="sxs-lookup"><span data-stu-id="a9f19-122">You may want to set up a new group code to use for invoice rounding.</span></span>
4. <span data-ttu-id="a9f19-123">Оставьте поле **Общий тип учета** и поле **Налог бизнес-группа** или **НДС бизнес-группа** пустыми.</span><span class="sxs-lookup"><span data-stu-id="a9f19-123">Leave the **Gen. Posting Type**, and either the **Tax Bus. Posting Group** or **VAT Bus. Posting Group** fields blank.</span></span> <!-- Why do we say to leave these blank, when there are a lot of other fields we also leave blank but don't mention? -->  
  
<span data-ttu-id="a9f19-124">Теперь можно назначить счет округления счета учетным группам на странице **Учетные группы поставщика**.</span><span class="sxs-lookup"><span data-stu-id="a9f19-124">Now you can assign the invoice rounding account to posting groups on the **Vendor Posting Groups** page.</span></span>  <!-- Why only the vendor posting groups? -->

## <a name="how-to-set-up-rounding-for-foreign-and-local-currencies"></a><span data-ttu-id="a9f19-125">Практическое руководство. Настройка округления для иностранной и местной валюты</span><span class="sxs-lookup"><span data-stu-id="a9f19-125">How to: Set up rounding for foreign and local currencies</span></span>
<span data-ttu-id="a9f19-126">Прежде чем использовать функцию автоматического округления, необходимо настроить правила округления для иностранной и местной валют.</span><span class="sxs-lookup"><span data-stu-id="a9f19-126">Before you can use the automatic invoice rounding function, you must set up rounding rules for foreign and local currencies.</span></span>

### <a name="to-set-up-rounding-for-foreign-currencies"></a><span data-ttu-id="a9f19-127">Для настройки правил округления для иностранных валют</span><span class="sxs-lookup"><span data-stu-id="a9f19-127">To set up rounding for foreign currencies</span></span>  
1. <span data-ttu-id="a9f19-128">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Валюты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a9f19-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Currencies**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a9f19-129">На странице **Валюты** выберите иностранную валюту, чтобы открыть окно **Валютная карточка**, затем заполните поля **Точность округления суммы**, **Точность округления цены**, **Точность округления счета** и **Тип округления счета**.</span><span class="sxs-lookup"><span data-stu-id="a9f19-129">On the **Currencies** page, choose the foreign currency to open the **Currency Card**, and then fill in the **Amount Rounding Precision**, **Unit-Amount Rounding Precision**, **Invoice Rounding Precision** and **Invoice Rounding Type** fields.</span></span>
  
### <a name="to-set-up-rounding-for-your-local-currency"></a><span data-ttu-id="a9f19-130">Для настройки округления для локальной валюты</span><span class="sxs-lookup"><span data-stu-id="a9f19-130">To set up rounding for your local currency</span></span>
1. <span data-ttu-id="a9f19-131">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка ГК**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a9f19-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a9f19-132">На странице **Настройка ГК** на экспресс-вкладке **Общее** заполните поля **Точность округления счета** и **Тип округления счета**.</span><span class="sxs-lookup"><span data-stu-id="a9f19-132">On the **General Ledger Setup** page, on the **General** FastTab, fill in the **Inv. Rounding Precision** and **Inv. Rounding Type** fields.</span></span>  

## <a name="how-to-activate-the-invoice-rounding-function"></a><span data-ttu-id="a9f19-133">Практическое руководство. Активизация функции округления счета</span><span class="sxs-lookup"><span data-stu-id="a9f19-133">How to: Activate the invoice rounding function</span></span>  
<span data-ttu-id="a9f19-134">Чтобы автоматически округлять счета покупки и продажи, следует активизировать функцию округления счета.</span><span class="sxs-lookup"><span data-stu-id="a9f19-134">To ensure that sales and purchase invoices are rounded automatically, you must activate the invoice rounding function.</span></span> <span data-ttu-id="a9f19-135">Округление счета включается отдельно для счетов продажи и покупки.</span><span class="sxs-lookup"><span data-stu-id="a9f19-135">You activate invoice rounding separately for sales and purchase invoices.</span></span>

1. <span data-ttu-id="a9f19-136">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка модуля "Продажи"** или **Настройка модуля "Покупки"**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a9f19-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales & Receivables Setup** or **Purchases & Payables Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a9f19-137">На экспресс-вкладке **Общее** установите флажок **Округление счета**.</span><span class="sxs-lookup"><span data-stu-id="a9f19-137">On the **General** FastTab, choose the **Invoice Rounding** check box.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="a9f19-138">См. также</span><span class="sxs-lookup"><span data-stu-id="a9f19-138">See Also</span></span>  
[<span data-ttu-id="a9f19-139">Практическое руководство. Выставление счетов продажи</span><span class="sxs-lookup"><span data-stu-id="a9f19-139">How to: Invoice Sales</span></span>](sales-how-invoice-sales.md)  
[<span data-ttu-id="a9f19-140">Практическое руководство. Регистрация покупок</span><span class="sxs-lookup"><span data-stu-id="a9f19-140">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)
