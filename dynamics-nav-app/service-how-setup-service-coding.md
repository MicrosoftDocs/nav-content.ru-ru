---
title: "Настройка кодов для стандартных сервисов"
description: "Узнайте, как настроить коды для часто выполняемых сервисных работ."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: service, service item, service order, repairs, maintenance
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 109e71ab1b06ccbe0a931a998ae0681713eff9da
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-standard-service-codes"></a><span data-ttu-id="16459-103">Практическое руководство. Настройка стандартных сервисных кодов</span><span class="sxs-lookup"><span data-stu-id="16459-103">How to: Set Up Standard Service Codes</span></span>
<span data-ttu-id="16459-104">При выполнении типичных сервисных операций часто необходимо создавать сервисные документы, в которых сервисные строки содержат похожую информацию.</span><span class="sxs-lookup"><span data-stu-id="16459-104">When you perform typical service, you often have to create service documents that use service lines that contain similar information.</span></span> <span data-ttu-id="16459-105">Чтобы упростить создание этих строк, можно настроить стандартные сервисные коды, имеющие заранее заданный набор сервисных строк.</span><span class="sxs-lookup"><span data-stu-id="16459-105">To make it easy to create these lines, you can set up standard service codes that have a predefined set of service lines.</span></span> <span data-ttu-id="16459-106">При выборе кода в сервисном документе эти строки вводятся автоматически.</span><span class="sxs-lookup"><span data-stu-id="16459-106">When you choose the code on a service document, the lines are entered automatically.</span></span> <span data-ttu-id="16459-107">Можно настроить любое количество стандартных сервисных кодов, и с каждым кодом можно связать неограниченное количество сервисных строк различных типов, включая товар, ресурс, себестоимость или стандартный текст.</span><span class="sxs-lookup"><span data-stu-id="16459-107">You can set up any number of standard service codes, and each code can have an unlimited number of service lines of different types, including item, resource, cost, or standrd text linked to it.</span></span> <span data-ttu-id="16459-108">Сервисные строки для каждого стандартного сервисного кода создаются на карточке **Стандартный сервисный код**.</span><span class="sxs-lookup"><span data-stu-id="16459-108">You create service lines of each standard serice code on the **Standard Service Code** card.</span></span> <span data-ttu-id="16459-109">Можно присвоить стандартные сервисные коды группам сервисных товаров на странице **Станд. коды групп серв. товаров**.</span><span class="sxs-lookup"><span data-stu-id="16459-109">You then assign standard service codes to service item groups on the **Standard Serv. Item Gr. Codes** page.</span></span> <span data-ttu-id="16459-110">Позднее при создании сервисного документа можно использовать действие **Получить стандартные коды сервиса** для добавления сервисных строк.</span><span class="sxs-lookup"><span data-stu-id="16459-110">Later, when you create a service document, you can use the **Get Standard Service Codes** action to add service lines.</span></span>  
  
> [!Tip]
>  <span data-ttu-id="16459-111">Можно использовать эту же концепцию для создания строк в документах продажи и покупки.</span><span class="sxs-lookup"><span data-stu-id="16459-111">You can use the same concept to create lines on sales and purchase documents.</span></span> <span data-ttu-id="16459-112">Дополнительные сведения см. в разделе [Практическое руководство. Создание типовых строк продажи и покупки](sales-how-work-standard-lines.md).</span><span class="sxs-lookup"><span data-stu-id="16459-112">For more information, see [How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md).</span></span>    
  
## <a name="to-set-up-a-standard-service-code"></a><span data-ttu-id="16459-113">Настройка стандартного сервисного кода</span><span class="sxs-lookup"><span data-stu-id="16459-113">To set up a standard service code</span></span>    
1. <span data-ttu-id="16459-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Стандартные коды сервиса**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="16459-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Standard Service Codes**, and then choose the related link.</span></span>  
2. <span data-ttu-id="16459-115">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="16459-115">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
4. <span data-ttu-id="16459-116">Заполните строки сервиса, связанные с данным сервисным кодом.</span><span class="sxs-lookup"><span data-stu-id="16459-116">Fill in the service lines linked to this service code.</span></span>  

## <a name="to-assign-a-standard-service-code-to-a-service-item-group"></a><span data-ttu-id="16459-117">Присвоение стандартного сервисного кода группе сервисных товаров</span><span class="sxs-lookup"><span data-stu-id="16459-117">To assign a standard service code to a service item group</span></span>
1. <span data-ttu-id="16459-118">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Группы сервисных товаров**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="16459-118">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Service item Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="16459-119">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="16459-119">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. <span data-ttu-id="16459-120">Заполните строки сервиса, связанные с данным сервисным кодом.</span><span class="sxs-lookup"><span data-stu-id="16459-120">Fill in the service lines linked to this service code.</span></span>  

## <a name="see-also"></a><span data-ttu-id="16459-121">См. также</span><span class="sxs-lookup"><span data-stu-id="16459-121">See Also</span></span>
[<span data-ttu-id="16459-122">Сервисный центр</span><span class="sxs-lookup"><span data-stu-id="16459-122">Service Management</span></span>](service-service.md)
