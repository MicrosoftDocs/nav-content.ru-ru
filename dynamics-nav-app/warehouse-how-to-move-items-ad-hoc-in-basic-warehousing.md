---
title: "Как перемещать специальные товары в основных конфигурациях склада"
description: "Иногда может потребоваться переместить товары между внутренними ячейками, ячейками без приемки или ячейками отгрузки без определенного требования из документа-источника. Можно выполнить эти специальные передвижения, например, чтобы реорганизовать товары на складе, переместить товары в зону осмотра либо переместить дополнительные товары в область производства или из нее без привязки системы к документу-источнику производственного заказа."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 8502b182198015cfc584be31ce36db9956bc6bd1
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-move-items-ad-hoc-in-basic-warehouse-configurations"></a><span data-ttu-id="505a8-104">Практическое руководство. Перемещение специальных товаров в основных конфигурациях склада</span><span class="sxs-lookup"><span data-stu-id="505a8-104">How to: Move Items Ad Hoc in Basic Warehouse Configurations</span></span>
<span data-ttu-id="505a8-105">Иногда может потребоваться переместить товары между внутренними ячейками, ячейками без приемки или ячейками отгрузки без определенного требования из документа-источника.</span><span class="sxs-lookup"><span data-stu-id="505a8-105">You may occasionally need to move items between internal bins, not receiving or shipping bins, without a specific demand from a source document.</span></span> <span data-ttu-id="505a8-106">Можно выполнить эти специальные передвижения, например, чтобы реорганизовать товары на складе, переместить товары в зону осмотра либо переместить дополнительные товары в область производства или из нее без привязки системы к документу-источнику производственного заказа.</span><span class="sxs-lookup"><span data-stu-id="505a8-106">You may perform these ad hoc movements, for example, to reorganize the warehouse, to bring items to an inspection area, or to move additional items to and from a production area without a system relation to the production order source document.</span></span>  

<span data-ttu-id="505a8-107">В рамках базовой конфигурации склада, в котором используется поле настройки **Ячейка обязательна** и, возможно, поля настройки **Требуется подбор** и **Требуется размещение**, можно ввести специальный счет движения без документа-источника одним из следующих способов:</span><span class="sxs-lookup"><span data-stu-id="505a8-107">In basic warehouse configurations, that is locations that use the **Bin Mandatory** setup field and possibly the **Require Pick** and the **Require Put-away** setup fields, you can register ad hoc movements without source documents in the following ways:</span></span>  

    - <span data-ttu-id="505a8-108">С помощью окна **Внутреннее перемещение**.</span><span class="sxs-lookup"><span data-stu-id="505a8-108">With the **Internal Movement** window.</span></span>  
    - <span data-ttu-id="505a8-109">С помощью окна **Журнал реклассификаций товаров**.</span><span class="sxs-lookup"><span data-stu-id="505a8-109">With the **Item Reclassification Journal** window.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="505a8-110">В расширенных настройках складов, в которых используется поле настройки **Расширенный подбор и размещение**, используется окно **Журнал перемещений** или окна **Внутренний складской подбор** или **Внутреннее складское размещение** для перемещения товаров между ячейками на ходу.</span><span class="sxs-lookup"><span data-stu-id="505a8-110">In advanced warehouse configurations, that is locations that use the **Directed Put-away and Pick** setup field, you use the **Movement Worksheet** window or the **Internal Whse. Pick** or the **Internal Whse. Put-away** windows to move items ad hoc between bins.</span></span>  

## <a name="to-move-items-as-an-internal-movement"></a><span data-ttu-id="505a8-111">Перемещение товаров как складское помещение</span><span class="sxs-lookup"><span data-stu-id="505a8-111">To move items as an internal movement</span></span>  
1.  <span data-ttu-id="505a8-112">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Внутреннее перемещение**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="505a8-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Internal Movement**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="505a8-113">На экспресс-вкладке **Общее** заполните поле **Номер**</span><span class="sxs-lookup"><span data-stu-id="505a8-113">On the **General** FastTab, fill in the **No.**</span></span> <span data-ttu-id="505a8-114">оставив поле или нажав кнопку **AssistEdit**, чтобы выбрать из серии номеров.</span><span class="sxs-lookup"><span data-stu-id="505a8-114">field, either by leaving the field or by choosing the **AssistEdit** button to select from the number series.</span></span>  
3.  <span data-ttu-id="505a8-115">В поле **Код склада** введите склад, где происходит перемещение.</span><span class="sxs-lookup"><span data-stu-id="505a8-115">In the **Location Code** field, enter the location where the movement takes place.</span></span>  

    <span data-ttu-id="505a8-116">Если склад настроен как склад по умолчанию для работника склада, код склада автоматически вставлен.</span><span class="sxs-lookup"><span data-stu-id="505a8-116">If the location is set up as your default location as a warehouse employee, the location code is inserted automatically.</span></span>  
4.  <span data-ttu-id="505a8-117">В поле **В код ячейки** введите код ячейки, в которую требуется переместить товар.</span><span class="sxs-lookup"><span data-stu-id="505a8-117">In the **To Bin Code** field, enter a code for the bin that you want to move the item to.</span></span> <span data-ttu-id="505a8-118">Для производственных целей это может быть например код ячейки сборки, указанный на карточке склада или в рабочем центре.</span><span class="sxs-lookup"><span data-stu-id="505a8-118">For production purposes, this could be the open shop floor bin code, for example, as defined on the location card or work center.</span></span>  
5.  <span data-ttu-id="505a8-119">В поле **Срок оплаты** введите дату, до которой должно быть завершено перемещение.</span><span class="sxs-lookup"><span data-stu-id="505a8-119">In the **Due Date** field, enter the date by which the movement must be completed.</span></span>  
6.  <span data-ttu-id="505a8-120">На экспресс-вкладке **Строки** выберите поле **Код товара**, чтобы открыть окно **Список содержимого ячейки**, а затем выберите товар, чтобы переместить его в зависимости от его наличия в ячейках. В качестве альтернативы выберите действие **Получить содержимое ячейки** для заполнения строк внутреннего перемещения на основе фильтров.</span><span class="sxs-lookup"><span data-stu-id="505a8-120">On the **Lines** FastTab, choose the **Item No.** field to open the **Bin Contents List** window, and then select the item to move based on its availability in bins. Alternatively, choose the **Get Bin Contents** action to fill the internal movement lines based on your filters.</span></span> <span data-ttu-id="505a8-121">Дополнительные сведения см. во всплывающей подсказке для действия **Получить содержимое ячейки**.</span><span class="sxs-lookup"><span data-stu-id="505a8-121">For more information, see the tooltip for the **Get Bin Content** action.</span></span>   

    <span data-ttu-id="505a8-122">При выборе товара поле **Из кода ячейки** заполняется автоматически в соответствии с выбранными содержимым ячейки, но ячейку можно изменить на любую другую, в которой доступен товар.</span><span class="sxs-lookup"><span data-stu-id="505a8-122">When you have selected the item, the **From Bin Code** field is automatically filled according to the selected bin content, but you can change it to any other bin where the item is available.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="505a8-123">Так как поля **Код товара** и **Из кода ячейки** взаимосвязаны, значения этих полей могут изменяться взаимозависимо при редактировании любого из них.</span><span class="sxs-lookup"><span data-stu-id="505a8-123">Because the **Item No.** field and the **From Bin Code** field are connected, their values may change interdependently when you edit either field.</span></span>  

    <span data-ttu-id="505a8-124">В поле **В код ячейки** вносится значение, введенное в заголовке, но его можно изменить в строке на любой другой код ячейки, который не заблокирован и не выделен для специальных целей.</span><span class="sxs-lookup"><span data-stu-id="505a8-124">The **To Bin Code** field is filled with the value you entered on the header, but you can change it on the line to any other bin code that isn’t blocked or dedicated to special purposes.</span></span> <span data-ttu-id="505a8-125">Дополнительные сведения о создании выделенных ячеек см. в разделе Специальная.</span><span class="sxs-lookup"><span data-stu-id="505a8-125">For more information about making bins dedicated, see Dedicated.</span></span>  
7.  <span data-ttu-id="505a8-126">После определения ячеек, в которые и из которых будет перемещаться товар, введите количество для перемещения в поле **Количество**.</span><span class="sxs-lookup"><span data-stu-id="505a8-126">When you have defined which bins you want to move the item from and to, enter the quantity to move in the **Quantity** field.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="505a8-127">Количество должно быть в наличии в коде исходящей ячейки.</span><span class="sxs-lookup"><span data-stu-id="505a8-127">Quantity must be available in the From Bin code.</span></span>  

8.  <span data-ttu-id="505a8-128">Когда все будет готово для обработки внутреннего перемещения, выберите действие **Создать перемещение запасов**.</span><span class="sxs-lookup"><span data-stu-id="505a8-128">When you are ready to process the internal movement, choose the **Create Inventory Movement** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="505a8-129">После создания перемещения запасов строки складского помещения будут удалены.</span><span class="sxs-lookup"><span data-stu-id="505a8-129">When you have created the inventory movement, the internal movement lines are deleted.</span></span>  

    <span data-ttu-id="505a8-130">Оставшееся специальное перемещение выполняется в окне **Перемещение запасов** таким же образом, как и для перемещения на основе документов источника.</span><span class="sxs-lookup"><span data-stu-id="505a8-130">You perform the remainder of the ad hoc movement in the **Inventory Movement** window in the same way as you would for a movement based on source documents.</span></span> <span data-ttu-id="505a8-131">Дополнительные сведения см., например, в разделе [Практическое руководство. Перемещение компонентов в производственную зону в основных конфигурациях склада](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)</span><span class="sxs-lookup"><span data-stu-id="505a8-131">For more information, see for example [How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)</span></span>  

## <a name="to-move-items-with-the-item-reclassification-journal"></a><span data-ttu-id="505a8-132">Перемещение товаров с помощью журнала реклассификации товара</span><span class="sxs-lookup"><span data-stu-id="505a8-132">To move items with the item reclassification journal</span></span>
<span data-ttu-id="505a8-133">Вместо использования документов складского перемещения, можно регистрировать перемещение товаров, переквалифицируя коды их ячеек.</span><span class="sxs-lookup"><span data-stu-id="505a8-133">In stead of using warehouse movement documents, you can record the moving of items by reclassifying their bin codes.</span></span> <span data-ttu-id="505a8-134">Дополнительные сведения см. в разделе [Практическое руководство. Подсчет, корректировка и повторная классификация запасов](inventory-how-count-adjust-reclassify.md).</span><span class="sxs-lookup"><span data-stu-id="505a8-134">For more information, see [How to: Count, Adjust, and Reclassify Inventory](inventory-how-count-adjust-reclassify.md).</span></span>   
1.  <span data-ttu-id="505a8-135">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал реклассификации товаров**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="505a8-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Reclass. Journal**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="505a8-136">Для каждой строки журнала укажите ячейки, из которых и в которые предполагается перемещать товары, заполняя поля **Код ячейки** и **Код новой ячейки**.</span><span class="sxs-lookup"><span data-stu-id="505a8-136">On each journal line, define the bins from which and to which you want to move items by filling in the **Bin Code** and the **New Bin Code** fields.</span></span>  

    1.  <span data-ttu-id="505a8-137">Чтобы все содержимое ячейки переместить в другую ячейку, выберите действие **Получить содержимое ячейки**.</span><span class="sxs-lookup"><span data-stu-id="505a8-137">To move a bin's entire contents to another bin, choose the **Get Bin Contents** action.</span></span>  
    2.  <span data-ttu-id="505a8-138">Введите фильтр, чтобы найти ячейку, содержимое которой предполагается переместить, и нажмите кнопку **OK**.</span><span class="sxs-lookup"><span data-stu-id="505a8-138">Fill in the filters to find the bin whose contents you would like to move and then choose the **OK** button.</span></span> <span data-ttu-id="505a8-139">Строки журнала заполняются содержимым ячейки.</span><span class="sxs-lookup"><span data-stu-id="505a8-139">The journal lines are filled with the contents of the bin.</span></span>  
3.  <span data-ttu-id="505a8-140">Заполните во всех строках журнала оставшиеся поля.</span><span class="sxs-lookup"><span data-stu-id="505a8-140">Fill in the remaining fields on each journal line.</span></span>   
4.  <span data-ttu-id="505a8-141">Выполните учет журнала реклассификации.</span><span class="sxs-lookup"><span data-stu-id="505a8-141">Post the reclassification journal.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="505a8-142">В отличие от документов перемещения перемещение, учтенное с помощью журнала реклассификации, не создает складской запрос на выполнение физической задачи.</span><span class="sxs-lookup"><span data-stu-id="505a8-142">Unlike with movement documents, a movement posted with the reclassification journal does not create a warehouse request to perform the physical task.</span></span>  

## <a name="see-also"></a><span data-ttu-id="505a8-143">См. также</span><span class="sxs-lookup"><span data-stu-id="505a8-143">See Also</span></span>  
[<span data-ttu-id="505a8-144">Управление складом</span><span class="sxs-lookup"><span data-stu-id="505a8-144">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="505a8-145">Наличие</span><span class="sxs-lookup"><span data-stu-id="505a8-145">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="505a8-146">[Настройка управления складом](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="505a8-146">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="505a8-147">[Управление сборкой](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="505a8-147">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="505a8-148">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="505a8-148">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="505a8-149">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="505a8-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
