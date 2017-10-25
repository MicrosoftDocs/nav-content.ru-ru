---
title: "Использование расширения миграции данных C5"
description: "Используйте это расширение для переноса клиентов, поставщиков, товаров и счетов главной книги из Microsoft Dynamics C5 2012 в Dynamics NAV."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: extension, migrate, data, C5, import
ms.date: 09/26/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2307849566a44bb49a5db6965ec3056b1a39684b
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---

# <a name="the-c5-data-migration-extension-for-dynamics-nav"></a><span data-ttu-id="08286-103">Расширение миграции данных C5 для Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="08286-103">The C5 Data Migration Extension for Dynamics NAV</span></span>
<span data-ttu-id="08286-104">Это расширение упрощает перенос клиентов, поставщиков, товаров и ваших счетов главной книги из Microsoft Dynamics C5 2012 в [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="08286-104">This extension makes it easy to migrate customers, vendors, items, and your general ledger accounts from Microsoft Dynamcis C5 2012 to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> 

> [!Note] 
> <span data-ttu-id="08286-105">Организация в [!INCLUDE[d365fin](includes/d365fin_md.md)] не должна содержать никаких данных.</span><span class="sxs-lookup"><span data-stu-id="08286-105">The company in [!INCLUDE[d365fin](includes/d365fin_md.md)] must not contain any data.</span></span> <span data-ttu-id="08286-106">Кроме того, после запуска миграции не создавайте клиентов, поставщиков, товаров или счетов, пока миграция не закончит работу.</span><span class="sxs-lookup"><span data-stu-id="08286-106">Additionally, after you start a migration, do not create customers, vendors, items, or accounts until the migration finishes.</span></span>

## <a name="to-migrate-data"></a><span data-ttu-id="08286-107">Для миграции данных</span><span class="sxs-lookup"><span data-stu-id="08286-107">To migrate data</span></span>
<span data-ttu-id="08286-108">Для экспорта данных из C5 и импорта их в [!INCLUDE[d365fin](includes/d365fin_md.md)] нужно выполнить всего несколько шагов:</span><span class="sxs-lookup"><span data-stu-id="08286-108">There are just a few steps to export data from C5, and import it in [!INCLUDE[d365fin](includes/d365fin_md.md)]:</span></span> 

1. <span data-ttu-id="08286-109">В C5, используйте функцию **Экспорт базы данных**, чтобы экспортировать данные.</span><span class="sxs-lookup"><span data-stu-id="08286-109">In C5, use the **Export Database** feature to export the data.</span></span> <span data-ttu-id="08286-110">Затем отправьте папку экспорта в сжатую (ZIP) папку.</span><span class="sxs-lookup"><span data-stu-id="08286-110">Then send the export folder to a compressed (zipped) folder.</span></span>  
2. <span data-ttu-id="08286-111">В [!INCLUDE[d365fin](includes/d365fin_md.md)] выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Миграция данных**, затем выберите **Миграция данных**.</span><span class="sxs-lookup"><span data-stu-id="08286-111">In [!INCLUDE[d365fin](includes/d365fin_md.md)], choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Data Migration**, and then choose **Data Migration**.</span></span>
3. <span data-ttu-id="08286-112">Выполните шаги облегчить в мастере настройки.</span><span class="sxs-lookup"><span data-stu-id="08286-112">Complete the steps in the assisted setup guide.</span></span> <span data-ttu-id="08286-113">Обязательно выберите в качестве источника данных **Импорт из Microsoft Dynamcis C5 2012**.</span><span class="sxs-lookup"><span data-stu-id="08286-113">Make sure to choose **Import from Microsoft Dynamcis C5 2012** as the data source.</span></span>  

> [!Note] 
> <span data-ttu-id="08286-114">Организации часто добавляют поля для настройки C5 для определенной сферы деятельности.</span><span class="sxs-lookup"><span data-stu-id="08286-114">Companies often add fields to customize C5 for their specific line of business.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="08286-115"> не производит миграцию данных из настраиваемых полей.</span><span class="sxs-lookup"><span data-stu-id="08286-115"> does not migrate data from custom fields.</span></span> <span data-ttu-id="08286-116">Кроме того, миграция потерпит неудачу, если имеется более 10 настраиваемых полей.</span><span class="sxs-lookup"><span data-stu-id="08286-116">Also, migration will fail if you have more than 10 custom fields.</span></span> 

## <a name="viewing-the-status-of-the-migration"></a><span data-ttu-id="08286-117">Просмотр состояния миграции</span><span class="sxs-lookup"><span data-stu-id="08286-117">Viewing the Status of the Migration</span></span>
<span data-ttu-id="08286-118">Используйте страницу **Обзор миграции данных** для контроля успешности миграции.</span><span class="sxs-lookup"><span data-stu-id="08286-118">Use the **Data Migration Overview** page to monitor the success of the migration.</span></span> <span data-ttu-id="08286-119">На этой странице отображается такая информация, как количество объектов, которые будут включены в миграцию, состояние миграции, количество элементов, для который была произведена миграция, и была ли эта миграция успешной.</span><span class="sxs-lookup"><span data-stu-id="08286-119">The page shows information such as the number of entities that the migration will include, the status of the migration, and the number of items that have been migrated and whether they were successfull.</span></span> <span data-ttu-id="08286-120">Также отображается число ошибок, позволяет вам определить, что пошло неправильно, и, когда это возможно, позволяет легко перейти к объекту для устранения проблем.</span><span class="sxs-lookup"><span data-stu-id="08286-120">It also shows the number of errors, lets you investigate what went wrong and, when possible, makes it easy to go to the entity to fix the issues.</span></span> <span data-ttu-id="08286-121">Дополнительные сведения см. в следующем разделе этой статьи.</span><span class="sxs-lookup"><span data-stu-id="08286-121">For more information, see the next section in this topic.</span></span> 

> [!Note] 
> <span data-ttu-id="08286-122">Пока результаты миграции еще ожидаются, следует обновить страницу для отображения результатов.</span><span class="sxs-lookup"><span data-stu-id="08286-122">While you are waiting for the results of the migration, you must refresh the page to display the results.</span></span>

## <a name="correcting-errors"></a><span data-ttu-id="08286-123">Исправление ошибок</span><span class="sxs-lookup"><span data-stu-id="08286-123">Correcting Errors</span></span>
<span data-ttu-id="08286-124">Если что-то пошло не так и возникли ошибки, в поле **Состояние** отображается **Завершено с ошибками**, а в поле **Число ошибок** отображается количество ошибок.</span><span class="sxs-lookup"><span data-stu-id="08286-124">If something goes wrong and an error occurs, the **Status** field will show **Completed with Errors**, and the **Error Count** field will show how many.</span></span> <span data-ttu-id="08286-125">Для просмотра списка ошибок можно открыть страницу **Ошибки миграции данных**, выбрав:</span><span class="sxs-lookup"><span data-stu-id="08286-125">To view a list of the errors, you can open the **Data Migration Errors** page by choosing:</span></span>

* <span data-ttu-id="08286-126">Номер в поле **Число ошибок** для объекта.</span><span class="sxs-lookup"><span data-stu-id="08286-126">The number in the **Error Count** field for the entity.</span></span> 
* <span data-ttu-id="08286-127">Объект, затем действие **Показать ошибки**.</span><span class="sxs-lookup"><span data-stu-id="08286-127">The entity, and then the **Show Errors** action.</span></span> 

<span data-ttu-id="08286-128">На странице **Ошибки миграции данных** чтобы исправить ошибку, можно выбрать сообщение об ошибке, затем выбрать **Изменить запись** для открытия страницы, которая показывает перенесенные данные для объекта.</span><span class="sxs-lookup"><span data-stu-id="08286-128">On the **Data Migration Errors** page, to fix an error you can choose an error message, then choose **Edit Record** to open a page that shows the migrated data for the entity.</span></span> <span data-ttu-id="08286-129">После исправления одной или нескольких ошибок можно выбрать **Миграция**, чтобы выполнить перенос только исправленных объектов, без необходимости полного повторного выполнения миграции.</span><span class="sxs-lookup"><span data-stu-id="08286-129">After you fix one or more errors, you can choose **Migrate** to migrate only the entities you fixed, without having to completely restart the migration.</span></span>  

> [!Tip]
> <span data-ttu-id="08286-130">Если исправлено несколько ошибок, можно использовать функцию **Выбрать больше**, чтобы выбрать несколько строк для миграции.</span><span class="sxs-lookup"><span data-stu-id="08286-130">If you have fixed more than one error, you can use the **Select More** feature to select multiple lines to migrate.</span></span> <span data-ttu-id="08286-131">Если же ошибки не важны и их можно не исправлять, можно выбрать их, затем выбрать **Пропустить выбранные элементы**.</span><span class="sxs-lookup"><span data-stu-id="08286-131">Alternatively, if there are errors that are not important to fix, you can choose them and then choose **Skip Selections**.</span></span>

> [!Note]
> <span data-ttu-id="08286-132">Если имеются товары, которые включены в спецификацию, может возникнуть необходимость выполнить миграцию несколько раз, если исходный товар не был создан до вариантов, которые ссылаются на него.</span><span class="sxs-lookup"><span data-stu-id="08286-132">If you have items that are included in a BOM, you might need to migrate more than once if the original item is not created before the variants that reference it.</span></span> <span data-ttu-id="08286-133">Если сначала создается вариант товара, то ссылка на исходный товару может привести к появлению сообщения об ошибке.</span><span class="sxs-lookup"><span data-stu-id="08286-133">If an item variant is created first, the reference to the original item can cause an error message.</span></span>  

## <a name="verifying-data-after-migrating"></a><span data-ttu-id="08286-134">Проверка данных после миграции</span><span class="sxs-lookup"><span data-stu-id="08286-134">Verifying Data After Migrating</span></span> 
<span data-ttu-id="08286-135">Если требуется проверять правильность миграции данных, можно просмотреть следующие страницы в C5 и [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="08286-135">If you want to verify that your data migrated correctly, you can look at the following pages in C5 and [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

|<span data-ttu-id="08286-136">Microsoft Dynamics C5 2012</span><span class="sxs-lookup"><span data-stu-id="08286-136">Microsoft Dynamcis C5 2012</span></span> | [!INCLUDE[d365fin](includes/d365fin_md.md)]|
|-----|-----|
|<span data-ttu-id="08286-137">Объекты клиента</span><span class="sxs-lookup"><span data-stu-id="08286-137">Customer Entries</span></span>| <span data-ttu-id="08286-138">Финансовые журналы</span><span class="sxs-lookup"><span data-stu-id="08286-138">General Journals</span></span>|
|<span data-ttu-id="08286-139">Объекты поставщика</span><span class="sxs-lookup"><span data-stu-id="08286-139">Vendor Entries</span></span>| <span data-ttu-id="08286-140">Финансовые журналы</span><span class="sxs-lookup"><span data-stu-id="08286-140">General Journals</span></span>|
|<span data-ttu-id="08286-141">Операции товара</span><span class="sxs-lookup"><span data-stu-id="08286-141">Item Entries</span></span>| <span data-ttu-id="08286-142">Журналы товаров</span><span class="sxs-lookup"><span data-stu-id="08286-142">Item Journals</span></span>|

<span data-ttu-id="08286-143">В [!INCLUDE[d365fin](includes/d365fin_md.md)] пакет для перенесенных данных называется **C5MIGRATE**.</span><span class="sxs-lookup"><span data-stu-id="08286-143">In [!INCLUDE[d365fin](includes/d365fin_md.md)], the batch for the migrated data is named **C5MIGRATE**.</span></span> 

> [!Note]
> <span data-ttu-id="08286-144">Помните, что выполняется миграция только открытых операций.</span><span class="sxs-lookup"><span data-stu-id="08286-144">Remember that we migrate only open entries.</span></span> <span data-ttu-id="08286-145">Вы не найдете никаких исторических данных.</span><span class="sxs-lookup"><span data-stu-id="08286-145">You will not find any historical data.</span></span>

## <a name="stopping-data-migration"></a><span data-ttu-id="08286-146">Остановка миграции данных</span><span class="sxs-lookup"><span data-stu-id="08286-146">Stopping Data Migration</span></span>
<span data-ttu-id="08286-147">Можно остановить миграцию данных, выбрав **Остановить все операции миграции**.</span><span class="sxs-lookup"><span data-stu-id="08286-147">You can stop migrating data by choosing **Stop All Migrations**.</span></span> <span data-ttu-id="08286-148">Если это сделать, все ожидающие операции миграции также будут остановлены.</span><span class="sxs-lookup"><span data-stu-id="08286-148">If you do, all pending migrations are also stopped.</span></span>

## <a name="see-also"></a><span data-ttu-id="08286-149">См. также</span><span class="sxs-lookup"><span data-stu-id="08286-149">See Also</span></span>
<span data-ttu-id="08286-150">[Настройка [!INCLUDE[d365fin](includes/d365fin_md.md)] с помощью расширений](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="08286-150">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  
<span data-ttu-id="08286-151">[Добро пожаловать в [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="08286-151">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span></span>  

