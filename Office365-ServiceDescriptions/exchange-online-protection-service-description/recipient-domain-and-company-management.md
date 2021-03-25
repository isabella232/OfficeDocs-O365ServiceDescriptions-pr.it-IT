---
title: Gestione di destinatari, domini e società in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Leggere questo articolo per informazioni sulla gestione di destinatari, domini e società in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: a01d572ce239e7d1a6c0c57814fb7494a6670f84
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173721"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Gestione di destinatari, domini e società in Exchange Online Protection

Microsoft Exchange Online Protection (EOP) offre diversi strumenti per gestire le informazioni relative a destinatari, domini e società. In quanto amministratore, è possibile eseguire determinate attività di gestione nell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguite nell'interfaccia di amministrazione di Microsoft 365.
  
Per informazioni su tutte le funzionalità di EOP? Vedere la [descrizione del servizio Exchange Online Protection.](exchange-online-protection-service-description.md)
  
## <a name="mail-recipients"></a>Mail recipients

I destinatari di posta elettronica vengono classificati come utenti o gruppi di posta elettronica e possono essere gestiti attraverso la sincronizzazione di directory, direttamente nella EAC o in remoto Windows PowerShell. Se i destinatari vengono gestiti in locale, è necessario eseguire la sincronizzazione della directory affinché i destinatari di posta elettronica vengano visualizzati nell'interfaccia di amministrazione di Exchange. Gli utenti gestiti esclusivamente nell'interfaccia di amministrazione di Microsoft 365 non sono visualizzabili nell'interfaccia di amministrazione di Exchange, ma possono essere aggiunti o rimossi dall'appartenenza a un gruppo di ruoli amministratore nell'interfaccia di amministrazione di Exchange. Per ulteriori informazioni sui destinatari in EOP, vedere [Destinatario in EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

In EOP, è possibile configurare solo ruoli amministrativi. Gli utenti possono essere aggiunti e rimossi da gruppi di regole predefinite direttamente in EAC. Non è disponibile alcuna personalizzazione RBAC. Per ulteriori informazioni, vedere [Gestione autorizzazioni gruppo di ruoli di amministratore in EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).
  
## <a name="domain-management"></a>Gestione del dominio

I domini gestiti sono quelli protetti da EOP. I domini gestiti possono essere visualizzati e i tipi di domini possono essere modificati nell'interfaccia di amministrazione di Exchange. Il provisioning e la gestione del dominio si verificano nell'interfaccia di amministrazione di Microsoft 365 e le modifiche si riflettono nell'interfaccia di amministrazione di Exchange. Per ulteriori informazioni, vedere [Visualizza o modifica domini gestiti in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).
  
## <a name="match-subdomains"></a>Corrispondenza sottodomini

In EOP, puoi abilitare il flusso di posta nei sottodomini di un dominio gestito. Per ulteriori informazioni, vedi [Abilitare il flusso di posta nei sottodomini in EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>DBEB (Directory Based Edge Blocking)

La funzionalità Directory Based Edge Blocking consente di rifiutare messaggi per destinatari non validi nel perimetro della rete di servizio. DBEB consente agli amministratori di aggiungere destinatari abilitati alla posta elettronica a Microsoft e di bloccare tutti i messaggi inviati a indirizzi di posta elettronica non presenti in Microsoft. Se un messaggio viene inviato a un indirizzo di posta elettronica valido presente in Microsoft, il messaggio continua attraverso il resto dei livelli di filtro del servizio (antimalware, protezione da posta indesiderata, regole di trasporto). Se l'indirizzo non è presente, il servizio blocca il messaggio prima che venga applicato il filtro e un rapporto di mancato recapito viene inviato al mittente per informarlo che il messaggio non è stato recapitato. 
  
L'attivazione DBEB richiede alcuni utenti e la configurazione del dominio. Per ulteriori informazioni, vedere [Utilizzare Directory Based Edge Blocking per rifiutare i messaggi inviati ai destinatari non validi](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Descrizione del servizio [Exchange Online Protection.](exchange-online-protection-service-description.md)