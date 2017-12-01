---
title: "Несколько контрактов"
description: "В соответствии с заключенными с клиентом соглашениями об уровне обслуживания может возникнуть необходимость работы с сервисным товаром, входящим в несколько сервисных контрактов."
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
ms.openlocfilehash: 7e3a5d897f8dded76340c51a001cb7c65e6f0a01
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="multiple-contracts"></a><span data-ttu-id="38aa9-103">Несколько контрактов</span><span class="sxs-lookup"><span data-stu-id="38aa9-103">Multiple Contracts</span></span>
<span data-ttu-id="38aa9-104">В соответствии с заключенными с клиентом соглашениями об уровне обслуживания может возникнуть необходимость работы с сервисным товаром, входящим в несколько сервисных контрактов.</span><span class="sxs-lookup"><span data-stu-id="38aa9-104">Depending on your service level agreements with a customer, you may have to handle a service item under more than one service contract.</span></span>  
  
<span data-ttu-id="38aa9-105">При работе с сервисным товаром под несколькими контрактами можно сделать следующее:</span><span class="sxs-lookup"><span data-stu-id="38aa9-105">By handling a service item under multiple contracts, you can do the following:</span></span>  
  
* <span data-ttu-id="38aa9-106">Создание различных контрактов для одного и того же сервисного товара.</span><span class="sxs-lookup"><span data-stu-id="38aa9-106">Issue different contracts for the same service item.</span></span>  
* <span data-ttu-id="38aa9-107">Обслуживать части независимо друг от друга.</span><span class="sxs-lookup"><span data-stu-id="38aa9-107">Service parts separately.</span></span>  
* <span data-ttu-id="38aa9-108">Рассматривать отдельные навыки, требуемые для обслуживания различных аспектов сервисного товара, таких как механические компоненты и программное обеспечение.</span><span class="sxs-lookup"><span data-stu-id="38aa9-108">Consider different skills that are required to service different aspects of a service item, such as mechanical components and software.</span></span>  
* <span data-ttu-id="38aa9-109">Укажите разное время отклика и частоту при обслуживании различных частей сервисного товара.</span><span class="sxs-lookup"><span data-stu-id="38aa9-109">Specify different response times and frequencies in servicing different parts of a service item.</span></span>  
* <span data-ttu-id="38aa9-110">Осуществлять различные виды работ по отношению к сервисному товару, если этому товару требуются разные типы обслуживания в разные периоды времени.</span><span class="sxs-lookup"><span data-stu-id="38aa9-110">Address different kinds of activities to be performed on a service item when the service item requires different types of service in different time periods.</span></span>  
* <span data-ttu-id="38aa9-111">Выберите и припишите строке сервисного товара подходящий номер контракта при создании сервисного заказа.</span><span class="sxs-lookup"><span data-stu-id="38aa9-111">Select and assign an appropriate contract number to a service item line when you are creating a service order.</span></span>  
* <span data-ttu-id="38aa9-112">Работа с финансовой информацией, касающейся сервисных товаров и договоров об уровне обслуживания.</span><span class="sxs-lookup"><span data-stu-id="38aa9-112">Handle relevant financial information about service items and service level agreements.</span></span>  
  
<span data-ttu-id="38aa9-113">Вот несколько примеров использования функциональных возможностей нескольких контрактов.</span><span class="sxs-lookup"><span data-stu-id="38aa9-113">You can consider the following examples of using the multiple contracts functionality.</span></span>  
  
## <a name="creating-multiple-contracts-per-service-item"></a><span data-ttu-id="38aa9-114">Создание нескольких контрактов для одного сервисного товара</span><span class="sxs-lookup"><span data-stu-id="38aa9-114">Creating Multiple Contracts per Service Item</span></span>  
<span data-ttu-id="38aa9-115">Можно вручную создать сервисный контракт или предложение по контракту для сервисных товаров, уже зарегистрированных в других не отмененных контрактах того же клиента.</span><span class="sxs-lookup"><span data-stu-id="38aa9-115">You can manually create a service contract or contract quote for service items already registered in non-canceled contracts owned by the same customer.</span></span> <span data-ttu-id="38aa9-116">Для этого достаточно выполнить стандартную процедуру создания сервисного контракта или предложения по контракту.</span><span class="sxs-lookup"><span data-stu-id="38aa9-116">To do this, follow the standard procedure of creating service contracts and service contract quotes.</span></span> <span data-ttu-id="38aa9-117">Дополнительные сведения см. в разделе [Практическое руководство. Работа с сервисными контрактами и предложениями по сервисному контракту](service-how-to-create-service-contracts-and-service-contract-quotes.md).</span><span class="sxs-lookup"><span data-stu-id="38aa9-117">For more information, see [How to: Work with Service Contracts and Service Contract Quotes](service-how-to-create-service-contracts-and-service-contract-quotes.md).</span></span>  
  
<span data-ttu-id="38aa9-118">При добавлении в строку контракта сервисного товара, который уже зарегистрирован в другом сервисном контракте или предложении по контракту, на экран выводится предупреждение о том, что данный сервисный товар уже принадлежит одному или нескольким сервисным контрактам или предложениям по контракту.</span><span class="sxs-lookup"><span data-stu-id="38aa9-118">When you add a service item on a contract line that is registered in other service contracts or contract quotes, a warning message is displayed stating that the service item already belongs to one or more service contracts or contract quotes.</span></span> <span data-ttu-id="38aa9-119">Если ответить на предупреждение утвердительно, вся относящаяся к данному сервисному товару информация будет скопирована в только что созданную строку контракта.</span><span class="sxs-lookup"><span data-stu-id="38aa9-119">If you confirm this message, all relevant service item information is copied to a newly created contract line.</span></span>  
  
## <a name="copying-documents"></a><span data-ttu-id="38aa9-120">Копирование документов</span><span class="sxs-lookup"><span data-stu-id="38aa9-120">Copying Documents</span></span>  
<span data-ttu-id="38aa9-121">Можно автоматически создать сервисный контракт или предложение по контракту для сервисных товаров, уже зарегистрированных в других сервисных контрактах или сервисных предложениях, с помощью действия **Копировать документ**.</span><span class="sxs-lookup"><span data-stu-id="38aa9-121">You can automatically create a service contract or contract quote for service items that are already registered in other service contracts or contract quotes by using the **Copy Document** action.</span></span>  
  
## <a name="creating-service-orders-for-multiple-contracts"></a><span data-ttu-id="38aa9-122">Создание сервисных заказов для нескольких контрактов</span><span class="sxs-lookup"><span data-stu-id="38aa9-122">Creating Service Orders for Multiple Contracts</span></span>  
<span data-ttu-id="38aa9-123">Можно вручную создать сервисный заказ для сервисного товара, зарегистрированного в нескольких активных контрактах.</span><span class="sxs-lookup"><span data-stu-id="38aa9-123">You can manually create a service order for a service item that is registered in multiple active contracts.</span></span> <span data-ttu-id="38aa9-124">Сервисный контракт считается активным, когда он подписан и не просрочен.</span><span class="sxs-lookup"><span data-stu-id="38aa9-124">A service contract is active when it is signed and not expired.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="38aa9-125">См. также</span><span class="sxs-lookup"><span data-stu-id="38aa9-125">See Also</span></span>  
[<span data-ttu-id="38aa9-126">Выполнение контрактов на обслуживание</span><span class="sxs-lookup"><span data-stu-id="38aa9-126">Fulfilling Service Contracts</span></span>](service-fulfill-service-contracts.md)  
[<span data-ttu-id="38aa9-127">Практическое руководство. Создание сервисных заказов</span><span class="sxs-lookup"><span data-stu-id="38aa9-127">How to: Create Service Orders</span></span>](service-how-to-create-service-orders.md)  

