---
title: "Сведения о об учете документов продажи"
description: "Узнайте о различных функциях учета документов продажи."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: a43c9639592b8249481832cb2b3a89e93638f229
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="posting-sales"></a><span data-ttu-id="87035-103">Учет продаж</span><span class="sxs-lookup"><span data-stu-id="87035-103">Posting Sales</span></span>
<span data-ttu-id="87035-104">В разделе **Учетная группа** в документе продажи можно выбирать следующие функции учета:</span><span class="sxs-lookup"><span data-stu-id="87035-104">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

* <span data-ttu-id="87035-105">**Учесть**</span><span class="sxs-lookup"><span data-stu-id="87035-105">**Post**</span></span>
* <span data-ttu-id="87035-106">**Тестовый отчет**</span><span class="sxs-lookup"><span data-stu-id="87035-106">**Test Report**</span></span>
* <span data-ttu-id="87035-107">**Учесть и отправить**</span><span class="sxs-lookup"><span data-stu-id="87035-107">**Post and Send**</span></span>
* <span data-ttu-id="87035-108">**Учет и печать**</span><span class="sxs-lookup"><span data-stu-id="87035-108">**Post and Print**</span></span>
* <span data-ttu-id="87035-109">**Учесть и отправить по эл. почте**</span><span class="sxs-lookup"><span data-stu-id="87035-109">**Post and Email**</span></span>
* <span data-ttu-id="87035-110">**Пакетный учет**</span><span class="sxs-lookup"><span data-stu-id="87035-110">**Post Batch**</span></span>
* <span data-ttu-id="87035-111">**Предварительный просмотр учета**</span><span class="sxs-lookup"><span data-stu-id="87035-111">**Preview Posting**</span></span>

<span data-ttu-id="87035-112">После заполнения всех строк и ввода всей информации в заказ на продажу его можно учесть.</span><span class="sxs-lookup"><span data-stu-id="87035-112">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="87035-113">Это создает отгрузку и счет.</span><span class="sxs-lookup"><span data-stu-id="87035-113">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="87035-114">Когда учитывается заказ на продажу, обновляются счет клиента, главная книга и записи книги операций по товарам.</span><span class="sxs-lookup"><span data-stu-id="87035-114">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="87035-115">По каждому заказу на продажу в таблице **Операция ГК** создается операция продажи.</span><span class="sxs-lookup"><span data-stu-id="87035-115">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="87035-116">Операция создается также в счете клиента в таблице **Книга операций клиентов**, а операция ГК создается в соответствующем счете дебеторской задолженности.</span><span class="sxs-lookup"><span data-stu-id="87035-116">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="87035-117">Кроме этого, в результате учета заказа может быть создана операция НДС и операция Главной книги по сумме скидки.</span><span class="sxs-lookup"><span data-stu-id="87035-117">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="87035-118">Учет операции по скидке зависит от содержимого поля **Учет скидки** окна **Настройка модуля "Продажи"**.</span><span class="sxs-lookup"><span data-stu-id="87035-118">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="87035-119">Для каждой строки заказа на продажу будет создаваться операция книги товаров в таблице **Книга операций по товарам** (если строки продажи содержат номера товаров) или операция ГК в таблице **Операция ГК** (если строки продажи содержат счет ГК).</span><span class="sxs-lookup"><span data-stu-id="87035-119">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="87035-120">В дополнение к этому заказы продажи всегда записываются в таблицах **«Расх. накладная - заголовок»** и **Заголовок счета продаж**.</span><span class="sxs-lookup"><span data-stu-id="87035-120">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

> [!IMPORTANT]  
>   <span data-ttu-id="87035-121">При учете заказа можно создавать, как расходную накладную, так и счет.</span><span class="sxs-lookup"><span data-stu-id="87035-121">When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="87035-122">Их можно выполнять одновременно и независимо друг от друга.</span><span class="sxs-lookup"><span data-stu-id="87035-122">These can be done at the same time or independently.</span></span> <span data-ttu-id="87035-123">Можно создавать частичную расходную накладную и частичный счет, заполнив поля **Кол-во для отгрузки** и **Кол-во для выставления счета** в строках отдельных заказов на продажу перед учетом.</span><span class="sxs-lookup"><span data-stu-id="87035-123">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="87035-124">Следует отметить, что невозможно создавать счет по тому, что еще не отгружено.</span><span class="sxs-lookup"><span data-stu-id="87035-124">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="87035-125">Т.е. прежде, чем выставлять счет, следует зарегистрировать расходную накладную или следует выбрать одновременное выполнение отгрузки и выставления счета.</span><span class="sxs-lookup"><span data-stu-id="87035-125">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span>

<span data-ttu-id="87035-126">Если учет завершен, учтенные строки продажи удаляются из заказа.</span><span class="sxs-lookup"><span data-stu-id="87035-126">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="87035-127">При завершении учета появляется соответствующее сообщение.</span><span class="sxs-lookup"><span data-stu-id="87035-127">A message tells you when the posting is completed.</span></span> <span data-ttu-id="87035-128">После этого появится возможность просмотра учтенных операций в различных окнах, содержащих учтенные операции, в том числе в окнах **Книга операций по клиентам**, **Операции ГК**, **Книга операций по товарам**, **Учтенные расх. накладные продажи** и **Учтенные счета продажи**.</span><span class="sxs-lookup"><span data-stu-id="87035-128">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="87035-129">См. также</span><span class="sxs-lookup"><span data-stu-id="87035-129">See Also</span></span>
[<span data-ttu-id="87035-130">Продажи</span><span class="sxs-lookup"><span data-stu-id="87035-130">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="87035-131">Практическое руководство. Отправка документов по электронной почте</span><span class="sxs-lookup"><span data-stu-id="87035-131">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)  
<span data-ttu-id="87035-132">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="87035-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>


