---
title: "Как настраивать производственные календари"
description: "Календарь рабочего центра определяет рабочие дни и часы, смены, праздники и отсутствия, которые определяют общую производственную мощность рабочего центра во временных единицах согласно определенным для него значениям эффективности и мощности. Создание и применение календаря рабочего центра предполагает выполнение нескольких подготовительных задач."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 59131cdded4bf854aed02a7d835e8160342adb36
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-shop-calendars"></a><span data-ttu-id="f6807-104">Практическое руководство. Настройка производственных календарей</span><span class="sxs-lookup"><span data-stu-id="f6807-104">How to: Set Up Shop Calendars</span></span>
<span data-ttu-id="f6807-105">Календарь рабочего центра или машин определяет рабочие дни и часы, смены, праздники и простои, которые определяют общую производственную мощность (измеренную во временных единицах) рабочего центра согласно его определенным значениям эффективности и мощности.</span><span class="sxs-lookup"><span data-stu-id="f6807-105">A work center or machine calendar specifies the working days and hours, shifts, holidays, and absences that determine the center’s gross available capacity, measured in time, according to its defined efficiency and capacity values.</span></span>

<span data-ttu-id="f6807-106">В качестве основы для вычисления календаря рабочего или машинного центра сначала следует настроить один или больше общих производственных календарей.</span><span class="sxs-lookup"><span data-stu-id="f6807-106">As a foundation for calculating a specific work or machine center calendar, you must first set up one or more general shop calendars.</span></span> <span data-ttu-id="f6807-107">Производственный календарь определяет стандартную рабочую неделю в соответствии с временем начала и окончания каждого рабочего дня и рабочих смен.</span><span class="sxs-lookup"><span data-stu-id="f6807-107">A shop calendar defines a standard work week according to start and end times of each working day and the work shift relation.</span></span> <span data-ttu-id="f6807-108">Кроме того, производственный календарь определяет утвержденные праздники на весь год.</span><span class="sxs-lookup"><span data-stu-id="f6807-108">In addition, the shop calendar defines the fixed holidays during a year.</span></span>  

<span data-ttu-id="f6807-109">Ниже описано, как настроить календари рабочих центров.</span><span class="sxs-lookup"><span data-stu-id="f6807-109">The following describes how to set up work center calendars.</span></span> <span data-ttu-id="f6807-110">Действия при настройке календарей машинных центров аналогичны.</span><span class="sxs-lookup"><span data-stu-id="f6807-110">The steps are similar when setting up machine center calendars.</span></span>  

## <a name="to-create-work-shifts"></a><span data-ttu-id="f6807-111">Создание рабочих смен</span><span class="sxs-lookup"><span data-stu-id="f6807-111">To create work shifts</span></span>  
1.  <span data-ttu-id="f6807-112">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Рабочие смены**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f6807-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Work Shifts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f6807-113">В пустой строке в поле **Код** введите число, которое будет определять рабочую смену (например, **1**).</span><span class="sxs-lookup"><span data-stu-id="f6807-113">On a blank line, enter a number in the **Code** field to identify the work shift, for example, **1**.</span></span>  
3.  <span data-ttu-id="f6807-114">В поле **Описание** введите описание рабочей смены (например, **1-я смена**).</span><span class="sxs-lookup"><span data-stu-id="f6807-114">Describe the work shift in the **Description** field, for example, **1st shift**.</span></span>  
4.  <span data-ttu-id="f6807-115">При необходимости заполните строки для второй и третьей рабочих смен.</span><span class="sxs-lookup"><span data-stu-id="f6807-115">Optionally, fill in lines for a second or third work shift.</span></span>  

<span data-ttu-id="f6807-116">Даже если рабочие центры не работают в разных рабочих сменах, необходимо ввести хотя бы один код рабочей смены.</span><span class="sxs-lookup"><span data-stu-id="f6807-116">Even if your work centers do not work in different work shifts, enter at least one work shift code.</span></span>  

## <a name="to-set-up-a-shop-calendar"></a><span data-ttu-id="f6807-117">Настройка производственного календаря</span><span class="sxs-lookup"><span data-stu-id="f6807-117">To set up a shop calendar</span></span>  
1.  <span data-ttu-id="f6807-118">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Произв. календари**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f6807-118">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Shop Calendars**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f6807-119">В пустой строке в поле **Код** введите число, которое будет определять производственный календарь.</span><span class="sxs-lookup"><span data-stu-id="f6807-119">On a blank line, enter a number in the **Code** field to identify the shop calendar.</span></span>  
3.  <span data-ttu-id="f6807-120">Введите описание производственного календаря в поле **Описание**.</span><span class="sxs-lookup"><span data-stu-id="f6807-120">Describe the shop calendar in the **Description** field.</span></span>  
4.  <span data-ttu-id="f6807-121">Выберите действие **Рабочие дни**.</span><span class="sxs-lookup"><span data-stu-id="f6807-121">Choose the **Working Days** action.</span></span>
5.  <span data-ttu-id="f6807-122">В окне **Рабочие дни производственного календаря** определите полную рабочую неделю, вместе со временем начала и конца для каждого дня.</span><span class="sxs-lookup"><span data-stu-id="f6807-122">In the **Shop Calendar Working Days** window, define a complete work week, with the start and end times for each day.</span></span>  

    <span data-ttu-id="f6807-123">В поле **Код рабочей смены** выберите одну из смен, которые ранее были определены.</span><span class="sxs-lookup"><span data-stu-id="f6807-123">In the **Work Shift Code** field, select one of the shifts that you previously defined.</span></span> <span data-ttu-id="f6807-124">Добавьте строку для каждого рабочего дня и смены.</span><span class="sxs-lookup"><span data-stu-id="f6807-124">Add a line for every working day and every shift.</span></span> <span data-ttu-id="f6807-125">Например:</span><span class="sxs-lookup"><span data-stu-id="f6807-125">For example:</span></span>  

    <span data-ttu-id="f6807-126">Понедельник 07:00 15:00 1</span><span class="sxs-lookup"><span data-stu-id="f6807-126">Monday  07:00 15:00 1</span></span>   
    <span data-ttu-id="f6807-127">Вторник 07:00 15:00 1</span><span class="sxs-lookup"><span data-stu-id="f6807-127">Tuesday 07:00 15:00 1</span></span>  

    <span data-ttu-id="f6807-128">Если нужно создать производственный календарь с двумя рабочими сменами, следует заполнить его следующим образом:</span><span class="sxs-lookup"><span data-stu-id="f6807-128">If you need a shop calendar with two work shifts, you must fill it in in this manner:</span></span>  

    <span data-ttu-id="f6807-129">Понедельник 07:00 15:00 1</span><span class="sxs-lookup"><span data-stu-id="f6807-129">Monday 07:00 15:00 1</span></span>   
    <span data-ttu-id="f6807-130">Понедельник 15:00 23:00 2</span><span class="sxs-lookup"><span data-stu-id="f6807-130">Monday 15:00 23:00 2</span></span>  
    <span data-ttu-id="f6807-131">Вторник 07:00 15:00 1</span><span class="sxs-lookup"><span data-stu-id="f6807-131">Tuesday 07:00 15:00 1</span></span>  
    <span data-ttu-id="f6807-132">Вторник 15:00 23:00 2</span><span class="sxs-lookup"><span data-stu-id="f6807-132">Tuesday 15:00 23:00 2</span></span>  

    <span data-ttu-id="f6807-133">Любые дни недели, не определяемые в производственном календаре, например суббота и воскресенье, рассматриваются как нерабочие дни. В календаре рабочего центра им будет соответствовать нулевое значение доступной производственной мощности.</span><span class="sxs-lookup"><span data-stu-id="f6807-133">Any week days that you do not define in the shop calendar, such as Saturday and Sunday, are considered non-working days and will have zero available capacity in a work center calendar.</span></span>  

    <span data-ttu-id="f6807-134">По завершении определения всех рабочих дней недели можно закрыть окно **Произв. календарь - рабочие дни** и перейти к вводу праздников.</span><span class="sxs-lookup"><span data-stu-id="f6807-134">When all the working days of a week are defined, you can close the **Shop Calendar Working Days** window and proceed to enter holidays.</span></span>  

6.  <span data-ttu-id="f6807-135">В окне **Произв. календари** выберите производственный календарь, затем выберите действие **Праздники**.</span><span class="sxs-lookup"><span data-stu-id="f6807-135">In the **Shop Calendars** window, select the shop calendar, and then choose the **Holidays** action.</span></span>
7. <span data-ttu-id="f6807-136">В окне **Нерабочие дни произв. календаря** определите в отдельных строках праздничные дни на год, введя их дату, начальное и конечное время и описание каждого праздника.</span><span class="sxs-lookup"><span data-stu-id="f6807-136">In the **Shop Calendar Holidays** window, define the holidays of the year by entering the start date and time, the end time, and description of each holiday on individual lines.</span></span> <span data-ttu-id="f6807-137">Например:</span><span class="sxs-lookup"><span data-stu-id="f6807-137">For example:</span></span>  

    <span data-ttu-id="f6807-138">04.07.14 0:00:00 23:59:00 День Независимости</span><span class="sxs-lookup"><span data-stu-id="f6807-138">04/07/14 0:00:00 23:59:00 Summer Holiday</span></span>  
    <span data-ttu-id="f6807-139">05/07/14 0:00:00 23:59:00 День Независимости</span><span class="sxs-lookup"><span data-stu-id="f6807-139">05/07/14 0:00:00 23:59:00 Summer Holiday</span></span>  
    <span data-ttu-id="f6807-140">06.07.14 0:00:00 23:59:00 День Независимости</span><span class="sxs-lookup"><span data-stu-id="f6807-140">06/07/14 0:00:00 23:59:00 Summer Holiday</span></span>  

<span data-ttu-id="f6807-141">Определенным здесь праздникам в календаре рабочего центра будет соответствовать нулевое значение доступной производственной мощности.</span><span class="sxs-lookup"><span data-stu-id="f6807-141">The defined holidays will have zero available capacity in a work center calendar.</span></span>  

<span data-ttu-id="f6807-142">Теперь производственный календарь можно связать с рабочим центром, чтобы рассчитать цеховой производственный календарь, который будет использоваться для управления планом всех операций для данного рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="f6807-142">The shop calendar can now be assigned to a work center to calculate the work shop calendar that will govern all operation scheduling at that work center.</span></span>  

## <a name="to-calculate-a-work-center-calendar"></a><span data-ttu-id="f6807-143">Расчет календаря рабочего центра</span><span class="sxs-lookup"><span data-stu-id="f6807-143">To calculate a work center calendar</span></span>  

1.  <span data-ttu-id="f6807-144">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Производственные центры**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f6807-144">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Work Centers**, and then choose the related link.</span></span>
2. <span data-ttu-id="f6807-145">Откройте рабочий центр, который требуется обновить.</span><span class="sxs-lookup"><span data-stu-id="f6807-145">Open the work center that you want to update.</span></span>  
3. <span data-ttu-id="f6807-146">В поле **Код производственного календаря** выберите производственный календарь, который будет использоваться в качестве основы для календаря.</span><span class="sxs-lookup"><span data-stu-id="f6807-146">In the **Shop Calendar Code** field, select which shop calendar to use as the foundation for a work center calendar.</span></span>  
4. <span data-ttu-id="f6807-147">Выберите действие **Календарь**.</span><span class="sxs-lookup"><span data-stu-id="f6807-147">Choose the **Calendar** action.</span></span>  
5. <span data-ttu-id="f6807-148">В окне **Календарь производственного центра** выберите действие **Показать матрицу**.</span><span class="sxs-lookup"><span data-stu-id="f6807-148">In the **Work Center Calendar** window, choose the **Show Matrix** action.</span></span>  

    <span data-ttu-id="f6807-149">В левой части окна матрицы перечисляются настроенные рабочие центры.</span><span class="sxs-lookup"><span data-stu-id="f6807-149">The left side of the matrix window lists the work centers that are set up.</span></span> <span data-ttu-id="f6807-150">В правой части показан календарь со значениями доступной производственной мощности на каждый рабочий день в заданной единице измерения, например **480** минут.</span><span class="sxs-lookup"><span data-stu-id="f6807-150">The right side shows a calendar displaying the available capacity values for each working day in the defined unit of measure, for example, **480** minutes.</span></span> <span data-ttu-id="f6807-151">Каждая строка представляет календарь одного рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="f6807-151">Each line represents the calendar of one work center.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f6807-152">Также можно выбрать просмотр значения производственной мощности понедельно или помесячно, выбрав соответствующее значение в поле **Просмотр по** в окне **Календарь производственного центра**.</span><span class="sxs-lookup"><span data-stu-id="f6807-152">You can also select to view the capacity values for each week or month by changing the selection in the **View By** field in the **Work Center Calendar** window.</span></span>  

    <span data-ttu-id="f6807-153">Чтобы отразить новый производственный календарь в качестве строки в выбранном рабочем центре, его необходимо сначала рассчитать.</span><span class="sxs-lookup"><span data-stu-id="f6807-153">To reflect the new shop calendar as a line on the selected work center, it must first be calculated.</span></span>  

6.  <span data-ttu-id="f6807-154">Выберите действие **Рассчитать**.</span><span class="sxs-lookup"><span data-stu-id="f6807-154">Choose the **Calculate** action.</span></span>  
7.  <span data-ttu-id="f6807-155">На экспресс-вкладке **Рабочий центр** можно настроить фильтр, чтобы вычисления выполнялись только для одного рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="f6807-155">On the **Work Center** FastTab, you can set a filter to only calculate for one work center.</span></span> <span data-ttu-id="f6807-156">Если фильтр не задан, будут рассчитаны все существующие календари рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="f6807-156">If you do not set a filter, all existing work center calendars will be calculated.</span></span>  
8.  <span data-ttu-id="f6807-157">Определите дату начала и окончания календарного периода, который должен быть рассчитан, например, с 01.01.04 по 31.12.04 для периода в один год.</span><span class="sxs-lookup"><span data-stu-id="f6807-157">Define the starting and ending dates of the calendar period that should be calculated, for example, one year from 01/01/14 to 31/12/14.</span></span>
9. <span data-ttu-id="f6807-158">Выберите кнопку **ОК** для расчета производственной мощности.</span><span class="sxs-lookup"><span data-stu-id="f6807-158">Choose the **OK** button to calculate capacity.</span></span>  

<span data-ttu-id="f6807-159">Теперь созданы (или обновлены) записи календаря, показывающие доступную производственную мощность на каждый из периодов в соответствии со следующими тремя наборами основных данных:</span><span class="sxs-lookup"><span data-stu-id="f6807-159">Calendar entries are now created or updated displaying the available capacity for each period according to the following three sets of master data:</span></span>  

- <span data-ttu-id="f6807-160">Рабочие дни и смены, определенные в назначенном производственном календаре.</span><span class="sxs-lookup"><span data-stu-id="f6807-160">The working days and shift defined in the assigned shop calendar.</span></span>  
- <span data-ttu-id="f6807-161">Значение поля **Произв. мощность** карточки рабочего центра.</span><span class="sxs-lookup"><span data-stu-id="f6807-161">The value in the **Capacity** field on the work center card.</span></span>  
- <span data-ttu-id="f6807-162">Значение поля **Эффективность** карточки рабочего центра</span><span class="sxs-lookup"><span data-stu-id="f6807-162">The value in the **Efficiency** field on the work center card.</span></span>  

<span data-ttu-id="f6807-163">Теперь рассчитанный календарь рабочего центра позволяет определить, когда и какая производственная мощность доступна в данном рабочем центре.</span><span class="sxs-lookup"><span data-stu-id="f6807-163">The calculated work center calendar will now define when and how much capacity is available at this work center.</span></span> <span data-ttu-id="f6807-164">Это управляет подробным планированием операций, выполняемых в рабочем центре.</span><span class="sxs-lookup"><span data-stu-id="f6807-164">This controls the detailed scheduling of operations performed at the work center.</span></span>  

## <a name="to-record-work-center-absence"></a><span data-ttu-id="f6807-165">Запись простоев рабочего центра</span><span class="sxs-lookup"><span data-stu-id="f6807-165">To record work center absence</span></span>  
1.  <span data-ttu-id="f6807-166">В окне **Календарь производственного центра** выберите действие **Показать матрицу**.</span><span class="sxs-lookup"><span data-stu-id="f6807-166">In the **Work Center Calendar** window, choose the **Show Matrix** action.</span></span>
2. <span data-ttu-id="f6807-167">В окне **Матрица календаря производственного центра** выберите рабочий центр и календарный день, когда должно быть записано время простоя, затем выберите действие **Простой**.</span><span class="sxs-lookup"><span data-stu-id="f6807-167">In the **Work Center Calendar Matrix** window, select the work center and calendar day when the absence time should be recorded, and then choose the **Absence** action.</span></span>  
3.  <span data-ttu-id="f6807-168">В окне **Простой** определите начальное время, конечное время и описание дня простоя.</span><span class="sxs-lookup"><span data-stu-id="f6807-168">In the **Absence** window, define the starting time, ending time, and description of that day’s absence.</span></span> <span data-ttu-id="f6807-169">Например.</span><span class="sxs-lookup"><span data-stu-id="f6807-169">For example:</span></span>  

    <span data-ttu-id="f6807-170">25/01/01 08:00 10:00 Обслуживание</span><span class="sxs-lookup"><span data-stu-id="f6807-170">25/01/01 08:00 10:00 Maintenance</span></span>  

4.  <span data-ttu-id="f6807-171">Выберите действие **Обновить**, затем закройте окно **Простой**.</span><span class="sxs-lookup"><span data-stu-id="f6807-171">Choose the **Update** action, and then close the **Absence** window.</span></span>  

<span data-ttu-id="f6807-172">Производственная мощность выбранного дня теперь уменьшена на введенное время простоя.</span><span class="sxs-lookup"><span data-stu-id="f6807-172">The capacity of the selected day has now decreased by the recorded absence time.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f6807-173">См. также</span><span class="sxs-lookup"><span data-stu-id="f6807-173">See Also</span></span>  
[<span data-ttu-id="f6807-174">Практическое руководство. Настройка базовых календарей</span><span class="sxs-lookup"><span data-stu-id="f6807-174">How to: Set Up Base Calendars</span></span>](across-how-to-assign-base-calendars.md)  
[<span data-ttu-id="f6807-175">Практическое руководство. Настройка рабочих центров и машинных центров</span><span class="sxs-lookup"><span data-stu-id="f6807-175">How to: Set Up Work Centers and Machine Centers</span></span>](production-how-to-set-up-work-and-machine-centers.md)  
[<span data-ttu-id="f6807-176">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="f6807-176">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
[<span data-ttu-id="f6807-177">Производство</span><span class="sxs-lookup"><span data-stu-id="f6807-177">Manufacturing</span></span>](production-manage-manufacturing.md)  
<span data-ttu-id="f6807-178">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f6807-178">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

