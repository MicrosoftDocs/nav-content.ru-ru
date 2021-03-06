---
title: "Настройка модуля \"Запасы\""
description: "Как часть управления запасами, можно настроить запасы для назначения товарных издержек по покупкам из зарубежных стран и регионов в соответствии с весом или объемом, и использовать один столбец для первоначального учета и корректировок."
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
ms.openlocfilehash: 78bf36201afeb3afd1b4fb4bb98107e108ddbc0b
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="inventory-setup"></a>Настройка модуля "Запасы"
Как часть управление запасами, можно настроить запасы, чтобы:  

- Назначать товарные издержки при покупках из зарубежных стран или регионов на основе веса или объема.  
- Использовать один и тот же столбец для первоначального учета и корректировок.  

## <a name="item-charge-assignment-in-purchase-documents"></a>Назначение товарных издержек в документах покупки  
В России [!INCLUDE[navnow](../../includes/navnow_md.md)] может назначать товарные издержки при покупках из зарубежных стран или регионов на основе веса или объема. Для каждого товара в окне **Карточка товара** на экспресс-вкладке **Внешняя торговля** если установлены флажки **Вес брутто обязателен** и **Объем единицы обязателен**, необходимо заполнить поля **Вес брутто** и **Объем единицы**. Когда вы предлагает назначение товарных издержек по заказу на покупку, необходимо указать, что принцип распределения, вес и объем добавляются в параметры для выбора. Дополнительные сведения см. в разделе [Практическое руководство. Использование товарных издержек для учета дополнительных торговых расходов](../../payables-how-assign-item-charges.md).

## <a name="item-corrections"></a>Корректировки товара  
Можно настраивать склад на использование одного столбца для первоначального и корректирующего учета. Эта функция часто называется *красный сторно*.  

Можно использовать учет "красный сторно" для учета корректировок следующих операций склада:  

- Корректирующие операции в журнале товаров.  
- Сторнирование товарных документов, таких как акты оприходования и акты списания товаров.  
- Учет журналов переоценки или реклассификации товаров.  
- Периодические корректировки себестоимости товара.  

Дополнительные сведения см. в разделе [Практическое руководство. Учет корректировок "красный сторно"](how-to-post-red-storno-corrections.md).  

### <a name="adjusting-item-cost"></a>Корректировка себестоимость товаров  
Если выбрано поле "Применять красное сторно" в окне **Настройка модуля "Запасы"**, то отрицательные отклонения учитываются в соответствии с "красным сторно" при исполнении пакетного задания **Коррекция себест. запасов**.  

## <a name="see-also"></a>См. также  
 [Акты Оприходования](item-documents.md)   
 [Акты обязательств по товару](item-obligatory-acts.md)   
 [Практическое руководство. Учет коррекций "красный сторно"](how-to-post-red-storno-corrections.md)   
 [Практическое руководство. Использование товарных издержек для учета дополнительных торговых расходов](../../payables-how-assign-item-charges.md)

