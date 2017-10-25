---
title: "Настройка организационных уровней для контактных лиц"
description: "В можете определить организационный уровень и назначить его контакту, чтобы указать положение, которое они занимают в организации, например относятся к высшему руководству."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, client, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fe8554f0335ef332fc940d020c3f8441d8e1359d
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-organizational-levels-for-contact-persons"></a><span data-ttu-id="27fff-103">Практическое руководство. Настройка организационных уровней для контактных лиц</span><span class="sxs-lookup"><span data-stu-id="27fff-103">How to: Set Up Organizational Levels for Contact Persons</span></span>
<span data-ttu-id="27fff-104">Вы можете использовать организационные уровни для контактов, чтобы задавать положение, которое они занимают в организации, например относятся к высшему руководству.</span><span class="sxs-lookup"><span data-stu-id="27fff-104">You can use organizational levels on your contacts to specify which position they have in the company, for example, top management.</span></span> <span data-ttu-id="27fff-105">Эту информацию можно использовать при вводе информации о контактах.</span><span class="sxs-lookup"><span data-stu-id="27fff-105">You can use this information when entering information about your contacts.</span></span>

<span data-ttu-id="27fff-106">Использование организационных уровней для контактов — это двухэтапный процесс.</span><span class="sxs-lookup"><span data-stu-id="27fff-106">Using organizational levels on contacts is a two-step process.</span></span> <span data-ttu-id="27fff-107">Сначала вы определяете код организационного уровня.</span><span class="sxs-lookup"><span data-stu-id="27fff-107">First, you define the organizational level code.</span></span> <span data-ttu-id="27fff-108">Этот шаг нужно выполнить один раз для каждого организационного уровня.</span><span class="sxs-lookup"><span data-stu-id="27fff-108">You only have to perform this step one time for each organizational level.</span></span> <span data-ttu-id="27fff-109">После настройки кода организационного уровня можно начинать назначение кода контактным лицам.</span><span class="sxs-lookup"><span data-stu-id="27fff-109">Once you have an organizational level code, you can start to assign the code to contact persons.</span></span>

## <a name="to-define-an-organizational-level-code"></a><span data-ttu-id="27fff-110">Определение кода организационного уровня</span><span class="sxs-lookup"><span data-stu-id="27fff-110">To define an organizational level code</span></span>
<span data-ttu-id="27fff-111">Код организационного уровня определяет тип или категорию организационного уровня, например ГЕД или ФИД.</span><span class="sxs-lookup"><span data-stu-id="27fff-111">The organizational level code defines the type or category of the organizational level, such a CEO  or CFO.</span></span> <span data-ttu-id="27fff-112">Допускается наличие нескольких кодов организационных уровней.</span><span class="sxs-lookup"><span data-stu-id="27fff-112">You can have several organizational level codes.</span></span> <span data-ttu-id="27fff-113">Для определения организационного уровня используется окно **Организационные уровни**.</span><span class="sxs-lookup"><span data-stu-id="27fff-113">To define the organizational level, you use the **Organizational Levels** window.</span></span>

1. <span data-ttu-id="27fff-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Организационные уровни**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="27fff-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Organizational Levels**, and then choose the related link.</span></span>
2. <span data-ttu-id="27fff-115">Выберите действие **Создать**, введите код и описание.</span><span class="sxs-lookup"><span data-stu-id="27fff-115">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="27fff-116">Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).</span><span class="sxs-lookup"><span data-stu-id="27fff-116">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <a name="to-assign-organizational-levels-to-a-contact-person"></a><span data-ttu-id="27fff-117">Назначение организационных уровней контактному лицу</span><span class="sxs-lookup"><span data-stu-id="27fff-117">To assign organizational levels to a contact person</span></span>
<span data-ttu-id="27fff-118">Организационные уровни можно назначать только контактным лицам, а не контактным организациям.</span><span class="sxs-lookup"><span data-stu-id="27fff-118">You can assign organizational levels to contact persons only, not contact companies.</span></span> <span data-ttu-id="27fff-119">Каждому контакту можно назначить только один организационный уровень.</span><span class="sxs-lookup"><span data-stu-id="27fff-119">You can only assign one organizational level to each contact.</span></span>

1. <span data-ttu-id="27fff-120">Откройте контакт.</span><span class="sxs-lookup"><span data-stu-id="27fff-120">Open the contact.</span></span>
2. <span data-ttu-id="27fff-121">В поле **Организационные уровни** выберите код, который нужно назначить.</span><span class="sxs-lookup"><span data-stu-id="27fff-121">In the **Organizational Levels** field, select the code you want to assign.</span></span>

<span data-ttu-id="27fff-122">После назначения организационных уровней контактам можно использовать эту информацию для создания сегментов.</span><span class="sxs-lookup"><span data-stu-id="27fff-122">After you have assigned organizational levels to your contacts, you can use this information to create segments.</span></span>

<span data-ttu-id="27fff-123">После назначения контактам должностных обязанностей можно использовать эту информацию для выбора контактов для сегмента.</span><span class="sxs-lookup"><span data-stu-id="27fff-123">After you have assigned job responsibilities to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="27fff-124">Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="27fff-124">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="27fff-125">См. также</span><span class="sxs-lookup"><span data-stu-id="27fff-125">See Also</span></span>
[<span data-ttu-id="27fff-126">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="27fff-126">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
[<span data-ttu-id="27fff-127">Создание контактных лиц</span><span class="sxs-lookup"><span data-stu-id="27fff-127">Creating Contact Persons</span></span>](marketing-create-contact-persons.md)  
<span data-ttu-id="27fff-128">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="27fff-128">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

