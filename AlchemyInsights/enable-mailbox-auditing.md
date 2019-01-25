---
title: Habilitar a auditoria de caixa de correio
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: bd94ec10f9df2e72ec6e3d8552d2eb80212a9d78
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29500270"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="de81d-102">Habilitar a auditoria de caixa de correio</span><span class="sxs-lookup"><span data-stu-id="de81d-102">Enable mailbox auditing</span></span>

<span data-ttu-id="de81d-103">Para habilitar a auditoria de caixa de correio para uma organização inteira ou um único usuário, os cmdlets a seguir deve ser executados do Power Shell remoto:</span><span class="sxs-lookup"><span data-stu-id="de81d-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="de81d-104">**Usuário único**</span><span class="sxs-lookup"><span data-stu-id="de81d-104">**Single User**</span></span>
  
<span data-ttu-id="de81d-105">Set-Mailbox - Identity "Jane Dow" - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="de81d-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="de81d-106">**Organização**</span><span class="sxs-lookup"><span data-stu-id="de81d-106">**Organization**</span></span>
  
<span data-ttu-id="de81d-107">Get-Mailbox - ResultSize Ilimitado - filtro {RecipientTypeDetails - eq "UserMailbox"} | Set-Mailbox - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="de81d-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="de81d-108">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="de81d-108">Learn more</span></span>](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

