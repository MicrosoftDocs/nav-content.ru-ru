---
title: "Как выполнять планирование от заказа к заказу"
description: "Эта задача планирования может быть выполнена в окне **Планирование заказов**, в котором отображаются все данные нового спроса наряду со сведениями о готовности и предложениями по поставке. В окне обеспечиваются обзор и инструменты, необходимые для эффективного планирования спроса из строк продажи и компонентов и последующего непосредственного создания различных типов заказов поставки."
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
ms.openlocfilehash: ab072cd0bae72b7fe3a7ca04c1dd8d00ce5ca5ba
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-plan-for-new-demand-order-by-order"></a><span data-ttu-id="9eff6-104">Практическое руководство. Последовательное планирование по каждому заказу</span><span class="sxs-lookup"><span data-stu-id="9eff6-104">How to: Plan for New Demand Order by Order</span></span>
<span data-ttu-id="9eff6-105">Эта задача планирования может быть выполнена в окне **Планирование заказов**, в котором отображаются все данные нового спроса наряду со сведениями о готовности и предложениями по поставке.</span><span class="sxs-lookup"><span data-stu-id="9eff6-105">This planning task can be performed in the **Order Planning** window, which displays all new demand along with availability information and suggestions for supply.</span></span> <span data-ttu-id="9eff6-106">В окне обеспечиваются обзор и инструменты, необходимые для эффективного планирования спроса из строк продажи и компонентов и последующего непосредственного создания различных типов заказов поставки.</span><span class="sxs-lookup"><span data-stu-id="9eff6-106">It provides the visibility and tools needed to effectively plan demand from sales lines and component lines and then create different types of supply orders directly.</span></span>  

<span data-ttu-id="9eff6-107">В окно **Планирование заказов** можно перейти двумя способами в зависимости от фокуса: из конкретного заказа, для который требуется планирование, или в пакетном режиме, если вы хотите выполнить планирование для всего нового спроса.</span><span class="sxs-lookup"><span data-stu-id="9eff6-107">You can enter the **Order Planning** window in two ways depending on your focus: From an order that you want to plan for specifically or in batch mode because you want to plan for all and any new demand.</span></span>  


## <a name="to-plan-for-new-production-order-demand"></a><span data-ttu-id="9eff6-108">Планирование потребности в новом производственном заказе</span><span class="sxs-lookup"><span data-stu-id="9eff6-108">To plan for new production order demand</span></span>  
1.  <span data-ttu-id="9eff6-109">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Плановые производственные заказы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9eff6-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Planned Production Orders**, and then choose the related link.</span></span> <span data-ttu-id="9eff6-110">(Эти действия можно выполнять для запланированных, утвержденных или выпущенных производственных заказов.)</span><span class="sxs-lookup"><span data-stu-id="9eff6-110">(You can perform these steps for planned, firm planned, or released production orders).</span></span>
2.  <span data-ttu-id="9eff6-111">Откройте производственный заказ, для которого требуется выполнить планирование, затем выберите действие **Планирование**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-111">Open the production order you want to plan for, and then choose the **Planning** action.</span></span>  
3.  <span data-ttu-id="9eff6-112">В окне **Планирование заказов** выберите действие **Вычислить план**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-112">In the **Order Planning** window, choose the **Calculate Plan** action.</span></span>  

<span data-ttu-id="9eff6-113">Строки планирования отображаются в окне в соответствии с фильтром представления **Производственные требования**, то есть невыполненные строки компонентов всех существующих производственных заказов.</span><span class="sxs-lookup"><span data-stu-id="9eff6-113">The window displays planning lines according to the view filter **Production Demand**, meaning unfulfilled component lines of all existing production orders.</span></span> <span data-ttu-id="9eff6-114">Спрос отображается не только для рассматриваемого производственного заказа, так как планировать отдельный производственный заказ без учета требований по потенциально более ранним строкам компонентов было бы "опасно".</span><span class="sxs-lookup"><span data-stu-id="9eff6-114">Demand for only the one production order is not shown because it is necessary to plan for one production order with an overview of demand for potentially earlier components lines.</span></span> <span data-ttu-id="9eff6-115">Планируемые строки рассматриваемого производственного заказа отображаются развернутыми.</span><span class="sxs-lookup"><span data-stu-id="9eff6-115">Planning lines for the production order in context are expanded.</span></span>  

## <a name="to-plan-for-any-new-demand"></a><span data-ttu-id="9eff6-116">Планирование с учетом нового спроса</span><span class="sxs-lookup"><span data-stu-id="9eff6-116">To plan for any new demand</span></span>  
1. <span data-ttu-id="9eff6-117">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Вычислить план**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9eff6-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Order Planning**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="9eff6-118">В окне **Планирование заказов** выберите действие **Вычислить план**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-118">In the **Order Planning** window, choose the **Calculate Plan** action.</span></span>
3.  <span data-ttu-id="9eff6-119">Нажмите кнопку **Развернуть (+)** перед датой в поле **Дата требования**, чтобы просмотреть подчиненные строки планирования, соответствующие строкам спроса с недостаточным наличием.</span><span class="sxs-lookup"><span data-stu-id="9eff6-119">Choose the **Expand (+)** button in front of the date in the **Demand Date** field to see the underlying planning lines that represent demand lines with insufficient availability.</span></span>  
4.  <span data-ttu-id="9eff6-120">Для каждой развернутой строки планирования (строки спроса) можно просмотреть значения в информационных полях внизу окна.</span><span class="sxs-lookup"><span data-stu-id="9eff6-120">For each expanded planning line, that is, demand line, you can see values in information fields at the bottom of the window.</span></span>  

    |<span data-ttu-id="9eff6-121">Параметр</span><span class="sxs-lookup"><span data-stu-id="9eff6-121">Option</span></span>|<span data-ttu-id="9eff6-122">Описанием</span><span class="sxs-lookup"><span data-stu-id="9eff6-122">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9eff6-123">**Количество на других складах**</span><span class="sxs-lookup"><span data-stu-id="9eff6-123">**Qty. on Other Locations**</span></span>|<span data-ttu-id="9eff6-124">Показывает, есть ли товар на другом складе.</span><span class="sxs-lookup"><span data-stu-id="9eff6-124">Shows if the item exists on another location.</span></span> <span data-ttu-id="9eff6-125">Можно просмотреть и выбрать его.</span><span class="sxs-lookup"><span data-stu-id="9eff6-125">You can then look up and select it.</span></span>|  
    |<span data-ttu-id="9eff6-126">**Наличие заменителей**</span><span class="sxs-lookup"><span data-stu-id="9eff6-126">**Substitutes Exist**</span></span>|<span data-ttu-id="9eff6-127">Показывает, создана ли для товара замена.</span><span class="sxs-lookup"><span data-stu-id="9eff6-127">Shows if a substitute item is created for the item.</span></span> <span data-ttu-id="9eff6-128">Можно просмотреть и выбрать его.</span><span class="sxs-lookup"><span data-stu-id="9eff6-128">You can then look up and select it.</span></span> <span data-ttu-id="9eff6-129">Следует заметить, что эта функция применима только к компонентам, то есть, происходящим от строк спроса с типом **Производство**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-129">Note that this feature only applies to components, that is, from demand lines of type **Production**.</span></span>|  
    |<span data-ttu-id="9eff6-130">**Доступное количество**</span><span class="sxs-lookup"><span data-stu-id="9eff6-130">**Quantity Available**</span></span>|<span data-ttu-id="9eff6-131">Показывает общую доступность товара, т. е. предполагаемое свободное наличие.</span><span class="sxs-lookup"><span data-stu-id="9eff6-131">Shows the total availability of the item, that is, the Projected Available Balance.</span></span>|  
    |<span data-ttu-id="9eff6-132">**Ближайшая доступная дата**</span><span class="sxs-lookup"><span data-stu-id="9eff6-132">**Earliest Date Available**</span></span>|<span data-ttu-id="9eff6-133">Показывает дату прибытия входящего заказа на поставку, который может покрыть необходимое количество на дату, более позднюю, чем требуемая дата.</span><span class="sxs-lookup"><span data-stu-id="9eff6-133">Shows the arrival date of an inbound supply order that can cover the needed quantity on a date later than the demand date.</span></span>|  

5.  <span data-ttu-id="9eff6-134">В поле **Метод пополнения** выберите тип создаваемого заказа на поставку.</span><span class="sxs-lookup"><span data-stu-id="9eff6-134">In the **Replenishment System** field, select which type of supply order to create.</span></span>  

    <span data-ttu-id="9eff6-135">По умолчанию используется значение из карточки товара или карточки единицы хранения, однако его можно изменить на одно из трех следующих значений:</span><span class="sxs-lookup"><span data-stu-id="9eff6-135">The default value is that of the item card, or SKU card, but you can change it to one of three options:</span></span>  

    |<span data-ttu-id="9eff6-136">Параметр</span><span class="sxs-lookup"><span data-stu-id="9eff6-136">Option</span></span>|<span data-ttu-id="9eff6-137">Описанием</span><span class="sxs-lookup"><span data-stu-id="9eff6-137">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9eff6-138">**Покупка**</span><span class="sxs-lookup"><span data-stu-id="9eff6-138">**Purchase**</span></span>|<span data-ttu-id="9eff6-139">Создает заказ покупки.</span><span class="sxs-lookup"><span data-stu-id="9eff6-139">Creates a purchase order.</span></span>|  
    |<span data-ttu-id="9eff6-140">**Перемещение**</span><span class="sxs-lookup"><span data-stu-id="9eff6-140">**Transfer**</span></span>|<span data-ttu-id="9eff6-141">Создает заказ на перемещение.</span><span class="sxs-lookup"><span data-stu-id="9eff6-141">Creates a transfer order.</span></span>|  
    |<span data-ttu-id="9eff6-142">**Произв. заказ**</span><span class="sxs-lookup"><span data-stu-id="9eff6-142">**Prod. Order**</span></span>|<span data-ttu-id="9eff6-143">Создает производственный заказ.</span><span class="sxs-lookup"><span data-stu-id="9eff6-143">Creates a production order.</span></span>|  

    <span data-ttu-id="9eff6-144">В поле **Поставка от** выберите значение в соответствии с выбранной системой пополнения.</span><span class="sxs-lookup"><span data-stu-id="9eff6-144">In the **Supply From** field you must select a value according to the selected replenishment system.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="9eff6-145">Если это поле не заполнено, при использовании функции **Создание заказов на поставку** система выводит сообщение об ошибке, и заказ на поставку для данной строки планирования не создается.</span><span class="sxs-lookup"><span data-stu-id="9eff6-145">If the field is not filled in, the system will display an error message when you use the **Make Supply Order** function, and no supply order will be created for the planning line in question.</span></span> <span data-ttu-id="9eff6-146">Это, однако, не относится к случаю, когда система пополнения — **Произв. заказ**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-146">This, however, is not the case if the replenishment system is **Prod. Order**.</span></span>  

6.  <span data-ttu-id="9eff6-147">В поле **Поставка от** выберите в соответствующем списке источник поставки.</span><span class="sxs-lookup"><span data-stu-id="9eff6-147">From the **Supply From** field, you can look up in the relevant list and select where the supply should come from:</span></span>  

    - <span data-ttu-id="9eff6-148">Если метод пополнения — **Покупка**, кнопка выбора используется для выбора в окне **Каталог поставщиков товара**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-148">If replenishment system is **Purchase**, the look-up button in this field looks up in the **Item Vendor Catalog** window.</span></span>  
    - <span data-ttu-id="9eff6-149">Если метод пополнения — **Перемещение**, кнопка выбора используется для выбора в окне **Список складов**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-149">If replenishment system is **Transfer**, the look-up button in this field looks up in the **Location List** window.</span></span>  

    <span data-ttu-id="9eff6-150">Если товар находится на другом складе, в расположенном внизу поле **Количество на другом складе** отображается соответствующее значение, и пользователь может выбрать склад, с которого должен быть получен товар при выполнении заказа на перемещение.</span><span class="sxs-lookup"><span data-stu-id="9eff6-150">In case the item exists in another location, the **Qty. on Other Location** field at the bottom shows a value and you can then look up and select the location from which the item should be supplied when you make the transfer order.</span></span>  

    <span data-ttu-id="9eff6-151">Если для требуемого товара существует замена, значением поля **Наличие заменителей** будет **Да**, и пользователь сможет выбрать замену в окне **Замена товара - операции**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-151">If a substitute exists for the demanded item, the **Substitute Exists** field is set to **Yes**, and you can then look up to the **Item Substitution Entries** window and select the substitute.</span></span>  

7.  <span data-ttu-id="9eff6-152">Установите флажок **Резервировать**, если требуется обеспечить резерв между создаваемым заказом на поставку и строкой спроса, для которой она создается.</span><span class="sxs-lookup"><span data-stu-id="9eff6-152">Select the **Reserve** check box if you want to make a reservation between the supply order you are creating and the demand line that it is created for.</span></span> <span data-ttu-id="9eff6-153">Это поле по умолчанию не заполнено.</span><span class="sxs-lookup"><span data-stu-id="9eff6-153">It is empty by default.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="9eff6-154">Установить флажок можно, только если значение поля **Резервировать** в карточке товара равно **Необязательно** или **Резервировать**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-154">You can only select this check box if the item has **Optional** or **Always** in the **Reserve** field on its item card.</span></span>  

8.  <span data-ttu-id="9eff6-155">В поле **Кол-во для заказа** можно ввести количество, которое затем будет перенесено в создаваемый заказ на поставку.</span><span class="sxs-lookup"><span data-stu-id="9eff6-155">In the **Qty. to Order** field, you can enter the quantity that will go on the supply order you are creating.</span></span>   
    <span data-ttu-id="9eff6-156">По умолчанию принимается такое же количество, как и в поле **Требуемое количество**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-156">The default value is the same quantity as that in the **Needed Quantity** field.</span></span> <span data-ttu-id="9eff6-157">Но можно заказать больше или меньше данного количества в зависимости от знания о ситуации со спросом.</span><span class="sxs-lookup"><span data-stu-id="9eff6-157">But you may decide to order more or less than this quantity based on your knowledge of the demand situation.</span></span> <span data-ttu-id="9eff6-158">Если, например, в окне **Планирование заказов** имеется несколько несвязанных строк спроса с одной датой выполнения для одного купленного товара, их можно объединить, введя общее необходимое количество в поле **Кол-во для заказа** одной строки, а затем удалив остальные ненужные строки планирования для данного товара.</span><span class="sxs-lookup"><span data-stu-id="9eff6-158">If, for example, you see in the **Order Planning** window that several unrelated demand lines are for the same purchased item, and they are due around the same date, you can consolidate these by entering the total needed quantity in the **Qty. to Order** field of one line, and then delete the other, obsolete planning lines for that item.</span></span>  

9.  <span data-ttu-id="9eff6-159">В полях **Дата завершения** и **Дата заказа** можно ввести временные параметры создаваемых заказов на поставку.</span><span class="sxs-lookup"><span data-stu-id="9eff6-159">In the **Due Date** and **Order Date** fields, you can enter the dates that should apply to the created supply orders.</span></span>  

    <span data-ttu-id="9eff6-160">Эти 2 поля взаимосвязаны через поле **Страховой запас времени по умолчанию**, которое находится в окне **Производство - настройка**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-160">These two fields are interrelated according to the **Default Safety Lead Time** field, which can be found in the **Manufacturing Setup** window.</span></span> <span data-ttu-id="9eff6-161">По умолчанию срок оплаты совпадает с датой спроса, но при необходимости его можно изменить.</span><span class="sxs-lookup"><span data-stu-id="9eff6-161">By default, the due date is the same as the demand date, but you can change this as you like.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="9eff6-162">Если введенная дата наступает после даты требования, программа выдаст предупреждение.</span><span class="sxs-lookup"><span data-stu-id="9eff6-162">If you enter a date later than the demand date, you will receive a warning message.</span></span>  

## <a name="to-make-supply-orders"></a><span data-ttu-id="9eff6-163">Создание заказов на поставку</span><span class="sxs-lookup"><span data-stu-id="9eff6-163">To make supply orders</span></span>  
1.  <span data-ttu-id="9eff6-164">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Плановые производственные заказы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9eff6-164">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Planned Production Orders**, and then choose the related link.</span></span> <span data-ttu-id="9eff6-165">Эти действия можно выполнять для запланированных, утвержденных или выпущенных производственных заказов.</span><span class="sxs-lookup"><span data-stu-id="9eff6-165">You can perform these steps for a planned, firm planned, or released production order.</span></span>  
2.  <span data-ttu-id="9eff6-166">Откройте производственный заказ, для которого требуется выполнить планирование, затем выберите действие **Планирование**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-166">Open the production order you want to plan for, and then choose the **Planning** action.</span></span>  
3.  <span data-ttu-id="9eff6-167">Установите курсор в нужной строке планирования, затем выберите действие **Заказы на изготовление**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-167">Place the cursor on a relevant planning line, and then choose the **Make Orders** action.</span></span>  
4.  <span data-ttu-id="9eff6-168">В окне **Создание заказов на поставку** на экспресс-вкладке **Планирование заказов** в поле **Заказы на изготовление для** выберите один из следующих параметров.</span><span class="sxs-lookup"><span data-stu-id="9eff6-168">In the **Make Supply Orders** window, on the **Order Planning** FastTab, in the **Make Orders for** field, select one of the following options.</span></span>  

    |<span data-ttu-id="9eff6-169">Параметр</span><span class="sxs-lookup"><span data-stu-id="9eff6-169">Option</span></span>|<span data-ttu-id="9eff6-170">Описанием</span><span class="sxs-lookup"><span data-stu-id="9eff6-170">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9eff6-171">**Активная строка**</span><span class="sxs-lookup"><span data-stu-id="9eff6-171">**The Active Line**</span></span>|<span data-ttu-id="9eff6-172">Создайте заказ на поставку только для выбранной строки.</span><span class="sxs-lookup"><span data-stu-id="9eff6-172">Make a supply order only for the line where the cursor is placed.</span></span>|  
    |<span data-ttu-id="9eff6-173">**Активный заказ**</span><span class="sxs-lookup"><span data-stu-id="9eff6-173">**The Active Order**</span></span>|<span data-ttu-id="9eff6-174">Создайте заказы на поставку для всех строк в заказе, где установлен курсор.</span><span class="sxs-lookup"><span data-stu-id="9eff6-174">Make supply orders for all lines in the order where the cursor is placed.</span></span>|  
    |<span data-ttu-id="9eff6-175">**Все строки**</span><span class="sxs-lookup"><span data-stu-id="9eff6-175">**All Lines**</span></span>|<span data-ttu-id="9eff6-176">Создайте заказ на поставку для всех строк в окне **Планирование заказов**.</span><span class="sxs-lookup"><span data-stu-id="9eff6-176">Make supply orders for all lines in the **Order Planning** window.</span></span>|  

5.  <span data-ttu-id="9eff6-177">На экспресс-вкладке **Параметры** укажите тип заказов на поставку или строк журнала заявок, которые необходимо создать.</span><span class="sxs-lookup"><span data-stu-id="9eff6-177">On the **Options** FastTab, define what kind of supply orders, or requisition worksheet lines, should be made.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="9eff6-178">Параметры, выбранные в последний раз в окне **Создание заказов на поставку**, сохраняются под кодом пользователя и остаются неизменными до следующего обращения к окну.</span><span class="sxs-lookup"><span data-stu-id="9eff6-178">The settings you last made in the **Make Supply Orders** window will be saved under your user ID so that they are the same the next time you use the window.</span></span>  

6.  <span data-ttu-id="9eff6-179">Нажмите кнопку **OK**, чтобы создать предложенные заказы на поставку или строки журнала заявок.</span><span class="sxs-lookup"><span data-stu-id="9eff6-179">Choose the **OK** button to make the suggested supply orders or requisition worksheet lines.</span></span>  

<span data-ttu-id="9eff6-180">Теперь, создав соответствующие заказы на поставку, можно распланировать невыполненные требования.</span><span class="sxs-lookup"><span data-stu-id="9eff6-180">You have now planned for the unfulfilled demand by making respective supply orders.</span></span> <span data-ttu-id="9eff6-181">Данные конкретных рабочих процессов в окне **Планирование заказов** зависят от внутренних политик организации.</span><span class="sxs-lookup"><span data-stu-id="9eff6-181">Details about specific work flows when using the **Order Planning** window would depend on a company’s internal policies.</span></span>  

<span data-ttu-id="9eff6-182">По завершении процедур планирования в окне **Планирование заказов**, например определения альтернативного способа поставки заданного количества, можно переходить к созданию заказов на поставку для одной или нескольких строк планирования.</span><span class="sxs-lookup"><span data-stu-id="9eff6-182">When you have finished your planning work in the **Order Planning** window, for example defined an alternative way to supply the quantity, you can proceed to create supply orders for one or more of the planning lines.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="9eff6-183">Создаваемые заказы на поставку могут порождать новое зависимое требование, например для подчиненных производственных заказов. Поэтому, прежде чем переходить далее по списку, следует снова выбрать **Вычислить план**, чтобы выявить и разрешить новое требование.</span><span class="sxs-lookup"><span data-stu-id="9eff6-183">The supply orders you create may introduce new dependent demand, for example for underlying production orders, and you should therefore choose **Calculate Plan** again to find and resolve this before moving down the list.</span></span>  

## <a name="see-also"></a><span data-ttu-id="9eff6-184">См. также</span><span class="sxs-lookup"><span data-stu-id="9eff6-184">See Also</span></span>  
[<span data-ttu-id="9eff6-185">Планирование</span><span class="sxs-lookup"><span data-stu-id="9eff6-185">Planning</span></span>](production-planning.md)  
[<span data-ttu-id="9eff6-186">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="9eff6-186">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="9eff6-187">[Производство](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="9eff6-187">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="9eff6-188">Наличие</span><span class="sxs-lookup"><span data-stu-id="9eff6-188">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="9eff6-189">Покупки</span><span class="sxs-lookup"><span data-stu-id="9eff6-189">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="9eff6-190">[Сведения о проектировании: планирование поставок](design-details-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="9eff6-190">[Design Details: Supply Planning](design-details-supply-planning.md) </span></span>  
[<span data-ttu-id="9eff6-191">Рекомендации по настройке. Планирование поставок</span><span class="sxs-lookup"><span data-stu-id="9eff6-191">Setup Best Practices: Supply Planning</span></span>](setup-best-practices-supply-planning.md)  
<span data-ttu-id="9eff6-192">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9eff6-192">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
