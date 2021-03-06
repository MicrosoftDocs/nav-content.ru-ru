---
title: "Как объединять поставки в один счет"
description: "Если требуется выставить счет сразу по нескольким отгрузкам, можно использовать функцию объединения поставок."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 804667ba690506f78af38cf1a89f3490d1721062
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-combine-shipments-on-a-single-invoice"></a>Практическое руководство. Объединение поставок в один счет
Если требуется выставить счет сразу по нескольким отгрузкам, можно использовать функцию объединения поставок.  

 Чтобы создать объединенную расходную накладную, необходимо сначала учесть несколько расходных накладных для одного и того же клиента в одной и той же валюте. Иными словами, следует заполнить два или более заказа на продажу и учесть их как отгруженные, но без выставления счета. Чтобы объединить расходные накладные возврата, необходимо флажок в поле **Объединение поставок** на экспресс-вкладке **Отгрузка** карточки **Клиент**.  

## <a name="to-manually-combine-shipments-on-a-single-invoice"></a>Объединение поставок в один счет вручную  
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Счета продажи**, а затем выберите связанную ссылку.  
2. Выберите действие **Создать**. Дополнительные сведения см. в разделе [Практическое руководство. Выставление счетов продажи](sales-how-invoice-sales.md).
3. В поле **Код клиента (покупателя)** укажите клиента, который получит счет за отгруженные товары.  
4. На экспресс-вкладке **Строки** выберите действие **Получение строк отгрузки**.  
5. Выберите строку расходной накладной, которую необходимо включить в этот счет.  

    - Чтобы вставить все строки, выделите все строки и нажмите кнопку **OK**.  
    - Чтобы вставить определенные строки, выделите эти строки и нажмите кнопку **OK**. Для выбора нескольких непоследовательных строк можно использовать клавишу Ctrl.  

    Если строка расходной накладной была выделена ошибочно или необходимо начать сначала, то можно просто удалить строки счета и запустить функцию **Получить строки расх. накл.** повторно.  
7. Чтобы учесть счет, выберите действие **Учесть**.  

## <a name="to-automatically-combine-shipments-on-a-single-invoice"></a>Автоматическое объединение поставок в один счет  
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Объединение поставок**, затем выберите связанную ссылку. Откроется окно запроса пакетного задания.  
2. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Установите флажок **Учет счетов**.  
4.  Нажмите кнопку **ОК**.  

> [!NOTE]  
>  В том случае, когда флажок **Учет счетов** в пакетном задании не установлен, потребуется выполнить учет счетов вручную.  

## <a name="to-remove-open-sales-orders-after-combined-shipment-posting"></a>Удаление открытых заказов на продажу после совмещенного учета расходных накладных 
Когда расходные накладные объединяются в счете и учитываются, для строк, включенных в счет, создается учтенный счет продажи. Поле **Кол-во по выст. счетам** в исходном общем заказе на продажу или заказе на продажу обновляется на основе количества в выставленных счетах.  

При таком способе выставления счетов по отгрузкам заказы, из которых были учтены эти отгрузки, продолжают существовать, даже если они были полностью отгружены и включены в счета.   

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Удаление заказов на продажу, по которым выставлены счета**, затем выберите ссылку.  
2. Укажите в поле фильтра **Номер**, какие заказы на продажу следует удалить.  
3. Нажмите кнопку **ОК**.  

В качестве альтернативы удалите отдельные заказы на продажу вручную.  

Повторите шаги с 1 по 3 для всех остальных затронутых документов, таких как общие заказы на продажу.

## <a name="see-also"></a>См. также  
[Продажи](sales-manage-sales.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

