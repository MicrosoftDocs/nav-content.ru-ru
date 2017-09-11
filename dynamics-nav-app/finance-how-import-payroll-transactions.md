---
title: "Практическое руководство: импорт транзакций по зарплате "
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d5e70a0a1659c7facdeec3f0971eda43ff8a03cc
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="58efe-102">Практическое руководство: импорт транзакций по зарплате </span><span class="sxs-lookup"><span data-stu-id="58efe-102">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="58efe-103">Для учета выплаты зарплаты и связанных транзакций необходимо импортировать и учесть финансовые транзакции, сделанные поставщиком системы зарплаты, в главную книгу.</span><span class="sxs-lookup"><span data-stu-id="58efe-103">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="58efe-104">Чтобы это сделать, следует сначала импортировать файл CSV,</span><span class="sxs-lookup"><span data-stu-id="58efe-104">To do this, you first import a csv.</span></span> <span data-ttu-id="58efe-105">полученный от поставщика системы зарплаты, в окно **Финансовый журнал**.</span><span class="sxs-lookup"><span data-stu-id="58efe-105">file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="58efe-106">Затем следует сопоставить внешние счета в файле зарплаты с соответствующими счетами ГК.</span><span class="sxs-lookup"><span data-stu-id="58efe-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="58efe-107">Наконец требуется учесть транзакции зарплаты в соответствии с сопоставлением счетов.</span><span class="sxs-lookup"><span data-stu-id="58efe-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="58efe-108">Импорт файла зарплаты</span><span class="sxs-lookup"><span data-stu-id="58efe-108">To import a payroll file</span></span>
1. <span data-ttu-id="58efe-109">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Финансовые журналы**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="58efe-109">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="58efe-110">В соответствующем разделе финансового журнала выберите действие **Импорт транзакций зарплаты**.</span><span class="sxs-lookup"><span data-stu-id="58efe-110">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span>
3. <span data-ttu-id="58efe-111">В окне **Импорт** выберите соответствующий файл зарплаты, затем нажмите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="58efe-111">In the **Import** window, select the relevant payroll file, and then choose the **OK** button.</span></span> <span data-ttu-id="58efe-112">Файл должен быть в формате CSV.</span><span class="sxs-lookup"><span data-stu-id="58efe-112">The file must be in CSV format.</span></span> 
4. <span data-ttu-id="58efe-113">Выполните шаги в окне **Импорт транзакций зарплаты**, чтобы импортировать транзакции и сопоставить счета, затем нажмите кнопку **Готово**.</span><span class="sxs-lookup"><span data-stu-id="58efe-113">Follow the steps in the **Import Payroll Transactions** window to import transactions and map accounts, and then choose the **Finish** button.</span></span>

    <span data-ttu-id="58efe-114">Финансовый журнал заполняется строками, представляющими транзакции, содержащиеся в файле зарплаты, и соответствующими счетами в столбце **Счет ГК**.</span><span class="sxs-lookup"><span data-stu-id="58efe-114">The general journal is filled with lines representing the transactions that the payroll file contains and with the relevant accounts in the **G/L Account** column.</span></span>
4. <span data-ttu-id="58efe-115">Отредактируйте или учтите строки журнала, как и для любых других транзакций главной книги.</span><span class="sxs-lookup"><span data-stu-id="58efe-115">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="58efe-116">Дополнительные сведения см. в разделе [Практическое руководство. Работа с финансовыми журналами](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="58efe-116">For more information, see [How to: Work With General Journals](ui-work-general-journals.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="58efe-117">См. также</span><span class="sxs-lookup"><span data-stu-id="58efe-117">See Also</span></span>
[<span data-ttu-id="58efe-118">Финансы</span><span class="sxs-lookup"><span data-stu-id="58efe-118">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="58efe-119">Практическое руководство. Работа с финансовыми журналами</span><span class="sxs-lookup"><span data-stu-id="58efe-119">How to: Work With General Journals</span></span>](ui-work-general-journals.md)  

