---
title: "Сведения о проектировании — внутренние складские потоки"
description: "Перемещение товаров между ячейками на складах компании заключается в комплектовании компонентов и откладывании конечных товаров для заказов на сборку или производственных запасов и специальных перемещений, таких как пополнение ячейки, без связи с исходными документами."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: ee1a7aaa1c4b8cf2ce4c37e904cbe15e4faaea8a
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-internal-warehouse-flows"></a><span data-ttu-id="e4529-103">Сведения о проектировании: внутренние складские потоки</span><span class="sxs-lookup"><span data-stu-id="e4529-103">Design Details: Internal Warehouse Flows</span></span>
<span data-ttu-id="e4529-104">Перемещение товаров между ячейками на складах компании заключается в комплектовании компонентов и откладывании конечных товаров для заказов на сборку или производственных запасов и специальных перемещений, таких как пополнение ячейки, без связи с исходными документами.</span><span class="sxs-lookup"><span data-stu-id="e4529-104">The flow of items between bins at a company location centers on picking components and putting away end items for assembly or production orders and ad-hoc movements, such as bin replenishments, without a relation to source documents.</span></span> <span data-ttu-id="e4529-105">Масштаб и природа включенных действий варьируется между базовым и расширенным складированием.</span><span class="sxs-lookup"><span data-stu-id="e4529-105">The scope and nature of the involved activities vary between basic and advanced warehousing.</span></span>  

 <span data-ttu-id="e4529-106">Некоторые внутренние потоки перекрываются с входящими или исходящими потоками.</span><span class="sxs-lookup"><span data-stu-id="e4529-106">Some internal flows overlap with inbound or outbound flows.</span></span> <span data-ttu-id="e4529-107">Часть такого перекрытия показана на шагах 4 и 5 графических схем для расширенных исходящих и входящих потоков соответственно.</span><span class="sxs-lookup"><span data-stu-id="e4529-107">Some of this overlap is shown as steps 4 and 5 in the graphical diagrams for advanced inbound and outbound flows respectively.</span></span> <span data-ttu-id="e4529-108">Дополнительные сведения см. в разделе [Сведения о проектировании: входящий складской поток](design-details-outbound-warehouse-flow.md).</span><span class="sxs-lookup"><span data-stu-id="e4529-108">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span></span>  

## <a name="internal-flows-in-basic-warehousing"></a><span data-ttu-id="e4529-109">Внутренние потоки в базовых функциях склада</span><span class="sxs-lookup"><span data-stu-id="e4529-109">Internal Flows in Basic Warehousing</span></span>  
 <span data-ttu-id="e4529-110">В базовой конфигурации склада поток товаров между ячейками в пределах организации основывается на подборе компонентов и размещении конечных товаров для производственных заказов или заказов на сборку, а также специальных перемещениях, таких как пополнения ячеек, без связи с документами-источниками.</span><span class="sxs-lookup"><span data-stu-id="e4529-110">In basic warehouse configuration, the flow of items between bins inside the company centers on picking component and putting away end items for production or assembly orders and ad-hoc movements, such as bin replenishments, without relation to source documents.</span></span>  

### <a name="flows-to-and-from-production"></a><span data-ttu-id="e4529-111">Перемещение в производство и из него</span><span class="sxs-lookup"><span data-stu-id="e4529-111">Flows to and from Production</span></span>  
 <span data-ttu-id="e4529-112">Основная интеграция между производственными заказами и действиями основного складирования представлена возможностью подбирать производственные компоненты в окнах **Подбор запасов** или **Перемещение запасов**.</span><span class="sxs-lookup"><span data-stu-id="e4529-112">The main integration between production orders and basic warehouse activities is represented by the ability to pick production components with the **Inventory Pick** or the **Inventory Movement** windows.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e4529-113">В окне **Подбор запасов** потребление компонентов учитывается вместе с учетом подбора.</span><span class="sxs-lookup"><span data-stu-id="e4529-113">In the **Inventory Pick** window, the component consumption is posted together with the pick posting.</span></span> <span data-ttu-id="e4529-114">С помощью окна **Перемещение запасов** можно зарегистрировать только коррекции ячеек, учет книги товаров не выполняется.</span><span class="sxs-lookup"><span data-stu-id="e4529-114">By using the **Inventory Movement** window, only bin adjustments are registered, no item ledger posting occurs.</span></span>  

 <span data-ttu-id="e4529-115">В дополнение к обработке компонентов при интеграции предоставляется возможность размещать произведенные товары с помощью окна **Размещение запасов**.</span><span class="sxs-lookup"><span data-stu-id="e4529-115">In addition to component handling, the integration is represented by the ability to put produced items away with the **Inventory Put-away** window.</span></span>  

 <span data-ttu-id="e4529-116">**Код входящей ячейки**, **Код ячейки готовой продукции** и **Код ячейки комплектования** в карточке склада или станции/карточках рабочего центра определяют потоки по умолчанию в производственные области и из них.</span><span class="sxs-lookup"><span data-stu-id="e4529-116">The **To-Production Bin Code**, **From-Production Bin Code**, and **Open Shop Floor Bin Code** fields on the location card or the machine/work center cards define default flows to and from production areas.</span></span>  

 <span data-ttu-id="e4529-117">Дополнительные сведения о списании потребления компонентов из входящей производственной ячейки или ячейки общего доступа см. в разделе "Списание производственных компонентов на складе" этой статьи.</span><span class="sxs-lookup"><span data-stu-id="e4529-117">For more information about how component consumption is flushed from the To-Production or Open Shop Floor bins, see the “Flushing Production Components in the Warehouse” section in this topic.</span></span>  

### <a name="flows-to-and-from-assembly"></a><span data-ttu-id="e4529-118">Перемещение в сборку и из нее</span><span class="sxs-lookup"><span data-stu-id="e4529-118">Flows to and from Assembly</span></span>  
 <span data-ttu-id="e4529-119">Основная интеграция между заказами на сборку и действиями базового складирования представлена возможностью перемещать компоненты сборки в область сборки.</span><span class="sxs-lookup"><span data-stu-id="e4529-119">The main integration between assembly orders and basic warehouse activities is represented by the ability to move assembly components to the assembly area.</span></span>  

 <span data-ttu-id="e4529-120">Несмотря на то что конкретной складской функциональности для размещения сборочных элементов не существует, можно настроить код ячейки в заголовке заказа на сборку на ячейку размещения по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="e4529-120">While no specific warehouse functionality exists for putting assembly items away, the bin code on the assembly order header may be set to a default put-away bin.</span></span> <span data-ttu-id="e4529-121">В результате учет заказа на сборку выполняется так же, как учет размещения.</span><span class="sxs-lookup"><span data-stu-id="e4529-121">Posting the assembly order then functions like posting a put-away.</span></span> <span data-ttu-id="e4529-122">Складской операцией по перемещению сборочных элементов на склад можно управлять в окне **Внутреннее перемещение** без связи с заказом на сборку.</span><span class="sxs-lookup"><span data-stu-id="e4529-122">The warehouse activity to move assembly items into the warehouse can be managed in the **Internal Movement** window, with no relation to the assembly order.</span></span>  

 <span data-ttu-id="e4529-123">Существуют следующие потоки сборки.</span><span class="sxs-lookup"><span data-stu-id="e4529-123">The following assembly flows exist.</span></span>  

|<span data-ttu-id="e4529-124">Рабочий процесс</span><span class="sxs-lookup"><span data-stu-id="e4529-124">Flow</span></span>|<span data-ttu-id="e4529-125">Описанием</span><span class="sxs-lookup"><span data-stu-id="e4529-125">Description</span></span>|  
|----------|---------------------------------------|  
|<span data-ttu-id="e4529-126">Сборка на склад</span><span class="sxs-lookup"><span data-stu-id="e4529-126">Assemble-to-stock</span></span>|<span data-ttu-id="e4529-127">Компоненты необходимы для заказа на сборку, результат которого хранится на складе.</span><span class="sxs-lookup"><span data-stu-id="e4529-127">The components are needed on an assembly order where the output is stored in the warehouse.</span></span><br /><br /> <span data-ttu-id="e4529-128">Управление этим складским потоком осуществляется в окне **Перемещение запасов**.</span><span class="sxs-lookup"><span data-stu-id="e4529-128">This warehouse flow is managed in the **Inventory Movement** window.</span></span> <span data-ttu-id="e4529-129">Одна строка подбора определяет место подбора компонентов.</span><span class="sxs-lookup"><span data-stu-id="e4529-129">One take line specifies where to take the components.</span></span> <span data-ttu-id="e4529-130">Одна строка размещения определяет место размещения компонентов.</span><span class="sxs-lookup"><span data-stu-id="e4529-130">One place line specifies where to place the components.</span></span>|  
|<span data-ttu-id="e4529-131">Сборка на заказ</span><span class="sxs-lookup"><span data-stu-id="e4529-131">Assemble-to-order</span></span>|<span data-ttu-id="e4529-132">Компоненты необходимы для заказа на сборку, связанного с заказом на продажу, который отгружается при сборке проданного товара.</span><span class="sxs-lookup"><span data-stu-id="e4529-132">The components are needed on an assembly order that is linked to a sales order that is shipped when the sold item is assembled.</span></span>|  

> [!NOTE]  
>  <span data-ttu-id="e4529-133">Если товары собираются в заказ, подбор запасов связанных заказов на продажу приводит к перемещению запасов для всех компонентов сборки, а не только для проданного товара, как при отгрузке товаров в запасах.</span><span class="sxs-lookup"><span data-stu-id="e4529-133">If items are assembled to order, then the inventory pick of the linked sales order triggers an inventory movement for all the involved assembly components, not just for the sold item as when shipping inventory items.</span></span>  

 <span data-ttu-id="e4529-134">Поля **Код входящей сборочн. ячейки**, **Код исходящей сборочн. ячейки** и **Код ячейки сборки на заказ** в карточке склада определяет потоки в области сборки и из них по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="e4529-134">The **To-Assembly Bin Code**, **From-Assembly Bin Code**, and **Asm.-to-Order Shpt. Bin Code** fields on the location card define default flows to and from assembly areas.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e4529-135">Поле **Код ячейки сборки на заказ** выступает в качестве исходящей сборочной ячейки в сценариях сборки на заказ.</span><span class="sxs-lookup"><span data-stu-id="e4529-135">The **Asm.-to-Order Shpt. Bin Code** field functions as the from-assembly bin in assemble-to-order scenarios.</span></span>  

### <a name="ad-hoc-movements"></a><span data-ttu-id="e4529-136">Специальные перемещения</span><span class="sxs-lookup"><span data-stu-id="e4529-136">Ad-Hoc Movements</span></span>  
 <span data-ttu-id="e4529-137">В базовых конфигурациях склада перемещение товаров из ячейки в ячейку без связи с документами-источниками выполняется в окне **Внутреннее перемещение**, которое используется вместе с окном **Перемещение запасов**.</span><span class="sxs-lookup"><span data-stu-id="e4529-137">In basic warehousing, the movement of items from bin to bin without relation to source documents is performed in the **Internal Movement** window, which functions together with the **Inventory Movement** window.</span></span>  

 <span data-ttu-id="e4529-138">Еще одним способом перемещения специальных товаров между ячейками является учет положительных операций в поле **Код новой ячейки** в окне **Журнал реклассификации товаров**.</span><span class="sxs-lookup"><span data-stu-id="e4529-138">Another way to move items ad hoc between bins is to post positive entries in the **New Bin Code** field in the **Item Reclass. Journal** window.</span></span>  

## <a name="internal-flows-in-advanced-warehousing"></a><span data-ttu-id="e4529-139">Внутренние потоки в расширенных функциях склада</span><span class="sxs-lookup"><span data-stu-id="e4529-139">Internal Flows in Advanced Warehousing</span></span>  
 <span data-ttu-id="e4529-140">В расширенных конфигурациях склада поток товаров между ячейками в пределах организации основывается на подборе компонентов и размещении конечных товаров для производственных заказов, а также подборе компонентов для заказов на сборку.</span><span class="sxs-lookup"><span data-stu-id="e4529-140">In advanced warehouse configurations, the flow of items between bins inside the company centers on picking component and putting away end items for production orders and picking components for assembly orders.</span></span> <span data-ttu-id="e4529-141">Кроме того, внутренние потоки представляют собой специальные передвижения, например пополнение ячеек, и не связаны с документами-источниками.</span><span class="sxs-lookup"><span data-stu-id="e4529-141">In addition, internal flows occur as ad-hoc movements, such as bin replenishments, without relation to source documents.</span></span>  

### <a name="flows-to-and-from-production"></a><span data-ttu-id="e4529-142">Перемещение в производство и из него</span><span class="sxs-lookup"><span data-stu-id="e4529-142">Flows To and From Production</span></span>  
 <span data-ttu-id="e4529-143">Основная интеграция между производственными заказами и действиями расширенного складирования представлена возможностью подбора производственных компонентов в окне **Складской подбор** и **Журнал подбора**, а также возможностью размещать произведенные товары в окне **Внутреннее складское размещение**.</span><span class="sxs-lookup"><span data-stu-id="e4529-143">The main integration between production orders and advanced warehouse activities is represented by the ability to pick production components, in the **Warehouse Pick** window and the **Pick Worksheet** window, and the ability to put produced items away with the **Whse. Internal-Put-away** window.</span></span>  

 <span data-ttu-id="e4529-144">Еще одна точка интеграции предоставляется в окне **Складское перемещение**, а также в окне "Журнал перемещения", в котором можно разместить компоненты и взять произведенные товары для запущенных производственных заказов.</span><span class="sxs-lookup"><span data-stu-id="e4529-144">Another integration point in production is provided with the **Warehouse Movement** window, together with the Movement Worksheet window, which enables you to place components and take produced items for released production orders.</span></span>  

 <span data-ttu-id="e4529-145">**Код входящей ячейки**, **Код ячейки готовой продукции** и **Код ячейки комплектования** в карточке склада или станции/карточках рабочего центра определяют потоки по умолчанию в производственные области и из них.</span><span class="sxs-lookup"><span data-stu-id="e4529-145">The **To-Production Bin Code**, **From-Production Bin Code**, and **Open Shop Floor Bin Code** fields on the location card or the machine/work center cards define default flows to and from production areas.</span></span>  

 <span data-ttu-id="e4529-146">Дополнительные сведения о списании потребления компонентов из входящей производственной ячейки или ячейки общего доступа см. в разделе "Списание производственных компонентов на складе" этой статьи.</span><span class="sxs-lookup"><span data-stu-id="e4529-146">For more information about how component consumption is flushed from the To-Production or Open Shop Floor Bins, see the “Flushing Production Components in the Warehouse” section in this topic.</span></span>  

### <a name="flows-to-and-from-assembly"></a><span data-ttu-id="e4529-147">Перемещение в сборку и из нее</span><span class="sxs-lookup"><span data-stu-id="e4529-147">Flows to and from Assembly</span></span>  
 <span data-ttu-id="e4529-148">Основная интеграция между заказами на сборку и действиями расширенного складирования представлена возможностью подбирать компоненты сборки в окне **Складской подбор** и **Журнал подбора**.</span><span class="sxs-lookup"><span data-stu-id="e4529-148">The main integration between assembly orders and advanced warehouse activities is represented by the ability to pick assembly components, both with the **Warehouse Pick** window and the **Pick Worksheet** window.</span></span> <span data-ttu-id="e4529-149">Эта функциональность работает так же, как при подборе компонентов для производственных заказов.</span><span class="sxs-lookup"><span data-stu-id="e4529-149">This functionality works just like when picking components for production orders.</span></span>  

 <span data-ttu-id="e4529-150">Несмотря на то что конкретной складской функциональности для размещения сборочных элементов не существует, можно настроить код ячейки в заголовке заказа на сборку на ячейку размещения по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="e4529-150">While no specific warehouse functionality exists for putting assembly items away, the bin code on the assembly order header may be set to a default put-away bin.</span></span> <span data-ttu-id="e4529-151">В результате учет заказа на сборку выполняется так же, как учет размещения.</span><span class="sxs-lookup"><span data-stu-id="e4529-151">Posting the assembly order then functions like posting a put-away.</span></span> <span data-ttu-id="e4529-152">Складской операцией по перемещению сборочных элементов на склад можно управлять в окне **Журнал перемещения** или окне **Внутреннее размещение склада** без связи с заказом на сборку.</span><span class="sxs-lookup"><span data-stu-id="e4529-152">The warehouse activity to move assembly items into the warehouse can be managed in the **Movement Worksheet** window or the **Whse. Internal Put-away** window, with no relation to the assembly order.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e4529-153">Если товары собираются в заказ, расходная накладная связанных заказов на продажу приводит к складскому подбору для всех компонентов сборки, а не только для проданного товара, как при отгрузке товаров в запасах.</span><span class="sxs-lookup"><span data-stu-id="e4529-153">If items are assembled to order, then the warehouse shipment of the linked sales order triggers a warehouse pick for all the involved assembly components, not just for the sold item as when shipping inventory items.</span></span>  

 <span data-ttu-id="e4529-154">Поля **Код входящей сборочн. ячейки** и **Код исходящей сборочн. ячейки** в карточке склада определяет потоки в области сборки и из них по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="e4529-154">The **To-Assembly Bin Code** and **From-Assembly Bin Code** fields on the location card define default flows to and from assembly areas.</span></span>  

### <a name="ad-hoc-movements"></a><span data-ttu-id="e4529-155">Специальные перемещения</span><span class="sxs-lookup"><span data-stu-id="e4529-155">Ad-Hoc Movements</span></span>  
 <span data-ttu-id="e4529-156">В расширенных конфигурациях склада перемещением товаров из ячейки в ячейку без связи с документами-источниками можно управлять в окне **Журнал перемещения** и окне "Складское перемещение".</span><span class="sxs-lookup"><span data-stu-id="e4529-156">In advanced warehousing, the movement of items from bin to bin without relation to source documents is managed in the **Movement Worksheet** window and registered in the Warehouse Movement window.</span></span>  

## <a name="flushing-production-components-in-the-warehouse"></a><span data-ttu-id="e4529-157">Списание производственных компонентов на складе</span><span class="sxs-lookup"><span data-stu-id="e4529-157">Flushing Production Components in the Warehouse</span></span>  
 <span data-ttu-id="e4529-158">Если компоненты настроены в карточке товара и подбираются с помощью складских подборов, они учитываются как использованные в производственном заказе при регистрации складского подбора.</span><span class="sxs-lookup"><span data-stu-id="e4529-158">If set up on the item card, components picked with warehouse picks are posted as consumed by the production order when the warehouse pick is registered.</span></span> <span data-ttu-id="e4529-159">С помощью метода **Подбор + прямой** и метода списания **Подбор + обратный** регистрация подбора начинает связанный процесс учета потребления, когда выполняется первая операция или заканчивается последняя операция, соответственно.</span><span class="sxs-lookup"><span data-stu-id="e4529-159">By using the **Pick + Forward** method and the **Pick + Backward** flushing method, the pick registration triggers the related consumption posting when the first operation starts or when the last operation finishes, respectively.</span></span>  

 <span data-ttu-id="e4529-160">Рассмотрите следующий сценарий на основе демонстрационной базы данных [!INCLUDE[d365fin](includes/d365fin_md.md)], склад БЕЛЫЙ.</span><span class="sxs-lookup"><span data-stu-id="e4529-160">Consider the following scenario based on the [!INCLUDE[d365fin](includes/d365fin_md.md)] demonstration database, WHITE location.</span></span>  

 <span data-ttu-id="e4529-161">Существует производственный заказ на 15 шт. товара LS-100.</span><span class="sxs-lookup"><span data-stu-id="e4529-161">A production order for 15 PCS of item LS-100 exists.</span></span> <span data-ttu-id="e4529-162">Некоторые из товаров в списке компонентов необходимо списывать вручную в журнале потребления, тогда как другие товары в списке можно подобрать и списать автоматически с помощью метода списания **Подбор + обратный**.</span><span class="sxs-lookup"><span data-stu-id="e4529-162">Some of the items on the component list must be flushed manually in a consumption journal, and other items on the list can be picked and flushed automatically using the **Pick + Backward** flushing method.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e4529-163">**Подбор + прямой** работает, только если вторая операция строки производственного маршрута использует код связи маршрута.</span><span class="sxs-lookup"><span data-stu-id="e4529-163">**Pick + Forward** only works if the second production routing line operation uses a routing link code.</span></span> <span data-ttu-id="e4529-164">Выпуск планового производственного заказа инициирует прямое списание компонентов, для которых задано значение **Подбор + прямой**.</span><span class="sxs-lookup"><span data-stu-id="e4529-164">Releasing a planned production order initiates forward flushing of components set to **Pick + Forward**.</span></span> <span data-ttu-id="e4529-165">Однако списание невозможно выполнить, пока не будет зарегистрирован подбор компонентов, который, в свою очередь, может быть выполнен, только если выпущен заказ.</span><span class="sxs-lookup"><span data-stu-id="e4529-165">However, the flushing cannot take place until the pick of the components is registered, which again can only take place when the order is released.</span></span>  

 <span data-ttu-id="e4529-166">Следующие шаги описывают действия разных пользователей и соответствующую реакцию.</span><span class="sxs-lookup"><span data-stu-id="e4529-166">The following steps describe the involved actions by different users and the related response:</span></span>  

1.  <span data-ttu-id="e4529-167">Контролер сборочного цеха выпускает заказ.</span><span class="sxs-lookup"><span data-stu-id="e4529-167">The shop floor supervisor releases the production order.</span></span> <span data-ttu-id="e4529-168">Товары с методом списания **Вперед** и без кода связи маршрута вычитаются из ячейка общего доступа.</span><span class="sxs-lookup"><span data-stu-id="e4529-168">Items with **Forward** flushing method and no routing link code are deducted from the open shop floor bin.</span></span>  
2.  <span data-ttu-id="e4529-169">Контролер цеха нажимает кнопку **Создать складской подбор** на производственном заказе.</span><span class="sxs-lookup"><span data-stu-id="e4529-169">The shop floor supervisor chooses the **Create Warehouse Pick** button on the production order.</span></span> <span data-ttu-id="e4529-170">Создается документ складского подбора для подбора товаров с методами списания **Ручной**, **Подбор + обратный** и **Подбор + прямой**.</span><span class="sxs-lookup"><span data-stu-id="e4529-170">A warehouse pick document is created pick for items with **Manual**, **Pick + Backward**, and **Pick + Forward** flushing methods.</span></span> <span data-ttu-id="e4529-171">Эти товары помещаются во входящую производственную ячейку.</span><span class="sxs-lookup"><span data-stu-id="e4529-171">These items are placed in the To-Production bin.</span></span>  
3.  <span data-ttu-id="e4529-172">Диспетчер склада присваивает подборы работнику склада.</span><span class="sxs-lookup"><span data-stu-id="e4529-172">The warehouse manager assigns the picks to a warehouse worker.</span></span>  
4.  <span data-ttu-id="e4529-173">Складской сотрудник подбирает товары из соответствующих ячеек и помещает их во входящей производственной ячейке или ячейке, заданной для складского подбора, которая может являться ячейкой производственного центра или машинного центра.</span><span class="sxs-lookup"><span data-stu-id="e4529-173">The warehouse worker picks the items from appropriate bins and places them in the To-Production bin or in the bin specified on the warehouse pick, which may be a work center or machine center bin.</span></span>  
5.  <span data-ttu-id="e4529-174">Сотрудник склада регистрирует подбор.</span><span class="sxs-lookup"><span data-stu-id="e4529-174">The warehouse worker registers the pick.</span></span> <span data-ttu-id="e4529-175">Количество вычитается из ячеек подбора и добавляется в ячейку потребления.</span><span class="sxs-lookup"><span data-stu-id="e4529-175">The quantity is subtracted from the pick bins and added to the consumption bin.</span></span> <span data-ttu-id="e4529-176">Поле **Подобр. кол-во** в списке компонентов для всех подобранных товаров обновляется.</span><span class="sxs-lookup"><span data-stu-id="e4529-176">The **Qty. Picked** field on the component list for all picked items is updated.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="e4529-177">Можно использовать только количество, которое подобрано.</span><span class="sxs-lookup"><span data-stu-id="e4529-177">Only the quantity that is picked can be consumed.</span></span>  

6.  <span data-ttu-id="e4529-178">Оператор станка уведомляет менеджера по производству, что время завершения истекло.</span><span class="sxs-lookup"><span data-stu-id="e4529-178">The machine operator informs the production manager that the end items are finished.</span></span>  
7.  <span data-ttu-id="e4529-179">Контролер цеха использует журнал потребления или производственный журнал для учета потребления компонентов, в которых используются метод списания материалов или **Ручной** или **Вперед** или **Подбор + прямой** вместе с кодами маршрутных ссылок.</span><span class="sxs-lookup"><span data-stu-id="e4529-179">The shop floor supervisor uses the consumption journal or production journal to post the consumption of component items that use either **Manual** flushing method or **Forward** or **Pick + Forward** flushing methods together with routing link codes.</span></span>  
8.  <span data-ttu-id="e4529-180">Менеджер по производству учитывает выход производственного заказа и меняет статус на **Готовые**.</span><span class="sxs-lookup"><span data-stu-id="e4529-180">The production manager posts the output of the production order and changes status to **Finished**.</span></span> <span data-ttu-id="e4529-181">Количество компонентных товаров, использующих метод списания **В обратном направлении**, вычитается из ячейки общего доступа, а количество компонентных товаров, использующих метод списания **Подбор + В обратном направлении**, вычитается из входящей производственной ячейки.</span><span class="sxs-lookup"><span data-stu-id="e4529-181">The quantity of component items that use **Backward** flushing method is deducted from the open shop floor bin, and the quantity of component items that use **Pick + Backward** flushing method is deducted from the To-Production bin.</span></span>  

 <span data-ttu-id="e4529-182">На следующей иллюстрации показано, что происходит, если поле **Код ячейки** в списке компонентов заполняется в соответствии с местоположением или настройкой машины или производственного центра.</span><span class="sxs-lookup"><span data-stu-id="e4529-182">The following illustration shows when the **Bin Code** field on the component list is filled according to your location or machine/work center setup.</span></span>  

 <span data-ttu-id="e4529-183">![Диаграмма ячейки](media/binflow.png "BinFlow")</span><span class="sxs-lookup"><span data-stu-id="e4529-183">![Bin flow chart](media/binflow.png "BinFlow")</span></span>  

## <a name="see-also"></a><span data-ttu-id="e4529-184">См. также</span><span class="sxs-lookup"><span data-stu-id="e4529-184">See Also</span></span>  
 [<span data-ttu-id="e4529-185">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="e4529-185">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)
