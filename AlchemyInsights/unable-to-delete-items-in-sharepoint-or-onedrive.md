---
title: Não é possível excluir itens no SharePoint ou no OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: db45aa8df40484fdcda7c430f1ca27482a1dd4ce
ms.sourcegitcommit: a9415f3ae8c7ba267b5134bcbdc1e070cea41a0f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/12/2020
ms.locfileid: "49019571"
---
# <a name="unable-to-delete-items"></a>Não é possível excluir itens

- As políticas de retenção podem causar isso, você precisa desabilitar ou excluir o respectivo bloqueio que está causando esse problema. Depois que uma política de retenção ou uma retenção for removida, pode levar até 24 horas para que a alteração entre em vigor. Certifique-se de que não haja uma configuração de [política de retenção](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) no item.

- O site pode ter excedido o limite de armazenamento, aumentar a [cota do site](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) e excluir o item.

- Verifique se o item não está [com check-out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) para outro usuário.

- Por fim, os administradores podem usar o PnP ( [padrões e práticas do SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) ) que contém uma biblioteca de comandos do PowerShell que permitem executar ações complexas de gerenciamento, como forçar exclusão de itens do Stubborn.
- [Remover arquivo PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Remover pasta PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Remover item de lista PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Remover lista PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Remover campo PNP (coluna)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)