---
title: Mover mensagens de email para a caixa de correio de arquivo morto
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 61d0b1a58fff6655b745bb9d39e8384f0a543336
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47799768"
---
# <a name="move-email-to-the-archive-mailbox"></a>Mover email para a caixa de correio de arquivo morto

Se você quiser executar verificações automatizadas para as configurações mencionadas abaixo, selecione o botão voltar <: na parte superior desta página e insira o endereço de email do usuário que tem problemas ao mover o email para sua caixa de correio de arquivo morto.

1. Confirmar se uma **caixa de correio de arquivo morto** foi habilitada. Caso contrário, use as etapas neste [artigo](https://docs.microsoft.com/microsoft-365/compliance/enable-archive-mailboxes) para habilitar a caixa de correio de arquivo morto.

2. Para arquivar mensagens automaticamente na caixa de correio de arquivo morto, uma marca de retenção com a ação **mover para arquivo morto** deve ser definida como **aplicada automaticamente à marca de caixa de correio inteira (padrão)**. Use as etapas aqui para criar a marca de formatação: [arquivo morto padrão](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Em seguida, adicione a marca **Archive** à sua política de retenção. No centro de administração do Exchange, escolha **políticas de retenção** > adicionar a **marca mover para arquivo morto** à política > **salvar**.

4. Agora, [atribua a política de retenção](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) à caixa de correio do usuário específico. A mesma política será aplicada à caixa de correio **principal** e de **arquivo morto** .

Pode ser necessário forçar o assistente de pasta gerenciada (MFA) a ser executado e aplicar as novas configurações à caixa de correio do usuário. Execute o seguinte comando enquanto [estiver conectado ao EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar o assistente de pasta gerenciada para uma caixa de correio específica:
  
Start-ManagedFolderAssistant-Identity <name of the mailbox>

Para obter mais informações sobre como configurar uma política de arquivo morto, consulte [Configurar uma política de arquivo morto e exclusão para caixas de correio](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  