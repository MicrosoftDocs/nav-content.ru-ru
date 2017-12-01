---
title: "Методы амортизации"
description: "В [!INCLUDE[navnow](../../includes/navnow_md.md)] есть три метода амортизации, доступных только в России."
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
ms.openlocfilehash: 7d638974e01a819a9a1582035d218bf02aabe6f5
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="depreciation-methods"></a><span data-ttu-id="1bb73-103">Методы амортизации</span><span class="sxs-lookup"><span data-stu-id="1bb73-103">Depreciation Methods</span></span>
<span data-ttu-id="1bb73-104">В [!INCLUDE[navnow](../../includes/navnow_md.md)] есть три метода амортизации, доступных только в России.</span><span class="sxs-lookup"><span data-stu-id="1bb73-104">There are three depreciation methods that are unique to Russia that can be used in [!INCLUDE[navnow](../../includes/navnow_md.md)].</span></span>  

- <span data-ttu-id="1bb73-105">Линейный метод — **Линейный (Россия)**</span><span class="sxs-lookup"><span data-stu-id="1bb73-105">Straight-line method **(SL-RU)**</span></span>  
- <span data-ttu-id="1bb73-106">Нелинейный метод — **Ум. ост./лин. (Россия)**</span><span class="sxs-lookup"><span data-stu-id="1bb73-106">Non-linear method **(DB/SL-RU)**</span></span>  
- <span data-ttu-id="1bb73-107">Нелинейный метод для группы ОС — **Ум. ост./лин. (Россия) - группа нал.**</span><span class="sxs-lookup"><span data-stu-id="1bb73-107">Non-linear method for a group of fixed assets **(DB/SL-RU Tax Group)**</span></span>  

## <a name="straight-line-method"></a><span data-ttu-id="1bb73-108">Линейный метод</span><span class="sxs-lookup"><span data-stu-id="1bb73-108">Straight-line Method</span></span>  
 <span data-ttu-id="1bb73-109">Для использования данного метода выберите параметр **Линейный (Россия)** в соответствующей книге амортизации основного средства.</span><span class="sxs-lookup"><span data-stu-id="1bb73-109">To use this method, select the **(SL-RU)** option in the appropriate fixed asset depreciation book.</span></span>  

 <span data-ttu-id="1bb73-110">Основная формула расчета для линейного метода имеет вид K = 1/N * 100%, где K — это ежемесячная норма амортизации, N — номер месяца амортизации.</span><span class="sxs-lookup"><span data-stu-id="1bb73-110">The main calculation formula for the straight-line method is K = 1/N * 100%, where K is the monthly rate of depreciation, and N is the number of depreciation in months.</span></span> <span data-ttu-id="1bb73-111">Метод SL работает следующим образом:</span><span class="sxs-lookup"><span data-stu-id="1bb73-111">The straight line method works as follows:</span></span>  

-   <span data-ttu-id="1bb73-112">Расчет амортизации основывается на ежемесячном принципе; в каждом месяце амортизации 30 дней.</span><span class="sxs-lookup"><span data-stu-id="1bb73-112">The calculation of depreciation is based on the month’s principle, and every depreciation month has 30 days.</span></span> <span data-ttu-id="1bb73-113">Эти параметры настраиваются автоматически во время расчета амортизации.</span><span class="sxs-lookup"><span data-stu-id="1bb73-113">These parameters are automatically set up during calculation of depreciation.</span></span>  

-   <span data-ttu-id="1bb73-114">Дата начала амортизации для любой операции приобретения основного средства является первым днем месяца, следующего за месяцем, когда приобретенное ОС было введено в эксплуатацию.</span><span class="sxs-lookup"><span data-stu-id="1bb73-114">The start date of depreciation for any fixed asset acquisition is the first day of the month that follows the month in which the acquisition is released into operation.</span></span>  

-   <span data-ttu-id="1bb73-115">Дата окончания амортизации является последней датой месяца реализации ОС, его списания или продажи.</span><span class="sxs-lookup"><span data-stu-id="1bb73-115">The end date of depreciation is the end of the month when the fixed asset is disposed, written off, or sold.</span></span>  

-   <span data-ttu-id="1bb73-116">В процессе расчета амортизации система проверяет, что амортизация за предыдущий месяц была учтена для конкретного ОС.</span><span class="sxs-lookup"><span data-stu-id="1bb73-116">During depreciation calculation, the depreciation of the previous month will be checked to see if it has been posted for the particular fixed asset.</span></span> <span data-ttu-id="1bb73-117">Эта функция позволяет избежать пропуска периодов амортизации.</span><span class="sxs-lookup"><span data-stu-id="1bb73-117">This feature enables you to avoid skipping depreciation periods.</span></span>  

## <a name="non-linear-method"></a><span data-ttu-id="1bb73-118">Нелинейный метод</span><span class="sxs-lookup"><span data-stu-id="1bb73-118">Non-linear Method</span></span>  
 <span data-ttu-id="1bb73-119">Для использования данного метода выберите параметр **Ум. ост./лин. (Россия)** в соответствующей книге амортизации основного средства.</span><span class="sxs-lookup"><span data-stu-id="1bb73-119">To use this method, select the **(DB/SL-RU)** option in the appropriate fixed asset depreciation book.</span></span>  

 <span data-ttu-id="1bb73-120">При расчете по нелинейному методу используются две формулы — одна для начала амортизации, а другая для ее завершения.</span><span class="sxs-lookup"><span data-stu-id="1bb73-120">The calculation for the non-linear method consists of two formulas—one for the start of the depreciation and another for the end of the depreciation.</span></span>  

 <span data-ttu-id="1bb73-121">Формула расчета для нелинейного метода имеет вид K = 2/N * 100%, где K — это ежемесячная норма амортизации, N — номер месяца амортизации.</span><span class="sxs-lookup"><span data-stu-id="1bb73-121">The formula for the non-linear method is K = 2/N * 100%, where K is the monthly rate of depreciation, and N is the number of depreciation months.</span></span> <span data-ttu-id="1bb73-122">Константа 2 в этой формуле фиксирована в коде и не должна настраиваться вручную.</span><span class="sxs-lookup"><span data-stu-id="1bb73-122">The constant in this formula, 2, is fixed in the code and should not be set up manually.</span></span>  

 <span data-ttu-id="1bb73-123">Если остаточная стоимость ОС становится равной или меньшей чем 20 процентов стоимости приобретения, ежемесячная амортизация будет рассчитываться по другому.</span><span class="sxs-lookup"><span data-stu-id="1bb73-123">When the book value of the fixed asset becomes equal to or less than 20 percent of the acquisition cost, the monthly depreciation will be calculated differently.</span></span> <span data-ttu-id="1bb73-124">С этого момента используется линейная амортизация до того момента, пока основное средство не будет полностью амортизировано.</span><span class="sxs-lookup"><span data-stu-id="1bb73-124">From this point on, the straight line formula is used to calculate depreciation until the fixed asset is fully depreciated.</span></span>  

 <span data-ttu-id="1bb73-125">Константа в 20 процентов от стоимости приобретения фиксирована в коде и не должна настраиваться вручную.</span><span class="sxs-lookup"><span data-stu-id="1bb73-125">The constant of the acquisition cost, 20 percent, is fixed in the code and should not be set up manually.</span></span>  

## <a name="non-linear-method-for-a-group-of-fixed-assets"></a><span data-ttu-id="1bb73-126">Нелинейный метод для группы ОС</span><span class="sxs-lookup"><span data-stu-id="1bb73-126">Non-linear Method for a Group of Fixed Assets</span></span>  
 <span data-ttu-id="1bb73-127">Для использования данного метода выберите параметр **Ум. ост./лин. (Россия) - группа нал.** в соответствующей книге амортизации основного средства.</span><span class="sxs-lookup"><span data-stu-id="1bb73-127">To use this method, select the **(DB/SL-RU Tax Group)** option in the appropriate fixed asset depreciation book.</span></span>  

 <span data-ttu-id="1bb73-128">Нелинейный метод можно применять к группам основных средств с помощью групп амортизации, настроенных в окне в окне **Группа амортизации**.</span><span class="sxs-lookup"><span data-stu-id="1bb73-128">The non-linear depreciation method can be applied to groups of fixed assets using the depreciation groups set up in the **Depreciation Group** window.</span></span> <span data-ttu-id="1bb73-129">Каждая группа амортизации должна иметь определенные значение **Норма налоговой амортизации** и **Коэффициент амортизации**, равный **1**.</span><span class="sxs-lookup"><span data-stu-id="1bb73-129">Each depreciation group should have a defined **Tax Depreciation Rate** and a **Depreciation Factor** with a value of **1**.</span></span>  

 <span data-ttu-id="1bb73-130">Прежде чем использовать этот метод следует убедиться в том, были применены соответствующие параметры в окне **Настройка налоговых регистров**.</span><span class="sxs-lookup"><span data-stu-id="1bb73-130">Before you use this method, you will have to make sure that the appropriate settings have been applied in the **Tax Register Setup** window.</span></span> <span data-ttu-id="1bb73-131">Используйте информацию в следующей таблице для правильного применения параметров.</span><span class="sxs-lookup"><span data-stu-id="1bb73-131">Use the information in the following table to apply the correct settings.</span></span>  

|<span data-ttu-id="1bb73-132">Поле</span><span class="sxs-lookup"><span data-stu-id="1bb73-132">Field</span></span>|<span data-ttu-id="1bb73-133">Описанием</span><span class="sxs-lookup"><span data-stu-id="1bb73-133">Description</span></span>|  
|---------------------------------|---------------------------------------|  
|<span data-ttu-id="1bb73-134">**Использ. метод групповой аморт. из**</span><span class="sxs-lookup"><span data-stu-id="1bb73-134">**Use Group Depr. Method from**</span></span>|<span data-ttu-id="1bb73-135">Введите дату начала, с которой можно применять нелинейный метод амортизации.</span><span class="sxs-lookup"><span data-stu-id="1bb73-135">Enter the start date from which the non-linear depreciation method can be applied.</span></span> <span data-ttu-id="1bb73-136">Дата должна быть первым днем календарного года.</span><span class="sxs-lookup"><span data-stu-id="1bb73-136">The date should be the first day of the calendar year.</span></span>|  
|<span data-ttu-id="1bb73-137">**Миним. баланс по группе**</span><span class="sxs-lookup"><span data-stu-id="1bb73-137">**Min. Group Balance**</span></span>|<span data-ttu-id="1bb73-138">Введите минимальную сумму, действующую как сальдо для группы амортизации.</span><span class="sxs-lookup"><span data-stu-id="1bb73-138">Enter the minimum amount that is valid as the balance for the depreciation group.</span></span> <span data-ttu-id="1bb73-139">Если учетная стоимость основного средства меньше этой суммы, в этом периоде амортизацию можно списать.</span><span class="sxs-lookup"><span data-stu-id="1bb73-139">If the book value for the fixed assets is less than this amount, the depreciation can be written off in this period.</span></span>|  
|<span data-ttu-id="1bb73-140">**Списание в расходы**</span><span class="sxs-lookup"><span data-stu-id="1bb73-140">**Write-off in Charges**</span></span>|<span data-ttu-id="1bb73-141">Укажите, нужно ли списывать издержки ОС, если балансовая стоимость основного средства списывается в периоде, когда балансовая стоимость меньше или равна сумме **Миним. баланс по группе**.</span><span class="sxs-lookup"><span data-stu-id="1bb73-141">Select if you want to write off fixed asset charges if the book value of the fixed assets is written off in the period when the book value is less than or equal to the **Min. Group Balance** amount.</span></span> <span data-ttu-id="1bb73-142">В противном случае балансовая стоимость будет списана в следующем периоде.</span><span class="sxs-lookup"><span data-stu-id="1bb73-142">Otherwise, the book value will be written off in the next period.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="1bb73-143">См. также</span><span class="sxs-lookup"><span data-stu-id="1bb73-143">See Also</span></span>  
 <span data-ttu-id="1bb73-144">[Амортизационная премия](depreciation-bonus.md) </span><span class="sxs-lookup"><span data-stu-id="1bb73-144">[Depreciation Bonus](depreciation-bonus.md) </span></span>  
 [<span data-ttu-id="1bb73-145">Практическое руководство. Настройка амортизации основных средств</span><span class="sxs-lookup"><span data-stu-id="1bb73-145">How to: Set Up Fixed Asset Depreciation</span></span>](../../fa-how-setup-depreciation.md)

