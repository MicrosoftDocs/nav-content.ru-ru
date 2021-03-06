---
title: "Как разместить товары с помощью складского размещения"
description: "Если настройки склада таковы, что требуется обработка размещения, но не требуется обработка приемки, то, чтобы зарегистрировать и учесть информацию о размещении и приемке для документов-источников, нужно пользоваться документом **Размещение запасов**. Входящим документом-источником может быть заказ покупки, заказ возврата продажи, входящий заказ передвижения или производственный заказ, готовая продукция которого готова для размещения."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b42ac71b23a173d5bd3a9e3f1a99b9ac5379e286
ms.contentlocale: ru-ru
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-put-items-away-with-inventory-put-aways"></a>Практическое руководство. Размещение товаров с помощью складского размещения
Если настройки склада таковы, что требуется обработка размещения, но не требуется обработка приемки, то, чтобы зарегистрировать и учесть информацию о размещении и приемке для документов-источников, нужно пользоваться документом **Размещение запасов**. Входящим документом-источником может быть заказ покупки, заказ возврата продажи, входящий заказ передвижения, заказ на сборку или производственный заказ, готовая продукция которого готова для размещения.  

Размещение запасов можно создать тремя способами:  

- Создание размещения в два этапа, при котором сначала создается складской запрос из документа-источника, являющийся для склада сигналом о том, что документ-источник готов для размещения. После этого складское размещение можно создавать в окне **Размещение запасов** на основании документа-источника.  
- Создание складского размещения непосредственно из самого документа-источника.  
- Создавайте складские размещения одновременно для нескольких документов-источников с помощью пакетного задания.  

## <a name="to-request-an-inventory-put-away-by-releasing-the-source-document"></a>Запрос складского размещения путем выпуска документа-источника
В случае заказов на продажу, заказов на возврат продажи, входящих заказов на перемещение и заказов на сборку складской запрос создается путем выпуска заказа. Ниже описано, как это делать из заказа на покупку.  

1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Заказы на покупку**, затем выберите связанную ссылку.
2. Выберите заказ на покупку, который требуется выпустить, затем выберите действие **Выпустить**.  

    Для производственных заказов запрос склада создается посредством создания входящего запроса из выпущенного производственного заказа.  
3.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Запущенные произв. заказы**, затем выберите связанную ссылку.  
4. Выберите действие **Создать вход. складской запрос**.  

> [!NOTE]  
>  Можно также создать входящий запрос склада, если установить флажок **Создать входящий запрос** при обновлении производственного заказа. Дополнительные сведения см. в разделе [Практическое руководство. Обновление или перепланирование производственных заказов](production-how-to-replan-refresh-production-orders.md).  

После создания складского запроса работник склада, которому поручено размещение, сможет увидеть, что документ-источник готов, и создать документ складского размещения.  

## <a name="to-create-an-inventory-put-away-based-on-the-source-document"></a>Создание документа складского размещения из документа-источника
Теперь, если запрос создан, работник склада может создать новое размещение запасов на основании выпущенного документа-источника.   
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Размещение запасов**, а затем выберите связанную ссылку.  
2. Выберите действие **Создать**.  
3. В поле **Документ-источник** выберите тип документа-источника, для которого выполняется размещение.  
4. В поле **Номер источника** выберите документ.  
5. В качестве альтернативы выберите действие **Получить источник документа**, чтобы выбрать документ из списка входящих документов-источников, готовых к размещению на складе.  
6. Нажмите кнопку **ОК**, чтобы заполнить строки размещения в соответствии с выбранными документом-источником.  

## <a name="to-create-an-inventory-put-away-from-the-source-document"></a>Создание документа складского размещения из документа-источника  
1.  В документе-источнике, который может быть заказом на покупку, заказом на возврат продажи, входящим заказом на перемещение или производственным заказом, выберите действие **Создать размещение/подбор запасов**.  
2. Установите флажок **Создать товарное размещение**.
3. Нажмите кнопку **ОК**. Создается новое размещение запасов.

## <a name="to-create-multiple-inventory-put-aways-with-a-batch-job"></a>Создание нескольких размещений запасов с помощью пакетного задания  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Создать товарное размещение/подбор**, затем выберите связанную ссылку.  
2.  В окне запроса на экспресс-вкладке **Запрос склада** с помощью полей **Документ-источник** и **Номер источника** отфильтруйте данные по определенному типу документов или диапазонам номеров документов.  
3.  На экспресс-вкладке **Параметры** установите флажок **Создать размещение запасов**.
4.  Нажмите кнопку **ОК**. Создаются указанные размещения запасов.

## <a name="to-record-the-inventory-put-away"></a>Регистрация размещения запасов  
1. Откройте предварительно созданный документ размещения, выбрав одно из окон **Размещения запасов**.  
2. В поле **Код ячейки** в строках размещения, ячейка, в которой требуется разместить товары, предлагается в соответствии с ячейкой товара по умолчанию. При необходимости данную ячейку можно изменить в этом окне.  
3. Произведите размещение и введите в поле **Кол-во для обработки** информацию о реальном количестве размещенного товара.

    Если товары для одной строки необходимо поместить в несколько ячеек, например из-за того, что назначенная ячейка полная, то воспользуйтесь функцией **Разделить строку** на экспресс-вкладке **Строки**. Дополнительные сведения о разделении строк см. в разделе [Практическое руководство. Разделение строк складских заданий](warehouse-how-to-split-warehouse-activity-lines.md).  
4. По завершении размещения выберите действие **Учет**.  

В процессе учета будет учтена приемка или, для производственных заказов, выход размещенных строк документа-источника, а если на складе используются ячейки, то при учете будут также созданы складские операции, чтобы учесть изменения количества в ячейках.

## <a name="see-also"></a>См. также  
[Управление складом](warehouse-manage-warehouse.md)  
[Наличие](inventory-manage-inventory.md)  
[Настройка управления складом](warehouse-setup-warehouse.md)     
[Управление сборкой](assembly-assemble-items.md)    
[Сведения о проектировании: управление складом](design-details-warehouse-management.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

