---
title: Gestione destinatari, dominio e società
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) offre diversi mezzi per la gestione delle informazioni relative a destinatari, dominio e società. In qualità di amministratore, è possibile eseguire alcune attività di gestione all'interno dell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguite nell'interfaccia di amministrazione di Microsoft 365.
ms.openlocfilehash: dcd039eab77c1b9df638df5ac3a3e5f6373e852d
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640264"
---
# <a name="recipient-domain-and-company-management"></a>Gestione destinatari, dominio e società

Microsoft Exchange Online Protection (EOP) offre diversi mezzi per la gestione delle informazioni relative a destinatari, dominio e società. In qualità di amministratore, è possibile eseguire alcune attività di gestione all'interno dell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguite nell'interfaccia di amministrazione di Microsoft 365.
  
Per informazioni su tutte le funzionalità di EOP? Vedere la [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

I destinatari di posta elettronica vengono classificati come utenti o gruppi di posta elettronica e possono essere gestiti attraverso la sincronizzazione di directory, direttamente nella EAC o in remoto Windows PowerShell. Se i destinatari vengono gestiti in locale, è necessario eseguire la sincronizzazione della directory affinché i destinatari di posta elettronica vengano visualizzati nell'interfaccia di amministrazione di Exchange. Gli utenti gestiti esclusivamente nell'interfaccia di amministrazione di Microsoft 365 non sono visualizzabili in EAC, ma possono essere aggiunti o rimossi dall'appartenenza a un gruppo di ruoli amministratore in EAC. Per ulteriori informazioni sui destinatari in EOP, vedere [Destinatario in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

In EOP, è possibile configurare solo ruoli amministrativi. Gli utenti possono essere aggiunti e rimossi da gruppi di regole predefinite direttamente in EAC. Non è disponibile alcuna personalizzazione RBAC. Per ulteriori informazioni, vedere [Gestione autorizzazioni gruppo di ruoli di amministratore in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Gestione del dominio

I domini gestiti sono quelli protetti da EOP. I domini gestiti possono essere visualizzati e i tipi di domini possono essere modificati nell'interfaccia di amministrazione di Exchange. Il provisioning e la gestione dei domini si verificano nell'interfaccia di amministrazione di Microsoft 365 e le modifiche vengono riflesse nell'EAC. Per ulteriori informazioni, vedere [Visualizza o modifica domini gestiti in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Corrispondenza sottodomini

In EOP, puoi abilitare il flusso di posta nei sottodomini di un dominio gestito. Per ulteriori informazioni, vedi [Abilitare il flusso di posta nei sottodomini in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>DBEB (Directory Based Edge Blocking)

La funzionalità Directory Based Edge Blocking consente di rifiutare messaggi per destinatari non validi nel perimetro della rete di servizio. DBEB consente agli amministratori di aggiungere destinatari abilitati alla posta elettronica a Microsoft e di bloccare tutti i messaggi inviati a indirizzi di posta elettronica che non sono presenti in Microsoft. Se un messaggio viene inviato a un indirizzo di posta elettronica valido presente in Microsoft, il messaggio prosegue attraverso gli altri livelli del filtro del servizio (antimalware, protezione dalla posta indesiderata, regole di trasporto). Se l'indirizzo non è presente, il servizio blocca il messaggio prima che venga applicato il filtro e un rapporto di mancato recapito viene inviato al mittente per informarlo che il messaggio non è stato recapitato. 
  
L'attivazione DBEB richiede alcuni utenti e la configurazione del dominio. Per ulteriori informazioni, vedere [Utilizzare Directory Based Edge Blocking per rifiutare i messaggi inviati ai destinatari non validi](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
