---
title: "Практическое руководство. Включение платежей клиентов через PayPal"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 92b00332f3fb5adff12d518ca2af4aa4093fbf7a
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="db66c-102">Практическое руководство. Включение платежей клиентов через PayPal#</span><span class="sxs-lookup"><span data-stu-id="db66c-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="db66c-103">В качестве альтернативы сбору платежей через банковские переводы или кредитные карты вы можете предложить клиентам оплату через учетную запись PayPal.</span><span class="sxs-lookup"><span data-stu-id="db66c-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="db66c-104">Когда клиент выбирает в счете продажи или в документе заказа на продажу ссылку PayPal, открывается страница сервиса для его учетной записи PayPal, содержащая сведения об оплате этой продажи.</span><span class="sxs-lookup"><span data-stu-id="db66c-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="db66c-105">Затем клиент может оплатить счет как любой другой платеж PayPal.</span><span class="sxs-lookup"><span data-stu-id="db66c-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="db66c-106">Чтобы включить для клиентов платежи через PayPal, необходимо сделать следующее:</span><span class="sxs-lookup"><span data-stu-id="db66c-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="db66c-107">Настройте PayPal Payments Standard в качестве службы платежей в окне **Службы платежей**.</span><span class="sxs-lookup"><span data-stu-id="db66c-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="db66c-108">Выберите PayPal Payments Standard в поле **Служба платежей** в нужном документе продажи.</span><span class="sxs-lookup"><span data-stu-id="db66c-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="db66c-109">Служба стандарта платежей PayPal устанавливается в качестве расширения к Dynamics NAV и готова к включению.</span><span class="sxs-lookup"><span data-stu-id="db66c-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="db66c-110">Дополнительные сведения см. в разделе [Настройка Dynamics NAV с помощью расширений](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="db66c-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="db66c-111">Включение службы PayPal Payments Standard</span><span class="sxs-lookup"><span data-stu-id="db66c-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="db66c-112">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Службы платежей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="db66c-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="db66c-113">В окне **Службы платежей** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="db66c-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="db66c-114">Выберите **PayPal Standard**, затем закройте окно.</span><span class="sxs-lookup"><span data-stu-id="db66c-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="db66c-115">В окне **Службы платежей** выберите действие **Настройка**.</span><span class="sxs-lookup"><span data-stu-id="db66c-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="db66c-116">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="db66c-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="db66c-117">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="db66c-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="db66c-118">**Примечание**. Установите флажок **Всегда включать в документы**, если гиперссылка службы платежей PayPal должна всегда отображаться в документах продажи, для которых включена оплата через PayPal.</span><span class="sxs-lookup"><span data-stu-id="db66c-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="db66c-119">Закройте окно.</span><span class="sxs-lookup"><span data-stu-id="db66c-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="db66c-120">Выбор PayPal Payments Standard в счете продажи</span><span class="sxs-lookup"><span data-stu-id="db66c-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="db66c-121">На начальной странице выберите **Счета продажи**.</span><span class="sxs-lookup"><span data-stu-id="db66c-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="db66c-122">Откройте счет продажи, для которого требуется включить платежи PayPal.</span><span class="sxs-lookup"><span data-stu-id="db66c-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="db66c-123">В поле **Служба платежей** выберите PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="db66c-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="db66c-124">**Примечание**. Поле **Служба платежей** видимо, только если служба PayPal Payments Standard включена.</span><span class="sxs-lookup"><span data-stu-id="db66c-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="db66c-125">См. также</span><span class="sxs-lookup"><span data-stu-id="db66c-125">See Also</span></span>  
[<span data-ttu-id="db66c-126">Настройка продаж</span><span class="sxs-lookup"><span data-stu-id="db66c-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="db66c-127">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="db66c-127">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="db66c-128">Настройка Dynamics NAV с помощью расширений</span><span class="sxs-lookup"><span data-stu-id="db66c-128">Customizing Dynamics NAV Using Extensions</span></span>](ui-extensions.md)

