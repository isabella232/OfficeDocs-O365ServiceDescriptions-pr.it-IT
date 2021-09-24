---
title: Exchange Online per ambienti governativi statunitensi
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud governativo statunitense e il cloud commerciale, come indicato nella descrizione Exchange Online servizio.
ms.openlocfilehash: 674d2e50b11624f206797cfef97883e9fda87df5
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671075"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online per ambienti governativi statunitensi

In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud governativo statunitense e il cloud commerciale, come indicato nella descrizione Exchange Online [servizio.](../../exchange-online-service-description/exchange-online-service-description.md) Exchange Online è disponibile per gli ambienti Government Community Cloud (GCC), GCC High e Department of Defense (DoD).

Per ulteriori informazioni sul cloud per enti pubblici, inclusi l'idoneità e l'acquisto, [vedere Microsoft 365 Government - come acquistare](./microsoft-365-government-how-to-buy.md). Per confrontare Office 365 Government piani, vedere [Office 365 Government piani.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Per informazioni sugli endpoint necessari per la gestione della connettività di rete, vedere la pagina Office 365 [U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche degli ambienti cloud del governo statunitense:

- Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi Office 365 commerciali.

- I contenuti dei clienti dell'organizzazione vengono archiviati a riposo negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Gli ambienti cloud governativi sono conformi a certificazioni e accreditamenti spesso necessari per i clienti del settore pubblico statunitense.

È nostro intento generale fornire tutte le funzionalità Exchange e commerciali all'ambiente cloud per enti pubblici. Ciò detto, alcune funzionalità non sono disponibili a causa dei requisiti dei clienti cloud per enti pubblici. Altre funzionalità sono disponibili negli ambienti governativi, ma non sono ancora disponibili. Fare riferimento alle sezioni seguenti per informazioni sulla disponibilità delle funzionalità negli ambienti cloud per enti pubblici.

## <a name="exchange-online-features"></a>Funzionalità di Exchange Online 

Nella tabella seguente viene indicato se le funzionalità Exchange Online sono disponibili negli ambienti GCC, GCC High e DoD. In caso di sfumature relative all'affermazione di supporto (o mancanza di tale supporto), viene fornito un contesto aggiuntivo.<br><br>

| Funzionalità | GCC | GCC High | DoD | Considerazioni chiave |
|:-----|:-----|:-----|:-----|:-----|
|**[Pianificazione e distribuzione](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Distribuzione ibrida supportata|Sì|Sì|Sì|Per la coesistenza con Exchange Server locale, Microsoft richiede l'installazione di almeno un server Accesso client Exchange Server 2013 (o Exchange Server 2016). Exchange Server 2010 e versioni precedenti non sono supportati.|
|Migrazione IMAP supportata|Sì|Sì|Sì||
|Migrazione cutover supportata|Sì|Sì|Sì||
|Migrazione in fasi supportata|Sì|Sì|Sì|La migrazione GSuite non è supportata per GCC High e DoD. Per ulteriori informazioni, vedere <a href="/exchange/mailbox-migration/perform-g-suite-migration">Perform a GSuite migration</a>.|
|**[Autorizzazioni](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Autorizzazioni basate sui ruoli|Sì|Sì|Sì||
|Gruppi di ruoli|Sì|Sì|Sì||
|Criteri di assegnazione dei ruoli|Sì|Sì|Sì||
|**[Criteri e conformità dei messaggi](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Archiviazione di cassette postali di Exchange Online|Sì|Sì|Sì||
|Archiviazione basata su cloud delle cassette postali locali|Sì|Sì|Sì||
|Messaging Records Management (MRM) |Sì|Sì|Sì||
|Criteri di conservazione manuali, etichette e tag |Sì|Sì|Sì||
|Crittografia dei dati inattivi (BitLocker)|Sì|Sì|Sì||
|IRM con Protezione delle informazioni di Azure|Sì|Sì|Sì|Per ulteriori informazioni sulle limitazioni di AIP in GCC High e DoD, vedere <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>Azure Information Protection non è incluso in G1/F3, ma può essere acquistato come componente aggiuntivo separato e abiliterà le funzionalità IRM (Information Rights Management) supportate. Alcune funzionalità di Azure Information Protection richiedono una sottoscrizione a Office 365 ProPlus, che non è inclusa in Office 365 Government G1 o Office 365 Government F3.|
|IRM mediante Windows Server AD RMS|Sì|Sì|Sì|Windows Server AD RMS è un server locale che deve essere acquistato e gestito separatamente per abilitare le funzionalità IRM supportate.|
|Crittografia dei messaggi di Office 365|Sì|Sì|Sì|Vedere Office 365 Message Encryption behavior [across GCC High/DoD boundary](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) in questo articolo e Unique characteristics of Office 365 Message Encryption in a GCC High <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">deployment</a>, che documenta sfumature comportamentali di Office 365 Message Encryption quando si inviano messaggi tra utenti GCC high/dod e non GCC High/DoD.|
|Customer Key|Sì|Sì|Sì|Richiede il piano di servizio G5.|
|S/MIME|Sì|Sì|Sì||
|Archiviazione sul posto e conservazione per controversia legale|Sì|Sì|Sì|Richiede il piano di servizio G3 o G5.|
|eDiscovery sul posto|Sì|Sì|Sì||
|Regole del flusso di posta|Sì|Sì|Sì||
|Prevenzione della perdita di dati|Sì|Sì|Sì|Richiede il piano di servizio G3 o G5.|
|Inserimento nel journal|Sì|Sì|Sì||
|**[Protezione antispam e antimalware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Protezione da posta indesiderata integrata|Sì|Sì|Sì||
|Customize anti-spam policies|Sì|Sì|Sì||
|Protezione antimalware integrata|Sì|Sì|Sì||
|Customize anti-malware policies|Sì|Sì|Sì||
|Quarantena - gestione da parte dell'amministrazione|Sì|Sì|Sì||
|Quarantena - autogestione dell'utente finale|Sì|Sì|Sì||
|Microsoft Defender per Office 365|Sì|Sì|Sì|Richiede il piano del servizio G5 (o l'acquisto di componenti aggiuntivi).<br><br>Anti-phishing per la rappresentazione di utenti e domini e spoofing intelligence non sono ancora disponibili in GCC High e DoD.|
|**[Flusso di posta](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Routing personalizzato della posta in uscita|Sì|Sì|Sì||
|Secure messaging with a trusted partner|Sì|Sì|Sì||
|Conditional mail routing|Sì|Sì|Sì||
|Aggiunta di un partner a un elenco di indirizzi attendibili in ingresso|Sì|Sì|Sì||
|Routing posta ibrida|Sì|Sì|Sì||
|**[Destinatari](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Avvisi di capacità|Sì|Sì|Sì||
|Messaggi secondari|Sì|Sì|Sì||
|Suggerimenti messaggio|Sì|Sì|Sì||
|Accesso delegato|Sì|Sì|Sì||
|Regole della posta in arrivo|Sì|Sì|Sì||
|Account connessi|Sì|No|No|Questa funzionalità non è supportata in GCC High o DoD a causa di restrizioni sulle connessioni in uscita a servizi di terze parti. Per ulteriori informazioni sulle funzionalità influenzate, vedere [Connettività con servizi di terze parti](#connectivity-with-third-party-services) in questo articolo.|
|Cassette postali inattive|Sì|Sì|Sì|Richiede il piano di servizio G3 o G5.|
|Rubrica offline|Sì|Sì|Sì||
|Criteri delle rubriche|Sì|Sì|Sì||
|Rubrica gerarchica|Sì|Sì|Sì||
|Elenchi indirizzi ed elenco indirizzi globale|Sì|Sì|Sì||
|Gruppi di Office 365|Sì|Sì|Sì|L'accesso guest Office 365 gruppi non è supportato negli ambienti GCC High e DoD. Per ulteriori informazioni, vedere <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity.</a>|
|Gruppi di distribuzione|Sì|Sì|Sì||
|Contatti esterni (globali)|Sì|Sì|Sì|Soggetto a limitazioni di collaborazione tra organizzazioni GCC ambienti High e DoD. |
|Collegamento dei contatti con i social network|Sì|No|No|Questa funzionalità non è supportata in GCC High o DoD.|
|Cassette postali per le risorse|Sì|Sì|Sì||
|Gestione delle sale riunioni|Sì|Sì|Sì||
|Risposte Fuori sede|Sì|Sì|Sì||
|Condivisione calendario Internet|Sì|No|No|In GCC High, la pubblicazione/condivisione del calendario Internet funziona per la connessione in ingresso ai calendari condivisi da utenti GCC Utenti elevati, ma non per gli utenti di GCC High che si connettono in uscita a un calendario condiviso al di fuori di GCC High.<br><br>In DoD- La condivisione del calendario Internet non è supportata a causa del requisito per l'inserimento di connessioni in ingresso/in uscita consentite in tale ambiente.|
|**[Funzionalità di creazione dei report e strumenti di risoluzione problemi](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Report nell'interfaccia di amministrazione di Microsoft 365|Sì|Sì|No|Report non disponibili per DoD. Fai riferimento alla sezione <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">relativa alle funzionalità della</a> piattaforma della Office 365 servizio us government per gli aggiornamenti e la disponibilità corrente.|
|Report servizi Web|Sì|Sì|No|Report non disponibili per DoD. Fai riferimento alla sezione <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">relativa alle funzionalità della</a> piattaforma della Office 365 servizio us government per gli aggiornamenti e la disponibilità corrente.|
|Message trace|Sì|Sì|Sì||
|Report di controllo|Sì|Sì|No|Report non disponibili per DoD. Fai riferimento alla sezione <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">relativa alle funzionalità della</a> piattaforma della Office 365 servizio us government per gli aggiornamenti e la disponibilità corrente.|
|Rapporti di messaggistica unificata|Sì|No|No||
|**[Condivisione e collaborazione](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Condivisione federata (inclusa la pubblicazione del calendario)|Sì|Sì|Sì|Esistono limitazioni sia in GCC High che in DoD. Vedere [Federazione delle informazioni sulla disponibilità](#freebusy-federation) in questo articolo.|
|Cassette postali del sito|Sì|Sì|Sì||
|Cartelle pubbliche|Sì|Sì|Sì||
|**[Client e dispositivi mobili](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|To Do sul Web|Sì|No|No||
|Outlook per Windows|Sì|Sì|Sì|Per soddisfare GCC requisiti di conformità High e DoD, è necessario eseguire almeno la versione 1803 di Office 365 ProPlus. Office 365 ProPlus non è incluso in G1 o F3.|
|Outlook sul web<sup>1</sup>|Sì|Sì|Sì||
|Outlook per Mac|Sì|Sì|Sì|Per soddisfare GCC requisiti di conformità High e DoD, è necessario eseguire almeno la versione 1803 di Office 365 ProPlus. Office 365 ProPlus non è incluso in G1 o F3.|
|Outlook per iOS e Android|Sì|Sì|Sì||
|Exchange ActiveSync|Sì|Sì|Sì||
|Mobilità e sicurezza di base per Microsoft 365|Sì|No|No||
|POP e IMAP|Sì|Sì|Sì||
|SMTP|Sì|Sì|Sì||
|Supporto delle applicazioni EWS|Sì|Sì|Sì||
|**[Servizi di messaggistica vocale](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Posta vocale|No|No|No|L'integrazione di sistemi IP-PBX locali con Exchange Online messaggistica unificata non è supportata.|
|Integrazione tra segreteria telefonica e FAX di terze parti|No|No|No|L'integrazione di sistemi IP-PBX locali con Exchange Online messaggistica unificata non è supportata.|
|Interoperabilità posta vocale di terze parti|No|No|No|L'integrazione di sistemi IP-PBX locali con Exchange Online messaggistica unificata non è supportata.|
|Skype for Business integrazione|Sì|Sì|Sì||
|**[Disponibilità elevata e continuità aziendale](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Replica delle cassette postali nei datacenter|Sì|Sì|Sì||
|Recupero di cassette postali eliminate|Sì|Sì|Sì||
|Recupero di elementi eliminati|Sì|Sì|Sì||
|Ripristino di un unico elemento|Sì|Sì|Sì||
|**[Interoperabilità, connettività e compatibilità](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Presenza in OWA e Outlook|Sì|Sì|Sì||
|SharePoint interoperabilità|Sì|Sì|Sì||
|Supporto della connettività EWS|Sì|Sì|Sì||
|Supporto dell'inoltro SMTP|Sì|Sì|Sì||
|**[Installazione e amministrazione di Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Accesso al portale di Microsoft Office 365|Sì|Sì|No|Report non disponibili per DoD. Fai riferimento alla sezione <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">relativa alle funzionalità della</a> piattaforma della descrizione Office 365 servizio us government per gli aggiornamenti e la disponibilità corrente.|
|interfaccia di amministrazione di Microsoft 365 accesso|Sì|Sì|No|Report non disponibili per DoD. Fai riferimento alla sezione <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">relativa alle funzionalità della</a> piattaforma della descrizione Office 365 servizio us government per gli aggiornamenti e la disponibilità corrente.|
|Accesso all'interfaccia di amministrazione di Exchange|Sì|Sì|Sì||
|Accesso a Windows PowerShell remoto|Sì|Sì|Sì||
|Criteri di ActiveSync per i dispositivi mobili|Sì|Sì|Sì||
|Report utilizzo|Sì|Sì|No|Report non disponibili per DoD. Fai riferimento alla sezione <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">relativa alle funzionalità della</a> piattaforma della descrizione Office 365 servizio us government per gli aggiornamenti e la disponibilità corrente.|
|**[Estensione del servizio: personalizzazione, componenti aggiuntivi e risorse](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**Considerazioni chiave**|
|Outlook componenti aggiuntivi e Outlook MAPI|Sì|Sì|Sì|Solo alcuni OWA e Outlook componenti aggiuntivi sono disponibili in GCC High e DoD. Vedere [Componenti aggiuntivi in Outlook e Outlook Web App](#add-insin-outlook-and-outlook-web-app) in questo articolo.|

<sup>1</sup> Outlook sul Web può essere utilizzato in scenari in cui Outlook per Windows non è in grado di visualizzare i messaggi protetti da IRM a causa di restrizioni oltre i limiti (scenari GCC High / Non-GCC High).

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Sfumature delle funzionalità GCC ambienti High e DoD

### <a name="connectivity-with-third-party-services"></a>Connettività con servizi di terze parti  

Sia GCC High che DoD sono ambienti con restrizioni che richiedono l'approvazione esplicita e la configurazione delle connessioni in uscita. Inoltre, Microsoft non può soddisfare le richieste per consentire l'accesso in uscita da questi ambienti a servizi cloud commerciali (Commercial Office 365, Google GSuite, Amazon Web Services e così via).

A causa di queste restrizioni, le funzionalità che si basano su questa connettività in uscita dagli ambienti High/DoD di GCC in genere non sono supportate, tra cui:

- Account connessi: gli utenti non possono aggiungere/sincronizzare account (Google, POP/IMAP e così via).

- Supporto per provider di archiviazione file di terze parti- Solo l'account OneDrive for Business dell'utente all'interno di *GCC High/DoD* può essere accessibile dall'interno dei vari client Outlook allo scopo di allegare/condividere file. Gli account di archiviazione di terze parti (Dropbox, Box, Google Drive) non possono essere aggiunti.

- Connettività con i social network, ad esempio Facebook o LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory Collaborazione B2B

Azure Active Directory La collaborazione B2B è attualmente supportata solo tra organizzazioni che sono entrambe nel cloud di Azure US Government e che supportano entrambe la collaborazione B2B

Inoltre, gli utenti B2B come utenti guest in Office 365 non sono supportati in ambienti GCC High e DoD. 

Per altre informazioni e gli aggiornamenti più recenti, vedi [Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity)

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365 Message Encryption comportamento tra GCC limite High/DoD

Se si prevede di utilizzare Office 365 Message Encryption in un ambiente GCC High, tenere presenti queste caratteristiche univoche relative all'esperienza del destinatario:  

- Quando si invia posta elettronica crittografata da GCC High o DoD ai destinatari nello stesso ambiente:
    
    - I mittenti possono crittografare manualmente i messaggi di posta elettronica in Outlook per PC e Mac e Outlook sul web oppure le organizzazioni possono configurare un criterio per crittografare i messaggi di posta elettronica Exchange regole del flusso di posta.
    
    - I destinatari all'interno GCC High/DoD ricevono la stessa esperienza di lettura in linea in Outlook per PC e Mac e Outlook sul web come tutti gli altri Office 365 utenti.

<!-- end list -->

- Quando si inviano messaggi di posta elettronica crittografati da GCC High a destinatari esterni a tale ambiente (tra cui DoD, GCC e Commercial):

    - I mittenti all'interno GCC high possono inviare messaggi di posta elettronica crittografati all'esterno GCC limite alto.
    - Tutti i destinatari esterni GCC High, inclusi DoD, utenti di Office 365 commerciali, utenti Outlook.com e altri utenti di altri provider di posta elettronica, ricevono una posta wrapper. Questa posta wrapper reindirizza il destinatario al portale OME in cui il destinatario può leggere e rispondere ai messaggi.

Per ulteriori informazioni e gli aggiornamenti più recenti, vedere [Confrontare le versioni di OME.](/microsoft-365/compliance/ome-version-comparison)

### <a name="freebusy-federation"></a>Federazione delle informazioni sulla disponibilità

La condivisione federata, incluse le informazioni sulla disponibilità, è attualmente soggetta a diverse limitazioni importanti negli ambienti DoD.

Nell'GCC high:

- La relazione di trust federativa (inclusa la condivisione delle informazioni sulla disponibilità bidirezionale) è supportata tra i tenant all'interno di GCC High, i tenant in GCC e cloud commerciali e tramite la coesistenza ibrida (Exchange 2013 o versioni successive).

Nell'ambiente DoD:

  - La relazione di trust federativa (inclusa la condivisione delle informazioni sulla disponibilità) è attualmente supportata solo tra i tenant all'interno dell'ambiente DoD. Non è supportato tra tenant DoD e tenant GCC, GCC high o commerciali.

### <a name="client-configuration"></a>Configurazione client

Ulteriori passaggi sono coinvolti nella distribuzione e nella configurazione di Office ProPlus (incluso Outlook). Per una descrizione dettagliata di questi passaggi, vedere [Guidance for deploying Microsoft 365 Apps for enterprise in a GCC High or DoD environment](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook per iOS e Android è disponibile anche per gli GCC High e DoD. Per altre informazioni sulle limitazioni e sulla gestione delle funzionalità in tali ambienti, vedi Uso di [Outlook per iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)e Android in Government Community Cloud .

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Componenti aggiuntivi in Outlook e Outlook Web App  

Solo alcuni OWA e Outlook componenti aggiuntivi sono disponibili in GCC High e DoD. I modelli personali e le riunioni suggerite sono disponibili e dovrebbero funzionare. Sono supportati solo OWA componenti aggiuntivi predefiniti. L'integrazione con applicazioni di terze parti è possibile, tuttavia, tali integrazioni non sono coperte dalle promesse di conformità Microsoft per GCC High o DoD. I clienti devono acquisire familiarità con le procedure di gestione dei dati di terze parti e le promesse di conformità prima di configurare il componente aggiuntivo per l'organizzazione.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Sfumature di funzionalità in GCC ambienti per Microsoft To Do

| Funzionalità | Descrizione | WW | Disponibilità in GCC |
|:-----|:-----|:-----|:-----|
|Piattaforme supportate|Web, Android, iOS, Mac, Windows|Tutto|Solo Web|
|Hub M365 supporta|Integrazioni con Outlook, Teams, Planner|Tutto|Outlook, Planner (Teams disponibile con l'app Teams attività)|
|Wunderlist Migrazione|Consentire agli utenti wunderlist di eseguire la migrazione dei dati To Do sul Web|Sì|No|
|Notifiche Push|Invia notifiche Push agli utenti finali per promemoria e così via.|Sì|No|
|Supporto helpshift|Usare l'interfaccia helpshift per creare una richiesta di supporto|Sì|No|
|My Day|Pianificare la giornata|Sì|Sì|
|Elenco pianificato|Visualizzare tutte le attività con una data di scadenza|Sì|Sì|
|Elenco Assegnato a te|Tutte le attività assegnate all'utente in un elenco condiviso, Planner o WXP (futuro)|Sì|Sì|
|Posta elettronica contrassegnata|Visualizzare i messaggi di posta elettronica contrassegnati in Outlook come attività|Sì|Sì|
|Supporto per più account|Usare l'account di casa e di ufficio in un riquadro|Sì|Sì|
|Condivisione elenco|Condividere elenchi con colleghi nella stessa organizzazione|Sì|Sì|
|Condivisione tra tenant|Condividere l'elenco attività all'esterno dell'organizzazione|Sì|No|
|Promemoria e ricorrenza|Impostare promemoria per l'attività |Sì|Sì|

*Tutte le altre funzionalità non menzionate sono disponibili in entrambi gli ambienti.