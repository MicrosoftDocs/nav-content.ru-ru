---
title: "Использование расширения \"Анализатор изображений\""
description: "Это расширение позволяет анализировать изображения контактных лиц и товаров, для обнаружения атрибутов, которые можно быстро присвоить им в Dynamics NAV."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: API, extension, Cognitive Services, image, computer vision, attribute, tag, recognition
ms.date: 06/19/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 08a832708dcbb550e880d2a669af265b2fb670b5
ms.contentlocale: ru-ru
ms.lasthandoff: 10/23/2017

---

# <a name="the-image-analyzer-extension-for-includenavnowincludesnavnowmdmd"></a>Расширение "Анализатор изображений" для [!INCLUDE[navnow](includes/navnow_md.md)]
Расширение "Анализатор изображений" использует мощные механизмы анализа изображений, предоставленные API компьютерного зрения для Microsoft Cognitive Services, чтобы обнаруживать атрибуты на изображениях, которые вы импортируете для товаров и контактных лиц, чтобы вы могли их легко проверять и назначать. Для товаров это могут быть такие атрибуты как "стол" или "автомобиль", либо "красный" или "синий". Для контактных лиц атрибутом может быть пол или возраст.

"Анализатор изображений" предлагает атрибуты на основании тегов, которые находит API компьютерного зрения, и уровня достоверности. По умолчанию он предлагает атрибуты только в случае уверенности не ниже 80%. При необходимости вы можете установить другой уровень достоверности. Чтобы получить дополнительные сведения о том, как определяются уровни доверия и теги, см. раздел [API компьютерного зрения](https://go.microsoft.com/fwlink/?linkid=851476).  

В [!INCLUDE[d365fin](includes/d365fin_md.md)] "Анализатор изображений" доступен бесплатно, но с ограничением по количеству элементов, которое можно проанализировать в течение определенного периода времени. По умолчанию можно анализировать 100 изображений месяц.

После включения расширения "Анализатор изображений" запускается при каждом импорте изображения товара или контактного лица. Вы будете видеть атрибуты, уровень достоверности и сведения сразу, и сможете решить, что делать с каждым атрибутом. Если вы импортировали изображения до включения расширения "Анализатор изображений", вы должны открыть карточки товаров или контактов и выбрать действие **Анализировать изображение**.  

>   [!NOTE]  
>   Включая это расширение, вы соглашаетесь, что корпорация Майкрософт может сохранять ваши данные и использовать для улучшения службы Майкрософт, например API компьютерного зрения. Чтобы защитить вашей конфиденциальную информацию, мы принимаем меры по тому, чтобы хранить данные в анонимном виде и делать это безопасным образом. Мы не публикуем ваши данные и не позволяем другим людям их использовать. Вы можете удалить изображение товара в [!INCLUDE[d365fin](includes/d365fin_md.md)], однако оно все равно сохранится в API компьютерного зрения в неидентифицированном виде. Дополнительные сведения в разделе [Центр доверия Майкрософт](https://go.microsoft.com/fwlink/?linkid=851463).

## <a name="requirements"></a>Требования
К изображению предъявляются несколько требований:

* Форматы изображений: JPEG, PNG, GIF, BMP  
* Максимальный размер файла: 4 МБ  
* Минимальный размер: 50 x 50 пикселей  

## <a name="blacklisting-suggested-attributes"></a>Внесение предложенных атрибутов в черный список
Если в ходе анализа будет предложен атрибут, который вы не хотите видеть, его можно внести в черный список. При этом следует соблюдать осторожность. Атрибуты из черного списка не будут предлагаться для других товаров или контактных лиц. Если вы передумали включать атрибут в черный список, вы можете выбрать **Атрибуты в черном списке**, а затем удалить любой атрибут из списка.

## <a name="to-enable-image-analyzer"></a>Включение "Анализатора изображений"
Расширение "Анализатор изображений" встроено в [!INCLUDE[d365fin](includes/d365fin_md.md)]. Достаточно его включить.

> [!NOTE]  
> Чтобы включить расширение "Анализатор изображений", нужно быть администратором. Убедитесь, что вам назначен набор разрешений **SUPER**.

1. Чтобы включить расширение "Анализатор изображений", выполните одно из следующих действий:

* Откройте карточку контакта или товара. На панели уведомлений выберите **Анализировать изображения**, а затем выполните действия руководства по сопровождаемой настройке.  
* Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Подключения к службе**, а затем выберите **Настройка анализа изображений**. Установите флажок **Включить анализатор изображений**, а затем завершите шаги руководства по сопровождаемой настройке.  

>   [!TIP]  
>   На странице **Настройка анализа изображений** вы также можете изменить степень достоверности для предложений атрибутов. Например, если вам требуется более высокий уровень достоверности, вы можете ввести более высокий процент.

## <a name="to-analyze-an-image-of-an-item"></a>Анализ изображения товара
Следующие шаги описывают порядок анализа изображения, которое было импортировано до включения расширения "Анализатор изображений".  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Товары**, а затем выберите связанную ссылку.  
2. Выберите товар, а затем выберите действие **Анализировать изображение**.  
3. На странице **Атрибуты анализатора изображений** будут показаны обнаруженные атрибуты, уровень достоверности, а также другие подробности о атрибуте. С помощью параметров **Действия для выполнения** укажите, что нужно сделать с атрибутом.  

>   [!TIP]  
>   Вы можете добавить название атрибута в описание товара, выбрав **Добавить в описание товара**. Например, это может пригодиться для быстрого добавления сведений.  

## <a name="to-analyze-a-picture-of-a-contact-person"></a>Анализ изображения контактного лица
Следующие шаги описывают порядок анализа изображения, которое было импортировано до включения расширения "Анализатор изображений".  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Контакты**, а затем выберите связанную ссылку.  
2. Выберите контактное лицо, а затем выберите действие **Анализировать изображение**.  
3. На экспресс-вкладке **Анкета профиля** просмотрите предложения и при необходимости исправления.  

## <a name="to-use-your-own-account-for-the-computer-vision-api"></a>Использование учетной записи для API компьютерного зрения
Вы также можете использовать свою учетную запись для API компьютерного зрения, если вы хотите проанализировать большее число изображений, чем допускается.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка анализатора изображений**, а затем выберите связанную ссылку.  
2. Введите **URI-адрес API** и **Ключ API**, которые вы получили для API компьютерного зрения.  

>   [!NOTE]  
>   Вы должны добавить **/analyze** в конец URI-адреса API, если его там еще нет. Пример: ```https://cronus.api.cognitive.microsoft.com/vision/v1.0/analyze```.

## <a name="to-see-how-many-analyses-you-have-left-in-the-current-period"></a>Просмотр оставшегося количества анализов в текущем периоде
Вы можете видеть количество сделанных анализов и оставшихся анализов для текущего периода.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка анализатора изображений**, а затем выберите связанную ссылку.  
2. Информация об использовании содержится в полях **Тип лимита**, **Значение лимита** и **Анализ выполнен**.  

## <a name="to-stop-using-the-image-analyzer-extension"></a>Прекращение использования расширения "Анализатор изображений"
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Подключения к службе**, а затем выберите **Настройка анализатора изображений**.  
2. Снимите флажок **Включать анализатор изображений**.  

## <a name="see-also"></a>См. также
[Практическое руководство. Работа с атрибутами товаров](inventory-how-work-item-attributes.md)  
[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)  
[Добро пожаловать в [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)  

