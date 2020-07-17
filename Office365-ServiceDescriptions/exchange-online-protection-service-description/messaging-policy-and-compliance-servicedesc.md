---
title: Criteri di messaggistica e conformità
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) fornisce funzionalità di conformità e criteri di messaggistica che consentono di gestire i dati della posta elettronica.
ms.openlocfilehash: 53997df9a3e5de8b8b2e319f6e4c36382e4db412
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132790"
---
# <a name="messaging-policy-and-compliance"></a>Criteri di messaggistica e conformità

Microsoft Exchange Online Protection (EOP) fornisce funzionalità di conformità e criteri di messaggistica che consentono di gestire i dati della posta elettronica.

Per informazioni su tutte le funzionalità di EOP? Vedere la [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).

## <a name="mail-flow-rules"></a>Regole del flusso di posta

Le regole del flusso di posta (note anche come regole di trasporto) offrono la flessibilità di applicare ai messaggi di posta elettronica i propri criteri specifici per la società. Le regole del flusso di posta sono costituite da criteri flessibili, che consentono di definire le condizioni, le eccezioni e le azioni da intraprendere in base ai criteri. Per ulteriori informazioni, vedere [regole del flusso di posta (regole di trasporto) in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Registrazione di controllo

La registrazione di controllo consente di tracciare modifiche specifiche apportate dagli amministratori all'organizzazione. Tali rapporti consentono di soddisfare i requisiti di conformità, normativi e relativi alle controversie. Per ulteriori informazioni, vedere [Report di controllo in EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Prevenzione della perdita di dati (DLP)

Non disponibili per gli utenti EOP autonomi. Prevenzione della perdita di dati (DLP) aiuta a identificare, monitorare e proteggere i dati sensibili dell'organizzazione attraverso un'analisi approfondita del contenuto. La prevenzione della perdita dei dati è una funzionalità avanzata che sta diventando sempre più importante per i sistemi di messaggistica aziendali, in quanto i messaggi di posta elettronica business-critical contengono informazioni sensibili che devono protette. La funzionalità DLP consente di proteggere i dati sensibili senza influire sulla produttività dei lavoratori.

È possibile configurare criteri DLP nell'interfaccia di amministrazione di Exchange, per:

- Attivare un modello dei criteri preconfigurato che consente di rilevare specifiche tipologie di informazioni sensibili, come i dati PCI-DSS, i dati della legge Gramm-Leach-Bliley o perfino i dati personali in una specifica lingua.

- Utilizzare l'intera potenza dei criteri e delle azioni della regola del flusso di posta esistente e aggiungere nuove regole del flusso di posta.

- Testare l'efficacia dei criteri di prevenzione della perdita dei dati prima di metterle in atto.

- Incorporare i propri modelli dei criteri di prevenzione della perdita dei dati e i propri tipi di informazioni sensibili.

- Rilevare le informazioni sensibili negli allegati dei messaggi, nel testo del corpo del messaggio o nelle righe che contengono l'oggetto del messaggio e regolare il livello di probabilità della presenza di queste informazioni a fronte del quale deve agire.

- I dati sensibili vengono rilevati mediante l'impronta digitale del documento. L'impronta digitale dei documenti consente di creare facilmente tipi di informazioni riservate personalizzate in base ai moduli basati su testo che è possibile utilizzare per definire le regole del flusso di posta e i criteri DLP.

- Aggiungere suggerimenti per i criteri, che possono contribuire a ridurre la perdita di dati visualizzando un avviso per gli utenti di Outlook 2013, Outlook sul Web e OWA per i dispositivi e può anche migliorare l'efficacia dei criteri consentendo la creazione di report falsi positivi.

- Analizzare i dati delle operazioni non consentite nei rapporti sulla prevenzione della perdita dei dati oppure aggiungere rapporti personalizzati tramite l'azione di creazione dei rapporti operazioni non consentite.

> [!NOTE]
> I criteri DLP vengono applicati solo alla posta che attraversa l'organizzazione. Alla posta interna non vengono applicati criteri DLP a meno che Exchange Server 2013 non venga eseguito localmente con DLP. Questo vale anche per i suggerimenti sui criteri DLP che informano gli utenti di possibili violazioni dei criteri prima che i dati sensibili vengano inviati per errore a destinatari non autorizzati.

Per ulteriori informazioni su DLP, vedere [prevenzione della perdita dei dati in Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

La crittografia dei messaggi di Office 365, una parte di Azure Information Protection, è un servizio online che consente agli utenti di posta elettronica di inviare messaggi di posta elettronica crittografati a qualsiasi utente. I clienti locali possono accedere alla crittografia dei messaggi di Office 365 acquistando Azure Information Protection e utilizzando Exchange Online Protection per impostare il flusso di posta attraverso Exchange Online. Per ulteriori informazioni sulla crittografia dei messaggi di Office 365 in Exchange Online, vedere [crittografia dei messaggi di office 365](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) nella descrizione del servizio Exchange Online.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Funzionalità di conformità e criteri di messaggistica tra opzioni EOP

|**Funzionalità**|**EOP autonomo**|**Funzionalità di EOP in <br/> Exchange Online**|**Exchange Enterprise <br/> CAL con servizi**|
|:-----|:-----|:-----|:-----|
|Regole del flusso di posta|Sì<sup>1</sup>|Sì<sup>1</sup>|Sì<sup>1, 3</sup>|
|Registrazione di controllo|Sì<sup>2</sup>|Sì|Sì|
|Prevenzione della perdita di dati (DLP)|No|Sì|Sì<sup>3</sup>|
|Crittografia dei messaggi di Office 365|Sì<sup>4</sup>|Sì|Sì<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> le condizioni, le eccezioni e le azioni delle regole del flusso di posta disponibili differiscono leggermente tra EOP e Exchange Online. Queste differenze sono indicate nelle [condizioni ed eccezioni (predicati) delle regole del flusso di posta in](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) Exchange Online e le [azioni delle regole del flusso di posta in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions). <br/>
> <sup>2</sup> I report di controllo di EOP corrispondono a un sottoinsieme dei report di controllo di Exchange Online che non includono informazioni sulle cassette postali. <br/>
> <sup>3</sup> I suggerimenti relativi ai criteri DLP non sono disponibili per i clienti che dispongono di Exchange Enterprise CAL with Services. <br/>
> <sup>4</sup> supportato per i clienti locali che acquistano il componente aggiuntivo di Azure Information Protection e utilizzano Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. Per l'esperienza desktop, oltre al componente aggiuntivo di Azure Information Protection, è necessario acquistare le app Microsoft 365 per l'organizzazione. <br/>
