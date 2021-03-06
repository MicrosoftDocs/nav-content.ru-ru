---
title: "Сведения о проектировании — спрос и поставка"
description: "В этом разделе вводится концепция спроса — это общий термин, используемый для любого типа общего спроса, такого как заказ на продажу и требуемый компонент в производственном заказе."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, demand, supply, inventory, planning
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d744b55835f5553e249a536e0fca0eb0046fda7b
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-demand-and-supply"></a>Сведения о проектировании: спрос и поставка
Спрос — это общий термин, используемый для любого типа общего спроса, такого как заказ на продажу и требуемый компонент в производственном заказе. Кроме того, в программе предусмотрены более технические типы спроса, например отрицательные остатки и возврат покупки.  
  
Предложение — это общий термин, используемый для любого положительного или входящего количества, такого как запасы, покупки, сборка, производство или входящие перемещения. Кроме того, возврат продажи также может представлять поставку.  
  
Для сортировки многочисленных источников спроса и предложения система планирования организует их в два временных ряда, которые называются профилями склада. В одном профиле содержатся события спроса, в другом — соответствующие события поставок. Каждое событие представляет один объект сети заказов, такой как строка заказа на продажу, операция книги товаров или строка производственного заказа.  
  
При загрузке профилей запасов разные наборы спроса и предложения уравновешиваются, чтобы получить в результате план поставки, соответствующий перечисленным целям.  
  
Параметры планирования и уровни запасов являются типами спроса и поставки соответственно, для которых выполняется интегрированная балансировка для пополнения товаров склада. Дополнительные сведения см. в разделе [Сведения о проектировании: обработка политик дозаказа](design-details-handling-reordering-policies.md).  
  
## <a name="see-also"></a>См. также  
[Сведения о проектировании: балансировка спроса и поставки](design-details-balancing-demand-and-supply.md)   
[Сведения о проектировании: основные понятия системы планирования](design-details-central-concepts-of-the-planning-system.md)   
[Сведения о проектировании: планирование поставок](design-details-supply-planning.md)
