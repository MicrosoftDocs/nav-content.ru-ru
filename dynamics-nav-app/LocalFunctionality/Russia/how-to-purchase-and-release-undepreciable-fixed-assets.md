---
title: "Практическое руководство. Покупка и ввод в эксплуатацию малоценных основных средств"
description: "После учета основных средств необходимо создать акт ввода основного средства в эксплуатацию и учесть его."
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
ms.openlocfilehash: b2be919e90afa17274d62e3abf96272d30befa1b
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-purchase-and-release-undepreciable-fixed-assets"></a><span data-ttu-id="2f451-103">Практическое руководство. Покупка и ввод в эксплуатацию малоценных основных средств</span><span class="sxs-lookup"><span data-stu-id="2f451-103">How to: Purchase and Release Undepreciable Fixed Assets</span></span>
<span data-ttu-id="2f451-104">После учета основных средств необходимо создать акт ввода основного средства в эксплуатацию и учесть его.</span><span class="sxs-lookup"><span data-stu-id="2f451-104">After posting the fixed assets, you must create a fixed asset release act of the fixed asset and post it.</span></span> <span data-ttu-id="2f451-105">Если открыть окно **Карточка основного средства**, можно видеть, что в соответствующих строках как в поле амортизации для операции, так и в поле остаточной стоимости указано нулевое значение.</span><span class="sxs-lookup"><span data-stu-id="2f451-105">If you open the **Fixed Asset Card** window for that fixed asset, you can see that in the corresponding lines, the depreciation for operation contains a zero, and the book value also contains a zero.</span></span>  

<span data-ttu-id="2f451-106">В ходе учета акта ввода основного средства в эксплуатацию в оперативной книге амортизации создаются две операции основного средства.</span><span class="sxs-lookup"><span data-stu-id="2f451-106">The posting of the fixed asset release act results in two fixed asset operations in the operation depreciation book.</span></span> <span data-ttu-id="2f451-107">Первая — это операция основного средства с учтенной стоимостью его приобретения и учтенным количеством.</span><span class="sxs-lookup"><span data-stu-id="2f451-107">The first is the fixed asset operation with the acquisition cost and quantity posted.</span></span> <span data-ttu-id="2f451-108">Вторая — операция основного средства, в которой приобретение при реализации учтено с той же стоимостью и тем же количеством, но с обратным знаком для обоих.</span><span class="sxs-lookup"><span data-stu-id="2f451-108">The second is the fixed asset operation with the acquisition on disposal posted with the same cost and quantity, but with the sign reversed for both.</span></span> <span data-ttu-id="2f451-109">Основное средство вводится в эксплуатацию и реализуется с суммой и количеством в данной книге амортизации, интегрированной с главной книгой.</span><span class="sxs-lookup"><span data-stu-id="2f451-109">The fixed asset is released and disposed in amount and quantity in this depreciation book, which is integrated with the general ledger.</span></span> <span data-ttu-id="2f451-110">Остаточная стоимость и количество для основного средства равны нулю, а операция амортизации отсутствует.</span><span class="sxs-lookup"><span data-stu-id="2f451-110">The book value and quantity of the fixed asset are zero, and there is no depreciation operation.</span></span> <span data-ttu-id="2f451-111">Согласно этой книге амортизации основное средство полностью реализовано без амортизации.</span><span class="sxs-lookup"><span data-stu-id="2f451-111">According to this depreciation book, the fixed asset is fully disposed without depreciation.</span></span>  

<span data-ttu-id="2f451-112">В окне **Карточка основного средства** автоматически открывается новая строка с книгой амортизации количественного учета.</span><span class="sxs-lookup"><span data-stu-id="2f451-112">In the **Fixed Asset Card** window, a new line automatically opens with the quantity depreciation book.</span></span> <span data-ttu-id="2f451-113">Количество, стоимость приобретения и остаточная стоимость в книге амортизации этого основного средства равны соответствующим сумме и количеству в заказе покупки.</span><span class="sxs-lookup"><span data-stu-id="2f451-113">The quantity, acquisition cost, and book value in this fixed asset depreciation book are equal to the corresponding amount and quantity in the purchase order.</span></span> <span data-ttu-id="2f451-114">Эта книга показывает существование данного основного средства в терминах количества и суммы.</span><span class="sxs-lookup"><span data-stu-id="2f451-114">This book shows the existence of this fixed asset in terms of the quantity and amount.</span></span> <span data-ttu-id="2f451-115">Она не интегрирована с главной книгой, и поэтому будущие операции не повлияют на финансовый учет.</span><span class="sxs-lookup"><span data-stu-id="2f451-115">It is not integrated with the general ledger, so future operations will not influence financial accounting.</span></span>  

<span data-ttu-id="2f451-116">В финансовом отношении основное средство полностью реализуется в момент его ввода в эксплуатацию, но с ним можно работать в терминах количества и суммы.</span><span class="sxs-lookup"><span data-stu-id="2f451-116">The fixed asset is disposed financially in full at the time of release, but can be operated in quantities and amounts.</span></span>  

<span data-ttu-id="2f451-117">Ниже показано, как создать заказ на покупку и заказ ввода в эксплуатацию для малоценных основных средств.</span><span class="sxs-lookup"><span data-stu-id="2f451-117">The following procedures show how to create a purchase order and a release order for undepreciable fixed assets.</span></span>  

## <a name="to-create-a-purchase-order-for-an-undepreciable-fixed-asset"></a><span data-ttu-id="2f451-118">Создание заказа на покупку для малоценного основного средства</span><span class="sxs-lookup"><span data-stu-id="2f451-118">To create a purchase order for an undepreciable fixed asset</span></span>  

1.  <span data-ttu-id="2f451-119">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказ на покупку**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="2f451-119">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Order**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="2f451-120">Выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="2f451-120">Choose the **Post** action.</span></span>  
3.  <span data-ttu-id="2f451-121">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="2f451-121">Choose the **OK** button.</span></span>  

## <a name="to-create-a-release-order-for-an-undepreciable-fixed-asset"></a><span data-ttu-id="2f451-122">Создание заказа на ввод в эксплуатацию для малоценного основного средства</span><span class="sxs-lookup"><span data-stu-id="2f451-122">To create a release order for an undepreciable fixed asset</span></span>  

1.  <span data-ttu-id="2f451-123">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Акты ввода в эксплуатацию ОС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="2f451-123">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Releases**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="2f451-124">Откройте выпуск.</span><span class="sxs-lookup"><span data-stu-id="2f451-124">Open a release.</span></span>
3. <span data-ttu-id="2f451-125">В окне **Акт ввода в эксплуатацию ОС** выберите действие **Учесть**.</span><span class="sxs-lookup"><span data-stu-id="2f451-125">In the **FA Release Act** window, choose the **Post** action.</span></span>  
3.  <span data-ttu-id="2f451-126">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="2f451-126">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="2f451-127">См. также</span><span class="sxs-lookup"><span data-stu-id="2f451-127">See Also</span></span>  
 <span data-ttu-id="2f451-128">[Практическое руководство. Настройка книги количественного учета](how-to-set-up-a-quantity-book.md) </span><span class="sxs-lookup"><span data-stu-id="2f451-128">[How to: Set Up a Quantity Book](how-to-set-up-a-quantity-book.md) </span></span>  
 <span data-ttu-id="2f451-129">[Малоценные основные средства](undepreciable-fixed-assets.md) </span><span class="sxs-lookup"><span data-stu-id="2f451-129">[Undepreciable Fixed Assets](undepreciable-fixed-assets.md) </span></span>  
 [<span data-ttu-id="2f451-130">Практическое руководство. Настройка малоценных основных средств</span><span class="sxs-lookup"><span data-stu-id="2f451-130">How to: Set Up Undepreciable Fixed Assets</span></span>](how-to-set-up-undepreciable-fixed-assets.md)   

