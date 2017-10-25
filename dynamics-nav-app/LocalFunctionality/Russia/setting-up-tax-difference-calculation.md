---
title: "Настройка расчета налоговых разниц"
description: "Расчет налоговых разниц необходимо настроить, если имеется налоговая разница в представлении операций с основными средствами, операций себестоимости товаров или финансовых операций в бухгалтерском и налоговом учете, для которых необходимо зафиксировать расходы, подлежащие списанию. Чтобы настроить налоговые разницы, щелкните **Настройка**, а затем щелкните **Налоговые разницы**."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6631158feaff6a85d401a138e21dfde307ed9f8a
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-tax-difference-calculation"></a>Настройка расчета налоговых разниц
Расчет налоговых разниц необходимо настроить, если имеется налоговая разница в представлении операций с основными средствами, операций себестоимости товаров или финансовых операций в бухгалтерском и налоговом учете, для которых необходимо зафиксировать расходы, подлежащие списанию. Чтобы настроить налоговые разницы, щелкните **Настройка**, а затем щелкните **Налоговые Разницы**.  
  
## <a name="setting-up-posting-groups"></a>Настройка учетных групп  
 В пункте меню **Группы Учета** необходимо указать финансовые счета из настроенного плана счетов, на которых будут учитываться финансовые транзакции с налоговыми разницами.  
  
 В форме "Группы учета налоговой разницы" заполните поля, описанные в следующей таблице.  
  
|Поле|Описанием|  
|---
    title: Setting up Tax Difference Calculation 
    description: Tax difference calculations must be set up if there is a tax difference for the presentation of fixed asset entries, item cost entries, or finance transactions in bookkeeping and tax accounting for which expenses to write off must be fixed. To set tax difference, click **Setup** and then click **Tax Differences**.
    
    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2017"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

------
    title: Setting up Tax Difference Calculation 
    description: Tax difference calculations must be set up if there is a tax difference for the presentation of fixed asset entries, item cost entries, or finance transactions in bookkeeping and tax accounting for which expenses to write off must be fixed. To set tax difference, click **Setup** and then click **Tax Differences**.
    
    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2017"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

-----------|-----------------|  
|**Дата учета ОС**|Введите дату транзакции.|  
|**Номер документа**|Введите номер документа, для которого создана текущая транзакция.|  
|**Номер ОС**|Введите код расходов будущих периодов, для которых создана текущая транзакция.|  
|**Код книги амортизации**|Введите код книги амортизации, для которой будет сформирована эта транзакция.|  
|**Тип учета ОС**|Выберите тип **Транзакция**. Доступные значения: **Покупка**, **Амортизация** и **Продажи**.|  
|**Описание**|Введите описание цели транзакции.|  
|**Сумма**|Введите сумму транзакции.|  
|**Сумма амортиз. без нормализации**|Отображает сумму амортизации до расчета норм списания расходов.|  
  
 Если имеются строки журнала, которые необходимо нормализовать перед списанием расходов, эти журналы невозможно учесть без запуска периодического задания нормализации.  
  
 В следующей процедуре показан порядок обработки функции нормализации.  
  
1.  В журнале расходов будущих периодов щелкните **Функция**, а затем щелкните **Расчет Нормируемой Амортизации**.  
  
2.  В форме **Расчет Аморт. РБП с Норм.** на вкладке **Налоговая Разница** установите фильтр для налоговой разницы.  
  
3.  На вкладке **Параметры** введите учетный период, для которого выполняется расчет.  
  
4.  Нажмите **Печать** для распечатки отчета.  
  
5.  Выполните операцию учета журнала расходов будущих периодов.  
  
## <a name="see-also"></a>См. также  
 [Налоговые регистры](tax-registers.md)   
 [Налоговые разницы](assetId:///e42ca8e7-1cee-4fb8-9f71-e596f29cabc3)   
 [Регистры налоговых разниц](tax-difference-registers.md)   
 [Практическое руководство. Настройка юрисдикций нормы](how-to-set-up-norm-jurisdictions.md)   
 [Практическое руководство. Учет налоговых разниц](how-to-post-tax-differences.md)
