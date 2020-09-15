---
title: Código de erro 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Se você estiver recebendo um erro ao ativar o Office 2013 em implantações de serviços de área de trabalho remota (RDS), considere habilitar a ADAL editando o registro.
ms.openlocfilehash: deb2ac4b0fb6a7b2e0045ff1b0ba95ad6e5e4a3a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47709175"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="acaf0-103">Erro ao ativar o Office 2013 nos serviços de área de trabalho remota</span><span class="sxs-lookup"><span data-stu-id="acaf0-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="acaf0-104">Se você estiver recebendo um erro ao ativar o Office 2013 em implantações de serviços de área de trabalho remota (RDS), considere habilitar a ADAL editando o registro.</span><span class="sxs-lookup"><span data-stu-id="acaf0-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="acaf0-105">**Chave do Registro**</span><span class="sxs-lookup"><span data-stu-id="acaf0-105">**Registry key**</span></span>|<span data-ttu-id="acaf0-106">**Tipo**</span><span class="sxs-lookup"><span data-stu-id="acaf0-106">**Type**</span></span>|<span data-ttu-id="acaf0-107">**Valor**</span><span class="sxs-lookup"><span data-stu-id="acaf0-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="acaf0-108">HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="acaf0-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="acaf0-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="acaf0-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="acaf0-110">1 </span><span class="sxs-lookup"><span data-stu-id="acaf0-110">1</span></span>  <br/> |

<span data-ttu-id="acaf0-111">Para obter mais informações, consulte [habilitar a autenticação moderna do Office 2013 em dispositivos Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="acaf0-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="acaf0-112">A ADAL é habilitada por padrão no Microsoft 365 Apps for Enterprise e no Office 2016.</span><span class="sxs-lookup"><span data-stu-id="acaf0-112">ADAL is enabled by default in Microsoft 365 Apps for enterprise and Office 2016.</span></span> <span data-ttu-id="acaf0-113">Os serviços de área de trabalho remota (RDS) eram chamados anteriormente dos serviços de terminal.</span><span class="sxs-lookup"><span data-stu-id="acaf0-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  