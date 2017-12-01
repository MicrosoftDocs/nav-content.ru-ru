---
title: "О функциональности планирования"
description: "Система планирования учитывает все данные спроса и предложения, сравнивает результаты и генерирует предложения для соответствия между предложением и спросом."
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
ms.openlocfilehash: 37bc24dc5e90be24616f77a484dbe15b2bd051af
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="about-planning-functionality"></a><span data-ttu-id="e5b9e-103">О функциональности планирования</span><span class="sxs-lookup"><span data-stu-id="e5b9e-103">About Planning Functionality</span></span>
<span data-ttu-id="e5b9e-104">Система планирования учитывает все данные спроса и предложения, сравнивает результаты и генерирует предложения для соответствия между предложением и спросом.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-104">The planning system takes all demand and supply data into account, nets the results, and creates suggestions for balancing the supply to meet the demand.</span></span>  

<span data-ttu-id="e5b9e-105">Дополнительные сведения см. в разделе [Сведения о проектировании: планирование поставок](design-details-supply-planning.md).</span><span class="sxs-lookup"><span data-stu-id="e5b9e-105">For detailed information, see [Design Details: Supply Planning](design-details-supply-planning.md).</span></span>  

> [!NOTE]  
> <span data-ttu-id="e5b9e-106">Для всех полей, которые указаны в этом разделе, ознакомьтесь с всплывающей подсказкой, чтобы понять их функции.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-106">For all the fields that are mentioned in this topic, read the tooltip to understand their function.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="demand-and-supply"></a><span data-ttu-id="e5b9e-107">Спрос и предложение</span><span class="sxs-lookup"><span data-stu-id="e5b9e-107">Demand and Supply</span></span>  
<span data-ttu-id="e5b9e-108">Планирование включает два элемента: спрос и предложение.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-108">Planning has two elements: demand and supply.</span></span> <span data-ttu-id="e5b9e-109">Необходимо поддерживать их баланс, чтобы обеспечить своевременное и эффективное удовлетворение спроса.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-109">These must be held in balance to ensure that the demand is met in a timely and cost-efficient manner.</span></span>  

- <span data-ttu-id="e5b9e-110">Спрос - это общий термин, используемый для значительных потребностей, таких как заказ на продажу, сервисный заказ, потребность в компоненте со стороны производственного или сборочного заказа, исходящее перемещение, общий заказ или прогноз.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-110">Demand is the common term used for any kind of gross requirement such as a sales order, service order, component need from assembly or production orders, outbound transfer, blanket order or forecast.</span></span> <span data-ttu-id="e5b9e-111">Программа использует также некоторые другие технические типы спроса, - такие как отрицательное производство или заказ на покупку, отрицательные остатки и возврат покупки.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-111">In addition to these, the program allows some other technical types of demand - such as a negative production or purchase order, negative inventory, and purchase return.</span></span>  
- <span data-ttu-id="e5b9e-112">Предложение — это общий термин, используемый для любых пополнений, например склад, заказ на покупку, сборочный заказ, производственный заказ или входящее перемещение.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-112">Supply is the common word used for any kind of replenishment such as inventory, a purchase order, assembly order, production order, or inbound transfer.</span></span> <span data-ttu-id="e5b9e-113">Соответственно, могут быть отрицательные заказы на продажу или сервисные заказы, отрицательная потребность в компонентах или возврат проданного товара — все они в некотором смысле также представляют собой предложение.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-113">Correspondingly, there can be a negative sales or service order, negative component need or sales return – all of which in some way also represent supply.</span></span>  

<span data-ttu-id="e5b9e-114">Еще одна цель системы планирования - не допустить увеличения объема складского хранения сверх необходимого предела.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-114">Another goal of the planning system is to ensure that the inventory does not grow unnecessarily.</span></span> <span data-ttu-id="e5b9e-115">В случае уменьшения спроса система планирования предложит отложить, уменьшить количество или отменить существующие заказы на пополнение.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-115">In the case of decreasing demand, the planning system will suggest that you postpone, decrease in quantity, or cancel existing replenishment orders.</span></span>  

## <a name="planning-calculation"></a><span data-ttu-id="e5b9e-116">Расчет плана</span><span class="sxs-lookup"><span data-stu-id="e5b9e-116">Planning Calculation</span></span>  
<span data-ttu-id="e5b9e-117">Работа системы планирования зависит от ожидаемого и фактического клиентского спроса, а также от параметров повторного заказа товаров для склада.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-117">The planning system is driven by anticipated and actual customer demand, as well as inventory reordering parameters.</span></span> <span data-ttu-id="e5b9e-118">При расчета плана программа предлагает специальные действия («Указания») для пополнения запасов от поставщиков, перемещений между складами или производства.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-118">Running the planning calculation will result in the program suggesting specific actions (Action Messages) to take concerning possible replenishment from vendors, transfers between warehouses, or production.</span></span> <span data-ttu-id="e5b9e-119">Если заказы на пополнение уже существуют, может быть предложено увеличение или ускорение выполнения заказов для удовлетворения изменений спроса.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-119">If replenishment orders already exist, the suggested actions could be to increase or expedite the orders to meet the changes in demand.</span></span>  

<span data-ttu-id="e5b9e-120">В основе процедуры планирования лежит расчет брутто-нетто.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-120">The basis of the planning routine is in the gross-to-net calculation.</span></span> <span data-ttu-id="e5b9e-121">Чистые потребности определяют запуск спланированных заказов, которые планируются на основе данных маршрута (производимые товары) или времени упреждения в карточке товара (приобретаемые товары).</span><span class="sxs-lookup"><span data-stu-id="e5b9e-121">Net requirements drive planned order releases, which are scheduled based on the routing information (manufactured items) or the item card lead time (purchased items).</span></span> <span data-ttu-id="e5b9e-122">Количества в запускаемых спланированных заказах основаны на расчете плана и определяются параметрами, заданными в карточках отдельных товаров.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-122">Planned order release quantities are based on the planning calculation, and are affected by the parameters set on the individual item cards.</span></span>  

## <a name="planning-with-manual-transfer-orders"></a><span data-ttu-id="e5b9e-123">Планирование с использованием заказов на перемещение, созданных вручную</span><span class="sxs-lookup"><span data-stu-id="e5b9e-123">Planning with Manual Transfer Orders</span></span>
<span data-ttu-id="e5b9e-124">Как можно видеть в поле **Метод пополнения** карточки единицы хранения, систему планирования можно настроить так, чтобы она создавала заказы на перемещение, позволяющие сбалансировать спрос и предложение между складами.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-124">As you can see from the **Replenishment System** field on a SKU card, the planning system can be set up to create transfer orders to balance supply and demand across locations.</span></span>  

<span data-ttu-id="e5b9e-125">Кроме подобных автоматических заказов на перемещение, иногда может понадобиться выполнить общее перемещение определенных количеств товаров на другой склад независимо от существующего спроса.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-125">In addition to such automatic transfer orders, you may sometimes need to perform a general move of inventory quantities to another location, irrespective of existing demand.</span></span> <span data-ttu-id="e5b9e-126">Для этого можно вручную создать заказ на перемещение нужного количества.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-126">For this purpose you would manually create a transfer order for the quantity to move.</span></span> <span data-ttu-id="e5b9e-127">Чтобы система планирования наверняка не попыталась управлять этим созданным вручную заказом на перемещение, необходимо установить в поле **Гибкость планирования** строки (строк) перемещения значение "Нет".</span><span class="sxs-lookup"><span data-stu-id="e5b9e-127">To ensure that the planning system does not try to manipulate this manual transfer order, you must set the **Planning Flexibility** on the transfer line(s) to None.</span></span>  

<span data-ttu-id="e5b9e-128">Если нужно, чтобы система планирования откорректировала количества и даты заказа на перемещения в соответствии с существующим спросом, необходимо установить в поле **Гибкость планирования** значение по умолчанию "Неограниченно".</span><span class="sxs-lookup"><span data-stu-id="e5b9e-128">Contrarily, if you do want the planning system to adjust the transfer order quantities and dates to existing demand, you must set the **Planning Flexibility** field to the default value, Unlimited.</span></span>

## <a name="planning-parameters"></a><span data-ttu-id="e5b9e-129">Параметры планирования</span><span class="sxs-lookup"><span data-stu-id="e5b9e-129">Planning Parameters</span></span>  
<span data-ttu-id="e5b9e-130">Параметры планирования определяют, когда, в каком объеме и как пополнять запасы в зависимости от различных настроек в карточке товара (или в единице хранения - SKU), а также в настройках производства.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-130">The planning parameters control when, how much, and how to replenish based on the various settings on the item card (or stockkeeping unit - SKU), and the manufacturing setup.</span></span>  

<span data-ttu-id="e5b9e-131">В карточке товара или единицы хранения имеются следующие параметры планирования.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-131">The following planning parameters exist on the item or SKU card:</span></span>  

-   <span data-ttu-id="e5b9e-132">Буферный период</span><span class="sxs-lookup"><span data-stu-id="e5b9e-132">Dampener Period</span></span>  
-   <span data-ttu-id="e5b9e-133">Буферное количество</span><span class="sxs-lookup"><span data-stu-id="e5b9e-133">Dampener Quantity</span></span>  
-   <span data-ttu-id="e5b9e-134">Политика дозаказа</span><span class="sxs-lookup"><span data-stu-id="e5b9e-134">Reordering Policy</span></span>  
-   <span data-ttu-id="e5b9e-135">Точка дозаказа</span><span class="sxs-lookup"><span data-stu-id="e5b9e-135">Reorder Point</span></span>
-   <span data-ttu-id="e5b9e-136">Максимальный запас</span><span class="sxs-lookup"><span data-stu-id="e5b9e-136">Maximum Inventory</span></span>  
-   <span data-ttu-id="e5b9e-137">Допустимый избыток</span><span class="sxs-lookup"><span data-stu-id="e5b9e-137">Overflow Level</span></span>  
-   <span data-ttu-id="e5b9e-138">Горизонт планирования</span><span class="sxs-lookup"><span data-stu-id="e5b9e-138">Time Bucket</span></span>  
-   <span data-ttu-id="e5b9e-139">Период накопления лота</span><span class="sxs-lookup"><span data-stu-id="e5b9e-139">Lot Accumulation Period</span></span>  
-   <span data-ttu-id="e5b9e-140">Период перепланирования</span><span class="sxs-lookup"><span data-stu-id="e5b9e-140">Rescheduling Period</span></span>  
-   <span data-ttu-id="e5b9e-141">Кол-во для дозаказа</span><span class="sxs-lookup"><span data-stu-id="e5b9e-141">Reorder Quantity</span></span>  
-   <span data-ttu-id="e5b9e-142">Cтраховое время подготовки</span><span class="sxs-lookup"><span data-stu-id="e5b9e-142">Safety Lead Time</span></span>  
-   <span data-ttu-id="e5b9e-143">Кол-во страхового запаса</span><span class="sxs-lookup"><span data-stu-id="e5b9e-143">Safety Stock Quantity</span></span>  
-   <span data-ttu-id="e5b9e-144">Политика сборки</span><span class="sxs-lookup"><span data-stu-id="e5b9e-144">Assembly Policy</span></span>  
-   <span data-ttu-id="e5b9e-145">Политика производства</span><span class="sxs-lookup"><span data-stu-id="e5b9e-145">Manufacturing Policy</span></span>  

<span data-ttu-id="e5b9e-146">В карточке товара или единицы хранения имеются следующие модификаторы заказа.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-146">The following order modifiers exist on the item or SKU card:</span></span>  

-   <span data-ttu-id="e5b9e-147">Минимальное кол-во заказа</span><span class="sxs-lookup"><span data-stu-id="e5b9e-147">Minimum Order Quantity</span></span>  
-   <span data-ttu-id="e5b9e-148">Максимальное кол-во заказа</span><span class="sxs-lookup"><span data-stu-id="e5b9e-148">Maximum Order Quantity</span></span>  
-   <span data-ttu-id="e5b9e-149">Заказать несколько</span><span class="sxs-lookup"><span data-stu-id="e5b9e-149">Order Multiple</span></span>  

<span data-ttu-id="e5b9e-150">Поля настройки глобального планирования в окне **Производство - настройка** включают:</span><span class="sxs-lookup"><span data-stu-id="e5b9e-150">Global planning setup fields on the **Manufacturing Setup** window include:</span></span>  

-   <span data-ttu-id="e5b9e-151">Динамический код нижнего уровня</span><span class="sxs-lookup"><span data-stu-id="e5b9e-151">Dynamic Low-Level Code</span></span>  
-   <span data-ttu-id="e5b9e-152">Текущий прогноз производства</span><span class="sxs-lookup"><span data-stu-id="e5b9e-152">Current Production Forecast</span></span>  
-   <span data-ttu-id="e5b9e-153">Исп. прогноз по складам</span><span class="sxs-lookup"><span data-stu-id="e5b9e-153">Use Forecast on Locations</span></span>  
-   <span data-ttu-id="e5b9e-154">Страховой запас времени подготовки по умолчанию</span><span class="sxs-lookup"><span data-stu-id="e5b9e-154">Default Safety Lead Time</span></span>  
-   <span data-ttu-id="e5b9e-155">Общий допустимый избыток</span><span class="sxs-lookup"><span data-stu-id="e5b9e-155">Blank Overflow Level</span></span>  
-   <span data-ttu-id="e5b9e-156">Совместный расчет MPS/MRP</span><span class="sxs-lookup"><span data-stu-id="e5b9e-156">Combined MPS/MRP Calculation</span></span>   
-   <span data-ttu-id="e5b9e-157">Компоненты по складам</span><span class="sxs-lookup"><span data-stu-id="e5b9e-157">Components at Location</span></span>  
-   <span data-ttu-id="e5b9e-158">Буферный период по умолчанию</span><span class="sxs-lookup"><span data-stu-id="e5b9e-158">Default Dampener Period</span></span>  
-   <span data-ttu-id="e5b9e-159">Буферное количество по умолчанию</span><span class="sxs-lookup"><span data-stu-id="e5b9e-159">Default Dampener Quantity</span></span>  

<span data-ttu-id="e5b9e-160">Для получения дополнительной информации см. раздел [Сведения о проектировании: параметры планирования](design-details-planning-parameters.md)</span><span class="sxs-lookup"><span data-stu-id="e5b9e-160">For more information, see [Design Details: Planning Parameters](design-details-planning-parameters.md)</span></span>  

## <a name="other-important-planning-fields"></a><span data-ttu-id="e5b9e-161">Другие важные поля планирования</span><span class="sxs-lookup"><span data-stu-id="e5b9e-161">Other Important Planning Fields</span></span>
### <a name="planning-flexibility"></a><span data-ttu-id="e5b9e-162">Гибкость планирования</span><span class="sxs-lookup"><span data-stu-id="e5b9e-162">Planning Flexibility</span></span>
<span data-ttu-id="e5b9e-163">В большей часть заказов на поставку, таких как производственные заказы, можно выбрать значение **Неограниченно** или **Нет** в поле **Гибкость планирования** в строках.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-163">On most supply orders, such as production orders, you can select **Unlimited** or **None** in the **Planning Flexibility** field on the lines.</span></span>

<span data-ttu-id="e5b9e-164">Это указывает, учитывается ли поставка, представленная строкой в производственном заказе, системой планирования при расчете указаний.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-164">This specifies whether the supply represented by the production order line is considered by the planning system when calculating action messages.</span></span>
<span data-ttu-id="e5b9e-165">Если в данном поле указан параметр **Неограниченно**, система планирования учитывает строку при расчете указаний.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-165">If the field contains **Unlimited**, then the planning system includes the line when calculating action messages.</span></span> <span data-ttu-id="e5b9e-166">Если в поле указано **Нет**, строка является фиксированной и не подлежит изменению, и система планирования не учитывает ее при расчете указаний.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-166">If the field contains **None**, then the line is firm and unchangeable, and the planning system does not include the line when calculating action messages.</span></span>

### <a name="warning"></a><span data-ttu-id="e5b9e-167">Предупреждение</span><span class="sxs-lookup"><span data-stu-id="e5b9e-167">Warning</span></span>
<span data-ttu-id="e5b9e-168">Информационное поле **Предупреждение** в окне **Журнал планирования** информирует о любых строках планирования, созданных для нетипичной ситуации, с текстом, который пользователь может выбрать для ознакомления с дополнительной информацией.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-168">The **Warning** information field in the **Planning Worksheet** window informs you of any planning line created for an unusual situation with a text, which the user can choose to read additional information.</span></span> <span data-ttu-id="e5b9e-169">Существуют следующие типы предупреждений:</span><span class="sxs-lookup"><span data-stu-id="e5b9e-169">The following warning types exist:</span></span>

- <span data-ttu-id="e5b9e-170">Экстренный,</span><span class="sxs-lookup"><span data-stu-id="e5b9e-170">Emergency</span></span>
- <span data-ttu-id="e5b9e-171">Исключение,</span><span class="sxs-lookup"><span data-stu-id="e5b9e-171">Exception</span></span>
- <span data-ttu-id="e5b9e-172">Внимание!</span><span class="sxs-lookup"><span data-stu-id="e5b9e-172">Attention</span></span>
- <span data-ttu-id="e5b9e-173">Экстренный,</span><span class="sxs-lookup"><span data-stu-id="e5b9e-173">Emergency</span></span>

<span data-ttu-id="e5b9e-174">Экстренное предупреждение отображается в двух случаях:</span><span class="sxs-lookup"><span data-stu-id="e5b9e-174">The emergency warning is displayed in two situations:</span></span>

- <span data-ttu-id="e5b9e-175">отрицательный остаток запасов на планируемую дату начала;</span><span class="sxs-lookup"><span data-stu-id="e5b9e-175">The inventory is negative on the planning starting date.</span></span>
- <span data-ttu-id="e5b9e-176">поставка датирована прошедшим числом или существуют события, в результате которых возникли требования.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-176">Back-dated supply or demand events exist.</span></span>

<span data-ttu-id="e5b9e-177">В случае отрицательного остатка по запасам товара на планируемую дату начала, система планирования предложит экстренный заказ на поставку с количеством, равным отрицательному остатку, и поставкой на планируемую дату начала.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-177">If an item’s inventory is negative on the planning starting date, the planning system suggests an emergency supply order for the negative quantity to arrive on the planning starting date.</span></span> <span data-ttu-id="e5b9e-178">В тексте предупреждения указывается дата начала и количество для экстренного заказа.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-178">The warning text states the starting date and the quantity of the emergency order.</span></span>

<span data-ttu-id="e5b9e-179">Любые строки документа с датами завершения до планируемой даты начала объединяются в один экстренный заказ на поставку товара с доставкой на планируемую дату начала.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-179">Any document lines with due dates before the planning starting date are consolidated into one emergency supply order for the item to arrive on the planning starting date.</span></span>

### <a name="exception"></a><span data-ttu-id="e5b9e-180">Исключение,</span><span class="sxs-lookup"><span data-stu-id="e5b9e-180">Exception</span></span>
<span data-ttu-id="e5b9e-181">Предупреждение об исключении отображается в случае, когда прогнозируемые доступные запасы оказываются ниже количества страхового запаса.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-181">The exception warning is displayed if the projected available inventory drops below the safety stock quantity.</span></span>

<span data-ttu-id="e5b9e-182">Система планирования предложит заказ на поставку для выполнения требования к сроку выполнения.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-182">The planning system will suggest a supply order to meet the demand on its due date.</span></span> <span data-ttu-id="e5b9e-183">В тексте предупреждения указывается количество страхового запаса товара и дата на которую произошло данное нарушение.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-183">The warning text states the item’s safety stock quantity and the date on which it is violated.</span></span>

<span data-ttu-id="e5b9e-184">Нарушение требования к уровню страхового запаса считается причиной исключения, так как в случае правильной настройки точки повтора заказа такая ситуация возникать не должна.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-184">Violating the safety stock level is considered an exception because it should not occur if the reorder point has been set correctly.</span></span>

> [!NOTE]
> <span data-ttu-id="e5b9e-185">Поставка в строках планирования с предупреждениями об исключениях обычно не изменяется в соответствии с параметрами планирования.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-185">Supply on planning lines with Exception warnings is normally not modified according to planning parameters.</span></span> <span data-ttu-id="e5b9e-186">Вместо этого, система планирования только предлагает поставку для покрытия конкретного требуемого количества.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-186">Instead, the planning system only suggests a supply to cover the exact demand quantity.</span></span> <span data-ttu-id="e5b9e-187">Однако, можно настроить запуск планирования для строк планирования, которые следует учитывать с некоторыми предупреждениями.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-187">However, you can set the planning run up to respect certain planning parameters for planning lines with certain warnings.</span></span> <span data-ttu-id="e5b9e-188">Дополнительные сведения см. в пункте "Учет параметров планирования для предупреждений об исключениях" в разделе "Расчет плана - журнал</span><span class="sxs-lookup"><span data-stu-id="e5b9e-188">For more information, see “Respect Planning Parameters for Exception Warnings” in Calculate Plan - Plan.</span></span> <span data-ttu-id="e5b9e-189">планов.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-189">Wksh.</span></span>

### <a name="attention"></a><span data-ttu-id="e5b9e-190">Внимание!</span><span class="sxs-lookup"><span data-stu-id="e5b9e-190">Attention</span></span>
<span data-ttu-id="e5b9e-191">Предупреждение о необходимости обратить на что-либо внимание отображается в двух случаях:</span><span class="sxs-lookup"><span data-stu-id="e5b9e-191">The attention warning is displayed in two situations:</span></span>

- <span data-ttu-id="e5b9e-192">планируемая дата начала наступает раньше рабочей даты;</span><span class="sxs-lookup"><span data-stu-id="e5b9e-192">The planning starting date is earlier than the work date.</span></span>
- <span data-ttu-id="e5b9e-193">в строке планирования предлагается изменить выпущенный заказ на покупку или производственный заказ.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-193">The planning line suggests to change a released purchase or production order.</span></span>

> [!NOTE]
> <span data-ttu-id="e5b9e-194">В строках планирования с предупреждениями поле **Принять указания** не выбрано, так как ожидается, что планировщик дополнительно изучит эти строки перед составлением плана.</span><span class="sxs-lookup"><span data-stu-id="e5b9e-194">In planning lines with warnings, the **Accept Action Message** field is not selected, because the planner is expected to further investigate these lines before carrying out the plan.</span></span>

## <a name="see-also"></a><span data-ttu-id="e5b9e-195">См. также</span><span class="sxs-lookup"><span data-stu-id="e5b9e-195">See Also</span></span>  
[<span data-ttu-id="e5b9e-196">Сведения о проектировании: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="e5b9e-196">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)  
<span data-ttu-id="e5b9e-197">[Планирование](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="e5b9e-197">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="e5b9e-198">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="e5b9e-198">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="e5b9e-199">[Производство](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="e5b9e-199">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="e5b9e-200">Наличие</span><span class="sxs-lookup"><span data-stu-id="e5b9e-200">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="e5b9e-201">Покупки</span><span class="sxs-lookup"><span data-stu-id="e5b9e-201">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="e5b9e-202">Рекомендации по настройке: планирование поставок</span><span class="sxs-lookup"><span data-stu-id="e5b9e-202">Setup Best Practices: Supply Planning</span></span>](setup-best-practices-supply-planning.md)  
<span data-ttu-id="e5b9e-203">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="e5b9e-203">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

