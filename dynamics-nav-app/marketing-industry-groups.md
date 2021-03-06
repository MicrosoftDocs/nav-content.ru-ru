---
title: "Настройка отраслевых групп в контактных организациях"
description: "Описывается порядок определения отраслевой группы и ее назначения контактной организации, например в сфере розничной торговли или автомобильной промышленности."
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
ms.openlocfilehash: 62d946155cb65a3e976771bc5029878893bd4797
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-industry-groups-for-contact-companies"></a>Практическое руководство. Настройка отраслевых групп в контактных организациях
Отраслевые группы используются для указания типа отрасли, к которой относится контакт, например розничная торговля или автомобильное производство.

Использование отраслевых групп для контактов — это двухэтапный процесс. Сначала вы определяете код отраслевой группы. Этот шаг нужно выполнить один раз для каждой отраслевой группы. После настройки кода отраслевой группы можно начинать назначение кода контактным организациям.

> [!NOTE]  
>   При планировании синхронизации контактов с поставщиками, клиентами или банковскими счетами в других частях приложения может понадобиться настроить для них деловое отношение.

## <a name="to-define-an-industry-group-code"></a>Определение кода отраслевой группы
Код отраслевой группы определяет тип или категорию группы, например РЕКЛАМА для сферы рекламы или ПРЕССА для ТВ и радио. Допускается наличие нескольких кодов отраслевых групп. Для определения отраслевых групп используется окно **Отраслевые группы**.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Отраслевые группы**, а затем выберите связанную ссылку.
2. Выберите действие **Создать**, введите код и описание. Длина кода не должна превышать 11 знаков (допускается сочетание букв и цифр).

## <a name="AssignIndustryGroupContact"></a> Присвоение отраслевых групп контакту
Нельзя назначать отраслевые группы контактным лицам — только организациям.

1. Откройте контакт.
2. Выберите действие **Организация**, а затем действие **Отраслевые группы**. Откроется окно **Отраслевые группы контакта**.
3. В поле **Код отраслевой группы** выберите отраслевую группу, которую нужно назначить.

Повторите эти шаги для назначения желаемого количества отраслевых групп. Также можно назначать отраслевые группы из списка контактов, следуя той же процедуре.

Число отраслевых групп, назначенных контакту, отображается в окне **Контакт** в разделе **Сегментация** в поле **Число отраслевых групп**.

После назначения контактам отраслевых групп эта информация может использоваться для выбора контактов для сегментов. Дополнительные сведения см. в разделе [Практическое руководство. Добавление контактов к сегментам](marketing-add-contact-segment.md).

## <a name="see-also"></a>См. также
[Создание контактных организаций](marketing-create-contact-companies.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

