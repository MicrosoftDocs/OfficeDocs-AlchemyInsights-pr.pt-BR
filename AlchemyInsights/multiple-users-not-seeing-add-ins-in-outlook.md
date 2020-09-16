---
title: Vários usuários não estão vendo suplementos no Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.openlocfilehash: a0c272f40044795754ed8630e88e00ed14ea6ad7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47729859"
---
# <a name="multiple-users-not-seeing-add-ins-in-outlook"></a><span data-ttu-id="86fb3-102">Vários usuários não estão vendo suplementos no Outlook</span><span class="sxs-lookup"><span data-stu-id="86fb3-102">Multiple users not seeing add-ins in Outlook</span></span>

<span data-ttu-id="86fb3-103">Se você testar suplementos do Outlook e nenhum for exibido, como uma primeira etapa de solução de problemas, use o cmdlet do Windows PowerShell **Get-Set OrganizationConfig** para consultar o parâmetro do _AppsForOfficeEnabled_.</span><span class="sxs-lookup"><span data-stu-id="86fb3-103">If you test Outlook add-ins and none show up, as a first troubleshooting step, use the **Get-OrganizationConfig** PowerShell cmdlet to query the _AppsForOfficeEnabled_ parameter.</span></span> <span data-ttu-id="86fb3-104">Se a consulta retornar um valor **Falso**, defina esse parâmetro como **Verdadeiro** usando o cmdlet **Set-Set OrganizationConfig**, para que os suplementos apareçam como esperado.</span><span class="sxs-lookup"><span data-stu-id="86fb3-104">If the query returns a value of **False**, set this parameter to **True** by using the **Set-OrganizationConfig** cmdlet, so add-ins appear as expected.</span></span>

<span data-ttu-id="86fb3-105">Não é recomendável que o parâmetro _AppsForOfficeEnabled_ esteja definido como **Falso**.</span><span class="sxs-lookup"><span data-stu-id="86fb3-105">We do not recommend that the _AppsForOfficeEnabled_ parameter is set to **False**.</span></span> <span data-ttu-id="86fb3-106">Um valor **Falso** substitui todas as configurações de funções administrativas e de usuário acima e impede que os novos aplicativos sejam ativados por qualquer usuário da organização.</span><span class="sxs-lookup"><span data-stu-id="86fb3-106">A value of **False** overrides all of the above Administrative and User role settings and prevents any new apps from being activated by any user in the organization.</span></span>

<span data-ttu-id="86fb3-107">Para obter mais informações, consulte [Especificar os administradores e usuários que podem instalar e gerenciar suplementos do Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins#user-roles).</span><span class="sxs-lookup"><span data-stu-id="86fb3-107">For more information, see [Specify the administrators and users who can install and manage add-ins for Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins#user-roles).</span></span>