---
title: "Настройка и подача отчетности Интрастат"
description: "Узнайте, как настраивать функции отчетности Интрастат, а также как отчитываться о торговле с организациями из других стран ЕС."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, Intrastat, trade, EU, European Union
ms.date: 08/15/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 96a840ed697df0bb74755af92ced351ebf26ea40
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-and-report-intrastat"></a><span data-ttu-id="d93fc-103">Практическое руководство. Настройка и подача отчетности Интрастат</span><span class="sxs-lookup"><span data-stu-id="d93fc-103">How To: Set Up and Report Intrastat</span></span>
<span data-ttu-id="d93fc-104">Все организации в странах ЕС должны подавать отчет о торговых операциях с другими странами/регионами Евросоюза.</span><span class="sxs-lookup"><span data-stu-id="d93fc-104">All companies in the European Union must report their trade with other EU countries/regions.</span></span> <span data-ttu-id="d93fc-105">Необходимо подавать ежемесячный отчет о перемещении товаров в статистическое бюро, а также отчет в налоговые органы вашей страны/региона.</span><span class="sxs-lookup"><span data-stu-id="d93fc-105">You must report the movement of goods to the statistics authorities in your country/region every month, and the report must be delivered to the tax authorities.</span></span> <span data-ttu-id="d93fc-106">Эти функции называются "Отчеты Интрастат".</span><span class="sxs-lookup"><span data-stu-id="d93fc-106">This is referred to as Intrastat Reporting.</span></span> <span data-ttu-id="d93fc-107">Заполнение периодических отчетов Интрастат осуществляется на странице **Журнал Интрастат**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-107">You use the **Intrastat Journal** page to complete periodic Intrastat reports.</span></span>  
  
## <a name="required-and-optional-setups"></a><span data-ttu-id="d93fc-108">Обязательные и необязательные настройки</span><span class="sxs-lookup"><span data-stu-id="d93fc-108">Required and Optional Setups</span></span>
<span data-ttu-id="d93fc-109">Перед началом использования журнала Интрастат для подачи информации Интрастат необходимо выполнить несколько настроек:</span><span class="sxs-lookup"><span data-stu-id="d93fc-109">Before you can use the Intrastat journal to report Intrastat information, there are several things you must set up:</span></span>  
  
* <span data-ttu-id="d93fc-110">**Шаблоны журнала Интрастат**: необходимо настроить шаблоны и раздела журнала Интрастат, которые будут использоваться.</span><span class="sxs-lookup"><span data-stu-id="d93fc-110">**Intrastat journal templates**: You must set up the Intrastat journal templates and batches you will use.</span></span> <span data-ttu-id="d93fc-111">Поскольку отчет Интрастат подается ежемесячно, необходимо создать 12 разделов журнала Интрастат на базе одного и того же шаблона.</span><span class="sxs-lookup"><span data-stu-id="d93fc-111">Because Intrastat is reported monthly, you must create 12 Intrastat journal batches based on the same template.</span></span>  
* <span data-ttu-id="d93fc-112">**Товарные коды**: таможенные и налоговые органы определяют числовые коды классификации товаров и услуг.</span><span class="sxs-lookup"><span data-stu-id="d93fc-112">**Commodity codes**: Customs and tax authorities have established numerical codes that classify items and services.</span></span> <span data-ttu-id="d93fc-113">Вы указываете эти коды на товарах.</span><span class="sxs-lookup"><span data-stu-id="d93fc-113">You specify these codes on items.</span></span>
* <span data-ttu-id="d93fc-114">**Коды характера транзакции**: в разных странах и регионах имеются различные коды для типов транзакций Интрастат, таких как обычная купля и продажа, замена возвращенных товаров и замена невозвращенных товаров.</span><span class="sxs-lookup"><span data-stu-id="d93fc-114">**Transaction nature codes**: Countries and regions have different codes for types of Intrastat transactions, such as ordinary purchase and sale, exchange of returned goods, and exchange of non-returned goods.</span></span> <span data-ttu-id="d93fc-115">Настройте все коды, которые применяются в вашей стране или регионе.</span><span class="sxs-lookup"><span data-stu-id="d93fc-115">Set up all of the codes that apply to your country/region.</span></span> <span data-ttu-id="d93fc-116">Эти коды используются в документах покупок и продаж, а также при обработке возвратов.</span><span class="sxs-lookup"><span data-stu-id="d93fc-116">You use these codes on sales and purchase documents, and when you process returns.</span></span>  
* <span data-ttu-id="d93fc-117">**Методы перевозки**: предусмотрено семь однозначных кодов для методов перевозки Интрастат.</span><span class="sxs-lookup"><span data-stu-id="d93fc-117">**Transport methods**: There are seven, one-digit codes for Intrastat transport methods.</span></span> <span data-ttu-id="d93fc-118">**1** для морских перевозок, **2** для железнодорожных перевозок, **3** для автомобильных перевозок, **4** для авиационных перевозок, **5** для отправке по почте, **7** для фиксированных установок и **9** для перевозок своим ходом (например, транспортировка автомобиля своим ходом).</span><span class="sxs-lookup"><span data-stu-id="d93fc-118">**1** for sea, **2** for rail, **3** for road, **4** for air, **5** for post, **7** for fixed installations, and **9** for own propulsion (for eample, transporting a car by driving it).</span></span> <span data-ttu-id="d93fc-119">Для Dynamics NAV эти коды не требуются, однако рекомендуется, чтобы описания имели аналогичное значение.</span><span class="sxs-lookup"><span data-stu-id="d93fc-119">Dynamics NAV does not require these codes, however, we recommend that the descriptions provide a similar meaning.</span></span>  

<span data-ttu-id="d93fc-120">При желании можно также настроить:</span><span class="sxs-lookup"><span data-stu-id="d93fc-120">Optionally, you can also set up:</span></span>

* <span data-ttu-id="d93fc-121">**Спецификации транзакции**: с их помощью можно дополнять описания из типов транзакций.</span><span class="sxs-lookup"><span data-stu-id="d93fc-121">**Transaction specifications**: Use these to supplement the descriptions from the transaction types.</span></span>  
* <span data-ttu-id="d93fc-122">**Области**: с их помощью можно указывать дополнительную информацию о странах и регионах.</span><span class="sxs-lookup"><span data-stu-id="d93fc-122">**Areas**: Use these to supplement information about countries and regions.</span></span>  
* <span data-ttu-id="d93fc-123">**Пункты ввоза/вывоза**: с их помощью можно указывать склады, на которые отправляются товары в другие страны или на которых получаются товары из других стран.</span><span class="sxs-lookup"><span data-stu-id="d93fc-123">**Entry/exit points**: Use these to specify the locations where you ship or receive items to or from other countries.</span></span> <span data-ttu-id="d93fc-124">Примером пункта ввоза или вывоза может служить аэропорт Хитроу.</span><span class="sxs-lookup"><span data-stu-id="d93fc-124">Heathrow Airport is an example of an entry or exit point.</span></span> <span data-ttu-id="d93fc-125">Пункт ввоза или вывоза указывается в документах продаж и покупок на экспресс-вкладке **Внешняя торговля**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-125">You enter entry or exit points on sales and purchase documents on the **Foreign Trade** FastTab.</span></span> <span data-ttu-id="d93fc-126">Эта информация также копируется из записей о товарах при создании журнала Интрастат.</span><span class="sxs-lookup"><span data-stu-id="d93fc-126">This information will also be copied from the item entries when you create the Intrastat journal.</span></span>  

### <a name="to-set-up-intrastat-templates-and-batches"></a><span data-ttu-id="d93fc-127">Настройка шаблонов и разделов Интрастат</span><span class="sxs-lookup"><span data-stu-id="d93fc-127">To set up Intrastat templates and batches</span></span>
<span data-ttu-id="d93fc-128">Пакетное задание Интрастат включает только операции товаров, но не операции главной книги.</span><span class="sxs-lookup"><span data-stu-id="d93fc-128">The Intrastat batch jobs include only item entries, and not general ledger entries.</span></span> <span data-ttu-id="d93fc-129">При наличии операций главной книги, которые должны быть включены в отчетность Интрастат, необходимо ввести их вручную.</span><span class="sxs-lookup"><span data-stu-id="d93fc-129">If you have general ledger entries that qualify for Intrastat reporting, you must enter them manually.</span></span> <span data-ttu-id="d93fc-130">Например, если вы приобрели компьютер в другой стране или /регионе ЕС, этот компьютер не включается в состав запасов, но учитывается в счете главной книги.</span><span class="sxs-lookup"><span data-stu-id="d93fc-130">For example, if you purchase a computer from another EU country or region, the computer is not placed in inventory, but is posted to a general ledger account.</span></span> <span data-ttu-id="d93fc-131">Необходимо вручную ввести операции такого типа в журнал Интрастат.</span><span class="sxs-lookup"><span data-stu-id="d93fc-131">You must manually enter this type of entry in the Intrastat journal.</span></span>  
  
<span data-ttu-id="d93fc-132">Операции можно экспортировать в файл, который можно отправить в органы Интрастат.</span><span class="sxs-lookup"><span data-stu-id="d93fc-132">You can export the entries to a file that you can send to your Intrastat authorities.</span></span> <span data-ttu-id="d93fc-133">Отчет можно также напечатать, вручную ввести сведения в формы из ответственных органов, и затем подать информацию.</span><span class="sxs-lookup"><span data-stu-id="d93fc-133">You can also print a report, manually enter the information on the forms from your authorities, and then submit the information.</span></span>

>  [!Note]
> <span data-ttu-id="d93fc-134">Рекомендуется настроить раздел журнала Интрастат для каждого месяца.</span><span class="sxs-lookup"><span data-stu-id="d93fc-134">We recommended that you set up an Intrastat journal batch for each month.</span></span>  
  
1. <span data-ttu-id="d93fc-135">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Шаблоны журналов Интрастат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journal Templates**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-136">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="d93fc-136">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]<span data-ttu-id="d93fc-137">.</span><span class="sxs-lookup"><span data-stu-id="d93fc-137">.</span></span> <span data-ttu-id="d93fc-138">Создайте шаблон для каждой формы Интрастат, которую вы используйте.</span><span class="sxs-lookup"><span data-stu-id="d93fc-138">Create a template for each Intrastat form you use.</span></span>  
3. <span data-ttu-id="d93fc-139">Для создания разделов выберите вкладку **Навигация**, затем выберите **Разделы**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-139">To create batches, choose the **Navigate** tab, and then choose **Batches**.</span></span>  
4. <span data-ttu-id="d93fc-140">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="d93fc-140">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]<span data-ttu-id="d93fc-141">.</span><span class="sxs-lookup"><span data-stu-id="d93fc-141">.</span></span> <span data-ttu-id="d93fc-142">Создайте шаблон для каждой формы Интрастат, которую вы используйте.</span><span class="sxs-lookup"><span data-stu-id="d93fc-142">Create a template for each Intrastat form you use..</span></span>  

> [!Note]
> <span data-ttu-id="d93fc-143">В поле **Статистика - период** введите статистический период в виде четырехзначного числа, в котором первые две цифры указывают на год, а следующие две — на месяц.</span><span class="sxs-lookup"><span data-stu-id="d93fc-143">In the **Statistics Period** field, enter the statistics period as a four-digit number, where the first two digits represent the year and the next two digits represent the month.</span></span> <span data-ttu-id="d93fc-144">Например, введите 1706 для июня 2017 г.</span><span class="sxs-lookup"><span data-stu-id="d93fc-144">For example, enter 1706 for June, 2017.</span></span>

### <a name="to-set-up-commodity-codes"></a><span data-ttu-id="d93fc-145">Настройка товарных кодов</span><span class="sxs-lookup"><span data-stu-id="d93fc-145">To set up commodity codes</span></span>
<span data-ttu-id="d93fc-146">Все покупаемые и продаваемые вами товары должны иметь товарный код.</span><span class="sxs-lookup"><span data-stu-id="d93fc-146">All items that you buy or sell must have a commodity code.</span></span>  
  
1. <span data-ttu-id="d93fc-147">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Товарные коды**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-147">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Commodity Codes**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-148">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="d93fc-148">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. <span data-ttu-id="d93fc-149">Чтобы назначить товарный код товару, перейдите на страницу **Карточка товара**, разверните экспресс-вкладку **Затраты и учет**, затем введите код в поле **Товарный код**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-149">To assign a commodity code to an item, go to the **Item Card** page, expand the **Costs & Posting** FastTab, and then enter the code in the **Commodity Code** field.</span></span>   

### <a name="to-set-up-transaction-nature-codes"></a><span data-ttu-id="d93fc-150">Настройка кодов характера транзакции</span><span class="sxs-lookup"><span data-stu-id="d93fc-150">To set up transaction nature codes</span></span>
1. <span data-ttu-id="d93fc-151">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Коды характера транзакции**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-151">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Transaction Nature Codes**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-152">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="d93fc-152">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

> [!Tip]
> <span data-ttu-id="d93fc-153">Если вы часто используете конкретный код характера транзакции, можно назначить его кодом по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="d93fc-153">If you frequently use a particular transaction nature code, you can make it the default.</span></span> <span data-ttu-id="d93fc-154">Чтобы это сделать, перейдите на страницу **Настройка Интрастат**, затем выберите код.</span><span class="sxs-lookup"><span data-stu-id="d93fc-154">To do this, go to the **Intrastat Setup** page, and choose the code.</span></span> 

### <a name="to-set-up-transport-methods"></a><span data-ttu-id="d93fc-155">Настройка методов перевозки</span><span class="sxs-lookup"><span data-stu-id="d93fc-155">To set up transport methods</span></span>
1. <span data-ttu-id="d93fc-156">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Методы перевозки**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-156">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Transport Methods**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-157">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="d93fc-157">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-report-intrastat"></a><span data-ttu-id="d93fc-158">Для подачи отчета Интрастат</span><span class="sxs-lookup"><span data-stu-id="d93fc-158">To Report Intrastat</span></span>
<span data-ttu-id="d93fc-159">После заполнения журнала Интрастат можно напечатать отчет **Контрольный список**, чтобы проверить правильность всей информации в журнале.</span><span class="sxs-lookup"><span data-stu-id="d93fc-159">After you fill in the Intrastat journal, you can print the **Checklist** report to make sure that that all information in the journal is correct.</span></span> <span data-ttu-id="d93fc-160">Затем можно распечатать отчет Интрастат в виде формы или создать файл для отправки в налоговый орган вашей страны или региона.</span><span class="sxs-lookup"><span data-stu-id="d93fc-160">Afterward, you can print an Intrastat report as a form, or create a file to submit to the tax authority in your country/region.</span></span>  

### <a name="to-fill-in-intrastat-journals"></a><span data-ttu-id="d93fc-161">Заполнение журналов Интрастат</span><span class="sxs-lookup"><span data-stu-id="d93fc-161">To fill in Intrastat journals</span></span>  
1. <span data-ttu-id="d93fc-162">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал Интрастат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-162">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journal** and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-163">На странице **Журнал Интрастат** в поле **Название пакета** выберите нужный пакета журнала, затем нажмите кнопку **OK**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-163">On the **Intrastat Journal** page, in the **Batch Name** field, choose the relevant journal batch, and then Choose the **OK** button.</span></span>  
3. <span data-ttu-id="d93fc-164">Выберите действие **Предложить строки**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-164">Choose the **Suggest Lines** action.</span></span> <span data-ttu-id="d93fc-165">Поля **Дата начала** и **Дата окончания** уже содержат даты, указанные в разделе журнала для периода статистики.</span><span class="sxs-lookup"><span data-stu-id="d93fc-165">The **Starting Date** and **Ending Date** fields will already contain the dates specified for the statistics period on the journal batch.</span></span>  
4. <span data-ttu-id="d93fc-166">В поле **Рег. себестоимости (%)** можно указать процент для покрытия транспортных расходов и расходов на страхование.</span><span class="sxs-lookup"><span data-stu-id="d93fc-166">In the **Cost Regulation %** field, you can enter a percentage to cover transport and insurance.</span></span> <span data-ttu-id="d93fc-167">Если указать процент, содержимое поля **Статистическое значение** в журнале будет пропорционально выше.</span><span class="sxs-lookup"><span data-stu-id="d93fc-167">If you enter a percentage, the content of the **Statistical Value** field in the journal is proportionally higher.</span></span>  
5. <span data-ttu-id="d93fc-168">Нажмите **ОК** для запуска пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="d93fc-168">Choose **OK** to start the batch job.</span></span>  
  
<span data-ttu-id="d93fc-169">При выполнении этого пакетного задания выполняется поиск всех операций с товаром в течение статистического периода и такие операции вставляются в журнал Интрастат в виде строк.</span><span class="sxs-lookup"><span data-stu-id="d93fc-169">The batch job retrieves all the item entries in the statistics period and inserts them as lines in the Intrastat journal.</span></span> <span data-ttu-id="d93fc-170">При необходимости можно отредактировать строки.</span><span class="sxs-lookup"><span data-stu-id="d93fc-170">You can edit the lines if needed.</span></span>  
  
> [!IMPORTANT]  
>  <span data-ttu-id="d93fc-171">Пакетное задание находит только те операции, которые содержат код страны или региона, для которых на странице **Страны/регионы** был введен код Интрастат.</span><span class="sxs-lookup"><span data-stu-id="d93fc-171">The batch job retrieves only the entries that contain a country/region code for which an Intrastat code has been entered on the **Countries/Regions** page.</span></span> <span data-ttu-id="d93fc-172">Поэтому необходимо указывать коды Интрастат стран/регионов, по которым будет выполняться пакетное задание.</span><span class="sxs-lookup"><span data-stu-id="d93fc-172">Therefore, you must enter Intrastat codes for the country/region codes for which you will run the batch job.</span></span>  

### <a name="how-to-report-intrastat-on-a-form-or-a-file"></a><span data-ttu-id="d93fc-173">Практическое руководство. Предоставление отчета Интрастат на бланке или в файле</span><span class="sxs-lookup"><span data-stu-id="d93fc-173">How to: Report Intrastat on a form or a file</span></span>
<span data-ttu-id="d93fc-174">Для получения информации, требуемой для заполнения формы Интрастат, предоставляемой в органы статистики, следует распечатать отчет **Интрастат - форма**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-174">To get the information that is required on the Intrastat form from the statistical authorities, you must print the **Intrastat – Form** report.</span></span> <span data-ttu-id="d93fc-175">Перед этим следует подготовить журнал «Интрастат» и заполнить его.</span><span class="sxs-lookup"><span data-stu-id="d93fc-175">Before you can do this, you must prepare the Intrastat journal and fill it in.</span></span> <span data-ttu-id="d93fc-176">Если имеются транзакции по покупкам и по продажам, следует заполнить отдельную форму для каждого типа, т. е. придется распечатать отчет дважды.</span><span class="sxs-lookup"><span data-stu-id="d93fc-176">If you have both sales and purchase transactions, you must complete a separate form for each type, so that you must print the report two times.</span></span>  
  
1. <span data-ttu-id="d93fc-177">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы Интрастат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-177">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-178">На странице **Журнал Интрастат** выберите соответствующий раздел журнала в поле **Код раздела**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-178">On the **Intrastat Journal** page, choose the relevant journal batch in the **Batch Name** field.</span></span>  
3. <span data-ttu-id="d93fc-179">Если это еще не сделано, заполните журнал вручную или выберите **Предложить строки**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-179">If you have not already done this, fill in the journal manually or choose **Suggest Lines**.</span></span>  
4. <span data-ttu-id="d93fc-180">Выберите действие **Печать журнала Интрастат**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-180">Choose the **Prints Intrastat Journal** action.</span></span>  
5. <span data-ttu-id="d93fc-181">На экспресс-вкладке **Журнал Интрастат - строка** добавьте фильтр **Тип** и укажите для него значение **Накладная** или **Расх. накладная**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-181">On the **Intrastat Jnl. Line** FastTab, add a **Type** filter and then specify whether this is a **Receipt** or a **Shipment**.</span></span>  
6. <span data-ttu-id="d93fc-182">Выберите **Отправить** для печати отчета.</span><span class="sxs-lookup"><span data-stu-id="d93fc-182">Choose **Send to** to print the report.</span></span>  

### <a name="how-to-report-intrastat-in-a-file"></a><span data-ttu-id="d93fc-183">Практическое руководство. Передача отчетов Интрастат в виде файла</span><span class="sxs-lookup"><span data-stu-id="d93fc-183">How to: Report Intrastat in a file</span></span>
<span data-ttu-id="d93fc-184">Отчет Интрастат может быть представлен в виде файла.</span><span class="sxs-lookup"><span data-stu-id="d93fc-184">You can submit the Intrastat report as a file.</span></span> <span data-ttu-id="d93fc-185">Перед созданием файла можно распечатать контрольную таблицу, содержащую ту же информацию, что и в файле.</span><span class="sxs-lookup"><span data-stu-id="d93fc-185">Before creating the file, you can print a checklist that contains the same information that will be in the file.</span></span>  
  
1. <span data-ttu-id="d93fc-186">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал Интрастат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-186">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journal**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-187">В окне **Журнал Интрастат** выберите соответствующий раздел журнала в поле **Код раздела**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-187">In the **Intrastat Journal** window, select the relevant journal batch in the **Batch Name** field.</span></span>  
3. <span data-ttu-id="d93fc-188">Если это еще не сделано, заполните журнал вручную или выбрав **Предложить строки**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-188">If you have not already done this, fill in the journal manually or by choosing **Suggest Lines**.</span></span>  
4. <span data-ttu-id="d93fc-189">Выберите действие **Создать файл**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-189">Choose the **Create File** action.</span></span>  
5. <span data-ttu-id="d93fc-190">В окне пакетного задания нажмите кнопку **OK**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-190">In the batch job window, Choose the **OK** button.</span></span>  
6. <span data-ttu-id="d93fc-191">Выберите **Сохранить**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-191">Choose **Save**.</span></span>  
7. <span data-ttu-id="d93fc-192">Перейдите в расположение, в котором требуется сохранить файл, ведите имя файла, затем выберите **Сохранить**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-192">Browse to the location where you want to save the file, enter the file name, and then choose **Save**.</span></span> 

## <a name="how-to-reorganize-intrastat-journals"></a><span data-ttu-id="d93fc-193">Практическое руководство. Перестройка журналов Интрастат</span><span class="sxs-lookup"><span data-stu-id="d93fc-193">How to: Reorganize Intrastat Journals</span></span>
<span data-ttu-id="d93fc-194">Поскольку отчет Интрастат должен предоставляться каждый месяц и для каждого отчета следует создавать новый раздел журнала, со временем таких разделов журнала будет много.</span><span class="sxs-lookup"><span data-stu-id="d93fc-194">Because you must submit an Intrastat report every month, and you create a new journal batch for each report, you will eventually have many journal batches.</span></span> <span data-ttu-id="d93fc-195">Строки журнала автоматически не удаляются.</span><span class="sxs-lookup"><span data-stu-id="d93fc-195">The journal lines are not deleted automatically.</span></span> <span data-ttu-id="d93fc-196">Периодически может возникать необходимость перестройки кодов разделов журнала.</span><span class="sxs-lookup"><span data-stu-id="d93fc-196">You may want to reorganize the journal batch names periodically.</span></span> <span data-ttu-id="d93fc-197">Это делается путем удаления разделов журнала, в которых больше нет необходимости.</span><span class="sxs-lookup"><span data-stu-id="d93fc-197">You do this by deleting the journal batches that you no longer need.</span></span> <span data-ttu-id="d93fc-198">Строки таких разделов журнала также удаляются.</span><span class="sxs-lookup"><span data-stu-id="d93fc-198">The journal lines in these batches are also deleted.</span></span>  
  
1. <span data-ttu-id="d93fc-199">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы Интрастат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d93fc-199">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intrastat Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d93fc-200">Для просмотра параметров выберите поле **Код раздела**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-200">To view the options, choose the **Batch Name** field.</span></span>  
3. <span data-ttu-id="d93fc-201">Выберите разделы журнала, которые требуется удалить, затем выберите **Удалить**.</span><span class="sxs-lookup"><span data-stu-id="d93fc-201">Choose the journal batches to deleted, and then choose **Delete**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="d93fc-202">См. также</span><span class="sxs-lookup"><span data-stu-id="d93fc-202">See Also</span></span>
[<span data-ttu-id="d93fc-203">Финансовый менеджмент</span><span class="sxs-lookup"><span data-stu-id="d93fc-203">Financial Management</span></span>](finance.md)

## 