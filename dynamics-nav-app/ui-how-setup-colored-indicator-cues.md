---
title: "Практическое руководство. Настройка цветного индикатора в очередях"
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
ms.openlocfilehash: 38cd904d0cf22374eac430d035e6ea6d205bcab8
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---
    
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a><span data-ttu-id="69ee5-102">Практическое руководство. Настройка цветного индикатора в очередях</span><span class="sxs-lookup"><span data-stu-id="69ee5-102">How to: Set Up a Colored Indicator on Cues</span></span>
<span data-ttu-id="69ee5-103">Вы можете настроить очереди, отображаемые на странице **Главная**, чтобы включить индикатор, меняющий цвет в зависимости от значений данных в очередях.</span><span class="sxs-lookup"><span data-stu-id="69ee5-103">You can set up Cues that appear on the **Home** page to include an indicator that changes color based on the data values in the Cues.</span></span> 

<span data-ttu-id="69ee5-104">Индикатор отображается как цветная полоса вдоль верхней границы плитки очереди.</span><span class="sxs-lookup"><span data-stu-id="69ee5-104">The indicator appears as a colored bar along the top border of the Cue tile.</span></span> <span data-ttu-id="69ee5-105">Предоставляет визуальный сигнал статуса операций очереди, который может указывать на благоприятные или неблагоприятные условия и необходимость действий пользователя.</span><span class="sxs-lookup"><span data-stu-id="69ee5-105">It provides a visual signal of the status of the Cue's activity, which can indicate favorable or unfavorable conditions to prompt the user to take action.</span></span> <span data-ttu-id="69ee5-106">Например, если в очереди отображаются текущие счета продажи, можно настроить, чтобы индикатор отображался зеленым (положительный), если общее число текущих счетов продажи меньше 10, и красным (отрицательный), если это число больше 20.</span><span class="sxs-lookup"><span data-stu-id="69ee5-106">For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favorable) when total number of ongoing sales invoices is below 10, and appears red (unfavorable) when the total is greater than 20.</span></span>

<span data-ttu-id="69ee5-107">В окне **Настройка очереди** можно настроить индикаторы для всех очередей, доступных в базе данных организации.</span><span class="sxs-lookup"><span data-stu-id="69ee5-107">From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.</span></span>

<span data-ttu-id="69ee5-108">Для настройки индикатора нужно задать до двух пороговых значений, определяющих три диапазона значений данных (низкий, средний и высокий), к которым можно применить другой цвет (или стиль).</span><span class="sxs-lookup"><span data-stu-id="69ee5-108">To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different color (or style).</span></span>

## <a name="to-set-up-colored-indicators-on-cues"></a><span data-ttu-id="69ee5-109">Настройка цветных индикаторов в очередях</span><span class="sxs-lookup"><span data-stu-id="69ee5-109">To set up colored indicators on Cues</span></span>
1. <span data-ttu-id="69ee5-110">В разделе **Действия** на странице **Главная** выберите **Настроить очереди**.</span><span class="sxs-lookup"><span data-stu-id="69ee5-110">Under **Activities** on your **Home** page, choose **Set Up Cues**.</span></span>  
<span data-ttu-id="69ee5-111">Откроется окно **Настройка очереди**.</span><span class="sxs-lookup"><span data-stu-id="69ee5-111">The **Cue Setup** window appears.</span></span> <span data-ttu-id="69ee5-112">В окне перечисляются индикаторы, которые в настоящее время настроены в очередях.</span><span class="sxs-lookup"><span data-stu-id="69ee5-112">The window lists the indicators that are currently setup up on Cues.</span></span>
2. <span data-ttu-id="69ee5-113">Чтобы изменить индикатор, измените поля и, например, значения различных порогов.</span><span class="sxs-lookup"><span data-stu-id="69ee5-113">To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.</span></span>  

<span data-ttu-id="69ee5-114">В следующей таблице перечислены цвета, соответствующие параметрам полей **Стиль низкого диапазона**, **Стиль среднего диапазона** и **Стиль высокого диапазона**.</span><span class="sxs-lookup"><span data-stu-id="69ee5-114">The following table lists the colors that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.</span></span>

|<span data-ttu-id="69ee5-115">Параметр</span><span class="sxs-lookup"><span data-stu-id="69ee5-115">Option</span></span>|<span data-ttu-id="69ee5-116">Цвет</span><span class="sxs-lookup"><span data-stu-id="69ee5-116">Color</span></span>|
|------|-----|
|<span data-ttu-id="69ee5-117">**Нет**</span><span class="sxs-lookup"><span data-stu-id="69ee5-117">**None**</span></span>|<span data-ttu-id="69ee5-118">Без цвета (цвет плитки очереди</span><span class="sxs-lookup"><span data-stu-id="69ee5-118">No color (same color as the Cue tile</span></span>|
|<span data-ttu-id="69ee5-119">**Положительный**</span><span class="sxs-lookup"><span data-stu-id="69ee5-119">**Favorable**</span></span>|<span data-ttu-id="69ee5-120">Зеленый</span><span class="sxs-lookup"><span data-stu-id="69ee5-120">Green</span></span>|
|<span data-ttu-id="69ee5-121">**Отрицательный**</span><span class="sxs-lookup"><span data-stu-id="69ee5-121">**Unfavorable**</span></span>|<span data-ttu-id="69ee5-122">Красный</span><span class="sxs-lookup"><span data-stu-id="69ee5-122">Red</span></span>|
|<span data-ttu-id="69ee5-123">**Нераспознанные**</span><span class="sxs-lookup"><span data-stu-id="69ee5-123">**Ambiguous**</span></span>|<span data-ttu-id="69ee5-124">Желтый</span><span class="sxs-lookup"><span data-stu-id="69ee5-124">Yellow</span></span>|
|<span data-ttu-id="69ee5-125">**Подчиненный**</span><span class="sxs-lookup"><span data-stu-id="69ee5-125">**Subordinate**</span></span>|<span data-ttu-id="69ee5-126">Серый</span><span class="sxs-lookup"><span data-stu-id="69ee5-126">Gray</span></span>|

## <a name="see-also"></a><span data-ttu-id="69ee5-127">См. также</span><span class="sxs-lookup"><span data-stu-id="69ee5-127">See Also</span></span>
[<span data-ttu-id="69ee5-128">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="69ee5-128">Work with Dynamics NAV</span></span>](ui-work-product.md)


