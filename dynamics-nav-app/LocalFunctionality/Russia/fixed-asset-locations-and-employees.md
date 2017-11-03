---
title: "ОС: местоположения и ответственные сотрудники"
description: "Функция местоположения и ответственных сотрудников для основных средств позволяет, помимо прочего, управлять движением основных средств и отслеживать историю перемещений основных средств между различными местоположениями и подотчетными лицами."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 7fb11f5ade2dcfd48cec895aef0e5ae78012ee6c
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="fixed-asset-locations-and-employees"></a><span data-ttu-id="31ce9-103">ОС: местоположения и ответственные сотрудники</span><span class="sxs-lookup"><span data-stu-id="31ce9-103">Fixed Asset Locations and Employees</span></span>
<span data-ttu-id="31ce9-104">Функция местоположений и ответственных сотрудников для основных средств позволяет:</span><span class="sxs-lookup"><span data-stu-id="31ce9-104">The fixed assets locations and the fixed assets employees feature enable you to:</span></span>  

- <span data-ttu-id="31ce9-105">управлять движением основных средств и хранить историю перемещений ОС между различными местоположениями и подотчетными лицами;</span><span class="sxs-lookup"><span data-stu-id="31ce9-105">Control the movement of fixed assets and to keep the history of the movements of fixed assets between locations and responsible employees.</span></span>  

- <span data-ttu-id="31ce9-106">указывать местоположение и подотчетное лицо для ОС в документах и журналах для учета основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-106">Enter the fixed assets location and responsible employee in documents and journals for fixed asset posting.</span></span> <span data-ttu-id="31ce9-107">Эти данные будут отражены в операциях основных средств;</span><span class="sxs-lookup"><span data-stu-id="31ce9-107">This information is reflected in fixed assets operations.</span></span>  

- <span data-ttu-id="31ce9-108">создавать отчеты и расчеты, в которых используется история перемещений основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-108">Create reports and calculations that use the history of the movements of fixed assets.</span></span> <span data-ttu-id="31ce9-109">Кроме того, можно связать сотрудников (по умолчанию), местоположения (склад товара) и регионы в официальной классификации (код ОКАТО) с любым местоположением основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-109">You can also connect employees (by default), locations (item location), and regions in an official classification (OKATO code) to any fixed assets location.</span></span>  

## <a name="setup"></a><span data-ttu-id="31ce9-110">Настройка</span><span class="sxs-lookup"><span data-stu-id="31ce9-110">Setup</span></span>  
<span data-ttu-id="31ce9-111">Ниже показано, как обеспечить, чтобы поля **Код местонахождения ОС** и **Код сотрудника**</span><span class="sxs-lookup"><span data-stu-id="31ce9-111">The following procedure shows how to make sure the **FA Location Code** and **Employee No.**</span></span> <span data-ttu-id="31ce9-112">были всегда заполнены для основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-112">fields are always filled in for fixed assets.</span></span>  

1.  <span data-ttu-id="31ce9-113">Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите *Настройка ОС*, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="31ce9-113">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Setup*, and then choose the related link.</span></span>
2.  <span data-ttu-id="31ce9-114">На экспресс-вкладке **Общие** установите флажок **Местонахождение ОС обязательно**.</span><span class="sxs-lookup"><span data-stu-id="31ce9-114">On the **General** FastTab, select the **FA Location Mandatory** check box.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="31ce9-115">Если этот флажок установлен, процедуры учета основных средств управляются, пока они генерируют операции ОС с ненулевым значением в поле **Кол-во**.</span><span class="sxs-lookup"><span data-stu-id="31ce9-115">When this field is selected, fixed asset posting procedures are controlled as long as they generate fixed asset operations with a non-zero value in the **Quantity** field.</span></span>  

3.  <span data-ttu-id="31ce9-116">Установите флажок **Код сотрудника обязателен**.</span><span class="sxs-lookup"><span data-stu-id="31ce9-116">Select the **Employee No. Mandatory** check box.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="31ce9-117">Если этот флажок установлен, процедуры учета основных средств управляются, пока они генерируют операции ОС с ненулевым значением в поле **Кол-во**.</span><span class="sxs-lookup"><span data-stu-id="31ce9-117">When this field is selected, fixed asset posting procedures are controlled as long as they generate fixed asset operations with a non-zero value in the **Quantity** field.</span></span>  

## <a name="added-fields"></a><span data-ttu-id="31ce9-118">Добавленные поля</span><span class="sxs-lookup"><span data-stu-id="31ce9-118">Added Fields</span></span>  
<span data-ttu-id="31ce9-119">Поля со ссылками на местоположения и подотчетных лиц для ОС были добавлены к следующим элементам:</span><span class="sxs-lookup"><span data-stu-id="31ce9-119">Fields with references to fixed asset locations and responsible employees have been added to the following:</span></span>  

- <span data-ttu-id="31ce9-120">строки документов покупки;</span><span class="sxs-lookup"><span data-stu-id="31ce9-120">Lines of purchase documents</span></span>  
- <span data-ttu-id="31ce9-121">журналы основных средств;</span><span class="sxs-lookup"><span data-stu-id="31ce9-121">Fixed asset journals</span></span>  
- <span data-ttu-id="31ce9-122">финансовые журналы основных средств;</span><span class="sxs-lookup"><span data-stu-id="31ce9-122">Fixed asset G/L journals</span></span>  
- <span data-ttu-id="31ce9-123">журналы реклассификации основных средств;</span><span class="sxs-lookup"><span data-stu-id="31ce9-123">Fixed asset reclassification journals</span></span>  
- <span data-ttu-id="31ce9-124">акты основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-124">Fixed asset acts</span></span>  

<span data-ttu-id="31ce9-125">Если установлен флажок **Код сотрудника обязателен** или **Местонахождение ОС обязательно** в окне **Настройка основных средств**, поля со ссылками на соответствующие таблицы должны быть заполнены для операций с основными средствами.</span><span class="sxs-lookup"><span data-stu-id="31ce9-125">If the **Employee No. Mandatory** or the **FA Location Mandatory** check box is selected in the **Fixed Asset Setup** window, then the fields with references to corresponding tables must be filled in for fixed asset operations.</span></span> <span data-ttu-id="31ce9-126">Вы вводите значение в поле **Код местоположения ОС** в строке, затем поле **Код сотрудника**</span><span class="sxs-lookup"><span data-stu-id="31ce9-126">If you enter a value in the **FA Location Code** field in a line, then the **Employee No.**</span></span> <span data-ttu-id="31ce9-127">и **Код склада** (если оно существует в строке) заполняются соответствующими значениями по умолчанию из таблицы местоположения основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-127">field and **Location Code** field (if it exists in the line) are filled with the corresponding default values from the Fixed Asset Location table.</span></span> <span data-ttu-id="31ce9-128">Затем значения этих полей можно изменить вручную.</span><span class="sxs-lookup"><span data-stu-id="31ce9-128">Then the values of the fields can be changed manually.</span></span>  

 <span data-ttu-id="31ce9-129">При учете документов и журналов значения в этих полях переносятся в соответствующие новые операции ОС и в соответствующие поля в карточках основных средств.</span><span class="sxs-lookup"><span data-stu-id="31ce9-129">When posting the documents and journals, the values of these fields are transferred to the corresponding new fixed asset operations and to corresponding fields in the Fixed Asset cards.</span></span>  

## <a name="see-also"></a><span data-ttu-id="31ce9-130">См. также</span><span class="sxs-lookup"><span data-stu-id="31ce9-130">See Also</span></span>  
 [<span data-ttu-id="31ce9-131">Инвентаризация основных средств</span><span class="sxs-lookup"><span data-stu-id="31ce9-131">Fixed Asset Inventory</span></span>](fixed-asset-inventory.md)

