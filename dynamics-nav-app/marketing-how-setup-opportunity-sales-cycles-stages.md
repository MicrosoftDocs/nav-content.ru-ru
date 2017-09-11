---
title: "Практическое руководство. Настройка циклов продаж и этапов циклов"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 756e9b2f33fe66cd4c2b4e26ca4390683bd087af
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---
# <a name="how-to-set-up-opportunity-sales-cycles-and-cycle-stages"></a><span data-ttu-id="eeb15-102">Практическое руководство. Настройка циклов продаж и этапов циклов</span><span class="sxs-lookup"><span data-stu-id="eeb15-102">How to: Set Up Opportunity Sales Cycles and Cycle Stages</span></span>
<span data-ttu-id="eeb15-103">Прежде чем начать использовать возможностей продаж, необходимо настроить циклы продаж и их этапы.</span><span class="sxs-lookup"><span data-stu-id="eeb15-103">Before you can start using sales opportunities, you must set up sales cycles and sales cycle stages.</span></span> <span data-ttu-id="eeb15-104">Цикл продаж состоит из последовательности этапов от первого контакта до закрытия продаж.</span><span class="sxs-lookup"><span data-stu-id="eeb15-104">A sales cycle is made up of a series of stages that go from the initial contact to the closing of a sale.</span></span> <span data-ttu-id="eeb15-105">Каждый этап может содержать определенные требования, которые должны быть соблюдены, такие как обязательное наличие предложения по продаже перед переходом к следующей стадии.</span><span class="sxs-lookup"><span data-stu-id="eeb15-105">Each stage can have certain requirements that must be met, such as requiring a sales quote, before an opportunity can go to the next stage.</span></span> <span data-ttu-id="eeb15-106">Можно также указать, можно ли пропустить этап.</span><span class="sxs-lookup"><span data-stu-id="eeb15-106">You can also specify whether a stage can be skipped.</span></span> <span data-ttu-id="eeb15-107">Можно настроить столько циклов продаж, сколько требуется, а также необходимое количество этапов цикла продаж в каждом цикле.</span><span class="sxs-lookup"><span data-stu-id="eeb15-107">You can setup as many sales cycles as you need, and you can set up as many sales cycle stages as necessary within a sales cycle.</span></span>

<span data-ttu-id="eeb15-108">Реализация циклов продаж включает настройку кода цикла продаж, определение различных этапов цикла и назначение циклов возможностям.</span><span class="sxs-lookup"><span data-stu-id="eeb15-108">Implementing opportunity sales cycles involves setting up the sales cycle code, defining the different stages of the cycle, and then assigning the cycle to opportunities.</span></span>

## <a name="to-set-up-an-opportunity-sales-cycle-code"></a><span data-ttu-id="eeb15-109">Настройка кода цикла продаж</span><span class="sxs-lookup"><span data-stu-id="eeb15-109">To set up an opportunity sales cycle code</span></span>
1. <span data-ttu-id="eeb15-110">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Циклы продаж**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="eeb15-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Cycles**, and then choose the related link.</span></span> <span data-ttu-id="eeb15-111">Откроется окно **Циклы продаж**, содержащее все существующие циклы продаж.</span><span class="sxs-lookup"><span data-stu-id="eeb15-111">The **Sales Cycles** window opens, and lists all the existing sales cycles.</span></span>
2. <span data-ttu-id="eeb15-112">Выберите действие **Создать** и заполните поля.</span><span class="sxs-lookup"><span data-stu-id="eeb15-112">Choose the **New** action, and fill in the fields.</span></span>

<span data-ttu-id="eeb15-113">Повторите эти шаги, чтобы настроить необходимое количество циклов продаж.</span><span class="sxs-lookup"><span data-stu-id="eeb15-113">Repeat these steps to set up as many sales cycles as you want.</span></span> <span data-ttu-id="eeb15-114">После настройки циклов продаж может понадобиться настроить различные этапы внутри каждого цикла.</span><span class="sxs-lookup"><span data-stu-id="eeb15-114">After you have set up opportunity sales cycles, you may want to set up the different stages within each cycle.</span></span>

## <a name="to-define-opportunity-sales-cycle-stages"></a><span data-ttu-id="eeb15-115">Определение этапов цикла продаж</span><span class="sxs-lookup"><span data-stu-id="eeb15-115">To define opportunity sales cycle stages</span></span>
1. <span data-ttu-id="eeb15-116">В окне **Циклы продаж** выберите цикл продаж, для которого требуется настроить этапы, и выберите действие **Этапы**.</span><span class="sxs-lookup"><span data-stu-id="eeb15-116">In the **Sales Cycles** window, select the opportunity sales cycle for which you want to set up stages, and then choose the **Stages** action.</span></span> <span data-ttu-id="eeb15-117">Откроется окно **Этапы цикла продажи**.</span><span class="sxs-lookup"><span data-stu-id="eeb15-117">The **Sales Cycle Stages** window opens.</span></span>
2. <span data-ttu-id="eeb15-118">Выберите действие **Создать**, чтобы создать новый этап цикла продаж.</span><span class="sxs-lookup"><span data-stu-id="eeb15-118">Choose the **New** action to enter a new stage in the sales cycle.</span></span>

<span data-ttu-id="eeb15-119">Повторите эти шаги для настройки нужного количества стадий цикла продаж.</span><span class="sxs-lookup"><span data-stu-id="eeb15-119">Repeat these steps to set up as many stages as you want within the sales cycle.</span></span>

## <a name="to-assign-stage-cycle-to-an-opportunity"></a><span data-ttu-id="eeb15-120">Назначение цикла продаж возможности</span><span class="sxs-lookup"><span data-stu-id="eeb15-120">To assign stage cycle to an opportunity</span></span>
<span data-ttu-id="eeb15-121">После добавления цикла продаж вы можете добавлять возможности продаж и назначать цикл продаж возможностям, устанавливая поле **Код цикла продаж**.</span><span class="sxs-lookup"><span data-stu-id="eeb15-121">After you add the opportunities stage cycle, you can start to add sales opportunities, and then assign the stage cycle to opportunities by setting the **Sales Cycle Code** field.</span></span> <span data-ttu-id="eeb15-122">Дополнительные сведения см. в разделе [Практическое руководство. Создание возможностей продаж](marketing-how-create-opportunities.md).</span><span class="sxs-lookup"><span data-stu-id="eeb15-122">For more information, see [How to: Create Sales Opportunities](marketing-how-create-opportunities.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="eeb15-123">См. также</span><span class="sxs-lookup"><span data-stu-id="eeb15-123">See Also</span></span>  
[<span data-ttu-id="eeb15-124">Обработка возможностей продаж</span><span class="sxs-lookup"><span data-stu-id="eeb15-124">Processing Sales Opportunities</span></span>](marketing-processing-sales-opportunities.md)  
[<span data-ttu-id="eeb15-125">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="eeb15-125">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="eeb15-126">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="eeb15-126">Working with Dynamics NAV</span></span>](ui-work-product.md)

