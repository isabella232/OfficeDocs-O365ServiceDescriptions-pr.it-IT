---
title: Criteri di messaggistica e conformità
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) fornisce funzionalità di conformità e criteri di messaggistica che consentono di gestire i dati della posta elettronica.
ms.openlocfilehash: a37ad3c1bcecb73f7c903b553bdcb43935dc9ed7
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246122"
---
# <a name="messaging-policy-and-compliance"></a>Criteri di messaggistica e conformità

Microsoft Exchange Online Protection (EOP) fornisce funzionalità di conformità e criteri di messaggistica che consentono di gestire i dati della posta elettronica.
  
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

La crittografia dei messaggi di Office 365, una parte di Azure Information Protection, è un servizio online che consente agli utenti di posta elettronica di inviare messaggi di posta elettronica crittografati a qualsiasi utente. I clienti locali possono accedere alla crittografia dei messaggi di Office 365 acquistando Azure Information Protection e utilizzando Exchange Online Protection per impostare il flusso di posta attraverso Exchange Online. Per ulteriori informazioni sulla crittografia messaggi di Office 365 in Exchange Online, vedere [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) nella descrizione del servizio Exchange Online. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Funzionalità di conformità e criteri di messaggistica tra opzioni EOP
<a name="BKMK_OME_in_EOP"> </a>

|**Funzionalità**|**EOP autonomo**|**Funzionalità di EOP in Exchange Online**|**Exchange Enterprise CAL con servizi**|
|:-----|:-----|:-----|:-----|
|Regole di trasporto  <br/> |Sì<sup>1</sup> <br/> |Sì<sup>1</sup> <br/> |Sì  <br/> |
|Registrazione di controllo  <br/> |Sì<sup>2</sup> <br/> |Sì  <br/> |Sì  <br/> |
|Prevenzione della perdita di dati (DLP)  <br/> |No  <br/> |Sì  <br/> |Sì<sup>3</sup> <br/> |
|Crittografia dei messaggi di Office 365  <br/> |Sì<sup>4</sup> <br/> |Sì  <br/> |Sì<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> I criteri e le azioni disponibili in EOP e in Exchange Online sono diversi. Per un elenco dei criteri e delle azioni disponibili in EOP, vedere [Criteri delle regole di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320392) e [Azioni delle regole di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320393). [](https://go.microsoft.com/fwlink/p/?LinkId=320394)[5](https://go.microsoft.com/fwlink/p/?LinkId=320395) I report di controllo di Exchange Online corrispondono a un sottoinsieme dei report di controllo di Exchange Online che non includono informazioni sulle cassette postali. <br/>
> <sup>2</sup> I report di controllo di EOP corrispondono a un sottoinsieme dei report di controllo di Exchange Online che non includono informazioni sulle cassette postali. <br/>
> <sup>3</sup> I suggerimenti relativi ai criteri DLP non sono disponibili per i clienti che dispongono di Exchange Enterprise CAL with Services. <br/>
> <sup>4</sup> supportato per i clienti locali che acquistano il componente aggiuntivo di Azure Information Protection e utilizzano Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. Per l'esperienza desktop, oltre al componente aggiuntivo di Azure Information Protection, è necessario acquistare Office 365 ProPlus. <br/>
  

