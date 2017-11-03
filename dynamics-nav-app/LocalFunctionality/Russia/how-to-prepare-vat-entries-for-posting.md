---
title: "Практическое руководство. Подготовка операций НДС к учету"
description: "Необходимо периодически предоставлять в налоговые органы данные о чистой сумме НДС. Можно использовать **Журнал НДС** для подготовки транзакций с открытыми суммами НДС к учету и для копирования операций в соответствующий журнал НДС."
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
ms.openlocfilehash: cc545bc86331e36641983a69e4ffc907dc928d94
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-prepare-vat-entries-for-posting"></a><span data-ttu-id="38aa9-104">Практическое руководство. Подготовка операций НДС к учету</span><span class="sxs-lookup"><span data-stu-id="38aa9-104">How to: Prepare VAT Entries for Posting</span></span>
<span data-ttu-id="38aa9-105">Необходимо периодически предоставлять в налоговые органы данные о чистой сумме НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-105">You may want to periodically remit the net VAT from sales and purchase transactions to the tax authorities.</span></span> <span data-ttu-id="38aa9-106">Можно использовать **Журнал НДС** для подготовки транзакций с открытыми суммами НДС к учету и для копирования операций в соответствующий журнал НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-106">You can use the **VAT Settlement Worksheet** to prepare transactions with open VAT amounts for posting and copy the entries to the appropriate VAT settlement journal.</span></span> <span data-ttu-id="38aa9-107">Обычно это нужно перед запуском пакетного задания **Вычисление и учет зачета НДС** для учета и закрытия операций НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-107">This is typically done before you run the **Calc. and Post VAT Settlement** batch job to post and close VAT entries.</span></span>  

## <a name="to-prepare-vat-entries-for-posting"></a><span data-ttu-id="38aa9-108">Подготовка операций НДС к учету</span><span class="sxs-lookup"><span data-stu-id="38aa9-108">To prepare VAT entries for posting</span></span>  

1.  <span data-ttu-id="38aa9-109">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал НДС**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="38aa9-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Settlement Worksheet**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="38aa9-110">Выберите фильтры, которые определяют связанные с НДС транзакции, которые требуется включить в зачет НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-110">Select the filters that define the VAT related transactions that you want to include in the VAT settlement.</span></span>  

    |<span data-ttu-id="38aa9-111">Поле</span><span class="sxs-lookup"><span data-stu-id="38aa9-111">Field</span></span>|<span data-ttu-id="38aa9-112">Описанием</span><span class="sxs-lookup"><span data-stu-id="38aa9-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="38aa9-113">**Тип**</span><span class="sxs-lookup"><span data-stu-id="38aa9-113">**Type**</span></span>|<span data-ttu-id="38aa9-114">Выберите типы транзакций, которые требуется включить в зачет НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-114">Select the type of transactions that you want to include in the VAT settlement.</span></span>|  
    |<span data-ttu-id="38aa9-115">**Просмотр по**</span><span class="sxs-lookup"><span data-stu-id="38aa9-115">**View by**</span></span>|<span data-ttu-id="38aa9-116">Выберите период времени для зачета НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-116">Select the time period for the VAT settlement.</span></span>|  
    |<span data-ttu-id="38aa9-117">**Просмотр как**</span><span class="sxs-lookup"><span data-stu-id="38aa9-117">**View as**</span></span>|<span data-ttu-id="38aa9-118">Выберите способ просмотра чистой суммы НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-118">Select how you want to view the net VAT.</span></span> <span data-ttu-id="38aa9-119">Возможные варианты: **Оборот** и **Сальдо на дату**.</span><span class="sxs-lookup"><span data-stu-id="38aa9-119">The options include **Net Change** and **Balance at Date**.</span></span>|  

3.  <span data-ttu-id="38aa9-120">Выберите **Предложить документы**.</span><span class="sxs-lookup"><span data-stu-id="38aa9-120">Choose **Suggest Documents**.</span></span> <span data-ttu-id="38aa9-121">Будут показаны транзакции с открытыми операциями НДС, которые соответствуют выбранным фильтрам.</span><span class="sxs-lookup"><span data-stu-id="38aa9-121">Transactions with open VAT entries that match the filters that you selected will be displayed.</span></span>  
4.  <span data-ttu-id="38aa9-122">Проверьте выбранные транзакции.</span><span class="sxs-lookup"><span data-stu-id="38aa9-122">Review the transactions that are included to ensure accuracy.</span></span> <span data-ttu-id="38aa9-123">При необходимости скорректируйте фильтр.</span><span class="sxs-lookup"><span data-stu-id="38aa9-123">If necessary, adjust your filter selection.</span></span>  
5.  <span data-ttu-id="38aa9-124">Выберите **Копировать строки в журнал**.</span><span class="sxs-lookup"><span data-stu-id="38aa9-124">Choose **Copy Lines to Journal**.</span></span>  

<span data-ttu-id="38aa9-125">Операции копируется в соответствующие журналы НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-125">The entries are copied to the appropriate VAT settlement journals.</span></span> <span data-ttu-id="38aa9-126">Теперь можно запустить пакетное задание **Вычисление и учет зачета НДС**, чтобы закрыть операции НДС.</span><span class="sxs-lookup"><span data-stu-id="38aa9-126">You can now run the **Calc. and Post VAT Settlement** batch job to close the VAT entries.</span></span>  

## <a name="see-also"></a><span data-ttu-id="38aa9-127">См. также</span><span class="sxs-lookup"><span data-stu-id="38aa9-127">See Also</span></span>  
 [<span data-ttu-id="38aa9-128">Практическое руководство. Подача отчета об НДС в налоговые органы</span><span class="sxs-lookup"><span data-stu-id="38aa9-128">How to: Report VAT to Tax Authorities</span></span>](../../finance-how-report-vat.md)

