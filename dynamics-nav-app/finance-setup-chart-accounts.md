---
title: "Настройка или изменение плана счетов"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 2a2f1f2ec3ac5bdd935ec19c11d74e16bdee7686
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---

# <a name="set-up-or-change-the-chart-of-accounts"></a><span data-ttu-id="65ecc-102">Настройка или изменение плана счетов</span><span class="sxs-lookup"><span data-stu-id="65ecc-102">Set Up or Change the Chart of Accounts</span></span>
<span data-ttu-id="65ecc-103">В плане счетов отображаются счета главной книги, на которых хранятся финансовые данные.</span><span class="sxs-lookup"><span data-stu-id="65ecc-103">The chart of accounts shows the ledger accounts that store your financial data.</span></span> <span data-ttu-id="65ecc-104">Dynamics NAV включает стандартный план счетов, готовый к использованию в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="65ecc-104">Dynamics NAV includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="65ecc-105">Однако вы можете изменить счета по умолчанию и добавить новые счета.</span><span class="sxs-lookup"><span data-stu-id="65ecc-105">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="65ecc-106">Добавление или изменение счетов</span><span class="sxs-lookup"><span data-stu-id="65ecc-106">Adding or Changing Accounts</span></span>
<span data-ttu-id="65ecc-107">В плане счетов вы можете открыть каждый счет ГК и добавить или изменить параметры.</span><span class="sxs-lookup"><span data-stu-id="65ecc-107">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

<span data-ttu-id="65ecc-108">**Примечание**. Вы можете удалить счет главной книги.</span><span class="sxs-lookup"><span data-stu-id="65ecc-108">**Note**: You can delete a general ledger account.</span></span> <span data-ttu-id="65ecc-109">Однако прежде чем удалять его, должно быть соблюдено следующее:</span><span class="sxs-lookup"><span data-stu-id="65ecc-109">However, before you delete it, the following must be true:</span></span>  
- <span data-ttu-id="65ecc-110">Сальдо счета должно быть нулевым.</span><span class="sxs-lookup"><span data-stu-id="65ecc-110">The balance on the account must be zero.</span></span>  
- <span data-ttu-id="65ecc-111">В окне **Настройка Главной книги** должно быть задано поле **Разрешить удаление счета ГК до**, а на счете не должно быть операций книги в эту дату и после нее.</span><span class="sxs-lookup"><span data-stu-id="65ecc-111">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
- <span data-ttu-id="65ecc-112">Если в окне **Настройка Главной книги** установлен флажок **Проверка использования счета ГК**, то счет не должен использоваться ни в одной из учетных групп или настроек учета.</span><span class="sxs-lookup"><span data-stu-id="65ecc-112">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

<span data-ttu-id="65ecc-113">Dynamics NAV не допускает удаления счета главной книги, на котором хранятся данные, необходимые для плана счетов.</span><span class="sxs-lookup"><span data-stu-id="65ecc-113">Dynamics NAV will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

##<a name="see-also"></a><span data-ttu-id="65ecc-114">См. также</span><span class="sxs-lookup"><span data-stu-id="65ecc-114">See Also</span></span>  
[<span data-ttu-id="65ecc-115">Главная книга и план счетов</span><span class="sxs-lookup"><span data-stu-id="65ecc-115">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  
[<span data-ttu-id="65ecc-116">Управление банковскими счетами</span><span class="sxs-lookup"><span data-stu-id="65ecc-116">Manage Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="65ecc-117">Измерения</span><span class="sxs-lookup"><span data-stu-id="65ecc-117">Dimensions</span></span>](finance-setup-dimensions.md)  
[<span data-ttu-id="65ecc-118">Практическое руководство. Работа с кодами GIFI в Канаде</span><span class="sxs-lookup"><span data-stu-id="65ecc-118">How to: Work With GIFI Codes in Canada</span></span>](ca-finance-setup-work-GiFI-codes.md)

