---
title: "Как управлять шаблонами уведомлений"
description: "Пользователи потоков операций получают уведомления, поясняющие, какие шаги им следует предпринять, либо информирующие их о статусе подзадач процесса. Можно задать, кто и когда будет получать уведомление, указав утверждающих пользователей, график уведомления пользователей, а также отклики процесса для определения получателя уведомления. Дополнительные сведения см. в разделе [Настройка уведомлений рабочего процесса](across-setting-up-workflow-notifications.md)."
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
ms.openlocfilehash: 8dee7a54cb086ffa8259f6523733b964ee2c080a
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-notification-templates"></a><span data-ttu-id="3153b-105">Практическое руководство. Управление шаблонами уведомлений</span><span class="sxs-lookup"><span data-stu-id="3153b-105">How to: Manage Notification Templates</span></span>
<span data-ttu-id="3153b-106">Пользователи потоков операций получают уведомления, поясняющие, какие шаги им следует предпринять, либо информирующие их о статусе подзадач процесса.</span><span class="sxs-lookup"><span data-stu-id="3153b-106">Notifications are sent to workflow users to notify them about steps they must make or to inform them about the status of workflow steps.</span></span> <span data-ttu-id="3153b-107">Можно задать, кто и когда будет получать уведомление, указав утверждающих пользователей, график уведомления пользователей, а также отклики процесса для определения получателя уведомления.</span><span class="sxs-lookup"><span data-stu-id="3153b-107">You set up who receives notification and when by setting up approval users, the users’ notification schedule, and the involved workflow responses to define the notification recipient.</span></span> <span data-ttu-id="3153b-108">Дополнительные сведения см. в разделе [Настройка уведомлений рабочего процесса](across-setting-up-workflow-notifications.md).</span><span class="sxs-lookup"><span data-stu-id="3153b-108">For more information, see [Setting Up Workflow Notifications](across-setting-up-workflow-notifications.md).</span></span>  

 <span data-ttu-id="3153b-109">Уведомления создаются на базе шаблонов, определяющих их структуру и содержимое.</span><span class="sxs-lookup"><span data-stu-id="3153b-109">Notifications are based on templates that define the content and layout of the notification.</span></span> <span data-ttu-id="3153b-110">Содержимое шаблона уведомления можно экспортировать, изменить и затем импортировать в этот же или новый шаблон уведомлений.</span><span class="sxs-lookup"><span data-stu-id="3153b-110">You can export the content of a notification template, edit it, and then import into the same or a new notification template.</span></span> <span data-ttu-id="3153b-111">Это описано в следующих процедурах.</span><span class="sxs-lookup"><span data-stu-id="3153b-111">This is described in the following procedures.</span></span>  

 <span data-ttu-id="3153b-112">Универсальная версия [!INCLUDE[d365fin](includes/d365fin_md.md)] включает три шаблона уведомлений: для уведомления о запросах утверждения, для уведомления о новых записях и для уведомления о просроченных запросах утверждения.</span><span class="sxs-lookup"><span data-stu-id="3153b-112">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] contains three notification templates, one for notifying about approval requests, one for notifying about new records, and one for notifying about overdue approval requests.</span></span> <span data-ttu-id="3153b-113">Три заранее определенных шаблона уведомлений поддерживают методы уведомления **Электронная почта** и **Заметка**.</span><span class="sxs-lookup"><span data-stu-id="3153b-113">The three predefined notification templates support **Email** and **Note** as notification method.</span></span> <span data-ttu-id="3153b-114">Для просмотра содержимого трех шаблонов уведомлений просмотрите раздел "Содержимое шаблонов уведомлений" данной темы.</span><span class="sxs-lookup"><span data-stu-id="3153b-114">To view the content of the three notification templates, see the “Content of the Notification Templates” section in this topic.</span></span>

## <a name="to-create-a-new-notification-template"></a><span data-ttu-id="3153b-115">Создание нового шаблона уведомлений</span><span class="sxs-lookup"><span data-stu-id="3153b-115">To create a new notification template</span></span>  
1.  <span data-ttu-id="3153b-116">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Шаблоны уведомлений**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3153b-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Notification Templates**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="3153b-117">В окне **Шаблоны уведомлений** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="3153b-117">In the **Notification Templates** window, choose the **New** action.</span></span>  
3.  <span data-ttu-id="3153b-118">Заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="3153b-118">Fill the fields as described in the following table.</span></span>  

    |<span data-ttu-id="3153b-119">Поле</span><span class="sxs-lookup"><span data-stu-id="3153b-119">Field</span></span>|<span data-ttu-id="3153b-120">Описанием</span><span class="sxs-lookup"><span data-stu-id="3153b-120">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="3153b-121">**Код**</span><span class="sxs-lookup"><span data-stu-id="3153b-121">**Code**</span></span>|<span data-ttu-id="3153b-122">Обозначение шаблона уведомлений.</span><span class="sxs-lookup"><span data-stu-id="3153b-122">Identify the notification template.</span></span>|  
    |<span data-ttu-id="3153b-123">**Описание**</span><span class="sxs-lookup"><span data-stu-id="3153b-123">**Description**</span></span>|<span data-ttu-id="3153b-124">Введите описание шаблона уведомлений.</span><span class="sxs-lookup"><span data-stu-id="3153b-124">Describe the notification template.</span></span>|  
    |<span data-ttu-id="3153b-125">**Метод уведомления**</span><span class="sxs-lookup"><span data-stu-id="3153b-125">**Notification Method**</span></span>|<span data-ttu-id="3153b-126">Укажите способ отправки уведомления — по электронной почте или в виде заметки.</span><span class="sxs-lookup"><span data-stu-id="3153b-126">Specify if the notification is sent as an email or as a note.</span></span>|  
    |<span data-ttu-id="3153b-127">**Тип**</span><span class="sxs-lookup"><span data-stu-id="3153b-127">**Type**</span></span>|<span data-ttu-id="3153b-128">Определите бизнес-процесс, для которого будет использоваться уведомление.</span><span class="sxs-lookup"><span data-stu-id="3153b-128">Specify the business process that the notification will be used for.</span></span><br /><br /> <span data-ttu-id="3153b-129">Выберите один из следующих типов:</span><span class="sxs-lookup"><span data-stu-id="3153b-129">Select one of the following types:</span></span><br /><br /> <span data-ttu-id="3153b-130">-   **Утверждение** определяет, что шаблон применяется для уведомления пользователей рабочих процессов утверждения.</span><span class="sxs-lookup"><span data-stu-id="3153b-130">-   **Approval** specifies that the template is used to notify users in approval workflows.</span></span><br /><span data-ttu-id="3153b-131">-   **Новая запись** определяет, что шаблон применяется для уведомления пользователей в случае, если их утверждения требует новая запись – например, карточка клиента.</span><span class="sxs-lookup"><span data-stu-id="3153b-131">-   **New Record** specifies that the template is to notify approvers when a new record, such as a customer card, needs their approval.</span></span><br /><span data-ttu-id="3153b-132">-   **Просрочено** определяет, что шаблон применяется для уведомления пользователей о просроченных запросах утверждения.</span><span class="sxs-lookup"><span data-stu-id="3153b-132">-   **Overdue** specifies that the template is used to notify users about overdue approval requests.</span></span>|  
    |<span data-ttu-id="3153b-133">**По умолч.**</span><span class="sxs-lookup"><span data-stu-id="3153b-133">**Default**</span></span>|<span data-ttu-id="3153b-134">Определите, будет ли шаблон уведомлений использоваться по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="3153b-134">Specify if the notification template will be used by default.</span></span>|  

## <a name="to-modify-a-notification-template"></a><span data-ttu-id="3153b-135">Изменение шаблона уведомлений</span><span class="sxs-lookup"><span data-stu-id="3153b-135">To modify a notification template</span></span>  
1.  <span data-ttu-id="3153b-136">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Шаблоны уведомлений**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3153b-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Notification Templates**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="3153b-137">В окне **Шаблоны уведомлений** выберите шаблон уведомлений, который требуется изменить.</span><span class="sxs-lookup"><span data-stu-id="3153b-137">In the **Notification Templates** window, select the notification template that you want to modify.</span></span>  
3.  <span data-ttu-id="3153b-138">Выберите действие **Экспорт содержимого шаблона**.</span><span class="sxs-lookup"><span data-stu-id="3153b-138">Choose the **Export Template Content** action.</span></span>  
4.  <span data-ttu-id="3153b-139">В окне **Экспорт файла** выберите кнопку **Сохранить**, введите название и сохраните HTML-файл в соответствующем местоположении.</span><span class="sxs-lookup"><span data-stu-id="3153b-139">In the **Export File** window, choose the **Save** button, and then name and save the HTML file in an appropriate location.</span></span>  
5.  <span data-ttu-id="3153b-140">Щелкните по файлу правой кнопкой мыши, выберите **Открыть при помощи** и затем выберите соответствующую программу.</span><span class="sxs-lookup"><span data-stu-id="3153b-140">Right-click the file, choose **Open with**, and then choose the relevant program.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="3153b-141">Содержимое шаблонов уведомлений типа "Электронная почта" имеет формат HTML.</span><span class="sxs-lookup"><span data-stu-id="3153b-141">Content for notification templates of type Email are in HTML format.</span></span> <span data-ttu-id="3153b-142">Содержимое шаблонов уведомлений типа "Заметка" имеет формат TXT.</span><span class="sxs-lookup"><span data-stu-id="3153b-142">Content for notification templates of type Note are in TXT format.</span></span>  
6.  <span data-ttu-id="3153b-143">Отредактируйте содержимое шаблона уведомлений посредством добавления, изменения или удаления переменных-параметров для определения нужного содержимого и затем сохраните его.</span><span class="sxs-lookup"><span data-stu-id="3153b-143">Edit the content of the notification template by adding, changing, or removing parameter variables to define the content that you want, and then save it.</span></span> <span data-ttu-id="3153b-144">Дополнительные сведения см. в разделе “Содержимое шаблонов уведомлений”.</span><span class="sxs-lookup"><span data-stu-id="3153b-144">For more information, see the “Content of the Notification Templates” section.</span></span>  

    <span data-ttu-id="3153b-145">После этого импортируйте измененное содержимое в этот же или новый шаблон уведомлений.</span><span class="sxs-lookup"><span data-stu-id="3153b-145">Proceed to import the modified content back into the same or a new notification template.</span></span>  
7.  <span data-ttu-id="3153b-146">Для изменения экспортированного шаблона уведомлений в окне **Шаблоны уведомлений** выберите шаблон, ранее выбранный на шаге 2.</span><span class="sxs-lookup"><span data-stu-id="3153b-146">To modify the notification template that you exported, in the **Notification Templates** window, select the template that you selected in step 2.</span></span>  

    <span data-ttu-id="3153b-147">Также можно импортировать измененное содержимое шаблона в новый шаблон уведомлений; для этого следуйте процедуре “Создание нового шаблона уведомлений” и выберите новый шаблон уведомлений.</span><span class="sxs-lookup"><span data-stu-id="3153b-147">Alternatively, to import the modified template content into a new notification template, follow the “To create a new notification template” procedure, and then select the new notification template.</span></span>  
8.  <span data-ttu-id="3153b-148">Выберите действие **Импорт содержимого шаблона**.</span><span class="sxs-lookup"><span data-stu-id="3153b-148">Choose the **Import Template Content** action.</span></span>  
9. <span data-ttu-id="3153b-149">В случае изменения существующего шаблона уведомлений нажмите кнопку **Да** в сообщении о перезаписи существующего шаблона.</span><span class="sxs-lookup"><span data-stu-id="3153b-149">If you are modifying an existing notification template, choose the **Yes** button on the message about overwriting the existing template.</span></span>  
10. <span data-ttu-id="3153b-150">В окне **Выбрать файл для импорта** выберите HTML-файл, измененный на шаге 6, а затем нажмите кнопку **Открыть**.</span><span class="sxs-lookup"><span data-stu-id="3153b-150">In the **Select a file to import** window, choose the HTML file that you modified in step 6, and then choose the **Open** button.</span></span>  

<span data-ttu-id="3153b-151">Существующий или новый шаблон уведомлений в окне **Шаблоны уведомлений** будет заполнен измененным содержимым.</span><span class="sxs-lookup"><span data-stu-id="3153b-151">The existing or new notification template in the **Notification Templates** window is now updated with the modified content.</span></span>  

### <a name="content-of-the-notification-templates"></a><span data-ttu-id="3153b-152">Содержимое шаблонов уведомлений</span><span class="sxs-lookup"><span data-stu-id="3153b-152">Content of the Notification Templates</span></span>  
<span data-ttu-id="3153b-153">Три типа шаблонов уведомлений – **Новая запись**, **Утверждение** и **Просрочка** – имеют разное содержимое.</span><span class="sxs-lookup"><span data-stu-id="3153b-153">The three notification template types, **New Record**, **Approval**, and **Overdue**, have different content.</span></span>  

<span data-ttu-id="3153b-154">Значения параметров автоматически вставляются в уведомления в соответствии с типом шаблона.</span><span class="sxs-lookup"><span data-stu-id="3153b-154">Parameter values are automatically inserted in notifications according to the notification template type.</span></span>  

#### <a name="new-record"></a><span data-ttu-id="3153b-155">Новая запись</span><span class="sxs-lookup"><span data-stu-id="3153b-155">New Record</span></span>  
 <span data-ttu-id="3153b-156">![NAV&#95;notification&#95;template&#95;new&#95;record&#95;type](media/nav_notification_template_new_record.png "NAV_notification_template_new_record")</span><span class="sxs-lookup"><span data-stu-id="3153b-156">![NAV&#95;notification&#95;template&#95;new&#95;record&#95;type](media/nav_notification_template_new_record.png "NAV_notification_template_new_record")</span></span>  

#### <a name="approval"></a><span data-ttu-id="3153b-157">Утверждение</span><span class="sxs-lookup"><span data-stu-id="3153b-157">Approval</span></span>  
 <span data-ttu-id="3153b-158">![NAV&#95;notification&#95;template&#95;approval&#95;type](media/nav_notification_template_approval_type.png "NAV_notification_template_approval_type")</span><span class="sxs-lookup"><span data-stu-id="3153b-158">![NAV&#95;notification&#95;template&#95;approval&#95;type](media/nav_notification_template_approval_type.png "NAV_notification_template_approval_type")</span></span>  

#### <a name="overdue"></a><span data-ttu-id="3153b-159">Просрочено</span><span class="sxs-lookup"><span data-stu-id="3153b-159">Overdue</span></span>  
 <span data-ttu-id="3153b-160">![NAV&#95;notification&#95;overdue&#95;type](media/nav_notification_overdue_type.png "NAV_notification_overdue_type")</span><span class="sxs-lookup"><span data-stu-id="3153b-160">![NAV&#95;notification&#95;overdue&#95;type](media/nav_notification_overdue_type.png "NAV_notification_overdue_type")</span></span>  

## <a name="see-also"></a><span data-ttu-id="3153b-161">См. также</span><span class="sxs-lookup"><span data-stu-id="3153b-161">See Also</span></span>  
 <span data-ttu-id="3153b-162">[Настройка уведомлений рабочего процесса](across-setting-up-workflow-notifications.md) </span><span class="sxs-lookup"><span data-stu-id="3153b-162">[Setting Up Workflow Notifications](across-setting-up-workflow-notifications.md) </span></span>  
 <span data-ttu-id="3153b-163">[Практическое руководство. Настройка электронной почты](madeira-how-setup-email.md) </span><span class="sxs-lookup"><span data-stu-id="3153b-163">[How to: Set up Email](madeira-how-setup-email.md) </span></span>  
 <span data-ttu-id="3153b-164">[Практическое руководство. Настройка пользователей рабочих процессов](across-how-to-set-up-workflow-users.md) </span><span class="sxs-lookup"><span data-stu-id="3153b-164">[How to: Set Up Workflow Users](across-how-to-set-up-workflow-users.md) </span></span>  
 <span data-ttu-id="3153b-165">[Практическое руководство. Настройка утверждающих пользователей](across-how-to-set-up-approval-users.md) </span><span class="sxs-lookup"><span data-stu-id="3153b-165">[How to: Set Up Approval Users](across-how-to-set-up-approval-users.md) </span></span>  
 <span data-ttu-id="3153b-166">[Практическое руководство. Создание рабочих процессов](across-how-to-create-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="3153b-166">[How to: Create Workflows](across-how-to-create-workflows.md) </span></span>  
 <span data-ttu-id="3153b-167">[Использование очередей работ для планирования задач](admin-job-queues-schedule-tasks.md) </span><span class="sxs-lookup"><span data-stu-id="3153b-167">[Use Job Queues to Schedule Tasks](admin-job-queues-schedule-tasks.md) </span></span>  
 [<span data-ttu-id="3153b-168">Рабочий процесс</span><span class="sxs-lookup"><span data-stu-id="3153b-168">Workflow</span></span>](across-workflow.md)   
