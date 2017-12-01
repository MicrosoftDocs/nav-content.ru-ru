---
title: "Сведения о об учете документов покупки"
description: "Узнайте о различных функциях учета документов покупки."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 05/12/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 4d743ce44400fde3fd49433f405c4b21508db522
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="posting-purchases"></a><span data-ttu-id="d0862-103">Учет покупок</span><span class="sxs-lookup"><span data-stu-id="d0862-103">Posting Purchases</span></span>
<span data-ttu-id="d0862-104">В разделе **Учетная группа** в документе покупки можно выбирать следующие функции учета:</span><span class="sxs-lookup"><span data-stu-id="d0862-104">In the **Posting group** on a purchase document, you can choose between the following posting functions:</span></span>

* <span data-ttu-id="d0862-105">**Учесть**</span><span class="sxs-lookup"><span data-stu-id="d0862-105">**Post**</span></span>
* <span data-ttu-id="d0862-106">**Предварительный просмотр учета**</span><span class="sxs-lookup"><span data-stu-id="d0862-106">**Preview Posting**</span></span>
* <span data-ttu-id="d0862-107">**Учет и печать**</span><span class="sxs-lookup"><span data-stu-id="d0862-107">**Post and Print**</span></span>
* <span data-ttu-id="d0862-108">**Тестовый отчет**</span><span class="sxs-lookup"><span data-stu-id="d0862-108">**Test Report**</span></span>
* <span data-ttu-id="d0862-109">**Пакетный учет**</span><span class="sxs-lookup"><span data-stu-id="d0862-109">**Post Batch**</span></span>

<span data-ttu-id="d0862-110">После завершения всех строк и ввода всей информации в заказ покупки, его можно учесть, т.е. создать приходную накладную или счет.</span><span class="sxs-lookup"><span data-stu-id="d0862-110">When you have completed all the lines and entered all the information on the purchase order, you can post it, that is, create a receipt and an invoice.</span></span>

<span data-ttu-id="d0862-111">Когда учитывается заказ на покупку, обновляются счет поставщика, главная книга и записи книги операций по товарам.</span><span class="sxs-lookup"><span data-stu-id="d0862-111">When a purchase order is posted, the vendor's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="d0862-112">По каждому заказу на покупку в таблице **Операция ГК** создается операция покупки.</span><span class="sxs-lookup"><span data-stu-id="d0862-112">For each purchase order, a purchase entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="d0862-113">Операция создается также на счете поставщика в таблице **Книга операций поставщиков**, а операция ГК создается на соответствующем счете кредиторской задолженности.</span><span class="sxs-lookup"><span data-stu-id="d0862-113">An entry is also created in the vendor's account in the **Vendor Ledger Entry** table and a G/L entry is created in the relevant payables account.</span></span> <span data-ttu-id="d0862-114">Кроме этого, в результате учета заказа может быть создана операция НДС и операция ГК по сумме скидки.</span><span class="sxs-lookup"><span data-stu-id="d0862-114">In addition, posting the order may result in a VAT entry and a G/L entry for the discount amount.</span></span> <span data-ttu-id="d0862-115">Учет операции по скидке зависит от содержания поля **Учет скидки** окна **Настройка модуля "Покупки"**.</span><span class="sxs-lookup"><span data-stu-id="d0862-115">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Purchases & Payables Setup** window.</span></span>

<span data-ttu-id="d0862-116">Для каждой строки заказа на покупку будет создаваться операция книги товаров в таблице **Книга операций по товарам** (если строки покупки содержат номера товара) или операция ГК в таблице **Операция ГК** (если строки покупки содержат счет ГК).</span><span class="sxs-lookup"><span data-stu-id="d0862-116">For each purchase order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the purchase lines contain item numbers) or a G/L entry will be created in the **G/L Entry** table (if the purchase lines contain a G/L account).</span></span> <span data-ttu-id="d0862-117">Кроме того, заказы покупки всегда записываются в таблицах **Прих. накладная покупки - заголовок** и **Заголовок счета покупки**.</span><span class="sxs-lookup"><span data-stu-id="d0862-117">In addition, purchase orders are always recorded in the **Purch. Recpt. Header** and **Purch. Inv. Header** tables.</span></span>

<span data-ttu-id="d0862-118">Прежде чем приступить к учету, можно напечатать тестовый отчет, который будет содержать всю информацию из заказа на покупку с указанием имеющихся в нем ошибок.</span><span class="sxs-lookup"><span data-stu-id="d0862-118">Before you start to post, you can print a test report that contains all the information in the purchase order and indicates any errors there.</span></span> <span data-ttu-id="d0862-119">Чтобы напечатать отчет, выберите **Учет**, а затем — **Тестовый отчет**.</span><span class="sxs-lookup"><span data-stu-id="d0862-119">To print the report, choose **Posting**, and then choose **Test Report**.</span></span>

> [!IMPORTANT]  
>   <span data-ttu-id="d0862-120">При учете заказа можно создавать, как приходную накладную, так и счет.</span><span class="sxs-lookup"><span data-stu-id="d0862-120">When you post an order, you can create both a receipt and an invoice.</span></span> <span data-ttu-id="d0862-121">Их можно выполнять одновременно и независимо друг от друга.</span><span class="sxs-lookup"><span data-stu-id="d0862-121">These can be done simultaneously or independently.</span></span> <span data-ttu-id="d0862-122">Кроме того, прежде чем приступить к учету, можно создать частичную приходную накладную и частичный счет, заполнив поля **Кол-во для получения** и **Кол-во для выставления счета** в отдельных строках заказа на покупку.</span><span class="sxs-lookup"><span data-stu-id="d0862-122">You can also create a partial receipt and a partial invoice by completing the **Qty. to Receive** and **Qty. to Invoice** fields on the individual purchase order lines before you post.</span></span> <span data-ttu-id="d0862-123">Следует отметить, что невозможно создавать счет для чего-либо, что еще не было получено.</span><span class="sxs-lookup"><span data-stu-id="d0862-123">Note that you cannot create an invoice for something that has not been received.</span></span> <span data-ttu-id="d0862-124">Это означает, что прежде, чем можно будет выставлять счет, следует зарегистрировать приходную накладную или выбрать одновременное получение и выставление счета.</span><span class="sxs-lookup"><span data-stu-id="d0862-124">That is, before you can invoice, you must have recorded a receipt, or you must choose to receive and invoice at the same time.</span></span>

<span data-ttu-id="d0862-125">Программа позволяет выполнить либо учет, либо учет и печать.</span><span class="sxs-lookup"><span data-stu-id="d0862-125">You can either post, or post and print.</span></span> <span data-ttu-id="d0862-126">Если выбрать учет и печать, отчет напечатается одновременно с его учетом.</span><span class="sxs-lookup"><span data-stu-id="d0862-126">If you choose to post and print, a report is printed when the order is posted.</span></span> <span data-ttu-id="d0862-127">Можно также выбрать функцию **Пакетный учет**, позволяющую выполнять учет нескольких заказов одновременно.</span><span class="sxs-lookup"><span data-stu-id="d0862-127">You can also choose the **Post Batch** function, which lets you post several orders at the same time.</span></span>

<span data-ttu-id="d0862-128">Если учет завершен, учтенные строки покупки удаляются из заказа.</span><span class="sxs-lookup"><span data-stu-id="d0862-128">When the posting is completed, the posted purchase lines are removed from the order.</span></span> <span data-ttu-id="d0862-129">При завершении учета появляется соответствующее сообщение.</span><span class="sxs-lookup"><span data-stu-id="d0862-129">A message tells you when the posting is completed.</span></span> <span data-ttu-id="d0862-130">После этого появится возможность просмотра учтенных операций в различных окнах, содержащих учтенные операции, в том числе в окнах **Книга операций по поставщикам**, **Операции ГК**, **Книга операций по товарам**, **Приходные накладные** и **Учтенные счета покупки**.</span><span class="sxs-lookup"><span data-stu-id="d0862-130">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Vendor Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Purchase Receipts**, and **Posted Purchase Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="d0862-131">См. также</span><span class="sxs-lookup"><span data-stu-id="d0862-131">See Also</span></span>
[<span data-ttu-id="d0862-132">Покупки</span><span class="sxs-lookup"><span data-stu-id="d0862-132">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="d0862-133">Учет документов и журналов</span><span class="sxs-lookup"><span data-stu-id="d0862-133">Post Documents and Journals</span></span>](ui-post-documents-journals.md)  
<span data-ttu-id="d0862-134">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="d0862-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>


