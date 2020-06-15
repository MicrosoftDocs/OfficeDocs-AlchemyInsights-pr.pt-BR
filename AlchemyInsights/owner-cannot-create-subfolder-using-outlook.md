---
title: O proprietário não consegue criar subpasta usando o Outlook
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5884"
- "3500007"
ms.openlocfilehash: 2116bb837e4378ea29d7882df1d3010b3a4e0b1c
ms.sourcegitcommit: 936330b11fec49f6174eadea6c765bdf9e6ba784
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/12/2020
ms.locfileid: "44716506"
---
# <a name="owner-cannot-create-sub-folder-using-outlook"></a><span data-ttu-id="c6d32-102">O proprietário não consegue criar subpasta usando o Outlook</span><span class="sxs-lookup"><span data-stu-id="c6d32-102">Owner cannot create sub-folder using Outlook</span></span>

<span data-ttu-id="c6d32-103">**Há um problema contínuo com os proprietários de pasta pública que criam subpastas usando o Outlook. O problema será corrigido em breve.**</span><span class="sxs-lookup"><span data-stu-id="c6d32-103">**There's an ongoing issue with public folder owners creating subfolders using Outlook. The issue will be fixed soon.**</span></span>

<span data-ttu-id="c6d32-104">Você pode usar uma das seguintes soluções alternativas:</span><span class="sxs-lookup"><span data-stu-id="c6d32-104">Meanwhile, use one of the following workarounds:</span></span>

1. <span data-ttu-id="c6d32-105">Use o Outlook para MAC para criar a subpasta já que o problema afeta apenas o Outlook para Windows para área de trabalho (todas as versões)</span><span class="sxs-lookup"><span data-stu-id="c6d32-105">Use Outlook for MAC to create the subfolder as the issue impacts only Outlook for desktop windows (all versions)</span></span>
2. <span data-ttu-id="c6d32-106">O administrador cria a subpasta usando o Shell EXO ou o EAC</span><span class="sxs-lookup"><span data-stu-id="c6d32-106">Have admin create the subfolder using EXO Shell or EAC</span></span>
3. <span data-ttu-id="c6d32-107">Alterar o DefaultPublicFolderMailbox/EffectivePublicFolderMailbox no usuário para outra caixa de correio do que a caixa de correio de conteúdo da pasta, causando o problema</span><span class="sxs-lookup"><span data-stu-id="c6d32-107">Change the DefaultPublicFolderMailbox/EffectivePublicFolderMailbox on the user to other mailbox than the Content Mailbox for the folder causing issue</span></span>  
    - <span data-ttu-id="c6d32-108">*Set-Mailbox User1 DefaultPublicFolderMailbox PubMBX3*</span><span class="sxs-lookup"><span data-stu-id="c6d32-108">*Set-Mailbox User1 DefaultPublicFolderMailbox PubMBX3*</span></span>
4. <span data-ttu-id="c6d32-109">Esperar por uma hora, reiniciar o cliente do Outlook</span><span class="sxs-lookup"><span data-stu-id="c6d32-109">Wait for an hour, restart outlook client</span></span>