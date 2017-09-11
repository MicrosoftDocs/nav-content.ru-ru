---
title: "Практическое руководство. Как создавать записи входящих документов"
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
ms.openlocfilehash: e91c4570ff60d991974ac6afd16ba3bc3e73e44f
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="how-to-create-incoming-document-records"></a><span data-ttu-id="5a1ce-102">Практическое руководство. Как создавать записи входящих документов</span><span class="sxs-lookup"><span data-stu-id="5a1ce-102">How to: Create Incoming Document Records</span></span>
<span data-ttu-id="5a1ce-103">В окне **Входящие документы** можно использовать различные функции для просмотра квитанций по расходам, управления задачами OCR, а также преобразования входящих файлов документов, вручную и автоматически, в соответствующие документы либо строки журналов.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-103">In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="5a1ce-104">Внешние файлы можно прикреплять на любом этапе обработки, в том числе к учтенным документам и к полученным записям поставщика, клиента и главной книги.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-104">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span>

<span data-ttu-id="5a1ce-105">Чтобы записать внешний документ в Dynamics NAV, сначала необходимо создать или завершить запись входящего документа.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-105">To record an external document in Dynamics NAV, you must first create or complete an incoming document record.</span></span> <span data-ttu-id="5a1ce-106">Это можно сделать вручную или можно сфотографировать внешний документ, а затем создать запись входящего документа с вложенным файлом изображения.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-106">You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.</span></span>

<span data-ttu-id="5a1ce-107">Перед использованием функции входящих документов необходимо выполнить обязательную настройку.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-107">Before you can use the Incoming Documents feature, you must perform the required setup.</span></span> <span data-ttu-id="5a1ce-108">Дополнительные сведения см. в разделе [Практическое руководство. Настройка входящих документов](across-how-setup-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="5a1ce-108">For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).</span></span>

## <a name="to-approve-or-reject-an-incoming-document"></a><span data-ttu-id="5a1ce-109">Утверждение или отклонение входящего документа</span><span class="sxs-lookup"><span data-stu-id="5a1ce-109">To approve or reject an incoming document</span></span>
<span data-ttu-id="5a1ce-110">Если необходимо разрешить пользователям создавать счета или строки общего журнала на основе записей входящего документа до их утверждения, можно настроить утверждающих, которые будут утверждать записи перед их обработкой.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-110">If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.</span></span>

1. <span data-ttu-id="5a1ce-111">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Входящие документы**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-111">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="5a1ce-112">Выберите строку с документом, который необходимо утвердить или отклонить, а затем выберите действие **Утвердить** или **Отклонить**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-112">Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.</span></span>

<span data-ttu-id="5a1ce-113">При утверждении записи входящего документа в строке этого документа устанавливается флажок **Выпущено**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-113">If you approve the incoming document record, the **Released** check box on the incoming document line is selected.</span></span> <span data-ttu-id="5a1ce-114">Например, пользователь, который отвечает за создание счетов на покупку, может перейти к обработке записи.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-114">The user in charge of creating, for example, purchase invoices can proceed to process the record.</span></span>

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="5a1ce-115">Создание записи входящего документа по фотографии</span><span class="sxs-lookup"><span data-stu-id="5a1ce-115">To create an incoming document record by taking a photo</span></span>
<span data-ttu-id="5a1ce-116">**Примечание**. Следующая процедура применяется только к клиентам Dynamics NAV для планшетов и телефонов.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-116">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="5a1ce-117">В строке приложения выберите плитку **Создать входящий документ по данным камеры**, а затем перейдите к шагу 4.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-117">On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.</span></span>
2. <span data-ttu-id="5a1ce-118">Или же в строке приложения нажмите кнопку приложения, выберите **Входящие документы**, а затем выберите **Все**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-118">Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
3. <span data-ttu-id="5a1ce-119">В окне **Входящие документы** нажмите кнопку с многоточием, а затем выберите **Создать из камеры**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-119">In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**.</span></span> <span data-ttu-id="5a1ce-120">Камера планшета или телефона включится.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-120">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="5a1ce-121">Сделайте фотографию документа, например приходной накладной, которую требуется обработать как входящий документ, а затем нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-121">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="5a1ce-122">Создается новая запись входящего документа с прикрепленным изображением.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-122">A new incoming document record is created, with the image attached.</span></span>

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="5a1ce-123">Прикрепление изображения к записи входящего документа по фотографии</span><span class="sxs-lookup"><span data-stu-id="5a1ce-123">To attach an image to an incoming document record by taking a photo</span></span>
<span data-ttu-id="5a1ce-124">**Примечание**. Следующая процедура применяется только к клиентам Dynamics NAV для планшетов и телефонов.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-124">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="5a1ce-125">В строке приложения нажмите кнопку приложения, выберите **Входящие документы**, а затем выберите **Все**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-125">On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
2. <span data-ttu-id="5a1ce-126">Откройте карточку для существующей записи входящего документа.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-126">Open the card for an existing incoming document record.</span></span>
3. <span data-ttu-id="5a1ce-127">В окне **Входящий документ** нажмите кнопку с многоточием, а затем выберите **Прикрепить изображение с камеры**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-127">In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**.</span></span> <span data-ttu-id="5a1ce-128">Камера планшета или телефона включится.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-128">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="5a1ce-129">Сделайте фотографию документа, например приходной накладной, которую требуется обработать как входящий документ, а затем нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-129">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="5a1ce-130">Изображение прикрепляется к записи входящего документа.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-130">The image is attached to the incoming document record.</span></span>

## <a name="to-create-an-incoming-document-record-manually"></a><span data-ttu-id="5a1ce-131">Создание записи входящего документа вручную</span><span class="sxs-lookup"><span data-stu-id="5a1ce-131">To create an incoming document record manually</span></span>
1. <span data-ttu-id="5a1ce-132">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Входящие документы**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-132">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="5a1ce-133">Выберите действие **Создать из файла**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-133">Choose the **Create from File** action.</span></span>  
3. <span data-ttu-id="5a1ce-134">В окне **Вставка файла** выделите файл, а затем выберите **Открыть**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-134">In the **Insert File** window, select a file, and then choose **Open**.</span></span>

    <span data-ttu-id="5a1ce-135">Файл будет прикреплен автоматически.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-135">The file is automatically attached.</span></span>
4. <span data-ttu-id="5a1ce-136">Кроме того, выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-136">Alternatively, choose the **New** action.</span></span>
5. <span data-ttu-id="5a1ce-137">Чтобы вложить файл, выберите действие **Прикрепить файл**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-137">To attach a file, choose the **Attach File** action.</span></span>
6. <span data-ttu-id="5a1ce-138">В окне **Вставка файла** выберите файл, представляющий соответствующий входящий документ, а затем нажмите кнопку **Открыть**.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-138">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>
7. <span data-ttu-id="5a1ce-139">В окне **Входящий документ** заполните поля по мере необходимости.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-139">In the **Incoming Document** window, fill in the fields as necessary.</span></span> <span data-ttu-id="5a1ce-140">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="5a1ce-140">Choose a field to read a short description of the field or link to more information.</span></span>

##<a name="see-also"></a><span data-ttu-id="5a1ce-141">См. также</span><span class="sxs-lookup"><span data-stu-id="5a1ce-141">See Also</span></span>  
[<span data-ttu-id="5a1ce-142">Обработка входящих документов</span><span class="sxs-lookup"><span data-stu-id="5a1ce-142">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="5a1ce-143">Входящие документы</span><span class="sxs-lookup"><span data-stu-id="5a1ce-143">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="5a1ce-144">Управление закупками</span><span class="sxs-lookup"><span data-stu-id="5a1ce-144">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="5a1ce-145">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5a1ce-145">Work With Dynamics NAV</span></span>](ui-work-product.md)

