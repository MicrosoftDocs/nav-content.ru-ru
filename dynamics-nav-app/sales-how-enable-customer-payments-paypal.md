---
title: "Практическое руководство. Включение платежей клиентов через PayPal"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="3f6e3-102">Практическое руководство. Включение платежей клиентов через PayPal#</span><span class="sxs-lookup"><span data-stu-id="3f6e3-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="3f6e3-103">В качестве альтернативы сбору платежей через банковские переводы или кредитные карты вы можете предложить клиентам оплату через учетную запись PayPal.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="3f6e3-104">Когда клиент выбирает в счете продажи или в документе заказа на продажу ссылку PayPal, открывается страница сервиса для его учетной записи PayPal, содержащая сведения об оплате этой продажи.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="3f6e3-105">Затем клиент может оплатить счет как любой другой платеж PayPal.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="3f6e3-106">Чтобы включить для клиентов платежи через PayPal, необходимо сделать следующее:</span><span class="sxs-lookup"><span data-stu-id="3f6e3-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="3f6e3-107">Настройте PayPal Payments Standard в качестве службы платежей в окне **Службы платежей**.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="3f6e3-108">Выберите PayPal Payments Standard в поле **Служба платежей** в нужном документе продажи.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="3f6e3-109">Служба PayPal Payments Standard устанавливается в качестве расширения к Dynamics NAV и готова к включению.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="3f6e3-110">Дополнительные сведения см. в разделе [Настройка Dynamics NAV с помощью расширений](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="3f6e3-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="3f6e3-111">Включение службы PayPal Payments Standard</span><span class="sxs-lookup"><span data-stu-id="3f6e3-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="3f6e3-112">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Службы платежей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="3f6e3-113">В окне **Службы платежей** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="3f6e3-114">Выберите **PayPal Standard**, затем закройте окно.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="3f6e3-115">В окне **Службы платежей** выберите действие **Настройка**.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="3f6e3-116">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="3f6e3-117">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="3f6e3-118">**Примечание**. Установите флажок **Всегда включать в документы**, если гиперссылка службы платежей PayPal должна всегда отображаться в документах продажи, для которых включена оплата через PayPal.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="3f6e3-119">Закройте окно.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="3f6e3-120">Выбор PayPal Payments Standard в счете продажи</span><span class="sxs-lookup"><span data-stu-id="3f6e3-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="3f6e3-121">На начальной странице выберите **Счета продажи**.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="3f6e3-122">Откройте счет продажи, для которого требуется включить платежи PayPal.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="3f6e3-123">В поле **Служба платежей** выберите PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="3f6e3-124">**Примечание**. Поле **Служба платежей** видимо, только если служба PayPal Payments Standard включена.</span><span class="sxs-lookup"><span data-stu-id="3f6e3-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="3f6e3-125">См. также</span><span class="sxs-lookup"><span data-stu-id="3f6e3-125">See Also</span></span>  
[<span data-ttu-id="3f6e3-126">Настройка продаж</span><span class="sxs-lookup"><span data-stu-id="3f6e3-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="3f6e3-127">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="3f6e3-127">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="3f6e3-128">Настройка Dynamics NAV с помощью расширений</span><span class="sxs-lookup"><span data-stu-id="3f6e3-128">Customizing Dynamics NAV Using Extensions</span></span>](ui-extensions.md)

