---
title: "Практическое руководство. Работа с кодами GIFI в Канаде"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a><span data-ttu-id="37c6d-102">Практическое руководство. Работа с кодами GIFI в Канаде</span><span class="sxs-lookup"><span data-stu-id="37c6d-102">How to: Work With GIFI Codes in Canada</span></span>
<span data-ttu-id="37c6d-103">Финансовая информация может включать счета главной книги, отчеты, отчеты о прибылях и убытках, балансовые отчеты и включать фискальная счета главной книги, в отчете перечисляются, прибыли и убытках, балансовые отчеты и отчеты о нераспределенной прибыли.</span><span class="sxs-lookup"><span data-stu-id="37c6d-103">Fiscal information can include general ledger accounts, reports, income statements, balance sheets, and statements of retained earnings.</span></span> <span data-ttu-id="37c6d-104">Финансовая информация классифицируется с помощью кодов.</span><span class="sxs-lookup"><span data-stu-id="37c6d-104">Fiscal information is classified using codes.</span></span> <span data-ttu-id="37c6d-105">Использование кодов помогает правительству обрабатывать информацию, готовиться к электронной подаче документов и электронным образом проверять налоговую информацию.</span><span class="sxs-lookup"><span data-stu-id="37c6d-105">The use of codes helps the government to process information, prepare for electronic filing, and validate tax information electronically.</span></span> <span data-ttu-id="37c6d-106">Использование кодов также помогает статистическим организациям работать более эффективно, поскольку финансовая информация более доступна.</span><span class="sxs-lookup"><span data-stu-id="37c6d-106">The use of codes also helps statistical organizations to work more efficiently, as financial information is more readily available.</span></span> <span data-ttu-id="37c6d-107">Дополнительные сведения см. [на веб-сайте Canada Revenue Agency](http://www.cra-arc.gc.ca/).</span><span class="sxs-lookup"><span data-stu-id="37c6d-107">For more information, see the [Canada Revenue Agency website](http://www.cra-arc.gc.ca/).</span></span>

<span data-ttu-id="37c6d-108">Канадское налоговое агентство (Canada Revenue Agency) использует коды GIFI (General Index of Financial Information) для сбора, проверки и обработки финансовое и налоговой информации в электронном виде.</span><span class="sxs-lookup"><span data-stu-id="37c6d-108">The Canada Revenue Agency uses General Index of Financial Information (GIFI) codes to collect, validate, and process financial and tax information electronically.</span></span> <span data-ttu-id="37c6d-109">Рекомендуется назначать коды GIFI только счетам учета, чтобы все суммирование выполнялось вашим ПО для подготовки налоговой отчетности.</span><span class="sxs-lookup"><span data-stu-id="37c6d-109">It is a best practice to assign GIFI codes only to posting accounts, so that all totaling is done by your tax preparation software.</span></span>

<span data-ttu-id="37c6d-110">Если счет должен быть связан с кодом GIFI, он передается в налоговое агентство под этим кодом.</span><span class="sxs-lookup"><span data-stu-id="37c6d-110">When an account is associated with a GIFI code, it is reported to the revenue agency under that code.</span></span> <span data-ttu-id="37c6d-111">Несколько счетов могут иметь один и тот же код GIFI, но каждый счет может иметь только один код GIFI.</span><span class="sxs-lookup"><span data-stu-id="37c6d-111">Multiple accounts can all have the same GIFI code, but each account can have only one GIFI code.</span></span>

<span data-ttu-id="37c6d-112">Вы можете экспортировать сальдо по коду GIFI и сохранять экспортированный файл в Excel, что бывает полезно для переноса информации в ваше ПО по подготовке налоговой отчетности.</span><span class="sxs-lookup"><span data-stu-id="37c6d-112">You can export balance information by GIFI code and save the exported file in Excel, which is useful for transferring information to your tax preparation software.</span></span>

## <a name="to-set-up-gifi-codes"></a><span data-ttu-id="37c6d-113">Настройка кодов GIFI</span><span class="sxs-lookup"><span data-stu-id="37c6d-113">To set up GIFI codes</span></span>
<span data-ttu-id="37c6d-114">В Dynamics NAV необходимо настроить коды GIFI для счетов главной книги, отчетов, балансовых отчетов, отчетов о прибылях и убытках и отчетах о нераспределенной прибыли.</span><span class="sxs-lookup"><span data-stu-id="37c6d-114">In Dynamics NAV, you must set up GIFI codes for general ledger accounts, reports, balance sheets, income sheets, and statements of retained earnings.</span></span>

1. <span data-ttu-id="37c6d-115">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Коды GIFI**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="37c6d-115">In the top right corner, choose the **Search for Page or Report** icon, enter **GIFI Codes**, and then choose the related link.</span></span>
2. <span data-ttu-id="37c6d-116">В окне **Коды GIFI** выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="37c6d-116">In the **GIFI Codes** window, choose the **New** action.</span></span>
3. <span data-ttu-id="37c6d-117">Настройте коды GIFI, заполнив поля.</span><span class="sxs-lookup"><span data-stu-id="37c6d-117">Set up GIFI codes by filling the fields.</span></span> <span data-ttu-id="37c6d-118">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="37c6d-118">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-associate-gifi-codes-with-gl-accounts"></a><span data-ttu-id="37c6d-119">Связывание кодов GIFI со счетами ГК</span><span class="sxs-lookup"><span data-stu-id="37c6d-119">To associate GIFI codes with G/L accounts</span></span>
<span data-ttu-id="37c6d-120">Для подачи финансовой отчетности по коду GIFI каждый код GIFI долежн быть связан с соответствующими счетами в плане счетов.</span><span class="sxs-lookup"><span data-stu-id="37c6d-120">To report financial information by GIFI code, each GIFI code must be associated with the appropriate accounts in the chart of accounts.</span></span>

1. <span data-ttu-id="37c6d-121">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **План счетов**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="37c6d-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="37c6d-122">Выберите соответствующий счет главной книги, а затем выберите действие **Изменить**.</span><span class="sxs-lookup"><span data-stu-id="37c6d-122">Select a relevant general ledger account, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="37c6d-123">На экспресс-вкладке **Учет затрат** в поле **Код GIFI** выберите подходящий код GIFI.</span><span class="sxs-lookup"><span data-stu-id="37c6d-123">On the **Cost Accounting** FastTab, in the **GIFI Code** field, select an appropriate GIFI code.</span></span>

## <a name="to-view-account-balances-using-the-gifi-code-report"></a><span data-ttu-id="37c6d-124">Просмотр сальдо счетов с помощью отчета по кодам GIFI</span><span class="sxs-lookup"><span data-stu-id="37c6d-124">To view account balances using the GIFI code report</span></span>
<span data-ttu-id="37c6d-125">Можно просматривать сальдо счетов по кодам GIFI, используя отчет **Сальдо счетов по кодам GIFI**.</span><span class="sxs-lookup"><span data-stu-id="37c6d-125">You can review your account balances by GIFI code by using the **Account Balances by GIFI Code** report.</span></span>

1. <span data-ttu-id="37c6d-126">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Сальдо счетов по кодам GIFI**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="37c6d-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Account Balances by GIFI Code**, and then choose the related link.</span></span>
2. <span data-ttu-id="37c6d-127">Заполните поля, чтобы указать, что должно быть включено в отчет.</span><span class="sxs-lookup"><span data-stu-id="37c6d-127">Specify what to include in the report by filling the fields.</span></span> <span data-ttu-id="37c6d-128">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="37c6d-128">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="37c6d-129">Нажмите кнопку **Печать** или **Просмотр**.</span><span class="sxs-lookup"><span data-stu-id="37c6d-129">Choose the **Print** or the **Preview** button.</span></span>

## <a name="to-export-balance-information-using-gifi-codes"></a><span data-ttu-id="37c6d-130">Экспорт сведения о сальдо с помощью кодов GIFI</span><span class="sxs-lookup"><span data-stu-id="37c6d-130">To export balance information using GIFI codes</span></span>
<span data-ttu-id="37c6d-131">Вы можете экспортировать сведения о сальдо с помощью кодов GIFI и сохранить экспортированный файл в формате Excel.</span><span class="sxs-lookup"><span data-stu-id="37c6d-131">You can export balance information using GIFI codes and save the exported file in Excel.</span></span> <span data-ttu-id="37c6d-132">Этот файл можно изменять, сохранять или удалять.</span><span class="sxs-lookup"><span data-stu-id="37c6d-132">You can modify, save, or delete the file.</span></span> <span data-ttu-id="37c6d-133">Файл можно использовать для передачи информации в ПО для подготовки налоговой отчетности.</span><span class="sxs-lookup"><span data-stu-id="37c6d-133">You can use the file to transfer information to your tax preparation software.</span></span>

1. <span data-ttu-id="37c6d-134">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Экспорт данных GIFI в Excel**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="37c6d-134">In the top right corner, choose the **Search for Page or Report** icon, enter **Export GIFI Info. to Excel**, and then choose the related link.</span></span>
2. <span data-ttu-id="37c6d-135">Заполните поля, чтобы указать, какие данные должны быть экспортированы в Excel.</span><span class="sxs-lookup"><span data-stu-id="37c6d-135">Specify what to export to Excel by filling the fields.</span></span> <span data-ttu-id="37c6d-136">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="37c6d-136">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="37c6d-137">Выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="37c6d-137">Choose the **OK** button.</span></span>

<span data-ttu-id="37c6d-138">**Примечание**. Файл Excel имеет следующие характеристики:</span><span class="sxs-lookup"><span data-stu-id="37c6d-138">**Note:** The Excel file has the following characteristics:</span></span>

* <span data-ttu-id="37c6d-139">Сальдо округлено до ближайшего процента, но значение ячейки сохраняет тот же процент, что и в главной книге.</span><span class="sxs-lookup"><span data-stu-id="37c6d-139">The balance is rounded to the nearest percentage, but the cell value maintains the same percentage as it does in the general ledger.</span></span>

* <span data-ttu-id="37c6d-140">Отрицательные числа представлены в виде положительного числа в скобках.</span><span class="sxs-lookup"><span data-stu-id="37c6d-140">Negative numbers are represented as positive number in brackets.</span></span> <span data-ttu-id="37c6d-141">Соответственно -123 представлено как (123).</span><span class="sxs-lookup"><span data-stu-id="37c6d-141">Accordingly, -123 is represented as (123).</span></span>

## <a name="see-also"></a><span data-ttu-id="37c6d-142">См. также</span><span class="sxs-lookup"><span data-stu-id="37c6d-142">See Also</span></span>
<span data-ttu-id="37c6d-143">[Финансы](finance-setup.md) </span><span class="sxs-lookup"><span data-stu-id="37c6d-143">[Finance](finance-setup.md) </span></span>  
[<span data-ttu-id="37c6d-144">Настройка основных финансовых процессов</span><span class="sxs-lookup"><span data-stu-id="37c6d-144">Set Up Core Financial Processes</span></span>](finance-setup-setup-finance-setup.md)

