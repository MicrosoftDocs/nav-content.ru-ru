---
title: "Учет межфирменных документов и журналов"
description: "Использование межфирменных документов для учета транзакций с МФ-партнерами."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: IC, group, consolidation, affiliate, subsidiary
ms.date: 06/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 176c12271c55936e61235e3a726932aa02b29b74
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-intercompany-documents-and-journals"></a>Практическое руководство. Работа с межфирменными документами и журналами
Межфирменные документы или журналы можно использовать для учета транзакций, выполненных с партнерами по межфирменным операциям. При учете межфирменного документа или строки журнала в вашей организации в вашем межфирменном выходном ящике создается соответствующий документ или строка журнала, которые можно передать партнеру. Затем партнер может учесть соответствующую транзакцию в своей организации без повторного ввода данных.

Для документов покупки и продажи код межфирменного партнера для соответствующего клиента или поставщика обеспечивает, что все заказы и счета, создаваемые в связи с транзакциями с этими организациями, будут создавать соответствующие документы в партнерской организации, что приведет к правильно балансировке счетов.

Для строк межфирменного финансового журнала нет необходимости указывать счета для отдельных наборов журналов, достаточно дать идентификатор организации-партнера. Соответствующие стоки межфирменного финансового журнала затем создаются в организации-партнере, которые после учета обеспечивают балансировку журналов обеих организаций, участвующих в транзакции.

## <a name="to-fill-in-and-send-an-intercompany-sales-order"></a>Заполнение и отправка межфирменного заказа на продажу
До учета можно отправить заказы на продажу и покупку, а также заказы на возврат. Счета-фактуры и заявки на кредит не могут быть отправлены, пока не будут учтены.

Следующая процедура описывает, как заполнить и отправить межфирменный заказ на продажу. Эти же действия применяются к межфирменным заказам на покупку и возвратам, а также к учтенным межфирменным счетам и кредит-нотам.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказы на продажу**, а затем выберите связанную ссылку.  
2. Чтобы создать новый заказ на продажу, выберите **Создать**. Дополнительные сведения см. в разделе [Практическое руководство. Продажа продукции](sales-how-sell-products.md).  
3. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Убедитесь, что клиент является межфирменным партнером.
5. Для отправки заказа на продажу до его учета выберите действие **Отправить межфирменный заказ на продажу**.

> [!NOTE]
> Если шаг 4 будет выполнен, то заказ на продажу будет перемещен в межфирменный выходной ящик, откуда его можно отправить позже. Дополнительные сведения см. в разделе [Практическое руководство. Управление межфирменными входящими и исходящими ящиками](intercompany-how-manage-intercompany-inbox.md).

## <a name="to-fill-in-and-post-an-intercompany-journal"></a>Заполнение и учет межфирменного журнала
При учете строки межфирменного финансового журнала в вашей организации в вашем межфирменном выходном ящике создается соответствующая строка журнала, которую можно передать партнеру. Затем партнер может учесть соответствующую транзакцию в своей организации без повторного ввода данных.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **МФ - финансовые журналы**, затем выберите связанную ссылку.  
2. Откройте соответствующий раздел журнала. Дополнительные сведения см. в разделе [Работа с финансовыми журналами](ui-work-general-journals.md).
3. Заполните соответствующим образом поля.
4. В поле **МФ Номер счета ГК партнера** введите счет межфирменной ГК, сумма с которого будет учтена в партнерской организации.

    > [!NOTE]
    > Это поле должно быть заполнено вводом банковского счета или счета главной книги в поле **Номер счета** или **Номер бал. счета**.  
5. Выберите действие **Учесть**.

Соответствующие операции учитываются в вашей организации, и журнал с соответствующими операциями создается в межфирменном исходящем ящике, который можно отправить в вашей партнерскую организацию. Дополнительные сведения см. в разделе [Практическое руководство. Управление межфирменными входящими и исходящими ящиками](intercompany-how-manage-intercompany-inbox.md). 

## <a name="see-also"></a>См. также
[Управление межфирменными транзакциями](intercompany-manage.md)  
[Финансы](finance.md)  
[Настройка финансов](finance-setup-finance.md)  
[Работа с финансовыми журналами](ui-work-general-journals.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

