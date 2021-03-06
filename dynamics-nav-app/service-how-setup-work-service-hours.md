---
title: "Настройка рабочих часов и часов работы сервиса"
description: "Можно указать стандартные часы работы сервиса в вашей организации. Эти сервисные часы используются для вычисления даты и времени отклика для сервисных заказов и предложений, а также при отправке предупреждений о времени отклика."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7b4d813f734fbaa53bc185e2477ca73705872097
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-work-hours-and-service-hours"></a>Практическое руководство. Настройка рабочих часов и часов работы сервиса
Как правило, система сервисного управления отслеживает время использования ресурсов и статус сервисных заказов с целью прогнозирования рабочих нагрузок и потребностей в сервисе. В [!INCLUDE[d365fin](includes/d365fin_md.md)] предусмотрены встроенные средства, которые можно настроить индивидуально для записи такого рода информации.  
  
После настройки времени по умолчанию, затраченного организацией на предоставление сервисного обслуживания, можно вычислить время отклика для сервисных заказов либо отправки уведомлений или предупреждений при обращении в службу поддержки. Функция уведомления и планировщик заданий связаны между собой.   
  
При работе с сервисным заказом требуется обновлять его статус, чтобы можно было контролировать ход его выполнения. Статус сервисного заказа отражает статус ремонта всех сервисных товаров данного сервисного заказа. Дополнительные сведения см. в разделе [Сервисный заказ и статус ремонта](service-order-repair-status.md). 

## <a name="to-set-up-default-service-hours"></a>Настройка сервисных часов по умолчанию  
Используйте окно **Время работы по умолчанию**, чтобы установить стандартные часы работы сервиса организации. Эти сервисные часы используются для вычисления даты и времени отклика для сервисных заказов и предложений, а также при отправке предупреждений о времени отклика. Для сервисных контрактов используются стандартные сервисные часы, пока для контракта не будут определены особые сервисные часы.  
  
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Часы работы сервиса по умолчанию**, а затем выберите связанную ссылку.  
2. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
  
> [!IMPORTANT]  
>  Если оставить строки в окне **Время работы по умолчанию** незаполненными, будет использоваться значение по умолчанию 24 часа, действующее только в календарные рабочие дни.  
  
## <a name="to-set-up-work-hour-templates"></a>Чтобы настроить шаблоны рабочих часов
Можно использовать окно **Шаблон рабочего времени**, чтобы настроить шаблоны, содержащие обычные рабочие часы вашей организации. Например, можно создать шаблоны для специалистов, работающих полный рабочий день, и для специалистов, работающих неполный рабочий день. Шаблоны рабочих часов можно использовать при добавлении производственной мощности в ресурсы.  
  
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Шаблоны рабочего времени**, затем выберите связанную ссылку.  
2. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
  
> [!Note]
> После ввода рабочих часов для каждого дня значение в поле **Всего в неделю** рассчитывается автоматически.  

## <a name="to-set-up-contract-specific-service-hours"></a>Настройка времени работы для конкретного контракта  
Можно использовать окно **Время работы**, чтобы настроить конкретное время работы для клиента, которому принадлежит сервисный контракт. Время работы используется для вычисления даты и времени отклика на сервисные заказы и предложения, относящиеся к данному сервисному контракту.  
  
Если для сервисного контракта не настраивается конкретное время работы, для контракта используется стандартное время работы.  
  
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные контракты**, затем выберите связанную ссылку.  
2. Откройте сервисный контракт, для которого нужно задать часы работы сервиса, и выберите **Часы работы сервиса**.  
4. Чтобы задать часы работы сервиса на основе времени работы по умолчанию, выберите действие **Копировать часы работы сервиса по умолчанию**.  
5. Отредактируйте поля в записях часов обслуживания. Вставьте или удалите записи, чтобы настроить сервисное время для данного договора. Обратите внимание, что поля **День**, **Время начала** и **Время окончания** обязательны для каждой строки.  
6. Чтобы сервисное время вступило в действие с определенной даты, заполните поле **Дата начала**.  
7. Чтобы сервисное время действовало в выходные, отметьте флажком поле **Действует в праздники**.  

## <a name="see-also"></a>См. также  
[Статус распределения и ремонта](service-allocation-status-and-repair-status.md)  
[Настройка управления сервисным обслуживанием](service-setup-service.md)  
[Сервисный заказ и статус ремонта](service-order-repair-status.md)  

