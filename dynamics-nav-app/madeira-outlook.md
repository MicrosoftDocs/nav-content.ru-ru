---
title: "Использование Dynamics NAV с Outlook"
description: "Dynamics NAV обладает глубокой интеграцией с Office 365, что позволяет вам вести бизнес и взаимодействовать по электронной почте с клиентами и поставщиками непосредственно из Outlook."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: get-started-article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: SMTP, mail, Office 365
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 832f07d5419f9dbb02059bd412563e2087c9b791
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="using-dynamics-nav-as-your-business-inbox-in-outlook"></a><span data-ttu-id="3edf6-103">Использование Dynamics NAV в качестве рабочего почтового ящика в Outlook</span><span class="sxs-lookup"><span data-stu-id="3edf6-103">Using Dynamics NAV as your Business Inbox in Outlook</span></span>
<span data-ttu-id="3edf6-104">В [!INCLUDE[d365fin](includes/d365fin_md.md)] появилась возможность управления бизнес-взаимодействиями с клиентами и поставщиками непосредственно в Microsoft Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-104">[!INCLUDE[d365fin](includes/d365fin_md.md)] introduces the ability to manage business interactions with your customers and vendors, directly in Microsoft Outlook.</span></span> <span data-ttu-id="3edf6-105">С помощью надстроек [!INCLUDE[d365fin](includes/d365fin_md.md)] Outlook вы можете просматривать финансовые данные, связанные с клиентами и поставщиками, а также создавать и отправлять финансовые документы, такие как предложения и счета.</span><span class="sxs-lookup"><span data-stu-id="3edf6-105">With the [!INCLUDE[d365fin](includes/d365fin_md.md)] Outlook add-ins, you can see financial data related to customers and vendors, as well as create and send financial documents, such as quotes and invoices.</span></span>  

## <a name="get-the-add-in"></a><span data-ttu-id="3edf6-106">Получение надстройки</span><span class="sxs-lookup"><span data-stu-id="3edf6-106">Get the add-in</span></span>
<span data-ttu-id="3edf6-107">В [!INCLUDE[d365fin](includes/d365fin_md.md)] один из шагов по сопровождаемой настройки "Приступая к работе" выполняется в окне **Управление бизнесом из Office 365**.</span><span class="sxs-lookup"><span data-stu-id="3edf6-107">In [!INCLUDE[d365fin](includes/d365fin_md.md)], one of the steps in the Getting Started assisted setup is the **Run your business within Office 365** window.</span></span> <span data-ttu-id="3edf6-108">В этом окне при нажатии кнопки **Настроить в Outlook** вы должны указать имя пользователя и пароль для Office 365.</span><span class="sxs-lookup"><span data-stu-id="3edf6-108">In that window, when you choose the **Set up in Outlook** button, you must specify your Office 365 user name and password.</span></span> <span data-ttu-id="3edf6-109">После этого надстройки [!INCLUDE[d365fin](includes/d365fin_md.md)] будут автоматически добавлены в Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-109">The [!INCLUDE[d365fin](includes/d365fin_md.md)] add-ins are then automatically added to your Outlook.</span></span>  

<span data-ttu-id="3edf6-110">Затем при открытии Outlook отобразится сообщение электронной почты от администратора Dynamics NAV. Новая надстройка будет добавлена в ленту Outlook, а в Outlook Web Access вы сможете видеть ее в ленте надстроек непосредственно над телом сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="3edf6-110">Then, when you open Outlook, you will see an email messages from Dynamics NAV Admin. The new add-in is added to the Outlook ribbon, and in Outlook Web Access, you can see it in the add-in ribbon, immediately above the body of the email message.</span></span> <span data-ttu-id="3edf6-111">Сама надстройка будет обновляться периодически, и вы будете получать уведомления о том, что новая версия готова к использованию в Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-111">The add-in itself will be updated periodically, and you'll get notified that a new version is ready for you in Outlook.</span></span>  

<span data-ttu-id="3edf6-112">Некоторые организации, использующие Office 365, ограничивают права пользователей на развертывание надстроек. Поэтому вам следует убедиться, что вы используете подписку Office 365, включающую электронную почту и позволяющую развертывать надстройки. Если вы хотите попробовать надстройку в любом случае, вы можете [попробовать Office 365 бесплатно](https://products.office.com/try).</span><span class="sxs-lookup"><span data-stu-id="3edf6-112">Some companies using Office 365 restrict users’ permissions to deploy add-ins. So you must make sure that you have an Office 365 subscription that includes email and allows you to deploy add-ins. If you want to try out the add-in anyway, you can [try Office 365 for free](https://products.office.com/try).</span></span>  

## <a name="using-the-contact-insights-add-in"></a><span data-ttu-id="3edf6-113">Использование надстройки Contact Insights</span><span class="sxs-lookup"><span data-stu-id="3edf6-113">Using the Contact Insights add-in</span></span>
<span data-ttu-id="3edf6-114">Допустим, вы получили сообщение электронной почты от клиента, который желает получить предложение по определенным товарам.</span><span class="sxs-lookup"><span data-stu-id="3edf6-114">Let's say that you get an email from a customer that wants to get a quote on some items.</span></span> <span data-ttu-id="3edf6-115">Непосредственно в Outlook вы можете открыть надстройку Dynamics NAV, которая распознает отправителя как клиента и откроет карточку клиента для его организации.</span><span class="sxs-lookup"><span data-stu-id="3edf6-115">Directly in Outlook, you can open the Dynamics NAV add-in, which recognizes the sender as a customer, and opens the customer card for his company.</span></span> <span data-ttu-id="3edf6-116">На этой панели вы видите обзорные сведения о клиенте, а также возможность просматривать более подробную информацию в конкретных документах.</span><span class="sxs-lookup"><span data-stu-id="3edf6-116">From this dashboard, you can see overview information for the customer, as well as drill down for more detail on specific documents.</span></span> <span data-ttu-id="3edf6-117">Можно также просмотреть историю продаж для клиента.</span><span class="sxs-lookup"><span data-stu-id="3edf6-117">You can also dig into the sales history for the customer.</span></span> <span data-ttu-id="3edf6-118">Если это новый клиент, его можно создать как нового клиента в [!INCLUDE[d365fin](includes/d365fin_md.md)], не выходя из Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-118">If it's a new customer, you can create them as a new customer in [!INCLUDE[d365fin](includes/d365fin_md.md)] without leaving Outlook.</span></span>  

<span data-ttu-id="3edf6-119">В надстройке вы можете создать предложение по продаже и отправить его клиенту, не выходя из Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-119">In the add-in, you can create a sales quote and send it back to this customer without leaving Outlook.</span></span> <span data-ttu-id="3edf6-120">Вся информация, которая вам нужна для отправки предложения продаже, доступна в рабочем почтовом ящике в Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-120">All of the information that you need to send the sales quote is available in your business inbox in Outlook.</span></span>  
<span data-ttu-id="3edf6-121">После ввода данных вы можете учесть предложение.</span><span class="sxs-lookup"><span data-stu-id="3edf6-121">Once you have the data entered, you can post the quote.</span></span> <span data-ttu-id="3edf6-122">Затем его можно отправить по электронной почте.</span><span class="sxs-lookup"><span data-stu-id="3edf6-122">You can then send it by email.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="3edf6-123"> создает PDF-файл с предложением по продаже и прикрепляет его к сообщению электронной почты, черновик которого вы создаете в надстройке.</span><span class="sxs-lookup"><span data-stu-id="3edf6-123"> generates a .PDF file with the sales quote and attaches it to the email message that you draft in the add-in.</span></span>  

<span data-ttu-id="3edf6-124">Аналогично, если вы получаете сообщение электронной почты от поставщика, вы можете использовать надстройку для работы с поставщиками и счетами покупки.</span><span class="sxs-lookup"><span data-stu-id="3edf6-124">Similarly, if you get an email from a vendor, you can use the add-in to work with vendors and purchase invoices.</span></span>  

<span data-ttu-id="3edf6-125">Иногда необходимо просмотреть больше полей, чем отображается в надстройке, например если вам нужно заполнить строки счета.</span><span class="sxs-lookup"><span data-stu-id="3edf6-125">Sometimes you want to see more fields than you can see in the add-in, such as when you want to fill in lines in an invoice.</span></span> <span data-ttu-id="3edf6-126">Чтобы у вас было больше места для работы, вы можете открыть надстройку в отдельном окне.</span><span class="sxs-lookup"><span data-stu-id="3edf6-126">To give you a bit more space to work with, you can pop out the add-in to a separate window.</span></span> <span data-ttu-id="3edf6-127">Она все еще будет частью Outlook, но более просторной.</span><span class="sxs-lookup"><span data-stu-id="3edf6-127">It's still part of Outlook, but you have more space.</span></span> <span data-ttu-id="3edf6-128">По мере ввода данных в документа в раскрывающемся представлении изменения автоматически сохраняются.</span><span class="sxs-lookup"><span data-stu-id="3edf6-128">As you enter data for the document in the pop-out view, the changes are automatically saved.</span></span> <span data-ttu-id="3edf6-129">После завершения ввода данных в документ можно нажать кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="3edf6-129">When you are done entering data for the document, you can choose the **OK** button.</span></span> <span data-ttu-id="3edf6-130">При выборе области надстройки в Outlook документ будет автоматически обновлен с учетом изменений, внесенных в раскрывающемся окне.</span><span class="sxs-lookup"><span data-stu-id="3edf6-130">Choosing the add-in frame in Outlook automatically refreshes the document with the changes you made in the pop-out view.</span></span>  

## <a name="create-invoices-from-your-meeting-appointments"></a><span data-ttu-id="3edf6-131">Создание счетов для встреч</span><span class="sxs-lookup"><span data-stu-id="3edf6-131">Create invoices from your meeting appointments</span></span>
<span data-ttu-id="3edf6-132">Некоторые организации регистрируют все оплачиваемые встречи в календаре Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-132">Some businesses record all billable appointments in the Outlook calendar.</span></span> <span data-ttu-id="3edf6-133">С помощью [!INCLUDE[d365fin](includes/d365fin_md.md)] можно создать счет для клиента непосредственно из календарной позиции. Откройте встречу, откройте надстройку [!INCLUDE[d365fin](includes/d365fin_md.md)], найдите существующую информацию или создайте счет либо другой документ продажи прямо здесь.</span><span class="sxs-lookup"><span data-stu-id="3edf6-133">With [!INCLUDE[d365fin](includes/d365fin_md.md)], you can create the invoice for the customer right from the calendar item: Open the appointment, and then you can open the [!INCLUDE[d365fin](includes/d365fin_md.md)] add-in, look up existing information or create an invoice or another sales document right there.</span></span>  

## <a name="quick-document-lookup"></a><span data-ttu-id="3edf6-134">Быстрый поиск документов</span><span class="sxs-lookup"><span data-stu-id="3edf6-134">Quick document lookup</span></span>
<span data-ttu-id="3edf6-135">Надстройка "Ссылки на документы [!INCLUDE[d365fin](includes/d365fin_md.md)] позволяет быстро находить документы, упоминаемые в сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="3edf6-135">The [!INCLUDE[d365fin](includes/d365fin_md.md)] Document Links add-in gives you quick access to documents mentioned in email messages.</span></span> <span data-ttu-id="3edf6-136">Надстройка доступна для сообщения электронной почты, если номер документа распознан в теле сообщения.</span><span class="sxs-lookup"><span data-stu-id="3edf6-136">The add-in is available for an email message if a document number is recognized in the body of the message.</span></span> <span data-ttu-id="3edf6-137">Открытие надстройки позволяет быстро перейти к документу.</span><span class="sxs-lookup"><span data-stu-id="3edf6-137">Opening the add-in provides quick access to the document.</span></span>  

<span data-ttu-id="3edf6-138">Например, если вы получили сообщение электронной почты, содержащее текст *S-QUO100*, [!INCLUDE[d365fin](includes/d365fin_md.md)] определит, что это предложение по продаже, и вы можете открыть этот документ в Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-138">For example, if you receive an email message that mentions the text *S-QUO100*, [!INCLUDE[d365fin](includes/d365fin_md.md)] identifies that as a sales quote, and so you can open this document in Outlook.</span></span> <span data-ttu-id="3edf6-139">В Outlook нажмите кнопку **Ссылки на документ** непосредственно над телом сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="3edf6-139">In Outlook, choose the **Document Links** button immediately above the body of the email message.</span></span> <span data-ttu-id="3edf6-140">В Outlook Web App выберите текст *S-QUO1001* в теле сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="3edf6-140">In the Outlook Web App, choose the *S-QUO1001* text in the body of the email message.</span></span>  

<span data-ttu-id="3edf6-141">В надстройке "Ссылки на документы" вы можете изменять документ и выполнять с ним другие действия, как в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="3edf6-141">In the Document Links add-in, you can modify and take actions with the document, just like you can in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

## <a name="adding-the-add-ins-manually"></a><span data-ttu-id="3edf6-142">Добавление надстроек вручную</span><span class="sxs-lookup"><span data-stu-id="3edf6-142">Adding the add-ins manually</span></span>
<span data-ttu-id="3edf6-143">В некоторых случаях надстройки не добавляются автоматически в Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-143">In some cases, the add-ins do not get added automatically to Outlook.</span></span> <span data-ttu-id="3edf6-144">Даже если вы или ваш коллега запускает руководство по сопровождаемой настройке от имени организации, [!INCLUDE[d365fin](includes/d365fin_md.md)] может не отобразиться в Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-144">Even if you or a colleague ran the assisted setup guide on behalf of the company, [!INCLUDE[d365fin](includes/d365fin_md.md)] might not show up in Outlook.</span></span> <span data-ttu-id="3edf6-145">При возникновении этой проблемы вы можете добавить надстройки [!INCLUDE[d365fin](includes/d365fin_md.md)] вручную.</span><span class="sxs-lookup"><span data-stu-id="3edf6-145">If you experience this issue, you can add the [!INCLUDE[d365fin](includes/d365fin_md.md)] add-ins manually.</span></span>  

<span data-ttu-id="3edf6-146">Прежде всего, необходимо проверить, что у вас есть доступ к надстройкам в учетной записи Office 365.</span><span class="sxs-lookup"><span data-stu-id="3edf6-146">First, you must verify that you have access to the add-ins in your Office 365 account.</span></span> <span data-ttu-id="3edf6-147">Откройте Outlook Web Access в браузере, а затем добавьте `/owa/#path=/options/manageapps` к URL-адресу в адресной строке.</span><span class="sxs-lookup"><span data-stu-id="3edf6-147">Quite simply open your Outlook Web Access in a browser, and then add `/owa/#path=/options/manageapps` to the URL in the address bar.</span></span> <span data-ttu-id="3edf6-148">В результате откроется страница **Управление надстройками**, в котором можно включить Dynamics NAV для Outlook.</span><span class="sxs-lookup"><span data-stu-id="3edf6-148">This opens the **Manage add-ins** page, where you can enable Dynamics NAV for your Outlook.</span></span> <span data-ttu-id="3edf6-149">Затем при переходе назад в Outlook приложение [!INCLUDE[d365fin](includes/d365fin_md.md)] должно быть доступно.</span><span class="sxs-lookup"><span data-stu-id="3edf6-149">Then, when you navigate back to Outlook, [!INCLUDE[d365fin](includes/d365fin_md.md)] should be available.</span></span>  

<span data-ttu-id="3edf6-150">Аналогичным образом, в настольном клиенте Outlook можно проверить, что приложение [!INCLUDE[d365fin](includes/d365fin_md.md)] установлено, в окне **Управление надстройками**.</span><span class="sxs-lookup"><span data-stu-id="3edf6-150">Similarly in the Outlook desktop client, you can verify that [!INCLUDE[d365fin](includes/d365fin_md.md)] is listed in the **Manage Add-ins** window.</span></span>  

<span data-ttu-id="3edf6-151">В обоих случаях, если [!INCLUDE[d365fin](includes/d365fin_md.md)] все еще отсутствует, необходимо получить файлы манифеста надстройки.</span><span class="sxs-lookup"><span data-stu-id="3edf6-151">In both cases, if [!INCLUDE[d365fin](includes/d365fin_md.md)] is still not available, you have to get the add-in manifest files.</span></span> <span data-ttu-id="3edf6-152">Для получения более подробных сведений обратитесь к администратору Office 365.</span><span class="sxs-lookup"><span data-stu-id="3edf6-152">For more information, please contact your Office 365 administrator.</span></span>

## <a name="see-also"></a><span data-ttu-id="3edf6-153">См. также</span><span class="sxs-lookup"><span data-stu-id="3edf6-153">See Also</span></span>
<span data-ttu-id="3edf6-154">[Добро пожаловать в [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="3edf6-154">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span></span>  
[<span data-ttu-id="3edf6-155">Финансы</span><span class="sxs-lookup"><span data-stu-id="3edf6-155">Finance</span></span>](finance.md)  
[<span data-ttu-id="3edf6-156">Продажи</span><span class="sxs-lookup"><span data-stu-id="3edf6-156">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="3edf6-157">Покупки</span><span class="sxs-lookup"><span data-stu-id="3edf6-157">Purchasing</span></span>](purchasing-manage-purchasing.md)  
