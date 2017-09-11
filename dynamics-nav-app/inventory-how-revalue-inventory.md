<properties
                pageTitle="Практическое руководство. Переоценка запасов| Dynamics NAV"
                description="Описывается, как повысить или понизить стоимость одного или нескольких товаров в запасах путем учета текущей вычисленной стоимости."
                services="project-madeira"
                documentationCenter=""
                authors="SorenGP"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="11/07/2016"
    ms.author="SorenGP" />


# <a name="how-to-revalue-inventory"></a><span data-ttu-id="12d49-103">Практическое руководство. Переоценка запасов</span><span class="sxs-lookup"><span data-stu-id="12d49-103">How to: Revalue Inventory</span></span>   
<span data-ttu-id="12d49-104">Чтобы повысить или понизить стоимость изделия или конкретной учтенной товарной операции, нужно воспользоваться журналом переоценки.</span><span class="sxs-lookup"><span data-stu-id="12d49-104">If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.</span></span>

## <a name="to-revalue-inventory"></a><span data-ttu-id="12d49-105">Переоценка запасов</span><span class="sxs-lookup"><span data-stu-id="12d49-105">To revalue inventory</span></span>
1. <span data-ttu-id="12d49-106">В правом верхнем углу выберите значок **Поиск страницы или отчета**, введите **Журнал переоценки**, затем выберите связанную ссылку.</span><span class="sxs-lookup"><span data-stu-id="12d49-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Revaluation Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="12d49-107">Выберите действие **Расчет стоимости запасов**.</span><span class="sxs-lookup"><span data-stu-id="12d49-107">Choose the **Calculate Inventory Value** action.</span></span>
3. <span data-ttu-id="12d49-108">В окне **Расчет стоимости запасов** заполните требуемые поля.</span><span class="sxs-lookup"><span data-stu-id="12d49-108">In the **Calculate Inventory Value** window, fill in the fields as necessary.</span></span> <span data-ttu-id="12d49-109">Выберите поле для чтения краткого описания поля или ссылки на дополнительную информацию.</span><span class="sxs-lookup"><span data-stu-id="12d49-109">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="12d49-110">Выберите кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="12d49-110">Choose the **OK** button.</span></span>
5. <span data-ttu-id="12d49-111">В каждой строке в окне **Журнал переоценки** в поле **Себестоимость единицы (переоценка)** введите новую себестоимость единицы.</span><span class="sxs-lookup"><span data-stu-id="12d49-111">On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost.</span></span> <span data-ttu-id="12d49-112">Можно также ввести новую общую сумму в поле **Стоимость запасов (переоценка)**.</span><span class="sxs-lookup"><span data-stu-id="12d49-112">Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.</span></span>

    <span data-ttu-id="12d49-113">Соответствующие поля обновляются автоматически.</span><span class="sxs-lookup"><span data-stu-id="12d49-113">The relevant fields are automatically updated.</span></span> <span data-ttu-id="12d49-114">Следует учесть, что в поле **Сумма** отражается фактическое изменение в значении склада для выбранных учтенных товарных операций.</span><span class="sxs-lookup"><span data-stu-id="12d49-114">Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry.</span></span> <span data-ttu-id="12d49-115">Там подсчитывается разница между полями **Стоимость запасов (расчетная)** и **Стоимость запасов (переоценка)**.</span><span class="sxs-lookup"><span data-stu-id="12d49-115">It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.</span></span>

6. <span data-ttu-id="12d49-116">После того как будут заполнены все строки в журнале переоценки, выберите действие **Учет**.</span><span class="sxs-lookup"><span data-stu-id="12d49-116">When you have completed all lines in the revaluation journal, choose the **Post** action.</span></span>

<span data-ttu-id="12d49-117">Создаются новые операции стоимости, которые отражают учтенную переоценку.</span><span class="sxs-lookup"><span data-stu-id="12d49-117">New value entries are now created to reflect the revaluations that you have posted.</span></span> <span data-ttu-id="12d49-118">Новые значения можно просмотреть в соответствующей карточке товара.</span><span class="sxs-lookup"><span data-stu-id="12d49-118">You can see the new values on the respective item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="12d49-119">См. также</span><span class="sxs-lookup"><span data-stu-id="12d49-119">See Also</span></span>
[<span data-ttu-id="12d49-120">Управление запасами</span><span class="sxs-lookup"><span data-stu-id="12d49-120">Manage Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="12d49-121">Управление продажами</span><span class="sxs-lookup"><span data-stu-id="12d49-121">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="12d49-122">Управление закупками</span><span class="sxs-lookup"><span data-stu-id="12d49-122">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="12d49-123">Работа с Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="12d49-123">Work With Dynamics NAV</span></span>](ui-work-product.md)

