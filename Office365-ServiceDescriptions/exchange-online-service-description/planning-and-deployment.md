---
title: Pianificazione e distribuzione
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132660"
---
# <a name="planning-and-deployment"></a>Pianificazione e distribuzione

## <a name="planning-for-service-changes-and-growth"></a>Pianificazione per l'aggiornamento e la crescita dei servizi

Per le organizzazioni, è preferibile scegliere le opzioni di migrazione basate sui sistemi di posta elettronica di origine, lo stato finale desiderato (completamente o parzialmente ospitato), il numero di utenti di cui eseguire la migrazione e i tempi in cui raggiungere lo stato finale.
  
## <a name="deployment-options"></a>Opzioni di distribuzione

- **Solo distribuzione cloud** Nell'organizzazione tutte le cassette postali degli utenti sono ospitate in Exchange Online. 
    
- **Distribuzione ibrida di Exchange** Nell'organizzazione alcune cassette postali utente sono ospitate in un'organizzazione Exchange locale e altre in Exchange Online. 
    
### <a name="cloud-only"></a>Solo cloud

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>Configurazione ibrida

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>Opzioni di migrazione

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **Migrazione IMAP** Migrazione dei dati delle cassette postali da sistemi di posta elettronica basati su IMAP a Exchange Online. 
    
- **Migrazione "cutover" di Exchange** Migrazione delle cassette postali dai sistemi Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 e Hosted Exchange a Exchange Online in un'unica migrazione "cutover". 
    
- **Migrazione di Exchange in fasi** Migrazione in fasi delle cassette postali da Exchange Server 2003 o Exchange Server 2007 con strumenti di migrazione basati sul Web e modifiche minimali dell'infrastruttura locale. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Per ulteriori informazioni sulla migrazione della posta elettronica e delle cassette postali a Exchange Online, vedere [Eseguire la migrazione della posta elettronica a Office 365 - Guida dell'amministratore](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migrazione IMAP

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. Creazione di cassette postali vuote nel cloud per gli utenti nell'organizzazione (in genere, l'operazione viene effettuata caricando un file CSV o utilizzando Windows PowerShell).
    
2. Immissione delle impostazioni di connessione del server remoto.
    
3. Il file CSV consente di specificare le cassette postali di cui eseguire la migrazione dei dati nelle casette postali di Exchange Online.
    
4. Dopo aver immesso le informazioni, Exchange Online avvia la migrazione del contenuto delle cassette postali tramite IMAP (non verrà eseguita la migrazione di elementi del calendario, contatti, attività e altri elementi non riguardanti la posta).
    
Per ulteriori informazioni sulla migrazione IMAP, vedere [Eseguire la migrazione di cassette postali IMAP a Office 365](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) e [Eseguire la migrazione di altri tipi di cassette postali IMAP a Office 365](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Per non abusare delle risorse dei server remoti e della larghezza di banda durante la migrazione, in Exchange Online vengono create meno di 10 connessioni al server IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migrazione del cutover di Exchange

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Utilizzando l'indirizzo di posta elettronica e le credenziali di un account amministratore locale, Exchange Online stabilisce una connessione all'organizzazione di posta elettronica locale utilizzando il servizio di individuazione automatica.
    
2. Exchange Online utilizza una connessione RPC/HTTP per leggere direttamente le informazioni provenienti dal server remoto e creare cassette postali in Exchange Online.
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. Una volta completata la migrazione iniziale, le eventuali modifiche apportate vengono sincronizzate con il cloud ogni 24 ore, fino a quando l'amministratore non interrompe o elimina il batch di migrazione.
    
Per passare gli utenti alle cassette postali cloud, gli amministratori configurano il record MX in modo che punti a Microsoft e configurino i profili degli utenti in Outlook. Quando gli utenti passano alle cassette postali cloud, le cartelle offline locali (file OST) saranno risincronizzate, con conseguente download della posta migrata nella workstation client. Gli utenti possono rispondere ai messaggi meno recenti nelle cassette postali dopo la migrazione.
  
Per ulteriori informazioni sulla migrazione completa di Exchange, vedere [Informazioni utili su una migrazione completa della posta elettronica a Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Migrazione di Exchange in fasi

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Per ulteriori informazioni sulle migrazioni di Exchange a fasi, vedere [Informazioni utili su una migrazione a fasi della posta elettronica a Office 365](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>Strumenti di migrazione

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **Informazioni dettagliate sugli elementi ignorati** Per le migrazioni IMAP, complete e in fasi, nel dashboard di migrazione vengono visualizzate le informazioni sugli elementi che sono stati ignorati, incluso il motivo e la posizione dell'elemento nella cassetta postale dell'utente. 
    
  - **Apertura di report di migrazione** Gli amministratori possono aprire statistiche di migrazione o il report sugli errori verificatisi in un batch di migrazione direttamente nel dashboard. 
    
  - **Modifica di un batch di migrazione** Se un batch di migrazione per una migrazione di Exchange in fasi o IMAP si trova nella coda di migrazione ma non in esecuzione al momento, gli amministratori possono modificare il batch. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Per ulteriori informazioni su strumento di sincronizzazione di Azure Active Directory, vedere [Sincronizzazione della directory: roadmap](https://go.microsoft.com/fwlink/p/?LinkId=287034).
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Procedura guidata nell'interfaccia di amministrazione di Exchange che assiste gli amministratori nel processo end-to-end per la configurazione di una distribuzione ibrida.
    
  - Un set di comandi di Exchange Management Shell (EMS) che orchestrano il processo di configurazione.
    
    Per ulteriori informazioni sulla procedura guidata di configurazione ibrida, vedere l'articolo relativo alla [procedura guidata di configurazione ibrida](https://go.microsoft.com/fwlink/p/?LinkId=271734).
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

