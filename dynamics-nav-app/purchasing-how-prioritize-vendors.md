---
title: "Практическое руководство. Назначение приоритетов поставщикам"
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
ms.openlocfilehash: df14bab26aa0d52e7ad5215862fcef608ba5a7d7
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-prioritize-vendors"></a><span data-ttu-id="344fd-102">Практическое руководство. Назначение приоритетов поставщикам</span><span class="sxs-lookup"><span data-stu-id="344fd-102">How to: Prioritize Vendors</span></span>
<span data-ttu-id="344fd-103">В Dynamics NAV предлагаются различные виды оплат поставщикам, например оплаты, которые должны быть произведены быстро, или оплаты, для которых возможны скидки.</span><span class="sxs-lookup"><span data-stu-id="344fd-103">Dynamics NAV can suggest various payments to vendors, for example, payments that will be due soon or payments where a discount is available.</span></span> <span data-ttu-id="344fd-104">Дополнительные сведения см. в разделе [Практическое руководство. Предложение оплаты поставщикам](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="344fd-104">for more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>

<span data-ttu-id="344fd-105">Во-первых, следует назначить приоритеты поставщикам путем назначения им номеров.</span><span class="sxs-lookup"><span data-stu-id="344fd-105">First, you must prioritize your vendors by assigning numbers to them.</span></span>

## <a name="to-prioritize-vendors"></a><span data-ttu-id="344fd-106">Назначение приоритета поставщикам</span><span class="sxs-lookup"><span data-stu-id="344fd-106">To prioritize vendors</span></span>
1. <span data-ttu-id="344fd-107">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Поставщики**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="344fd-107">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="344fd-108">Выберите соответствующего поставщика, а затем выберите **Правка**.</span><span class="sxs-lookup"><span data-stu-id="344fd-108">Select the relevant vendor, and then choose **Edit**.</span></span>
3. <span data-ttu-id="344fd-109">В поле **Приоритет** введите номер.</span><span class="sxs-lookup"><span data-stu-id="344fd-109">In the **Priority** field, enter a number.</span></span>

<span data-ttu-id="344fd-110">Dynamics NAV будет рассматривать самый нижний номер (за исключением 0), как номер, получивший наивысший приоритет.</span><span class="sxs-lookup"><span data-stu-id="344fd-110">Dynamics NAV considers the lowest number, except 0, to have the highest priority.</span></span> <span data-ttu-id="344fd-111">Так, например, если используются 1, 2 и 3, то 1 будет иметь наивысший приоритет.</span><span class="sxs-lookup"><span data-stu-id="344fd-111">So, for example, if you use 1, 2, and 3, then 1 will have the highest priority.</span></span>

<span data-ttu-id="344fd-112">Если назначать приоритет для поставщика не требуется, оставьте поле **Приоритет** пустым.</span><span class="sxs-lookup"><span data-stu-id="344fd-112">If you do not want to prioritize a vendor, leave the **Priority** field blank.</span></span> <span data-ttu-id="344fd-113">В случае же использования средства предложения с учетом приоритетов, поставщик, с пустым полем "Приоритет", будет числиться после всех поставщиков, которые имеют номер приоритета.</span><span class="sxs-lookup"><span data-stu-id="344fd-113">Then, if you use the payment suggestion feature, the vendor will be listed after all the vendors that have a priority number.</span></span> <span data-ttu-id="344fd-114">В случае необходимости можно вводить столько уровней приоритета, сколько требуется.</span><span class="sxs-lookup"><span data-stu-id="344fd-114">You can enter as many priority levels as necessary.</span></span>

## <a name="see-also"></a><span data-ttu-id="344fd-115">См. также</span><span class="sxs-lookup"><span data-stu-id="344fd-115">See Also</span></span>
[<span data-ttu-id="344fd-116">Настройка покупок</span><span class="sxs-lookup"><span data-stu-id="344fd-116">Set Up Purchasing</span></span>](purchasing-setup-purchasing.md)  
[<span data-ttu-id="344fd-117">Управление кредиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="344fd-117">Manage Payables</span></span>](payables-manage-payables.md)

