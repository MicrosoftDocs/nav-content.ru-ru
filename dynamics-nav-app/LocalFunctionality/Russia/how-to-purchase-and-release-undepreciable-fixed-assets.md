---
title: "Практическое руководство. Покупка и ввод в эксплуатацию малоценных основных средств"
description: "После учета основных средств необходимо создать акт ввода основного средства в эксплуатацию и учесть его. Если открыть окно **Карточка основного средства**, можно видеть, что в соответствующих строках как в поле амортизации для операции, так и в поле остаточной стоимости указано нулевое значение."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b261c61ebf4b28e50c5a9c8e17b8fabd13d0b411
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-purchase-and-release-undepreciable-fixed-assets"></a><span data-ttu-id="8de8a-104">Практическое руководство. Покупка и ввод в эксплуатацию малоценных основных средств</span><span class="sxs-lookup"><span data-stu-id="8de8a-104">How to: Purchase and Release Undepreciable Fixed Assets</span></span>
<span data-ttu-id="8de8a-105">После учета основных средств необходимо создать акт ввода основного средства в эксплуатацию и учесть его.</span><span class="sxs-lookup"><span data-stu-id="8de8a-105">After posting the fixed assets, you must create a fixed asset release act of the fixed asset and post it.</span></span> <span data-ttu-id="8de8a-106">Если открыть окно **Карточка основного средства**, можно видеть, что в соответствующих строках как в поле амортизации для операции, так и в поле остаточной стоимости указано нулевое значение.</span><span class="sxs-lookup"><span data-stu-id="8de8a-106">If you open the **Fixed Asset Card** window for that fixed asset, you can see that in the corresponding lines, the depreciation for operation contains a zero, and the book value also contains a zero.</span></span>  
  
 <span data-ttu-id="8de8a-107">В ходе учета акта ввода основного средства в эксплуатацию в оперативной книге амортизации создаются две операции основного средства.</span><span class="sxs-lookup"><span data-stu-id="8de8a-107">The posting of the fixed asset release act results in two fixed asset operations in the operation depreciation book.</span></span> <span data-ttu-id="8de8a-108">Первая — это операция основного средства с учтенной стоимостью его приобретения и учтенным количеством.</span><span class="sxs-lookup"><span data-stu-id="8de8a-108">The first is the fixed asset operation with the acquisition cost and quantity posted.</span></span> <span data-ttu-id="8de8a-109">Вторая — операция основного средства, в которой приобретение при реализации учтено с той же стоимостью и тем же количеством, но с обратным знаком для обоих.</span><span class="sxs-lookup"><span data-stu-id="8de8a-109">The second is the fixed asset operation with the acquisition on disposal posted with the same cost and quantity, but with the sign reversed for both.</span></span> <span data-ttu-id="8de8a-110">Основное средство вводится в эксплуатацию и реализуется с суммой и количеством в данной книге амортизации, интегрированной с главной книгой.</span><span class="sxs-lookup"><span data-stu-id="8de8a-110">The fixed asset is released and disposed in amount and quantity in this depreciation book, which is integrated with the general ledger.</span></span> <span data-ttu-id="8de8a-111">Остаточная стоимость и количество для основного средства равны нулю, а операция амортизации отсутствует.</span><span class="sxs-lookup"><span data-stu-id="8de8a-111">The book value and quantity of the fixed asset are zero, and there is no depreciation operation.</span></span> <span data-ttu-id="8de8a-112">Согласно этой книге амортизации основное средство полностью реализовано без амортизации.</span><span class="sxs-lookup"><span data-stu-id="8de8a-112">According to this depreciation book, the fixed asset is fully disposed without depreciation.</span></span>  
  
 <span data-ttu-id="8de8a-113">В окне **Карточка основного средства** автоматически открывается новая строка с книгой амортизации количественного учета.</span><span class="sxs-lookup"><span data-stu-id="8de8a-113">In the **Fixed Asset Card** window, a new line automatically opens with the quantity depreciation book.</span></span> <span data-ttu-id="8de8a-114">Количество, стоимость приобретения и остаточная стоимость в книге амортизации этого основного средства равны соответствующим сумме и количеству в заказе покупки.</span><span class="sxs-lookup"><span data-stu-id="8de8a-114">The quantity, acquisition cost, and book value in this fixed asset depreciation book are equal to the corresponding amount and quantity in the purchase order.</span></span> <span data-ttu-id="8de8a-115">Эта книга показывает существование данного основного средства в терминах количества и суммы.</span><span class="sxs-lookup"><span data-stu-id="8de8a-115">This book shows the existence of this fixed asset in terms of the quantity and amount.</span></span> <span data-ttu-id="8de8a-116">Она не интегрирована с главной книгой, и поэтому будущие операции не повлияют на финансовый учет.</span><span class="sxs-lookup"><span data-stu-id="8de8a-116">It is not integrated with the general ledger, so future operations will not influence financial accounting.</span></span>  
  
 <span data-ttu-id="8de8a-117">В финансовом отношении основное средство полностью реализуется в момент его ввода в эксплуатацию, но с ним можно работать в терминах количества и суммы.</span><span class="sxs-lookup"><span data-stu-id="8de8a-117">The fixed asset is disposed financially in full at the time of release, but can be operated in quantities and amounts.</span></span>  
  
 <span data-ttu-id="8de8a-118">Ниже показано, как создать заказ на покупку и заказ ввода в эксплуатацию для малоценных основных средств.</span><span class="sxs-lookup"><span data-stu-id="8de8a-118">The following procedures show how to create a purchase order and a release order for undepreciable fixed assets.</span></span>  
  
### <a name="to-create-a-purchase-order-for-an-undepreciable-fixed-asset"></a><span data-ttu-id="8de8a-119">Создание заказа на покупку для малоценного основного средства</span><span class="sxs-lookup"><span data-stu-id="8de8a-119">To create a purchase order for an undepreciable fixed asset</span></span>  
  
1.  <span data-ttu-id="8de8a-120">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказ на покупку**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="8de8a-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Order**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="8de8a-121">В окне **Заказ на покупку** на вкладке **Главная** в группе **Учет** выберите **Учет**.</span><span class="sxs-lookup"><span data-stu-id="8de8a-121">In the **Purchase Order** window, on the **Home** tab, in the **Posting** group, choose **Post**.</span></span>  
  
3.  <span data-ttu-id="8de8a-122">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="8de8a-122">Choose the **OK** button.</span></span>  
  
### <a name="to-create-a-release-order-for-an-undepreciable-fixed-asset"></a><span data-ttu-id="8de8a-123">Создание заказа на ввод в эксплуатацию для малоценного основного средства</span><span class="sxs-lookup"><span data-stu-id="8de8a-123">To create a release order for an undepreciable fixed asset</span></span>  
  
1.  <span data-ttu-id="8de8a-124">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Акты ввода в эксплуатацию ОС**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="8de8a-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Releases**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="8de8a-125">Выберите акт ввода в эксплуатацию и в окне **Акт ввода в эксплуатацию ОС** на вкладке **Главная** в группе **Учет** выберите **Учет**.</span><span class="sxs-lookup"><span data-stu-id="8de8a-125">Select a release, and in the **FA Release Act** window, and on the **Home** tab, in the **Posting** group, choose **Post**.</span></span>  
  
3.  <span data-ttu-id="8de8a-126">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="8de8a-126">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="8de8a-127">См. также</span><span class="sxs-lookup"><span data-stu-id="8de8a-127">See Also</span></span>  
 <span data-ttu-id="8de8a-128">[Практическое руководство. Настройка книги количественного учета](how-to-set-up-a-quantity-book.md) </span><span class="sxs-lookup"><span data-stu-id="8de8a-128">[How to: Set Up a Quantity Book](how-to-set-up-a-quantity-book.md) </span></span>  
 <span data-ttu-id="8de8a-129">[Малоценные основные средства](undepreciable-fixed-assets.md) </span><span class="sxs-lookup"><span data-stu-id="8de8a-129">[Undepreciable Fixed Assets](undepreciable-fixed-assets.md) </span></span>  
 <span data-ttu-id="8de8a-130">[Практическое руководство. Настройка малоценных основных средств](how-to-set-up-undepreciable-fixed-assets.md) </span><span class="sxs-lookup"><span data-stu-id="8de8a-130">[How to: Set Up Undepreciable Fixed Assets](how-to-set-up-undepreciable-fixed-assets.md) </span></span>  
 <span data-ttu-id="8de8a-131">Заказ на покупку</span><span class="sxs-lookup"><span data-stu-id="8de8a-131">Purchase Order</span></span>