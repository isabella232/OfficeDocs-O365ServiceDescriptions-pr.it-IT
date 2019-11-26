---
title: Office 365 GCC High e DoD
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Per soddisfare i requisiti univoci e in evoluzione del dipartimento della difesa degli Stati Uniti, così come i contraenti che detengono o elaborano le informazioni non classificate gestite dal DoD o soggette alle normative internazionali sul traffico di armi (ITAR), Microsoft offre Ambienti GCC High e DoD. Disponibili attraverso contratti multilicenza, le organizzazioni interessate portano avanti una procedura di convalida per verificare l'idoneità prima che venga definito un ambiente. Al momento, non sono disponibili versioni di valutazione.
ms.openlocfilehash: 4d539df25546255feae5d33369b678833b2d967f
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262547"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High e DoD

Per soddisfare i requisiti univoci e in evoluzione del dipartimento della difesa degli Stati Uniti, così come i contraenti che detengono o elaborano le informazioni non classificate gestite dal DoD o soggette alle normative internazionali sul traffico di armi (ITAR), Microsoft offre Ambienti GCC High e DoD. Disponibili attraverso contratti multilicenza, le organizzazioni interessate portano avanti una procedura di convalida per verificare l'idoneità prima che venga definito un ambiente. Al momento, non sono disponibili versioni di valutazione. 
  
È opportuno invitare il team degli account o il proprio partner preferito a informarsi ulteriormente in merito alla procedura di convalida oppure ad avviarla. Per ulteriori informazioni su come acquistare, vedere [Microsoft 365 Government-come acquistare](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy).
  
## <a name="how-to-use-this-service-description-section"></a>Informazioni su come utilizzare questa sezione relativa alla descrizione del servizio

La descrizione del servizio Office 365 US Government è progettata per essere utilizzato come sovrapposizione alla descrizione generale del servizio Office 365. Il documento definisce gli impegni univoci ed evidenzia le differenze rispetto alle offerte Office 365 Enterprise.
  
## <a name="compliance"></a>Conformità

GCC High e DoD rispettano i requisiti di conformità previsti per le certificazioni e gli accrediti seguenti: 
  
- Il programma Federal Risk and Authorization Management Program con baseline Moderate (FedRAMP Moderate), che include i controlli di sicurezza e i miglioramenti di controllo descritti nel documento National Institute of Standards and Technology (NIST) Special Publication 800-53.
    
- I controlli di sicurezza e i miglioramenti del controllo per la United States Department of Defense Cloud Computing Security Requirements Guide (SRG) in merito alle informazioni con livello di impatto massimo pari a 5 (L5).
    
Gli abbonati a Office 365 che fanno capo al Dipartimento della Difesa potranno usare i servizi offerti dall'ambiente esclusivo del Dipartimento che rientra nel DOD SRG L5. Gli abbonati che non fanno capo al Dipartimento della Difesa potranno ricevere i servizi dall'ambiente del Dipartimento della Difesa valutati L5 ma che utilizzano la segmentazione L4.
  
## <a name="background-screening"></a>Screening del background

Il personale Office 365 non ha un accesso diretto all'ambiente di produzione per GCC High e DoD. Qualsiasi membro del personale che richiede l'elevazione dei privilegi temporanea per ottenere l'accesso ai contenuti dei clienti prima deve aver superato i controlli di background riportati di seguito.
  
|||
|:-----|:-----|
|**Controlli del background e screening del personale Microsoft**<sup>1</sup> <br/> |**Descrizione** <br/> |
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

<sup>1</sup> si applica solo al personale con accesso temporaneo o permanente ai contenuti dei clienti ospitati in Office 365 US GCC-High o DOD Clouds.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Dettagli sulle caratteristiche basate sull'architettura cloud conforme

Le sottoscrizioni Office 365 negli ambienti GCC High e DoD includono le caratteristiche principali di Exchange Online, SharePoint Online e Skype for Business. Considerando l'aumento di certificazione e accredito dell'infrastruttura, sono presenti alcune differenze tra le offerte Office 365 commerciali e quelle disponibili in GCC High e DoD.
  
### <a name="exchange-online"></a>Exchange Online

 **Supporto della Messaggistica unificata di Exchange Online per IP-PBX locale** - Il supporto per l'integrazione di sistemi IP-PBX locali con la Messaggistica unificata di Exchange Online non è incluso nelle sottoscrizioni di GCC High e DoD. 
  
### <a name="sharepoint-online"></a>SharePoint Online

 **Condivisione di documenti** - SharePoint Online e OneDrive for Business consentono la condivisione delle informazioni e la collaborazione tra utenti e team. I proprietari dei documenti possono fornire ad altri utenti l'accesso ai documenti tramite l'interfaccia Web o gli allegati moderni in Outlook. Quando si condivide un documento, sono disponibili diverse opzioni per la gestione delle autorizzazioni: 
  
1. Solo utente corrente
    
2. Tutti gli utenti all'interno dell'azienda
    
3. Chiunque abbia questo collegamento
    
4. Persone specifiche
    
I clienti che utilizzano SharePoint Online e OneDrive for business negli ambienti GCC High o DoD possono mantenere i documenti privati (prima opzione), condividerli con tutti gli utenti dell'organizzazione (seconda opzione), condividerli con tutti gli utenti che dispongono del collegamento al documento (terza opzione) e condivisione con utenti specifici (quarta opzione). È possibile limitare queste opzioni in base ai controlli di accesso a livello di tenant.

Quando si condivide con persone specifiche, SharePoint verificherà che gli utenti siano destinatari di un collegamento tramite l'invio di un codice di accesso una tantum all'indirizzo di posta elettronica condiviso. Tuttavia, quando un tenant di GCC-High condivide un altro tenant di GCC-High, verrà creato un account Guest per il destinatario in Azure AD, che eseguirà l'accesso con il nome utente e la password.
  
Altri esempi:
  
- GCC High tenant A è in grado di condividere con il tenant elevato B GCC, mentre gli utenti B eseguono l'accesso utilizzando il nome utente e la password di Azure AD.
    
- Il tenant alto C non GCC può condividere con il tenant A o B di GCC High, mentre gli utenti A o B eseguono l'accesso utilizzando codici di codice una tantum.
    
- L'alto tenant A o B di GCC può condividere con il tenant alto C non GCC e gli utenti C si configurano utilizzando codici di accesso una tantum.
    
Inoltre, gli indirizzi di posta elettronica non basati su GCC alti associati ai profili utente non sono supportati e non consentiranno di inviare messaggi di posta elettronica di avviso. Ad esempio, per l'utente locale A viene assegnato un indirizzo di posta elettronica di Gmail e quindi sincronizzato con Azure GCC High tenant. L'utente A si sposta in una raccolta e crea un avviso per eventuali modifiche. L'avviso non verrà inviato all'indirizzo Gmail.
  
 **Accesso alle applicazioni esterne** - I collegamenti alle applicazioni esterne, ad esempio, l'origine dati per i componenti aggiuntivi, sono limitati alle origini comprese nei limiti di sicurezza del sistema supportati da GCC High e DoD. 
  
 **Servizi di integrazione applicativa** -la funzionalità BCS è supportata per gli scenari di connettività in cui le origini dati rimangono raggiungibili entro il limite di sicurezza per il servizio cloud. 
  
 **Soluzioni sandbox** - Questa funzionalità è stata rimossa e non è disponibile. Tutte le soluzioni in modalità sandbox devono essere migrate nel [modello extensibility del componente aggiuntivo di SharePoint ]( https://msdn.microsoft.com/library/office/fp179930.aspx).
  
### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN Calling &amp; PSTN Conferencing** - Due to the requirement to use the Public Switched Telephone Network (PSTN) for telephony-oriented services, PSTN Calling &amp; PSTN Conferencing services are currently not available in GCC High and DoD. 
  
### <a name="identity"></a>Identità

L'autenticazione a più fattori che utilizza un modello di identità federata consente di utilizzare le schede PIV e CAC.
  
### <a name="yammer"></a>Yammer

Yammer Enterprise non è disponibile negli ambienti GCC High e DoD.
  
## <a name="customer-support"></a>Supporto clienti

Microsoft ricorda di non condividere informazioni controllate, sensibili o riservate con il personale di supporto clienti come parte dell'evento di supporto quando si utilizza Office 365 GCC High/DOD, almeno fino a quando non si conferma l'autorizzazione dell'agente di supporto per visualizzare o accedere a tali dati.

Microsoft si impegna a proteggere la [privacy](https://privacy.microsoft.com/privacystatement)). Tuttavia, il supporto di Office 365 GCC High/DoD non è incluso nel limite di accreditamento del servizio e non fornisce FedRAMP, DOD SRG, ITAR, IRS 1075 o CJIS data handling Compliance Assurances.
