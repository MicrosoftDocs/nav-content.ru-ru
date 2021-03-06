---
title: "Настройка организационных уровней для контактных лиц"
description: "В можете определить организационный уровень и назначить его контакту, чтобы указать положение, которое они занимают в организации, например относятся к высшему руководству."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, client, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fe8554f0335ef332fc940d020c3f8441d8e1359d
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-organizational-levels-for-contact-persons"></a>Практическое руководство. Настройка организационных уровней для контактных лиц
Вы можете использовать организационные уровни для контактов, чтобы задавать положение, которое они занимают в организации, например относятся к высшему руководству. Эту информацию можно использовать при вводе информации о контактах.

Использование организационных уровней для контактов — это двухэтапный процесс. Сначала вы определяете код организационного уровня. Этот шаг нужно выполнить один раз для каждого организационного уровня. После настройки кода организационного уровня можно начинать назначение кода контактным лицам.

## <a name="to-define-an-organizational-level-code"></a>Определение кода организационного уровня
Код организационного уровня определяет тип или категорию организационного уровня, например ГЕД или ФИД. Допускается наличие нескольких кодов организационных уровней. Для определения организационного уровня используется окно **Организационные уровни**.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Организационные уровни**, а затем выберите связанную ссылку.
2. Выберите действие **Создать**, введите код и описание. Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).

## <a name="to-assign-organizational-levels-to-a-contact-person"></a>Назначение организационных уровней контактному лицу
Организационные уровни можно назначать только контактным лицам, а не контактным организациям. Каждому контакту можно назначить только один организационный уровень.

1. Откройте контакт.
2. В поле **Организационные уровни** выберите код, который нужно назначить.

После назначения организационных уровней контактам можно использовать эту информацию для создания сегментов.

После назначения контактам должностных обязанностей можно использовать эту информацию для выбора контактов для сегмента. Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).

## <a name="see-also"></a>См. также
[Создание контактных организаций](marketing-create-contact-companies.md)  
[Создание контактных лиц](marketing-create-contact-persons.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

