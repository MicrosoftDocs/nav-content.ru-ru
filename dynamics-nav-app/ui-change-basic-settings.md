---
title: "Просмотр и изменение основных настроек в Dynamics NAV"
description: "Узнайте, как изменять некоторые из базовых параметров в Dynamics NAV, например ролевой центр, компанию или рабочую дату."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: change Role Center, notification, change company, change work date
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: cf5a74cea6d7906845a0e087576ab090c319f297
ms.contentlocale: ru-ru
ms.lasthandoff: 10/23/2017

---
# <a name="changing-basic-settings"></a>Изменение базовых настроек
В окне **Мои настройки** вы можете просмотреть и изменить базовые настройки для [!INCLUDE[d365fin](includes/d365fin_md.md)].  

## <a name="role-center"></a>Ролевой центр
Ролевой центр представляет начальную страницу, разработанную в соответствии с задачами конкретной роли. На начальной странице представлен обзор вашего бизнеса. Слева отображается панель навигации, которая позволяет легко переходить к клиентам, поставщикам, товарам и так далее.

В центе имеются плитки "Действия". Действия показывают текущие данные и их можно нажимать для простого доступа к выбранному документу. Ключевые индикаторы производительности можно настроить для отображения выбранной диаграммы для визуального представления, например, движения денежных средств или прибылей и убытков.

Также на начальной странице можно составить список "Избранные клиенты" для клиентов, с которыми вы работаете чаще и которые требуют особого внимания. Используйте стрелки, чтобы свернуть часть страницы и освободить место для просмотра конкретных данных. В верхней части начальной страницы представлены все действия, которые могут быть применены к текущему содержимому. Их тоже можно сворачивать, достаточно щелкнуть или нажать свернутую область, чтобы снова открыть ее.

Ролевой центр по умолчанию — **Бизнес-руководитель**, но вы можете выбрать другой ролевой центр в соответствии со своими потребностями. Дополнительные сведения см. в разделе [Практическое руководство. Изменение ролевого центра](change-role.md).

## <a name="company"></a>Организация
Организация выполняет роль контейнера данных в [!INCLUDE[d365fin](includes/d365fin_md.md)]. В базе данных может быть несколько организаций, но одновременно можно выбрать только одну из них.

Организация по умолчанию называется CRONUS и содержит только демонстрационные данные.

> [!TIP]  
>   Если требуется отобразить другое название для вашей организации в приложении (например, на домашней странице), установите значение в поле **Имя** на странице **Информация об организации** или в поле **Отображаемое имя** на странице **Организации**.  

## <a name="work-date"></a>Рабочая дата
Рабочей датой по умолчанию обычно является текущая дата. Для выполнения таких задач, как проведение транзакций на определенную дату, не являющуюся текущей датой, может возникнуть потребность во временном изменении рабочей даты.

> [!TIP]  
>   Введите **w**, чтобы быстро подставить рабочую дату в поле даты. Введите **t**, чтобы быстро подставить текущую дату в поле даты.

> [!IMPORTANT]  
>   Рабочая дата изменяется только до закрытия организации или до изменения даты. Если при открытии другой организации или той же организации на следующий день требуется использование другой рабочей даты, необходимо снова установить рабочую дату.

## <a name="region"></a>Регион
Настройка **Регион** определяет способ отображения или форматирования дат, времени, чисел и валюты.   

## <a name="change-when-i-receive-notifications"></a>Изменение времени получения уведомлений
Выберите эту ссылку для просмотра или изменения уведомлений, которые вы получаете об определенных событиях или изменениях статуса, например, когда вы собираетесь выставить счет клиенту, у которого имеется просроченная задолженность, или когда доступные запасы ниже количества, которое вы собираетесь продать. Дополнительные сведения см. в разделе [Умные уведомления](ui-smart-notifications.md).

## <a name="see-also"></a>См. также
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Практическое руководство. Изменение ролевого центра](change-role.md)  
[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-customizing-overview.md)  

