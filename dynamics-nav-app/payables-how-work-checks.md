---
title: "Практическое руководство. Работа с платежными документами"
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a><span data-ttu-id="e4de6-102">Практическое руководство. Работа с платежными документами</span><span class="sxs-lookup"><span data-stu-id="e4de6-102">How to: Work With Checks</span></span>
<span data-ttu-id="e4de6-103">Dynamics NAV поддерживает как электронный выпуск платежных документов, так и вручную.</span><span class="sxs-lookup"><span data-stu-id="e4de6-103">Dynamics NAV supports electronic and manual check issuance.</span></span> <span data-ttu-id="e4de6-104">Оба метода используют журнал платежей для выпуска платежных документов для поставщиков.</span><span class="sxs-lookup"><span data-stu-id="e4de6-104">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="e4de6-105">Также можно аннулировать платежные документы и просмотреть операции с платежными документами.</span><span class="sxs-lookup"><span data-stu-id="e4de6-105">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="e4de6-106">В результате процесса выпуска платежных документов предлагаются платежи, создаются операции главной книги и печатаются электронные платежные документы.</span><span class="sxs-lookup"><span data-stu-id="e4de6-106">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

<span data-ttu-id="e4de6-107">Ваши принтер должен быть соответствующим образом настроен для использования форм платежных документов, и вы должны определить макеты чеков для использования.</span><span class="sxs-lookup"><span data-stu-id="e4de6-107">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="e4de6-108">Дополнительные сведения см. в разделе [Практическое руководство. Определение макетов платежных документов](finance-setup-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="e4de6-108">For more information, see [How to: Define Check Layouts](finance-setup-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="e4de6-109">Выпуск платежных документов</span><span class="sxs-lookup"><span data-stu-id="e4de6-109">To issue checks</span></span>
1. <span data-ttu-id="e4de6-110">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Журналы платежей**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e4de6-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="e4de6-111">Заполните журнал соответствующими платежами, например с помощью функции "Предлож. оплаты поставщикам".</span><span class="sxs-lookup"><span data-stu-id="e4de6-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="e4de6-112">Дополнительные сведения см. в разделе [Практическое руководство. Предложение оплаты поставщикам](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="e4de6-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="e4de6-113">В **Вид платежа** в строках для платежа, которые вы ходите осуществить с помощь платежного документа, выберите один из следующих вариантов:</span><span class="sxs-lookup"><span data-stu-id="e4de6-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

 - <span data-ttu-id="e4de6-114">**Компьютерный**. Выберите эту опцию, если хотите, чтобы программа распечатала платежный документ на сумму из этой строки журнала платежей.</span><span class="sxs-lookup"><span data-stu-id="e4de6-114">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="e4de6-115">Платежные документы нужно печатать до учета строк журнала.</span><span class="sxs-lookup"><span data-stu-id="e4de6-115">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="e4de6-116">Параметр **Компьютерный** можно выбрать, только если параметр **Тип баланс. счета** или **Тип счета** имеет значение **Банковский счет**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-116">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

 - <span data-ttu-id="e4de6-117">**Ручной**. Выберите эту опцию, если платежный документ создан вручную и нужно создать соответствующую операцию книги платежных документов на эту сумму.</span><span class="sxs-lookup"><span data-stu-id="e4de6-117">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="e4de6-118">При использовании нельзя распечатывать платежные документы из Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="e4de6-118">By using this option, you cannot print checks from Dynamics NAV.</span></span> <span data-ttu-id="e4de6-119">Параметр **Ручной** можно выбрать, только если параметр **Тип баланс. счета** или **Тип счета** имеет значение **Банковский счет**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-119">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

    <span data-ttu-id="e4de6-120">**Примечание**. Компьютерные платежные документы нужно печатать до учета соответствующих строк журнала.</span><span class="sxs-lookup"><span data-stu-id="e4de6-120">**Note**: You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="e4de6-121">В случае компьютерных платежных документов выберите **Печать платежного документа**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-121">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="e4de6-122">В окне **Платежный документ** заполните поля по мере необходимости.</span><span class="sxs-lookup"><span data-stu-id="e4de6-122">In the **Check** window, fill in the fields as necessary.</span></span> <span data-ttu-id="e4de6-123">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="e4de6-123">Choose a field to read a short description of the field or link to more information.</span></span>
6. <span data-ttu-id="e4de6-124">Выберите кнопку **Печать**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-124">Choose the **Print** button.</span></span>

<span data-ttu-id="e4de6-125">**Примечание**. Если требуется напечатать платежные документы в нескольких валютах с различных банковских счетов, следует выполнить пакетное задание **Печать платежного документа** отдельно по каждой валюте и указать соответствующий банковский счет.</span><span class="sxs-lookup"><span data-stu-id="e4de6-125">**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="e4de6-126">Отмена напечатанных платежных документов. которые не учтены</span><span class="sxs-lookup"><span data-stu-id="e4de6-126">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="e4de6-127">Вы можете отменить неучтенные платежные документы после их печати с помощью действия **Аннулировать платеж. документ** в окне **Журнал платежей**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-127">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>
1. <span data-ttu-id="e4de6-128">В окне **Журнал платежей** выберите **Аннулировать платеж. документ**, а затем выберите платежные документы для отмены.</span><span class="sxs-lookup"><span data-stu-id="e4de6-128">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="e4de6-129">Аннулирование платежных документов</span><span class="sxs-lookup"><span data-stu-id="e4de6-129">To void checks</span></span>
<span data-ttu-id="e4de6-130">Если платеж с помощью платежного документа учтен, аннулировать (отменять) платежные документы можно только в итоговых операциях книги банка.</span><span class="sxs-lookup"><span data-stu-id="e4de6-130">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="e4de6-131">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Банковские счета**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="e4de6-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="e4de6-132">Выберите соответствующий банковский счет, выберите действие **Изменить**, а затем выберите действие **Книга платежных документов**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="e4de6-133">В окне **Книга платежных документов** выберите действие **Аннулировать платеж. документ**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-133">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="e4de6-134">Установите флажок **Аннулировать только платеж. документ**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-134">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="e4de6-135">Выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="e4de6-135">Choose the **OK**button.</span></span>

## <a name="see-also"></a><span data-ttu-id="e4de6-136">См. также</span><span class="sxs-lookup"><span data-stu-id="e4de6-136">See Also</span></span>
[<span data-ttu-id="e4de6-137">Управление кредиторской задолженностью</span><span class="sxs-lookup"><span data-stu-id="e4de6-137">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="e4de6-138">Настройка банка</span><span class="sxs-lookup"><span data-stu-id="e4de6-138">Set Up Banking</span></span>](bank-setup-banking.md)  

