---
title: "Сведения о проектировании — Codeunit 408 Dimension Management"
description: "Codeunit 408 Dimension Management — это библиотека функций, обрабатывающих общие задачи, связанные с измерениями, такие как копирование из одной таблицы в другую или из одного документа в другой."
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
ms.openlocfilehash: 560adbc39f4f77e27d9ac9be6dbea1aa7ed71c81
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-codeunit-408-dimension-management"></a>Сведения о проектировании: Codeunit 408 Dimension Management
Codeunit 408 Dimension Management — это библиотека функций, обрабатывающих общие задачи, связанные с измерениями, такие как копирование из одной таблицы в другую или из одного документа в другой. В этом разделе перечислены изменяемые в Microsoft Dynamics NAV 2013 R2 функции и указано, какие изменения внесены в функции. Множество функций удалено, поскольку нет необходимости копировать данные между таблицами измерений.  

## <a name="modified-functions"></a>Измененные функции  

|Имя функции|Описание изменения|  
|-------------------|------------------------------|  
|CheckDimSetIDComb|Новая функция, которая заменяет собой другие функции проверки и принимает код набора измерений в качестве аргумента вместо таблицы измерений.|  
|CheckDimSetIDComb<br /><br /> CheckDocDimComb<br /><br /> CheckServContractDimComb<br /><br /> CheckDimBuffer<br /><br /> CheckDimComb<br /><br /> CheckDimValueComb|Удаление. Все потребление должно быть изменено на CheckDimSetIDComb.|  
|GetDefaultDim|Изменение для возврата кода набора измерений вместо набора записей.|  
|CopyJnlLineDimToICJnlDim<br /><br /> CopyICJnlDimToJnlLineDim<br /><br /> CopyDocDimtoICDocDim<br /><br /> CopyICDocDimtoICDocDim|Изменение для работы с DimSetID -> ICJnlLineDim|  

## <a name="deleted-functions"></a>Удаленные функции  
 Функции, удаленные из модуля Codeunit 408 в связи с компонентом "Записи набора измерений", перечислены ниже.  

> [!CAUTION]  
>  В ходе обновления кода приложения с Microsoft Dynamics NAV 2009 или предыдущих версий до Microsoft Dynamics NAV 2016 следующие функции будут недоступны для Microsoft Dynamics NAV 2016. Если у вас имеются настройки, использующие какие-либо из этих функций, вам потребуется внести в код соответствующие изменения.

 InsertJnlLineDim  

 UpdateJnlLineDefaultDim  

 GetJnlLineDefaultDim  

 GetPreviousDocDefaultDim  

 GetPreviousProdDocDefaultDim  

 InsertDocDim  

 UpdateDocDefaultDim  

 ExtractDocDefaultDim  

 InsertProdDocDim  

 UpdateProdDocDefaultDim  

 InsertServContractDim  

 UpdateServcontractDim  

 UpdateDefaultDimNewDimValue  

 GetDocDim  

 GetProdDocDim  

 TypeToTableID1  

 TypeToTableID2  

 TypeToTableID3  

 TypeToTableID4  

 TypeToTableID5  

 DeleteJnlLineDim  

 DeleteDocDim  

 DeletePostedDocDim  

 DeleteProdDocDim  

 DeleteServContractDim  

 ShowJnlLineDim  

 SaveJnlLineDim  

 ShowJnlLineNewDim  

 SaveJnlLineNewDim  

 ShowDocDim  

 SaveDocDim  

 ShowProdDocDim  

 SaveProdDocDim  

 ShowTempDim  

 SaveTempDim  

 ShowTempNewDim  

 SaveTempNewDim  

 SaveServContractDim  

 MoveJnlLineDimToLedgEntryDim  

 MoveDocDimToPostedDocDim  

 MoveOneDocDimToPostedDocDim  

 MoveLedgEntryDimToJnlLineDim  

 MoveDimBufToJnlLineDim  

 MoveDimBufToLedgEntryDim  

 MoveDimBufToPostedDocDim  

 MoveDimBufToGLBudgetDim  

 CopyJnlLineDimToJnlLineDim  

 CopyLedgEntryDimToJnlLineDim  

 CopyDocDimToDocDim  

 CopyPostedDocDimToPostedDocDim  

 CopyDocDimToJnlLineDim  

 CopyDimBufToJnlLineDim  

 CopyDimBufToDocDim  

 CopySCDimToDocDim  

 MoveDocDimToLedgEntryDim  

 MoveDocDimToDocDim  

 MoveDocDimArchvToDocDim  

 MoveLedgEntryDimToDocDim  

 MoveProdDocDimToProdDocDim  

 MoveJnlLineDimToProdDocDim  

 MoveJnlLineDimToDocDim  

 MoveJnlLineDimToJnlLineDim  

 CopyLedgEntryDimToLedgEntryDim  

 MoveTempFromDimToTempToDim  

 TransferTempToDimToDocDim  

 MoveJnlLineDimToBuf  

 CopyICJnlDimToICJnlDim  

 TestDimValue  

 TestNewDimValue  

 MoveDimBufToItemBudgetDim. (Удалено, поскольку удалена таблица ItemBudgetDim.)  

 GetServContractDim  

 MoveTempDimToBuf  

 UpdateSCInvLineDim  

 CopyJnlLineDimToBuffer  

 UpdateDocDefaultDim2  

## <a name="see-also"></a>См. также
 [Сведения о проектировании: операции набора измерений](design-details-dimension-set-entries.md)   
 [Сведения о проектировании: обзор операций набора измерений](design-details-dimension-set-entries-overview.md)   
 [Сведения о проектировании: поиск комбинаций измерений](design-details-searching-for-dimension-combinations.md)   
 [Сведения о проектировании: структура таблицы](design-details-table-structure.md)   
 [Сведения о проектировании: примеры кода измененных шаблонов в модификациях](design-details-code-examples-of-changed-patterns-in-modifications.md)

