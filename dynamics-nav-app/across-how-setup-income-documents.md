---
title: "Практическое руководство. Настройка входящих документов"
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
ms.openlocfilehash: 2bce97c76876c86a576ec6a281a306a46881027c
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-incoming-documents"></a>Практическое руководство. Настройка входящих документов
При создании строк финансового журнала на основании записей входящих документов необходимо выбрать в окне **Настройка входящих документов** шаблон и раздел журнала.

Если пользователи не должны создавать счета или строки финансового журнала на основании записей входящих документов до утверждения документов, необходимо настроить утверждающих в окне **Утверждающие для входящего документа**.

Чтобы преобразовать файлы PDF и изображений в электронные документы, которые можно будет преобразовывать, например, счета покупки в Dynamics NAV, следует сначала настроить функцию OCR и включить эту службу.

Если функция входящих документов настроена, можно использовать различные функции для просмотра квитанций по расходам, управления задачами OCR, а также преобразования входящих файлов документов, вручную и автоматически, в соответствующие документы либо строки журналов. Внешние файлы можно прикреплять на любом этапе обработки, в том числе к учтенным документам и к полученным записям поставщика, клиента и главной книги. Дополнительные сведения см. в разделе [Практическое руководство. Обработка входящих документов](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>Настройка возможности входящих документов
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка входящих документов**, а затем выберите связанную ссылку.
2. Заполните соответствующим образом поля. Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>Настройка утверждающих для записей входящих документов
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка входящих документов**, а затем выберите связанную ссылку.  
2. В окне **Настройка входящих документов** выберите действие **Утверждающие**.

    В окне **Утверждающие для входящего документа** будут показаны все пользователи, настроенные в Dynamics NAV.  
3. Выберите одного или нескольких пользователей, которые могут утвердить входящий документ до создания соответствующей строки в документе или журнале.

После настройки утверждающих в окне **Утверждание для входящего документа** только такие пользователи смогут утверждать входящий документ, если установлен флажок **Требовать утверждение для создания** в окне **Настройка входящих документов**.

**Примечание**. Эта настройка утверждения не связана с рабочими процессами утверждения. Дополнительные сведения см. в разделе [Практическое руководство. Использование рабочих процессов утверждения](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>Настройка службы распознавания
1. В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка OCR**, а затем выберите связанную ссылку.
2. Заполните соответствующим образом поля. Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.


## <a name="to-encrypt-your-login-information"></a>Шифрование реквизитов доступа
Рекомендуется защищать данные для входа, введенные в окне **Настройка OCR**. Можно зашифровать данные на сервере, создав новые или импортировав существующие ключи шифрования, включаемые на экземпляре сервера, подключенном к базе данных.

1. В окне **Настройка OCR** выберите действие **Управление шифрованием**.
2. В окне **Управление шифрованием данных** включите шифрование данных.

## <a name="see-also"></a>См. также  
[Обработка входящих документов](across-process-income-documents.md)  
[Входящие документы](across-income-documents.md)  
[Управление закупками](purchasing-manage-purchasing.md)  
[Работа с Dynamics NAV](ui-work-product.md)
