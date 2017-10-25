---
title: "Почему заблокирована персонализация страницы?"
description: "Объяснение причин, почему невозможно персонализировать страницу и как разблокировать страницу, чтобы ее можно было персонализировать."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: personalization locked, cannot personalize page
ms.date: 09/07/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b365d14c199d36abebcae0b3ac86340fd59cf8ef
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="why-is-the-page-is-locked-from-personalizing"></a>Почему заблокирована персонализация страницы?
Если в баннере **Персонализация** открытой страницы имеется значок замка, это означает, что вы в настоящее время не можете делать никаких дополнительных изменений персонализации на странице в [!INCLUDE[nav_web](includes/nav_web_md.md)].

![Замок персонализации](media/personalization-locked.png "Замок персонализации")

Для этого может быть две причины.
1.  До настоящего времени вы использовали только [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] для персонализации страницы.

2. Вы использовали [!INCLUDE[nav_web](includes/nav_web_md.md)] для персонализации страницы ранее, но это делалось с помощью [!INCLUDE[nav2017](includes/nav2017.md)] или более ранней версии.   

Если нужно продолжить персонализировать страницу с помощью [!INCLUDE[nav_web](includes/nav_web_md.md)], выберите значок замка, затем выберите **Разблокировать**.

## <a name="what-happens-when-you-unlock-the-page"></a>Что происходит при разблокировании страницы
Если вы разблокируете страницу, текущая персонализация страницы в [!INCLUDE[nav_web](includes/nav_web_md.md)] будет сброшена, то есть будет восстановлен исходный макет страницы и вам придется начать все с начала.

В [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] страница останется такой, какой она и была, и на нее не повлияют новые изменения, сделанные в [!INCLUDE[nav_web](includes/nav_web_md.md)]. Персонализация в [!INCLUDE[nav_web](includes/nav_web_md.md)] и [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] станут раздельными, поэтому у вас будут отдельная персонализированная версия в каждом из клиентов. 

В будущем вы будете персонализировать страницу в двух клиентах отдельно. Следовательно, страница потенциально между выглядеть по-разному в двух клиентах.

## <a name="see-also"></a>См. также
[Обзор персонализации](ui-personalization-overview.md)  
[Работа с персонализацией между Windows- и веб-клиентами Dynamics NAV](ui-personalization-overview.md#PersonalizationWinWeb)  
[Персонализация рабочей области с помощью веб-клиента](ui-personalization-user.md)  
[Персонализация рабочей области с помощью Windows-клиента](ui-personalization-windows-client.md)  
[Управление персонализацией](ui-personalization-manage.md)  
[Работа с [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-work-product.md)  
[Практическое руководство. Изменение ролевого центра](change-role.md)  

