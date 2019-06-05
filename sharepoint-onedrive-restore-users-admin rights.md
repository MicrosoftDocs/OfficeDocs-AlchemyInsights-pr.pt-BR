---
title: Conceder aos usuários acesso ao SharePoint e ao OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: ae4d2c00be6387744bdc84e1d8a021530f80f8fa
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715200"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Conceder aos usuários acesso ao SharePoint e ao OneDrive

<p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Esse problema ocorre com mais frequência quando um usuário é excluído e recriado com o mesmo nome de usuário principal (UPN). A nova conta é criada usando um valor diferente de PUID (ID exclusiva do Passport). Quando o usuário tenta acessar um conjunto de sites ou seu OneDrive, o usuário tem um PUID incorreto. Um segundo cenário envolve a sincronização de diretório com uma unidade organizacional (OU) do Active Directory. Se os usuários já tiverem entrado no SharePoint e forem movidos para uma OU diferente e ressincronizado com o SharePoint, poderão enfrentar esse problema.</span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Para resolver esse problema, você deve restaurar o UPN original com as etapas no artigo, <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">restaurar um usuário no Office 365.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Depois disso, você pode verificar se o usuário tem direitos de administrador para o site do OneDrive seguindo as etapas para <a href="https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive">Adicionar o administrador do onedrive de um usuário.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Para obter mais informações sobre níveis de permissão, confira o artigo <a href="https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels">noções básicas sobre níveis de permissão no SharePoint.</a>&nbsp;</span></p>