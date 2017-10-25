---
title: "Сведения о проектировании — операции набора измерений"
description: "Документация содержит подробные технические сведения о концепциях и принципах, используемых для перегруппировки функции хранения и учета операций измерения."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, dimensions, codeunit
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8c285ae7af2fd6590f67e721c4e824f168528776
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-dimension-set-entries"></a><span data-ttu-id="b6860-103">Сведения о проектировании: операции набора измерений</span><span class="sxs-lookup"><span data-stu-id="b6860-103">Design Details: Dimension Set Entries</span></span>
<span data-ttu-id="b6860-104">Документация содержит подробные технические сведения о концепциях и принципах, используемых для перегруппировки функции хранения и учета операций измерения в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="b6860-104">This documentation provides detailed technical insight into the concepts and principles that are used to redesign the dimension entry storing and posting feature in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="b6860-105">В начале документа приводится концептуальный обзор переконструирования.</span><span class="sxs-lookup"><span data-stu-id="b6860-105">The documentation starts by describing conceptual overviews of the redesign.</span></span> <span data-ttu-id="b6860-106">Затем поясняется техническая архитектура с целью понять, как осуществляется перегруппировка.</span><span class="sxs-lookup"><span data-stu-id="b6860-106">Then it explains the technical architecture to show how the redesign is made.</span></span> <span data-ttu-id="b6860-107">Наконец, в ней приводятся примеры кода для подготовки к миграции и обновлению кодов измерений.</span><span class="sxs-lookup"><span data-stu-id="b6860-107">Finally, it provides code examples to prepare you for dimension code migration and upgrade.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="b6860-108">В этом разделе</span><span class="sxs-lookup"><span data-stu-id="b6860-108">In This Section</span></span>  
[<span data-ttu-id="b6860-109">Обзор записей набора измерений</span><span class="sxs-lookup"><span data-stu-id="b6860-109">Dimension Set Entries Overview</span></span>](design-details-dimension-set-entries-overview.md)  
[<span data-ttu-id="b6860-110">Сведения о проектировании: поиск комбинаций измерений</span><span class="sxs-lookup"><span data-stu-id="b6860-110">Design Details: Searching for Dimension Combinations</span></span>](design-details-searching-for-dimension-combinations.md)  
[<span data-ttu-id="b6860-111">Сведения о проектировании: структура таблицы</span><span class="sxs-lookup"><span data-stu-id="b6860-111">Design Details: Table Structure</span></span>](design-details-table-structure.md)  
[<span data-ttu-id="b6860-112">Сведения о проектировании: Codeunit 408 Dimension Management</span><span class="sxs-lookup"><span data-stu-id="b6860-112">Design Details: Codeunit 408 Dimension Management</span></span>](design-details-codeunit-408-dimension-management.md)  
[<span data-ttu-id="b6860-113">Сведения о проектировании: примеры кода измененных шаблонов в модификациях</span><span class="sxs-lookup"><span data-stu-id="b6860-113">Design Details: Code Examples of Changed Patterns in Modifications</span></span>](design-details-code-examples-of-changed-patterns-in-modifications.md)

