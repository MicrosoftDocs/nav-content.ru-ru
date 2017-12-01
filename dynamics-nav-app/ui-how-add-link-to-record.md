---
title: "Как добавлять в записи ссылки на внешние документы или программы"
description: "Присоединение гиперссылок к документам или веб-сайтам на конкретную запись, например, на клиента или документ."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 438d504d5c8c494ca5fae271297593df19a1a7bc
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="adding-links-to-websites-documents-or-programs-on-records"></a><span data-ttu-id="35a23-103">Добавление в записи ссылок на веб-сайты, документы или программы</span><span class="sxs-lookup"><span data-stu-id="35a23-103">Adding Links to Websites, Documents, or Programs on Records</span></span>
<span data-ttu-id="35a23-104">На определенную запись, такую как клиент, документ или заказ на продажу, можно добавить ссылку на внешний документ, веб-сайт или программу.</span><span class="sxs-lookup"><span data-stu-id="35a23-104">On a specific record, such as a customer, document, or sales order, you can add a link to an external document, website, or program.</span></span> <span data-ttu-id="35a23-105">Кроме того, может понадобиться ссылка, при выборе которой будет открываться новое пустое сообщение электронной почты определенному получателю.</span><span class="sxs-lookup"><span data-stu-id="35a23-105">Or, you may want a link that opens a new empty email to a specific recipient when you select it.</span></span> <span data-ttu-id="35a23-106">Страница карточки для некоторых записей, таких как карточки клиентов и поставщиков, предусмотрено поле **Интернет-адрес**, в котором можно ввести URL-адрес.</span><span class="sxs-lookup"><span data-stu-id="35a23-106">The card page for some records, such as customer and vendor cards, include a **Home Page** field where you can enter an Internet address (URL).</span></span> <span data-ttu-id="35a23-107">Для включения других ссылок можно воспользоваться методом, описанным в данной статье.</span><span class="sxs-lookup"><span data-stu-id="35a23-107">To include other links, you can use the method described in this article.</span></span>

<span data-ttu-id="35a23-108">Другим примером может быть получение распечатанных счетов от поставщиков.</span><span class="sxs-lookup"><span data-stu-id="35a23-108">Another example could be when you receive printed invoices from vendors.</span></span> <span data-ttu-id="35a23-109">Можно отсканировать их и сохранить в виде PDF-файлов на сайте SharePoint.</span><span class="sxs-lookup"><span data-stu-id="35a23-109">You can scan them and store them as .pdf files on a SharePoint site.</span></span> <span data-ttu-id="35a23-110">Затем в счете покупки в [!INCLUDE[d365fin_md](includes/d365fin_md.md)] можно добавить ссылку на соответствующий счет на сервере SharePoint.</span><span class="sxs-lookup"><span data-stu-id="35a23-110">Then you can make a link from a purchase invoice in [!INCLUDE[d365fin_md](includes/d365fin_md.md)] to the corresponding invoice on  SharePoint.</span></span> <span data-ttu-id="35a23-111">Кроме того, в карточке товара можно добавить ссылку на соответствующую страницу в онлайновом каталоге поставщика.</span><span class="sxs-lookup"><span data-stu-id="35a23-111">Or, you can make a link from an item card to the corresponding page in your vendor's online catalog.</span></span>
  
## <a name="to-add-a-link-on-a-record"></a><span data-ttu-id="35a23-112">Добавление ссылки на запись</span><span class="sxs-lookup"><span data-stu-id="35a23-112">To add a link on a record</span></span>   
  
1.  <span data-ttu-id="35a23-113">Откройте запись, в которую требуется вложить ссылку, например карточку клиента или заказ на продажу.</span><span class="sxs-lookup"><span data-stu-id="35a23-113">Open the record that you want to attach the link to, such as a customer card or sales order.</span></span> <span data-ttu-id="35a23-114">Если нужно вложить ссылку в конкретную строку, например строку журнала, выделите эту строку.</span><span class="sxs-lookup"><span data-stu-id="35a23-114">If you want to attach the link to a specific line, such as a journal line, select the line.</span></span>  
  
2.  <span data-ttu-id="35a23-115">Выберите действие **Ссылки**, чтобы открыть окно **Ссылки**, в котором отображаются все текущие ссылки, которые добавлены в запись.</span><span class="sxs-lookup"><span data-stu-id="35a23-115">Choose the **Links** action to open the **Links** windows that shows all the current links that are added to the record.</span></span>

3. <span data-ttu-id="35a23-116">Чтобы добавить новую ссылку, выберите **+создать**.</span><span class="sxs-lookup"><span data-stu-id="35a23-116">To add a new link, choose **+new**.</span></span> 
  
4.  <span data-ttu-id="35a23-117">В поле **Адрес ссылки** введите</span><span class="sxs-lookup"><span data-stu-id="35a23-117">In the **Link Address** field, enter</span></span>

    -   <span data-ttu-id="35a23-118">Для связывания с файлом на компьютере или в сети введите полный путь и имя файла, например **C:My Documentsinvoice1.doc**.</span><span class="sxs-lookup"><span data-stu-id="35a23-118">To link to a file on your computer or network, enter the full path and file name, such as  **C:My Documentsinvoice1.doc**.</span></span>
    -   <span data-ttu-id="35a23-119">Для связывания с веб-сайтом введите интернет-адрес (URL-адрес), например **www.microsoft.com**.</span><span class="sxs-lookup"><span data-stu-id="35a23-119">To link to website, enter the Internet address (URL), such as **www.microsoft.com**.</span></span> 
    -   <span data-ttu-id="35a23-120">Для связывания с веб-сайтом введите интернет-адрес (URL-адрес), например **www.microsoft.com**.</span><span class="sxs-lookup"><span data-stu-id="35a23-120">To link to website, enter the Internet address (URL), such as **www.microsoft.com**.</span></span> 
    -   <span data-ttu-id="35a23-121">Для связывания с программой введите специальную строку для открытия программы.</span><span class="sxs-lookup"><span data-stu-id="35a23-121">To link to a program, enter a specific string to open the program.</span></span> <span data-ttu-id="35a23-122">Например, чтобы открыть OneNote с определенной страницы, введите **onenote:///C:My Documentstest.one**.</span><span class="sxs-lookup"><span data-stu-id="35a23-122">For example, to open OneNote with a specific page, enter **onenote:///C:My Documentstest.one**.</span></span> <span data-ttu-id="35a23-123">Или, чтобы открыть Outlook с новым пустым сообщением электронной почты пользователю с определенным псевдонимом, введите следующее: **mailto:тестовый_псевдоним**.</span><span class="sxs-lookup"><span data-stu-id="35a23-123">Or, to open Outlook with a new empty email to a specific alias, enter **mailto:testalias**.</span></span>  
  
5.  <span data-ttu-id="35a23-124">Заполните поле **Описание** сведениями о ссылке.</span><span class="sxs-lookup"><span data-stu-id="35a23-124">Fill in the **Description** field with information about the link.</span></span>  
  
6.  <span data-ttu-id="35a23-125">Нажмите кнопку **Сохранить**.</span><span class="sxs-lookup"><span data-stu-id="35a23-125">Choose the **Save** button.</span></span>  
  
## <a name="to-delete-a-link-from-a-record"></a><span data-ttu-id="35a23-126">Удаление ссылки из записи</span><span class="sxs-lookup"><span data-stu-id="35a23-126">To delete a link from a record</span></span>  
  
<span data-ttu-id="35a23-127">Чтобы удалить ссылку, можно в окне **Ссылки** выбрать **...**, затем **Удалить**.</span><span class="sxs-lookup"><span data-stu-id="35a23-127">To delete a link, in the **Links** window, you can select **...** and then **Delete**.</span></span>

<span data-ttu-id="35a23-128">При удалении одной записи, например строки заказа на продажу, заказа на продажу или клиента, будут удалены все ссылки, вложенные в эту запись.</span><span class="sxs-lookup"><span data-stu-id="35a23-128">If you delete a single record, such as a sales order line, a sales order, or a customer, then all the links attached to the record are deleted.</span></span> <span data-ttu-id="35a23-129">Однако если записи удаляются с помощью пакетного задания, например пакетного задания **Удаление заказов на продажу, по которым выставлены счета**, то ссылки будут по-прежнему храниться в базе данных.</span><span class="sxs-lookup"><span data-stu-id="35a23-129">However, if you delete records using a batch job, such as the **Delete Invoiced Sales Orders** batch job, then the links are still stored in the database.</span></span> <span data-ttu-id="35a23-130">Чтобы удалить их из базы данных, необходимо запустить модуль Codeunit **Удаление зависших ссылок на записи**.</span><span class="sxs-lookup"><span data-stu-id="35a23-130">To delete the links from the database, run the **Delete Orphaned Record Links** codeunit.</span></span> <span data-ttu-id="35a23-131">Чтобы это сделать, выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Удаление зависших ссылок на записи**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="35a23-131">To do this, choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delete Orphaned Record Links**, and then choose the related link.</span></span>   
  
<!-- ### To run delete orphaned record links  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Data Deletion**, and then choose the related link.  
  
2.  On the **Data Deletion** page, choose **Tasks**, and then choose **Delete Orphaned Record Links**.  -->
  
## <a name="see-also"></a><span data-ttu-id="35a23-132">См. также</span><span class="sxs-lookup"><span data-stu-id="35a23-132">See Also</span></span>  
<span data-ttu-id="35a23-133">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="35a23-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
