---
title: "Как настраивать типы ячеек"
description: "Можно направить поток товаров через ячейки, указанные для определенной складской деятельности. Для ячейки заданы базовые действия и определен метод использования ячейки при помощи присвоения типа ячейки."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 406f9e1a325c791fb19558e13db5ace93fdc8e31
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-bin-types"></a>Практическое руководство. Настройка типов ячеек
Можно направить поток товаров через ячейки, указанные для определенной складской деятельности. Для ячейки заданы базовые действия и определен метод использования ячейки при помощи присвоения типа ячейки.  

Существует 8 типов ячеек. Возможно управление складом с использованием всех восьми типов ячеек, возможна также работа с ячейками только следующих типов: RECEIVE, PUTPICK, SHIP и QC. Эти четыре типа ячеек дают возможность делать предложения по поддержанию потока товаров и позволяют регистрировать расхождения в запасах.  

## <a name="to-set-up-the-bin-types-you-want-to-use"></a>Настройка необходимых типов ячеек  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Типы ячеек**, а затем выберите связанную ссылку.  
2.  В окне **Типы ячейки** создайте код из десяти символов для типа ячейки.  
3.  Выберите действия, которые можно выполнить с каждым типом ячейки.  

> [!NOTE]  
>  Типы ячеек можно применять только в том случае, если на складе используется расширенный подбор и размещение.  

Тип ячейки определяет только то, как ячейка будет использоваться при обработке товарного потока на складе. Всегда существует возможность отменить предложения по любому складскому документу и перемещать товары в ячейку или из нее складским передвижением.  

Типы ячеек, которые можно создать, перечислены ниже.  

|Тип ячейки|Описанием|  
|------------------|---------------------------------------|  
|ПРИЕМ|Товары, зарегистрированные как учтенные приемки, но еще не размещенные.|  
|SHIP|Товары, подобранные для строк отгрузки со склада, но еще не учтенные как отгруженные.|  
|PUT AWAY|Обычно товары складируются по более крупным единицам измерения, но это неудобно для целей подбора. Поскольку эти ячейки не используются для подбора ни по производственному заказу, ни для отгрузки, полезность ячейки с типом Размещение может оказаться небольшой, но этот тип ячеек может быть полезен при покупке большого количества товаров. Для ячеек этого типа всегда должен быть установлен низкий рейтинг, чтобы при размещении полученных товаров программой сначала использовались ячейки РАЗПОД с более высоким рейтингом, закрепленные за товаром. Если используется этот тип ячеек, необходимо регулярно выполнять пополнение ячеек, чтобы товары, хранящиеся в этих ячейках, были доступны также в ячейках с типами «Размещение/подбор» или «Подбор».|  
|PICK|Товары подлежат использованию только для подбора, например, для товаров с приближающимся окончанием срока годности, размещенных в данной ячейке. Если присвоить этим ячейкам более высокий рейтинг, они будут предлагаться на подбор в первую очередь.|  
|PUTPICK|Товары в ячейках, которые предлагаются для функций размещения и подбора. Ячейки этого типа, вероятно, обладают различным рейтингом. Можно настроить ячейки хранения крупных партий как ячейки данного типа с низким рейтингом, по сравнению с обычными ячейками подбора или ячейками зоны прямого подбора.|  
|QC|Эта ячейка используется для коррекции товара, если такая ячейка задана в карточке склада в поле **Код ячейки коррекции**. Можно также настроить ячейки этого типа для бракованных товаров и товаров, подлежащих проверке. Можно переместить товары в ячейку данного типа, если необходимо сделать их недоступными для обычного потока товаров.<br /><br /> **ПРИМЕЧАНИЕ.** В отличие от всех других типов ячеек тип ячейки **КОНКАЧ** не имеет полей с флажками для обработки товаров, устанавливаемых по умолчанию. Это свидетельствует о том, что любое содержимое, помещаемое в ячейку QC, исключается из потоков товаров.|  

## <a name="see-also"></a>См. также
[Управление складом](warehouse-manage-warehouse.md)  
[Наличие](inventory-manage-inventory.md)  
[Настройка управления складом](warehouse-setup-warehouse.md)     
[Управление сборкой](assembly-assemble-items.md)    
[Сведения о проектировании: управление складом](design-details-warehouse-management.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

