---
title: "Сведения о проектировании — обработка заказов до даты начала планирования"
description: "В этом разделе описываются правила, которые применяются при планировании заказов в замороженной зоне."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: planning, frozen, design serial, lot
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: be20503b92b92448eceb1f388649d9f4022836ca
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-dealing-with-orders-before-the-planning-starting-date"></a>Сведения о проектировании: обработка заказов до даты начала планирования
Чтобы избежать отображения невозможных и, следовательно, бесполезных предположений в плане поставок, система планирования учитывает период до начальной даты зоны заморозки, в которой ничего нельзя планировать. Следующее правило применяется к замороженной зоне:  
  
Весь спрос и поставки до даты начала периода планирования будут считаться частью запасов или будут считаться отгруженными.  
  
Соответственно, за некоторыми исключениями система планирования не будет предлагать какие-либо изменения в заказах на поставку в замороженной зоне, и связи трассировки заказа не будут создаваться или поддерживаться на данный период.  
  
В этом правиле следующие исключения.  
  
* Если прогнозируемые доступные запасы, включая сумму спроса и поставки в замороженной зоне, меньше нуля.  
* Если требуются серийные номера/номера партий в заказах, записываемых задним числом.  
* Если набор поставки и спроса связан требованиями политики "заказ-в-заказ".  
  
Если исходные доступные запасы ниже нуля, система планирования предложит экстренный заказ на поставку на день, предшествующий периоду планирования для обеспечения наличия отсутствующего количества. Следовательно, прогнозируемые и доступные запасы всегда будут равны хотя бы нулю, когда начинается планирование будущего периода. Строка планирования для этого заказа на поставку отобразит предупреждающий значок аварийной ситуации с возможностью просмотра дополнительных сведений.  
  
## <a name="seriallot-numbers-and-order-to-order-links-are-exempt-from-the-frozen-zone"></a>Серийные номера или номера партий и связи "заказ-в-заказ" исключены из замороженной зоны  
Если требуются серийные номера или номера партий либо существует связь "заказ-а-заказ", система планирования будет игнорировать замороженную зону и включит записанные задним числом количества, начиная с даты начала, а также, возможно, предложит корректирующие действия, если спрос и поставка не синхронизированы. Коммерческое обоснование этого принципа следующее: конкретные наборы спроса и предложения должны совпадать, чтобы обеспечить удовлетворение спроса.  
  
## <a name="see-also"></a>См. также  
[Сведения о проектировании: балансировка спроса и поставки](design-details-balancing-demand-and-supply.md)   
[Сведения о проектировании: основные понятия системы планирования](design-details-central-concepts-of-the-planning-system.md)   
[Сведения о проектировании: планирование поставок](design-details-supply-planning.md)
