---
title: "Как удалять рабочие процессы"
description: "Если вы уверены, что рабочий процесс уже не используется, то его можно удалить. Все экземпляры шагов рабочего процесса, определенные в рабочем процессе, должны иметь статус **Завершено**."
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
ms.openlocfilehash: 97621dfeed6c8a224efc199ee5ab3a28e519b951
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-delete-workflows"></a><span data-ttu-id="bcf67-104">Практическое руководство. Удаление рабочих процессов</span><span class="sxs-lookup"><span data-stu-id="bcf67-104">How to: Delete Workflows</span></span>
<span data-ttu-id="bcf67-105">Если вы уверены, что рабочий процесс уже не используется, то его можно удалить.</span><span class="sxs-lookup"><span data-stu-id="bcf67-105">If you are certain that a workflow is no longer being used, you can delete it.</span></span> <span data-ttu-id="bcf67-106">Все экземпляры шагов рабочего процесса, определенные в рабочем процессе, должны иметь статус **Завершено**.</span><span class="sxs-lookup"><span data-stu-id="bcf67-106">All workflow step instances that are defined in the workflow must have status **Completed**.</span></span>  

> [!CAUTION]  
>  <span data-ttu-id="bcf67-107">При удалении рабочего процесса все сведения в рабочем процессе будут утеряны.</span><span class="sxs-lookup"><span data-stu-id="bcf67-107">When you delete a workflow, all information in the workflow will be lost.</span></span>  

 <span data-ttu-id="bcf67-108">В окне **Рабочий процесс** создайте рабочий процесс, указав в строках связанные с ним шаги.</span><span class="sxs-lookup"><span data-stu-id="bcf67-108">In the **Workflow** window, you create a workflow by listing the involved steps on the lines.</span></span> <span data-ttu-id="bcf67-109">Каждый шаг состоит из события рабочего процесса, ограниченного условиями события, и отклика рабочего процесса, ограниченного параметрами отклика.</span><span class="sxs-lookup"><span data-stu-id="bcf67-109">Each step consists of a workflow event, moderated by event conditions, and a workflow response, moderated by response options.</span></span> <span data-ttu-id="bcf67-110">Шаги рабочего процесса заполняются посредством заполнения полей в строках рабочего процесса из фиксированных списков значений события и отклика, представляющих сценарии, которые поддерживаются кодом приложения.</span><span class="sxs-lookup"><span data-stu-id="bcf67-110">You define workflow steps by filling fields on workflow lines from fixed lists of event and response values representing scenarios that are supported by the application code.</span></span> <span data-ttu-id="bcf67-111">Дополнительные сведения см. в разделе [Практическое руководство. Создание рабочих процессов](across-how-to-create-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="bcf67-111">For more information, see [How to: Create Workflows](across-how-to-create-workflows.md).</span></span>  

## <a name="to-delete-a-workflow"></a><span data-ttu-id="bcf67-112">Удаление рабочего процесса</span><span class="sxs-lookup"><span data-stu-id="bcf67-112">To delete a workflow</span></span>  
1.  <span data-ttu-id="bcf67-113">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Рабочие процессы**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="bcf67-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Workflows**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="bcf67-114">Выберите рабочий процесс, который требуется удалить.</span><span class="sxs-lookup"><span data-stu-id="bcf67-114">Select the workflow that you want to delete.</span></span>  
3.  <span data-ttu-id="bcf67-115">Выберите действие **Удалить**.</span><span class="sxs-lookup"><span data-stu-id="bcf67-115">Choose the **Delete** action.</span></span>  
4.  <span data-ttu-id="bcf67-116">Также можно открыть рабочий процесс, который требуется удалить.</span><span class="sxs-lookup"><span data-stu-id="bcf67-116">Alternatively, open the workflow that you want to delete.</span></span>  
5.  <span data-ttu-id="bcf67-117">В окне **Рабочий процесс** выберите действие **Удалить**.</span><span class="sxs-lookup"><span data-stu-id="bcf67-117">In the **Workflow** window, choose the **Delete** action.</span></span>  

## <a name="see-also"></a><span data-ttu-id="bcf67-118">См. также</span><span class="sxs-lookup"><span data-stu-id="bcf67-118">See Also</span></span>  
 <span data-ttu-id="bcf67-119">[Практическое руководство. Создание рабочих процессов](across-how-to-create-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="bcf67-119">[How to: Create Workflows](across-how-to-create-workflows.md) </span></span>  
 <span data-ttu-id="bcf67-120">[Практическое руководство. Включение рабочих процессов](across-how-to-enable-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="bcf67-120">[How to: Enable Workflows](across-how-to-enable-workflows.md) </span></span>  
 <span data-ttu-id="bcf67-121">[Практическое руководство. Просмотр архивированных экземпляров шагов рабочих процессов](across-how-to-view-archived-workflow-step-instances.md) </span><span class="sxs-lookup"><span data-stu-id="bcf67-121">[How to: View Archived Workflow Step Instances](across-how-to-view-archived-workflow-step-instances.md) </span></span>  
 <span data-ttu-id="bcf67-122">[Пошаговое руководство. Настройка и использование рабочего процесса утверждения покупки](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md) </span><span class="sxs-lookup"><span data-stu-id="bcf67-122">[Walkthrough: Setting Up and Using a Purchase Approval Workflow](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md) </span></span>  
 <span data-ttu-id="bcf67-123">[Настройка рабочих процессов](across-set-up-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="bcf67-123">[Setting Up Workflows](across-set-up-workflows.md) </span></span>  
 <span data-ttu-id="bcf67-124">[Использование рабочих процессов](across-use-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="bcf67-124">[Using Workflows](across-use-workflows.md) </span></span>  
 [<span data-ttu-id="bcf67-125">Рабочий процесс</span><span class="sxs-lookup"><span data-stu-id="bcf67-125">Workflow</span></span>](across-workflow.md)   

