---
title: "Управление банком"
description: "В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно создать структуры справочника ЦБ РФ для хранения справочной информации по банку в одном месте, создания бюджетных классификаций, добавления сведений о банковских счетах в определенные счета главной книги и печати и учета соответствующих документов."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e094aa85fbff67f620f931ee0e3453eed3ae2731
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="bank-management"></a><span data-ttu-id="7f62a-103">Управление банком</span><span class="sxs-lookup"><span data-stu-id="7f62a-103">Bank Management</span></span>
<span data-ttu-id="7f62a-104">В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно создать структуры справочника ЦБ РФ для хранения справочной информации по банку в одном месте, создания бюджетных классификаций, добавления сведений о банковских счетах в определенные счета главной книги и печати и учета соответствующих документов.</span><span class="sxs-lookup"><span data-stu-id="7f62a-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can create bank directory structures to keep bank reference information in one location, create budget classifications, add bank account details to specific general ledger accounts, and print and post required documents.</span></span>  

## <a name="creating-bank-directory-structures"></a><span data-ttu-id="7f62a-105">Создание структур справочника ЦБ РФ</span><span class="sxs-lookup"><span data-stu-id="7f62a-105">Creating Bank Directory Structures</span></span>  
 <span data-ttu-id="7f62a-106">Структуру справочника ЦБ РФ можно использовать для хранения справочной информации обо всех банках в одном месте.</span><span class="sxs-lookup"><span data-stu-id="7f62a-106">You can use a bank directory structure to keep reference information about all the banks in one location.</span></span> <span data-ttu-id="7f62a-107">Можно использовать эту информацию для автоматического заполнения соответствующих полей в окнах **Карточка банк. счета**, **Карточка банк. счета поставщика** и **Карточка банк. счета клиента**.</span><span class="sxs-lookup"><span data-stu-id="7f62a-107">This information can be used to automatically fill in the corresponding fields in the **Bank Account Card**, **Vendor Bank Account Card**, and **Customer Bank Account Card** windows.</span></span>  

## <a name="creating-budget-classification-codes"></a><span data-ttu-id="7f62a-108">Создание кодов бюджетной классификации</span><span class="sxs-lookup"><span data-stu-id="7f62a-108">Creating Budget Classification Codes</span></span>  
 <span data-ttu-id="7f62a-109">Каталог кодов бюджетной классификации можно использовать в банковских платежах в государственный бюджет (например, в налоговых платежах).</span><span class="sxs-lookup"><span data-stu-id="7f62a-109">You can use a budget classification codes catalog in bank payments that are made to the state budget, such as tax payments.</span></span> <span data-ttu-id="7f62a-110">Эти коды позволяют отслеживать классификацию типов платежей в государственный бюджет.</span><span class="sxs-lookup"><span data-stu-id="7f62a-110">These codes allow you to track the classification of budget payment types in the state budget.</span></span>  

## <a name="creating-bank-account-details-records"></a><span data-ttu-id="7f62a-111">Создание записей сведений о банковском счете</span><span class="sxs-lookup"><span data-stu-id="7f62a-111">Creating Bank Account Details Records</span></span>  
 <span data-ttu-id="7f62a-112">Подробные сведения о банковском счете можно использовать, чтобы определять различные измерения и другие коды, относящиеся к платежным поручениям и банковским выпискам.</span><span class="sxs-lookup"><span data-stu-id="7f62a-112">You can use bank account details to define dimensions and other codes that are pertinent to bank payment orders and bank statements.</span></span> <span data-ttu-id="7f62a-113">Записи в банковских операциях с типом счета **Счет ГК** содержат подробные сведения, связанные с указанным счетом.</span><span class="sxs-lookup"><span data-stu-id="7f62a-113">Records in a bank operation that have the account type information set to **G/L Account** can have bank account details attached to the specified account.</span></span> <span data-ttu-id="7f62a-114">Сведения о банковском счете настраиваются в окне **Сведения о банковских счетах**.</span><span class="sxs-lookup"><span data-stu-id="7f62a-114">Bank account details are set up in the **Bank Account Details** window.</span></span>  

## <a name="printing-and-posting-required-documents"></a><span data-ttu-id="7f62a-115">Печать и учет необходимых документов</span><span class="sxs-lookup"><span data-stu-id="7f62a-115">Printing and Posting Required Documents</span></span>  
 <span data-ttu-id="7f62a-116">Вы можете готовить документы платежных поручений, документов кассовых ордеров и платежей в журнале оплаты поставщикам путем копирования процедур из учтенных документов банковских поручений и кассовых ордеров.</span><span class="sxs-lookup"><span data-stu-id="7f62a-116">You can prepare bank payment order documents, cash order documents, and payments in the payment journal by copying procedures from the posted bank payment order and cash order documents.</span></span> <span data-ttu-id="7f62a-117">Затем можно создать печатные документы и учесть их в требуемом формате.</span><span class="sxs-lookup"><span data-stu-id="7f62a-117">Then you can create the printed documents and post them in the required format.</span></span>  

 <span data-ttu-id="7f62a-118">Вы можете напечатать следующие обязательные документы управления банком.</span><span class="sxs-lookup"><span data-stu-id="7f62a-118">You can print the following required bank management documents.</span></span>  

|<span data-ttu-id="7f62a-119">Отчет</span><span class="sxs-lookup"><span data-stu-id="7f62a-119">Report</span></span>|<span data-ttu-id="7f62a-120">Описанием</span><span class="sxs-lookup"><span data-stu-id="7f62a-120">Description</span></span>|  
|------------|---------------------------------------|  
|<span data-ttu-id="7f62a-121">**Платежное поручение**</span><span class="sxs-lookup"><span data-stu-id="7f62a-121">**Bank Payment Order**</span></span>|<span data-ttu-id="7f62a-122">Этот отчет является копией платежного поручения.</span><span class="sxs-lookup"><span data-stu-id="7f62a-122">This report is a copy of the bank payment order.</span></span>|  
|<span data-ttu-id="7f62a-123">**Банк. счет - оборотная ведомость**</span><span class="sxs-lookup"><span data-stu-id="7f62a-123">**Bank Account G/L Turnover**</span></span>|<span data-ttu-id="7f62a-124">Этот отчет содержит список информации по финансовому обороту.</span><span class="sxs-lookup"><span data-stu-id="7f62a-124">This report is a list of general ledger turnover information.</span></span>|  
|<span data-ttu-id="7f62a-125">**Карточка банковского счета**</span><span class="sxs-lookup"><span data-stu-id="7f62a-125">**Bank Account Card**</span></span>|<span data-ttu-id="7f62a-126">Этот отчет содержит информацию о банковских операциях.</span><span class="sxs-lookup"><span data-stu-id="7f62a-126">This report contains information about bank operations.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="7f62a-127">См. также</span><span class="sxs-lookup"><span data-stu-id="7f62a-127">See Also</span></span>  
 [<span data-ttu-id="7f62a-128">Практическое руководство. Настройка платежного поручения</span><span class="sxs-lookup"><span data-stu-id="7f62a-128">How to: Set Up a Bank Payment Order</span></span>](how-to-set-up-a-bank-payment-order.md)

