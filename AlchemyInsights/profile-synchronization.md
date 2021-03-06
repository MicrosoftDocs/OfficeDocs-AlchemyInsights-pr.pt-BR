---
title: Sincronização de perfil
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: eee1080a95955332e205db3852381e39aaf5ae0e
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47801757"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>Quando o meu perfil é alterado, sincronizar com o aplicativo de perfil de usuário do SharePoint?

O SharePoint Online usa o trabalho de timer de importação do Active Directory (AD Import) para importar usuários e grupos para o aplicativo de perfil de usuário. 
  
1. A importação do AD sincroniza as alterações do repositório de diretórios do SharePoint Online para o aplicativo de perfil de usuário. Essas alterações são processadas em lotes.
    
2. O trabalho de timer é executado até que as alterações sejam sincronizadas.
    
> [!NOTE]
> O tempo necessário para a execução do trabalho depende do número de alterações a serem processadas. Um grande número de alterações demora mais. O contrato de nível de serviço (SLA) informa que uma alteração em um usuário no diretório do SharePoint Online será refletida no aplicativo de perfil de usuário em 24 horas. 
  
[Mais informações sobre a sincronização de perfil de usuário no SharePoint Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

