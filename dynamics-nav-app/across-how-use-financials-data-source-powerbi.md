---
title: "Создание источника данных Power BI с помощью вашего Dynamics NAV"
description: "Можно сделать данные Dynamics NAV доступными в качестве источника данных в Power BI и создать мощные отчеты о состоянии вашего бизнеса."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: business intelligence, KPI, Odata, Power App, SOAP, analysis
ms.date: 06/06/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b1beb7286eb221e5df3e7d5b2050ddcb389a0a07
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="using-included365finincludesd365finmdmd-as-a-power-bi-data-source"></a>Использование [!INCLUDE[d365fin](includes/d365fin_md.md)] как источника данных Power BI
Можно сделать данные [!INCLUDE[d365fin](includes/d365fin_md.md)] доступными в качестве источника данных в Power BI и создать мощные отчеты о состоянии вашего бизнеса.  

> [!NOTE]  
>   Вы должны иметь допустимую учетную запись в [!INCLUDE[d365fin](includes/d365fin_md.md)] и в Power BI. Кроме того, необходимо загрузить [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).  

## <a name="to-add-included365finincludesd365finmdmd-as-a-data-source-in-power-bi-desktop"></a>Добавление [!INCLUDE[d365fin](includes/d365fin_md.md)] как источника данных в Power BI Desktop
1. В Power BI Desktop в левой области навигации выберите **Получить данные**.
2. В окне **Получить данные** выберите **Веб-службы**, выберите **Dynamics NAV**, а затем нажмите кнопку **Подключиться**.

   Power BI отобразит мастер с руководством по процессу подключения. Первым шагом будет ввод URL-адреса OData и названия организации, связанного с учетной записью [!INCLUDE[d365fin](includes/d365fin_md.md)].  

   Для параметра *URL-адрес OData* можно скопировать URL-адрес OData V4 любой из веб-служб, перечисленных на странице **Веб-службы** в [!INCLUDE[d365fin](includes/d365fin_md.md)], например `https://mycompany.financials.dynamics.com:7048/MS/ODataV4/`.  

   Для параметра *Название организации* используйте название, которое отображается в поле **Имя** в окне **Информация об организации** в [!INCLUDE[d365fin](includes/d365fin_md.md)]. Если [!INCLUDE[d365fin](includes/d365fin_md.md)] содержит несколько организаций, выберите соответствующее название организации из списка в окне **Организации**. В обоих случаях убедитесь, что название, указываемое в мастере Power BI точно соответствует тексту, отображаемому в [!INCLUDE[d365fin](includes/d365fin_md.md)], например `My Company`.
3. После ввода информации нажмите кнопку ОК. Следующий шаг в мастере — ввод имени пользователя и пароля.

   > [!NOTE]  
>    Если доступны другие параметры проверки подлинности в левой области навигации, выберите *Базовый*.
4. Введите имя пользователя и пароль. Эти сведения можно найти в окне **Пользователи** в [!INCLUDE[d365fin](includes/d365fin_md.md)]. Используйте **Ключ веб-доступа** в качестве пароля.

   Например, ваше имя пользователя — *ADMIN*, а ключ доступа веб-службы, который используется как пароль, — *EgzeUFQ9Uv0o5O0lUMyqCzo1ueUW9yRF3SsLU=*.
5. Нажмите кнопку **Подключение**, чтобы продолжить. Мастер Power BI отобразит список источников данных [!INCLUDE[d365fin](includes/d365fin_md.md)]. Эти источники данных представляют все веб-службы, которые вы опубликовали из [!INCLUDE[d365fin](includes/d365fin_md.md)].

   Либо создайте новый URL-адрес веб-службы в [!INCLUDE[d365fin](includes/d365fin_md.md)], используя действие **Создать набор данных** на странице **Веб-службы** с помощью руководства по сопровождаемой настройке **Настройка отчетов** либо используя действие **Изменить в Excel** в любом списке.

6. Укажите данные, которые требуется добавить в модель данных, а затем нажмите кнопку **Загрузить**.
7. Повторите предыдущие шаги для добавления дополнительных данных [!INCLUDE[d365fin](includes/d365fin_md.md)] в модель данных Power BI.

   > [!NOTE]  
>    После успешного подключения к [!INCLUDE[d365fin](includes/d365fin_md.md)] вводить URL-адрес OData, имя пользователя или пароль повторно не требуется.

После загрузки данные отобразятся в правой области навигации на странице. На этом шаге вы успешно подключились с данным Dynamics NAV и готовы начать создание отчета Power BI. Дополнительные сведения см. в разделе [Документация Power BI](https://powerbi.microsoft.com/documentation/powerbi-landing-page/).

## <a name="see-also"></a>См. также
[Бизнес-аналитика](bi.md)  
[Добро пожаловать в [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Импорт бизнес-данных из других финансовых систем](upload-data.md)  
[Установка [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)  
[Финансы](finance.md)  

