---
title: "Практическое руководство. Учет налоговых разниц"
description: "**Журнал налоговых разниц** используется для создания и учета транзакций для налоговых разниц. Налоговые разницы представляют собой расхождения сумм налога, вызванные различиями в правилах признания доходов и расходов в бухгалтерском и налоговом учете."
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
ms.openlocfilehash: ac872b314ac6626eb5e8755ba905195c88cdc9f5
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-post-tax-differences"></a><span data-ttu-id="d4d2f-104">Практическое руководство. Учет налоговых разниц</span><span class="sxs-lookup"><span data-stu-id="d4d2f-104">How to: Post Tax Differences</span></span>
<span data-ttu-id="d4d2f-105">**Журнал налоговых разниц** используется для создания и учета транзакций для налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-105">The **Tax Difference Journal** is used to create and post tax difference transactions.</span></span> <span data-ttu-id="d4d2f-106">Налоговые разницы представляют собой расхождения сумм налога, вызванные различиями в правилах признания доходов и расходов в бухгалтерском и налоговом учете.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-106">Tax differences are variations in tax amounts caused by the different rules for recognizing income and expenses between entries for book accounting and tax accounting.</span></span>  

<span data-ttu-id="d4d2f-107">С помощью окна **Журнал налоговых разниц** можно вручную создавать операции налоговых разниц и изменять имеющиеся операции, созданные периодическими процедурами расчета налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-107">You can use the **Tax Difference Journal** window to manually create tax difference journal entries or you can modify existing entries created by periodic tax difference calculation activities.</span></span> <span data-ttu-id="d4d2f-108">При учете окна **Журнал налоговых разниц** соответствующие операции учитываются в выбранных учетных группах.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-108">When you post the **Tax Difference Journal** window, tax differences entries are posted to the selected posting groups.</span></span>  

## <a name="to-post-tax-differences"></a><span data-ttu-id="d4d2f-109">Учет налоговых разниц</span><span class="sxs-lookup"><span data-stu-id="d4d2f-109">To post tax differences</span></span>  

1.  <span data-ttu-id="d4d2f-110">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы налоговых разниц**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Tax Difference Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d4d2f-111">Введите значения в поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-111">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="d4d2f-112">Поле</span><span class="sxs-lookup"><span data-stu-id="d4d2f-112">Field</span></span>|<span data-ttu-id="d4d2f-113">Описанием</span><span class="sxs-lookup"><span data-stu-id="d4d2f-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="d4d2f-114">**Дата учета**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-114">**Posting Date**</span></span>|<span data-ttu-id="d4d2f-115">Введите дату транзакции.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-115">Enter the transaction date.</span></span>|  
    |<span data-ttu-id="d4d2f-116">**Номер документа:**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-116">**Document No.**</span></span>|<span data-ttu-id="d4d2f-117">Введите номер документа из исходной транзакции.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-117">Enter the document number from the source transaction.</span></span>|  
    |<span data-ttu-id="d4d2f-118">**Описание**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-118">**Description**</span></span>|<span data-ttu-id="d4d2f-119">Введите описание транзакции.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-119">Enter a description for the transaction.</span></span>|  
    |<span data-ttu-id="d4d2f-120">**Тип налог. разницы**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-120">**Tax Diff. Type**</span></span>|<span data-ttu-id="d4d2f-121">Укажите, является налоговая разница **постоянной** или **временной**.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-121">Select if the tax difference is **Constant** or **Temporary**.</span></span>|  
    |<span data-ttu-id="d4d2f-122">**Код налог. разницы**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-122">**Tax Diff. Code**</span></span>|<span data-ttu-id="d4d2f-123">Выберите идентификационный код дохода или расхода, определяющий источник налоговой разницы.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-123">Select an identifying income or expense code that defines the source of the tax difference.</span></span>|  
    |<span data-ttu-id="d4d2f-124">**Тип источника**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-124">**Source Type**</span></span>|<span data-ttu-id="d4d2f-125">Выберите источник налоговой разницы.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-125">Select the source of tax difference.</span></span> <span data-ttu-id="d4d2f-126">Возможные варианты: **Расходы будущих периодов**, **Основное средство** и **Нематериальный актив**.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-126">The options include **Future Expense**, **Fixed Asset**, and **Intangible Asset**.</span></span>|  
    |<span data-ttu-id="d4d2f-127">**Номер источника**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-127">**Source No.**</span></span>|<span data-ttu-id="d4d2f-128">Если поле **Тип источника** имеет значение **Расходы будущих периодов**, введите код расходов будущих периодов.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-128">If the **Source Type** is **Future Expense**, enter an identifying code for the future period expenses.</span></span>  <span data-ttu-id="d4d2f-129">В противном случае это поле следует оставить пустым.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-129">Otherwise, leave this field blank.</span></span>|  
    |<span data-ttu-id="d4d2f-130">**Код Юрисдикции**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-130">**Jurisdiction Code**</span></span>|<span data-ttu-id="d4d2f-131">Выберите код юрисдикции, который используется для расчета налогооблагаемых прибыли и убытков для налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-131">Select the identifying code for the jurisdiction that is used to calculate taxable profits and losses for tax differences.</span></span>|  
    |<span data-ttu-id="d4d2f-132">**Код Нормы**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-132">**Norm Code**</span></span>|<span data-ttu-id="d4d2f-133">Выберите код юрисдикции нормы, который используется для расчета налогооблагаемых прибыли и убытков для налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-133">Select the identifying code for the norm jurisdiction that is used to calculate taxable profits and losses for the tax differences.</span></span>|  
    |<span data-ttu-id="d4d2f-134">**Ставка Налога**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-134">**Tax Factor**</span></span>|<span data-ttu-id="d4d2f-135">Введите ставку налога на прибыль, которая используется для расчета налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-135">Enter the profit tax rate that is used to calculate tax differences.</span></span>|  
    |<span data-ttu-id="d4d2f-136">**Сумма (БУ)**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-136">**Amount (Base)**</span></span>|<span data-ttu-id="d4d2f-137">Введите сумму расходов на основании данных бухгалтерского учета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-137">Enter an expense amount based on book accounting transactions.</span></span> <span data-ttu-id="d4d2f-138">Эта информация используется, если настроен расчет налоговых разниц для периода времени.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-138">This information is used if the tax difference calculation is for a set period of time.</span></span>|  
    |<span data-ttu-id="d4d2f-139">**Сумма (НУ)**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-139">**Amount (Tax)**</span></span>|<span data-ttu-id="d4d2f-140">Введите сумму расходов на основании транзакций налогового учета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-140">Enter an expense amount based on tax accounting transactions.</span></span> <span data-ttu-id="d4d2f-141">Эта информация используется, если настроен расчет налоговых разниц для периода времени.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-141">This information is used if the tax difference calculation is for a set period of time.</span></span>|  
    |<span data-ttu-id="d4d2f-142">**Разница**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-142">**Difference**</span></span>|<span data-ttu-id="d4d2f-143">Введите значение разницы между транзакциями бухгалтерского и налогового учета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-143">Enter the value of the difference between the book accounting and tax accounting transactions.</span></span>|  
    |<span data-ttu-id="d4d2f-144">**Сумма на Конец НП (БУ)**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-144">**YTD Amount (Base)**</span></span>|<span data-ttu-id="d4d2f-145">Введите значение расходов и доходов по данным бухгалтерского учета с начала года.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-145">Enter the year-to-date value of the expense or income amount based on the book accounting data.</span></span>|  
    |<span data-ttu-id="d4d2f-146">**Сумма на Конец НП (НУ)**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-146">**YTD Amount (Tax)**</span></span>|<span data-ttu-id="d4d2f-147">Введите значение расходов и доходов по данным налогового учета с начала года.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-147">Enter the year-to-date value of the expense or income amount based on the tax accounting data.</span></span>|  
    |<span data-ttu-id="d4d2f-148">**Разница на Конец НП**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-148">**YTD Difference**</span></span>|<span data-ttu-id="d4d2f-149">Введите значение разницы между транзакциями бухгалтерского и налогового учета с начала года.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-149">Enter the year-to-date value of the difference between the book accounting and tax accounting transactions.</span></span>|  
    |<span data-ttu-id="d4d2f-150">**Реж. расч. налог. разницы**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-150">**Tax Diff. Calc. Mode**</span></span>|<span data-ttu-id="d4d2f-151">Определяет разницу режима подсчета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-151">Specifies the difference of the counting mode.</span></span> <span data-ttu-id="d4d2f-152">Если выбрано значение **Баланс**, разница будет рассчитываться нарастающим итогом с начала года.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-152">If **Balance** is selected, the difference will be calculated by a creating total starting from the start of the year.</span></span> <span data-ttu-id="d4d2f-153">Если это поле не выбрано, разница будет создана для текущего периода.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-153">If not selected, the difference will be created for the current period.</span></span>|  
    |<span data-ttu-id="d4d2f-154">**Сумма Налога**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-154">**Tax Amount**</span></span>|<span data-ttu-id="d4d2f-155">Определяет результат подсчета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-155">Specifies the counting result.</span></span> <span data-ttu-id="d4d2f-156">Значение этого поля корректирует налог на прибыль в транзакциях бухгалтерского учета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-156">The value of this field will correct the profit tax in the book accounting transactions.</span></span>|  
    |<span data-ttu-id="d4d2f-157">**Сумма Налог. Актива**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-157">**Asset Tax Amount**</span></span>|<span data-ttu-id="d4d2f-158">Определяет рассчитанную сумму налогового актива.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-158">Specifies the calculated asset tax amount.</span></span>|  
    |<span data-ttu-id="d4d2f-159">**Сумма Налог. Обязательства**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-159">**Liability Tax Amount**</span></span>|<span data-ttu-id="d4d2f-160">Определяет рассчитанную сумму налогового обязательства.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-160">Specifies the calculated liability tax amount.</span></span>|  
    |<span data-ttu-id="d4d2f-161">**Сумма Списания ОНО/ОНА**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-161">**Disposal Tax Amount**</span></span>|<span data-ttu-id="d4d2f-162">Определяет сумму налога, которая списывается при реализации товара.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-162">Specifies the tax amount that is written off at disposal of an item.</span></span>|  
    |<span data-ttu-id="d4d2f-163">**ОНА Начальное Сальдо**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-163">**DTA Starting Balance**</span></span>|<span data-ttu-id="d4d2f-164">Определяет начальную сумму реализации ОНО/ОНА перед расчетом.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-164">Specifies the starting disposal tax amount before counting.</span></span>|  
    |<span data-ttu-id="d4d2f-165">**ОНО Начальное Сальдо**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-165">**DTL Starting Balance**</span></span>|<span data-ttu-id="d4d2f-166">Определяет обязательства по начальной сумме реализации ОНО/ОНА перед расчетом.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-166">Specifies the starting disposal tax liability amount before counting.</span></span>|  
    |<span data-ttu-id="d4d2f-167">**ОНА Конечное Сальдо**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-167">**DTA Ending Balance**</span></span>|<span data-ttu-id="d4d2f-168">Определяет сумму реализации ОНО/ОНА после расчета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-168">Specifies the disposal tax amount after counting.</span></span>|  
    |<span data-ttu-id="d4d2f-169">**ОНО Конечное Сальдо**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-169">**DTL Ending Balance**</span></span>|<span data-ttu-id="d4d2f-170">Определяет обязательства по сумме реализации ОНО/ОНА после расчета.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-170">Specifies the disposal tax liability amount after counting.</span></span>|  
    |<span data-ttu-id="d4d2f-171">**Режим Выбытия**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-171">**Disposal Mode**</span></span>|<span data-ttu-id="d4d2f-172">Выберите, требуется ли записать налоговую разницу или преобразовать ее в постоянную разницу.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-172">Select if you want to write down the tax difference or transform it into a constant difference.</span></span>|  
    |<span data-ttu-id="d4d2f-173">**Дата Выбытия**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-173">**Disposal Date**</span></span>|<span data-ttu-id="d4d2f-174">Введите дату реализации товара.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-174">Enter the date of the item’s disposal.</span></span>|  
    |<span data-ttu-id="d4d2f-175">**Частичное Выбытие**</span><span class="sxs-lookup"><span data-stu-id="d4d2f-175">**Partial Disposal**</span></span>|<span data-ttu-id="d4d2f-176">Выберите, если требуется реализовать товар, который приводит к расхождениям в коде расходов или доходов.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-176">Select if you want to dispose of an item that causes differences in the expense or income code.</span></span> <span data-ttu-id="d4d2f-177">Если данное поле не выбрано, налоговые разницы списываются.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-177">If this field is not selected, the tax differences are written off.</span></span>|  

3.  <span data-ttu-id="d4d2f-178">Выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-178">Choose the **Post** action.</span></span> <span data-ttu-id="d4d2f-179">Транзакции журнала налоговых разниц будут учтены.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-179">The tax difference journal transaction is posted.</span></span>  
4.  <span data-ttu-id="d4d2f-180">Выберите действие **Книга операций**, чтобы открыть окно **Книга операций по налоговым разницам** и проверить учтенные операции.</span><span class="sxs-lookup"><span data-stu-id="d4d2f-180">Choose the **Ledger Entries** action to open the **Tax Diff. Ledger Entry** window and review the posted entries.</span></span>  

## <a name="see-also"></a><span data-ttu-id="d4d2f-181">См. также</span><span class="sxs-lookup"><span data-stu-id="d4d2f-181">See Also</span></span>  
 <span data-ttu-id="d4d2f-182">[Налоговые разницы](tax-differences.md) </span><span class="sxs-lookup"><span data-stu-id="d4d2f-182">[Tax Differences](tax-differences.md) </span></span>  
 <span data-ttu-id="d4d2f-183">[Настройка расчета налоговых разниц](setting-up-tax-difference-calculation.md) </span><span class="sxs-lookup"><span data-stu-id="d4d2f-183">[Setting up Tax Difference Calculation](setting-up-tax-difference-calculation.md) </span></span>  
 <span data-ttu-id="d4d2f-184">[Налоговый учет](tax-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="d4d2f-184">[Tax Accounting](tax-accounting.md) </span></span>  
 <span data-ttu-id="d4d2f-185">[Налоговые отчеты](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span><span class="sxs-lookup"><span data-stu-id="d4d2f-185">[Tax Reports](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span></span>  
 <span data-ttu-id="d4d2f-186">[Налоговые регистры](tax-registers.md) </span><span class="sxs-lookup"><span data-stu-id="d4d2f-186">[Tax Registers](tax-registers.md) </span></span>  
 [<span data-ttu-id="d4d2f-187">Практическое руководство. Создание налоговых регистров</span><span class="sxs-lookup"><span data-stu-id="d4d2f-187">How to: Create Tax Registers</span></span>](how-to-create-tax-registers.md)
