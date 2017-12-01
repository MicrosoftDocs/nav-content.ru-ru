---
title: "Обзор задач по распределению затрат и дохода"
description: "Описание задач по распределению операции финансового журнала по нескольким разным счетам при учете журнала."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e7d6aed9a57bb2ddd20cb45fd4d68ec0a30eb61a
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-allocate-costs-and-income"></a><span data-ttu-id="f9f51-103">Практическое руководство. Распределение затрат и дохода</span><span class="sxs-lookup"><span data-stu-id="f9f51-103">How to: Allocate Costs and Income</span></span>
<span data-ttu-id="f9f51-104">При учете журнала операцию финансового журнала можно распределить по нескольким разным счетам.</span><span class="sxs-lookup"><span data-stu-id="f9f51-104">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="f9f51-105">Для распределения можно воспользоваться тремя методами:</span><span class="sxs-lookup"><span data-stu-id="f9f51-105">The allocation can be made by three different methods:</span></span>

* <span data-ttu-id="f9f51-106">количество;</span><span class="sxs-lookup"><span data-stu-id="f9f51-106">Quantity</span></span>
* <span data-ttu-id="f9f51-107">процент (%);</span><span class="sxs-lookup"><span data-stu-id="f9f51-107">Percentage (%)</span></span>
* <span data-ttu-id="f9f51-108">Сумма</span><span class="sxs-lookup"><span data-stu-id="f9f51-108">Amount</span></span>

<span data-ttu-id="f9f51-109">Функция распределения может использоваться с типовыми финансовыми журналами и в журналах основных средств.</span><span class="sxs-lookup"><span data-stu-id="f9f51-109">The allocation features can be used with recurring general journals and in fixed assets journals.</span></span>
<!--You can also distribute the cost or revenue of a line to an intercompany partner when you post a sales or purchase document. When you post the document, a line will be posted in your general journal, and a corresponding line will be created in the intercompany outbox.-->

<span data-ttu-id="f9f51-110">Далее описана процедура подготовки к распределению затрат в типовом финансовом журнале путем определения ключей распределения.</span><span class="sxs-lookup"><span data-stu-id="f9f51-110">The following procedures describe how to prepare to allocate costs in a recurring general journal by defining allocation keys.</span></span> <span data-ttu-id="f9f51-111">После определения ключей распределения вы выполняете и учитываете журнал как любой другой типовой финансовый журнал.</span><span class="sxs-lookup"><span data-stu-id="f9f51-111">When allocation keys are defined, you complete and post the journal like any other recurring general journal.</span></span> <span data-ttu-id="f9f51-112">Дополнительные сведения см. в разделе [Работа с финансовыми журналами](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="f9f51-112">For more information, see [Working with General Journals](ui-work-general-journals.md).</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="f9f51-113">Настройка ключей распределения</span><span class="sxs-lookup"><span data-stu-id="f9f51-113">To set up allocation keys</span></span>
<span data-ttu-id="f9f51-114">При учете журнала операцию типового финансового журнала можно распределить по нескольким разным счетам.</span><span class="sxs-lookup"><span data-stu-id="f9f51-114">You can allocate an entry in a recurring general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="f9f51-115">Распределение может выполняться по количеству, по процентному отношению или сумме.</span><span class="sxs-lookup"><span data-stu-id="f9f51-115">The allocation can be made by quantity, percentage, or amount.</span></span>
1. <span data-ttu-id="f9f51-116">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Типовой финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f9f51-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="f9f51-117">Выберите поле **Код раздела**, чтобы открыть окно **Разделы финансового журнала**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-117">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="f9f51-118">Вы можете изменить распределения в существующем разделе в списке или создать новый раздел с распределениями.</span><span class="sxs-lookup"><span data-stu-id="f9f51-118">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
   * <span data-ttu-id="f9f51-119">Для создания нового раздела выберите действие **Создать** и перейдите к следующему шагу.</span><span class="sxs-lookup"><span data-stu-id="f9f51-119">To create a new batch, choose the **New** action, and go to the next step.</span></span>
   * <span data-ttu-id="f9f51-120">Для изменения распределений в существующем журнале выберите журнал и перейдите к шагу 7.</span><span class="sxs-lookup"><span data-stu-id="f9f51-120">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="f9f51-121">В поле **Название** укажите название раздела, например CLEANING.</span><span class="sxs-lookup"><span data-stu-id="f9f51-121">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="f9f51-122">В поле **Описание** введите описание, например "Журнал для расходов по уборке".</span><span class="sxs-lookup"><span data-stu-id="f9f51-122">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="f9f51-123">По завершении закройте окно.</span><span class="sxs-lookup"><span data-stu-id="f9f51-123">When you are done, close the window.</span></span> <span data-ttu-id="f9f51-124">Откроется новый пустой типовой журнал.</span><span class="sxs-lookup"><span data-stu-id="f9f51-124">A new, empty recurring journal opens.</span></span>
6. <span data-ttu-id="f9f51-125">Заполните поля строки.</span><span class="sxs-lookup"><span data-stu-id="f9f51-125">Fill in the fields on the line.</span></span>
7. <span data-ttu-id="f9f51-126">Выберите действие **Распределения**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-126">Choose the **Allocations** action.</span></span>
8. <span data-ttu-id="f9f51-127">Добавьте строку для каждого распределения.</span><span class="sxs-lookup"><span data-stu-id="f9f51-127">Add a line for each allocation.</span></span> <span data-ttu-id="f9f51-128">Следует по выбору заполнить поля **Распределение (%)**, **Распред. кол-во** или **Сумма**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-128">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="f9f51-129">Следует также заполнить поле **Номер счета** и, если производится распределение транзакции по глобальным измерениям, поля глобального измерения.</span><span class="sxs-lookup"><span data-stu-id="f9f51-129">You must also fill in the **Account No.** field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="f9f51-130">Если в строке указан процент, сумма в поле **Сумма** будет рассчитана автоматически.</span><span class="sxs-lookup"><span data-stu-id="f9f51-130">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="f9f51-131">Эти суммы по знаку противоположны итоговой сумме из поля **Сумма** типового журнала.</span><span class="sxs-lookup"><span data-stu-id="f9f51-131">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="f9f51-132">После ввода строк распределения выберите **ОК**, чтобы вернуться к окну **Типовой финансовый журнал**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-132">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="f9f51-133">Поле **Распред. сумма (руб.)** будет заполнено и его значение будет соответствовать полю **Сумма**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-133">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="f9f51-134">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="f9f51-134">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="f9f51-135">Изменение уже настроенного ключа распределения</span><span class="sxs-lookup"><span data-stu-id="f9f51-135">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="f9f51-136">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Типовой финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f9f51-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="f9f51-137">В окне **Типовой финансовый журнал** выберите журнал с распределением.</span><span class="sxs-lookup"><span data-stu-id="f9f51-137">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="f9f51-138">Выберите строку с распределением, а затем выберите действие **Распределения**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-138">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="f9f51-139">Измените соответствующие поля и нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="f9f51-139">Change the relevant fields, and then choose the **OK** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="f9f51-140">См. также</span><span class="sxs-lookup"><span data-stu-id="f9f51-140">See Also</span></span>
[<span data-ttu-id="f9f51-141">Закрытие года и периодов</span><span class="sxs-lookup"><span data-stu-id="f9f51-141">Closing Years and Periods</span></span>](year-close-years-periods.md)  
<span data-ttu-id="f9f51-142">[Работа с финансовыми журналами](ui-work-general-journals.md)  </span><span class="sxs-lookup"><span data-stu-id="f9f51-142">[Working with General Journals](ui-work-general-journals.md)  </span></span>  
<span data-ttu-id="f9f51-143">[Учет документов и журналов](ui-post-documents-journals.md)  </span><span class="sxs-lookup"><span data-stu-id="f9f51-143">[Posting Documents and Journals](ui-post-documents-journals.md)  </span></span>  
<span data-ttu-id="f9f51-144">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f9f51-144">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

