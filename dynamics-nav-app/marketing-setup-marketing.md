---
title: "Настройка маркетинга и управление контактами"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ddeef7532db8e16652ecab06d1303869531be9b2
ms.contentlocale: ru-ru
ms.lasthandoff: 06/26/2017

---
# <a name="set-up-marketing-and-contact-management"></a>Настройка маркетинга и управление контактами
Прежде чем начинать работу с контактами и маркетинговыми интересами, необходимо принять несколько решений и выполнить определенные действия по настройке управления определенными аспектами контактов в маркетинговой области. Например, можно решить, нужно ли синхронизировать карточку контакта с карточкой клиента, карточкой поставщика и карточкой банковского счета, как определяется серия номеров или какое стандартное обращение должно использоваться при написании сообщений к вашим контактам.

Управление контактами и стратегия определения, привлечения и удержания клиентов помогут оптимизировать бизнес и повысить уровень обслуживания клиентов. Хорошо налаженная система управления контактами также поможет создавать и поддерживать отношения с клиентами. Коммуникации являются ключевым моментом в этих отношениях. Для успешной деятельности организации необходимо выстроить коммуникации с потенциальными и имеющимися клиентами, поставщиками и бизнес-партнерами в соответствии с их запросами. Первым шагом является разработка стратегии и определение способа использования контактной информации в организации. Эту информацию будут просматривать разные группы в организации, поэтому правильно организованная система повысит общую производительность.

Параметры маркетинга и управления контактами задаются в окне **Настройка модуля Маркетинг**. Чтобы открыть окно **Настройка модуля Маркетинг**, в правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Настройка модуля Маркетинг**, а затем выберите связанную ссылку.

## <a name="automatically-copy-specific-information-from-the-contact-companies-to-the-contact-persons"></a>Автоматически скопируйте определенные сведений из контактных организаций в контактные лица.
Иногда информация о контактных организациях совпадает с информацией о контактных лицах, работающих в этих организациях, например подробный адрес. В разделе **Наследование** окна **Настройка модуля Маркетинг** можно указать, что приложение должно автоматически копировать определенные поля из карточки контактной организации в карточку контактного лица каждый раз при создании контактного лица для контактной организации. Например, можно скопировать код менеджера, подробный адрес (адрес, адрес 2, город, почтовый индекс и страну), сведения о связи (номер факса, телекс, номера телефона) и другую информацию.

При изменении одного из этих полей в карточке контактной организации программа автоматически изменит соответствующее поле в карточке контактного лица (если в карточке данного контактного лица это поле не было изменено вручную).

Дополнительные сведения см. в разделе [Практическое руководство. Создание контактных лиц](marketing-how-create-contact-persons.md).

## <a name="use-predefined-defaults-on-new-contacts"></a>Использование заранее определенных значений по умолчанию для новых контактов
Можно выбрать автоматическое назначение приложением определенного кода языка, кода территории, кода менеджера и кода страны/региона по умолчанию каждому вновь создаваемому контакту. Также можно ввести стандартный код цикла продажи, который будет автоматически присваиваться программой каждой новой создаваемой возможности.

Наследование полей переписывает установленные по умолчанию значения. Например, если по умолчанию установлен английский язык, а язык контактной организации немецкий, программа автоматически назначит немецкий язык кодом языка для контактных лиц, регистрируемых для данной организации.

<!--You can also setup a default salutation that the program automatically assigns to your contacts. You can use these salutations in your interaction template attachments (for example, Microsoft Word documents). When setting up a default salutation, you can enter a salutation text and a salutation format. For example, if the salutation text is Dear, and the salutation format is Salutation Text + Title + Name, the program will automatically enter Dear Mr. John Smith as a salutation for a contact called John Smith.-->

## <a name="automatically-record-interactions"></a>Автоматическая запись взаимодействий
Dynamics NAV может автоматически регистрировать документы покупки и продажи как взаимодействия (например, заказы, счета, накладные и т. д.), так же как и адреса электронной почты, телефонные звонки и титульные листы.

Дополнительные сведения см. в разделе [Автоматическая регистрация взаимодействий с контактами](marketing-auto-record-interactions.md).

## <a name="synchronize-contacts-with-customers-and-more"></a>Синхронизация контактов с заказчиками и т. д.
Для того, чтобы синхронизировать карточку контакта с карточкой клиента, следует ввести код бизнес отношения для клиентов, поставщиков и банковских счетов. Например, связать контакт с существующим клиентом можно, только если в окне **Настройка модуля Маркетинг** выбран код бизнес отношения для клиентов.

Дополнительные сведения см. в разделе [Синхронизация контактов с клиентами, поставщиками и банковскими счетами](marketing-synchronize-contacts-customers-vendors-bank-accounts.md).

## <a name="assign-a-number-series-to-contacts-and-opportunities"></a>Назначение серии номеров контактам и возможностям
Можно настроить серии номеров для нумерации контактов и возможностей. Если настроены серии номеров для контактов, то при создании контакта и нажатии клавиши ВВОД в поле "Номер" в карточке контакта программа автоматически вводит следующий свободный номер контакта.

Дополнительные сведения о сериях номеров см. в разделе [Создание серий номеров](ui-create-number-series.md).

## <a name="search-for-duplicate-contacts-when-contacts-are-created"></a>Поиск повторяющихся контактов при создании контактов
Может быть выбран автоматический поиск дубликатов программой каждый раз, когда создается контактная организация или ручной поиск после создания контактов. Можно также выбрать автоматическое обновление строк поиска при каждом изменении контактной информации или создании контакта. Имеется возможность установить процент совпадений, то процент совпадения строк двух контактов, требуемый для того, чтобы программа рассматривала эти контакты как дубликаты.

## <a name="set-up-email-logging"></a>Настройка регистрации эл.почты
Можно обмениваться сообщениями электронной почты с контактами, клиентами, поставщиками и т. п. Отправлять и получать сообщения электронной почты можно либо из приложения, либо из Outlook. Чтобы обмениваться сообщениями электронной почты и обеспечить их хранение в системе и постановку в очередь, необходимо сначала настроить некоторые параметры, такие как временной интервал для проверки наличия сообщений для обработки, имя профиля регистрации электронной почты и т. д.

## <a name="see-also"></a>См. также
[Управление контактами](marketing-contacts.md)  
