---
title: Precisa de ajuda com os limites de envio de e-mails?
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002938"
- "5630"
ms.openlocfilehash: b5bdfbf818328c97ec93b3468aeedcbe88e03913
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51836267"
---
# <a name="need-help-with-email-sending-limits"></a>Precisa de ajuda com os limites de envio de e-mails?

Veja a seguir o **limite de envio por design** impostos no serviço. Para saber mais sobre esses limites, confira [aqui](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).

- Para desencorajar a entrega de mensagens não solicitadas em massa, aplicamos **limites de taxa de destinatário por usuário a todas as mensagens de saída e internas**. Em todas as SKUs, esse limite é de **10.000 destinatários por dia**.  Os clientes que precisam enviar emails comerciais legítimos em massa (por exemplo, boletins informativos para clientes) devem usar provedores de terceiros especializados nesses serviços.
    - **Observação**: Após o limite ter sido atingido, não será mais possível enviar mensagens da caixa de correio até que o número de destinatários para os quais foram enviadas mensagens nas últimas 24 horas fique abaixo do limite. O usuário não poderá enviar mensagens até esse ponto.
- A taxa limite de mensagem de **30 mensagens por minuto** são aplicadas a todas as SKUs. Isso determina quantas mensagens um usuário pode enviar de suas contas do Exchange Online dentro de um período especificado.
- O **número máximo de destinatários permitidos nos campos Para, CC e CCO** para uma única mensagem de email, em todas as SKUs, é **1000 destinatários**. Para personalizar esse limite, veja [aqui](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).
