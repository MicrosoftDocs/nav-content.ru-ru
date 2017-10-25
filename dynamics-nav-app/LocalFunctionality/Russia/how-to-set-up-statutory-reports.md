---
title: "Практическое руководство. Настройка регламентных отчетов"
description: "Налоговые органы Российской Федерации требуют от организаций подачи регламентных отчетов в электронных форматах, например в формате XML или Microsoft Excel. В [!INCLUDE[navnow](../../includes/navnow_md.md)] необходимо настроить шаблоны, форматы, XML-схемы и другие параметры, чтобы вы могли формировать нужные файлы."
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
ms.openlocfilehash: a430bf7cff26db9c9c606e8364cf85e6ec362e70
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-statutory-reports"></a><span data-ttu-id="41afa-104">Практическое руководство. Настройка регламентных отчетов</span><span class="sxs-lookup"><span data-stu-id="41afa-104">How to: Set Up Statutory Reports</span></span>
<span data-ttu-id="41afa-105">Налоговые органы Российской Федерации требуют от организаций подачи регламентных отчетов в электронных форматах, например в формате XML или Microsoft Excel.</span><span class="sxs-lookup"><span data-stu-id="41afa-105">The Russian federal tax authorities require companies to submit statutory reports in electronic formats such as XML or as Microsoft Excel documents.</span></span> <span data-ttu-id="41afa-106">В [!INCLUDE[navnow](../../includes/navnow_md.md)] необходимо настроить шаблоны, форматы, XML-схемы и другие параметры, чтобы вы могли формировать нужные файлы.</span><span class="sxs-lookup"><span data-stu-id="41afa-106">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you must set up the templates, formats, XML schemas, and other prerequisites so that you can generate the required files.</span></span>  
  
 <span data-ttu-id="41afa-107">После настройки отчета и указания необходимой информации вы можете экспортировать отчет в Microsoft Excel или печатать его.</span><span class="sxs-lookup"><span data-stu-id="41afa-107">After you have set up a report and specified the required information, you can export the report to Excel, and then print the report.</span></span>  
  
 <span data-ttu-id="41afa-108">Дополнительные сведения см. в разделах [Директивы регламентных отчетов](http://go.microsoft.com/fwlink/?LinkId=216143) и [ПО для подготовки регламентных отчетов](http://go.microsoft.com/fwlink/?LinkId=216142) на веб-сайте Федеральной налоговой службы.</span><span class="sxs-lookup"><span data-stu-id="41afa-108">For more information, see [Statutory Reporting Directives](http://go.microsoft.com/fwlink/?LinkId=216143) and [Statutory Reporting Software](http://go.microsoft.com/fwlink/?LinkId=216142) on the Federal Tax Service website.</span></span>  
  
 <span data-ttu-id="41afa-109">Сначала необходимо настроить общие сведения, которые применяются ко всем регламентным отчетам.</span><span class="sxs-lookup"><span data-stu-id="41afa-109">First, you must set up general information that applies to all statutory reports.</span></span>  
  
### <a name="to-set-up-general-information-about-statutory-reports"></a><span data-ttu-id="41afa-110">Настройка общих сведений о регламентных отчетах</span><span class="sxs-lookup"><span data-stu-id="41afa-110">To set up general information about statutory reports</span></span>  
  
1.  <span data-ttu-id="41afa-111">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка регламентных отчетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="41afa-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Statutory Report Setup**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="41afa-112">На экспресс-вкладке **Общее** заполните поля, чтобы описать форматирование XML, местоположения файлов и другие параметры.</span><span class="sxs-lookup"><span data-stu-id="41afa-112">On the **General** FastTab, fill in the fields to describe XML formatting, file locations, and so on.</span></span>  
  
3.  <span data-ttu-id="41afa-113">На экспресс-вкладке **Нумерация** заполните поля, чтобы описать серии номеров для журналов экспорта данных и импорта данных.</span><span class="sxs-lookup"><span data-stu-id="41afa-113">On the **Numbering** FastTab, fill in the fields to describe the number series to use for data export and data import logs.</span></span>  
  
 <span data-ttu-id="41afa-114">Следующая процедура является необязательной.</span><span class="sxs-lookup"><span data-stu-id="41afa-114">The following procedure is optional.</span></span> <span data-ttu-id="41afa-115">Она позволяет настроить группы для объединения различных типов отчетов.</span><span class="sxs-lookup"><span data-stu-id="41afa-115">It allows you to set up groups in which to group different types of reports.</span></span>  
  
### <a name="to-set-up-statutory-report-groups"></a><span data-ttu-id="41afa-116">Настройка групп регламентных отчетов</span><span class="sxs-lookup"><span data-stu-id="41afa-116">To set up statutory report groups</span></span>  
  
1.  <span data-ttu-id="41afa-117">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка групп регламентных отчетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="41afa-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Statutory Report Groups**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="41afa-118">На вкладке **Главная** выберите **Создать**.</span><span class="sxs-lookup"><span data-stu-id="41afa-118">On the **Home** tab, choose **New**.</span></span> <span data-ttu-id="41afa-119">В поле **Код** введите код группы, а в поле **Описание** введите описание цели группы.</span><span class="sxs-lookup"><span data-stu-id="41afa-119">In the **Code** field, enter a code for the group, and in the **Description** field, enter a description of the purpose of the group.</span></span>  
  
 <span data-ttu-id="41afa-120">Затем необходимо настроить версии отчетов.</span><span class="sxs-lookup"><span data-stu-id="41afa-120">Next, you must set up report versions.</span></span>  
  
### <a name="to-set-up-report-versions"></a><span data-ttu-id="41afa-121">Настройка версий отчетов</span><span class="sxs-lookup"><span data-stu-id="41afa-121">To set up report versions</span></span>  
  
1.  <span data-ttu-id="41afa-122">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Версии форматов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="41afa-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Format Versions**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="41afa-123">Заполните поля для описания версий форматов регламентных отчетов.</span><span class="sxs-lookup"><span data-stu-id="41afa-123">Fill in the fields to describe the format version of the statutory report.</span></span>  
  
3.  <span data-ttu-id="41afa-124">На вкладке **Главная** в группе **Процес** импортируйте шаблон Excel или схему XML.</span><span class="sxs-lookup"><span data-stu-id="41afa-124">On the **Home** tab, in the **Process** group, choose to import an Excel Template or and XML schema.</span></span>  
  
     <span data-ttu-id="41afa-125">В зависимости от типа отчета можно импортировать шаблоны Microsoft Excel как файлы .xls либо импортировать XML-схемы как файлы .xml или .xsd.</span><span class="sxs-lookup"><span data-stu-id="41afa-125">Depending on the type of report, you can import Microsoft Excel templates as .xls files or you can import XML schemas as .xml or .xsd files.</span></span> <span data-ttu-id="41afa-126">Вы также можете указать дату начала периода использования регламентного отчета.</span><span class="sxs-lookup"><span data-stu-id="41afa-126">You can also define the start date for when the statutory report must be used.</span></span>  
  
 <span data-ttu-id="41afa-127">При объявлении новой версии отчета вы можете добавить ее к списку версий в этом окне.</span><span class="sxs-lookup"><span data-stu-id="41afa-127">When a new version of a report is announced, you can add it to the version list in this window.</span></span>  
  
## <a name="defining-statutory-reports"></a><span data-ttu-id="41afa-128">Определение регламентных отчетов</span><span class="sxs-lookup"><span data-stu-id="41afa-128">Defining Statutory Reports</span></span>  
 <span data-ttu-id="41afa-129">После этого необходимо определить каждый регламентный отчет.</span><span class="sxs-lookup"><span data-stu-id="41afa-129">Next, you must define each statutory report.</span></span>  
  
#### <a name="to-define-a-statutory-report"></a><span data-ttu-id="41afa-130">Определение регламентного отчета</span><span class="sxs-lookup"><span data-stu-id="41afa-130">To define a statutory report</span></span>  
  
1.  <span data-ttu-id="41afa-131">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Регламентные отчеты**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="41afa-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Statutory Reports**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="41afa-132">При необходимости можно создать одну или несколько строк, объединяющих набор регламентных отчетов, например отчетов по НДС или отчетов по налогу на имущество.</span><span class="sxs-lookup"><span data-stu-id="41afa-132">Optionally, you can create one or more rows that group a range of statutory reports, such as reports for VAT reporting or reports for property tax.</span></span> <span data-ttu-id="41afa-133">Чтобы определить строку для внутренней группировки, заполните поля **Код** и **Описание**, а затем установите флажок **Заголовок**.</span><span class="sxs-lookup"><span data-stu-id="41afa-133">To specify a row as an internal grouping, enter information in the **Code** and **Description** fields, and the select the **Header** check box.</span></span> <span data-ttu-id="41afa-134">Остальные поля оставьте пустыми.</span><span class="sxs-lookup"><span data-stu-id="41afa-134">Leave the other fields blank.</span></span>  
  
3.  <span data-ttu-id="41afa-135">Чтобы определить строку как регламентный отчет, создайте новую запись и заполните поля, чтобы описать этот регламентный отчет.</span><span class="sxs-lookup"><span data-stu-id="41afa-135">To specify a row as a statutory report, create a new entry and fill in the fields to describe the statutory report.</span></span>  
  
     <span data-ttu-id="41afa-136">Для каждого регламентного отчета в поле **Код версии формата** можно указать текущую версию, которая должна использоваться для отчетов этого типа.</span><span class="sxs-lookup"><span data-stu-id="41afa-136">For each statutory report, in the **Format Version Code** field, you can specify the current version to use for this kind of report.</span></span>  
  
4.  <span data-ttu-id="41afa-137">Для каждого регламентного отчета выберите **Навигация** и в группе **Настройка** выберите **Таблицы**.</span><span class="sxs-lookup"><span data-stu-id="41afa-137">For each statutory report, choose **Navigate**, and in the **Setup** group, choose **Tables**.</span></span>  
  
    1.  <span data-ttu-id="41afa-138">В окне **Таблицы регламентного отчета** заполните поля с описанием каждой таблицы, которая должна быть создана в книге Microsoft Excel.</span><span class="sxs-lookup"><span data-stu-id="41afa-138">In the **Statutory Report Tables** window, fill in the fields to describe each table that must be created in the Microsoft Excel workbook.</span></span> <span data-ttu-id="41afa-139">../../включает указание названия книги.</span><span class="sxs-lookup"><span data-stu-id="41afa-139">This ../../includes specifying the name of the worksheet.</span></span>  
  
         <span data-ttu-id="41afa-140">Например, согласно требованиям вы можете подавать регламентный отчет в формате книги Microsoft Excel, где каждому разделу отчета соответствует отдельная таблица.</span><span class="sxs-lookup"><span data-stu-id="41afa-140">For example, a statutory report can require that you submit a Microsoft Excel workbook with a separate table for each section of the report.</span></span>  
  
    2.  <span data-ttu-id="41afa-141">Для каждой таблицы определите строки и столбцы.</span><span class="sxs-lookup"><span data-stu-id="41afa-141">For each table, specify the table rows and table columns.</span></span>  
  
         <span data-ttu-id="41afa-142">Также можно определить отдельные требования.</span><span class="sxs-lookup"><span data-stu-id="41afa-142">You can also specify individual requisites.</span></span> <span data-ttu-id="41afa-143">Закройте окна таблиц.</span><span class="sxs-lookup"><span data-stu-id="41afa-143">Close the table windows.</span></span>  
  
5.  <span data-ttu-id="41afa-144">Для каждого регламентного отчета выберите **Навигация** и в группе **Настройка** выберите **Строки XML элемента**.</span><span class="sxs-lookup"><span data-stu-id="41afa-144">For each statutory report, choose **Navigate**, and in the **Setup** group, choose **XML Element Lines**.</span></span>  
  
    -   <span data-ttu-id="41afa-145">В окне **Строки XML элемента** заполните поля, чтобы описать структуру XML-файла для экспорта.</span><span class="sxs-lookup"><span data-stu-id="41afa-145">In the **XML Element Lines** window, fill in the fields to describe the XML structure of the file that you will export.</span></span> <span data-ttu-id="41afa-146">Вы можете использовать выражения для расчета значений или использовать табличные данные в явном виде.</span><span class="sxs-lookup"><span data-stu-id="41afa-146">You can use expressions to calculate values, or you can use table data directly.</span></span>  
  
         <span data-ttu-id="41afa-147">Вы можете связать каждый элемент XML с таблицей, определенной в окне **Таблицы регламентного отчета**.</span><span class="sxs-lookup"><span data-stu-id="41afa-147">You can link each XML element line to a table that you defined in the **Statutory Report Tables** window for that statutory report.</span></span>  
  
6.  <span data-ttu-id="41afa-148">При необходимости, если требуется определить регламентный отчет на основе имеющегося отчета, можно скопировать имеющийся отчет.</span><span class="sxs-lookup"><span data-stu-id="41afa-148">Optionally, if you want to define a statutory report that resembles an existing report, you can copy the existing report.</span></span>  
  
    1.  <span data-ttu-id="41afa-149">В окне **Регламентные отчеты** создайте операцию, введя код в поле **Код**.</span><span class="sxs-lookup"><span data-stu-id="41afa-149">In the **Statutory Reports** window, create an entry by entering a code in the **Code** field.</span></span>  
  
    2.  <span data-ttu-id="41afa-150">Выберите **Навигация** и в группе **Настройка** выберите **Копировать отчет**.</span><span class="sxs-lookup"><span data-stu-id="41afa-150">Choose **Navigate**, and in the **Setup** group, choose **Copy Report**.</span></span>  
  
    3.  <span data-ttu-id="41afa-151">В окне **Копирование регламентного отчета** в поле **Копировать из отчета - код** выберите имеющийся отчет, а затем нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="41afa-151">In the **Copy Statutory Report** window, in the **Copy From Report Code** field, select the existing report, and then choose the **OK** button.</span></span>  
  
         <span data-ttu-id="41afa-152">Будет создана копия имеющегося отчета со строками из таблиц и элементов XML.</span><span class="sxs-lookup"><span data-stu-id="41afa-152">This creates a copy of the existing report with the tables and XML element lines.</span></span> <span data-ttu-id="41afa-153">Теперь вы можете внести необходимые изменения, как было описано ранее в этом разделе.</span><span class="sxs-lookup"><span data-stu-id="41afa-153">Now, you can make the appropriate changes as described earlier in this section.</span></span>  
  
 <span data-ttu-id="41afa-154">Теперь вы можете использовать определенные регламентные отчеты, чтобы формировать и отправлять отчеты для соответствующих органов.</span><span class="sxs-lookup"><span data-stu-id="41afa-154">You can now use the defined statutory reports to generate and submit reports to the authorities.</span></span> <span data-ttu-id="41afa-155">Дополнительные сведения см. в разделе [Практическое руководство. Создание данных регламентного отчета](how-to-create-statutory-report-data.md).</span><span class="sxs-lookup"><span data-stu-id="41afa-155">For more information, see [How to: Create Statutory Report Data](how-to-create-statutory-report-data.md).</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="41afa-156">См. также</span><span class="sxs-lookup"><span data-stu-id="41afa-156">See Also</span></span>  
 <span data-ttu-id="41afa-157">[Регламентные отчеты](statutory-reports.md) </span><span class="sxs-lookup"><span data-stu-id="41afa-157">[Statutory Reports](statutory-reports.md) </span></span>  
 [<span data-ttu-id="41afa-158">Практическое руководство. Создание данных регламентного отчета</span><span class="sxs-lookup"><span data-stu-id="41afa-158">How to: Create Statutory Report Data</span></span>](how-to-create-statutory-report-data.md)
