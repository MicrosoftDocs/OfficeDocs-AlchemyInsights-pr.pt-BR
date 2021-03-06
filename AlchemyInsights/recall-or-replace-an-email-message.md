---
title: Cancelar ou substituir uma mensagem de email
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: 05016213a1387c5290cb5899359f1f10b5a413c0
ms.sourcegitcommit: 4e0ae808ee2a586339b396320e3edb8ba066a91a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/19/2020
ms.locfileid: "49353494"
---
# <a name="recall-or-replace-an-email-message-in-microsoft-365"></a>Cancelar ou substituir uma mensagem de email no Microsoft 365

- Você **só pode recuperar mensagens que são enviadas para pessoas em sua organização**. Por exemplo, se a mensagem foi enviada para um endereço do Gmail, você não poderá recuperá-la.
- Você pode **apenas recuperar mensagens enviadas do Outlook para o PC**. Se um usuário enviar uma mensagem usando o Outlook para Mac ou o Outlook na Web, você não poderá recuperá-la.
- Como administrador de locatários, você pode **recuperar mensagens em nome dos usuários usando o PowerShell** (para obter mais informações, consulte: [Pesquisar e excluir mensagens de email](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messages-in-your-organization)).
- Não é possível recuperar mensagens do centro de administração. Role para baixo até "procurar e excluir mensagens de email em sua organização" para obter mais informações.

**Cancelar ou substituir uma mensagem de email enviada**

1. No painel de pastas à esquerda da janela do Outlook, escolha a pasta Itens enviados.
2. Abra a mensagem que você deseja cancelar. Você deve clicar duas vezes para abrir a mensagem. Selecionar a mensagem para que ela apareça no painel de leitura não permite que você relembre a mensagem.
3. Na guia mensagem, selecione **ações**  >  **cancelar esta mensagem**.
4. Escolha **Excluir cópias não lidas desta mensagem** ou **Excluir cópias não lidas e substituir por uma nova mensagem** e, em seguida, selecione **OK**.
5. Se você estiver enviando uma mensagem de substituição, redija a mensagem e selecione **Enviar**.
6. O sucesso ou a falha de uma recuperação de mensagem depende das configurações dos destinatários no Outlook.

Para obter mais informações, incluindo como verificar o cancelamento, confira [cancelar ou substituir uma mensagem de email enviada](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

**_Para pesquisar e excluir mensagens de email em sua organização_**, é mais fácil se você for um administrador global. Se você não for um administrador global, sua conta deverá ser adicionada ao grupo de funções Gerenciador de descoberta eletrônica ou à função de gerenciamento de pesquisa de conformidade. Para excluir mensagens, você precisará ingressar no grupo de função gerenciamento da organização ou na função gerenciamento de pesquisa e limpeza. As permissões para essas funções são atribuídas no [centro de conformidade de & de segurança](https://protection.office.com/).

1. [Criar uma pesquisa de conteúdo](https://docs.microsoft.com/microsoft-365/compliance/content-search) para localizar a mensagem a ser excluída.
2. [Conectar-se ao Windows PowerShell do Centro de Conformidade e Segurança](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell).

Se você estiver usando a MFA (autenticação multifator), confira [conectar-se ao PowerShell do centro de conformidade do Microsoft 365 Security & usando a autenticação multifator](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell).
