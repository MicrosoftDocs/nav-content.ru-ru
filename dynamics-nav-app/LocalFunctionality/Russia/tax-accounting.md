---
title: "Налоговый Учет"
description: "В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно настроить и вести налоговые регистры для отслеживания подлежащих налогообложению прибылей и убытков."
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
ms.openlocfilehash: deae926bae1304fc9520fdc7f92da3ce109590c4
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="tax-accounting"></a>Налоговый Учет
В [!INCLUDE[navnow](../../includes/navnow_md.md)] можно настроить и вести налоговые регистры для отслеживания подлежащих налогообложению прибылей и убытков. Это основано на следующих методах налогового учета:  

- Финансовая база данных используется для налогового учета.  
- План счетов используется для отслеживания налогооблагаемых прибылей и убытков.  
- Доходы и расходы записываются с использованием отдельных субсчетов и измерений.  
- Транзакции и расходы основных средств для будущих периодов отслеживаются с использованием книги амортизации для налогового учета.  
- Налоговые регистры группируются и суммируются ежемесячно. В каждом регистре содержится 12 значений для налогового периода 12 месяцев.  

Поскольку [!INCLUDE[navnow](../../includes/navnow_md.md)] сохраняет историю всех транзакций, подробная информация из транзакций, которая изменяет налогооблагаемую прибыль, автоматически отслеживается. Собранные сведения отображаются в налоговых регистрах в соответствии с принципами достоверности и законности налога.  

## <a name="tax-registers"></a>Налоговые регистры  
Для отслеживания налогооблагаемых прибылей и убытков используются налоговые регистры двух типов.  

|Тип налогового регистра|Описанием|  
|-----------------------|---------------------------------------|  
|Аналитический налоговый регистр|Аналитический регистр основан на операциях книги для налогооблагаемых транзакций. Информация обеспечивает непрерывное отображение в хронологической последовательности бизнес-операций, что позволяет отслеживать налогооблагаемые прибыли и убытки на основе налоговых кодов.|  
|Синтетический налоговый регистр|Синтетический регистр основан на суммарной и расчетной информации из аналитического регистра или другого синтетического регистра.|  

Транзакции обрабатываются с помощью определенных методов налогового учета, которые применяются к следующим типам налоговых регистров.  

|Налоговый регистр|Описанием|  
|------------------|---------------------------------------|  
|Операция главной книги|Аналитический регистр основан на операциях транзакций главной книги.|  
|Операция по КП|Группа аналитических регистров основана на информации, связанной с обязательствами дебиторов и кредиторов.|  
|Операция ОС|Группа аналитических регистров основана на налоговых данных для основных средств. Эта группа создается с использованием книги ОС и книги амортизации для налогового учета, которая не интегрирована с книгой финансового учета.|  
|Операция товара|Аналитический регистр основан на учтенных товарных операциях.|  
|Операция РБП|Группа аналитических регистров основана на налоговых данных для расходов будущих периодов. Эта группа создается с использованием книги ОС и книги амортизации для налогового учета, которая не интегрирована с книгой финансового учета.|  
|Накопление|Синтетический регистр основан на расчетных алгоритмах, определенных при настройке налогового регистра.|  

## <a name="see-also"></a>См. также  
 [Практическое руководство. Настройка налогового учета](how-to-set-up-tax-accounting.md)   
 [Налоговые регистры](tax-registers.md)   
 [Практическое руководство. Создание налоговых регистров](how-to-create-tax-registers.md)   
 [Практическое руководство. Настройка секций налогового регистра](how-to-set-up-tax-register-sections.md)   
 [Налоговые разницы](tax-differences.md)   
 [Налоговые отчеты](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3)

