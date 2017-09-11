---
title: "Закрытие периодов"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a><span data-ttu-id="b024b-102">Закрытие периодов</span><span class="sxs-lookup"><span data-stu-id="b024b-102">Close Periods</span></span>
<span data-ttu-id="b024b-103">Приложение не требует принудительного закрытия периодов, однако предусмотрено множество действий на конец периода (месяца), которые можно выполнять в приложении, если это необходимо.</span><span class="sxs-lookup"><span data-stu-id="b024b-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span></span> <span data-ttu-id="b024b-104">В этом разделе приведет обзор этих процессов и действий, которые могут потребоваться для вашей организации.</span><span class="sxs-lookup"><span data-stu-id="b024b-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span></span>

## <a name="general-ledger"></a><span data-ttu-id="b024b-105">Главная книга</span><span class="sxs-lookup"><span data-stu-id="b024b-105">General Ledger</span></span>
* <span data-ttu-id="b024b-106">Укажите системные и пользовательские периоды учета.</span><span class="sxs-lookup"><span data-stu-id="b024b-106">Specify system-wide and user-specific posting period.</span></span>

    <span data-ttu-id="b024b-107">Они определяют даты, между которыми возможен учет.</span><span class="sxs-lookup"><span data-stu-id="b024b-107">This specifies the dates between which postings are allowed.</span></span> <span data-ttu-id="b024b-108">В зависимости от потребностей бизнеса можно ограничить пользовательские диапазоны дат учета началом процесса завершения периода или более поздней датой в конце периода.</span><span class="sxs-lookup"><span data-stu-id="b024b-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span></span> <span data-ttu-id="b024b-109">Дополнительные сведения см. в разделе [Практическое руководство. Определение периодов учета](finance-setup-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="b024b-109">For more information, see [How to: Specify Posting Periods](finance-setup-how-specify-posting-periods.md).</span></span>
* <span data-ttu-id="b024b-110">Внесите все необходимые корректировки в ГК.</span><span class="sxs-lookup"><span data-stu-id="b024b-110">Make all necessary G/L adjustments.</span></span>
* <span data-ttu-id="b024b-111">Обновите и учтите типовые журналы.</span><span class="sxs-lookup"><span data-stu-id="b024b-111">Update and post Recurring Journals.</span></span>
<!--* Process Consolidations-->
* <span data-ttu-id="b024b-112">Создайте финансовые отчеты следующим образом:</span><span class="sxs-lookup"><span data-stu-id="b024b-112">Run account schedules as follows:</span></span>
  1. <span data-ttu-id="b024b-113">Откройте окно **Финансовый отчет** и выберите действие **Печать**.</span><span class="sxs-lookup"><span data-stu-id="b024b-113">Open the **Account Schedule** window, and choose the **Print** action.</span></span>
  2. <span data-ttu-id="b024b-114">Заполните окно запроса **Финансовый отчет** и выберите действие **Печать**.</span><span class="sxs-lookup"><span data-stu-id="b024b-114">Fill the **Account Schedule** request window and choose the **Print** action.</span></span>

## <a name="sales--receivables"></a><span data-ttu-id="b024b-115">Продажи и расчеты с дебиторами</span><span class="sxs-lookup"><span data-stu-id="b024b-115">Sales & Receivables</span></span>
* <span data-ttu-id="b024b-116">Учтите все заказы на продажу, счета, кредит-ноты и заказы на возврат.</span><span class="sxs-lookup"><span data-stu-id="b024b-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="b024b-117">Выполните учет всех журналов кассовых поступлений.</span><span class="sxs-lookup"><span data-stu-id="b024b-117">Post all cash receipt journals.</span></span>
* <span data-ttu-id="b024b-118">Выполните обновление и учет типовых журналов, относящихся к продажам и расчетам с дебиторами.</span><span class="sxs-lookup"><span data-stu-id="b024b-118">Update and post recurring journals that are related to Sales & Receivables.</span></span>
* <span data-ttu-id="b024b-119">Выполните выверку дебиторской задолженности с главной книгой.</span><span class="sxs-lookup"><span data-stu-id="b024b-119">Reconcile accounts receivable to the general ledger.</span></span>
* <span data-ttu-id="b024b-120">Выполните пакетное задание **Удаление заказов на продажу, по которым выставлены счета**.</span><span class="sxs-lookup"><span data-stu-id="b024b-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>

## <a name="purchases--payables"></a><span data-ttu-id="b024b-121">Покупки и расчеты с кредиторами</span><span class="sxs-lookup"><span data-stu-id="b024b-121">Purchases & Payables</span></span>
* <span data-ttu-id="b024b-122">Выполните учет всех заказов на покупку, счетов, кредит-нот и заказов на возврат.</span><span class="sxs-lookup"><span data-stu-id="b024b-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="b024b-123">Выполните учет всех журналов оплат.</span><span class="sxs-lookup"><span data-stu-id="b024b-123">Post all payment journals.</span></span>
* <span data-ttu-id="b024b-124">Выполните обновление и учет типовых журналов, относящихся к покупкам и расчетам с кредиторами.</span><span class="sxs-lookup"><span data-stu-id="b024b-124">Update and post recurring journals that are related to purchases & payables.</span></span>
* <span data-ttu-id="b024b-125">Выполните отчет **Кредиторская задолженность по срокам давности** и проведите выверку кредиторской задолженности с главной книгой.</span><span class="sxs-lookup"><span data-stu-id="b024b-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>
* <span data-ttu-id="b024b-126">Выполните пакетное задание **Удалить заказы на покупку, по которым выставлены счета**.</span><span class="sxs-lookup"><span data-stu-id="b024b-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="b024b-127">Расчет и обработка налога с продаж</span><span class="sxs-lookup"><span data-stu-id="b024b-127">Calculate and Process Sales Tax</span></span>
*  <span data-ttu-id="b024b-128">Завершите отчеты по НДС.</span><span class="sxs-lookup"><span data-stu-id="b024b-128">Complete Tax Statements.</span></span>

## <a name="see-also"></a><span data-ttu-id="b024b-129">См. также</span><span class="sxs-lookup"><span data-stu-id="b024b-129">See Also</span></span>
[<span data-ttu-id="b024b-130">Закрытие года и периодов</span><span class="sxs-lookup"><span data-stu-id="b024b-130">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="b024b-131">Закрыть книги</span><span class="sxs-lookup"><span data-stu-id="b024b-131">Close Books</span></span>](year-close-books.md)

