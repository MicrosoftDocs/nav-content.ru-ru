---
title: "Настройка табелей учета времени и процесса их утверждения"
description: "Вы можете настроить табели учета рабочего времени для отслеживания затраченного времени и использования ресурсов в работах, что помогает при управлении проектами, комплектации штата и планировании производственной мощности."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, capacity, staff, resource
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 636bf45213ab4adf33244cb97dd1328733bf27ad
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-time-sheets"></a>Практическое руководство: настройка табелей
Табели учета рабочего времени в [!INCLUDE[d365fin](includes/d365fin_md.md)] регистрируются на еженедельной основе с периодичностью в семь дней. Их можно использовать для отслеживания времени, затраченного на работы, а также для записи простой регистрации затрат времени ресурса. Прежде чем использовать табели, необходимо указать, как они должны быть установлены и настроены.

После настройки того, как организация будет использовать табели учета времени, можно указать, требуется ли утверждение табелей и как будет производиться утверждение. В зависимости от потребностей организации, могут быть указаны:

* Один или несколько пользователей в качестве администратора и утверждающего табелей для всех табелей.
* Утверждающий табели для каждого ресурса.

После настройки табелей можно создавать табели для ресурсов, назначать им строки планирования работ и учитывать строки табелей. Дополнительные сведения см. в разделе [Практическое руководство. Использование табелей](projects-how-use-time-sheets.md).

## <a name="to-set-up-general-information-for-time-sheets"></a>Настройка общей информации для табелей.
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка модуля "Ресурсы"**, а затем выберите связанную ссылку.  
2. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Для поля **Табель учета рабочего времени по утверждению работы** выберите один из следующих вариантов.

| Параметр | Описание |
| --- | --- |
| **Никогда** |Пользователь в поле **Код пользователя, утверждающего табель** на карточке ресурса утверждает табель. |
| **Всегда** |Пользователь в поле **Ответственное лицо** на карточке работы утверждает табель. |
| **Только машина** |Если машинный табель связан с работой, то сотрудник, указанный в поле **Ответственное лицо** на карточке работы, утверждает этот табель. Если машинный табель связан с ресурсом, то сотрудник, указанный в поле **Код пользователя, утверждающего табель** на карточке ресурса, утверждает этот табель. |

## <a name="to-assign-a-time-sheet-administrator"></a>Назначение администратора табелей
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройки пользователей**, а затем выберите связанную ссылку.  
2. Добавьте нового пользователя, если список пользователей не включает лицо, которое вы хотите назначить администратором табелей. Дополнительные сведения см. в разделе [Практическое руководство. Управление пользователями и разрешениями](ui-how-users-permissions.md).
3. Выберите пользователя, который будет администратором табеля, затем установите флажок **Админ. табеля учета рабочего времени**.  

> [!TIP]  
>   Рекомендуется назначать только одного пользователя в качестве администратора табелей в организации. В следующей процедуре настраиваются владелец табеля и утверждающий, где утверждающий табелей назначается для каждого ресурса.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>Назначение владельца и утверждающего для табелей
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Ресурсы**, а затем выберите связанную ссылку.
2. Выберите ресурс, для которого требуется настроить возможность использовать табели, затем установите флажок **Использовать табель**.  
3. В поле **Код пользователя владельца табеля** введите код владельца табеля. Держатель может ввести расход времени в табель и представить его для утверждения. В целом, когда ресурс — физическое лицо, это лицо также является владельцем.  
4. В поле **Код пользователя, утверждающего табель** введите код утверждающего табеля. Утверждающий может утвердить, отклонить или повторно открыть табель.  

> [!NOTE]  
>   Нельзя изменить код пользователя, утверждающего табели, если имеются табели, которые еще не были обработаны и имеют статус **Отправлено** или **Открыто**.

## <a name="see-also"></a>См. также
[Настройка управления проектами](projects-setup-projects.md)  
[Управление проектами](projects-manage-projects.md)  
[Финансы](finance.md)  
[Покупки](purchasing-manage-purchasing.md)         
[Продажи](sales-manage-sales.md)      
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

