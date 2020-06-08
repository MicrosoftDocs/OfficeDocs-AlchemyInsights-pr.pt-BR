---
title: Solucionar Problemas de Eventos do E-mail
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000301"
- "5765"
ms.openlocfilehash: e27589b7f6730036040b948b6275cef072fd8235
ms.sourcegitcommit: dc149ab45fbc2c974b54fb81156d2bc1b07017bb
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/02/2020
ms.locfileid: "44515955"
---
# <a name="troubleshooting-events-from-email"></a><span data-ttu-id="e349b-102">Solucionar Problemas de Eventos do E-mail</span><span class="sxs-lookup"><span data-stu-id="e349b-102">Troubleshooting Events from Email</span></span>

1. <span data-ttu-id="e349b-103">Verifique se o recurso está habilitado para a caixa de correio: **Get-EventsFromEmailConfiguration -Identity <mailbox>**</span><span class="sxs-lookup"><span data-stu-id="e349b-103">Verify the feature is enabled for the mailbox: **Get-EventsFromEmailConfiguration -Identity <mailbox>**</span></span>

2. <span data-ttu-id="e349b-104">Em seguida, examine os logs de "Eventos de E-mail" **Export-MailboxDiagnosticLogs <mailbox> -Component TimeProfile**</span><span class="sxs-lookup"><span data-stu-id="e349b-104">Then look at the 'Events from Email' logs **Export-MailboxDiagnosticLogs <mailbox> -Component TimeProfile**</span></span>

3. <span data-ttu-id="e349b-105">Nos logs de 'Eventos de E-mail', localize o InternetMessageId que corresponde ao item na caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="e349b-105">In the 'Events from Email' logs, find the InternetMessageId that matches the item in the mailbox.</span></span>  

4. <span data-ttu-id="e349b-106">O TrustScore determina se o item é adicionado ou não.</span><span class="sxs-lookup"><span data-stu-id="e349b-106">The TrustScore determines if the item is added or not.</span></span> <span data-ttu-id="e349b-107">Os eventos só serão adicionados se o TrustScore = "Trusted".</span><span class="sxs-lookup"><span data-stu-id="e349b-107">Events will only be added if the TrustScore = "Trusted".</span></span>

<span data-ttu-id="e349b-108">O TrustScore é determinado pelas propriedades SPF, Dkim ou Dmarc, que estão no Cabeçalho da Mensagem.</span><span class="sxs-lookup"><span data-stu-id="e349b-108">The TrustScore is determined by SPF, Dkim or Dmarc properties, which are in the Message Header.</span></span>

<span data-ttu-id="e349b-109">Para exibir estas propriedades:</span><span class="sxs-lookup"><span data-stu-id="e349b-109">To view these properties:</span></span>

<span data-ttu-id="e349b-110">**Área de trabalho do Outlook**</span><span class="sxs-lookup"><span data-stu-id="e349b-110">**Desktop Outlook**</span></span>

- <span data-ttu-id="e349b-111">Abra o item</span><span class="sxs-lookup"><span data-stu-id="e349b-111">Open the item</span></span>
- <span data-ttu-id="e349b-112">Arquivo -> Propriedades -> Cabeçalhos de Internet</span><span class="sxs-lookup"><span data-stu-id="e349b-112">File -> Properties -> Internet Headers</span></span>

<span data-ttu-id="e349b-113">ou</span><span class="sxs-lookup"><span data-stu-id="e349b-113">or</span></span>

<span data-ttu-id="e349b-114">**MFCMapi**</span><span class="sxs-lookup"><span data-stu-id="e349b-114">**MFCMapi**</span></span>

- <span data-ttu-id="e349b-115">Navegue até o item na caixa de entrada</span><span class="sxs-lookup"><span data-stu-id="e349b-115">Navigate to the item in the inbox</span></span>
- <span data-ttu-id="e349b-116">Procure PR_TRANSPORT_MESSAGE_HEADERS_W</span><span class="sxs-lookup"><span data-stu-id="e349b-116">Look for PR_TRANSPORT_MESSAGE_HEADERS_W</span></span>

<span data-ttu-id="e349b-117">Essas propriedades são determinadas e gravadas durante o transporte e o roteamento.</span><span class="sxs-lookup"><span data-stu-id="e349b-117">These properties are determined and recorded during transport and routing.</span></span> <span data-ttu-id="e349b-118">Para obter mais soluções de problemas, talvez seja necessário acompanhar junto ao Suporte de Transporte sobre as falhas no SPF, DKIM e.ou DMARC.</span><span class="sxs-lookup"><span data-stu-id="e349b-118">For further troubleshooting, you may need to follow up with Transport Support about the failures in  SPF, DKIM and.or DMARC.</span></span>