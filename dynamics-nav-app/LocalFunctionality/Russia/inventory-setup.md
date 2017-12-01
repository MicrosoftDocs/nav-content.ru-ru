---
title: "Настройка модуля \"Запасы\""
description: "Как часть управления запасами, можно настроить запасы для назначения товарных издержек по покупкам из зарубежных стран и регионов в соответствии с весом или объемом, и использовать один столбец для первоначального учета и корректировок."
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
ms.openlocfilehash: 86f57c7b18b98201e1c40291d18cadf08ad63b44
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="inventory-setup"></a><span data-ttu-id="2a4fe-103">Настройка модуля "Запасы"</span><span class="sxs-lookup"><span data-stu-id="2a4fe-103">Inventory Setup</span></span>
<span data-ttu-id="2a4fe-104">Как часть управление запасами, можно настроить запасы, чтобы:</span><span class="sxs-lookup"><span data-stu-id="2a4fe-104">As part of inventory management, you can set up inventory to:</span></span>  

- <span data-ttu-id="2a4fe-105">Назначать товарные издержки при покупках из зарубежных стран или регионов на основе веса или объема.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-105">Assign item charges on purchases from foreign countries/regions based on weight or volume.</span></span>  
- <span data-ttu-id="2a4fe-106">Использовать один и тот же столбец для первоначального учета и корректировок.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-106">Use the same column for original and corrective postings.</span></span>  

## <a name="item-charge-assignment-in-purchase-documents"></a><span data-ttu-id="2a4fe-107">Назначение товарных издержек в документах покупки</span><span class="sxs-lookup"><span data-stu-id="2a4fe-107">Item Charge Assignment in Purchase Documents</span></span>  
<span data-ttu-id="2a4fe-108">В России [!INCLUDE[navnow](../../includes/navnow_md.md)] может назначать товарные издержки при покупках из зарубежных стран или регионов на основе веса или объема.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-108">In Russia, [!INCLUDE[navnow](../../includes/navnow_md.md)] can assign item charges on purchases from foreign countries/regions based on weight or volume.</span></span> <span data-ttu-id="2a4fe-109">Для каждого товара в окне **Карточка товара** на экспресс-вкладке **Внешняя торговля** если установлены флажки **Вес брутто обязателен** и **Объем единицы обязателен**, необходимо заполнить поля **Вес брутто** и **Объем единицы**.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-109">For each item, in the **Item Card** window, on the **Foreign Trade** FastTab, if the **Gross Weight Mandatory** and **Unit Volume Mandatory** check boxes are selected, you must fill in the **Gross Weight** and **Unit Volume** fields.</span></span> <span data-ttu-id="2a4fe-110">Когда вы предлагает назначение товарных издержек по заказу на покупку, необходимо указать, что принцип распределения, вес и объем добавляются в параметры для выбора.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-110">When you suggest an item charge assignment on a purchase order, you must specify that the distribution principle, weight, and volume are added to the options to choose from.</span></span> <span data-ttu-id="2a4fe-111">Дополнительные сведения см. в разделе [Практическое руководство. Использование товарных издержек для учета дополнительных торговых расходов](../../payables-how-assign-item-charges.md).</span><span class="sxs-lookup"><span data-stu-id="2a4fe-111">For more information, see [How to: Use Item Charges to Account for Additional Trade Costs](../../payables-how-assign-item-charges.md).</span></span>

## <a name="item-corrections"></a><span data-ttu-id="2a4fe-112">Корректировки товара</span><span class="sxs-lookup"><span data-stu-id="2a4fe-112">Item Corrections</span></span>  
<span data-ttu-id="2a4fe-113">Можно настраивать склад на использование одного столбца для первоначального и корректирующего учета.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-113">You can set up inventory to use the same column for original and corrective postings.</span></span> <span data-ttu-id="2a4fe-114">Эта функция часто называется *красный сторно*.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-114">This is often referred to as *red storno*.</span></span>  

<span data-ttu-id="2a4fe-115">Можно использовать учет "красный сторно" для учета корректировок следующих операций склада:</span><span class="sxs-lookup"><span data-stu-id="2a4fe-115">You can use red storno posting to post corrections for the following inventory entries:</span></span>  

- <span data-ttu-id="2a4fe-116">Корректирующие операции в журнале товаров.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-116">Corrective entries in the item journal.</span></span>  
- <span data-ttu-id="2a4fe-117">Сторнирование товарных документов, таких как акты оприходования и акты списания товаров.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-117">Reversal of item documents such as item receipts and item shipments.</span></span>  
- <span data-ttu-id="2a4fe-118">Учет журналов переоценки или реклассификации товаров.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-118">Posting item revaluation or item reclassification journals.</span></span>  
- <span data-ttu-id="2a4fe-119">Периодические корректировки себестоимости товара.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-119">Periodic adjustments of item costs.</span></span>  

<span data-ttu-id="2a4fe-120">Дополнительные сведения см. в разделе [Практическое руководство. Учет корректировок "красный сторно"](how-to-post-red-storno-corrections.md).</span><span class="sxs-lookup"><span data-stu-id="2a4fe-120">For more information, see [How to: Post Red Storno Corrections](how-to-post-red-storno-corrections.md).</span></span>  

### <a name="adjusting-item-cost"></a><span data-ttu-id="2a4fe-121">Корректировка себестоимость товаров</span><span class="sxs-lookup"><span data-stu-id="2a4fe-121">Adjusting Item Cost</span></span>  
<span data-ttu-id="2a4fe-122">Если выбрано поле "Применять красное сторно" в окне **Настройка модуля "Запасы"**, то отрицательные отклонения учитываются в соответствии с "красным сторно" при исполнении пакетного задания **Коррекция себест. запасов**.</span><span class="sxs-lookup"><span data-stu-id="2a4fe-122">If you select the Enable Red Storno field in the **Inventory Setup** window, then negative deviations are posted according to red storno when you run the **Adjust Cost - Item Entries** batch job.</span></span>  

## <a name="see-also"></a><span data-ttu-id="2a4fe-123">См. также</span><span class="sxs-lookup"><span data-stu-id="2a4fe-123">See Also</span></span>  
 <span data-ttu-id="2a4fe-124">[Акты Оприходования](item-documents.md) </span><span class="sxs-lookup"><span data-stu-id="2a4fe-124">[Item Documents](item-documents.md) </span></span>  
 <span data-ttu-id="2a4fe-125">[Акты обязательств по товару](item-obligatory-acts.md) </span><span class="sxs-lookup"><span data-stu-id="2a4fe-125">[Item Obligatory Acts](item-obligatory-acts.md) </span></span>  
 <span data-ttu-id="2a4fe-126">[Практическое руководство. Учет коррекций "красный сторно"](how-to-post-red-storno-corrections.md) </span><span class="sxs-lookup"><span data-stu-id="2a4fe-126">[How to: Post Red Storno Corrections](how-to-post-red-storno-corrections.md) </span></span>  
 [<span data-ttu-id="2a4fe-127">Практическое руководство. Использование товарных издержек для учета дополнительных торговых расходов</span><span class="sxs-lookup"><span data-stu-id="2a4fe-127">How to: Use Item Charges to Account for Additional Trade Costs</span></span>](../../payables-how-assign-item-charges.md)

