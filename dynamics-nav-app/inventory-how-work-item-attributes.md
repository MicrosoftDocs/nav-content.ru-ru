---
title: "Практическое руководство. Работа с атрибутами продуктов"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: eaf539f1d4d00c2cd5679f39f29a3428e33ee1fd
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-item-attributes"></a>Практическое руководство. Работа с атрибутами продуктов
Когда клиенты интересуются товаром, с помощью личного обращения или в интегрированном интернет-магазине, они могут осуществлять запрос или поиск по определенным характеристикам, например по высоте или модельному году. Чтобы предоставить такую услугу, вы можете назначить товарам атрибуты различных типов, которые можно использовать при поиске товаров.

Можно также назначить атрибуты товаров товарным категориям, которые затем применяются к товарам, которые используют эти товарные категории. Дополнительные сведения см. в разделе [Практическое руководство. Категоризация товаров](inventory-how-categorize-items.md).

## <a name="to-create-item-attributes"></a>Создание атрибутов товара
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Атрибуты товаров**, а затем выберите связанную ссылку.
2. В окне **Атрибуты товаров** выберите действие **Создать**.
3. В окне **Атрибуты товаров** заполните поля, как требуется. Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.

**Примечание**. Если выбрать **Параметр** в поле **Тип**, то вы можете выбрать действие **Значения атрибута товара**, чтоб создать значения для этого атрибута товара. Дополнительные сведения см. в разделе "Создание значений для атрибутов товаров типа "Параметр"".  

## <a name="to-create-values-for-item-attributes-of-type-option"></a>Создание значений для атрибутов товаров типа "Параметр"
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Атрибуты товаров**, а затем выберите связанную ссылку.
2. В окне **Атрибуты товаров** выберите атрибут товара типа «Параметр», для которого требуется создать значения, затем выберите действие **Значения атрибута товара**.
3. В окне **Значения атрибута товара** заполните поля, как требуется. Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.

## <a name="to-assign-item-attributes-to-items"></a>Назначение товарам атрибутов товара
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Товары**, а затем выберите связанную ссылку.
2. В окне **Товары** выберите атрибут товара, которому будут назначены атрибуты товара, а затем выберите действие **Атрибуты**.
3. В окне **Значения атрибута товара** выберите действие **Создать**.
4. В поле **Атрибут** нажмите кнопку AssistEdit и выберите существующее значение атрибута товара. Можно также выбрать действие **Создать**, чтобы сначала создать новый атрибут товара, как объясняется в разделе "Создание атрибутов товара".
5. В поле **Значение** введите значение атрибута товара, например «2010» для атрибута «Модельный год».
6. Для атрибутов товара типа «Параметр» нажмите кнопку AssistEdit в поле **Значение** и выберите значение атрибута товара. Можно также выбрать действие **Создать**, чтобы сначала создать новое значение атрибута товара, как объясняется в разделе "Создание значений для атрибутов товаров типа "Параметр"".
7. Повторите шаги с 4 по 6 для всех атрибутов товаров, которые нужно назначить товару.

## <a name="to-assign-item-attributes-to-item-categories"></a>Назначение атрибутов товара товарным категориям
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Категории товара**, затем выберите связанную ссылку.
2. В окне **Категории товара** выберите категорию товара, которой будут назначены атрибуты товара, затем выберите действие **Правка**.
3. В окне **Карточка категории товаров** на экспресс-вкладке **Атрибуты** выберите действие **Создать**.
4. В поле **Атрибут** нажмите кнопку AssistEdit и выберите существующее значение атрибута товара. Можно также выбрать действие **Создать**, чтобы сначала создать новый атрибут товара, как объясняется в разделе "Создание атрибута товара".
5. В поле **Значение по умолчанию** нажмите кнопку AssistEdit и выберите значение атрибута товара.
6. Повторите шаги 4 и 5 для всех атрибутов товаров, которые нужно назначить категории товаров.

**Примечание**. Атрибуты товаров для родительской категории товара будут наследоваться дочерними категориями товаров. Это обозначается полем **Унаследовано от** на экспресс-вкладке **Атрибуты**. Дополнительные сведения см. в разделе [Практическое руководство. Категоризация товаров](inventory-how-categorize-items.md).

## <a name="to-filter-by-item-attributes"></a>Фильтрация по атрибутам товаров
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Товары**, а затем выберите связанную ссылку.
2. В окне **Товары** выберите действие **Фильтр по атрибутам**.
3. В окне **Фильтр товаров по атрибутам** нажмите кнопку AssistEdit в поле **Атрибут**, затем выберите атрибут товара.
4. В поле **Значение** нажмите кнопку AssistEdit и выберите значение атрибута для фильтрации товаров.

    **Примечание**. Можно выбирать значения только для атрибутов товаров, имеющих фиксированные значения, например цвет. Для атрибутов товаров с переменными значениями, например для ширины, необходимо указывать значения атрибута, сначала выбрав условие. См. шаг 5.
5. В поле **Значение** переменного атрибута товара нажмите кнопку AssistEdit.
6. В окне **Определение значения фильтра** в поле **Условие** выберите стрелку раскрывающегося списка и выберите условие.
7. В поле **Значение** введите значение атрибута для фильтрации товаров.

    **Пример**. Для фильтрации по товарам, описание материалов которых начинается со слова "синий", заполните поля следующим образом: поле **Атрибут**: "Описание материала", поле **Условие**: "Начинается с", поле **Значение**: "синий".
8. Выберите кнопку **ОК**.   

Товары в окне **Товары** фильтруются по указанным значениям атрибутов товаров.

## <a name="see-also"></a>См. также
[Практическое руководство. Категоризация товара](inventory-how-categorize-items.md)    
[Практическое руководство. Регистрация новых продуктов](inventory-how-register-new-products.md)  
[Управление запасами](inventory-manage-inventory.md)  
[Работа с Dynamics NAV](ui-work-product.md)
