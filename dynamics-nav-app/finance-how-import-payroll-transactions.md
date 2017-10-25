---
title: "Импорт транзакций зарплаты"
description: "Для управления зарплатой необходимо импортировать финансовые транзакции от поставщика заработной платы непосредственно в главную книгу, используя расширение для зарплаты, например Ceridian или Quickbooks."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: Ceridian, Quickbooks, salary
ms.date: 06/16/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 675a63c7862854ef3f8e2ca3d37dd3f2e290cf29
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="06718-103">Практическое руководство: импорт транзакций по зарплате</span><span class="sxs-lookup"><span data-stu-id="06718-103">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="06718-104">Для учета выплаты зарплаты и связанных транзакций необходимо импортировать и учесть финансовые транзакции, сделанные поставщиком системы зарплаты, в главную книгу.</span><span class="sxs-lookup"><span data-stu-id="06718-104">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="06718-105">Чтобы это сделать, следует сначала импортировать файл, полученный от поставщика системы зарплаты, в окно **Финансовый журнал**.</span><span class="sxs-lookup"><span data-stu-id="06718-105">To do this, you first import a file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="06718-106">Затем следует сопоставить внешние счета в файле зарплаты с соответствующими счетами ГК.</span><span class="sxs-lookup"><span data-stu-id="06718-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="06718-107">Наконец требуется учесть транзакции зарплаты в соответствии с сопоставлением счетов.</span><span class="sxs-lookup"><span data-stu-id="06718-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

> [!NOTE]  
>   <span data-ttu-id="06718-108">Чтобы воспользоваться этой функцией, расширение для импорта зарплаты необходимо установить и включить.</span><span class="sxs-lookup"><span data-stu-id="06718-108">To use this functionality, an extension for payroll import must be installed and enabled.</span></span> <span data-ttu-id="06718-109">Расширения "Зарплата Ceridian" и "Импорт файла зарплаты Quickbooks" предварительно установлены в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="06718-109">The Ceridian Payroll and the Quickbooks Payroll File Import extensions are pre-installed in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="06718-110">Дополнительные сведения см. в разделе [Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="06718-110">For more information, see [Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md).</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="06718-111">Импорт файла зарплаты</span><span class="sxs-lookup"><span data-stu-id="06718-111">To import a payroll file</span></span>
1. <span data-ttu-id="06718-112">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Финансовые журналы**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="06718-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="06718-113">В соответствующем разделе финансового журнала выберите действие **Импорт транзакций зарплаты**.</span><span class="sxs-lookup"><span data-stu-id="06718-113">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span> <span data-ttu-id="06718-114">Откроется руководство по сопровождаемой настройке.</span><span class="sxs-lookup"><span data-stu-id="06718-114">An assisted setup guide opens.</span></span>
3. <span data-ttu-id="06718-115">Выполните шаги в окне **Импорт транзакций зарплаты**.</span><span class="sxs-lookup"><span data-stu-id="06718-115">Follow the steps in the **Import Payroll Transactions** window.</span></span>

    > [!TIP]  
>   <span data-ttu-id="06718-116">На шаге сопоставления внешних записей зарплаты со счетами ГК выполненные сопоставления будут отображаться при следующем импорте тех же записей.</span><span class="sxs-lookup"><span data-stu-id="06718-116">In the step about mapping the external payroll records to your G/L accounts, the mappings that you make will be remembered next time the same records are imported.</span></span> <span data-ttu-id="06718-117">Это экономит время, так как не требуется вручную заполнять поле **Номер счета** в финансовом журнале при каждом импорте повторяющихся транзакций зарплаты.</span><span class="sxs-lookup"><span data-stu-id="06718-117">This will save you time as you do not have to manually fill in the **Account No.** field in the general journal every time you have imported recurring payroll transactions.</span></span>   

    <span data-ttu-id="06718-118">При нажатии кнопки **ОК** в руководстве по сопровождаемой настройке окно **Финансовый журнал** будет заполнено строками, представляющими транзакции, содержащиеся в файле зарплаты, с соответствующими счетами, предварительно заполненными в полях **Счет ГК** в соответствии с сопоставлениями, выполненными в руководстве.</span><span class="sxs-lookup"><span data-stu-id="06718-118">When you choose the **OK** button in the assisted setup guide, the **General Journal** window is filled with lines representing the transactions that the payroll file contains and with the relevant accounts prefilled in the **G/L Account** fields according to mappings you made in the guide.</span></span>
4. <span data-ttu-id="06718-119">Отредактируйте или учтите строки журнала, как и для любых других транзакций главной книги.</span><span class="sxs-lookup"><span data-stu-id="06718-119">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="06718-120">Дополнительные сведения см. в разделе [Практическое руководство. Учет транзакций непосредственно в главной книге](finance-how-post-transactions-directly.md).</span><span class="sxs-lookup"><span data-stu-id="06718-120">For more information, see [How to: Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="06718-121">См. также</span><span class="sxs-lookup"><span data-stu-id="06718-121">See Also</span></span>
[<span data-ttu-id="06718-122">Финансы</span><span class="sxs-lookup"><span data-stu-id="06718-122">Finance</span></span>](finance.md)  
<span data-ttu-id="06718-123">[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="06718-123">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  
[<span data-ttu-id="06718-124">Работа с финансовыми журналами</span><span class="sxs-lookup"><span data-stu-id="06718-124">Working with General Journals</span></span>](ui-work-general-journals.md)  

