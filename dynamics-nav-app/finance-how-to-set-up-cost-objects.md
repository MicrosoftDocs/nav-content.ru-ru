---
title: "Как настраивать объекты затрат"
description: "Узнайте, как настраивать объекты затрат, которые аналогичны измерениям для главной книги."
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
ms.openlocfilehash: d525729ee42fe3803c52e2c54925496aa23f9712
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-cost-objects"></a><span data-ttu-id="e3a41-103">Практическое руководство. Настройка объектов затрат</span><span class="sxs-lookup"><span data-stu-id="e3a41-103">How to: Set Up Cost Objects</span></span>
<span data-ttu-id="e3a41-104">Объекты затрат — это проекты, продукты или сервисы организации.</span><span class="sxs-lookup"><span data-stu-id="e3a41-104">Cost objects are projects, products, or services of a company.</span></span> <span data-ttu-id="e3a41-105">Диаграмма объектов затрат аналогична информации об измерениях для главной книги.</span><span class="sxs-lookup"><span data-stu-id="e3a41-105">The chart of cost objects is similar to the dimension information for the general ledger.</span></span> <span data-ttu-id="e3a41-106">Диаграмму объектов затрат можно настроить одним из следующих способов:</span><span class="sxs-lookup"><span data-stu-id="e3a41-106">You can set up the chart of cost objects in the following ways:</span></span>  

* <span data-ttu-id="e3a41-107">Перенос значений измерений главной книги в план объектов затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-107">Transfer dimension values in the general ledger to the chart of cost objects.</span></span> <span data-ttu-id="e3a41-108">Все необходимые изменения можно внести после перевода.</span><span class="sxs-lookup"><span data-stu-id="e3a41-108">You can make any necessary adjustments after the transfer.</span></span>  
* <span data-ttu-id="e3a41-109">Создайте новую диаграмму объектов затрат, которая не зависит от Главной книги, или добавьте новый объект затрат в существующую диаграмму объектов затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-109">Create a new chart of cost object that is independent of the general ledger or add a new cost object to an existing chart of cost objects.</span></span> <span data-ttu-id="e3a41-110">Необходимо создать каждый объект затрат по отдельности.</span><span class="sxs-lookup"><span data-stu-id="e3a41-110">You must create each cost object individually.</span></span>  

## <a name="to-transfer-dimension-values-from-the-general-ledger-to-the-chart-of-cost-objects"></a><span data-ttu-id="e3a41-111">Перенос значений измерений из главной книги в план объектов затрат</span><span class="sxs-lookup"><span data-stu-id="e3a41-111">To transfer dimension values from the general ledger to the chart of cost objects</span></span>  
1.  <span data-ttu-id="e3a41-112">Установите измерение, которое должно быть измерением объекта затрат, в окне **Обновить измерения CA**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-112">Set a dimension to be the cost object dimension in the **Update CA Dimensions** window.</span></span> <span data-ttu-id="e3a41-113">Передаются только значения данного измерения.</span><span class="sxs-lookup"><span data-stu-id="e3a41-113">Only the values from this dimension are transferred.</span></span>  
2.  <span data-ttu-id="e3a41-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Диаграмма объектов затрат**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e3a41-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Cost Objects**, and then choose the related link.</span></span>  
3.  <span data-ttu-id="e3a41-115">Выберите действие **Получить объекты затрат из измерения** для возвращения значений измерений в диаграмму объектов затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-115">Choose the **Get Cost Objects from Dimension** action to transfer dimension values to the chart of cost objects.</span></span> <span data-ttu-id="e3a41-116">Функция перемещает значения измерений, заданные на шаге 1.</span><span class="sxs-lookup"><span data-stu-id="e3a41-116">The function transfers the dimension values that you defined in step 1.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="e3a41-117">Можно настроить поле **Выровнять измерение объекта затрат** для односторонней синхронизации значений измерений из главной книги в диаграмму объектов затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-117">You can set up the **Align Cost Object Dimension**  field to define a one-way synchronization of dimension values from the general ledger to the chart of cost objects.</span></span> <span data-ttu-id="e3a41-118">Нельзя определить синхронизацию диаграммы объектов затрат со значениями измерений из главной книги.</span><span class="sxs-lookup"><span data-stu-id="e3a41-118">You cannot define a synchronization of the chart of cost objects to dimension values from the general ledger.</span></span>  

<span data-ttu-id="e3a41-119">Диаграмма объектов затрат теперь содержит все заданные значения измерений из главной книги и включает должности и подытоги.</span><span class="sxs-lookup"><span data-stu-id="e3a41-119">The chart of cost objects now contains all specified dimension values from the general ledger and includes titles and subtotals.</span></span>  

## <a name="to-create-new-cost-objects-in-the-chart-of-cost-objects-window"></a><span data-ttu-id="e3a41-120">Создание новых объектов затрат в окне "Диаграмма объектов затрат"</span><span class="sxs-lookup"><span data-stu-id="e3a41-120">To create new cost objects in the Chart of Cost Objects window</span></span>  
<span data-ttu-id="e3a41-121">Можно настроить и обслуживать объекты затрат в карточке **Карта объектов затрат** или в окне **Диаграмма объектов затрат**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-121">You can set up and maintain cost objects in either the **Cost Object Card** card or in the **Chart of Cost Objects** window.</span></span> <span data-ttu-id="e3a41-122">В рамках этой процедуры настраиваются объекты затрат в окне **Диаграмма объектов затрат**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-122">In this procedure, you set up cost objects in the **Chart of Cost Objects** window.</span></span>  

1.  <span data-ttu-id="e3a41-123">Откройте окно **Диаграмма объектов затрат** в режиме редактирования.</span><span class="sxs-lookup"><span data-stu-id="e3a41-123">Open the **Chart of Cost Objects** window in edit mode.</span></span>  
2.  <span data-ttu-id="e3a41-124">В поле **Код** введите код объекта затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-124">In the **Code** field, enter the cost object code.</span></span> <span data-ttu-id="e3a41-125">У всех объектов затрат должен быть код.</span><span class="sxs-lookup"><span data-stu-id="e3a41-125">All cost objects must have a code.</span></span>  
3.  <span data-ttu-id="e3a41-126">В поле **Имя** введите название объекта затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-126">In the **Name** field, enter the cost object name.</span></span>  
4.  <span data-ttu-id="e3a41-127">Выберите стрелку раскрывающегося списка в поле **Тип строки**, чтобы указать назначение объекта затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-127">Choose the drop-down arrow in the **Line Type** field to specify the purpose of the cost object.</span></span>  

    * <span data-ttu-id="e3a41-128">Для объектов затрат с типом строки **Всего** следует заполнить поле **Всего из/в**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-128">For cost objects of the **Total** line type, fill in the **Total From/To** field.</span></span> <span data-ttu-id="e3a41-129">Используйте оператор **или**, который представлен вертикальной чертой (**&#124;**), чтобы установить диапазоны объектов затрат.</span><span class="sxs-lookup"><span data-stu-id="e3a41-129">Use the **or** operator, which is a vertical line (**&#124;**), to set ranges of cost objects.</span></span>  
    * <span data-ttu-id="e3a41-130">Для объектов затрат с типом строки **Сумма (до)** это поле заполняется автоматически при использовании функции отступа.</span><span class="sxs-lookup"><span data-stu-id="e3a41-130">For cost objects of the **End-Total** line type, this field is filled in automatically when you use  the indent function.</span></span>  
5.  <span data-ttu-id="e3a41-131">Заполните поле **Порядок сортировки**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-131">Fill in the **Sorting Order** field.</span></span>  
6.  <span data-ttu-id="e3a41-132">Выберите следующую пустую строку, чтобы создать новый объект затрат, затем повторите шаги с 2 по 5.</span><span class="sxs-lookup"><span data-stu-id="e3a41-132">Chose the next empty line to create a new cost object, and then repeat steps 2 through 5.</span></span>  
7.  <span data-ttu-id="e3a41-133">После настройки всех объектов затрат выберите действие **Сдвинуть объекты затрат**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-133">After you have set up all the cost objects, choose the **Indent Cost Objects** action.</span></span> <span data-ttu-id="e3a41-134">Нажмите кнопку **Да**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-134">Choose the **Yes** button.</span></span>  

> [!IMPORTANT]  
>  <span data-ttu-id="e3a41-135">Если введены определения в полях **Всего из/в** для объектов затрат **Сумма (до)**, то перед запуском этой функции необходимо снова ввести определения.</span><span class="sxs-lookup"><span data-stu-id="e3a41-135">If you have entered definitions in the **Total From/To** fields for **End-Total** cost objects before you run the indent function, then you must enter them again.</span></span> <span data-ttu-id="e3a41-136">Функция переопределяет значения во всех полях **Сумма (до)**.</span><span class="sxs-lookup"><span data-stu-id="e3a41-136">The function overwrites the values in all **End-Total** fields.</span></span>  

## <a name="see-also"></a><span data-ttu-id="e3a41-137">См. также</span><span class="sxs-lookup"><span data-stu-id="e3a41-137">See Also</span></span>  
[<span data-ttu-id="e3a41-138">Учет по затратам</span><span class="sxs-lookup"><span data-stu-id="e3a41-138">Accounting for Costs</span></span>](finance-manage-cost-accounting.md)  
<span data-ttu-id="e3a41-139">[Определение центров затрат и объектов затрат для плана счетов](finance-defining-cost-centers-and-cost-objects-for-chart-of-accounts.md) </span><span class="sxs-lookup"><span data-stu-id="e3a41-139">[Defining Cost Centers and Cost Objects for Chart of Accounts](finance-defining-cost-centers-and-cost-objects-for-chart-of-accounts.md) </span></span>  
<span data-ttu-id="e3a41-140">[Обеспечивает баланс между типом затрат, центром затрат и объектом затрат](finance-balances-between-cost-type-cost-center-and-cost-object.md) </span><span class="sxs-lookup"><span data-stu-id="e3a41-140">[Balances Between Cost Type, Cost Center, and Cost Object](finance-balances-between-cost-type-cost-center-and-cost-object.md) </span></span>  
<span data-ttu-id="e3a41-141">[Настройка учета затрат](finance-set-up-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="e3a41-141">[Setting Up Cost Accounting](finance-set-up-cost-accounting.md) </span></span>  
<span data-ttu-id="e3a41-142">[Терминология в учете затрат](finance-terminology-in-cost-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="e3a41-142">[Terminology in Cost Accounting](finance-terminology-in-cost-accounting.md) </span></span>  
[<span data-ttu-id="e3a41-143">Об учете затрат</span><span class="sxs-lookup"><span data-stu-id="e3a41-143">About Cost Accounting</span></span>](finance-about-cost-accounting.md)  
<span data-ttu-id="e3a41-144">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="e3a41-144">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

