---
title: "Настройка Dynamics NAV с помощью расширений"
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: cc832772a255c7c801a7b956c74da827caca3765
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="customizing-dynamics-nav-using-extensions"></a><span data-ttu-id="7afdc-102">Настройка Dynamics NAV с помощью расширений</span><span class="sxs-lookup"><span data-stu-id="7afdc-102">Customizing Dynamics NAV Using Extensions</span></span>
<span data-ttu-id="7afdc-103">Вы можете изменить Dynamics NAV за счет установки расширений, которые добавляют функциональность, изменяют поведение или, например, предоставляют доступ к новым интернет-службам.</span><span class="sxs-lookup"><span data-stu-id="7afdc-103">You can change Dynamics NAV by installing extensions that add functionality, change behavior, or give you access to new online services, for example.</span></span>
<span data-ttu-id="7afdc-104">При первом запуске Dynamics NAV некоторые расширения уже установлены.</span><span class="sxs-lookup"><span data-stu-id="7afdc-104">When you first launch Dynamics NAV, some extensions are already installed for you.</span></span> <span data-ttu-id="7afdc-105">Со временем вам могут стать доступны дополнительные расширения, и вы сможете выбрать, хотите ли вы использовать эти расширения.</span><span class="sxs-lookup"><span data-stu-id="7afdc-105">Over time, more extensions can be made available to you, and you can then choose if you want to use the extension or not.</span></span>

<span data-ttu-id="7afdc-106">Например, корпорация Майкрософт предлагает расширение, которое обеспечивает интеграцию с PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="7afdc-106">For example, Microsoft provides an extension that provides integration with PayPal Payments Standard.</span></span> <span data-ttu-id="7afdc-107">Это расширение установлено по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7afdc-107">This extension is installed by default.</span></span>
<span data-ttu-id="7afdc-108">Но если появится другое расширение, предлагающее интеграцию с другой службой платежей, вы можете установить его и выбрать службу платежей для использования.</span><span class="sxs-lookup"><span data-stu-id="7afdc-108">But if another extension is made available that offers integration with another payment service, you can install the new extension and then choose which of the two services to use.</span></span>  

<span data-ttu-id="7afdc-109">Управление расширениями осуществляется в окне **Управление расширениями**.</span><span class="sxs-lookup"><span data-stu-id="7afdc-109">You manage the extensions in the **Extension Management** window.</span></span> <span data-ttu-id="7afdc-110">Это окно доступно с начальной страницы.</span><span class="sxs-lookup"><span data-stu-id="7afdc-110">You can access this window from Home.</span></span> <span data-ttu-id="7afdc-111">Кроме того, вы можете выбрать значок **Поиск страницы или отчета** в правом верхнем углу, ввести **Расширение**, а затем выбрать связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="7afdc-111">Alternatively, choose the **Search for Page or Report** icon in the top right corner, enter **Extension**, and then choose the related link.</span></span>   

## <a name="installing-an-extension"></a><span data-ttu-id="7afdc-112">Установка расширения</span><span class="sxs-lookup"><span data-stu-id="7afdc-112">Installing an Extension</span></span>
<span data-ttu-id="7afdc-113">Если новые расширения стали доступны вам, поскольку они были опубликованы на вашем сервере, они будут показаны в окне **Управление расширениями**.</span><span class="sxs-lookup"><span data-stu-id="7afdc-113">If new extensions are made available to you because they have been published to your server, they will be shown in the **Extension Management** window.</span></span> <span data-ttu-id="7afdc-114">Отсюда можно выбрать, следует ли установить и удалить расширения.</span><span class="sxs-lookup"><span data-stu-id="7afdc-114">From here, you can choose to install and uninstall extensions.</span></span>  

<span data-ttu-id="7afdc-115">Если вы выберите расширение, вы можете прочитать о его возможностях и открыть справку по расширению для получения более подробной информации.</span><span class="sxs-lookup"><span data-stu-id="7afdc-115">If you choose an extension, you can read about what the extension does, and you can access Help for the extension to learn more.</span></span> <span data-ttu-id="7afdc-116">Если вы хотите получить расширение, необходимо согласиться с условиями использования.</span><span class="sxs-lookup"><span data-stu-id="7afdc-116">When you choose to get an extension, you must agree to the terms of use.</span></span>  

<span data-ttu-id="7afdc-117">При установке расширения может потребоваться настроить его, например указать учетную запись для использования расширения **PayPal Payments Standard для Dynamics NAV**.</span><span class="sxs-lookup"><span data-stu-id="7afdc-117">When you install an extension, you might have to set it up, such as specifying an account for use with the **PayPal Payments Standard for Dynamics NAV** extension.</span></span>
<span data-ttu-id="7afdc-118">Другие расширения просто добавляют поля на существующую страницу или добавляют новую страницу.</span><span class="sxs-lookup"><span data-stu-id="7afdc-118">Other extensions simply add fields to an existing page, or they add a new page, for example.</span></span>   

<span data-ttu-id="7afdc-119">Если вы удалили расширение, а потом передумали, вы можете снова установить его.</span><span class="sxs-lookup"><span data-stu-id="7afdc-119">If you uninstall an extension, and you then change your mind, you can install it again.</span></span> <span data-ttu-id="7afdc-120">При удалении расширения, которое вы использовали, данные сохраняются, чтобы вы могли установить его снова и данные были по-прежнему доступны.</span><span class="sxs-lookup"><span data-stu-id="7afdc-120">When you uninstall an extension that you have been using, the data is preserved so that if you install the extension again, your data is still available.</span></span>  

<span data-ttu-id="7afdc-121">Корпорация Майкрософт предоставляет следующие расширения:</span><span class="sxs-lookup"><span data-stu-id="7afdc-121">Microsoft provides the following extensions:</span></span>  
- [<span data-ttu-id="7afdc-122">PayPal Payments Standard</span><span class="sxs-lookup"><span data-stu-id="7afdc-122">PayPal Payments Standard</span></span>](ui-extensions-paypal-payments-standard.md)  
- [<span data-ttu-id="7afdc-123">Прогноз запасов и продаж</span><span class="sxs-lookup"><span data-stu-id="7afdc-123">Sales and Inventory Forecast</span></span>](ui-extensions-sales-forecast.md)  

<span data-ttu-id="7afdc-124">Другие расширения также доступны по умолчанию, в зависимости из вашей страны или региона.</span><span class="sxs-lookup"><span data-stu-id="7afdc-124">Other extensions are also available by default, depending on your country/region.</span></span>

## <a name="see-also"></a><span data-ttu-id="7afdc-125">См. также</span><span class="sxs-lookup"><span data-stu-id="7afdc-125">See Also</span></span>  
[<span data-ttu-id="7afdc-126">Практическое руководство. Включение платежей клиентов через PayPal</span><span class="sxs-lookup"><span data-stu-id="7afdc-126">How to: Enable Customer Payment Through PayPal</span></span>](sales-how-enable-customer-payments-paypal.md)  
[<span data-ttu-id="7afdc-127">Добро пожаловать в Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="7afdc-127">Welcome to Dynamics NAV</span></span>](across-get-started.md)  

