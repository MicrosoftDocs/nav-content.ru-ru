---
title: "Практическое руководство. Учет налоговых разниц"
description: "**Журнал налоговых разниц** используется для создания и учета транзакций для налоговых разниц. Налоговые разницы представляют собой расхождения сумм налога, вызванные различиями в правилах признания доходов и расходов в бухгалтерском и налоговом учете."
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
ms.openlocfilehash: 93357ee4df44ad5151afd363ed6923d5f0d70145
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-post-tax-differences"></a>Практическое руководство. Учет налоговых разниц
**Журнал налоговых разниц** используется для создания и учета транзакций для налоговых разниц. Налоговые разницы представляют собой расхождения сумм налога, вызванные различиями в правилах признания доходов и расходов в бухгалтерском и налоговом учете.  

С помощью окна **Журнал налоговых разниц** можно вручную создавать операции налоговых разниц и изменять имеющиеся операции, созданные периодическими процедурами расчета налоговых разниц. При учете окна **Журнал налоговых разниц** соответствующие операции учитываются в выбранных учетных группах.  

## <a name="to-post-tax-differences"></a>Учет налоговых разниц  

1.  Выберите значок ![Поиск страницы или отчета](../../media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Журналы налоговых разниц**, а затем выберите связанную ссылку.  
2.  Введите значения в поля, как описано в следующей таблице.  

    |Поле|Описанием|  
    |---------------------------------|---------------------------------------|  
    |**Дата учета**|Введите дату транзакции.|  
    |**Номер документа:**|Введите номер документа из исходной транзакции.|  
    |**Описание**|Введите описание транзакции.|  
    |**Тип налог. разницы**|Укажите, является налоговая разница **постоянной** или **временной**.|  
    |**Код налог. разницы**|Выберите идентификационный код дохода или расхода, определяющий источник налоговой разницы.|  
    |**Тип источника**|Выберите источник налоговой разницы. Возможные варианты: **Расходы будущих периодов**, **Основное средство** и **Нематериальный актив**.|  
    |**Номер источника**|Если поле **Тип источника** имеет значение **Расходы будущих периодов**, введите код расходов будущих периодов.  В противном случае это поле следует оставить пустым.|  
    |**Код Юрисдикции**|Выберите код юрисдикции, который используется для расчета налогооблагаемых прибыли и убытков для налоговых разниц.|  
    |**Код Нормы**|Выберите код юрисдикции нормы, который используется для расчета налогооблагаемых прибыли и убытков для налоговых разниц.|  
    |**Ставка Налога**|Введите ставку налога на прибыль, которая используется для расчета налоговых разниц.|  
    |**Сумма (БУ)**|Введите сумму расходов на основании данных бухгалтерского учета. Эта информация используется, если настроен расчет налоговых разниц для периода времени.|  
    |**Сумма (НУ)**|Введите сумму расходов на основании транзакций налогового учета. Эта информация используется, если настроен расчет налоговых разниц для периода времени.|  
    |**Разница**|Введите значение разницы между транзакциями бухгалтерского и налогового учета.|  
    |**Сумма на Конец НП (БУ)**|Введите значение расходов и доходов по данным бухгалтерского учета с начала года.|  
    |**Сумма на Конец НП (НУ)**|Введите значение расходов и доходов по данным налогового учета с начала года.|  
    |**Разница на Конец НП**|Введите значение разницы между транзакциями бухгалтерского и налогового учета с начала года.|  
    |**Реж. расч. налог. разницы**|Определяет разницу режима подсчета. Если выбрано значение **Баланс**, разница будет рассчитываться нарастающим итогом с начала года. Если это поле не выбрано, разница будет создана для текущего периода.|  
    |**Сумма Налога**|Определяет результат подсчета. Значение этого поля корректирует налог на прибыль в транзакциях бухгалтерского учета.|  
    |**Сумма Налог. Актива**|Определяет рассчитанную сумму налогового актива.|  
    |**Сумма Налог. Обязательства**|Определяет рассчитанную сумму налогового обязательства.|  
    |**Сумма Списания ОНО/ОНА**|Определяет сумму налога, которая списывается при реализации товара.|  
    |**ОНА Начальное Сальдо**|Определяет начальную сумму реализации ОНО/ОНА перед расчетом.|  
    |**ОНО Начальное Сальдо**|Определяет обязательства по начальной сумме реализации ОНО/ОНА перед расчетом.|  
    |**ОНА Конечное Сальдо**|Определяет сумму реализации ОНО/ОНА после расчета.|  
    |**ОНО Конечное Сальдо**|Определяет обязательства по сумме реализации ОНО/ОНА после расчета.|  
    |**Режим Выбытия**|Выберите, требуется ли записать налоговую разницу или преобразовать ее в постоянную разницу.|  
    |**Дата Выбытия**|Введите дату реализации товара.|  
    |**Частичное Выбытие**|Выберите, если требуется реализовать товар, который приводит к расхождениям в коде расходов или доходов. Если данное поле не выбрано, налоговые разницы списываются.|  

3.  Выберите действие **Учесть**. Транзакции журнала налоговых разниц будут учтены.  
4.  Выберите действие **Книга операций**, чтобы открыть окно **Книга операций по налоговым разницам** и проверить учтенные операции.  

## <a name="see-also"></a>См. также  
 [Налоговые разницы](tax-differences.md)   
 [Настройка расчета налоговых разниц](setting-up-tax-difference-calculation.md)   
 [Налоговый учет](tax-accounting.md)   
 [Налоговые отчеты](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3)   
 [Налоговые регистры](tax-registers.md)   
 [Практическое руководство. Создание налоговых регистров](how-to-create-tax-registers.md)
