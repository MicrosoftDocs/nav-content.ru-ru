---
title: "Персонализация рабочей области с помощью веб-клиента Dynamics NAV"
description: "Узнайте, как настраивать пользовательский интерфейс в соответствии с вашим способом работы."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customize, personalize, personalize page, personalization, hide columns, remove fields, move fields
ms.date: 07/26/2017
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c266842d4a64b62c90dab8db26f5206f9a10e4cc
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="personalizing-your-workspace-using-the-dynamics-nav-web-client"></a>Персонализация рабочей области с помощью веб-клиента Dynamics NAV
<!--NAV in the Web client-->
Можно настраивать или *персонализировать* рабочую область в соответствии со своей работой и своими предпочтениями, изменяя страницы, чтобы на них отображалась только требуемая информация в тех местах, в которых она нужна. Сделанная вами персонализация изменяет только то, что видите вы, а не то, что видят другие пользователи.

В зависимости от типа страницы и ее содержимого можно:

-   Добавлять, перемещать и удалять поля.
-   Добавлять, перемещать и удалять столбцы в списке.
-   Изменять область закрепления столбцов в списке. Область закрепления закрепляет один или несколько столбцов в левой части списка, чтобы они были всегда видны, даже при прокрутке по горизонтали.
-   Перемещать и удалять подсказки (плитки).
-   Перемещать и удалять части. Части — это части или области страницы, которые содержат, например, несколько полей, другую страницу, диаграмму или плитки.  

## <a name="to-personalize-a-page"></a>Персонализация страницы

1. В правом верхнем углу выберите ![Настройка](media/ui-experience/settings_icon_small.png "Значок настроек для ролевого центра"), затем **Персонализировать**.

    Сверху появляется баннер **Персонализация**, который указывает, что можно начинать вносить изменения.

    ![Режим персонализации](media/ui_personalize_mode_small.png "Режим персонализации")

2.  Перейдите на страницу, которую требуется персонализировать.

    Если на баннере отображается значок замка, подробнее см. в разделе [Почему страница заблокирована](ui-personalization-locked.md).

3.  Укажите на область, которые требуется персонализировать, например на поле или заголовок столбца в списке. Все, что можно персонализировать, немедленно выделяется со стрелкой или границей.
<!--
    -  If a component can be personalized, an arrow head (![Personalization indicator arrow left](media/ui_personalize_arrow_left.png "Personalization indicator arrow left") or ![Personalization indicator arrow down](media/ui_personalize_arrow_down.png "Personalization indicator arrow down")) appears.
    -   If the component is a part, the extent of the part is indicated by a border.
    -   The freeze pane in a list is indicated by a vertical line along the entire right-side of the last column of the freeze pane.
    -->

4.  Эта таблица служит для упрощения внесения изменений:     <table>
        <tr><th>Что вы хотите сделать</td><th>Как это сделать</th></tr>
        <tr><td>Что-то переместить, например поле, столбец в списке, плитку или часть</td><td> Укажите на любое место объекта, который требуется переместить, и перетащите его в новое положение. Положение указывается толстой горизонтальной или вертикальной линией.</td></tr>
        <tr><td>Что-то удалить</td><td>Выберите стрелку, затем выберите <b>Удалить</b>. </td></tr>
        <tr><td>Добавление поля или столбца</td><td>На баннере <b>Персонализация</b> выберите <b>Дополнительно</b>, затем выберите <b>Поле</b>.<br /></br>Справа открывается область <b>Добавить поле на страницу</b>. В ней приводится список полей, которые можно добавить на страницу. Поля с пометкой <b>Размещено</b> уже находятся на странице. Поля с пометкой <b>Готово</b> в настоящее время не находятся на странице.<br /></br>Чтобы добавить поле, перетащите его из этой области в требуемое место. Положение указывается толстой горизонтальной или вертикальной линией.</td></tr>
        <tr><td>Изменение области закрепления в списке на другой столбец</td><td>Выберите стрелку столбца, который должен быть последним столбцом области закрепления, затем выберите <b>Установить область закрепления</b>.<br /><br/>Если требуется восстановить для области закрепления первоначальное положение, выберите стрелку для текущего столбца области закрепления, затем выберите <b>Очистить область закрепления</b>. Примечание. Невозможно удалить первоначальную область закрепления. Всегда будет область закрепления, которая содержит по крайней мере один столбец.</td></tr>
      </table>

    > [!IMPORTANT]  
    >   Невозможно внести изменения в список, если он отображается как плитки. Необходимо сначала переключить страницу в представление списка, выбрав значок ![Показать как список](media/ui_show_as_list_icon.png "Показать как список").

5.  Можно продолжить вносить изменения на той же странице или перейти на другую страницу. Изменения автоматически сохраняются по мере их внесения. Когда все будет готово, в баннере **Персонализация** выберите **Готово**.

## <a name="clear-personalization-to-change-a-page-back-to-its-original-layout"></a>Очистка персонализации для восстановления исходной компоновки страницы
В какой-то момент может потребоваться отменить все связанные с персонализацией изменения, внесенных с течением времени на эту страницу, чтобы страница приняла первоначальный вид. Для этого на баннере **Персонализация** выберите **Дополнительно**, затем **Очистить персонализацию**.

## <a name="personalization-in-detail"></a>Подробно о персонализации
Чтобы помочь лучше понять персонализацию, вот некоторые указания.  
-   При внесении изменений на странице карточки, которая открывается из списка, эти изменения вступают в силу для всех записей, которые открываются из этого списка. Например, допустим вы открываете определенного клиента со страницы списка "Клиенты", а затем персонализируете эту страницу, добавив на нее поле. При открытии других клиентов из этого списка также будет отображаться добавленное поле.
-   Сделанные изменения влияют на все ваши ролевые центры. Например, если изменить список "Клиенты", когда в ролевом центре задан "Бизнес-руководитель", эти изменения будут также отображаться в списке "Клиенты", когда для ролевого центра задан обработчик заказов на продажу.
-   Изменения на странице в области применяются к странице в любом месте, в котором она отображается.  
-   Поля и столбцы можно добавлять только из предопределенного списка, который зависит от страницы. Невозможно создать новые.

## <a name="see-also"></a>См. также
[Обзор персонализации](ui-personalization-overview.md)  
[Управление персонализацией](ui-personalization-manage.md)  
[Работа с [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-work-product.md)  
[Практическое руководство. Изменение ролевого центра](change-role.md)  

