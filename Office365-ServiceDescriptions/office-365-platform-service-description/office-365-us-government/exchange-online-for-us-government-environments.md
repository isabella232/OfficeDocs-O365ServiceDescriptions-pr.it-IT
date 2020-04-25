---
title: Exchange Online per gli ambienti governativi degli Stati Uniti
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud governativo degli Stati Uniti e il cloud commerciale, come elencato nella descrizione del servizio Exchange Online.
ms.openlocfilehash: f104f072a74707f46528d9b111d8af46103a919e
ms.sourcegitcommit: 87c1b1cc9c02e5f446e382f1174cbbccad20196d
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2020
ms.locfileid: "43813402"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online per gli ambienti governativi degli Stati Uniti

In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud governativo degli Stati Uniti e il cloud commerciale, come elencato nella [Descrizione del servizio Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description). Exchange Online è disponibile per gli ambienti Government community Cloud (GCC), GCC High e Department of Defense (DoD).

Per ulteriori informazioni sul cloud governativo, tra cui l'eleggibilità e l'acquisto, vedere [Microsoft 365 Government-How to buy](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Per confrontare i piani governativi di Office 365, vedere [piani governativi di office 365](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Per informazioni sugli endpoint necessari per la gestione della connettività di rete, vedere gli endpoint di Office [365 US Government GCC High Endpoints](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o [Office 365 US Government](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità esclusive per gli ambienti cloud del governo degli Stati Uniti:

- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi di Office 365 commerciali.

- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Gli ambienti cloud governativi sono conformi alle certificazioni e agli accreditamenti spesso necessari per i clienti del settore pubblico degli Stati Uniti.

È nostra intenzione generale offrire tutte le caratteristiche e funzionalità commerciali di Exchange all'ambiente cloud governativo. Detto questo, alcune funzionalità non sono disponibili a causa dei requisiti dei clienti del cloud governativo. Altre caratteristiche vengono ritornate agli ambienti governativi, ma non sono ancora disponibili. Fare riferimento alle sezioni seguenti per informazioni sulla disponibilità delle funzionalità negli ambienti cloud governativi.

## <a name="exchange-online-features"></a>Funzionalità di Exchange Online 

Nella tabella seguente viene descritto se le funzionalità di Exchange Online specificate sono disponibili nell'ambiente GCC, GCC High e DoD. Quando sono presenti sfumature relative all'affermazione del supporto (o della sua mancanza), viene fornito un contesto aggiuntivo.

|**Area funzionale**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|:-----|:-----|:-----|:-----|:-----|
|**[Pianificazione e distribuzione](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Distribuzione ibrida supportata|Sì|Sì|Sì|Per la coesistenza con Exchange Server locale, Microsoft richiede l'installazione di almeno un server Accesso client di Exchange Server 2013 (o Exchange Server 2016). Exchange Server 2010 e versioni precedenti non sono supportati.|
|Migrazione IMAP supportata|Sì|Sì|Sì||
|Migrazione cutover supportata|Sì|Sì|Sì||
|Migrazione in fasi supportata|Sì|Sì|Sì|La migrazione di GSuite non è supportata per GCC High e DoD. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">eseguire una migrazione GSuite</a>.|
|**[Autorizzazioni](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Autorizzazioni basate sui ruoli|Sì|Sì|Sì||
|Gruppi di ruoli|Sì|Sì|Sì||
|Criteri di assegnazione dei ruoli|Sì|Sì|Sì||
|**[Conformità e criteri dei messaggi](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Archiviazione di cassette postali di Exchange Online|Sì|Sì|Sì||
|Archiviazione basata su cloud delle cassette postali locali|Sì|Sì|Sì||
|Messaging Records Management (MRM) |Sì|Sì|Sì||
|Criteri di conservazione, etichette e tag manuali |Sì|Sì|Sì||
|Crittografia dei dati inattivi (BitLocker)|Sì|Sì|Sì||
|IRM con Protezione delle informazioni di Azure|Sì|Sì|Sì|Per ulteriori informazioni sulle limitazioni di AIP in GCC High e DoD, vedere <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Descrizione del servizio governativo di Azure Information Protection Premium</a>.<br><br>Azure Information Protection non è incluso in G1/F3, ma può essere acquistato come componente aggiuntivo separato e consentirà di abilitare le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono un abbonamento a Office 365 ProPlus, che non è incluso in Office 365 Government G1 o Office 365 Government F3.|
|IRM mediante Windows Server AD RMS|Sì|Sì|Sì|Windows Server AD RMS è un server in locale che deve essere acquistato e gestito separatamente per abilitare le funzionalità IRM supportate.|
|Crittografia dei messaggi di Office 365|Sì|Sì|Sì|Vedere il [comportamento di crittografia dei messaggi di office 365 tra il limite GCC High/DOD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) in questo articolo e le <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">caratteristiche uniche di Office 365 Message Encryption in una distribuzione di GCC High</a>, che documentano le sfumature comportamentali della crittografia dei messaggi di Office 365 quando si inviano messaggi tra gli utenti GCC High/DOD e non GCC High/DOD.|
|Customer Key|Sì|Sì|Sì|Richiede il piano del servizio G5.|
|S/MIME|Sì|Sì|Sì||
|Archiviazione sul posto e conservazione per controversia legale|Sì|Sì|Sì|Richiede un piano di servizio G3 o G5.|
|eDiscovery sul posto|Sì|Sì|Sì||
|Regole del flusso di posta|Sì|Sì|Sì||
|Prevenzione della perdita di dati|No|Sì|Sì|Richiede un piano di servizio G3 o G5.|
|Inserimento nel journal|Sì|Sì|Sì||
|**[Protezione dalla posta indesiderata e antimalware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Protezione da posta indesiderata integrata|Sì|Sì|Sì||
|Customize anti-spam policies|Sì|Sì|Sì||
|Protezione antimalware integrata|Sì|Sì|Sì||
|Customize anti-malware policies|Sì|Sì|Sì||
|Quarantena - gestione da parte dell'amministrazione|Sì|Sì|Sì||
|Quarantena - autogestione dell'utente finale|Sì|Sì|Sì||
|Protezione avanzata dalle minacce|Sì|Sì|Sì|Richiede il piano di servizio G5 o l'acquisto di un componente aggiuntivo.<br><br>Anti-phishing per la rappresentazione di utenti e domini e la falsificazione dell'intelligenza non sono ancora disponibili in GCC High e DoD.|
|**[Flusso di posta](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Routing personalizzato della posta in uscita|Sì|Sì|Sì||
|Secure messaging with a trusted partner|Sì|Sì|Sì||
|Conditional mail routing|Sì|Sì|Sì||
|Aggiunta di un partner a un elenco di indirizzi attendibili in ingresso|Sì|Sì|Sì||
|Routing posta ibrida|Sì|Sì|Sì||
|**[Destinatari](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Avvisi di capacità|Sì|Sì|Sì||
|Messaggi secondari|Sì|Sì|Sì||
|Suggerimenti messaggio|Sì|Sì|Sì||
|Accesso delegato|Sì|Sì|Sì||
|Regole di Posta in arrivo|Sì|Sì|Sì||
|Account connessi|Sì|No|No|Questa funzionalità non è supportata in GCC High o DoD a causa di restrizioni sulle connessioni in uscita a servizi di terze parti. Per ulteriori informazioni sulle funzionalità interessate, vedere [connettività con servizi di terze parti](#connectivity-with-third-party-services) in questo articolo.|
|Cassette postali inattive|Sì|Sì|Sì|Richiede un piano di servizio G3 o G5.|
|Rubrica offline|Sì|Sì|Sì||
|Criteri delle rubriche|Sì|Sì|Sì||
|Rubrica gerarchica|Sì|Sì|Sì||
|Elenchi di indirizzi e elenco indirizzi globale|Sì|Sì|Sì||
|Gruppi di Office 365|Sì|Sì|Sì|L'accesso Guest ai gruppi di Office 365 non è supportato negli ambienti GCC High e DoD. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Gruppi di distribuzione|Sì|Sì|Sì||
|Contatti esterni (globali)|Sì|Sì|Sì|Soggette a limitazioni di collaborazione org-Relationship negli ambienti GCC High e DoD. |
|Collegamento dei contatti con i social network|Sì|No|No|Questa funzionalità non è supportata in GCC High o DoD.|
|Cassette postali per la risorsa|Sì|Sì|Sì||
|Gestione delle sale riunioni|Sì|Sì|Sì||
|Risposte Fuori sede|Sì|Sì|Sì||
|Condivisione del calendario Internet|Sì|No|No|In GCC High, la pubblicazione/condivisione di calendari Internet funziona per la connessione in ingresso ai calendari condivisi dagli utenti di GCC High, ma non per gli utenti di GCC High che si connettono in uscita a un calendario condiviso esterno a GCC High.<br><br>In DoD – la condivisione del calendario Internet non è supportata a causa del requisito di connessione in ingresso/in uscita Consenti l'elenco in tale ambiente.|
|**[Funzionalità di creazione dei report e strumenti di risoluzione problemi](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Rapporti dell'interfaccia di amministrazione di Microsoft 365|Sì|Sì|No|Rapporti non disponibili per la difesa. Fare riferimento alla sezione <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">funzionalità della piattaforma</a> della descrizione del servizio Office 365 US Government per gli aggiornamenti e la disponibilità corrente.|
|Report sui servizi Web|Sì|Sì|No|Rapporti non disponibili per la difesa. Fare riferimento alla sezione <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">funzionalità della piattaforma</a> della descrizione del servizio Office 365 US Government per gli aggiornamenti e la disponibilità corrente.|
|Message trace|Sì|Sì|Sì||
|Report di controllo|Sì|Sì|No|Rapporti non disponibili per la difesa. Fare riferimento alla sezione <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">funzionalità della piattaforma</a> della descrizione del servizio Office 365 US Government per gli aggiornamenti e la disponibilità corrente.|
|Rapporti di messaggistica unificata|Sì|No|No||
|**[Condivisione e collaborazione](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Condivisione federata (inclusa la pubblicazione del calendario)|Sì|Sì|Sì|Le limitazioni sono presenti sia in GCC High che in DoD. Vedere la [Federazione sulla disponibilità](#freebusy-federation) in questo articolo.|
|Cassette postali del sito|Sì|Sì|Sì||
|Cartelle pubbliche|Sì|Sì|Sì||
|**[Client e dispositivi mobili](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
| Outlook per Windows|Sì|Sì|Sì|Per soddisfare i requisiti di conformità di GCC High e DoD, è necessario eseguire almeno la versione 1803 di Office 365 ProPlus. Office 365 ProPlus non è incluso in G1 o F3.|
|Outlook sul Web|Sì|Sì|Sì||
|Outlook per Mac|Sì|Sì|Sì|Per soddisfare i requisiti di conformità di GCC High e DoD, è necessario eseguire almeno la versione 1803 di Office 365 ProPlus. Office 365 ProPlus non è incluso in G1 o F3.|
|Outlook per iOS e Android|Sì|Sì|Sì||
|Exchange ActiveSync|Sì|Sì|Sì||
|Gestione dispositivi mobili in Office 365|Sì|Sì|Sì||
|POP e IMAP|Sì|Sì|Sì||
|SMTP|Sì|Sì|Sì||
|Supporto dell'applicazione EWS|Sì|Sì|Sì||
|**[Servizi di messaggistica vocale](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Posta vocale|No|No|No|L'integrazione di sistemi IP-PBX locali con la messaggistica unificata di Exchange Online non è supportata.|
|Integrazione tra segreteria telefonica e FAX di terze parti|No|No|No|L'integrazione di sistemi IP-PBX locali con la messaggistica unificata di Exchange Online non è supportata.|
|Interoperabilità posta vocale di terze parti|No|No|No|L'integrazione di sistemi IP-PBX locali con la messaggistica unificata di Exchange Online non è supportata.|
|Integrazione di Skype for business|Sì|Sì|Sì||
|**[Disponibilità elevata e continuità aziendale](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Replica delle cassette postali nei datacenter|Sì|Sì|Sì||
|Recupero di cassette postali eliminate|Sì|Sì|Sì||
|Recupero di elementi eliminati|Sì|Sì|Sì||
|Ripristino di un unico elemento|Sì|Sì|Sì||
|**[Interoperabilità, connettività e compatibilità](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Presenza in OWA e Outlook|Sì|Sì|Sì||
|Interoperabilità di SharePoint|Sì|Sì|Sì||
|Supporto per la connettività EWS|Sì|Sì|Sì||
|Supporto per l'inoltro SMTP|Sì|Sì|Sì||
|**[Installazione e amministrazione di Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Accesso al portale di Microsoft Office 365|Sì|Sì|No|Rapporti non disponibili per la difesa. Fare riferimento alla sezione <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">funzionalità della piattaforma</a> della descrizione del servizio Office 365 US Government per gli aggiornamenti e la disponibilità corrente.|
|Accesso all'interfaccia di amministrazione di Microsoft 365|Sì|Sì|No|Rapporti non disponibili per la difesa. Fare riferimento alla sezione <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">funzionalità della piattaforma</a> della descrizione del servizio Office 365 US Government per gli aggiornamenti e la disponibilità corrente.|
|Accesso all'interfaccia di amministrazione di Exchange|Sì|Sì|Sì||
|Accesso a Windows PowerShell remoto|Sì|Sì|Sì||
|Criteri di ActiveSync per i dispositivi mobili|Sì|Sì|Sì||
|Report di utilizzo|Sì|Sì|No|Rapporti non disponibili per la difesa. Fare riferimento alla sezione <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">funzionalità della piattaforma</a> della descrizione del servizio Office 365 US Government per gli aggiornamenti e la disponibilità corrente.|
|**[Estensione del servizio: personalizzazione, componenti aggiuntivi e risorse](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni principali**|
|Componenti aggiuntivi di Outlook e MAPI di Outlook|Sì|Sì|Sì|Solo alcuni componenti aggiuntivi OWA e Outlook sono disponibili in GCC High e DoD. Vedere i [componenti aggiuntivi in Outlook e Outlook Web App](#add-insin-outlook-and-outlook-web-app) in questo articolo.|

## <a name="feature-nuances-within-gcc-high-and-dod-environment"></a>Sfumature delle caratteristiche all'interno dell'ambiente GCC High e DoD

### <a name="connectivity-with-third-party-services"></a>Connettività con servizi di terze parti  

Gli ambienti GCC High e DoD sono ambienti con restrizioni che richiedono l'approvazione esplicita e la configurazione delle connessioni in uscita. Inoltre, Microsoft non è in grado di soddisfare le richieste per consentire l'accesso in uscita da tali ambienti ai servizi cloud commerciali (Commercial Office 365, Google GSuite, Amazon Web Services e così via).     

A causa di queste restrizioni, le caratteristiche che si basano su questa connettività in uscita dagli ambienti GCC High/DoD generalmente non sono supportate, tra cui: 

- Account&mdash;connessi gli utenti non possono aggiungere/sincronizzare gli account (Google, POP/IMAP e così via). 

- Supporto per i provider&mdash;di archiviazione dei file di terze parti è possibile accedere solo all'account OneDrive for business dell'utente *all'interno di GCC High/DOD* all'interno dei diversi client di Outlook allo scopo di collegare/condividere file. Non è possibile aggiungere account di archiviazione di terze parti (Dropbox, box, Google Drive). 

- Connettività con i social network, ad esempio Facebook o LinkedIn. 

### <a name="azure-active-directoryb2b-collaboration"></a>Collaborazione B2B di Azure Active Directory 

La collaborazione B2B di Azure Active Directory è attualmente supportata solo tra organizzazioni che si trovano entrambi all'interno di Azure US Government cloud e che supportano la collaborazione B2B

Inoltre, gli utenti B2B come ospiti nei gruppi di Office 365 non sono supportati negli ambienti GCC High e DoD. 

Per ulteriori informazioni e gli aggiornamenti più recenti, vedere [Azure Government Security + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity). 

### <a name="office-365-message-encryptionbehavior-across-gcc-highdod-boundary"></a>Comportamento di crittografia dei messaggi di Office 365 tra i limiti GCC High/DoD 

Se si desidera utilizzare la crittografia dei messaggi di Office 365 in un ambiente GCC High, tenere presente queste caratteristiche esclusive relative all'esperienza del destinatario:  

- Quando si inviano messaggi di posta elettronica crittografati da GCC High o DoD ai destinatari nello stesso ambiente:
    
    - I mittenti possono crittografare manualmente i messaggi di posta elettronica in Outlook per PC e Mac e Outlook sul Web, oppure le organizzazioni possono configurare un criterio per crittografare i messaggi di posta elettronica utilizzando le regole del flusso del messaggio di Exchange. 
    
    - I destinatari all'interno di GCC High/DoD ricevono la stessa esperienza di lettura in linea in Outlook per PC e Mac e Outlook sul Web come tutti gli altri utenti di Office 365. 

<!-- end list -->

- Quando si inviano messaggi di posta elettronica crittografati da GCC High o DoD ai destinatari esterni all'ambiente (inclusi GCC e Commercial):
    
    - I mittenti all'interno di GCC High/DoD possono inviare messaggi di posta elettronica crittografati all'esterno del limite GCC High/DoD. 
    
    - Tutti i destinatari esterni a GCC High/DoD, compresi gli utenti di Office 365 commerciali, gli utenti di Outlook.com e altri utenti di altri provider di posta elettronica, ricevono un messaggio di posta elettronica wrapper. Questo indirizzo di posta elettronica del wrapper reindirizza il destinatario al portale OME in cui il destinatario può leggere e rispondere al messaggio. 

Per ulteriori informazioni e gli aggiornamenti più recenti, vedere [compare versions of ome](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide).

### <a name="freebusy-federation"></a>Federazione di disponibilità

La condivisione federata, incluse le informazioni sulla disponibilità, è attualmente soggetta a diverse importanti limitazioni negli ambienti GCC High e DoD.

Nell'ambiente GCC High:

- La relazione di trust federativa (inclusa la condivisione delle informazioni sulla disponibilità bidirezionale) è supportata tra i tenant all'interno di GCC High e tramite la coesistenza ibrida (Exchange 2013 o versione successiva).

- La condivisione federata non è supportata tra i tenant in GCC High e GCC o Office 365 Commercial. Non sono consentite le connessioni in uscita dall'ambiente GCC alto a nuvole commerciali (tra cui GCC e Office 365 Commercial). Di conseguenza, gli utenti di GCC High non sono in grado di eseguire la richiesta di accesso in uscita a GCC/Commercial per accedere alle informazioni del calendario condiviso.

Nell'ambiente DoD:

  - La relazione di trust federativa (inclusa la condivisione delle informazioni sulla disponibilità) è attualmente supportata solo tra i tenant all'interno dell'ambiente DoD. Non è supportato tra i tenant DoD e GCC o i tenant commerciali.

### <a name="client-configuration"></a>Configurazione client 

Sono necessari ulteriori passaggi per la distribuzione e la configurazione di Office ProPlus (compreso Outlook). Per una descrizione dettagliata di questi passaggi, vedere [linee guida per la distribuzione di Microsoft 365 Apps for Enterprise in un ambiente GCC High o DOD ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook per iOS e Android è disponibile anche per gli ambienti GCC High e DoD. Per ulteriori informazioni sulle limitazioni e la gestione delle funzionalità in tali ambienti, vedere [utilizzo di Outlook per iOS e Android nel cloud della community pubblica](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-insin-outlook-and-outlook-web-app"></a>Componenti aggiuntivi in Outlook e Outlook Web App  

Solo alcuni componenti aggiuntivi OWA e Outlook sono disponibili in GCC High e DoD. I modelli personali e le riunioni consigliate sono disponibili e dovrebbero funzionare. Sono supportati solo i cinque componenti aggiuntivi di OWA predefiniti. L'integrazione con le applicazioni di terze parti è possibile, tuttavia, queste integrazioni non sono coperte dalle promesse di conformità di Microsoft per GCC High o DoD. I clienti devono acquisire familiarità con le procedure di gestione dei dati di terze parti e le promesse di conformità prima di configurare il componente aggiuntivo per la propria organizzazione.
