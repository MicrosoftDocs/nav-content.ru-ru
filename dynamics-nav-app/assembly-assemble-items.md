---
title: "Управление сборкой"
description: "Поддерживайте компании, которые поставляют продукты своим клиентам, объединяя компоненты в простые процессы без потребности в функциях производства, но с функциями сборки товаров, интегрирующиеся с существующими функциями, например для организации продаж, планирования, резервирования и складской деятельности."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4e0490e63268edd68a22e61b25311aa133c507c1
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="assembly-management"></a>Управление сборкой
Для обеспечения поддержки компаний, которые поставляют продукты своим клиентам, объединяя компоненты в простые процессы без потребности в функциях производства, [!INCLUDE[d365fin](includes/d365fin_md.md)] содержит функции сборки товаров, интегрирующиеся с существующими функциями, например для организации продаж, планирования, резервирования и складской деятельности.  

 Сборочный элемент определяется как продаваемый товар, который содержит сборочную спецификацию. Дополнительные сведения см. в разделе [Практическое руководство. Работа со спецификациями](inventory-how-work-BOMs.md).

 Сборочные заказы являются внутренними заказами, так же как и производственные, которые используются для управления процессом сборки и связи с требованиями продаж с включенными складскими действиями. Сборочные заказы отличаются от остальных типов заказов, так как при учете в них задействуется как выход, так и потребление. Заголовок сборочного заказа работает аналогично строке заказа на продажу, и строки сборочного заказа работают аналогично строкам журнала потребления.  

 Для обеспечения поддержки стратегии своевременного снабжения запасами и возможности настраивать продукцию согласно запросам клиента сборочные заказы могут быть автоматически созданы и связаны при создании строки заказа продажи. Связь между требованием продаж и поставкой сборки позволяет обработчикам заказов на продажу оперативно настраивать сборочный элемент и планировать даты доставки в соответствии с наличием компонентов, а также учитывать выход и отгрузку собранного товара непосредственно в интерфейсе заказа на продажу. Дополнительные сведения см. в разделе [Практическое руководство. Продажа товара, собранного на заказ](assembly-how-to-sell-items-assembled-to-order.md).  

 В одной строке заказа на продажу можно продать количество, которое доступно и должно быть подобрано из запасов, вместе с количеством, которое следует собрать в заказ. Существуют определенные правила, регулирующие распределение таких количеств для обеспечения того, чтобы количества сборки на заказ получали приоритет перед количествами запасов при частичной отгрузке. Дополнительные сведения см. в подразделе "Сценарии комбинации" в разделе [Сборка на заказ и сборка на склад](assembly-assemble-to-order-or-assemble-to-stock.md).  

 Существует специальная функция для управления отгрузкой количеств для сборки на заказ. Если товары, собранные на заказ, готовы к отправке, ответственный работник склада учитывает складской подбор для строк заказа на продажу под вопросом. Это, в свою очередь, вызывает перемещение запасов для компонентов, учет производительности сборки и отгрузку заказа на продажу. Дополнительные сведения см. в разделе "Обработка сборок на заказ в подборах запасов" в статье [Практическое руководство. Подбор товаров с помощью подбора запасов](warehouse-how-to-pick-items-with-inventory-picks.md).

В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.   

|**Задача**|**Ссылка**|  
|------------|-------------|  
|Узнайте о разнице между сборкой товаров непосредственно перед отгрузкой заказов на продажу и сборкой товаров, которые запланированы для хранения.|[Сборка на заказ и сборка на склад](assembly-assemble-to-order-or-assemble-to-stock.md)|
|Заполните поля в карточках складов и в настройке запасов, чтобы определить порядок перемещения товаров на участок сборки и с участка сборки.|[Практическое руководство. Настройка базовых складов с помощью зон операций](warehouse-how-to-set-up-basic-warehouses-with-operations-areas.md)|
|Настройте сборочный элемент по запросу клиента во время процесса продаж и преобразуйте в продажу после подтверждения.|[Практическое руководство. Предложения продажи сборки на заказ](assembly-how-to-quote-an-assemble-to-order-sale.md)|
|Объедините компоненты для создания элемента в ходе простого процесса, на заказ или на склад.|[Практическое руководство. Сборка товаров](assembly-how-to-assemble-items.md)|  
|Продавайте сборочные элементы, которых нет в данный момент в наличии, создавая связанный заказ на сборку для поставки полного или частичного количества по заказу на продажу.|[Практическое руководство. Продажа товара, собранного на заказ](assembly-how-to-sell-items-assembled-to-order.md)|
|Если некоторые товары сборки на заказ уже находятся на складе, вычтите это количество из сборочного заказа и зарезервируйте его со склада.|[Практическое руководство. Продажа складских товаров в потоках сборки на заказ](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md)|  
|Если продаются сборочные элементы из запасов, и все товары недоступны, можно указать, чтобы сборочный заказ автоматически поставлял часть или все количество для заказа на продажу.|[Практическое руководство. Совместная продажа товаров, собираемых на заказ, и складских товаров](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md)|
|Отмените учтенный заказ на сборку, например если заказ был учтен с ошибками, которые необходимо исправить.|[Практическое руководство: отмена учета сборки](assembly-how-to-undo-assembly-posting.md)|
|Узнайте о разнице между сборочными спецификациями и производственными спецификациями и отличиях в их обработке.|[Практическое руководство. Работа со спецификациями](inventory-how-work-BOMs.md)|
|Узнайте о том, как потребление при сборке и выход обрабатываются при учете сборочных заказов и как производный товар и себестоимость ресурсов обрабатываются и распределяются в Главной книге.|[Сведения о проектировании: учет заказа на сборку](design-details-assembly-order-posting.md)|  

## <a name="see-also"></a>См. также  
[Практическое руководство. Работа со спецификациями](inventory-how-work-BOMs.md)  
[Наличие](inventory-manage-inventory.md)  
[Сведения о проектировании: управление складом](design-details-warehouse-management.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
