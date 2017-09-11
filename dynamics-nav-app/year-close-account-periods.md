---
title: "Как завершать учетные периоды"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 929e8f1e391e868122077ad1baa72b7b170aa4d4
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---
# <a name="how-to-close-accounting-periods"></a><span data-ttu-id="ae46a-102">Как завершать учетные периоды</span><span class="sxs-lookup"><span data-stu-id="ae46a-102">How to: Close Accounting Periods</span></span>
<span data-ttu-id="ae46a-103">При завершении финансового года следует завершить периоды, которые его образуют.</span><span class="sxs-lookup"><span data-stu-id="ae46a-103">When a fiscal year is over, you must close the periods that comprise it.</span></span>

## <a name="to-close-accounting-periods"></a><span data-ttu-id="ae46a-104">Практическое руководство. Закрытие учетных периодов</span><span class="sxs-lookup"><span data-stu-id="ae46a-104">To close accounting periods</span></span>
1. <span data-ttu-id="ae46a-105">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Учетные периоды**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="ae46a-105">In the top right corner, choose the **Search for Page or Report** icon, enter **Accounting Periods**, and then choose the related link.</span></span>
2. <span data-ttu-id="ae46a-106">В окне **Учетные периоды** выберите действие **Закрыть год**.</span><span class="sxs-lookup"><span data-stu-id="ae46a-106">In the **Accounting Periods** window, choose the **Close Year** action.</span></span>

    <span data-ttu-id="ae46a-107">Если открыто несколько финансовых лет, автоматически считается, что должен быть закрыт более ранний год.</span><span class="sxs-lookup"><span data-stu-id="ae46a-107">If more than one fiscal year is open, the earliest one is automatically selected to be closed.</span></span> <span data-ttu-id="ae46a-108">Отображается сообщение, указывающее подлежащий закрытию год и сообщающее о последствиях закрытия года.</span><span class="sxs-lookup"><span data-stu-id="ae46a-108">A message displays identifying the year that will close and the consequences of closing the year.</span></span>
3. <span data-ttu-id="ae46a-109">Для закрытия года нажмите кнопку **Да**.</span><span class="sxs-lookup"><span data-stu-id="ae46a-109">To close the year, choose the **Yes** button.</span></span>

<span data-ttu-id="ae46a-110">Финансовый год закрыт, и выбираются поля **Закрыто** и **Дата закрыта** для всех периодов в таком году.</span><span class="sxs-lookup"><span data-stu-id="ae46a-110">The fiscal year is closed, and the **Closed** and **Date Locked** fields for all the periods in the year are selected.</span></span> <span data-ttu-id="ae46a-111">Финансовый год не может быть открыт снова, и флажок из полей **Закрыто** или **Дата закрыта** удалить нельзя.</span><span class="sxs-lookup"><span data-stu-id="ae46a-111">The fiscal year cannot be opened again and you cannot remove the check mark from the **Closed** or **Date Locked** fields.</span></span>

<span data-ttu-id="ae46a-112">**Примечание**. Нельзя закрыть финансовый год, если прежде не будет открыт новый финансовый год.</span><span class="sxs-lookup"><span data-stu-id="ae46a-112">**Note:** You cannot close a fiscal year before you create a new one.</span></span> <span data-ttu-id="ae46a-113">Следует отметить, что после закрытия финансового года уже невозможно изменить дату начала следующего финансового года.</span><span class="sxs-lookup"><span data-stu-id="ae46a-113">Notice that when a fiscal year has been closed, you cannot change the starting date of the following fiscal year.</span></span>

<span data-ttu-id="ae46a-114">Несмотря на то, что финансовый год закрыт, можно по-прежнему производить учет ГК операций по нему.</span><span class="sxs-lookup"><span data-stu-id="ae46a-114">Even though a fiscal year has been closed, you can still post general ledger entries to it.</span></span> <span data-ttu-id="ae46a-115">При этом операции будут помечаться как учтенные по закрытому финансовому году, и будет выбрано поле **Операция прошлого года**.</span><span class="sxs-lookup"><span data-stu-id="ae46a-115">When you do this, the entries will be marked as posted to a closed fiscal year and the **Prior-Year Entry** field will be selected.</span></span>

<span data-ttu-id="ae46a-116">После закрытия финансового года счета прибылей и убытков следует закрыть, а результаты года должны быть перемещены на счет в балансовом отчете.</span><span class="sxs-lookup"><span data-stu-id="ae46a-116">After a fiscal year is closed, you must close the income statement accounts and transfer the year's results to an account in the balance sheet.</span></span> <span data-ttu-id="ae46a-117">Эти действия можно повторять при каждом учете закрытого финансового года.</span><span class="sxs-lookup"><span data-stu-id="ae46a-117">You can repeat this every time that you post to the closed fiscal year.</span></span>

## <a name="see-also"></a><span data-ttu-id="ae46a-118">См. также</span><span class="sxs-lookup"><span data-stu-id="ae46a-118">See Also</span></span>
[<span data-ttu-id="ae46a-119">Закрыть книги</span><span class="sxs-lookup"><span data-stu-id="ae46a-119">Close Books</span></span>](year-close-books.md)  
[<span data-ttu-id="ae46a-120">Практическое руководство: учет операции закрытия года</span><span class="sxs-lookup"><span data-stu-id="ae46a-120">How to: Post the Year-End Closing Entry</span></span>](year-how-post-year-end-close-entry.md)  
[<span data-ttu-id="ae46a-121">Как открыть новый финансовый года</span><span class="sxs-lookup"><span data-stu-id="ae46a-121">How to: Open a New Fiscal Year</span></span>](finance-setup-how-open-new-fiscal-year.md)

