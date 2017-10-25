---
title: "Пошаговое руководство — создание прогнозов движения денежных средств с использованием финансовых отчетов"
description: "В этом пошаговом руководстве описывается использование финансовых отчетов для создания прогнозов движения денежных средств. Финансовые отчеты выполняют расчеты, которые невозможно выполнить непосредственно в диаграмме счетов движения денежных средств. В финансовых отчетах можно настроить промежуточные итоги для приема и распределения движения денежных средств. Эти подытоги могут включаться в новые итоговые значения, которые затем можно использовать при создании прогнозов движения денежных средств."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 72e2c2ab540ce53dc747792c3d1fa93ec87282f8
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="walkthrough-making-cash-flow-forecasts-by-using-account-schedules"></a><span data-ttu-id="26c20-106">Пошаговое руководство: создание прогнозов движения денежных средств с использованием финансовых отчетов</span><span class="sxs-lookup"><span data-stu-id="26c20-106">Walkthrough: Making Cash Flow Forecasts by Using Account Schedules</span></span>
<span data-ttu-id="26c20-107">В этом пошаговом руководстве описывается использование финансовых отчетов для создания прогнозов движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-107">This walkthrough describes how you can use account schedules to make cash flow forecasts.</span></span> <span data-ttu-id="26c20-108">Финансовые отчеты выполняют расчеты, которые невозможно выполнить непосредственно в диаграмме счетов движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-108">Account schedules perform calculations that cannot be done directly in the chart of cash flow accounts.</span></span> <span data-ttu-id="26c20-109">В финансовых отчетах можно настроить промежуточные итоги для приема и распределения движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-109">In the account schedules, you can set up subtotals for cash flow receipts and disbursements.</span></span> <span data-ttu-id="26c20-110">Эти подытоги могут включаться в новые итоговые значения, которые затем можно использовать при создании прогнозов движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-110">These subtotals can be included in new totals that can then be used in making cash flow forecasts.</span></span>  

## <a name="about-this-walkthrough"></a><span data-ttu-id="26c20-111">Об этом пошаговом руководстве</span><span class="sxs-lookup"><span data-stu-id="26c20-111">About This Walkthrough</span></span>  
<span data-ttu-id="26c20-112">В этом пошаговом руководстве описываются следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="26c20-112">This walkthrough describes the following tasks:</span></span>  

- <span data-ttu-id="26c20-113">Настройте новое название финансового отчета о движении денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-113">Setting up a new cash flow account schedule name.</span></span>  
- <span data-ttu-id="26c20-114">Настройка строк финансового отчета.</span><span class="sxs-lookup"><span data-stu-id="26c20-114">Setting up account schedule lines.</span></span>  
- <span data-ttu-id="26c20-115">Настройка новой раскладки столбцов.</span><span class="sxs-lookup"><span data-stu-id="26c20-115">Setting up a new column layout.</span></span>  
- <span data-ttu-id="26c20-116">Назначение раскладки столбцов финансовому отчету.</span><span class="sxs-lookup"><span data-stu-id="26c20-116">Assigning a column layout to an account schedule.</span></span>  
- <span data-ttu-id="26c20-117">Просмотр и печать прогноза движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-117">Viewing and printing the cash flow forecast.</span></span>  

### <a name="prerequisites"></a><span data-ttu-id="26c20-118">Предварительные требования</span><span class="sxs-lookup"><span data-stu-id="26c20-118">Prerequisites</span></span>  
<span data-ttu-id="26c20-119">Для выполнения данного пошагового руководства необходимо выполнить следующие действия.</span><span class="sxs-lookup"><span data-stu-id="26c20-119">To complete this walkthrough, you will need:</span></span>  

- <span data-ttu-id="26c20-120">Установлен [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="26c20-120">[!INCLUDE[d365fin](includes/d365fin_md.md)] installed.</span></span>  
- <span data-ttu-id="26c20-121">Строки журнала движения денежных средств регистрируются.</span><span class="sxs-lookup"><span data-stu-id="26c20-121">The cash flow worksheet lines are registered.</span></span>  

## <a name="roles"></a><span data-ttu-id="26c20-122">Роли</span><span class="sxs-lookup"><span data-stu-id="26c20-122">Roles</span></span>  
<span data-ttu-id="26c20-123">В этом пошаговом руководстве демонстрируются задачи, выполняемые исполнителем следующей роли:</span><span class="sxs-lookup"><span data-stu-id="26c20-123">This walkthrough demonstrates tasks that are performed by the following user role:</span></span>  

- <span data-ttu-id="26c20-124">Контроллер</span><span class="sxs-lookup"><span data-stu-id="26c20-124">Controller</span></span>  

## <a name="story"></a><span data-ttu-id="26c20-125">Сюжет</span><span class="sxs-lookup"><span data-stu-id="26c20-125">Story</span></span>  
<span data-ttu-id="26c20-126">Иван — контролер в CRONUS, который делает ежемесячные прогнозы движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-126">Ken is a controller at CRONUS who makes monthly cash flow forecasts.</span></span> <span data-ttu-id="26c20-127">Он включает в финансы, продажи, покупки, а также основные средства в прогнозе, а затем представляет в CFO Sara для рассмотрения.</span><span class="sxs-lookup"><span data-stu-id="26c20-127">He includes finance, sales, purchase, and fixed assets in the forecast, and then he presents it to CFO Sara for business insight.</span></span>  

## <a name="setting-up-a-new-account-schedule-name"></a><span data-ttu-id="26c20-128">Настройки нового названия финансового отчета</span><span class="sxs-lookup"><span data-stu-id="26c20-128">Setting Up a New Account Schedule Name</span></span>  
<span data-ttu-id="26c20-129">Финансовый отчет состоит из названия финансового отчета о движении денежных средств с серией строк и раскладкой столбцов.</span><span class="sxs-lookup"><span data-stu-id="26c20-129">An account schedule consists of a cash flow account schedule name with a series of lines and a column layout.</span></span>  

### <a name="to-set-up-a-new-account-schedule-name"></a><span data-ttu-id="26c20-130">Задание нового названия финансового отчета</span><span class="sxs-lookup"><span data-stu-id="26c20-130">To set up a new account schedule name</span></span>  

1.  <span data-ttu-id="26c20-131">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовые отчеты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="26c20-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Account Schedules**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="26c20-132">В окне **Названия финансовых отчетов** на выберите действие **Создать**, чтобы создать новое название графика счета движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-132">In the **Account Schedule Names** window, choose the **New** to create a new cash flow account schedule name.</span></span>  
3.  <span data-ttu-id="26c20-133">В поле **Имя** введите **Прогноз**.</span><span class="sxs-lookup"><span data-stu-id="26c20-133">In the **Name** field, enter **Forecast**.</span></span>  
4.  <span data-ttu-id="26c20-134">В поле **Описание** введите **Прогноз движения денежных средств**.</span><span class="sxs-lookup"><span data-stu-id="26c20-134">In the **Description** field, enter **Cash Flow Forecast**.</span></span>  
5.  <span data-ttu-id="26c20-135">Оставьте пустыми поля **Раскладка столбцов по умолчанию** и **Название аналитического отчета**.</span><span class="sxs-lookup"><span data-stu-id="26c20-135">Leave the **Default Column Layout** and **Analysis View Name** fields blank.</span></span>  

## <a name="setting-up-account-schedule-lines"></a><span data-ttu-id="26c20-136">Настройка строк финансового отчета</span><span class="sxs-lookup"><span data-stu-id="26c20-136">Setting Up Account Schedule Lines</span></span>  
<span data-ttu-id="26c20-137">После настройки названия финансового отчета Кен определяет каждую строку, которая отображается в финансовом отчете о движении денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-137">After an account schedule name is set up, Ken defines each line that appears in the cash flow account schedule.</span></span> <span data-ttu-id="26c20-138">Иван, определяет строки, которые могут отображаться в отчетах в дополнение к строкам, предназначенным только для вычислений.</span><span class="sxs-lookup"><span data-stu-id="26c20-138">Ken defines lines that can be shown in reports in addition to lines that are only for calculation purposes.</span></span>  

### <a name="to-set-up-account-schedule-lines"></a><span data-ttu-id="26c20-139">Процедура настройки строк финансового отчета</span><span class="sxs-lookup"><span data-stu-id="26c20-139">To set up account schedule lines</span></span>  

1.  <span data-ttu-id="26c20-140">В окне **Названия финансовых отчетов** выберите новое название созданного финансового отчета **Прогноз**.</span><span class="sxs-lookup"><span data-stu-id="26c20-140">In the **Account Schedule Names** window, select the new **Forecast** account schedule name that you have created.</span></span> <span data-ttu-id="26c20-141">На вкладке **Главная** в группе **Процесс** выберите **Изменение финансового отчета**.</span><span class="sxs-lookup"><span data-stu-id="26c20-141">On the **Home** tab, in the **Process** group, choose **Edit Account Schedule**.</span></span>  
2.  <span data-ttu-id="26c20-142">В окне **Финансовый отчет** заполните каждую строку, как показано в следующей таблице.</span><span class="sxs-lookup"><span data-stu-id="26c20-142">In the **Account Schedule** window, enter each line exactly as shown in the following table.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="26c20-143">С помощью функции **Вставить счета CF** можно быстро отмечать счета движения денежных средств в диаграмме счетов движения денежных средств и копировать их в строки финансового отчета.</span><span class="sxs-lookup"><span data-stu-id="26c20-143">Using the **Insert CF Accounts** function, you can quickly mark the cash flow accounts from the chart of cash flow accounts and copy them to account schedule lines.</span></span>  

    <span data-ttu-id="26c20-144">|Номер строки|Описание|Тип группировки|Группировка|Тип строки|Тип суммы|Показать|</span><span class="sxs-lookup"><span data-stu-id="26c20-144">|Row No.|Description|Totaling Type|Totaling|Row Type|Amount Type|Show|</span></span>  
    <span data-ttu-id="26c20-145">|-------|-----------|-------------|--------|--------|---  ------|----| |C10|Сумма|Оборот|Операции|Чистая сумма|Всегда|</span><span class="sxs-lookup"><span data-stu-id="26c20-145">|-------|-----------|-------------|--------|--------|---  ------|----| |C10|Amount|Net Change|Entries|Net Amount|Always|</span></span>  
    <span data-ttu-id="26c20-146">|C20|Сумма до даты|Сальдо на дату|Операции|Чистая сумма|Всегда|</span><span class="sxs-lookup"><span data-stu-id="26c20-146">|C20|Amount until Date|Balance at Date|Entries|Net Amount|Always|</span></span>  
    <span data-ttu-id="26c20-147">|C30|Весь фин. год|Весь фин. год|Операции|Чистая сумма|Всегда|</span><span class="sxs-lookup"><span data-stu-id="26c20-147">|C30|Entire Fiscal Year|Entire Fiscal Year|Entries|Net Amount|Always|</span></span>  

4.  <span data-ttu-id="26c20-148">Нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="26c20-148">Choose the **OK** button.</span></span>  

## <a name="assigning-the-column-layout-to-the-account-schedule-name"></a><span data-ttu-id="26c20-149">Назначение раскладки столбцов названию финансового отчета</span><span class="sxs-lookup"><span data-stu-id="26c20-149">Assigning the Column Layout to the Account Schedule Name</span></span>  
<span data-ttu-id="26c20-150">Иван теперь готов назначить шаблон столбцов названию финансового отчета.</span><span class="sxs-lookup"><span data-stu-id="26c20-150">Ken is now ready to assign the column layout to the account schedule name.</span></span>  

### <a name="to-assign-the-column-layout-to-the-account-schedule-name"></a><span data-ttu-id="26c20-151">Присвоение раскладки столбцов названию финансового отчета</span><span class="sxs-lookup"><span data-stu-id="26c20-151">To assign the column layout to the account schedule name</span></span>  

1.  <span data-ttu-id="26c20-152">В окне **Названия финансовых отчетов** выберите **Прогноз** в поле **Название**.</span><span class="sxs-lookup"><span data-stu-id="26c20-152">In the **Account Schedule Names** window, select **Forecast** in the **Name** field.</span></span>  
2.  <span data-ttu-id="26c20-153">В поле **Раскладка столбцов по умолчанию** выберите раскладку столбцов **Движение денежных средств** в качестве раскладки по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="26c20-153">In the **Default Column Layout** field, choose the column layout **Cash Flow** to assign as the default column layout.</span></span>  

### <a name="to-view-and-print-the-cash-flow-forecast"></a><span data-ttu-id="26c20-154">Просмотр и печать прогноза движения денежных средств</span><span class="sxs-lookup"><span data-stu-id="26c20-154">To view and print the cash flow forecast</span></span>  
1.  <span data-ttu-id="26c20-155">В окне **Названия финансовых отчетов** выберите действие **Обзор**, чтобы просмотреть прогноз движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-155">In the **Account Schedule Names** window, choose the **Overview** action to view the cash flow forecast.</span></span>  
2.  <span data-ttu-id="26c20-156">В окне **Просмотр финансового отчета** можно выбрать сумму, а затем просмотреть записи прогноза движения денежных средств, которые составляют сумму.</span><span class="sxs-lookup"><span data-stu-id="26c20-156">In the **Acc. Schedule Overview** window, you can select an amount and then view the cash flow forecast entries that make up the amount.</span></span> <span data-ttu-id="26c20-157">Кроме того, можно просмотреть используемую формулу для расчета суммы.</span><span class="sxs-lookup"><span data-stu-id="26c20-157">In addition, you can view the formula that is used to calculate the amount.</span></span> <span data-ttu-id="26c20-158">Можно также фильтровать суммы по дате и измерению.</span><span class="sxs-lookup"><span data-stu-id="26c20-158">You can also filter the amounts by date and dimension.</span></span>  
3.  <span data-ttu-id="26c20-159">Выберите действие **Печать** для печати прогноза движения денежных средств.</span><span class="sxs-lookup"><span data-stu-id="26c20-159">Choose the **Print** action to print the cash flow forecast.</span></span>  

## <a name="see-also"></a><span data-ttu-id="26c20-160">См. также</span><span class="sxs-lookup"><span data-stu-id="26c20-160">See Also</span></span>  
 <span data-ttu-id="26c20-161">[Практическое руководство. Работа с финансовыми отчетами](bi-how-work-account-schedule.md) </span><span class="sxs-lookup"><span data-stu-id="26c20-161">[How to: Work with Account Schedules](bi-how-work-account-schedule.md) </span></span>  
 [<span data-ttu-id="26c20-162">Пошаговые описания бизнес-процессов</span><span class="sxs-lookup"><span data-stu-id="26c20-162">Business Process Walkthroughs</span></span>](walkthrough-business-process-walkthroughs.md)  
 <span data-ttu-id="26c20-163">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="26c20-163">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

