---
title: "Как настроить единицы хранения"
description: "Единицы хранения используются для записи информации о товарах для кода конкретного склада или кода конкретного варианта."
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
ms.openlocfilehash: 7ea31e21df842e63dc9d75998d2a0c3dfe65f1d3
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-stockkeeping-units"></a><span data-ttu-id="f9697-103">Как настроить единицы хранения</span><span class="sxs-lookup"><span data-stu-id="f9697-103">How to: Set Up Stockkeeping Units</span></span>
<span data-ttu-id="f9697-104">Единицы хранения используются для записи информации о товарах для кода конкретного склада или кода конкретного варианта.</span><span class="sxs-lookup"><span data-stu-id="f9697-104">You can use stockkeeping units to record information about your items for a specific location or a specific variant code.</span></span>  

 <span data-ttu-id="f9697-105">Единицы хранения являются дополнением к карточкам товара.</span><span class="sxs-lookup"><span data-stu-id="f9697-105">Stockkeeping units are a supplement to item cards.</span></span> <span data-ttu-id="f9697-106">Они не заменяют их, хотя связаны с ними.</span><span class="sxs-lookup"><span data-stu-id="f9697-106">They do not replace them, although they are related to them.</span></span> <span data-ttu-id="f9697-107">Единицы хранения позволяют различать для одного и того же товара информацию о товаре, предназначенном для конкретной площадки хранения (как складской комплекс или центр дистрибуции) или для конкретного варианта хранения (таких как различные номера полок и различная информация о пополнении).</span><span class="sxs-lookup"><span data-stu-id="f9697-107">Stockkeeping units allow you to differentiate information about an item for a specific location, such as a warehouse or distribution center, or a specific variant, such as different shelf numbers and different replenishment information, for the same item.</span></span>  

## <a name="to-set-up-a-stockkeeping-unit"></a><span data-ttu-id="f9697-108">Настройка единицы хранения</span><span class="sxs-lookup"><span data-stu-id="f9697-108">To set up a stockkeeping unit</span></span>  

1.  <span data-ttu-id="f9697-109">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), войдите в **Единицы хранения**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f9697-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Stockkeeping Units**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f9697-110">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="f9697-110">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="f9697-111">Заполните поля в карточке.</span><span class="sxs-lookup"><span data-stu-id="f9697-111">Fill in the fields on the card.</span></span> <span data-ttu-id="f9697-112">Следующие поля являются обязательными: **Код товара**, **Код склада** и/или **Код варианта**.</span><span class="sxs-lookup"><span data-stu-id="f9697-112">The following fields are required: **Item No.**, **Location Code**, and/or **Variant Code**.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

<span data-ttu-id="f9697-113">После настройки первой единицы хранения для товара устанавливается флажок **Есть единица хранения** в карточке **Товар**.</span><span class="sxs-lookup"><span data-stu-id="f9697-113">When you have set up the first stockkeeping unit for an item, the **Stockkeeping Unit Exists** check box on the **Item** card is selected.</span></span>  

<span data-ttu-id="f9697-114">Для создания нескольких единиц хранения для одного товара используется пакетное задание **Создание единицы хранения**.</span><span class="sxs-lookup"><span data-stu-id="f9697-114">To create several stockkeeping units for an item, use the **Create Stockkeeping Unit** batch job.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f9697-115">Информация в карточке **Единица хранения** обладает более высоким приоритетом по сравнению с информацией в карточке **Товар**.</span><span class="sxs-lookup"><span data-stu-id="f9697-115">The information on the **Stockkeeping Unit** card has priority over the **Item** card.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f9697-116">См. также</span><span class="sxs-lookup"><span data-stu-id="f9697-116">See Also</span></span>  
[<span data-ttu-id="f9697-117">Практическое руководство. Регистрация новых товаров</span><span class="sxs-lookup"><span data-stu-id="f9697-117">How to: Register New Items</span></span>](inventory-how-register-new-items.md)  
[<span data-ttu-id="f9697-118">Настройка управления складом</span><span class="sxs-lookup"><span data-stu-id="f9697-118">Setting Up Warehouse Management</span></span>](warehouse-setup-warehouse.md)  
[<span data-ttu-id="f9697-119">Управление складом</span><span class="sxs-lookup"><span data-stu-id="f9697-119">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="f9697-120">Наличие</span><span class="sxs-lookup"><span data-stu-id="f9697-120">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="f9697-121">[Управление сборкой](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="f9697-121">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="f9697-122">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="f9697-122">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="f9697-123">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f9697-123">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

