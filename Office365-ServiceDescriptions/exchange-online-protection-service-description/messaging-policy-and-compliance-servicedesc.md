---
title: Criteri di messaggistica e conformità in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Leggere questo articolo per informazioni sui criteri di messaggistica e sulle funzionalità di conformità in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 8bd7b752191f6304d95f079984a281b25169352f
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672307"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Criteri di messaggistica e conformità in Exchange Online Protection

Microsoft Exchange Online Protection (EOP) fornisce criteri di messaggistica e funzionalità di conformità che consentono di gestire i dati di posta elettronica.

Per informazioni su tutte le funzionalità di EOP? Vedere la [descrizione Exchange Online Protection servizio.](exchange-online-protection-service-description.md)

## <a name="mail-flow-rules"></a>Regole del flusso di posta

Le regole del flusso di posta (note anche come regole di trasporto) offrono la flessibilità di applicare criteri specifici dell'azienda alla posta elettronica. Le regole del flusso di posta sono basate su criteri flessibili, che consentono di definire condizioni, eccezioni e azioni da eseguire in base ai criteri. Per ulteriori informazioni, vedere [Mail flow rules (transport rules) in Exchange Online Protection](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Registrazione di controllo

La registrazione di controllo consente di tracciare modifiche specifiche apportate dagli amministratori all'organizzazione. Tali rapporti consentono di soddisfare i requisiti di conformità, normativi e relativi alle controversie. Per ulteriori informazioni, vedere [Report di controllo in EOP](/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Prevenzione della perdita di dati (DLP)

Non disponibili per gli utenti EOP autonomi. Prevenzione della perdita di dati (DLP) aiuta a identificare, monitorare e proteggere i dati sensibili dell'organizzazione attraverso un'analisi approfondita del contenuto. La prevenzione della perdita dei dati è una funzionalità avanzata che sta diventando sempre più importante per i sistemi di messaggistica aziendali, in quanto i messaggi di posta elettronica business-critical contengono informazioni sensibili che devono protette. La funzionalità DLP consente di proteggere i dati sensibili senza influire sulla produttività dei lavoratori.

È possibile configurare criteri DLP nell'interfaccia di amministrazione di Exchange, per:

- Attivare un modello dei criteri preconfigurato che consente di rilevare specifiche tipologie di informazioni sensibili, come i dati PCI-DSS, i dati della legge Gramm-Leach-Bliley o perfino i dati personali in una specifica lingua.

- Utilizzare l'intera potenza delle azioni e dei criteri delle regole del flusso di posta esistente e aggiungere nuove regole del flusso di posta.

- Testare l'efficacia dei criteri di prevenzione della perdita dei dati prima di metterle in atto.

- Incorporare i propri modelli dei criteri di prevenzione della perdita dei dati e i propri tipi di informazioni sensibili.

- Rilevare le informazioni sensibili negli allegati dei messaggi, nel testo del corpo del messaggio o nelle righe che contengono l'oggetto del messaggio e regolare il livello di probabilità della presenza di queste informazioni a fronte del quale deve agire.

- I dati sensibili vengono rilevati mediante l'impronta digitale del documento. L'impronta digitale dei documenti consente di creare facilmente tipi di informazioni riservate personalizzati basati su moduli basati su testo che è possibile utilizzare per definire le regole del flusso di posta e i criteri DLP.

- Aggiungi Suggerimenti criteri, che consente di ridurre la perdita di dati visualizzando un avviso per gli utenti di Outlook 2013, Outlook sul web e OWA per dispositivi e può anche migliorare l'efficacia dei criteri consentendo la segnalazione di falsi positivi.

- Analizzare i dati delle operazioni non consentite nei rapporti sulla prevenzione della perdita dei dati oppure aggiungere rapporti personalizzati tramite l'azione di creazione dei rapporti operazioni non consentite.

> [!NOTE]
> I criteri DLP vengono applicati solo alla posta che attraversa l'organizzazione. Alla posta interna non vengono applicati criteri DLP a meno che Exchange Server 2013 non venga eseguito localmente con DLP. Questo vale anche per i suggerimenti sui criteri DLP che informano gli utenti di possibili violazioni dei criteri prima che i dati sensibili vengano inviati per errore a destinatari non autorizzati.

Per ulteriori informazioni sulla prevenzione della perdita dei dati, vedere Prevenzione della perdita dei [dati in Exchange Online](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Office 365 Message Encryption, parte di Azure Information Protection, è un servizio online che consente agli utenti di posta elettronica di inviare messaggi di posta elettronica crittografati a chiunque. I clienti locali possono accedere Office 365 Message Encryption acquistando Azure Information Protection e usando Exchange Online Protection per configurare il flusso di posta attraverso Exchange Online. Per altre informazioni sulle Office 365 Message Encryption in Exchange Online, vedere [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) nella descrizione Exchange Online servizio.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Funzionalità di conformità e criteri di messaggistica tra opzioni EOP

| Funzionalità | EOP autonomo | Funzionalità di EOP in <br/> Exchange Online | Exchange Enterprise <br/> CAL con servizi |
|:-----|:-----|:-----|:-----|
|Regole del flusso di posta|Sì<sup>1</sup>|Sì<sup>1</sup>|Sì<sup>1, 3</sup>|
|Registrazione di controllo|Sì<sup>2</sup>|Sì|Sì|
|Prevenzione della perdita di dati (DLP)|No|Sì|Sì<sup>3</sup>|
|Crittografia dei messaggi di Office 365|Sì<sup>4</sup>|Sì|Sì<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> Le condizioni, le eccezioni e le azioni delle regole del flusso di posta disponibili sono leggermente diverse tra EOP e Exchange Online. Queste differenze vengono notate nelle condizioni e nelle eccezioni delle regole del flusso di posta [(predicati) in](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) Exchange Online e nelle azioni delle regole del flusso di posta [in Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions). <br/>
> <sup>2</sup> I report di controllo di EOP corrispondono a un sottoinsieme dei report di controllo di Exchange Online che non includono informazioni sulle cassette postali.<br/>
> <sup>3</sup> I suggerimenti relativi ai criteri DLP non sono disponibili per i clienti che dispongono di Exchange Enterprise CAL with Services.<br/>
> <sup>4</sup> Supportato per i clienti locali che acquistano il componente aggiuntivo Azure Information Protection e usano Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. Per l'esperienza desktop, oltre al componente aggiuntivo Azure Information Protection, è necessario Microsoft 365 Apps for enterprise acquisto. <br/>