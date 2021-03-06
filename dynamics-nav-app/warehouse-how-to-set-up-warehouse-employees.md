---
title: "Как настраивать работников склада"
description: "Каждый пользователь, который выполняет складские действия, должен быть настроен как работник склада, которому назначен один склад по умолчанию и могут быть назначены другие склады."
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
ms.openlocfilehash: e326d2450c5d45e0cf380f4862ca584a057dbff3
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-warehouse-employees"></a>Практическое руководство. Настройка работников склада
Каждый пользователь, который выполняет складские действия, должен быть настроен как работник склада, которому назначен один склад по умолчанию и могут быть назначены другие склады. Данная настройка пользователя фильтрует все складские действия в базе данных по складу сотрудника, чтобы сотрудник мог выполнять складские задачи только для склада по умолчанию. Пользователю могут быть назначены дополнительные нестандартные склады, где работник может просматривать строки задач, но не выполнять их.

## <a name="to-set-up-warehouse-employees"></a>Настройка работников склада  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сотрудники склада**, а затем выберите связанную ссылку.  
2. Выберите действие **Создать**.  
3. Выберите поле **Код пользователя**, а затем выберите пользователя, которого необходимо добавить как работника склада. Нажмите кнопку **ОК**.  
6.  В поле **Код склада** введите код склада, где будет работать пользователь.  
7.  Установите флажок **По умолчанию**, чтобы определить склад как единственный, где сотрудник может выполнять складские действия.  
8.  Повторите эти шаги, чтобы назначить работникам склады или назначить нестандартные склады существующим работникам склада.  

## <a name="see-also"></a>См. также  
[Управление складом](warehouse-manage-warehouse.md)  
[Наличие](inventory-manage-inventory.md)  
[Настройка управления складом](warehouse-setup-warehouse.md)     
[Управление сборкой](assembly-assemble-items.md)    
[Сведения о проектировании: управление складом](design-details-warehouse-management.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

