---
title: "Изменение внешнего вида отчета путем выбора другого макета"
description: "Вы можете использовать различные макеты для отчетов и переключаться между ними, чтобы изменять внешний вид отчета."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7fc680503a3fb2d685758b69e123dc98b2d98e75
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a><span data-ttu-id="f02f6-103">Практическое руководство. Изменение макета, в настоящее время используемого в отчете</span><span class="sxs-lookup"><span data-stu-id="f02f6-103">How to: Change Which Layout is Currently Used on a Report</span></span>
<span data-ttu-id="f02f6-104">Отчет можно настроить с использованием нескольких макетов, между которыми затем при необходимости можно будет переключаться.</span><span class="sxs-lookup"><span data-stu-id="f02f6-104">A report can be set up with more than one report layout, which you can then switch among as needed.</span></span>

<span data-ttu-id="f02f6-105">В зависимости от доступных для отчета макетов можно принять решение об использовании встроенного макета отчета RDLC, встроенного макета отчета Word или пользовательского макета.</span><span class="sxs-lookup"><span data-stu-id="f02f6-105">Depending on the layouts that are available for a report, you can choose to use a built-in RDLC report layout, a built-in Word report layout, or a custom layout.</span></span> <span data-ttu-id="f02f6-106">Дополнительные сведения о макетах отчетов RDLC и Word, встроенных и пользовательских макетах и др. см. в разделе [Управление макетами отчетов](ui-manage-report-layouts.md).</span><span class="sxs-lookup"><span data-stu-id="f02f6-106">For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).</span></span>

## <a name="to-change-the-layout-that-is-used-on-a-report"></a><span data-ttu-id="f02f6-107">Изменение макета, используемого в отчете</span><span class="sxs-lookup"><span data-stu-id="f02f6-107">To change the layout that is used on a report</span></span>
1. <span data-ttu-id="f02f6-108">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Выбор макета отчета**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f02f6-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Report Layout Selection**, and then choose the related link.</span></span>  
   <span data-ttu-id="f02f6-109">В окне **Выбор макета отчета** перечисляются все доступные отчеты для организации, которая указана в поле "Организация" в верхней части окна.</span><span class="sxs-lookup"><span data-stu-id="f02f6-109">The **Report Layout Selection** window lists all the reports that are available for the company that is specified in the Company field at the top of the window.</span></span> <span data-ttu-id="f02f6-110">Поле "Выбранный макет" задает макет, который в настоящее время используется в отчете.</span><span class="sxs-lookup"><span data-stu-id="f02f6-110">The Selected Layout field specifies the layout that is currently used on the report.</span></span>
2. <span data-ttu-id="f02f6-111">Укажите в поле **Организация** в верхней части окна организацию, которую требуется включить в отчет.</span><span class="sxs-lookup"><span data-stu-id="f02f6-111">Set the **Company** field at the top of the window to the company that includes the report.</span></span>
3. <span data-ttu-id="f02f6-112">Чтобы изменить макет отчета, в строке отчета в списке настройте в поле **Выбранный отчет** один из следующих вариантов.</span><span class="sxs-lookup"><span data-stu-id="f02f6-112">To change the layout that is used by a report, in the row for the report in the list, set the **Selected Layout** field to one of the following options:</span></span>
   * <span data-ttu-id="f02f6-113">RDLC (встроенный), использует встроенный макет отчета RDLC.</span><span class="sxs-lookup"><span data-stu-id="f02f6-113">RDLC (built-in), uses the built-in RDLC report layout on the report.</span></span>
   * <span data-ttu-id="f02f6-114">Word (встроенный), использует встроенный макет отчета Word.</span><span class="sxs-lookup"><span data-stu-id="f02f6-114">Word (built-in), uses the built-in Word report layout on the report.</span></span>
   * <span data-ttu-id="f02f6-115">Пользовательский, использует пользовательский макет отчета.</span><span class="sxs-lookup"><span data-stu-id="f02f6-115">Custom, uses a custom layout on the report.</span></span>  
     <span data-ttu-id="f02f6-116">Можно просмотреть, какие пользовательские отчеты доступны для отчета на информационной панели "Часть макетов отчета".</span><span class="sxs-lookup"><span data-stu-id="f02f6-116">You can see which custom layouts are available for the report in the Report Layouts Part FactBox.</span></span> <span data-ttu-id="f02f6-117">Если отсутствуют пользовательские макеты для отчета, сначала необходимо создать их.</span><span class="sxs-lookup"><span data-stu-id="f02f6-117">If there are no custom layouts for the report, then you will have to create one first.</span></span> <span data-ttu-id="f02f6-118">Если выбрать этот вариант, перейдите к следующей процедуре, чтобы задать пользовательский макет, который требуется использовать.</span><span class="sxs-lookup"><span data-stu-id="f02f6-118">If you choose this option, go to the next procedure to specify the custom layout that you want to use.</span></span>

    > [!NOTE]  
    >   <span data-ttu-id="f02f6-119">Если выбрано значение **RDLC (встроенный)** или **Word (встроенный)** и пользователь получает сообщение об ошибке, что этот отчет не имеет макета заданного типа, необходимо выбрать другой макет или создать пользовательский макет отчета нужного типа.</span><span class="sxs-lookup"><span data-stu-id="f02f6-119">If you choose **RDLC (built-in)** or **Word (built-in)** and you get an error message that the report does not have a layout of the specified type, then you must choose another layout option or create a custom report layout of the type that you want to use.</span></span>

<span data-ttu-id="f02f6-120">Если выбран встроенный макет отчета RDLC или Word, никакие дальнейшие действия не требуются, а макет будет использоваться при следующем выполнении отчета.</span><span class="sxs-lookup"><span data-stu-id="f02f6-120">If you selected a built-in RDLC or Word report layout, then no further action is required and the layout will be used the next time the report is run.</span></span>

## <a name="to-specify-a-custom-layout-on-a-report"></a><span data-ttu-id="f02f6-121">Определение пользовательского макета отчета</span><span class="sxs-lookup"><span data-stu-id="f02f6-121">To specify a custom layout on a report</span></span>
1. <span data-ttu-id="f02f6-122">Вы указываете, какой пользовательский макет нужно использовать в отчете из окна **Пользовательские макеты отчетов**.</span><span class="sxs-lookup"><span data-stu-id="f02f6-122">You specify which custom layout to use on the report from the **Custom Report Layouts** window.</span></span> <span data-ttu-id="f02f6-123">Если окно **Пользовательские макеты отчетов** не открыто, нажмите кнопку выбора в поле **Описание макета отчета**.</span><span class="sxs-lookup"><span data-stu-id="f02f6-123">If the **Custom Report Layouts** window is not open, then in the **Report Layout Description** field, choose the lookup button.</span></span>
2. <span data-ttu-id="f02f6-124">В окне **Пользовательские макеты отчетов** выберите строку для пользовательского макета, который требуется использовать, затем закройте окно.</span><span class="sxs-lookup"><span data-stu-id="f02f6-124">In the **Custom Report Layouts** window, select the row for custom layout that you want to use, and then close the window.</span></span>

<span data-ttu-id="f02f6-125">Вы вернетесь в окно **Выбор макета отчета**.</span><span class="sxs-lookup"><span data-stu-id="f02f6-125">You return to the **Report Layout Selection** window.</span></span> <span data-ttu-id="f02f6-126">Имя выбранного пользовательского макета отображается в поле **Описание пользовательского макета**.</span><span class="sxs-lookup"><span data-stu-id="f02f6-126">The name of the selected custom layout displays in the **Custom Layout Description** field.</span></span> <span data-ttu-id="f02f6-127">Пользовательский макет будет использован при следующем выполнении отчета.</span><span class="sxs-lookup"><span data-stu-id="f02f6-127">The custom layout will be used the next time that you run the report.</span></span>

## <a name="see-also"></a><span data-ttu-id="f02f6-128">См. также</span><span class="sxs-lookup"><span data-stu-id="f02f6-128">See Also</span></span>
[<span data-ttu-id="f02f6-129">Управление макетами отчетов</span><span class="sxs-lookup"><span data-stu-id="f02f6-129">Managing Report Layouts</span></span>](ui-manage-report-layouts.md)  
<span data-ttu-id="f02f6-130">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f02f6-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

