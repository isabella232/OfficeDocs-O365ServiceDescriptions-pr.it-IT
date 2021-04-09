---
title: Pianificazione e distribuzione
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
description: Informazioni sulla pianificazione e la distribuzione in Microsoft Exchange Online.
ms.openlocfilehash: eabef8014f64295058b4f41ccd9835a8dea473d8
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652700"
---
# <a name="planning-and-deployment"></a>Pianificazione e distribuzione

## <a name="planning-for-service-changes-and-growth"></a>Pianificazione per l'aggiornamento e la crescita dei servizi

Per le organizzazioni, è preferibile scegliere le opzioni di migrazione basate sui sistemi di posta elettronica di origine, lo stato finale desiderato (completamente o parzialmente ospitato), il numero di utenti di cui eseguire la migrazione e i tempi in cui raggiungere lo stato finale.
  
## <a name="deployment-options"></a>Opzioni di distribuzione

- **Distribuzione solo cloud:** l'organizzazione dispone di tutte le cassette postali utente ospitate in Exchange Online. 
    
- **Distribuzione ibrida di Exchange** - L'organizzazione dispone di alcune cassette postali utente ospitate in un'organizzazione exchange locale e alcune cassette postali utente ospitate in Exchange Online. 
    
### <a name="cloud-only"></a>Solo cloud

Per distribuzione "solo cloud" si intende una soluzione in cui nel servizio Exchange Online l'organizzazione non è connessa all'organizzazione Exchange locale. Tutti gli utenti e le cassette postali sono ospitate e gestite in Exchange Online e Office 365.
  
### <a name="hybrid"></a>Ibrido

Disponibile per le organizzazioni Microsoft Exchange 2003, Exchange 2007, Exchange 2010 ed Exchange 2013 locali, la distribuzione ibrida offre una configurazione di coesistenza a lungo termine con alcune cassette postali ospitate in Exchange Online o un percorso di migrazione verso l'hosting di tutte le cassette postali utente in Exchange Online. La distribuzione ibrida offre alle organizzazioni la possibilità di estendere al cloud le numerose funzionalità e il controllo amministrativo che hanno nell'organizzazione Microsoft Exchange locale. Le funzionalità di configurazione ibrida includono trasporto della posta sicuro, informazioni sulla disponibilità del calendario condiviso e verifica dei messaggi tra le organizzazioni locali ed Exchange Online.
  
Per ulteriori informazioni sulle distribuzioni ibride, vedere l'articolo relativo alle [distribuzioni ibride di Exchange Server 2013](/exchange/exchange-hybrid). Se si utilizza Office 365 gestito da 21Vianet, vedere [Configurazione delle funzionalità ibride di Exchange con Office 365 gestito da 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> Le organizzazioni Exchange 2003 locali devono installare almeno un server Accesso client/Cassette postali di Exchange 2010 per configurare la distribuzione ibrida con Exchange Online. Le organizzazioni Exchange 2007 locali devono installare almeno un server Accesso client/Cassette postali di Exchange 2010 o Exchange 2013 per configurare una distribuzione ibrida con Exchange Online. Le organizzazioni Exchange 2010 ed Exchange 2013 locali supportano in modo nativo le distribuzioni ibride con Exchange Online. Per ulteriori informazioni sulla compatibilità dei server Exchange nelle distribuzioni ibride, vedere l'articolo relativo ai [prerequisiti per la distribuzione ibrida](/exchange/hybrid-deployment-prerequisites)> Le organizzazioni Exchange locali devono configurare la propria organizzazione per la distribuzione ibrida. Per configurare la distribuzione ibrida, si consiglia agli amministratori di utilizzare l'Assistente per la distribuzione di Exchange Server e la procedura guida di configurazione ibrida. Ulteriori informazioni relative [all'assistente per la distribuzione di Exchange Server](/exchange/exchange-deployment-assistant)
  
## <a name="migration-options"></a>Opzioni di migrazione

Per le organizzazioni, è preferibile scegliere le opzioni di migrazione basate sui sistemi di posta elettronica di origine, lo stato finale desiderato (completamente o parzialmente ospitato), il numero di utenti di cui eseguire la migrazione e i tempi in cui raggiungere lo stato finale. Di seguito vengono riportate le opzioni di migrazione possibili:
  
- **Migrazione IMAP:** eseguire la migrazione dei dati delle cassette postali dai sistemi di posta elettronica basati su IMAP a Exchange Online. 
    
- Migrazione completa di **Exchange** - Eseguire la migrazione delle cassette postali da Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 e Sistemi Exchange ospitati a Exchange Online in una singola migrazione completa. 
    
- **Migrazione** a fasi di Exchange - Eseguire una migrazione a fasi per eseguire la migrazione delle cassette postali da Exchange Server 2003 o Exchange Server 2007 con strumenti di migrazione basati sul Web e modifiche minime all'infrastruttura locale. 
    
- **Migrazione di spostamento remoto** - Eseguire la migrazione delle cassette postali di Exchange locali a Exchange Online in una distribuzione ibrida di Exchange. Per utilizzare la migrazione di spostamento remoto è necessario disporre di una distribuzione ibrida di Exchange. 
    
Per ulteriori informazioni sulla migrazione della posta elettronica e delle cassette postali a Exchange Online, vedere [Eseguire la migrazione della posta elettronica a Office 365 - Guida dell'amministratore](https://support.office.com/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migrazione IMAP

Exchange Online fornisce un strumento basato sul Web per la migrazione dei dati delle cassette postali dai sistemi di posta elettronica che supportano IMAP. Gli amministratori potranno contare su un'assistenza adeguata in tutti i passaggi della migrazione, descritti qui di seguito: 
  
1. Creazione di cassette postali vuote nel cloud per gli utenti nell'organizzazione (in genere, l'operazione viene effettuata caricando un file CSV o utilizzando Windows PowerShell).
    
2. Immissione delle impostazioni di connessione del server remoto.
    
3. Il file CSV consente di specificare le cassette postali di cui eseguire la migrazione dei dati nelle casette postali di Exchange Online.
    
4. Dopo aver immesso le informazioni, Exchange Online avvia la migrazione del contenuto delle cassette postali tramite IMAP (non verrà eseguita la migrazione di elementi del calendario, contatti, attività e altri elementi non riguardanti la posta).
    
Per ulteriori informazioni sulla migrazione IMAP, vedere [Eseguire la migrazione di cassette postali IMAP a Office 365](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) e [Eseguire la migrazione di altri tipi di cassette postali IMAP a Office 365](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Per non abusare delle risorse dei server remoti e della larghezza di banda durante la migrazione, in Exchange Online vengono create meno di 10 connessioni al server IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migrazione del cutover di Exchange

Exchange Online fornisce uno strumento basato sul Web per la migrazione dei dati da ambienti Exchange Server 2003, Exchange Server 2007 o Exchange Server 2010 locali. L'amministratore potrà contare su un'assistenza adeguata in tutti i passaggi della migrazione, descritti qui di seguito:
  
1. Utilizzando l'indirizzo di posta elettronica e le credenziali di un account amministratore locale, Exchange Online stabilisce una connessione all'organizzazione di posta elettronica locale utilizzando il servizio di individuazione automatica.
    
2. Exchange Online utilizza una connessione RPC/HTTP per leggere direttamente le informazioni provenienti dal server remoto e creare cassette postali in Exchange Online.
    
3. Exchange Online sincronizza il contenuto delle cassette postali con le cassette postali cloud. Durante la migrazione dei dati verso Exchange Online, gli utenti mantengono la connessione alle cassette postali originarie.
    
4. Una volta completata la migrazione iniziale, le eventuali modifiche apportate vengono sincronizzate con il cloud ogni 24 ore, fino a quando l'amministratore non interrompe o elimina il batch di migrazione.
    
Per passare agli utenti alle proprie cassette postali cloud, gli amministratori configurano il record MX in modo che puntino a Microsoft e riconfigurino i profili degli utenti in Outlook. Quando gli utenti passano alle cassette postali cloud, le cartelle offline locali (file OST) saranno risincronizzate, con conseguente download della posta migrata nella workstation client. Gli utenti possono rispondere ai messaggi meno recenti nelle cassette postali dopo la migrazione.
  
Per ulteriori informazioni sulla migrazione completa di Exchange, vedere [Informazioni utili su una migrazione completa della posta elettronica a Office 365](https://support.office.com/article/365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> Un'organizzazione può eseguire la migrazione sul cloud di massimo 2.000 cassette postali di Exchange 2003, Exchange 2007, Exchange 2010 o Exchange 2013 utilizzando una migrazione completa. > Exchange Online deve stabilire una connessione a un server Exchange locale, quindi il server locale deve disporre di un certificato rilasciato da un'autorità di certificazione attendibile e di un indirizzo IP pubblico. 
  
### <a name="staged-exchange-migration"></a>Migrazione di Exchange in fasi

Con la migrazione in fasi, la migrazione degli utenti nel cloud può essere eseguita utilizzando lo strumento di migrazione di Exchange basato sul Web e lo strumento di sincronizzazione della directory. Anziché eseguire la migrazione di tutti gli utenti contemporaneamente, come nella migrazione "cutover" di Exchange, gli amministratori procedono in batch. A tale scopo, viene caricato un file CSV con un elenco parziale degli utenti interessati dalla migrazione. Nella migrazione in fasi, tutti gli utenti dell'organizzazione condividono lo stesso nome del dominio di posta elettronica.
  
Nella migrazione in fasi di Exchange, gli amministratori utilizzano lo Strumento di sincronizzazione della directory dei Microsoft Online Services. In questo modo, agli utenti viene fornito un Elenco indirizzi globale (GAL, Global Address List) unificato in cui l'ambiente online viene costantemente sincronizzato con l'ambiente locale.
  
Per ulteriori informazioni sulle migrazioni di Exchange a fasi, vedere [Informazioni utili su una migrazione a fasi della posta elettronica a Office 365](https://support.office.com/en-ie/article/365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Le organizzazioni non possono utilizzare una migrazione di Exchange in fasi per spostare cassette postali di Exchange 2010 ed Exchange 2013. Se nell'organizzazione sono presenti meno di 2.000 cassette postali di Exchange 2010 o Exchange 2013, è possibile utilizzare una migrazione completa di Exchange. Se, invece, il loro numero è superiore a 2.000 è possibile implementare una distribuzione ibrida. > Durante la migrazione, gli amministratori devono utilizzare lo strumento di sincronizzazione della directory dei Microsoft Online Services per fornire agli utenti un elenco indirizzi globale unificato in cui l'ambiente online viene costantemente sincronizzato con l'ambiente locale. 
  
## <a name="migration-tools"></a>Strumenti di migrazione

Microsoft offre una varietà di strumenti per consentire la migrazione di un ambiente di posta elettronica esistente in Exchange Online. La scelta degli strumenti più appropriati dipende dall'ambiente corrente dell'organizzazione e dalle finalità della distribuzione:
  
- **Dashboard di migrazione** : gli amministratori possono utilizzare il dashboard di migrazione nell'interfaccia di amministrazione di Exchange per gestire la migrazione delle cassette postali a Exchange Online in una migrazione completa o a fasi di Exchange. Possono anche utilizzare il dashboard per la migrazione del contenuto delle cassette postali degli utenti da un server IMAP locale alle cassette postali di Exchange Online esistenti. Il dashboard offre agli amministratori le seguenti funzionalità: 
    
  - **Creare e avviare più batch di migrazione:** gli amministratori possono creare e accodare fino a 100 batch di migrazione. Viene eseguito un solo batch di migrazione alla volta, tuttavia gli amministratori possono mettere in coda più batch e, quando un batch di migrazione è terminato, viene elaborato il batch successivo in coda. 
    
  - **Riavviare** un batch di migrazione con errori: dopo la sincronizzazione iniziale di un batch di migrazione, in cui gli elementi vengono copiati dalle cassette postali locali alle cassette postali cloud per ogni utente nel batch di migrazione, è possibile che alcune cassette postali non riescano a eseguire la sincronizzazione. Gli amministratori possono riavviare il batch di migrazione per tentare di sincronizzare le cassette postali interessate. 
    
  - **Ottenere** informazioni dettagliate sugli elementi ignorati- Per le migrazioni IMAP, le migrazioni completate e le migrazioni a fasi, il dashboard di migrazione visualizza informazioni sugli elementi specifici ignorati, incluso il motivo e la posizione dell'elemento nella cassetta postale dell'utente. 
    
  - **Aprire i report di migrazione:** gli amministratori possono aprire le statistiche di migrazione o il report degli errori di migrazione per un batch di migrazione direttamente dal dashboard. 
    
  - **Modificare un batch di** migrazione: se un batch di migrazione per una migrazione a fasi di Exchange o una migrazione IMAP si trova nella coda di migrazione ma non è attualmente in esecuzione, gli amministratori possono modificare il batch di migrazione. 
    
- **Strumento di sincronizzazione** di Azure Active Directory - Lo strumento di sincronizzazione di Azure Active Directory svolge un ruolo importante nella migrazione a scenari di posta elettronica ibridi che utilizzano Sia Exchange Online che un Exchange Server locale. Lo strumento esegue una sincronizzazione unidirezionale da Active Directory locale a Exchange Online. Dopo aver completato la migrazione, gli amministratori non rimane che utilizzare Exchange Online per gestire gli utenti e i gruppi di Active Directory. Inoltre, lo strumento offre agli utenti un Elenco indirizzi globale unificato in cui l'ambiente online viene costantemente sincronizzato con l'ambiente locale. 
    
    Per ulteriori informazioni su strumento di sincronizzazione di Azure Active Directory, vedere [Sincronizzazione della directory: roadmap](/azure/active-directory/hybrid/whatis-hybrid-identity).
    
- **Procedura guidata di** configurazione ibrida : la procedura guidata di configurazione ibrida semplifica il processo di distribuzione ibrida semplificando la configurazione locale ed Exchange Online di funzionalità e servizi. Presentata come parte integrante di Exchange Server 2010 Service Pack 2, la procedura guidata di configurazione viene eseguita solo in organizzazioni locali e dispone dei seguenti componenti: 
    
  - Procedura guidata nell'interfaccia di amministrazione di Exchange che assiste gli amministratori nel processo end-to-end per la configurazione di una distribuzione ibrida.
    
  - Un set di comandi di Exchange Management Shell (EMS) che orchestrano il processo di configurazione.
    
    Per ulteriori informazioni sulla procedura guidata di configurazione ibrida, vedere l'articolo relativo alla [procedura guidata di configurazione ibrida](/exchange/hybrid-configuration-wizard).
    
- **Remote Windows PowerShell** - Nell'ambito dell'aggiornamento del servizio Exchange Online di dicembre 2011, è possibile Windows PowerShell per risolvere gli errori di migrazione. Ad esempio, gli amministratori possono visualizzare informazioni diagnostiche per i batch di migrazione, oltre a statistiche sulla migrazione e informazioni diagnostiche per gli utenti in base agli indirizzi SMTP primari. 
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Descrizione del servizio [Exchange Online.](exchange-online-service-description.md)
