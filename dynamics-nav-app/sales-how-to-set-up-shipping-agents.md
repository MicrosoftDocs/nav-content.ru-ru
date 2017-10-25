---
title: "Как настраивать экспедиторов"
description: "Для каждого экспедитора можно задать код и указать соответствующую информацию."
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
ms.openlocfilehash: aa35d295c4c4f527a55394ca3777b978bd33e0b9
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-shipping-agents"></a><span data-ttu-id="18eea-103">Практическое руководство. Настройка экспедиторов</span><span class="sxs-lookup"><span data-stu-id="18eea-103">How to: Set Up Shipping Agents</span></span>
<span data-ttu-id="18eea-104">Для каждого экспедитора можно задать код и указать соответствующую информацию.</span><span class="sxs-lookup"><span data-stu-id="18eea-104">You can set up a code for each of your shipping agents and enter information about them.</span></span>  

<span data-ttu-id="18eea-105">Если для экспедитора указывается адрес Интернет и экспедитор предоставляет пакет услуг, связанных с трассировкой товара при помощи Интернет, можно использовать функцию автоматической трассировки посылок.</span><span class="sxs-lookup"><span data-stu-id="18eea-105">If you enter an Internet address for the shipping agent, and the agent provides package tracking services on the Internet, you can use the automatic package tracking feature.</span></span> <span data-ttu-id="18eea-106">Дополнительные сведения см. в разделе [Практическое руководство. Трассировка посылок](sales-how-track-packages.md).</span><span class="sxs-lookup"><span data-stu-id="18eea-106">For more information, see [How to: Track Packages](sales-how-track-packages.md).</span></span>

<span data-ttu-id="18eea-107">При настройке в заказах продажи экспедиторов можно также указать услуги, предоставляемые каждым экспедитором.</span><span class="sxs-lookup"><span data-stu-id="18eea-107">When you set up shipping agents on your sales orders, you can also specify the services that each shipping agent offers.</span></span>  
<span data-ttu-id="18eea-108">Для каждого экспедитора можно настроить неограниченное количество услуг и по каждой услуге указать время отгрузки.</span><span class="sxs-lookup"><span data-stu-id="18eea-108">For each shipping agent, you can set up an unlimited number of services, and you can specify a shipping time for each service.</span></span>  

<span data-ttu-id="18eea-109">После того, как для строки продажи задана услуга экспедитора, время отгрузки для услуги будет включаться в расчет сроков по заказу для данной строки.</span><span class="sxs-lookup"><span data-stu-id="18eea-109">When you have assigned a shipping agent service to a sales order line, the shipping time of the service will be included in the order promising calculation, for that line.</span></span> <span data-ttu-id="18eea-110">Дополнительные сведения см. в разделе [Практическое руководство. Расчет сроков планирования заказов](sales-how-to-calculate-order-promising-dates.md).</span><span class="sxs-lookup"><span data-stu-id="18eea-110">For more information, see [How to: Calculate Order Promising Dates](sales-how-to-calculate-order-promising-dates.md).</span></span>

## <a name="to-set-up-a-shipping-agent"></a><span data-ttu-id="18eea-111">Настройка экспедитора</span><span class="sxs-lookup"><span data-stu-id="18eea-111">To set up a shipping agent</span></span>  
1.  <span data-ttu-id="18eea-112">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Экспедиторы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="18eea-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Shipping Agents**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="18eea-113">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="18eea-113">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]<span data-ttu-id="18eea-114">.</span><span class="sxs-lookup"><span data-stu-id="18eea-114">.</span></span>  
3.  <span data-ttu-id="18eea-115">Выберите действие **Услуги экспедитора**.</span><span class="sxs-lookup"><span data-stu-id="18eea-115">Choose the **Shipping Agent Services** action.</span></span>
4. <span data-ttu-id="18eea-116">В поле **Услуги экспедитора** заполните требуемые поля.</span><span class="sxs-lookup"><span data-stu-id="18eea-116">In the **Shipping Agent Services**, fill in the fields as necessary.</span></span>

> [!NOTE]  
>  <span data-ttu-id="18eea-117">Если удалить экспедитора из строки заказа, код услуги экспедитора для данной строки также будет удален.</span><span class="sxs-lookup"><span data-stu-id="18eea-117">If you delete the shipping agent on the order line, the shipping agent service code is also deleted.</span></span> <span data-ttu-id="18eea-118">Производится пересчет содержимого полей, которые были частично связаны с данной услугой экспедитора.</span><span class="sxs-lookup"><span data-stu-id="18eea-118">The contents of fields that were based in part on the shipping agent service are recalculated.</span></span>  

## <a name="see-also"></a><span data-ttu-id="18eea-119">См. также</span><span class="sxs-lookup"><span data-stu-id="18eea-119">See Also</span></span>
<span data-ttu-id="18eea-120">[Как осуществить трассировку посылок](sales-how-track-packages.md)  </span><span class="sxs-lookup"><span data-stu-id="18eea-120">[How to: Track Packages](sales-how-track-packages.md)  </span></span>  
[<span data-ttu-id="18eea-121">Управление складом</span><span class="sxs-lookup"><span data-stu-id="18eea-121">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="18eea-122">Наличие</span><span class="sxs-lookup"><span data-stu-id="18eea-122">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="18eea-123">[Настройка управления складом](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="18eea-123">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="18eea-124">[Управление сборкой](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="18eea-124">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="18eea-125">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="18eea-125">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="18eea-126">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="18eea-126">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

