---
title: "Практическое руководство: учет себестоимости товаров в главной книге"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: b64d01609cde6b79393e405a2e4ffc30d6d1c4c8
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---

# <a name="how-to-post-inventory-costs-to-the-general-ledger"></a><span data-ttu-id="bb863-102">Практическое руководство: учет себестоимости товаров в главной книге</span><span class="sxs-lookup"><span data-stu-id="bb863-102">How to: Post Inventory Costs to the General Ledger</span></span>   
<span data-ttu-id="bb863-103">При учете складских транзакций, таких как расходные накладные, счета покупки или корректировки запасов измененные количества и значения себестоимости записываются в операциях книги товаров и в операциях стоимости соответственно.</span><span class="sxs-lookup"><span data-stu-id="bb863-103">When you post inventory transactions, such as sales shipments, purchase invoices, or inventory adjustments, the changed quantities and costs are recorded in the item ledger entries and the value entries, respectively.</span></span> <span data-ttu-id="bb863-104">Чтобы отразить такое изменение стоимости запасов в финансовых книгах, необходимо учесть себестоимость товаров на соответствующих счетах товаров в главной книге.</span><span class="sxs-lookup"><span data-stu-id="bb863-104">To reflect this change of inventory value in your financial books, you must post inventory costs to the related inventory accounts in the general ledger.</span></span>

<span data-ttu-id="bb863-105">Себестоимость товаров можно учитывать в главной книге двумя способами.</span><span class="sxs-lookup"><span data-stu-id="bb863-105">You can post inventory costs to the general ledger in two ways:</span></span>

- <span data-ttu-id="bb863-106">Автоматически, когда себестоимость товаров учитывает в главной книге каждый раз при учете складской транзакции.</span><span class="sxs-lookup"><span data-stu-id="bb863-106">Automatically, so that inventory costs are posted to the general ledger every time you post an inventory transaction.</span></span>
- <span data-ttu-id="bb863-107">Вручную, когда себестоимость товаров учитывается в главной книге, когда вы выполняете пакетное задание.</span><span class="sxs-lookup"><span data-stu-id="bb863-107">Manually, so that inventory costs are only posted to the general ledger when you run a batch job.</span></span>


## <a name="to-post-inventory-costs-automatically"></a><span data-ttu-id="bb863-108">Учет себестоимости товаров на складе автоматически</span><span class="sxs-lookup"><span data-stu-id="bb863-108">To post inventory costs automatically</span></span>
1. <span data-ttu-id="bb863-109">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка модуля "Запасы"**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="bb863-109">In the top right corner, choose the **Search for Page or Report** icon, enter **Inventory Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="bb863-110">В окне **Настройка модуля "Запасы"** установите флажок **Автомат. учет себест.**</span><span class="sxs-lookup"><span data-stu-id="bb863-110">In the **Inventory Setup** window, select the **Automatic Cost Posting** check box.</span></span>

<span data-ttu-id="bb863-111">Для каждой учитываемой складской транзакции учитываются соответствующие стоимости в товарном счете, счете коррекции и счете себестоимости продажи в Главной книге</span><span class="sxs-lookup"><span data-stu-id="bb863-111">For each inventory transaction that you post, the appropriate values are posted to the inventory account, adjustment account, and COGS account in the general ledger.</span></span>

<span data-ttu-id="bb863-112">Даже при использовании автоматического учета себестоимости необходимо периодически выполнять пакетное задание "Коррекция себест. запасов", чтобы гарантировать перенос стоимости товаров в соответствующие исходящие транзакции, такие как продажи или перемещения.</span><span class="sxs-lookup"><span data-stu-id="bb863-112">Even if you use automatic cost posting, it is still necessary to periodically run the Adjust Cost - Item Entries batch job to ensure that the costs of goods are forwarded to the appropriate outbound transactions, such as sales or transfers.</span></span> <span data-ttu-id="bb863-113">Это особенно важно в ситуациях, когда товары продаются до того, как на их покупку выставляется счет.</span><span class="sxs-lookup"><span data-stu-id="bb863-113">This is especially important in situations where you sell goods before invoicing the purchase of those goods.</span></span>

<span data-ttu-id="bb863-114">Если при учете себестоимости товара в Главной книге обнаруживается ошибка в настройке измерения, учет завершается с ошибкой.</span><span class="sxs-lookup"><span data-stu-id="bb863-114">If an error occurs in the dimension setup while posting the inventory cost to the general ledger, the posting will end with an error.</span></span>

## <a name="to-post-inventory-costs-manually"></a><span data-ttu-id="bb863-115">Учет себестоимости товаров на складе вручную</span><span class="sxs-lookup"><span data-stu-id="bb863-115">To post inventory costs manually</span></span>
1. <span data-ttu-id="bb863-116">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Учет себест. запасов в ГК**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="bb863-116">In the top right corner, choose the **Search for Page or Report** icon, enter **Post Inventory Cost to G/L**, and then choose the related link.</span></span>
2. <span data-ttu-id="bb863-117">Учтите себестоимость товаров в главной книге вручную, выполнив пакетное задание.</span><span class="sxs-lookup"><span data-stu-id="bb863-117">Post inventory costs to the general ledger manually by running the batch job.</span></span> <span data-ttu-id="bb863-118">При запуске этого пакетного задания операции главной книги создаются на основе операций стоимости.</span><span class="sxs-lookup"><span data-stu-id="bb863-118">When you run this batch job, general ledger entries are created on the basis of value entries.</span></span> <span data-ttu-id="bb863-119">Можно учесть эти операции, суммировав их по учетной группе.</span><span class="sxs-lookup"><span data-stu-id="bb863-119">You can post the entries so that they are summarized per posting group.</span></span>

<span data-ttu-id="bb863-120">**Примечание**. При запуске этого пакетного задания могут обнаружиться ошибки, связанные с отсутствием настройки или с неправильной настройкой измерений.</span><span class="sxs-lookup"><span data-stu-id="bb863-120">**Note**: When you run this batch job, you may encounter errors having to do with missing setup or incompatible dimension setup.</span></span> <span data-ttu-id="bb863-121">Если обнаруживается ошибка в настройке измерения, пакетное задание игнорирует эти ошибки и использует измерения из операции стоимости.</span><span class="sxs-lookup"><span data-stu-id="bb863-121">If the batch job encounters errors in the dimension setup, it overrides these errors and uses the dimensions of the value entry.</span></span> <span data-ttu-id="bb863-122">Если обнаруживаются другие ошибки, пакетное задание пропускает учет операций стоимости и включает их в виде списка в конце отчета в разделе “Пропущенные операции”.</span><span class="sxs-lookup"><span data-stu-id="bb863-122">For any other errors, the batch job skips posting the value entries and lists them at the end of the report in a section titled “Skipped Entries.”</span></span> <span data-ttu-id="bb863-123">Чтобы учесть эти операции, необходимо исправить ошибки.</span><span class="sxs-lookup"><span data-stu-id="bb863-123">To post these entries, you must fix the errors.</span></span>

<span data-ttu-id="bb863-124">Чтобы просмотреть список ошибок перед выполнением пакетного задания, можно сформировать отчет **Учет себест. запасов в ГК - тест**.</span><span class="sxs-lookup"><span data-stu-id="bb863-124">To see a list of errors before running the posting batch job, you can run the **Post Invt. Cost to G/L - Test** report.</span></span> <span data-ttu-id="bb863-125">В тестовом отчете будут указаны все ошибки, которые произошли при тестовом учете.</span><span class="sxs-lookup"><span data-stu-id="bb863-125">The test report lists all the errors encountered during a test posting.</span></span> <span data-ttu-id="bb863-126">Затем эти ошибки можно исправить и выполнить пакетное задание учета себестоимости товаров на складе, не пропуская операции.</span><span class="sxs-lookup"><span data-stu-id="bb863-126">You can then fix the errors, and run the inventory cost posting batch job without skipping any entries.</span></span>

<span data-ttu-id="bb863-127">Если необходимо просто просмотреть стоимости, которые могут быть учтены в Главной книге, без фактического выполнения учета, можно выполнить пакетное задание Учет себест. запасов в ГК, не выполняя фактический учет стоимостей в Главной книге.</span><span class="sxs-lookup"><span data-stu-id="bb863-127">If you would like to simply get an overview of what values could be posted to the general ledger without actually performing the posting, you can run the Post Inventory Cost to G/L batch job without actually posting the values to the general ledger.</span></span> <span data-ttu-id="bb863-128">Для этого следует снять флажок в поле Учет страницы запроса.</span><span class="sxs-lookup"><span data-stu-id="bb863-128">You do this by clearing the check mark from the Post field on the request page.</span></span> <span data-ttu-id="bb863-129">В этом случае при выполнении пакетного задания будет создан отчет, содержащий только стоимости, которые могут быть учтены в Главной книге, но которые не учтены.</span><span class="sxs-lookup"><span data-stu-id="bb863-129">This way, when you run the batch job, the report is produced showing the values that are ready to be posted to the general ledger, but they are not posted.</span></span>

## <a name="see-also"></a><span data-ttu-id="bb863-130">См. также</span><span class="sxs-lookup"><span data-stu-id="bb863-130">See Also</span></span>
<span data-ttu-id="bb863-131">[Управление запасами](inventory-manage-inventory.md)  </span><span class="sxs-lookup"><span data-stu-id="bb863-131">[Manage Inventory](inventory-manage-inventory.md)  </span></span>  
[<span data-ttu-id="bb863-132">Практическое руководство. Корректировка себестоимости товаров</span><span class="sxs-lookup"><span data-stu-id="bb863-132">How to: Adjust Item Costs</span></span>](inventory-how-adjust-item-costs.md)  
[<span data-ttu-id="bb863-133">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="bb863-133">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="bb863-134">Управление закупками</span><span class="sxs-lookup"><span data-stu-id="bb863-134">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)
