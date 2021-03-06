---
title: "Производство"
description: "После планирования спроса и выдачи материалов в соответствии с производственными спецификациями можно приступать к выполнению фактических производственных операций в последовательности, определенной маршрутизацией производственных заказов."
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
ms.openlocfilehash: 1d3e6b49626aaf60f398b9f9cf8a656bd3dc4946
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="manufacturing"></a>Производство
После планирования спроса и выдачи материалов в соответствии с производственными спецификациями можно приступать к выполнению фактических производственных операций в последовательности, определенной маршрутизацией производственных заказов.  

Важной частью процесса производства, с системной точки зрения, является учет выпуска продукции в базе данных, необходимый для составления отчетов о ходе выполнения и пополнения запасов израсходованных товаров. Учет потребления можно выполнить вручную, заполнив строки журнала и выполнив их учет после выполнения производственных операций. Эта процедура может также выполняться автоматически с помощью обратного списания. В таком случае потребление материалов учитывается автоматически наряду с выпуском, когда производственный заказ приобретает статус завершенного.  

В качестве альтернативы разделу журнала учета выпуска для нескольких производственных заказов для учета потребления и/или выпуска по одной строке производственного заказа можно воспользоваться окном **Производственный журнал**.

Прежде чем начать производить товары, необходимо выполнять различные настройки, например производственные центры, маршруты и производственные спецификации. Дополнительные сведения см. в разделе [Настройка производства](production-configure-production-processes.md).

В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.   

|**Задача**|**Ссылка**|  
|------------|-------------|  
|Узнайте, как работают производственные заказы.|[О производственных заказах](production-about-production-orders.md)|
|Создание производственных заказов вручную.|[Практическое руководство. Создание производственных заказов](production-how-to-create-production-orders.md)|
|Передача субподрядчику всех или выбранных операций в производственном заказе.|[Практическое руководство. Субподрядное производство](production-how-to-subcontract-manufacturing.md)|
|Запись и учет выхода продукции наряду с материалами и временем потребления для одной строки запущенного производственного заказа|[Практическое руководство. Учет потребления и выхода для одной строки запущенного производственного заказа](production-how-to-register-consumption-and-output.md)|  
|Учет в пакетном режиме количества компонентов, использованных на операцию, в журнале, который может обрабатывать несколько плановых производственных заказов.|[Практическое руководство. Учет потребления в пакетном режиме](production-how-to-post-consumption.md)|
|Учет количества готовых товаров и затраченного времени на операцию, в журнале, который может обрабатывать несколько запущенных производственных заказов.|[Практическое руководство. Учет в пакетном режиме выпуска продукции и времени работы](production-how-to-post-output-quantity.md)|  
|Учет количества товара, произведенного за каждую завершенную операцию, которые считаются незаконченным выпуском, а бракованным материалом|[Практическое руководство. Учет брака/отходов](production-how-to-post-scrap.md)|
|Просмотр загрузки цеха в результате запланированные и запущенных производственных заказов.|[Практическое руководство. Просмотр загрузки производственных и машинных центров](production-how-to-view-the-load-on-work-centers.md)|      
|Использование окна **Журнал производственных мощностей** для учета использованных производственных мощностей, которые не назначены производственному заказу, например работы по техническому обслуживанию|[Практическое руководство. Учет производственных мощностей](production-how-to-post-capacities.md)|  
|Расчет и коррекция себестоимости производимых готовых товаров и использованных компонентов для финансовой выверки|[О затратах на завершенные производственные заказы](finance-about-finished-production-order-costs.md)|  

## <a name="see-also"></a>См. также  
[Настройка производства](production-configure-production-processes.md)  
[Планирование](production-planning.md)      
[Наличие](inventory-manage-inventory.md)  
[Покупки](purchasing-manage-purchasing.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

