---
title: "Практическое руководство. Выверка банковских счетов по отдельности"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8b05bc9d09fa1e1a7a01eb4816ffba727611b776
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-bank-accounts-separately"></a>Практическое руководство. Выверка банковских счетов по отдельности
Для выверки банковских счетов в Dynamics NAV на основании выписок, полученных из банка, нужно заполнить строки в окне **Выверка банковского счета**.

**Примечание**. Банковские счета также можно выверять в окне **Журнал выверки платежей**. Если выбрать действие **Учесть платежи и выверить банковский счет**, все открытые операции книги банковских счетов, связанные с примененными операциями книг клиентов или поставщиков, будут закрыты. Это означает, что банковский счет автоматически выверяется по платежам, которые учтены с использованием журнала. Дополнительные сведения см. в разделе [Практическое руководство. Выверка платежей с использованием автоматического применения](receivables-how-reconcile-payments-auto-application.md).

Чтобы включить импорт банковских выписок в электронном виде, необходимо сначала настроить и включить службу банковских выписок Envestnet Yodlee, а затем связать свои банковские счета с соответствующими счетами интернет-банка. Дополнительные сведения см. в разделе [Практическое руководство. Настройка службы банковских выписок Envestnet Yodlee](bank-how-setup-bank-statement-service.md).

**Примечание**. Служба банковских выписок Envestnet Yodlee или служба банковских выписок другого поставщика может быть недоступна в вашей системе. Обратитесь к партнеру Microsoft, если требуется использовать службу банковских выписок для импорта банковских выписок.

Строки в окне **Выверка банковского счета** разделены на две области. В области **Строки банковской выписки** показаны импортированные банковские транзакции или операции книги с неоплаченными платежами. В области **Книга операций по банку/кассе** показаны операции книги на банковском счете.

Операция поиска и применения операций для выверки называется *сопоставлением*. Можно выбрать выполнение соответствия автоматически с помощью функции **Совпадение автоматически**. Кроме того, можно выбрать строки вручную в обеих панелях для связывания каждой строки банковской выписки с одной или несколькими связанными операциями книги операций по банку/кассе, а затем использовать функцию **Совпадение вручную**. В строках с сопоставленными операциями установлен флажок **Применено**.

Область **Строки банковской выписки** в окне **Выверка банковского счета** можно заполнять следующими способами:

* Автоматически, с помощью функции **Импорт выписки с банк. счета** для заполнения строк в соответствии с фактическими банковскими выписками на основе файла, предоставленного банком.
* Вручную, с помощью функции **Предложить строки** для заполнения строк операциями книги по счетам с неоплаченными платежами.

Если значение в поле **Общее сальдо** в области **Строки банковской выписки** равняется значению поля **Сальдо для выверки** в области **Книга операций по банку/кассе**, вы можете выбрать действие **Учесть**, чтобы выверить примененные операции книги банковских счетов. Все непримененные операции книги банковских счетов останутся в этом окне, что указывает на то, что платежи, обработанные для банковского счета, не отражены в последней банковской выписке, или некоторые платежи были получены по чекам.

**Примечание**. Если строки банковских выписок относятся к операциям книги платежных документов, функции сопоставления нельзя использовать. Вместо этого необходимо выбрать действие **Применить операции** и выбрать соответствующую операцию в книге платежных документов для сопоставления строки банковской выписки.

## <a name="to-fill-bank-reconciliation-lines-by-importing-a-bank-statement"></a>Заполнение строк банковской выверки путем импорта банковской выписки  
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Выверка банковского счета**, а затем выберите связанную ссылку.
2. Выберите действие **Создать**.
3. В поле **Номер банковского счета** выберите соответствующий банковский счет. Операции книги банковских счетов, существующие для банковского счета, будут отображаться в области **Книга операций по банку/кассе**.
4. В поле **Дата выписки** укажите дату выписки, полученной из банка.
5. В поле **Конечное сальдо выписки** укажите сальдо из банковской выписки.
6. При наличии файла банковской выписки, выберите действие **Импорт банковской выписки**.
7. Найдите файл, а затем нажмите кнопку **Открыть** для импорта банковских транзакций в строки окна **Выверка банковского счета**.

## <a name="to-fill-bank-reconciliation-lines-with-the-suggest-lines-function"></a>Заполнение строки банковской выверки с помощью функции предложения строк
1. В окне **Выверка банковского счета** выберите действие **Предложить строки**.
2. В поле **Дата начала** укажите самую раннюю дату учета для выверяемых операций книги.
3. В поле **Дата окончания** укажите самую позднюю дату учета для выверяемых операций книги.
4. Установите флажок **Включать платежные документы**, чтобы предложить операции книги платежных документов вместо соответствующих операций книги банковских счетов.
5. Выберите кнопку **ОК**.

## <a name="to-match-bank-statement-lines-with-bank-account-ledger-entries-automatically"></a>Автоматическое сопоставление строк банковских выписок с операциями книги банковских счетов
1. В окне **Выверка банковского счета** выберите **Определять соответствие автоматически**. Откроется окно **Сопоставить банковские операции**.
2. В окне **Отклонение даты транзакции (дни)** укажите период в днях до и после даты учета операции по банковскому счету, в пределах которого функция будет искать соответствующие даты транзакций в банковской выписке.

    Если ввести значение 0 или поле остается пустым, то функция **Сопоставлять автоматически** будет искать даты транзакции, совпадающие с датой учета операции книги банковских счетов.  
3. Выберите кнопку **ОК**.  
Все строки банковских выписок и операций книги банковских счетов, которые можно сопоставить, становятся зелеными, и устанавливается флажок **Применено**.
4. Чтобы удалить сопоставление, выберите строку банковской выписки и выберите действие **Удалить соответствие**.

## <a name="to-match-bank-statement-lines-with-bank-account-ledger-entries-manually"></a>Сопоставление строк банковских выписок с операциями книги банковских счетов вручную
1. В окне **Выверка банковского счета** выберите непримененную строку в области **Строки банковской выписки**.
2. В области **Книга операций по банку/кассе** выберите одну или несколько операций книги банковских счетов, которые можно сопоставить с выделенной строкой банковской выписки. Чтобы выделить несколько строк, нажмите и удерживайте клавишу CTRL.  
3. Выберите действие **Определить соответствие вручную**.

    Шрифт выбранной строки банковской выписки и выбранных операций книги платежей становится зеленым, и устанавливается флажок **Применено** в правой панели.
4. Повторите шаги с 1 по 3 для всех строк банковских выписок, которые не совпадают.
5. Чтобы удалить сопоставление, выберите строку банковской выписки и выберите действие **Удалить соответствие**.

## <a name="to-create-missing-ledger-entries-to-match-bank-transactions-with"></a>Создание отсутствующих операций книги для сопоставления с банковским транзакции
Иногда банковская выписка содержит суммы начисленных процентов или взысканных комиссий. Такие банковские транзакции не удается сопоставить из-за отсутствия соответствующих операций книги в Dynamics NAV. Затем нужно учесть строку журнала для каждой транзакции, чтобы создать соответствующую операцию книги, которую можно сопоставить.

1. В окне **Выверка банковского счета** выберите действие **Переместить в финансовый журнал**.  
2. В окне **Перемещ. банк. выверки в фин. журнал** укажите финансовый журнал, который будет использоваться, а затем нажмите кнопку **ОК**.

    Откроется окно **Финансовый журнал**, содержащее новые строки журнала для всех строк банковской выписки с недостающими операциями книги.
3. Заполните строки журнала соответствующими сведениями, например укажите балансирующий счет. Дополнительные сведения см. в разделе [Работа с финансовыми журналами](ui-work-general-journals.md).  
4. Выберите действие **Учесть**.  
После учета операции перейдите к сопоставлению банковских транзакций.
5. Обновите или заново откройте окно **Выверка банковского счета**. В области **Книга операций по банку/кассе** появится новая операция книги.
6. Сопоставьте строку банковской выписки с операцией книги банковских счетов вручную или автоматически.

## <a name="see-also"></a>См. также  
[Управление банковскими счетами](bank-manage-bank-accounts.md)  
[Настройка банка](bank-setup-banking.md)
