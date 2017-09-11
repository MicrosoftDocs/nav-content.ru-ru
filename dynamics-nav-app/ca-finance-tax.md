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

# <a name="sales-tax-and-goods-and-services-tax-in-canada"></a><span data-ttu-id="ba0fc-102">Налог с продаж и налог на товары и услуги в Канаде</span><span class="sxs-lookup"><span data-stu-id="ba0fc-102">Sales Tax and Goods and Services Tax in Canada</span></span>
<span data-ttu-id="ba0fc-103">В Канаде, если поставщик не имеет представительства в провинции, в которой будет совершаться покупка, поставщик будет начислять GST-налог (Goods and Services Tax) или только HST-налог (Harmonized Sales Tax).</span><span class="sxs-lookup"><span data-stu-id="ba0fc-103">In Canada, when a vendor does not have a business presence in the province in which purchases are made, the vendor will charge the Goods and Services Tax (GST) or Harmonized Sales Tax (HST) only.</span></span> <span data-ttu-id="ba0fc-104">Однако если в провинции применяется местный налог с продаж (PST, Provincial Sales Tax), покупатель должен рассчитывать PST-налог и уплачивать его непосредственно в провинции.</span><span class="sxs-lookup"><span data-stu-id="ba0fc-104">However, if the province has a Provincial Sales Tax (PST), then the purchaser must still calculate the PST and pay it directly to the province.</span></span> <span data-ttu-id="ba0fc-105">Если выбран провинциальный код налоговой области, Dynamics NAV использует его для вычисления PST-налога и учета его таким образом, чтобы налоговые обязательства отражались как в главной книге, так и в записях налоговой операции.</span><span class="sxs-lookup"><span data-stu-id="ba0fc-105">When a Provincial Tax Area Code is selected, Dynamics NAV uses it to calculate the PST and post it so that there is a tax liability in both the general ledger and the tax entry records.</span></span> <span data-ttu-id="ba0fc-106">Поэтому выбранный здесь код налоговой области должен соответствовать коду области, где применяется PST-налог, а не GST-налог.</span><span class="sxs-lookup"><span data-stu-id="ba0fc-106">Therefore, the tax area code selected here should be one where only the PST is included, not the GST.</span></span>  
<span data-ttu-id="ba0fc-107">Дополнительные сведения о налоге с продаж см в разделе [Налог с продаж и налоговые группы в США и Канаде](us-finance-setup-sales-tax.md).</span><span class="sxs-lookup"><span data-stu-id="ba0fc-107">For more information about sales tax, see [Sales Tax and Tax Groups in the US and Canada](us-finance-setup-sales-tax.md).</span></span>  

## <a name="submitting-the-gsthst-file"></a><span data-ttu-id="ba0fc-108">Отправка GST/HST-файла</span><span class="sxs-lookup"><span data-stu-id="ba0fc-108">Submitting the GST/HST File</span></span>
<span data-ttu-id="ba0fc-109">Сведения о налоге в документах покупки используются для формирования GST/HST-файлов для подачи по Интернету в налоговые органы.</span><span class="sxs-lookup"><span data-stu-id="ba0fc-109">The tax information in purchase documents is used to generate a GST/HST internet file transfer that you must  provided to the tax authorities.</span></span> <span data-ttu-id="ba0fc-110">Этот файл включает GST-налог и HST-налог.</span><span class="sxs-lookup"><span data-stu-id="ba0fc-110">This file includes goods and services tax (GST) and harmonized sales tax (HST).</span></span> <span data-ttu-id="ba0fc-111">Файл создается в формате .tax, который можно передавать через Интернет.</span><span class="sxs-lookup"><span data-stu-id="ba0fc-111">The file is created in a .tax file format, which can be transferred via the internet.</span></span>  

## <a name="see-also"></a><span data-ttu-id="ba0fc-112">См. также</span><span class="sxs-lookup"><span data-stu-id="ba0fc-112">See Also</span></span>
[<span data-ttu-id="ba0fc-113">Финансы</span><span class="sxs-lookup"><span data-stu-id="ba0fc-113">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="ba0fc-114">Настройка финансов</span><span class="sxs-lookup"><span data-stu-id="ba0fc-114">Set Up Finance</span></span>](finance-setup-setup-finance-setup.md)  
[<span data-ttu-id="ba0fc-115">Налог с продаж и налоговые группы в США и Канаде</span><span class="sxs-lookup"><span data-stu-id="ba0fc-115">Sales Tax and Tax Groups in the US and Canada</span></span>](us-finance-setup-sales-tax.md)

