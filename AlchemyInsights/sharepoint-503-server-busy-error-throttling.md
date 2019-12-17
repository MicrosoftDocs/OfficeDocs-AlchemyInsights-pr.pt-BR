---
title: Limitação do SharePoint Online
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: ed3598dc92a7c36c9c9b077db0ab31f63537ef60
ms.sourcegitcommit: 14894a09db1c4101e48ff720d878d1c9f7b1dac8
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/16/2019
ms.locfileid: "40065546"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="bb245-102">Limitação do SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="bb245-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="bb245-103">Os usuários podem receber um erro de servidor 503 está ocupado ao tentar navegar até sites do SharePoint ou do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="bb245-103">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="bb245-104">Esse erro pode ser causado pela limitação no serviço do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="bb245-104">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="bb245-105">SharePoint Online usa a limitação para manter o melhor desempenho e confiabilidade do serviço SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bb245-105">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="bb245-106">O número de ações do usuário ou simultâneas redução dos limites chamadas (por script ou código) para impedir o uso excessivo de recursos.</span><span class="sxs-lookup"><span data-stu-id="bb245-106">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="bb245-107">Para obter mais informações sobre limitação, confira o artigo sobre [como ficar limitado ou bloqueado no SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="bb245-107">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="bb245-108">Se acreditar que esse erro não está relacionado à limitação, você poderá verificar se há manutenção ativa ocorrendo no locatário, navegando até o [centro de mensagens](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="bb245-108">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="bb245-109">Por fim, verifique se você está visitando a página [integridade do serviço](https://portal.office.com/adminportal/home#/servicehealth) para verificar se há avisos/incidentes que possam ocorrer.</span><span class="sxs-lookup"><span data-stu-id="bb245-109">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

