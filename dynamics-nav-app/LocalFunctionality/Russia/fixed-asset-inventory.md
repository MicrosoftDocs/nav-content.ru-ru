---
title: "Инвентаризация основных средств"
description: "Функция инвентаризации основных средств позволяет обрабатывать аудит учета основных средств в соответствии с требованиями законодательства, создавать электронные инвентарные списки основных средств, которые подлежат инвентаризации, с расчетными количествами и суммами, и многое другое."
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
ms.openlocfilehash: 4bc5df267c868043973e9e5a5c1e42ce2e3336bc
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="fixed-asset-inventory"></a><span data-ttu-id="29dde-103">Инвентаризация основных средств</span><span class="sxs-lookup"><span data-stu-id="29dde-103">Fixed Asset Inventory</span></span>
<span data-ttu-id="29dde-104">Функция инвентаризации основных средств позволяет:</span><span class="sxs-lookup"><span data-stu-id="29dde-104">The fixed assets inventory feature enables you to:</span></span>  

- <span data-ttu-id="29dde-105">выполнять инвентаризацию основных средств в соответствии с требованиями законодательства;</span><span class="sxs-lookup"><span data-stu-id="29dde-105">Process inventory auditing of fixed assets in accordance with legal requirements.</span></span>  
- <span data-ttu-id="29dde-106">создавать электронные инвентарные списки основных средств, подлежащих инвентаризации, с учетом расчетных количеств и сумм;</span><span class="sxs-lookup"><span data-stu-id="29dde-106">Generate electronic inventory lists of fixed assets that are to be inventoried with calculated quantities and amounts.</span></span>  
- <span data-ttu-id="29dde-107">разделять инвентарные списки по физическому местоположению основных средств (по коду местоположения основного средства);</span><span class="sxs-lookup"><span data-stu-id="29dde-107">Divide the inventory lists by the physical locations of fixed assets (by Fixed Asset Location code).</span></span>  
- <span data-ttu-id="29dde-108">фильтровать инвентарные списки по другим аналитикам (например, по подотчетнику);</span><span class="sxs-lookup"><span data-stu-id="29dde-108">Filter the inventory lists by other analytics (such as responsible employee).</span></span>  
- <span data-ttu-id="29dde-109">печатать формы с инвентарными списками, в которых показаны все основные средства, прошедшие инвентаризацию, а также со списками, в которых перечислены основные средства с разницей только в количестве или сумме;</span><span class="sxs-lookup"><span data-stu-id="29dde-109">Print the forms with inventory lists that show all inventoried fixed assets, as well as lists that show the fixed assets with differences only in quantities or amounts.</span></span>  
- <span data-ttu-id="29dde-110">печатать стандартные формы основных средств.</span><span class="sxs-lookup"><span data-stu-id="29dde-110">Print unified fixed asset forms.</span></span>  

## <a name="inventory-lists-of-fixed-assets"></a><span data-ttu-id="29dde-111">Инвентарные списки основных средств</span><span class="sxs-lookup"><span data-stu-id="29dde-111">Inventory Lists of Fixed Assets</span></span>  
<span data-ttu-id="29dde-112">Для проведения инвентаризации необходимо создать инвентарные списки основных средств с расчетными количествами и суммами.</span><span class="sxs-lookup"><span data-stu-id="29dde-112">You must create inventory lists of fixed assets with calculated quantities and amounts for inventory auditing.</span></span> <span data-ttu-id="29dde-113">Такие списки разделены по аналитике: например, по физическому местоположению или сотруднику, ответственному за определенные основные средства.</span><span class="sxs-lookup"><span data-stu-id="29dde-113">The lists are divided by analytics such as physical locations and employees responsible for certain fixed assets.</span></span>  

<span data-ttu-id="29dde-114">Можно создать специальные шаблоны в окне **Журнал учета основных средств**.</span><span class="sxs-lookup"><span data-stu-id="29dde-114">You can create special templates in the **Fixed Asset Journal** window.</span></span>  

<span data-ttu-id="29dde-115">Ниже показано, как создать список основных средств, подлежащих инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="29dde-115">The following procedure shows how to generate a list of fixed assets that are to be inventoried.</span></span>  

1. <span data-ttu-id="29dde-116">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы ОС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="29dde-116">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="29dde-117">Выберите действие **Расчет ОС**.</span><span class="sxs-lookup"><span data-stu-id="29dde-117">Choose the **Calculate FA** action.</span></span> <span data-ttu-id="29dde-118">Откроется форма запроса отчета для создания инвентарных списков основных средств.</span><span class="sxs-lookup"><span data-stu-id="29dde-118">The request form of a report that makes fixed asset inventory lists is displayed.</span></span>  
2. <span data-ttu-id="29dde-119">На экспресс-вкладке **Основные средства** отфильтруйте основные средства.</span><span class="sxs-lookup"><span data-stu-id="29dde-119">On the **Fixed Asset** FastTab, filter the fixed assets.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="29dde-120">Фильтрацию можно выполнять по любому параметру из карточки основного средства, например по местоположению основного средства или по подотчетнику.</span><span class="sxs-lookup"><span data-stu-id="29dde-120">They can be filtered by any parameter from the Fixed Asset card, such fixed asset location or responsible employee.</span></span>  

<span data-ttu-id="29dde-121">Параметры, перечисленные в таблице ниже, можно найти на экспресс-вкладке **Параметры**.</span><span class="sxs-lookup"><span data-stu-id="29dde-121">The parameters listed in the following table are on the **Options** FastTab.</span></span>  

|<span data-ttu-id="29dde-122">Параметр</span><span class="sxs-lookup"><span data-stu-id="29dde-122">Parameter</span></span>|<span data-ttu-id="29dde-123">Описанием</span><span class="sxs-lookup"><span data-stu-id="29dde-123">Description</span></span>|  
|---------------|-----------------|  
|<span data-ttu-id="29dde-124">**ОС Журнал Шаблон**</span><span class="sxs-lookup"><span data-stu-id="29dde-124">**Fixed Asset Journal Template**</span></span>|<span data-ttu-id="29dde-125">Выберите шаблон журнала основных средств, который будет использоваться для работы со списком основных средств в ходе инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="29dde-125">Select the fixed asset journal template to work with the fixed assets list during the inventory auditing process.</span></span> <span data-ttu-id="29dde-126">По умолчанию указывается шаблон журнала основных средств.</span><span class="sxs-lookup"><span data-stu-id="29dde-126">It is filled by default with the fixed asset journal template.</span></span>|  
|<span data-ttu-id="29dde-127">**Код Книги Амортизации**</span><span class="sxs-lookup"><span data-stu-id="29dde-127">**Depreciation Book Code**</span></span>|<span data-ttu-id="29dde-128">Выберите книгу амортизации с записями, для которых будет выполнен расчет по количеству и сумме.</span><span class="sxs-lookup"><span data-stu-id="29dde-128">Select the depreciation book with the records, which will be calculated by quantities and amounts.</span></span>|  
|<span data-ttu-id="29dde-129">**Начальный Документ Номер**</span><span class="sxs-lookup"><span data-stu-id="29dde-129">**Starting Document No.**</span></span>|<span data-ttu-id="29dde-130">Укажите номер документа, применявшийся при создании строк в журнале основных средств.</span><span class="sxs-lookup"><span data-stu-id="29dde-130">Specify the document number used to make lines in the fixed asset journal.</span></span>|  
|<span data-ttu-id="29dde-131">**Дата Документа**</span><span class="sxs-lookup"><span data-stu-id="29dde-131">**Document Date**</span></span>|<span data-ttu-id="29dde-132">Укажите дату документа.</span><span class="sxs-lookup"><span data-stu-id="29dde-132">Specify the document date.</span></span>|  
|<span data-ttu-id="29dde-133">**Дата учета**</span><span class="sxs-lookup"><span data-stu-id="29dde-133">**Posting Date**</span></span>|<span data-ttu-id="29dde-134">Укажите дату учета.</span><span class="sxs-lookup"><span data-stu-id="29dde-134">Specify the posting date.</span></span> <span data-ttu-id="29dde-135">Количества и суммы рассчитываются на эту дату.</span><span class="sxs-lookup"><span data-stu-id="29dde-135">The quantities and amounts are calculated on this date.</span></span> <span data-ttu-id="29dde-136">В поле **Дата Учета** тоже заносится это значение.</span><span class="sxs-lookup"><span data-stu-id="29dde-136">The **Posting Date** field is also filled with this value.</span></span>|  
|<span data-ttu-id="29dde-137">**Показывать ОС с Остаточной Стоимостью = 0**</span><span class="sxs-lookup"><span data-stu-id="29dde-137">**Show Fixed Asset with Book Value = 0**</span></span>|<span data-ttu-id="29dde-138">Установите этот флажок, чтобы создать в журнале основных средств строки для ОС с нулевой остаточной стоимостью.</span><span class="sxs-lookup"><span data-stu-id="29dde-138">Select this field to create fixed asset journal lines for fixed assets which have a book value of zero.</span></span>|  

<span data-ttu-id="29dde-139">Отчет создает один раздел в шаблоне журнала основных средств для каждого местоположения основных средств, отфильтрованного в форме запроса.</span><span class="sxs-lookup"><span data-stu-id="29dde-139">The report creates one batch in the fixed asset journal template for every fixed asset location that is filtered in the request form.</span></span> <span data-ttu-id="29dde-140">Для каждого отфильтрованного основного средства создается одна строка журнала в разделе, соответствующем местоположению этого ОС.</span><span class="sxs-lookup"><span data-stu-id="29dde-140">For every fixed asset that is filtered, one journal line is created in the batch according to its location.</span></span> <span data-ttu-id="29dde-141">Раздел журнала создается для основных средств в каждом местоположении ОС.</span><span class="sxs-lookup"><span data-stu-id="29dde-141">A journal batch is created for fixed assets in each fixed asset location.</span></span>  

<span data-ttu-id="29dde-142">Ниже показано, как начать инвентаризацию по местоположению основных средств.</span><span class="sxs-lookup"><span data-stu-id="29dde-142">The following procedure shows how to begin inventory auditing by fixed asset locations.</span></span>  

1.  <span data-ttu-id="29dde-143">Выберите раздел, соответствующий местоположению основных средств, а затем выберите **ОК**.</span><span class="sxs-lookup"><span data-stu-id="29dde-143">Select the batch according to the fixed asset location, and choose **ОК**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="29dde-144">Можно просмотреть строки основных средств, отфильтрованные в отчете, и строки для данного местоположения ОС.</span><span class="sxs-lookup"><span data-stu-id="29dde-144">You can view the fixed assets lines that are filtered in the report and the lines that are in this fixed asset location.</span></span>  

2.  <span data-ttu-id="29dde-145">Расположите столбцы журнала основных средств таким образом, чтобы можно было просматривать расчетные и фактические количества и суммы.</span><span class="sxs-lookup"><span data-stu-id="29dde-145">Place the columns of the fixed asset journal so that you can view calculated and actual quantities and amounts.</span></span> <span data-ttu-id="29dde-146">Они указаны в следующих полях:</span><span class="sxs-lookup"><span data-stu-id="29dde-146">They are reflected in the following fields:</span></span>  

    - <span data-ttu-id="29dde-147">**Факт. Кол-во**;</span><span class="sxs-lookup"><span data-stu-id="29dde-147">**Actual Quantity**</span></span>  
    - <span data-ttu-id="29dde-148">**Расчет. Кол-во**;</span><span class="sxs-lookup"><span data-stu-id="29dde-148">**Calc. Quantity**</span></span>  
    - <span data-ttu-id="29dde-149">**Факт. Сумма**;</span><span class="sxs-lookup"><span data-stu-id="29dde-149">**Actual Amount**</span></span>  
    - <span data-ttu-id="29dde-150">**Расчет. Сумма**.</span><span class="sxs-lookup"><span data-stu-id="29dde-150">**Calc. Amount**</span></span>  

> [!NOTE]  
>  <span data-ttu-id="29dde-151">Значение суммы — это остаточная стоимость основного средства.</span><span class="sxs-lookup"><span data-stu-id="29dde-151">The amount value is the book value of the fixed asset.</span></span>  

## <a name="inventory-auditing-of-fixed-assets"></a><span data-ttu-id="29dde-152">Инвентаризация основных средств</span><span class="sxs-lookup"><span data-stu-id="29dde-152">Inventory Auditing of Fixed Assets</span></span>  
<span data-ttu-id="29dde-153">Чтобы приступить к инвентаризации основных средств, нужно создать список ОС, подлежащих инвентаризации в определенных местоположениях основных средств, с расчетными количествами и суммами на основе системных записей.</span><span class="sxs-lookup"><span data-stu-id="29dde-153">To begin inventory auditing of fixed assets, create the list of fixed assets to be inventoried in certain fixed asset locations, with calculated quantities and amounts, on the basis of system records.</span></span>  

## <a name="fixed-asset-physical-inventory-inv-1-report"></a><span data-ttu-id="29dde-154">Отчет ИНВ-1 о физической инвентаризации основных средств</span><span class="sxs-lookup"><span data-stu-id="29dde-154">Fixed Asset Physical Inventory INV-1 Report</span></span>  
<span data-ttu-id="29dde-155">Можно напечатать отчет **Физическая инвентаризация основных средств ИНВ-1**, в котором приводится список строк журнала основных средств со всеми ОС, прошедшими инвентаризацию, отфильтрованными в форме запроса отчета.</span><span class="sxs-lookup"><span data-stu-id="29dde-155">You can print the **Fixed Asset Physical Inventory INV-1** report, which shows the list of fixed asset journal lines with all inventoried fixed assets filtered in the request form of the report.</span></span> <span data-ttu-id="29dde-156">В этом отчете показаны расчетные и фактические количества и суммы для основных средств, прошедших инвентаризацию.</span><span class="sxs-lookup"><span data-stu-id="29dde-156">The report shows the calculated and actual quantities and amounts of inventoried fixed assets.</span></span>  

<span data-ttu-id="29dde-157">Ниже показано, как напечатать отчет **Физическая инвентаризация основных средств ИНВ-1**.</span><span class="sxs-lookup"><span data-stu-id="29dde-157">The following procedure shows how to print the **Fixed Asset Physical Inventory INV-1** report.</span></span>  

1.  <span data-ttu-id="29dde-158">На экспресс-вкладке **Строка журнала ОС** формы запроса отфильтруйте строки журнала основных средств, которые требуется включить в отчет.</span><span class="sxs-lookup"><span data-stu-id="29dde-158">On the **FA Journal Line** FastTab of the request form, filter the fixed asset journal lines to be included in the report.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="29dde-159">Фильтрацию можно выполнять по коду местоположения, чтобы просмотреть все ОС в определенном физическом местоположении, или по номеру сотрудника, чтобы просмотреть все ОС, за которые отвечает определенный сотрудник.</span><span class="sxs-lookup"><span data-stu-id="29dde-159">You can filter them by location code to see all fixed assets in a certain physical location, or you can filter them by employee number to see all fixed assets that a certain employee is responsible for.</span></span>  

2.  <span data-ttu-id="29dde-160">В качестве фильтров в полях **Имя Шаблона Журнала** и **Код Раздела Журнала** по умолчанию указываются соответствующие значения из того раздела журнала, из которого был открыт отчет.</span><span class="sxs-lookup"><span data-stu-id="29dde-160">The filters on the **Journal Template Name** and **Journal Batch Name** fields are filled in by default with the corresponding values from the journal batch from where the report is called.</span></span>  
3.  <span data-ttu-id="29dde-161">На экспресс-вкладке **Параметры** задайте остальные параметры отчета.</span><span class="sxs-lookup"><span data-stu-id="29dde-161">On the **Options** FastTab, set other parameters for the report.</span></span> <span data-ttu-id="29dde-162">Все параметры на этой вкладке показаны в форме печати.</span><span class="sxs-lookup"><span data-stu-id="29dde-162">All the parameters on this tab are shown on the printing form.</span></span>  

## <a name="fixed-asset-comparative-sheet-inv-18-report"></a><span data-ttu-id="29dde-163">Отчет "ОС Сличительная Ведомость ИНВ-18"</span><span class="sxs-lookup"><span data-stu-id="29dde-163">Fixed Asset Comparative Sheet INV-18 Report</span></span>  
<span data-ttu-id="29dde-164">В отчете **ОС Сличительная Ведомость ИНВ-18** приводится список тех строк журнала основных средств, в которых имеются различия между расчетными и фактическими количествами или суммами для основных средств, прошедших инвентаризацию.</span><span class="sxs-lookup"><span data-stu-id="29dde-164">The **Fixed Asset Comparative Sheet INV-18** report shows the list of fixed asset journal lines, but only those that have differences between calculated and actual quantities or amounts of inventoried fixed assets.</span></span> <span data-ttu-id="29dde-165">Строки журнала с основными средствами, прошедшими инвентаризацию, можно отфильтровать в форме запроса данного отчета.</span><span class="sxs-lookup"><span data-stu-id="29dde-165">The journal lines with inventoried fixed assets can be filtered in the request form of the report.</span></span> <span data-ttu-id="29dde-166">В отчете показаны расчетные и фактические количества и суммы соответствующих ОС.</span><span class="sxs-lookup"><span data-stu-id="29dde-166">The report shows the calculated and actual quantities and amounts of the inventoried fixed assets.</span></span> <span data-ttu-id="29dde-167">Отчет **ОС Сличительная Ведомость ИНВ-18** можно напечатать.</span><span class="sxs-lookup"><span data-stu-id="29dde-167">You can print the **Fixed Asset Comparative Sheet INV-18** report.</span></span>  

<span data-ttu-id="29dde-168">Процедура печати отчета "ОС Сличительная Ведомость ИНВ-18" аналогична таковой для отчета "ОС Сличительная Ведомость ИНВ-1".</span><span class="sxs-lookup"><span data-stu-id="29dde-168">The procedure to print the Fixed Asset Comparative Sheet INV-18 report is similar to the Fixed Asset Comparative Sheet INV-1 report.</span></span>  

## <a name="see-also"></a><span data-ttu-id="29dde-169">См. также</span><span class="sxs-lookup"><span data-stu-id="29dde-169">See Also</span></span>  
[<span data-ttu-id="29dde-170">ОС: местоположения и ответственные сотрудники</span><span class="sxs-lookup"><span data-stu-id="29dde-170">Fixed Asset Locations and Employees</span></span>](fixed-asset-locations-and-employees.md)

