---
title: "Как планировать заказы проекта"
description: "Выполнение этой задачи планирования начинается с заказа на продажу и производится в окне **Планирование заказа на продажу**. После создания проектного производственного заказа его планирование может быть продолжено в окне **Планирование заказов**."
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
ms.openlocfilehash: a03cdaf16b25cbcf030e9a33c538ea3df96a1fe9
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-plan-project-orders"></a><span data-ttu-id="3a584-104">Практическое руководство. Планирование заказов проекта</span><span class="sxs-lookup"><span data-stu-id="3a584-104">How to: Plan Project Orders</span></span>
<span data-ttu-id="3a584-105">Выполнение этой задачи планирования начинается с заказа на продажу и производится в окне **Планирование заказа на продажу**.</span><span class="sxs-lookup"><span data-stu-id="3a584-105">This planning task starts from a sales order and uses the **Sales Order Planning** window.</span></span> <span data-ttu-id="3a584-106">После создания проектного производственного заказа его планирование может быть продолжено в окне **Планирование заказов**.</span><span class="sxs-lookup"><span data-stu-id="3a584-106">Once you have created a project production order, you can plan it further by using the **Order Planning** window.</span></span>  

## <a name="to-create-a-project-production-order"></a><span data-ttu-id="3a584-107">Создание проектного производственного заказа</span><span class="sxs-lookup"><span data-stu-id="3a584-107">To create a project production order</span></span>  

1.  <span data-ttu-id="3a584-108">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказы на продажу**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3a584-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="3a584-109">Выберите заказ на продажу, который представляет производственный проект, затем выберите действие **Планирование**.</span><span class="sxs-lookup"><span data-stu-id="3a584-109">Select the sales order that represents the production project, and then choose the **Planning** action.</span></span>  
4.  <span data-ttu-id="3a584-110">В окне **Планирование заказа на продажу** выберите действие **Создать произв. заказ**.</span><span class="sxs-lookup"><span data-stu-id="3a584-110">In the **Sales Order Planning** window, choose  the **Create Prod. Order** action.</span></span>  
5.  <span data-ttu-id="3a584-111">В окне **Создание заказа из продажи** в поле **Тип заказа** выберите **Проектный заказ**.</span><span class="sxs-lookup"><span data-stu-id="3a584-111">In the **Create Order from Sales** window, in the **Order Type** field, select **Project Order**.</span></span>  
6.  <span data-ttu-id="3a584-112">Нажмите кнопку **Да**.</span><span class="sxs-lookup"><span data-stu-id="3a584-112">Choose the **Yes** button.</span></span>  
7.  <span data-ttu-id="3a584-113">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Производственные заказы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3a584-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Production Orders**, and then choose the related link.</span></span>
8. <span data-ttu-id="3a584-114">Откройте только что созданный производственный заказ.</span><span class="sxs-lookup"><span data-stu-id="3a584-114">Open the production order just created.</span></span>  

    <span data-ttu-id="3a584-115">Обратите внимание, что поле **Тип источника** производственного заказа содержит **Продажи - заголовок**, а заказ содержит несколько строк (по одной на каждую товарную позицию, которая должна быть произведена).</span><span class="sxs-lookup"><span data-stu-id="3a584-115">Notice that the **Source Type** field of the production order contains **Sales Header** and the order has multiple lines, one for each sales line item that must be produced.</span></span>  
9. <span data-ttu-id="3a584-116">Выберите действие **Планирование**.</span><span class="sxs-lookup"><span data-stu-id="3a584-116">Choose the **Planning** action.</span></span>
10. <span data-ttu-id="3a584-117">В окне **Планирование заказов** выберите действие **Обновить**, чтобы рассчитать новый спрос.</span><span class="sxs-lookup"><span data-stu-id="3a584-117">In the **Order Planning** window, choose the **Refresh** action to calculate new demand.</span></span>  

<span data-ttu-id="3a584-118">Строка заголовка проектного заказа отображается в развернутом виде со всеми невыполненными строками требования.</span><span class="sxs-lookup"><span data-stu-id="3a584-118">The order header line for the project order is displayed with all unfulfilled demand lines expanded under it.</span></span> <span data-ttu-id="3a584-119">Хотя производственный заказ содержит строки для нескольких производимых товаров, общее требование для всех строк производственного заказа вместе с названием исходного клиента отображается под одной строкой заголовка заказа в окне **Планирование заказов**.</span><span class="sxs-lookup"><span data-stu-id="3a584-119">Although the production order contains lines for several produced items, the total demand for all production order lines is listed under one order header line in the **Order Planning** window, and the original customer name is displayed.</span></span> <span data-ttu-id="3a584-120">Теперь можно приступать к планированию спроса, как описано в разделе [Практическое руководство. Планирование нового спроса по заказам](production-how-to-plan-for-new-demand.md).</span><span class="sxs-lookup"><span data-stu-id="3a584-120">You can now proceed to plan for the demand as described in [How to: Plan for New Demand Order by Order](production-how-to-plan-for-new-demand.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="3a584-121">Строки спроса в производственном заказе проекта, которые в поле **Метод пополнения** имеют значение **Произв. заказ**, представляют подчиненные производственные заказы.</span><span class="sxs-lookup"><span data-stu-id="3a584-121">Demand lines in the project production order that have **Prod. Order** in their **Replenishment System** field represent underlying production orders.</span></span> <span data-ttu-id="3a584-122">После формирования этих производственных заказов необходимо снова вычислить план в окне **Планирование заказов** для определения возможного невыполненного требования компонента для них.</span><span class="sxs-lookup"><span data-stu-id="3a584-122">After you have generated these production orders, you must again calculate a plan in the **Order Planning** window to identify any unfulfilled component demand for them.</span></span> <span data-ttu-id="3a584-123">В этом случае они отображаются в виде строк спроса под обычной строкой заголовка производственного заказа, обозначая, что связь проекта более не отображается в окне.</span><span class="sxs-lookup"><span data-stu-id="3a584-123">In that case, they are displayed as demand lines under a normal production order header line, meaning, the project relation is no longer visible in the window.</span></span> <span data-ttu-id="3a584-124">Если используется "Трассировка заказов", можно пролистать назад и вперед все заказы на поставку, созданные под исходным заказом на продажу.</span><span class="sxs-lookup"><span data-stu-id="3a584-124">However, if you are using the Order Tracking feature, then you can look back and forth to all supply orders made under the original sales order.</span></span>  

## <a name="see-also"></a><span data-ttu-id="3a584-125">См. также</span><span class="sxs-lookup"><span data-stu-id="3a584-125">See Also</span></span>
<span data-ttu-id="3a584-126">[Планирование](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="3a584-126">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="3a584-127">Настройка производства</span><span class="sxs-lookup"><span data-stu-id="3a584-127">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="3a584-128">[Производство](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="3a584-128">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="3a584-129">Наличие</span><span class="sxs-lookup"><span data-stu-id="3a584-129">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="3a584-130">Покупки</span><span class="sxs-lookup"><span data-stu-id="3a584-130">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="3a584-131">[Сведения о проектировании: планирование поставок](design-details-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="3a584-131">[Design Details: Supply Planning](design-details-supply-planning.md) </span></span>  
[<span data-ttu-id="3a584-132">Рекомендации по настройке. Планирование поставок</span><span class="sxs-lookup"><span data-stu-id="3a584-132">Setup Best Practices: Supply Planning</span></span>](setup-best-practices-supply-planning.md)  
<span data-ttu-id="3a584-133">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="3a584-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

