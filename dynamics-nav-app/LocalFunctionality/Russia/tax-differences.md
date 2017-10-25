---
title: "Налоговые разницы"
description: "Налоговые разницы представляют собой расхождения сумм налога, вызванные различиями в правилах признания доходов и расходов в бухгалтерском и налоговом учете."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 565058c3b8f6fd5179ba33080ad37b0f5995fe91
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="tax-differences"></a><span data-ttu-id="b33cb-103">Налоговые разницы</span><span class="sxs-lookup"><span data-stu-id="b33cb-103">Tax Differences</span></span>
<span data-ttu-id="b33cb-104">Налоговые разницы представляют собой расхождения сумм налога, вызванные различиями в правилах признания доходов и расходов в бухгалтерском и налоговом учете.</span><span class="sxs-lookup"><span data-stu-id="b33cb-104">Tax differences are variations in tax amounts caused by the different rules for recognizing income and expenses between entries for book accounting and tax accounting.</span></span>  
  
 <span data-ttu-id="b33cb-105">В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно настроить регистры налоговых разниц и журналы налоговых разниц для отслеживания и управления разницами между суммами бухгалтерского и налогового учета.</span><span class="sxs-lookup"><span data-stu-id="b33cb-105">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can set up tax difference registers and tax difference journals to track and manage differences between book accounting and tax accounting amounts.</span></span>  
  
## <a name="preparing-the-chart-of-accounts"></a><span data-ttu-id="b33cb-106">Подготовка плана счетов</span><span class="sxs-lookup"><span data-stu-id="b33cb-106">Preparing the Chart of Accounts</span></span>  
 <span data-ttu-id="b33cb-107">Перед настройкой налоговых разниц необходимо убедиться, что план счетов настроен для корректной обработки налогового учета и налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="b33cb-107">Before you set up tax differences, you will have to make sure that your chart of accounts is set up to correctly handle tax accounting and tax differences.</span></span> <span data-ttu-id="b33cb-108">Как минимум план счетов должен содержать счет налоговых разниц для транзакций доходов и расходов.</span><span class="sxs-lookup"><span data-stu-id="b33cb-108">At a minimum, your chart of accounts must contain tax difference accounts for income and expense transactions.</span></span>  
  
## <a name="getting-started-with-tax-differences"></a><span data-ttu-id="b33cb-109">Начало работы с налоговыми разницами</span><span class="sxs-lookup"><span data-stu-id="b33cb-109">Getting Started with Tax Differences</span></span>  
 <span data-ttu-id="b33cb-110">Для настройки и просмотра операций налоговые разниц используются следующие таблицы, поддерживающие окна налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="b33cb-110">To set up and view tax difference entries, you will use the following tables, which support tax differences windows.</span></span>  
  
|<span data-ttu-id="b33cb-111">Окно</span><span class="sxs-lookup"><span data-stu-id="b33cb-111">Window</span></span>|<span data-ttu-id="b33cb-112">ADD INCLUDE<!--[!INCLUDE[bp_tabledescription](../../includes/bp_tabledescription_md.md)]--></span><span class="sxs-lookup"><span data-stu-id="b33cb-112">ADD INCLUDE<!--[!INCLUDE[bp_tabledescription](../../includes/bp_tabledescription_md.md)]--></span></span>|  
|------------|---------------------------------------|  
|<span data-ttu-id="b33cb-113">Учетная группа налоговой разницы</span><span class="sxs-lookup"><span data-stu-id="b33cb-113">Tax Diff. Posting Group</span></span>|<span data-ttu-id="b33cb-114">Определяет учетные группы для транзакций налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="b33cb-114">Specifies posting groups for tax difference transactions.</span></span>|  
|<span data-ttu-id="b33cb-115">Шаблон налоговых разниц</span><span class="sxs-lookup"><span data-stu-id="b33cb-115">Tax Diff. Journal Template</span></span>|<span data-ttu-id="b33cb-116">Определяет журналы, используемые для учета операций налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="b33cb-116">Specifies the journals that are used for posting tax difference entries.</span></span>|  
|<span data-ttu-id="b33cb-117">Операция корресп. налогового расчета</span><span class="sxs-lookup"><span data-stu-id="b33cb-117">Tax Calc. Corresp. Entry</span></span>|<span data-ttu-id="b33cb-118">Определяет данные налоговой разницы, необходимые для внешних отчетов и форм.</span><span class="sxs-lookup"><span data-stu-id="b33cb-118">Specifies tax difference information that is needed for external reports and forms.</span></span>|  
|<span data-ttu-id="b33cb-119">Строка налоговых разниц</span><span class="sxs-lookup"><span data-stu-id="b33cb-119">Tax Diff. Journal Line</span></span>|<span data-ttu-id="b33cb-120">Определяет учтенные операции журнала налоговых разниц.</span><span class="sxs-lookup"><span data-stu-id="b33cb-120">Specifies posted tax difference journal entries.</span></span>|  
  
## <a name="see-also"></a><span data-ttu-id="b33cb-121">См. также</span><span class="sxs-lookup"><span data-stu-id="b33cb-121">See Also</span></span>  
 <span data-ttu-id="b33cb-122">[Настройка расчета налоговых разниц](setting-up-tax-difference-calculation.md) </span><span class="sxs-lookup"><span data-stu-id="b33cb-122">[Setting up Tax Difference Calculation](setting-up-tax-difference-calculation.md) </span></span>  
 <span data-ttu-id="b33cb-123">[Регистры налоговых разниц](tax-difference-registers.md) </span><span class="sxs-lookup"><span data-stu-id="b33cb-123">[Tax Difference Registers](tax-difference-registers.md) </span></span>  
 <span data-ttu-id="b33cb-124">[Налоговые отчеты](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span><span class="sxs-lookup"><span data-stu-id="b33cb-124">[Tax Reports](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3) </span></span>  
 <span data-ttu-id="b33cb-125">[Налоговый учет](tax-accounting.md) </span><span class="sxs-lookup"><span data-stu-id="b33cb-125">[Tax Accounting](tax-accounting.md) </span></span>  
 [<span data-ttu-id="b33cb-126">Налоговые регистры</span><span class="sxs-lookup"><span data-stu-id="b33cb-126">Tax Registers</span></span>](tax-registers.md)
