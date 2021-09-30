---
title: Conformità e criteri dei messaggi
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
description: Informazioni sui criteri dei messaggi e sulla conformità in Exchange Online.
ms.openlocfilehash: 77885b5db378734b1108c240663c0533cdffed7e
ms.sourcegitcommit: 28c7d4dc2c98364ca9a2c9ba91744f2db89950bf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/30/2021
ms.locfileid: "60015670"
---
# <a name="message-policy-and-compliance"></a>Conformità e criteri dei messaggi

## <a name="archiving-exchange-online-based-mailboxes"></a>Archiviazione di cassette postali di Exchange Online

Le cassette postali di Exchange Online risiedono nel cloud e la loro archiviazione richiede ambienti host univoci. In alcuni casi, è possibile utilizzare Exchange Online per archiviare le cassette postale locali nel cloud. In questa sezione vengono descritte le opzioni per l'archiviazione in Exchange Online.
  
Exchange Online dispone di funzionalità di archiviazione integrate per le cassette postali basate su cloud, tra cui un Archivio in locale che consente agli utenti di archiviare comodamente i messaggi di posta elettronica meno recenti. Un In-Place è un tipo speciale di cassetta postale che viene visualizzato insieme alle cartelle principali delle cassette postali di un utente in Outlook e Outlook sul web. Gli utenti possono accedere all'archivio ed effettuarvi ricerche esattamente come fanno per le cassette postali principali. Le funzionalità disponibili dipendono dal client in uso:
  
- **Outlook 2016, Outlook 2013, Outlook 2010 e Outlook sul web** Gli utenti hanno accesso alle funzionalità complete dell'archivio, nonché alle funzionalità di conformità correlate, come il controllo sui criteri di conservazione e archiviazione. 
    
- **Outlook 2007** Gli utenti dispongono di un supporto base per l'Archivio in locale e non tutte le funzionalità di archiviazione e conformità sono disponibili. Ad esempio, gli utenti non possono applicare i criteri di archiviazione o conservazione agli elementi di una cassetta postale e devono avvalersi invece dei criteri stabiliti dall'amministratore. 
    
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per abilitare la funzionalità di archiviazione personalizzata per specifici utenti.
  
Per ulteriori informazioni, vedere:
  
- [Cassette postali di archiviazione in Exchange Online](../exchange-online-archiving-service-description/archive-features.md)
    
- [Abilitare o disabilitare una cassetta postale di archiviazione in Exchange Online](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Dimensioni degli archivi

Ciascun archivio personale può contenere i dati di messaggistica di un solo utente. L'allocazione di spazio di archiviazione dipende dal piano di abbonamento. Per ulteriori informazioni sulle dimensioni delle cassette postali di archiviazione, vedere la sezione "Limiti di archiviazione delle cassette postali" in [Exchange Online limiti.](exchange-online-limits.md)
  
> [!IMPORTANT]
> - L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a una cassetta postale di Exchange Online a scopo di archiviazione non è consentito. Microsoft si riserva il diritto di negare l'archiviazione aggiuntiva nei casi in cui un archivio delle cassette postali non viene utilizzato in uno scenario personale o in altri casi di utilizzo inappropriato.
> - L'archivio locale presenta specifici requisiti di licenza per gli utenti di Outlook. Gli utenti di Outlook 2007 devono disporre dell'aggiornamento cumulativo di Office 2007 del febbraio 2011 per poter accedere all'archivio personale. 
> - Exchange Online non supporta il cmdlet _New-MailboxImportRequest_ Windows PowerShell di Exchange Server 2010 Service Pack 1 o versione successiva per l'importazione guidata dall'amministratore di file pst in un archivio personale. Se un utente dispone sia della cassetta postale principale sia dell'archivio in Exchange Online, un amministratore può utilizzare PST Capture, uno strumento gratuito, per importare i dati dei file pst nella cassetta postale principale o nell'archivio dell'utente.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archiviazione basata su cloud delle cassette postali locali

L'utilizzo di Exchange Online per l'archiviazione su cloud di cassette postali locali di Exchange Server 2010 o versioni successive è possibile tramite Archiviazione Microsoft Exchange Online, una soluzione di archiviazione su host fornita da Microsoft. Ciò richiede che l'organizzazione locale sia in modalità ibrida oppure sia impostata per l'archiviazione Exchange Online.
  
> [!IMPORTANT]
> Gli utenti che dispongono di una cassetta postale locale su un server cassette postali Exchange 2010 e per i quali sono applicati i criteri per le cartelle gestite non possono avere un Archivio in locale o su cloud abilitato. 
  
## <a name="retention-tags-and-retention-policies"></a>Tag di conservazione e criteri di conservazione

Exchange Online fornisce dei criteri di conservazione che consentono alle organizzazioni di ridurre le responsabilità associate ai messaggi di posta elettronica e ad altre comunicazioni. Con questi criteri, gli amministratori possono applicare le impostazioni di conservazione a specifiche cartelle nelle cassette postali degli utenti. Gli amministratori possono inoltre fornire agli utenti un menu di criteri di conservazione e consentire loro di applicare i criteri a elementi, conversazioni o cartelle specifici utilizzando Outlook 2010 o versioni successive o Outlook sul web.
  
In Exchange Online, gli amministratori gestiscono i criteri di conservazione tramite l'interfaccia di amministrazione di Exchange o tramite Windows PowerShell remoto.
  
Exchange Online fornisce due tipi di criteri: i criteri di archiviazione e i criteri di eliminazione. Entrambi i tipi di criteri possono essere combinati nello stesso elemento o nella stessa cartella. Ad esempio, un utente può assegnare un tag a un messaggio di posta elettronica in modo che il messaggio venga automaticamente spostato dopo un dato numero di giorni ed eliminato dopo un ulteriore numero di giorni.
  
Con Outlook 2010 o versioni successive e Outlook sul web, gli utenti possono applicare criteri di conservazione a cartelle, conversazioni o singoli messaggi. Possono altresì visualizzare i criteri di conservazione applicati e le date di eliminazione previste per i messaggi. Gli utenti di altri client di posta elettronica possono solo eliminare o archiviare i propri messaggi di posta elettronica sulla base dei criteri di conservazione definiti dall'amministratore sul server.
  
I criteri di conservazione disponibili Exchange Online sono gli stessi disponibili in Exchange Server 2010 Service Pack 2 RU4. Gli amministratori possono utilizzare Windows PowerShell in remoto per migrare i criteri di conservazione dagli ambienti Exchange Server 2010 in locale o versioni successive a Exchange Online.
  
> [!IMPORTANT]
> Le cartelle gestite, che rappresentano il precedente metodo di gestione dei record di messaggistica introdotto in Exchange Server 2007, non sono più disponibili in Exchange Online. 
  
Per ulteriori informazioni, vedere [Tag di conservazione e criteri di conservazione](/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Crittografia dei dati statici

La crittografia dei dati dei clienti in pausa è fornita da più tecnologie sul lato servizio, tra cui BitLocker, DKM, crittografia del servizio Archiviazione di Azure e crittografia dei servizi in Exchange Online, Skype for Business, OneDrive for Business e SharePoint Online. Office 365 La crittografia del servizio include un'opzione per usare le chiavi di crittografia gestite dal cliente archiviate in Azure Key Vault. Questa opzione chiave gestita dal cliente, denominata [Customer Key,](/microsoft-365/compliance/customer-key-overview)è disponibile per Exchange Online, SharePoint Online e OneDrive for Business. 
  
### <a name="bitlocker"></a>BitLocker

I server Microsoft usano BitLocker per crittografare le unità disco contenenti i dati dei clienti in pausa a livello di volume. La crittografia BitLocker è una funzionalità di protezione dei dati incorporata Windows. BitLocker è una delle tecnologie utilizzate per la protezione dalle minacce in caso di problemi in altri processi o controlli (ad esempio, il controllo dell'accesso o il riciclo dell'hardware) che potrebbero portare a un utente che ottiene l'accesso fisico ai dischi contenenti i dati dei clienti. In questo caso, BitLocker elimina il rischio di furto o esposizione dei dati a causa di computer e dischi smarriti, rubati o inappropriati. 
  
### <a name="distributed-key-manager"></a>Distributed Key Manager

Oltre a BitLocker, usiamo una tecnologia denominata Distributed Key Manager (DKM). DKM è una funzionalità sul lato client che utilizza un set di chiavi segrete per crittografare e decrittografare le informazioni. Solo i membri di un gruppo di sicurezza specifico in Servizi di dominio Active Directory possono accedere a tali chiavi per decrittografare i dati crittografati da DKM. In Exchange Online, fanno parte di quel determinato gruppo di sicurezza solo determinati account di servizio nei quali sono in esecuzione i processi di Exchange. Nell'ambito della procedura operativa standard nel datacenter, le credenziali che fanno parte del gruppo di sicurezza non vengono fornite a nessuno; pertanto, nessuno ha accesso alle chiavi in grado di decrittografare le informazioni riservate.
  
## <a name="customer-key"></a>Customer Key

Con Customer Key, puoi controllare le chiavi di crittografia dell'organizzazione e quindi configurarle per crittografare i dati in pausa nei data center di Microsoft. I dati in pausa includono i dati Exchange Online e Skype for Business archiviati nelle cassette postali e nei file archiviati in SharePoint Online e OneDrive for Business. Per ulteriori informazioni, vedere [Controllo dei dati nell'utilizzo della chiave del](/office365/securitycompliance/controlling-your-data-using-customer-key) cliente e della crittografia del servizio con le domande frequenti sulla chiave del [cliente.](/office365/securitycompliance/service-encryption-with-customer-key-faq)
  
## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Office 365 Message Encryption consente agli utenti di posta elettronica di inviare messaggi di posta elettronica crittografati a chiunque. Sono stati annunciati nuovi Office crittografia dei messaggi che sfruttano le funzionalità di protezione in Crittografia delle informazioni di Azure. Queste nuove funzionalità hanno fornito esperienze utente finali avanzate che semplificano la condivisione e la collaborazione su messaggi protetti con chiunque all'interno o all'esterno dell'organizzazione. Le nuove funzionalità Office crittografia dei messaggi hanno alcuni requisiti di configurazione. Vedi Configurare nuove funzionalità Office 365 Message Encryption integrate in Azure Information Protection. I clienti con Office 365 Message Encryption legacy non ottengono le nuove funzionalità senza seguire le indicazioni di configurazione fornite in precedenza. Leggi le domande [frequenti](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) per ulteriori dettagli su ciò che è incluso nelle nuove funzionalità Office 365 Message Encryption legacy. 

Office 365 Advanced Message Encryption protezione aggiuntiva consentendo la scadenza e la revoca dei messaggi.  È inoltre possibile creare più modelli per i messaggi di posta elettronica crittografati provenienti dall'organizzazione.  La crittografia avanzata dei messaggi è inclusa in Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (prezzi del personale no profit), Office 365 Enterprise E5 (Prezzi del personale non profit) o Office 365 Education A5. Se l'organizzazione ha una sottoscrizione che non include Office 365 Advanced Message Encryption, è possibile acquistare Microsoft 365 E5 Compliance o lo SKU Office 365 Advanced Compliance come componente aggiuntivo.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME consente di proteggere le informazioni riservate inviando messaggi di posta elettronica firmati e crittografati all'interno dell'organizzazione. Gli amministratori possono utilizzare Windows PowerShell in remoto per configurare S/MIME dopo aver stabilito e rilasciato i certificati PKI agli utenti. Tali certificati devono essere sincronizzati da un servizio certificati Active Directory locale.
  
S/MIME è supportato in Microsoft Edge e Internet Explorer 11. Al momento, S/MIME non è supportato su Firefox, Opera e Chrome. Per ulteriori informazioni, vedere [S/MIME per la funzionalità di firma e crittografia dei messaggi](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Archiviazione sul posto e conservazione per controversia legale

In presenza di un ragionevole rischio di controversia, le organizzazioni sono tenute a conservare le informazioni in forma elettronica, inclusi i messaggi pertinenti al caso. Questa aspettativa può divenire realtà prima che siano note le specifiche del caso, richiedendo pertanto una conservazione ad ampio spettro. Le organizzazioni possono conservare tutti i messaggi di posta elettronica relativi a uno specifico argomento oppure tutti i messaggi di posta elettronica di determinati individui.
  
In Exchange Online, è possibile utilizzare Conservazione in locale o Conservazione per controversia legale per raggiungere i seguenti obiettivi:
  
- Consentire agli utenti di conservare gli elementi della cassetta postale in maniera iimmutabile
    
- Conservare gli elementi della cassetta postale eliminati dagli utenti o da processi di eliminazione automatica, quali Gestione record di messaggistica
    
- Proteggere gli elementi della cassetta postale da alterazione dei dati, modifiche apportate da un utente o processi automatici, salvando una copia dell'elemento originale
    
- Conservare elementi a tempo indeterminato o per un determinato periodo di tempo
    
- Mantenere trasperanti le conservazioni dall'utente, non dovendo sospendere MRM
    
- Utilizzare eDiscovery locale per effettuare la ricerca degli elementi delle cassette postali, compresi quelli conservati
    
Inoltre, è possibile utilizzare l'archiviazione sul posto per:
  
- Ricercare e conservare gli elementi che corrispondono a specifici criteri
    
- Inserire un utente in più archiviazioni sul posto per differenti casi o indagini
    
> [!NOTE]
> Quando imposta una cassetta postale sull'archiviazione sul posto o sul blocco per controversia legale, la conservazione interessa sia la cassetta postale primaria che quella di archiviazione. 
  
Per ulteriori informazioni, vedere [Conservazione in locale](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>eDiscovery sul posto

Exchange Online consente ai clienti di cercare il contenuto delle cassette postali in un'organizzazione utilizzando un'interfaccia basata sul Web. Gli amministratori o i responsabili di conformità e protezione autorizzati a eseguire ricerche eDiscovery in locale (mediante assegnazione) possono effettuare ricerche nei messaggi di posta elettronica, negli allegati, negli appuntamenti sul calendario, nelle attività, nei contatti e in altri elementi. La ricerca eDiscovery in locale può essere eseguita simultaneamente negli archivi e nelle cassette postali primarie. Tra gli efficienti filtri disponibili ci sono quelli per mittente, destinatario, tipo di messaggio, data di invio/ricezione e Cc/Bcc, oltre a quelli per la sintassi KQL. I risultati della ricerca includono anche gli elementi contenuti nella cartella Posta eliminata, se soddisfano i criteri di ricerca specificati.
  
I risultati delle ricerche eDiscovery in locale possono essere visualizzati in anteprima in un'interfaccia basata sul Web, esportati in un file PST oppure copiati in una particolare cassetta postale detta "cassetta postale di individuazione". Una cassetta postale di individuazione ha una quota di 50 GB per l'archiviazione dei risultati della ricerca. Gli amministratori possono connettere Outlook alla cassetta postale di individuazione per accedere ai risultati della ricerca ed esportarli come file .pst.
  
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per effettuare ricerche in più cassette postali. L'interfaccia di amministrazione di Exchange è in grado di fornire un'anteprima di sola lettura dei risultati della ricerca, permettendo agli amministratori di verificarli e, se necessario, di eseguire di nuovo la ricerca con altri parametri. Una volta ottimizzata la ricerca, l'amministratore può copiare i risultati nella cassetta postale di individuazione.
  
Per impostazione predefinita, viene creata una cassetta postale di individuazione per ciascuna organizzazione, ma gli amministratori possono creare altre cassette postali di individuazione utilizzando Windows PowerShell in remoto. Le cassette postali di individuazione possono essere utilizzate solo per archiviare i risultati delle ricerche eDiscovery in locale.
  
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per effettuare ricerche eDiscovery in locale. L'interfaccia di amministrazione di Exchange è in grado di fornire un'anteprima di sola lettura dei risultati della ricerca, permettendo agli amministratori di verificarli e, se necessario, di eseguire di nuovo la ricerca con altri parametri. Una volta ottimizzata la ricerca, l'amministratore può copiare i risultati nella cassetta postale di individuazione o esportarli in un file PST.
  
Gli amministratori possono utilizzare l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per cercare fino a 10.000 cassette postali alla volta in una ricerca eDiscovery sul posto. 
  
In Exchange Online, gli utenti autorizzati possono eseguire la funzionalità eDiscovery in locale e scegliere una delle seguenti azioni:
  
- **Stima risultati della ricerca** Consente di ottenere una stima del numero di messaggi restituiti dalla ricerca, incluse le statistiche sulle parole chiave, per determinare l'efficacia delle parole chiave utilizzate nella ricerca e modificare i parametri di ricerca, se necessario. 
    
- **Anteprima dei risultati della ricerca**
    
- Copiare i messaggi restituiti nei risultati di ricerca in una cassetta postale di individuazione.
    
Per ulteriori informazioni, vedere [eDiscovery in locale](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Regole del flusso di posta

È possibile utilizzare le regole del flusso di posta per cercare condizioni specifiche sui messaggi che passano attraverso l'organizzazione e agire su di essi. Le regole del flusso di posta consentono di applicare criteri di messaggistica ai messaggi di posta elettronica, proteggere i messaggi, proteggere i sistemi di messaggistica e impedire la perdita di informazioni.
  
Molte organizzazioni sono oggi obbligate dalla legge, dai requisiti normativi e dai criteri aziendali ad applicare i criteri di messaggistica per limitare l'interazione tra destinatari e mittenti, sia all'interno sia all'esterno dell'organizzazione. Oltre a limitare le interazioni tra singoli utenti, gruppi di reparto all'interno dell'organizzazione ed entità esterne all'organizzazione, alcune organizzazioni sono soggette anche ai seguenti requisiti dei criteri di messaggistica:
  
- Blocco di contenuto inappropriato in entrata o in uscita dall'organizzazione
    
- Filtro di informazioni riservate dell'organizzazione
    
- Verifica o copia di messaggi inviati a o ricevuti da determinate persone
    
- Reindirizzamento di messaggi in entrata o in uscita per l'ispezione prima del recapito
    
- Applicazione di dichiarazioni di non responsabilità ai messaggi che transitano nell'organizzazione
    
> [!IMPORTANT]
> I tipi di file allegati che richiedono l'installazione di iFilter di terze parti nel server di posta elettronica (ad esempio Adobe .pdf) non possono essere esaminati utilizzando le regole del flusso di posta finché non viene installato un iFilter appropriato. Per ulteriori informazioni sui tipi di file supportati dalle regole del flusso di posta, vedere [Use mail flow rules to inspect message attachments in Office 365](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Per ulteriori informazioni sulle regole del flusso di posta, vedere [Mail flow rules in Exchange 2016](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Prevenzione della perdita di dati

La funzionalità di prevenzione della perdita dei dati consente di identificare, monitorare e proteggere le informazioni sensibili dell'organizzazione attraverso un'approfondita analisi dei contenuti. La prevenzione della perdita dei dati è una funzionalità avanzata che sta diventando sempre più importante per i sistemi di messaggistica aziendali, in quanto i messaggi di posta elettronica business-critical contengono informazioni sensibili che devono protette. La funzionalità DLP in Exchange Online consente di proteggere i dati sensibili senza influire sulla produttività dei lavoratori.
  
È possibile configurare i criteri DLP nell'interfaccia di gestione dell'interfaccia di amministrazione di Exchange per: 
  
- Attivare un modello dei criteri preconfigurato che consente di rilevare specifiche tipologie di informazioni sensibili, come i dati PCI-DSS, i dati della legge Gramm-Leach-Bliley o perfino i dati personali in una specifica lingua.
    
- Utilizzare l'efficacia dei criteri e delle azioni delle regole di trasporto esistenti e aggiungere nuove regole.
    
- Testare l'efficacia dei criteri di prevenzione della perdita dei dati prima di metterle in atto.
    
- Incorporare i propri modelli dei criteri di prevenzione della perdita dei dati e i propri tipi di informazioni sensibili.
    
- Rilevare le informazioni riservate negli allegati dei messaggi, nel corpo del testo o nelle righe dell'oggetto e regolare il livello di probabilità a cui Exchange Online messaggi.
    
- I dati sensibili vengono rilevati mediante l'impronta digitale del documento. L'impronta digitale del documento facilita la creazione di tipi di informazione sensibili personalizzate basate su moduli di testo utilizzabili per definire le regole di trasporto e i criteri DLP.
    
- Aggiungi Suggerimenti criteri, che consente di ridurre la perdita di dati visualizzando un avviso per gli utenti di Outlook 2016, Outlook 2013, Outlook sul web e OWA per dispositivi e può anche migliorare l'efficacia dei criteri consentendo la segnalazione di falsi positivi. 
    
- Analizzare i dati delle operazioni non consentite nei rapporti sulla prevenzione della perdita dei dati oppure aggiungere rapporti personalizzati tramite l'azione di creazione dei rapporti operazioni non consentite.
    
Per ulteriori informazioni sulla prevenzione della perdita dei dati (DLP), vedere [Prevenzione della perdita dei dati](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Inserimento nel journal

È possibile configurare Exchange Online in modo che inserisca le copie di messaggi di posta elettronica nel journal di una cassetta postale esterna in grado di ricevere i messaggi tramite SMTP. La creazione del journal consente alle organizzazioni di soddisfare i requisiti di conformità legale, normativa e organizzativa registrando le comunicazioni di posta elettronica in entrata e in uscita. Quando si pianifica un sistema per garantire la conservazione e la conformità dei messaggi, è fondamentale avere ben chiaro il concetto di inserimento in un journal ed essere in grado di adattarlo ai criteri di conformità dell'organizzazione.
  
È possibile gestire le regole del journal utilizzando l'interfaccia di amministrazione di Exchange oppure Windows PowerShell remoto. È possibile configurare l'inserimento nel journal in base all'utente e in base alla lista di distribuzione e scegliere di inserire nel journal solo i messaggi interni, solo i messaggi esterni oppure entrambi. I messaggi inseriti nel journal sono costituiti non soltanto dal messaggio originale, ma anche dalle informazioni su mittente, destinatario, CC e CC nascosti.
  
Per garantire una soluzione di inserimento nel journal corretta e affidabile, è necessario completare le attività seguenti:
  
- Assicurarsi che la destinazione di inserimento nel journal non sia una Exchange Online cassetta postale.
    
- Creare nella directory del cliente un oggetto contatto per l'indirizzo di posta elettronica di destinazione SMTP da utilizzare per l'inserimento nel journal.
    
- Creare un secondo oggetto contatto come cassetta postale del journal alternativa per catturare i rapporti del journal nel caso in cui la cassetta postale del journal principale sia indisponibile.
    
- Mantenere livelli di gestione, ridondanza, disponibilità, prestazioni e funzionalità adeguati della destinazione SMTP per garantire sempre la corretta accettazione della posta.
    
- Fornire la necessaria interoperabilità con Exchange Server e il trasporto di Exchange inclusi i formati dei messaggi, l'integrazione delle informazioni su mittente/destinatario e l'appropriata conversione dei contenuti.
    
Per informazioni sull'inserimento nel journal, vedere [Inserimento nel journal](/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Exchange Online [descrizione del servizio.](exchange-online-service-description.md)
