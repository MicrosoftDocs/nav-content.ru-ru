---
title: "Финансовые отчеты"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 60425a242ddfc3459601e343fcc4b5b19363c656
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---

# <a name="account-schedules"></a><span data-ttu-id="a549f-102">Финансовые отчеты</span><span class="sxs-lookup"><span data-stu-id="a549f-102">Account Schedules</span></span>
<span data-ttu-id="a549f-103">Финансовые отчеты можно использовать для глубокого анализа финансовых данных.</span><span class="sxs-lookup"><span data-stu-id="a549f-103">With account schedules, you can get detailed insights into your financial data.</span></span> <span data-ttu-id="a549f-104">Вы можете настроить различные макеты, чтобы определить информацию, которая должна извлекаться из плана счетов. В плане счетов хранятся ваши финансовые данные, но иногда вам нужно получить такое представление своих данных, которого не возможно добиться от плана счетов.</span><span class="sxs-lookup"><span data-stu-id="a549f-104">You can set up various layouts to define the information that you want to extract from the chart of accounts The chart of accounts stores your financial data, but sometimes you want to get a view on your data that the chart of accounts cannot really show.</span></span> <span data-ttu-id="a549f-105">В этом случае вы используете финансовые отчеты для анализа цифр на счетах главной книги и для сравнения операций главной книги с операциями бюджета главной книги.</span><span class="sxs-lookup"><span data-stu-id="a549f-105">So you use account schedules to analyze figures in general ledger accounts and to compare general ledger entries with general ledger budget entries.</span></span>
<span data-ttu-id="a549f-106">Например, вам нужно рассчитать подытоги для групп счетов, чтобы включить эти подытоги в новые итоговые значения и т. д.</span><span class="sxs-lookup"><span data-stu-id="a549f-106">For example, you want to calculate subtotals for groups of accounts, and you want to include these subtotals in new totals, and so on.</span></span>
<span data-ttu-id="a549f-107">В Dynamics NAV имеются примеры финансовых отчетов, с помощью которых можно сформировать диаграммы на начальной странице.</span><span class="sxs-lookup"><span data-stu-id="a549f-107">Dynamics NAV includes sample account schedules that are used to generate the charts on your Home page.</span></span> <span data-ttu-id="a549f-108">Кроме того, вы можете создать финансовые отчеты для вычисления размеров прибыли по таким измерениям, как подразделения или группы клиентов.</span><span class="sxs-lookup"><span data-stu-id="a549f-108">You can also create account schedules to calculate profit margins on such dimensions as departments or customer groups.</span></span>  

<span data-ttu-id="a549f-109">Настройка финансовых отчетов требует понимания финансовых данных в плане счетов.</span><span class="sxs-lookup"><span data-stu-id="a549f-109">Setting up account schedules requires an understanding of the financial data in the chart of accounts.</span></span>
<span data-ttu-id="a549f-110">Например, можно рассматривать операции главной книги как процент от бюджетных операций.</span><span class="sxs-lookup"><span data-stu-id="a549f-110">For example, you can view general ledger entries as percentages of budget entries.</span></span>
<span data-ttu-id="a549f-111">Вы можете использовать один из макетов по умолчанию для своего финансового отчета или настроить собственные строки и столбцы, чтобы решить, какие именно показатели вы хотите сравнивать и как.</span><span class="sxs-lookup"><span data-stu-id="a549f-111">You can use one of the default layouts for your account schedule, or you can set up your own rows and columns so that you can decide exactly which figures you wish to compare and how.</span></span>
<span data-ttu-id="a549f-112">Это означает, что можно создать столько пользовательских финансовых отчетов, сколько нужно.</span><span class="sxs-lookup"><span data-stu-id="a549f-112">This means that you can create as many customized financial statements as you want.</span></span> <span data-ttu-id="a549f-113">Для настройки финансовых отчетов используется окно **Финансовый отчет**.</span><span class="sxs-lookup"><span data-stu-id="a549f-113">You use the **Account Schedule** window to set up account schedules.</span></span>  

## <a name="account-categories-and-account-schedules"></a><span data-ttu-id="a549f-114">Категории счетов и финансовые отчеты</span><span class="sxs-lookup"><span data-stu-id="a549f-114">Account Categories and Account Schedules</span></span>
<span data-ttu-id="a549f-115">Дл изменения макетов финансовых отчетов можно использовать категории счетов.</span><span class="sxs-lookup"><span data-stu-id="a549f-115">You can use account categories to change the layout of your financial statements.</span></span> <span data-ttu-id="a549f-116">Если в окне **Категории счетов ГК** настроены категории счетов и вы выбрали действие **Создать финансовые отчеты**, соответствующие финансовые отчеты для основных финансовых отчетов будут обновлены.</span><span class="sxs-lookup"><span data-stu-id="a549f-116">When you have set up your account categories in the **G/L Account Categories** window, and you choose the **Generate Account Schedules** action, the underlying account schedules for the core financial reports are updated.</span></span> <span data-ttu-id="a549f-117">При следующем выполнении один из этих отчетов, например балансового отчета, будут добавлены новые итоговые значения и вложенные операции на основании внесенных изменений.</span><span class="sxs-lookup"><span data-stu-id="a549f-117">the next time you run one of these reports, such as the balance statement, new totals and subentries are added, based on your changes.</span></span> <span data-ttu-id="a549f-118">Дополнительные сведения см. в разделе [Главная книга и план счетов](finance-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="a549f-118">For more information, see [The General Ledger and the Chart of Accounts](finance-general-ledger.md).</span></span>    
## <a name="see-also"></a><span data-ttu-id="a549f-119">См. также</span><span class="sxs-lookup"><span data-stu-id="a549f-119">See Also</span></span>
[<span data-ttu-id="a549f-120">Финансы</span><span class="sxs-lookup"><span data-stu-id="a549f-120">Finance</span></span>](finance.md)  
[<span data-ttu-id="a549f-121">Настройка финансов</span><span class="sxs-lookup"><span data-stu-id="a549f-121">Set Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="a549f-122">Главная книга и план счетов</span><span class="sxs-lookup"><span data-stu-id="a549f-122">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  

