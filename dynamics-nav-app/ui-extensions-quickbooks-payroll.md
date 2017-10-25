---
title: "Использование расширения импорта файла зарплаты Quickbooks"
description: "Описывает использование расширения для импорта транзакция по зарплате из службы Quickbooks Payroll."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, salary, wage
ms.date: 03/29/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e1b47161b7fdd4238ff4590c2139c9622d5d3fbb
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="the-quickbooks-payroll-file-import-extension-to-dynamics-nav"></a><span data-ttu-id="77af0-103">Расширения импорта файла зарплаты Quickbooks в Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="77af0-103">The Quickbooks Payroll File Import Extension to Dynamics NAV</span></span>
<span data-ttu-id="77af0-104">Для учета выплаты зарплаты и связанных транзакций необходимо импортировать и учесть финансовые транзакции, сделанные поставщиком системы зарплаты, в главную книгу.</span><span class="sxs-lookup"><span data-stu-id="77af0-104">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span>

<span data-ttu-id="77af0-105">Чтобы это сделать, следует сначала импортировать файл, полученный от поставщика системы зарплаты, в окно **Финансовый журнал**.</span><span class="sxs-lookup"><span data-stu-id="77af0-105">To do this, you first import a file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="77af0-106">Затем следует сопоставить внешние счета в файле зарплаты с соответствующими счетами ГК.</span><span class="sxs-lookup"><span data-stu-id="77af0-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="77af0-107">Наконец требуется учесть транзакции зарплаты в соответствии с сопоставлением счетов.</span><span class="sxs-lookup"><span data-stu-id="77af0-107">Lastly, you post the payroll transactions according to the account mapping.</span></span> <span data-ttu-id="77af0-108">Дополнительные сведения см. в разделе [Практическое руководство. Импорт транзакций зарплаты](finance-how-import-payroll-transactions.md).</span><span class="sxs-lookup"><span data-stu-id="77af0-108">For more information, see [How to: Import Payroll Transactions](finance-how-import-payroll-transactions.md).</span></span>

<span data-ttu-id="77af0-109">Расширение импорта файла зарплаты Quickbooks позволяет импортировать транзакции зарплаты из службы зарплаты Quickbooks.</span><span class="sxs-lookup"><span data-stu-id="77af0-109">The Quickbooks Payroll File Import extension allows you to import payroll transaction from the Quickbooks Payroll service.</span></span>

## <a name="see-also"></a><span data-ttu-id="77af0-110">См. также</span><span class="sxs-lookup"><span data-stu-id="77af0-110">See Also</span></span>
<span data-ttu-id="77af0-111">[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)  </span><span class="sxs-lookup"><span data-stu-id="77af0-111">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)  </span></span>  
<span data-ttu-id="77af0-112">[Финансы](finance.md)  </span><span class="sxs-lookup"><span data-stu-id="77af0-112">[Finance](finance.md)  </span></span>  
<span data-ttu-id="77af0-113">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="77af0-113">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

