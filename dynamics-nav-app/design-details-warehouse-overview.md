---
title: "Сведения о проектировании — обзор склада"
description: "Для обеспечения поддержки физической обработки товаров на уровне зон и ячеек все сведения должны отслеживаться для каждой транзакции или перемещения на складе. Управление этим осуществляется в таблице **Складская операция**. Каждая транзакция хранится в складском регистре."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 6e93b63fe6faefc601444a4179833818f384e364
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-warehouse-overview"></a><span data-ttu-id="1bf1d-105">Сведения о проектировании: обзор склада</span><span class="sxs-lookup"><span data-stu-id="1bf1d-105">Design Details: Warehouse Overview</span></span>
<span data-ttu-id="1bf1d-106">Для обеспечения поддержки физической обработки товаров на уровне зон и ячеек все сведения должны отслеживаться для каждой транзакции или перемещения на складе.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-106">To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse.</span></span> <span data-ttu-id="1bf1d-107">Управление этим осуществляется в таблице **Складская операция**.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-107">This is managed in the **Warehouse Entry** table.</span></span> <span data-ttu-id="1bf1d-108">Каждая транзакция хранится в складском регистре.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-108">Each transaction is stored in a warehouse register.</span></span>  

<span data-ttu-id="1bf1d-109">Складские документы и складской журнал используются для регистрации перемещений товаров на складе.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-109">Warehouse documents and a warehouse journal are used to register item movements in the warehouse.</span></span> <span data-ttu-id="1bf1d-110">При каждом перемещении, получении, размещении, подборе, отгрузке или коррекции товара на складе регистрируются складские операции для хранения физической информации о зоне, ячейке и количестве.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-110">Every time that an item in the warehouse is moved, received, put away, picked, shipped, or adjusted, warehouse entries are registered to store the physical information about zone, bin, and quantity.</span></span> <span data-ttu-id="1bf1d-111">Дополнительные сведения см. в разделе [Сведения о проектировании: входящий складской поток](design-details-outbound-warehouse-flow.md).</span><span class="sxs-lookup"><span data-stu-id="1bf1d-111">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span></span>  

<span data-ttu-id="1bf1d-112">Таблица **Содержимое ячейки** используется для обработки разнообразных измерений содержимого ячейки для товара, например единицы измерения, максимального количества и минимального количества.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-112">The **Bin Content** table is used to handle all the different dimensions of the contents of a bin per item, such as unit of measure, maximum quantity, and minimum quantity.</span></span> <span data-ttu-id="1bf1d-113">Таблица **Содержимое ячейки** также содержит поля FlowField для складских операций, инструкций склада и строк складского журнала, что обеспечивает возможность быстрого вычисления доступности товара по ячейкам и ячеек для товаров.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-113">The **Bin Content** table also contains flow fields to the warehouse entries, warehouse instructions, and warehouse journal lines, which ensures that the availability of an item per bin and a bin for an item can be calculated quickly.</span></span> <span data-ttu-id="1bf1d-114">Дополнительные сведения см. в разделе [Сведения о проектировании: наличие на складе](design-details-availability-in-the-warehouse.md).</span><span class="sxs-lookup"><span data-stu-id="1bf1d-114">For more information, see [Design Details: Availability in the Warehouse](design-details-availability-in-the-warehouse.md).</span></span>  

<span data-ttu-id="1bf1d-115">Если учет товаров осуществляется за пределами складского модуля, ячейка корректировки по умолчанию для конкретного склада используется для синхронизации складских операций с операциями инвентаризации.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-115">When item postings occur outside the warehouse module, a default adjustment bin per location is used to synchronize warehouse entries with inventory entries.</span></span> <span data-ttu-id="1bf1d-116">Во время инвентаризации склада любые расхождения между расчетными и подсчитанными количествами регистрируются в ячейке для коррекций, а затем учитываются как корректирующие операции книги товаров.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-116">During physical inventory of the warehouse, any differences between the calculated and counted quantities are recorded in the adjustment bin and then posted as correcting item ledger entries.</span></span> <span data-ttu-id="1bf1d-117">Дополнительные сведения см. в разделе [Сведения о проектировании: интеграция с запасом](design-details-integration-with-inventory.md).</span><span class="sxs-lookup"><span data-stu-id="1bf1d-117">For more information, see [Design Details: Integration with Inventory](design-details-integration-with-inventory.md).</span></span>  

<span data-ttu-id="1bf1d-118">На следующей иллюстрации показаны типичные складские потоки.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-118">The following illustration outlines typical warehouse flows.</span></span>  

<span data-ttu-id="1bf1d-119">![Обзор складских процессов](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span><span class="sxs-lookup"><span data-stu-id="1bf1d-119">![Overview of warehouse processes](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span></span>  

## <a name="basic-or-advanced-warehousing"></a><span data-ttu-id="1bf1d-120">Базовые или расширенные функции склада</span><span class="sxs-lookup"><span data-stu-id="1bf1d-120">Basic or Advanced Warehousing</span></span>  
<span data-ttu-id="1bf1d-121">Складская функциональность в [!INCLUDE[d365fin](includes/d365fin_md.md)] может быть реализована на разных уровнях сложности в зависимости от процессов и объема заказов компании.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-121">Warehouse functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] can be implemented in different complexity levels, depending on a company’s processes and order volume.</span></span> <span data-ttu-id="1bf1d-122">Основное различие в том, что действия выполняются на уровне отдельных заказов в базовом складировании, когда они консолидируются для нескольких заказов в расширенном складировании.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-122">The main difference is that activities are performed order-by-order in basic warehousing when they are consolidated for multiple orders in advanced warehousing.</span></span>  

 <span data-ttu-id="1bf1d-123">Чтобы различить разные уровни сложности, в этой документации используется два общих понятия — базовое и расширенное складирование.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-123">To differentiate between the different complexity levels, this documentation refers to two general denominations, Basic and Advanced Warehousing.</span></span> <span data-ttu-id="1bf1d-124">Эта простая дифференциация охватывает несколько разных уровней сложности, как определено областями продукции и настройками склада, каждый из которых поддерживается разными документами ИП.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-124">This simple differentiation covers several different complexity levels as defined by product granules and location setup, each supported by different UI documents.</span></span> <span data-ttu-id="1bf1d-125">Дополнительные сведения см. в разделе [Сведения о проектировании: настройка склада](design-details-warehouse-setup.md).</span><span class="sxs-lookup"><span data-stu-id="1bf1d-125">For more information, see [Design Details: Warehouse Setup](design-details-warehouse-setup.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="1bf1d-126">Самый расширенный уровень складирования — установки WMS в этой документации, поскольку этот уровень требует самой широкой функциональности, системы управления складом.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-126">The most advanced level of warehousing is referred to as “WMS installations” in this documentation, since this level requires the most advanced granule, Warehouse Management Systems.</span></span>  

 <span data-ttu-id="1bf1d-127">Следующие документы ИП используются в основном и расширенном складировании.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-127">The following different UI documents are used in basic and advanced warehousing.</span></span>  

## <a name="basic-ui-documents"></a><span data-ttu-id="1bf1d-128">Основные документы пользовательского интерфейса</span><span class="sxs-lookup"><span data-stu-id="1bf1d-128">Basic UI Documents</span></span>  

-   <span data-ttu-id="1bf1d-129">**Размещение запасов**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-129">**Inventory Put-away**</span></span>  
-   <span data-ttu-id="1bf1d-130">**Подбор запасов**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-130">**Inventory Pick**</span></span>  
-   <span data-ttu-id="1bf1d-131">**Перемещение запасов**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-131">**Inventory Movement**</span></span>  
-   <span data-ttu-id="1bf1d-132">**Журнал товаров**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-132">**Item Journal**</span></span>  
-   <span data-ttu-id="1bf1d-133">**Журнал реклассификации товаров**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-133">**Item Reclassification Journal**</span></span>  
-   <span data-ttu-id="1bf1d-134">(Различные отчеты)</span><span class="sxs-lookup"><span data-stu-id="1bf1d-134">(Various reports)</span></span>  

## <a name="advanced-ui-documents"></a><span data-ttu-id="1bf1d-135">Документы по расширенному пользовательскому интерфейсу</span><span class="sxs-lookup"><span data-stu-id="1bf1d-135">Advanced UI Documents</span></span>  

-   <span data-ttu-id="1bf1d-136">**Складская приемка**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-136">**Warehouse Receipt**</span></span>  
-   <span data-ttu-id="1bf1d-137">**Журнал размещения**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-137">**Put-away Worksheet**</span></span>  
-   <span data-ttu-id="1bf1d-138">**Складское размещение**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-138">**Warehouse Put-away**</span></span>  
-   <span data-ttu-id="1bf1d-139">**Журнал подбора**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-139">**Pick Worksheet**</span></span>  
-   <span data-ttu-id="1bf1d-140">**Складской подбор**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-140">**Warehouse Pick**</span></span>  
-   <span data-ttu-id="1bf1d-141">**Журнал перемещения**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-141">**Movement Worksheet**</span></span>  
-   <span data-ttu-id="1bf1d-142">**Складское перемещение**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-142">**Warehouse Movement**</span></span>  
-   <span data-ttu-id="1bf1d-143">**Внутренний подбор склада**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-143">**Internal Whse. Pick**</span></span>  
-   <span data-ttu-id="1bf1d-144">**Внутреннее размещение склада**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-144">**Internal Whse. Put-away**</span></span>  
-   <span data-ttu-id="1bf1d-145">**Журнал создания ячеек**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-145">**Bin Creation Worksheet**</span></span>  
-   <span data-ttu-id="1bf1d-146">**Журнал создания содержимого ячеек**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-146">**Bin Content Creation Worksheet**</span></span>  
-   <span data-ttu-id="1bf1d-147">**Журнал товаров склада**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-147">**Whse. Item Journal**</span></span>  
-   <span data-ttu-id="1bf1d-148">**Журнал реклассификации складских товаров**</span><span class="sxs-lookup"><span data-stu-id="1bf1d-148">**Whse. Item Reclass. Journal**</span></span>  
-   <span data-ttu-id="1bf1d-149">(Различные отчеты)</span><span class="sxs-lookup"><span data-stu-id="1bf1d-149">(Various reports)</span></span>  

<span data-ttu-id="1bf1d-150">Дополнительные сведения о каждом документе см. в соответствующих разделах окон.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-150">For more information about each document, see the respective window topics.</span></span>  

### <a name="terminology"></a><span data-ttu-id="1bf1d-151">Терминология</span><span class="sxs-lookup"><span data-stu-id="1bf1d-151">Terminology</span></span>  
<span data-ttu-id="1bf1d-152">Для того чтобы скоординировать с финансовыми понятиями покупки и продажи, складская документация [!INCLUDE[d365fin](includes/d365fin_md.md)] использует следующие термины для обозначения потока товаров на складе.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-152">To align with the financial concepts of purchases and sales, [!INCLUDE[d365fin](includes/d365fin_md.md)] warehouse documentation refers to the following terms for item flow in the warehouse.</span></span>  

|<span data-ttu-id="1bf1d-153">Термин</span><span class="sxs-lookup"><span data-stu-id="1bf1d-153">Term</span></span>|<span data-ttu-id="1bf1d-154">Описанием</span><span class="sxs-lookup"><span data-stu-id="1bf1d-154">Description</span></span>|  
|----------|---------------------------------------|  
|<span data-ttu-id="1bf1d-155">Входящий поток</span><span class="sxs-lookup"><span data-stu-id="1bf1d-155">Inbound flow</span></span>|<span data-ttu-id="1bf1d-156">Товары, перемещаемые на склад, например покупки и входящие перемещения.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-156">Items moving into the warehouse location, such as purchases and inbound transfers.</span></span>|  
|<span data-ttu-id="1bf1d-157">Внутренний поток</span><span class="sxs-lookup"><span data-stu-id="1bf1d-157">Internal flow</span></span>|<span data-ttu-id="1bf1d-158">Товары, перемещаемые в пределах склада, например производственные компоненты и выход.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-158">Items moving inside the warehouse location, such as production components and output.</span></span>|  
|<span data-ttu-id="1bf1d-159">Исходящий поток</span><span class="sxs-lookup"><span data-stu-id="1bf1d-159">Outbound flow</span></span>|<span data-ttu-id="1bf1d-160">Товары, перемещаемые со склада, например продажи и исходящие перемещения.</span><span class="sxs-lookup"><span data-stu-id="1bf1d-160">Items moving out of the warehouse location, such as sales and outbound transfers.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="1bf1d-161">См. также</span><span class="sxs-lookup"><span data-stu-id="1bf1d-161">See Also</span></span>  
 [<span data-ttu-id="1bf1d-162">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="1bf1d-162">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)

