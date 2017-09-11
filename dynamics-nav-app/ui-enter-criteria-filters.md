---
title: "Ввод критериев в фильтрах"
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
ms.openlocfilehash: df386e1195db385ee053b69fec0f5082d8df4116
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---

# <a name="entering-criteria-in-filters"></a><span data-ttu-id="8de10-102">Ввод критериев в фильтрах</span><span class="sxs-lookup"><span data-stu-id="8de10-102">Entering Criteria in Filters</span></span>
<span data-ttu-id="8de10-103">Если необходимо выполнить поиск данных, таких как название клиента, адреса или товарные группы, вводятся критерии.</span><span class="sxs-lookup"><span data-stu-id="8de10-103">When you want to search for data, such as customer names, addresses, or product groups, you enter criteria.</span></span> <span data-ttu-id="8de10-104">В критериях поиска можно использовать все цифры и буквы, которые вводятся в соответствующие поля.</span><span class="sxs-lookup"><span data-stu-id="8de10-104">In search criteria you can use all the numbers and letters that you normally use in the specific field.</span></span> <span data-ttu-id="8de10-105">Кроме того, для дополнительной фильтрации результатов можно использовать специальные символы.</span><span class="sxs-lookup"><span data-stu-id="8de10-105">In addition, you can use special symbols to further filter the results.</span></span>

## <a name="searching-using-the-quick-filter"></a><span data-ttu-id="8de10-106">Поиск с помощью экспресс-фильтра</span><span class="sxs-lookup"><span data-stu-id="8de10-106">Searching using the Quick Filter</span></span>
<span data-ttu-id="8de10-107">Вы можете добавить фильтры на все страницы с помощью экспресс-фильтра.</span><span class="sxs-lookup"><span data-stu-id="8de10-107">You can add filters to all pages by using the Quick Filter.</span></span> <span data-ttu-id="8de10-108">Экспресс-фильтр включается при выборе значка лупы в правом верхнем углу страницы.</span><span class="sxs-lookup"><span data-stu-id="8de10-108">The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page.</span></span> <span data-ttu-id="8de10-109">Данный тип фильтра используется для быстрого ввода критериев.</span><span class="sxs-lookup"><span data-stu-id="8de10-109">This filtering type is used for a fast entry of criteria.</span></span>

<span data-ttu-id="8de10-110">**Внимание**. Экспресс-фильтр обеспечивает удобный доступ к фильтруемым данным путем ввода простого текста, а также множество вариантов указания критериев поиска.</span><span class="sxs-lookup"><span data-stu-id="8de10-110">**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options.</span></span> <span data-ttu-id="8de10-111">В зависимости от того, введен ли обычный текст или текст с символами, поведение экспресс-фильтра отличается.</span><span class="sxs-lookup"><span data-stu-id="8de10-111">Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.</span></span>  
- <span data-ttu-id="8de10-112">Если в критериях поиска ввести обычный текст, критерии поиска будут рассматриваться без учета регистра и будет выполняться поиск определенного текста.</span><span class="sxs-lookup"><span data-stu-id="8de10-112">If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.</span></span>  
- <span data-ttu-id="8de10-113">Если в критериях поиска ввести тест с символами, критерии поиска будут рассматриваться с учетом регистра и будет выполняться поиск точного текста.</span><span class="sxs-lookup"><span data-stu-id="8de10-113">If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.</span></span>

### <a name="quick-filter-criteria"></a><span data-ttu-id="8de10-114">Критерии экспресс-фильтра</span><span class="sxs-lookup"><span data-stu-id="8de10-114">Quick filter criteria</span></span>
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH><span data-ttu-id="8de10-115">Критерии поиска</span><span class="sxs-lookup"><span data-stu-id="8de10-115">Search Criteria</span></span></TH>
    <TH><span data-ttu-id="8de10-116">Интерпретируется как…</span><span class="sxs-lookup"><span data-stu-id="8de10-116">Interpreted as...</span></span></TH>
    <TH><span data-ttu-id="8de10-117">Возвращает…</span><span class="sxs-lookup"><span data-stu-id="8de10-117">Returns...</span></span></TH>
  </TR>
  <TR>
    <TD><span data-ttu-id="8de10-118">>man</span><span class="sxs-lookup"><span data-stu-id="8de10-118">>man</span></span></TD>
    <TD><span data-ttu-id="8de10-119">@*man*</span><span class="sxs-lookup"><span data-stu-id="8de10-119">@*man*</span></span></TD>
    <TD><span data-ttu-id="8de10-120">Все записи, содержащие текст man, без учета регистра.</span><span class="sxs-lookup"><span data-stu-id="8de10-120">All records that contain the text man and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8de10-121">>se</span><span class="sxs-lookup"><span data-stu-id="8de10-121">>se</span></span></TD>
    <TD><span data-ttu-id="8de10-122">@*se*</span><span class="sxs-lookup"><span data-stu-id="8de10-122">@*se*</span></span></TD>
    <TD><span data-ttu-id="8de10-123">Все записи, содержащие текст se, без учета регистра.</span><span class="sxs-lookup"><span data-stu-id="8de10-123">All records that contain the text se and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8de10-124">>Man*</span><span class="sxs-lookup"><span data-stu-id="8de10-124">>Man*</span></span></TD>
    <TD><span data-ttu-id="8de10-125">Начинается с Man с учетом регистра.</span><span class="sxs-lookup"><span data-stu-id="8de10-125">Starts with Man and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="8de10-126">Все записи, которые начинаются с текста Man.</span><span class="sxs-lookup"><span data-stu-id="8de10-126">All records that start with the text Man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8de10-127">'man'</span><span class="sxs-lookup"><span data-stu-id="8de10-127">'man'</span></span></TD>
    <TD><span data-ttu-id="8de10-128">Точный текст с учетом регистра.</span><span class="sxs-lookup"><span data-stu-id="8de10-128">An exact text and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="8de10-129">Все записи, которые в точности соответствуют man.</span><span class="sxs-lookup"><span data-stu-id="8de10-129">All records that match man exactly.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8de10-130">@*man</span><span class="sxs-lookup"><span data-stu-id="8de10-130">@*man</span></span></TD>
    <TD><span data-ttu-id="8de10-131">Заканчивается на man без учета регистра.</span><span class="sxs-lookup"><span data-stu-id="8de10-131">Ends with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="8de10-132">Все записи, которые заканчиваются на man.</span><span class="sxs-lookup"><span data-stu-id="8de10-132">All records that end with man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8de10-133">@man*</span><span class="sxs-lookup"><span data-stu-id="8de10-133">@man*</span></span></TD>
    <TD><span data-ttu-id="8de10-134">Начинается на man без учета регистра.</span><span class="sxs-lookup"><span data-stu-id="8de10-134">Starts with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="8de10-135">Все записи, которые начинаются на man.</span><span class="sxs-lookup"><span data-stu-id="8de10-135">All records that start with man.</span></span></TD>
  </TR>
</TABLE>

<span data-ttu-id="8de10-136">**Примечание**. Нельзя использовать подстановочные символы при фильтрации в полях перечислений, например в поле **Статус** заказов на продажу.</span><span class="sxs-lookup"><span data-stu-id="8de10-136">**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders.</span></span> <span data-ttu-id="8de10-137">Чтобы ввести фильтр для данного типа поля, можно ввести в качестве параметра фильтра числовое значение.</span><span class="sxs-lookup"><span data-stu-id="8de10-137">To enter a filter for this type of field, you can enter the numeric value as a filtering parameter.</span></span> <span data-ttu-id="8de10-138">Например, в поле **Статус** в заказе на продажу, которое имеет значения **Открыть**, **Выпущено**, **Ожидает утверждения** и **Ожидает предоплаты**, используйте значения **0**, **1**, **2**, и **3** для фильтрации этих параметров.</span><span class="sxs-lookup"><span data-stu-id="8de10-138">For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.</span></span>  

## <a name="see-also"></a><span data-ttu-id="8de10-139">См. также</span><span class="sxs-lookup"><span data-stu-id="8de10-139">See Also</span></span>
[<span data-ttu-id="8de10-140">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="8de10-140">Work with Dynamics NAV</span></span>](ui-work-product.md)

