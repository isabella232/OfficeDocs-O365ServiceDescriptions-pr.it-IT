---
title: Destinatari
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: In questo argomento sono descritte le funzionalità correlate ai destinatari incluse con Microsoft Exchange Online. Questo include le funzionalità di posta elettronica, contatti, gruppi di distribuzione, calendario e pianificazione.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132640"
---
# <a name="recipients"></a>Destinatari

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>Posta elettronica

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Gli indirizzi generali non sono più supportati in Exchange Online. A causa del filtro dei destinatari sul posto per proteggersi da potenziali messaggi di posta indesiderata, gli indirizzi di posta elettronica che non esistono nell'organizzazione verranno rifiutati. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Tipi di cassetta postale, limiti di archiviazione e avvisi di capacità

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
Per ulteriori informazioni, vedere la sezione "limiti di archiviazione delle cassette postali" e "avvisi di capacità" nell'argomento [Exchange Online limits](exchange-online-limits.md).
  
### <a name="mailtips"></a>Suggerimenti messaggio

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Accesso delegato

Exchange Online supporta l'accesso delegato, ovvero la possibilità per gli utenti di delegare ad altri la gestione della propria posta elettronica e dei calendari. L'accesso delegato è in genere utilizzato tra manager e assistente, quando l'assistente si occupa dei messaggi di posta elettronica in arrivo del manager e ne coordina l'agenda. L'accesso delegato può essere abilitato dagli utenti di Exchange online in Outlook o Outlook sul Web o dagli amministratori nell'interfaccia di amministrazione di Exchange. 
  
Per i delegati sono disponibili due tipi di accesso:
  
- **Autorizzazioni Invia per conto di** Il delegato può comporre messaggi di posta elettronica e immettere il nome dell'altra persona nel campo Da, in cui sarà visualizzato come "[nome delegato] per conto di [nome della persona]". 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
Per ulteriori informazioni su come concedere la delega di accesso, vedere [Gestire le autorizzazioni per i destinatari](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Regole di Posta in arrivo

Exchange Online consente agli utenti di creare regole di posta in arrivo che eseguono automaticamente azioni specifiche basate su criteri sui messaggi in arrivo. Ad esempio, è possibile creare una regola per spostare automaticamente tutta la posta in una cartella specifica se la posta è stata inviata a un determinato gruppo di distribuzione. Gli utenti gestiscono le regole di posta in arrivo da Outlook o Outlook sul Web. Gli amministratori possono bloccare determinati tipi di regole di posta in arrivo disabilitando l'inoltro e/o le risposte automatiche sul lato server. Ad esempio, disabilitando l'inoltro della posta elettronica sul lato server si impedisce agli utenti l'inoltro automatico dei messaggi di posta elettronica agli account personali. In modo analogo, disabilitando le risposte automatiche sul lato server si impedisce agli utenti esterni di utilizzare tali risposte allo scopo di identificare indirizzi di posta elettronica validi. Tali modifiche vengono effettuate tramite Windows PowerShell remoto.
  
### <a name="clutter"></a>Messaggi secondari

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Account connessi

La funzionalità account connessi consente agli utenti di Exchange Online di connettere gli account di posta elettronica esterni (ad esempio gli account personali) ai propri account di posta elettronica interni in Exchange Online e quindi di utilizzare Outlook sul Web per interagire con tutti i messaggi in un'unica posizione. Gli account connessi vengono sincronizzati automaticamente al momento dell'accesso a Outlook sul Web. Gli utenti possono anche sincronizzare manualmente gli account da Outlook sul Web. Gli amministratori possono abilitare e disabilitare questa funzionalità per determinati utenti o per tutti gli utenti nell'[Interfaccia di amministrazione di Exchange](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Cassette postali inattive

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
L'abilitazione di una cassetta postale inattiva prevede che alla cassetta venga assegnata una licenza di Exchange Online (Piano 2) o una sottoscrizione per l'archiviazione in Exchange Online in modo che sia possibile applicare alla cassetta postale l'attributo per la conservazione o un blocco per controversie prima che venga eliminata.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
Per ulteriori informazioni, vedere:
  
- [Gestire le cassette postali inattive in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [Conservazione in locale e per controversia legale](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- l'articolo relativo a [eDiscovery sul posto](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Contatti e gruppi di distribuzione

### <a name="offline-address-book"></a>Rubrica offline

La caratteristica Rubrica fuori rete fornisce un'istantanea delle informazioni di Active Directory disponibili nell'elenco indirizzi globale (GAL) di Outlook. Lo snapshot è memorizzato nella cache locale in Outlook per essere disponibile quando l'utente lavora fuori rete.
  
### <a name="address-book-policies"></a>Criteri delle rubriche

Exchange Online supporta i criteri della Rubrica. I criteri della rubrica consentono di suddividere gli utenti in gruppi specifici per fornire viste personalizzate dell'Elenco indirizzi globale dell'organizzazione. Quando si crea un criterio delle rubriche, si assegna un Elenco indirizzi globale, una Rubrica offline, un elenco di sale e uno o più elenchi indirizzi al criterio. È quindi possibile assegnare il criterio rubrica agli utenti delle cassette postali, fornendo loro l'accesso a un elenco indirizzi globale personalizzato in Outlook e Outlook sul Web. Gli amministratori possono configurare questi criteri utilizzando Windows PowerShell Remote. Per ulteriori informazioni sui criteri della rubrica, vedere [Rubriche in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203).
  
### <a name="address-lists"></a>Elenchi di indirizzi

Exchange Online supporta la personalizzazione di elenchi indirizzi e GAL. Un elenco indirizzi globale è una directory a livello di organizzazione di tutti gli utenti abilitati alla posta elettronica, i gruppi di distribuzione e i contatti esterni. Gli amministratori possono nascondere utenti, gruppi di distribuzione e contatti dall'elenco indirizzi globale utilizzando lo strumento di sincronizzazione della directory o Windows PowerShell remoto.
  
### <a name="hierarchical-address-books"></a>Rubriche gerarchiche

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>Gruppi di distribuzione (globali)

Un gruppo di distribuzione (o elenco di distribuzione) è una raccolta di utenti, contatti e altri gruppi di distribuzione disponibili in una società. Per inviare messaggi a tutti i componenti di un gruppo di distribuzione, gli utenti indirizzano la posta elettronica all'alias del gruppo. I gruppi di distribuzione sono simili ai gruppi di distribuzione personali creati dai singoli utenti in Outlook, con la differenza che gli elenchi dei membri sono disponibili per la società a livello globale. I gruppi di distribuzione vengono creati dagli amministratori nell'interfaccia di amministrazione di Exchange. I gruppi possono inoltre essere sincronizzati con Exchange Online da Active Directory locale. Vengono visualizzati nell'elenco indirizzi globale in Outlook. Exchange Online supporta le funzionalità dei gruppi di distribuzione avanzate, tra cui quelle descritte qui di seguito:
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>Contatti esterni (globali)

Per contatto esterno si intende un record con informazioni su una persona che lavora esternamente all'organizzazione specificata. I contatti esterni sono simili ai contatti personali creati dai singoli utenti in Outlook, con la differenza che i contatti esterni sono disponibili per la società a livello globale. I contatti esterni vengono creati dagli amministratori nell'interfaccia di amministrazione di Exchange o in Windows PowerShell Remote. I contatti possono inoltre essere sincronizzati con Exchange Online da Active Directory locale. Vengono visualizzati nell'elenco indirizzi globale in Outlook.
  
Per ulteriori informazioni sui contatti esterni, vedere [Creazione di una relazione dell'organizzazione in Exchange Online.](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Calendario e pianificazione

### <a name="resource-mailboxes"></a>Cassette postali per la risorsa

Le cassette postali per le risorse (ad esempio per sale runioni e attrezzature) rappresentano le sale riunioni oppure altre strutture o risorse di una società. Gli utenti possono prenotare sale o risorse aggiungendo l'alias di posta elettronica della risorsa alle convocazioni di riunione in Outlook o Outlook sul Web. Le sale riunioni e le risorse vengono visualizzate nell'elenco indirizzi globale in Outlook e Outlook sul Web.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
Per ulteriori informazioni sulle cassette postali per le risorse, vedere:
  
- [Creazione e gestione delle cassette sala](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Gestire le cassette postali dell’attrezzatura](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Gestione delle sale riunioni

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
Gli amministratori possono personalizzare le risposte alle sale riunioni automatizzate e configurare i criteri di prenotazione in Outlook sul Web. Nei criteri sono inclusi l'autore della programmazione, l'ora e il giorno della programmazione, le informazioni sulla riunione visibili nel calendario della risorsa e la percentuale di conflitti di programmazione consentiti. Gli amministratori possono disabilitare Operatore Prenotazione risorse e assegnare a utenti specifici la gestione manuale delle convocazioni di riunioni.
  
Gli amministratori devono definire e gestire le impostazioni RBA mediante Windows PowerShell remoto.
  
### <a name="out-of-office-replies"></a>Risposte Fuori sede

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>Condivisione del calendario

Gli utenti possono condividere il calendario personale in uno dei due modi seguenti:
  
- **Condivisione calendario federata** La federazione fa riferimento all'infrastruttura di trust sottostante che supporta la condivisione federata, un metodo semplice per gli utenti di Exchange per condividere le informazioni relative al calendario e ai contatti con i destinatari in altre organizzazioni esterne federate. Sono incluse le organizzazioni di Exchange Online oppure organizzazioni di Exchange Server 2010 o Exchange Server 2013 locali. Gli amministratori di Exchange Online non devono configurare una relazione di trust con Microsoft Federation Gateway perché questa relazione di trust è preconfigurata per tutti i clienti di Exchange Online quando viene creato il servizio Microsoft. Un criterio di condivisione predefinito consente agli utenti di inviare inviti alla condivisione del calendario da Outlook sul Web o Outlook 2010. In Windows PowerShell remoto, gli amministratori possono disabilitare il criterio o configurare il livello dei dati del calendario relativi alla disponibilità che gli utenti possono condividere. Possono inoltre creare una relazione tra organizzazioni con un'altra organizzazione federata, che consente la visibilità tra le organizzazioni del livello desiderato di informazioni sulla disponibilità per ogni utente senza alcun invito alla condivisione da parte dei singoli utenti. Nell'ambito dei criteri di condivisione definiti dagli amministratori e/o delle relazioni tra organizzazioni, gli utenti possono definire individualmente i dettagli delle future condivisioni. 
    
- **Condivisione calendario su Internet** In Exchange Online gli utenti possono pubblicare i propri calendari utilizzando il formato iCal per l'accesso anonimo di tutti gli utenti, internamente o esternamente all'organizzazione. I destinatari possono utilizzare Exchange, una piattaforma diversa o semplicemente un browser Web. Gli utenti di Exchange Online possono anche abbonarsi ai calendari pubblicati da altre persone in posizioni Internet tramite iCal. La condivisione dei calendari personali è diversa dalla condivisione dei calendari federata, che viene configurata da un amministratore e offre condivisione della disponibilità tra organizazioni. Nessun utente può pubblicare dati del calendario in formato iCal finché l'amministratore non ha impostato e applicato un criterio di condivisione che lo consenta. Gli amministratori possono disabilitare la pubblicazione e le sottoscrizioni iCal per gli utenti di un'organizzazione utilizzando Windows PowerShell remoto.
    
Per ulteriori informazioni sulla condivisione federata, vedere [Condivisione in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Ricerca sala di Outlook 2010

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- Per creare un nuovo elenco di sale, utilizzare Windows PowerShell remoto. 
    
- I gruppi di distribuzione che contengono esclusivamente sale possono essere convertiti in elenchi di sale utilizzando Windows PowerShell remoto.
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  