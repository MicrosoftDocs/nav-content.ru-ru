---
title: "Включение платежей клиентов через службу платежей"
description: "Облегчите клиентам оплату счетов, включив службы платежей."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: online payment
ms.date: 07/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: ed26ab9e5f1f3c374a6dd15fbed5917720c3010b
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-enable-customer-payments-through-payment-services"></a><span data-ttu-id="aae4c-103">Практическое руководство. Включение платежей клиентов через службу платежей</span><span class="sxs-lookup"><span data-stu-id="aae4c-103">How to: Enable Customer Payments Through Payment Services</span></span>
<span data-ttu-id="aae4c-104">В качестве альтернативы сбору платежей через банковские переводы или кредитные карты вы можете предложить клиентам оплату через учетную запись в службе платежей, например PayPal или WorldPay.</span><span class="sxs-lookup"><span data-stu-id="aae4c-104">As an alternative to collecting payments through bank transfer or credit cards, your customers can pay you through their account with payment services, such as PayPal and WorldPay.</span></span>  

<span data-ttu-id="aae4c-105">После включения службы платежей в [!INCLUDE[d365fin](includes/d365fin_md.md)] станет доступна ссылка на службу в документах продажи, отправляемых по электронной почте клиентам.</span><span class="sxs-lookup"><span data-stu-id="aae4c-105">After you enable a payment service in [!INCLUDE[d365fin](includes/d365fin_md.md)], a link to the service is available on sales documents that you send by email to your customers.</span></span> <span data-ttu-id="aae4c-106">Клиенты могут использовать эту ссылку для перехода к службе платежей и оплаты счетов непосредственно из документа продажи.</span><span class="sxs-lookup"><span data-stu-id="aae4c-106">Customers can use the link to go to the payment service and pay the bill, directly from the sales document.</span></span> <span data-ttu-id="aae4c-107">Если не требуется включать ссылку, например если клиент платит наличными деньгами, можно удалить службу платежей из счета до учета.</span><span class="sxs-lookup"><span data-stu-id="aae4c-107">If you don't want to include the link, for example, if a customer will pay with cash, you can remove the payment service from the invoice before posting.</span></span>  

<span data-ttu-id="aae4c-108">Расширения PayPal Payments Standard и WorldPay Payments Standard установлены в [!INCLUDE[d365fin](includes/d365fin_md.md)] и готовы к включению.</span><span class="sxs-lookup"><span data-stu-id="aae4c-108">The PayPal Payments Standard and WorldPay Payments Standard extensions are installed in [!INCLUDE[d365fin](includes/d365fin_md.md)], and are ready for you to enable.</span></span>  

## <a name="to-enable-a-payment-service-in-included365finincludesd365finmdmd"></a><span data-ttu-id="aae4c-109">Включение службы платежей в [!INCLUDE[d365fin](includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="aae4c-109">To enable a payment service in [!INCLUDE[d365fin](includes/d365fin_md.md)]</span></span>
1. <span data-ttu-id="aae4c-110">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Службы платежей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="aae4c-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="aae4c-111">В окне **Службы платежей** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="aae4c-111">In the **Payment Services** window, choose the **New** action.</span></span>  
3. <span data-ttu-id="aae4c-112">Выберите службу платежей, а затем закройте окно.</span><span class="sxs-lookup"><span data-stu-id="aae4c-112">Select the payment service, and then close the window.</span></span>  
4. <span data-ttu-id="aae4c-113">В окне **Службы платежей** выберите действие **Настройка**.</span><span class="sxs-lookup"><span data-stu-id="aae4c-113">In the **Payment Services** window, choose the **Setup** action.</span></span>  
5. <span data-ttu-id="aae4c-114">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="aae4c-114">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
6. <span data-ttu-id="aae4c-115">Закройте данное окно.</span><span class="sxs-lookup"><span data-stu-id="aae4c-115">Close the window.</span></span>  

## <a name="to-select-a-payment-service-on-a-sales-invoice"></a><span data-ttu-id="aae4c-116">Выбор службы платежей в счете продажи</span><span class="sxs-lookup"><span data-stu-id="aae4c-116">To select a payment service on a sales invoice</span></span>
1. <span data-ttu-id="aae4c-117">На начальной странице выберите **Счета продажи**.</span><span class="sxs-lookup"><span data-stu-id="aae4c-117">On the Home page, choose **Sales Invoices**.</span></span>  
2. <span data-ttu-id="aae4c-118">Откройте счет продажи, который необходимо оплатить с помощью службы платежей.</span><span class="sxs-lookup"><span data-stu-id="aae4c-118">Open the sales invoice that you want to pay by using the payment service.</span></span>  
3. <span data-ttu-id="aae4c-119">В поле **Служба платежей** выберите службу платежей.</span><span class="sxs-lookup"><span data-stu-id="aae4c-119">In the **Payment Service** field, choose the payment service.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="aae4c-120">Поле **Служба платежей** доступно, только если включена служба платежей.</span><span class="sxs-lookup"><span data-stu-id="aae4c-120">The **Payment Service** field is available only if you've enabled the payment service.</span></span>  

## <a name="see-also"></a><span data-ttu-id="aae4c-121">См. также</span><span class="sxs-lookup"><span data-stu-id="aae4c-121">See Also</span></span>  
[<span data-ttu-id="aae4c-122">Настройка продаж</span><span class="sxs-lookup"><span data-stu-id="aae4c-122">Setting Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="aae4c-123">Продажи</span><span class="sxs-lookup"><span data-stu-id="aae4c-123">Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="aae4c-124">[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="aae4c-124">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  
<span data-ttu-id="aae4c-125">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="aae4c-125">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
