---
title: "Использование расширения миграции QuickBooks"
description: "Описывает, как использовать расширение для миграции клиентов, поставщиков, товаров и счетов из QuickBooks Online в Dynamics NAV."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: extension, migrate, data, QuickBooks, import
ms.date: 05/24/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e4854a5695f050c710440c5652d70ae7c4bc02bd
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---

# <a name="the-quickbooks-online-data-migration-extension-for-dynamics-nav"></a><span data-ttu-id="c84db-103">Расширение для миграции данных QuickBooks Online для Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="c84db-103">The QuickBooks Online Data Migration Extension for Dynamics NAV</span></span>
<span data-ttu-id="c84db-104">Это расширение входит в руководстве по сопровождаемой настройке **Миграция данных**, которое помогает переносить важные бизнес-данные из QuickBooks Online в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="c84db-104">This extension is included in the **Data Migration** assisted setup guide to help you migrate important business data from QuickBooks Online to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="c84db-105">Например, это бывает полезно, если ваш бизнес расет, и вы решили обновить свое приложение для управления бизнесом и перейти на [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="c84db-105">For example, this is useful when your business is growing, and you've decided to upgrade your business management app by starting to use [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

## <a name="what-data-can-i-import-from-quickbooks-online"></a><span data-ttu-id="c84db-106">Какие данные можно импортировать из QuickBooks Online?</span><span class="sxs-lookup"><span data-stu-id="c84db-106">What data can I import from QuickBooks Online?</span></span>
<span data-ttu-id="c84db-107">Вы можете импортировать следующие данные из QuickBooks Online в [!INCLUDE[d365fin](includes/d365fin_md.md)]:</span><span class="sxs-lookup"><span data-stu-id="c84db-107">You can import the following data from QuickBooks Online to [!INCLUDE[d365fin](includes/d365fin_md.md)]:</span></span>  

* <span data-ttu-id="c84db-108">Клиенты</span><span class="sxs-lookup"><span data-stu-id="c84db-108">Customers</span></span>
* <span data-ttu-id="c84db-109">Поставщики</span><span class="sxs-lookup"><span data-stu-id="c84db-109">Vendors</span></span>
* <span data-ttu-id="c84db-110">Товаров</span><span class="sxs-lookup"><span data-stu-id="c84db-110">Items</span></span>
* <span data-ttu-id="c84db-111">План счетов</span><span class="sxs-lookup"><span data-stu-id="c84db-111">Chart of accounts</span></span> 
* <span data-ttu-id="c84db-112">Транзакция начального сальдо в главной книге</span><span class="sxs-lookup"><span data-stu-id="c84db-112">Beginning balance transaction in the general ledger</span></span>
* <span data-ttu-id="c84db-113">Товары в наличии</span><span class="sxs-lookup"><span data-stu-id="c84db-113">On-hand quantities for inventory items</span></span>
* <span data-ttu-id="c84db-114">Открытые документы для клиентов и поставщиков, например счета, кредит-ноты и платежи</span><span class="sxs-lookup"><span data-stu-id="c84db-114">Open documents for customers and vendors, such as invoices, credit memos, and payments</span></span>

<span data-ttu-id="c84db-115">Мы переносим только полные суммы документов продажи и покупки.</span><span class="sxs-lookup"><span data-stu-id="c84db-115">We migrate only full amounts on sales and purchase documents.</span></span> <span data-ttu-id="c84db-116">Мы не обновляем частично оплаченные суммы.</span><span class="sxs-lookup"><span data-stu-id="c84db-116">We do not update partially paid amounts.</span></span> <span data-ttu-id="c84db-117">Например, если клиент оплатил 300 долларов из 500 по счету продажи, мы переносим 500 долларов.</span><span class="sxs-lookup"><span data-stu-id="c84db-117">For example, if a customer has paid 300 of a total of 500 dollars on a sales invoice, we migrate the full 500.</span></span> <span data-ttu-id="c84db-118">Если вы получили частичные платежи, их необходимо вручную обновить либо до миграции данных, либо после нее.</span><span class="sxs-lookup"><span data-stu-id="c84db-118">If you have received partial payments, you must update these manually, either before or after you migrate data.</span></span> <span data-ttu-id="c84db-119">Рекомендуется применить незакрытые транзакции перед миграцией, чтобы потом было проще работать.</span><span class="sxs-lookup"><span data-stu-id="c84db-119">We recommend that you apply outstanding transactions before you migrate, just to make things easier afterward.</span></span>

> [!NOTE]  
>   <span data-ttu-id="c84db-120">Мы не переносим заказы на покупку и заказы на продажу.</span><span class="sxs-lookup"><span data-stu-id="c84db-120">We do not migrate purchase orders or sales orders.</span></span>

## <a name="before-you-start"></a><span data-ttu-id="c84db-121">Перед началом работы</span><span class="sxs-lookup"><span data-stu-id="c84db-121">Before you start</span></span>
<span data-ttu-id="c84db-122">Важной частью процесса миграции является указание счетов, на которые должны быть перенесены транзакции.</span><span class="sxs-lookup"><span data-stu-id="c84db-122">An important part of the migration process is to specify the accounts to migrate transactions to.</span></span> <span data-ttu-id="c84db-123">Рекомендуется задать сопоставление до переноса данных.</span><span class="sxs-lookup"><span data-stu-id="c84db-123">It's a good idea to plan this mapping before you migrate data.</span></span> <span data-ttu-id="c84db-124">Например, задать счета, на которых вы учитываете транзакции для:</span><span class="sxs-lookup"><span data-stu-id="c84db-124">For example, the accounts where you post transactions for:</span></span>  
  
* <span data-ttu-id="c84db-125">Продажи товаров или услуг клиентам.</span><span class="sxs-lookup"><span data-stu-id="c84db-125">The sale of items or services to customers.</span></span>
* <span data-ttu-id="c84db-126">Покупки товаров или услуг у поставщиков.</span><span class="sxs-lookup"><span data-stu-id="c84db-126">The purchase of items or services from vendors.</span></span>  
* <span data-ttu-id="c84db-127">Коррекции в главной книге.</span><span class="sxs-lookup"><span data-stu-id="c84db-127">Adjustments in the general ledger.</span></span>  

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="c84db-128"> требует, чтобы счетам главной книги были назначены номера.</span><span class="sxs-lookup"><span data-stu-id="c84db-128"> requires that general ledger accounts have account numbers assigned to them.</span></span> <span data-ttu-id="c84db-129">Убедитесь, что номера счетов назначены в QuickBooks Online.</span><span class="sxs-lookup"><span data-stu-id="c84db-129">Make sure that account numbers are assigned to your accounts in QuickBooks Online.</span></span>

<span data-ttu-id="c84db-130">Если транзакции в QuickBooks Online содержат суммы налога, необходимо настроить налоговый счет в налоговых юрисдикциях в [!INCLUDE[d365fin](includes/d365fin_md.md)], прежде чем вы сможете учитывать транзакции.</span><span class="sxs-lookup"><span data-stu-id="c84db-130">If transactions in QuickBooks Online have tax amounts, you must set up a tax account for your tax jurisdictions in [!INCLUDE[d365fin](includes/d365fin_md.md)] before you can post transactions.</span></span>

## <a name="how-do-i-start-using-the-extension"></a><span data-ttu-id="c84db-131">Как начать использование расширения?</span><span class="sxs-lookup"><span data-stu-id="c84db-131">How do I start using the extension?</span></span>
<span data-ttu-id="c84db-132">Начать очень просто.</span><span class="sxs-lookup"><span data-stu-id="c84db-132">Getting started is easy.</span></span> <span data-ttu-id="c84db-133">Вам достаточно запустить руководство по сопровождаемой настройке **Миграция данных**.</span><span class="sxs-lookup"><span data-stu-id="c84db-133">All you need to do is run the **Data Migration** assisted setup guide.</span></span> <span data-ttu-id="c84db-134">Вот как это сделать:</span><span class="sxs-lookup"><span data-stu-id="c84db-134">Here's how:</span></span>

1. <span data-ttu-id="c84db-135">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сопровождаемая настройка**, а затем выберите **Миграция бизнес-данных**.</span><span class="sxs-lookup"><span data-stu-id="c84db-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Assisted Setup**, and then choose **Migrate business data**.</span></span>
2. <span data-ttu-id="c84db-136">На каждом этапе следуйте инструкциям руководства по сопровождаемой настройке.</span><span class="sxs-lookup"><span data-stu-id="c84db-136">Follow the instructions on each step in the assisted setup guide.</span></span>

## <a name="what-do-i-do-after-i-migrate-data"></a><span data-ttu-id="c84db-137">Что нужно сделать после переноса данных?</span><span class="sxs-lookup"><span data-stu-id="c84db-137">What do I do after I migrate data?</span></span>
<span data-ttu-id="c84db-138">После переноса данных транзакции имеют статус **Неучтенные**, чтобы их можно было проверить и внести корректировки.</span><span class="sxs-lookup"><span data-stu-id="c84db-138">After you migrate data, transactions have the status **Unposted**, so you can review them and make adjustments.</span></span> <span data-ttu-id="c84db-139">Чтобы проверить транзакции, откройте страницу, на которой они должны находиться.</span><span class="sxs-lookup"><span data-stu-id="c84db-139">To review the transactions, go to the page where you would normally find them.</span></span> <span data-ttu-id="c84db-140">Например, чтобы проверить неучтенные счета продажи, перейдите на страницу **Счета продажи**.</span><span class="sxs-lookup"><span data-stu-id="c84db-140">For example, to review unposted sales invoices, go to the **Sales Invoices** page.</span></span> <span data-ttu-id="c84db-141">Чтобы проверить журналы платежей, перейдите на страницу **Журналы платежей**.</span><span class="sxs-lookup"><span data-stu-id="c84db-141">To review payment journals, go to the **Payment Journals** page.</span></span>   

<span data-ttu-id="c84db-142">Есть несколько важных вещей, которые нужно сделать.</span><span class="sxs-lookup"><span data-stu-id="c84db-142">There are a few things in particular that you should do:</span></span>

* <span data-ttu-id="c84db-143">Если для транзакций в QuickBooks Online были заданы суммы наценки или скидки, их необходимо вручную добавить в соответствующие транзакции в [!INCLUDE[d365fin](includes/d365fin_md.md)], прежде чем учитывать их.</span><span class="sxs-lookup"><span data-stu-id="c84db-143">If the transactions in QuickBooks Online had markup or discount amounts, you must manually add the amounts to the related transactions in [!INCLUDE[d365fin](includes/d365fin_md.md)] before you post them.</span></span>
* <span data-ttu-id="c84db-144">Если вы используете налог на добавленную стоимость (НДС), вы можете добавить учетные бизнес-группы или товарные группы в параметры учета, чтобы вы могли учитывать суммы НДС.</span><span class="sxs-lookup"><span data-stu-id="c84db-144">If you are using value added tax (VAT), you may need to add a business posting group and a product posting group to the posting setup so that you can post VAT amounts.</span></span>
* <span data-ttu-id="c84db-145">Проверьте начальные сальдо счетов в главной книге.</span><span class="sxs-lookup"><span data-stu-id="c84db-145">Verify the beginning balances for accounts in the general ledger.</span></span> <span data-ttu-id="c84db-146">В QuickBooks Online не хранится текущее сальдо для всех счетов, поэтому вам может потребоваться исправить начальные сальдо.</span><span class="sxs-lookup"><span data-stu-id="c84db-146">QuickBooks Online does not store the current balance for all accounts, so you might need to correct beginning balances.</span></span>

## <a name="see-also"></a><span data-ttu-id="c84db-147">См. также</span><span class="sxs-lookup"><span data-stu-id="c84db-147">See Also</span></span>
[<span data-ttu-id="c84db-148">Импорт бизнес-данных из других финансовых систем</span><span class="sxs-lookup"><span data-stu-id="c84db-148">Importing Business Data from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="c84db-149">[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="c84db-149">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  

