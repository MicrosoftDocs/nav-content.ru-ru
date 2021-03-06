---
title: "Настройка должностных обязанностей для контактов"
description: "Вы можете определять коды должностной обязанностей и назначать их контактам, чтобы задавать задачи, за которые отвечает контакт в своей организации, например за ИТ или производство."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: task, to-do, relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7d4481226772b902eeb1b526a291adff70372908
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-job-responsibilities-for-contact-persons"></a>Практическое руководство. Настройка должностных обязанностей для контактных лиц
Вы можете добавить информацию о должностных обязанностей контактных лиц, чтобы показать, за что контактное лицо ответственно в своей организации, например ИТ, управление или производство. Эту информацию можно использовать при вводе информации о контактах.

Использование должностных обязанностей для контактов — это двухэтапный процесс. Сначала вы определяете код должностной обязанности. Этот шаг нужно выполнить один раз для каждой должностной обязанности. После настройки кода должностной обязанности можно начинать назначение кода контактным лицам.

## <a name="to-define-a-job-responsibility-code"></a>Определение кода должностной обязанности
Код должностной обязанности определяет тип или категорию работы, например МАРКЕТИНГ или ЗАКУПКИ. Допускается наличие нескольких кодов должностных обязанностей. Для определения должностной обязанности используется окно **Должностные обязанности**.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Должностные обязанности**, а затем выберите связанную ссылку.
2. Выберите действие **Создать**, введите код и описание. Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).

## <a name="to-assign-job-responsibilities-to-a-contact-person"></a>Назначение должностных обязанностей контактному лицу
Должностные обязанности не могут назначаться контактным организациям.

1. Откройте контактное лицо.
2. Выберите действие **Лицо**, а затем выберите действие **Должностные обязанности**. Откроется окно **Должностные обязанности контакта**.
3. В поле **Код должностной обязанности** выберите должностную обязанность, которую требуется назначить.

Повторите эти шаги для назначения желаемого количества функциональных обязанностей. Также можно назначать должностные обязанности из списка контактов, следуя той же процедуре.

Число должностных обязанностей, назначенных контакту, отображается в окне **Контакт** в разделе **Сегментация** в поле **Число должностных обязанностей**.

После назначения контактам должностных обязанностей можно использовать эту информацию для выбора контактов для сегмента. Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).

## <a name="see-also"></a>См. также
[Создание контактных лиц](marketing-create-contact-persons.md)  
[Создание контактных организаций](marketing-create-contact-companies.md)  
[Работа с Dynamics NAV](ui-work-product.md)

