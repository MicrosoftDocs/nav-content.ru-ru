---
title: "Как работать с центрами ответственности"
description: "Центры ответственности позволяют обслуживать центры администрирования. Центр ответственности может быть центром затрат, центром прибыли, центром инвестиций или другим определенным организацией центром."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: ffbb79befe9fa37d789c21854e1b05a8f29a8b86
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-work-with-responsibility-centers"></a><span data-ttu-id="4cd46-104">Практическое руководство. Работа с центрами ответственности</span><span class="sxs-lookup"><span data-stu-id="4cd46-104">How to: Work with Responsibility Centers</span></span>
<span data-ttu-id="4cd46-105">Центры ответственности обеспечивают возможность работы с центрами администрирования.</span><span class="sxs-lookup"><span data-stu-id="4cd46-105">Responsibility centers provide the ability to handle administrative centers.</span></span> <span data-ttu-id="4cd46-106">Центр ответственности может быть центром затрат, центром прибыли, центром инвестиций или другим определенным организацией центром.</span><span class="sxs-lookup"><span data-stu-id="4cd46-106">A responsibility center can be a cost center, a profit center, an investment center, or other company-defined administrative center.</span></span> <span data-ttu-id="4cd46-107">Примеры центров ответственности: отдел продаж, отдел снабжения для нескольких складов и отдел планирования завода.</span><span class="sxs-lookup"><span data-stu-id="4cd46-107">Examples of responsibility centers are a sales office, a purchasing department for several locations, and a plant planning office.</span></span> <span data-ttu-id="4cd46-108">Используя данную функцию, организации могут, например, задавать пользовательские представления документов продажи и покупки, относящиеся к исключительно к конкретному центру ответственности.</span><span class="sxs-lookup"><span data-stu-id="4cd46-108">Using this functionality, for example, companies can set up user-specific views of sales and purchase documents related exclusively to a particular responsibility center.</span></span>  

<span data-ttu-id="4cd46-109">Использование нескольких складов вместе с центрами ответственности позволяет организациям с территориально разнесенными подразделениями наиболее гибко и эффективно управлять своими бизнес-операциями.</span><span class="sxs-lookup"><span data-stu-id="4cd46-109">Using multiple locations together with responsibility centers provides the ability to manage business operations in the most flexible, yet optimal way.</span></span>

<span data-ttu-id="4cd46-110">Использование нескольких складов позволяет организациям управлять товарами на нескольких складах с помощью одной базы данных.</span><span class="sxs-lookup"><span data-stu-id="4cd46-110">Multiple locations allows companies to manage their inventory in multiple locations using one database.</span></span> <span data-ttu-id="4cd46-111">Два понятия — склады и единицы хранения — лежат в основе данной области.</span><span class="sxs-lookup"><span data-stu-id="4cd46-111">Two concepts, locations and stockkeeping units, are the cornerstones of this granule.</span></span> <span data-ttu-id="4cd46-112">Склад — это место, где физически хранятся определенные количества товара.</span><span class="sxs-lookup"><span data-stu-id="4cd46-112">A location is defined as a place that handles physical placement and quantities of items.</span></span> <span data-ttu-id="4cd46-113">Это широкое понятие, которое включает в себя такие склады как заводы или производственные помещения, а также распределительные центры, склады, выставочные залы и служебные автомобили.</span><span class="sxs-lookup"><span data-stu-id="4cd46-113">The concept is broad enough to include locations such as plants or production facilities as well as distribution centers, warehouses, showrooms and service vehicles.</span></span> <span data-ttu-id="4cd46-114">Единица хранения — это товар на определенном складе и/или вариант.</span><span class="sxs-lookup"><span data-stu-id="4cd46-114">A stockkeeping unit is defined as an item at a specific location and/or as a variant.</span></span> <span data-ttu-id="4cd46-115">Используя единицы хранения, организации, расположенные в нескольких местах, могут добавлять сведения о пополнении, адреса и некоторые сведения финансового учета на уровне склада.</span><span class="sxs-lookup"><span data-stu-id="4cd46-115">Using stockkeeping units, companies with multiple locations are able to add replenishment information, addresses, and some financial posting information at the location level.</span></span> <span data-ttu-id="4cd46-116">В результате у них появляется возможность пополнить варианты одного и того же товара на каждом складе, а также заказать товары на каждый склад на основании сведений о пополнении каждого склада.</span><span class="sxs-lookup"><span data-stu-id="4cd46-116">As a result, they have the ability to replenish variants of the same item for each location as well as to order items for each location on the basis of location-specific replenishment information.</span></span>  

<span data-ttu-id="4cd46-117">Центры ответственности расширяют функцию нескольких складов, чтобы пользователи могли управлять административными центрами.</span><span class="sxs-lookup"><span data-stu-id="4cd46-117">Responsibility centers extends the multiple locations functionality by providing users the ability to handle administrative centers.</span></span> <span data-ttu-id="4cd46-118">Центр ответственности может быть центром затрат, центром прибыли, центром инвестиций или другим определенным организацией центром.</span><span class="sxs-lookup"><span data-stu-id="4cd46-118">A responsibility center can be a cost center, a profit center, an investment center, or other company-defined administrative center.</span></span> <span data-ttu-id="4cd46-119">Примеры центров ответственности: отдел продаж, отдел снабжения для нескольких складов и отдел планирования завода.</span><span class="sxs-lookup"><span data-stu-id="4cd46-119">Examples of responsibility centers are a sales office, a purchasing department for several locations, and a plant planning office.</span></span> <span data-ttu-id="4cd46-120">Используя данную функцию, организации могут, например, задавать пользовательские представления документов продажи и покупки, относящиеся к исключительно к конкретному центру ответственности.</span><span class="sxs-lookup"><span data-stu-id="4cd46-120">Using this functionality, for example, companies can set up user-specific views of sales and purchase documents related exclusively to a particular responsibility center.</span></span>

## <a name="to-set-up-a-responsibility-center"></a><span data-ttu-id="4cd46-121">Настройка центра ответственности</span><span class="sxs-lookup"><span data-stu-id="4cd46-121">To set up a responsibility center</span></span>  
1.  <span data-ttu-id="4cd46-122">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Центры ответственности**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="4cd46-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Responsibility Centers**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4cd46-123">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="4cd46-123">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="4cd46-124">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="4cd46-124">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    <span data-ttu-id="4cd46-125">Если для управления организацией используются центры ответственности, может оказаться полезным настроить центр ответственности по умолчанию для организации.</span><span class="sxs-lookup"><span data-stu-id="4cd46-125">If you are using responsibility centers to administer your company, it can be useful to have a default responsibility center for your company.</span></span>
4. <span data-ttu-id="4cd46-126">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Информация об организации**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="4cd46-126">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Company Information**, and then choose the related link.</span></span>
5. <span data-ttu-id="4cd46-127">В поле **Центр ответственности** введите код центра ответственности.</span><span class="sxs-lookup"><span data-stu-id="4cd46-127">In the **Responsibility Center** field, enter a responsibility center code.</span></span>

<span data-ttu-id="4cd46-128">Этот код будет использован во всех документах покупок, продаж или обслуживания, если пользователь, клиент или поставщик не имеют центра ответственности по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="4cd46-128">This code will be used on all purchase, sales, or service documents, if the user, customer, or vendor has no default responsibility center.</span></span> <span data-ttu-id="4cd46-129">В любом документе продажи, покупки или обслуживания можно ввести другой центр ответственности, отличный от центра по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="4cd46-129">On any sales, purchase, or service document, you can enter another responsibility center than the default.</span></span>

> [!NOTE]  
>  <span data-ttu-id="4cd46-130">При вводе в документ кода центра ответственности он оказывает влияние на адрес, измерения и цены в этом документе.</span><span class="sxs-lookup"><span data-stu-id="4cd46-130">When you enter a responsibility center code on a document, it affects the address, dimensions, and prices on the document.</span></span>  

## <a name="to-assign-responsibility-centers-to-users"></a><span data-ttu-id="4cd46-131">Присвоение центров ответственности пользователям</span><span class="sxs-lookup"><span data-stu-id="4cd46-131">To assign responsibility centers to users</span></span>  
<span data-ttu-id="4cd46-132">Можно произвести настройку пользователей таким образом, чтобы из результатов их ежедневной деятельности программа отбирала документы, относящиеся только к их областям ответственности.</span><span class="sxs-lookup"><span data-stu-id="4cd46-132">You can set up users so that in their daily routines the program retrieves only the documents relevant for their particular work areas.</span></span> <span data-ttu-id="4cd46-133">Пользователи как правило относятся к одному дистрибьюторскому центру и работают только с документами, относящимися к областям приложения для данного конкретного дистрибьюторского центра.</span><span class="sxs-lookup"><span data-stu-id="4cd46-133">Users are usually associated with one responsibility center and work only with documents related to specific application areas at that particular center.</span></span>  

<span data-ttu-id="4cd46-134">Для настройки такой схемы работы следует поставить в соответствие пользователям дистрибьюторские центры в рамках трех основных функциональных областей: покупки, продажи и сервисное управление.</span><span class="sxs-lookup"><span data-stu-id="4cd46-134">To set this up, you assign responsibility centers to users in three functional areas: Purchases, Sales, and Service Management.</span></span>  

1.  <span data-ttu-id="4cd46-135">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройки пользователей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="4cd46-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **User Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4cd46-136">В окне **Настройки пользователей** выберите пользователя, для которого необходимо задать дистрибьюторский центр.</span><span class="sxs-lookup"><span data-stu-id="4cd46-136">In the **User Setup** window, select the user you want to assign a responsibility center to.</span></span> <span data-ttu-id="4cd46-137">Если пользователь не присутствует в списке, в поле **Код пользователя** следует указать Код пользователя.</span><span class="sxs-lookup"><span data-stu-id="4cd46-137">If the user not is on the list, you must enter a user ID in the **User ID** field.</span></span>  
3.  <span data-ttu-id="4cd46-138">В поле **Фильтр по центру отв. по продажам** укажите дистрибьюторский центр, в котором пользователь выполняет задачи, связанные с продажами.</span><span class="sxs-lookup"><span data-stu-id="4cd46-138">In the **Sales Resp. Ctr. Filter** field, enter the responsibility center where the user will have tasks related to sales.</span></span>  
4.  <span data-ttu-id="4cd46-139">В поле **Фильтр по центру отв. по закупкам** укажите дистрибьюторский центр, в котором пользователь выполняет задачи, связанные с покупками.</span><span class="sxs-lookup"><span data-stu-id="4cd46-139">In the **Purchase Resp. Ctr. Filter** field, enter the responsibility center where the user will have tasks related to purchasing.</span></span>  
5.  <span data-ttu-id="4cd46-140">В поле **Фильтр по центру отв. по серв. обслуж.** укажите дистрибьюторский центр, в котором пользователь выполняет задачи, связанные с сервисным управлением.</span><span class="sxs-lookup"><span data-stu-id="4cd46-140">In the **Service Resp. Ctr. Filter** field, enter the responsibility center where the user will have tasks related to service management.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="4cd46-141">Пользователи также имеют возможность просматривать все учтенные документы и операции книги, а не только те, которые относятся к их дистрибьюторским центрам.</span><span class="sxs-lookup"><span data-stu-id="4cd46-141">Users will still be able to view all posted documents and ledger entries, not just those related to their own responsibility center.</span></span>

## <a name="see-also"></a><span data-ttu-id="4cd46-142">См. также</span><span class="sxs-lookup"><span data-stu-id="4cd46-142">See Also</span></span>  
[<span data-ttu-id="4cd46-143">Настройка запасов</span><span class="sxs-lookup"><span data-stu-id="4cd46-143">Setting Up Inventory</span></span>](inventory-setup-inventory.md)  
<span data-ttu-id="4cd46-144">[Настройка управления складом](warehouse-setup-warehouse.md)
[Запасы](inventory-manage-inventory.md)[Управление складом](warehouse-manage-warehouse.md)</span><span class="sxs-lookup"><span data-stu-id="4cd46-144">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)
[Inventory](inventory-manage-inventory.md)[Warehouse Management](warehouse-manage-warehouse.md)</span></span>  
<span data-ttu-id="4cd46-145">[Управление складом](warehouse-manage-warehouse.md)  </span><span class="sxs-lookup"><span data-stu-id="4cd46-145">[Warehouse Management](warehouse-manage-warehouse.md)  </span></span>  
[<span data-ttu-id="4cd46-146">Сведения о проектировании: управление складом</span><span class="sxs-lookup"><span data-stu-id="4cd46-146">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="4cd46-147">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="4cd46-147">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
