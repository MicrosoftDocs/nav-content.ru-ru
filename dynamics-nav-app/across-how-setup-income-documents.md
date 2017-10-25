---
title: "Настройка входящих документов"
description: "Используйте функцию входящих документов для создания документов, управления задачами OCR, импорта счетов преобразования файлов изображений."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 80c57f6a332ace58941929811e3f3a9b1f156028
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="f0845-103">Практическое руководство. Настройка входящих документов</span><span class="sxs-lookup"><span data-stu-id="f0845-103">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="f0845-104">При создании строк финансового журнала на основании записей входящих документов необходимо выбрать в окне **Настройка входящих документов** шаблон и раздел журнала.</span><span class="sxs-lookup"><span data-stu-id="f0845-104">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="f0845-105">Если пользователи не должны создавать счета или строки финансового журнала на основании записей входящих документов до утверждения документов, необходимо настроить утверждающих в окне **Утверждающие для входящего документа**.</span><span class="sxs-lookup"><span data-stu-id="f0845-105">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="f0845-106">Чтобы преобразовать PDF-файлы и файлы изображений в электронные документы, которые можно будет преобразовывать, например, счета покупки в [!INCLUDE[d365fin](includes/d365fin_md.md)], следует сначала настроить функцию OCR и включить этот сервис.</span><span class="sxs-lookup"><span data-stu-id="f0845-106">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside [!INCLUDE[d365fin](includes/d365fin_md.md)], you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="f0845-107">Если функция входящих документов настроена, можно использовать различные функции для просмотра квитанций по расходам, управления задачами OCR, а также преобразования входящих файлов документов, вручную и автоматически, в соответствующие документы либо строки журналов.</span><span class="sxs-lookup"><span data-stu-id="f0845-107">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="f0845-108">Внешние файлы можно прикреплять на любом этапе обработки, в том числе к учтенным документам и к полученным записям поставщика, клиента и главной книги.</span><span class="sxs-lookup"><span data-stu-id="f0845-108">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="f0845-109">Дополнительные сведения см. в разделе [Обработка входящих документов](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="f0845-109">For more information, see [Processing Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="f0845-110">Настройка возможности входящих документов</span><span class="sxs-lookup"><span data-stu-id="f0845-110">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="f0845-111">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка входящих документов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f0845-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="f0845-112">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="f0845-112">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="f0845-113">Настройка утверждающих для записей входящих документов</span><span class="sxs-lookup"><span data-stu-id="f0845-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="f0845-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка входящих документов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f0845-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="f0845-115">В окне **Настройка входящих документов** выберите действие **Утверждающие**.</span><span class="sxs-lookup"><span data-stu-id="f0845-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="f0845-116">В окне **Утверждающие для входящего документа** будут показаны все пользователи, настроенные в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="f0845-116">The **Incoming Document Approvers** window shows all users that are set up in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  
3. <span data-ttu-id="f0845-117">Выберите одного или нескольких пользователей, которые могут утвердить входящий документ до создания соответствующей строки в документе или журнале.</span><span class="sxs-lookup"><span data-stu-id="f0845-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="f0845-118">После настройки утверждающих в окне **Утверждание для входящего документа** только такие пользователи смогут утверждать входящий документ, если установлен флажок **Требовать утверждение для создания** в окне **Настройка входящих документов**.</span><span class="sxs-lookup"><span data-stu-id="f0845-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

> [!NOTE]  
>   <span data-ttu-id="f0845-119">Эта настройка утверждения не связана с рабочими процессами утверждения.</span><span class="sxs-lookup"><span data-stu-id="f0845-119">This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="f0845-120">Дополнительные сведения см. в разделе [Практическое руководство. Использование рабочих процессов утверждения](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="f0845-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="f0845-121">Настройка службы распознавания</span><span class="sxs-lookup"><span data-stu-id="f0845-121">To set up an OCR service</span></span>
1. <span data-ttu-id="f0845-122">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка службы OCR**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="f0845-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="f0845-123">Заполните соответствующим образом поля.</span><span class="sxs-lookup"><span data-stu-id="f0845-123">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="f0845-124">Шифрование реквизитов доступа</span><span class="sxs-lookup"><span data-stu-id="f0845-124">To encrypt your login information</span></span>
<span data-ttu-id="f0845-125">Рекомендуется защищать данные для входа, введенные в окне **Настройка OCR**.</span><span class="sxs-lookup"><span data-stu-id="f0845-125">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="f0845-126">Можно зашифровать данные на сервере, создав новые или импортировав существующие ключи шифрования, включаемые на экземпляре сервера, подключенном к базе данных.</span><span class="sxs-lookup"><span data-stu-id="f0845-126">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="f0845-127">В окне **Настройка OCR** выберите действие **Управление шифрованием**.</span><span class="sxs-lookup"><span data-stu-id="f0845-127">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="f0845-128">В окне **Управление шифрованием данных** включите шифрование данных.</span><span class="sxs-lookup"><span data-stu-id="f0845-128">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="f0845-129">См. также</span><span class="sxs-lookup"><span data-stu-id="f0845-129">See Also</span></span>
[<span data-ttu-id="f0845-130">Обработка входящих документов</span><span class="sxs-lookup"><span data-stu-id="f0845-130">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="f0845-131">Входящие документы</span><span class="sxs-lookup"><span data-stu-id="f0845-131">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="f0845-132">Покупки</span><span class="sxs-lookup"><span data-stu-id="f0845-132">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="f0845-133">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f0845-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

