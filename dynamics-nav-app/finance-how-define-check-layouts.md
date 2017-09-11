---
title: "Практическое руководство. Определение макетов платежных документов"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 50d0b1ac6250d4f9bfd1734b06be9a9621f6f233
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-define-check-layouts"></a><span data-ttu-id="3759c-102">Практическое руководство. Определение макетов платежных документов</span><span class="sxs-lookup"><span data-stu-id="3759c-102">How to: Define Check Layouts</span></span>

<span data-ttu-id="3759c-103">Вы можете разработать платежные документы в соответствии со стандартами, установленными местными органами власти.</span><span class="sxs-lookup"><span data-stu-id="3759c-103">You can design your checks to conform with the standards set by the local authorities.</span></span> <span data-ttu-id="3759c-104">Изображения платежных документов можно печатать на английском, французском или испанском языке.</span><span class="sxs-lookup"><span data-stu-id="3759c-104">Check images can be printed in English, French, or Spanish.</span></span>

<span data-ttu-id="3759c-105">Платежные документы разрабатываются для печати в форматах изображений платежных документов США и Канады в формате "платежный документ-бланк-платежный документ" или "бланк-бланк-платежный документ".</span><span class="sxs-lookup"><span data-stu-id="3759c-105">Checks are designed to print in both the United States and Canadian check image formats in either a check-stub-check format or a stub-stub-check format.</span></span>

## <a name="to-define-check-layouts"></a><span data-ttu-id="3759c-106">Определение макетов платежных документов</span><span class="sxs-lookup"><span data-stu-id="3759c-106">To define check layouts</span></span>
1. <span data-ttu-id="3759c-107">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Выбор отчета - банковский счет**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3759c-107">In the top right corner, choose the **Search for Page or Report** icon, enter **Report Selections Bank Account**, and choose the related link.</span></span>
2. <span data-ttu-id="3759c-108">В окне **Выбор отчета - банковский счет**</span><span class="sxs-lookup"><span data-stu-id="3759c-108">In the **Report Selection - Bank Acc.**</span></span> <span data-ttu-id="3759c-109">в поле **Использование** выберите **Платежный документ**.</span><span class="sxs-lookup"><span data-stu-id="3759c-109">window, in the **Usage** field, select **Check**.</span></span>
3. <span data-ttu-id="3759c-110">Выберите один из следующих кодов отчетов.</span><span class="sxs-lookup"><span data-stu-id="3759c-110">Select one of the following report IDs.</span></span>

| <span data-ttu-id="3759c-111">Код отчета</span><span class="sxs-lookup"><span data-stu-id="3759c-111">Report ID</span></span>   | <span data-ttu-id="3759c-112">Название отчета</span><span class="sxs-lookup"><span data-stu-id="3759c-112">Report Name</span></span>   | <span data-ttu-id="3759c-113">Описание</span><span class="sxs-lookup"><span data-stu-id="3759c-113">Description</span></span> |
|-------------|---------------|-------------|
|<span data-ttu-id="3759c-114">1401</span><span class="sxs-lookup"><span data-stu-id="3759c-114">1401</span></span>|<span data-ttu-id="3759c-115">Платежный документ</span><span class="sxs-lookup"><span data-stu-id="3759c-115">Check</span></span>|<span data-ttu-id="3759c-116">Это отчет по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="3759c-116">This is the default report.</span></span>|
|<span data-ttu-id="3759c-117">10401</span><span class="sxs-lookup"><span data-stu-id="3759c-117">10401</span></span>|<span data-ttu-id="3759c-118">Платежный документ (Бланк/Бланк/Платежный документ)</span><span class="sxs-lookup"><span data-stu-id="3759c-118">Check (Stub/Stub/Check)</span></span>|<span data-ttu-id="3759c-119">Этот отчет предназначен для печати платежных документов в формате "бланк/бланк/платежный документ".</span><span class="sxs-lookup"><span data-stu-id="3759c-119">This report is designed to print checks in a stub/stub/check format.</span></span>|
|<span data-ttu-id="3759c-120">10411</span><span class="sxs-lookup"><span data-stu-id="3759c-120">10411</span></span>|<span data-ttu-id="3759c-121">Платежный документ (Бланк/Платежный документ/Бланк)</span><span class="sxs-lookup"><span data-stu-id="3759c-121">Check (Stub/Check/Stub)</span></span>|<span data-ttu-id="3759c-122">Этот отчет предназначен для печати платежных документов в формате "платежный документ/бланк/платежный документ".</span><span class="sxs-lookup"><span data-stu-id="3759c-122">This report is designed to print checks in a check/stub/check format.</span></span>|

<span data-ttu-id="3759c-123">После настройки макетов платежных документов их можно распечатывать из окна **Журнал платежей**.</span><span class="sxs-lookup"><span data-stu-id="3759c-123">When you have set up check layouts, you can print checks from the **Payment Journal** window.</span></span> <span data-ttu-id="3759c-124">Дополнительные сведения см. в разделе [Работа с платежными документами](payables-how-work-checks.md).</span><span class="sxs-lookup"><span data-stu-id="3759c-124">For more information, see [Work With Checks](payables-how-work-checks.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="3759c-125">См. также</span><span class="sxs-lookup"><span data-stu-id="3759c-125">See Also</span></span>
[<span data-ttu-id="3759c-126">Управление кредиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="3759c-126">Manage Payables</span></span>](payables-manage-payables.md)  
<span data-ttu-id="3759c-127">[Управление банковскими счетами](bank-manage-bank-accounts.md) </span><span class="sxs-lookup"><span data-stu-id="3759c-127">[Manage Bank Accounts](bank-manage-bank-accounts.md) </span></span>  
[<span data-ttu-id="3759c-128">Выполнение процессов завершения периода</span><span class="sxs-lookup"><span data-stu-id="3759c-128">Completing Period-End Processes</span></span>](year-how-complete-period-end-processes.md)  
[<span data-ttu-id="3759c-129">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="3759c-129">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="3759c-130">Функции, доступные в различных деловых областях</span><span class="sxs-lookup"><span data-stu-id="3759c-130">Across Business Areas</span></span>](ui-across-business-areas.md)

