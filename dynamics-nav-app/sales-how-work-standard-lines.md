---
title: "Настройка и использование стандартных строка для типовых продаж и покупок"
description: "Вы можете настроить строки покупок и продаж, которые вы регулярно осуществляете, а затем вставлять их в документы продажи и покупки, чтобы быстро заполнять строки стандартной информацией."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: trade, sell, replenishment
ms.date: 07/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d3e7b514dfc91346a697b3c85cf36d7d69f56ddc
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-recurring-sales-and-purchase-lines"></a><span data-ttu-id="fb539-103">Практическое руководство. Создание типовых строк продажи и покупки</span><span class="sxs-lookup"><span data-stu-id="fb539-103">How to: Create Recurring Sales and Purchase Lines</span></span>
<span data-ttu-id="fb539-104">Если вам часто приходится создавать строки покупки и продажи с одинаковыми данными, вы можете настроить стандартные строки, которые затем можно вставлять в документы типовых продаж и покупок, например для типовых заказов на пополнение.</span><span class="sxs-lookup"><span data-stu-id="fb539-104">If you often need to create sales and purchase lines with similar information, you can set up standard lines that you can then insert on recurring sales and purchase documents, for example, for recurring replenishment orders.</span></span>  

<span data-ttu-id="fb539-105">Ниже приводится процедура работы со стандартными строками продажи.</span><span class="sxs-lookup"><span data-stu-id="fb539-105">The following procedure shows how to work with standard sales lines.</span></span> <span data-ttu-id="fb539-106">Она аналогична процедуре для стандартных строк покупки.</span><span class="sxs-lookup"><span data-stu-id="fb539-106">It works in a similar way for standard purchase lines.</span></span>  

## <a name="to-set-up-standard-sales-lines"></a><span data-ttu-id="fb539-107">Настройка стандартных строк продажи</span><span class="sxs-lookup"><span data-stu-id="fb539-107">To set up standard sales lines</span></span>  
1. <span data-ttu-id="fb539-108">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Стандартные коды продажи**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="fb539-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Standard Sales Codes**, and then choose the related link.</span></span>  
2. <span data-ttu-id="fb539-109">В окне **Стандартные коды продажи** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="fb539-109">In the **Standard Sales Lines** window, choose the **New** action.</span></span>  
3. <span data-ttu-id="fb539-110">На экспресс-вкладке **Общее** заполните необходимые поля.</span><span class="sxs-lookup"><span data-stu-id="fb539-110">On the **General** FastTab, fill the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
4. <span data-ttu-id="fb539-111">На экспресс-вкладке **Строки** заполните поля для подготовки строк продажи, которые отражают стандартные строки, которые ожидаются как типовые в документах продажи.</span><span class="sxs-lookup"><span data-stu-id="fb539-111">On the **Lines** FastTab, enter information in the fields to prepare sales lines that reflect the standard lines that you expect to use as recurring lines on sales documents.</span></span>  

## <a name="to-insert-standard-sales-lines-on-a-sales-invoice"></a><span data-ttu-id="fb539-112">Вставка стандартных строк продажи в счет продажи</span><span class="sxs-lookup"><span data-stu-id="fb539-112">To insert standard sales lines on a sales invoice</span></span>
1. <span data-ttu-id="fb539-113">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Счета**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="fb539-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Invoices**, and then choose the related link.</span></span>
2. <span data-ttu-id="fb539-114">Откройте счет продажи, в который требуется вставить одну или несколько стандартных строк.</span><span class="sxs-lookup"><span data-stu-id="fb539-114">Open the sales invoice that you want to insert one or more standard sales lines on.</span></span>
3. <span data-ttu-id="fb539-115">Выберите значение **Получить строки типовых продаж**.</span><span class="sxs-lookup"><span data-stu-id="fb539-115">Choose the **Get Recurring Sales Lines** action.</span></span>
4. <span data-ttu-id="fb539-116">В окне **Строки типовых продаж** нажмите кнопку выбора в поле **Код**, а затем выберите набор стандартных строк продажи.</span><span class="sxs-lookup"><span data-stu-id="fb539-116">In the **Recurring Sales Lines** window, choose the lookup button in the **Code** field, and then select a set of standard sales lines.</span></span>
5. <span data-ttu-id="fb539-117">Нажмите кнопку **ОК**, чтобы вставить в счет стандартные строки продажи, которые можно потом использовать повторно или изменить.</span><span class="sxs-lookup"><span data-stu-id="fb539-117">Choose the **OK** button to insert the standard sales lines on the invoice, where you can reuse as is or edit the information.</span></span>

## <a name="to-create-multiple-sales-invoices-based-on-standard-sales-lines"></a><span data-ttu-id="fb539-118">Создание нескольких счетов продажи на основе стандартных строк продаж</span><span class="sxs-lookup"><span data-stu-id="fb539-118">To create multiple sales invoices based on standard sales lines</span></span>
<span data-ttu-id="fb539-119">Можно использовать пакетное задание **Создание типовых счетов продажи** для создания счетов продаж в соответствии со стандартными строками продаж, которые назначены клиентам, и с учетными датами в пределах дат "Действительно с" и "Действительно по", указанных в стандартных кодах продажи.</span><span class="sxs-lookup"><span data-stu-id="fb539-119">You can use the **Create Recurring Sales Inv.** batch job to create sales invoices according to standard sales lines that are assigned to the customers and with posting dates within the valid-from and valid-to dates that you specify on the standard sales code.</span></span>

<span data-ttu-id="fb539-120">В окне **Строки типовых продаж** также можно также определять метод оплаты прямого дебета и поручение прямого дебетования.</span><span class="sxs-lookup"><span data-stu-id="fb539-120">In the **Recurring Sales Lines** window, you can also specify a direct-debit payment method and a direct-debit mandate.</span></span> <span data-ttu-id="fb539-121">Счета продажи, созданные с помощью пакетного задания **Создание типовых счетов продажи**, затем будут включать информацию, необходимую для получения платежей по счетам продажи с прямым дебетом SEPA.</span><span class="sxs-lookup"><span data-stu-id="fb539-121">The sales invoices that are created with the **Create Recurring Sales Inv.** batch job will then include information required to collect payment for the sales invoices with SEPA direct debit.</span></span> <span data-ttu-id="fb539-122">Дополнительные сведения см. в разделе [Сбор платежей с прямым дебетованием SEPA](finance-collect-payments-with-sepa-direct-debit.md).</span><span class="sxs-lookup"><span data-stu-id="fb539-122">For more information, see [Collecting Payments with SEPA Direct Debit](finance-collect-payments-with-sepa-direct-debit.md).</span></span>

1. <span data-ttu-id="fb539-123">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Создание типовых счетов продажи**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="fb539-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Create Recurring Sales Invoices**, and then choose the related link.</span></span>
2. <span data-ttu-id="fb539-124">В окне **Создание типовых счетов продажи** заполните поля по мере необходимости.</span><span class="sxs-lookup"><span data-stu-id="fb539-124">In the **Create Recurring Sales Inv.** window, fill in the fields as necessary.</span></span>
3. <span data-ttu-id="fb539-125">В поле **Код** введите код для стандартных строк продажи, назначенных клиенту, для которого требуется создать счета продаж.</span><span class="sxs-lookup"><span data-stu-id="fb539-125">In the **Code** field, enter the code for standard sales lines assigned to a customer that you want to create sales invoices for.</span></span>
4. <span data-ttu-id="fb539-126">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="fb539-126">Choose the **OK** button.</span></span>

<span data-ttu-id="fb539-127">Для клиентов создаются счета продажи с указанным стандартным клиентским кодом продажи, а также всеми заданными сведениями о прямом дебете для учета на определенную дату.</span><span class="sxs-lookup"><span data-stu-id="fb539-127">Sales invoices are created for the customers with the specified standard customer sales code, and any specified direct-debit information, for posting on the specified date.</span></span>

## <a name="see-also"></a><span data-ttu-id="fb539-128">См. также</span><span class="sxs-lookup"><span data-stu-id="fb539-128">See Also</span></span>  
[<span data-ttu-id="fb539-129">Продажи</span><span class="sxs-lookup"><span data-stu-id="fb539-129">Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="fb539-130">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="fb539-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

