---
title: "Рабочий процесс"
description: "Можно настроить и использовать рабочие процессы, связывающие задачи бизнес-процесса, выполняемые различными пользователями. Системные задачи, такие как автоматический учет, могут включаться в качестве шагов рабочего процесса, предшествующих задачам пользователя или выполняемых после них. Типичные шаги рабочего процесса – запрос и выдача разрешения на создание новых записей."
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
ms.openlocfilehash: e1efc43df4e0676c8c8bd704c58458ab9398cbe1
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="workflow"></a><span data-ttu-id="5ce4c-105">Рабочий процесс</span><span class="sxs-lookup"><span data-stu-id="5ce4c-105">Workflow</span></span>
<span data-ttu-id="5ce4c-106">Можно настроить и использовать рабочие процессы, связывающие задачи бизнес-процесса, выполняемые различными пользователями.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-106">You can set up and use workflows that connect business-process tasks performed by different users.</span></span> <span data-ttu-id="5ce4c-107">Системные задачи, такие как автоматический учет, могут включаться в качестве шагов рабочего процесса, предшествующих задачам пользователя или выполняемых после них.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-107">System tasks, such as automatic posting, can be included as steps in workflows, preceded or followed by user tasks.</span></span> <span data-ttu-id="5ce4c-108">Типичные шаги рабочего процесса – запрос и выдача разрешения на создание новых записей.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-108">Requesting and granting approval to create new records are typical workflow steps.</span></span>  

 <span data-ttu-id="5ce4c-109">В окне **Рабочий процесс** создайте рабочий процесс, указав в строках связанные с ним шаги.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-109">In the **Workflow** window, you create a workflow by listing the involved steps on the lines.</span></span> <span data-ttu-id="5ce4c-110">Каждый шаг состоит из события рабочего процесса, ограниченного условиями события, и отклика рабочего процесса, ограниченного параметрами отклика.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-110">Each step consists of a workflow event, moderated by event conditions, and a workflow response, moderated by response options.</span></span> <span data-ttu-id="5ce4c-111">Шаги рабочего процесса заполняются посредством заполнения полей в строках рабочего процесса из фиксированных списков значений события и отклика, представляющих сценарии, которые поддерживаются кодом приложения.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-111">You define workflow steps by filling fields on workflow lines from fixed lists of event and response values representing scenarios that are supported by the application code.</span></span>  

 <span data-ttu-id="5ce4c-112">Универсальная версия [!INCLUDE[d365fin](includes/d365fin_md.md)] содержит ряд заранее настроенных рабочих процессов, представленных в шаблонах рабочих процессов, которые можно копировать при создании рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-112">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] includes a number of preconfigured workflows represented by workflow templates that you can copy to create workflows.</span></span> <span data-ttu-id="5ce4c-113">Код для шаблонов рабочих процессов, добавленных Майкрософт, имеет приставку "MS-".</span><span class="sxs-lookup"><span data-stu-id="5ce4c-113">The code for workflow templates that are added by Microsoft are prefixed with “MS-“.</span></span> <span data-ttu-id="5ce4c-114">Дополнительные сведения см. в шаблонах рабочих процессов в окне Шаблоны рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-114">For more information, see the list of workflow templates in the Workflow Templates window.</span></span>  

 <span data-ttu-id="5ce4c-115">Если бизнес-сценарий требует события или отклика рабочего процесса, которые не поддерживаются, партнеру Майкрософт придется реализовать их, настроив код приложения.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-115">If a business scenario requires a workflow event or response that is not supported, a Microsoft partner must implement them by customizing the application code.</span></span> <span data-ttu-id="5ce4c-116">Дополнительные сведения см. в разделе [Пошаговое руководство. Реализация новых и событий и отзывов рабочего процесса](https://msdn.microsoft.com/en-us/library/mt574349.aspx) на сайте MSDN.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-116">For more information, see [Walkthrough: Implementing New Workflow Events and Responses](https://msdn.microsoft.com/en-us/library/mt574349.aspx) on MSDN.</span></span>  

 <span data-ttu-id="5ce4c-117">В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-117">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>  

|<span data-ttu-id="5ce4c-118">**Чтобы**</span><span class="sxs-lookup"><span data-stu-id="5ce4c-118">**To**</span></span>|<span data-ttu-id="5ce4c-119">**Смотрите**</span><span class="sxs-lookup"><span data-stu-id="5ce4c-119">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="5ce4c-120">Настройте пользователей рабочего процесса, определите, как пользователи будут получать уведомления, и создайте новые рабочие процессы.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-120">Set up workflow users, specify how users get notified, and create new workflows.</span></span> <span data-ttu-id="5ce4c-121">Для новых рабочих процессов для неподдерживаемых сценариев реализуйте необходимые элементы рабочего процесса путем настройки кода приложения.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-121">For new workflows for unsupported scenarios, implement the required workflow elements by customizing the application code.</span></span>|[<span data-ttu-id="5ce4c-122">Настройка рабочих процессов</span><span class="sxs-lookup"><span data-stu-id="5ce4c-122">Setting Up Workflows</span></span>](across-set-up-workflows.md)|  
|<span data-ttu-id="5ce4c-123">Включите процессы, выполните действия над уведомлениями рабочего процесса, включая запрос утверждения, и утвердите запросы на выполнение шага рабочего процесса.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-123">Enable workflows, act on workflow notifications, including request approvals and approve requests to perform a workflow step.</span></span> <span data-ttu-id="5ce4c-124">Архивируйте и удалите рабочие процессы.</span><span class="sxs-lookup"><span data-stu-id="5ce4c-124">Archive and delete workflows.</span></span>|[<span data-ttu-id="5ce4c-125">Использование рабочих процессов</span><span class="sxs-lookup"><span data-stu-id="5ce4c-125">Using Workflows</span></span>](across-use-workflows.md)|  

## <a name="see-also"></a><span data-ttu-id="5ce4c-126">См. также</span><span class="sxs-lookup"><span data-stu-id="5ce4c-126">See Also</span></span>  
[<span data-ttu-id="5ce4c-127">Продажи</span><span class="sxs-lookup"><span data-stu-id="5ce4c-127">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="5ce4c-128">Покупки</span><span class="sxs-lookup"><span data-stu-id="5ce4c-128">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="5ce4c-129">Управление проектами</span><span class="sxs-lookup"><span data-stu-id="5ce4c-129">Managing Projects</span></span>](projects-manage-projects.md)  
<span data-ttu-id="5ce4c-130">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="5ce4c-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

