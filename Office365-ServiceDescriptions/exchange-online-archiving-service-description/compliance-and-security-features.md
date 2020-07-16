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
  
Archiviazione Exchange Online offre due tipi di criteri: archiviazione ed eliminazione. Entrambi i tipi possono essere applicati allo stesso elemento o alla stessa cartella. Un utente, ad esempio, può contrassegnare un messaggio di posta elettronica per impostarne lo spostamento automatico nell'archivio personale entro un numero di giorni specificato e l'eliminazione automatica dopo un altro intervallo di giorni.
  
Con Outlook 2010 e versioni successive e Outlook sul Web, gli utenti possono applicare i criteri di conservazione alle cartelle, alle conversazioni o ai singoli messaggi ed è inoltre possibile visualizzare i criteri di conservazione applicati e le date di eliminazione previste nei messaggi. Anche gli utenti di altri client di posta elettronica possono utilizzare le funzionalità di eliminazione o archiviazione dei messaggi in base ai criteri di conservazione sul lato server configurati dall'amministratore, ma non possono usufruire dello stesso livello di visibilità e controllo.
  
I criteri di conservazione disponibili in Archiviazione Exchange Online sono identici a quelli di Exchange Server 2010 Service Pack 2 (SP2) e versioni successive. Gli amministratori possono gestire i criteri di conservazione da ambienti locali Exchange Server 2010 e versioni successive. Le cartelle gestite, ossia il precedente approccio alla gestione dei record di messaggistica introdotto in Exchange 2007, non sono disponibili né compatibili con Archiviazione Exchange Online. Per ulteriori dettagli, vedere [Tag di conservazione e criteri di conservazione](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Archiviazione sul posto e conservazione per controversia legale

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
  
> [!NOTE]
> Per gli utenti di Archiviazione Exchange Online, la quota predefinita per la cartella degli elementi ripristinabili è pari a 100 GB. 
  
### <a name="in-place-ediscovery"></a>eDiscovery sul posto

Archiviazione Exchange Online supporta eDiscovery in locale per la ricerca nei contenuti delle cassette postali di un'organizzazione. Utilizzando l'interfaccia di amministrazione di Exchange o una sessione remota di Windows PowerShell da un server Exchange 2013 locale, gli amministratori o i responsabili dell'individuazione autorizzati possono eseguire ricerche in una vasta gamma di elementi delle cassette postali, inclusi messaggi di posta elettronica, allegati, appuntamenti del calendario, attività e contatti. eDiscovery in locale può eseguire simultaneamente ricerche nelle cassette postali principali e negli archivi. Tra i filtri disponibili sono inclusi quelli per mittente, destinatario, tipo di messaggio, data di invio o ricezione, Cc e Bcc, oltre a quelli per la sintassi KQL (Keyword Query Language). Per ulteriori dettagli, vedere [eDiscovery in locale](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
Con l'interfaccia di amministrazione di Exchange e Windows PowerShell remoto è possibile utilizzare fino a 5.000 cassette postali alla volta in una ricerca eDiscovery in locale. per dettagli sull'utilizzo di Windows PowerShell remoto per eseguire le ricerche eDiscovery in locale, vedere [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In Windows PowerShell remoto, è possibile utilizzare il cmdlet  `Search-Mailbox` per cercare più di 5.000 cassette postali. Per informazioni dettagliate sulla ricerca in un numero elevato di cassette postali mediante una sessione remota di Windows PowerShell, vedere [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
I risultati di una ricerca mediante eDiscovery in locale possono essere visualizzati in anteprima nell'interfaccia di amministrazione di Exchange, esportati in un file con estensione pst oppure copiati in una particolare cassetta postale denominata cassetta postale di individuazione. Gli amministratori o i responsabili della conformità possono connettersi a tale cassetta postale per esaminare i messaggi. Per informazioni dettagliate, vedere [Creazione di una ricerca eDiscovery sul posto](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> Quando si copiano i risultati relativi a una ricerca di eDiscovery in locale eseguita in cassette postali o archivi locali e basati sul cloud, è necessario selezionare una cassetta postale di individuazione locale. I messaggi provenienti dalla cassetta postale principale locale e dall'archivio basato sul cloud vengono copiati nella cassetta postale di individuazione locale. 
  
Gli amministratori possono anche cercare ed eliminare i messaggi di posta elettronica inappropriati inviati a più cassette postali dell'organizzazione. Ad esempio, se per errore è stato inviato a tutti i dipendenti un messaggio contenente informazioni riservate sugli stipendi, un amministratore può eliminare questo messaggio dalle cassette postali degli utenti. Questo tipo di ricerca non è disponibile nell'interfaccia di amministrazione di Exchange. Deve essere eseguito mediante una sessione remota di PowerShell. Per informazioni dettagliate su come eliminare i messaggi dalle cassette postali degli utenti, vedere [Ricerca ed eliminazione dei messaggi](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Funzionalità di sicurezza in Archiviazione Exchange Online

Nelle sezioni seguenti vengono descritte le funzionalità di sicurezza di Microsoft Archiviazione Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Crittografia tra server locali e Archiviazione Exchange Online

Per crittografare la connessione tra server di posta elettronica, in modo da evitare lo spoofing e offrire la necessaria riservatezza per i messaggi in transito, viene utilizzato TLS (Transport Layer Security). TLS viene utilizzato anche per la protezione del traffico del server di posta elettronica locale nei Data Center Microsoft per l'archiviazione Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Crittografia tra client e Archiviazione Exchange Online

Per una maggiore sicurezza, le connessioni tra client e Archiviazione Exchange Online utilizzano i seguenti metodi di crittografia:
  
- SSL viene utilizzato per proteggere Outlook, Outlook sul Web e il traffico dei servizi Web di Exchange, utilizzando la porta TCP 443.
    
- Le connessioni client ai server locali rimangono invariate con l'introduzione di Archiviazione Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Crittografia: S/MIME e PGP

Archiviazione Exchange Online esegue l'archiviazione di messaggi S/MIME (Secure Multipurpose Internet Mail Extensions). Tuttavia, Archiviazione Exchange Online non ospita funzioni S/MIME o chiavi pubbliche, né offre servizi di archivio chiavi, gestione chiavi o directory chiavi perché tutti questi servizi sono associati all'infrastruttura di Exchange locale.
  
Analogamente, Archiviazione Exchange Online archivia messaggi crittografati tramite soluzioni di crittografia client di terze parti, come PGP (Pretty Good Privacy).
  
### <a name="information-rights-management"></a>Information Rights Management

Archiviazione Exchange Online non offre servizi IRM (Information Rights Management) ospitati, ma gli amministratori possono utilizzare i servizi locali AD RMS (Active Directory Rights Management Services). Se viene distribuito un server AD RMS, Outlook può comunicare direttamente con tale server, consentendo agli utenti di scrivere e leggere messaggi protetti tramite IRM. Se è configurata l'interoperabilità tra il server AD RMS e l'ambiente locale di Exchange, gli utenti potranno scrivere e leggere messaggi protetti tramite IRM.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Supporto di IRM in Outlook sul Web

Gli utenti possono leggere e creare messaggi protetti con IRM in modo nativo in Outlook sul Web, proprio come in Outlook. È possibile accedere ai messaggi protetti tramite IRM in Outlook sul Web tramite Internet Explorer, Firefox, Safari e Chrome (senza che sia necessario alcun plug-in). Per i messaggi sono disponibili la ricerca di testo, la visualizzazione delle conversazioni e il riquadro di anteprima. Per abilitare questa funzionalità è necessario che sia configurata l'interoperabilità tra il server AD RMS e l'ambiente locale di Exchange.
  
#### <a name="irm-search"></a>Ricerca IRM

I messaggi protetti tramite IRM sono indicizzati e supportano l'esecuzione di ricerche nei vari componenti, inclusi intestazioni, oggetto, corpo del messaggio e allegati. Gli utenti possono cercare gli elementi protetti tramite IRM in Outlook e Outlook sul Web e gli amministratori possono cercare gli elementi protetti tramite IRM utilizzando eDiscovery sul posto o il cmdlet **Search-Mailbox** .
  
### <a name="auditing"></a>Controllo

Archiviazione Exchange Online include due tipi di funzionalità di controllo predefinite:
  
- **Registrazione di controllo dell'amministratore** Consente ai clienti di tenere traccia delle modifiche apportate dagli amministratori nell'ambiente di Archiviazione Exchange Online, incluse le modifiche ai ruoli RBAC o ai criteri e alle impostazioni di Exchange. 
    
- **Registrazione di controllo della cassetta postale** Consente ai clienti di tenere traccia degli accessi alle cassette postali eseguiti da utenti che non ne sono i legittimi proprietari. 
    
Nell'interfaccia di amministrazione di Exchange sono disponibili vari rapporti di controllo predefiniti, ad esempio sulle modifiche dei ruoli apportate dall'amministratore, sulla conservazione per controversia legale e sull'accesso alle cassette postali da parte di utenti non proprietari. Gli amministratori possono filtrare i rapporti per data e ruolo, nonché esportare tutti gli eventi di controllo per le cassette postali specificate in formato XML per l'archiviazione a lungo termine o la creazione di rapporti personalizzati.
  
Per impostazione predefinita, la registrazione di controllo dell'amministratore è attivata, mentre la registrazione di controllo della cassetta postale è disattivata. Gli amministratori possono utilizzare una sessione remota di Windows PowerShell per abilitare la registrazione di controllo per alcune o per tutte le cassette postali nell'organizzazione. Per ulteriori informazioni, vedere [Rapporti di controllo](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).
  

