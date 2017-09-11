---
title: "Настройка отраслевых групп в контактных организациях"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 5d0a8f8f8f1e5b50671911d6bfba3da00f2d7ae2
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---
# <a name="set-up-industry-groups-for-contact-companies"></a><span data-ttu-id="9528a-102">Настройка отраслевых групп в контактных организациях</span><span class="sxs-lookup"><span data-stu-id="9528a-102">Set Up Industry Groups for Contact Companies</span></span>
<span data-ttu-id="9528a-103">Отраслевые группы используются для указания типа отрасли, к которой относится контакт, например розничная торговля или автомобильное производство.</span><span class="sxs-lookup"><span data-stu-id="9528a-103">You use industry groups to indicate the type of industry to which your contacts belong, for example, the retail industry or the automobile industry.</span></span>

<span data-ttu-id="9528a-104">Использование отраслевых групп для контактов — это двухэтапный процесс.</span><span class="sxs-lookup"><span data-stu-id="9528a-104">Using industry groups on contacts is a two-step process.</span></span> <span data-ttu-id="9528a-105">Сначала вы определяете код отраслевой группы.</span><span class="sxs-lookup"><span data-stu-id="9528a-105">First, you define the industry group code.</span></span> <span data-ttu-id="9528a-106">Этот шаг нужно выполнить один раз для каждой отраслевой группы.</span><span class="sxs-lookup"><span data-stu-id="9528a-106">You only have to perform this step one time for each industry group.</span></span> <span data-ttu-id="9528a-107">После настройки кода отраслевой группы можно начинать назначение кода контактным организациям.</span><span class="sxs-lookup"><span data-stu-id="9528a-107">Once you have an industry group code, you can start to assign the code to contact companies.</span></span>

<span data-ttu-id="9528a-108">**Примечание**. Если вы планируете синхронизировать контакты с поставщиками, клиентами или банковскими счетами в других частях приложения, может понадобиться настроить для них деловые отношения.</span><span class="sxs-lookup"><span data-stu-id="9528a-108">**Note:** If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="define-an-industry-group-code"></a><span data-ttu-id="9528a-109">Определение кода отраслевой группы</span><span class="sxs-lookup"><span data-stu-id="9528a-109">Define an Industry Group Code</span></span>
<span data-ttu-id="9528a-110">Код отраслевой группы определяет тип или категорию группы, например РЕКЛАМА для сферы рекламы или ПРЕССА для ТВ и радио.</span><span class="sxs-lookup"><span data-stu-id="9528a-110">The industry group code defines the type or category of the group, such as ADVERT for advertising, or PRESS, for TV and radio.</span></span> <span data-ttu-id="9528a-111">Допускается наличие нескольких кодов отраслевых групп.</span><span class="sxs-lookup"><span data-stu-id="9528a-111">You can have several industry group codes.</span></span> <span data-ttu-id="9528a-112">Для определения отраслевых групп используется окно **Отраслевые группы**.</span><span class="sxs-lookup"><span data-stu-id="9528a-112">To define the industry groups, you use the **Industry Groups** window.</span></span>

1. <span data-ttu-id="9528a-113">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Отраслевые группы**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="9528a-113">In the top right corner, choose the **Search for Page or Report** icon, enter **Industry Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="9528a-114">Выберите действие **Создать**, введите код и описание.</span><span class="sxs-lookup"><span data-stu-id="9528a-114">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="9528a-115">Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).</span><span class="sxs-lookup"><span data-stu-id="9528a-115">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <a name="assign-industry-groups-to-a-contact"></a><span data-ttu-id="9528a-116">Присвоение отраслевых групп контакту</span><span class="sxs-lookup"><span data-stu-id="9528a-116">Assign Industry Groups to a Contact</span></span>
<span data-ttu-id="9528a-117">Нельзя назначать отраслевые группы контактным лицам — только организациям.</span><span class="sxs-lookup"><span data-stu-id="9528a-117">You cannot assign industry groups to a contact person - only companies.</span></span>

1. <span data-ttu-id="9528a-118">Откройте контакт.</span><span class="sxs-lookup"><span data-stu-id="9528a-118">Open the contact.</span></span>
2. <span data-ttu-id="9528a-119">Выберите действие **Организация**, а затем действие **Отраслевые группы**.</span><span class="sxs-lookup"><span data-stu-id="9528a-119">Choose the **Company** action, and then the **Industry Groups** action.</span></span> <span data-ttu-id="9528a-120">Откроется окно **Отраслевые группы контакта**.</span><span class="sxs-lookup"><span data-stu-id="9528a-120">The **Contact Industry Groups** window opens.</span></span>
3. <span data-ttu-id="9528a-121">В поле **Код отраслевой группы** выберите отраслевую группу, которую нужно назначить.</span><span class="sxs-lookup"><span data-stu-id="9528a-121">In the **Industry Groups Code** field, select the industry groups you want to assign.</span></span>

<span data-ttu-id="9528a-122">Повторите эти шаги для назначения желаемого количества отраслевых групп.</span><span class="sxs-lookup"><span data-stu-id="9528a-122">Repeat these steps to assign as many industry groups as you want.</span></span> <span data-ttu-id="9528a-123">Также можно назначать отраслевые группы из списка контактов, следуя той же процедуре.</span><span class="sxs-lookup"><span data-stu-id="9528a-123">You can also assign industry groups from the contact list by following the same procedure.</span></span>

<span data-ttu-id="9528a-124">Число отраслевых групп, назначенных контакту, отображается в окне **Контакт** в разделе **Сегментация** в поле **Число отраслевых групп**.</span><span class="sxs-lookup"><span data-stu-id="9528a-124">The number of industry groups that you have assigned to the contact is displayed in the **No. of Industry Groups** field on the **Segmentation** section of the **Contact** window.</span></span>

<span data-ttu-id="9528a-125">После назначения контактам отраслевых групп эта информация может использоваться для выбора контактов для сегментов.</span><span class="sxs-lookup"><span data-stu-id="9528a-125">After you have assigned industry groups to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="9528a-126">Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="9528a-126">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="9528a-127">См. также</span><span class="sxs-lookup"><span data-stu-id="9528a-127">See Also</span></span>
[<span data-ttu-id="9528a-128">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="9528a-128">Create Contact Companies</span></span>](marketing-create-contact-companies.md)

