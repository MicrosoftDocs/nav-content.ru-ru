---
title: "Учет продаж"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e87dd5faf7713aecfbe7209d00bb8076fcae9d25
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---

# <a name="posting-sales"></a><span data-ttu-id="38bb6-102">Учет продаж</span><span class="sxs-lookup"><span data-stu-id="38bb6-102">Posting Sales</span></span>
<span data-ttu-id="38bb6-103">В разделе **Учетная группа** в документе продажи можно выбирать следующие функции учета:</span><span class="sxs-lookup"><span data-stu-id="38bb6-103">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

- <span data-ttu-id="38bb6-104">**Учесть**</span><span class="sxs-lookup"><span data-stu-id="38bb6-104">**Post**</span></span>
- <span data-ttu-id="38bb6-105">**Тестовый отчет**</span><span class="sxs-lookup"><span data-stu-id="38bb6-105">**Test Report**</span></span>
- <span data-ttu-id="38bb6-106">**Учесть и отправить**</span><span class="sxs-lookup"><span data-stu-id="38bb6-106">**Post and Send**</span></span>
- <span data-ttu-id="38bb6-107">**Учет и печать**</span><span class="sxs-lookup"><span data-stu-id="38bb6-107">**Post and Print**</span></span>
- <span data-ttu-id="38bb6-108">**Учесть и отправить по эл. почте**</span><span class="sxs-lookup"><span data-stu-id="38bb6-108">**Post and Email**</span></span>
- <span data-ttu-id="38bb6-109">**Пакетный учет**</span><span class="sxs-lookup"><span data-stu-id="38bb6-109">**Post Batch**</span></span>
- <span data-ttu-id="38bb6-110">**Предварительный просмотр учета**</span><span class="sxs-lookup"><span data-stu-id="38bb6-110">**Preview Posting**</span></span>

<span data-ttu-id="38bb6-111">После заполнения всех строк и ввода всей информации в заказ на продажу его можно учесть.</span><span class="sxs-lookup"><span data-stu-id="38bb6-111">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="38bb6-112">Это создает отгрузку и счет.</span><span class="sxs-lookup"><span data-stu-id="38bb6-112">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="38bb6-113">Когда учитывается заказ на продажу, обновляются счет клиента, главная книга и записи книги операций по товарам.</span><span class="sxs-lookup"><span data-stu-id="38bb6-113">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="38bb6-114">По каждому заказу на продажу в таблице **Операция ГК** создается операция продажи.</span><span class="sxs-lookup"><span data-stu-id="38bb6-114">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="38bb6-115">Операция создается также в счете клиента в таблице **Книга операций клиентов**, а операция ГК создается в соответствующем счете дебеторской задолженности.</span><span class="sxs-lookup"><span data-stu-id="38bb6-115">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="38bb6-116">Кроме этого, в результате учета заказа может быть создана операция НДС и операция Главной книги по сумме скидки.</span><span class="sxs-lookup"><span data-stu-id="38bb6-116">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="38bb6-117">Учет операции по скидке зависит от содержимого поля **Учет скидки** окна **Настройка модуля "Продажи"**.</span><span class="sxs-lookup"><span data-stu-id="38bb6-117">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="38bb6-118">Для каждой строки заказа на продажу будет создаваться операция книги товаров в таблице **Книга операций по товарам** (если строки продажи содержат номера товаров) или операция ГК в таблице **Операция ГК** (если строки продажи содержат счет ГК).</span><span class="sxs-lookup"><span data-stu-id="38bb6-118">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="38bb6-119">В дополнение к этому заказы продажи всегда записываются в таблицах **Расх. накладная - заголовок** и **Заголовок счета продаж**.</span><span class="sxs-lookup"><span data-stu-id="38bb6-119">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

<span data-ttu-id="38bb6-120">**Внимание**. При учете заказа можно создать как расходную накладную, так и счет.</span><span class="sxs-lookup"><span data-stu-id="38bb6-120">**Important**: When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="38bb6-121">Их можно выполнять одновременно и независимо друг от друга.</span><span class="sxs-lookup"><span data-stu-id="38bb6-121">These can be done at the same time or independently.</span></span> <span data-ttu-id="38bb6-122">Можно создавать частичную расходную накладную и частичный счет, заполнив поля **Кол-во для отгрузки** и **Кол-во для выставления счета** в строках отдельных заказов на продажу перед учетом.</span><span class="sxs-lookup"><span data-stu-id="38bb6-122">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="38bb6-123">Следует отметить, что невозможно создавать счет по тому, что еще не отгружено.</span><span class="sxs-lookup"><span data-stu-id="38bb6-123">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="38bb6-124">Т.е. прежде, чем выставлять счет, следует зарегистрировать расходную накладную или следует выбрать одновременное выполнение отгрузки и выставления счета.</span><span class="sxs-lookup"><span data-stu-id="38bb6-124">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span> 

<span data-ttu-id="38bb6-125">Если учет завершен, учтенные строки продажи удаляются из заказа.</span><span class="sxs-lookup"><span data-stu-id="38bb6-125">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="38bb6-126">При завершении учета появляется соответствующее сообщение.</span><span class="sxs-lookup"><span data-stu-id="38bb6-126">A message tells you when the posting is completed.</span></span> <span data-ttu-id="38bb6-127">После этого появится возможность просмотра учтенных операций в различных окнах, содержащих учтенные операции, в том числе в окнах **Книга операций по клиентам**, **Операции ГК**, **Книга операций по товарам**, **Учтенные расх. накладные продажи** и **Учтенные счета продажи**.</span><span class="sxs-lookup"><span data-stu-id="38bb6-127">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="38bb6-128">См. также</span><span class="sxs-lookup"><span data-stu-id="38bb6-128">See Also</span></span>
[<span data-ttu-id="38bb6-129">Практическое руководство. Отправка документов по электронной почте</span><span class="sxs-lookup"><span data-stu-id="38bb6-129">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)

