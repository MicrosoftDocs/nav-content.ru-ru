---
title: "Ввод критериев в фильтрах"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8eab393a0a77f9f1595ca1247c7549e68b491cb2
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="entering-criteria-in-filters"></a>Ввод критериев в фильтрах
Если необходимо выполнить поиск данных, таких как название клиента, адреса или товарные группы, вводятся критерии. В критериях поиска можно использовать все цифры и буквы, которые вводятся в соответствующие поля. Кроме того, для дополнительной фильтрации результатов можно использовать специальные символы.

## <a name="searching-using-the-quick-filter"></a>Поиск с помощью экспресс-фильтра
Вы можете добавить фильтры на все страницы с помощью экспресс-фильтра. Экспресс-фильтр включается при выборе значка лупы в правом верхнем углу страницы. Данный тип фильтра используется для быстрого ввода критериев.

**Внимание**. Экспресс-фильтр обеспечивает удобный доступ к фильтруемым данным путем ввода простого текста, а также множество вариантов указания критериев поиска. В зависимости от того, введен ли обычный текст или текст с символами, поведение экспресс-фильтра отличается.  
- Если в критериях поиска ввести обычный текст, критерии поиска будут рассматриваться без учета регистра и будет выполняться поиск определенного текста.  
- Если в критериях поиска ввести тест с символами, критерии поиска будут рассматриваться с учетом регистра и будет выполняться поиск точного текста.

### <a name="quick-filter-criteria"></a>Критерии экспресс-фильтра
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Критерии поиска</TH>
    <TH>Интерпретируется как…</TH>
    <TH>Возвращает…</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*man*</TD>
    <TD>Все записи, содержащие текст man, без учета регистра.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>Все записи, содержащие текст se, без учета регистра.</TD>
  </TR>
  <TR>
    <TD>>Man*</TD>
    <TD>Начинается с Man с учетом регистра.</TD>
    <TD>Все записи, которые начинаются с текста Man.</TD>
  </TR>
  <TR>
    <TD>'man'</TD>
    <TD>Точный текст с учетом регистра.</TD>
    <TD>Все записи, которые в точности соответствуют man.</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Заканчивается на man без учета регистра.</TD>
    <TD>Все записи, которые заканчиваются на man.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Начинается на man без учета регистра.</TD>
    <TD>Все записи, которые начинаются на man.</TD>
  </TR>
</TABLE>

**Примечание**. Нельзя использовать подстановочные символы при фильтрации в полях перечислений, например в поле **Статус** заказов на продажу. Чтобы ввести фильтр для данного типа поля, можно ввести в качестве параметра фильтра числовое значение. Например, в поле **Статус** в заказе на продажу, которое имеет значения **Открыть**, **Выпущено**, **Ожидает утверждения** и **Ожидает предоплаты**, используйте значения **0**, **1**, **2**, и **3** для фильтрации этих параметров.  

## <a name="see-also"></a>См. также
[Работа с Dynamics NAV](ui-work-product.md)
