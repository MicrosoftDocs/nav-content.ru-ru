---
title: "Создание контактных организаций"
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
ms.openlocfilehash: e3490b10039f430137ee35f1a50c73111386fab4
ms.contentlocale: ru-ru
ms.lasthandoff: 09/11/2017

---
# <a name="create-contact-companies"></a><span data-ttu-id="ae240-102">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="ae240-102">Create Contact Companies</span></span>
<span data-ttu-id="ae240-103">Вы можете создать контакт для каждой новой организации, с которой происходит взаимодействие, например заказчика, поставщика, банка, юридической организации, консультанта и т. д.</span><span class="sxs-lookup"><span data-stu-id="ae240-103">You can create a contact for each new company you interact with, for example, a customer, vendor, prospective customer, bank, law firm, consultant, and so on.</span></span>

<span data-ttu-id="ae240-104">Есть два способа создания контактов: с нуля или на основе имеющегося клиента, поставщика или банковского счета.</span><span class="sxs-lookup"><span data-stu-id="ae240-104">There are two ways to create a contact: from scratch or from an existing customer, vendor, or bank account.</span></span>

<span data-ttu-id="ae240-105">Перед созданием контакта может понадобиться проверить настройки в окне **Маркетинг - настройка**.</span><span class="sxs-lookup"><span data-stu-id="ae240-105">Before creating a contact, you may want to check the settings in the **Marketing Setup** window.</span></span> <span data-ttu-id="ae240-106">Дополнительные сведения см. в разделе [Настройка маркетинга и управление контактами](marketing-setup-marketing.md).</span><span class="sxs-lookup"><span data-stu-id="ae240-106">For more information, see [Set Up Marketing and Contact Management](marketing-setup-marketing.md).</span></span>

## <a name="create-a-company-contact-from-scratch"></a><span data-ttu-id="ae240-107">Создание контакта организации с нуля</span><span class="sxs-lookup"><span data-stu-id="ae240-107">Create a company contact from scratch</span></span>
1. <span data-ttu-id="ae240-108">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Контакты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="ae240-108">In the top right corner, choose the **Search for Page or Report** icon, enter **Contacts**, and then choose the related link.</span></span>
2. <span data-ttu-id="ae240-109">Выберите действие **Создать**.</span><span class="sxs-lookup"><span data-stu-id="ae240-109">Choose the **New** action.</span></span>
3. <span data-ttu-id="ae240-110">В поле **Номер** введите номер контакта.</span><span class="sxs-lookup"><span data-stu-id="ae240-110">In the **No. field**, enter a number for the contact.</span></span>

  <span data-ttu-id="ae240-111">Вместо этого, если настроены серии номеров для контактов в окне **Маркетинг - настройка**, можно нажать клавишу ВВОД, чтобы выбрать следующий доступный номер контакта.</span><span class="sxs-lookup"><span data-stu-id="ae240-111">Alternatively, if you have set up a number series for contacts in the **Marketing Setup** window, you can press the Enter key to select the next available contact number.</span></span>
4. <span data-ttu-id="ae240-112">В поле **Тип** выберите **Организация**.</span><span class="sxs-lookup"><span data-stu-id="ae240-112">Set **Type** to **Company**.</span></span>
5. <span data-ttu-id="ae240-113">Заполните остальные поля соответствующим образом.</span><span class="sxs-lookup"><span data-stu-id="ae240-113">Fill in the other fields as required.</span></span>

## <a name="create-a-company-contact-from-a-customer-vendor-or-bank-account"></a><span data-ttu-id="ae240-114">Создание контакта организации из клиента, поставщика или банковского счета</span><span class="sxs-lookup"><span data-stu-id="ae240-114">Create a company contact from a customer, vendor, or bank account</span></span>
<span data-ttu-id="ae240-115">Если вы уже создали какое-либо количество клиентов, поставщиков и банковских счетов, можно создавать контакты на основе имеющихся данных.</span><span class="sxs-lookup"><span data-stu-id="ae240-115">If you have already set up a number of customers, vendors, and bank accounts, you can create contacts on the basis of the existing data.</span></span> <span data-ttu-id="ae240-116">При создании контакта таким способом сведения о контакте синхронизируются с клиентом, поставщиком или банковским счетом.</span><span class="sxs-lookup"><span data-stu-id="ae240-116">When you create a contact this way, the contact information is synchronized with the customer, vendor, or bank account information.</span></span>

<span data-ttu-id="ae240-117">**Примечание**. Прежде чем можно будет создавать контактные организации таким образом, необходимо указать код деловых отношений для клиентов, поставщиков или банковских счетов в окне **Настройка модуля "Маркетинг"**.</span><span class="sxs-lookup"><span data-stu-id="ae240-117">**Note**: Before you can create contact companies this way, you must specify a business relation code for customers, vendors, and bank accounts in the **Marketing Setup** window.</span></span> <span data-ttu-id="ae240-118">Если вы будет создавать контакты из банковских счетов, вы должны также указать серии номеров для банковских счетов в окне **Настройка ГК**.</span><span class="sxs-lookup"><span data-stu-id="ae240-118">If you will be creating contacts from a bank accounts, you must also specify numbers series for bank accounts in the **General Ledger Setup** window.</span></span>

1. <span data-ttu-id="ae240-119">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите одно из следующих значений в зависимости от того, откуда требуется создать контакты, а затем выберите соответствующую ссылку.</span><span class="sxs-lookup"><span data-stu-id="ae240-119">In the top right corner, choose the **Search for Page or Report** icon, enter one of the following, depending on from where you want to create contacts, and then choose the related link.</span></span>
  * <span data-ttu-id="ae240-120">**Создать контакты из клиентов**</span><span class="sxs-lookup"><span data-stu-id="ae240-120">**Create Contacts from Customers**</span></span>
  * <span data-ttu-id="ae240-121">**Создать контакты из поставщиков**</span><span class="sxs-lookup"><span data-stu-id="ae240-121">**Create Contacts from Vendors**</span></span>
  * <span data-ttu-id="ae240-122">**Создать контакты из банк. счетов**</span><span class="sxs-lookup"><span data-stu-id="ae240-122">**Create Contacts from Bank Accounts**</span></span>
2. <span data-ttu-id="ae240-123">В открывшемся окне пакетного задания в разделе **Клиент**, **Поставщик** или **Банковский счет** установите фильтры, если требуется создать контакты из конкретных клиентов, поставщиков или банковских счетов.</span><span class="sxs-lookup"><span data-stu-id="ae240-123">In the batch job window that opens, in the **Customer**, **Vendor**, or **Bank Account** section, set filters if you want to create contacts from specific customers, vendors, or bank accounts.</span></span>
3. <span data-ttu-id="ae240-124">Нажмите кнопку **ОК** для начала создания контактов.</span><span class="sxs-lookup"><span data-stu-id="ae240-124">Choose the **OK** button to start creating contacts.</span></span>

  <span data-ttu-id="ae240-125">Новым контактам присваиваются следующие номера контактов из серии номеров.</span><span class="sxs-lookup"><span data-stu-id="ae240-125">The next contact numbers in the number series are assigned to the new contacts.</span></span> <span data-ttu-id="ae240-126">Деловое отношение поставщиков, указанное в окне **Настройка модуля "Маркетинг"**, назначается созданным новым контактам.</span><span class="sxs-lookup"><span data-stu-id="ae240-126">The business relation for vendors that is specified in the **Marketing Setup** window is assigned to the newly created contacts.</span></span>

<span data-ttu-id="ae240-127">**Совет**. Вы также можете создать клиента, поставщика или банковский счет из контакта.</span><span class="sxs-lookup"><span data-stu-id="ae240-127">**Tip**: You can also create a customer, vendor, or bank account from a contact.</span></span> <span data-ttu-id="ae240-128">Дополнительные сведения см. в разделе [Создание клиента, поставщика или банковского счета из клиента](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).</span><span class="sxs-lookup"><span data-stu-id="ae240-128">For more information, see [Create a Customer, Vendor, or Bank Account From a Contact](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).</span></span>
##<a name="see-also"></a><span data-ttu-id="ae240-129">См. также</span><span class="sxs-lookup"><span data-stu-id="ae240-129">See Also</span></span>
[<span data-ttu-id="ae240-130">Синхронизация контактов с клиентами, поставщиками и банковскими счетами</span><span class="sxs-lookup"><span data-stu-id="ae240-130">Synchronizing Contacts With Customers, Vendors, and Bank Accounts</span></span>](marketing-synchronize-contacts-customers-vendors-bank-accounts.md)  
[<span data-ttu-id="ae240-131">Назначение деловых отношений контакту</span><span class="sxs-lookup"><span data-stu-id="ae240-131">Assign Business Relations to a Contact</span></span>](marketing-business-relations.md#assign-business-relations-to-a-contact)  
[<span data-ttu-id="ae240-132">Присвоение отраслевых групп контакту</span><span class="sxs-lookup"><span data-stu-id="ae240-132">Assign Industry Groups to a Contact</span></span>](marketing-industry-groups.md#assign-industry-groups-to-a-contact)  
[<span data-ttu-id="ae240-133">Назначение групп рассылки контакту</span><span class="sxs-lookup"><span data-stu-id="ae240-133">Assign Mailing Groups to a Contact</span></span>](marketing-mailing-groups.md#assign-mailing-groups-to-a-contact)  
[<span data-ttu-id="ae240-134">Как создать контактные лица</span><span class="sxs-lookup"><span data-stu-id="ae240-134">How to: Create Contact Persons</span></span>](marketing-create-contact-persons.md)  

