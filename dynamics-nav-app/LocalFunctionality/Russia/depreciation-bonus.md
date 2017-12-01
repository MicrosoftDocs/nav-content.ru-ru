---
title: "Амортизационная премия"
description: "Амортизационная премия представляет собой метод ускоренной амортизации, применяемый в налоговом учете в связи с положениями налогового законодательства России. Амортизационная премия позволяет включить затраты на основные средства и капиталовложения в текущий период по ставке, равной 10 или 30 процентам."
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
ms.openlocfilehash: 15f1aa4bb291c4bf5097b23e50ab1b69b9062be6
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="depreciation-bonus"></a><span data-ttu-id="839e1-104">Амортизационная премия</span><span class="sxs-lookup"><span data-stu-id="839e1-104">Depreciation Bonus</span></span>
<span data-ttu-id="839e1-105">*Амортизационная премия* представляет собой метод ускоренной амортизации, применяемый в налоговом учете в связи с положениями налогового законодательства России.</span><span class="sxs-lookup"><span data-stu-id="839e1-105">*Depreciation bonus* is an accelerated depreciation method applied in tax accounting because of provisions in the Russian tax laws.</span></span> <span data-ttu-id="839e1-106">Амортизационная премия позволяет включить затраты на основные средства и капиталовложения в текущий период по ставке, равной 10 или 30 процентам.</span><span class="sxs-lookup"><span data-stu-id="839e1-106">A depreciation bonus enables you to include fixed asset and capital investment expenses in the current period at the rate of 10 percent or 30 percent.</span></span>  

## <a name="depreciation-bonus-calculation"></a><span data-ttu-id="839e1-107">Расчет амортизационной премии</span><span class="sxs-lookup"><span data-stu-id="839e1-107">Depreciation Bonus Calculation</span></span>  
<span data-ttu-id="839e1-108">Амортизационная премия может рассчитываться и применяться для следующих типов транзакций:</span><span class="sxs-lookup"><span data-stu-id="839e1-108">A depreciation bonus can be calculated and applied for the following types of transactions:</span></span>  

- <span data-ttu-id="839e1-109">Затраты на приобретение основных средств.</span><span class="sxs-lookup"><span data-stu-id="839e1-109">Acquisition costs of fixed assets.</span></span>  
- <span data-ttu-id="839e1-110">Затраты на приобретение и повышение оценочной стоимости капиталовложений для всех предшествующих периодов, исключая текущий.</span><span class="sxs-lookup"><span data-stu-id="839e1-110">Acquisition costs and appreciation of capital investments for all previous periods excluding the current period.</span></span>  

<span data-ttu-id="839e1-111">Ставка амортизационной премии составляет 10 или 30 процентов в зависимости от класса основных средств.</span><span class="sxs-lookup"><span data-stu-id="839e1-111">The rate of the depreciation bonus is 10 percent or 30 percent, depending on the class of the fixed asset.</span></span> <span data-ttu-id="839e1-112">Ставка установлена для группы амортизации с помощью поля **Процент амортизационной премии** в окне **Группа амортизации**.</span><span class="sxs-lookup"><span data-stu-id="839e1-112">The rate is set for a depreciation group using the **Depr. Bonus Percentage** field in the **Depreciation Group** window.</span></span>  

<span data-ttu-id="839e1-113">После того как амортизационная премия рассчитана и учтена для периода, все транзакции очищаются для подготовки к следующему периоду.</span><span class="sxs-lookup"><span data-stu-id="839e1-113">After the depreciation bonus is calculated and posted for a period, all transactions are cleared in preparation for the next period.</span></span>  

## <a name="depreciation-bonus-settings"></a><span data-ttu-id="839e1-114">Параметры амортизационной премии</span><span class="sxs-lookup"><span data-stu-id="839e1-114">Depreciation Bonus Settings</span></span>  
<span data-ttu-id="839e1-115">Перед расчетом амортизационной премии необходимо убедиться в том, были применены соответствующие параметры в окне **Настройка налоговых регистров**.</span><span class="sxs-lookup"><span data-stu-id="839e1-115">Before depreciation bonus is calculated, you will have to make sure that the appropriate settings have been applied in the **Tax Register Setup** window.</span></span> <span data-ttu-id="839e1-116">Используйте информацию в следующей таблице для применения параметров амортизационной премии.</span><span class="sxs-lookup"><span data-stu-id="839e1-116">Use the information in the following table to apply depreciation bonus settings.</span></span>  

|<span data-ttu-id="839e1-117">Поле</span><span class="sxs-lookup"><span data-stu-id="839e1-117">Field</span></span>|<span data-ttu-id="839e1-118">Описанием</span><span class="sxs-lookup"><span data-stu-id="839e1-118">Description</span></span>|  
|---------------------------------|---------------------------------------|  
|<span data-ttu-id="839e1-119">**Вкл. акт ввода в эксп. в расчет аморт. премии**</span><span class="sxs-lookup"><span data-stu-id="839e1-119">**Rel. Act as Depr. Bonus Base**</span></span>|<span data-ttu-id="839e1-120">Выберите, требуется ли использовать прием-передачу ОС для расчета базы амортизационной премии.</span><span class="sxs-lookup"><span data-stu-id="839e1-120">Select if you want fixed asset releases to be used to calculate the depreciation bonus base.</span></span>|  
|<span data-ttu-id="839e1-121">**Код нал. разн. по аморт. премии**</span><span class="sxs-lookup"><span data-stu-id="839e1-121">**Depr. Bonus TD Code**</span></span>|<span data-ttu-id="839e1-122">Введите код налоговой разницы, который используется для вычисления амортизационной премии.</span><span class="sxs-lookup"><span data-stu-id="839e1-122">Enter a tax difference code that is used to calculate the depreciation bonus.</span></span> <span data-ttu-id="839e1-123">Выбранный код налоговой разницы должен быть задан как амортизационная премия во время настройки налоговой разницы.</span><span class="sxs-lookup"><span data-stu-id="839e1-123">The selected tax difference code should be identified as a depreciation bonus during tax difference setup.</span></span>|  
|<span data-ttu-id="839e1-124">**Восстановление аморт. премии c**</span><span class="sxs-lookup"><span data-stu-id="839e1-124">**Depr. Bonus Recovery from**</span></span>|<span data-ttu-id="839e1-125">Введите начальную дату восстановления амортизации в случае продажи ОС.</span><span class="sxs-lookup"><span data-stu-id="839e1-125">Enter the starting date from which depreciation is recovered if the fixed asset is sold.</span></span> <span data-ttu-id="839e1-126">Если основное средство продано до этой даты и уже была применена амортизационная премия, амортизационная премия не будет восстанавливаться.</span><span class="sxs-lookup"><span data-stu-id="839e1-126">If the fixed asset is sold before this date and the depreciation bonus has already been applied, the depreciation bonus will not be recovered.</span></span>|  
|<span data-ttu-id="839e1-127">**Период восстановл. аморт. премии (лет)**</span><span class="sxs-lookup"><span data-stu-id="839e1-127">**Depr. Bonus Recov. Per. (Year)**</span></span>|<span data-ttu-id="839e1-128">Введите период, в который производится восстановления амортизационной премии в случае продажи ОС.</span><span class="sxs-lookup"><span data-stu-id="839e1-128">Enter the period in which the depreciation bonus is recovered if the fixed asset is sold.</span></span>|  
|<span data-ttu-id="839e1-129">**Код нал.разн. для восстановл. аморт.премии**</span><span class="sxs-lookup"><span data-stu-id="839e1-129">**Depr. Bonus Recovery TD Code**</span></span>|<span data-ttu-id="839e1-130">Ведите код налоговой разницы, который используется для вычисления суммы восстановления амортизационной премии в налоговом учете.</span><span class="sxs-lookup"><span data-stu-id="839e1-130">Enter the tax difference code that is used to calculate the depreciation bonus recovery amount in tax accounting.</span></span>|  

## <a name="selecting-and-canceling-depreciation-bonus-transactions"></a><span data-ttu-id="839e1-131">Выбор и отмена транзакций амортизационной премии</span><span class="sxs-lookup"><span data-stu-id="839e1-131">Selecting and Canceling Depreciation Bonus Transactions</span></span>  
<span data-ttu-id="839e1-132">Транзакции амортизационной премии должны учитываться до расчета и учета суммы ежемесячной амортизации.</span><span class="sxs-lookup"><span data-stu-id="839e1-132">Depreciation bonus transactions should be posted before the monthly depreciation amount is calculated and posted.</span></span>  

<span data-ttu-id="839e1-133">Для выбора транзакций амортизационной премии публикации для учета за период выберите **Аморт. премия** в окне **Журнал ОС** и окне **Журнал ГК основных средств**.</span><span class="sxs-lookup"><span data-stu-id="839e1-133">To select depreciation bonus transactions for posting for a period, select **Depr. Bonus** in the **Fixed Asset Journal** window and the **Fixed Asset G/L Journal** window.</span></span>  

<span data-ttu-id="839e1-134">Можно отменять транзакции амортизационной премии путем выполнения пакетного задания **Отменить операции книги ОС**.</span><span class="sxs-lookup"><span data-stu-id="839e1-134">You can cancel depreciation bonus transactions by running the **Cancel FA Ledger Entries** batch job.</span></span> <span data-ttu-id="839e1-135">После учета отмены амортизационной премии все операции, включенные в базу амортизационной премии, необходимо вручную выбрать как базу амортизационной премии.</span><span class="sxs-lookup"><span data-stu-id="839e1-135">After posting the depreciation bonus cancellation, all operations that are included in the depreciation bonus base must be manually selected as the depreciation bonus base.</span></span>  

## <a name="see-also"></a><span data-ttu-id="839e1-136">См. также</span><span class="sxs-lookup"><span data-stu-id="839e1-136">See Also</span></span>  
[<span data-ttu-id="839e1-137">Основные Средства</span><span class="sxs-lookup"><span data-stu-id="839e1-137">Fixed Assets</span></span>](../../fa-manage.md)  

