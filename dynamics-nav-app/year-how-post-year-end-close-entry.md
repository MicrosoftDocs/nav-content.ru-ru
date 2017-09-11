---
title: "Практическое руководство. Учет операции закрытия года"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: fe32ee973c90ba857852ae092acf03db09e648ee
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---
# <a name="how-to-post-year-end-closing-entry"></a><span data-ttu-id="20d96-102">Практическое руководство. Учет операции закрытия года</span><span class="sxs-lookup"><span data-stu-id="20d96-102">How to: Post Year-End Closing Entry</span></span>
<span data-ttu-id="20d96-103">В составе процесса закрытия книг для финансового года выполняется пакетное задание «Закрытие отчета о прибылях и убытках» для перемещения результатов года на счет в балансовом отчете и закрытия отчета по прибылях и убытках.</span><span class="sxs-lookup"><span data-stu-id="20d96-103">As part of closing the books for a fiscal year, you will run the Close Income Statement batch job to transfer the year's result to an account in the balance sheet and close the income statement accounts.</span></span> <span data-ttu-id="20d96-104">После запуска пакетного задания "Закрытие отчета о прибылях и убытках" необходимо открыть журнал, указанный для пакетного задания, и затем просмотреть и учесть записи.</span><span class="sxs-lookup"><span data-stu-id="20d96-104">After you run the Close Income Statement batch job, you must open the journal you specified in the batch job, and then review and post the entries.</span></span>

## <a name="to-post-the-year-end-closing-entry"></a><span data-ttu-id="20d96-105">Учет операции закрытия года</span><span class="sxs-lookup"><span data-stu-id="20d96-105">To post the year end closing entry</span></span>
1. <span data-ttu-id="20d96-106">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="20d96-106">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="20d96-107">В окне **Финансовый журнал** в поле **Код раздела** выберите раздел, который содержит закрывающие операции.</span><span class="sxs-lookup"><span data-stu-id="20d96-107">In the **General Journal** window, in the **Batch Name** field, select the batch that contains the closing entries.</span></span>
3. <span data-ttu-id="20d96-108">Проверьте записи.</span><span class="sxs-lookup"><span data-stu-id="20d96-108">Review the entries.</span></span>
4. <span data-ttu-id="20d96-109">Чтобы учесть журнал, выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="20d96-109">To post the journal, choose the **Post** action.</span></span>

<span data-ttu-id="20d96-110">**Примечание**. При обнаружении ошибки отображается сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="20d96-110">**Note**: If an error is detected, an error message is displayed.</span></span> <span data-ttu-id="20d96-111">Если учет выполнен успешно, система удалит учтенные записи из журнала.</span><span class="sxs-lookup"><span data-stu-id="20d96-111">If the posting is successful, the posted entries are removed from the journal.</span></span> <span data-ttu-id="20d96-112">После завершения учета запись учитывается во всех счетах прибылей и убытков, при этом ее сальдо становится нулевым, и результат года переносится в балансовый отчет.</span><span class="sxs-lookup"><span data-stu-id="20d96-112">After posting is complete, an entry is posted to each income statement account so that its balance becomes zero and the year's result is transferred to the balance sheet.</span></span>

## <a name="see-also"></a><span data-ttu-id="20d96-113">См. также</span><span class="sxs-lookup"><span data-stu-id="20d96-113">See Also</span></span>
[<span data-ttu-id="20d96-114">Закрыть книги</span><span class="sxs-lookup"><span data-stu-id="20d96-114">Close Books</span></span>](year-close-books.md)  
[<span data-ttu-id="20d96-115">Закрытие отчета о прибылях и убытках</span><span class="sxs-lookup"><span data-stu-id="20d96-115">Close Income Statement</span></span>](year-close-income-statement.md)  
[<span data-ttu-id="20d96-116">Как завершать учетные периоды</span><span class="sxs-lookup"><span data-stu-id="20d96-116">How to: Close Accounting Periods</span></span>](year-close-account-periods.md)  
