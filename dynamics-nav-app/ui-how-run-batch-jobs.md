---
title: "Создание и выполнение пакетных заданий"
description: "Пакетные задания запускаются для обработки данных и обновления информации, например для выполнения периодических действий и других расчетов."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: task, process
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 3cdc028e41c42a0dfa9ee5a6495f87a6d96545b9
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-run-batch-jobs"></a><span data-ttu-id="62e74-103">Практическое руководство: запуск пакетных заданий</span><span class="sxs-lookup"><span data-stu-id="62e74-103">How to: Run Batch Jobs</span></span>
<span data-ttu-id="62e74-104">Пакетное задание — это процедура обработки данных в пакетах, например пакетное задание **Коррекция валютных курсов**.</span><span class="sxs-lookup"><span data-stu-id="62e74-104">A batch job is a routine that processes data in batches, for example the **Adjust Exchange Rates** batch job.</span></span> <span data-ttu-id="62e74-105">В некоторых пакетных заданиях выполняются периодические действия, связанные с учетом, например закрытие отчета о прибыли и убытках в конце финансового года.</span><span class="sxs-lookup"><span data-stu-id="62e74-105">There are batch jobs that perform periodic accounting activities, such as closing the income statement at the end of a fiscal year.</span></span> <span data-ttu-id="62e74-106">Во многих пакетных заданиях выполняются вычисления, например вычисление финансовых выплат, коррекция валютного курса и вычисление цены единицы.</span><span class="sxs-lookup"><span data-stu-id="62e74-106">Many batch jobs do calculation work, such as calculation of finance charges, exchange rate adjustment, and calculation of unit prices.</span></span>

<span data-ttu-id="62e74-107">Пакетное задание подобно отчету, за исключением того, что в пакетном задании результаты обработки используются не для печати, а для непосредственного обновления информации.</span><span class="sxs-lookup"><span data-stu-id="62e74-107">A batch job is like a report, except the batch job uses the result of its work to update information directly, instead of printing the results.</span></span>

## <a name="to-run-a-batch-job"></a><span data-ttu-id="62e74-108">Выполнение пакетного задания</span><span class="sxs-lookup"><span data-stu-id="62e74-108">To run a batch job</span></span>
1. <span data-ttu-id="62e74-109">Чтобы открыть окно запроса для соответствующего пакетного задания, в правом верхнем углу выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите имя пакетного задания, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="62e74-109">To open the request window for the relevant batch job, choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter the name of the batch job, and then choose the related link.</span></span>
2. <span data-ttu-id="62e74-110">Если для этого пакетного задания доступна экспресс-вкладка **Параметры**, заполните поля, определив действия, которые должны в нем выполняться.</span><span class="sxs-lookup"><span data-stu-id="62e74-110">If there is an **Options** FastTab for the batch job, fill in the fields to determine what the batch job will do.</span></span>
3. <span data-ttu-id="62e74-111">В окне запроса может быть одна или несколько экспресс-вкладок с фильтрами, которые можно использовать для ограничения количества данных, которые будут обрабатываться при выполнении пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="62e74-111">The window may contain one or more FastTab with filters, which you can use to limit the data included in the batch job.</span></span> <span data-ttu-id="62e74-112">Можно задать критерии в предлагаемых фильтрах или добавить дополнительные фильтры.</span><span class="sxs-lookup"><span data-stu-id="62e74-112">You can enter criteria in the suggested filters or add more filters.</span></span>
4. <span data-ttu-id="62e74-113">Нажмите кнопку **ОК** для запуска пакетного задания.</span><span class="sxs-lookup"><span data-stu-id="62e74-113">Choose the **OK** button to start the batch job.</span></span>

## <a name="see-also"></a><span data-ttu-id="62e74-114">См. также</span><span class="sxs-lookup"><span data-stu-id="62e74-114">See Also</span></span>
[<span data-ttu-id="62e74-115">Ввод критериев в фильтрах</span><span class="sxs-lookup"><span data-stu-id="62e74-115">Entering Criteria in Filters</span></span>](ui-enter-criteria-filters.md)  
<span data-ttu-id="62e74-116">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="62e74-116">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

