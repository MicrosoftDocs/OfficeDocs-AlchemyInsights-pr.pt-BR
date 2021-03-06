---
title: Salvar site ou lista como modelo
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 37ae727aa6dd6af94d0d833ce972aec413d90194
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47727519"
---
# <a name="save-site-or-list-as-a-template"></a>Salvar site ou lista como modelo

Os modelos de site do SharePoint são definições pré-compiladas projetadas de acordo com uma necessidade comercial em particular. Para obter mais informações, consulte [usando modelos para criar diferentes tipos de sites do SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Aqui estão alguns problemas comuns/soluções sobre como salvar um site ou uma lista como um modelo no SharePoint Online.

O **botão salvar site/modelo de lista não está disponível ou ausente**. 

- Os administradores precisarão permitir que o script personalizado habilite os recursos do modelo. Para obter etapas detalhadas, exemplos e considerações, consulte [permitir ou impedir o script personalizado](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


- O comando salvar site como modelo não é suportado e pode causar problemas em sites que usam a infraestrutura de publicação do SharePoint Server.


**O modelo de site não pode ser criado ou não funciona corretamente**

- O modelo pode não ter um [recurso](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) e não será ativado. Se o recurso não estiver disponível para ser ativado no conjunto de sites atual, você não poderá usar o modelo de site para criar um site.


- Verifique se as listas ou bibliotecas excedem o limite de [exibição de lista](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) de 5000 itens, pois isso pode bloquear a criação de um modelo de site.


- O site pode estar usando muitos recursos e, portanto, o modelo de site excede o limite de 50 megabytes (MB).


- Há problemas ao exibir dados de uma lista que usa uma coluna de pesquisa. Para obter mais informações, consulte [Template-generated List não exibe dados da lista de pesquisa correta no SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).


Para obter informações mais detalhadas sobre problemas e soluções comuns, consulte, [crie e use modelos de site](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).

