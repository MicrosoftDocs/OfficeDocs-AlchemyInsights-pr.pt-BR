---
title: Problemas de desempenho-SharePoint ou OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 3b04e811b69a1f9d652abbd603c3c09df068480c
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719505"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>SharePoint ou OneDrive lento, inacessível ou indisponível para vários usuários

Se um site do OneDrive ou do SharePoint não estiver disponível para vários usuários que anteriormente tinham acesso, pode haver um problema de serviço temporário. [Verifique o painel de integridade do serviço](https://portal.office.com/adminportal/home#/servicehealth).

## <a name="add-and-license-the-user"></a>Adicionar e licenciar o usuário

Certifique-se de [atribuir licenças aos usuários no Office 365 para empresas](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).


## <a name="assign-permissions"></a>Atribuir permissões

Se o usuário tiver recebido uma licença do SharePoint e ainda estiver recebendo uma mensagem de acesso negado, verifique se ele tem o [nível de permissão apropriado](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) atribuído.

## <a name="consider-using-the-access-request-feature"></a>Considere usar o recurso de solicitação de acesso

O [recurso de solicitação de acesso](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) permite que as pessoas solicitem acesso ao conteúdo que eles não têm permissão para ver no momento.

## <a name="allow-custom-script-may-cause-access-denied-issues"></a>Permitir que o script personalizado possa causar problemas de acesso negado

Há determinados cenários em que o recurso *permitir script personalizado* pode estar apresentando um acesso negado. Para obter uma lista dos recursos afetados, considerações sobre segurança e a capacidade de desabilitar o recurso. Visite [permitir ou impedir o script personalizado](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).
