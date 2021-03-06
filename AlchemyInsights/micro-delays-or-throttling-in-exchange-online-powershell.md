---
title: Micro atrasos ou limitação no Windows PowerShell do Exchange Online
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
- "3500011"
- "5106"
ms.openlocfilehash: 204e0248bc2f07f14fa789d1d2999495910ee034
ms.sourcegitcommit: d2108b13acc44e26b65f9a2739cbce9bf98959a5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/28/2021
ms.locfileid: "52702114"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Micro atrasos ou limitação no Windows PowerShell do Exchange Online

É provável que você veja os avisos "Ocorreram micro atrasos" ou os atrasos executar scripts e cmdlets no Exchange Online. Eis algumas sugestões de como resolver isso: 

- Execute nossos diagnósticos para relaxar as políticas de locação do PowerShell do seu locatário. Essa solução resolverá o problema para a maioria.
- Se o problema ainda não tiver sido resolvido, use o [Módulo do PowerShell no Exchange Online v2](/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps&preserve-view=true), que inclui CMDlets baseados na API REST e que são significativamente mais eficazes. Essa pode ser uma ótima solução para muitos CMDlets de Get- que são usados com frequência.
- Se você precisar usar CMDlets que não são abordados no módulo v2, consulte [Executando cmdlets do PowerShell para grandes quantidades de usuários no Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), que tratam de como conferir os limites esperados de limitação do PowerShell no Exchange Online.
