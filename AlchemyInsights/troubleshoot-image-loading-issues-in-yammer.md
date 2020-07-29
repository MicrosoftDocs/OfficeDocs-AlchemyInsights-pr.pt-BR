---
title: Solucionar problemas de carregamento de imagens no Yammer
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/15/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6000"
- "9003112"
ms.openlocfilehash: 93894eaa5818b591acd1c7b9a90bc1cabbe00450
ms.sourcegitcommit: b677b85395b7244b2bf2b753468b696b4cf27c8d
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/16/2020
ms.locfileid: "45146741"
---
# <a name="troubleshoot-image-loading-issues-in-yammer"></a><span data-ttu-id="72dab-102">Solucionar problemas de carregamento de imagens no Yammer</span><span class="sxs-lookup"><span data-stu-id="72dab-102">Troubleshoot image loading issues in Yammer</span></span>

<span data-ttu-id="72dab-103">Quando problemas ocorrem com fotos e visualizações de arquivos no Yammer, solucione o problema verificando se o problema ocorre para todos os usuários, se ele ocorre em dispositivos móveis e se é reproduzível ao carregar o anexo.</span><span class="sxs-lookup"><span data-stu-id="72dab-103">When issues occur with photos and file previews in Yammer, troubleshoot by checking whether the issue occurs for all users, whether it occurs on mobile devices, and if it is reproducible when uploading the attachment.</span></span>  

<span data-ttu-id="72dab-104">**Problemas com a foto do perfil**</span><span class="sxs-lookup"><span data-stu-id="72dab-104">**Profile photo issues**</span></span>  

<span data-ttu-id="72dab-105">Se usuários finais entrarem no Yammer pelo Microsoft 365, eles devem alterar seu perfil, incluindo a foto do perfil.</span><span class="sxs-lookup"><span data-stu-id="72dab-105">If end users sign into Yammer via Microsoft 365, they must change their profile, including their profile photo.</span></span> <span data-ttu-id="72dab-106">Se usuários não tiverem permissão para fazer atualizações no perfil, um administrador poderá fazer a atualização para o usuário.</span><span class="sxs-lookup"><span data-stu-id="72dab-106">If users are not permitted to make profile updates, an admin can make the update for the user.</span></span> <span data-ttu-id="72dab-107">Para mais informações, confira [Exibir e atualizar seu perfil no Office Delve](https://support.microsoft.com/office/view-and-update-your-profile-in-office-delve-4e84343b-eedf-45a1-aeb9-8627ccca14ba).</span><span class="sxs-lookup"><span data-stu-id="72dab-107">For more info, see [View and update your profile in Office Delve](https://support.microsoft.com/office/view-and-update-your-profile-in-office-delve-4e84343b-eedf-45a1-aeb9-8627ccca14ba).</span></span>

<span data-ttu-id="72dab-108">Para informações sobre edição de perfil, incluindo fotos de perfil, confira [Alterar perfil e configurações no Yammer](https://support.microsoft.com/office/classic-yammer-change-my-yammer-profile-and-settings-a3aeca0e-de34-4897-9b59-de6516542851).</span><span class="sxs-lookup"><span data-stu-id="72dab-108">For info about profile editing, including profile photos, see [Change my Yammer profile and settings](https://support.microsoft.com/office/classic-yammer-change-my-yammer-profile-and-settings-a3aeca0e-de34-4897-9b59-de6516542851).</span></span> 

<span data-ttu-id="72dab-109">Fotos atualizadas do perfil são sincronizadas de maneira diferente dos atributos de perfil.</span><span class="sxs-lookup"><span data-stu-id="72dab-109">Updated profile photos are synced differently than profile attributes.</span></span> <span data-ttu-id="72dab-110">Usuários devem entrar para iniciar a sincronização da foto de perfil.</span><span class="sxs-lookup"><span data-stu-id="72dab-110">Users must sign in to initiate a sync of their profile photo.</span></span> <span data-ttu-id="72dab-111">Para saber mais, confira [são imagens de perfil de usuário atualizadas do Office 365 para o Yammer](https://docs.microsoft.com/yammer/manage-yammer-users/manage-users-across-their-lifecycle#q-are-user-profile-pictures-updated-from-office-365-to-yammer).</span><span class="sxs-lookup"><span data-stu-id="72dab-111">For info, see [are user profile pictures updated from Office 365 to Yammer](https://docs.microsoft.com/yammer/manage-yammer-users/manage-users-across-their-lifecycle#q-are-user-profile-pictures-updated-from-office-365-to-yammer).</span></span>

<span data-ttu-id="72dab-112">Para informações sobre o ciclo de vida do Yammer, confira [Gerenciar usuários do Yammer em todo o ciclo de vida do Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-users-across-their-lifecycle).</span><span class="sxs-lookup"><span data-stu-id="72dab-112">For info about the user lifecycle for Yammer, see [Manage Yammer users across their lifecycle from Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-users-across-their-lifecycle).</span></span>  

<span data-ttu-id="72dab-113">Para obter detalhes sobre como funciona a sincronização de imagens de perfil no Microsoft 365, confira [Informações sobre a sincronização de imagens de perfil no Microsoft 365](https://support.microsoft.com/office/information-about-profile-picture-synchronization-in-microsoft-365-20594d76-d054-4af4-a660-401133e3d48a).</span><span class="sxs-lookup"><span data-stu-id="72dab-113">For details on how profile picture sync works in Microsoft 365, see [Information about profile picture synchronization in Microsoft 365](https://support.microsoft.com/office/information-about-profile-picture-synchronization-in-microsoft-365-20594d76-d054-4af4-a660-401133e3d48a).</span></span>  

<span data-ttu-id="72dab-114">**Problemas de visualização de documentos e miniaturas de imagens**</span><span class="sxs-lookup"><span data-stu-id="72dab-114">**Document previews and image thumbnail issues**</span></span>  

<span data-ttu-id="72dab-115">Quando arquivos ou imagens são publicados no Yammer, as visualizações podem não aparecer porque:</span><span class="sxs-lookup"><span data-stu-id="72dab-115">When files or images are posted to Yammer, previews might not appear because:</span></span> 

- <span data-ttu-id="72dab-116">O arquivo está corrompido e não pode ser processado.</span><span class="sxs-lookup"><span data-stu-id="72dab-116">The file is corrupt and cannot be processed.</span></span>
- <span data-ttu-id="72dab-117">O arquivo não foi recentemente carregado no SharePoint Online ou o Yammer tem metadados inválidos por outros motivos.</span><span class="sxs-lookup"><span data-stu-id="72dab-117">The file has not been recently uploaded to SharePoint Online, or Yammer has invalid metadata for other reasons.</span></span>
- <span data-ttu-id="72dab-118">As URLs necessárias para carregar as imagens de visualização estão bloqueadas.</span><span class="sxs-lookup"><span data-stu-id="72dab-118">URLs required for loading the preview images are blocked.</span></span>
- <span data-ttu-id="72dab-119">A visualização de arquivo foi removida pelo usuário antes da publicação.</span><span class="sxs-lookup"><span data-stu-id="72dab-119">The file preview was removed by the user before posting.</span></span>
- <span data-ttu-id="72dab-120">Um problema de serviço impediu uma visualização de ser gerada.</span><span class="sxs-lookup"><span data-stu-id="72dab-120">A service issue prevented a preview being generated.</span></span>

<span data-ttu-id="72dab-121">**Observação** Visualizações de links e carregamento de arquivos podem se comportar de maneira diferente.</span><span class="sxs-lookup"><span data-stu-id="72dab-121">**Note** Previews for links and file uploads might behave differently.</span></span> <span data-ttu-id="72dab-122">Links para arquivos na internet ou links que requerem autenticação adicional podem não ser exibidos corretamente.</span><span class="sxs-lookup"><span data-stu-id="72dab-122">Links to files on the internet or links that require additional authentication might not display correctly.</span></span>

<span data-ttu-id="72dab-123">Para saber mais, confira [Anexar um arquivo ou imagem a uma mensagem no Yammer](https://support.microsoft.com/office/attach-a-file-or-image-to-a-yammer-message-f576d4d1-ad66-4ce4-9c43-46cf75978dbf).</span><span class="sxs-lookup"><span data-stu-id="72dab-123">For more info, see [Attach a file or image to a Yammer message](https://support.microsoft.com/office/attach-a-file-or-image-to-a-yammer-message-f576d4d1-ad66-4ce4-9c43-46cf75978dbf).</span></span> 