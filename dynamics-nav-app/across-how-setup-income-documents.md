---
title: "Практическое руководство. Настройка входящих документов"
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
ms.openlocfilehash: d55329b571e4c59d4821a86a39362ea58480b86a
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---

# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="cbd6d-102">Практическое руководство. Настройка входящих документов</span><span class="sxs-lookup"><span data-stu-id="cbd6d-102">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="cbd6d-103">При создании строк финансового журнала на основании записей входящих документов необходимо выбрать в окне **Настройка входящих документов** шаблон и раздел журнала.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="cbd6d-104">Если пользователи не должны создавать счета или строки финансового журнала на основании записей входящих документов до утверждения документов, необходимо настроить утверждающих в окне **Утверждающие для входящего документа**.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="cbd6d-105">Чтобы преобразовать файлы PDF и изображений в электронные документы, которые можно будет преобразовывать, например, счета покупки в Dynamics NAV, следует сначала настроить функцию OCR и включить эту службу.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="cbd6d-106">Если функция входящих документов настроена, можно использовать различные функции для просмотра квитанций по расходам, управления задачами OCR, а также преобразования входящих файлов документов, вручную и автоматически, в соответствующие документы либо строки журналов.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="cbd6d-107">Внешние файлы можно прикреплять на любом этапе обработки, в том числе к учтенным документам и к полученным записям поставщика, клиента и главной книги.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="cbd6d-108">Дополнительные сведения см. в разделе [Практическое руководство. Обработка входящих документов](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="cbd6d-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="cbd6d-109">Настройка возможности входящих документов</span><span class="sxs-lookup"><span data-stu-id="cbd6d-109">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="cbd6d-110">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка входящих документов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="cbd6d-111">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="cbd6d-112">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-112">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="cbd6d-113">Настройка утверждающих для записей входящих документов</span><span class="sxs-lookup"><span data-stu-id="cbd6d-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="cbd6d-114">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка входящих документов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="cbd6d-115">В окне **Настройка входящих документов** выберите действие **Утверждающие**.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="cbd6d-116">В окне **Утверждающие для входящего документа** будут показаны все пользователи, настроенные в Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span></span>  
3. <span data-ttu-id="cbd6d-117">Выберите одного или нескольких пользователей, которые могут утвердить входящий документ до создания соответствующей строки в документе или журнале.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="cbd6d-118">После настройки утверждающих в окне **Утверждание для входящего документа** только такие пользователи смогут утверждать входящий документ, если установлен флажок **Требовать утверждение для создания** в окне **Настройка входящих документов**.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

<span data-ttu-id="cbd6d-119">**Примечание**. Эта настройка утверждения не связана с рабочими процессами утверждения.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-119">**Note**: This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="cbd6d-120">Дополнительные сведения см. в разделе [Практическое руководство. Использование рабочих процессов утверждения](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="cbd6d-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="cbd6d-121">Настройка службы распознавания</span><span class="sxs-lookup"><span data-stu-id="cbd6d-121">To set up an OCR service</span></span>
1. <span data-ttu-id="cbd6d-122">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка OCR**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="cbd6d-123">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-123">Fill in the fields as necessary.</span></span> <span data-ttu-id="cbd6d-124">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-124">Choose a field to read a short description of the field or link to more information.</span></span>


## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="cbd6d-125">Шифрование реквизитов доступа</span><span class="sxs-lookup"><span data-stu-id="cbd6d-125">To encrypt your login information</span></span>
<span data-ttu-id="cbd6d-126">Рекомендуется защищать данные для входа, введенные в окне **Настройка OCR**.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="cbd6d-127">Можно зашифровать данные на сервере, создав новые или импортировав существующие ключи шифрования, включаемые на экземпляре сервера, подключенном к базе данных.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="cbd6d-128">В окне **Настройка OCR** выберите действие **Управление шифрованием**.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="cbd6d-129">В окне **Управление шифрованием данных** включите шифрование данных.</span><span class="sxs-lookup"><span data-stu-id="cbd6d-129">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="cbd6d-130">См. также</span><span class="sxs-lookup"><span data-stu-id="cbd6d-130">See Also</span></span>  
[<span data-ttu-id="cbd6d-131">Обработка входящих документов</span><span class="sxs-lookup"><span data-stu-id="cbd6d-131">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="cbd6d-132">Входящие документы</span><span class="sxs-lookup"><span data-stu-id="cbd6d-132">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="cbd6d-133">Управление закупками</span><span class="sxs-lookup"><span data-stu-id="cbd6d-133">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="cbd6d-134">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="cbd6d-134">Work With Dynamics NAV</span></span>](ui-work-product.md)

