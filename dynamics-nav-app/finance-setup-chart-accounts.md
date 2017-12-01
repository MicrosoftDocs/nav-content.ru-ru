---
title: "Настройка плана счетов"
description: "Вы можете изменить счета по умолчанию в плане счетов и добавить новые счета."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: COA, cha of acc
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 41e0af4aa5ca7e8309d9c61457998933ef4433d8
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="setting-up-or-changing-the-chart-of-accounts"></a><span data-ttu-id="f7231-103">Настройка или изменение плана счетов</span><span class="sxs-lookup"><span data-stu-id="f7231-103">Setting Up or Changing the Chart of Accounts</span></span>
<span data-ttu-id="f7231-104">В плане счетов отображаются счета главной книги, на которых хранятся финансовые данные.</span><span class="sxs-lookup"><span data-stu-id="f7231-104">The chart of accounts shows the ledger accounts that store your financial data.</span></span> [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]<span data-ttu-id="f7231-105"> включает стандартный план счетов, готовый к использованию в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="f7231-105"> includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="f7231-106">Однако вы можете изменить счета по умолчанию и добавить новые счета.</span><span class="sxs-lookup"><span data-stu-id="f7231-106">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="f7231-107">Добавление или изменение счетов</span><span class="sxs-lookup"><span data-stu-id="f7231-107">Adding or Changing Accounts</span></span>
<span data-ttu-id="f7231-108">В плане счетов вы можете открыть каждый счет ГК и добавить или изменить параметры.</span><span class="sxs-lookup"><span data-stu-id="f7231-108">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

> [!NOTE]  
>   <span data-ttu-id="f7231-109">Вы можете удалить счет главной книги.</span><span class="sxs-lookup"><span data-stu-id="f7231-109">You can delete a general ledger account.</span></span> <span data-ttu-id="f7231-110">Однако прежде чем удалять его, должно быть соблюдено следующее:</span><span class="sxs-lookup"><span data-stu-id="f7231-110">However, before you delete it, the following must be true:</span></span>  

* <span data-ttu-id="f7231-111">Сальдо счета должно быть нулевым.</span><span class="sxs-lookup"><span data-stu-id="f7231-111">The balance on the account must be zero.</span></span>  
* <span data-ttu-id="f7231-112">В окне **Настройка Главной книги** должно быть задано поле **Разрешить удаление счета ГК до**, а на счете не должно быть операций книги в эту дату и после нее.</span><span class="sxs-lookup"><span data-stu-id="f7231-112">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
* <span data-ttu-id="f7231-113">Если в окне **Настройка Главной книги** установлен флажок **Проверка использования счета ГК**, то счет не должен использоваться ни в одной из учетных групп или настроек учета.</span><span class="sxs-lookup"><span data-stu-id="f7231-113">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="f7231-114"> не допускает удаления счета главной книги, на котором хранятся данные, необходимые для плана счетов.</span><span class="sxs-lookup"><span data-stu-id="f7231-114"> will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f7231-115">См. также</span><span class="sxs-lookup"><span data-stu-id="f7231-115">See Also</span></span>
[<span data-ttu-id="f7231-116">Главная книга и план счетов</span><span class="sxs-lookup"><span data-stu-id="f7231-116">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
[<span data-ttu-id="f7231-117">Управление банковскими счетами</span><span class="sxs-lookup"><span data-stu-id="f7231-117">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="f7231-118">Работа с измерениями</span><span class="sxs-lookup"><span data-stu-id="f7231-118">Working with Dimensions</span></span>](finance-dimensions.md)  
[<span data-ttu-id="f7231-119">Импорт из других финансовых систем</span><span class="sxs-lookup"><span data-stu-id="f7231-119">Importing from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="f7231-120">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f7231-120">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

## 

