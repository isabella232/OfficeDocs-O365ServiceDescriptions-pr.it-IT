---
title: Office 365 GCC High e DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Informazioni sugli impegni e sulle differenze univoci degli Office 365 GCC High e DoD rispetto all'ambiente Office 365 commerciale.
ms.openlocfilehash: e23093e2fdebad45175746aa57bedc0c87728d4b
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670331"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High e DoD

Per soddisfare i requisiti univoci e in evoluzione del Dipartimento della Difesa degli Stati Uniti, così come gli appaltatori che deteneno o elaborano informazioni non classificate controllate da DoD (CUI) o soggetti alle normative ITAR (International Traffic in Arms Regulations), Microsoft offre ambienti GCC High e DoD. Disponibili attraverso contratti multilicenza, le organizzazioni interessate portano avanti una procedura di convalida per verificare l'idoneità prima che venga definito un ambiente. Al momento, non sono disponibili versioni di valutazione. 
  
Coinvolgere il team dell'account o il partner preferito per saperne di più o avviare il processo di convalida. Per ulteriori informazioni su come acquistare, [vedere Microsoft 365 Government - How to Buy](./microsoft-365-government-how-to-buy.md).
  
## <a name="how-to-use-this-service-description"></a>Come utilizzare la descrizione del servizio

La Office 365 descrizione del servizio us government è progettata per fungere da sovrimpressione alla descrizione generale Office 365 servizio. Definisce gli impegni e le differenze univoci rispetto alle Office 365 offerte aziendali.
  
## <a name="compliance"></a>Conformità

GCC High e DoD rispettano i requisiti di conformità previsti per le certificazioni e gli accrediti seguenti: 
  
- Federal Risk and Authorization Management Program presso FedRAMP High, inclusi i controlli di sicurezza e i miglioramenti del controllo, come descritto nella pubblicazione speciale NIST (National Institute of Standards and Technology) 800-53.
    
- I controlli di sicurezza e i miglioramenti del controllo per la United States Department of Defense Cloud Computing Security Requirements Guide (SRG) in merito alle informazioni con livello di impatto massimo pari a 5 (L5).
    
Gli abbonati a Office 365 che fanno capo al Dipartimento della Difesa potranno usare i servizi offerti dall'ambiente esclusivo del Dipartimento che rientra nel DOD SRG L5. Gli abbonati non del Dipartimento della Difesa riceveranno servizi dall'ambiente us government defense che viene valutato su L5, ma usa la segmentazione L4.
  
## <a name="background-screening"></a>Screening in background

Il personale Office 365 non ha un accesso diretto all'ambiente di produzione per GCC High e DoD. Tutti i membri del personale che richiedono l'elevazione temporanea delle autorizzazioni che concedono l'accesso al contenuto del cliente devono prima aver superato i controlli in background seguenti.<br><br>
  
| Screening del personale Microsoft e controlli in background<sup>1</sup> | Descrizione |
|:-----|:-----|
|Cittadinanza negli Stati Uniti  <br/> |Verifica della cittadinanza negli Stati Uniti  <br/> |
|Controllo della storia professionale  <br/> |Verifica della storia professionale degli ultimi sette (7) anni  <br/> |
|Verifica dell'istruzione  <br/> |Verifica del livello massimo raggiunto  <br/> |
|Ricerca del numero di previdenza sociale (SSN)  <br/> |Verifica della validità del numero di previdenza sociale (SSN) fornito  <br/> |
|Controllo di precedenti penali  <br/> |Un controllo dei precedenti penali relativo agli ultimi sette (7) anni per rilevare eventuali infrazioni o reati a livello statale, provinciale, locale e federale  <br/> |
|Office of Foreign Assets Control List (OFAC)  <br/> |Convalida relativa agli elenchi del Dipartimento del Tesoro degli Stati Uniti d'America dei gruppi con cui i cittadini statunitensi non possono avere transazioni commerciali o finanziarie  <br/> |
|Bureau of Industry and Security List (BIS)  <br/> |Convalida rispetto all'elenco del Dipartimento del Commercio degli Stati Uniti d'America di soggetti ed entità che non possono effettuare attività di esportazione  <br/> |
|Office of Defense Trade Controls Debarred Persons List (DDTC)  <br/> |Convalida rispetto all'elenco del Dipartimento di Stato di soggetti ed entità che non possono effettuare attività di esportazione correlate al settore della difesa  <br/> |
|Controllo delle impronte digitali  <br/> |Controllo delle impronte digitali rispetto ai database dell'FBI  <br/> |
|Department of Defense IT-2  <br/> |I dipendenti del Dipartimento che richiedono autorizzazioni elevate per i dati dei clienti oppure accesso amministrativo con privilegi alle funzionalità del servizio Dept of Defense SRG L5 devono attendere la decisione del Defense IT-2, che si basa sul superamento di un'indagine OPM Tier 3  <br/> |

<sup>1</sup> Si applica solo al personale con accesso temporaneo o permanente ai contenuti dei clienti ospitati Office 365 cloud GCC-High o DOD.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Dettagli sulle caratteristiche basate sull'architettura cloud conforme

Le sottoscrizioni negli GCC High e DoD includono le funzionalità Exchange Online, SharePoint e Skype for Business principali. Considerando l'aumento di certificazione e accredito dell'infrastruttura, sono presenti alcune differenze tra le offerte Office 365 commerciali e quelle disponibili in GCC High e DoD.
  
### <a name="exchange-online"></a>Exchange Online

 **Supporto della Messaggistica unificata di Exchange Online per IP-PBX locale** - Il supporto per l'integrazione di sistemi IP-PBX locali con la Messaggistica unificata di Exchange Online non è incluso nelle sottoscrizioni di GCC High e DoD. 
  
### <a name="file-sharing"></a>Condivisione di file

Gli utenti hanno più opzioni per la condivisione di file e cartelle in SharePoint e OneDrive. Tutte le opzioni sono disponibili negli ambienti GCC High e DoD. Per ulteriori informazioni sulla gestione di queste opzioni, vedere [Gestire le impostazioni di condivisione.](/sharepoint/turn-external-sharing-on-or-off) Gli utenti GCC-High potranno condividere solo con altre organizzazioni in GCC-High. Inoltre, gli indirizzi di posta elettronica non GCC elevati allegati ai profili utente non sono supportati e non consentono l'invio di messaggi di avviso. Ad esempio, all'utente A locale viene assegnato un indirizzo di posta elettronica Gmail e quindi sincronizzato con un'organizzazione di Azure GCC High. L'utente A passa a una raccolta e crea un avviso per eventuali modifiche. L'avviso non verrà inviato all'indirizzo Gmail.

> [!NOTE]
> Gli utenti GCC-High non sono attualmente in grado di condividere con gli utenti nelle organizzazioni non GCC High.

[Le richieste](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) di file non sono disponibili per Office 365 Government.

### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN Calling &amp; PSTN Conferencing** - Due to the requirement to use the Public Switched Telephone Network (PSTN) for telephony-oriented services, PSTN Calling &amp; PSTN Conferencing services are currently not available in GCC High and DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Sistema telefonico e audioconferenza (tramite** routing diretto): Sistema telefonico e audioconferenza per ambienti GCC High e DoD vengono recapitati tramite routing diretto. Per ulteriori informazioni, vedere la documentazione del livello di servizio qui:

- [Sistema telefonico tramite routing diretto](/microsoftteams/here-s-what-you-get-with-phone-system)
- [Audioconferenza con Instradamento diretto per GCC High e DoD](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identità

L'autenticazione a più fattori che utilizza un modello di identità federata consente di utilizzare le schede PIV e CAC.
  
### <a name="yammer"></a>Yammer

Yammer per le aziende non è disponibile negli ambienti GCC High e DoD.
  
## <a name="customer-support"></a>Supporto clienti

Microsoft ricorda all'utente di non condividere informazioni controllate, riservate o riservate con il personale del supporto tecnico nell'ambito dell'evento imprevisto di supporto quando si utilizza Office 365 GCC High/DOD, almeno fino a quando non si conferma l'autorizzazione dell'agente di supporto per visualizzare o accedere a tali dati.

Microsoft si impegna a proteggere la [privacy dell'utente](https://privacy.microsoft.com/privacystatement). Tuttavia, Office 365 GCC supporto High/DoD non è incluso nel limite di accreditamento del servizio e non fornisce fedRAMP, DOD SRG, ITAR, IRS 1075 o garanzie di conformità per la gestione dei dati CJIS.