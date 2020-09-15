---
title: Um usuário recebe o erro Acesso Negado ao adicionar suplementos ao Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5892"
- "6700008"
ms.openlocfilehash: 355f37386e0a498185e195c1d715386785d0b54b
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47673269"
---
# <a name="one-user-gets-access-denied-error-while-adding-add-ins-in-outlook"></a><span data-ttu-id="f2a40-102">Um usuário recebe o erro Acesso Negado ao adicionar suplementos ao Outlook</span><span class="sxs-lookup"><span data-stu-id="f2a40-102">One user gets Access Denied error while adding add-ins in Outlook</span></span>

<span data-ttu-id="f2a40-103">Use o PowerShell para localizar as permissões:</span><span class="sxs-lookup"><span data-stu-id="f2a40-103">User PowerShell To find permissions:</span></span>

<span data-ttu-id="f2a40-104">Get-ManagementRoleAssignment -RoleAssignee [user@domain.com](mailto:user@domain.com "mailto:user@domain.com") -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span><span class="sxs-lookup"><span data-stu-id="f2a40-104">Get-ManagementRoleAssignment -RoleAssignee [user@domain.com](mailto:user@domain.com "mailto:user@domain.com") -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span></span>