---
title: Configuração virtual com serviços de domínio do AAD
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7927"
- "9004397"
ms.openlocfilehash: 7c56e467679f9b9a48cfd7a6f70f7ee148ded3e8
ms.sourcegitcommit: a61a29dbd0382370fea0be5fa4a61c9a1a9354c7
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/18/2021
ms.locfileid: "49884550"
---
# <a name="virtual-configuration-with-aad-domain-services"></a><span data-ttu-id="66e33-102">Configuração virtual com serviços de domínio do AAD</span><span class="sxs-lookup"><span data-stu-id="66e33-102">Virtual configuration with AAD domain services</span></span>

<span data-ttu-id="66e33-103">A configuração virtual com serviços de domínio do AAD envolve as seguintes etapas:</span><span class="sxs-lookup"><span data-stu-id="66e33-103">Virtual configuration with AAD domain services involves the following steps:</span></span> 

1. <span data-ttu-id="66e33-104">Verificar a integridade do domínio no portal do Azure https://aka.ms/aadds-health</span><span class="sxs-lookup"><span data-stu-id="66e33-104">Checking your domain’s health on the Azure portal https://aka.ms/aadds-health</span></span>
2. <span data-ttu-id="66e33-105">Verificar o NSG em busca de regras que bloqueiam as portas necessárias para sincronizar o Azure Active Directory Domain Services ao portal https://aka.ms/aadds-networking</span><span class="sxs-lookup"><span data-stu-id="66e33-105">Checking your NSG for rules that block ports needed to synchronize in Azure AD Domain Services on the portal https://aka.ms/aadds-networking</span></span>
3. <span data-ttu-id="66e33-106">Garantir que a rede virtual seja implantada na mesma região do Azure que seu domínio gerenciado pelo Azure AD Domain Services.</span><span class="sxs-lookup"><span data-stu-id="66e33-106">Ensuring that your virtual network is deployed in the same Azure Region as your Azure AD Domain Services-managed domain.</span></span>
4. <span data-ttu-id="66e33-107">Garantir que você não tenha um domínio existente com o mesmo nome de domínio disponível na rede virtual.</span><span class="sxs-lookup"><span data-stu-id="66e33-107">Ensuring you don’t have an existent domain with the same domain name available on the virtual network.</span></span>

<span data-ttu-id="66e33-108">Para obter mais detalhes sobre a consideração de design na Rede Virtual do Azure para oferecer suporte a serviços de domínio do AAD, confira [Consideração sobre a Rede Virtual](https://docs.microsoft.com/azure/active-directory-domain-services/network-considerations).</span><span class="sxs-lookup"><span data-stu-id="66e33-108">For more details on design consideration on Azure Virtual Network to support AAD domain services, see [Virtual Network Consideration](https://docs.microsoft.com/azure/active-directory-domain-services/network-considerations).</span></span>

