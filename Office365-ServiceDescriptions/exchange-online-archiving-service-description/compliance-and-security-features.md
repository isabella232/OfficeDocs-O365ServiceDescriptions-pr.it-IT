---
title: Funzionalità di conformità e sicurezza in archiviazione Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132740"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Funzionalità di conformità e sicurezza in archiviazione Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Funzionalità di conformità in Archiviazione Exchange Online

Nelle sezioni seguenti vengono descritte le funzionalità di conformità di Microsoft Archiviazione Exchange Online.
  
### <a name="retention-policies"></a>Criteri di conservazione

Archiviazione Exchange Online fornisce dei criteri di conservazione che consentono alle organizzazioni di ridurre le responsabilità associate ai messaggi di posta elettronica e ad altre comunicazioni. Con questi criteri, gli amministratori possono applicare le impostazioni di conservazione a specifiche cartelle nelle cassette postali degli utenti. Gli amministratori possono anche fornire agli utenti un menu di criteri di conservazione e consentire loro di applicare i criteri a elementi, conversazioni o cartelle specifici utilizzando Outlook 2010 o versione successiva o Outlook sul Web. In Archiviazione Exchange Online gli amministratori gestiscono i criteri di conservazione dall'infrastruttura locale.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Con Outlook 2010 e versioni successive e Outlook sul Web, gli utenti possono applicare i criteri di conservazione alle cartelle, alle conversazioni o ai singoli messaggi ed è inoltre possibile visualizzare i criteri di conservazione applicati e le date di eliminazione previste nei messaggi. Anche gli utenti di altri client di posta elettronica possono utilizzare le funzionalità di eliminazione o archiviazione dei messaggi in base ai criteri di conservazione sul lato server configurati dall'amministratore, ma non possono usufruire dello stesso livello di visibilità e controllo.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Archiviazione sul posto e conservazione per controversia legale

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
  
Per ulteriori informazioni, vedere [Conservazione in locale](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
> [!NOTE]
> Per gli utenti di Archiviazione Exchange Online, la quota predefinita per la cartella degli elementi ripristinabili è pari a 100 GB. 
  
### <a name="in-place-ediscovery"></a>eDiscovery sul posto

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Funzionalità di sicurezza in Archiviazione Exchange Online

Nelle sezioni seguenti vengono descritte le funzionalità di sicurezza di Microsoft Archiviazione Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Crittografia tra server locali e Archiviazione Exchange Online

Per crittografare la connessione tra server di posta elettronica, in modo da evitare lo spoofing e offrire la necessaria riservatezza per i messaggi in transito, viene utilizzato TLS (Transport Layer Security). TLS viene utilizzato anche per la protezione del traffico del server di posta elettronica locale nei Data Center Microsoft per l'archiviazione Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Crittografia tra client e Archiviazione Exchange Online

Per una maggiore sicurezza, le connessioni tra client e Archiviazione Exchange Online utilizzano i seguenti metodi di crittografia:
  
- SSL viene utilizzato per proteggere Outlook, Outlook sul Web e il traffico dei servizi Web di Exchange, utilizzando la porta TCP 443.
    
- Le connessioni client ai server locali rimangono invariate con l'introduzione di Archiviazione Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Crittografia: S/MIME e PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
Analogamente, Archiviazione Exchange Online archivia messaggi crittografati tramite soluzioni di crittografia client di terze parti, come PGP (Pretty Good Privacy).
  
### <a name="information-rights-management"></a>Information Rights Management

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Supporto di IRM in Outlook sul Web

Gli utenti possono leggere e creare messaggi protetti con IRM in modo nativo in Outlook sul Web, proprio come in Outlook. È possibile accedere ai messaggi protetti tramite IRM in Outlook sul Web tramite Internet Explorer, Firefox, Safari e Chrome (senza che sia necessario alcun plug-in). Per i messaggi sono disponibili la ricerca di testo, la visualizzazione delle conversazioni e il riquadro di anteprima. Per abilitare questa funzionalità è necessario che sia configurata l'interoperabilità tra il server AD RMS e l'ambiente locale di Exchange.
  
#### <a name="irm-search"></a>Ricerca IRM

I messaggi protetti tramite IRM sono indicizzati e supportano l'esecuzione di ricerche nei vari componenti, inclusi intestazioni, oggetto, corpo del messaggio e allegati. Gli utenti possono cercare gli elementi protetti tramite IRM in Outlook e Outlook sul Web e gli amministratori possono cercare gli elementi protetti tramite IRM utilizzando eDiscovery sul posto o il cmdlet **Search-Mailbox** .
  
### <a name="auditing"></a>Controllo

Archiviazione Exchange Online include due tipi di funzionalità di controllo predefinite:
  
- **Registrazione di controllo dell'amministratore** Consente ai clienti di tenere traccia delle modifiche apportate dagli amministratori nell'ambiente di Archiviazione Exchange Online, incluse le modifiche ai ruoli RBAC o ai criteri e alle impostazioni di Exchange. 
    
- **Registrazione di controllo della cassetta postale** Consente ai clienti di tenere traccia degli accessi alle cassette postali eseguiti da utenti che non ne sono i legittimi proprietari. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).
  

