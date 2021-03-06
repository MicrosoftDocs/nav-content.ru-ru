---
title: "Настройка преобразования банковских данных"
description: "Вы можете настроить банковские счета для отслеживания транзакций и импорта или экспорта банковских выписок."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: feed, stream, data exchange, AMC, bank file import, bank file export, re-export, bank transfer, AMC, bank data conversion service, funds transfer
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d0ee64e4b1426d6ce9d8b8052919e4afcae326d5
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-the-bank-data-conversion-service"></a>Практическое руководство. Настройка службы конвертации банковских данных
Глобальный поставщик услуг преобразования платежной информации в любой формат данных, требуемый банком, подключен и готов к включению в [!INCLUDE[d365fin](includes/d365fin_md.md)]. В [!INCLUDE[d365fin](includes/d365fin_md.md)] он называется службой конвертации банковских данных.

Вы можете экспортировать строки платежей из окна **Журнал платежей** в файл или поток данных, который затем можно передать в банк для автоматической обработки, чтобы не проводить электронные платежи по одному. Дополнительные сведения см. в разделе [Практическое руководство. Экспорт платежей в банковский файл](payables-how-export-payments-bank-file.md).

Можно импортировать файлы банковской выписки в окно **Журнал выверки платежей** с помощью службы конвертации банковских данных для конвертации файла, полученного от банка, в поток данных, который может импортировать [!INCLUDE[d365fin](includes/d365fin_md.md)]. Дополнительные сведения см. в разделе [Практическое руководство. Автоматическое применение платежей и выверка банковских счетов](receivables-apply-payments-auto-reconcile-bank-accounts.md).

Для импорта или экспорта банковских файлов следует настроить собственный банковский счет и банковские счета поставщиков. Дополнительные сведения см. в разделе [Практическое руководство. Настройка банковских счетов](bank-how-setup-bank-accounts.md).

> [!NOTE]  
>   Служба конвертации банковских данных может налагать ограничение на число строк, экспортируемых в одном файле. Если превысить это ограничение, будет выдано сообщение об ошибке. Рекомендуется, чтобы файлы банковских выписок не превышали 1000 строк, поскольку время обработки в службе конвертации банковских данных может значительно увеличиться.

## <a name="to-sign-your-company-up-for-the-bank-data-conversion-service"></a>Регистрация компании на получение услуг преобразования банковских данных
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка службы преобр. банковских данных**, а затем выберите связанную ссылку.  
2. Откроется окно **Настройка службы преобр. банковских данных** с тремя полями, предварительно заполненными соответствующими URL-адресами поставщика службы преобразования банковских данных .

    > [!NOTE]  
>   В демонстрационной базе денных CRONUS International Ltd. поля "Имя пользователя" и "Пароль" предварительно заполняются демонстрационными данными для входа, которые следует заменить фактическими сведениями об организации при подписке на службу преобразования банковских данных.
3. В поле **URL-адрес регистрации** нажмите кнопку браузера, чтобы открыть страницу регистрации поставщика услуг.  
4. На странице регистрации поставщика службы преобразования банковских данных введите имя пользователя и пароль для подписки организации на обслуживание, а затем пройдите процесс регистрации, как указано поставщиком службы.

    Организация подписана на службу преобразования банковских данных. Затем введите имя пользователя и пароль, указанные для службы в связанных полях настройки в [!INCLUDE[d365fin](includes/d365fin_md.md)].
5. В окне **Настройка службы преобр. банковских данных** в поле **Имя** введите то же значение, которое было введено как имя для входа на странице поставщика услуг на шаге 4.
6. В поле **Пароль** введите то же значение, которое было введено в поле **Пароль** на странице поставщика услуг на шаге 4.

## <a name="to-encrypt-your-login-information"></a>Шифрование реквизитов доступа
Рекомендуется защищать данные для входа, введенные в окне **Настройка службы преобр. банковских данных**. Можно зашифровать данные на сервере [!INCLUDE[d365fin](includes/d365fin_md.md)], создав новые или импортировав существующие ключи шифрования, включаемые на экземпляре сервера [!INCLUDE[d365fin](includes/d365fin_md.md)], подключенном к базе данных.

1. В окне **Настройка службы преобр. банковских данных** выберите действие **Управление шифрованием**.
2. В окне **Управление шифрованием данных** включите шифрование данных.

## <a name="to-view-or-update-the-list-of-currently-supported-bank-data-formats"></a>Просмотр или обновление списка поддерживаемых в настоящее время форматов банковских данных
1. Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Настройка службы преобр. банковских данных**, а затем выберите связанную ссылку.
2. В окне **Настройка службы преобр. банковских данных** выберите **Название банка – Список преобр. данных**, чтобы открыть список наименований банка, представляющих форматы банковских данных, поддерживаемые службой преобразования.
3. На странице **Название банка – Список преобр. данных** выберите **Обновить список названий банков**.

Список форматов банковских данных, поддерживаемых службой преобразования банковских данных, теперь обновлен. Это список названий банков, отфильтрованный по странам и регионам, которые можно выбрать в поле **Название банка - преобразование данных** окна **Карточка банковского счета**.

> [!NOTE]  
>   Обновление поддерживаемых форматов банковских данных также происходит при выборе или вводе значения в поле **Название банка - преобразование данных**.

Вы подписаны на услуги преобразования банковских данных. Продолжите для добавления сведений о регистрации в каждый банковский счет, который будет использовать эту службу.

## <a name="see-also"></a>См. также
[Настройка банковских операций](bank-setup-banking.md)  
[Управление банковскими счетами](bank-manage-bank-accounts.md)  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

