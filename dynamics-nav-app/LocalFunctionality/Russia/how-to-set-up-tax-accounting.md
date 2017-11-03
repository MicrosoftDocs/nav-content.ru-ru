---
title: "Практическое руководство. Настройка налогового учета"
description: "Налоговый учет позволяет применять правила признания доходов и расходов в соответствии с местным законодательством. Вы можете активировать функции налогового учета в [!INCLUDE[navnow](../../includes/navnow_md.md)], настроив налоговые регистры."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 55c573babe523cb72ffe5220d95d53e8915e9dd3
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-set-up-tax-accounting"></a><span data-ttu-id="e917c-104">Практическое руководство. Настройка налогового учета</span><span class="sxs-lookup"><span data-stu-id="e917c-104">How to: Set Up Tax Accounting</span></span>
<span data-ttu-id="e917c-105">Налоговый учет позволяет применять правила признания доходов и расходов в соответствии с местным законодательством.</span><span class="sxs-lookup"><span data-stu-id="e917c-105">Tax accounting lets you apply rules for recognizing income and expenses that follow your local tax laws.</span></span> <span data-ttu-id="e917c-106">Вы можете активировать функции налогового учета в [!INCLUDE[navnow](../../includes/navnow_md.md)], настроив налоговые регистры.</span><span class="sxs-lookup"><span data-stu-id="e917c-106">You can activate tax accounting features in [!INCLUDE[navnow](../../includes/navnow_md.md)] by setting up tax registers.</span></span>  

## <a name="to-activate-tax-accounting"></a><span data-ttu-id="e917c-107">Активация налогового учета</span><span class="sxs-lookup"><span data-stu-id="e917c-107">To activate tax accounting</span></span>  

1.  <span data-ttu-id="e917c-108">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка налоговых регистров**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e917c-108">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Tax Register Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="e917c-109">На экспресс-вкладке **Общее** выберите коды для следующих измерений.</span><span class="sxs-lookup"><span data-stu-id="e917c-109">On the **General** FastTab, select codes for the following dimensions.</span></span>  

    |<span data-ttu-id="e917c-110">Поле</span><span class="sxs-lookup"><span data-stu-id="e917c-110">Field</span></span>|<span data-ttu-id="e917c-111">Описанием</span><span class="sxs-lookup"><span data-stu-id="e917c-111">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="e917c-112">**Условие - код измерения**</span><span class="sxs-lookup"><span data-stu-id="e917c-112">**Condition Dimension Code**</span></span>|<span data-ttu-id="e917c-113">Выберите код измерения, описывающий условие налогового регистра.</span><span class="sxs-lookup"><span data-stu-id="e917c-113">Select a dimension code that describes the condition of the tax register.</span></span>|  
    |<span data-ttu-id="e917c-114">**Вид - код измерения**</span><span class="sxs-lookup"><span data-stu-id="e917c-114">**Kind Dimension Code**</span></span>|<span data-ttu-id="e917c-115">Выберите код измерения, описывающий тип налогового регистра.</span><span class="sxs-lookup"><span data-stu-id="e917c-115">Select a dimension code that describes the type of tax register.</span></span>|  

3.  <span data-ttu-id="e917c-116">Выберите следующие поля, чтобы активировать операции в налоговом регистре.</span><span class="sxs-lookup"><span data-stu-id="e917c-116">Select the following fields to activate entries in the tax register.</span></span>  

    |<span data-ttu-id="e917c-117">Поле</span><span class="sxs-lookup"><span data-stu-id="e917c-117">Field</span></span>|<span data-ttu-id="e917c-118">Описанием</span><span class="sxs-lookup"><span data-stu-id="e917c-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="e917c-119">**Создавать Приобретение в ОС Книге по Нал. Книге Аморт.**</span><span class="sxs-lookup"><span data-stu-id="e917c-119">**Create Acquis. FA Tax Ledger**</span></span>|<span data-ttu-id="e917c-120">Выберите, чтобы создать операции приобретения ОС.</span><span class="sxs-lookup"><span data-stu-id="e917c-120">Select to create fixed asset acquisition entries.</span></span>|  
    |<span data-ttu-id="e917c-121">**Создавать Реклассификацию в ОС Книге по Нал. Книге Аморт.**</span><span class="sxs-lookup"><span data-stu-id="e917c-121">**Create Reclass. FA Tax Ledger**</span></span>|<span data-ttu-id="e917c-122">Выберите, чтобы создать операции реклассификации ОС.</span><span class="sxs-lookup"><span data-stu-id="e917c-122">Select to create fixed asset reclassification entries.</span></span>|  
    |<span data-ttu-id="e917c-123">**Создавать РБП по приобр. в НУ**</span><span class="sxs-lookup"><span data-stu-id="e917c-123">**Create Acquis. FE Tax Ledger**</span></span>|<span data-ttu-id="e917c-124">Выберите, чтобы создать операции приобретения с учетом в будущих периодах.</span><span class="sxs-lookup"><span data-stu-id="e917c-124">Select to create future expense acquisition entries.</span></span>|  

4.  <span data-ttu-id="e917c-125">Выберите соответствующие книги амортизации в полях **Книга амортизации для налогового учета** и **Расх. буд. пер. - книга аморт.**.</span><span class="sxs-lookup"><span data-stu-id="e917c-125">Select the appropriate depreciation books in the **Tax Depreciation Book** and **Future Exp. Depreciation Book** fields.</span></span> <span data-ttu-id="e917c-126">Книги амортизации, которые вы выбрали, должны быть интегрированы с модулем финансов [!INCLUDE[navnow](../../includes/navnow_md.md)].</span><span class="sxs-lookup"><span data-stu-id="e917c-126">The depreciation books that you select should not be integrated with the [!INCLUDE[navnow](../../includes/navnow_md.md)] finance module.</span></span>  

5.  <span data-ttu-id="e917c-127">Установите флажок **Создать данные для печати форм**, чтобы разрешить печать подробных данные налогового регистра в отчетах и формах.</span><span class="sxs-lookup"><span data-stu-id="e917c-127">Select the **Create Data for Printing Forms** check box to enable detailed tax register entry information to be printed on reports and forms.</span></span>  
6.  <span data-ttu-id="e917c-128">Нажмите кнопку **Закрыть**, чтобы закрыть окно и сохранить введенные данные.</span><span class="sxs-lookup"><span data-stu-id="e917c-128">Choose the **Close** button to close the window and save your entries.</span></span>  

<span data-ttu-id="e917c-129">Дополнительные сведения о том, как настроить налоговые регистры, см. в разделе [Практическое руководство. Создание налоговых регистров](how-to-create-tax-registers.md).</span><span class="sxs-lookup"><span data-stu-id="e917c-129">For more information about how to set up and customize tax registers, see [How to: Create Tax Registers](how-to-create-tax-registers.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="e917c-130">См. также</span><span class="sxs-lookup"><span data-stu-id="e917c-130">See Also</span></span>  
 <span data-ttu-id="e917c-131">[Налоговый учет](tax-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="e917c-131">[Tax Accounting](tax-accounting.md) </span></span>  
 <span data-ttu-id="e917c-132">[Налоговые отчеты](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span><span class="sxs-lookup"><span data-stu-id="e917c-132">[Tax Reports](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span></span>  
 <span data-ttu-id="e917c-133">[Налоговые регистры](tax-registers.md) </span><span class="sxs-lookup"><span data-stu-id="e917c-133">[Tax Registers](tax-registers.md) </span></span>  
 <span data-ttu-id="e917c-134">[Практическое руководство. Создание налоговых регистров](how-to-create-tax-registers.md) </span><span class="sxs-lookup"><span data-stu-id="e917c-134">[How to: Create Tax Registers](how-to-create-tax-registers.md) </span></span>  
 [<span data-ttu-id="e917c-135">Налоговые разницы</span><span class="sxs-lookup"><span data-stu-id="e917c-135">Tax Differences</span></span>](tax-differences.md)

