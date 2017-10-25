---
title: "Автоматическая разбивка с расширенным подбором и размещением"
description: "Для складов, использующих расширенный подбор и размещение, можно осуществлять автоматическую разбивку, т. е. при создании складских инструкций, удовлетворяющих требованиям документов-источников, производственных заказов или внутренних подборов и размещений преобразовывать крупные единицы измерения в более мелкие."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 67b292438c0b262e7baecd622909ce3fc0f7f233
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-automatic-breaking-bulk-with-directed-put-away-and-pick"></a><span data-ttu-id="f49aa-103">Практическое руководство. Разрешение автоматической разбивки с расширенным подбором и размещением</span><span class="sxs-lookup"><span data-stu-id="f49aa-103">How to: Enable Automatic Breaking Bulk with Directed Put-away and Pick</span></span>
<span data-ttu-id="f49aa-104">Для складов, использующих расширенный подбор и размещение, [!INCLUDE[d365fin](includes/d365fin_md.md)] в различных ситуациях осуществляет разбивку автоматически, т. е. при создании складских инструкций, удовлетворяющих требованиям документов-источников, производственных заказов или внутренних подборов и размещений преобразует крупные единицы измерения в более мелкие.</span><span class="sxs-lookup"><span data-stu-id="f49aa-104">For locations that use directed put-away and pick, [!INCLUDE[d365fin](includes/d365fin_md.md)] can, in various situations, automatically breakbulk, that is, break a larger unit of measure into smaller units of measure, when it creates warehouse instructions that fulfill the needs of source documents, production orders, or internal picks and put-aways.</span></span> <span data-ttu-id="f49aa-105">Разбивка иногда также означает сбор более мелких единиц измерения при необходимости удовлетворить исходящие запросы, разбивая крупные единицы измерения в документе-источнике или производственном заказе на более мелкие единицы, существующие на складе.</span><span class="sxs-lookup"><span data-stu-id="f49aa-105">To breakbulk sometimes also means gathering smaller units of measure, if necessary, to meet outbound requests by breaking the larger unit of measure on the source document or production order into the smaller units of measure that are available in the warehouse.</span></span>   

## <a name="breakbulking-in-picks"></a><span data-ttu-id="f49aa-106">Разбивка в подборах</span><span class="sxs-lookup"><span data-stu-id="f49aa-106">Breakbulking in Picks</span></span>  
<span data-ttu-id="f49aa-107">Для хранения товаров в нескольких единицах измерения и возможности их автоматического комбинирования в процессе подбора установить флажок в поле **Разрешить разбивку** в карточке склада.</span><span class="sxs-lookup"><span data-stu-id="f49aa-107">If you want to store items in several different units of measure and allow them to be automatically combined as needed in the picking process, select the **Allow Breakbulk** field on the location card.</span></span>  

<span data-ttu-id="f49aa-108">Для выполнения задачи программа автоматически разыскивает товар в одинаковых единицах измерения.</span><span class="sxs-lookup"><span data-stu-id="f49aa-108">To fulfill a task, the program automatically looks for an item in the same unit of measure.</span></span> <span data-ttu-id="f49aa-109">Однако если товаров в этой форме программа не находит, а данное поле выбрано, программа предложит распаковать крупную единицу измерения и получить требуемую единицу измерения.</span><span class="sxs-lookup"><span data-stu-id="f49aa-109">But if it cannot find this form of the item, and this field is selected, the program will suggest that you break a larger unit of measure into the unit of measure that is needed.</span></span>  

<span data-ttu-id="f49aa-110">Если система находит только мелкие единицы измерения, то она может предложить собрать товары для того, чтобы получить количество, удовлетворяющее требования расходной накладной или производственной накладной.</span><span class="sxs-lookup"><span data-stu-id="f49aa-110">If the system can only find smaller units of measure, it will suggest that you gather items to fulfill the quantity on the shipment or production order.</span></span> <span data-ttu-id="f49aa-111">В сущности, более крупная единица измерения в документе-источнике преобразуется в более мелкие единицы для подбора.</span><span class="sxs-lookup"><span data-stu-id="f49aa-111">In effect, it breaks the larger unit of measure on the source document into smaller units for picking.</span></span>  

## <a name="breakbulking-in-put-aways"></a><span data-ttu-id="f49aa-112">Разбивка в размещениях</span><span class="sxs-lookup"><span data-stu-id="f49aa-112">Breakbulking in Put-aways</span></span>  
<span data-ttu-id="f49aa-113">При размещении на складе программой автоматически предлагаются строки действия "Поместить" в единице измерения размещения (например, в штуках), даже если товары поступают в каких-либо других единицах измерения.</span><span class="sxs-lookup"><span data-stu-id="f49aa-113">In the warehouse put-away, the program automatically suggests Place action lines in the put-away unit of measure, for example, pieces, even though the items arrive in a different unit of measure.</span></span>  

## <a name="breakbulking-in-movements"></a><span data-ttu-id="f49aa-114">Разбивка в перемещениях</span><span class="sxs-lookup"><span data-stu-id="f49aa-114">Breakbulking in Movements</span></span>  
<span data-ttu-id="f49aa-115">Разбивка производится программой автоматически в случае перемещений для пополнения, если установлен флажок в поле **Разрешить разбивку** на экспресс-вкладке **Параметр** в окне **Расчет пополнения ячеек**.</span><span class="sxs-lookup"><span data-stu-id="f49aa-115">The program also breakbulks automatically in replenishment movements, if the **Allow Breakbulk** field is selected on the **Option** FastTab in the **Calculate Bin Replenishment** window.</span></span>  

<span data-ttu-id="f49aa-116">Результаты процесса преобразования одной единицы измерения в другую отображаются в виде промежуточных строк разбивки в инструкциях по размещению, подбору или перемещению.</span><span class="sxs-lookup"><span data-stu-id="f49aa-116">You can view the results of the conversion process from one unit of measure to another as intermediate breakbulk lines in the put-away, pick, or movement instructions.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f49aa-117">Если выбрать поле **Установить фильтр разбивки** в заголовке складской инструкции, то программа не будет отображать строки разбивки каждый раз, когда более крупная единица будет использована полностью.</span><span class="sxs-lookup"><span data-stu-id="f49aa-117">If you select the **Set Breakbulk Filter** field on the warehouse instruction header, the program will hide the breakbulk lines whenever the larger unit of measure is going to be completely used.</span></span> <span data-ttu-id="f49aa-118">Например, если на поддоне расположено 12 штук и все они будут использованы, то при подборе будет рекомендовано взять 1 поддон и поместить 12 штук.</span><span class="sxs-lookup"><span data-stu-id="f49aa-118">For example, if a pallet is 12 pieces and you are going to use all 12 pieces, the pick will then direct you to take 1 pallet and place 12 pieces.</span></span> <span data-ttu-id="f49aa-119">Однако если нужно подобрать только 9 штук, строки разбивки не будут скрыты, даже если выбрать поле **Фильтр по разбивке**, т. к. оставшиеся 3 штуки необходимо будет поместить куда-либо на складе.</span><span class="sxs-lookup"><span data-stu-id="f49aa-119">However, if you have to pick only 9 pieces, then the breakbulk lines will not be hidden, even if you have selected the **Breakbulk Filter** field, because you have to place the remaining three pieces somewhere in the warehouse.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f49aa-120">Для того, чтобы единицы измерения на складе были бы оптимальными, а также для осуществления функции разбивки, следует по возможности:</span><span class="sxs-lookup"><span data-stu-id="f49aa-120">If you want your units of measure to perform optimally in the warehouse, also in connection with the breakbulk functionality, you should wherever possible try to:</span></span>  
>   
> - <span data-ttu-id="f49aa-121">Настроить в качестве базовой единицы измерения для товара наименьшую единицу, которая, как ожидается, будет вовлечена в складские процессы.</span><span class="sxs-lookup"><span data-stu-id="f49aa-121">Set up the base unit of measure for an item as the smallest unit of measure that you expect to handle in your warehouse processes.</span></span>  
> - <span data-ttu-id="f49aa-122">Настроить альтернативные единицы измерения, кратные базовой единице измерения.</span><span class="sxs-lookup"><span data-stu-id="f49aa-122">Set up your alternative units of measure for the item as multiples of the base unit of measure.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f49aa-123">См. также</span><span class="sxs-lookup"><span data-stu-id="f49aa-123">See Also</span></span>  
[<span data-ttu-id="f49aa-124">Управление складом</span><span class="sxs-lookup"><span data-stu-id="f49aa-124">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="f49aa-125">Наличие</span><span class="sxs-lookup"><span data-stu-id="f49aa-125">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="f49aa-126">[Настройка управления складом](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="f49aa-126">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="f49aa-127">[Управление сборкой](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="f49aa-127">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="f49aa-128">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="f49aa-128">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="f49aa-129">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f49aa-129">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

