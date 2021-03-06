---
title: "Утверждение или отклонение документов в бизнес-процессах"
description: "Запрашивать, отклонять или делегировать утверждение, например, документа покупки или продажи можно в рамках бизнес-процесса."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reject, delegate, request
ms.date: 08/24/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b0cd3c6c2465c29d5e4710ae2ef13e3f42522245
ms.contentlocale: ru-ru
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-use-approval-workflows"></a>Практическое руководство. Использование рабочего процесса утверждения
Когда запись — например, документ покупки или карточка клиента — должен быть утвержден кем-либо в вашей организации, вы отправляете запрос на утверждение как часть рабочего процесса. В зависимости от того, как настроен рабочий процесс, соответствующее утверждающее лицо получает уведомление о том, что запись требует его утверждения.

Рабочие процессы утверждения можно настроить в окне **Рабочий процесс**. Дополнительные сведения см. в разделе [Настройка рабочих процессов](across-set-up-workflows.md).

В дополнение к рабочим процессам утверждения, описанным в этом разделе, можно выполнять различные другие задачи рабочих процессов. Дополнительные сведения см. в разделе [Использование рабочих процессов](across-use-workflows.md).

Основные рабочие процессы для утверждения документов покупки, документов продажи, журналов платежей, карточек клиентов и карточек товаров готовы к запуску в рамках сопровождаемой настройки. Дополнительные сведения см. в разделе [Добро пожаловать в [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md).

## <a name="to-request-approval-of-a-record"></a>Запрос утверждения записи
Следующая задача выполняется утверждающим пользователем.

1. В открывшемся окне с записью выберите действие **Отправить запрос на утверждение**.
2. Чтобы увидеть свои запросы на утверждение, в правом верхнем углу выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Операции запросов утверждения**, а затем выберите связанную ссылку.  

Статус операции утверждения обновляется с **Создано** на **Открыто**. Статус записи, например счета покупки, обновляется с **Открыто** на **Ожидает утверждения** и остается запрещенным к обработке до тех пор, пока все утверждающие лица не утвердят запись.

После того как утверждающее лицо утвердит запись, ее статус меняется на **Выпущено**. После этого можно продолжить выполнять действия с записью.

## <a name="to-cancel-requests-for-approval"></a>Отмена запросов утверждения
Следующая задача выполняется утверждающим пользователем с правом утверждения.

Клиенту может потребоваться изменить заказ после того, как он будет отправлен на утверждение. В этом случае процесс утверждения отменяется и перед повторной отправкой запроса утверждения в документ вносятся необходимые изменения.

- В открывшемся окне с записью выберите действие **Отменить запрос на утверждение**.

После того запрос утверждения будет отменен, статус соответствующей операции утверждения меняется на **Отменено**. Статус записи меняется с **Ожидает утверждения** на **Открыто**. После этого процесс утверждения может быть начат сначала.

## <a name="to-approve-or-reject-requests-for-approval"></a>Утверждение или отклонение запросов утверждения
Следующая задача выполняется утверждающим пользователем с правом утверждения.

Вы можете обрабатывать запросы утверждения в окне **Запросы утверждения**, например, для утверждения нескольких запросов одновременно. Кроме того, вы можете обрабатывать каждый запрос в соответствующей записи, например в окне **Счет покупки**, выбрав ссылку в уведомлении, которое вы получаете.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Запросы на утверждение**, а затем выберите связанную ссылку.
2. Выберите одну или несколько строк для записи или записей, которые необходимо утвердить или отклонить.
3. Выберите действие **Утвердить**, **Отклонить** или **Делегировать**.

Если запись была утверждена или отклонена, статус утверждения в поле **Статус** меняется на **Утверждено** или **Отклонено**.

Если настроена иерархия утверждающих лиц, то запись будет иметь статус **Ожидает утверждения** до тех пор, пока все утверждающие лица не утвердят ее. После этого статус записи будет изменен на **Обработано**.

В то же время статус утверждения меняется с **Создано** на **Открыто**, как только будет создан запрос утверждения для записи. Если запрос отклоняется, статус утверждения меняется на **Отклонено**. Статус сохраняет значение **Открыто** или **Отклонено**, пока все утверждающие лица не утвердят запрос.

## <a name="to-delegate-requests-for-approval"></a>Делегирование запросов утверждения
Следующая задача выполняется утверждающим пользователем с правом утверждения.

Чтобы избежать нагромождения документов и других препятствий для рабочего процесса, утверждающее лицо и администратор утверждающего лица могут делегировать запрос утверждения заместителю. Заменой может стать назначенный пользователь, прямой утверждающий или администратор утверждения (в таком порядке). Обычно эта функция используется, если утверждающее лицо отсутствует на рабочем месте и не может утвердить запросы в срок.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Запросы на утверждение**, а затем выберите связанную ссылку.
2. Выберите одну или несколько строк для запроса утверждения, который требуется делегировать заместителю утверждающего лица, а затем выберите действие **Делегировать**.

Заместителю утверждающего лица отправляется уведомление об утверждении запроса.

## <a name="to-manage-overdue-approval-requests"></a>Управление просроченными запросами утверждения
Следующая задача выполняется утверждающим пользователем с правом утверждения.

Через равные промежутки времени следует напоминать пользователям рабочего процесса о просроченных запросах на утверждение, на которые они должны отреагировать. Используйте для этого функцию **Отправить сообщения о просроченных утверждениях**.

Функция The **Отправить сообщения о просроченных утверждениях** проверяет все открытые запросы на утверждение, которые в текущий момент просрочены. Каждое утверждающее лицо, имеющее хотя бы одно просроченное утверждение, получает уведомление со списком всех просроченных запросов на утверждение. Уведомление также отправляется утверждающим лицам данного запроса и всем запрашивающим сторонам просроченных утверждений. Это полезно в том случае, когда операция просроченного утверждения должна быть делегирована заместителю.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Просроченные запросы на утверждение**, а затем выберите связанную ссылку.
2. В окне **Просроченные запросы утверждения** выберите действие **Отправить уведомления о просроченном утверждении**.

## <a name="see-also"></a>См. также
[Продажи](sales-manage-sales.md)    
[Входящие документы](across-income-documents.md)  
[Покупки](purchasing-manage-purchasing.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

