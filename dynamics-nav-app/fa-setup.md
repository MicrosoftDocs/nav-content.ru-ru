---
title: "Настройка основных средств"
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
ms.openlocfilehash: 954c20f713752774bc3a7c0bc10d625962d1ccc2
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="set-up-fixed-assets"></a><span data-ttu-id="8fd22-102">Настройка основных средств</span><span class="sxs-lookup"><span data-stu-id="8fd22-102">Set Up Fixed Assets</span></span>
<span data-ttu-id="8fd22-103">Чтобы можно было использовать функции модуля основных средств, необходимо настроить различные сведения для определения порядка страхования, обслуживания и амортизации основных средств, а также способа регистрации затрат и других сумм в главной книге.</span><span class="sxs-lookup"><span data-stu-id="8fd22-103">Before you can use the Fixed Assets functionality, you must set up various information to define how you insure, maintain, and depreciate fixed assets, and how costs and other values are recorded in the general ledger.</span></span>

<span data-ttu-id="8fd22-104">После выполнения настройки основных средств можно выполнять различные соответствующие действия.</span><span class="sxs-lookup"><span data-stu-id="8fd22-104">When you have set up Fixed Assets, you can perform the various activities involved.</span></span> <span data-ttu-id="8fd22-105">Дополнительные сведения см. в разделе [Практическое руководство. Управление основными средствами](fa-manage.md).</span><span class="sxs-lookup"><span data-stu-id="8fd22-105">For more information, see [How to: Manage Fixed Assets](fa-manage.md).</span></span>

<span data-ttu-id="8fd22-106">**Примечание**. Можно записывать транзакции основного средства в окне **Журнал ГК учета основных средств** или в окне **Журнал ОС**, в зависимости от назначения транзакций: для финансовой отчетности или для внутреннего управления.</span><span class="sxs-lookup"><span data-stu-id="8fd22-106">**Note**: You can record fixed asset transactions in the **Fixed Asset G/L Journal** window or in the **Fixed Asset Journal** window, depending on whether the transactions are for financial reporting or for internal management.</span></span> <span data-ttu-id="8fd22-107">В справке для основных средств описывается только использование окна **Журнал ГК учета основных средств**.</span><span class="sxs-lookup"><span data-stu-id="8fd22-107">Help for Fixed Assets only describes how to use the **Fixed Asset G/L Journal** window.</span></span>

<span data-ttu-id="8fd22-108">Если установлен флажок для действия основного средства в разделе **Интеграция С ГК** в окне **Карточка книги амортизации**, окно **Журнал ГК учета основных средств** будет использоваться для учета транзакций для соответствующего действия.</span><span class="sxs-lookup"><span data-stu-id="8fd22-108">When you select a check box for a fixed asset activity in the **G/L Integration** section in the **Depreciation Book Card** window, then the **Fixed Asset G/L Journal** window will be used to post transactions for the activity in question.</span></span>

<span data-ttu-id="8fd22-109">В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.</span><span class="sxs-lookup"><span data-stu-id="8fd22-109">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

| <span data-ttu-id="8fd22-110">Действие</span><span class="sxs-lookup"><span data-stu-id="8fd22-110">To</span></span> | <span data-ttu-id="8fd22-111">Ссылка</span><span class="sxs-lookup"><span data-stu-id="8fd22-111">See</span></span> |  
|----|-----|  
|<span data-ttu-id="8fd22-112">Настройте счета ГК по умолчанию, ключи распределения, шаблоны и разделы журналов для учета основных средств, а также настройте классы и подклассы основных средств, такие как материальные и нематериальные основные средства.</span><span class="sxs-lookup"><span data-stu-id="8fd22-112">Set up default G/L accounts, allocation keys, journal templates and batches for fixed asset posting, and set up fixed asset classes and subclasses, such as Tangible and Intangible.</span></span>|[<span data-ttu-id="8fd22-113">Практическое руководство. Настройка общих данных основных средств</span><span class="sxs-lookup"><span data-stu-id="8fd22-113">How to: Set Up General Fixed Assets Information</span></span>](fa-how-setup-general.md)|  
|<span data-ttu-id="8fd22-114">Создайте книги амортизации, определите различные методы амортизации, выполните интеграцию с главной книгой и включите дублирование операций в нескольких книгах амортизации.</span><span class="sxs-lookup"><span data-stu-id="8fd22-114">Create depreciation books, define various depreciation methods, integrate with the general ledger, and enable duplication of entries in several depreciation books.</span></span>|[<span data-ttu-id="8fd22-115">Практическое руководство. Настройка амортизации основных средств</span><span class="sxs-lookup"><span data-stu-id="8fd22-115">How to: Set Up Fixed Asset Depreciation</span></span>](fa-how-setup-depreciation.md)|
|<span data-ttu-id="8fd22-116">Включите страхование основных средств, настройте общие сведения о страховании, страховую карточку для каждого полиса, а также подготовьте журналы для учета затрат на страхование.</span><span class="sxs-lookup"><span data-stu-id="8fd22-116">Enable insurance of fixed assets, set up general insurance information, an insurance card per policy, and prepare journals to post insurance costs.</span></span>|[<span data-ttu-id="8fd22-117">Практическое руководство. Настройка страхования основных средств</span><span class="sxs-lookup"><span data-stu-id="8fd22-117">How to: Set Up Fixed Asset Insurance</span></span>](fa-how-setup-insurance.md)|
|<span data-ttu-id="8fd22-118">Включите обслуживание основных средств, настройте общие сведения об обслуживании, настройте счета учета обслуживания и определите типы работ по техническому обслуживанию.</span><span class="sxs-lookup"><span data-stu-id="8fd22-118">Enable maintenance of fixed assets, set up general maintenance information, set up maintenance posting accounts, and define types of maintenance work.</span></span>|[<span data-ttu-id="8fd22-119">Практическое руководство. Настройка обслуживания основных средств</span><span class="sxs-lookup"><span data-stu-id="8fd22-119">How to: Set Up Fixed Asset Maintenance</span></span>](fa-how-setup-maintenance.md)|
|<span data-ttu-id="8fd22-120">Изучите различные методы расчета амортизации основных средств.</span><span class="sxs-lookup"><span data-stu-id="8fd22-120">Learn about different fixed asset depreciation methods.</span></span>|[<span data-ttu-id="8fd22-121">Методы амортизации</span><span class="sxs-lookup"><span data-stu-id="8fd22-121">Depreciation Methods</span></span>](fa-depreciation-methods.md)|

## <a name="see-also"></a><span data-ttu-id="8fd22-122">См. также</span><span class="sxs-lookup"><span data-stu-id="8fd22-122">See Also</span></span>
[<span data-ttu-id="8fd22-123">Управление основными средствами</span><span class="sxs-lookup"><span data-stu-id="8fd22-123">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="8fd22-124">Финансы</span><span class="sxs-lookup"><span data-stu-id="8fd22-124">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="8fd22-125">Добро пожаловать в Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="8fd22-125">Welcome to Dynamics NAV</span></span>](across-get-started.md)

