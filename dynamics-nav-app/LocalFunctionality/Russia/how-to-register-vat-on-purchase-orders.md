---
title: "Практическое руководство. Регистрация НДС по заказам на покупку"
description: "В России организации должны вести журнал НДС по входящим и исходящим счетам. [!INCLUDE[navnow](../../includes/navnow_md.md)] позволяет регистрировать НДС по заказам на покупку, чтобы эта информация отслеживалась в журнале счетов НДС."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 64c3c0e6233bcc1b7973ca62cf75aeabeb76c4c9
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-register-vat-on-purchase-orders"></a><span data-ttu-id="01de8-104">Практическое руководство. Регистрация НДС по заказам на покупку</span><span class="sxs-lookup"><span data-stu-id="01de8-104">How to: Register VAT on Purchase Orders</span></span>
<span data-ttu-id="01de8-105">В России организации должны вести журнал НДС по входящим и исходящим счетам.</span><span class="sxs-lookup"><span data-stu-id="01de8-105">In Russia, organizations are required to keep a journal of received and issued VAT invoices.</span></span> [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="01de8-106"> позволяет регистрировать НДС по заказам на покупку, чтобы эта информация отслеживалась в журнале счетов НДС.</span><span class="sxs-lookup"><span data-stu-id="01de8-106"> enables you to register VAT on purchase orders so that the information is tracked in the VAT invoices journal.</span></span>  

## <a name="to-register-vat-on-a-purchase-order"></a><span data-ttu-id="01de8-107">Регистрация НДС по заказам на покупку</span><span class="sxs-lookup"><span data-stu-id="01de8-107">To register VAT on a purchase order</span></span>  

1.  <span data-ttu-id="01de8-108">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказ на покупку**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="01de8-108">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Order**, and then choose the related link.</span></span> <span data-ttu-id="01de8-109">Выберите соответствующий заказ на покупку.</span><span class="sxs-lookup"><span data-stu-id="01de8-109">Select the relevant purchase order.</span></span>  
2.  <span data-ttu-id="01de8-110">На экспресс-вкладке **Отгрузка** заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="01de8-110">On the **Shipping** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="01de8-111">Поле</span><span class="sxs-lookup"><span data-stu-id="01de8-111">Field</span></span>|<span data-ttu-id="01de8-112">Описанием</span><span class="sxs-lookup"><span data-stu-id="01de8-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="01de8-113">**Поставщик Накладная Но.**</span><span class="sxs-lookup"><span data-stu-id="01de8-113">**Vendor Receipts No.**</span></span>|<span data-ttu-id="01de8-114">Введите номер из накладной поставщика.</span><span class="sxs-lookup"><span data-stu-id="01de8-114">Enter the identification number from the vendor receipt.</span></span>|  
    |<span data-ttu-id="01de8-115">**Поставщик Накладная Дата**</span><span class="sxs-lookup"><span data-stu-id="01de8-115">**Vendor Receipts Date**</span></span>|<span data-ttu-id="01de8-116">Введите дату из накладной поставщика.</span><span class="sxs-lookup"><span data-stu-id="01de8-116">Enter the date from the vendor receipt.</span></span>|  

3.  <span data-ttu-id="01de8-117">На экспресс-вкладке **НДС** заполните поля, как описано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="01de8-117">On the **VAT** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="01de8-118">Поле</span><span class="sxs-lookup"><span data-stu-id="01de8-118">Field</span></span>|<span data-ttu-id="01de8-119">Описанием</span><span class="sxs-lookup"><span data-stu-id="01de8-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="01de8-120">**Счет-Фактура Но.**</span><span class="sxs-lookup"><span data-stu-id="01de8-120">**Vendor VAT Invoice No.**</span></span>|<span data-ttu-id="01de8-121">Введите номер счета из исходной транзакции НДС.</span><span class="sxs-lookup"><span data-stu-id="01de8-121">Enter the invoice number from the original VAT transaction.</span></span>|  
    |<span data-ttu-id="01de8-122">**Счет-Фактура Дата Выставления**</span><span class="sxs-lookup"><span data-stu-id="01de8-122">**Vendor VAT Invoice Date**</span></span>|<span data-ttu-id="01de8-123">Введите дату счета из исходной транзакции НДС.</span><span class="sxs-lookup"><span data-stu-id="01de8-123">Enter the invoice date from the original VAT transaction.</span></span>|  
    |<span data-ttu-id="01de8-124">**Дата получения счета-фактуры поставщика**</span><span class="sxs-lookup"><span data-stu-id="01de8-124">**Vendor VAT Invoice Rcvd Date**</span></span>|<span data-ttu-id="01de8-125">Введите дату получения покупки.</span><span class="sxs-lookup"><span data-stu-id="01de8-125">Enter the date that the purchase was received.</span></span>|  

 <span data-ttu-id="01de8-126">Транзакция НДС теперь зарегистрирована и будет отслеживаться в журнале счетов НДС после учета заказа на покупку.</span><span class="sxs-lookup"><span data-stu-id="01de8-126">The VAT transaction is now registered and will be tracked in the VAT invoices journal after the purchase order is posted.</span></span>  

## <a name="see-also"></a><span data-ttu-id="01de8-127">См. также</span><span class="sxs-lookup"><span data-stu-id="01de8-127">See Also</span></span>  
 <span data-ttu-id="01de8-128">[Практическое руководство. Настройка книг НДС](how-to-set-up-vat-ledgers.md) </span><span class="sxs-lookup"><span data-stu-id="01de8-128">[How to: Set Up VAT Ledgers](how-to-set-up-vat-ledgers.md) </span></span>  
 [<span data-ttu-id="01de8-129">Практическое руководство. Подготовка операций НДС к учету</span><span class="sxs-lookup"><span data-stu-id="01de8-129">How to: Prepare VAT Entries for Posting</span></span>](how-to-prepare-vat-entries-for-posting.md)  
 [<span data-ttu-id="01de8-130">Практическое руководство. Подача отчета об НДС в налоговые органы</span><span class="sxs-lookup"><span data-stu-id="01de8-130">How to: Report VAT to Tax Authorities</span></span>](../../finance-how-report-vat.md)

