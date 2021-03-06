---
title: "Как учитывать сервисные заказы"
description: "После создания сервисного заказа, заполнения всей необходимой информации и внесения всех изменений, можно учесть этот сервисный заказ. Чтобы получить возможность учета сервисного заказа, он должен содержать, по меньшей мере, одну строку сервисного товара и одну строку сервиса. Если в заказе содержится несколько сервисных строк, будет выполнен учет всех строк одновременно."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d93f6520237d2153220654f0f2eb226d8a75adfb
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-service-orders-and-credit-memos"></a>Практическое руководство. Учет сервисных заказов и кредит-нот
После создания сервисного заказа, заполнения всей необходимой информации и внесения всех изменений, можно учесть этот сервисный заказ. Чтобы получить возможность учета сервисного заказа, он должен содержать, по меньшей мере, одну строку сервисного товара и одну строку сервиса. Если в заказе содержится несколько сервисных строк, будет выполнен учет всех строк одновременно.  

При наличии большого количества сервисных заказов можно экономить время, используя пакетное задание для их одновременного учета. Пакетное задание можно запустить из любого сервисного заказа.

> [!Tip]
> Перед учетом сервисного документа рекомендуется использовать действие **Тестовый отчет** для проверки, нет ли каких-либо ошибок или недостающей информации. Если существуют ошибки, необходимо разрешить данную проблему. Затем можно распечатать новый тестовый отчет для проверки исправлений, и затем выполнить учет документа.
  
## <a name="to-post-a-service-order"></a>Учет сервисного заказа    
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные заказы**, затем выберите связанную ссылку.  
2. Откройте соответствующий сервисный заказ.  
3. На странице **Сервисный заказ** выберите одно из следующих действий.  
  
    |**Действие**|**Результат**|  
    |------------------|----------------|  
    |**Тестовый отчет** | Проверяет все части этого документа и создает отчет по результатам проверки. Если в отчёте показаны какие-либо ошибки или указано на отсутствие данных, следует устранить проблему. Тогда можно распечатать новый отчёт.|  
    |**Учет** | Производится учет заказа без распечатки расходной накладной или счета.|  
    |**Учет и печать** | Производится учет заказа и распечатка либо расходной накладной (если по заказу производится отгрузка без выставления счета), либо счета (если по заказу выставлен счет).|  
    |**Пакетный учет.** | Учитывает несколько сервисных заказов за один раз.|  
  
4. После учета заказа требуется указать один из следующих параметров учета заказа.  
  
    |**Варианты учета**|**Результат**|  
    |------------------------|----------------|  
    |**Отгрузить** | Учитывает расходную накладную для товара.|  
    |**Cчет** | Производится выставление счета по уже отгруженному товару.|  
    |**Отгрузить и выставить счет** | Товар отгружается и по нему выставляется счет.|  
    |**Отгрузка и использование** | Учитывает отгрузку и использование по данному заказу. При этом обновляются соответствующие количества в строках сервиса данного заказа и в документе сервисной расходной накладной, который был учтен раньше.|  
  
Учет потребления возможен только в том случае, если строка содержит количество, которое было поставлено, но еще не включено в счет или не потреблено.  
  
Во время учета заказа создаются соответствующие операции книги и учтенные документы. Соответствующие поля обновляются в документе сервисного заказа.  

## <a name="to-batch-post-service-orders"></a>Выполнение пакетного учета сервисных заказов
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные заказы**, затем выберите связанную ссылку.  
2. Выберите действие **Пакетный учет**.  
3.  Задав фильтры, можно выбрать для обработки в пакетном задании определенные номера или интервал номеров сервисных заказов.  
4.  Нажмите **ОК** для запуска пакетного задания.  

## <a name="to-post-a-service-credit-memo"></a>Учет сервисной кредит-ноты  
После создания и заполнения сервисной кредит-ноты можно учесть кредит-ноту. Если обнаружены какие-либо ошибки или отсутствие данных во время учета кредит-ноты, процесс будет прерван с сообщением об ошибке.  
   
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные кредит-ноты**, затем выберите связанную ссылку.  
2. Создать новую сервисную кредит-ноту. На вкладке **Главная** в группе **Создать** выберите **Создать**.  
3. Заполните обязательные поля.  
4. На вкладке **Действия** в группе **Учет** выберите **Учет**. Если требуется распечатать кредит-ноту одновременно с ее учетом, выберите вместо этого **Учет и печать**.  
5. Выберите **Тестовый отчет**, чтобы проверить кредит-ноты перед их учетом. После запуска этого отчета проверяются указанные в документе даты учета.  
6. Чтобы выполнить учет нескольких сервисных кредит-нот одновременно, выполните пакетное задание **Пакетный учет сервисных кредит-нот**. Это удобно, если необходимо учесть большое количество кредит-нот.  
  
> [!NOTE]  
>  Важно ввести всю необходимую информацию в кредит-ноты перед их пакетным учетом. В противном случае они, возможно, не будут учтены. После завершения учета пакетным заданием выдается сообщение о количестве учтенных сервисных кредит-нот.  

## <a name="to-post-consumption-from-a-service-order"></a>Учет потребления из сервисного заказа  
Далее описан порядок учета товаров, часов использования ресурса и/или себестоимостей для конкретной сервисной операции, которые не будут включены в выставляемые клиенту счета. Обратите внимание, что учесть использованные товары, ресурсо-часы или себестоимости можно только для учтенных отгрузок, для которых нет учтенных счетов или использования.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные заказы**, затем выберите связанную ссылку.  
2. Откройте сервисный заказ, для которого требуется учесть потребление.  
3. Выберите сервисный товар. Выберите **Действия**, затем выберите **Заказ** и **Сервисные строки**.  
4. Найдите необходимые операции и укажите те количества, для которых необходимо учесть потребление, в поле **Количество для потребления**. Данное количество не может превышать уже отгруженное количество и оставшееся количество, не включенное в выставленные счета после частичного выставления счетов по данной отгрузки.  
  
    > [!NOTE]  
    >  Чтобы зарегистрировать потребление для работы, заполните поля **Код работы**, **Номер рабочего задания** и **Тип строки работы** в сервисной строке.  
  
5. Выберите строки для учета, затем выберите действие **Учесть**. На открывшейся странице выберите **Отгрузить и потребить**.  
  
Сервис учитывается как использованный полностью или частично в зависимости от значения в поле **Количество для потребления**, и создаются соответствующие операции книги. Кроме того, будут хронологически обновлены учтенные раньше документы сервисных расходных накладных, с учетом использованных количеств. Соответствующие количества будут обновлены в сервисных строках заказа.  

## <a name="to-post-shipments-from-service-orders"></a>Учет отгрузок из сервисных заказов  
После уточнения информации по обслуживанию можно скорректировать и учесть использованные товары, затраченное время и понесенные затраты. В результате [!INCLUDE[d365fin](includes/d365fin_md.md)] вносит необходимые изменения, отражающие новое состояние складских запасов и текущий статус обработки конкретного заказа.  
  
В следующей процедуре описывается учет отгрузки товаров из сервисной строки на складах, для которых не настроена обязательная обработка склада.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисный заказ**, затем выберите связанную ссылку. 2. В окне выбранного сервисного заказа выберите **Действия**, **Заказ**, **Сервисные строки**.  
3. В окне **Строки сервиса** найдите необходимые операции и укажите в поле **Кол-во для отгрузки** количество, которое должно быть учтено.  
  
   > [!NOTE]  
   >  Значение количества для отгрузки зависит того, в каком объеме необходимо учесть отгрузку: полностью или частично. Если выбирается полная отгрузка, значение в поле **Кол-во для отгрузки** должно быть равно значению в поле **Кол-во**. В случае учета частичной отгрузки необходимо указать количество, которое планируется отгрузить сначала. Если частичная отгрузка по этому сервисному заказу уже производилась, необходимо указать значение отгруженного ранее количества в поле **Отгруженное кол-во**. Максимальное количество, которое можно указать в поле **Кол-во для отгрузки** — это количество, которое еще не было отгружено, выраженное в заданных единицах измерения.  
  
4. Выберите **Действия**, **Учет**, **Учет**. В открывшемся окне выберите **Отгрузить**.  
  
[!INCLUDE[d365fin](includes/d365fin_md.md)] создает операции в книге учета (в книге гарантии, книге товаров, книге сервиса или ГК), создает учтенный документ сервисной расходной накладной и обновляет соответствующие поля в строках сервиса данного сервисного заказа.  
  
Если в настройках склада указана необходимость обработки склада, отгрузка и перемещение товаров из сервисных строк происходят так же, как и в других исходных документах. Единственным отличием является то, что товары в сервисной строке можно потребить для внутренних или внешних целей, поэтому требуются две разные функции выпуска.  
  
Дополнительные сведения об отгрузке товаров сервисной строки в расширенных конфигурациях склада см. в разделе [Подбор товаров для складской отгрузки](warehouse-pick-items.md).  

## <a name="to-undo-posted-consumption"></a>Отмена учтенного потребления  
Может отменить потребление по сервисным заказам. Например, в случае учета по ошибке.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Учтенные сервисные расходные накладные**, затем выберите связанную ссылку.  
2. Откройте учтенную сервисную расх. накладную по которой было учтено ошибочное потребление.  
3. Выберите **Действия**, выберите **Расх. накладная**, затем выберите **Строки сервисной расх. накладной**.  
4. Выберите строки, содержащие неправильное потребление, затем выберите действие **Отмена потребления**.  
  
 Для выбранных строк вставляется балансирующая строка сервисной расходной накладной с отрицательными значениями в полях количества.  
  
> [!NOTE]  
>  Нельзя отменить потребление, если:  

>    * Сервисный заказ был закрыт.  
>    * Оно учтено в области "Работы", поэтому с ним связаны операции книги работ.  
  
## <a name="to-post-service-lines"></a>Учет сервисных строк  
Если необходимо обрабатывать сервисный заказ длительное время без выполнения учёта, может понадобиться учесть некоторые из связанных с этим заказом строк сервиса, например, в качестве способа поддержки обновления склада. Можно выполнить учет, указав соответствующие количества в подлежащих учету строках. Имеется возможность выбрать поочередный учет строк или одновременный учет нескольких строк.  
  
Следующая процедура описывает учет отгрузки непосредственно из сервисного заказа на складах, где не настроена обработка на складе. Если настройки склада требуют обработку склада, то учет из различных полей отгрузки происходит в складском документе, в зависимости от настроек склад.
  
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Сервисные заказы**, затем выберите связанную ссылку.  
2. Откройте сервисный заказ, затем выберите действие **Сервисные строки**.  
4. В строках, которые необходимо учесть, заполните поля **Кол-во для отгрузки**, **Кол-во для выставления счета** и **Количество для потребления**, в зависимости от того, как будут учитываться строки.  
5. Выберите действие **Учесть**.
  
## <a name="see-also"></a>См. также  
[Учет в сервисном обслуживании](service-service-posting.md)  
[Практическое руководство. Создание сервисного заказа](service-how-to-create-service-orders.md)  

