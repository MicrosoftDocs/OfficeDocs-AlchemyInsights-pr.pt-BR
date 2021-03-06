---
title: Criar um site no SharePoint Online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: b554bfa4ccccbd68d0c3df27cf17397f860735c2
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47732200"
---
# <a name="create-sharepoint-sites-using-templates"></a>Criar sites do SharePoint usando modelos

A capacidade de salvar um site como modelo não é suportada com a comunicação moderna ou com sites de equipe. Para obter mais informações sobre como usar modelos [, consulte salvar, baixar e carregar um site do SharePoint como um modelo](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).

Aqui estão alguns problemas comuns/soluções sobre como salvar um site ou uma lista como um modelo no SharePoint Online. 

**O botão salvar site/modelo de lista não está disponível ou ausente**

Os administradores precisarão permitir que o script personalizado habilite os recursos do modelo. Para obter etapas detalhadas, exemplos e considerações, consulte 

- [Permitir ou impedir o script personalizado](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- O comando salvar site como modelo não é suportado e pode causar problemas em sites que usam a infraestrutura de publicação do SharePoint Server.

**O modelo de site não pode ser criado ou não funciona corretamente**

O modelo pode não ter um [recurso](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) e não será ativado. Se o recurso não estiver disponível para ser ativado no conjunto de sites atual, você não poderá usar o modelo de site para criar um site.

- Verifique se as listas ou bibliotecas excedem o limite de [exibição de lista](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) de 5000 itens, pois isso pode bloquear a criação de um modelo de site.

- O site pode estar usando muitos recursos e, portanto, o modelo de site excede o limite de 50 MB.


- Há problemas ao exibir dados de uma lista que usa uma coluna de pesquisa. Para obter mais informações, consulte [Template-generated List não exibe dados da lista de pesquisa correta no SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).

Para obter informações mais detalhadas sobre problemas e soluções comuns, verifique [criar e usar modelos de site](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).



