---
title: "Управление документами, удаление или сжатие документов"
description: "Можно хранить исторические данные или удалить их."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 89e541c7d38d26204c403636e4df11b7468bffa9
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="manage-documents"></a>Управление документами
Исполнителю главной роли, например администратору приложения, приходится постоянно иметь дело с накапливающимися архивными документами (удалять или сжимать их).  

## <a name="delete-documents"></a>Удаление документов
В определенных ситуациях может возникнуть потребность в удалении заказов на покупку с уже выставленными счетами, которые ещё не были удалены. В [!INCLUDE[d365fin](includes/d365fin_md.md)] выполняется проверка наличия для удаленных заказов на покупку полностью выставленных счетов. Невозможно удалить заказы, на которые не полностью выставлены счета и которые не полностью получены.  

Возвраты обычно удаляются после выставления по ним счета. Когда счет учтен, он переносится в окно **Учтенная кредит-нота покупки**. Если установлен флажок **Возврат поставки по кредит-ноте** в окне **Настройка модуля покупок**, счет переносится в окно **Учтенный возврат поставки**. Можно удалить документы с помощью пакетного задания **Удаление занесенных на счет возвратов покупки**. Перед удалением пакетное задание проверяет, полностью ли отгружены заказы на возврат покупки и выставлены ли по ним счета.  

Общие заказы на покупку не удаляются после обработки и выставления счёта по всем связанным заказам на покупку. Можно удалить подобные заказы с помощью пакетного задания **Удалить общие заказы на покупку, по которым выставлены счета**.  

Сервисные заказы, учтенные в счетах, обычно удаляются автоматически после выставления по ним счетов в полном объеме. Во время учета счета в окне **Учтенные сервисные счета** создается соответствующая запись. Учтенный документ можно просматривать в окне **Учтенный сервисный счет**.  

Однако сервисные заказы не удаляются автоматически, если общее количество по заказу было учтено не из самого заказа, а из окна **Сервисный счет**. В этом случае может понадобиться удалить вручную заказы, по которым выставлены счета и которые не были удалены программой. Это можно выполнить путем запуска пакетного задания **Удалить серв. заказы, по кот. выст. сч.**.  

## <a name="see-also"></a>См. также  
[Настройка и администрирование в Dynamics NAV](admin-setup-and-administration.md)  

