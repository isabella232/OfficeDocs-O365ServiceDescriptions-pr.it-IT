---
title: Criteri di messaggistica e conformità [descrizione del servizio]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) fornisce criteri di messaggistica e funzionalità di conformità che consentono di gestire i dati della posta elettronica.
ms.openlocfilehash: f88cd016586384f4617cd4899708c811a32af980
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035989"
---
# <a name="messaging-policy-and-complianceservicedesc"></a>Criteri di messaggistica e conformità [descrizione del servizio]

Microsoft Exchange Online Protection (EOP) fornisce criteri di messaggistica e funzionalità di conformità che consentono di gestire i dati della posta elettronica.
  
Per informazioni su tutte le funzionalità di EOP? vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="transport-rules"></a>Regole di trasporto
<a name="BKMK_transportrules"> </a>

Le regole di trasporto offrono la flessibilità di applicare alla posta elettronica i propri criteri specifici. Le regole di trasporto sono costituite da criteri flessibili, che consentono di definire condizioni ed eccezioni, e dalle azioni, che vengono eseguite sulla base di tali criteri. Per ulteriori informazioni sulle regole di trasporto in EOP, vedere [Regole di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320399).
  
## <a name="audit-logging"></a>Registrazione di controllo
<a name="BKMK_auditlogging"> </a>

La registrazione di controllo consente di tracciare modifiche specifiche apportate dagli amministratori all'organizzazione. Tali rapporti consentono di soddisfare i requisiti di conformità, normativi e relativi alle controversie. Per ulteriori informazioni, vedere [Rapporti di controllo in EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).
  
## <a name="data-loss-prevention-dlp"></a>Prevenzione della perdita di dati (DLP)
<a name="BKMK_datalossprevention"> </a>

Non disponibili per gli utenti EOP autonomi. Prevenzione della perdita di dati (DLP) aiuta a identificare, monitorare e proteggere i dati sensibili dell'organizzazione attraverso un'analisi approfondita del contenuto. La prevenzione della perdita dei dati è una funzionalità avanzata che sta diventando sempre più importante per i sistemi di messaggistica aziendali, in quanto i messaggi di posta elettronica business-critical contengono informazioni sensibili che devono protette. La funzionalità di prevenzione della perdita dei dati consente agli amministratori di proteggere i dati sensibili senza influire negativamente sulla produttività degli utenti.
  
È possibile configurare criteri DLP nell'interfaccia di amministrazione di Exchange, per:
  
- Attivare un modello dei criteri preconfigurato che consente di rilevare specifiche tipologie di informazioni sensibili, come i dati PCI-DSS, i dati della legge Gramm-Leach-Bliley o perfino i dati personali in una specifica lingua.
    
- Utilizzare l'efficacia dei criteri e delle azioni delle regole di trasporto esistenti e aggiungere nuove regole.
    
- Testare l'efficacia dei criteri di prevenzione della perdita dei dati prima di metterle in atto.
    
- Incorporare i propri modelli dei criteri di prevenzione della perdita dei dati e i propri tipi di informazioni sensibili.
    
- Rilevare le informazioni sensibili negli allegati dei messaggi, nel testo del corpo del messaggio o nelle righe che contengono l'oggetto del messaggio e regolare il livello di probabilità della presenza di queste informazioni a fronte del quale deve agire.
    
- I dati sensibili vengono rilevati mediante l'impronta digitale del documento. L'impronta digitale del documento facilita la creazione di tipi di informazione sensibili personalizzate basate su moduli di testo utilizzabili per definire le regole di trasporto e i criteri DLP.
    
- Aggiungere dei suggerimenti relativi ai criteri che possono contribuire a ridurre la perdita di dati presentando un avviso agli utenti di Outlook 2013, Outlook Web App e OWA e a migliorare l'efficienza dei criteri applicati permettendo agli utenti di segnalare eventuali falsi positivi.
    
- Analizzare i dati delle operazioni non consentite nei rapporti sulla prevenzione della perdita dei dati oppure aggiungere rapporti personalizzati tramite l'azione di creazione dei rapporti operazioni non consentite.
    
> [!NOTE]
> I criteri DLP vengono applicati solo alla posta che attraversa l'organizzazione. Alla posta interna non vengono applicati criteri DLP a meno che Exchange Server 2013 non venga eseguito localmente con DLP. Questo vale anche per i suggerimenti sui criteri DLP che informano gli utenti di possibili violazioni dei criteri prima che i dati sensibili vengano inviati per errore a destinatari non autorizzati. 
  
Per ulteriori informazioni sulla prevenzione della perdita dei dati (DLP), vedere [Prevenzione della perdita dei dati](https://go.microsoft.com/fwlink/p/?LinkId=320398).
  
## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365
<a name="BKMK_OME_in_EOP"> </a>

Crittografia dei messaggi di Office 365, una parte di Azure Information Protection è un servizio online che consente agli utenti di posta elettronica inviare messaggi di posta elettronica crittografata a tutti gli utenti. Clienti locali possono accedere a Office 365 Message Encryption acquisto Azure Information Protection e utilizzando Exchange Online Protection per impostare il flusso di posta elettronica tramite Exchange Online. Per ulteriori informazioni sulla crittografia dei messaggi di Office 365 in Exchange Online, vedere [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in Exchange Online Service Description. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Funzionalità di conformità e criteri di messaggistica tra opzioni EOP
<a name="BKMK_OME_in_EOP"> </a>

|**Funzionalità**|**EOP autonomo**|**Funzionalità di EOP in Exchange Online**|**Exchange Enterprise CAL con servizi**|
|:-----|:-----|:-----|:-----|
|Regole di trasporto  <br/> |Sì<sup>1</sup> <br/> |Sì<sup>1</sup> <br/> |Sì  <br/> |
|Registrazione di controllo  <br/> |Yes<sup>2</sup> <br/> |Sì  <br/> |Sì  <br/> |
|Prevenzione della perdita di dati (DLP)  <br/> |No  <br/> |Sì  <br/> |Yes<sup>3</sup> <br/> |
|Crittografia dei messaggi di Office 365  <br/> |Yes<sup>4</sup> <br/> |Sì  <br/> |Yes<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> i criteri disponibili e le azioni sono diverse EOP ed Exchange Online. Per un elenco dei criteri disponibili e le azioni in EOP, vedere [Criteri della regola di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320392) e [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393). Per un elenco dei criteri disponibili e le azioni in Exchange Online, vedere [Criteri della regola di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320394) e [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395). > Rapporti di controllo di EOP <sup>2</sup> è un sottoinsieme di Exchange Online controllo report che non includono informazioni sulle cassette postali. > <sup>3</sup> suggerimenti dei criteri DLP non sono disponibili per Exchange Enterprise CAL con i clienti di servizi. > <sup>4</sup> supportato per clienti locali che hanno acquistato il componente aggiuntivo di protezione delle informazioni Azure e utilizzare Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. Per l'esperienza desktop, oltre ai componenti aggiuntivi Azure Information Protection Office 365 ProPlus deve essere acquistato. 
  

