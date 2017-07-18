---
title: "Налог с продаж и налог на товары и услуги в Канаде"
author: edupont04
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c032a02b545441b927ef5c4facc9f77731f37ab7
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-goods-and-services-tax-in-canada"></a>Налог с продаж и налог на товары и услуги в Канаде
В Канаде, если поставщик не имеет представительства в провинции, в которой будет совершаться покупка, поставщик будет начислять GST-налог (Goods and Services Tax) или только HST-налог (Harmonized Sales Tax). Однако если в провинции применяется местный налог с продаж (PST, Provincial Sales Tax), покупатель должен рассчитывать PST-налог и уплачивать его непосредственно в провинции. Если выбран провинциальный код налоговой области, Dynamics NAV использует его для вычисления PST-налога и учета его таким образом, чтобы налоговые обязательства отражались как в главной книге, так и в записях налоговой операции. Поэтому выбранный здесь код налоговой области должен соответствовать коду области, где применяется PST-налог, а не GST-налог.  
Дополнительные сведения о налоге с продаж см в разделе [Налог с продаж и налоговые группы в США и Канаде](us-finance-setup-sales-tax.md).  

## <a name="submitting-the-gsthst-file"></a>Отправка GST/HST-файла
Сведения о налоге в документах покупки используются для формирования GST/HST-файлов для подачи по Интернету в налоговые органы. Этот файл включает GST-налог и HST-налог. Файл создается в формате .tax, который можно передавать через Интернет.  

## <a name="see-also"></a>См. также
[Финансы](finance-setup.md)  
[Настройка финансов](finance-setup-setup-finance-setup.md)  
[Налог с продаж и налоговые группы в США и Канаде](us-finance-setup-sales-tax.md)

