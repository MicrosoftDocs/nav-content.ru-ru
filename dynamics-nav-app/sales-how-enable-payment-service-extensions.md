---
title: "Включение платежей клиентов через службу платежей"
description: "Облегчите клиентам оплату счетов, включив службы платежей."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: online payment
ms.date: 07/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 71ff4af2fa3c0d1020a24de4325aafe17978f715
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-customer-payments-through-payment-services"></a>Практическое руководство. Включение платежей клиентов через службу платежей
В качестве альтернативы сбору платежей через банковские переводы или кредитные карты вы можете предложить клиентам оплату через учетную запись в службе платежей, например Microsoft Pay, PayPal или WorldPay.  

После включения службы платежей в [!INCLUDE[d365fin](includes/d365fin_md.md)] станет доступна ссылка на службу в документах продажи, отправляемых по электронной почте клиентам. Клиенты могут использовать эту ссылку для перехода к службе платежей и оплаты счетов непосредственно из документа продажи. Если не требуется включать ссылку, например если клиент платит наличными деньгами, можно удалить службу платежей из счета до учета.  

Расширения Microsoft Pay, PayPal Payments Standard и WorldPay Payments Standard установлены в [!INCLUDE[d365fin](includes/d365fin_md.md)] и готовы к включению.  

## <a name="to-enable-a-payment-service-in-included365finincludesd365finmdmd"></a>Включение службы платежей в [!INCLUDE[d365fin](includes/d365fin_md.md)]
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Службы платежей**, а затем выберите связанную ссылку.  
2. В окне **Службы платежей** выберите действие **Создать**.  
3. Выберите службу платежей, а затем закройте окно.  
4. В окне **Службы платежей** выберите действие **Настройка**.  
5. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
6. Закройте данное окно.  

## <a name="to-select-a-payment-service-on-a-sales-invoice"></a>Выбор службы платежей в счете продажи
1. На начальной странице выберите **Счета продажи**.  
2. Откройте счет продажи, который необходимо оплатить с помощью службы платежей.  
3. В поле **Служба платежей** выберите службу платежей.  

    > [!NOTE]  
>   Поле **Служба платежей** доступно, только если включена служба платежей.  

## <a name="see-also"></a>См. также  
[Настройка продаж](sales-setup-sales.md)  
[Продажи](sales-manage-sales.md)  
[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

