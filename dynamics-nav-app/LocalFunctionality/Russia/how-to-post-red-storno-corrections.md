---
title: "Учет коррекций \"красный сторно\""
description: "Можно настраивать склад на использование одного столбца для первоначального и корректирующего учета. Эта функция часто называется *красный сторно*."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 93652cbff8d0cdb4f810c3537ac0fe5a7bd90266
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-post-red-storno-corrections"></a><span data-ttu-id="10d54-104">Практическое руководство. Учет коррекций "красный сторно"</span><span class="sxs-lookup"><span data-stu-id="10d54-104">How to: Post Red Storno Corrections</span></span>
<span data-ttu-id="10d54-105">Можно настраивать склад на использование одного столбца для первоначального и корректирующего учета.</span><span class="sxs-lookup"><span data-stu-id="10d54-105">You can set up inventory to use the same column for original and corrective postings.</span></span> <span data-ttu-id="10d54-106">Эта функция часто называется *красный сторно*.</span><span class="sxs-lookup"><span data-stu-id="10d54-106">This is often referred to as *red storno*.</span></span> <span data-ttu-id="10d54-107">Можно использовать учет "красный сторно" для учета следующих операций склада:</span><span class="sxs-lookup"><span data-stu-id="10d54-107">You can use red storno posting to post the following inventory entries:</span></span>  

- <span data-ttu-id="10d54-108">Корректирующие операции в журнале товаров.</span><span class="sxs-lookup"><span data-stu-id="10d54-108">Corrective entries in the item journal.</span></span>  
- <span data-ttu-id="10d54-109">Сторнирование товарных документов, таких как акты оприходования и акты списания товаров.</span><span class="sxs-lookup"><span data-stu-id="10d54-109">Reversal of item documents such as item receipts and item shipments.</span></span>  
- <span data-ttu-id="10d54-110">Учет журналов переоценки или реклассификации товаров.</span><span class="sxs-lookup"><span data-stu-id="10d54-110">Posting item revaluation or item reclassification journals.</span></span>  
- <span data-ttu-id="10d54-111">Периодические корректировки себестоимости товара.</span><span class="sxs-lookup"><span data-stu-id="10d54-111">Periodic adjustments of item costs.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="10d54-112">Следует включить функцию "красный сторно в окне **Настройка модуля "Запасы"**, прежде чем можно будет учитывать корректирующие операции.</span><span class="sxs-lookup"><span data-stu-id="10d54-112">You must enable red storno in the **Inventory Setup** window before you can post corrective entries.</span></span> <span data-ttu-id="10d54-113">Дополнительные сведения см. в разделе [Настройка модуля "Запасы"](inventory-setup.md).</span><span class="sxs-lookup"><span data-stu-id="10d54-113">For more information, see [Inventory Setup](inventory-setup.md).</span></span>  

## <a name="to-post-corrective-entries-in-the-item-journal"></a><span data-ttu-id="10d54-114">Учет корректирующих операций в журнале товаров</span><span class="sxs-lookup"><span data-stu-id="10d54-114">To post corrective entries in the item journal</span></span>  

1.  <span data-ttu-id="10d54-115">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал товаров**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="10d54-115">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Journal**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="10d54-116">Введите значения в поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="10d54-116">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="10d54-117">Поле</span><span class="sxs-lookup"><span data-stu-id="10d54-117">Field</span></span>|<span data-ttu-id="10d54-118">Описанием</span><span class="sxs-lookup"><span data-stu-id="10d54-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="10d54-119">**Тип операции**</span><span class="sxs-lookup"><span data-stu-id="10d54-119">**Entry Type**</span></span>|<span data-ttu-id="10d54-120">Выберите тот же тип операции, что и для первоначального учета.</span><span class="sxs-lookup"><span data-stu-id="10d54-120">Select the same entry type as the original posting.</span></span>|  
    |<span data-ttu-id="10d54-121">**Количество**</span><span class="sxs-lookup"><span data-stu-id="10d54-121">**Quantity**</span></span>|<span data-ttu-id="10d54-122">Введите количество со знаком, противоположным первоначальному учету, например **-4**.</span><span class="sxs-lookup"><span data-stu-id="10d54-122">Enter the quantity with the opposite sign of the original posting, such as **-4**.</span></span>|  
    |<span data-ttu-id="10d54-123">**Красное сторно**</span><span class="sxs-lookup"><span data-stu-id="10d54-123">**Red Storno**</span></span>|<span data-ttu-id="10d54-124">Выберите для учета в качестве корректирующего учета.</span><span class="sxs-lookup"><span data-stu-id="10d54-124">Select to post as a corrective posting.</span></span>|  

     <span data-ttu-id="10d54-125">Также необходимо выбрать соответствующие операции в полях **Примен. к операции** или **Примен. из операции**.</span><span class="sxs-lookup"><span data-stu-id="10d54-125">You must also select the appropriate entries in the **Applies-to Entry** or **Applies-from Entry** fields.</span></span>  

3.  <span data-ttu-id="10d54-126">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="10d54-126">Post the journal.</span></span>  

<span data-ttu-id="10d54-127">Коррекция учитывается, и учитывается все корреспонденция счета главной книги, которая была настроена.</span><span class="sxs-lookup"><span data-stu-id="10d54-127">The correction is posted, and any general ledger account correspondence that you have set up will be considered.</span></span>  

## <a name="to-reverse-item-documents"></a><span data-ttu-id="10d54-128">Сторнирование товарных документов</span><span class="sxs-lookup"><span data-stu-id="10d54-128">To reverse item documents</span></span>  

1.  <span data-ttu-id="10d54-129">Для сторнирования акта оприходования товаров выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Акты оприходования товаров**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="10d54-129">To reverse an item receipt, Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Receipt**, and then choose the related link.</span></span>  

    <span data-ttu-id="10d54-130">Для сторнирования акта списания товара выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Учт. акты списания товаров**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="10d54-130">To reverse an item shipment, Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Shipment**, and then choose the related link.</span></span>  

2.  <span data-ttu-id="10d54-131">На экспресс-вкладке **Общее** установите флажок **Корректировка**.</span><span class="sxs-lookup"><span data-stu-id="10d54-131">On the **General** FastTab, select the **Correction** check box.</span></span>  
3.  <span data-ttu-id="10d54-132">Выберите действие **Копировать документ**.</span><span class="sxs-lookup"><span data-stu-id="10d54-132">Choose the **Copy Document** action.</span></span>  
4.  <span data-ttu-id="10d54-133">В окне **Копировать документ** установите соответствующие фильтры, затем выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="10d54-133">In the **Copy Document** window, set the appropriate filters, and then choose the **OK** button.</span></span>  
5.  <span data-ttu-id="10d54-134">Внесите необходимые изменения в количество и суммы.</span><span class="sxs-lookup"><span data-stu-id="10d54-134">Make the needed changes to quantity and amounts.</span></span>  

    <span data-ttu-id="10d54-135">Также необходимо выбрать соответствующие операции в полях **Примен. к операции** или **Примен. из операции**.</span><span class="sxs-lookup"><span data-stu-id="10d54-135">You must also select the appropriate entries in the **Applies-to Entry** or **Applies-from Entry** fields.</span></span> <span data-ttu-id="10d54-136">Эти поля определяют неправильно учтенный документ.</span><span class="sxs-lookup"><span data-stu-id="10d54-136">These fields identify the incorrectly posted document.</span></span>  

6.  <span data-ttu-id="10d54-137">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="10d54-137">Post the document.</span></span>  

## <a name="to-post-item-revaluation-or-item-reclassification-journals"></a><span data-ttu-id="10d54-138">Учет журналов переоценки или реклассификации товаров</span><span class="sxs-lookup"><span data-stu-id="10d54-138">To post item revaluation or item reclassification journals</span></span>  

1.  <span data-ttu-id="10d54-139">Для учета переоценки товара выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал переоценки**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="10d54-139">To post an item revaluation, Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Revaluation Journal**, and then choose the related link.</span></span>  

    <span data-ttu-id="10d54-140">Для учета реклассификации товара выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал реклассификации товаров**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="10d54-140">To post an item reclassification, Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Reclass Journal**, and then choose the related link.</span></span>  

2.  <span data-ttu-id="10d54-141">Введите значения в поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="10d54-141">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="10d54-142">Поле</span><span class="sxs-lookup"><span data-stu-id="10d54-142">Field</span></span>|<span data-ttu-id="10d54-143">Описанием</span><span class="sxs-lookup"><span data-stu-id="10d54-143">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="10d54-144">**Примен. к номеру операции**</span><span class="sxs-lookup"><span data-stu-id="10d54-144">**Applies-to Entry**</span></span>|<span data-ttu-id="10d54-145">Указывает товарную операцию, для которой требуется выполнить переоценку или реклассификацию.</span><span class="sxs-lookup"><span data-stu-id="10d54-145">Specifies the item entry that you want to revalue or reclassify.</span></span>|  
    |<span data-ttu-id="10d54-146">**Примен. из операции**</span><span class="sxs-lookup"><span data-stu-id="10d54-146">**Applies-from Entry**</span></span>|<span data-ttu-id="10d54-147">Указывает товарную операцию, для которой требуется выполнить переоценку или реклассификацию.</span><span class="sxs-lookup"><span data-stu-id="10d54-147">Specifies the item entry that you want to revalue or reclassify.</span></span>|  
    |<span data-ttu-id="10d54-148">**Красное сторно**</span><span class="sxs-lookup"><span data-stu-id="10d54-148">**Red Storno**</span></span>|<span data-ttu-id="10d54-149">Выберите для учета в качестве корректирующего учета.</span><span class="sxs-lookup"><span data-stu-id="10d54-149">Select to post as a corrective posting.</span></span>|  

3.  <span data-ttu-id="10d54-150">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="10d54-150">Post the document.</span></span>  

## <a name="see-also"></a><span data-ttu-id="10d54-151">См. также</span><span class="sxs-lookup"><span data-stu-id="10d54-151">See Also</span></span>  
[<span data-ttu-id="10d54-152">Настройка запасов</span><span class="sxs-lookup"><span data-stu-id="10d54-152">Setting Up Inventory</span></span>](../../inventory-setup-inventory.md)   

