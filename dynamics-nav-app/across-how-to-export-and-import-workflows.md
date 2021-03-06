---
title: "Как экспортировать и импортировать рабочие процессы"
description: "Для передачи рабочих процессов в другие базы данных [!INCLUDE[d365fin](includes/d365fin_md.md)], например для экономии времени при создании рабочих процессов, рабочие процессы можно экспортировать и импортировать."
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
ms.openlocfilehash: 7ce7c6bd83efaacaed53f5d5ca5c2eb1521c0e6e
ms.contentlocale: ru-ru
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-and-import-workflows"></a>Практическое руководство. Экспорт и импорт рабочих процессов
Для передачи рабочих процессов в другие базы данных [!INCLUDE[d365fin](includes/d365fin_md.md)], например для экономии времени при создании рабочих процессов, рабочие процессы можно экспортировать и импортировать.  

 Другой способ быстрого создания рабочих процессов — создание рабочих процессов из шаблонов рабочих процессов. Дополнительные сведения см. в разделе [Практическое руководство. Создание рабочих процессов из шаблонов рабочих процессов](across-how-to-create-workflows-from-workflow-templates.md).  

 В окне **Рабочий процесс** создайте рабочий процесс, указав в строках связанные с ним шаги. Каждый шаг состоит из события рабочего процесса, ограниченного условиями события, и отклика рабочего процесса, ограниченного параметрами отклика. Шаги рабочего процесса заполняются посредством заполнения полей в строках рабочего процесса из фиксированных списков значений события и отклика, представляющих сценарии, которые поддерживаются кодом приложения. Дополнительные сведения см. в разделе [Практическое руководство. Создание рабочих процессов](across-how-to-create-workflows.md).  

## <a name="to-export-a-workflow"></a>Экспорт рабочего процесса  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Рабочие процессы**, затем выберите связанную ссылку.  
2.  Выберите рабочий процесс, затем выберите действие **Экспортировать в файл**.  
3.  В диалоговом окне **Экспорт файла** нажмите кнопку **Сохранить**.  
4.  В окне **Экспорт** выберите расположение файла и затем нажмите кнопку **Сохранить**.  

## <a name="to-import-a-workflow"></a>Импорт рабочего процесса  
1.  Выберите значок ![Поиск страницы или отчета](media/ui-search/search_small.png "Значок поиска страницы или отчета"), введите **Рабочие процессы**, затем выберите связанную ссылку.  
2.  Выберите действие **Импорт из файла**.  
3.  В окне **Импорт** выберите XML-файл, содержащий рабочий процесс, а затем нажмите кнопку **Открыть**.  

> [!CAUTION]  
>  Если код рабочего процесса уже есть в базе данных, шаги рабочего процесса будут перезаписаны шагами в импортированном рабочем процессе.  

## <a name="see-also"></a>См. также  
 [Практическое руководство. Создание рабочих процессов](across-how-to-create-workflows.md)   
 [Практическое руководство. Создание рабочих процессов из шаблонов рабочих процессов](across-how-to-create-workflows-from-workflow-templates.md)   
 [Практическое руководство. Просмотр архивированных экземпляров шагов рабочих процессов](across-how-to-view-archived-workflow-step-instances.md)   
 [Практическое руководство. Удаление рабочих процессов](across-how-to-delete-workflows.md)   
 [Пошаговое руководство. Настройка и использование рабочего процесса утверждения покупки](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md)   
 [Настройка рабочих процессов](across-set-up-workflows.md)   
 [Использование рабочих процессов](across-use-workflows.md)   
 [Рабочий процесс](across-workflow.md)   

