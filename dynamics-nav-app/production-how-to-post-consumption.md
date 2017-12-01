---
title: "Как учитывать потребление в пакетном режиме"
description: "Если выбран метод списания **Вручную**, учет компонентов производится вручную с использованием журнала потребления."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bd4cedaf3fdb2d0f5627120836580fc82f4befa3
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-batch-post-production-consumption"></a>Практическое руководство. Учет потребления для производства в пакетном режиме
Если выбран метод списания **Вручную**, учет компонентов производится вручную с использованием журнала потребления.

Можно также настроить систему для автоматического учета (*списания*) компонентов при запуске или завершении производственных заказов. Дополнительные сведения см. в разделе [Включение списания компонентов в соответствии с производственным выпуском](production-how-to-flush-components-according-to-operation-output.md).

## <a name="to-post-consumption-for-one-or-more-production-order-lines"></a>Учет потребления для одной или нескольких строк производственного заказа  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал потребления**, затем выберите связанную ссылку.  
2.  Заполните поля данными производственного заказа и данными о потреблении. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    Если склад, на котором хранятся компоненты, настроен на использование ячеек, но не требует обработки подбора, присвойте код ячейки строке журнала для указания места на складе, откуда должны забираться товары. Дополнительные сведения см. в разделе [Практическое руководство. Подбор для производства или сборки](warehouse-how-to-pick-for-production.md).  
3.  Выберите действие **Учесть**, чтобы учесть потребление. Соответствующие операции в книге товаров уменьшаются.

## <a name="see-also"></a>См. также  
[Производство](production-manage-manufacturing.md)    
[Настройка производства](production-configure-production-processes.md)  
[Планирование](production-planning.md)      
[Наличие](inventory-manage-inventory.md)  
[Покупки](purchasing-manage-purchasing.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

