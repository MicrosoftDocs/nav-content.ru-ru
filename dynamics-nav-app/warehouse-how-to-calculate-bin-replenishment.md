---
title: "Как рассчитывать пополнение ячеек"
description: "Если склад настроен для использования направленного подбора и размещения, приоритеты шаблона размещения для данного склада учитываются при размещении приходных накладных."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3a6ff833aad54cf98720857a8ae67492abe9af4f
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-calculate-bin-replenishment"></a>Практическое руководство. Расчет пополнения ячеек
Если склад настроен для использования направленного подбора и размещения, приоритеты шаблона размещения для данного склада учитываются при размещении приходных накладных. Приоритеты включают максимальное и минимальное количества содержимого ячеек, которые были зафиксированы для конкретной ячейки, а также рейтинги ячеек. Следовательно, если товары поступают равномерно, наиболее часто используемые ячейки подбора будут заполняться по мере их опорожнения.  

Но товары не всегда поступают равномерно. Иногда товары закупаются в больших количествах, чтобы организация получила скидку, или производственное подразделение изготавливает большое количество одного товара для уменьшения себестоимости единицы. После этого данные товары не будут поступать на склад в течение какого-то времени, и складу необходимо периодически перемещать товары в ячейки подбора из навалочной зоны.  

Иногда на складе ожидается скорое поступление новых товаров, и необходимо освободить навалочную зону до их поступления.  

Наконец, если тип ячейки навалочного хранения содержит только действие **размещения**, т. е. для типа ячейки флажок действия **Подбор** не установлен, то ячейки подбора должны постоянно пополняться, т. к. программа не будет предлагать подбора товаров только из ячеек типа "Размещение".  

## <a name="to-replenish-pick-bins"></a>Пополнение ячеек подбора  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал перемещения**, затем выберите связанную ссылку.  
2.  Выберите действие **Расчет пополнения ячеек**, чтобы открыть страницу запроса отчета.  
3.  Заполните окно запроса пакетного задания для того, чтобы ограничить рамки предложений по пополнению, которые будут рассчитываться. Например, может потребоваться обработка только конкретных товаров, зон или ячеек.  
4.  Нажмите кнопку **ОК**. Будут созданы строки для передвижений пополнения, которые необходимо выполнить согласно правилам, настроенным для ячеек и содержимого ячеек (то есть товаров в ячейках).  
5.  Если необходимо выполнить все предложенные пополнения, выберите действие **Создать передвижение**. Теперь сотрудники должны найти инструкции в пункте меню **Перемещения**, выполнить и зарегистрировать их.  
6.  Если необходимо выполнить некоторые из предложенных пополнений, удалите менее важные строки и затем создайте передвижение.  

Когда пополнение ячеек будет рассчитываться в следующий раз, удаленные предложения будут созданы заново, если они еще имеют силу.  

> [!NOTE]  
>  Если товар соответствует следующим критериям:  
>   
>  -   Указан срок годности товара и  
> -   Выбрано поле **Выбрать по методу FEFO** в карточке склада, и  
> -   Вы используете функцию **Расчет пополнения ячеек**  
>   
>  то поля **Из зоны** и **Из ячейки** будут пусты, потому что алгоритм, рассчитывающий, откуда необходимо переместить товары, запускается при активации функции **Создать передвижение**.  

## <a name="see-also"></a>См. также  
[Управление складом](warehouse-manage-warehouse.md)  
[Подбор по методу FEFO](warehouse-picking-by-fefo.md)  
[Наличие](inventory-manage-inventory.md)  
[Настройка управления складом](warehouse-setup-warehouse.md)     
[Управление сборкой](assembly-assemble-items.md)    
[Сведения о проектировании: управление складом](design-details-warehouse-management.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
