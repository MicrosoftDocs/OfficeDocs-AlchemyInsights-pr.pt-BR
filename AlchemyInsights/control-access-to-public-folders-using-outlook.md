---
title: Controlar o acesso às pastas públicas usando o Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: f528044ca7f6f2ee2812f9f831093c44eca26fe1
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51816728"
---
# <a name="control-access-to-public-folders-using-outlook"></a><span data-ttu-id="386c5-102">Controlar o acesso às pastas públicas usando o Outlook</span><span class="sxs-lookup"><span data-stu-id="386c5-102">Control access to public folders using Outlook</span></span>

<span data-ttu-id="386c5-103">Para controlar quais usuários podem acessar pastas públicas usando o Outlook:</span><span class="sxs-lookup"><span data-stu-id="386c5-103">To control which users can access public folders using Outlook:</span></span>

1. <span data-ttu-id="386c5-104">Usar o `Set-CASMailbox <mailboxname> -PublicFolderClientAccess $true or $false`</span><span class="sxs-lookup"><span data-stu-id="386c5-104">Use `Set-CASMailbox <mailboxname> -PublicFolderClientAccess $true or $false`</span></span>

<span data-ttu-id="386c5-105">$true: permitir que os usuários acessem pastas públicas no Outlook</span><span class="sxs-lookup"><span data-stu-id="386c5-105">$true: Allow users access public folders in Outlook</span></span>  
<span data-ttu-id="386c5-106">$false: impedir que os usuários acessem pastas públicas no Outlook.</span><span class="sxs-lookup"><span data-stu-id="386c5-106">$false: Prevent user access to public folders in Outlook.</span></span> <span data-ttu-id="386c5-107">Esse é o valor padrão.</span><span class="sxs-lookup"><span data-stu-id="386c5-107">This is the default value.</span></span>  

2. `Set-OrganizationConfig -PublicFolderShowClientControl $true`

<span data-ttu-id="386c5-108">Observação: este procedimento pode controlar somente as conexões com a área de trabalho do Outlook para clientes Windows.</span><span class="sxs-lookup"><span data-stu-id="386c5-108">Note: This procedure can only control connections with Outlook desktop for Windows clients.</span></span> <span data-ttu-id="386c5-109">Os usuários podem continuar acessando as pastas públicas usando o OWA ou o Outlook para Mac.</span><span class="sxs-lookup"><span data-stu-id="386c5-109">Users can continue accessing public folders using OWA or Outlook for Mac.</span></span>

<span data-ttu-id="386c5-110">Para saber mais, confira [Conexões controladas para pastas públicas no Outlook](https://aka.ms/controlpf).</span><span class="sxs-lookup"><span data-stu-id="386c5-110">For more information, see [Controlled Connections to Public Folders in Outlook](https://aka.ms/controlpf) for more information.</span></span>
