---
title: "Как добавлять в записи ссылки на внешние документы или программы"
description: "Присоединение гиперссылок к документам или веб-сайтам на конкретную запись, например, на клиента или документ."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 903d8710a8c77348e1366d9a9a29b75395887198
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="adding-links-to-websites-documents-or-programs-on-records"></a>Добавление в записи ссылок на веб-сайты, документы или программы
На определенную запись, такую как клиент, документ или заказ на продажу, можно добавить ссылку на внешний документ, веб-сайт или программу. Кроме того, может понадобиться ссылка, при выборе которой будет открываться новое пустое сообщение электронной почты определенному получателю. Страница карточки для некоторых записей, таких как карточки клиентов и поставщиков, предусмотрено поле **Интернет-адрес**, в котором можно ввести URL-адрес. Для включения других ссылок можно воспользоваться методом, описанным в данной статье.

Другим примером может быть получение распечатанных счетов от поставщиков. Можно отсканировать их и сохранить в виде PDF-файлов на сайте SharePoint. Затем в счете покупки в [!INCLUDE[d365fin_md](includes/d365fin_md.md)] можно добавить ссылку на соответствующий счет на сервере SharePoint. Кроме того, в карточке товара можно добавить ссылку на соответствующую страницу в онлайновом каталоге поставщика.
  
## <a name="to-add-a-link-on-a-record"></a>Добавление ссылки на запись   
  
1.  Откройте запись, в которую требуется вложить ссылку, например карточку клиента или заказ на продажу. Если нужно вложить ссылку в конкретную строку, например строку журнала, выделите эту строку.  
  
2.  Выберите действие **Ссылки**, чтобы открыть окно **Ссылки**, в котором отображаются все текущие ссылки, которые добавлены в запись.

3. Чтобы добавить новую ссылку, выберите **+создать**. 
  
4.  В поле **Адрес ссылки** введите

    -   Для связывания с файлом на компьютере или в сети введите полный путь и имя файла, например **C:My Documentsinvoice1.doc**.
    -   Для связывания с веб-сайтом введите интернет-адрес (URL-адрес), например **www.microsoft.com**. 
    -   Для связывания с веб-сайтом введите интернет-адрес (URL-адрес), например **www.microsoft.com**. 
    -   Для связывания с программой введите специальную строку для открытия программы. Например, чтобы открыть OneNote с определенной страницы, введите **onenote:///C:My Documentstest.one**. Или, чтобы открыть Outlook с новым пустым сообщением электронной почты пользователю с определенным псевдонимом, введите следующее: **mailto:тестовый_псевдоним**.  
  
5.  Заполните поле **Описание** сведениями о ссылке.  
  
6.  Нажмите кнопку **Сохранить**.  
  
## <a name="to-delete-a-link-from-a-record"></a>Удаление ссылки из записи  
  
Чтобы удалить ссылку, можно в окне **Ссылки** выбрать **...**, затем **Удалить**.

При удалении одной записи, например строки заказа на продажу, заказа на продажу или клиента, будут удалены все ссылки, вложенные в эту запись. Однако если записи удаляются с помощью пакетного задания, например пакетного задания **Удаление заказов на продажу, по которым выставлены счета**, то ссылки будут по-прежнему храниться в базе данных. Чтобы удалить их из базы данных, необходимо запустить модуль Codeunit **Удаление зависших ссылок на записи**. Чтобы это сделать, выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Удаление зависших ссылок на записи**, затем выберите связанную ссылку.   
  
<!-- ### To run delete orphaned record links  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Data Deletion**, and then choose the related link.  
  
2.  On the **Data Deletion** page, choose **Tasks**, and then choose **Delete Orphaned Record Links**.  -->
  
## <a name="see-also"></a>См. также  
[Работа с [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
