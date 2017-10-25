---
title: "Сведения о проектировании — изменения модуля codeunit 12: изменения в процедурах учета финансовых журналов"
description: "В этом выпуске [!INCLUDE[d365fin](includes/d365fin_md.md)] реализованы следующие изменения."
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
ms.openlocfilehash: 19bbc6eb4939fa7f4e0180a62b03998cd2f386b6
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="codeunit-12-changes-changes-in-general-journal-post-procedures"></a>Изменения модуля codeunit 12: изменения процедур учета финансовых журналов
В этом выпуске [!INCLUDE[d365fin](includes/d365fin_md.md)] реализованы следующие изменения.  

|**Microsoft Dynamics NAV 2009 R2**|**Microsoft Dynamics NAV 2013 R2**|**Комментарий**|  
|----------------------------------------|----------------------------------------|-----------------|  
|GetGLReg|GetGLReg|Обновлено|  
|RunWithCheck|RunWithCheck|Обновлено|  
|RunWithoutCheck|RunWithoutCheck|Обновлено|  
|Code|Code|Обновлено|  
||PostGenJnlLine|Добавление|  
||InitAmounts|Добавление|  
||InitLastDocDate|Добавление|  
|InitVAT|InitVAT|Обновлено|  
|PostVAT|PostVAT|Обновлено|  
|InsertVAT|InsertVAT|Обновлено|  
|SummarizeVAT|SummarizeVAT|Обновлено|  
|InsertSummarizedVAT|InsertSummarizedVAT|Обновлено|  
|PostGLAcc|PostGLAcc|Обновлено|  
|PostCust|PostCust|Обновлено|  
|PostVend|PostVend|Обновлено|  
|PostBankAcc|PostBankAcc|Обновлено|  
|PostFixedAsset|PostFixedAsset|Обновлено|  
|PostICPartner|PostICPartner|Обновлено|  
|InitCodeUnit|StartPosting|Обновлено|  
||ContinuePosting|Добавление|  
|FinishCodeunit|FinishPosting|Обновлено|  
||PostUnrealizedVAT|Добавление|  
||CheckPostUnrealizedVAT|Добавление|  
||ExchangeAccounts|Добавление|  
|InitGLEntry|InitGLEntry|Обновлено|  
||InitGLEntryVAT|Добавление|  
||InitGLEntryVATCopy|Добавление|  
|InsertGLEntry|InsertGLEntry|Обновлено|  
||CreateGLEntry|Добавление|  
||CreateGLEntryBalAcc|Добавление|  
||CreateGLEntryVAT|Добавление|  
||CreateGLEntryVATCollectAdj|Добавление|  
||CreateGLEntryFromVATEntry|Добавление|  
||UpdateCheckAmounts|Добавление|  
|ApplyCustLedgEntry|ApplyCustLedgEntry|Обновлено|  
||CalcPmtDiscPossible|Добавление|  
||CalcPmtTolerancePossible|Добавление|  
|CalcPmtTolerance|CalcPmtTolerance|Обновлено|  
|CalcPmtDisc|CalcPmtDisc|Обновлено|  
|CalcPmtDiscIfAdjVAT|CalcPmtDiscIfAdjVAT|Обновлено|  
|CalcPmtDiscTolerance|CalcPmtDiscTolerance|Обновлено|  
||CalcPmtDiscVATBases|Добавление|  
||CalcPmtDiscVATAmounts|Добавление|  
||InsertPmtDiscVATForVATEntry|Добавление|  
||InsertPmtDiscVATForGLEntry|Добавление|  
|CalcCurrencyApplnRounding|CalcCurrencyApplnRounding|Обновлено|  
|FindAmtForAppln|FindAmtForAppln|Обновлено|  
|CalcCurrencyUnrealizedGainLoss|CalcCurrencyUnrealizedGainLoss|Обновлено|  
|CalcCurrencyRealizedGainLoss|CalcCurrencyRealizedGainLoss|Обновлено|  
|CalcApplication|CalcApplication|Обновлено|  
|CalcRemainingPmtDisc|CalcRemainingPmtDisc|Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CalcAmtLCYAdjustment|CalcAmtLCYAdjustment|Добавление|  
|InitNewCVLedgEntry|InitFromGenJnlLine|Перемещено в таблицу 383 "Буфер подробных операций КП"|  
|InitOldCVLedgEntry|CopyFromCVLedgEntryBuf|Перемещено в таблицу 383 "Буфер подробных операций КП"|  
|InsertDtldCVLedgEntry|InsertDtldCVLedgEntry|Перемещено в таблицу 383 "Буфер подробных операций КП"|  
||InitBankAccLedgEntry|Добавление|  
||InitCheckLedgEntry|Добавление|  
||InitCustLedgEntry|Добавление|  
||InitVendLedgEntry|Добавление|  
||InsertDtldCustLedgEntry|Добавление|  
||InsertDtldVendLedgEntry|Добавление|  
|CustUnrealizedVAT|CustUnrealizedVAT|Обновлено|  
|CustPostApplyCustLedgEntry|CustPostApplyCustLedgEntry|Обновлено|  
||PrepareTempCustLedgEntry|Добавление|  
|UnapplyCustLedgEntry|UnapplyCustLedgEntry|Обновлено|  
|TransferCustLedgEntry|CopyFromGenJnlLine|Перемещено в таблицу 21 "Книга операций клиентов"|  
|PostDtldCustLedgEntries|PostDtldCustLedgEntries|Обновлено|  
||PostDtldCustLedgEntry|Добавление|  
||PostDtldCustLedgEntryUnapply|Добавление|  
||GetDtldCustLedgEntryAccNo|Добавление|  
|ZeroTransNoDtldCustLedgEntries|SetZeroTransNo|Перемещено в таблицу 379 "Подробные операции клиента"|  
|AutoEntrForDtldCustLedgEntries||Реорганизовано в PostDtldCustLedgEntryUnapply|  
|CustUpdateDebitCredit|UpdateDebitCredit|Перемещено в таблицу 379 "Подробные операции клиента"|  
|ApplyVendLedgEntry|ApplyVendLedgEntry|Обновлено|  
||PrepareTempVendLedgEntry|Добавление|  
|VendPostApplyVendLedgEntry|VendPostApplyVendLedgEntry|Обновлено|  
|UnapplyVendLedgEntry|UnapplyVendLedgEntry|Обновлено|  
|TransferVendLedgEntry|CopyFromGenJnlLine|Перемещено в таблицу 25 "Книга операций поставщиков"|  
|PostDtldVendLedgEntries|PostDtldVendLedgEntries|Обновлено|  
||PostDtldVendLedgEntry|Добавление|  
||PostDtldVendLedgEntryUnapply|Добавление|  
||GetDtldVendLedgEntryAccNo|Добавление|  
||PostDtldCVLedgEntry|Добавление|  
||PostDtldCustVATAdjustment|Добавление|  
||PostDtldVendVATAdjustment|Добавление|  
|ZeroTransNoDtldVendLedgEntries|SetZeroTransNo|Перемещено в таблицу 380 "Подробные операции поставщика"|  
|AutoEntrForDtldVendLedgEntries||Реорганизовано в PostDtldVendLedgEntryUnapply|  
|VendUpdateDebitCredit|UpdateDebitCredit|Перемещено в таблицу 380 "Подробные операции поставщика"|  
|VendUnrealizedVAT|VendUnrealizedVAT|Обновлено|  
||PostUnrealVATEntry|Добавление|  
||PostApply|Добавление|  
|PostUnrealVATByUnapply|PostUnrealVATByUnapply|Обновлено|  
||PostUnapply|Добавление|  
||InsertDtldCustLedgEntryUnapply|Добавление|  
||InsertDtldVendLedgEntryUnapply|Добавление|  
||InsertTempVATEntry|Добавление|  
||ProcessTempVATEntry|Добавление|  
||UpdateCustLedgEntry|Добавление|  
||UpdateVendLedgEntry|Добавление|  
|UpdateCalcInterest|UpdateCalcInterest|Обновлено|  
|UpdateCalcInterest2|UpdateCalcInterest2|Обновлено|  
|GLCalcAddCurrency|GLCalcAddCurrency|Обновлено|  
|HandleAddCurrResidualGLEntry|HandleAddCurrResidualGLEntry|Обновлено|  
|CalcLCYToAddCurr|CalcLCYToAddCurr|Обновлено|  
|CalcAddCurrFactor||Удалено|  
|GetCurrencyExchRate|GetCurrencyExchRate|Обновлено|  
|ExchAmount|ExchangeAmount|Перемещено в таблицу 330 "Курс валюты"|  
|ExchangeAmtLCYToFCY2|ExchangeAmtLCYToFCY2|Обновлено|  
|CalcAddCurrForUnapplication|CalcAddCurrForUnapplication|Обновлено|  
|CheckNonAddCurrCodeOccurred|CheckNonAddCurrCodeOccurred|Обновлено|  
|CheckCalcPmtDisc||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CheckCalcPmtDiscCVCust||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CheckCalcPmtDiscCust||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CheckCalcPmtDiscGenJnlCust||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CheckCalcPmtDiscCVVend||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CheckCalcPmtDiscVend||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|CheckCalcPmtDiscGenJnlVend||Перемещено в модуль Codeunit 426 "Управление отклонением в оплате"|  
|Reverse|Reverse|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|ReverseCustLedgEntry|ReverseCustLedgEntry|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|ReverseVendLedgEntry|ReverseVendLedgEntry|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|ReverseBankAccLedgEntry|ReverseBankAccLedgEntry|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|ReverseVAT|ReverseVAT|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|SetReversalDescription|SetReversalDescription|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|ApplyCustLedgEntryByReversal|ApplyCustLedgEntryByReversal|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|ApplyVendLedgEntryByReversal|ApplyVendLedgEntryByReversal|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
|PostPmtDiscountVATByUnapply|PostPmtDiscountVATByUnapply|Перемещено в модуль Codeunit 17 "Фин. журнал - Обратный учет"|  
||CheckDimComb|Добавлено в модуль codeunit 17 "Фин. журнал - Обратный учет"|  
||CopyCustLedgEntry|Добавлено в модуль codeunit 17 "Фин. журнал - Обратный учет"|  
||CopyVendLedgEntry|Добавлено в модуль codeunit 17 "Фин. журнал - Обратный учет"|  
||CopyBankAccLedgEntry|Добавлено в модуль codeunit 17 "Фин. журнал - Обратный учет"|  
|HandlDtlAddjustment|HandleDtldAdjustment|Обновлено|  
|CollectAddjustment|CollectAdjustment|Обновлено|  
|SetOverDimErr|SetOverDimErr|Обновлено|  
|PostJob|PostJob|Обновлено|  
|InsertVATEntriesFromTemp|InsertVATEntriesFromTemp|Обновлено|  
|CaptureOrRefundCreditCardPmnt|CaptureOrRefundCreditCardPmnt|Обновлено|  
|UpdateDOPaymentTransactEntry|UpdateDOPaymentTransactEntry|Обновлено|  
|ABSMin|ABSMin|Обновлено|  
|GetApplnRoundPrecision|GetApplnRoundPrecision|Обновлено|  
|CheckDimValueForDisposal|CheckDimValueForDisposal|Обновлено|  
|CalculateCurrentBalance|CalculateCurrentBalance|Обновлено|  
|IncludeVATAmount||Перемещено в таблицу 81 "Строка финансового журнала"|  
|CalcVATAmountFromVATEntry|CalcVATAmountFromVATEntry|Обновлено|  
||TotalVATAmountOnJnlLines|Добавление|  
||SetGLRegReverse|Добавление|  
||GetGLSetup|Добавление|  
||ReadGLSetup|Добавление|  
||CheckSalesExtDocNo|Добавление|  
||CheckPurchExtDocNo|Добавление|  
||CheckGLAccDimError|Добавление|  
||GetCurrency|Добавление|  
||PostDtldAdjustment|Добавление|  
||GetNextEntryNo|Добавление|  
||GetNextTransactionNo|Добавление|  
||GetNextVATEntryNo|Добавление|  
||IncrNextVATEntryNo|Добавление|  
||IsNotPayment|Добавление|  
||IsTempGLEntryBufEmpty|Добавление|  
||IsVATAdjustment|Добавление|  
||IsVATExcluded|Добавление|  
||UpdateDimensions|Добавление|  
||UpdateDimensionsFromCustLedgEntry|Добавление|  
||UpdateDimensionsFromVendLedgEntry|Добавление|  
||UpdateTotalAmounts|Добавление|  
||CreateGLEntriesForTotalAmounts|Добавление|  

## <a name="see-also"></a>См. также  
 [Сведения о проектировании. Изменения модуля codeunit 12: сопоставление глобальных переменных для строки учета финансового журнала](design-details-codeunit-12-changes-mapping-global-variables-for-general-journal-post-line.md)

