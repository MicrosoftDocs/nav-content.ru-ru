---
title: "Сведения о проектировании — интеграция с запасом"
description: "Область применения управления складом и область применения запасов взаимодействуют друг с другом в физических запасах и в корректировке запасов или склада."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ca9a1b5b1ea20fc125107f3fb5b7a74814a85837
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-integration-with-inventory"></a><span data-ttu-id="d73f8-103">Сведения о проектировании: интеграция с запасом</span><span class="sxs-lookup"><span data-stu-id="d73f8-103">Design Details: Integration with Inventory</span></span>
<span data-ttu-id="d73f8-104">Область применения управления складом и область применения запасов взаимодействуют друг с другом в физических запасах и в корректировке запасов или склада.</span><span class="sxs-lookup"><span data-stu-id="d73f8-104">The Warehouse Management application area and the Inventory application area interact with one another in physical inventory and in inventory or warehouse adjustment.</span></span>  
  
## <a name="physical-inventory"></a><span data-ttu-id="d73f8-105">Физические запасы</span><span class="sxs-lookup"><span data-stu-id="d73f8-105">Physical Inventory</span></span>  
 <span data-ttu-id="d73f8-106">Окно **Инвентаризация склада — журнал** используется вместе с окном **Журнал инвентаризации** для всех расширенных складов.</span><span class="sxs-lookup"><span data-stu-id="d73f8-106">The **Whse. Phys. Inventory Journal** window is used with the **Phys. Inventory Journal** window for all advanced warehouse locations.</span></span> <span data-ttu-id="d73f8-107">Вычисляются запасы на уровне ячейки, сотруднику склада предоставляется распечатанный список.</span><span class="sxs-lookup"><span data-stu-id="d73f8-107">The inventory on bin level is calculated, and a printed list is provided for the warehouse employee.</span></span> <span data-ttu-id="d73f8-108">В списке показано, какие товары и в каких ячейках необходимо учитывать.</span><span class="sxs-lookup"><span data-stu-id="d73f8-108">The list shows which items in which bins must be counted.</span></span>  
  
 <span data-ttu-id="d73f8-109">Сотрудник склада вводит посчитанное количество в окне **Журнал — инвентаризация склада**, а затем учитывает журнал.</span><span class="sxs-lookup"><span data-stu-id="d73f8-109">The warehouse employee enters the counted quantity in the **Whse. Phys. Inventory Journal** window and then posts the journal.</span></span>  
  
 <span data-ttu-id="d73f8-110">Если подсчитанное количество больше количества в строке журнала, то для данной разницы учитывается перемещение из ячейки коррекции по умолчанию в подсчитанную ячейку.</span><span class="sxs-lookup"><span data-stu-id="d73f8-110">If the counted quantity is greater than the quantity on the journal line, a movement is posted for this difference from the default adjustment bin to the counted bin.</span></span> <span data-ttu-id="d73f8-111">В результате количество в подсчитанной ячейке увеличивается, а количество в ячейки коррекции по умолчанию уменьшается.</span><span class="sxs-lookup"><span data-stu-id="d73f8-111">This increases the quantity in the counted bin and decreases the quantity in the default adjustment bin.</span></span>  
  
 <span data-ttu-id="d73f8-112">Если подсчитанное количество меньше количества в строке журнала, то для данной разницы учитывается перемещение из подсчитанной ячейки в ячейку коррекции по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="d73f8-112">If the quantity counted is less than the quantity on the journal line, a movement for this difference is posted from the counted bin to the default adjustment bin.</span></span> <span data-ttu-id="d73f8-113">В результате количество в подсчитанной ячейке уменьшается, а количество в ячейке коррекции по умолчанию увеличивается.</span><span class="sxs-lookup"><span data-stu-id="d73f8-113">This decreases the quantity in the counted bin and increases the quantity in the default adjustment bin.</span></span>  
  
 <span data-ttu-id="d73f8-114">В расширенных конфигурациях склада значение в поле **Расчетное количество** извлекается из операций книги товаров, а значение в поле **Кол-во (инвентаризация)** извлекается из складских операций, за исключением содержимого ячейки коррекции.</span><span class="sxs-lookup"><span data-stu-id="d73f8-114">In advanced warehouse configurations, the value in the **Quantity (Calculated)** field is retrieved from item ledger entries and the value in the **Quantity (Phys. Inventory)** field is retrieved from warehouse entries, excluding the adjustment bin content.</span></span> <span data-ttu-id="d73f8-115">Поле **Кол-во** определяет разницу между первыми двумя полями, что должно быть равно содержимому ячейки коррекции.</span><span class="sxs-lookup"><span data-stu-id="d73f8-115">The **Quantity** field specifies the difference between the first two fields, which should be equal to the contents of the adjustment bin.</span></span>  
  
 <span data-ttu-id="d73f8-116">При учете журнала физических запасов обновляются складские запасы и ячейка корректировки по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="d73f8-116">When you post the physical inventory journal, the inventory and the default adjustment bin are updated.</span></span>  
  
### <a name="warehouse-adjustments-to-the-item-ledger"></a><span data-ttu-id="d73f8-117">Складские коррекции в журнале товаров</span><span class="sxs-lookup"><span data-stu-id="d73f8-117">Warehouse Adjustments to the Item Ledger</span></span>  
 <span data-ttu-id="d73f8-118">Окно **Журнал товаров** и функция **Расчет коррекции склада** используется для корректировки наличия товаров в книге операций в соответствии с корректировками, внесенными в количество товаров в ячейке склада.</span><span class="sxs-lookup"><span data-stu-id="d73f8-118">You use the **Item Journal** window and the **Calculate Whse. Adjustment** function to adjust inventory on the item ledger in accordance with an adjustment that has been made to the item quantity in a warehouse bin.</span></span> <span data-ttu-id="d73f8-119">Для создания ссылки между запасами и складом необходимо определить ячейку коррекции по умолчанию для склада.</span><span class="sxs-lookup"><span data-stu-id="d73f8-119">To create a link between the inventory and the warehouse, you must define a default adjustment bin per location.</span></span>  
  
 <span data-ttu-id="d73f8-120">Ячейка коррекции по умолчанию регистрирует товары на складе при учете увеличения запаса.</span><span class="sxs-lookup"><span data-stu-id="d73f8-120">The default adjustment bin registers items in the warehouse when you post an increase for the inventory.</span></span> <span data-ttu-id="d73f8-121">Однако при учете расхода также уменьшается количество в ячейке по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="d73f8-121">However, if you post a decrease, the quantity on the default bin is also decreased.</span></span> <span data-ttu-id="d73f8-122">В обоих случаях создаются операции книги товаров и складские операции.</span><span class="sxs-lookup"><span data-stu-id="d73f8-122">In both cases, item ledger entries and warehouse entries are created.</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="d73f8-123">Ячейка коррекции не включается в вычисление доступности.</span><span class="sxs-lookup"><span data-stu-id="d73f8-123">The adjustment bin is not included in the availability calculation.</span></span>  
  
 <span data-ttu-id="d73f8-124">Если необходимо откорректировать содержимое ячейки, можно использовать журнал товаров склада, из которого можно ввести номенклатурный номер, код зоны, код ячейки и количество, которые необходимо откорректировать.</span><span class="sxs-lookup"><span data-stu-id="d73f8-124">If you want to adjust the bin content, you can use the warehouse item journal, from which you can enter the item number, zone code, bin code, and quantity that you want to adjust.</span></span>  
  
 <span data-ttu-id="d73f8-125">Если ввести положительное количество и учесть строку, запасы, хранящиеся в ячейках, увеличатся, а количество в ячейке коррекции по умолчанию уменьшится соответствующим образом.</span><span class="sxs-lookup"><span data-stu-id="d73f8-125">If you enter a positive quantity and post the line, then the inventory stored in the bin increases, and the quantity of the default adjustment bin decreases correspondingly.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="d73f8-126">См. также</span><span class="sxs-lookup"><span data-stu-id="d73f8-126">See Also</span></span>  
 <span data-ttu-id="d73f8-127">[Сведения о проектировании: управление складом](design-details-warehouse-management.md) </span><span class="sxs-lookup"><span data-stu-id="d73f8-127">[Design Details: Warehouse Management](design-details-warehouse-management.md) </span></span>  
 [<span data-ttu-id="d73f8-128">Сведения о проектировании: наличие на складе</span><span class="sxs-lookup"><span data-stu-id="d73f8-128">Design Details: Availability in the Warehouse</span></span>](design-details-availability-in-the-warehouse.md)
