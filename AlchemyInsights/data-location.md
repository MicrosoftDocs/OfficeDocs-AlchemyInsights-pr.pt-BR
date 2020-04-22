---
title: Local dos dados
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: c769c17796d805f88afb4d5b32adb7d4a9bb3ce0
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43655270"
---
# <a name="data-location"></a><span data-ttu-id="ac290-102">Local dos dados</span><span class="sxs-lookup"><span data-stu-id="ac290-102">Data location</span></span>

<span data-ttu-id="ac290-103">Você pode exibir o local do seu locatário no centro de administração ou conectando-se ao Exchange Online por meio do PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ac290-103">You can view the location of your tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="ac290-104">**Centro de administração:**</span><span class="sxs-lookup"><span data-stu-id="ac290-104">**Admin center:**</span></span>
1. <span data-ttu-id="ac290-105">Faça logon no [centro de administração](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="ac290-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="ac290-106">Selecione **configurações** > **perfil da organização**.</span><span class="sxs-lookup"><span data-stu-id="ac290-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="ac290-107">Em **local dos dados**, selecione **Exibir detalhes**.</span><span class="sxs-lookup"><span data-stu-id="ac290-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="ac290-108">**™**</span><span class="sxs-lookup"><span data-stu-id="ac290-108">**PowerShell:**</span></span>
1. <span data-ttu-id="ac290-109">Conecte-se ao Exchange Online usando o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ac290-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="ac290-110">Execute o cmdlet [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) para exibir uma lista das propriedades do locatário.</span><span class="sxs-lookup"><span data-stu-id="ac290-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant's properties.</span></span> 
3. <span data-ttu-id="ac290-111">Observe a propriedade OrganizationId.</span><span class="sxs-lookup"><span data-stu-id="ac290-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="ac290-112">Quando você tem o local de dados do EXO e do SPO, é possível determinar o local dos dados de outros serviços que você pode usar de [onde seus dados estão localizados](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="ac290-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>