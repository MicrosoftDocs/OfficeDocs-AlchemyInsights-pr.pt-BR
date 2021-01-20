---
title: 'Controlador de domínio '
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/17/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7909"
- "9003233"
ms.openlocfilehash: d4cbe80c3e8f0ce32fcbe89e852f24efd6f50575
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/18/2021
ms.locfileid: "49886768"
---
# <a name="domain-controller"></a><span data-ttu-id="5034e-102">Controlador de domínio</span><span class="sxs-lookup"><span data-stu-id="5034e-102">Domain controller</span></span>

<span data-ttu-id="5034e-103">**Não é possível habilitar o AAD-DS ou a implantação está falhando**</span><span class="sxs-lookup"><span data-stu-id="5034e-103">**Unable to enable AAD-DS or deployment is failing**</span></span>

<span data-ttu-id="5034e-104">Para resolver o problema que faz com que o serviço de domínio do Azure Active Directory (AAD-DS) não possa ser habilitado ou implantado, execute as seguintes etapas:</span><span class="sxs-lookup"><span data-stu-id="5034e-104">To solve the issue of Azure AD domain service (AAD-DS) not being enabled or failing to be deployed, perform the following steps:</span></span>

1. <span data-ttu-id="5034e-105">Se você estiver usando uma rede virtual já existente, verifique em seu NSG as regras que bloqueiam as portas necessárias para sincronizar o AAD-DS ao portal https://aka.ms/aadds-networking.</span><span class="sxs-lookup"><span data-stu-id="5034e-105">If you are using an already existing virtual network, check your NSG for rules that block ports needed to synchronize in AAD-DS in the portal https://aka.ms/aadds-networking.</span></span>
2. <span data-ttu-id="5034e-106">Verifique se a mensagem de erro foi respondida neste guia de solução de problemas que está disponível em  https://aka.ms/aadds-troubleshoot-enable.</span><span class="sxs-lookup"><span data-stu-id="5034e-106">Check to see if your error message is answered in this troubleshooting guide that is available in  https://aka.ms/aadds-troubleshoot-enable.</span></span>
3. <span data-ttu-id="5034e-107">Tente implantar o Azure AD Domain Services em uma nova rede virtual.</span><span class="sxs-lookup"><span data-stu-id="5034e-107">Try deploying Azure AD Domain Services in a new virtual network.</span></span>
4. <span data-ttu-id="5034e-108">Siga o guia de Introdução sobre como implantar o AAD-DS, que está disponível no [Tutorial para Criar Microsoft Azure Active Directory](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-create-instance).</span><span class="sxs-lookup"><span data-stu-id="5034e-108">Follow the Getting Started guide on how to deploy AAD-DS, which is available at [Tutorial to Create Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-create-instance).</span></span>
5. <span data-ttu-id="5034e-109">Se estiver tendo problemas com a implantação do Azure AD Domain Services, consulte [Solucionar problemas do Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot) para resolver erros comuns e ajudá-lo a fazer as coisas funcionarem novamente.</span><span class="sxs-lookup"><span data-stu-id="5034e-109">If you are having issues with Deploying Azure AD Domain Services, see [Troubleshoot Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot) to resolve common errors to help you get things working again.</span></span> 

<span data-ttu-id="5034e-110">**Não é possível desabilitar o AAD-DS**</span><span class="sxs-lookup"><span data-stu-id="5034e-110">**Unable to disable AAD-DS**</span></span>

<span data-ttu-id="5034e-111">O AAD-DS não pode ser pausado.</span><span class="sxs-lookup"><span data-stu-id="5034e-111">AAD-DS is unable to be paused.</span></span> <span data-ttu-id="5034e-112">Se deseja parar de usar seu domínio gerenciado, ele deve ser excluído.</span><span class="sxs-lookup"><span data-stu-id="5034e-112">If you wish to stop using your managed domain, it must be deleted.</span></span>

<span data-ttu-id="5034e-113">Se você tiver problemas para resolver mensagens de erro comuns e para etapas de solução de problemas associadas para ajudá-lo a voltar a funcionar, consulte [Solucionar problemas do Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot).</span><span class="sxs-lookup"><span data-stu-id="5034e-113">If you run into issues, to resolve common error messages and for associated troubleshooting steps to help you get things running again, see [Troubleshoot Azure Active Directory Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot).</span></span>
