---
title: "Практическое руководство. Создание предсказывающих прогнозов движения денежных средств"
author: bholtorf
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f657509fc2195674db81f47bc5ae31b7ba1aa40e
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-predictive-cash-flow-forecasts"></a>Практическое руководство. Создание предсказывающих прогнозов движения денежных средств
Прогнозы движения денежных средств помогают обеспечить наличие у вашей организации денежных средств в объеме, достаточном для выполнения финансовых обязательств, а также полезны для идентификации коррекций. Например, при наличии кассовых излишков можно погасить определенные долги; также полезно будет ранее предупреждение, если график выглядит очень плотным. 

Cortana Intelligence использует службу машинного обучения Azure Machine Learning для подготовки надежных предсказательных прогнозов. Например, прогнозы от Cortana Intelligence могут помочь предсказать и избежать дефицита денежных средств. Служба объединяет историческую информацию с текущими учетными операциями по дебиторской и кредиторской задолженности, включая учетные операциями с датами завершения в будущем. К ним относятся:
* Заказы на покупку
* Заказы на продажу
* Учтенные счета на покупку и продажу
* Кредит-ноты

## <a name="before-you-start"></a>Перед началом работы  
Прежде чем можно будет использовать Cortana Intelligence для прогнозирования движения денежных средств, необходимо кое-что сделать: 
* Если вы еще не используете прогнозы движения денежных средств, то необходимо настроить:
    * Одна или несколько настроек в **Настройка движения денежных средств**. 
    * Счета для кредиторской задолженности, дебиторской задолженности, заказов на продажу и заказов на покупку. Cortana Intelligence использует операции учета по этим счетам.
    * Один или несколько прогнозов движения денежных средств в **Прогноз движения денежных средств**. Обязательно включите заказы покупки, заказы на продажу, кредиторскую задолженность и дебиторскую задолженность как источники.  
    Для получения дополнительных сведений выполните поиск по _прогнозы движения денежных средств_ в справочной системе. 
* Узнайте URL-адрес API и ключ API для использования веб-службой прогнозирования.  
    Можно использовать службу машинного обучения Azure Machine Learning или другую службу, если таковая имеется. Кроме того, в Интернете в галерее Cortana Intelligence Gallery доступна общедоступная модель под названием _Forecasting model for Microsoft Dynamics NAV_ (Прогнозная модель для Microsoft Dynamics NAV). Чтобы использовать эту модель, выполните следующие шаги:

    1. В браузере перейдите в галерею [Cortana Intelligence Gallery](https://go.microsoft.com/fwlink/?linkid=828352)
    2. Выполните поиск по _Forecasting Model for Microsoft Dynamics NAV_, затем откройте эту модель в Azure Machine Learning Studio.
    3. Используйте свою учетную запись Microsoft, чтобы подписаться на рабочее пространство, затем скопируйте модель.
    4. Запустите модель и опубликуйте ее как веб-службу.
    5. Запишите URL-адрес API и ключ API. Эти учетные данные будут использоваться при настройке Cortana Intelligence в Microsoft Dynamics NAV.  

* Решите, насколько часто требуется рассчитывать прогноз. Служба Azure Machine Learning имеет ограничения в отношении использования. Например, при наличии большого числа товаров может быть лучше выполнять расчет не так часто. 
* Будьте назначены ролевому центру бухгалтера. 

## <a name="set-up-cortana-intelligence"></a>Настройка Cortana Intelligence
Можно использовать руководство по сопровождаемой настройке для создания прогнозов движения денежных средств. Это руководство помогает указать такие параметры как частота обновления прогноза, счета, на которых основан прогноз, сведения о дате уплаты налогов, а также следует ли использовать Cortana Intelligence.  

Если вы уже используете прогнозы движения денежных средств и просто хотите включить Cortana Intelligence, можно также использовать ручную процедуру. При входе в синем поле в верхней части рабочей области отображается уведомление. Чтобы сразу же настроить Cortana Intelligence, выберите **Да, пожалуйста**. Это сообщение отображается только один раз. Если вы закрыли его, используйте ручной процесс для настройки Cortana Intelligence.  

**Совет.** Учитывайте длительность периодов, которые служба будет учитывать в расчетах. Чем больше предоставлено данных, тем точнее будут прогнозы. Кроме того, избегайте больших отклонений в длительности периодов. Они также будут влиять на прогнозы. Если Cortana Intelligence не находит достаточно данных или данные сильно изменяются, эта служба не создает прогноз. 

Использование руководства по сопровождаемой настройке:
1. В ролевом центре «Бухгалтер» на диаграмме **Прогноз движения денежных средств** выберите действие **Открыть сопровождаемую настройку**.
2. Требуемым образом заполните поля в каждом шаге руководства.

Использование ручного процесса:
1. Выполните поиск по **Настройка движения денежных средств**, затем выберите связанную ссылку.
2. Разверните экспресс-вкладку **Cortana Intelligence**, затем требуемым образом заполните поля.

## <a name="turn-on-cortana-intelligence-for-cash-flow-forecasts"></a>Включение Cortana Intelligence для прогнозов потоков денежных средств
1. Выполните поиск по **Прогнозы движения денежных средств**, затем выберите связанную ссылку.
2. Выберите действие **Журнал движения денежных средств**.
3. На странице **Журнал движения денежных средств** выберите действие **Предложить строки журнала**.  
4. В разделе **Включаемые типы источников** установите флажок **Прогноз Cortana Intelligence**.

## <a name="investigate-a-cash-flow-forecast"></a>Изучение прогноза движения денежных средств
Чтобы получить ясное представление о данных, лежащих в основе прогноза, включая их дисперсию, выберите столбец **Cortana Intelligence**. Первая строка в таблице показывает дисперсию. Другие строки организованы по документам-источникам.  

Например, можно посмотреть, как в прогнозе:    
* Обрабатываются подтвержденные продажи и покупки 
* Вычитается кредиторская задолженность и добавляется дебиторская задолженность
* Пропускаются дублирующие заказы на продажу и заказы на покупку

## <a name="see-also"></a>См. также  
[Работа с Dynamics NAV](ui-work-product.md)
