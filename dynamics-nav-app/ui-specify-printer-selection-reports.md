---
title: "Выбор принтера для отчета"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="51e9c-102">Выбор принтера для отчета</span><span class="sxs-lookup"><span data-stu-id="51e9c-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="51e9c-103">Можно настроить отчеты таким образом, чтобы они распечатывались на определенном принтере.</span><span class="sxs-lookup"><span data-stu-id="51e9c-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="51e9c-104">Ниже представлены примеры выбора принтера.</span><span class="sxs-lookup"><span data-stu-id="51e9c-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="51e9c-105">Отчеты можно печатать на корпоративном бланке организации.</span><span class="sxs-lookup"><span data-stu-id="51e9c-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="51e9c-106">Отчеты можно печатать на бумаге разного размера.</span><span class="sxs-lookup"><span data-stu-id="51e9c-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="51e9c-107">Отчеты можно печатать на принтере по умолчанию конкретного сотрудника.</span><span class="sxs-lookup"><span data-stu-id="51e9c-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="51e9c-108">Окно **Выбор принтера** служит для определения различных значений для получения другого вывода.</span><span class="sxs-lookup"><span data-stu-id="51e9c-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="51e9c-109">Если задан выбор определенного принтера, то он имеет преимущество над общим выбором принтера.</span><span class="sxs-lookup"><span data-stu-id="51e9c-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="51e9c-110">Например, можно выбрать параметры принтера, которые имеют значения в полях **Код пользователя**, **Номер отчета** и **Название принтера**.</span><span class="sxs-lookup"><span data-stu-id="51e9c-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="51e9c-111">Этот выбор принтера имеет преимущество перед выбором принтера, который содержит пустые записи в полях **Код пользователя** или **Номер отчета**.</span><span class="sxs-lookup"><span data-stu-id="51e9c-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="51e9c-112">В следующей таблице описывается комбинация значений для указания, когда следует настраивать выбор принтера для отчета.</span><span class="sxs-lookup"><span data-stu-id="51e9c-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="51e9c-113">Задача</span><span class="sxs-lookup"><span data-stu-id="51e9c-113">To</span></span>                                                 |<span data-ttu-id="51e9c-114">Установите следующие значения</span><span class="sxs-lookup"><span data-stu-id="51e9c-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="51e9c-115">Печать отчета на определенном принтере для всех пользователей</span><span class="sxs-lookup"><span data-stu-id="51e9c-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="51e9c-116">Укажите значения в полях **Номер отчета** и **Название принтера** и оставьте поле **Код пользователя** пустым.</span><span class="sxs-lookup"><span data-stu-id="51e9c-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="51e9c-117">Печать всех отчетов на принтере для определенного пользователя</span><span class="sxs-lookup"><span data-stu-id="51e9c-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="51e9c-118">Укажите значения в полях **Код пользователя** и **Название принтера** и оставьте поле **Номер отчета** пустым.</span><span class="sxs-lookup"><span data-stu-id="51e9c-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="51e9c-119">Установка принтера по умолчанию для всех отчетов</span><span class="sxs-lookup"><span data-stu-id="51e9c-119">Set the default printer for all reports</span></span>|<span data-ttu-id="51e9c-120">Укажите значение в поле **Название принтера** и оставьте поля **Код пользователя** и **Номер отчета** пустыми.</span><span class="sxs-lookup"><span data-stu-id="51e9c-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="51e9c-121">Печать определенного отчета на принтере пользователя по умолчанию</span><span class="sxs-lookup"><span data-stu-id="51e9c-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="51e9c-122">Укажите значение в поле **Номер отчета** и оставьте поля **Название принтера** и **Код пользователя** пустыми.</span><span class="sxs-lookup"><span data-stu-id="51e9c-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="51e9c-123">Печать определенного отчета на принтере для определенного пользователя</span><span class="sxs-lookup"><span data-stu-id="51e9c-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="51e9c-124">Укажите значения во всех трех полях.</span><span class="sxs-lookup"><span data-stu-id="51e9c-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="51e9c-125">См. также</span><span class="sxs-lookup"><span data-stu-id="51e9c-125">See Also</span></span>
[<span data-ttu-id="51e9c-126">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="51e9c-126">Work with Dynamics NAV</span></span>](ui-work-product.md)

