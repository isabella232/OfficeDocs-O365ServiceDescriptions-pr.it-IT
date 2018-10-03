---
title: Criteri dei messaggi e conformità
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: fd5062df19298720417566d91667f3c3b237b164
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036188"
---
# <a name="message-policy-and-compliance"></a>Criteri dei messaggi e conformità

## <a name="archiving-exchange-online-based-mailboxes"></a>Archiviazione di cassette postali di Exchange Online

Le cassette postali di Exchange Online risiedono nel cloud e la loro archiviazione richiede ambienti host univoci. In alcuni casi, è possibile utilizzare Exchange Online per archiviare le cassette postale locali nel cloud. In questa sezione vengono descritte le opzioni per l'archiviazione in Exchange Online.
  
Exchange Online dispone di funzionalità di archiviazione integrate per le cassette postali basate su cloud, tra cui un Archivio in locale che consente agli utenti di archiviare comodamente i messaggi di posta elettronica meno recenti. Un Archivio in locale è una speciale cassetta postale che viene visualizzata insieme alle cartelle della cassetta postale principale di un utente in Outlook e Outlook Web App. Gli utenti possono accedere all'archivio ed effettuarvi ricerche esattamente come fanno per le cassette postali principali. Le funzionalità disponibili dipendono dal client in uso:
  
- **Outlook 2016, Outlook 2013, Outlook 2010 e Outlook Web App** Gli utenti hanno accesso a tutte le funzionalità dell'archivio e alle relative funzionalità di conformità, come il controllo sui criteri di conservazione e archiviazione. 
    
- **Outlook 2007** Gli utenti dispongono di un supporto base per l'Archivio in locale e non tutte le funzionalità di archiviazione e conformità sono disponibili. Ad esempio, gli utenti non possono applicare i criteri di archiviazione o conservazione agli elementi di una cassetta postale e devono avvalersi invece dei criteri stabiliti dall'amministratore. 
    
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per abilitare la funzionalità di archiviazione personalizzata per specifici utenti.
  
Per ulteriori informazioni, vedere:
  
- [Cassette postali di archiviazione in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [Abilitare o disabilitare una cassetta postale di archiviazione in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a>Dimensioni degli archivi

Ciascun archivio personale può contenere i dati di messaggistica di un solo utente. L'allocazione di spazio di archiviazione dipende dal piano di abbonamento. Per ulteriori informazioni sulle dimensioni delle cassette postali di archiviazione, vedere la sezione "Limiti di archiviazione delle cassette postali" in [Limiti Exchange Online Limits](exchange-online-limits.md).
  
> [!IMPORTANT]
> L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a una cassetta postale di Exchange Online a scopo di archiviazione non è consentito. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione non sia utilizzata in uno scenario personale. > L'archivio locale presenta specifici requisiti di licenza per gli utenti di Outlook. Gli utenti di Outlook 2007 devono disporre dell'aggiornamento cumulativo di Office 2007 del febbraio 2011 per poter accedere all'archivio personale. > Exchange Online non supporta il cmdlet  _New-MailboxImportRequest_ di Windows PowerShell in Exchange Server 2010 Service Pack 1 o versioni successive per l'importazione di file pst in un archivio personale da parte dell'amministratore. Se un utente dispone sia della cassetta postale principale sia dell'archivio in Exchange Online, un amministratore può utilizzare PST Capture, uno strumento gratuito, per importare i dati dei file pst nella cassetta postale principale o nell'archivio dell'utente. 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archiviazione basata su cloud delle cassette postali locali

L'utilizzo di Exchange Online per l'archiviazione su cloud di cassette postali locali di Exchange Server 2010 o versioni successive è possibile tramite Archiviazione Microsoft Exchange Online, una soluzione di archiviazione su host fornita da Microsoft. Ciò richiede che l'organizzazione locale sia in modalità ibrida oppure sia impostata per l'archiviazione Exchange Online.
  
> [!IMPORTANT]
> Gli utenti che dispongono di una cassetta postale locale su un server cassette postali Exchange 2010 e per i quali sono applicati i criteri per le cartelle gestite non possono avere un Archivio in locale o su cloud abilitato. 
  
## <a name="retention-tags-and-retention-policies"></a>Tag di conservazione e criteri di conservazione

Exchange Online fornisce dei criteri di conservazione che consentono alle organizzazioni di ridurre le responsabilità associate ai messaggi di posta elettronica e ad altre comunicazioni. Con questi criteri, gli amministratori possono applicare le impostazioni di conservazione a specifiche cartelle nelle cassette postali degli utenti. Gli amministratore possono anche fornire agli utenti un menu di criteri di conservazione e permettere loro di applicarli a particolari elementi, conversazioni o cartelle utilizzando Outlook 2010 o versioni successive oppure Outlook Web App.
  
In Exchange Online, gli amministratori gestiscono i criteri di conservazione tramite l'interfaccia di amministrazione di Exchange o tramite Windows PowerShell remoto.
  
Exchange Online fornisce due tipi di criteri: i criteri di archiviazione e i criteri di eliminazione. Entrambi i tipi di criteri possono essere combinati nello stesso elemento o nella stessa cartella. Ad esempio, un utente può assegnare un tag a un messaggio di posta elettronica in modo che il messaggio venga automaticamente spostato dopo un dato numero di giorni ed eliminato dopo un ulteriore numero di giorni.
  
Con Outlook 2010 o versioni successive e Outlook Web App, gli utenti possono applicare i criteri di conservazione alle cartelle, alle conversazioni o a messaggi specifici. Possono altresì visualizzare i criteri di conservazione applicati e le date di eliminazione previste per i messaggi. Gli utenti di altri client di posta elettronica possono solo eliminare o archiviare i propri messaggi di posta elettronica sulla base dei criteri di conservazione definiti dall'amministratore sul server.
  
I criteri di conservazione disponibili Exchange Online sono gli stessi disponibili in Exchange Server 2010 Service Pack 2 RU4. Gli amministratori possono utilizzare Windows PowerShell in remoto per migrare i criteri di conservazione dagli ambienti Exchange Server 2010 in locale o versioni successive a Exchange Online.
  
> [!IMPORTANT]
> Le cartelle gestite, che rappresentano il precedente metodo di gestione dei record di messaggistica introdotto in Exchange Server 2007, non sono più disponibili in Exchange Online. 
  
Per ulteriori informazioni, vedere [Tag di conservazione e criteri di conservazione](https://go.microsoft.com/fwlink/p/?LinkId=271745).
  
## <a name="encryption-of-data-at-rest"></a>Crittografia dei dati statici

Crittografia dei dati dei clienti di Office 365 statici fornita da più tecnologie di lato del servizio, inclusi BitLocker, DKM, la crittografia del servizio di archiviazione Azure e la crittografia del servizio di Exchange Online, Skype for Business, OneDrive for Business e SharePoint In linea. Office 365 la crittografia del servizio includono un'opzione per utilizzare chiavi di crittografia gestite cliente archiviate in Azure chiave cassaforte. Questa opzione chiave cliente gestiti, denominata [Chiave dei clienti di Office 365](https://go.microsoft.com/fwlink/?linkid=863349), è disponibile per Exchange Online, SharePoint Online e OneDrive for Business. 
  
### <a name="bitlocker"></a>BitLocker

Server di Office 365 utilizzare BitLocker per crittografare le unità disco contenente i dati dei clienti statici a livello di volume. BitLocker è una funzionalità di protezione di dati che è incorporata in Windows. BitLocker è una delle tecnologie utilizzate per la protezione contro le minacce nel caso in cui sono disponibili falle in altri processi o controlli (ad esempio, il controllo di accesso o riciclo di componenti hardware) che potrebbero causare un utente l'accesso fisico per i dischi che contengono i dati dei clienti. In questo caso, BitLocker Elimina il rischio di esposizione o furto di dati a causa di dischi e i computer perse, furto o rimozione delle autorizzazioni in modo improprio. 
  
### <a name="distributed-key-manager"></a>Gestione chiavi distribuita

Oltre a BitLocker, si utilizza una tecnologia denominata distribuita chiave Manager (DKM). DKM è una funzionalità sul lato client che utilizzano un set di chiavi segrete per la crittografia e decrittografia di informazioni. Le chiavi per decrittografare i dati crittografati per DKM possono accedere solo i membri di un gruppo di protezione specifiche in servizi di dominio Active Directory. In Exchange Online, solo determinati account di servizio in cui vengono eseguiti i processi di Exchange sono parte di tale gruppo di protezione. Come parte della procedura operativa standard nel centro dati, non umane sono assegnate le credenziali che fanno parte di questo gruppo di protezione e pertanto non umane dispone dell'accesso alle chiavi che possa essere decrittografato queste informazioni riservate.
  
## <a name="customer-key"></a>Chiave cliente

Con clienti chiave, controllare le chiavi di crittografia della propria organizzazione e quindi configurare Office 365 per utilizzarli per crittografare i dati statici nei centri dati di Microsoft. Dati statici includono i dati da Exchange Online e Skype for Business archiviati nelle cassette postali e i file archiviati in SharePoint Online e OneDrive for Business. Per ulteriori informazioni, vedere [il controllo dei dati in Office 365 con chiave cliente](https://go.microsoft.com/fwlink/?linkid=863349) e [Servizio di crittografia con chiave cliente di domande frequenti di Office 365](https://go.microsoft.com/fwlink/?linkid=869438).
  
## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365
<a name="bkmk_O365_MessageEncryption"> </a>

Crittografia dei messaggi di Office 365 consente agli utenti di posta elettronica inviare messaggi di posta elettronica crittografata a tutti gli utenti. Viene annunciato nuove funzionalità disponibili in crittografia dei messaggi di Office che sfruttano le funzionalità di protezione della crittografia informazioni di Azure. Queste nuove funzionalità disponibili avanzate degli utenti finali che rendono più semplice condividere e collaborare ai messaggi protetti con altre persone interne o esterne all'organizzazione. Le nuove funzionalità di crittografia dei messaggi di Office devono soddisfare alcuni requisiti il programma di installazione. Vedere Set up le nuove funzionalità di Office 365 Message Encryption basate sulla protezione delle informazioni di Azure. I clienti in Office 365 Message Encryption legacy non ricevere le nuove funzionalità senza seguire il set di istruzioni fornite in precedenza. Leggere le [domande frequenti](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) per ulteriori informazioni sul contenuto delle nuove e funzionalità di Office 365 Message Encryption legacy. 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)
<a name="bkmk_O365_MessageEncryption"> </a>

S/MIME consente di proteggere le informazioni riservate inviando messaggi di posta elettronica firmati e crittografati all'interno dell'organizzazione. Gli amministratori possono utilizzare Windows PowerShell in remoto per configurare S/MIME dopo aver stabilito e rilasciato i certificati PKI agli utenti. Tali certificati devono essere sincronizzati da un servizio certificati Active Directory locale.
  
S/MIME è supportato in Internet Explorer 9 o versione successiva. Al momento, S/MIME non è supportato su Firefox, Opera e Chrome. Per ulteriori informazioni, vedere [S/MIME per la funzionalità di firma e crittografia dei messaggi](https://go.microsoft.com/fwlink/p/?LinkID=393973).
  
## <a name="in-place-hold-and-litigation-hold"></a>Archiviazione sul posto e conservazione per controversia legale
<a name="bkmk_O365_MessageEncryption"> </a>

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
  
Per ulteriori informazioni, vedere [Conservazione in locale](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="in-place-ediscovery"></a>eDiscovery in locale
<a name="bkmk_O365_MessageEncryption"> </a>

Exchange Online consente ai clienti di effettuare ricerche nei contenuti delle cassette postali di un'organizzazione tramite un'interfaccia basata sul Web. Gli amministratori o i responsabili di conformità e protezione autorizzati a eseguire ricerche eDiscovery in locale (mediante assegnazione) possono effettuare ricerche nei messaggi di posta elettronica, negli allegati, negli appuntamenti sul calendario, nelle attività, nei contatti e in altri elementi. La ricerca eDiscovery in locale può essere eseguita simultaneamente negli archivi e nelle cassette postali primarie. Tra gli efficienti filtri disponibili ci sono quelli per mittente, destinatario, tipo di messaggio, data di invio/ricezione e Cc/Bcc, oltre a quelli per la sintassi KQL. I risultati della ricerca includono anche gli elementi contenuti nella cartella Posta eliminata, se soddisfano i criteri di ricerca specificati.
  
I risultati delle ricerche eDiscovery in locale possono essere visualizzati in anteprima in un'interfaccia basata sul Web, esportati in un file PST oppure copiati in una particolare cassetta postale detta "cassetta postale di individuazione". Una cassetta postale di individuazione ha una quota di 50 GB per l'archiviazione dei risultati della ricerca. Gli amministratori possono connettere Outlook alla cassetta postale di individuazione per accedere ai risultati della ricerca ed esportarli come file .pst.
  
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per effettuare ricerche in più cassette postali. L'interfaccia di amministrazione di Exchange è in grado di fornire un'anteprima di sola lettura dei risultati della ricerca, permettendo agli amministratori di verificarli e, se necessario, di eseguire di nuovo la ricerca con altri parametri. Una volta ottimizzata la ricerca, l'amministratore può copiare i risultati nella cassetta postale di individuazione.
  
Per impostazione predefinita, viene creata una cassetta postale di individuazione per ciascuna organizzazione, ma gli amministratori possono creare altre cassette postali di individuazione utilizzando Windows PowerShell in remoto. Le cassette postali di individuazione possono essere utilizzate solo per archiviare i risultati delle ricerche eDiscovery in locale.
  
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per effettuare ricerche eDiscovery in locale. L'interfaccia di amministrazione di Exchange è in grado di fornire un'anteprima di sola lettura dei risultati della ricerca, permettendo agli amministratori di verificarli e, se necessario, di eseguire di nuovo la ricerca con altri parametri. Una volta ottimizzata la ricerca, l'amministratore può copiare i risultati nella cassetta postale di individuazione o esportarli in un file PST.
  
Gli amministratori possono utilizzare l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per cercare fino a 10.000 cassette postali alla volta in una ricerca eDiscovery sul posto. 
  
In Exchange Online, gli utenti autorizzati possono eseguire la funzionalità eDiscovery in locale e scegliere una delle seguenti azioni:
  
- **Stima risultati della ricerca** Consente di ottenere una stima del numero di messaggi restituiti dalla ricerca, incluse le statistiche sulle parole chiave, per determinare l'efficacia delle parole chiave utilizzate nella ricerca e modificare i parametri di ricerca, se necessario. 
    
- **Anteprima dei risultati della ricerca**
    
- Copiare i messaggi restituiti nei risultati di ricerca in una cassetta postale di individuazione.
    
Per ulteriori informazioni, vedere [eDiscovery in locale](http://go.microsoft.com/fwlink/p/?LinkId=271747).
  
## <a name="mail-flow-rules"></a>Regole del flusso di posta
<a name="bkmk_O365_MessageEncryption"> </a>

È possibile utilizzare regole del flusso di posta elettronica per cercare le condizioni specifiche nei messaggi che transitano attraverso l'organizzazione e agiscono su di essi. Regole del flusso di posta elettronica consentono di applicare i criteri di messaggistica per i messaggi di posta elettronica, messaggi protetti, proteggere i sistemi di messaggistica e impedire la perdita di informazioni.
  
Molte organizzazioni sono oggi obbligate dalla legge, dai requisiti normativi e dai criteri aziendali ad applicare i criteri di messaggistica per limitare l'interazione tra destinatari e mittenti, sia all'interno sia all'esterno dell'organizzazione. Oltre a limitare le interazioni tra singoli utenti, gruppi di reparto all'interno dell'organizzazione ed entità esterne all'organizzazione, alcune organizzazioni sono soggette anche ai seguenti requisiti dei criteri di messaggistica:
  
- Blocco di contenuto inappropriato in entrata o in uscita dall'organizzazione
    
- Filtro di informazioni riservate dell'organizzazione
    
- Verifica o copia di messaggi inviati a o ricevuti da determinate persone
    
- Reindirizzamento di messaggi in entrata o in uscita per l'ispezione prima del recapito
    
- Applicazione di dichiarazioni di non responsabilità ai messaggi che transitano nell'organizzazione
    
> [!IMPORTANT]
> Tipi di file allegati che richiedono l'installazione di filtri IFilter di terze parti nel server di posta elettronica (ad esempio Adobe PDF) non può essere verificati utilizzando regole del flusso di posta elettronica fino a dopo l'installazione di un filtro iFilter appropriato. Per ulteriori informazioni sui tipi di file supportati dalle regole di flusso di posta elettronica, vedere [utilizzare le regole del flusso di posta elettronica per esaminare messaggi con allegati in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748). 
  
Per ulteriori informazioni sulle regole del flusso di posta, vedere [Mail flow rules in Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488).
  
## <a name="data-loss-prevention"></a>Prevenzione della perdita di dati
<a name="bkmk_O365_MessageEncryption"> </a>

La funzionalità di prevenzione della perdita dei dati consente di identificare, monitorare e proteggere le informazioni sensibili dell'organizzazione attraverso un'approfondita analisi dei contenuti. La prevenzione della perdita dei dati è una funzionalità avanzata che sta diventando sempre più importante per i sistemi di messaggistica aziendali, in quanto i messaggi di posta elettronica business-critical contengono informazioni sensibili che devono protette. La funzionalità di prevenzione della perdita dei dati in Exchange Online consente agli amministratori di proteggere i dati sensibili senza influire negativamente sulla produttività degli utenti.
  
È possibile configurare i criteri DLP nell'interfaccia di gestione dell'interfaccia di amministrazione di Exchange per: 
  
- Attivare un modello dei criteri preconfigurato che consente di rilevare specifiche tipologie di informazioni sensibili, come i dati PCI-DSS, i dati della legge Gramm-Leach-Bliley o perfino i dati personali in una specifica lingua.
    
- Utilizzare l'efficacia dei criteri e delle azioni delle regole di trasporto esistenti e aggiungere nuove regole.
    
- Testare l'efficacia dei criteri di prevenzione della perdita dei dati prima di metterle in atto.
    
- Incorporare i propri modelli dei criteri di prevenzione della perdita dei dati e i propri tipi di informazioni sensibili.
    
- Rileva informazioni riservate in righe oggetto, corpo del testo o allegati del messaggio e regolare il livello di probabilità in cui Exchange Online agisce.
    
- I dati sensibili vengono rilevati mediante l'impronta digitale del documento. L'impronta digitale del documento facilita la creazione di tipi di informazione sensibili personalizzate basate su moduli di testo utilizzabili per definire le regole di trasporto e i criteri DLP.
    
- Aggiungere dei suggerimenti relativi ai criteri che possono contribuire a ridurre la perdita di dati presentando un avviso agli utenti di Outlook 2016, Outlook 2013, Outlook Web App e OWA e a migliorare l'efficienza dei criteri applicati permettendo agli utenti di segnalare eventuali falsi positivi.  
    
- Analizzare i dati delle operazioni non consentite nei rapporti sulla prevenzione della perdita dei dati oppure aggiungere rapporti personalizzati tramite l'azione di creazione dei rapporti operazioni non consentite.
    
Per ulteriori informazioni sulla prevenzione della perdita dei dati (DLP), vedere [Prevenzione della perdita dei dati](https://go.microsoft.com/fwlink/p/?LinkId=271749).
  
## <a name="journaling"></a>Inserimento nel journal
<a name="bkmk_O365_MessageEncryption"> </a>

È possibile configurare Exchange Online in modo che inserisca le copie di messaggi di posta elettronica nel journal di una cassetta postale esterna in grado di ricevere i messaggi tramite SMTP. La creazione del journal consente alle organizzazioni di soddisfare i requisiti di conformità legale, normativa e organizzativa registrando le comunicazioni di posta elettronica in entrata e in uscita. Quando si pianifica un sistema per garantire la conservazione e la conformità dei messaggi, è fondamentale avere ben chiaro il concetto di inserimento in un journal ed essere in grado di adattarlo ai criteri di conformità dell'organizzazione.
  
È possibile gestire le regole del journal utilizzando l'interfaccia di amministrazione di Exchange oppure Windows PowerShell remoto. È possibile configurare l'inserimento nel journal in base all'utente e in base alla lista di distribuzione e scegliere di inserire nel journal solo i messaggi interni, solo i messaggi esterni oppure entrambi. I messaggi inseriti nel journal sono costituiti non soltanto dal messaggio originale, ma anche dalle informazioni su mittente, destinatario, CC e CC nascosti.
  
Per garantire una soluzione di inserimento nel journal efficiente e affidabile, è necessario completare le attività seguenti:
  
- Verificare che il journal di destinazione non è in una cassetta postale di Exchange Online.
    
- Creare nella directory del cliente un oggetto contatto per l'indirizzo di posta elettronica di destinazione SMTP da utilizzare per l'inserimento nel journal.
    
- Creare un secondo oggetto contatto come cassetta postale del journal alternativa per catturare i rapporti del journal nel caso in cui la cassetta postale del journal principale sia indisponibile.
    
- Mantenere una corretta gestione, ridondanza, disponibilità, prestazioni e livelli di funzionalità della destinazione SMTP per garantire sempre l'accettazione della posta.
    
- Fornire la necessaria interoperabilità con Exchange Server e il trasporto di Exchange inclusi i formati dei messaggi, l'integrazione delle informazioni su mittente/destinatario e l'appropriata conversione dei contenuti.
    
Per informazioni sull'inserimento nel journal, vedere [Inserimento nel journal](https://go.microsoft.com/fwlink/p/?LinkId=271750).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità
<a name="bkmk_O365_MessageEncryption"> </a>

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  
