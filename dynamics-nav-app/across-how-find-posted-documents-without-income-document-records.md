---
title: "Поиск учтенных документов без записей входящих документов"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: eca38d238361a9ac50aac117199fa97fbba4374f
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="82b07-102">Поиск учтенных документов без записей входящих документов</span><span class="sxs-lookup"><span data-stu-id="82b07-102">How to: Find Posted Documents without Incoming Document Records</span></span>
<span data-ttu-id="82b07-103">В окнах **План счетов** и **Операции главной книги** с помощью функции поиска можно найти операции главной книги для учтенных документов покупки и продажи, которые не имеют записей входящих документов, и затем централизованно связать их с существующими записями или создать новые записи с прикрепленными файлами документов.</span><span class="sxs-lookup"><span data-stu-id="82b07-103">From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.</span></span>

## <a name="to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="82b07-104">Поиск учтенных документов без записей входящих документов</span><span class="sxs-lookup"><span data-stu-id="82b07-104">To find posted documents without incoming document records</span></span>
1. <span data-ttu-id="82b07-105">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **План счетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="82b07-105">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="82b07-106">Выберите строку счета ГК для тех операций главной книги, для которых вы ходите увидеть учтенные документы покупки и продажи без записей входящих документов, а затем выберите действие **Учтенные документы без входящего документа**.</span><span class="sxs-lookup"><span data-stu-id="82b07-106">Select a line for a G/L account for whose general ledger entries you want to see posted purchase and sales documents without incoming document records, and then choose the **Posted Documents without Incoming Document** action.</span></span>
3. <span data-ttu-id="82b07-107">Альтернативный вариант — выберите действие **Книга операций**.</span><span class="sxs-lookup"><span data-stu-id="82b07-107">Alternatively, choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="82b07-108">В окне **Операции главной книги** выберите действие **Учтенные документы без входящих документов**.</span><span class="sxs-lookup"><span data-stu-id="82b07-108">In the **General Ledger Entries** window, choose the **Posted Documents without Incoming Documents** action.</span></span>

<span data-ttu-id="82b07-109">Откроется окно **Учтенные документы без входящего документа**, содержащее сведения об учтенных документах покупки и продажи без записей входящего документа, представленных записями ГК в счете ГК, для которого открыто это окно.</span><span class="sxs-lookup"><span data-stu-id="82b07-109">The **Posted Documents without Incoming Document** window opens showing posted purchase and sales documents without incoming document records represented by general ledger entries on the G/L account that you opened the window for.</span></span> <span data-ttu-id="82b07-110">Окно может содержать до 1000 строк.</span><span class="sxs-lookup"><span data-stu-id="82b07-110">The window can show a maximum of 1000 lines.</span></span> <span data-ttu-id="82b07-111">Таким образом, по умолчанию поле **Фильтр по дате** содержит фильтр, который ограничивает строки записями, имеющими дату учета с начала отчетного периода до рабочей даты.</span><span class="sxs-lookup"><span data-stu-id="82b07-111">By default, the **Date Filter** field therefore contains a filter that limits the lines to entries with posting dates from the beginning of the accounting period to the work date.</span></span>

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a><span data-ttu-id="82b07-112">Подключение найденных документов к существующим записям входящих документов</span><span class="sxs-lookup"><span data-stu-id="82b07-112">To connect found documents to existing incoming document records</span></span>
1. <span data-ttu-id="82b07-113">В окне **Учтенные документы без входящего документа** выберите строку для учтенного документа, который нужно связать с существующей записью входящего документа, и выберите действие **Выбрать входящий документ**.</span><span class="sxs-lookup"><span data-stu-id="82b07-113">In the **Posted Documents without Incoming Document** window, select the line for a posted document that you want to connect to an existing incoming document record, and then choose the **Select Incoming Document** action.</span></span>
2. <span data-ttu-id="82b07-114">В окне **Входящие документы** выберите запись входящего документа, которую требуется связать с найденным учтенным документом, а затем нажмите кнопку **OK**.</span><span class="sxs-lookup"><span data-stu-id="82b07-114">In the **Incoming Documents** window, select the incoming document record that you want to connect to posted document found, and then choose the **OK** button.</span></span>
3. <span data-ttu-id="82b07-115">В окне **Учтенные документы без входящего документа** выбранная запись входящего документа будет связана с учтенным документом, как показано на информационной панели **Файлы входящих документов** .</span><span class="sxs-lookup"><span data-stu-id="82b07-115">In the **Posted Documents without Incoming Document** window, the selected incoming document record is now connected to the posted document, as you can see in the **Incoming Document Files** FactBox.</span></span>

<span data-ttu-id="82b07-116">Если нужная запись входящего документа отсутствует в окне **Входящие документы**, ее можно создать.</span><span class="sxs-lookup"><span data-stu-id="82b07-116">If a relevant incoming document record does not exist in the **Incoming Documents** window, then you can create it.</span></span> <span data-ttu-id="82b07-117">Дополнительные сведения см. в разделе [Практическое руководство. Создание записей входящих документов](across-how-create-income-document-records.md).</span><span class="sxs-lookup"><span data-stu-id="82b07-117">For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="82b07-118">См. также</span><span class="sxs-lookup"><span data-stu-id="82b07-118">See Also</span></span>  
[<span data-ttu-id="82b07-119">Обработка входящих документов</span><span class="sxs-lookup"><span data-stu-id="82b07-119">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="82b07-120">Входящие документы</span><span class="sxs-lookup"><span data-stu-id="82b07-120">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="82b07-121">Управление закупками</span><span class="sxs-lookup"><span data-stu-id="82b07-121">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="82b07-122">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="82b07-122">Work With Dynamics NAV</span></span>](ui-work-product.md)

