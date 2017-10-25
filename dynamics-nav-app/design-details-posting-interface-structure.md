---
title: "Сведения о проектировании — структура интерфейса учета"
description: "В этом разделе приведен обзор глобальных процедур в структуре интерфейса учета."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: posting, interface, design
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cc5efca8087bc24ab988ae592a9ba60e4caf46bb
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-posting-interface-structure"></a>Сведения о проектировании: структура интерфейса учета
В структуре интерфейса учета [!INCLUDE[d365fin](includes/d365fin_md.md)] существует несколько глобальных процедур, использующих одну и ту же структуру:  
  
* RunWithCheck и RunWithoutCheck вызывают код процедуры — универсальный интерфейс учета для строки финансового журнала.  
* CustPostApplyCustLedgEntry — учет применения клиента, вызываемого из модуля codeunit 226 CustEntry "Применение учтенных операций".  
* VendPostApplyVendLedgEntry — учет применения поставщика, вызываемого из модуля codeunit 227 VendEntry "Применение учтенных операций".  
* UnapplyCustLedgEntry — отмена учета применения клиента, вызываемого из модуля codeunit 226 CustEntry "Применение учтенных операций".  
* UnapplyVendLedgEntry — отмена учета применения поставщика, вызываемого из модуля codeunit 227 VendEntry "Применение учтенных операций".  
  
## <a name="see-also"></a>См. также  
[Сведения о проектировании: структура механизма учета](design-details-posting-engine-structure.md)
