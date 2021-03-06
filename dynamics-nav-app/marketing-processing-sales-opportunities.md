---
title: "Обработка возможностей продаж в циклах продаж"
description: "Вы можете просматривать, закрывать и удалять возможности продаж, а также создавать предложения продаж и заказы на продажу для возможностей и перемещать возможности по стадиям цикла продаж."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9fe0bd97f7493d9acf4ab99a771fd5f6219027f8
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-process-sales-opportunities"></a>Практическое руководство. Обработка возможностей продаж
После создания возможности есть ряд функций для управления возможностью и ее перемещения по этапам до завершения.

## <a name="to-view-opportunities"></a>Просмотр возможностей
Имеющиеся возможности продаж доступны в окне **Список возможностей**. Существуют различные способы доступа к этому окну для обработки возможностей продаж:

| Чтобы просмотреть возможности для | То |
| --- | --- |
| Всех менеджеров и контактов |Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Список возможностей**, а затем выберите связанную ссылку. |
| Конкретного менеджера по продажам |Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Менеджеры**, а затем выберите связанную ссылку. Выберите менеджера, выберите действие **Возможности**, а затем выберите действие **Список**. |
| Конкретного контакта |Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Контакты**, а затем выберите связанную ссылку. Выберите контакт из списка и выберите действие **Возможности**. |

Каждая из этих задач открывает окно **Список возможностей**.

## <a name="to-close-opportunities"></a>Закрытие возможностей
Возможности можно закрывать по окончании переговоров. При закрытии возможности можно указать, была она реализована или нет, а также причины ее закрытия. Чтобы указать причину, необходимо настроить коды закрытия возможностей.

1. В окне **Список возможностей** выберите возможность и выберите действие **Закрыть**. Откроется окно **Закрытие возможности**.
2. Заполните соответствующие поля и нажмите кнопку **ОК**.

   Поля **Код закрытия возможности** и **Дата закрытия** являются обязательными, и их следует заполнить до нажатия кнопки **ОК**.

   В поле **Код закрытия возможности** можно выбрать из одного из имеющихся кодов закрытия возможности или добавить новый код. Чтобы добавить новый код, в раскрывающемся списке выберите значение **Выбор из полного списка**, а затем выберите **новый**. В новой пустой строке заполните поля **Код**, **Тип** и **Описание**, а затем нажмите кнопку **ОК**.

## <a name="to-create-quotes-for-opportunities"></a>Создание предложений для возможностей
Можно создавать предложения по продаже для контактов, не зарегистрированных как заказчики.

1. В окне **Список возможностей** выберите возможность и выберите действие **Назначить предложение по продаже**. Откроется окно **Предложение по продаже**.
2. Заполните соответствующие поля.

## <a name="to-create-sales-orders-for-opportunities"></a>Создание заказов на продажу для возможностей
Заказы продажи можно создавать из предложений по продаже, созданных для возможностей. Перед созданием заказов на продажу для контактов необходимо создать контакт в качестве клиента. Дополнительные сведения см. в разделе [Создание клиента, поставщика или банковского счета из клиента](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).

1. В окне **Возможность — список** найдите возможность, для которой создано предложение по продаже.
2. Выберите действие **Назначить предложение по продаже**. Откроется окно **Предложение по продаже**, содержащее предложение по продаже, назначенное данной возможности.
3. Заполните дополнительные поля и выберите действие **Сделать заказ**.

При осуществлении манипуляций с возможностями продажи может потребоваться создать предложение для контакта, с которым связана эта возможность.

## <a name="to-delete-opportunities"></a>Удаление возможностей
Возможности можно удалить, например, после заключения вами сделки. Однако можно удалять только закрытые возможности. Существует два способа удалить закрытые возможности. Можно удалить отдельные закрытые возможности из окна **Список возможностей** или выполнить пакетное задание **Удалить закрытые возможности**, чтобы удалить несколько возможностей на основании определенных критериев.

Чтобы удалить закрытые возможности в окне **Список возможностей**, выберите возможность , а затем выберите действие **Удалить**.

Для уничтожения закрытых возможностей с помощью пакетного задания **Удалить закрытые возможности**, выполните следующие действия:

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Удалить возможности**, а затем выберите связанную ссылку.
2. В разделе **Возможность** настройте фильтры, которые определяют закрытые возможности для удаления.
3. Нажмите кнопку **ОК**.

После удаления возможности она удаляется из окна **Список возможностей**.

## <a name="to-move-an-opportunity-through-sales-cycle-stages"></a>Перемещение возможности по этапам цикла продаж
Если возможность обрабатывается в рамках цикла продаж, ее можно перемещать вперед или назад по различным этапам, а также можно пропускать этапы.

1. В окне **Список возможностей** выберите действие **Обновить**. Откроется окно **Обновление возможности**.
2. Используйте поле **Тип действия**, чтобы перемещать возможность по этапам цикла продаж:
   * **Следующий** перемещает возможность на следующий этап.
   * **Пропусттиь** перемещает возможность вперед на один или несколько этапов цикла продаж, указанных в поле **Презентация**. Можно пропускать только те этапы, которые допускают пропуск.
   * **Предыдущий** перемещает возможность на предыдущий этап.
   * **Перейти** перемещает возможность назад на один или несколько этапов цикла продаж, указанных в поле **Презентация**.
   * **Обновить** позволяет изменить информацию (например, изменить вашу оценку шансов на успех или приблизительные значения) без перехода на другой этап.
3. Заполните остальные поля по мере необходимости и нажмите кнопку **ОК**.

## <a name="see-also"></a>См. также
[Продажи](sales-manage-sales.md)  
[Создание контактов и управление ими](marketing-contacts.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

