---
title: "Настройка отраслевых групп в контактных организациях"
description: "Описывается порядок определения отраслевой группы и ее назначения контактной организации, например в сфере розничной торговли или автомобильной промышленности."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 303b619c4188a1b74a9c325c3458e244b364cd37
ms.contentlocale: ru-ru
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-industry-groups-for-contact-companies"></a><span data-ttu-id="647a1-103">Практическое руководство. Настройка отраслевых групп в контактных организациях</span><span class="sxs-lookup"><span data-stu-id="647a1-103">How to: Set Up Industry Groups for Contact Companies</span></span>
<span data-ttu-id="647a1-104">Отраслевые группы используются для указания типа отрасли, к которой относится контакт, например розничная торговля или автомобильное производство.</span><span class="sxs-lookup"><span data-stu-id="647a1-104">You use industry groups to indicate the type of industry to which your contacts belong, for example, the retail industry or the automobile industry.</span></span>

<span data-ttu-id="647a1-105">Использование отраслевых групп для контактов — это двухэтапный процесс.</span><span class="sxs-lookup"><span data-stu-id="647a1-105">Using industry groups on contacts is a two-step process.</span></span> <span data-ttu-id="647a1-106">Сначала вы определяете код отраслевой группы.</span><span class="sxs-lookup"><span data-stu-id="647a1-106">First, you define the industry group code.</span></span> <span data-ttu-id="647a1-107">Этот шаг нужно выполнить один раз для каждой отраслевой группы.</span><span class="sxs-lookup"><span data-stu-id="647a1-107">You only have to perform this step one time for each industry group.</span></span> <span data-ttu-id="647a1-108">После настройки кода отраслевой группы можно начинать назначение кода контактным организациям.</span><span class="sxs-lookup"><span data-stu-id="647a1-108">Once you have an industry group code, you can start to assign the code to contact companies.</span></span>

> [!NOTE]  
>   <span data-ttu-id="647a1-109">При планировании синхронизации контактов с поставщиками, клиентами или банковскими счетами в других частях приложения может понадобиться настроить для них деловое отношение.</span><span class="sxs-lookup"><span data-stu-id="647a1-109">If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="to-define-an-industry-group-code"></a><span data-ttu-id="647a1-110">Определение кода отраслевой группы</span><span class="sxs-lookup"><span data-stu-id="647a1-110">To define an industry group code</span></span>
<span data-ttu-id="647a1-111">Код отраслевой группы определяет тип или категорию группы, например РЕКЛАМА для сферы рекламы или ПРЕССА для ТВ и радио.</span><span class="sxs-lookup"><span data-stu-id="647a1-111">The industry group code defines the type or category of the group, such as ADVERT for advertising, or PRESS, for TV and radio.</span></span> <span data-ttu-id="647a1-112">Допускается наличие нескольких кодов отраслевых групп.</span><span class="sxs-lookup"><span data-stu-id="647a1-112">You can have several industry group codes.</span></span> <span data-ttu-id="647a1-113">Для определения отраслевых групп используется окно **Отраслевые группы**.</span><span class="sxs-lookup"><span data-stu-id="647a1-113">To define the industry groups, you use the **Industry Groups** window.</span></span>

1. <span data-ttu-id="647a1-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Отраслевые группы**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="647a1-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Industry Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="647a1-115">Выберите действие **Создать**, введите код и описание.</span><span class="sxs-lookup"><span data-stu-id="647a1-115">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="647a1-116">Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).</span><span class="sxs-lookup"><span data-stu-id="647a1-116">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <span data-ttu-id="647a1-117"><a name="AssignIndustryGroupContact"></a> Присвоение отраслевых групп контакту</span><span class="sxs-lookup"><span data-stu-id="647a1-117"><a name="AssignIndustryGroupContact"></a> To assign industry groups to a contact</span></span>
<span data-ttu-id="647a1-118">Нельзя назначать отраслевые группы контактным лицам — только организациям.</span><span class="sxs-lookup"><span data-stu-id="647a1-118">You cannot assign industry groups to a contact person - only companies.</span></span>

1. <span data-ttu-id="647a1-119">Откройте контакт.</span><span class="sxs-lookup"><span data-stu-id="647a1-119">Open the contact.</span></span>
2. <span data-ttu-id="647a1-120">Выберите действие **Организация**, а затем действие **Отраслевые группы**.</span><span class="sxs-lookup"><span data-stu-id="647a1-120">Choose the **Company** action, and then the **Industry Groups** action.</span></span> <span data-ttu-id="647a1-121">Откроется окно **Отраслевые группы контакта**.</span><span class="sxs-lookup"><span data-stu-id="647a1-121">The **Contact Industry Groups** window opens.</span></span>
3. <span data-ttu-id="647a1-122">В поле **Код отраслевой группы** выберите отраслевую группу, которую нужно назначить.</span><span class="sxs-lookup"><span data-stu-id="647a1-122">In the **Industry Groups Code** field, select the industry groups you want to assign.</span></span>

<span data-ttu-id="647a1-123">Повторите эти шаги для назначения желаемого количества отраслевых групп.</span><span class="sxs-lookup"><span data-stu-id="647a1-123">Repeat these steps to assign as many industry groups as you want.</span></span> <span data-ttu-id="647a1-124">Также можно назначать отраслевые группы из списка контактов, следуя той же процедуре.</span><span class="sxs-lookup"><span data-stu-id="647a1-124">You can also assign industry groups from the contact list by following the same procedure.</span></span>

<span data-ttu-id="647a1-125">Число отраслевых групп, назначенных контакту, отображается в окне **Контакт** в разделе **Сегментация** в поле **Число отраслевых групп**.</span><span class="sxs-lookup"><span data-stu-id="647a1-125">The number of industry groups that you have assigned to the contact is displayed in the **No. of Industry Groups** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="647a1-126">После назначения контактам отраслевых групп эта информация может использоваться для выбора контактов для сегментов.</span><span class="sxs-lookup"><span data-stu-id="647a1-126">After you have assigned industry groups to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="647a1-127">Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="647a1-127">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="647a1-128">См. также</span><span class="sxs-lookup"><span data-stu-id="647a1-128">See Also</span></span>
[<span data-ttu-id="647a1-129">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="647a1-129">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
<span data-ttu-id="647a1-130">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="647a1-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

