---
title: "Определение кодов деловых отношений для контактов"
description: "Деловые отношения в Dynamics NAV помогают в маркетинге и показывают ваши деловые отношения с потенциальными и текущими клиентами и партнерами, например с банком или с поставщиком услуг."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: marketing, prospect, contact, client, customer
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 36e77c794e7aa92d5d323d93a7703359018efd39
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-business-relations-on-contact-companies"></a><span data-ttu-id="aac42-103">Настройка деловых отношений в организациях контактов</span><span class="sxs-lookup"><span data-stu-id="aac42-103">Setting Up Business Relations on Contact Companies</span></span>
<span data-ttu-id="aac42-104">Деловые отношения используются для указания деловых отношений с контактами, например, с предполагаемым клиентом, банком, консультантом, поставщиком услуг и т. д.</span><span class="sxs-lookup"><span data-stu-id="aac42-104">You can use business relations to indicate the business relationship you have with your contacts, for example, a prospect, bank, consultant, service supplier, and so on.</span></span>

<span data-ttu-id="aac42-105">Использование деловых отношений для контактов — это двухэтапный процесс.</span><span class="sxs-lookup"><span data-stu-id="aac42-105">Using business relations on contacts is a two-step process.</span></span> <span data-ttu-id="aac42-106">Сначала вы определяете код делового отношения.</span><span class="sxs-lookup"><span data-stu-id="aac42-106">First, you define the business relation code.</span></span> <span data-ttu-id="aac42-107">Этот шаг нужно выполнить один раз для каждого делового отношения.</span><span class="sxs-lookup"><span data-stu-id="aac42-107">You only have to perform this step one time for each business relation.</span></span> <span data-ttu-id="aac42-108">После настройки кода делового отношения можно начинать назначение кода контактным организациям.</span><span class="sxs-lookup"><span data-stu-id="aac42-108">Once you have a business relation code, you can start to assign the code to contact companies.</span></span>

> [!NOTE]  
>   <span data-ttu-id="aac42-109">При планировании синхронизации контактов с поставщиками, клиентами или банковскими счетами в других частях приложения может понадобиться настроить для них деловое отношение.</span><span class="sxs-lookup"><span data-stu-id="aac42-109">If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="to-define-a-business-relation-code"></a><span data-ttu-id="aac42-110">Определение кода делового отношения</span><span class="sxs-lookup"><span data-stu-id="aac42-110">To define a business relation code</span></span>
<span data-ttu-id="aac42-111">Код деловых отношений определяет категорию или тип делового отношения, например "БАНК" или "Закон".</span><span class="sxs-lookup"><span data-stu-id="aac42-111">The business relation code defines a category or type of the business relationship, such as BANK or Law.</span></span> <span data-ttu-id="aac42-112">Допускается наличие нескольких кодов деловых отношений.</span><span class="sxs-lookup"><span data-stu-id="aac42-112">You can have several business relation codes.</span></span> <span data-ttu-id="aac42-113">Для определения делового отношения используется окно **Деловые отношения**.</span><span class="sxs-lookup"><span data-stu-id="aac42-113">To define the business relation, you use the **Business Relations** window.</span></span>

1. <span data-ttu-id="aac42-114">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Деловые отношения**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="aac42-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Relations**, and then choose the related link.</span></span>
2. <span data-ttu-id="aac42-115">Выберите действие **Создать**, введите код и описание.</span><span class="sxs-lookup"><span data-stu-id="aac42-115">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="aac42-116">Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).</span><span class="sxs-lookup"><span data-stu-id="aac42-116">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <span data-ttu-id="aac42-117"><a name="AssignBusRelContact"></a> Назначение деловых отношений контакту</span><span class="sxs-lookup"><span data-stu-id="aac42-117"><a name="AssignBusRelContact"></a> To assign business relations to a contact</span></span>
<span data-ttu-id="aac42-118">Нельзя назначать деловые отношения контактным лицам — только организациям.</span><span class="sxs-lookup"><span data-stu-id="aac42-118">You cannot assign business relations to a contact person - only companies.</span></span>

1. <span data-ttu-id="aac42-119">Откройте контакт.</span><span class="sxs-lookup"><span data-stu-id="aac42-119">Open the contact.</span></span>
2. <span data-ttu-id="aac42-120">Выберите действие **Организация**, а затем действие **Деловые отношения**.</span><span class="sxs-lookup"><span data-stu-id="aac42-120">Choose the **Company** action, and then the **Business Relations** action.</span></span>

    <span data-ttu-id="aac42-121">Откроется окно **Деловые отношения контакта**.</span><span class="sxs-lookup"><span data-stu-id="aac42-121">The **Contact Business Relations** window opens.</span></span>
3. <span data-ttu-id="aac42-122">В поле **Код деловых отношений** выберите деловые отношения, которые нужно присвоить.</span><span class="sxs-lookup"><span data-stu-id="aac42-122">In the **Business Relation Code** field, select the business relation you want to assign.</span></span>

<span data-ttu-id="aac42-123">Повторите эти шаги для каждого делового отношения, чтобы назначить желаемое количество деловых отношений.</span><span class="sxs-lookup"><span data-stu-id="aac42-123">Repeat these steps to assign as many business relations as you want.</span></span> <span data-ttu-id="aac42-124">Также можно назначать деловые отношения в списке контактов, следуя той же процедуре.</span><span class="sxs-lookup"><span data-stu-id="aac42-124">You can also assign business relations from the contact list by following the same procedure.</span></span>

<span data-ttu-id="aac42-125">Количество деловых отношений, назначенных контакту, отображается в поле **Число деловых связей** в разделе **Сегментация** окна **Контакт**.</span><span class="sxs-lookup"><span data-stu-id="aac42-125">The number of business relations you have assigned to the contact is displayed in the **No. of Business Relations** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="aac42-126">После назначения контактам деловых отношений можно использовать эту информацию для выбора контактов для сегментов.</span><span class="sxs-lookup"><span data-stu-id="aac42-126">After you have assigned business relations to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="aac42-127">Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="aac42-127">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="aac42-128">См. также</span><span class="sxs-lookup"><span data-stu-id="aac42-128">See Also</span></span>
[<span data-ttu-id="aac42-129">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="aac42-129">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
<span data-ttu-id="aac42-130">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="aac42-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

