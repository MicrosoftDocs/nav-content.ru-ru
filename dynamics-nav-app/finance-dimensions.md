---
title: "Работа с измерениями"
description: "Измерения служат для категоризации операций, например по отделам или проектам, чтобы данные было легко отслеживать и анализировать."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: analysis, history, track
ms.date: 06/14/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 95d8c0ddd8b12c2da7949b7ffbc9722edbc70d4e
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="working-with-dimensions"></a><span data-ttu-id="fb268-103">Работа с измерениями</span><span class="sxs-lookup"><span data-stu-id="fb268-103">Working with Dimensions</span></span>
<span data-ttu-id="fb268-104">Чтобы упростить анализ по документам, таким как заказы на продажу, можно использовать измерения.</span><span class="sxs-lookup"><span data-stu-id="fb268-104">To make it simpler to perform analysis on documents such as sales orders, you can use dimensions.</span></span> <span data-ttu-id="fb268-105">Измерения — это атрибуты и значения, которые классифицируют операции для их отслеживания и анализа.</span><span class="sxs-lookup"><span data-stu-id="fb268-105">Dimensions are attributes and values that categorize entries so you can track and analyze them.</span></span> <span data-ttu-id="fb268-106">Например, измерения могут указывать проект или отдел, который является источником операции.</span><span class="sxs-lookup"><span data-stu-id="fb268-106">For example, dimensions can indicate the project or department an entry came from.</span></span>  

<span data-ttu-id="fb268-107">Например, вместо настройки отдельных счетов главной книги для каждого отдела или проекта можно использовать измерения.</span><span class="sxs-lookup"><span data-stu-id="fb268-107">For example, instead of setting up separate general ledger accounts for each department and project, you can use dimensions.</span></span> <span data-ttu-id="fb268-108">Это дает прекрасные возможности анализа без создания сложного плана счетов.</span><span class="sxs-lookup"><span data-stu-id="fb268-108">This gives a rich opportunity for analysis, without creating a complicated chart of accounts.</span></span> <span data-ttu-id="fb268-109">Дополнительные сведения см. в разделе [Бизнес-аналитика](bi.md)</span><span class="sxs-lookup"><span data-stu-id="fb268-109">For more information, see [Business Intelligence](bi.md).</span></span>

<span data-ttu-id="fb268-110">Еще одним примером является настройка измерения *Отдел* и использование этого измерения при учете документов продажи.</span><span class="sxs-lookup"><span data-stu-id="fb268-110">Another example is to set up a dimension called *Department*, and use this dimension when you post sales documents.</span></span> <span data-ttu-id="fb268-111">Это позволит использовать инструменты бизнес-аналитик для просмотра того, какой отдел продал какие товары.</span><span class="sxs-lookup"><span data-stu-id="fb268-111">This will let you use business intelligence tools to see which department sold which items.</span></span>
<span data-ttu-id="fb268-112">Чем больше измерений вы используете, чем более подробные отчеты вы будете получать, чтобы принимать на их основе бизнес-решения.</span><span class="sxs-lookup"><span data-stu-id="fb268-112">The more dimensions you use, the more detailed reports you can base your business decisions on.</span></span> <span data-ttu-id="fb268-113">Например, одна операция продажи может содержать информацию о нескольких измерениях, например:</span><span class="sxs-lookup"><span data-stu-id="fb268-113">For example, a single sales entry can include multiple dimension information, such as:</span></span>  

* <span data-ttu-id="fb268-114">Счет, на котором был учтен товар.</span><span class="sxs-lookup"><span data-stu-id="fb268-114">The account the item sale was posted to</span></span>  
* <span data-ttu-id="fb268-115">Место продажи товара.</span><span class="sxs-lookup"><span data-stu-id="fb268-115">Where the item was sold</span></span>
* <span data-ttu-id="fb268-116">Лицо, продавшее товар.</span><span class="sxs-lookup"><span data-stu-id="fb268-116">Who sold it</span></span>
* <span data-ttu-id="fb268-117">Тип клиента, купившего товар.</span><span class="sxs-lookup"><span data-stu-id="fb268-117">The kind of customer who bought it</span></span>  

## <a name="analyzing-by-dimensions"></a><span data-ttu-id="fb268-118">Анализ по измерениям</span><span class="sxs-lookup"><span data-stu-id="fb268-118">Analyzing by Dimensions</span></span>
<span data-ttu-id="fb268-119">Функция измерений играет важную роль в бизнес-аналитике, например при определении представлений анализа.</span><span class="sxs-lookup"><span data-stu-id="fb268-119">The Dimensions functionality plays an important role in business intelligence, such as when defining analysis views.</span></span> <span data-ttu-id="fb268-120">Дополнительные сведения см. в разделе [Практическое руководство. Анализ данных по измерениям](bi-how-analyze-data-dimension.md).</span><span class="sxs-lookup"><span data-stu-id="fb268-120">For more information, see [How to: Analyze Data by Dimensions](bi-how-analyze-data-dimension.md).</span></span>

> [!TIP]
> <span data-ttu-id="fb268-121">Для быстрого анализа транзакционных данных по измерениям можно отфильтровать итоговые суммы в планах счетов и записи во всех окнах **Операции** по измерениям.</span><span class="sxs-lookup"><span data-stu-id="fb268-121">As a quick way to analyze transactional data by dimensions, you can filter totals in the chart of accounts and entries in all **Entries** windows by dimensions.</span></span> <span data-ttu-id="fb268-122">Найдите действие **Установить фильтр измерений**.</span><span class="sxs-lookup"><span data-stu-id="fb268-122">Look for the **Set Dimension Filter** action.</span></span>

## <a name="dimension-sets"></a><span data-ttu-id="fb268-123">Наборы измерений</span><span class="sxs-lookup"><span data-stu-id="fb268-123">Dimension Sets</span></span>
<span data-ttu-id="fb268-124">Набор измерений — это уникальная комбинация значений измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-124">A dimension set is a unique combination of dimension values.</span></span> <span data-ttu-id="fb268-125">Это храниться как записи набора измерений в базе данных.</span><span class="sxs-lookup"><span data-stu-id="fb268-125">It is stored as dimension set entries in the database.</span></span> <span data-ttu-id="fb268-126">Каждая запись набора измерений представляет отдельное значение измерения.</span><span class="sxs-lookup"><span data-stu-id="fb268-126">Each dimension set entry represents a single dimension value.</span></span> <span data-ttu-id="fb268-127">Набор измерений определяется общим кодом набора измерений, который присваивается каждой операции набора измерений, которая относится к набору измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-127">The dimension set is identified by a common dimension set ID that is assigned to each dimension set entry that belongs to the dimension set.</span></span>  

<span data-ttu-id="fb268-128">При создании строки журнала, заголовка документа или строки документа можно указать комбинации значений измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-128">When you create a journal line, document header, or document line, you can specify a combination of dimension values.</span></span> <span data-ttu-id="fb268-129">Вместо явного сохранения значения каждого измерения в базе данных, код набора измерений присваивается строке журнала, заголовку документа или строке документа для определения набора измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-129">Instead of explicitly storing each dimension value in the database, a dimension set ID is assigned to the journal line, document header, or document line to specify the dimension set.</span></span>  

## <a name="setting-up-dimensions"></a><span data-ttu-id="fb268-130">Настройка измерений</span><span class="sxs-lookup"><span data-stu-id="fb268-130">Setting Up Dimensions</span></span>
<span data-ttu-id="fb268-131">Можно определить измерения и значения измерений для категоризации журналов и документов, таких как заказы на покупку и заказы на продажу.</span><span class="sxs-lookup"><span data-stu-id="fb268-131">You can define the dimensions and dimension values to categorize journals and documents, such as sales orders and purchase orders.</span></span> <span data-ttu-id="fb268-132">Измерения можно настроить в окне **Измерения**, в котором создается по одной строке для каждого измерения, таких как *Проект*, *Отдел*, *Область* и *Менеджер по продажам*.</span><span class="sxs-lookup"><span data-stu-id="fb268-132">You set up dimensions in the **Dimensions** window, where you create one line for each dimension, such as *Project*, *Department*, *Area*, and *Salesperson*.</span></span>

<span data-ttu-id="fb268-133">Также можно настроить значения для измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-133">You also set up values for dimensions.</span></span> <span data-ttu-id="fb268-134">Например, значениями могут быть отделы в организации.</span><span class="sxs-lookup"><span data-stu-id="fb268-134">For example, values might be departments in your company.</span></span> <span data-ttu-id="fb268-135">Значения измерений можно настроить в иерархической структуре подобно плану счетов. После выполнения настройки можно будет разделять данные по нескольким уровням гранулярности, а также подсчитывать итоги по подмножествам значений измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-135">Dimension values can be set up in a hierarchical structure similar to the chart of accounts, so that data can be broken down into various levels of granularity, and subsets of dimension values can be totaled.</span></span> <span data-ttu-id="fb268-136">Можно задать любое количество измерений и значений измерений, и все пользователи в организации могут их использовать.</span><span class="sxs-lookup"><span data-stu-id="fb268-136">You can define as many dimensions and dimension values as you need, and everyone in your company can use them.</span></span>

<span data-ttu-id="fb268-137">Также можно настроить несколько глобальных измерений и ярлыков измерений:</span><span class="sxs-lookup"><span data-stu-id="fb268-137">You can also set up some global and shortcut dimensions:</span></span>  

* <span data-ttu-id="fb268-138">**Глобальные измерения** используются как фильтры, например в отчетах и пакетных заданиях.</span><span class="sxs-lookup"><span data-stu-id="fb268-138">**Global dimensions** are used as filters, for example, on reports and batch jobs.</span></span> <span data-ttu-id="fb268-139">Можно использовать только два глобальных измерения, поэтому выберите измерения, которые будут использоваться наиболее часто.</span><span class="sxs-lookup"><span data-stu-id="fb268-139">You can use only two global dimensions, so choose dimensions you will use often.</span></span>
* <span data-ttu-id="fb268-140">**Ярлыки измерений** доступны как поля в строках журналов и документов.</span><span class="sxs-lookup"><span data-stu-id="fb268-140">**Shortcut dimensions** are available as fields on journal and document lines.</span></span> <span data-ttu-id="fb268-141">Можно создать до шести ярлыков измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-141">You can create up to six of these.</span></span>  

### <a name="setting-up-default-dimensions-for-customers-vendors-and-other-accounts"></a><span data-ttu-id="fb268-142">Настройка измерений по умолчанию для клиентов, поставщиков и других счетов</span><span class="sxs-lookup"><span data-stu-id="fb268-142">Setting Up Default Dimensions for Customers, Vendors, and Other accounts</span></span>
<span data-ttu-id="fb268-143">Для конкретного счета можно назначить измерение по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="fb268-143">You can assign a default dimension for a specific account.</span></span> <span data-ttu-id="fb268-144">Измерение будет копироваться в журнал или документ при вводе номера счета в строку, но вы сможете удалить или изменить код в строке в случае необходимости.</span><span class="sxs-lookup"><span data-stu-id="fb268-144">The dimension will be copied to the journal or document when you enter the account number on a line, but you can delete or change the code on the line if appropriate.</span></span> <span data-ttu-id="fb268-145">Можно также создать измерение, необходимое для учета операции с определенным типом счета.</span><span class="sxs-lookup"><span data-stu-id="fb268-145">You can also make a dimension required for posting an entry with a specific type of account.</span></span>  

### <a name="translating-the-names-of-dimensions"></a><span data-ttu-id="fb268-146">Перевод имен измерений</span><span class="sxs-lookup"><span data-stu-id="fb268-146">Translating the Names of Dimensions</span></span>
<span data-ttu-id="fb268-147">При создании измерения и, в особенности, ярлыка измерения фактически вы создаете заголовок настраиваемого поля или столбца.</span><span class="sxs-lookup"><span data-stu-id="fb268-147">When you create a dimension, and especially a shortcut dimension, what you're actually creating is a custom field or column heading.</span></span> <span data-ttu-id="fb268-148">Если ваша организация международная, вы можете предоставить переводы имен измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-148">If your business is international, you can provide translations for the name of the dimension.</span></span> <span data-ttu-id="fb268-149">Документы, в которых встречается измерение, будут использовать переведенное имя, где это применимо.</span><span class="sxs-lookup"><span data-stu-id="fb268-149">Documents that include the dimension will use the translated name, where applicable.</span></span>   

### <a name="example-of-dimension-setup"></a><span data-ttu-id="fb268-150">Пример настройки измерений</span><span class="sxs-lookup"><span data-stu-id="fb268-150">Example of Dimension Setup</span></span>
<span data-ttu-id="fb268-151">Допустим, ваша организация желает отслеживать транзакции на основе организационной структуры и географического расположения.</span><span class="sxs-lookup"><span data-stu-id="fb268-151">Let's say that your company wants to track transactions based on organizational structure and geographic locations.</span></span> <span data-ttu-id="fb268-152">Для этого можно настроить два измерения в окне **Измерения**:</span><span class="sxs-lookup"><span data-stu-id="fb268-152">To do that, you can set up two dimensions in the **Dimensions** window:</span></span>

* <span data-ttu-id="fb268-153">**ОБЛАСТЬ**</span><span class="sxs-lookup"><span data-stu-id="fb268-153">**AREA**</span></span>  
* <span data-ttu-id="fb268-154">**ОТДЕЛ**</span><span class="sxs-lookup"><span data-stu-id="fb268-154">**DEPARTMENT**</span></span>  

| <span data-ttu-id="fb268-155">Код</span><span class="sxs-lookup"><span data-stu-id="fb268-155">Code</span></span> | <span data-ttu-id="fb268-156">Name</span><span class="sxs-lookup"><span data-stu-id="fb268-156">Name</span></span> | <span data-ttu-id="fb268-157">Метка кода</span><span class="sxs-lookup"><span data-stu-id="fb268-157">Code Caption</span></span> | <span data-ttu-id="fb268-158">Метка фильтра</span><span class="sxs-lookup"><span data-stu-id="fb268-158">Filter Caption</span></span> |
| --- | --- | --- | --- |
| <span data-ttu-id="fb268-159">РЕГИОН</span><span class="sxs-lookup"><span data-stu-id="fb268-159">AREA</span></span> |<span data-ttu-id="fb268-160">Регион</span><span class="sxs-lookup"><span data-stu-id="fb268-160">Area</span></span> |<span data-ttu-id="fb268-161">Код области</span><span class="sxs-lookup"><span data-stu-id="fb268-161">Area Code</span></span> |<span data-ttu-id="fb268-162">Фильтр области</span><span class="sxs-lookup"><span data-stu-id="fb268-162">Area Filter</span></span> |
| <span data-ttu-id="fb268-163">ОТДЕЛ</span><span class="sxs-lookup"><span data-stu-id="fb268-163">DEPARTMENT</span></span> |<span data-ttu-id="fb268-164">Отдел</span><span class="sxs-lookup"><span data-stu-id="fb268-164">Department</span></span> |<span data-ttu-id="fb268-165">Код подразделения</span><span class="sxs-lookup"><span data-stu-id="fb268-165">Department Code</span></span> |<span data-ttu-id="fb268-166">Фильтр по отделу</span><span class="sxs-lookup"><span data-stu-id="fb268-166">Department Filter</span></span> |

<span data-ttu-id="fb268-167">Для измерения **ОБЛАСТЬ** вы добавляете следующие значения измерения:</span><span class="sxs-lookup"><span data-stu-id="fb268-167">For **AREA**, you add the following dimension values:</span></span>

| <span data-ttu-id="fb268-168">Код</span><span class="sxs-lookup"><span data-stu-id="fb268-168">Code</span></span> | <span data-ttu-id="fb268-169">Name</span><span class="sxs-lookup"><span data-stu-id="fb268-169">Name</span></span> | <span data-ttu-id="fb268-170">Тип значения измерения</span><span class="sxs-lookup"><span data-stu-id="fb268-170">Dimension Value Type</span></span> |
| --- | --- | --- |
| <span data-ttu-id="fb268-171">10</span><span class="sxs-lookup"><span data-stu-id="fb268-171">10</span></span> |<span data-ttu-id="fb268-172">Центральная и Южная Америка</span><span class="sxs-lookup"><span data-stu-id="fb268-172">Americas</span></span> |<span data-ttu-id="fb268-173">Сумма (от)</span><span class="sxs-lookup"><span data-stu-id="fb268-173">Begin-Total</span></span> |
| <span data-ttu-id="fb268-174">2.0</span><span class="sxs-lookup"><span data-stu-id="fb268-174">20</span></span> |<span data-ttu-id="fb268-175">Северная Америка</span><span class="sxs-lookup"><span data-stu-id="fb268-175">North America</span></span> |<span data-ttu-id="fb268-176">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-176">Standard</span></span> |
| <span data-ttu-id="fb268-177">30</span><span class="sxs-lookup"><span data-stu-id="fb268-177">30</span></span> |<span data-ttu-id="fb268-178">Тихоокеанский регион</span><span class="sxs-lookup"><span data-stu-id="fb268-178">Pacific</span></span> |<span data-ttu-id="fb268-179">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-179">Standard</span></span> |
| <span data-ttu-id="fb268-180">40</span><span class="sxs-lookup"><span data-stu-id="fb268-180">40</span></span> |<span data-ttu-id="fb268-181">Южная Америка</span><span class="sxs-lookup"><span data-stu-id="fb268-181">South America</span></span> |<span data-ttu-id="fb268-182">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-182">Standard</span></span> |
| <span data-ttu-id="fb268-183">50</span><span class="sxs-lookup"><span data-stu-id="fb268-183">50</span></span> |<span data-ttu-id="fb268-184">Центральная и Южная Америка, всего</span><span class="sxs-lookup"><span data-stu-id="fb268-184">Americas, Total</span></span> |<span data-ttu-id="fb268-185">Сумма (до)</span><span class="sxs-lookup"><span data-stu-id="fb268-185">End-Total</span></span> |
| <span data-ttu-id="fb268-186">60</span><span class="sxs-lookup"><span data-stu-id="fb268-186">60</span></span> |<span data-ttu-id="fb268-187">Европа</span><span class="sxs-lookup"><span data-stu-id="fb268-187">Europe</span></span> |<span data-ttu-id="fb268-188">Сумма (от)</span><span class="sxs-lookup"><span data-stu-id="fb268-188">Begin-Total</span></span> |
| <span data-ttu-id="fb268-189">70</span><span class="sxs-lookup"><span data-stu-id="fb268-189">70</span></span> |<span data-ttu-id="fb268-190">ЕС</span><span class="sxs-lookup"><span data-stu-id="fb268-190">EU</span></span> |<span data-ttu-id="fb268-191">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-191">Standard</span></span> |
| <span data-ttu-id="fb268-192">80</span><span class="sxs-lookup"><span data-stu-id="fb268-192">80</span></span> |<span data-ttu-id="fb268-193">Страны-не члены ЕС</span><span class="sxs-lookup"><span data-stu-id="fb268-193">Non-EU</span></span> |<span data-ttu-id="fb268-194">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-194">Standard</span></span> |
| <span data-ttu-id="fb268-195">90</span><span class="sxs-lookup"><span data-stu-id="fb268-195">90</span></span> |<span data-ttu-id="fb268-196">Европа, всего</span><span class="sxs-lookup"><span data-stu-id="fb268-196">Europe, Total</span></span> |<span data-ttu-id="fb268-197">Сумма (до)</span><span class="sxs-lookup"><span data-stu-id="fb268-197">End-Total</span></span> |

<span data-ttu-id="fb268-198">Для двух основных географических областей (Центральная и Южная Америка и Европа) добавьте подкатегории для регионов, создав отступы значений измерения.</span><span class="sxs-lookup"><span data-stu-id="fb268-198">For the two main geographic areas, Americas and Europe, you add subcategories for regions by indenting the dimension values.</span></span> <span data-ttu-id="fb268-199">Это позволит создавать отчеты по продажам или расходам в регионах и получать итоги по более крупным географическим областям.</span><span class="sxs-lookup"><span data-stu-id="fb268-199">This will let you report on sales or expenses in regions, and get totals for the larger geographic areas.</span></span> <span data-ttu-id="fb268-200">Также можно использовать страны или регионы в качестве значений измерения или районы и города в зависимости от сферы деятельности организации.</span><span class="sxs-lookup"><span data-stu-id="fb268-200">You could also choose to use countries or regions as your dimension values, or counties or cities, depending on your business.</span></span>  
> [!NOTE]  
>   <span data-ttu-id="fb268-201">Чтобы настроить иерархию, коды должны быть расположены в алфавитном порядке.</span><span class="sxs-lookup"><span data-stu-id="fb268-201">To set up a hierarchy, the codes must be in alphabetical order.</span></span> <span data-ttu-id="fb268-202">Это включает коды значений измерений, предоставленных в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="fb268-202">This includes the codes of the dimension values that are provided in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

<span data-ttu-id="fb268-203">Для измерения **ОТДЕЛ** вы добавляете следующие значения измерения:</span><span class="sxs-lookup"><span data-stu-id="fb268-203">For **DEPARTMENT**, you add the following dimension values:</span></span>

| <span data-ttu-id="fb268-204">Код</span><span class="sxs-lookup"><span data-stu-id="fb268-204">Code</span></span> | <span data-ttu-id="fb268-205">Name</span><span class="sxs-lookup"><span data-stu-id="fb268-205">Name</span></span> | <span data-ttu-id="fb268-206">Тип значения измерения</span><span class="sxs-lookup"><span data-stu-id="fb268-206">Dimension Value Type</span></span> |
| --- | --- | --- |
| <span data-ttu-id="fb268-207">АДМИНИСТРАТОР</span><span class="sxs-lookup"><span data-stu-id="fb268-207">ADMIN</span></span> |<span data-ttu-id="fb268-208">Администрация</span><span class="sxs-lookup"><span data-stu-id="fb268-208">Administration</span></span> |<span data-ttu-id="fb268-209">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-209">Standard</span></span> |
| <span data-ttu-id="fb268-210">ПРОИЗВ</span><span class="sxs-lookup"><span data-stu-id="fb268-210">PROD</span></span> |<span data-ttu-id="fb268-211">Зона производства</span><span class="sxs-lookup"><span data-stu-id="fb268-211">Production</span></span> |<span data-ttu-id="fb268-212">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-212">Standard</span></span> |
| <span data-ttu-id="fb268-213">ПРОДАЖИ</span><span class="sxs-lookup"><span data-stu-id="fb268-213">SALES</span></span> |<span data-ttu-id="fb268-214">Продажи</span><span class="sxs-lookup"><span data-stu-id="fb268-214">Sales</span></span> |<span data-ttu-id="fb268-215">Стандартная</span><span class="sxs-lookup"><span data-stu-id="fb268-215">Standard</span></span> |

<span data-ttu-id="fb268-216">В этой настройке вы можете добавить два измерения в качестве глобальных измерений в окне **Настройка ГК**.</span><span class="sxs-lookup"><span data-stu-id="fb268-216">With this set up, you then add your two dimensions as the two global dimensions in the **General Ledger Setup** window.</span></span> <span data-ttu-id="fb268-217">Это означает, что можно использовать ОБЛАСТЬ и ОТДЕЛ в качестве фильтров для операций главной книги, а также для всех отчетов и финансовых отчетов.</span><span class="sxs-lookup"><span data-stu-id="fb268-217">This means that you can use AREA and DEPARTMENT as filters for general ledger entries, as well as on all reports and account schedules.</span></span> <span data-ttu-id="fb268-218">Оба глобальных измерения автоматически становятся доступными для использования в качестве ярлыков измерений в строках операций и заголовках документов.</span><span class="sxs-lookup"><span data-stu-id="fb268-218">Both global dimensions are also automatically available for use on entry lines and document headers as shortcut dimensions.</span></span>  

## <a name="using-dimensions"></a><span data-ttu-id="fb268-219">Использование измерений</span><span class="sxs-lookup"><span data-stu-id="fb268-219">Using Dimensions</span></span>
<span data-ttu-id="fb268-220">В документе, например в заказе на продажу, вы можете добавить сведения об измерении как для отдельной строки документа так и для самого документа.</span><span class="sxs-lookup"><span data-stu-id="fb268-220">In a document such as a sales order, you can add dimension information for both an individual document line and the document itself.</span></span> <span data-ttu-id="fb268-221">Например, в окне **Заказ на продажу** можно ввести значения измерений для первых двух ярлыков измерений в отдельных строках продажи, а затем добавить дополнительные измерения, нажав кнопку **Измерения**.</span><span class="sxs-lookup"><span data-stu-id="fb268-221">For example, in the **Sales Order** window, you can enter dimension values for the first two shortcut dimensions on the individual sales lines, and you can add more dimension information if you choose the **Dimensions** button.</span></span>  

<span data-ttu-id="fb268-222">При работе в журнале вы можете добавлять в операцию информацию об измерениях аналогичным образом, если непосредственно в строках журнала в качестве полей были заданы ярлыки измерений.</span><span class="sxs-lookup"><span data-stu-id="fb268-222">If you work in a journal instead, you can add dimension information to an entry in the same way, if you have set up shortcut dimensions as fields directly on journal lines.</span></span>  

<span data-ttu-id="fb268-223">Можно настроить измерения по умолчанию для счетов или типов счетов, чтобы измерения и значения измерений заполнялись автоматически.</span><span class="sxs-lookup"><span data-stu-id="fb268-223">You can set up default dimensions for accounts or account types, so that dimensions and dimension values are filled in automatically.</span></span>

## <a name="see-also"></a><span data-ttu-id="fb268-224">См. также</span><span class="sxs-lookup"><span data-stu-id="fb268-224">See Also</span></span>
[<span data-ttu-id="fb268-225">Бизнес-аналитика</span><span class="sxs-lookup"><span data-stu-id="fb268-225">Business Intelligence</span></span>](bi.md)  
[<span data-ttu-id="fb268-226">Финансы</span><span class="sxs-lookup"><span data-stu-id="fb268-226">Finance</span></span>](finance.md)  
[<span data-ttu-id="fb268-227">Практическое руководство. Анализ данных по измерениям</span><span class="sxs-lookup"><span data-stu-id="fb268-227">How to: Analyze Data by Dimensions</span></span>](bi-how-analyze-data-dimension.md)  
<span data-ttu-id="fb268-228">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="fb268-228">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
