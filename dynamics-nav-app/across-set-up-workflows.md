---
title: "Настройка рабочих процессов"
description: "Можно настроить и использовать рабочие процессы, связывающие задачи бизнес-процесса, выполняемые различными пользователями. Системные задачи, такие как автоматический учет, могут включаться в качестве шагов рабочего процесса, предшествующих задачам пользователя или выполняемых после них. Типичные шаги рабочего процесса – запрос и выдача разрешения на создание новых записей."
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
ms.openlocfilehash: 060a402b54fa59110986907de2d6c64ba079db30
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-workflows"></a>Настройка рабочих процессов
Можно настроить и использовать рабочие процессы, связывающие задачи бизнес-процесса, выполняемые различными пользователями. Системные задачи, такие как автоматический учет, могут включаться в качестве шагов рабочего процесса, предшествующих задачам пользователя или выполняемых после них. Типичные шаги рабочего процесса – запрос и выдача разрешения на создание новых записей. Дополнительные сведения см. в разделе [Использование рабочих процессов](across-use-workflows.md).  

 Прежде чем начать использование рабочих процессов, необходимо произвести настройку пользователей рабочих процессов и утверждающих лиц, определить, как пользователи будут получать уведомления о шагах рабочих процессов, а затем создать рабочие процессы (возможно, перед этим потребуется настройка кода).  

 В окне **Рабочий процесс** создайте рабочий процесс, указав в строках связанные с ним шаги. Каждый шаг состоит из события рабочего процесса, ограниченного условиями события, и отклика рабочего процесса, ограниченного параметрами отклика. Шаги рабочего процесса заполняются посредством заполнения полей в строках рабочего процесса из фиксированных списков значений события и отклика, представляющих сценарии, которые поддерживаются кодом приложения.  

 Если бизнес-сценарий требует события или отклика рабочего процесса, которые не поддерживаются, партнеру Майкрософт придется реализовать их, настроив код приложения. Дополнительные сведения см. в разделе [Пошаговое руководство. Реализация новых и событий и отзывов рабочего процесса](https://msdn.microsoft.com/en-us/library/mt574349.aspx) на сайте MSDN.

 В следующей таблице приводится последовательность задач со ссылками на разделы, в которых они описываются.  

|**Действие**|**Смотрите**|  
|------------|-------------|  
|Настройка пользователей рабочего процесса и групп пользователей.|[Практическое руководство. Настройка пользователей рабочих процессов](across-how-to-set-up-workflow-users.md)|  
|Настройте пользователей рабочего процесса, участвующих в рабочих процессах утверждения.|[Практическое руководство. Настройка утверждающих пользователей](across-how-to-set-up-approval-users.md)|  
|Укажите, каким образом пользователи рабочего процесса получают уведомление о шагах рабочего процесса, включая запросы на утверждение.|[Настройка уведомлений рабочего процесса](across-setting-up-workflow-notifications.md)|  
|Задает, когда пользователи будут получать уведомления и следует ли суммировать уведомления за какой-либо период для уменьшения числа уведомлений.|[Практическое руководство. Определение сроков и порядка получения уведомлений пользователями](across-how-to-specify-when-and-how-to-receive-notifications.md)|  
|Настройка структуры и общего содержимого сообщений по электронной почте о новых уведомлениях рабочего процесса либо экспорт, изменение и реимпорт существующих, шаблонов.|[Практическое руководство. Управление шаблонами уведомлений](across-how-to-manage-notification-templates.md)|  
|Настройте SMTP-сервер для включения передачи сообщений электронной почты в [!INCLUDE[d365fin](includes/d365fin_md.md)] и из него.|[Практическое руководство. Настройка электронной почты](madeira-how-setup-email.md)|
|Определите различные шаги рабочего процесса, связав события рабочего процесса с откликами рабочего процесса.|[Практическое руководство. Создание рабочих процессов](across-how-to-create-workflows.md)|  
|Используйте шаблоны рабочих процессов для создания рабочих процессов.|[Практическое руководство. Создание рабочих процессов из шаблонов рабочих процессов](across-how-to-create-workflows-from-workflow-templates.md)|  
|Общий доступ к рабочим процессам с другими базами данных [!INCLUDE[d365fin](includes/d365fin_md.md)].|[Практическое руководство. Экспорт и импорт рабочих процессов](across-how-to-export-and-import-workflows.md)|  
|Изучение принципов настройки рабочего процесса для утверждения документов продажи, следуя единой комплексной процедуре.|[Пошаговое руководство. Настройка и использование рабочего процесса утверждения покупки](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md)|  
|Добавление поддержки для бизнеса сценария, для которого требуются новые события рабочих процессов или отклики путем настройки кода приложения.|[Пошаговое руководство. Реализация новых и событий и отзывов рабочего процесса](https://msdn.microsoft.com/en-us/library/mt574349.aspx) на сайте MSDN.|  

## <a name="see-also"></a>См. также  
 [Использование рабочих процессов](across-use-workflows.md)   
 [Рабочий процесс](across-workflow.md)   
 [Пошаговое руководство. Настройка и использование рабочего процесса утверждения покупки](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md)  
 [Работа с Dynamics NAV](ui-work-product.md)

