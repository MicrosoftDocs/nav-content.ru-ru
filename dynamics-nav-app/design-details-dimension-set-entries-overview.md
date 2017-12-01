---
title: "Обзор записей набора измерений"
description: "В этом разделе описывается, как операции набора измерений хранятся и учитываются в [!INCLUDE[d365fin](includes/d365fin_md.md)]."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: dimension
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 95b9f4569c734541e8c870096cae1e0a2f0685a4
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="dimension-set-entries-overview"></a><span data-ttu-id="229f8-103">Обзор записей набора измерений</span><span class="sxs-lookup"><span data-stu-id="229f8-103">Dimension Set Entries Overview</span></span>
<span data-ttu-id="229f8-104">В этом разделе описывается, как операции набора измерений хранятся и учитываются в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="229f8-104">This topic describes how dimension set entries are stored and posted in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  
  
## <a name="dimension-sets"></a><span data-ttu-id="229f8-105">Наборы измерений</span><span class="sxs-lookup"><span data-stu-id="229f8-105">Dimension Sets</span></span>  
<span data-ttu-id="229f8-106">Набор измерений — это уникальная комбинация значений измерений.</span><span class="sxs-lookup"><span data-stu-id="229f8-106">A dimension set is a unique combination of dimension values.</span></span> <span data-ttu-id="229f8-107">Это храниться как записи набора измерений в базе данных.</span><span class="sxs-lookup"><span data-stu-id="229f8-107">It is stored as dimension set entries in the database.</span></span> <span data-ttu-id="229f8-108">Каждая запись набора измерений представляет отдельное значение измерения.</span><span class="sxs-lookup"><span data-stu-id="229f8-108">Each dimension set entry represents a single dimension value.</span></span> <span data-ttu-id="229f8-109">Набор измерений определяется общим кодом набора измерений, который присваивается каждой операции набора измерений, которая относится к набору измерений.</span><span class="sxs-lookup"><span data-stu-id="229f8-109">The dimension set is identified by a common dimension set ID that is assigned to each dimension set entry that belongs to the dimension set.</span></span>  
  
<span data-ttu-id="229f8-110">В следующем примере представлен набор измерений с тремя операциями набора измерений.</span><span class="sxs-lookup"><span data-stu-id="229f8-110">The following example shows a dimension set that has three dimension set entries.</span></span> <span data-ttu-id="229f8-111">Набор измерений определяется кодом набора измерений, который равен 108.</span><span class="sxs-lookup"><span data-stu-id="229f8-111">The dimension set is identified by a dimension set ID, which is 108.</span></span>  
  
|<span data-ttu-id="229f8-112">Код набора измерений</span><span class="sxs-lookup"><span data-stu-id="229f8-112">Dimension Set ID</span></span>|<span data-ttu-id="229f8-113">Код Измерения:</span><span class="sxs-lookup"><span data-stu-id="229f8-113">Dimension Code</span></span>|<span data-ttu-id="229f8-114">Код значения измерения</span><span class="sxs-lookup"><span data-stu-id="229f8-114">Dimension Value Code</span></span>|<span data-ttu-id="229f8-115">Имя значения измерения</span><span class="sxs-lookup"><span data-stu-id="229f8-115">Dimension Value Name</span></span>|  
|----------------------|--------------------|--------------------------|--------------------------|  
|<span data-ttu-id="229f8-116">108</span><span class="sxs-lookup"><span data-stu-id="229f8-116">108</span></span>|<span data-ttu-id="229f8-117">РЕГИОН</span><span class="sxs-lookup"><span data-stu-id="229f8-117">AREA</span></span>|<span data-ttu-id="229f8-118">70</span><span class="sxs-lookup"><span data-stu-id="229f8-118">70</span></span>|<span data-ttu-id="229f8-119">Северная Америка</span><span class="sxs-lookup"><span data-stu-id="229f8-119">America North</span></span>|  
|<span data-ttu-id="229f8-120">108</span><span class="sxs-lookup"><span data-stu-id="229f8-120">108</span></span>|<span data-ttu-id="229f8-121">БИЗНЕСГРУППА</span><span class="sxs-lookup"><span data-stu-id="229f8-121">BUSINESSGROUP</span></span>|<span data-ttu-id="229f8-122">HOME</span><span class="sxs-lookup"><span data-stu-id="229f8-122">HOME</span></span>|<span data-ttu-id="229f8-123">В начало</span><span class="sxs-lookup"><span data-stu-id="229f8-123">Home</span></span>|  
|<span data-ttu-id="229f8-124">108</span><span class="sxs-lookup"><span data-stu-id="229f8-124">108</span></span>|<span data-ttu-id="229f8-125">ОТДЕЛ</span><span class="sxs-lookup"><span data-stu-id="229f8-125">DEPARTMENT</span></span>|<span data-ttu-id="229f8-126">ПРОДАЖИ</span><span class="sxs-lookup"><span data-stu-id="229f8-126">SALES</span></span>|<span data-ttu-id="229f8-127">Продажи</span><span class="sxs-lookup"><span data-stu-id="229f8-127">Sales</span></span>|  
  
## <a name="dimension-set-entries"></a><span data-ttu-id="229f8-128">Записи набора измерений</span><span class="sxs-lookup"><span data-stu-id="229f8-128">Dimension Set Entries</span></span>  
<span data-ttu-id="229f8-129">Наборы измерений сохраняются в таблице **Запись набора измерений** в виде записей набора измерений с одинаковым кодом набора измерений.</span><span class="sxs-lookup"><span data-stu-id="229f8-129">Dimension sets are stored in the **Dimension Set Entry** table as dimension set entries with the same dimension set ID.</span></span>  
  
<span data-ttu-id="229f8-130">![Обзор операции измерения](media/dimensionentrynav7.png "DimensionEntryNAV7")</span><span class="sxs-lookup"><span data-stu-id="229f8-130">![Dimension Entry overview](media/dimensionentrynav7.png "DimensionEntryNAV7")</span></span>  
  
<span data-ttu-id="229f8-131">При создании новой строки журнала, заголовка документа или строки документа можно указать комбинации значений измерений.</span><span class="sxs-lookup"><span data-stu-id="229f8-131">When you create a new journal line, document header, or document line, you can specify a combination of dimension values.</span></span> <span data-ttu-id="229f8-132">Вместо явного сохранения значения каждого измерения в базе данных, код набора измерений присваивается строке журнала, заголовку документа или строке документа для определения набора измерений.</span><span class="sxs-lookup"><span data-stu-id="229f8-132">Instead of explicitly storing each dimension value in the database, a dimension set ID is assigned to the journal line, document header, or document line to specify the dimension set.</span></span>  
  
<span data-ttu-id="229f8-133">При редактировании и закрытии окна **Изменить записи набора измерений** проверяется существование комбинации значений измерений как набора измерений в таблице.</span><span class="sxs-lookup"><span data-stu-id="229f8-133">When you edit and close the **Edit Dimension Set Entries** window, a check is performed to see whether the combination of dimension values exists as a dimension set in the table.</span></span> <span data-ttu-id="229f8-134">Если в таблице встречается комбинация, соответствующий КОД набора измерений присваивается заголовку документа, строке журнала, либо строке документа.</span><span class="sxs-lookup"><span data-stu-id="229f8-134">If the combination occurs in the table, then the corresponding dimension set ID is assigned to the journal line, document header, or document line.</span></span> <span data-ttu-id="229f8-135">В противном случае новый набор измерений добавляется к таблице, а идентификатор нового набора измерений присваивается заголовку документа, строке журнала либо строке документа.</span><span class="sxs-lookup"><span data-stu-id="229f8-135">Otherwise, a new dimension set is added to the table, and the new dimension set ID is assigned to the journal line, document header, or document line.</span></span>  
  
## <a name="performance-improvement"></a><span data-ttu-id="229f8-136">Повышение производительности</span><span class="sxs-lookup"><span data-stu-id="229f8-136">Performance Improvement</span></span>  
<span data-ttu-id="229f8-137">При сохранении наборов измерений один раз в базе данных экономится пространство БД и улучшается общая производительность.</span><span class="sxs-lookup"><span data-stu-id="229f8-137">By storing dimension sets once in the database, database space is preserved, and overall performance is improved.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="229f8-138">См. также</span><span class="sxs-lookup"><span data-stu-id="229f8-138">See Also</span></span>  
<span data-ttu-id="229f8-139">[Сведения о проектировании: поиск комбинаций измерений](design-details-searching-for-dimension-combinations.md) </span><span class="sxs-lookup"><span data-stu-id="229f8-139">[Design Details: Searching for Dimension Combinations](design-details-searching-for-dimension-combinations.md) </span></span>  
<span data-ttu-id="229f8-140">[Сведения о проектировании: структура таблицы](design-details-table-structure.md) </span><span class="sxs-lookup"><span data-stu-id="229f8-140">[Design Details: Table Structure](design-details-table-structure.md) </span></span>  
<span data-ttu-id="229f8-141">[Сведения о проектировании: Codeunit 408 Dimension Management](design-details-codeunit-408-dimension-management.md) </span><span class="sxs-lookup"><span data-stu-id="229f8-141">[Design Details: Codeunit 408 Dimension Management](design-details-codeunit-408-dimension-management.md) </span></span>  
<span data-ttu-id="229f8-142">[Сведения о проектировании: примеры кода измененных шаблонов в модификациях](design-details-code-examples-of-changed-patterns-in-modifications.md) </span><span class="sxs-lookup"><span data-stu-id="229f8-142">[Design Details: Code Examples of Changed Patterns in Modifications](design-details-code-examples-of-changed-patterns-in-modifications.md) </span></span>  
[<span data-ttu-id="229f8-143">Сведения о проектировании: операции набора измерений</span><span class="sxs-lookup"><span data-stu-id="229f8-143">Design Details: Dimension Set Entries</span></span>](design-details-dimension-set-entries.md)   

