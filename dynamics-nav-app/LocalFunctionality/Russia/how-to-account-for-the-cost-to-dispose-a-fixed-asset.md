---
title: "Практическое руководство. Учет себестоимости реализации основного средства"
description: "Функция обслуживания при реализации позволяет отчитываться за сумму, потраченную на реализацию основного средства (ОС), как за расходы. Можно учесть операции, которые относятся к затратам на реализацию основного средства, так чтобы эти операции были отражены в формах актов списания ОС."
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
ms.openlocfilehash: 5321e18db0fb1ea196bec95863ae4a8b5fe97bde
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-account-for-the-cost--to-dispose-a-fixed-asset"></a><span data-ttu-id="8d52c-104">Практическое руководство. Учет себестоимости реализации основного средства</span><span class="sxs-lookup"><span data-stu-id="8d52c-104">How to: Account for the Cost  to Dispose a Fixed Asset</span></span>
<span data-ttu-id="8d52c-105">Функция обслуживания при реализации позволяет отчитываться за сумму, потраченную на реализацию основного средства (ОС), как за расходы.</span><span class="sxs-lookup"><span data-stu-id="8d52c-105">The maintenance on disposal feature enables you to account for the amount spent to dispose a fixed asset (FA) as an expense.</span></span> <span data-ttu-id="8d52c-106">Можно учесть операции, которые относятся к затратам на реализацию основного средства, так чтобы эти операции были отражены в формах актов списания ОС.</span><span class="sxs-lookup"><span data-stu-id="8d52c-106">You can post operations related to spending for the disposal of a fixed asset so that they will be reflected in the FA Write-Off Act forms.</span></span>  
  
 <span data-ttu-id="8d52c-107">Расходы на реализацию основного средства можно учесть из финансовых журналов, журналов ОС и документов покупки.</span><span class="sxs-lookup"><span data-stu-id="8d52c-107">The expenses of a fixed asset disposal can be posted from general ledger journals, fixed asset journals, and purchase documents.</span></span> <span data-ttu-id="8d52c-108">Ниже показано, как учесть расходы на реализацию основного средства с помощью финансового журнала основных средств.</span><span class="sxs-lookup"><span data-stu-id="8d52c-108">The following procedure shows how to post the expenses for a fixed asset disposal by using the Fixed Asset General Ledger Journal.</span></span>  
  
 <span data-ttu-id="8d52c-109">Расходы на реализацию основного средства можно распечатать в отчете по акту списания ОС-4 и в отчете по кату списания ОС-4a.</span><span class="sxs-lookup"><span data-stu-id="8d52c-109">The expenses on a fixed asset disposal can be printed in the FA Write-off Act FA-4 report and the FA Writeoff Act FA-4a report.</span></span>  
  
### <a name="to-set-up-a-maintenance-code"></a><span data-ttu-id="8d52c-110">Настройки кодов обслуживания</span><span class="sxs-lookup"><span data-stu-id="8d52c-110">To set up a maintenance code</span></span>  
  
1.  <span data-ttu-id="8d52c-111">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка ОС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="8d52c-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Setup**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="8d52c-112">В окне **Настройка модуля ОС** на экспресс-вкладке **Общее** введите код обслуживания в поле **Код обслуживания при реализации**.</span><span class="sxs-lookup"><span data-stu-id="8d52c-112">In the **Fixed Asset Setup** window, on the **General** FastTab, enter a maintenance code in the **On Disposal Maintenance Code** field.</span></span>  
  
3.  <span data-ttu-id="8d52c-113">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="8d52c-113">Choose the **OK** button.</span></span>  
  
### <a name="to-post-expenses-on-a-fixed-asset-disposal"></a><span data-ttu-id="8d52c-114">Учет расходов на реализацию основного средства</span><span class="sxs-lookup"><span data-stu-id="8d52c-114">To post expenses on a fixed asset disposal</span></span>  
  
1.  <span data-ttu-id="8d52c-115">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы ГК ОС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="8d52c-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="8d52c-116">Заполните поля в окне **Журнал ГК основных средств**, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="8d52c-116">In the **Fixed Asset G/L Journal** window, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="8d52c-117">Поле</span><span class="sxs-lookup"><span data-stu-id="8d52c-117">Field</span></span>|<span data-ttu-id="8d52c-118">Описанием</span><span class="sxs-lookup"><span data-stu-id="8d52c-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="8d52c-119">**Тип счета**</span><span class="sxs-lookup"><span data-stu-id="8d52c-119">**Account Type**</span></span>|<span data-ttu-id="8d52c-120">Выберите **Основное средство** в качестве типа счета.</span><span class="sxs-lookup"><span data-stu-id="8d52c-120">Select **Fixed Asset** as the account type.</span></span>|  
    |<span data-ttu-id="8d52c-121">**Номер счета**</span><span class="sxs-lookup"><span data-stu-id="8d52c-121">**Account No.**</span></span>|<span data-ttu-id="8d52c-122">Определяет номер основного средства, реализация которого потребовал расходов.</span><span class="sxs-lookup"><span data-stu-id="8d52c-122">Specifies the number of the fixed asset for disposal for which the expenses are made.</span></span>|  
    |<span data-ttu-id="8d52c-123">**Тип учета ОС**</span><span class="sxs-lookup"><span data-stu-id="8d52c-123">**FA Posting Type**</span></span>|<span data-ttu-id="8d52c-124">Выберите **Обслуживание** в качестве типа учета основного средства.</span><span class="sxs-lookup"><span data-stu-id="8d52c-124">Select **Maintenance** as the fixed asset posting type.</span></span>|  
    |<span data-ttu-id="8d52c-125">**Код обслуживания**</span><span class="sxs-lookup"><span data-stu-id="8d52c-125">**Maintenance Code**</span></span>|<span data-ttu-id="8d52c-126">Определяет код обслуживания, введенный в поле **Код обслуживания при реализации** в окне **Настройка модуля ОС**.</span><span class="sxs-lookup"><span data-stu-id="8d52c-126">Specifies the maintenance code that is entered in the **On Disposal Maintenance Code** field of the **Fixed Asset Setup** window.</span></span>|  
  
3.  <span data-ttu-id="8d52c-127">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="8d52c-127">Choose the **OK** button.</span></span>  
  
### <a name="to-print-a-report-with-expenses-on-a-fixed-asset-disposal"></a><span data-ttu-id="8d52c-128">Печать отчета с расходами на реализацию основного средства</span><span class="sxs-lookup"><span data-stu-id="8d52c-128">To print a report with expenses on a fixed asset disposal</span></span>  
  
1.  <span data-ttu-id="8d52c-129">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Акт списания ОС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="8d52c-129">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Writeoff Act**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="8d52c-130">В окне **Акт списания ОС** введите расходы, учтенные для данного основного средства.</span><span class="sxs-lookup"><span data-stu-id="8d52c-130">In the **FA Writeoff Act** window, enter the expenses that are posted for the fixed asset.</span></span>  
  
3.  <span data-ttu-id="8d52c-131">Нажмите кнопку **Печать**, чтобы распечатать отчет, или кнопку **Просмотр**, чтобы отобразить его на экране.</span><span class="sxs-lookup"><span data-stu-id="8d52c-131">Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.</span></span> <span data-ttu-id="8d52c-132">Нажмите кнопку **Отмена** для сохранения информации без печати отчета.</span><span class="sxs-lookup"><span data-stu-id="8d52c-132">Choose the **Cancel** button to save the information without printing the report.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="8d52c-133">Если расходы на демонтаж основного средства производятся авансом, они будут показаны на второй странице отчета.</span><span class="sxs-lookup"><span data-stu-id="8d52c-133">If the expenses on the disposal of the fixed asset are made in advance, they are displayed on the second page of the report.</span></span>  
  
     <span data-ttu-id="8d52c-134">После того как отчет о списании основного средства учтен, он становится учтенным отчетом о списании основного средства.</span><span class="sxs-lookup"><span data-stu-id="8d52c-134">After the fixed asset write-off report is posted, it becomes the posted fixed asset write-off report.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="8d52c-135">См. также</span><span class="sxs-lookup"><span data-stu-id="8d52c-135">See Also</span></span>  
 <span data-ttu-id="8d52c-136">Настройка модуля ОС</span><span class="sxs-lookup"><span data-stu-id="8d52c-136">Fixed Asset Setup</span></span>   
 <span data-ttu-id="8d52c-137">[Настройка учета основных средств](fixed-assets-accounting-setup.md) </span><span class="sxs-lookup"><span data-stu-id="8d52c-137">[Fixed Assets Accounting Setup](fixed-assets-accounting-setup.md) </span></span>  
 <span data-ttu-id="8d52c-138">Карточка ОС</span><span class="sxs-lookup"><span data-stu-id="8d52c-138">Fixed Asset Card</span></span>