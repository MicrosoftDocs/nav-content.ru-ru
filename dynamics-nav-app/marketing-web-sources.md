---
title: "Настройка веб-источников для контактных организаций"
author: edupont04
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: eeb05b22a14917d759dadfe29957568baea6db34
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---
# <a name="set-up-web-sources-for-contact-companies"></a><span data-ttu-id="94cf1-102">Настройка веб-источников для контактных организаций</span><span class="sxs-lookup"><span data-stu-id="94cf1-102">Set Up Web Sources for Contact Companies</span></span>
<span data-ttu-id="94cf1-103">Можно присваивать веб-источники с контактными организациям, чтобы определять, например, поисковые системы и веб-сайты в Интернете, которые должны использоваться для поиска информации о контактах.</span><span class="sxs-lookup"><span data-stu-id="94cf1-103">You can use web sources with your contact companies to identify, for example, search engines and web sites, on the Internet that you want to use to search for information about the contacts.</span></span> <span data-ttu-id="94cf1-104">При присвоении веб-источников указывается, какую поисковую систему и какое слово поиска приложение использует для поиска требуемой информации.</span><span class="sxs-lookup"><span data-stu-id="94cf1-104">When assigning web sources, you specify which search engine and search word the application will use to find the requested information.</span></span>

<span data-ttu-id="94cf1-105">Использование веб-источников для контактов — это двухэтапный процесс.</span><span class="sxs-lookup"><span data-stu-id="94cf1-105">Using web sources on contacts is a two-step process.</span></span> <span data-ttu-id="94cf1-106">Сначала вы определяете код веб-источника.</span><span class="sxs-lookup"><span data-stu-id="94cf1-106">First, you define the web source code.</span></span> <span data-ttu-id="94cf1-107">Этот шаг нужно выполнить один раз для каждого веб-источника.</span><span class="sxs-lookup"><span data-stu-id="94cf1-107">You only have to perform this step one time for each web source.</span></span> <span data-ttu-id="94cf1-108">После настройки кода веб-источника можно начинать назначение кода контактным лицам.</span><span class="sxs-lookup"><span data-stu-id="94cf1-108">Once you have a web source code, you can start to assign the code to contact persons.</span></span>

## <a name="define-a-web-source-code"></a><span data-ttu-id="94cf1-109">Определение кода веб-источника</span><span class="sxs-lookup"><span data-stu-id="94cf1-109">Define a Web Source Code</span></span>
1. <span data-ttu-id="94cf1-110">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Веб-источники**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="94cf1-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Web Sources**, and then choose the related link.</span></span>
2. <span data-ttu-id="94cf1-111">Выберите действия **Создать**.</span><span class="sxs-lookup"><span data-stu-id="94cf1-111">Choose the **New** actions.</span></span>
3. <span data-ttu-id="94cf1-112">Заполните поля **Код**, **Описание** и **URL-адрес**.</span><span class="sxs-lookup"><span data-stu-id="94cf1-112">Fill in the **Code**, **Description**, and **URL** fields.</span></span>

  <span data-ttu-id="94cf1-113">В поле **URL-адрес** введите %1 для вставки заполнителя для слова поиска в URL-адрес.</span><span class="sxs-lookup"><span data-stu-id="94cf1-113">Type %1 in the **URL** field to insert a placeholder for a search word in the URL.</span></span> <span data-ttu-id="94cf1-114">При запуске веб-источника из контакта %1 заменяется на слово поиска (например, на название организации), которое было введено в окне **Веб-источники контакта**.</span><span class="sxs-lookup"><span data-stu-id="94cf1-114">When you launch the web source from a contact, the %1 is replaced with the search word, for example, the name of the company that you have entered in the **Contact Web Sources** window.</span></span>

<span data-ttu-id="94cf1-115">Повторите эти шаги, чтобы настроить необходимое количество веб-источников.</span><span class="sxs-lookup"><span data-stu-id="94cf1-115">Repeat these steps to set up as many web sources as you want.</span></span>

## <a name="assign-web-sources-to-a-contact-company"></a><span data-ttu-id="94cf1-116">Назначение веб-источников контактной организации</span><span class="sxs-lookup"><span data-stu-id="94cf1-116">Assign Web Sources to a Contact Company</span></span>
<span data-ttu-id="94cf1-117">При назначении веб-источников вы указываете, какую поисковую систему и какое слово поиска приложение будет использовать для поиска требуемой информации.</span><span class="sxs-lookup"><span data-stu-id="94cf1-117">When assigning web sources, you specify which search engine and search word that the application will use to find the requested information.</span></span>

1. <span data-ttu-id="94cf1-118">Откройте контакт.</span><span class="sxs-lookup"><span data-stu-id="94cf1-118">Open the contact.</span></span>
2. <span data-ttu-id="94cf1-119">Выберите действие **Организация**, а затем — действие **Веб-источники**.</span><span class="sxs-lookup"><span data-stu-id="94cf1-119">Choose the **Company** action, and then choose the **Web Sources** action.</span></span> <span data-ttu-id="94cf1-120">Откроется окно **Веб-источники контакта**.</span><span class="sxs-lookup"><span data-stu-id="94cf1-120">The **Contact Web Sources** window opens.</span></span>
3. <span data-ttu-id="94cf1-121">В поле **Код веб-источника** выберите веб-источник, который нужно назначить.</span><span class="sxs-lookup"><span data-stu-id="94cf1-121">In the **Web Source Code** field, choose the web source you want to assign.</span></span>
4. <span data-ttu-id="94cf1-122">В поле **Поиск слова** введите искомое слово, используемое для поиска информации.</span><span class="sxs-lookup"><span data-stu-id="94cf1-122">In the **Search Word** field, enter the search word that you want to use to find the information.</span></span>

<span data-ttu-id="94cf1-123">Повторите эти шаги для назначения желаемого количества веб-источников.</span><span class="sxs-lookup"><span data-stu-id="94cf1-123">Repeat these steps to assign as many web sources as you want.</span></span>

<span data-ttu-id="94cf1-124">Также можно назначать веб-источники в окне **Список контактов**, следуя той же процедуре.</span><span class="sxs-lookup"><span data-stu-id="94cf1-124">You can also assign web sources from the **Contact List** window by following the same procedure.</span></span>

##<a name="see-also"></a><span data-ttu-id="94cf1-125">См. также</span><span class="sxs-lookup"><span data-stu-id="94cf1-125">See Also</span></span>
[<span data-ttu-id="94cf1-126">Создание контактных организаций</span><span class="sxs-lookup"><span data-stu-id="94cf1-126">Create Contact Companies</span></span>](marketing-create-contact-companies.md)

