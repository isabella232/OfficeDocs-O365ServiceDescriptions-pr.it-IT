---
title: Conformità e criteri dei messaggi
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132700"
---
# <a name="message-policy-and-compliance"></a>Conformità e criteri dei messaggi

## <a name="archiving-exchange-online-based-mailboxes"></a>Archiviazione di cassette postali di Exchange Online

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online dispone di funzionalità di archiviazione integrate per le cassette postali basate su cloud, tra cui un Archivio in locale che consente agli utenti di archiviare comodamente i messaggi di posta elettronica meno recenti. Un archivio sul posto è un tipo speciale di cassetta postale che viene visualizzata accanto alle cartelle principali delle cassette postali di un utente in Outlook e Outlook sul Web. Gli utenti possono accedere all'archivio ed effettuarvi ricerche esattamente come fanno per le cassette postali principali. Le funzionalità disponibili dipendono dal client in uso:
  
- **Outlook 2016, outlook 2013, outlook 2010 e Outlook sul Web** Gli utenti possono accedere alle funzionalità complete dell'archivio, nonché alle relative funzionalità di conformità, come il controllo sui criteri di conservazione e archiviazione. 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
Gli amministratori utilizzano l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per abilitare la funzionalità di archiviazione personalizzata per specifici utenti.
  
Per ulteriori informazioni, vedere:
  
- [Cassette postali di archiviazione in Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [Abilitare o disabilitare una cassetta postale di archiviazione in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Dimensioni degli archivi

Ciascun archivio personale può contenere i dati di messaggistica di un solo utente. L'allocazione di spazio di archiviazione dipende dal piano di abbonamento. Per ulteriori informazioni sulle dimensioni delle cassette postali di archiviazione, vedere la sezione "limiti di archiviazione delle cassette postali" in [limiti di Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> - L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a una cassetta postale di Exchange Online a scopo di archiviazione non è consentito. Microsoft si riserva il diritto di negare l'archiviazione illimitata nei casi in cui un archivio di cassette postali non viene utilizzato in uno scenario personale o in altri casi di utilizzo inappropriato.
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange Online non supporta il cmdlet _New-MailboxImportRequest_ di Windows PowerShell di exchange server 2010 Service Pack 1 o versioni successive per l'importazione guidata dall'amministratore dei file PST in un archivio personale. Se un utente dispone sia della cassetta postale principale sia dell'archivio in Exchange Online, un amministratore può utilizzare PST Capture, uno strumento gratuito, per importare i dati dei file pst nella cassetta postale principale o nell'archivio dell'utente.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Archiviazione basata su cloud delle cassette postali locali

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> Gli utenti che dispongono di una cassetta postale locale su un server cassette postali Exchange 2010 e per i quali sono applicati i criteri per le cartelle gestite non possono avere un Archivio in locale o su cloud abilitato. 
  
## <a name="retention-tags-and-retention-policies"></a>Tag di conservazione e criteri di conservazione

Exchange Online fornisce dei criteri di conservazione che consentono alle organizzazioni di ridurre le responsabilità associate ai messaggi di posta elettronica e ad altre comunicazioni. Con questi criteri, gli amministratori possono applicare le impostazioni di conservazione a specifiche cartelle nelle cassette postali degli utenti. Gli amministratori possono anche fornire agli utenti un menu di criteri di conservazione e consentire loro di applicare i criteri a elementi, conversazioni o cartelle specifici utilizzando Outlook 2010 o versione successiva o Outlook sul Web.
  
In Exchange Online, gli amministratori gestiscono i criteri di conservazione tramite l'interfaccia di amministrazione di Exchange o tramite Windows PowerShell remoto.
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
Con Outlook 2010 o versioni successive e Outlook sul Web, gli utenti possono applicare i criteri di conservazione alle cartelle, alle conversazioni o ai singoli messaggi. Possono altresì visualizzare i criteri di conservazione applicati e le date di eliminazione previste per i messaggi. Gli utenti di altri client di posta elettronica possono solo eliminare o archiviare i propri messaggi di posta elettronica sulla base dei criteri di conservazione definiti dall'amministratore sul server.
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> Le cartelle gestite, che rappresentano il precedente metodo di gestione dei record di messaggistica introdotto in Exchange Server 2007, non sono più disponibili in Exchange Online. 
  
Per ulteriori informazioni, vedere [Tag di conservazione e criteri di conservazione](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Crittografia dei dati statici

La crittografia dei dati del cliente a riposo è fornita da più tecnologie sul fianco del servizio, tra cui BitLocker, DKM, la crittografia del servizio di archiviazione di Azure e la crittografia del servizio in Exchange Online, Skype for business, OneDrive for business e SharePoint Online. La crittografia dei servizi di Office 365 include un'opzione per l'utilizzo delle chiavi di crittografia gestite dal cliente archiviate in Azure Key Vault. Questa opzione di chiave gestita dal cliente, denominata [Customer Key](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697), è disponibile per Exchange Online, SharePoint Online e OneDrive for business. 
  
### <a name="bitlocker"></a>BitLocker

I server Microsoft utilizzano BitLocker per crittografare le unità disco che contengono i dati dei clienti a riposo a livello di volume. La crittografia BitLocker è una funzionalità di protezione dei dati incorporata in Windows. BitLocker è una delle tecnologie utilizzate per la salvaguardia dalle minacce, nel caso in cui si verifichino ricadute in altri processi o controlli, ad esempio il controllo dell'accesso o il riciclo dell'hardware, che potrebbero determinare un accesso fisico ai dischi che contengono i dati dei clienti. In questo caso, BitLocker Elimina le potenzialità per il furto o l'esposizione dei dati a causa di computer e dischi persi, rubati o disattivati in modo inappropriato. 
  
### <a name="distributed-key-manager"></a>Gestione delle chiavi distribuite

Oltre a BitLocker, viene utilizzata una tecnologia denominata Distributed Key Manager (DKM). DKM è una funzionalità sul retro del client che utilizza un set di chiavi segrete per crittografare e decrittografare le informazioni. Solo i membri di un gruppo di sicurezza specifico in servizi di dominio Active Directory possono accedere a tali chiavi per decrittografare i dati crittografati da DKM. In Exchange Online, fanno parte di quel determinato gruppo di sicurezza solo determinati account di servizio nei quali sono in esecuzione i processi di Exchange. Nell'ambito della procedura operativa standard nel datacenter, le credenziali che fanno parte del gruppo di sicurezza non vengono fornite a nessuno; pertanto, nessuno ha accesso alle chiavi in grado di decrittografare le informazioni riservate.
  
## <a name="customer-key"></a>Customer Key

Con la chiave Customer, è possibile controllare le chiavi di crittografia dell'organizzazione e quindi configurarle per crittografare i dati a riposo nei data center di Microsoft. Data at rest include i dati di Exchange Online e Skype for business archiviati nelle cassette postali e nei file archiviati in SharePoint Online e OneDrive for business. Per ulteriori informazioni, vedere [controlling your data in using Customer Key](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) and [Service Encryption with Customer Key FAQ](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

La crittografia dei messaggi di Office 365 consente agli utenti di inviare messaggi di posta elettronica crittografati a qualsiasi utente. Sono state annunciate nuove funzionalità nella crittografia dei messaggi di Office che sfruttano le funzionalità di protezione nella crittografia delle informazioni di Azure. Queste nuove funzionalità hanno fornito esperienze degli utenti finali avanzate che facilitano la condivisione e la collaborazione dei messaggi protetti con chiunque sia all'interno che all'esterno dell'organizzazione. Le nuove funzionalità di crittografia dei messaggi di Office presentano alcuni requisiti di installazione. Vedere Configurare le nuove funzionalità di crittografia dei messaggi di Office 365 basate su Azure Information Protection. I clienti sulla crittografia dei messaggi di Office 365 legacy non ottengono le nuove funzionalità senza seguire le istruzioni di installazione fornite sopra. Per ulteriori informazioni, vedere le [domande frequenti](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) su cosa è incluso nelle nuove funzionalità di crittografia dei messaggi di Office 365. 

La crittografia avanzata dei messaggi di Office 365 fornisce ulteriore protezione consentendo la scadenza e la revoca del messaggio.  È inoltre possibile creare più modelli per i messaggi di posta elettronica crittografati provenienti dall'organizzazione.  La crittografia avanzata dei messaggi è inclusa in Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (nonprofit staff pricing), Office 365 Enterprise E5 (nonprofit staff pricing) o Office 365 Education a5. Se l'organizzazione dispone di un abbonamento che non include la crittografia dei messaggi avanzata di Office 365, è possibile acquistare la conformità Microsoft 365 E5 o la SKU di Office 365 Advanced Compliance come componente aggiuntivo.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
S/MIME è supportato in Microsoft Edge e Internet Explorer 11. Al momento, S/MIME non è supportato su Firefox, Opera e Chrome. Per ulteriori informazioni, vedere [S/MIME per la funzionalità di firma e crittografia dei messaggi](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Archiviazione sul posto e conservazione per controversia legale

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
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
  
Per ulteriori informazioni, vedere [Conservazione in locale](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>eDiscovery sul posto

Exchange Online consente ai clienti di eseguire ricerche nei contenuti delle cassette postali in un'organizzazione tramite un'interfaccia basata sul Web. Gli amministratori o i responsabili di conformità e protezione autorizzati a eseguire ricerche eDiscovery in locale (mediante assegnazione) possono effettuare ricerche nei messaggi di posta elettronica, negli allegati, negli appuntamenti sul calendario, nelle attività, nei contatti e in altri elementi. La ricerca eDiscovery in locale può essere eseguita simultaneamente negli archivi e nelle cassette postali primarie. Tra gli efficienti filtri disponibili ci sono quelli per mittente, destinatario, tipo di messaggio, data di invio/ricezione e Cc/Bcc, oltre a quelli per la sintassi KQL. I risultati della ricerca includono anche gli elementi contenuti nella cartella Posta eliminata, se soddisfano i criteri di ricerca specificati.
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
Gli amministratori possono utilizzare l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto per cercare fino a 10.000 cassette postali alla volta in una ricerca eDiscovery sul posto. 
  
In Exchange Online, gli utenti autorizzati possono eseguire la funzionalità eDiscovery in locale e scegliere una delle seguenti azioni:
  
- **Stima risultati della ricerca** Consente di ottenere una stima del numero di messaggi restituiti dalla ricerca, incluse le statistiche sulle parole chiave, per determinare l'efficacia delle parole chiave utilizzate nella ricerca e modificare i parametri di ricerca, se necessario. 
    
- **Anteprima dei risultati della ricerca**
    
- Copiare i messaggi restituiti nei risultati di ricerca in una cassetta postale di individuazione.
    
Per ulteriori informazioni, vedere [eDiscovery in locale](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Regole del flusso di posta

È possibile utilizzare le regole del flusso di posta per cercare condizioni specifiche sui messaggi che passano attraverso l'organizzazione e agiscono su di essi. Le regole del flusso di posta consentono di applicare i criteri di messaggistica ai messaggi di posta elettronica, garantire messaggi, proteggere i sistemi di messaggistica e impedire la perdita di informazioni.
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- Blocco di contenuto inappropriato in entrata o in uscita dall'organizzazione
    
- Filtro di informazioni riservate dell'organizzazione
    
- Verifica o copia di messaggi inviati a o ricevuti da determinate persone
    
- Reindirizzamento di messaggi in entrata o in uscita per l'ispezione prima del recapito
    
- Applicazione di dichiarazioni di non responsabilità ai messaggi che transitano nell'organizzazione
    
> [!IMPORTANT]
> I tipi di file degli allegati che richiedono l'installazione di filtri iFilter di terze parti sul server di posta elettronica (ad esempio Adobe. pdf) non possono essere controllati utilizzando le regole del flusso di posta fino a quando non viene installato un filtro iFilter appropriato. Per ulteriori informazioni sui tipi di file supportati dalle regole del flusso di posta, vedere [Use Mail Flow Rules to inspect Message Attachments in Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Per ulteriori informazioni sulle regole del flusso di posta, vedere [Mail flow rules in Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Prevenzione della perdita di dati

La funzionalità di prevenzione della perdita dei dati consente di identificare, monitorare e proteggere le informazioni sensibili dell'organizzazione attraverso un'approfondita analisi dei contenuti. La prevenzione della perdita dei dati è una funzionalità avanzata che sta diventando sempre più importante per i sistemi di messaggistica aziendali, in quanto i messaggi di posta elettronica business-critical contengono informazioni sensibili che devono protette. La funzionalità DLP in Exchange Online consente di proteggere i dati sensibili senza influire sulla produttività dei lavoratori.
  
È possibile configurare i criteri DLP nell'interfaccia di gestione dell'interfaccia di amministrazione di Exchange per: 
  
- Attivare un modello dei criteri preconfigurato che consente di rilevare specifiche tipologie di informazioni sensibili, come i dati PCI-DSS, i dati della legge Gramm-Leach-Bliley o perfino i dati personali in una specifica lingua.
    
- Utilizzare l'efficacia dei criteri e delle azioni delle regole di trasporto esistenti e aggiungere nuove regole.
    
- Testare l'efficacia dei criteri di prevenzione della perdita dei dati prima di metterle in atto.
    
- Incorporare i propri modelli dei criteri di prevenzione della perdita dei dati e i propri tipi di informazioni sensibili.
    
- Rilevare le informazioni riservate negli allegati dei messaggi, nel testo del corpo o nelle linee degli oggetti e modificare il livello di probabilità a cui agiscono Exchange Online.
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- Aggiungere suggerimenti per i criteri, che possono contribuire a ridurre la perdita di dati visualizzando un avviso per Outlook 2016, Outlook 2013, Outlook sul Web e OWA per i dispositivi degli utenti e può anche migliorare l'efficacia dei criteri consentendo la creazione di report falsi positivi. 
    
- Analizzare i dati delle operazioni non consentite nei rapporti sulla prevenzione della perdita dei dati oppure aggiungere rapporti personalizzati tramite l'azione di creazione dei rapporti operazioni non consentite.
    
Per ulteriori informazioni sulla prevenzione della perdita dei dati (DLP), vedere [Prevenzione della perdita dei dati](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Inserimento nel journal

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
Per garantire una soluzione di inserimento nel journal corretta e affidabile, è necessario completare le attività seguenti:
  
- Verificare che la destinazione di inserimento nel journal non sia una cassetta postale di Exchange Online.
    
- Creare nella directory del cliente un oggetto contatto per l'indirizzo di posta elettronica di destinazione SMTP da utilizzare per l'inserimento nel journal.
    
- Creare un secondo oggetto contatto come cassetta postale del journal alternativa per catturare i rapporti del journal nel caso in cui la cassetta postale del journal principale sia indisponibile.
    
- Mantenere i livelli di gestione, ridondanza, disponibilità, prestazioni e funzionalità appropriati della destinazione SMTP per garantire sempre la corretta accettazione della posta.
    
- Fornire la necessaria interoperabilità con Exchange Server e il trasporto di Exchange inclusi i formati dei messaggi, l'integrazione delle informazioni su mittente/destinatario e l'appropriata conversione dei contenuti.
    
Per informazioni sull'inserimento nel journal, vedere [Inserimento nel journal](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

