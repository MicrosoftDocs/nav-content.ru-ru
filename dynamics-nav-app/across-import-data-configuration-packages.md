---
title: "Использование Excel для импорта данных в Dynamics NAV"
description: "Используйте пакет конфигурации по умолчанию для добавления данных в Excel и импорта данных обратно в Dynamics NAV."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: migration, Excel
ms.date: 07/05/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: eb9b7137ee31824ba845ff336c00c6f0e59f6f5c
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="importing-data-from-legacy-accounting-software-using-a-configuration-package"></a>Импорт данных из устаревшего ПО учета с использованием пакета конфигурации
Можно импортировать основные данные и некоторые транзакционные данные из других финансовых систем на основе пакета конфигурации по умолчанию в [!INCLUDE[d365fin](includes/d365fin_md.md)]. В окне **Пакеты конфигураций** можно использовать пакет для импорта и проверки данных перед применением пакета.  

Если вам знакомы службы RapidStart для Microsoft Dynamics, вам также знакомы пакеты конфигураций. Пакет конфигурации по умолчанию поддерживает наиболее распространенные типы данных, которые требуется импортировать из устаревшей системы. Затем в Excel можно добавить данные устаревшей системы и настроить их согласно бизнес-логике [!INCLUDE[d365fin](includes/d365fin_md.md)].  

> [!TIP]  
>   Кроме того, можно использовать мастеры миграции данных для импорта данных из QuickBooks или Dynamics GP. Дополнительные сведения см. в разделе [Миграция данных QuickBooks](ui-extensions-quickbooks-data-migration.md) или [Миграция данных Dynamics GP](ui-extensions-dynamicsgp-data-migration.md).  

## <a name="working-with-data-in-excel"></a>Работа с данными в Excel
При экспорте пакета конфигурации по умолчанию в Excel созданная книга содержит лист для каждой таблицы в пакете. Чтобы упростить задачи, можно воспользоваться преимуществами инструментов управления XML, которые встроены в Excel. Также можно воспользоваться встроенными функциями Excel, чтобы помочь с форматом данных и поместить данные в правильную ячейку. Например, добавьте пустой лист и скопируйте в него устаревшие данные. Затем создайте формулу Excel для сопоставления данных в листе преобразования между полями в экспортированном листе и устаревшими данными клиента. После сопоставления всех данных скопируйте диапазон данных в табличный журнал.  

> [!IMPORTANT]  
>  Не изменяйте столбцы в журналах. Если они перемещаются, изменяются или удаляются, то импортировать лист в [!INCLUDE[d365fin](includes/d365fin_md.md)] невозможно.

## <a name="tables-in-the-default-configuration-package"></a>Таблицы в пакете конфигурации по умолчанию
Пакет конфигурации по умолчанию поддерживает следующие таблицы:

-   Условия оплаты
-   Ценовая группа клиента
-   Метод поставки
-   Менеджер по продажам/закупкам
-   Склады
-   Счет ГК
-   Клиент
-   Поставщик
-   Пункт меню
-   Заголовок продажи
-   Строка продажи
-   Заголовок покупки
-   Строка покупки
-   Строка финансового журнала
-   Строка журнала товаров
-   Учетная группа клиента
-   Учетная группа поставщика
-   Учетная группа товаров
-   Единица измерения
-   Общая бизнес-группа
-   Общая товарная группа
-   Общая настройка учета
-   Территория
-   Категория товара
-   Цена продажи
-   Цена покупки

## <a name="importing-customer-data"></a>Импорт данных клиента
После ввода данных клиента в Excel вам следует импортировать данные в [!INCLUDE[d365fin](includes/d365fin_md.md)]. В окне **Пакеты конфигураций** импортируйте данные из файлов Excel и проверьте соответствие данных с [!INCLUDE[d365fin](includes/d365fin_md.md)] перед применением пакета.

## <a name="see-also"></a>См. также
[Импорт бизнес-данных из других финансовых систем](upload-data.md)  
[Миграция данных QuickBooks](ui-extensions-quickbooks-data-migration.md)  
[Миграция данных Dynamics GP](ui-extensions-dynamicsgp-data-migration.md)

