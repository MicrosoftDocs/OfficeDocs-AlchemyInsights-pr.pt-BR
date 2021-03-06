---
title: Restaurar uma pasta pública excluída
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: d5480389c3bf50cee9fe30f7ec8d8ff28ef694ca
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51809427"
---
# <a name="restore-a-deleted-public-folder"></a>Restaurar uma pasta pública excluída

**Para restaurar itens excluídos de uma pasta pública**:

- Consulte Não é possível recuperar itens excluídos de uma pasta pública que não seja de email [no Outlook 2016](https://aka.ms/pfrec).
 
**Para restaurar uma pasta pública excluída (de qualquer tipo)**: 

- Use o seguinte comando do EXO PowerShell:

    Sintaxe:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Exemplo: o seguinte comando restaurará Subpasta1 e a colocará em \Parent1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Confira [Restaurar uma pasta pública excluída](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) para obter mais detalhes.
