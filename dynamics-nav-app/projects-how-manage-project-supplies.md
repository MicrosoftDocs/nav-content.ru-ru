---
title: "Практическое руководство. Управление запасами для проекта"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a><span data-ttu-id="5fcf3-102">Практическое руководство. Управление запасами для работы</span><span class="sxs-lookup"><span data-stu-id="5fcf3-102">How to: Manage Job Supplies</span></span>
<span data-ttu-id="5fcf3-103">Управление поставками товаров, услуг и затратами по проекту является неотъемлемым и важным аспектом выполнения любых работ.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-103">Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs.</span></span> <span data-ttu-id="5fcf3-104">Программа позволяет пользоваться имеющимися запасами или, посредством заказов на покупку или счетов покупки, купить все необходимое для выполнения работы.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-104">You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices.</span></span> <span data-ttu-id="5fcf3-105">Пусть, например, для выполнения работы по обслуживанию компьютера необходим новый диск.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-105">For example, a service job on a computer requires a new disk.</span></span> <span data-ttu-id="5fcf3-106">В этом случае необходимо создать новый счет покупки нового диска и записать работу, для которой он будет использован.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-106">You create a purchase invoice to buy a new disk and record the job that it will be used on.</span></span>

<span data-ttu-id="5fcf3-107">Если в процессе покупки не требуется отдельная запись физической транзакции, то покупка может быть обработана в окне **Журнал ГК работы**.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-107">If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window.</span></span> <span data-ttu-id="5fcf3-108">Дополнительные сведения см. в разделе [Практическое руководство. Регистрация использования для работ](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="5fcf3-108">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="to-purchase-items-or-services-for-a-job"></a><span data-ttu-id="5fcf3-109">Приобретение товаров или услуг для работы</span><span class="sxs-lookup"><span data-stu-id="5fcf3-109">To purchase items or services for a job</span></span>
<span data-ttu-id="5fcf3-110">В следующей процедуре показан порядок использования счета покупки для приобретения товаров для работы.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-110">The following procedure shows how to use a purchase invoice to purchase products for a job.</span></span> <span data-ttu-id="5fcf3-111">Эти же шаги применяются при использовании заказа на покупку.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-111">The same steps apply when using a purchase order.</span></span>  

1. <span data-ttu-id="5fcf3-112">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Счета покупок**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="5fcf3-113">Выберите действие **Создать** и введите в поля требуемые данные.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-113">Choose the **New** action and fill in the fields as necessary.</span></span> <span data-ttu-id="5fcf3-114">Дополнительные сведения см. в разделе [Практическое руководство. Регистрация покупок](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="5fcf3-114">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
3. <span data-ttu-id="5fcf3-115">В полях **Код работы**</span><span class="sxs-lookup"><span data-stu-id="5fcf3-115">In the **Job No.**</span></span> <span data-ttu-id="5fcf3-116">и **Номер рабочего задания**</span><span class="sxs-lookup"><span data-stu-id="5fcf3-116">and **Job Task No.**</span></span> <span data-ttu-id="5fcf3-117">выберите информацию о задании, для которой требуется приобрести товары или услуги.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-117">fields, select the information of the job that you want to purchase items or services for.</span></span>  

    <span data-ttu-id="5fcf3-118">Значение, выбранное в поле **Тип строки работы**, определяет, создается ли строка планирования во время учета потребления товара.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-118">The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item.</span></span> <span data-ttu-id="5fcf3-119">Если поле содержит значение **К оплате**, будут созданы строки планирования работы, по которым можно выставлять счет клиенту.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-119">If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="5fcf3-120">Дополнительные сведения см. в разделе [Практическое руководство. Выставление счетов за работы](projects-how-invoice-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="5fcf3-120">For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).</span></span>

4. <span data-ttu-id="5fcf3-121">Выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-121">Choose the **Post** action.</span></span>

## <a name="to-view-the-value-of-purchases-for-a-job"></a><span data-ttu-id="5fcf3-122">Просмотр значения покупок для работы</span><span class="sxs-lookup"><span data-stu-id="5fcf3-122">To view the value of purchases for a job</span></span>  

1. <span data-ttu-id="5fcf3-123">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Работы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="5fcf3-124">Откройте соответствующую карточку работы.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-124">Open a relevant job card.</span></span>

    <span data-ttu-id="5fcf3-125">На экспресс-вкладке **Задачи** поле **Невыполненные заказы** показывает общую сумму по невыполненным поставкам (в локальной валюте) товарно-материальных ценностей и услуг по документам на покупку для строки рабочего задания.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-125">On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.</span></span>  

    <span data-ttu-id="5fcf3-126">Поле **Сумма, полученная без выст. счета** показывает объем товаров, доставленных по документам на покупку, по которым еще не выставлен счет.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-126">The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.</span></span>  

3. <span data-ttu-id="5fcf3-127">Выберите одно из этих полей, чтобы открыть окно **Строки покупки**, в котором можно просмотреть сведения о соответствующих строках документов на покупку, включая информацию о полученных товарах или услугах.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-127">Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.</span></span>

## <a name="to-post-a-job-related-expense"></a><span data-ttu-id="5fcf3-128">Учет связанных с работой расходов</span><span class="sxs-lookup"><span data-stu-id="5fcf3-128">To post a job-related expense</span></span>  
<span data-ttu-id="5fcf3-129">Если были произведены дополнительные или разовые расходы по работе, можно использовать окно **Журнал ГК работы**, чтобы учесть их непосредственно на соответствующем счете работы.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-129">If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.</span></span>

1. <span data-ttu-id="5fcf3-130">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Журналы ГК работ**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="5fcf3-131">Создайте новую строку и введите информацию о расходах, включая информацию в полях **Код работы**</span><span class="sxs-lookup"><span data-stu-id="5fcf3-131">Create a new line and enter information about the expense, including information in the **Job No.**</span></span> <span data-ttu-id="5fcf3-132">и **Номер рабочего задания**.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-132">and **Job Task No** fields.</span></span>  
3. <span data-ttu-id="5fcf3-133">Когда журнал будет готов, выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="5fcf3-133">When the journal is complete, choose the **Post** action.</span></span>


## <a name="see-also"></a><span data-ttu-id="5fcf3-134">См. также</span><span class="sxs-lookup"><span data-stu-id="5fcf3-134">See Also</span></span>
[<span data-ttu-id="5fcf3-135">Управление проектами</span><span class="sxs-lookup"><span data-stu-id="5fcf3-135">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="5fcf3-136">Финансы</span><span class="sxs-lookup"><span data-stu-id="5fcf3-136">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="5fcf3-137">[Управление закупками](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="5fcf3-137">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="5fcf3-138">[Управление продажами](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="5fcf3-138">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="5fcf3-139">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5fcf3-139">Work With Dynamics NAV</span></span>](ui-work-product.md)  

