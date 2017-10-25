---
title: "Перевод банковских средств"
description: "Вы можете переводить суммы между банковскими счетами, в том числе в различных валютах, учитывая транзакции в финансовом журнале."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bank account transfer, multiple currencies
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5cb652df51fc5b24088bb5cc6a41d8d3f067cfd4
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-bank-funds"></a><span data-ttu-id="3a997-103">Практическое руководство. Перевод банковских средств</span><span class="sxs-lookup"><span data-stu-id="3a997-103">How to: Transfer Bank Funds</span></span>
<span data-ttu-id="3a997-104">Иногда бывает необходимо перевести сумму с одного банковского счета на другой.</span><span class="sxs-lookup"><span data-stu-id="3a997-104">You may sometimes need to transfer an amount from one bank account to another.</span></span> <span data-ttu-id="3a997-105">Для этого необходимо учесть транзакцию в финансовом журнале.</span><span class="sxs-lookup"><span data-stu-id="3a997-105">To do this, you must post the a transaction in the general journal.</span></span> <span data-ttu-id="3a997-106">Задача зависит от того, используется на банковских счетах одна валюта или различные валюты.</span><span class="sxs-lookup"><span data-stu-id="3a997-106">The task varies depending on whether the bank accounts use the same currency or different currencies.</span></span>

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a><span data-ttu-id="3a997-107">Учет перемещения между банковскими счетами с одним кодом валюты</span><span class="sxs-lookup"><span data-stu-id="3a997-107">To post a transfer between bank accounts with the same currency code</span></span>
1. <span data-ttu-id="3a997-108">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3a997-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="3a997-109">В строке журнала заполните поля **Дата учета** и **Номер документа**</span><span class="sxs-lookup"><span data-stu-id="3a997-109">On a journal line, fill in the **Posting Date** and **Document No.** fields.</span></span>
3. <span data-ttu-id="3a997-110">В поле **Тип счета** выберите значение **Банковский счет**.</span><span class="sxs-lookup"><span data-stu-id="3a997-110">In the **Account Type** field, select **Bank Account**.</span></span>
4. <span data-ttu-id="3a997-111">В поле **Номер счета** выберите банк, из которого необходимо перевести средства.</span><span class="sxs-lookup"><span data-stu-id="3a997-111">In the **Account No.** field, select the bank from which you want to transfer the funds.</span></span>
5. <span data-ttu-id="3a997-112">В поле **Сумма** укажите сумму для перевода.</span><span class="sxs-lookup"><span data-stu-id="3a997-112">In the **Amount** field, enter the amount to be transferred.</span></span>
6. <span data-ttu-id="3a997-113">В поле **Тип баланс. счета** выберите **Банковский счет.**</span><span class="sxs-lookup"><span data-stu-id="3a997-113">In the **Bal. Account Type** field, select **Bank Account**.</span></span>
7. <span data-ttu-id="3a997-114">В поле **Номер баланс. счета** выберите банковский счет, на который необходимо перевести средства.</span><span class="sxs-lookup"><span data-stu-id="3a997-114">In the **Bal. Account No.** field, select the bank account to which you want to transfer the funds.</span></span>
8. <span data-ttu-id="3a997-115">Учтите журнал.</span><span class="sxs-lookup"><span data-stu-id="3a997-115">Post the journal.</span></span>

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a><span data-ttu-id="3a997-116">Учет перемещения между банковскими счетами с разными кодами валют</span><span class="sxs-lookup"><span data-stu-id="3a997-116">To post a transfer between bank accounts with different currency codes</span></span>
<span data-ttu-id="3a997-117">Для переноса средств между банковскими счетами, которые используют различные валюты, необходимо учесть две строки финансового журнала.</span><span class="sxs-lookup"><span data-stu-id="3a997-117">To transfer funds between bank accounts that use different currencies, you must post two general journal lines.</span></span>

1. <span data-ttu-id="3a997-118">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовый журнал**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="3a997-118">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="3a997-119">Создайте две строки журнала и заполните поля **Дата учета** и **Номер документа**.</span><span class="sxs-lookup"><span data-stu-id="3a997-119">Create two journal lines, and fill in the **Posting Date** and **Document No.** fields.</span></span>
3. <span data-ttu-id="3a997-120">В первой строке журнала в поле **Тип** выберите **Банковский счет**.</span><span class="sxs-lookup"><span data-stu-id="3a997-120">On the first journal line, in the **Type** field, select **Bank Account**.</span></span>
4. <span data-ttu-id="3a997-121">В поле **Номер счета** выберите банковский счет, с которого необходимо перевести средства.</span><span class="sxs-lookup"><span data-stu-id="3a997-121">In the **Account No.** field, select the bank account from which you want to transfer the funds.</span></span>
5. <span data-ttu-id="3a997-122">В поле **Сумма** введите сумму в валюте банковского счета.</span><span class="sxs-lookup"><span data-stu-id="3a997-122">In the **Amount** field, enter the amount in the currency of the bank account.</span></span> <span data-ttu-id="3a997-123">Введите суммы кредита со знаком "минус".</span><span class="sxs-lookup"><span data-stu-id="3a997-123">Enter credit amounts with a minus sign.</span></span> <span data-ttu-id="3a997-124">Введите суммы дебета без знака "минус".</span><span class="sxs-lookup"><span data-stu-id="3a997-124">Enter debit amounts without a minus sign.</span></span>
6. <span data-ttu-id="3a997-125">В поле **Тип баланс. счета** выберите **Банковский счет.**</span><span class="sxs-lookup"><span data-stu-id="3a997-125">In the **Bal. Account Type** field, select **Bank Account**.</span></span>
7. <span data-ttu-id="3a997-126">В поле **Номер баланс. счета** выберите банковский счет, на который необходимо перевести средства.</span><span class="sxs-lookup"><span data-stu-id="3a997-126">In the **Bal. Account No.** field, select the bank account to which you want to transfer the funds.</span></span>
8. <span data-ttu-id="3a997-127">Во второй строке журнала в поле **Тип** выберите **Банковский счет**.</span><span class="sxs-lookup"><span data-stu-id="3a997-127">On the second journal line, in the **Type** field, select **Bank Account**.</span></span>
9. <span data-ttu-id="3a997-128">В поле **Номер счета** выберите банковский счет, на который необходимо перевести средства.</span><span class="sxs-lookup"><span data-stu-id="3a997-128">In the **Account No.** field, select the bank account to which you want to transfer the funds.</span></span>
10. <span data-ttu-id="3a997-129">В поле **Сумма** введите сумму в валюте банковского счета.</span><span class="sxs-lookup"><span data-stu-id="3a997-129">In the **Amount** field, enter the amount in the currency of the bank account.</span></span> <span data-ttu-id="3a997-130">Введите суммы кредита со знаком "минус".</span><span class="sxs-lookup"><span data-stu-id="3a997-130">Enter credit amounts with a minus sign.</span></span> <span data-ttu-id="3a997-131">Введите суммы дебета без знака "минус".</span><span class="sxs-lookup"><span data-stu-id="3a997-131">Enter debit amounts without a minus sign.</span></span>
11. <span data-ttu-id="3a997-132">В поле **Тип баланс. счета** выберите **Банковский счет.**</span><span class="sxs-lookup"><span data-stu-id="3a997-132">In the **Bal. Account Type** field, select **Bank Account**.</span></span>  
12. <span data-ttu-id="3a997-133">В поле **Номер баланс. счета** выберите банковский счет, с которого необходимо перевести средства.</span><span class="sxs-lookup"><span data-stu-id="3a997-133">In the **Bal. Account No.** field, select the bank account from which you want to transfer the funds.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="3a997-134">Если валютные курсы, используемые в журнале, отличаются от валютных курсов в окне **Валютные курсы**, введите в третью строку положительную или отрицательную курсовую разницу.</span><span class="sxs-lookup"><span data-stu-id="3a997-134">If the exchange rates used in the journal are different than the exchange rates in the **Currency Exchange Rates** window, enter a third line for the exchange rate gain or loss.</span></span> <span data-ttu-id="3a997-135">Введите **Счет ГК** в поле **Тип счета**.</span><span class="sxs-lookup"><span data-stu-id="3a997-135">Enter **G/L Account** in the **Account Type** field.</span></span> <span data-ttu-id="3a997-136">Введите номер счета ГК для прибыли или убытка по курсовой разнице в поле **Номер счета**.</span><span class="sxs-lookup"><span data-stu-id="3a997-136">Enter the G/L account number for exchange rate gain or loss in the **Account No.** field.</span></span> <span data-ttu-id="3a997-137">Введите прибыль или убыток по курсовой разнице в поле **Сумма** со знаком минус или без него для сумм кредита и дебета соответственно.</span><span class="sxs-lookup"><span data-stu-id="3a997-137">Enter the exchange rate gain or loss in the **Amount** field with or without a minus sign for credits and debits respectively.</span></span>
13. <span data-ttu-id="3a997-138">Выполните учет журнала.</span><span class="sxs-lookup"><span data-stu-id="3a997-138">Post the journal.</span></span>

## <a name="see-also"></a><span data-ttu-id="3a997-139">См. также</span><span class="sxs-lookup"><span data-stu-id="3a997-139">See Also</span></span>
[<span data-ttu-id="3a997-140">Управление банковскими счетами</span><span class="sxs-lookup"><span data-stu-id="3a997-140">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="3a997-141">Настройка банковских операций</span><span class="sxs-lookup"><span data-stu-id="3a997-141">Setting Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="3a997-142">Работа с финансовыми журналами</span><span class="sxs-lookup"><span data-stu-id="3a997-142">Working with General Journals</span></span>](ui-work-general-journals.md)  
<span data-ttu-id="3a997-143">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="3a997-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

