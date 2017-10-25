---
title: "Проверка и учет операции закрытия года"
description: "Описывается порядок открытия журнала, указанного в пакетном задании \"Закрытие отчета о прибылях и убытках\", и проверки и учета операции закрытия года."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, bank account detailed trial balance
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: eeffd585b18c2b839db7be3f89d19497080b10ef
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-the-year-end-closing-entry"></a><span data-ttu-id="31942-103">Практическое руководство: учет операции закрытия года</span><span class="sxs-lookup"><span data-stu-id="31942-103">How to: Post the Year-End Closing Entry</span></span>
<span data-ttu-id="31942-104">После использования пакетного задания **Закрытие отчета о прибылях и убытках** для создания закрывающей операции (операций) на конец года необходимо открыть журнал, указанный для пакетного задания, и затем просмотреть и учесть записи.</span><span class="sxs-lookup"><span data-stu-id="31942-104">After you use the **Close Income Statement** batch job to generate the year-end closing entry or entries, you must open the journal you specified in the batch job, and then review and post the entries.</span></span>

## <a name="to-post-the-year-end-closing-entry"></a><span data-ttu-id="31942-105">Учет операции закрытия года</span><span class="sxs-lookup"><span data-stu-id="31942-105">To post the year end closing entry</span></span>
1. <span data-ttu-id="31942-106">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="31942-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="31942-107">В окне **Финансовый журнал** в поле **Код раздела** выберите раздел, который содержит закрывающие операции.</span><span class="sxs-lookup"><span data-stu-id="31942-107">In the **General Journal** window, in the **Batch Name** field, select the batch that contains the closing entries.</span></span>
3. <span data-ttu-id="31942-108">Проверьте записи.</span><span class="sxs-lookup"><span data-stu-id="31942-108">Review the entries.</span></span>
4. <span data-ttu-id="31942-109">Чтобы учесть журнал, выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="31942-109">To post the journal, choose the **Post** action.</span></span>

> [!NOTE]  
>   <span data-ttu-id="31942-110">При обнаружении ошибки отображается сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="31942-110">If an error is detected, an error message is displayed.</span></span> <span data-ttu-id="31942-111">Если учет выполнен успешно, система удалит учтенные записи из журнала.</span><span class="sxs-lookup"><span data-stu-id="31942-111">If the posting is successful, the posted entries are removed from the journal.</span></span> <span data-ttu-id="31942-112">После завершения учета запись учитывается во всех счетах прибылей и убытков, при этом ее сальдо становится нулевым, и результат года переносится в балансовый отчет.</span><span class="sxs-lookup"><span data-stu-id="31942-112">After posting is complete, an entry is posted to each income statement account so that its balance becomes zero and the year's result is transferred to the balance sheet.</span></span>

## <a name="see-also"></a><span data-ttu-id="31942-113">См. также</span><span class="sxs-lookup"><span data-stu-id="31942-113">See Also</span></span>
[<span data-ttu-id="31942-114">Практическое руководство. Закрытие учетных периодов</span><span class="sxs-lookup"><span data-stu-id="31942-114">How to: Close Accounting Periods</span></span>](year-close-account-periods.md)  
[<span data-ttu-id="31942-115">Закрытие книг</span><span class="sxs-lookup"><span data-stu-id="31942-115">Closing Books</span></span>](year-close-books.md)  
[<span data-ttu-id="31942-116">Закрытие отчета о прибылях и убытках</span><span class="sxs-lookup"><span data-stu-id="31942-116">Close Income Statement</span></span>](year-close-income-statement.md)  
<span data-ttu-id="31942-117">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="31942-117">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

