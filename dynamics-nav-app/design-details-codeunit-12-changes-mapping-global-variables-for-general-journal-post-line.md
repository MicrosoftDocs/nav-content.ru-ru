---
title: "Сведения о проектировании — изменения модуля codeunit 12 в части сопоставления глобальных переменных для строки учета финансового журнала"
description: "В этом выпуске [!INCLUDE[d365fin](includes/d365fin_md.md)] реализованы следующие изменения."
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
ms.openlocfilehash: cafaddb0ac263cd4dbeda6e3b9fa93243df3e23c
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="codeunit-12-changes-mapping-global-variables-for-general-journal-post-line"></a>Изменения модуля codeunit 12: сопоставление глобальных переменных для строки учета финансового журнала
В этом выпуске [!INCLUDE[d365fin](includes/d365fin_md.md)] реализованы следующие изменения.  

|**Microsoft Dynamics NAV 2009 R2**|**Microsoft Dynamics NAV 2013 R2**|**Комментарий**|  
|----------------------------------------|----------------------------------------|-----------------|  
|GLSetup@1009 : запись 98;|GLSetup@1009 : запись 98;|Не изменено|  
|SalesSetup@1010 : запись 311;||Изменено на локальное|  
|PurchSetup@1011 : запись 312;||Изменено на локальное|  
|AccountingPeriod@1012 : запись 50;||Изменено на локальное|  
|GLAcc@1013 : запись 15;||Изменено на локальное|  
|GLEntry@1014 : запись 17;|GlobalGLEntry@1014 : запись 17;|Переименовано|  
|GLEntryTmp@1015 : ВРЕМЕННАЯ запись 17;|TempGLEntryBuf@1010 : ВРЕМЕННАЯ запись 17;|Переименовано|  
|TempGLEntryVAT@1016 : ВРЕМЕННАЯ запись 17;|TempGLEntryVAT@1016 : ВРЕМЕННАЯ запись 17;|Не изменено|  
|OrigGLEntry@1017 : запись 17;||Удалено|  
|VATPostingSetup@1019 : запись 325;||Изменено на локальное|  
|Cust@1020 : запись 18;||Изменено на локальное|  
|Vend@1021 : запись 23;||Изменено на локальное|  
|GenJnlLine@1022 : запись 81;||Изменено на локальное|  
|GLReg@1029 : запись 45;|GLReg@1029 : запись 45;|Не изменено|  
|CustPostingGr@1030 : запись 92;||Изменено на локальное|  
|VendPostingGr@1031 : запись 93;||Изменено на локальное|  
|Currency@1032 : запись 4;||Изменено на локальное|  
|AddCurrency@1033 : запись 4;|AddCurrency@1033 : запись 4;|Не изменено|  
|ApplnCurrency@1034 : запись 4;||Изменено на локальное|  
|CurrExchRate@1035 : запись 330;|CurrExchRate@1035 : запись 330;|Не изменено|  
|VATEntry@1038 : запись 254;|VATEntry@1038 : запись 254;|Не изменено|  
|BankAcc@1039 : запись 270;||Изменено на локальное|  
|BankAccLedgEntry@1040 : запись 271;||Изменено на локальное|  
|CheckLedgEntry@1041 : запись 272;||Изменено на локальное|  
|CheckLedgEntry2@1042 : запись 272;||Изменено на локальное|  
|BankAccPostingGr@1043 : запись 277;||Изменено на локальное|  
|GenJnlTemplate@1044 : запись 80;||Изменено на локальное|  
|TaxJurisdiction@1045 : запись 320;||Изменено на локальное|  
|TaxDetail@1046 : запись 322;|TaxDetail@1046 : запись 322;|Не изменено|  
|FAGLPostBuf@1047 : ВРЕМЕННАЯ запись 5637;||Изменено на локальное|  
|UnrealizedCustLedgEntry@1084 : запись 21;|UnrealizedCustLedgEntry@1084 : запись 21;|Не изменено|  
|UnrealizedVendLedgEntry@1085 : запись 25;|UnrealizedVendLedgEntry@1085 : запись 25;|Не изменено|  
|GLEntryVATEntryLink@1087 : запись 253;|GLEntryVATEntryLink@1087 : запись 253;|Не изменено|  
|TempVATEntry@1088 : ВРЕМЕННАЯ запись 254;|TempVATEntry@1088 : ВРЕМЕННАЯ запись 254;|Не изменено|  
|ReversedGLEntryTemp@1089 : ВРЕМЕННАЯ запись 17;||Перемещено в модуль Codeunit 17|  
|CostAccSetup@1092 : запись 1108;||Изменено на локальное|  
|GenJnlCheckLine@1048 : модуль Codeunit 11;|GenJnlCheckLine@1001 : модуль Codeunit 11;|Не изменено|  
|ExchAccGLJnlLine@1049 : модуль Codeunit 366;||Изменено на локальное|  
|FAJnlPostLine@1050 : модуль Codeunit 5632;||Изменено на локальное|  
|SalesTaxCalculate@1051 : модуль Codeunit 398;||Изменено на локальное|  
|GenJnlApply@1052 : модуль Codeunit 225;||Изменено на локальное|  
|DimMgt@1053 : модуль Codeunit 408;||Изменено на локальное|  
|JobPostLine@1028 : модуль Codeunit 1001;||Изменено на локальное|  
|TransferGlEntriesToCA@1091 : модуль Codeunit 1105;||Изменено на локальное|  
||PaymentToleranceMgt@1002 : модуль Codeunit 426;|Добавление|  
||AddCurrencyCode@1117 : Код[10];|Добавление|  
|FiscalYearStartDate@1054 : дата;|FiscalYearStartDate@1011 : дата;|Не изменено|  
|NextEntryNo@1055 : целое;|NextEntryNo@1022 : целое;|Не изменено|  
|BalanceCheckAmount@1056 : десятичное;|BalanceCheckAmount@1056 : десятичное;|Не изменено|  
|BalanceCheckAmount2@1057 : десятичное;|BalanceCheckAmount2@1057 : десятичное;|Не изменено|  
|BalanceCheckAddCurrAmount@1058 : десятичное;|BalanceCheckAddCurrAmount@1058 : десятичное;|Не изменено|  
|BalanceCheckAddCurrAmount2@1059 : десятичное;|BalanceCheckAddCurrAmount2@1059 : десятичное;|Не изменено|  
|CurrentBalance@1060 : десятичное;|CurrentBalance@1060 : десятичное;|Не изменено|  
|SalesTaxBaseAmount@1061 : десятичное;||Изменено на локальное|  
|TotalAddCurrAmount@1062 : десятичное;|TotalAddCurrAmount@1062 : десятичное;|Не изменено|  
|TotalAmount@1063 : десятичное;|TotalAmount@1063 : десятичное;|Не изменено|  
|UnrealizedRemainingAmountCust@1086 : десятичное;|UnrealizedRemainingAmountCust@1086 : десятичное;|Не изменено|  
|UnrealizedRemainingAmountVend@1074 : десятичное;|UnrealizedRemainingAmountVend@1074 : десятичное;|Не изменено|  
|NextVATEntryNo@1064 : целое;|NextVATEntryNo@1064 : целое;|Не изменено|  
|FirstNewVATEntryNo@1065 : целое;|FirstNewVATEntryNo@1065 : целое;|Не изменено|  
|NextTransactionNo@1066 : целое;|NextTransactionNo@1066 : целое;|Не изменено|  
|NextConnectionNo@1067 : целое;|NextConnectionNo@1067 : целое;|Не изменено|  
|InsertedTempGLEntryVAT@1068 : целое;|InsertedTempGLEntryVAT@1027 : целое;|Не изменено|  
|LastDocNo@1069 : Код[20];|LastDocNo@1023 : Код[20];|Не изменено|  
|LastLineNo@1070 : целое;||Удалено|  
|LastDate@1071 : дата;|LastDate@1021 : дата;|Не изменено|  
|LastDocType@1072 : ' ,Платеж,Счет,Кредит-нота,Процент-нота,Напоминание';|LastDocType@1025 : ' ,Платеж,Счет,Кредит-нота,Процент-нота,Напоминание';|Не изменено|  
|NextCheckEntryNo@1073 : целое;|NextCheckEntryNo@1028 : целое;|Не изменено|  
|AddCurrGLEntryVATAmt@1075 : десятичное;|AddCurrGLEntryVATAmt@1017 : десятичное;|Не изменено|  
|CurrencyDate@1076 : дата;|CurrencyDate@1020 : дата;|Не изменено|  
|CurrencyFactor@1077 : десятичное;|CurrencyFactor@1019 : десятичное;|Не изменено|  
|UseCurrFactorOnly@1078 : логическое;|UseCurrFactorOnly@1078 : логическое;|Не изменено|  
|NonAddCurrCodeOccured@1079 : логическое;|NonAddCurrCodeOccured@1079 : логическое;|Не изменено|  
|FADimAlreadyChecked@1080 : логическое;|FADimAlreadyChecked@1080 : логическое;|Не изменено|  
|AllApplied@1081 : логическое;||Изменено на локальное|  
|OverrideDimErr@1018 : логическое;|OverrideDimErr@1018 : логическое;|Не изменено|  
|JobLine@1036 : логическое;|JobLine@1036 : логическое;|Не изменено|  
|Prepayment@1037 : логическое;||Удалено|  
|CheckUnrealizedCust@1082 : логическое;|CheckUnrealizedCust@1082 : логическое;|Не изменено|  
|CheckUnrealizedVend@1083 : логическое;|CheckUnrealizedVend@1083 : логическое;|Не изменено|  
|GLEntryNo@1090 : целое;|GLEntryNo@1026 : целое;|Не изменено|  
||GLSetupRead@1015 : логическое;|Добавление|  
||AmountRoundingPrecision@1012 : десятичное;|Добавление|  
||CrCardTransactionEntryNo@1013 : целое;|Добавление|  

## <a name="see-also"></a>См. также  
 [Сведения о проектировании. Изменения модуля codeunit 12: изменения в процедурах учета финансовых журналов](design-details-codeunit-12-changes-changes-in-general-journal-post-procedures.md)

