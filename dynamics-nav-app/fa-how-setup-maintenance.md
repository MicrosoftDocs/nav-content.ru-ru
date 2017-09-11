---
title: "Практическое руководство. Настройка обслуживания основных средств"
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
ms.openlocfilehash: ace0fb13d2be71c7204f16f34f6b65b54ff98230
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-maintenance"></a><span data-ttu-id="a1a21-102">Практическое руководство. Настройка обслуживания основных средств</span><span class="sxs-lookup"><span data-stu-id="a1a21-102">How to: Set Up Fixed Asset Maintenance</span></span>
<span data-ttu-id="a1a21-103">Для управления обслуживанием основных средств следует сначала настроить некоторые общие сведения об обслуживании, счета учета для затрат на обслуживание, а также коды обслуживания для различных типов работ, например планового обслуживания или ремонта.</span><span class="sxs-lookup"><span data-stu-id="a1a21-103">To manage fixed asset maintenance, you must first set up some general maintenance information, a posting account for maintenance costs, and maintenance codes for types of work, such as Routine Service or Repair.</span></span>

## <a name="to-set-up-general-maintenance-information"></a><span data-ttu-id="a1a21-104">Настройка общей информации об обслуживании</span><span class="sxs-lookup"><span data-stu-id="a1a21-104">To set up general maintenance information</span></span>
<span data-ttu-id="a1a21-105">Если устанавливаются поля для обслуживания, то можно учитывать расходы на обслуживание из журнала основных средств.</span><span class="sxs-lookup"><span data-stu-id="a1a21-105">If you set up the fields for maintenance, you can post maintenance expenses from the fixed asset journal.</span></span>
1. <span data-ttu-id="a1a21-106">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Основные средства**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a1a21-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="a1a21-107">Выберите основное средство, для которого определяется страховое покрытие, затем выберите действие **Правка**.</span><span class="sxs-lookup"><span data-stu-id="a1a21-107">Select the fixed asset that you to define insurance coverage for, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="a1a21-108">На экспресс-вкладке **Обслуживание** заполните необходимые поля.</span><span class="sxs-lookup"><span data-stu-id="a1a21-108">On the **Maintenance** FastTab, fill in the fields as necessary.</span></span> <span data-ttu-id="a1a21-109">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="a1a21-109">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-maintenance-codes"></a><span data-ttu-id="a1a21-110">Настройка кодов обслуживания</span><span class="sxs-lookup"><span data-stu-id="a1a21-110">To set up maintenance codes</span></span>  
<span data-ttu-id="a1a21-111">При учете затрат на обслуживание из финансового журнала заполняется поле **Код обслуживания**, чтобы зарегистрировать тип выполненного обслуживания, например плановое обслуживание или ремонт.</span><span class="sxs-lookup"><span data-stu-id="a1a21-111">When you post maintenance costs from a general journal, you fill in the **Maintenance Code** field to record what kind of maintenance has been performed, such as routine service or repair.</span></span>
1. <span data-ttu-id="a1a21-112">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Обслуживание**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a1a21-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Maintenance**, and then choose the related link.</span></span>
2. <span data-ttu-id="a1a21-113">В окне **Обслуживание** настройте коды для различных типов работ по техническому обслуживанию.</span><span class="sxs-lookup"><span data-stu-id="a1a21-113">In the **Maintenance** window, set up codes for different types of maintenance work.</span></span>

## <a name="to-set-up-maintenance-expense-accounts"></a><span data-ttu-id="a1a21-114">Настройка счетов расходов на обслуживание</span><span class="sxs-lookup"><span data-stu-id="a1a21-114">To set up maintenance expense accounts</span></span>  
<span data-ttu-id="a1a21-115">Чтобы учитывать затраты на обслуживание, следует сначала ввести номер счета в окне **ОС - учетные группы**.</span><span class="sxs-lookup"><span data-stu-id="a1a21-115">To post maintenance costs, you must first enter an account number in the **FA Posting Groups** window.</span></span>
1. <span data-ttu-id="a1a21-116">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Учетные группы ОС**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="a1a21-116">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Posting Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="a1a21-117">Заполните поле **Обслуживание - счет расходов** для каждой учетной группы.</span><span class="sxs-lookup"><span data-stu-id="a1a21-117">Fill in the **Maintenance Expense Account** field for each posting group.</span></span>

<span data-ttu-id="a1a21-118">**Примечание**. Чтобы задать распределение стоимости обслуживания между отделами или проектами, необходимо настроить ключи распределения.</span><span class="sxs-lookup"><span data-stu-id="a1a21-118">**Note**: To define that maintenance costs are allocated to departments or projects, set up an allocation keys.</span></span> <span data-ttu-id="a1a21-119">Дополнительные сведения см. в разделе [Практическое руководство. Настройка общих параметров основных средств](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="a1a21-119">For more information, see [How to: Set Up General Fixed Assets Features](fa-how-setup-general.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="a1a21-120">См. также</span><span class="sxs-lookup"><span data-stu-id="a1a21-120">See Also</span></span>
[<span data-ttu-id="a1a21-121">Настройка основных средств</span><span class="sxs-lookup"><span data-stu-id="a1a21-121">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="a1a21-122">Управление основными средствами</span><span class="sxs-lookup"><span data-stu-id="a1a21-122">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="a1a21-123">Финансы</span><span class="sxs-lookup"><span data-stu-id="a1a21-123">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="a1a21-124">Добро пожаловать в Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="a1a21-124">Welcome to Dynamics NAV</span></span>](across-get-started.md)

