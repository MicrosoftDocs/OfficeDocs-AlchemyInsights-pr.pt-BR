---
title: 2491 Alert email messages from the 'Phish Delivered due to tenant or user override' policy
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2b373423cf3e63b76a62465dd62076c023580e94
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52544566"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Alertar mensagens de email da política 'Phish Delivered due to tenant or user override'

Uma política de alerta padrão chamada "Phish Delivered due to tenant or user override" has been rolled out to tenants with Microsoft Defender for Office 365 P1 and P2 licenses. Se você recebeu esse alerta, aqui estão as etapas para investigar:

1. Na mensagem de alerta, clique em **Exibir Alerta** para ir até a página **Alertas** no Centro de Conformidade & Segurança.

2. Selecione o alerta para ver a opção Exibir lista **de mensagens** ou Exibir mensagens **no Explorer**. Ambas as opções levam você aos detalhes da mensagem, que inclui a ID da mensagem. Observe que o link do Explorador de Ameaças filtrará automaticamente as mensagens que corresponderem aos critérios de alerta. Talvez seja necessário ajustar o filtro de data no Explorador de Ameaças.

A mensagem de phishing foi entregue devido a uma substituição configurada manualmente:

- Um remetente ou domínio permitido definido pelo usuário.

- Um remetente ou domínio permitido definido pelo administrador em uma política anti-spam.

- Um endereço IP permitido em uma política de filtro de conexão.

- Uma regra de fluxo de emails (também conhecida como regra de transporte) configurada para permitir mensagens.

Se você acredita que a mensagem foi marcada incorretamente como phishing, use o Outlook [de](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) Mensagem de Relatório para enviar amostras de mensagem para a Microsoft.
