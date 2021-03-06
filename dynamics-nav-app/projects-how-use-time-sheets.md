---
title: "Работа с табелями учета рабочего времени для работ"
description: "Описывается процедура создания табеля учета рабочего времени для работы, копирования строк планирования в него, определения видов работ, заполнения табеля учета рабочего времени и его отправки на утверждение."
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
ms.openlocfilehash: c4a2bc57833af88038d022e2a13cb8a50a4a61f3
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-use-time-sheets-for-jobs"></a>Практическое руководство: использование табелей для работ
Используйте пакетное задание **Создать табели учета рабочего времени**, чтобы настроить табели для определенного количества периодов времени или недель. Вы должны иметь права на создание табелей.

Можно скопировать и использовать в табеле строки планирования работы. В этом способе необходимо только ввести информацию для одного места, и информация в строке всегда будет правильной.

После утверждения операций табеля для задания можно выполнять их учет в соответствующем журнале заданий или журнале ресурсов.

Прежде чем использовать табели, необходимо настроить общую информацию и указать администратора и одного или нескольких утверждающих табелей. Дополнительные сведения см. в разделе [Практическое руководство. Настройка табелей](projects-how-setup-time-sheets.md).

## <a name="to-create-a-time-sheet"></a>Создание табеля учета рабочего времени
Можно использовать пакетное задание **Создать табели учета рабочего времени**, чтобы настроить табели для определенного количества периодов времени или недель. Затем владелец табеля может открыть его и записать время, которое было затрачено на задание.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Табели учета рабочего времени**, а затем выберите связанную ссылку.
2. В окне **Список табелей** выберите действие **Создать табели учета рабочего времени**.
3. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Поля **Использовать табель** и **Код пользователя владельца табеля** должны быть заполнены в карте для ресурса табеля.

1. Нажмите кнопку **ОК**.  

Можно просматривать табели, созданные вами, в окне **Список табелей**.

## <a name="to-copy-job-planning-lines-to-a-time-sheet"></a>Копирование строк планирования работ в табель учета времени
Далее описывается процедура создания быстрого добавления строк планирования работы в табель.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Табели учета рабочего времени**, а затем выберите связанную ссылку.  
2. В окне **Список табелей** выберите табель для соответствующего периода времени, затем выберите действие **Изменить табель**.  
3. Выберите действие **Создать строки из планирования работ**. Все строки планирования заданий в периоде времени табеля копируются в табель для лица или машины в поле **Номер ресурса** табеля учета рабочего времени.

## <a name="to-define-work-types-and-add-one-to-a-time-sheet"></a>Определение видов работ и добавление вида работ в табель
Можно определить тип работы для всех для строк табелей для заданий. Таким образом можно добавить информацию, которая необходима, чтобы выставить счет клиенту за различные типы работ.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Табели учета рабочего времени**, а затем выберите связанную ссылку.   
2. Откройте соответствующий табель.
3. Выберите поле **Описание**.  
4. В окне **Сведения о работах строк табелей** окне выберите поле **Код вида работы** и выберите вид работы из списка, например **КМ**.  
5. В случае отсутствия видов работ, выберите действие **Создать**.
6. В окне **Виды работ** заполните требуемые поля.
7. Повторите шаг 4 для назначения нового вида работ табелю.

## <a name="to-reuse-time-sheet-lines-in-other-time-sheets"></a>Повторное использование строк табелей в других табелях
Если ваши сведения о табеле учета рабочего времени остаются прежним от периода времени к периоду времени, можно сохранить время, копируя строки из предыдущего периода времени. Затем необходимо просто ввести свое время работы для нового периода.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Табели учета рабочего времени**, а затем выберите связанную ссылку.  
2. Откройте табель дата периода, более позднего, чем период для существующего табеля со строками.  
3. Выберите действие **Копировать строки из предыдущих табелей**.

Строки копируются, включая подробную информацию, такую как тип и описание. Например, если данная строка связана с работой, то поле **Код работы** копируется. Все скопированные строки имеют статус **Открыто**. Теперь строки можно изменять, как требуется.

## <a name="to-fill-in-a-time-sheet-lines-and-submit-for-approval"></a>Заполнение строк табелей и отправка на утверждение
Регистрация табеля отслеживается в часах (стандартной базовой единице измерения для ресурсов). По умолчанию в табеле отображаются общие рабочие дни с понедельника по пятницу.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Табели учета рабочего времени**, а затем выберите связанную ссылку.  
2. Выберите табель для соответствующего периода времени, затем выберите действие **Изменить табель**.  
3. Заполните поля в строке по мере необходимости. Введите количество часов, использованных ресурсом, для каждого дня недели.

    > [!TIP]  
>   Можно просмотреть общее количество часов, которые вы ввели на информационной панели **Сводка по фактическим и бюджетным суммам**.  
4. Повторите шаг 3 для других видов работ, которые выполняет ресурс.
5. Выберите действие **Передать**, затем выберите действие **Все открытые строки** для передачи всех строк или действие **Только выбранные строки** для передачи только строк, которые выбраны в окне **Табель учета рабочего времени**.  

    > [!NOTE]  
>   Вы можете отправлять только строки табеля, для которых введено время.  
6. Чтобы изменить информацию в строке, для которой установлено значение **Представляется**, выделите строку и выберите действие **Открыть**.

    > [!NOTE]  
>   Менеджер может отклонить строку табеля, которая представлена на утверждение. Если строка имеет статус **Отклонено**, вы можете внести изменения в строку, а затем выбрать **Отправить** еще раз.  
7. Нажмите кнопку **ОК**.

## <a name="to-approve-or-reject-a-time-sheet"></a>Утверждение или отклонение табеля
Табель должны быть отправлен для утверждения, прежде чем его можно будет использовать. Можно принимать или отклонять отдельные строки в табеле либо отправлять обратно для выполнения дополнительного действия. Табель может быть утвержден двумя способами:

* Администратор табелей может утвердить любой табель.
* Лицо, указанное в поле **Код пользователя, утверждающего табель** в карточке ресурса, может утвердить табели этого ресурса. Дополнительные сведения см. в разделе [Практическое руководство. Настройка табелей](projects-how-setup-time-sheets.md).

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Управление табелями учета рабочего времени**, а затем выберите связанную ссылку.
2. Выберите табель в списке.  
3. В окне **Табель учета рабочего времени** выберите действие **Утвердить**, затем выберите действие **Все отправленные строки** для утверждения всех строк или действие **Только выбранные строки** для утверждения только строк, которые выбраны в окне **Табель учета рабочего времени**.
4. Нажмите кнопку **ОК**.  
5. Можно также выбрать действие **Отклонить** и выполнить шаги с 4 по 5.  

> [!TIP]  
>   Используйте информационные панели **Статус табеля** и **Сводка по фактическим и бюджетным суммам** для общего просмотра сведений о табеле учета рабочего времени.

После утверждения или отклонение табеля его нельзя изменить, пока он не будет повторно открыт. В следующей процедуре объясняется, как повторно открыть утвержденный или отклоненный табель.

## <a name="to-reopen-a-time-sheet"></a>Повторное открытие табеля
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), **введите Управление табелями учета рабочего времени** или **Табели учета рабочего времени**, а затем выберите связанную ссылку.
2. Откройте табель из списка.  

    > [!NOTE]  
>   Повторно можно открыть только строки с состоянием **Одобрено**. Невозможно повторно открыть строки со статусом **Отклонено**. Невозможно повторно открыть табель, если он был учтен.  
3. В окне **Табель учета рабочего времени** выберите действие **Открыть**, затем выберите действие **Все отправленные строки** для повторного открытия всех строк или действие **Только выбранные строки** для повторного открытия только строк, которые выбраны в окне **Табель учета рабочего времени**.
4. Нажмите кнопку **ОК**. Статус строки или строк табелей изменяется на **Представляется**.  

## <a name="to-post-time-sheet-lines-in-a-resource-journal"></a>Учет строк табеля в журнале ресурсов
После утверждения операций табеля для ресурса можно выполнять их учет в соответствующем журнале ресурсов.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал ресурсов**, а затем выберите связанную ссылку.  
2. Выберите действие **Предлагать строки из табелей**.  
3. Заполните соответствующим образом поля.  
4. Нажмите кнопку **ОК**. Операции для использования создаются в журнале ресурсов, в котором можно изменить информацию как нужно.  
5. Выберите действие **Учесть**.  
6. Чтобы проверить учет, выберите действие **Книга операций**. Открывается окно **Книга операций по ресурсам** с результатом учета журнала ресурсов.

## <a name="to-post-time-sheet-lines-in-a-job-journal"></a>Учет строк табеля в журнале работ
После утверждения операций табеля для работы можно выполнять их учет в соответствующем журнале работ.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журнал работ**, а затем выберите связанную ссылку.  
2. Выберите действие **Предлагать строки из табелей**.  
3. Заполните соответствующим образом поля.  
4. Нажмите кнопку **ОК**. Операции для использования создаются в журнале работ, в котором можно изменить информацию как нужно.  

    > [!NOTE]  
>   Информация о типе работы и о том, оплачивается ли эта работа, копируется из строки табеля. Если необходимо, можно сократить количество и выполнить частичный учет. Если уменьшить количество, то в следующий раз при выборе действия **Предлагать строки из табелей** создаваемая строка будет содержать остаток часов.  
5. Выберите действие **Учесть**.  
6. Чтобы проверить учет, выберите действие **Книга операций**. Открывается окно **Книга операций по работам** с результатом учета журнала ресурсов.

## <a name="to-archive-time-sheets"></a>Архивирование табелей
После учета табелей их можно поместить в архив для обращения в будущем. Все строки табелей необходимо учесть, прежде чем табель можно будет поместить в архив.

> [!NOTE]  
>   Примечание. Когда архивируется табель учета рабочего времени, он удаляется из списков в окнах **Табели учета рабочего времени** и **Управление табелями учета рабочего времени**.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Переместить табели учета рабочего времени менеджеров в архив**, а затем выберите связанную ссылку.  
2. Заполните поля, как требуется, и нажмите кнопку **ОК**.  
3. Для просмотра архивированных табелей выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Архивы табелей** или **Архивы табелей руководителя**, а затем выберите связанную ссылку.

## <a name="see-also"></a>См. также
[Управление проектами](projects-manage-projects.md)  
[Настройка управления проектами](projects-setup-projects.md)    
[Финансы](finance.md)  
[Покупки](purchasing-manage-purchasing.md)         
[Продажи](sales-manage-sales.md)     
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

