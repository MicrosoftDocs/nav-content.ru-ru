---
title: "Практическое руководство. Выверка платежей клиентов вручную из списка неоплаченных документов продажи"
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
ms.openlocfilehash: c03503324ba74ee265a8a432b7df416198b255b0
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-customer-payments-manually-from-a-list-of-unpaid-sales-documents"></a>Практическое руководство. Выверка платежей клиентов вручную из списка неоплаченных документов продажи
Когда ваши клиенты вносят оплату на ваш электронный банковский счет, необходимо применить каждую оплаченную сумму к связанному документу продажи, а затем учесть платеж и обновить главную книгу, клиента и банковские учтённые операции.

**Примечание**. Те же задачи, включая платежи поставщикам, можно выполнять в окне **Журнал выверки платежей** с помощью функций импорта банковской выписки, автоматического применения и выверки банковского счета. Дополнительные сведения см. в разделе [Выверка платежей с использованием автоматического применения](receivables-how-reconcile-payments-auto-application.md).

Окно **Регистрация платежей** предназначено для работы с задачами, относящимися к балансированию внутренних счетов за счет использования фактических показателей поступления денежных средств для эффективного получения платежей от клиентов. Этот инструмент обработки платежей позволяет выполнять быструю проверку и учет отдельных или единовременных платежей, обработку уцененных платежей и поиск конкретных неоплаченных документов, по которым проведена оплата.

Платежи от разных клиентов, которые имеют различные даты оплаты, должны учитываться как отдельные платежи. Платежи от одного и того же клиента, которые имеет одну и ту же дату оплаты, могут быть учтены как суммарный платеж. Это полезно, например если клиент выполнил один платеж, который охватывает несколько счетов продажи.

## <a name="to-set-up-the-payment-registration-journal"></a>Настройка журнала регистрации платежей
Поскольку можно учитывать разные типы платежей на разных балансирующих счетах, необходимо выбрать балансирующий счет в окне **Настройка регистрации платежей** перед началом обработки платежей клиентов. Если при учете всегда используется один и тот же балансирующий счет, то его можно настроить как счет по умолчанию и не выполнять данное действие каждый раз при открытии окна **Регистраций платежей**.
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка регистрации платежей**, а затем выберите связанную ссылку. Либо в окне **Регистрация платежей** выберите действие **Настройка**.
2. Заполните поля в окне **Настройка регистрации платежей**. Выберите поле для чтения краткого описания поля или ссылки на связанную информацию.  

## <a name="to-reconcile-payments-individually"></a>Выверка платежей по одному
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.  
2. Установите флажок **Оплата выполнена** в строке, представляющей учтенный документ, по которому произведен платеж.

    Если установлен флажок **Автозаполнение даты получения** в окне **Настройка регистрации платежей**, то в поле **Дата получения** вводится рабочая дата.
3. В поле **Дата получения** введите дату, когда был осуществлен платеж. Эта дата может отличаться от рабочей даты.  
4. В поле **Полученная сумма** укажите оплаченную сумму.

    Для полных платежей она совпадает с суммой в поле **Сумма остатка** в строке. Для частичных платежей это значение ниже суммы в поле **Сумма остатка** в строке.
5. Повторите шаги с 2 по 4 для других строк, представляющих учтенные документы, по которым произведены оплаты.
6. Выберите действие **Учесть платежи**.

Сведения по платежу учитываются для документов, представленных строками, в которых установлен флажок **Оплата выполнена**.

Оплаты операции учитываются в Главной книге, банке и счетах клиентов. Каждый платеж применяется к связанному учтенному документу продажи.

## <a name="to-reconcile-lump-payments"></a>Выверка единовременных платежей
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.
2. Установите флажок **Оплата выполнена** в строках, представляющих учтенные документы покупателя, по которым произведен единовременный платеж.

    **Примечание**. Клиент в поле **Название** должен быть одинаковым во всех строках, которые будут учтены как единовременный платеж.

    Если установлен флажок **Автозаполнение даты получения** в окне **Настройка регистрации платежей**, то в поле **Дата получения** вводится рабочая дата.
3. В поле **Дата получения** введите дату, когда был осуществлен платеж. Эта дата может отличаться от рабочей даты.

    **Примечание**. Эта дата должна быть одинаковой во всех строках, которые будут учтены как единовременный платеж.
4. В поле **Полученная сумма** введите суммы в нескольких строках, которые суммируют полную сумму оплаты.

    **Совет**. Постарайтесь учесть максимально возможное количество полных платежей в общей сумме. Введите суммы, совпадающие с суммой в поле **Сумма остатка** в как можно большем числе строк.
5. Повторите шаги с 2 по 4 в других строках, представляющих учтенные документы одного и того же клиента, по которым произведен суммарный платеж.  
6. Выберите действие **Учет в качестве единовременного платежа**. Введенные сведения по платежу учитываются для документов, представленных строками, в которых установлен флажок **Оплата выполнена**.

Операции платежей учитываются в на счетах главной книги, банка и клиента. Каждый платеж применяется к связанному учтенному документу продажи.

Если платеж в банке не представлена строкой в окне **Регистрация платежей**, это может означать, что соответствующий документ еще не был учтен. В этом случае можно использовать функцию поиска для ускоренного нахождения документа и его учета, чтобы выполнить обработку оплаты. Дополнительные сведения см. в разделе "Практическое руководство. Поиск неоплаченных документов в процессе выверки платежей клиентов вручную".

Если платеж в банке не представлена каким-либо документом в Dynamics NAV, можно открыть строку заполненного финансового журнала из окна **Регистрация платежей** для учета платежа непосредственно на балансирующем счете без применения платежей к документу. Кроме того, может возникнуть необходимость зарегистрировать платеж в журнале до тех пор, пока не будет распознан источник платежа. Дополнительные сведения см. в разделе "Запись либо учет платежа без связанного документа".

## <a name="to-customer-payments-with-discounts-manually"></a>Выверка платежей клиентов со скидками вручную
Если пользователь и клиент утвердили скидку оплаты, то суммы оплаты могут быть меньше суммы счетов, если оплата производится до даты согласованной скидки.

В этой процедуре объясняются четыре различные процедуры учета платежей со скидками в окне **Регистрация платежей**.

- Сумма оплаты равна оставшейся сумме с учетом скидки, а дата оплаты предшествует дате скидки. Платеж учитывается как есть.
- Сумма оплаты равна оставшейся сумме с учетом скидки, но дата оплаты следует за датой скидки. Платеж учитывается частично. Документ остается открытым для сбора/выплаты суммы остатка. Кроме того, дату скидки можно задать позже, чтобы разрешить платеж в полной мере.
- Сумма оплаты ниже оставшейся суммы с учетом скидки. Платеж учитывается частично. Документ остается открытым для сбора/выплаты суммы остатка.
- Сумма оплаты выше оставшейся суммы с учетом скидки. Платежи учитываются как есть. Только сумма остатка учитывается. Дополнительная сумма кредитуется клиенту.

## <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-and-where-the-payment-date-is-before-the-discount-date"></a>Обработка суммы платежа, равной оставшейся сумме с учетом скидки, для которой дата оплаты предшествует дате скидки
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.  
2. Введите сумму платежа в поле **Полученная сумма**. Сумма равна сумме в поле **Остаток суммы после скидки**.

    Автоматически устанавливается флажок **Оплата выполнена**, и в поле **Дата получения** вносится рабочая дата.
3. В поле **Дата получения** введите дату платежа. Дата предшествует дате в поле **Дата скидки оплаты**.
4. Удостоверьтесь, что поле **Сумма остатка** содержит нулевое значение (0).  
5. Выберите действие **Учет платежей**, чтобы полностью учесть платеж на счетах главной книги, банка и клиента.

Соответствующий документ закрывается.

## <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-but-where-the-payment-date-is-after-the-discount-date"></a>Обработка суммы платежа, равной оставшейся сумме с учетом скидки, но для которой дата оплаты наступает позднее даты скидки
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.  
2. Введите сумму платежа в поле **Полученная сумма**. Сумма равна сумме в поле **Остаток суммы после скидки**.

    Автоматически устанавливается флажок **Оплата выполнена**, и в поле **Дата получения** вносится рабочая дата.
3. В поле **Дата получения** введите дату оплаты, которая позже даты в поле **Дата скидки оплаты**. Поля дат меняют шрифт на красный, а внизу окна отображается сообщение об ошибке.

    **Совет**. Если требуется сделать исключение и предоставить скидку, несмотря на просрочку платежа, выполните следующие действия:  
4. Выберите действие **Сведения**.  
5. В окне **Сведения регистрации платежей** в поле **Дата скидки оплаты** на экспресс-вкладке **Скидка оплаты** введите дату, которая позже даты в поле **Дата получения** в окне **Регистрация платежей**.

    Сообщение об ошибке и красный шрифт исчезнут, и можно продолжить обработку оплаты со скидкой.
6. Удостоверьтесь, что поле **Сумма остатка** содержит полную сумму, которая подлежит оплате по счету.  
7. Выберите действие **Учет платежей**, чтобы частично учесть платеж на счетах главной книги, банка и клиента.  
Соответствующий документ остается открытым.

## <a name="to-process-a-payment-that-is-lower-than-the-remaining-discounted-amount"></a>Обработка суммы платежа, которая ниже оставшейся суммы с учетом скидки
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.  
2. Введите сумму платежа в поле **Полученная сумма**. Сумма меньше суммы в поле **Остаток суммы после скидки**.

    Автоматически устанавливается флажок **Оплата выполнена**, и в поле **Дата получения** вносится рабочая дата.
3. В поле **Дата получения** введите дату платежа. Дата предшествует дате в поле **Дата скидки оплаты**.
4. Удостоверьтесь, что поле **Сумма остатка** содержит сумму со скидкой, которая подлежит оплате.  
5. Выберите действие **Учет платежей**, чтобы частично учесть платеж на счетах главной книги, банка и клиента.  
Соответствующий документ остается открытым.

## <a name="to-process-a-payment-that-is-more-than-the-remaining-discounted-amount"></a>Обработка суммы платежа, которая выше оставшейся суммы с учетом скидки
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.  
2. Введите сумму платежа в поле **Полученная сумма**. Сумма больше суммы в поле **Остаток суммы после скидки**.

    Автоматически устанавливается флажок **Оплата выполнена**, и в поле **Дата получения** вносится рабочая дата.
3. В поле **Дата получения** введите дату платежа. Дата предшествует дате в поле **Дата скидки оплаты**.
4. Удостоверьтесь, что поле **Сумма остатка** содержит нулевое значение (0).  
5. Выберите действие **Учет платежей**, чтобы полностью учесть платеж на счетах главной книги, банка и клиента.

Соответствующий документ закрывается, а задолженность клиента увеличивается на неоплаченную сумму.

## <a name="to-find-a-specific-sales-document-that-is-not-fully-invoiced"></a>Поиск определенного документа продажи с неполностью выставленным счетом
Окно **Регистрация платежей** предназначено для работы с задачами, необходимыми для балансировки внутренних счетов по фактическим показателям денежных поступлений для эффективного получения платежей от клиентов и предоставления оплаты поставщикам. Окно отображает ожидаемые входящие платежи в виде строк, которые представляют документы продажи, где сумма должна быть оплачена.

Обычно при совершении платежа, зарегистрированного в банке или другим способом, связанный документ продажи или покупки представлен в виде строки в окне **Регистрация платежей**, так как рассматриваемый документ ожидает учета платежа относительно неуплаченной суммы. Однако иногда платеж, который был совершен, не отображается в строке окна **Регистрация платежей**. Чаще всего это происходит потому, что для соответствующего документа не был выставлен полный счет.

В окне **Поиск документов** можно выполнять поиск среди документов, на которые не полностью выставлены счета. Поиск можно выполнять по одному или нескольким из следующих критериев:

- Документ Но.
- Сумма или диапазон сумм

В следующей процедуре объясняется, как найти конкретный документ с использованием критериев поиска.

1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.
2. Установив указатель в любую строку, выберите действие **Поиск документов**.
3. В окне **Поиск документов** введите значение поиска в поле **Номер документа**. .

    **Примечание**. Значение, которое вводится в этом поле, заключается в скрытые символы подстановки. Это означает, что функция выполняет поиск всех номеров документов, содержащих введенное значение.
4. В поле **Сумма** введите конкретную сумму, имеющуюся в документе, который необходимо найти.  
5. В поле **Сумма отклонения, %** введите процентное значение для определения диапазона сумм, которые необходимо искать, чтобы найти открытый документ.

    Если ввести 10, то функция будет искать суммы на 10 процентов меньше и на 10 процентов больше значения в поле **Сумма**.
6. Выберите действие **Поиск**.

Функция поиска выполняет поиск среди документов, по которым не полностью выставлены счета, на основании заданных критериев.

Если критериям поиска отвечают один или несколько документов, открывается окно **Результат поиска документов**, в котором отображаются строки, представляющие эти документы. Каждая строка содержит номер документа, описание и сумму, что позволяет легко найти определенный документ, например на основе информации банковской выписки.

Если платеж в банке не представлена каким-либо документом в Dynamics NAV, можно открыть строку заполненного финансового журнала из окна **Регистрация платежей** для учета платежа непосредственно на балансирующем счете без применения платежей к документу. Кроме того, может возникнуть необходимость зарегистрировать платеж в журнале до тех пор, пока не будет распознан источник платежа.

##<a name="to-record-or-post-a-payment-without-a-related-document"></a>Запись либо учет платежа без связанного документа
Если платеж в банке не представлена каким-либо документом в Dynamics NAV, можно открыть строку заполненного финансового журнала из окна **Регистрация платежей** для учета платежа непосредственно на балансирующем счете без применения платежей к документу. Кроме того, может возникнуть необходимость зарегистрировать платеж в журнале до тех пор, пока не будет уточнен источник платежа.

1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Регистрация платежей**, а затем выберите связанную ссылку.  
Перейти к регистрации незадокументированного платежа.  
2. Выберите действие **Финансовый журнал**.

    Откроется окно **Финансовый журнал** с одной строкой, в которую уже внесен балансирующий счет раздела журнала, настраиваемого в окне **Настройка регистрации платежей**.
3. Заполните остальные поля в строке финансового журнала, например сумму и номер клиента или другую информацию из банковской выписки. Дополнительные сведения см. в разделе [Практическое руководство. Работа с финансовыми журналами](ui-work-general-journals.md).

Можно вести учет строки журнала, чтобы обновить итог в балансовом счете. Кроме того, можно оставить строку журнала неучтенной и, возможно, присоединить к ней заметку о том, что платеж требует дополнительного анализа.

Если оставить строку журнала неучтенной, она будет добавлена к значению в поле **Неучтенное сальдо** в нижней части окна **Регистрация платежей**.

## <a name="see-also"></a>См. также
[Управление дебиторской задолженностью](receivables-manage-receivables.md)  
[Управление продажами](sales-manage-sales.md)
