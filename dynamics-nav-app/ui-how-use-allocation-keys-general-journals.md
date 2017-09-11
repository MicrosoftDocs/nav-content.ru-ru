---
title: "Практическое руководство: использование ключей распределения в финансовых журналах"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d239ab62c4be88ccc4a2ce2669dcc2c20a3c0126
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

#  <a name="how-to-use-allocation-keys-in-general-journals"></a><span data-ttu-id="e0e28-102">Практическое руководство: использование ключей распределения в финансовых журналах</span><span class="sxs-lookup"><span data-stu-id="e0e28-102">How to: Use Allocation Keys in General Journals</span></span>
<span data-ttu-id="e0e28-103">При учете журнала операцию финансового журнала можно распределить по нескольким разным счетам.</span><span class="sxs-lookup"><span data-stu-id="e0e28-103">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="e0e28-104">Распределение может выполняться по количеству, по процентному отношению или сумме.</span><span class="sxs-lookup"><span data-stu-id="e0e28-104">The allocation can be made by quantity, percentage, or amount.</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="e0e28-105">Настройка ключей распределения</span><span class="sxs-lookup"><span data-stu-id="e0e28-105">To set up allocation keys</span></span> 
1. <span data-ttu-id="e0e28-106">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Типовой финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e0e28-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="e0e28-107">Выберите поле **Код раздела**, чтобы открыть окно **Разделы финансового журнала**.</span><span class="sxs-lookup"><span data-stu-id="e0e28-107">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="e0e28-108">Вы можете изменить распределения в существующем разделе в списке или создать новый раздел с распределениями.</span><span class="sxs-lookup"><span data-stu-id="e0e28-108">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
  * <span data-ttu-id="e0e28-109">Для создания нового раздела выберите действие **Создать** и перейдите к следующему шагу.</span><span class="sxs-lookup"><span data-stu-id="e0e28-109">To create a new batch, choose the **New** action, and go to the next step.</span></span>
  * <span data-ttu-id="e0e28-110">Для изменения распределений в существующем журнале выберите журнал и перейдите к шагу 7.</span><span class="sxs-lookup"><span data-stu-id="e0e28-110">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="e0e28-111">В поле **Название** укажите название раздела, например CLEANING.</span><span class="sxs-lookup"><span data-stu-id="e0e28-111">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="e0e28-112">В поле **Описание** введите описание, например "Журнал для расходов по уборке".</span><span class="sxs-lookup"><span data-stu-id="e0e28-112">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="e0e28-113">По завершении закройте окно.</span><span class="sxs-lookup"><span data-stu-id="e0e28-113">When you are done, close the window.</span></span> <span data-ttu-id="e0e28-114">Откроется новый пустой типовой журнал.</span><span class="sxs-lookup"><span data-stu-id="e0e28-114">A new, empty recurring journal opens.</span></span> 
6. <span data-ttu-id="e0e28-115">Заполните поля в строке.</span><span class="sxs-lookup"><span data-stu-id="e0e28-115">Fill in the fields in the line.</span></span>
7. <span data-ttu-id="e0e28-116">Выберите действие **Распределения**.</span><span class="sxs-lookup"><span data-stu-id="e0e28-116">Choose the **Allocations** action.</span></span> 
8. <span data-ttu-id="e0e28-117">Добавьте строку для каждого распределения.</span><span class="sxs-lookup"><span data-stu-id="e0e28-117">Add a line for each allocation.</span></span> <span data-ttu-id="e0e28-118">Следует по выбору заполнить поля **Распределение (%)**, **Распред. кол-во** или **Сумма**.</span><span class="sxs-lookup"><span data-stu-id="e0e28-118">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="e0e28-119">Необходимо также заполнить поле **Номер счета**</span><span class="sxs-lookup"><span data-stu-id="e0e28-119">You must also fill in the **Account No.**</span></span> <span data-ttu-id="e0e28-120">и, если производится распределение транзакции по глобальным измерениям, поля глобального измерения.</span><span class="sxs-lookup"><span data-stu-id="e0e28-120">field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="e0e28-121">Если в строке указан процент, сумма в поле **Сумма** будет рассчитана автоматически.</span><span class="sxs-lookup"><span data-stu-id="e0e28-121">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="e0e28-122">Эти суммы по знаку противоположны итоговой сумме из поля **Сумма** типового журнала.</span><span class="sxs-lookup"><span data-stu-id="e0e28-122">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="e0e28-123">После ввода строк распределения выберите **ОК**, чтобы вернуться к окну **Типовой финансовый журнал**.</span><span class="sxs-lookup"><span data-stu-id="e0e28-123">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="e0e28-124">Поле **Распред. сумма (руб.)** будет заполнено и его значение будет соответствовать полю **Сумма**.</span><span class="sxs-lookup"><span data-stu-id="e0e28-124">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="e0e28-125">Учтите журнал.</span><span class="sxs-lookup"><span data-stu-id="e0e28-125">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="e0e28-126">Изменение уже настроенного ключа распределения</span><span class="sxs-lookup"><span data-stu-id="e0e28-126">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="e0e28-127">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Типовой финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e0e28-127">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="e0e28-128">В окне **Типовой финансовый журнал** выберите журнал с распределением.</span><span class="sxs-lookup"><span data-stu-id="e0e28-128">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="e0e28-129">Выберите строку с распределением, а затем выберите действие **Распределения**.</span><span class="sxs-lookup"><span data-stu-id="e0e28-129">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="e0e28-130">Измените соответствующие поля и закройте окно.</span><span class="sxs-lookup"><span data-stu-id="e0e28-130">Change the relevant fields, and close the window.</span></span>

## <a name="see-also"></a><span data-ttu-id="e0e28-131">См. также</span><span class="sxs-lookup"><span data-stu-id="e0e28-131">See Also</span></span>
[<span data-ttu-id="e0e28-132">Работа с финансовыми журналами</span><span class="sxs-lookup"><span data-stu-id="e0e28-132">Work With General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="e0e28-133">Учет документов и журналов</span><span class="sxs-lookup"><span data-stu-id="e0e28-133">Post Documents and Journals</span></span>](ui-post-documents-journals.md)




