---
title: Ícone de energia ou bateria ausente no Windows 10
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
- "9002953"
- "5655"
ms.openlocfilehash: 95b68cee58f88d04f02e29477b139f7f583dc0b1
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51790536"
---
# <a name="power-or-battery-icon-missing-in-windows-10"></a>Ícone de energia ou bateria ausente no Windows 10

Se o seu dispositivo Windows 10 tiver uma bateria (por exemplo, um laptop ou tablet ou um PC conectado por meio de USB a um no-break), normalmente um ícone de alimentação/bateria será mostrado na barra de tarefas próximo ao relógio, por exemplo:

![Ícone de bateria](media/battery-icon.png)

Se você não vir esse ícone, ela poderá estar oculto:

1. Vá para **[Configurações > Personalização > Barra de Tarefas](ms-settings:taskbar?activationSource=GetHelp)**.

2. Na área de notificação, clique **Selecionar quais ícones aparecem na barra de tarefas**.

3. Em seguida, localize o item **Energia** na lista e alterne a configuração para **Ativado**.

    ![Mostrar ícone de energia na Barra de tarefas](media/power-icon-on.png)

**Solução de Problemas**

Se você seguiu as instruções acima e o botão de alternância **Energia** fica esmaecido ou não está visível, na caixa de pesquisa da barra de tarefas, digite **gerenciador de dispositivo** e, em seguida, selecione **Gerenciador de Dispositivos** na lista de resultados. Em **Bateria**, clique com o botão direito do mouse na bateria do dispositivo, clique em **Desabilitar** e clique em **Sim**. Aguarde alguns segundos e, em seguida, clique com o botão direito do mouse na bateria e clique em **Habilitar**. Em seguida, reinicie o dispositivo.

Se você seguiu as instruções acima, mas o ícone de bateria não aparece na barra de tarefas, na caixa de pesquisa da barra de tarefas, digite **gerenciador de tarefas** e, em seguida, clique em **Gerenciador de Tarefas** na lista de resultados. Na guia **Processos**, em **Nome**, clique com o botão direito do mouse **Explorador** e clique em **Reiniciar**.
