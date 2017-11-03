---
title: "Практическое руководство. Настройка корректирующих счетов"
description: "Вы можете создать корректирующие счета и корректирующие кредит-ноты, чтобы отразить изменения количества и суммы после того как товары были отгружены или получены."
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
ms.openlocfilehash: 1fd56cb4c954f9eeb6bcb850d9d36afd955f3820
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-set-up-corrective-invoicing"></a><span data-ttu-id="4a765-103">Практическое руководство. Настройка корректирующих счетов</span><span class="sxs-lookup"><span data-stu-id="4a765-103">How to: Set Up Corrective Invoicing</span></span>
<span data-ttu-id="4a765-104">Вы можете создать корректирующие счета и корректирующие кредит-ноты, чтобы отразить изменения количества и суммы после того как товары были отгружены или получены.</span><span class="sxs-lookup"><span data-stu-id="4a765-104">You can create corrective invoices and corrective credit memos to reflect changes in quantity and amounts after the items were shipped or received.</span></span> <span data-ttu-id="4a765-105">Сначала необходимо настроить [!INCLUDE[navnow](../../includes/navnow_md.md)].</span><span class="sxs-lookup"><span data-stu-id="4a765-105">First, you must set up [!INCLUDE[navnow](../../includes/navnow_md.md)] with prerequisites.</span></span>  

## <a name="to-set-up-number-series-for-corrective-documents"></a><span data-ttu-id="4a765-106">Настройка серии номеров для корректирующих документов</span><span class="sxs-lookup"><span data-stu-id="4a765-106">To set up number series for corrective documents</span></span>  

1.  <span data-ttu-id="4a765-107">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка модуля "Продажи"** и выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="4a765-107">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales & Receivables Setup**, and choose the related link.</span></span>  
2.  <span data-ttu-id="4a765-108">В окне **Настройка модуля "Продажи"** на вкладке **Нумерация** укажите серию номеров, которую следует использовать для учтенных корректирующих счетов и кредит-нот.</span><span class="sxs-lookup"><span data-stu-id="4a765-108">In the **Sales & Receivables Setup** window, on the **Numbering** tab, specify the number series that must be used for posted corrective invoices and credit memos.</span></span>  

## <a name="to-set-up-inventory-posting-groups"></a><span data-ttu-id="4a765-109">Настройка учетных групп товаров</span><span class="sxs-lookup"><span data-stu-id="4a765-109">To set up inventory posting groups</span></span>  

1.  <span data-ttu-id="4a765-110">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Учетные группы работ** и выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="4a765-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Inventory Posting Groups**, and choose the related link.</span></span>
2.  <span data-ttu-id="4a765-111">В окне **Учетные группы товаров** в поле **Издержки корр. док. продаж (товар)** выберите код товарной издержки, который требуется использовать в операциях стоимости для исправления исходной цены товаров в корректирующих документах.</span><span class="sxs-lookup"><span data-stu-id="4a765-111">In the **Inventory Posting Groups** window, in the **Sales Corr. Doc. Charge (Item)** field, select the item charge code that you want to use in in value entries to correct the original price of items in the corrective documents.</span></span>  

<span data-ttu-id="4a765-112">Для каждой учетной группы товаров можно настроить отдельный код.</span><span class="sxs-lookup"><span data-stu-id="4a765-112">You can set up a separate code for each inventory posting group.</span></span>  

## <a name="see-also"></a><span data-ttu-id="4a765-113">См. также</span><span class="sxs-lookup"><span data-stu-id="4a765-113">See Also</span></span>  
 [<span data-ttu-id="4a765-114">Корректирующие документы</span><span class="sxs-lookup"><span data-stu-id="4a765-114">Corrective Documents</span></span>](corrective-documents.md)

