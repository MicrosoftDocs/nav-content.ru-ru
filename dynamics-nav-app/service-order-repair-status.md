---
title: "Как настраивать статусы для сервисных заказов и ремонтных работ"
description: "Необходимо настроить девять параметров статуса ремонта, которые указывают продвижение ремонта и обслуживания сервисных товаров в сервисных заказах."
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
ms.openlocfilehash: d7dbc4cfc06d4c74476a04512bd368a0ab26f837
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-statuses-for-service-orders-and-repairs"></a><span data-ttu-id="9dec4-103">Практическое руководство. Настройка статусов для сервисных заказов и ремонтных работ</span><span class="sxs-lookup"><span data-stu-id="9dec4-103">How to: Set Up Statuses for Service Orders and Repairs</span></span>
<span data-ttu-id="9dec4-104">Необходимо настроить параметры статуса ремонта, которые указывают продвижение ремонта и обслуживания сервисных товаров в сервисных заказах.</span><span class="sxs-lookup"><span data-stu-id="9dec4-104">You must set up repair status options that identify the progress of repair and maintenance of service items in service orders.</span></span> <span data-ttu-id="9dec4-105">Необходимо настроить по крайней мере девять параметров статуса ремонта, указывающих ситуации или действия, производимые с сервисными товарами.</span><span class="sxs-lookup"><span data-stu-id="9dec4-105">You must set up at least nine repair status options that identify situations or actions taken when servicing service items.</span></span>  

<span data-ttu-id="9dec4-106">Можно задать уровень приоритета для параметров статуса сервисного заказа.</span><span class="sxs-lookup"><span data-stu-id="9dec4-106">You can set the priority level for service order status options.</span></span> <span data-ttu-id="9dec4-107">Имеется четыре приоритета: "Высокий", "Выше Среднего", "Ниже Среднего" и "Низкий".</span><span class="sxs-lookup"><span data-stu-id="9dec4-107">There four priorities are High, Medium High, Medium Low, and Low.</span></span>  
  
<span data-ttu-id="9dec4-108">При изменении статуса ремонта сервисного товара в сервисном заказе статус сервисного заказа обновляется.</span><span class="sxs-lookup"><span data-stu-id="9dec4-108">When you change the repair status of a service item in a service order, the service order status is updated.</span></span> <span data-ttu-id="9dec4-109">Статус ремонта каждого сервисного товара связан со статусом сервисного заказа.</span><span class="sxs-lookup"><span data-stu-id="9dec4-109">The repair status of each service item is linked to the service order status.</span></span> <span data-ttu-id="9dec4-110">Если сервисные товары связаны с двумя или более параметрами статуса сервисного заказа, то выбирается статус сервисного заказа с наиболее высоким приоритетом.</span><span class="sxs-lookup"><span data-stu-id="9dec4-110">If the service items are linked to two or more service order status options, the service order status with the highest priority is selected.</span></span>  

## <a name="to-set-up-a-repair-status"></a><span data-ttu-id="9dec4-111">Настройка статуса ремонта</span><span class="sxs-lookup"><span data-stu-id="9dec4-111">To set up a repair status</span></span>  
1. <span data-ttu-id="9dec4-112">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Статус ремонта**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9dec4-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Repair Status**, and then choose the related link.</span></span> <span data-ttu-id="9dec4-113">2.</span><span class="sxs-lookup"><span data-stu-id="9dec4-113">2.</span></span> <span data-ttu-id="9dec4-114">Создать новый статус ремонта.</span><span class="sxs-lookup"><span data-stu-id="9dec4-114">Create a new repair status.</span></span>  
3. <span data-ttu-id="9dec4-115">Заполните поля **Код** и **Описание**.</span><span class="sxs-lookup"><span data-stu-id="9dec4-115">Fill in the **Code** and **Description** fields.</span></span>  
4. <span data-ttu-id="9dec4-116">В поле **Статус сервисного заказа** выберите статус заказа, с которым требуется связать статус ремонта.</span><span class="sxs-lookup"><span data-stu-id="9dec4-116">In the **Service Order Status** field, choose the order status to link the repair status to.</span></span> <span data-ttu-id="9dec4-117">В поле **Приоритет** отображается приоритет выбранного статуса сервисного заказа.</span><span class="sxs-lookup"><span data-stu-id="9dec4-117">The **Priority** field displays the priority of the service order status you have chosen.</span></span>  
5. <span data-ttu-id="9dec4-118">Выберите статус ремонта.</span><span class="sxs-lookup"><span data-stu-id="9dec4-118">Choose a repair status.</span></span> <span data-ttu-id="9dec4-119">Можно выбрать только один.</span><span class="sxs-lookup"><span data-stu-id="9dec4-119">You can choose only one.</span></span>  
6. <span data-ttu-id="9dec4-120">Выберите поле **Учет разрешен**, чтобы можно было учитывать сервисные заказы с этим статусом ремонта, включая сервисные товары.</span><span class="sxs-lookup"><span data-stu-id="9dec4-120">To be able to post service orders, including service items, with this repair status, choose the **Posting Allowed** field.</span></span>  
7. <span data-ttu-id="9dec4-121">Выберите флажок **Статус ожидания разрешен**, чтобы иметь возможность менять вручную параметр статуса сервисного заказа на **Ожидание** в сервисных заказах с этим статусом ремонта, включая сервисные товары.</span><span class="sxs-lookup"><span data-stu-id="9dec4-121">To be able to manually change the service order status option to **Pending** in service orders including service items with this repair status, choose the **Pending Status Allowed** check box.</span></span>  
8. <span data-ttu-id="9dec4-122">Выберите флажки **Статус В работе разрешен**, **Статус Завершено разрешен** и **Статус На удержании разрешен** таким же образом.</span><span class="sxs-lookup"><span data-stu-id="9dec4-122">Choose the **In Process Status Allowed**, **Finished Status Allowed**, and **On Hold Status Allowed** check boxes in the same way.</span></span>
  
## <a name="to-set-up-service-status-priorities"></a><span data-ttu-id="9dec4-123">Настройка приоритетов сервисных статусов</span><span class="sxs-lookup"><span data-stu-id="9dec4-123">To set up service status priorities</span></span>  
1. <span data-ttu-id="9dec4-124">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Статус сервисного заказа**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9dec4-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Service Order Status**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9dec4-125">Выберите статус сервисного заказа, которому необходимо назначить приоритет.</span><span class="sxs-lookup"><span data-stu-id="9dec4-125">Select the service order status you want to set a priority for.</span></span>  
3. <span data-ttu-id="9dec4-126">В поле **Приоритет** выберите тот приоритет, который хотите назначить этому статусу сервисного заказа.</span><span class="sxs-lookup"><span data-stu-id="9dec4-126">In the **Priority** field, choose the priority you want for this service order status.</span></span> <span data-ttu-id="9dec4-127">Повторите этот шаг для каждого статуса.</span><span class="sxs-lookup"><span data-stu-id="9dec4-127">Repeat this step for each status.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="9dec4-128">См. также</span><span class="sxs-lookup"><span data-stu-id="9dec4-128">See Also</span></span>  
[<span data-ttu-id="9dec4-129">Статус сервисного заказа и статус ремонта</span><span class="sxs-lookup"><span data-stu-id="9dec4-129">Understanding Service Order Status and Repair Status</span></span>]()  
[<span data-ttu-id="9dec4-130">Настройка управления сервисным обслуживанием</span><span class="sxs-lookup"><span data-stu-id="9dec4-130">Setting Up Service Management</span></span>](service-setup-service.md)  

