---
title: "Практическое руководство. Создание налоговых регистров"
description: "В следующей процедуре показан порядок создания налоговых регистров."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 6a4c8b676155cdd7636ae89ce64f8e6f0c1df499
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-create-tax-registers"></a>Практическое руководство. Создание налоговых регистров
В следующей процедуре показан порядок создания налоговых регистров.  
  
1.  Выберите **Финансовый менеджмент**, выберите **Налоговый учет**, выберите **Настройка**, выберите **Налоговые регистры**, затем выберите **Разделы**.  
  
2.  В окне **Секции налоговых регистров** выберите кнопку **Функции**.  
  
3.  Выберите одно из следующих полей:  
  
    -   **Копирование секции** — копируются данные из одного налогового регистра в другой.  
  
    -   **Очистить регистры** — очищает данные, уже созданные в налоговых регистрах, и используется для отладки условий пересчета налоговых регистров.  
  
    -   **Создать регистры** — создает данные в налоговых регистрах**.**  
  
4.  Для создания данных выберите **Создать регистры**. Будет открыто окно **Создание налогового регистра**.  
  
5.  На вкладке **Общее** введите значения в поля, описанные в следующей таблице.  
  
    |Поле|Описанием|  
    |-----------|-----------------|  
    |**Периодичность**|Введите период для создания данных в регистрах налогового учета. Допустимые значения:<br /><br /> -   **Месяц**<br />-   **Квартал**<br />-   **Год** **Примечание**. Если указан месяц, данные в выбранных регистрах будут созданы специально для этого месяца. Если выбрать квартал, данные будут созданы для каждого из трех месяцев этого квартала. Если выбрать год, данные будут созданы для каждого из 12-ти месяцев этого года.|  
    |**Учетный период**|Значение, вводимое в это поле, зависит от значения, выбранного в поле "Периодичность". Выберите учетный период (**Месяц**, **Квартал** или **Год**).|  
    |**От, До**|Эти поля заполняются автоматически и показывают дату начала и дату конца выбранного периода.|  
    |**Операции ГК, Поставщики/Клиенты, Товары, Основные средства, РБП, Зарплата, Шаблоны**|Выберите поля для расчета регистров соответствующего типа.|  
    |**Статус**|В этом поле отображается информация о версии налогового регистра.|  
    |**Дата Начала, Дата Конца**|В этом поле отображаются даты, указанные при настройке этой версии налогового регистра.|  
  
6.  Выберите **ОК**, чтобы создать налоговый регистр.  
  
    > [!NOTE]  
    >  Если выбрано создание регистра для уже рассчитанного периода, на экран выводится предупреждение. На этом этапе создания налогового регистра можно либо продолжить расчет и удалить имеющиеся данные, либо прекратить создание.  
  
7.  Для просмотра результата расчетов в окне **Накопление налогового регистра** выберите **Финансовый менеджмент**, выберите **Налоговый учет**, выберите **Отчетность**, затем выберите **Налог на прибыль**.  
  
8.  Используя список регистров, можно просматривать содержимое любого регистра; используя стрелки вверху окна, можно просматривать информацию, переходя от одного регистра к другому.  
  
9. При помощи стрелок и кнопок в нижнем левом углу окна можно просматривать содержимое регистров для рассчитанных ранее периодов.  
  
10. Выберите кнопку **Раскрытие** в поле **Сумма** для просмотра источников, на основе которых был выполнен этот расчет. Источником может являться налоговый регистр или список транзакций, сформировавших эту сумму, в зависимости от настроек. Если источником формирования этой суммы является налоговый регистр, выберите кнопку **Раскрытие**, чтобы открыть окно с информацией об исходном налоговом регистре. После этого выберите кнопку **Раскрытие** в поле **Сумма** этой формы, чтобы получить список транзакций, сформировавших данную сумму.  
  
11. Выберите документ и выберите **Навигация**, чтобы получить все транзакции выбранного документа.  
  
12. Выберите **Показать** для просмотра всех транзакций любой созданной книги операций.  
  
## <a name="see-also"></a>См. также  
 [Налоговый учет](tax-accounting.md)   
 [Налоговые регистры](tax-registers.md)   
 [Практическое руководство. Настройка секций налогового регистра](how-to-set-up-tax-register-sections.md)   
 [Сбор сведений о налоге на прибыль для налоговой декларации](collecting-profit-tax-information-for-tax-declaration.md)