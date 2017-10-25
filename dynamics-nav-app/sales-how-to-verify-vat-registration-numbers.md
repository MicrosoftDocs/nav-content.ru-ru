---
title: "Как проверять регистрационные номера НДС"
description: "Можно использовать веб-службу ЕС для проверки того, что регистрационные номера НДС, вводимые в карточках клиента, поставщика или контакта, допустимы."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8ed345e346ba32a38ebb2738afbe6c12749842ff
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-verify-vat-registration-numbers"></a><span data-ttu-id="dd8a5-103">Практическое руководство. Проверка регистрационных номеров НДС</span><span class="sxs-lookup"><span data-stu-id="dd8a5-103">How to: Verify VAT Registration Numbers</span></span>
<span data-ttu-id="dd8a5-104">Можно использовать веб-службу ЕС для проверки того, что регистрационные номера НДС, вводимые в карточках клиента, поставщика или контакта, допустимы.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-104">You can use an EU web service to verify that VAT registration numbers that you enter on customer, vendor, or contact cards are valid.</span></span>  

 <span data-ttu-id="dd8a5-105">При изменении поля **ИНН** в карточке, в которой значением поля **Код страны или региона** является страна или регион ЕС, новый ИНН и ваш идентификатор пользователя регистрируются в окне **Журнал ИНН**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-105">When you modify the **VAT Registration No.** field on a card where the value in the **Country/Region Code** field is an EU country/region, then the new VAT registration number and your user ID are logged in the **VAT Registration Log** window.</span></span> <span data-ttu-id="dd8a5-106">Чтобы проверить регистрационный номер НДС, нажмите кнопку **Проверить регистрационный номер** в окне **Журнал ИНН**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-106">You verify a VAT registration number by choosing the **Verify Registration No.** button in the **VAT Registration Log** window.</span></span> <span data-ttu-id="dd8a5-107">Новая строка создается каждый раз, когда используется функция проверки.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-107">A new line is created every time you use the verification function.</span></span> <span data-ttu-id="dd8a5-108">Если номер может быть проверен, в поле **Состояние** содержится значение **Допустимо**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-108">If the number could be verified, the **Status** field contains **Valid**.</span></span> <span data-ttu-id="dd8a5-109">Если номер невозможно проверить, в поле **Статус** содержится значение **Не корректно**, и следует изменить номер в поле **ИНН** в карточке и повторно запустить функцию проверки.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-109">If the number could not be verified, the **Status** field contains **Invalid**, and you must then change the number in the **VAT Registration No.** field on the card and start the verification function again.</span></span>  

 <span data-ttu-id="dd8a5-110">URL\-адрес веб-службы по умолчанию устанавливается в поле **URL\-адрес проверки ИНН** в окне **Настройка ГК**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-110">The URL of the default web service is set up in the **VAT Reg. No. Validation URL** field in the **General Ledger Setup** window.</span></span>  

 <span data-ttu-id="dd8a5-111">В таблице **Формат ИНН** для каждой страны или региона можно изменить различные форматы ИНН, которые могут вводить пользователи в поле **ИНН**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-111">In the **VAT Registration No. Format** table, you can change for each country/region the different formats of VAT registration number that users are allowed to enter in the **VAT Registration No.** field.</span></span>  

> [!WARNING]  
>  <span data-ttu-id="dd8a5-112">Эта веб-служба использует протокол HTTP, что означает, что данные, передаваемые в этой службе, не шифруются.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-112">This web service uses the http protocol, which means that data transferred through the service is not encrypted.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="dd8a5-113">Могут возникнуть простои службы, за которые Майкрософт не несет ответственность, поскольку служба является частью широкой сети ЕС национальных регистров НДС.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-113">You may experience downtime for this service for which Microsoft is not responsible, as the service is part of a broad EU network of national VAT registers.</span></span>  

## <a name="to-verify-a-vat-registration-number-from-a-customer-card"></a><span data-ttu-id="dd8a5-114">Проверка регистрационного номера НДС в карточке клиента</span><span class="sxs-lookup"><span data-stu-id="dd8a5-114">To verify a VAT registration number from a customer card</span></span>  
<span data-ttu-id="dd8a5-115">Ниже описывается, как проверить ИНН клиента.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-115">The following describes how to verify a VAT registration number for a customer.</span></span> <span data-ttu-id="dd8a5-116">Действия для поставщика и контакта аналогичны.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-116">The steps are similar for a vendor and a contact.</span></span>   
1.  <span data-ttu-id="dd8a5-117">Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Клиенты**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span></span>  

2.  <span data-ttu-id="dd8a5-118">Откройте карточку клиента, в которой необходимо проверить регистрационный номер плательщика НДС.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-118">Open the card of a customer where you want to verify the VAT registration number.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="dd8a5-119">Поле **Код страны или региона** в карточке клиента должно содержать страну или регион ЕС.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-119">The **Country/Region Code** field on the customer card must contain an EU country/region.</span></span>  
3.  <span data-ttu-id="dd8a5-120">На экспресс-вкладке **Выставление счетов** нажмите кнопку раскрытия рядом с полем **ИНН**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-120">On the **Invoicing** FastTab, choose the DrillDown button next to the **VAT Registration No.** field.</span></span>  

    <span data-ttu-id="dd8a5-121">Откроется окно **Журнал ИНН** с одной строкой, в которой поле **Состояние** имеет значение **Не проверено**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-121">The **VAT Registration Log** window opens showing one line where the **Status** field contains **Not Verified**.</span></span>  
4.  <span data-ttu-id="dd8a5-122">Выберите действие **Проверить регистрационный номер**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-122">Choose the **Verify Registration No.** action.</span></span>  

     <span data-ttu-id="dd8a5-123">Новая строка создается, если в поле **Состояние** содержится значение **Допустимо** или **Не корректно**.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-123">A new line is created where the **Status** field contains either **Valid** or **Invalid**.</span></span>  
5.  <span data-ttu-id="dd8a5-124">Если поле **Статус** содержит значение **Не корректно**, измените номер в поле **ИНН** в карточке, а затем повторите шаги с 3 по 4.</span><span class="sxs-lookup"><span data-stu-id="dd8a5-124">If the **Status** field contains **Invalid**, change the number in the **VAT Registration No.** field on the card, and then repeat steps 3 through 4.</span></span>  

## <a name="see-also"></a><span data-ttu-id="dd8a5-125">См. также</span><span class="sxs-lookup"><span data-stu-id="dd8a5-125">See Also</span></span>  
[<span data-ttu-id="dd8a5-126">Финансы</span><span class="sxs-lookup"><span data-stu-id="dd8a5-126">Finance</span></span>](finance.md)  
[<span data-ttu-id="dd8a5-127">Практическое руководство. Регистрация новых клиентов</span><span class="sxs-lookup"><span data-stu-id="dd8a5-127">How to: Register New Customers</span></span>](sales-how-register-new-customers.md)  
[<span data-ttu-id="dd8a5-128">Практическое руководство. Регистрация новых поставщиков</span><span class="sxs-lookup"><span data-stu-id="dd8a5-128">How to: Register New Vendors</span></span>](purchasing-how-register-new-vendors.md)  
<span data-ttu-id="dd8a5-129">[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="dd8a5-129">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

