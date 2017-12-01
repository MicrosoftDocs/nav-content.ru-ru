---
title: "Практическое руководство. Печать подсказки по переводу"
description: "Ваши поставщики также могут выполнять выверку путем печати подсказки по переводу перед учетом журнала платежей, а также после учета платежа."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 10/26/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 7c7004ac5ded9436861bf5034f59a9c2bcd99dd0
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---

#<a name="how-to-print-remittance-advice"></a><span data-ttu-id="fea09-103">Практическое руководство. Печать подсказки по переводу</span><span class="sxs-lookup"><span data-stu-id="fea09-103">How to: Print Remittance Advice</span></span>
<span data-ttu-id="fea09-104">Подсказку по переводу можно напечатать перед учетом журнала платежей и после учета платежа.</span><span class="sxs-lookup"><span data-stu-id="fea09-104">You can print remittance advice before posting a payment journal and after posting a payment.</span></span> <span data-ttu-id="fea09-105">Эта подсказка содержит номера счетов поставщиков, которые помогают поставщикам выполнять выверку.</span><span class="sxs-lookup"><span data-stu-id="fea09-105">This advice displays vendor invoice numbers, which helps vendors to perform reconciliations.</span></span>

##<a name="to-print-remittance-advice"></a><span data-ttu-id="fea09-106">Печать подсказки по переводу</span><span class="sxs-lookup"><span data-stu-id="fea09-106">To print remittance advice</span></span>
1. <span data-ttu-id="fea09-107">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы платежей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="fea09-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="fea09-108">В окне **Журнал платежей** выберите платеж, для которого необходимо напечатать подсказку по переводу.</span><span class="sxs-lookup"><span data-stu-id="fea09-108">In the **Payment Journal** window, select the payment for which remittance advice must be printed.</span></span>  
3. <span data-ttu-id="fea09-109">Выберите действие **Печать подсказки по переводу**.</span><span class="sxs-lookup"><span data-stu-id="fea09-109">Choose the **Print Remittance Advice** action.</span></span>  
4. <span data-ttu-id="fea09-110">В пакетном задании **Печать подсказки по переводу - журнал** на экспресс-вкладке **Строка финансового журнала** установите соответствующие фильтры.</span><span class="sxs-lookup"><span data-stu-id="fea09-110">In the **Remittance Advice - Journal** batch job, on the **Fen. Journal Line** FastTab, choose the appropriate filters.</span></span>  
  
    >[!Note]
    > <span data-ttu-id="fea09-111">Вы можете выполнять фильтрацию по номеру внешнего документа, чтобы сопоставлять платежи со счетами.</span><span class="sxs-lookup"><span data-stu-id="fea09-111">You can filter using the vendor's external document number to match payments with invoices.</span></span>

5. <span data-ttu-id="fea09-112">На экспресс-вкладке **Поставщик** выберите соответствующие фильтры.</span><span class="sxs-lookup"><span data-stu-id="fea09-112">On the **Vendor** FastTab, choose the appropriate filters.</span></span>  
6. <span data-ttu-id="fea09-113">Выберите **Печать** для печати отчета или **Просмотр** для его просмотра на экране.</span><span class="sxs-lookup"><span data-stu-id="fea09-113">Choose **Print** to print the report, or choose **Preview** to view it now.</span></span>  

## <a name="using-remittance-advice-reports"></a><span data-ttu-id="fea09-114">Использование отчетов с подсказками по переводу</span><span class="sxs-lookup"><span data-stu-id="fea09-114">Using Remittance Advice Reports</span></span>
<span data-ttu-id="fea09-115">В следующей таблице описаны отчеты, которые можно использовать с подсказками по переводу.</span><span class="sxs-lookup"><span data-stu-id="fea09-115">The following table describes the reports that you can use with remittance advice:</span></span>

|<span data-ttu-id="fea09-116">Отчет</span><span class="sxs-lookup"><span data-stu-id="fea09-116">Report</span></span>|<span data-ttu-id="fea09-117">Описанием</span><span class="sxs-lookup"><span data-stu-id="fea09-117">Description</span></span>|
|----|----|
|<span data-ttu-id="fea09-118">Отчет "Подсказка по переводу — журнал"</span><span class="sxs-lookup"><span data-stu-id="fea09-118">Remittance Advice - Journal Report</span></span>|<span data-ttu-id="fea09-119">В этом показано, какие документы включены в оплату.</span><span class="sxs-lookup"><span data-stu-id="fea09-119">This report indicates which documents are included in the payment.</span></span> <span data-ttu-id="fea09-120">Для строк финансового журнала можно указать шаблон журнала и раздел журнала, из которого будут печататься подсказки, дата первого перевода и фильтра по номеру документа.</span><span class="sxs-lookup"><span data-stu-id="fea09-120">For general journal lines, you can specify the journal template and journal batch from which the remittance advices will be printed, the date of the first activity to print, and filter on a document number.</span></span> <span data-ttu-id="fea09-121">Для поставщиков можно ввести номера поставщиков для включения в отчет.</span><span class="sxs-lookup"><span data-stu-id="fea09-121">For vendors, you can enter the vendor numbers to include in the report.</span></span> |
|<span data-ttu-id="fea09-122">Отчет "Подсказка по переводу — операции"</span><span class="sxs-lookup"><span data-stu-id="fea09-122">Remittance Advice - Entries Report</span></span>| <span data-ttu-id="fea09-123">В этом показано, какие документы включены в оплату.</span><span class="sxs-lookup"><span data-stu-id="fea09-123">This report indicates which documents are included in the payment.</span></span> <span data-ttu-id="fea09-124">Содержание отчета определяется с помощью фильтров.</span><span class="sxs-lookup"><span data-stu-id="fea09-124">You define the report contents by setting filters.</span></span> <span data-ttu-id="fea09-125">Можно настроить дополнительные поля на вкладке **Поле**.</span><span class="sxs-lookup"><span data-stu-id="fea09-125">You can set additional fields on the tab by choosing the **Field** field.</span></span> <span data-ttu-id="fea09-126">Для операций книги поставщика можно указать поставщиков для включения в отчет, дату первого перевода для печати, валюту и номер операции, которая должна быть включена.</span><span class="sxs-lookup"><span data-stu-id="fea09-126">For vendor ledger entries, you can specify the vendors to include in the report, the date of the first activity to print, the currency, and the entry number to include.</span></span> |

> [!Note]
> <span data-ttu-id="fea09-127">Отчет "Подсказка по переводу — журнал" не поддерживает межвалютное применение и отклонения в оплате</span><span class="sxs-lookup"><span data-stu-id="fea09-127">The Remittance Advice - Journal Report does not support cross currency application scenarios or payment tolerances.</span></span> <span data-ttu-id="fea09-128">Дополнительные сведения см. в разделе [Практическое руководство. Включение операций книги в разных валютах](finance-how-enable-application-ledger-entries-different-currencies.md).</span><span class="sxs-lookup"><span data-stu-id="fea09-128">For more information, see [How to: Enable Application of Ledger Entries in Different Currencies](finance-how-enable-application-ledger-entries-different-currencies.md).</span></span>

> [!Tip]
> <span data-ttu-id="fea09-129">Дополнительные сведения о том, как работать с отчетами см. в разделах [Просмотр тестовых отчетов перед публикацией](ui-how-view-test-reports-posting.md), [Работа с отчетами](ui-work-report.md) и [Поиск, фильтрация и сортировка данных](ui-enter-criteria-filters.md).</span><span class="sxs-lookup"><span data-stu-id="fea09-129">For more information about how to work with reports, see [Viewing Test Reports before Posting](ui-how-view-test-reports-posting.md), [Work with Reports](ui-work-report.md), and [Searching, Filtering, and Sorting Data](ui-enter-criteria-filters.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="fea09-130">См. также</span><span class="sxs-lookup"><span data-stu-id="fea09-130">See Also</span></span>  
[<span data-ttu-id="fea09-131">Добро пожаловать в Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="fea09-131">Welcome to Dynamics NAV</span></span>](across-get-started.md)
