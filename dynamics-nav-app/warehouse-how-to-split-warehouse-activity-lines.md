---
title: "Как разделять строки складских заданий"
description: "При проведении складских размещений, передвижений или подборов, а также товарных размещений и подборов предлагаются ячейки для подбора и размещения товаров. В предлагаемой ячейке недостаточное количество товара или недостаточно места для размещения требуемого количества. В таком случае необходимо разделить строку так, чтобы товары из одной строки брались из нескольких ячеек или помещались в несколько ячеек."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d113b83d2c4d21463e1a015e7015bc1f566652f9
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-split-warehouse-activity-lines"></a><span data-ttu-id="20aaf-105">Практическое руководство: разделение строк складских заданий</span><span class="sxs-lookup"><span data-stu-id="20aaf-105">How to: Split Warehouse Activity Lines</span></span>
<span data-ttu-id="20aaf-106">При проведении складских размещений, передвижений или подборов, а также товарных размещений и подборов предлагаются ячейки для подбора и размещения товаров.</span><span class="sxs-lookup"><span data-stu-id="20aaf-106">In warehouse put-aways, movements, or picks, and in inventory put-aways and inventory picks, bins are suggested for the picking or putting away of items.</span></span> <span data-ttu-id="20aaf-107">В предлагаемой ячейке недостаточное количество товара или недостаточно места для размещения требуемого количества.</span><span class="sxs-lookup"><span data-stu-id="20aaf-107">The actual quantity in the bin suggested may not be sufficient, or there is not enough room in the suggested bin to put away the required quantity.</span></span> <span data-ttu-id="20aaf-108">В таком случае необходимо разделить строку так, чтобы товары из одной строки брались из нескольких ячеек или помещались в несколько ячеек.</span><span class="sxs-lookup"><span data-stu-id="20aaf-108">In these cases, you need to split the line, so that the items for one line are either taken from or placed into more than one bin.</span></span>  

<span data-ttu-id="20aaf-109">Следующая процедура применяется к складским документам, таким как складское размещение, перемещение, строки подбора или размещение запасов, перемещение и строки подбора.</span><span class="sxs-lookup"><span data-stu-id="20aaf-109">The following procedure applies to warehouse documents, such as warehouse put-away, movement, and pick lines, or inventory put-away, movement, and pick lines.</span></span>  

## <a name="to-split-warehouse-activity-lines"></a><span data-ttu-id="20aaf-110">Разделение строк складской операции</span><span class="sxs-lookup"><span data-stu-id="20aaf-110">To split warehouse activity lines</span></span>  
1.  <span data-ttu-id="20aaf-111">Откройте строку складских действий в попытками устранить недостающее количество.</span><span class="sxs-lookup"><span data-stu-id="20aaf-111">Open a warehouse activity line where you are trying to handle an insufficient quantity.</span></span>  
2.  <span data-ttu-id="20aaf-112">В поле **Кол-во для обработки** ввести уменьшенное количество, которое можно обработать.</span><span class="sxs-lookup"><span data-stu-id="20aaf-112">In the **Qty. to Handle** field, enter the reduced quantity that you are able to handle.</span></span>  
3.  <span data-ttu-id="20aaf-113">На экспресс-вкладке **Строки** выберите действие **Действия**, выберите действие **Функции**, затем выберите действие **Разделить строку**.</span><span class="sxs-lookup"><span data-stu-id="20aaf-113">On the **Lines** FastTab, choose the **Actions** action, choose the **Functions** action, and then choose the **Split Line** action.</span></span> <span data-ttu-id="20aaf-114">Появится новая строка, представляющая собой копию исходной строки за исключением поля **Кол-во для обработки**, которое будет содержать количество, изъятое из исходной строки.</span><span class="sxs-lookup"><span data-stu-id="20aaf-114">A new line appears, which is a copy of the original line, except that the **Qty. to Handle** field contains the quantity that you removed from the original line.</span></span>  
4.  <span data-ttu-id="20aaf-115">Присвойте этой новой строке соответствующую ячейку, а если используется расширенный подбор и размещение, то и зону, либо продолжайте разделение строки необходимым образом, пока для всего количества не будут найдены подходящие ячейки.</span><span class="sxs-lookup"><span data-stu-id="20aaf-115">Assign an appropriate bin and, if you are using directed put-away and pick, a zone, to this new line, or continue splitting the line as necessary until you find appropriate bins for all of the quantity.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="20aaf-116">Если на складе используется расширенный подбор и размещение, и выполняется разделение строк, нужно хорошо знать склад и выбирать ячейку, которая соответствует требованиям хранения товара и выполняет общие требования для складских документов.</span><span class="sxs-lookup"><span data-stu-id="20aaf-116">If the location uses directed put-away and pick and you split the lines, you must be familiar with the warehouse and be able to choose a bin that matches the storage requirements of the item and that fulfills the general requirements of the warehouse document.</span></span> <span data-ttu-id="20aaf-117">Например, нельзя разбивать строку в документе подбора и помещать товары в навалочную зону.</span><span class="sxs-lookup"><span data-stu-id="20aaf-117">For example, you would not split a line on a pick document and place some items in the bulk storage.</span></span>  

## <a name="see-also"></a><span data-ttu-id="20aaf-118">См. также</span><span class="sxs-lookup"><span data-stu-id="20aaf-118">See Also</span></span>  
[<span data-ttu-id="20aaf-119">Управление складом</span><span class="sxs-lookup"><span data-stu-id="20aaf-119">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="20aaf-120">Наличие</span><span class="sxs-lookup"><span data-stu-id="20aaf-120">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="20aaf-121">[Настройка управления складом](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="20aaf-121">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="20aaf-122">[Управление сборкой](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="20aaf-122">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="20aaf-123">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="20aaf-123">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="20aaf-124">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="20aaf-124">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

