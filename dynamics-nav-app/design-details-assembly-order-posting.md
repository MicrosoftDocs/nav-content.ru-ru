---
title: "Сведения о проектировании — учет заказа на сборку"
description: "Учет заказа на сборку основан на тех же принципах, что и учет похожих операций заказов на продажу и потребления/выход производства. Однако эти принципы объединены в заказах на сборку, которые имеют собственный пользовательский интерфейс учета, как в заказах на продажу, в то время как фактический учет операций осуществляется в фоновом режиме в виде прямого учета журнала товаров и ресурсов, как для производственного потребления, выхода и производственной мощности."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: ed71853b5a35dde157f7f90d6ddfc11afa663497
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-assembly-order-posting"></a><span data-ttu-id="1ded2-104">Сведения о проектировании: учет заказа на сборку</span><span class="sxs-lookup"><span data-stu-id="1ded2-104">Design Details: Assembly Order Posting</span></span>
<span data-ttu-id="1ded2-105">Учет заказа на сборку основан на тех же принципах, что и учет похожих операций заказов на продажу и потребления/выход производства.</span><span class="sxs-lookup"><span data-stu-id="1ded2-105">Assembly order posting is based on the same principles as when posting the similar activities of sales orders and production consumption/output.</span></span> <span data-ttu-id="1ded2-106">Однако эти принципы объединены в заказах на сборку, которые имеют собственный пользовательский интерфейс учета, как в заказах на продажу, в то время как фактический учет операций осуществляется в фоновом режиме в виде прямого учета журнала товаров и ресурсов, как для производственного потребления, выхода и производственной мощности.</span><span class="sxs-lookup"><span data-stu-id="1ded2-106">However, the principles are combined in that assembly orders have their own posting UI, like that for sales orders, while the actual entry posting happens in the background as direct item and resource journal postings, like that for production consumption, output, and capacity.</span></span>  

<span data-ttu-id="1ded2-107">Аналогично учету производственного заказа использованные компоненты и использованные ресурсы преобразуются и выпускаются как сборочный элемент при учете заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-107">Similarly to production order posting, the consumed components and the used resources are converted and output as the assembly item when the assembly order is posted.</span></span> <span data-ttu-id="1ded2-108">Дополнительные сведения см. в разделе [Сведения о проектировании: учет производственного заказа](design-details-production-order-posting.md).</span><span class="sxs-lookup"><span data-stu-id="1ded2-108">For more information, see [Design Details: Production Order Posting](design-details-production-order-posting.md).</span></span> <span data-ttu-id="1ded2-109">Однако поток затрат для заказов на сборку менее сложен, в частности из-за того, что учет себестоимости сборки выполняется только один раз и поэтому не создает запасы НЗП.</span><span class="sxs-lookup"><span data-stu-id="1ded2-109">However, the cost flow for assembly orders is less complex, especially because assembly cost posting only occurs once and therefore does not generate work-in-process inventory.</span></span>  

<span data-ttu-id="1ded2-110">Следующие проводки журнала имеют место при учете заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-110">The following journal postings occur during assembly order posting:</span></span>  

-   <span data-ttu-id="1ded2-111">Журнал товаров учитывает положительные операции книги товаров, представляя выпуск сборочных элементов из заголовка заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-111">The item journal posts positive item ledger entries, representing output of the assembly item, from the assembly order header</span></span>  
-   <span data-ttu-id="1ded2-112">Журнал товаров учитывает отрицательные операции книги товаров, представляя потребление компонентов сборки из строк заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-112">The item journal posts negative item ledger entries, representing consumption of assembly components, from the assembly order lines.</span></span>  
-   <span data-ttu-id="1ded2-113">Журнал ресурсов учитывает использование ресурсов сборки (временных единиц) из строк заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-113">The resource journal posts usage of assembly resources (time units), from the assembly order lines.</span></span>  
-   <span data-ttu-id="1ded2-114">В журнале производственных мощностей учитываются операции стоимости, связанные с использованием ресурсов, из строк сборочного заказа.</span><span class="sxs-lookup"><span data-stu-id="1ded2-114">The capacity journal posts value entries relating to the resource usage, from the assembly order lines.</span></span>  

<span data-ttu-id="1ded2-115">На следующей схеме показана структура операций журнала товаров и ресурсов, результатом которых является учет заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-115">The following diagram shows the structure of item and resource ledger entries that result from assembly order posting.</span></span>  

<span data-ttu-id="1ded2-116">![Затраты на ресурсы и мощности](media/design_details_assembly_posting_1.png "design_details_assembly_posting_1")</span><span class="sxs-lookup"><span data-stu-id="1ded2-116">![Resource and capacity costs](media/design_details_assembly_posting_1.png "design_details_assembly_posting_1")</span></span>  

> [!NOTE]  
>  <span data-ttu-id="1ded2-117">Машинные и рабочие центры включены для указания того, что операции книги операций производственных мощностей можно создать из производства и сборки.</span><span class="sxs-lookup"><span data-stu-id="1ded2-117">Machine and work centers are included to illustrate that capacity ledger entries are created from both production and assembly.</span></span>  

<span data-ttu-id="1ded2-118">На следующей схеме показано, как данные сборки попадают в операции ГК во время учета.</span><span class="sxs-lookup"><span data-stu-id="1ded2-118">The following diagram shows how assembly data flows into ledger entries during posting:</span></span>  

<span data-ttu-id="1ded2-119">![Поток данных во время учета](media/design_details_assembly_posting_2.png "design_details_assembly_posting_2")</span><span class="sxs-lookup"><span data-stu-id="1ded2-119">![Data flow during posting](media/design_details_assembly_posting_2.png "design_details_assembly_posting_2")</span></span>  

## <a name="posting-sequence"></a><span data-ttu-id="1ded2-120">Порядок учета</span><span class="sxs-lookup"><span data-stu-id="1ded2-120">Posting Sequence</span></span>  
<span data-ttu-id="1ded2-121">Учет заказа на сборку осуществляется в следующем порядке.</span><span class="sxs-lookup"><span data-stu-id="1ded2-121">The posting of an assembly order occurs in the following order:</span></span>  

1.  <span data-ttu-id="1ded2-122">Учитываются строки заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-122">The assembly order lines are posted.</span></span>  
2.  <span data-ttu-id="1ded2-123">Учитывается заголовок заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-123">The assembly order header is posted.</span></span>  

<span data-ttu-id="1ded2-124">В следующей таблице показана последовательность действий.</span><span class="sxs-lookup"><span data-stu-id="1ded2-124">The following table outlines the sequence of actions.</span></span>  

|<span data-ttu-id="1ded2-125">Действие</span><span class="sxs-lookup"><span data-stu-id="1ded2-125">Action</span></span>|<span data-ttu-id="1ded2-126">Описанием</span><span class="sxs-lookup"><span data-stu-id="1ded2-126">Description</span></span>|  
|------------|-----------------|  
|<span data-ttu-id="1ded2-127">Инициализация учета</span><span class="sxs-lookup"><span data-stu-id="1ded2-127">Initialize Posting</span></span>|<span data-ttu-id="1ded2-128">1.  Выполните предварительные проверки.</span><span class="sxs-lookup"><span data-stu-id="1ded2-128">1.  Make preliminary checks.</span></span><br /><span data-ttu-id="1ded2-129">2.  Добавьте учетный номер и измените заголовок заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-129">2.  Add posting number and modify the assembly order header.</span></span><br /><span data-ttu-id="1ded2-130">3.  Выпустите заказ на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-130">3.  Release the assembly order.</span></span>|  
|<span data-ttu-id="1ded2-131">Почта</span><span class="sxs-lookup"><span data-stu-id="1ded2-131">Post</span></span>|<ol><li><span data-ttu-id="1ded2-132">Создайте заголовок учтенного сборочного заказа.</span><span class="sxs-lookup"><span data-stu-id="1ded2-132">Create the posted assembly order header.</span></span></li><li><span data-ttu-id="1ded2-133">Скопируйте строки комментария.</span><span class="sxs-lookup"><span data-stu-id="1ded2-133">Copy comment lines.</span></span></li><li><span data-ttu-id="1ded2-134">Выполните учет строк заказа на сборку (потребление):</span><span class="sxs-lookup"><span data-stu-id="1ded2-134">Post assembly order lines (consumption):</span></span><br /><br /> <ol><li><span data-ttu-id="1ded2-135">Создайте окно статуса для расчета потребления при сборке.</span><span class="sxs-lookup"><span data-stu-id="1ded2-135">Create a status window to calculate assembly consumption.</span></span></li><li><span data-ttu-id="1ded2-136">Получите остаток, на котором будет основываться строка журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-136">Get the remaining quantity on which the item journal line will be based.</span></span></li><li><span data-ttu-id="1ded2-137">Сбросьте использованное количество и остаток.</span><span class="sxs-lookup"><span data-stu-id="1ded2-137">Reset the consumed and remaining quantities.</span></span></li><li><span data-ttu-id="1ded2-138">Для строк заказа на сборку типа "Товар":</span><span class="sxs-lookup"><span data-stu-id="1ded2-138">For assembly order lines of type Item:</span></span><br /><br /> <ol><li><span data-ttu-id="1ded2-139">Заполните поля в строке журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-139">Populate fields on the item journal line.</span></span></li><li><span data-ttu-id="1ded2-140">Резервирования перемещения в строку журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-140">Transfer reservations to the item journal line.</span></span></li><li><span data-ttu-id="1ded2-141">Выполните учет строки журнала товаров для создания операций книги товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-141">Post the item journal line to create the item ledger entries.</span></span></li><li><span data-ttu-id="1ded2-142">Создайте строки складского журнала и учтите их.</span><span class="sxs-lookup"><span data-stu-id="1ded2-142">Create warehouse journal lines and post them.</span></span></li></ol></li><li><span data-ttu-id="1ded2-143">Для строк заказа на сборку типа "Ресурс":</span><span class="sxs-lookup"><span data-stu-id="1ded2-143">For assembly order lines of type Resource:</span></span><br /><br /> <ol><li><span data-ttu-id="1ded2-144">Заполните поля в строке журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-144">Populate fields on the item journal line.</span></span></li><li><span data-ttu-id="1ded2-145">Выполните учет строки журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-145">Post the item journal line.</span></span> <span data-ttu-id="1ded2-146">В результате создаются операции журнала производственных мощностей.</span><span class="sxs-lookup"><span data-stu-id="1ded2-146">This creates capacity ledger entries.</span></span></li><li><span data-ttu-id="1ded2-147">Создайте и учтите строку журнала ресурсов.</span><span class="sxs-lookup"><span data-stu-id="1ded2-147">Create and post resource journal line.</span></span></li></ol></li><li><span data-ttu-id="1ded2-148">перенос значений поля из строки заказа на сборку в только что созданную строку учтенного заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-148">Transfer field values from the assembly order line into a newly created posted assembly order line.</span></span></li></ol></li><li><span data-ttu-id="1ded2-149">Выполните учет заголовка заказа на сборку (выход):</span><span class="sxs-lookup"><span data-stu-id="1ded2-149">Post the assembly order header (output):</span></span><br /><br /> <ol><li><span data-ttu-id="1ded2-150">Заполните поля в строке журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-150">Populate fields on the item journal line.</span></span></li><li><span data-ttu-id="1ded2-151">Резервирования перемещения в строку журнала товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-151">Transfer reservations to the item journal line.</span></span></li><li><span data-ttu-id="1ded2-152">Выполните учет строки журнала товаров для создания операций книги товаров.</span><span class="sxs-lookup"><span data-stu-id="1ded2-152">Post the item journal line to create the item ledger entries.</span></span></li><li><span data-ttu-id="1ded2-153">Создайте строки складского журнала и учтите их.</span><span class="sxs-lookup"><span data-stu-id="1ded2-153">Create warehouse journal lines and post them.</span></span></li><li><span data-ttu-id="1ded2-154">Сбросьте количества сборки и остаток.</span><span class="sxs-lookup"><span data-stu-id="1ded2-154">Reset the assembly quantities and remaining quantities.</span></span></li></ol></li></ol>|  

> [!IMPORTANT]  
>  <span data-ttu-id="1ded2-155">В отличие от производственного выпуска, который учитывается по ожидаемой себестоимости, выпуск сборки учитывается по фактической себестоимости.</span><span class="sxs-lookup"><span data-stu-id="1ded2-155">Unlike for production output, which is posted at expected cost, assembly output is posted at actual cost.</span></span>  

## <a name="cost-adjustment"></a><span data-ttu-id="1ded2-156">Коррекция себестоимости</span><span class="sxs-lookup"><span data-stu-id="1ded2-156">Cost Adjustment</span></span>  
 <span data-ttu-id="1ded2-157">После учета заказа на сборку, то есть после сборки компонентов (материала) и ресурсов в новый товар, можно определить фактическую себестоимость сборочного элемента и фактическую себестоимость запасов использованных компонентов.</span><span class="sxs-lookup"><span data-stu-id="1ded2-157">Once an assembly order is posted, meaning that components (material) and resources are assembled into a new item, then it should be possible to determine the actual cost of that assembly item, and the actual inventory cost of the components involved.</span></span> <span data-ttu-id="1ded2-158">Это достигается пересылкой себестоимости из учтенных операций источника (компоненты и ресурсы) в учтенные операции назначения (сборочный элемент).</span><span class="sxs-lookup"><span data-stu-id="1ded2-158">This is achieved by forwarding costs from the posted entries of the source (the components and resources) to the posted entries of the destination (the assembly item).</span></span> <span data-ttu-id="1ded2-159">Пересылка затрат осуществляется путем расчета и создания новых операций, называемых операциями корректировки, которые связываются с операциями распределения.</span><span class="sxs-lookup"><span data-stu-id="1ded2-159">The forwarding of costs is done by calculating and generating new entries, called adjustment entries that become associated with the destination entries.</span></span>  

 <span data-ttu-id="1ded2-160">Пересылаемые затраты на сборку обнаруживаются с помощью механизма обнаружения уровня заказа.</span><span class="sxs-lookup"><span data-stu-id="1ded2-160">The assembly costs to be forwarded are detected with the Order Level detection mechanism.</span></span> <span data-ttu-id="1ded2-161">Дополнительные сведения о других механизмах обнаружения коррекций см. в разделе [Сведения о проектировании: коррекция себестоимости](design-details-cost-adjustment.md).</span><span class="sxs-lookup"><span data-stu-id="1ded2-161">For information about other adjustment detection mechanisms, see [Design Details: Cost Adjustment](design-details-cost-adjustment.md).</span></span>  

### <a name="detecting-the-adjustment"></a><span data-ttu-id="1ded2-162">Обнаружение коррекции</span><span class="sxs-lookup"><span data-stu-id="1ded2-162">Detecting the Adjustment</span></span>  
<span data-ttu-id="1ded2-163">Функция обнаружения на уровне заказа используется в сценариях преобразования, производства и сборки.</span><span class="sxs-lookup"><span data-stu-id="1ded2-163">The order Level detection function is used in conversion scenarios, production and assembly.</span></span> <span data-ttu-id="1ded2-164">Функция работает следующим образом:</span><span class="sxs-lookup"><span data-stu-id="1ded2-164">The function works as follows:</span></span>  

-   <span data-ttu-id="1ded2-165">Коррекция себестоимости выявляется путем пометки заказа всякий раз при учете материала или ресурса как потребленного или использованного.</span><span class="sxs-lookup"><span data-stu-id="1ded2-165">Cost adjustment is detected by marking the order whenever a material/resource is posted as consumed/used.</span></span>  
-   <span data-ttu-id="1ded2-166">Перенаправление себестоимости производится путем применения себестоимости из материала или ресурса к операциям выхода, связанным с тем же заказом.</span><span class="sxs-lookup"><span data-stu-id="1ded2-166">Cost is forwarding by applying the costs from material/resource to the output entries associated with the same order.</span></span>  

<span data-ttu-id="1ded2-167">На следующем графике показана структура операции корректировки и корректировка затрат на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-167">The following graphic shows the adjustment entry structure and how assembly costs are adjusted.</span></span>  

<span data-ttu-id="1ded2-168">![Структура операции корректировки](media/design_details_assembly_posting_3.png "design_details_assembly_posting_3")</span><span class="sxs-lookup"><span data-stu-id="1ded2-168">![Adjustment entry structure](media/design_details_assembly_posting_3.png "design_details_assembly_posting_3")</span></span>  

### <a name="performing-the-adjustment"></a><span data-ttu-id="1ded2-169">Выполнение коррекции</span><span class="sxs-lookup"><span data-stu-id="1ded2-169">Performing the Adjustment</span></span>  
<span data-ttu-id="1ded2-170">Распространение обнаруженных корректировок из затрат на материалы и ресурсы в операции выпуска при сборке выполняется пакетным заданием **Коррекция себест. запасов**.</span><span class="sxs-lookup"><span data-stu-id="1ded2-170">The spreading of detected adjustments from material and resource costs onto the assembly output entries is performed by the **Adjust Cost – Item Entries** batch job.</span></span> <span data-ttu-id="1ded2-171">В нем предлагается функция многоуровневой коррекции, которая состоит из следующих двух элементов:</span><span class="sxs-lookup"><span data-stu-id="1ded2-171">It contains the Make Multilevel Adjustment function, which consists of the following two elements:</span></span>  

-   <span data-ttu-id="1ded2-172">Коррекция заказа на сборку — перемещение себестоимости из использования материала и ресурсов в операцию выхода при сборке.</span><span class="sxs-lookup"><span data-stu-id="1ded2-172">Make Assembly Order Adjustment – which forwards cost from material and resource usage to the assembly output entry.</span></span> <span data-ttu-id="1ded2-173">Строки 5 и 6 в алгоритме ниже отвечают за это действие.</span><span class="sxs-lookup"><span data-stu-id="1ded2-173">Lines 5 and 6 in the algorithm below are responsible for that.</span></span>  
-   <span data-ttu-id="1ded2-174">Одноуровневые коррекции — себестоимость перемещается для отдельных товаров с помощью метода учета себестоимости.</span><span class="sxs-lookup"><span data-stu-id="1ded2-174">Make Single Level Adjustments – which forwards costs for individual items using their costing method.</span></span> <span data-ttu-id="1ded2-175">Строки 9 и 10 в алгоритме ниже отвечают за это действие.</span><span class="sxs-lookup"><span data-stu-id="1ded2-175">Lines 9 and 10 in the algorithm below are responsible for that.</span></span>  

<span data-ttu-id="1ded2-176">![Алгоритм корректировки сборки](media/design_details_assembly_posting_4.jpg "design_details_assembly_posting_4")</span><span class="sxs-lookup"><span data-stu-id="1ded2-176">![Assembly adjustment algorithm](media/design_details_assembly_posting_4.jpg "design_details_assembly_posting_4")</span></span>  

> [!NOTE]  
>  <span data-ttu-id="1ded2-177">Элемент "Создание коррекций НЗП" в строках 7 и 8 отвечает за пересылку производственного материала и использования производственной мощности выходу незавершенных производственных заказов.</span><span class="sxs-lookup"><span data-stu-id="1ded2-177">The Make WIP Adjustments element, in lines 7 and 8, is responsible for forwarding production material and capacity usage to the output of unfinished production orders.</span></span> <span data-ttu-id="1ded2-178">Это не используется при корректировке себестоимости заказа на сборку, потому что концепция НЗП не применима к сборке.</span><span class="sxs-lookup"><span data-stu-id="1ded2-178">This is not used when adjusting assembly order costs as the concept of WIP does not apply to assembly.</span></span>  

<span data-ttu-id="1ded2-179">Дополнительные сведения о том, как выполнить учет себестоимостей из сборки и производства в главной книге, см. в разделе [Сведения о проектировании: учет запасов](design-details-inventory-posting.md).</span><span class="sxs-lookup"><span data-stu-id="1ded2-179">For information about how costs from assembly and production are posted to the general ledger, see [Design Details: Inventory Posting](design-details-inventory-posting.md).</span></span>  

## <a name="assembly-costs-are-always-actual"></a><span data-ttu-id="1ded2-180">Затраты на сборку всегда фактические</span><span class="sxs-lookup"><span data-stu-id="1ded2-180">Assembly Costs are Always Actual</span></span>  
 <span data-ttu-id="1ded2-181">Понятие незавершенного производства (WIP) не применимо в учете заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-181">The concept of work in process (WIP) does not apply in assembly order posting.</span></span> <span data-ttu-id="1ded2-182">Затраты на сборку учитываются как фактическая себестоимость, но не как ожидаемая себестоимость.</span><span class="sxs-lookup"><span data-stu-id="1ded2-182">Assembly costs are only posted as actual cost, never as expected cost.</span></span> <span data-ttu-id="1ded2-183">Дополнительные сведения см. в разделе [Сведения о проектировании: учет ожидаемой себестоимости](design-details-expected-cost-posting.md).</span><span class="sxs-lookup"><span data-stu-id="1ded2-183">For more information, see [Design Details: Expected Cost Posting](design-details-expected-cost-posting.md).</span></span>  

<span data-ttu-id="1ded2-184">Это возможно благодаря следующей структуре данных.</span><span class="sxs-lookup"><span data-stu-id="1ded2-184">This is enabled by the following data structure.</span></span>  

-   <span data-ttu-id="1ded2-185">В поле **Тип** в строках журнала товаров в таблицах **Книга операций по произв. мощностям** и **Операция стоимости** параметр *Ресурс* используется для определения операций сборочных ресурсов.</span><span class="sxs-lookup"><span data-stu-id="1ded2-185">In the **Type** field on item journal lines, in the **Capacity Ledger Entry** and **Value Entry** tables, *Resource* is used to identify assembly resource entries.</span></span>  
-   <span data-ttu-id="1ded2-186">В поле **Тип операции книги товаров** в строках журнала товаров в таблицах **Книга операций по произв. мощностям** и **Операция стоимости** параметры *Выход при сборке* и *Потребление при сборке* используются для определения операций сборочного элемента и операций использованных сборочных компонентов соответственно.</span><span class="sxs-lookup"><span data-stu-id="1ded2-186">In the **Item Ledger Entry Type** field on item journal lines, in the **Capacity Ledger Entry** and **Value Entry** tables, *Assembly Output* and *Assembly Consumption* are used to identify the output assembly item entries and the consumed assembly component entries respectively.</span></span>  

<span data-ttu-id="1ded2-187">Кроме того, поля учетной группы в заголовке заказа на сборку и строки заказа на сборку заполняются по умолчанию следующим образом.</span><span class="sxs-lookup"><span data-stu-id="1ded2-187">In addition, posting group fields on the assembly order header and assembly order lines are populated by default as follows.</span></span>  

|<span data-ttu-id="1ded2-188">Объект</span><span class="sxs-lookup"><span data-stu-id="1ded2-188">Entity</span></span>|<span data-ttu-id="1ded2-189">Тип</span><span class="sxs-lookup"><span data-stu-id="1ded2-189">Type</span></span>|<span data-ttu-id="1ded2-190">Учетная группа</span><span class="sxs-lookup"><span data-stu-id="1ded2-190">Posting Group</span></span>|<span data-ttu-id="1ded2-191">Общая товарная группа</span><span class="sxs-lookup"><span data-stu-id="1ded2-191">Gen. Prod. Posting Group</span></span>|  
|------------|----------|-------------------|------------------------------|  
|<span data-ttu-id="1ded2-192">Заголовок заказа на сборку</span><span class="sxs-lookup"><span data-stu-id="1ded2-192">Assembly Order Header</span></span>|<span data-ttu-id="1ded2-193">Товар</span><span class="sxs-lookup"><span data-stu-id="1ded2-193">Item</span></span>|<span data-ttu-id="1ded2-194">Учетная группа товаров</span><span class="sxs-lookup"><span data-stu-id="1ded2-194">Inventory Posting Group</span></span>|<span data-ttu-id="1ded2-195">Общая товарная группа</span><span class="sxs-lookup"><span data-stu-id="1ded2-195">Gen. Prod. Posting Group</span></span>|  
|<span data-ttu-id="1ded2-196">Строка заказа на сборку</span><span class="sxs-lookup"><span data-stu-id="1ded2-196">Assembly Order Line</span></span>|<span data-ttu-id="1ded2-197">Товар</span><span class="sxs-lookup"><span data-stu-id="1ded2-197">Item</span></span>|<span data-ttu-id="1ded2-198">Учетная группа товаров</span><span class="sxs-lookup"><span data-stu-id="1ded2-198">Inventory Posting Group</span></span>|<span data-ttu-id="1ded2-199">Общая товарная группа</span><span class="sxs-lookup"><span data-stu-id="1ded2-199">Gen. Prod. Posting Group</span></span>|  
|<span data-ttu-id="1ded2-200">Строка заказа на сборку</span><span class="sxs-lookup"><span data-stu-id="1ded2-200">Assembly Order Line</span></span>|<span data-ttu-id="1ded2-201">Ресурс</span><span class="sxs-lookup"><span data-stu-id="1ded2-201">Resource</span></span>||<span data-ttu-id="1ded2-202">Общая товарная группа</span><span class="sxs-lookup"><span data-stu-id="1ded2-202">Gen. Prod. Posting Group</span></span>|  

<span data-ttu-id="1ded2-203">Соответственно, только фактические затраты учитываются в главной книге, и промежуточные счета не заполняются сведениями учета заказа на сборку.</span><span class="sxs-lookup"><span data-stu-id="1ded2-203">Accordingly, only actual costs are posted to the general ledger, and no interim accounts are populated from assembly order posting.</span></span> <span data-ttu-id="1ded2-204">Дополнительные сведения см. в разделе [Сведения о проектировании: счета в главной книге](design-details-accounts-in-the-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="1ded2-204">For more information, see [Design Details: Accounts in the General Ledger](design-details-accounts-in-the-general-ledger.md)</span></span>  

## <a name="assemble-to-order"></a><span data-ttu-id="1ded2-205">Сборка для заказа</span><span class="sxs-lookup"><span data-stu-id="1ded2-205">Assemble to Order</span></span>  
<span data-ttu-id="1ded2-206">Операция товарной книги, полученная из учета продажи сборки на заказ, фиксируется применимо к соответствующей операции товарной книги для выхода сборки.</span><span class="sxs-lookup"><span data-stu-id="1ded2-206">The item ledger entry that results from posting an assemble-to-order sale is fixed applied to the related item ledger entry for the assembly output.</span></span> <span data-ttu-id="1ded2-207">Соответственно, себестоимость продажи сборки на заказ определяется на основе сборочного заказа, с которым она была связана.</span><span class="sxs-lookup"><span data-stu-id="1ded2-207">Accordingly, the cost of an assemble-to-order sale is derived from the assembly order that it was linked to.</span></span>  

<span data-ttu-id="1ded2-208">Операции книги товаров типа "Продажа", которые создаются в результате учета количеств сборки на заказ, отмечаются как **Да** в поле **Заказ на сборку**.</span><span class="sxs-lookup"><span data-stu-id="1ded2-208">Item ledger entries of type Sale that result from posting assemble-to-order quantities are marked with **Yes** in the **Assemble to Order** field.</span></span>  

<span data-ttu-id="1ded2-209">Учет строки заказа на продажу, в котором часть составляют товары в запасах, а другая часть приходится на сборку на заказ, создает отдельные учтенные операции книги товаров, одну для количества запасов и одну для количества сборки на заказ.</span><span class="sxs-lookup"><span data-stu-id="1ded2-209">Posting sales order lines where a part is inventory quantity and another part is assemble-to-order quantity results in separate item ledger entries, one for the inventory quantity and one for the assemble-to-order quantity.</span></span>  

## <a name="see-also"></a><span data-ttu-id="1ded2-210">См. также</span><span class="sxs-lookup"><span data-stu-id="1ded2-210">See Also</span></span>  
 <span data-ttu-id="1ded2-211">[Сведения о проектировании: себестоимость запасов](design-details-inventory-costing.md) </span><span class="sxs-lookup"><span data-stu-id="1ded2-211">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span></span>  
 <span data-ttu-id="1ded2-212">[Сведения о проектировании: учет производственного заказа](design-details-production-order-posting.md) </span><span class="sxs-lookup"><span data-stu-id="1ded2-212">[Design Details: Production Order Posting](design-details-production-order-posting.md) </span></span>  
 [<span data-ttu-id="1ded2-213">Сведения о проектировании: методы учета себестоимости</span><span class="sxs-lookup"><span data-stu-id="1ded2-213">Design Details: Costing Methods</span></span>](design-details-costing-methods.md)  
 [<span data-ttu-id="1ded2-214">Управление себестоимостью товаров</span><span class="sxs-lookup"><span data-stu-id="1ded2-214">Managing Inventory Costs</span></span>](finance-manage-inventory-costs.md)  
 [<span data-ttu-id="1ded2-215">Финансы</span><span class="sxs-lookup"><span data-stu-id="1ded2-215">Finance</span></span>](finance.md)  
 <span data-ttu-id="1ded2-216">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="1ded2-216">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
