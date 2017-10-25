---
title: "Как создавать сервисные предложения"
description: "Окно **Сервисное предложение** можно использовать, чтобы создавать документы, куда вводится информация о сервисе, например ремонте и обслуживании, для сервисных товаров по запросу клиента. Можно использовать сервисное предложение как предварительный черновик сервисного заказа, а затем преобразовать предложение в сервисный заказ."
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
ms.openlocfilehash: 2b78b8c1d4331aa8825c0d1a198fc83ed85179c8
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-service-quotes"></a><span data-ttu-id="f84d3-104">Практическое руководство. Создание сервисных предложений</span><span class="sxs-lookup"><span data-stu-id="f84d3-104">How to: Create Service Quotes</span></span>
<span data-ttu-id="f84d3-105">Сервисные предложения можно рассматривать как основу для сервисных заказов.</span><span class="sxs-lookup"><span data-stu-id="f84d3-105">You can think of service quotes as the basis for service orders.</span></span> <span data-ttu-id="f84d3-106">Фактически, они почти полностью идентичны.</span><span class="sxs-lookup"><span data-stu-id="f84d3-106">In fact, they are almost identical.</span></span> <span data-ttu-id="f84d3-107">Они содержат такие сведения, как клиент, тип заказа, товар, который требует обслуживания, сведения для выставления счетов и отгрузки, а также информацию о фактической сервисной работе.</span><span class="sxs-lookup"><span data-stu-id="f84d3-107">They both contain information such as who the customer is, the type of order, the item that needs service, billing and shipping information, and information about the actual service work.</span></span>
 
<span data-ttu-id="f84d3-108">Можно использовать сервисное предложение как предварительный черновик сервисного заказа, а затем преобразовать предложение в сервисный заказ.</span><span class="sxs-lookup"><span data-stu-id="f84d3-108">You can use a service quote as a preliminary draft for a service order, and then convert the quote to a service order.</span></span>  
  
## <a name="to-create-a-service-quote"></a><span data-ttu-id="f84d3-109">Создание сервисного предложения</span><span class="sxs-lookup"><span data-stu-id="f84d3-109">To create a service quote</span></span>  
1. <span data-ttu-id="f84d3-110">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные предложения**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f84d3-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Service Quotes**, and then choose the related link.</span></span>  
2. <span data-ttu-id="f84d3-111">Создание нового сервисного предложения.</span><span class="sxs-lookup"><span data-stu-id="f84d3-111">Create a new service quote.</span></span>  
3. <span data-ttu-id="f84d3-112">В поле **Номер**</span><span class="sxs-lookup"><span data-stu-id="f84d3-112">In the **No.**</span></span> <span data-ttu-id="f84d3-113">введите номер сервисного предложения.</span><span class="sxs-lookup"><span data-stu-id="f84d3-113">field, enter a number for the service quote.</span></span> <span data-ttu-id="f84d3-114">Вместо этого, если в окне **Сервисный центр - настройка** настроены серии номеров сервисных предложений, можно нажать клавишу ВВОД, чтобы выбрать следующий доступный номер сервисного предложения.</span><span class="sxs-lookup"><span data-stu-id="f84d3-114">Alternatively, if you have set up a number series for service quotes in the **Service Mgt. Setup** window, you can press Enter to select the next available service quote number.</span></span>  
4. <span data-ttu-id="f84d3-115">В поле **Номер клиента**</span><span class="sxs-lookup"><span data-stu-id="f84d3-115">In the **Customer No.**</span></span>  <span data-ttu-id="f84d3-116">выберите соответствующего клиента из списка.</span><span class="sxs-lookup"><span data-stu-id="f84d3-116">field, select the relevant customer from the list.</span></span>  

  > [!Note]  
  >  <span data-ttu-id="f84d3-117">Соответствующие поля для клиента заполняются автоматически данными из карточки **Клиент**.</span><span class="sxs-lookup"><span data-stu-id="f84d3-117">The customer fields are filled in automatically with information from the **Customer** card.</span></span> <span data-ttu-id="f84d3-118">Если карточка **Клиент** не существует для клиента, но шаблон клиента настроен, можно создать клиента из сервисного предложения.</span><span class="sxs-lookup"><span data-stu-id="f84d3-118">If a **Customer** card does not exist for the customer, and you have set up a customer template, you can create the customer from the service quote.</span></span> <span data-ttu-id="f84d3-119">Заполните соответствующие поля, затем выберите действие **Создать клиента**.</span><span class="sxs-lookup"><span data-stu-id="f84d3-119">Fill in the relevant fields, and then choose the **Create Customer** action.</span></span>  
  
5. <span data-ttu-id="f84d3-120">В зависимости от настроек на экспресс-вкладке **Обязательные поля**, возможно, в окне **Сервисный центр - настройка** нужно будет заполнить поля **Тип сервисного заказа** и **Код менеджера**.</span><span class="sxs-lookup"><span data-stu-id="f84d3-120">Depending on the settings on the **Mandatory Fields** FastTab in the **Service Mgt. Setup** window, you may need to fill in the **Service Order Type** field and the **Salesperson Code** field.</span></span>  
6. <span data-ttu-id="f84d3-121">Заполните строки сервисных товаров.</span><span class="sxs-lookup"><span data-stu-id="f84d3-121">Fill in the service item lines.</span></span>  
7. <span data-ttu-id="f84d3-122">Зарегистрируйте ожидаемые себестоимости в строках сервиса.</span><span class="sxs-lookup"><span data-stu-id="f84d3-122">Register estimated costs on the service lines.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="f84d3-123">См. также</span><span class="sxs-lookup"><span data-stu-id="f84d3-123">See Also</span></span>  
[<span data-ttu-id="f84d3-124">Практическое руководство. Создание сервисных заказов</span><span class="sxs-lookup"><span data-stu-id="f84d3-124">How to: Create Service Orders</span></span>](service-how-to-create-service-orders.md)  
[<span data-ttu-id="f84d3-125">Практическое руководство. Работа с сервисными задачами</span><span class="sxs-lookup"><span data-stu-id="f84d3-125">How to: Work on Service tasks</span></span>](service-how-to-work-on-service-tasks.md)  

 
