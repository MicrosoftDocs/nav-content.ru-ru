---
title: "Настройка деловых отношений в организациях контактов"
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
ms.openlocfilehash: 6616473a00e85e52648713d7e067f4b3b72caecf
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---
# <a name="set-up-business-relations-on-contact-companies"></a><span data-ttu-id="672ff-102">Настройка деловых отношений в организациях контактов</span><span class="sxs-lookup"><span data-stu-id="672ff-102">Set Up Business Relations on Contact Companies</span></span>
<span data-ttu-id="672ff-103">Деловые отношения используются для указания деловых отношений с контактами, например, с предполагаемым клиентом, банком, консультантом, поставщиком услуг и т. д.</span><span class="sxs-lookup"><span data-stu-id="672ff-103">You can use business relations to indicate the business relationship you have with your contacts, for example, a prospect, bank, consultant, service supplier, and so on.</span></span>

<span data-ttu-id="672ff-104">Использование деловых отношений для контактов — это двухэтапный процесс.</span><span class="sxs-lookup"><span data-stu-id="672ff-104">Using business relations on contacts is a two-step process.</span></span> <span data-ttu-id="672ff-105">Сначала вы определяете код делового отношения.</span><span class="sxs-lookup"><span data-stu-id="672ff-105">First, you define the business relation code.</span></span> <span data-ttu-id="672ff-106">Этот шаг нужно выполнить один раз для каждого делового отношения.</span><span class="sxs-lookup"><span data-stu-id="672ff-106">You only have to perform this step one time for each business relation.</span></span> <span data-ttu-id="672ff-107">После настройки кода делового отношения можно начинать назначение кода контактным организациям.</span><span class="sxs-lookup"><span data-stu-id="672ff-107">Once you have a business relation code, you can start to assign the code to contact companies.</span></span>

<span data-ttu-id="672ff-108">**Примечание**. Если вы планируете синхронизировать контакты с поставщиками, клиентами или банковскими счетами в других частях приложения, может понадобиться настроить для них деловые отношения.</span><span class="sxs-lookup"><span data-stu-id="672ff-108">**Note**: If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="define-a-business-relation-code"></a><span data-ttu-id="672ff-109">Определение кода делового отношения</span><span class="sxs-lookup"><span data-stu-id="672ff-109">Define a Business Relation Code</span></span>
<span data-ttu-id="672ff-110">Код деловых отношений определяет категорию или делового отношения, например БАНК или ЗАКОН.</span><span class="sxs-lookup"><span data-stu-id="672ff-110">The business relation code defines a category or type of the business relationship, such as BANK or LAW.</span></span> <span data-ttu-id="672ff-111">Допускается наличие нескольких кодов деловых отношений.</span><span class="sxs-lookup"><span data-stu-id="672ff-111">You can have several business relation codes.</span></span> <span data-ttu-id="672ff-112">Для определения делового отношения используется окно **Деловые отношения**.</span><span class="sxs-lookup"><span data-stu-id="672ff-112">To define the business relation, you use the **Business Relations** window.</span></span>

1. <span data-ttu-id="672ff-113">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Деловые отношения**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="672ff-113">In the top right corner, choose the **Search for Page or Report** icon, enter **Business Relations**, and then choose the related link.</span></span>
2. <span data-ttu-id="672ff-114">Выберите действие **Создать**, введите код и описание.</span><span class="sxs-lookup"><span data-stu-id="672ff-114">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="672ff-115">Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).</span><span class="sxs-lookup"><span data-stu-id="672ff-115">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <a name="assign-business-relations-to-a-contact"></a><span data-ttu-id="672ff-116">Назначение деловых отношений контакту</span><span class="sxs-lookup"><span data-stu-id="672ff-116">Assign Business Relations to a Contact</span></span>
<span data-ttu-id="672ff-117">Нельзя назначать деловые отношения контактным лицам — только организациям.</span><span class="sxs-lookup"><span data-stu-id="672ff-117">You cannot assign business relations to a contact person - only companies.</span></span>

1. <span data-ttu-id="672ff-118">Откройте контакт.</span><span class="sxs-lookup"><span data-stu-id="672ff-118">Open the contact.</span></span>
2. <span data-ttu-id="672ff-119">Выберите действие **Организация**, а затем действие **Деловые отношения**.</span><span class="sxs-lookup"><span data-stu-id="672ff-119">Choose the **Company** action, and then the **Business Relations** action.</span></span>

    <span data-ttu-id="672ff-120">Откроется окно **Деловые отношения контакта**.</span><span class="sxs-lookup"><span data-stu-id="672ff-120">The **Contact Business Relations** window opens.</span></span>
3. <span data-ttu-id="672ff-121">В поле **Код деловых отношений** выберите деловые отношения, которые нужно присвоить.</span><span class="sxs-lookup"><span data-stu-id="672ff-121">In the **Business Relation Code** field, select the business relation you want to assign.</span></span>

<span data-ttu-id="672ff-122">Повторите эти шаги для каждого делового отношения, чтобы назначить желаемое количество деловых отношений.</span><span class="sxs-lookup"><span data-stu-id="672ff-122">Repeat these steps to assign as many business relations as you want.</span></span> <span data-ttu-id="672ff-123">Также можно назначать деловые отношения в списке контактов, следуя той же процедуре.</span><span class="sxs-lookup"><span data-stu-id="672ff-123">You can also assign business relations from the contact list by following the same procedure.</span></span>

<span data-ttu-id="672ff-124">Количество деловых отношений, назначенных контакту, отображается в поле **Число деловых связей** в разделе **Сегментация** окна **Контакт**.</span><span class="sxs-lookup"><span data-stu-id="672ff-124">The number of business relations you have assigned to the contact is displayed in the **No. of Business Relations** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="672ff-125">После назначения контактам деловых отношений можно использовать эту информацию для выбора контактов для сегментов.</span><span class="sxs-lookup"><span data-stu-id="672ff-125">After you have assigned business relations to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="672ff-126">Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="672ff-126">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="672ff-127">См. также</span><span class="sxs-lookup"><span data-stu-id="672ff-127">See Also</span></span>
[<span data-ttu-id="672ff-128">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="672ff-128">Create Contact Companies</span></span>](marketing-create-contact-companies.md)

