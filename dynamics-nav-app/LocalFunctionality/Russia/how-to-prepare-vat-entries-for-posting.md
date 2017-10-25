---
title: "Практическое руководство. Подготовка операций НДС к учету"
description: "Необходимо периодически предоставлять в налоговые органы данные о чистой сумме НДС. Можно использовать **Журнал НДС** для подготовки транзакций с открытыми суммами НДС к учету и для копирования операций в соответствующий журнал НДС. Обычно это нужно перед запуском пакетного задания **Вычисление и учет зачета НДС** для учета и закрытия операций НДС."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 77ab41be678672e88c1046fd1944519f14eac7c4
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-prepare-vat-entries-for-posting"></a><span data-ttu-id="46c19-105">Практическое руководство. Подготовка операций НДС к учету</span><span class="sxs-lookup"><span data-stu-id="46c19-105">How to: Prepare VAT Entries for Posting</span></span>
<span data-ttu-id="46c19-106">Необходимо периодически предоставлять в налоговые органы данные о чистой сумме НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-106">You may want to periodically remit the net VAT from sales and purchase transactions to the tax authorities.</span></span> <span data-ttu-id="46c19-107">Можно использовать **Журнал НДС** для подготовки транзакций с открытыми суммами НДС к учету и для копирования операций в соответствующий журнал НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-107">You can use the **VAT Settlement Worksheet** to prepare transactions with open VAT amounts for posting and copy the entries to the appropriate VAT settlement journal.</span></span> <span data-ttu-id="46c19-108">Обычно это нужно перед запуском пакетного задания **Вычисление и учет зачета НДС** для учета и закрытия операций НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-108">This is typically done before you run the **Calc. and Post VAT Settlement** batch job to post and close VAT entries.</span></span>  
  
### <a name="to-prepare-vat-entries-for-posting"></a><span data-ttu-id="46c19-109">Подготовка операций НДС к учету</span><span class="sxs-lookup"><span data-stu-id="46c19-109">To prepare VAT entries for posting</span></span>  
  
1.  <span data-ttu-id="46c19-110">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал НДС**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="46c19-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Settlement Worksheet**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="46c19-111">Выберите фильтры, которые определяют связанные с НДС транзакции, которые требуется включить в зачет НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-111">Select the filters that define the VAT related transactions that you want to include in the VAT settlement.</span></span>  
  
    |<span data-ttu-id="46c19-112">Поле</span><span class="sxs-lookup"><span data-stu-id="46c19-112">Field</span></span>|<span data-ttu-id="46c19-113">Описанием</span><span class="sxs-lookup"><span data-stu-id="46c19-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="46c19-114">**Тип**</span><span class="sxs-lookup"><span data-stu-id="46c19-114">**Type**</span></span>|<span data-ttu-id="46c19-115">Выберите типы транзакций, которые требуется включить в зачет НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-115">Select the type of transactions that you want to include in the VAT settlement.</span></span>|  
    |<span data-ttu-id="46c19-116">**Просмотр по**</span><span class="sxs-lookup"><span data-stu-id="46c19-116">**View by**</span></span>|<span data-ttu-id="46c19-117">Выберите период времени для зачета НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-117">Select the time period for the VAT settlement.</span></span>|  
    |<span data-ttu-id="46c19-118">**Просмотр как**</span><span class="sxs-lookup"><span data-stu-id="46c19-118">**View as**</span></span>|<span data-ttu-id="46c19-119">Выберите способ просмотра чистой суммы НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-119">Select how you want to view the net VAT.</span></span> <span data-ttu-id="46c19-120">Возможные варианты: **Оборот** и **Сальдо на дату**.</span><span class="sxs-lookup"><span data-stu-id="46c19-120">The options include **Net Change** and **Balance at Date**.</span></span>|  
  
3.  <span data-ttu-id="46c19-121">Выберите **Предложить документы**.</span><span class="sxs-lookup"><span data-stu-id="46c19-121">Choose **Suggest Documents**.</span></span> <span data-ttu-id="46c19-122">Будут показаны транзакции с открытыми операциями НДС, которые соответствуют выбранным фильтрам.</span><span class="sxs-lookup"><span data-stu-id="46c19-122">Transactions with open VAT entries that match the filters that you selected will be displayed.</span></span>  
  
4.  <span data-ttu-id="46c19-123">Проверьте выбранные транзакции.</span><span class="sxs-lookup"><span data-stu-id="46c19-123">Review the transactions that are included to ensure accuracy.</span></span> <span data-ttu-id="46c19-124">При необходимости скорректируйте фильтр.</span><span class="sxs-lookup"><span data-stu-id="46c19-124">If necessary, adjust your filter selection.</span></span>  
  
5.  <span data-ttu-id="46c19-125">Выберите **Копировать строки в журнал**.</span><span class="sxs-lookup"><span data-stu-id="46c19-125">Choose **Copy Lines to Journal**.</span></span>  
  
 <span data-ttu-id="46c19-126">Операции копируется в соответствующие журналы НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-126">The entries are copied to the appropriate VAT settlement journals.</span></span> <span data-ttu-id="46c19-127">Теперь можно запустить пакетное задание **Вычисление и учет зачета НДС**, чтобы закрыть операции НДС.</span><span class="sxs-lookup"><span data-stu-id="46c19-127">You can now run the **Calc. and Post VAT Settlement** batch job to close the VAT entries.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="46c19-128">См. также</span><span class="sxs-lookup"><span data-stu-id="46c19-128">See Also</span></span>  
 <span data-ttu-id="46c19-129">Вычисление и учет зачета НДС</span><span class="sxs-lookup"><span data-stu-id="46c19-129">Calc. and Post VAT Settlement</span></span>   
 <span data-ttu-id="46c19-130">[О настройке НДС](about-setting-up-vat.md) </span><span class="sxs-lookup"><span data-stu-id="46c19-130">[About Setting Up VAT](about-setting-up-vat.md) </span></span>  
 <span data-ttu-id="46c19-131">[Практическое руководство. Настройка НДС бизнес-групп](how-to-set-up-vat-business-posting-groups.md) </span><span class="sxs-lookup"><span data-stu-id="46c19-131">[How to: Set Up VAT Business Posting Groups](how-to-set-up-vat-business-posting-groups.md) </span></span>  
 <span data-ttu-id="46c19-132">[Практическое руководство. Назначение НДС бизнес-групп для счетов клиента и поставщика](how-to-assign-vat-business-posting-groups-to-customer-accounts-and-vendor-accounts.md) </span><span class="sxs-lookup"><span data-stu-id="46c19-132">[How to: Assign VAT Business Posting Groups to Customer Accounts and Vendor Accounts](how-to-assign-vat-business-posting-groups-to-customer-accounts-and-vendor-accounts.md) </span></span>  
 <span data-ttu-id="46c19-133">[Практическое руководство. Корректировка НДС](how-to-correct-vat.md) </span><span class="sxs-lookup"><span data-stu-id="46c19-133">[How to: Correct VAT](how-to-correct-vat.md) </span></span>  
 <span data-ttu-id="46c19-134">Операция НДС</span><span class="sxs-lookup"><span data-stu-id="46c19-134">VAT Entry</span></span>
