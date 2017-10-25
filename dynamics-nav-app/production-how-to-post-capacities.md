---
title: "Как учитывать производственные мощности"
description: "Учет используемых производственных мощностей, не присвоенных производственному заказу, осуществляется в журнале производственных мощностей. Например, работы по обслуживанию должны быть приписаны к производственным мощностям, а не к производственному заказу."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4fe29c9ec6fdcc9680a865e60f6185eb892f2a2f
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-capacities"></a><span data-ttu-id="f6ff4-104">Практическое руководство. Учет производственных мощностей</span><span class="sxs-lookup"><span data-stu-id="f6ff4-104">How to: Post Capacities</span></span>
<span data-ttu-id="f6ff4-105">Учет используемых производственных мощностей, не присвоенных производственному заказу, осуществляется в журнале производственных мощностей.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-105">In the capacity journal, you post consumed capacities that are not assigned to the production order.</span></span> <span data-ttu-id="f6ff4-106">Например, работы по обслуживанию должны быть приписаны к производственным мощностям, а не к производственному заказу.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-106">For example, maintenance work must be assigned to capacity, but not to a production order.</span></span>  

## <a name="to-post-capacities"></a><span data-ttu-id="f6ff4-107">Учет произв. мощностей</span><span class="sxs-lookup"><span data-stu-id="f6ff4-107">To post capacities</span></span>  
1.  <span data-ttu-id="f6ff4-108">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы произв. мощностей**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Capacity Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f6ff4-109">Заполните поля **Дата учета** и **Номер документа**.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-109">Fill in the **Posting Date** and **Document No.** fields.</span></span>  
3.  <span data-ttu-id="f6ff4-110">В поле **Тип** введите тип производственных мощностей — **Машинный центр** или **Рабочий центр**, — учет которых необходимо осуществить.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-110">In the **Type** field, enter the type of the capacity, either **Machine Center** or **Work Center**, that you are posting.</span></span>  
4.  <span data-ttu-id="f6ff4-111">В поле **Номер**</span><span class="sxs-lookup"><span data-stu-id="f6ff4-111">In the **No.**</span></span> <span data-ttu-id="f6ff4-112">введите номер машинного или производственного центра.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-112">field, enter the number of the machine center or work center.</span></span>  
5.  <span data-ttu-id="f6ff4-113">Введите необходимые данные в остальные поля, такие как **Время начала**, **Время окончания**, **Кол-во** и **Брак**.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-113">Enter the relevant data in the other fields, such as **Starting Time**, **Ending Time**, **Quantity**, and **Scrap**.</span></span>  
6.  <span data-ttu-id="f6ff4-114">Выберите действие **Учесть**, чтобы учесть производственные мощности.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-114">Choose the **Post** action to post the capacities.</span></span>  

## <a name="to-view-work-center-ledger-entries"></a><span data-ttu-id="f6ff4-115">Для просмотра операций книги рабочего центра:</span><span class="sxs-lookup"><span data-stu-id="f6ff4-115">To view work center ledger entries</span></span>  
<span data-ttu-id="f6ff4-116">В окнах **Карточка производственного центра** и **Карточка машинного центра** можно просмотреть учтенные производственные мощности как результат завершенных производственных заказов.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-116">In the **Work Center Card** and **Machine Center Card** windows, you can view the posted capacities as a result of finished production orders.</span></span>    
1.  <span data-ttu-id="f6ff4-117">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Производственные центры**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Work Centers**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f6ff4-118">Откройте соответствующую карточку **Производственный центр** из списка, затем выберите действие **Книга операций по произв. мощностям**.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-118">Open the relevant **Work Center** card from the list, and then choose the **Capacity Ledger Entries** action.</span></span>  

<span data-ttu-id="f6ff4-119">В окне **Произв. мощности - книга операций** перечисляются учтенные операции рабочего центра в порядке их учета.</span><span class="sxs-lookup"><span data-stu-id="f6ff4-119">The **Capacity Ledger Entries** window displays the posted entries from the work center in the order they were posted.</span></span>   

## <a name="see-also"></a><span data-ttu-id="f6ff4-120">См. также</span><span class="sxs-lookup"><span data-stu-id="f6ff4-120">See Also</span></span>  
<span data-ttu-id="f6ff4-121">[Производство](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="f6ff4-121">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="f6ff4-122">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="f6ff4-122">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="f6ff4-123">[Планирование](production-planning.md)    </span><span class="sxs-lookup"><span data-stu-id="f6ff4-123">[Planning](production-planning.md)    </span></span>  
[<span data-ttu-id="f6ff4-124">Наличие</span><span class="sxs-lookup"><span data-stu-id="f6ff4-124">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="f6ff4-125">Покупки</span><span class="sxs-lookup"><span data-stu-id="f6ff4-125">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="f6ff4-126">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f6ff4-126">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

