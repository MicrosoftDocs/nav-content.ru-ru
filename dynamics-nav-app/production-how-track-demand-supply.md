---
title: "Как отслеживать связи между спросом и предложением"
description: "Из любого документа по предложению или спросу в так называемой сети заказов можно отслеживать требования по заказу (трассируемое количество), прогноз, общий заказ продажи или параметры планирования (нетрассируемое количество), ставших причиной создания соответствующей строки планирования."
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
ms.openlocfilehash: acf030ab57c9251671900b1262dd8441c241c185
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-track-relations-between-demand-and-supply"></a>Практическое руководство. Отслеживание связей между спросом и предложением
Из любого документа по предложению или спросу в так называемой сети заказов можно отслеживать требования по заказу (трассируемое количество), прогноз, общий заказ продажи или параметры планирования (нетрассируемое количество), ставших причиной создания соответствующей строки планирования.

В производственных планах также предлагаются такие вспомогательные сведения о планировании, как не связанные с заказом операции, помогающие планировщику составить оптимальный план поставки. Дополнительные сведения см. в разделе "Нетрассируемые элементы планирования".

## <a name="to-track-linked-items"></a>Трассировка связанных товаров
Трассировка заказов отображает, как при помощи резервирования заказы продаж, производственные заказы и заказы покупки соотносятся с производственным заказом в системах планирования и резервирования.

Ниже описано, как отслеживать связанные товары в утвержденном производственном заказе. Шаги аналогичны для всех типов заказов, а также из строк журнала планирования.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Утвержд. произ. заказ**, затем выберите связанную ссылку.
2. Откройте соответствующий утвержденный производственный заказ из списка.
3. На экспресс-вкладке **Строки** выберите действие **Функции**, затем действие **Трассировка заказа**.

В окне **Трассировка заказов** перечислены документы, которые имеют отношение к текущей строке производственного заказа.

## <a name="untracked-planning-elements"></a>Нетрассируемые элементы планирования
Окно **Нетрассируемые элементы планирования** открывается при выборе поля **Нетрассированное колич.** в окне **Планирование заказов**. Оно служит для двух целей:

1. для хранения сведений о нетрассированных количествах, которые отображаются, когда пользователь выполняет поиск из окна «Трассировка заказов», чтобы просмотреть нетрассированные количества;
2. для хранения предупреждений, которые отображаются, когда пользователь выбирает значок **Предупреждение** в окне **Журнал планирования**.

Окно содержит записи для учета нетрассированного избыточного количества в сети трассировки заказов. Эти записи создаются в ходе планирования и поясняют, откуда появилось нетрассированное избыточное количество в строке трассировки заказов. Этот нетрассированный излишек может появляться из следующих источников:

- «Прогноз производства»;
- «Общие заказы»;
- «Кол-во страхового запаса»;
- «Точка повтора заказа»;
- «Максимальный запас»;
- «Кол-во для повторного заказа»;
- «Максимальное кол-во заказа»;
- «Минимальное кол-во заказа»;
- «Заказать несколько»;
- «Демпфер (% от размера партии)».

## <a name="see-also"></a>См. также  
[Планирование](production-planning.md)   
[Настройка производства](production-configure-production-processes.md)  
[Производство](production-manage-manufacturing.md)    
[Наличие](inventory-manage-inventory.md)  
[Покупки](purchasing-manage-purchasing.md)  
[Сведения о проектировании. Резервирование, трассировка и отправка сообщений о действиях](design-details-reservation-order-tracking-and-action-messaging.md)  
[Сведения о проектировании: планирование поставок](design-details-supply-planning.md)   
[Рекомендации по настройке. Планирование поставок](setup-best-practices-supply-planning.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
