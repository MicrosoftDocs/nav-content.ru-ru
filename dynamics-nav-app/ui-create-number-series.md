---
title: "Создание серий номеров"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e42e5ed139b2487fea13ef0fd57757035764addd
ms.contentlocale: ru-ru
ms.lasthandoff: 07/19/2017

---

# <a name="create-number-series"></a><span data-ttu-id="5f87d-102">Создание серий номеров</span><span class="sxs-lookup"><span data-stu-id="5f87d-102">Create Number Series</span></span>

<span data-ttu-id="5f87d-103">В каждой настраиваемой организации таким объектам, как счета главной книги, клиентов и поставщиков, счета и документы, следует присвоить уникальные идентификационные коды.</span><span class="sxs-lookup"><span data-stu-id="5f87d-103">For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents.</span></span> <span data-ttu-id="5f87d-104">Нумерация необходима не только для идентификации.</span><span class="sxs-lookup"><span data-stu-id="5f87d-104">Numbering is important not only for identification.</span></span> <span data-ttu-id="5f87d-105">Хорошо продуманная система нумерации позволяет повысить управляемость организации, упростить анализ и сократить количество ошибок, возникающих при вводе данных.</span><span class="sxs-lookup"><span data-stu-id="5f87d-105">A well-designed numbering system also makes the company more manageable and easy to analyze, and can reduce the number of errors that occur in data entry.</span></span>

<span data-ttu-id="5f87d-106">Можно настроить полноценную систему нумерации с неограниченным количеством серий номеров.</span><span class="sxs-lookup"><span data-stu-id="5f87d-106">You can set up a complete numbering system with an unlimited number of number series.</span></span> <span data-ttu-id="5f87d-107">Серии номеров можно использовать для всех типов документов и журналов, а также для таких основных данных, как клиенты, товары и работы.</span><span class="sxs-lookup"><span data-stu-id="5f87d-107">You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.</span></span>

<span data-ttu-id="5f87d-108">Серии номеров можно использовать в сочетании с нумерацией вручную.</span><span class="sxs-lookup"><span data-stu-id="5f87d-108">You can combine the use of number series with manual numbering.</span></span>

<span data-ttu-id="5f87d-109">Чтобы создать систему нумерации, необходимо задать один или несколько кодов для каждого типа основных данных или документов.</span><span class="sxs-lookup"><span data-stu-id="5f87d-109">You create a numbering system by setting up one or more codes for each type of master data or document.</span></span> <span data-ttu-id="5f87d-110">Например, можно настроить один код для нумерации клиентов, второй — для нумерации счетов продажи, а третий — для нумерации документов в финансовых журналах.</span><span class="sxs-lookup"><span data-stu-id="5f87d-110">For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.</span></span>

<span data-ttu-id="5f87d-111">После настройки кода следует задать по меньшей мере одну строку серии номеров.</span><span class="sxs-lookup"><span data-stu-id="5f87d-111">After you have set up a code, you set must set up at least one number series line.</span></span> <span data-ttu-id="5f87d-112">В строке серии номеров содержатся такие сведения, как первый и последний номер в серии и дата начала.</span><span class="sxs-lookup"><span data-stu-id="5f87d-112">The number series line contains information such as the first and last number in the series and the starting date.</span></span> <span data-ttu-id="5f87d-113">Для каждого кода серии номеров можно задать несколько таких строк с различными датами начала.</span><span class="sxs-lookup"><span data-stu-id="5f87d-113">You can set up more than one number series line per number series code, with a different starting date for each line.</span></span> <span data-ttu-id="5f87d-114">Серии будут использоваться последовательно, каждая со своей даты начала.</span><span class="sxs-lookup"><span data-stu-id="5f87d-114">The series will be used consecutively, starting each series on the respective starting date.</span></span>

<span data-ttu-id="5f87d-115">При необходимости в использовании нескольких кодов серии номеров для одного типа основных данных, например, если требуется использовать разные серии номеров для разных категорий товаров, можно воспользоваться связями серий номеров.</span><span class="sxs-lookup"><span data-stu-id="5f87d-115">If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.</span></span>

<span data-ttu-id="5f87d-116">Помимо номеров, назначенных вручную или с помощью системы нумерации, всем транзакциям (книгам операций) автоматически назначаются порядковые номера.</span><span class="sxs-lookup"><span data-stu-id="5f87d-116">In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers.</span></span> <span data-ttu-id="5f87d-117">Эти номера можно видеть в поле **Номер операции**</span><span class="sxs-lookup"><span data-stu-id="5f87d-117">These numbers can be seen in the **Entry No.**</span></span> <span data-ttu-id="5f87d-118">в любом из окон операций книги.</span><span class="sxs-lookup"><span data-stu-id="5f87d-118">field in all the ledger entry windows.</span></span> <span data-ttu-id="5f87d-119">Их удаление и изменение невозможно.</span><span class="sxs-lookup"><span data-stu-id="5f87d-119">You cannot modify or delete these numbers.</span></span>

## <a name="to-create-relationships-between-number-series"></a><span data-ttu-id="5f87d-120">Создание связей между сериями номеров</span><span class="sxs-lookup"><span data-stu-id="5f87d-120">To create relationships between number series</span></span>
<span data-ttu-id="5f87d-121">Если для одного и того же типа базовой информации или транзакций настроено несколько кодов серий номеров, между кодами можно создать связи.</span><span class="sxs-lookup"><span data-stu-id="5f87d-121">If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes.</span></span> <span data-ttu-id="5f87d-122">Это поможет выбрать нужный код при использовании номера.</span><span class="sxs-lookup"><span data-stu-id="5f87d-122">This feature can assist you in deciding among the codes when you use a number.</span></span>

1. <span data-ttu-id="5f87d-123">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Серия номеров**, а затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="5f87d-123">In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.</span></span>
2. <span data-ttu-id="5f87d-124">Выберите строку с серией номеров, для которой необходимо создать связи и выберите **Связи**.</span><span class="sxs-lookup"><span data-stu-id="5f87d-124">Select the line with the number series you want to create relationships for and then choose **Relationships**.</span></span>
3. <span data-ttu-id="5f87d-125">В поле **Код серии** введите код серии номеров, которую требуется связать с серией, выбранной на шаге 2.</span><span class="sxs-lookup"><span data-stu-id="5f87d-125">In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.</span></span>
4. <span data-ttu-id="5f87d-126">Добавьте строку для каждого кода, который необходимо связать с выбранной серией номеров.</span><span class="sxs-lookup"><span data-stu-id="5f87d-126">Add a line for each code that you want to relate to the selected number series.</span></span>
5. <span data-ttu-id="5f87d-127">Закройте окно.</span><span class="sxs-lookup"><span data-stu-id="5f87d-127">Close the window.</span></span>

<span data-ttu-id="5f87d-128">Теперь, после настройки атрибутов, требующих нумерации, можно использовать созданные связи для выбора связанных серий номеров.</span><span class="sxs-lookup"><span data-stu-id="5f87d-128">Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.</span></span>

## <a name="see-also"></a><span data-ttu-id="5f87d-129">См. также</span><span class="sxs-lookup"><span data-stu-id="5f87d-129">See Also</span></span>
[<span data-ttu-id="5f87d-130">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5f87d-130">Work with Dynamics NAV</span></span>](ui-work-product.md)

