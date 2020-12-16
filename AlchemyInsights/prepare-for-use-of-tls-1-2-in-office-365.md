---
title: Preparar para o uso do TLS 1.2 no Microsoft 365
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Critical
ms.custom:
- "1266"
- "1600052"
ms.assetid: d5c84f5c-a3ca-4abd-8633-7e9ff01328a9
ms.openlocfilehash: 1ec40ba36c69296298e24dca64a873d53682833a
ms.sourcegitcommit: 35e2c122d8a838d98d1f0851c29b16282261580f
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/17/2020
ms.locfileid: "49085892"
---
# <a name="prepare-for-use-of-tls-12-in-microsoft-365"></a><span data-ttu-id="f474c-102">Preparar para o uso do TLS 1.2 no Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="f474c-102">Prepare for use of TLS 1.2 in Microsoft 365</span></span>

<span data-ttu-id="f474c-103">A partir de 31 de outubro de 2018, o Microsoft 365 continuará a transição para o TLS 1.2.</span><span class="sxs-lookup"><span data-stu-id="f474c-103">As of October 31st, 2018, Microsoft 365 will continue transitioning to TLS 1.2.</span></span> <span data-ttu-id="f474c-104">A partir de 15 de outubro de 2020, o O365 começará a substituir o TLS 1,0 e a 1,1 pelo serviço.</span><span class="sxs-lookup"><span data-stu-id="f474c-104">Starting October 15, 2020, O365 will begin the deprecation of TLS 1.0 and 1.1 across the service.</span></span> <span data-ttu-id="f474c-105">A implementação dessa alteração continuará nas próximas semanas e meses, mas os clientes devem presumir que nenhuma chamada TLS 1.0/1.1 funcionará ao interagir com o O365 a partir de 15 de outubro de 2020.</span><span class="sxs-lookup"><span data-stu-id="f474c-105">The rollout of this change will continue over the next few weeks and months, but customers should assume no TLS 1.0/1.1 calls will work when engaging with O365 starting Oct 15, 2020.</span></span> <span data-ttu-id="f474c-106">Conforme comunicado anteriormente (MC126199 em dezembro de 2017, MC128929 em fevereiro de 2018, MC186827 em julho de 2019 e MC218794 em julho de 2020), estamos movendo todos os nossos serviços online para protocolo TLS 1.2+ para fornecer o melhor da classe criptografia e para garantir que nosso serviço seja mais seguro, por padrão.</span><span class="sxs-lookup"><span data-stu-id="f474c-106">As previously communicated (MC126199 in Dec 2017, MC128929 in Feb 2018, MC186827 in July 2019, and MC218794 in July 2020), we are moving all of our online services to Transport Layer Security (TLS) 1.2+ to provide best-in-class encryption, and to ensure our service is more secure, by default.</span></span> <span data-ttu-id="f474c-107">Os clientes ainda podem escolher por ter o TLS 1.0/1.1 nos servidores e recursos, mas devem presumir que apenas o TLS 1.2 ou superior funcionará ao interagir com os recursos do O365.</span><span class="sxs-lookup"><span data-stu-id="f474c-107">Customers can still choose to have TLS 1.0/1.1 on their servers and resources, but they should assume only TLS 1.2 or higher will work when interacting with O365 resources.</span></span>
  
<span data-ttu-id="f474c-108">Para saber mais sobre essas alterações, confira [aqui](https://docs.microsoft.com/microsoft-365/compliance/prepare-tls-1.2-in-office-365?view=o365-worldwide) e [aqui](https://docs.microsoft.com/microsoft-365/compliance/tls-1.0-and-1.1-deprecation-for-office-365?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="f474c-108">To learn more about these changes, please see [here](https://docs.microsoft.com/microsoft-365/compliance/prepare-tls-1.2-in-office-365?view=o365-worldwide) and [here](https://docs.microsoft.com/microsoft-365/compliance/tls-1.0-and-1.1-deprecation-for-office-365?view=o365-worldwide).</span></span>

  