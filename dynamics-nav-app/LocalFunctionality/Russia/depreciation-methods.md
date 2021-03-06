---
title: "Методы амортизации"
description: "В [!INCLUDE[navnow](../../includes/navnow_md.md)] есть три метода амортизации, доступных только в России."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: f0cf7dafd3256f3f01fa1611f04e061a0489d042
ms.contentlocale: ru-ru
ms.lasthandoff: 10/26/2017

---
# <a name="depreciation-methods"></a>Методы амортизации
В [!INCLUDE[navnow](../../includes/navnow_md.md)] есть три метода амортизации, доступных только в России.  

- Линейный метод — **Линейный (Россия)**  
- Нелинейный метод — **Ум. ост./лин. (Россия)**  
- Нелинейный метод для группы ОС — **Ум. ост./лин. (Россия) - группа нал.**  

## <a name="straight-line-method"></a>Линейный метод  
 Для использования данного метода выберите параметр **Линейный (Россия)** в соответствующей книге амортизации основного средства.  

 Основная формула расчета для линейного метода имеет вид K = 1/N * 100%, где K — это ежемесячная норма амортизации, N — номер месяца амортизации. Метод SL работает следующим образом:  

-   Расчет амортизации основывается на ежемесячном принципе; в каждом месяце амортизации 30 дней. Эти параметры настраиваются автоматически во время расчета амортизации.  

-   Дата начала амортизации для любой операции приобретения основного средства является первым днем месяца, следующего за месяцем, когда приобретенное ОС было введено в эксплуатацию.  

-   Дата окончания амортизации является последней датой месяца реализации ОС, его списания или продажи.  

-   В процессе расчета амортизации система проверяет, что амортизация за предыдущий месяц была учтена для конкретного ОС. Эта функция позволяет избежать пропуска периодов амортизации.  

## <a name="non-linear-method"></a>Нелинейный метод  
 Для использования данного метода выберите параметр **Ум. ост./лин. (Россия)** в соответствующей книге амортизации основного средства.  

 При расчете по нелинейному методу используются две формулы — одна для начала амортизации, а другая для ее завершения.  

 Формула расчета для нелинейного метода имеет вид K = 2/N * 100%, где K — это ежемесячная норма амортизации, N — номер месяца амортизации. Константа 2 в этой формуле фиксирована в коде и не должна настраиваться вручную.  

 Если остаточная стоимость ОС становится равной или меньшей чем 20 процентов стоимости приобретения, ежемесячная амортизация будет рассчитываться по другому. С этого момента используется линейная амортизация до того момента, пока основное средство не будет полностью амортизировано.  

 Константа в 20 процентов от стоимости приобретения фиксирована в коде и не должна настраиваться вручную.  

## <a name="non-linear-method-for-a-group-of-fixed-assets"></a>Нелинейный метод для группы ОС  
 Для использования данного метода выберите параметр **Ум. ост./лин. (Россия) - группа нал.** в соответствующей книге амортизации основного средства.  

 Нелинейный метод можно применять к группам основных средств с помощью групп амортизации, настроенных в окне в окне **Группа амортизации**. Каждая группа амортизации должна иметь определенные значение **Норма налоговой амортизации** и **Коэффициент амортизации**, равный **1**.  

 Прежде чем использовать этот метод следует убедиться в том, были применены соответствующие параметры в окне **Настройка налоговых регистров**. Используйте информацию в следующей таблице для правильного применения параметров.  

|Поле|Описанием|  
|---------------------------------|---------------------------------------|  
|**Использ. метод групповой аморт. из**|Введите дату начала, с которой можно применять нелинейный метод амортизации. Дата должна быть первым днем календарного года.|  
|**Миним. баланс по группе**|Введите минимальную сумму, действующую как сальдо для группы амортизации. Если учетная стоимость основного средства меньше этой суммы, в этом периоде амортизацию можно списать.|  
|**Списание в расходы**|Укажите, нужно ли списывать издержки ОС, если балансовая стоимость основного средства списывается в периоде, когда балансовая стоимость меньше или равна сумме **Миним. баланс по группе**. В противном случае балансовая стоимость будет списана в следующем периоде.|  

## <a name="see-also"></a>См. также  
 [Амортизационная премия](depreciation-bonus.md)   
 [Практическое руководство. Настройка амортизации основных средств](../../fa-how-setup-depreciation.md)

