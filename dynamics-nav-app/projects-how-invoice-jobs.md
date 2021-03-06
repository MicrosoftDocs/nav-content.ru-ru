---
title: "Создание счета продажи работы с целью выставления счета по работе"
description: "Описывается, как выставлять счета клиентам за расходы по работе по мере выполнения проекта."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project invoice
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 74b9209216f6e62dfc9519b288adca785cdb8100
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-invoice-jobs"></a>Практическое руководство. Выставление счетов за работы
Во время проекта могут накапливаться затраты на выполнение работы из-за потребления ресурсов, материалов и связанных с работой покупок. В ходе выполнения работы, эти транзакции учитываются в журнале работ. Важно, чтобы перед выставлением счета клиенту в журнал работ были занесены все затраты.

Программа позволяет выставить счет за всю работу в окне **Рабочее задание - строки** или только по выбранным строками "К оплате" в окне **Строки планирования**. Счета можно выставлять после завершения работы или через определенные промежутки времени в ходе выполнения работы согласно плану выставления счетов.

> [!NOTE]  
>   Если выбрать значение **К оплате** в поле **Тип строки работы** в документах покупки для связанных с работой покупок, то создаются строки планирования работ, которые готовы для выставления счета клиенту. Дополнительные сведения см. в разделе [Практическое руководство. Управление запасами для проекта](projects-how-manage-project-supplies.md).

## <a name="to-create-and-post-a-job-sales-invoice"></a>Создание и учет счета продажи для работы
Счет по работе или по одному или нескольким рабочим заданиям можно создавать, когда работа, по которой требуется выставить счет, завершена или при наступлении даты выставления счета согласно плану выставления счетов.

Из окна **Работы** можно выставить клиенту счет, выбрав работу, затем выбрав действие **Создать счет продаж работ**. Приведенная ниже процедура показывает, как использовать пакетное задание для выставления счетов за несколько работ.  

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Работа - создание счета продажи**, а затем выберите связанную ссылку.  
2. Заполните соответствующим образом поля. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Установите фильтры, если требуется ограничить работы, которые будет обрабатывать пакетное задание.
4. Нажмите кнопку **ОК**, чтобы создать счета.  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a>Создание нескольких счетов продажи по работам из строк планирования работы
Можно создать счет из строк планирования работы и указать количество товара, ресурс или счет ГК, по которому следует выставить счет.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Работы**, а затем выберите связанную ссылку.
2. Откройте соответствующую работу.
3. Выберите рабочее задание, для которого поле **Тип рабочего задания** содержит значение **Учет**, затем выберите действие **Строки планирования работ**.  
4. В строке планирования работы в поле **Переносимое в счет количество** введите количество товара, ресурса, типа счета Главной книги, по которому следует выставить счет.  
5. Выберите действие **Создать счет продажи**.
6. В окне **Работа - создание счета продажи** введите дату учета и укажите, требуется ли создать новый счет или добавить этот счет в уже существующему.
7. Нажмите кнопку **ОК**.  

    В строке планирования работы, в поле **Перенесенное в счет количество**, можно увидеть, количество.
8. В окне **Строки планирования работ** выберите действие **Счета продажи/кредит-ноты**.

    Открывается окно **Счет продажи**, содержащее количество, которое было перемещено в счет.  
9. Внесите все дополнительные изменения, затем выберите действие **Учет**.

> [!NOTE]  
>   Приведенная выше процедура аналогична процедуре для создания, рассмотрения и учета кредит-ноты продажи, связанной с работой.

## <a name="to-calculate-and-post-job-completion-entries"></a>Расчет и учет операций выполнения работ
После завершения всех действий по работе, включая учет потребления и выставление счетов, необходимо обновить работу, чтобы она получила **статус** **Завершено**. Затем необходимо обратить все НЗП, которые были учтены в главной книге.

1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Работы**, а затем выберите связанную ссылку.  
2. Выберите открытую работу, затем выберите действие **Изменить**.
3. В поле **Статус** выберите **Завершено**.
4. Следуйте шагам помощи для вычисления и учета НЗП. Можно также выполнить шаги 5 и 6, чтобы сделать это вручную.  
5. Выберите действие **Рассчитать НЗП**.
6. В окне **Расчет НЗП по работам** заполните требуемые поля.  

     У операций НЗП по работам, созданных пакетным заданием, появится флажок в поле **Работа выполнена**, указывающий, что они являются операциями выполнения.  
7. Выберите действие **Работа - учет НЗП в ГК**.
8. В окне **Работа - учет НЗП в ГК** заполните требуемые поля.  

     У операций НЗП по работам в главной книге, созданных пакетным заданием, появится флажок в поле **Работа выполнена**, указывающий, что они являются операциями выполнения.

## <a name="see-also"></a>См. также
[Управление проектами](projects-manage-projects.md)  
[Финансы](finance.md)  
[Покупки](purchasing-manage-purchasing.md)         
[Продажи](sales-manage-sales.md)      
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

