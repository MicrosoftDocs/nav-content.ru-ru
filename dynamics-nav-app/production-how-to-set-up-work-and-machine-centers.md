---
title: "Как настраивать производственные и машинные центры"
description: "Карточка **Производственный центр** служит для организации фиксированных значений и требований определенного производственного ресурса и управления таким образом выходом продукции, производимой в данном рабочем центре."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/19/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fd257dc9a0b52160ccce7153505a4665552b26a7
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-work-centers-and-machine-centers"></a><span data-ttu-id="ecae1-103">Практическое руководство. Настройка производственных и машинных центров</span><span class="sxs-lookup"><span data-stu-id="ecae1-103">How to: Set Up Work Centers and Machine Centers</span></span>
<span data-ttu-id="ecae1-104">Программа различает три типа производственных мощностей.</span><span class="sxs-lookup"><span data-stu-id="ecae1-104">The program distinguishes between three types of capacities.</span></span> <span data-ttu-id="ecae1-105">Они организованы иерархически.</span><span class="sxs-lookup"><span data-stu-id="ecae1-105">These are arranged hierarchically.</span></span> <span data-ttu-id="ecae1-106">Каждый уровень содержит подчиненные уровни.</span><span class="sxs-lookup"><span data-stu-id="ecae1-106">Each level contains the subordinate levels.</span></span>  

<span data-ttu-id="ecae1-107">Верхний уровень является группой рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="ecae1-107">The top level is the work center group.</span></span> <span data-ttu-id="ecae1-108">Рабочие центры присваиваются группам рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="ecae1-108">Work centers are assigned to the work center groups.</span></span> <span data-ttu-id="ecae1-109">Каждый рабочий центр может принадлежать только одной группе рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="ecae1-109">Every work center can only belong to one work center group.</span></span>

<span data-ttu-id="ecae1-110">Можно назначить различные машинные центры каждому рабочему центру.</span><span class="sxs-lookup"><span data-stu-id="ecae1-110">You can assign various machine centers to every work center.</span></span> <span data-ttu-id="ecae1-111">Машинный центр может принадлежать только одному рабочему центру.</span><span class="sxs-lookup"><span data-stu-id="ecae1-111">A machine center may only belong to one work center.</span></span>  

<span data-ttu-id="ecae1-112">Планируемая производственная мощность производственного центра состоит из наличия соответствующих машинных центров и дополнительно запланированного наличия рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="ecae1-112">The planned capacity of a work center consists of the availability of the corresponding machine centers and the additional planned availability of the work center.</span></span> <span data-ttu-id="ecae1-113">Запланированное наличие группы рабочего центра, таким образом, является суммой всех соответствующих наличий машинных центров и рабочих центров.</span><span class="sxs-lookup"><span data-stu-id="ecae1-113">The planned availability of the work center group is, therefore, the sum of all corresponding availabilities of the machine centers and work centers.</span></span>  

<span data-ttu-id="ecae1-114">Наличие сохраняется в календаре операции.</span><span class="sxs-lookup"><span data-stu-id="ecae1-114">The availability is stored in calendar entries.</span></span> <span data-ttu-id="ecae1-115">Перед настройкой производственных или машинных центров необходимо сначала настроить производственные календари.</span><span class="sxs-lookup"><span data-stu-id="ecae1-115">Before you set up work or machine centers, you must set up shop calendars.</span></span> <span data-ttu-id="ecae1-116">Дополнительные сведения см. в разделе [Практическое руководство. Создание производственных календарей](production-how-to-create-work-center-calendars.md).</span><span class="sxs-lookup"><span data-stu-id="ecae1-116">For more information, see [How to: Create Shop Calendars](production-how-to-create-work-center-calendars.md).</span></span>  

## <a name="to-set-up-a-work-center"></a><span data-ttu-id="ecae1-117">Для настройки производственного центра</span><span class="sxs-lookup"><span data-stu-id="ecae1-117">To set up a work center</span></span>
<span data-ttu-id="ecae1-118">Ниже в первую очередь описано, как настроить производственный центр.</span><span class="sxs-lookup"><span data-stu-id="ecae1-118">The following primarily describes how to set up a work center.</span></span> <span data-ttu-id="ecae1-119">Шаги для настройки календаря машинного центра аналогичны, за исключением экспресс-вкладки **Настройка маршрута**.</span><span class="sxs-lookup"><span data-stu-id="ecae1-119">The steps to set up a machine center calendar are similar except for the **Routing Setup** FastTab.</span></span>  

1.  <span data-ttu-id="ecae1-120">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Производственные центры**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="ecae1-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Work Centers**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="ecae1-121">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="ecae1-121">Choose the **New** action.</span></span>  
3. <span data-ttu-id="ecae1-122">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="ecae1-122">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  <span data-ttu-id="ecae1-123">В поле **Рабочий центр — группы** выберите группировку ресурсов на высоком уровне, согласно которой организован рабочий центр, если требуется.</span><span class="sxs-lookup"><span data-stu-id="ecae1-123">In the **Work Center Group** field, select the higher-level resource grouping that the work center is organized under, if relevant.</span></span> <span data-ttu-id="ecae1-124">Выберите действие **Создать** в раскрывающемся списке.</span><span class="sxs-lookup"><span data-stu-id="ecae1-124">Choose the **New** action in the drop-down list.</span></span>  
5.  <span data-ttu-id="ecae1-125">Выберите поле **Заблокировано**, если необходимо избежать использования рабочего центра в любой обработке.</span><span class="sxs-lookup"><span data-stu-id="ecae1-125">Select the **Blocked** field if you want to prevent the work center from being used in any processing.</span></span> <span data-ttu-id="ecae1-126">Это означает, что выход нельзя учитывать для товара, который произведен в рабочем центре.</span><span class="sxs-lookup"><span data-stu-id="ecae1-126">This means that output cannot be posted for an item that is produced at the work center.</span></span> <span data-ttu-id="ecae1-127">Дополнительные сведения см. в разделе [Практическое руководство. Учет выпуска продукции](production-how-to-post-output-quantity.md).</span><span class="sxs-lookup"><span data-stu-id="ecae1-127">For more information, see [How to: Post Production Output](production-how-to-post-output-quantity.md).</span></span>
6.  <span data-ttu-id="ecae1-128">В поле **Прямая себестоимость единицы** введите себестоимость производства создания одной единицы измерения в этом рабочем центре, исключая все остальные элементы затрат.</span><span class="sxs-lookup"><span data-stu-id="ecae1-128">In the **Direct Unit Cost** field, enter the cost of producing one unit of measure at this work center, excluding any other cost elements.</span></span> <span data-ttu-id="ecae1-129">Эту себестоимость часто называют *прямой стоимостью труда*.</span><span class="sxs-lookup"><span data-stu-id="ecae1-129">This cost is often referred to as the *direct labor rate*.</span></span>  
7.  <span data-ttu-id="ecae1-130">В поле **Косвенные затраты (%)** введите общую себестоимость операции в данном рабочем центре в виде процента от прямой себестоимости единицы.</span><span class="sxs-lookup"><span data-stu-id="ecae1-130">In the **Indirect Cost %** field, enter the general operation costs of using the work center as a percentage of the direct unit cost.</span></span> <span data-ttu-id="ecae1-131">Этот процент добавляется к прямой себестоимости при вычислении себестоимости единицы.</span><span class="sxs-lookup"><span data-stu-id="ecae1-131">This percentage amount is added to the direct cost in the calculation of the unit cost.</span></span>  
8.  <span data-ttu-id="ecae1-132">В поле **Норма накладных расходов** введите абсолютную величину всех не связанных с производством расходов по рабочему центру, например, расходов на обслуживание.</span><span class="sxs-lookup"><span data-stu-id="ecae1-132">In the **Overhead Rate** field, enter any non-operational costs, for example maintenance expenses, of the work center as an absolute amount.</span></span>  

    <span data-ttu-id="ecae1-133">Поле **Себестоимость единицы** содержит рассчитанную себестоимость создания одной единицы измерения на данном рабочем центре, включая все элементы себестоимости, как указано ниже:</span><span class="sxs-lookup"><span data-stu-id="ecae1-133">The **Unit Cost** field contains the calculated unit cost of producing one unit of measure at this work center, including all cost elements, as follows:</span></span>  

    <span data-ttu-id="ecae1-134">Себестоимость единицы = Прямая себестоимость единицы + (Прямая себестоимость единицы x Косвенные затраты (%)) + Норма накладных расходов.</span><span class="sxs-lookup"><span data-stu-id="ecae1-134">Unit Cost = Direct Unit Cost + (Direct Unit Cost x Indirect Cost %) + Overhead Rate.</span></span>  

9.  <span data-ttu-id="ecae1-135">В поле **Расчет себестоимости единицы** определите, на чем должен базироваться приведенный выше расчет: на сумме использованного времени (**Время**) или на количестве произведенных единиц (**Единицы**).</span><span class="sxs-lookup"><span data-stu-id="ecae1-135">In the **Unit Cost Calculation** field, define whether the above calculation should be based on the amount of time used:  **Time**, or on the number of produced units:  **Units**.</span></span>  
10.  <span data-ttu-id="ecae1-136">Выберите поле **Специальная себест. единицы**, чтобы себестоимость единицы рабочего центра определялась в строке маршрута, в которой он используется.</span><span class="sxs-lookup"><span data-stu-id="ecae1-136">Select the **Specific Unit Cost** field if you want to define the work center’s unit cost on the routing line where it is being used.</span></span> <span data-ttu-id="ecae1-137">Это может быть удобно для операций, у которых себестоимость производственных мощностей существенно отличается от соответствующего значения при обычном выполнении в данном рабочем центре.</span><span class="sxs-lookup"><span data-stu-id="ecae1-137">This may be relevant for operations with dramatically different capacity costs than what would normally be processed at that work center.</span></span>  
11.  <span data-ttu-id="ecae1-138">В поле **Метод списания** выберите способ вычисления и учета для учета выхода для данного рабочего центра: вручную или автоматически, используя один из следующих методов.</span><span class="sxs-lookup"><span data-stu-id="ecae1-138">In the **Flushing Method** field, select whether output posting at this work center should be calculated and posted manually or automatically, using either of the following methods.</span></span>  

    |<span data-ttu-id="ecae1-139">Параметр</span><span class="sxs-lookup"><span data-stu-id="ecae1-139">Option</span></span>|<span data-ttu-id="ecae1-140">Описанием</span><span class="sxs-lookup"><span data-stu-id="ecae1-140">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ecae1-141">**Ручной**</span><span class="sxs-lookup"><span data-stu-id="ecae1-141">**Manual**</span></span>|<span data-ttu-id="ecae1-142">Потребление учитывается вручную в журнале выхода продукции или производственном журнале.</span><span class="sxs-lookup"><span data-stu-id="ecae1-142">Concumption is posted manually in the output journal or production journal.</span></span>|
    |<span data-ttu-id="ecae1-143">**Прямое**</span><span class="sxs-lookup"><span data-stu-id="ecae1-143">**Forward**</span></span>|<span data-ttu-id="ecae1-144">Потребление рассчитывается и учитывается автоматически при запуске производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="ecae1-144">Consumption is calculated and posted automatically when the production order is released.</span></span>|  
    |<span data-ttu-id="ecae1-145">**Обратный**</span><span class="sxs-lookup"><span data-stu-id="ecae1-145">**Backward**</span></span>|<span data-ttu-id="ecae1-146">Потребление рассчитывается и учитывается автоматически при завершении производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="ecae1-146">Consumption is calculated and posted automatically when the production order is finished.</span></span>|  

    > [!NOTE]  
    >  <span data-ttu-id="ecae1-147">При необходимости, метод очистки, выбранный здесь и на карточке **Товар**, может быть переопределен для отдельных операций путем изменения настройки в строках маршрута.</span><span class="sxs-lookup"><span data-stu-id="ecae1-147">If necessary, the flushing method selected here and on the **Item** card, can be overridden for individual operations by changing the setting on routing lines.</span></span>

12.  <span data-ttu-id="ecae1-148">В поле **Код единицы измерения** введите единицу времени, с применением которой по данному рабочему центру выполнялись расчет себестоимости и планирование производственной мощности.</span><span class="sxs-lookup"><span data-stu-id="ecae1-148">In the **Unit of Measure Code** field, enter the time unit in which this work center’s cost calculation and capacity planning are made.</span></span>
    <span data-ttu-id="ecae1-149">Чтобы постоянно отслеживать потребление, сначала следует настроить метод измерения.</span><span class="sxs-lookup"><span data-stu-id="ecae1-149">In order to be able to constantly monitor consumption, you must first set up a method of measure.</span></span> <span data-ttu-id="ecae1-150">Вводимые вами единицы являются базовыми.</span><span class="sxs-lookup"><span data-stu-id="ecae1-150">The units you enter are basic units.</span></span> <span data-ttu-id="ecae1-151">Например, время обработки измеряется в часах и минутах.</span><span class="sxs-lookup"><span data-stu-id="ecae1-151">For example, the processing time is measured in hours and minutes.</span></span>

    > [!NOTE]  
    > <span data-ttu-id="ecae1-152">Если выбрана единица Дни, следует помнить, что 1 день = 24 часа, а не 8 (рабочих) часов.</span><span class="sxs-lookup"><span data-stu-id="ecae1-152">If you select to use Days then remember that 1 day = 24 hours - and not 8 (working hours).</span></span>

13.  <span data-ttu-id="ecae1-153">В поле **Произв. мощность** укажите, работает ли в рабочем центре одновременно несколько машин или несколько человек.</span><span class="sxs-lookup"><span data-stu-id="ecae1-153">In the **Capacity** field, define whether the work center has more than one machine or person working at the same time.</span></span> <span data-ttu-id="ecae1-154">Если в установленном экземпляре **Имя продукта** использование машинного центра не поддерживается, то значением этого поля должна быть **1**).</span><span class="sxs-lookup"><span data-stu-id="ecae1-154">If your **Product Name** installation does not include the Machine Center functionality, then the value in this field must be **1**).</span></span>  
14.  <span data-ttu-id="ecae1-155">В поле **Эффективность** введите процент ожидаемого стандартного выхода, который фактически обеспечивает этот рабочий центр.</span><span class="sxs-lookup"><span data-stu-id="ecae1-155">In the **Efficiency** field, enter the percentage of the expected standard output that this work center actually outputs.</span></span> <span data-ttu-id="ecae1-156">Значение **100** означает, что рабочий центр может обеспечить фактический выход, равный стандартному выходу.</span><span class="sxs-lookup"><span data-stu-id="ecae1-156">If you enter **100**, it means that the work center has an actual output that is the same as the standard output.</span></span>  
15. <span data-ttu-id="ecae1-157">Установите флажок **Консолидированный календарь**, если также используются машинные центры.</span><span class="sxs-lookup"><span data-stu-id="ecae1-157">Select the **Consolidated Calendar** check box if you are also using machine centers.</span></span> <span data-ttu-id="ecae1-158">Это гарантирует, что операции календаря сводятся из календарей машинных центров.</span><span class="sxs-lookup"><span data-stu-id="ecae1-158">This ensures that calendar entries are rolled up from machine center calendars.</span></span>  
16.  <span data-ttu-id="ecae1-159">В поле **Код произв. календаря** выберите производственный календарь.</span><span class="sxs-lookup"><span data-stu-id="ecae1-159">In the **Shop Calendar Code** field, select a shop calendar.</span></span> <span data-ttu-id="ecae1-160">Дополнительные сведения см. в разделе [Практическое руководство. Создание производственных календарей](production-how-to-create-work-center-calendars.md).</span><span class="sxs-lookup"><span data-stu-id="ecae1-160">For more information, see [How to: Create Shop Calendars](production-how-to-create-work-center-calendars.md).</span></span>  
17.  <span data-ttu-id="ecae1-161">В поле **Время очереди** укажите фиксированный промежуток времени, который должен пройти перед началом работы на данном рабочем центре.</span><span class="sxs-lookup"><span data-stu-id="ecae1-161">In the **Queue Time** field, specify a fixed time span that must pass before assigned work can begin at this work center.</span></span> <span data-ttu-id="ecae1-162">Следует отметить, что время очереди добавляется к другим непроизводственным элементам времени, таким как время ожидания и время перемещения, которые можно задать в строках маршрута с помощью этого рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="ecae1-162">Note that queue time is added to other non-productive time elements such as wait time and move time that you may define on routing lines using this work center.</span></span>  

## <a name="example---different-machine-centers-assigned-to-a-work-center"></a><span data-ttu-id="ecae1-163">Пример. Различные машинные центры, назначенные производственному центру</span><span class="sxs-lookup"><span data-stu-id="ecae1-163">Example - Different Machine Centers Assigned to a Work Center</span></span>
<span data-ttu-id="ecae1-164">Важно планировать, какие производственные мощности должны составить общую производственную мощность при настройке машинных центров и рабочих центров.</span><span class="sxs-lookup"><span data-stu-id="ecae1-164">It is important to plan which capacities are to make up the total capacity when setting up the machine centers and work centers.</span></span>

<span data-ttu-id="ecae1-165">Если различные машинные центры (такие как 210 «Упаковочный стол 1», 310 «Окрасочная кабина» ...) присвоены машинному центру, важно осуществлять анализ одиночных производственных мощностей машинных центров, так как отказ одного машинного центра может прервать весь процесс обработки.</span><span class="sxs-lookup"><span data-stu-id="ecae1-165">If different machine centers (such as 210 Packing table 1, 310 Painting Cabin ...) are assigned to a work center, the consideration of the single capacities of the machine centers is significant because failure of one machine center can interrupt the entire process.</span></span> <span data-ttu-id="ecae1-166">Машинные группы можно ввести в соответствии с их производственной мощностью, но их можно не включать в планирование.</span><span class="sxs-lookup"><span data-stu-id="ecae1-166">The machine groups can be entered according to their capacity but may not be included in the planning.</span></span> <span data-ttu-id="ecae1-167">Если отключить поле **Консолидированный календарь**, при планировании будет назначаться только производственная мощность рабочего центра, но не машинного центра.</span><span class="sxs-lookup"><span data-stu-id="ecae1-167">By deactivating the **Consolidated Calendar** field only the capacity of the work center but not the machine center is assigned in the planning.</span></span>

<span data-ttu-id="ecae1-168">Однако, если одинаковые машинные центры (например, 210 «Упаковочный стол 1» и 220 «Упаковочный стол 2») объединены в рабочий центр, представляет интерес анализ рабочего центра как суммы присвоенных машинных центров.</span><span class="sxs-lookup"><span data-stu-id="ecae1-168">If, however, identical machine centers (such as 210 Packing table 1 and 220 Packing table 2) are combined in a work center, the consideration of the work center as a sum of the assigned machine centers is of interest.</span></span> <span data-ttu-id="ecae1-169">Следовательно, рабочий центр будет указан с нулевой производственной мощностью.</span><span class="sxs-lookup"><span data-stu-id="ecae1-169">Therefore, the work center would be listed with zero capacity.</span></span> <span data-ttu-id="ecae1-170">При активации поля **Консолидированный календарь** производственному центру присваивается общая производственная мощность.</span><span class="sxs-lookup"><span data-stu-id="ecae1-170">By activating the **Consolidated Calendar** field, the common capacity is assigned to the work center.</span></span>

<span data-ttu-id="ecae1-171">Если производственные мощности рабочих центров не должны составлять общую производственную мощность, это можно получить, задав эффективность = 0.</span><span class="sxs-lookup"><span data-stu-id="ecae1-171">If capacities of work centers are to make no contribution to the total capacity, you can achieve this with efficiency = 0.</span></span>

## <a name="to-set-up-a-capacity-constrained-machine-or-work-center"></a><span data-ttu-id="ecae1-172">Настройка машинного или рабочего центра с ограниченной производственной мощностью</span><span class="sxs-lookup"><span data-stu-id="ecae1-172">To set up a capacity constrained machine or work center</span></span>
<span data-ttu-id="ecae1-173">Необходимо настроить производственные ресурсы, которые считаются критическими, а также маркировать их для принятия ограниченной нагрузки вместо неограниченной нагрузки по умолчанию, которую принимают другие производственные ресурсы.</span><span class="sxs-lookup"><span data-stu-id="ecae1-173">You must set up production resources that you regard as critical and mark them to accept a finite load instead of the default infinite load that other production resources accept.</span></span> <span data-ttu-id="ecae1-174">Ресурс с ограниченной производственной мощностью может быть рабочим или машинным центром, определяемым как "узкое место", и для которого должна устанавливаться ограниченная (конечная) нагрузка.</span><span class="sxs-lookup"><span data-stu-id="ecae1-174">A capacity-constrained resource can be a work center or machine center that you have identified as a bottleneck and would like to establish a limited, finite load for.</span></span>

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="ecae1-175"> не поддерживается подробное управление сборочным цехом.</span><span class="sxs-lookup"><span data-stu-id="ecae1-175"> does not support detailed shop floor control.</span></span> <span data-ttu-id="ecae1-176">Она планирует возможное использование ресурсов, предоставляя приблизительный график, но не создает и не поддерживает подробные графики автоматически на основе приоритетов или правил оптимизации.</span><span class="sxs-lookup"><span data-stu-id="ecae1-176">It plans for a feasible utilization of resources by providing a rough-cut schedule, but it does not automatically create and maintain detailed schedules based on priorities or optimization rules.</span></span>

<span data-ttu-id="ecae1-177">В окне **Ограничения ресурсов произв. мощности** можно выполнять настройку, которая позволяет избежать перегрузки конкретных ресурсов и обеспечить распределение всех производственных ресурсов, если это позволило бы ускорить время выполнения производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="ecae1-177">In the **Capacity-Constrained Resources** window, you can make setup that avoids overload of specific resources and ensure that no capacity is left unallocated if it could increase the turn-around time of a production order.</span></span> <span data-ttu-id="ecae1-178">В поле **Демпфер (% от общей произв. мощности)** можно добавить к ресурсам буферный период для сведения к минимуму разделения операций.</span><span class="sxs-lookup"><span data-stu-id="ecae1-178">In the **Dampener (% of Total Capacity)** field, you can add dampener time to resources to minimize operation splitting.</span></span> <span data-ttu-id="ecae1-179">Это позволяет системе планировать загрузку на последний возможный день с небольшим превышением процента критической нагрузки, если при этом число разделяемых операций будет уменьшено.</span><span class="sxs-lookup"><span data-stu-id="ecae1-179">This enables the system to schedule load on the last possible day by exceeding the critical load percent slightly if this can reduce the number of operations that are split.</span></span>

<span data-ttu-id="ecae1-180">При планировании с ограниченными по мощности ресурсами система гарантирует, что ни один ресурс не загружается с превышением определенной производственной мощности (критическая загрузка).</span><span class="sxs-lookup"><span data-stu-id="ecae1-180">When planning with capacity-constrained resources, the system ensures that no resource is loaded above its defined capacity (critical load).</span></span> <span data-ttu-id="ecae1-181">Это выполняется путем назначения каждой операции ближайшему доступному временному интервалу.</span><span class="sxs-lookup"><span data-stu-id="ecae1-181">This is done by assigning each operation to the nearest available time slot.</span></span> <span data-ttu-id="ecae1-182">Если временной интервал недостаточно продолжительный для завершения всей операции, операция будет разделена на две или более частей, помещенных в ближайшие доступные временные интервалы.</span><span class="sxs-lookup"><span data-stu-id="ecae1-182">If the time slot is not big enough to complete the entire operation, then the operation will be split into two or more parts placed in the nearest available time slots.</span></span>

1. <span data-ttu-id="ecae1-183">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Ограничения ресурсов произв. мощности**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="ecae1-183">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Capacity Constrined Resources**, and then choose the related link.</span></span>
2. <span data-ttu-id="ecae1-184">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="ecae1-184">Choose the **New** action.</span></span>
3. <span data-ttu-id="ecae1-185">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="ecae1-185">Fill in the fields as necessary.</span></span>

> [!NOTE]
> <span data-ttu-id="ecae1-186">Операции в машинных центрах или машинные центры, настроенные как ограниченные ресурсы, всегда будут планироваться серийно.</span><span class="sxs-lookup"><span data-stu-id="ecae1-186">Operations on work centers or machine centers that are set up as constrained resources will always be planned serially.</span></span> <span data-ttu-id="ecae1-187">Это означает, что даже если в ограниченном рабочем центре есть несколько производственных мощностей, то эти производственные мощности могут быть запланированы только последовательно, а не параллельно, как было бы в ситуации, если бы рабочий или машинный центр не был настроен как ограниченный ресурс.</span><span class="sxs-lookup"><span data-stu-id="ecae1-187">This means that if a constrained resource has multiple capacities, then those capacities can only be planned in sequence, not in parallel as they would be if the work or machine center was not set up as a constrained resource.</span></span> <span data-ttu-id="ecae1-188">В таблице "Ограниченный ресурс" значение поля Мощность в рабочем центре или машинном центре больше 1.</span><span class="sxs-lookup"><span data-stu-id="ecae1-188">In a constrained resource, the Capacity field on the work center or machine center is greater than 1.</span></span>

> <span data-ttu-id="ecae1-189">В случае разделения операций время настройки назначается только один раз, поскольку предполагается, что выполняются некоторые коррекции вручную для оптимизации графика.</span><span class="sxs-lookup"><span data-stu-id="ecae1-189">In case of operation splitting, the setup time is only assigned once because it is assumed that some manual adjustment is done to optimize the schedule.</span></span>

## <a name="see-also"></a><span data-ttu-id="ecae1-190">См. также</span><span class="sxs-lookup"><span data-stu-id="ecae1-190">See Also</span></span>  
[<span data-ttu-id="ecae1-191">Практическое руководство. Создание производственных календарей</span><span class="sxs-lookup"><span data-stu-id="ecae1-191">How to: Create Shop Calendars</span></span>](production-how-to-create-work-center-calendars.md)  
[<span data-ttu-id="ecae1-192">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="ecae1-192">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="ecae1-193">[Производство](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="ecae1-193">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="ecae1-194">[Планирование](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="ecae1-194">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="ecae1-195">Наличие</span><span class="sxs-lookup"><span data-stu-id="ecae1-195">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="ecae1-196">Покупки</span><span class="sxs-lookup"><span data-stu-id="ecae1-196">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="ecae1-197">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="ecae1-197">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
