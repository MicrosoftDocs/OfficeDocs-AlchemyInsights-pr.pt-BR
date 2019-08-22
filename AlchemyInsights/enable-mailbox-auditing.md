---
title: Habilitar a auditoria de caixa de correio
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 1ef60017f1ea656296bc7b2aa3bc5365646f11f3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527579"
---
# <a name="enable-mailbox-auditing"></a>Habilitar a auditoria de caixa de correio

Para habilitar a auditoria de caixa de correio para um único usuário ou uma organização inteira, os cmdlets a seguir devem ser executados a partir do Shell de energia remoto:
  
 **Único usuário**
  
Set-Mailbox-Identity "Jane Dow"-AuditEnabled $true
  
 **Organização**
  
Get-Mailbox-Results Unlimited-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[Saiba mais](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

