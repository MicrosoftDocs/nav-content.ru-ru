---
title: "Как выполнять прямое перепланирование или обновление производственных заказов"
description: "Строки производственного заказа содержат товарные позиции, которые должны быть изготовлены для этого производственного заказа."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e37e642413ccac13f049b3d1ccd5dfc564f72516
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-replan-or-refresh-production-orders-directly"></a><span data-ttu-id="d1524-103">Практическое руководство. Прямое перепланирование или обновление производственных заказов</span><span class="sxs-lookup"><span data-stu-id="d1524-103">How to: Replan or Refresh Production Orders Directly</span></span>
<span data-ttu-id="d1524-104">Функция **Перепланировать** в производственных заказах обычно используется после добавления или изменения компонентов, которые составляют подчиненные производственные заказы.</span><span class="sxs-lookup"><span data-stu-id="d1524-104">The **Replan** function on production orders is typically used after you have added or changed components that constitute underlying production orders.</span></span> <span data-ttu-id="d1524-105">Эта функция позволяет рассчитать изменения, произведенные в строках компонентов и маршрутов, с включением элементов на нижний уровнях спецификаций, для которых она может генерировать новые производственные заказы.</span><span class="sxs-lookup"><span data-stu-id="d1524-105">The function calculates changes made to components and routings lines, and it includes items on lower production BOM levels for which it may generate new production orders.</span></span>  

<span data-ttu-id="d1524-106">В соответствии с изменениями, произведенными в строках компонентов и маршрутов, функция перепланирования вычисляет и планирует любой новый спрос для производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="d1524-106">Based on the changes you have made to the components and routing lines, the Replan function calculates and plans for any new demand for the production order.</span></span>  

<span data-ttu-id="d1524-107">Функция **Обновить** в производственных заказах обычно используется после выполнения одного из следующих действий:</span><span class="sxs-lookup"><span data-stu-id="d1524-107">The **Refresh** function on production orders is typically used after you have done one of the following:</span></span>

- <span data-ttu-id="d1524-108">Создан заголовок производственного заказа для первоначального вычисления и создания данных строки.</span><span class="sxs-lookup"><span data-stu-id="d1524-108">Created a production order header manually to calculate and create line data for the first time.</span></span>
- <span data-ttu-id="d1524-109">Внесение изменений в заголовке производственного заказа для пересчета всех данных строки.</span><span class="sxs-lookup"><span data-stu-id="d1524-109">Made changes to the production order header to recalculate all the line data.</span></span>

<span data-ttu-id="d1524-110">Функция обновления позволяет выполнить расчет изменений, произведенных в заголовке производственного заказа, не переходя на уровни спецификаций.</span><span class="sxs-lookup"><span data-stu-id="d1524-110">The Refresh function calculates changes made to a production order header and does not involve production BOM levels.</span></span> <span data-ttu-id="d1524-111">Назначением функции является вычисление и инициализация значений строк компонентов и маршрутов в соответствии с основными данными, заданными в назначенной спецификации и маршруте, согласно объему заказа и сроку выполнения в заголовке производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="d1524-111">The function calculates and initiates the values of the component lines and routing lines based on the master data defined in the assigned production BOM and routing, according to the order quantity and due date on the production order’s header.</span></span>

<span data-ttu-id="d1524-112">Можно либо вставить строки производственного заказа вручную, либо использовать функцию, которая рассчитывает строки производственного заказа согласно его заголовку.</span><span class="sxs-lookup"><span data-stu-id="d1524-112">You can either insert the production order lines manually or use the function that calculates the production order lines from the header.</span></span>  

> [!NOTE]
 <span data-ttu-id="d1524-113">Если функция обновления используется для вычисления строк для производственного заказа, старые строки производственного заказа удаляются и рассчитываются новые.</span><span class="sxs-lookup"><span data-stu-id="d1524-113">If you use the Refresh function to recalculate production order lines, the old production order lines are deleted and new lines are calculated.</span></span>  

## <a name="to-replan-a-production-order"></a><span data-ttu-id="d1524-114">Перепланировка производственного заказа</span><span class="sxs-lookup"><span data-stu-id="d1524-114">To replan a production order</span></span>  
1.  <span data-ttu-id="d1524-115">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Утвержд. произв. заказы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d1524-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Orders**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d1524-116">Откройте производственный заказ, который требуется перепланировать.</span><span class="sxs-lookup"><span data-stu-id="d1524-116">Open the production order you want to replan.</span></span>  
3.  <span data-ttu-id="d1524-117">На экспресс-вкладке **Строки** выберите действие **Строки**, затем выберите действие **Компоненты**.</span><span class="sxs-lookup"><span data-stu-id="d1524-117">On the **Lines** FastTab, choose the **Lines** action, and then choose the **Components** action.</span></span>  
4.  <span data-ttu-id="d1524-118">Добавьте компонент, который является производимым товаром или сборочным узлом.</span><span class="sxs-lookup"><span data-stu-id="d1524-118">Add a component, which is a produced item or subassembly.</span></span>  
5.  <span data-ttu-id="d1524-119">В окне производственного заказа выберите действие **Перепланировать**.</span><span class="sxs-lookup"><span data-stu-id="d1524-119">From the production order, choose the **Replan** action.</span></span>  

    <span data-ttu-id="d1524-120">В окне **Перепланирование произв. заказа** укажите, что и как перепланировать.</span><span class="sxs-lookup"><span data-stu-id="d1524-120">In the **Replan Production Order** window, proceed to define how and what to replan.</span></span>  
6.  <span data-ttu-id="d1524-121">В поле **Направление планирования** выберите один из следующих параметров:</span><span class="sxs-lookup"><span data-stu-id="d1524-121">In the **Scheduling Direction** field, select one of the following options.</span></span>  

    |<span data-ttu-id="d1524-122">Параметр</span><span class="sxs-lookup"><span data-stu-id="d1524-122">Option</span></span>|<span data-ttu-id="d1524-123">Описанием</span><span class="sxs-lookup"><span data-stu-id="d1524-123">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d1524-124">**Назад**</span><span class="sxs-lookup"><span data-stu-id="d1524-124">**Back**</span></span>|<span data-ttu-id="d1524-125">Вычисляет последовательность операций от самой ранней возможной даты окончания, определяемой сроком выполнения и/или другими планами заказов, до самой последней возможной начальной даты.</span><span class="sxs-lookup"><span data-stu-id="d1524-125">Calculates the operation sequence backwards from the earliest possible ending date, defined by due date and/or other scheduled orders, to the latest possible starting date.</span></span> <span data-ttu-id="d1524-126">**Примечание.** Этот выбираемый по умолчанию вариант подходит в большинстве случаев.</span><span class="sxs-lookup"><span data-stu-id="d1524-126">**Note:**  This default option is relevant in the majority of situations.</span></span>|  
    |<span data-ttu-id="d1524-127">**Прямое**</span><span class="sxs-lookup"><span data-stu-id="d1524-127">**Forward**</span></span>|<span data-ttu-id="d1524-128">Вычисляет последовательность операций от самой последней возможной даты начала, определяемой сроком выполнения и/или другими планами заказов, до самой ранней возможной даты окончания.</span><span class="sxs-lookup"><span data-stu-id="d1524-128">Calculates the operation sequence forward from the earliest latest possible starting date, defined by due date and/or other scheduled orders, to the earliest possible ending date.</span></span> <span data-ttu-id="d1524-129">**Примечание.** Этот параметр подходит только для срочных заказов.</span><span class="sxs-lookup"><span data-stu-id="d1524-129">**Note:**  This option is only relevant for expedite orders.</span></span>|  

7.  <span data-ttu-id="d1524-130">В поле **План** укажите, вычислять ли производственные требования для производимых товаров согласно спецификации следующим образом:</span><span class="sxs-lookup"><span data-stu-id="d1524-130">In the **Plan** field, select whether to calculate production requirements for produced items on the production BOM, as follows.</span></span>  

    |<span data-ttu-id="d1524-131">Параметр</span><span class="sxs-lookup"><span data-stu-id="d1524-131">Option</span></span>|<span data-ttu-id="d1524-132">Описанием</span><span class="sxs-lookup"><span data-stu-id="d1524-132">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d1524-133">**Отсутствуют уровни**</span><span class="sxs-lookup"><span data-stu-id="d1524-133">**No Levels**</span></span>|<span data-ttu-id="d1524-134">Не учитывать производство нижнего уровня.</span><span class="sxs-lookup"><span data-stu-id="d1524-134">Do not consider lower level production.</span></span> <span data-ttu-id="d1524-135">Этот вариант предусматривает обновление только плана для товара.</span><span class="sxs-lookup"><span data-stu-id="d1524-135">This only updates the item’s schedule, like refresh.</span></span>|  
    |<span data-ttu-id="d1524-136">**Один уровень**</span><span class="sxs-lookup"><span data-stu-id="d1524-136">**One Level**</span></span>|<span data-ttu-id="d1524-137">Планирование с учетом производственного спроса первого уровня.</span><span class="sxs-lookup"><span data-stu-id="d1524-137">Plan for first-level production demand.</span></span> <span data-ttu-id="d1524-138">Могут быть созданы производственные заказы первого уровня.</span><span class="sxs-lookup"><span data-stu-id="d1524-138">First-level production orders may be created.</span></span>|  
    |<span data-ttu-id="d1524-139">**Все уровни**</span><span class="sxs-lookup"><span data-stu-id="d1524-139">**All Levels**</span></span>|<span data-ttu-id="d1524-140">Планирование с учетом производственного спроса всех уровней.</span><span class="sxs-lookup"><span data-stu-id="d1524-140">Plan for all-level production demand.</span></span> <span data-ttu-id="d1524-141">Могут быть созданы nроизводственные заказы всех уровней.</span><span class="sxs-lookup"><span data-stu-id="d1524-141">All-level production orders may be created.</span></span>|  

8.  <span data-ttu-id="d1524-142">Выберите **Один уровень** и нажмите кнопку **ОК**, чтобы перепланировать производственный заказ, а также вычислить и создать новый подчиненный производственный заказ для внедренного сборочного узла, если он не полностью готов.</span><span class="sxs-lookup"><span data-stu-id="d1524-142">Select **One Level**, and choose the **OK** button to replan the production order, and calculate and create a new underlying production order for the introduced subassembly, if it is not fully available.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="d1524-143">Изменения, выполняемые функцией **Перепланировать**, очень часто приводят к изменению потребности в производственной мощности для выполнения производственного заказа, и впоследствии может потребоваться перепланирование операций.</span><span class="sxs-lookup"><span data-stu-id="d1524-143">Changes implemented with the **Replan** function are very likely to change the capacity need of the production order and you may therefore have to reschedule operations afterwards.</span></span>  

## <a name="to-refresh-a-production-order"></a><span data-ttu-id="d1524-144">Обновление производственного заказа</span><span class="sxs-lookup"><span data-stu-id="d1524-144">To refresh a production order</span></span>  
<span data-ttu-id="d1524-145">Если были изменены строки производственного заказа, компоненты или строки маршрутов, следует обновить также и информацию производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="d1524-145">If you have amended production order lines, components, or routing lines, you must also refresh the information on the production order.</span></span> <span data-ttu-id="d1524-146">В следующей процедуре показан расчет компонентов для утвержденного производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="d1524-146">In the following procedure, the components are calculated for a firm planned production order.</span></span> <span data-ttu-id="d1524-147">Действия для строк маршрутов аналогичны.</span><span class="sxs-lookup"><span data-stu-id="d1524-147">The steps are similar for routing lines.</span></span>

1.  <span data-ttu-id="d1524-148">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Утвержд. произ. заказ**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d1524-148">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Order**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d1524-149">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="d1524-149">Choose the **New** action.</span></span> <span data-ttu-id="d1524-150">Дополнительные сведения см. в разделе [Практическое руководство. Создание производственных заказов](production-how-to-create-production-orders.md).</span><span class="sxs-lookup"><span data-stu-id="d1524-150">For more information, see [How to: Create Production orders](production-how-to-create-production-orders.md).</span></span>  
3.  <span data-ttu-id="d1524-151">Выберите действие **Обновить**.</span><span class="sxs-lookup"><span data-stu-id="d1524-151">Choose the **Refresh** action.</span></span>
4. <span data-ttu-id="d1524-152">В окне **Обновление произв. заказа** выберите один из следующих параметров:</span><span class="sxs-lookup"><span data-stu-id="d1524-152">In the **Refresh Production Order** window, select one of the following options:</span></span>

    |<span data-ttu-id="d1524-153">Параметр</span><span class="sxs-lookup"><span data-stu-id="d1524-153">Option</span></span>|<span data-ttu-id="d1524-154">Описанием</span><span class="sxs-lookup"><span data-stu-id="d1524-154">Description</span></span>|  
    |----------------------------------|---------------|---------------------------------------|  
    |<span data-ttu-id="d1524-155">**Направление планирования**</span><span class="sxs-lookup"><span data-stu-id="d1524-155">**Scheduling Direction**</span></span>|<span data-ttu-id="d1524-156">**Прямое**</span><span class="sxs-lookup"><span data-stu-id="d1524-156">**Forward**</span></span>|<span data-ttu-id="d1524-157">Планирование начинается с даты начала и продолжается до даты окончания.</span><span class="sxs-lookup"><span data-stu-id="d1524-157">Scheduling starts from the starting date and proceeds forward to the finishing date.</span></span> <span data-ttu-id="d1524-158">Чтобы использовать этот параметр, необходимо ввести дату начала.</span><span class="sxs-lookup"><span data-stu-id="d1524-158">You must fill in the starting date to use this option.</span></span>|  
    ||<span data-ttu-id="d1524-159">**Обратный**</span><span class="sxs-lookup"><span data-stu-id="d1524-159">**Backward**</span></span>|<span data-ttu-id="d1524-160">Планирование начинается с даты окончания и продолжается до даты начала.</span><span class="sxs-lookup"><span data-stu-id="d1524-160">Scheduling starts from the ending date and proceeds backward to the starting date.</span></span>|  
    |<span data-ttu-id="d1524-161">**Вычислить**</span><span class="sxs-lookup"><span data-stu-id="d1524-161">**Calculate**</span></span>|<span data-ttu-id="d1524-162">**Строки**</span><span class="sxs-lookup"><span data-stu-id="d1524-162">**Lines**</span></span>|<span data-ttu-id="d1524-163">Выберите это поле для расчета строк производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="d1524-163">Select this field to calculate the production order lines.</span></span>|  
    ||<span data-ttu-id="d1524-164">**Маршруты**</span><span class="sxs-lookup"><span data-stu-id="d1524-164">**Routings**</span></span>|<span data-ttu-id="d1524-165">Данное поле не влияет на расчет строк производства.</span><span class="sxs-lookup"><span data-stu-id="d1524-165">This field has no influence on calculating the production lines.</span></span>|  
    ||<span data-ttu-id="d1524-166">**Требуемый компонент**</span><span class="sxs-lookup"><span data-stu-id="d1524-166">**Component Need**</span></span>|<span data-ttu-id="d1524-167">Данное поле не влияет на расчет строк производства.</span><span class="sxs-lookup"><span data-stu-id="d1524-167">This field has no influence on calculating the production lines.</span></span>|  
    |<span data-ttu-id="d1524-168">**Склад**</span><span class="sxs-lookup"><span data-stu-id="d1524-168">**Warehouse**</span></span>|<span data-ttu-id="d1524-169">**Создать входящий запрос**</span><span class="sxs-lookup"><span data-stu-id="d1524-169">**Create Inbound Request**</span></span>|<span data-ttu-id="d1524-170">Данное поле не влияет на расчет строк производства.</span><span class="sxs-lookup"><span data-stu-id="d1524-170">This field has no influence on calculating the production lines.</span></span>|  

5. <span data-ttu-id="d1524-171">Нажмите кнопку **OK** для подтверждения выбора.</span><span class="sxs-lookup"><span data-stu-id="d1524-171">Choose the **OK** button to confirm your selection.</span></span> <span data-ttu-id="d1524-172">Расчет строк производственного заказа выполнен.</span><span class="sxs-lookup"><span data-stu-id="d1524-172">Now the production order lines are calculated.</span></span>

> [!NOTE]  
>  <span data-ttu-id="d1524-173">При расчете компонентов производственного заказа ранее произведенные изменения компонентов не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="d1524-173">Calculating production order components deletes previous changes in the components.</span></span>

## <a name="see-also"></a><span data-ttu-id="d1524-174">См. также</span><span class="sxs-lookup"><span data-stu-id="d1524-174">See Also</span></span>  
[<span data-ttu-id="d1524-175">Планирование</span><span class="sxs-lookup"><span data-stu-id="d1524-175">Planning</span></span>](production-planning.md)  
[<span data-ttu-id="d1524-176">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="d1524-176">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="d1524-177">[Производство](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="d1524-177">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="d1524-178">Наличие</span><span class="sxs-lookup"><span data-stu-id="d1524-178">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="d1524-179">Покупки</span><span class="sxs-lookup"><span data-stu-id="d1524-179">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="d1524-180">[Сведения о проектировании: планирование поставок](design-details-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="d1524-180">[Design Details: Supply Planning](design-details-supply-planning.md) </span></span>  
[<span data-ttu-id="d1524-181">Рекомендации по настройке. Планирование поставок</span><span class="sxs-lookup"><span data-stu-id="d1524-181">Setup Best Practices: Supply Planning</span></span>](setup-best-practices-supply-planning.md)  
<span data-ttu-id="d1524-182">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="d1524-182">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
