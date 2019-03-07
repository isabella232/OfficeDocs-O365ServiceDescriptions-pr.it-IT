---
title: Autorizzazioni
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online utilizza un modello di controllo dell'accesso basato sui ruoli per consentire agli amministratori dell'organizzazione di controllare capillarmente ciò che gli utenti e i dipendenti IT possono fare nell'ambito del servizio. A esempio, se un funzionario addetto alla conformità è responsabile per le richieste di ricerca nelle cassette postali, l'amministratore può delegare la propria funzionalità amministrativa a questo funzionario tramite il controllo dell'accesso basato sui ruoli. Exchange Online utilizza la stessa struttura di controllo dell'accesso basato sui ruoli di Microsoft Exchange Server 2013.
ms.openlocfilehash: 9f7cad7587d3700971a9cedaf38a20161f203c01
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/07/2019
ms.locfileid: "30468133"
---
# <a name="permissions"></a>Autorizzazioni

Microsoft Exchange Online utilizza un modello di controllo dell'accesso basato sui ruoli per consentire agli amministratori dell'organizzazione di controllare capillarmente ciò che gli utenti e i dipendenti IT possono fare nell'ambito del servizio. A esempio, se un funzionario addetto alla conformità è responsabile per le richieste di ricerca nelle cassette postali, l'amministratore può delegare la propria funzionalità amministrativa a questo funzionario tramite il controllo dell'accesso basato sui ruoli. Exchange Online utilizza la stessa struttura di controllo dell'accesso basato sui ruoli di Microsoft Exchange Server 2013. 
  
Al livello più alto, il controllo dell'accesso basato sui ruoli è costituito da ruoli di gestione, gruppi di ruoli di gestione e criteri di assegnazione dei ruoli di gestione. Le seguenti sezioni forniscono ulteriori informazioni su ciascun componente del controllo dell'accesso basato sui ruoli.
  
Per ulteriori informazioni sul modello di autorizzazioni per il controllo dell'accesso basato sui ruoli utilizzato in Exchange Online, vedere [Autorizzazioni](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Autorizzazioni basate sui ruoli

In Exchange Online, le autorizzazione che vengono concesse agli amministratori e agli utenti sono basate sui ruoli di gestione. Un ruolo definisce l'insieme di attività che un amministratore o un utente sono in grado di eseguire. Ad esempio, il ruolo di gestione denominato  `Mail Recipients` definisce le attività che una persona può eseguire per un insieme di cassette postali, contatti e gruppi di distribuzione. Quando viene assegnato un ruolo a un amministratore o a un utente, alla persona vengono concesse le autorizzazioni fornite dal ruolo. 
  
Esistono due tipi di ruoli, ruoli amministrativi e ruoli dell'utente finale:
  
- **Ruoli amministrativi** Tali ruoli contengono le autorizzazioni che possono essere assegnate agli amministratori o a utenti esperti che utilizzano i gruppi di ruoli che si occupano della gestione di una parte dell'organizzazione Exchange Online, ad esempio destinatari, server o database. 
    
- **Ruoli dell'utente finale** Tali ruoli, assegnati mediante i criteri di assegnazione, consentono agli utenti di gestire vari aspetti delle proprie cassette postali e dei gruppi di distribuzione di cui sono proprietari. I ruoli dell'utente finale iniziano con il prefisso  `My`.
    
I ruoli definiscono le autorizzazioni che consentono ad amministratori e utenti di eseguire le attività rendendo disponibili i cmdlet per coloro ai quali sono stati assegnati quei ruoli. Poiché nell'interfaccia di amministrazione di Exchange e in Exchange Management Shell vengono utilizzati i cmdlet per gestire Exchange Online, la concessione dell'accesso a un cmdlet consente all'amministratore o all'utente di eseguire l'attività in ogni singola interfaccia di gestione di Exchange Online.
  
Le autorizzazioni basate sui ruoli di Microsoft Online Services si sovrappongono a quelle di Exchange Online in due diversi modi. Come prima cosa, gli utenti designati come amministratori globali o amministratori dei servizi in Microsoft Online vengono automaticamente assegnati al gruppo del ruolo Gestione organizzazione in Exchange Online. Come seconda cosa, gli utenti designati come amministratori dell'assistenza tecnica in Microsoft Online vengono automaticamente assegnati al gruppo del ruolo Assistenza tecnica in Exchange Online. In caso contrario, i due modelli di sicurezza vengono gestiti separatamente.
  
> [!IMPORTANT]
> Alcuni dei ruoli disponibili nella versione locale di Microsoft Exchange Server 2013 potrebbero non essere disponibili in Exchange Online. 
  
Per ulteriori informazioni sulle autorizzazioni in Exchange Online, vedere [Autorizzazioni basate sui ruoli](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Gruppi di ruoli

I gruppi di ruoli di gestione associano i ruoli di gestione a un gruppo di amministratori o utenti esperti. Gli amministratori gestiscono una configurazione del destinatario o dell'organizzazione di Exchange Online su vasta scala. Gli utenti specialisti gestiscono funzionalità specifiche di Exchange Online, come, ad esempio, la conformità, oppure possono avere capacità di gestione limitate, ad esempio, come membri dell'assistenza tecnica, ma senza autorizzazioni di gestione troppo ampie. I gruppi di ruoli in genere associano ruoli di gestione amministrativi che consentono agli amministratori e agli utenti esperti di gestire la configurazione dell'organizzazione e i destinatari. Ad esempio, la possibilità per gli amministratori di gestire i destinatari o di utilizzare le funzionalità di individuazione delle cassette postali viene controllata per mezzo dei gruppi di ruolo. 
  
> [!IMPORTANT]
> Alcuni dei gruppi di ruolo disponibili nella versione locale di Microsoft Exchange Server 2013 potrebbero non essere disponibili in Exchange Online. 
  
Per ulteriori informazioni sui gruppi di ruolo, vedere [Gruppi di ruolo e criteri di assegnazione dei ruoli](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Criteri di assegnazione dei ruoli

I criteri di assegnazione del ruolo di gestione consentono di associare i ruoli di gestione degli utenti finali agli utenti. I criteri di assegnazione di ruolo sono costituiti da ruoli che controllano le operazioni consentite agli utenti sulle loro cassette postali o sui loro gruppi di distribuzione. Questi ruoli non consentono la gestione delle funzionalità che non sono direttamente associate all'utente. Quando si crea un criterio di assegnazione del ruolo, è necessario definire tutte le operazioni che un utente può eseguire sulla sua cassetta postale. Ad esempio, un criterio di assegnazione di un ruolo potrebbe consentire a un utente di impostare il nome visualizzato, predisporre il sistema di caselle vocali e configurare le regole di Posta in arrivo. Un altro criterio di assegnazione di ruolo potrebbe consentire a un utente di cambiare l'indirizzo, utilizzare l'invio di SMS e configurare gruppi di distribuzioni. A ciascun utente con una cassetta postale di Exchange Online, inclusi gli amministratori, vengono assegnati dei criteri di assegnazione dei ruoli per impostazione predefinita. Si può decidere quali criteri di assegnazione dei ruoli devono essere assegnati per impostazione predefinita, scegliere il contenuto dei criteri di assegnazione dei ruoli predefiniti, ignorare l'impostazione predefinita di alcune cassette postali o non assegnare criteri di assegnazione dei ruoli.
  
> [!IMPORTANT]
> Alcune assegnazioni di ruolo disponibili nella versione locale di Microsoft Exchange Server 2013 potrebbero non essere disponibili in Exchange Online. 
  
Per ulteriori informazioni sui criteri di assegnazione dei ruoli, vedere [Gruppi di ruolo e criteri di assegnazione dei ruoli](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

