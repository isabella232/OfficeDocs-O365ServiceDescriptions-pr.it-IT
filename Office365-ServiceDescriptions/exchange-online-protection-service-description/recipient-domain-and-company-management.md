---
title: Gestione destinatari, dominio e società
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) sono disponibili diversi metodi di gestione dei destinatari, dominio e informazioni sulla società. Come amministratore, è possibile eseguire alcune attività di gestione nell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguita nell'interfaccia di amministrazione di Microsoft Office 365.
ms.openlocfilehash: 17a87a85611dc286e3d19eaeefe04466a1ac62d0
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036121"
---
# <a name="recipient-domain-and-company-management"></a>Gestione destinatari, dominio e società

Microsoft Exchange Online Protection (EOP) sono disponibili diversi metodi di gestione dei destinatari, dominio e informazioni sulla società. Come amministratore, è possibile eseguire alcune attività di gestione nell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguita nell'interfaccia di amministrazione di Microsoft Office 365.
  
Per informazioni su tutte le funzionalità di EOP? vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>destinatari posta
<a name="BKMK_mailrecipients"> </a>

I destinatari di posta elettronica vengono classificati come utenti o gruppi di posta elettronica e possono essere gestiti attraverso la sincronizzazione di directory, direttamente nella EAC o in remoto Windows PowerShell. Se i destinatari vengono gestiti in locale, è necessario eseguire la sincronizzazione della directory affinché i destinatari di posta elettronica vengano visualizzati nell'interfaccia di amministrazione di Exchange. Gli utenti gestiti esclusivamente nell'interfaccia di amministrazione di Office 365 non sono disponibili in EAC, ma possono essere aggiunti o rimossi dall'appartenenza in un gruppo ruolo amministratore in EAC. Per ulteriori informazioni sui destinatari in EOP, vedere [Destinatario in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Autorizzazioni del gruppo di ruolo Admin
<a name="BKMK_adminrolegrouppermissions"> </a>

In EOP, è possibile configurare solo ruoli amministrativi. Gli utenti possono essere aggiunti e rimossi da gruppi di regole predefinite direttamente in EAC. Non è disponibile alcuna personalizzazione RBAC. Per ulteriori informazioni, vedere [Gestione autorizzazioni gruppo di ruoli di amministratore in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Gestione del dominio
<a name="BKMK_domainmanagement"> </a>

I domini gestiti sono quelli protetti da EOP. I domini gestiti possono essere visualizzati e i tipi di domini possono essere modificati nell'interfaccia di amministrazione di Exchange. La gestione e il provisioning del dominio avvengono nell'interfaccia di amministrazione di Office 365 admin center e le modifiche vengono riflesse in EAC. Per ulteriori informazioni, vedere [Visualizza o modifica domini gestiti in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Corrispondenza sottodomini
<a name="BKMK_EOP_Match_Subdomains"> </a>

In EOP, puoi abilitare il flusso di posta nei sottodomini di un dominio gestito. Per ulteriori informazioni, vedi [Abilitare il flusso di posta nei sottodomini in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>DBEB (Directory Based Edge Blocking)
<a name="BKMK_DBEB"> </a>

La funzionalità Directory Based Edge Blocking consente di rifiutare messaggi per destinatari non validi nel perimetro della rete di servizio. DBEB consente agli amministratori di aggiungere destinatari a Office 365 e bloccare tutti i messaggi inviati a indirizzi di posta elettronica che non sono presenti in Office 365. Se un messaggio viene inviato a un indirizzo di posta elettronica valido presente in Office 365, il messaggio passa attraverso gli altri livelli del filtro del servizio (antimalware, antispam, regole di trasporto). Se l'indirizzo non è presente, il servizio blocca il messaggio prima che venga applicato il filtro e un rapporto di mancato recapito viene inviato al mittente per informarlo che il messaggio non è stato recapitato. 
  
L'attivazione DBEB richiede alcuni utenti e la configurazione del dominio. Per ulteriori informazioni, vedere [Utilizzare Directory Based Edge Blocking per rifiutare i messaggi inviati ai destinatari non validi](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità
<a name="BKMK_DBEB"> </a>

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  

