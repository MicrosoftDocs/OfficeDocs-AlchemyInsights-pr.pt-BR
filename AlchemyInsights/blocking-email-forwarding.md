---
title: 726 bloquear o encaminhamento de email
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "726"
- "1200004"
ms.assetid: 8865c68e-7e8a-4135-a254-d7f69f1ded30
ms.openlocfilehash: 610013c4f46e999f1a8715aea14dd557ed8b0e2a
ms.sourcegitcommit: 88f24bb6ced16842de165af416e3f21feae13063
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/15/2020
ms.locfileid: "48478332"
---
# <a name="blocking-or-unblocking-email-forwarding"></a>Bloqueando ou desbloqueando o encaminhamento de email

Para habilitar ou desabilitar o encaminhamento de emails para uma caixa de correio específica, confira [Configurar o encaminhamento de email](https://docs.microsoft.com/microsoft-365/admin/email/configure-email-forwarding).

No nível do locatário, o controle de encaminhamento externo é feito usando a política de spam de saída. Você pode verificar a política de filtro de spam de saída do centro de segurança e conformidade [aqui](https://protection.office.com/antispam) ou usando o [comando Get-HostedOutboundSpamFilterPolicy](https://docs.microsoft.com/powershell/module/exchange/get-hostedoutboundspamfilterpolicy).

Se você estiver recebendo o seguinte erro: **"550 5.7.520 acesso negado, sua organização não permitir encaminhamento externo"**, certifique-se de que a política está configurada para habilitar o avanço automático externo.

**Observação:** É recomendável manter o encaminhamento automático externo desabilitado na política de filtro de spam de saída padrão e habilitá-lo somente para os usuários que precisam de encaminhamento externo criando uma política personalizada para esses usuários. Você pode ler mais sobre como [Configurar o encaminhamento de email externo no Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/external-email-forwarding).