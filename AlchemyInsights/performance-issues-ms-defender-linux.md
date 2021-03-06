---
title: Problemas de desempenho do Microsoft Defender para Ponto de Extremidade no Linux
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/04/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11491"
- "9001464"
ms.openlocfilehash: 268f44640d3b2d8764133560d0cbf500eb4afd22
ms.sourcegitcommit: 8242a824491f64be48dfe81da09766920fbd7feb
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/06/2021
ms.locfileid: "52783414"
---
# <a name="performance-issues-for-microsoft-defender-for-endpoint-on-linux"></a>Problemas de desempenho do Microsoft Defender para Ponto de Extremidade no Linux

Este artigo serve de guia nas etapas de identificação de problemas de desempenho do Microsoft Defender para Ponto de Extremidade no Linux.

É importante verificar primeiro se o problema que você está enfrentando foi resolvido com a [versão mais recente](/microsoft-365/security/defender-endpoint/linux-whatsnew). 

Para iniciar a sua investigação, consulte [Solução de problemas de desempenho do Microsoft Defender para Ponto de Extremidade no Linux](/microsoft-365/security/defender-endpoint/linux-support-perf).

## <a name="exclusions"></a>Exclusões

As exclusões podem ajudar a atenuar os problemas de desempenho. Analise as suas exclusões antes de começar, para que qualquer risco adicional seja conhecido e documentado.

Para mais informações, confira [Configurar e validar exclusões no Microsoft Defender para Ponto de Extremidade no Linux](/microsoft-365/security/defender-endpoint/linux-exclusions).

Quando você tem vários arquivos e pastas para excluir e eles estão todos no mesmo ponto de montagem, pode ser mais fácil excluir o ponto de montagem. A partir da versão 101.22.80 de fevereiro, você pode excluir um ponto de montagem inteiro.

Por exemplo, se /mnt/backup for um ponto de montagem, você pode adicionar /mnt/backup à lista de exclusão executando este comando:

`$ mdatp exclusion folder add –path /mnt/backup`

**Observação**: adicionar exclusões aumenta o risco de o malware não ser detectado e deve ser tratado e implementado com cuidado.

## <a name="need-help"></a>Precisa de ajuda?

Para ajudá-lo da maneira mais eficiente, colete os dados de diagnóstico antes de abrir um caso de suporte.
