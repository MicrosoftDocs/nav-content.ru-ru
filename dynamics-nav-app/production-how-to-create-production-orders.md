---
title: "Как создавать заголовки производственных заказов"
description: "Производственный заказ можно создать вручную. Для этого сначала необходимо создать заголовок производственного заказа."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 653451206fe0baec63e9db4cce7626357bb00942
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-production-order-headers"></a>Практическое руководство. Создание заголовков производственных заказов
Производственный заказ можно создать вручную. Для этого сначала необходимо создать заголовок производственного заказа.

Производственные заказы обычно создаются автоматически функцией планирования для удовлетворения известного спроса. Дополнительные сведения см. в разделе [Планирование](production-planning.md).   

В следующей процедуре показан способ создания утвержденного производственного заказа. Можно создавать производственные заказы и с другим статусом.  

## <a name="to-create-a-production-order-header"></a>Создание заголовка производственного заказа  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Утвержд. произв. заказы**, затем выберите связанную ссылку.  
2.  Выберите действие **Создать**.  
3.  В поле **Номер** введите следующий номер в серии.  
4.  В поле **Тип источника** выберите источник производственного заказа.

    Здесь можно выбрать производство семейства товаров. Дополнительные сведения см. в разделе [Практическое руководство. Работа с производственными семействами](production-how-work-family.md).
5.  В поле **Номер источника** выберите номер товарной позиции, семейство или заголовок продажи, для которого будет создан производственный заказ.  
6.  Заполните поля **Кол-во** и **Дата выполнения** в соответствии со спецификациями.  

При изменении производственных требований, таких как компоненты или операции, можно быстро заново спланировать производственный заказ. Дополнительные сведения см. в разделе [Практическое руководство. Непосредственное перепланирование или обновление производственных заказов](production-how-to-replan-refresh-production-orders.md). 

## <a name="see-also"></a>См. также  
[Производство](production-manage-manufacturing.md)    
[Настройка производства](production-configure-production-processes.md)  
[Планирование](production-planning.md)      
[Наличие](inventory-manage-inventory.md)  
[Покупки](purchasing-manage-purchasing.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

