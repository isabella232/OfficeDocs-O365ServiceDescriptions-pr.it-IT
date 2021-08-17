---
title: Limiti Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Priority
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Trovare i limiti di Exchange Online per diverse aree di servizio, compresi, a titolo esemplificativo, quelli relativi a rubrica, archiviazione delle cassette postali, creazione di rapporti e traccia dei messaggi.
ms.openlocfilehash: c8d2fd228befb43e00b093951508e0084b12ce99
ms.sourcegitcommit: 4ef127c684c8a6ad630a2b9bce2fe3fb25aa3e25
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 08/16/2021
ms.locfileid: "58363593"
---
# <a name="exchange-online-limits"></a>Limiti Exchange Online

Trovare i limiti di Exchange Online per diverse aree di servizio, compresi, a titolo esemplificativo, quelli relativi a rubrica, archiviazione delle cassette postali, creazione di rapporti e traccia dei messaggi.

> [!NOTE]
> Se si necessita assistenza con questa operazione o per risolvere un problema, potrebbe essere necessario trovare utili i seguenti articoli:
> - [Posta elettronica](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (per assistenza con la creazione e l’invio di posta elettronica)
>- [Posta elettronica in Microsoft 365 per le aziende - Guida per gli amministratori](/microsoft-365/admin/email/)
>- [Risolvere i problemi relativi a Outlook e Microsoft 365 con l'Assistente supporto e ripristino di Microsoft](https://diagnostics.office.com/)
>- [Rapporti di mancato recapito della posta elettronica](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
>- [Guida di Exchange Online](/exchange/exchange-online)

I limiti in Microsoft Exchange Online rientrano in una delle seguenti categorie:

- [Limiti della rubrica](#address-book-limits)

- [Limiti di archiviazione delle cassette postali](#mailbox-storage-limits)

- [Avvisi di capacità](#capacity-alerts)

- [Limiti cartella delle cassette postali](#mailbox-folder-limits)

- [Limiti dei messaggi](#message-limits)

- [Limiti di invio e ricezione](#receiving-and-sending-limits)

- [Limiti relativi alla creazione di rapporti e traccia dei messaggi](#reporting-and-message-trace-limits)

- [Limiti di conservazione](#retention-limits)

- [Limiti dei gruppi di distribuzione](#distribution-group-limits)

- [Limiti delle regole del diario, trasporto e posta in arrivo](#journal-transport-and-inbox-rule-limits)

- [Limiti di moderazione](#moderation-limits)

- [Limiti di Exchange ActiveSync ](#exchange-activesync-limits)

> [!IMPORTANT]
> - I limiti applicati a un'organizzazione di Microsoft 365 potrebbero variare in base al tempo di registrazione dell'organizzazione nel servizio.
> - Quando un limite viene modificato nei datacenter Microsoft, la modifica può richiedere un certo tempo per essere applicata a tutti i clienti esistenti.
> - La maggioranza di questi limiti non è modificabile, tuttavia è opportuno conoscerli.
> - Questi limiti si applicano ai destinatari sia interni sia esterni.
> - Per impostazione predefinita, Exchange Online Protection (EOP) protegge le cassette postali di Exchange Online. Per i limiti che si applicano alle funzionalità di EOP in Exchange Online, vedere [Limiti di Exchange Online Protection](../exchange-online-protection-service-description/exchange-online-protection-limits.md).
> - Per informazioni sui limiti dei gruppi di Office 365, vedere "Come si gestiscono i propri gruppi?" in [Informazioni sui gruppi di Microsoft 365](https://go.microsoft.com/fwlink/?linkid=846714).

## <a name="address-book-limits"></a>Limiti della rubrica

- **Limite elenchi indirizzi**: il numero massimo di elenchi indirizzi che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013. Questo numero include gli elenchi indirizzi predefiniti in Exchange Online, quali Tutti i contatti e Tutti i gruppi.

    > [!NOTE]
    > È possibile assegnare un massimo di 20 elenchi indirizzi a una singola rubrica offline (OAB).

- **Limite rubrica offline** Il numero massimo di rubriche offline che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013.

- **Limite criteri delle rubriche** Il numero massimo di criteri delle rubriche che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013.

- **Elenchi indirizzi globali** Il numero massimo di elenchi indirizzi globali che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013.

### <a name="address-book-limits"></a>Limiti della rubrica

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite elenco indirizzi|1000|1000|1000|1000|1000|1000|
|Limite rubrica offline (OAB, offline address book)|250|250|250|250|250|250|
|Limite criteri delle rubriche (ABP, address book policies)|250|250|250|250|250|250|
|Limite elenchi indirizzi globali|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Limiti della rubrica nei piani autonomi

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite elenco indirizzi|1000|1000|1000|1000|
|Limite rubrica offline (OAB, offline address book)|250|250|250|250|
|Limite criteri delle rubriche (ABP, address book policies)|250|250|250|250|
|Limite elenchi indirizzi globali|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Limiti di archiviazione delle cassette postali

Il volume di archiviazione delle cassette postali è determinato dal tipo di cassetta postale e dalla licenza di sottoscrizione dell'utente. Gli amministratori possono ridurre le dimensioni massime della cassetta postale per singolo utente o a livello globale.

> [!NOTE]
> L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a una cassetta postale di Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti o in altri casi di utilizzo improprio.

### <a name="storage-limits"></a>Limiti di archiviazione

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Cassette postali utente|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Cassette postali di archiviazione<sup>7,8</sup>|50 GB|50 GB|50 GB|Unlimited<sup>1</sup>|Unlimited<sup>1</sup>|Non disponibile<sup>4</sup>|
|Cassette postali condivise<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50/100 GB<sup>2,9</sup>|50/100 GB<sup>2,9</sup>|50 GB<sup>2</sup>|
|Cassette postali per le risorse|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|Cassette postali delle cartelle pubbliche<sup>5</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|
|Cassette postali di gruppo|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Inizialmente, ogni utente riceve 100 GB di memoria nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria fino al raggiungimento della capacità massima di 100 GB. Per altre informazioni, vedere [Panoramica dell'archiviazione illimitata in Office 365](/microsoft-365/compliance/unlimited-archiving). <br/> <sup>2</sup> Per accedere a una cassetta postale condivisa un utente deve disporre di una licenza di Exchange Online, ma la cassetta postale condivisa non richiede una licenza separata. Senza licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare il limite per le dimensioni a 100 GB, la cassetta postale condivisa deve essere assegnata a una licenza di Exchange Online (Piano 2). Se viene assegnata una licenza di Exchange Online (Piano 1) con una licenza per il componente aggiuntivo Archiviazione Exchange Online, è possibile abilitare l'archiviazione a espansione automatica per una quantità illimitata di capacità di archiviazione. Analogamente, se si vuole mettere una cassetta postale condivisa in blocco per controversia legale, la cassetta postale condivisa deve essere assegnata a una licenza Exchange Online (Piano 2), oppure a una licenza Exchange Online (Piano 1) con una licenza per il componente aggiuntivo Archiviazione Exchange Online. Se si vogliono applicare caratteristiche avanzate come Microsoft Defender per Office 365, Advanced eDiscovery o criteri di conservazione automatica, è necessario che la cassetta postale condivisa sia concessa in licenza per tali caratteristiche. <br/> <sup>3</sup> Le cassette postali delle risorse non richiedono una licenza. Tuttavia, senza licenza, le cassette postali delle risorse sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo comporterà un aumento nella cassetta postale di 100 GB. <br/> <sup>4</sup>Le cassette postali di archiviazione non sono incluse in Chiosco Exchange Online. Tuttavia, possono essere acquistate come componenti aggiuntivi tramite Archiviazione Exchange Online. Per altre informazioni, vedere [Descrizione del servizio Archiviazione Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> Il limite predefinito per le dimensioni delle singole cartelle pubbliche è di 2 GB. È possibile modificare il limite di dimensioni singolarmente in ogni cartella o modificare il limite di dimensioni predefinito impostato nella configurazione dell'organizzazione per rendere effettiva la modifica per tutte le cartelle dell'organizzazione. Nota: la dimensione massima consigliata per la singola cartella pubblica è 25 GB. Se una singola cartella pubblica supera i 25 GB, si verificano problemi durante il [processo di suddivisione automatica](https://techcommunity.microsoft.com/t5/exchange-team-blog/how-exchange-online-automatically-cares-for-your-public-folder/ba-p/2050019). <br/> <sup>6</sup> L'utente ha un limite di 1.000 cassette postali delle cartelle pubbliche e le dimensioni totali sono pari a 100 TB. Le cassette postali di gestione della gerarchia sono limitate a 100 cassette postali di cartelle pubbliche.<br/> <sup>7</sup> Le cassette postali di archiviazione possono essere usate solo per archiviare messaggi per un singolo utente o entità (ad esempio, una cassetta postale condivisa) per il quale è stata applicata una licenza. Non è consentito usare cassette postali di archiviazione come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, un amministratore IT non può creare cassette postali condivise e lasciare che gli utenti le copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) con l'esplicito scopo di archiviarle. Tenere presente che una cassetta postale condivisa da più utenti non archivia automaticamente le e-mail dei singoli utenti. Più utenti possono accedere e inviare e-mail come cassetta postale condivisa. Pertanto, le uniche e-mail archiviate nella cassetta postale condivisa sono quelle inviate a o ricevute da questa, *come* casetta postale condivisa.<br/> <sup>8</sup> Se in Exchange Online è stato creato un criterio di conservazione, i messaggi verranno spostati automaticamente nella cassetta postale di archiviazione dell'utente soltanto se la cassetta postale principale ha una dimensione superiore a 10 MB. Il criterio di conservazione non verrà eseguito automaticamente per le cassette postali con dimensione inferiore a 10 MB.<br/> <sup>9</sup> Le cassette postali delle risorse e condivise non richiedono una licenza. Tuttavia, senza licenza, queste cassette postali sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo comporterà un aumento nella cassetta postale a 100 GB. <br/> <sup>10</sup> Per impostazione predefinita, alle cassette postali condivise è associato un account utente attivo con una password generata dal sistema (sconosciuta). Per bloccare l'accesso per l'account della cassetta postale condivisa associata, vedere [Blocca l'accesso per l'account della cassetta postale condivisa](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

### <a name="storage-limits-across-standalone-plans"></a>Limiti di spazio di archiviazione nei piani autonomi

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Cassette postali degli utenti|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|Cassette postali di archiviazione<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|Unlimited<sup>2</sup>|Non disponibile<sup>5</sup>|
|Cassette postali condivise<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3,10</sup>|50 GB<sup>3</sup>|
|Cassette postali per le risorse|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4,10</sup>|50 GB<sup>4</sup>|
|Cassette postali delle cartelle pubbliche|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|Non disponibile|
|Cassette postali di gruppo|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Questa è la dimensione predefinita delle cassette postali per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. Non esiste un limite massimo di spazio di archiviazione per le cassette postali locali. <br/> <sup>2</sup> Inizialmente, ogni utente riceve 100 GB di memoria nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria fino al raggiungimento della capacità massima di 100 GB. Per altre informazioni, vedere [Panoramica dell'archiviazione illimitata in Office 365](/microsoft-365/compliance/unlimited-archiving). Vedere la [Roadmap di Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) per i dettagli sulla disponibilità per l'archiviazione in espansione automatica. <br/> <sup>3</sup> Per accedere a una cassetta postale condivisa, un utente deve disporre di una licenza di Exchange Online, ma la cassetta postale condivisa non richiede una licenza separata. Senza licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare il limite per le dimensioni a 100 GB, la cassetta postale condivisa deve essere assegnata a una licenza di Exchange Online (Piano 2). La licenza di Exchange Online Piano 1, con una licenza del componente aggiuntivo Archiviazione di Exchange Online, aumenterà le dimensioni della cassetta postale di archiviazione. In questo modo sarà anche possibile abilitare l'archiviazione a espansione automatica per una quantità illimitata di capacità di archiviazione. Analogamente, se si vuole mettere una cassetta postale condivisa in blocco per controversia legale, la cassetta postale condivisa deve essere assegnata a una licenza Exchange Online (Piano 2), oppure a una licenza Exchange Online (Piano 1) con una licenza per il componente aggiuntivo Archiviazione Exchange Online. Se si vogliono applicare caratteristiche avanzate come Microsoft Defender per Office 365, Advanced eDiscovery o criteri di conservazione automatica, è necessario che la cassetta postale condivisa sia concessa in licenza per tali caratteristiche. <br/> <sup>4</sup> Le cassette postali delle risorse non richiedono una licenza. Tuttavia, senza licenza, le cassette postali delle risorse sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza Exchange Online piano 2. Questo comporterà un aumento nella cassetta postale di 100 GB. <br/> <sup>5</sup>Le cassette postali di archiviazione non sono incluse in Chiosco Exchange Online. Tuttavia, possono essere acquistate come componenti aggiuntivi tramite Archiviazione Exchange Online. Per ulteriori informazioni, vedere [Descrizione del servizio Archiviazione Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Questa è la dimensione predefinita delle cassette postali per le organizzazioni Microsoft Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. In Exchange Server 2013, l'utente ha un limite di 100 cassette postali per cartelle pubbliche e le dimensioni totali sono complessivamente pari a 50 TB.<br/> <sup>7</sup> In Exchange Online, l'utente ha un limite di 1,000 cassette postali per cartelle pubbliche e le dimensioni totali sono complessivamente pari a 50 TB.<br/> <sup>8</sup> Le cassette postali di archiviazione possono essere utilizzate solo per archiviare messaggi per un singolo utente o una singola entità per la quale è stata applicata una licenza. Non è consentito utilizzare una cassetta postale di archiviazione come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, gli amministratori IT non possono creare cassette postali condivise e lasciare che gli utenti copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) una cassetta postale condivisa con l'esplicito scopo di archiviarla. <br/> <sup>9</sup> Se in Exchange Online è stato creato un criterio di conservazione, i messaggi verranno spostati automaticamente nella cassetta postale di archiviazione dell'utente soltanto se la cassetta postale principale ha una dimensione superiore a 10 MB. Il criterio di conservazione non verrà eseguito automaticamente per le cassette postali con dimensione inferiore a 10 MB.<br/> <sup>10</sup> Le cassette postali delle risorse e condivise non richiedono una licenza. Tuttavia, senza licenza, queste cassette postali sono limitate a 50 GB. Per aumentare le dimensioni della cassetta postale, è necessario assegnare una licenza Exchange Online piano 2. Questo comporterà un aumento nella cassetta postale a 100 GB. <br/> <sup>11</sup> Per impostazione predefinita, alle cassette postali condivise è associato un account utente attivo con una password generata dal sistema (sconosciuta). Per bloccare l'accesso per l'account della cassetta postale condivisa associata, vedere [Blocca l'accesso per l'account della cassetta postale condivisa](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

## <a name="capacity-alerts"></a>Avvisi di capacità

Exchange Online offre tre tipi di notifiche quando la capacità della cassetta postale di un utente è quasi o del tutto esaurita:

- **Avviso**: l'utente riceve un avviso mediante posta elettronica con la segnalazione che la cassetta postale sta raggiungendo il limite massimo di dimensioni. Questo avviso ha lo scopo di spingere gli utenti a eliminare la posta indesiderata.

- **Invio non consentito**: l'utente riceve la notifica di invio non consentito quando la cassetta postale ha raggiunto il limite massimo di dimensione. L'utente non potrà più inviare nuovi messaggi fino a quando non viene eliminata una quantità di posta sufficiente a riportare la cassetta postale al di sotto dei limiti di dimensione consentiti.

- **Invio e ricezione non consentiti**: Exchange Online rifiuta la posta elettronica in arrivo quando la cassetta postale ha raggiunto il limite massimo di dimensioni e invia un rapporto di mancato recapito (NDR) al mittente. Il mittente ha la possibilità di provare a inviare di nuovo il messaggio in seguito. Per poter continuare a ricevere messaggi, l'utente deve eliminare i messaggi fino a riportare la cassetta postale al di sotto dei limiti di dimensione consentiti.

### <a name="capacity-alerts"></a>Avvisi di capacità

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Avviso|49 GB|49 GB|49 GB|98 GB|98 GB|1,96 GB|
|Invio non consentito|49,5 GB|49,5 GB|49,5 GB|99 GB|99 GB|1,98 GB|
|Invio e/o ricezione non consentiti|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>Avvisi di capacità nei piani autonomi

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Avviso|1,9 GB<sup>1</sup>|49 GB|98 GB|1,96 GB|
|Invio non consentito|2 GB<sup>1</sup>|49,5 GB|99 GB|1,98 GB|
|Invio e/o ricezione non consentiti|2,3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> Questo è il valore predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.

## <a name="mailbox-folder-limits"></a>Limiti cartella delle cassette postali

Tali limiti servono a delimitare, entro dimensioni note, le cassette postali che possono essere supportate in Exchange Online. L'obiettivo di tali limiti è di prevenire un numero infinito di elementi nella cassetta postale per cartella, un numero infinito di cartelle per cassetta postale o un numero infinito di cartelle pubbliche per organizzazione Exchange Online. Per scopi pratici, i limiti della cartella delle cassette postali non sono realmente limitati e sono sufficienti per supportare la maggior parte delle cassette postali di Exchange Online e in locale migrate su Exchange Online.

- **Numero massimo di messaggi per cartella delle cassette postali**: specifica il numero massimo di messaggi per una cartella cassetta postale. Una volta raggiunto tale limite i nuovi messaggi non possono essere recapitati o salvati in una cartella.

- **Avviso numero di messaggi per cartella delle cassette postali**: specifica il numero di messaggi che una cartella cassetta postale può contenere prima che Exchange Online invii un messaggio di avviso al proprietario della casetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

- **Numero massimo di messaggi per cartella nella cartella Elementi recuperabili**: specifica il numero massimo di messaggi che possono essere contenuti in ciascuna cartella nella cartella Elementi recuperabili. Quando una cartella supera il limite, non può archiviare nuovi messaggi. Ad esempio, se la cartella eliminazioni, presente nella cartella elementi ripristinabili, ha superato il numero massimo di messaggi e il proprietario della cassetta postale tenta di eliminare definitivamente degli elementi dalle loro cassette postali, l'eliminazione non riesce.

- **Avviso per numero di messaggi per cartella consentiti nella cartella Elementi recuperabili** Specifica il numero di messaggi che ciascuna cartella, nella cartella Elementi recuperabili, può mantenere prima che Exchange Online registri un evento nel registro dell'applicazione.

- **Numero massimo di sottocartelle per cartella delle cassette postali**: specifica il numero di sottocartelle che possono essere create nella cartella cassetta postale. Una volta raggiunto il limite, il proprietario della cassetta postale non potrà creare una nuova sottocartella.

- **Avviso numero di sottocartelle per cartella delle cassette postali**: specifica il numero di sottocartelle che possono essere create in una cartella cassetta postale prima che Exchange Online invii un messaggio di avviso al proprietario della casetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

- **Massima profondità gerarchia cartella**: specifica il numero massimo di livelli nella gerarchia della cartella di una cassetta postale. Una volta raggiunto il limite, il proprietario della cassetta postale non potrà creare un altro livello nella gerarchia di cartelle della cartella delle cassette postali.

- **Avviso profondità gerarchia cartella**: specifica il numero di livelli nella gerarchia della cartella delle cassette postali che può essere creata prima che Exchange Online invii un messaggio di avviso al proprietario della cassetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

- **Numero massimo di cartelle pubbliche**: indica il numero massimo di cartelle pubbliche nella gerarchia completa di cartelle pubbliche. Quando viene raggiunto questo limite, le cartelle pubbliche esistenti devono essere eliminate per poterne creare di nuove.

- **Numero massimo di sottocartelle per cartella pubblica**: specifica il numero di sottocartelle che possono essere create in una cartella pubblica. È impossibile creare nuove sottocartelle in una cartella pubblica quando viene raggiunto questo limite.

- **Avviso numero di sottocartelle per cartella pubblica**: specifica il numero di sottocartelle che possono essere create in una cartella pubblica prima che Exchange Online invii un messaggio di avviso al proprietario della cartella. Qualora quest'ultimo non esistesse, i messaggi di avviso vengono inviati agli utenti con le autorizzazioni di proprietario. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

### <a name="mailbox-folder-limits"></a>Limiti cartella delle cassette postali

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Numero massimo di messaggi per cartella di cassette postali|1 milione|1 milione|1 milione|1 milione|1 milione|1 milione|
|Avviso per numero di messaggi per cartella di cassette postali|900,000|900,000|900,000|900,000|900,000|900,000|
|Numero massimo di messaggi per cartella nella cartella Elementi ripristinabili|3 milioni|3 milioni|3 milioni|3 milioni|3 milioni|3 milioni|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (non in attesa)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (in attesa)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (non in attesa)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (in attesa)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Avviso per numero massimo di messaggi per cartella nella cartella Elementi ripristinabili|2,75 milioni|2,75 milioni|2,75 milioni|2,75 milioni|2,75 milioni|2,75 milioni|
|Numero massimo di sottocartelle per cartella delle cassette postali|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|
|Avviso per numero di sottocartelle per cartella di cassette postali|9000|9000|9000|9000|9000|9000|
|Massima profondità gerarchia cartella|300|300|300|300|300|300|
|Avviso per profondità della gerarchia di cartelle|250|250|250|250|250|250|
|Numero massimo di cartelle pubbliche|500.000|500.000|500.000|500.000|500.000|Non disponibile|
|Numero massimo di sottocartelle per cartella pubblica|10,000|10,000|10,000|10,000|10,000|Non disponibile|
|Avviso per numero di sottocartelle per cartella pubblica|9000|9000|9000|9000|9000|Non disponibile|

> [!NOTE]
> <sup>1</sup> Si tratta della quota di archiviazione per la cartella Elementi ripristinabili, non la quota per l'intera cassetta postale di archiviazione. La quota di archiviazione per la cassetta postale di archiviazione è illimitata per gli utenti con una licenza di Exchange Online Piano 2 oppure per gli utenti che dispongono sia di una licenza di Exchange Online Piano 1 sia di una licenza di Archiviazione Exchange Online. Per informazioni sulla quota di Elementi ripristinabili, vedere [Aumentare la quota degli elementi ripristinabili per le cassette postali bloccate](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> La quota di archiviazione iniziale per la cartella Elementi ripristinabili in una cassetta postale di archiviazione è di 100 GB. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima prevista per la cartella Elementi ripristinabili. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](/microsoft-365/compliance/unlimited-archiving). Consultare la [Roadmap di Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) per i dettagli riguardo la disponibilità dell'archiviazione con espansione automatica.
> <sup>2</sup> È un limite per lo store; è uno dei vincoli della forma della cassetta postale. Per un dato genitore possono essere presenti solo 10.000 cartelle figlio dirette. Ciò vale indipendentemente dalla migrazione o da altri client che creano cartelle.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limiti cartella delle cassette postali tra piani autonomi

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Numero massimo di messaggi per cartella delle cassette postali|Nessun limite<sup>1</sup>|1 milione|1 milione|1 milione|
|Avviso per numero di messaggi per cartella delle cassette postali|Nessun limite|900,000|900,000|900,000|
|Numero massimo di messaggi per cartella nella cartella Elementi recuperabili|Nessun limite|3 milioni|3 milioni|3 milioni|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (non in attesa)|30 GB|30 GB|30 GB|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (in attesa)|100 GB|100 GB|100 GB|100 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (non in attesa)|30 GB|30 GB|30 GB|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (in attesa)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|Avviso per numero massimo di messaggi per cartella nella cartella Elementi recuperabili|Nessun limite|2,75 milioni|2,75 milioni|2,75 milioni|
|Numero massimo di sottocartelle per cartella delle cassette postali|Nessun limite|1000|1000|1000|
|Avviso per numero di sottocartelle per cartella delle cassette postali|Nessun limite|900|900|900|
|Massima profondità gerarchia cartella|Nessun limite|300|300|300|
|Avviso per profondità gerarchia cartella|Nessun limite|250|250|250|
|Numero massimo di cartelle pubbliche|1,000,000|100,000|100,000|Non disponibile|
|Numero massimo di sottocartelle per cartella pubblica|N/D|1,000|1,000|Non disponibile|
|Avviso per numero di sottocartelle per cartella pubblica|N/D|900|900|Non disponibile|

> [!NOTE]
> <sup>1</sup> Microsoft consiglia di non conservare più di 1.000.000 di messaggi per ogni cartella della cassetta postale. > <br/> <sup>2</sup> Si tratta della quota di archiviazione per la cartella Elementi ripristinabili, non la quota per l'intera cassetta postale di archiviazione. La quota di archiviazione per la cassetta postale di archiviazione è illimitata per gli utenti con una licenza di Exchange Online Piano 2 oppure per gli utenti che dispongono sia di una licenza di Exchange Online Piano 1 sia di una licenza di Archiviazione Exchange Online. Per informazioni sulla quota di Elementi ripristinabili, vedere [Aumentare la quota degli elementi ripristinabili per le cassette postali bloccate](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> La quota di archiviazione iniziale per la cartella Elementi ripristinabili in una cassetta postale di archiviazione è di 100 GB. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima prevista per la cartella Elementi ripristinabili. Per altre informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](/microsoft-365/compliance/unlimited-archiving). Vedere la [Roadmap di Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) per i dettagli sulla disponibilità per l'archiviazione in espansione automatica. 

## <a name="message-limits"></a>Limiti dei messaggi

I seguenti limiti sono applicati a ogni messaggio di posta elettronica.

- **Limite dimensione messaggio**: i limiti di dimensione dei messaggi sono indispensabili per impedire ai messaggi di grandi dimensioni di bloccare il recapito di altri messaggi e compromettere le prestazioni del servizio a discapito di tutti gli utenti. I limiti includono gli allegati e sono validi a livello di organizzazione per tutti i messaggi (in ingresso, in uscita e interni). I messaggi che superano questo limite non verranno recapitati e il mittente riceverà un rapporto di mancato recapito (NDR). Sebbene limiti di dimensione dei messaggi possano essere configurati su valori più o meno alti o in base ai singoli utenti, gli amministratori possono creare regole di trasporto per limitare le dimensioni massime di ogni singolo allegato. Per ulteriori informazioni, vedere [Microsoft supports larger email messages](https://go.microsoft.com/fwlink/?linkid=2144144) (Microsoft supporta messaggi di posta elettronica più grandi).

    > [!NOTE]
    > Per determinati client di posta elettronica, i limiti di dimensione dei messaggi possono essere inferiori, o il limite di dimensione di un singolo file allegato può essere impostato su un valore inferiore al limite di un messaggio di posta elettronica stabilito in Exchange Online.

- **Limiti dimensioni intestazione messaggi** Specifica le dimensioni massime dei campi di intestazione dei messaggi. Il limite corrente è 256 KB. Se le dimensioni totali di tutte le intestazioni dei messaggi sono superiori a 256 KB, Exchange Online rifiuterà il messaggio con l’errore "552 5.3.4 L’intestazione supera la dimensione massima predefinita." La dimensione del corpo o degli allegati del messaggio non è considerata. Dato che i campi di intestazione sono testo normale, la dimensione dell'intestazione viene determinata dal numero di caratteri in ogni campo di intestazione e dal numero totale di campi di intestazione. Ciascun carattere di testo utilizza 1 byte.

- **Lunghezza massima dell'oggetto**: Il numero massimo di caratteri di testo consentito nella riga dell'oggetto di un messaggio di posta elettronica.

- **Limite massimo di file allegati**: numero massimo di allegati consentito in un messaggio di posta elettronica. Anche se la dimensione totale di tutti i file allegati non supera la dimensione massima del messaggio, esiste comunque un limite sul numero di allegati consentiti nel messaggio. Tale limite viene contrallato dal limite dei messaggi a più parti.

- **Limite di dimensione massima dei file allegati**: dimensione massima di un singolo file allegato.

    > [!NOTE]
    > Dimensione massima di un singolo file allegato. I singoli programmi client, incluso Outlook sul web, potrebbero limitare ulteriormente la dimensione degli allegati. Exchange ActiveSync non applica limiti per la dimensione degli allegati a ogni singolo allegato. È la dimensione totale di tutti gli allegati a un messaggio Exchange ActiveSync che deve essere minore del limite di dimensione dei messaggi consentita.

- **Limite dei messaggi a più parti**: numero massimo di parti del corpo del messaggio consentito in un messaggio a più parti MIME. Tale limite consente anche di controllare il numero massimo di file che è possibile allegare a un messaggio.

- **Limite di profondità dei messaggi incorporati**: Numero massimo di messaggi di posta elettronica inoltrati consentito in un messaggio di posta elettronica.

### <a name="message-limits"></a>Limiti dei messaggi

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite per la dimensione del messaggio - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Limite per la dimensione del messaggio - OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Limite per la dimensione del messaggio - Outlook per Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Limite per la dimensione del messaggio - migrazione|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Limite per la dimensione del messaggio - Outlook per iOS e Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano Crittografia messaggi di Office 365 con nuove funzionalità)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano una versione legacy Crittografia messaggi di Office 365)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Lunghezza massima dell'oggetto|255 caratteri|255 caratteri|255 caratteri|255 caratteri|255 caratteri|255 caratteri|
|Limite massimo dei file allegati|250 allegati|250 allegati|250 allegati|250 allegati|250 allegati|250 allegati|
|Limite di dimensione massima dei file allegati - Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Limite di dimensione massima dei file allegati - OWA |112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|
|Limite di dimensione massima dei file allegati - Outlook per Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Limite di dimensione massima dei file allegati - Outlook per iOS e Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Limite dei messaggi a più parti|250 parti|250 parti|250 parti|250 parti|250 parti|250 parti|
|Limite di profondità del messaggio incorporato|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|

> [!NOTE]
> <sup>1</sup> La dimensione massima predefinita per le cassette postali di Microsoft è 25 MB. Gli amministratori di Microsoft possono specificare un limite personalizzato compreso tra 1 MB e 150 MB. Tuttavia, le dimensioni dei messaggi che è possibile inviare o ricevere dipende anche da cosa è supportato dal client o dalla soluzione di posta elettronica in uso. Per ulteriori informazioni sulla personalizzazione della dimensione massima consentita dei messaggi per l'organizzazione, vedere [Microsoft supports larger email messages](https://go.microsoft.com/fwlink/?linkid=2144144) (Microsoft supporta messaggi di posta elettronica più grandi). <br/> <sup>2</sup> È possibile inviare e ricevere messaggi di dimensioni fino a 150 MB tra utenti (dove il messaggio non lascia mai i data center di Microsoft). I messaggi indirizzati al di fuori dei data center di Microsoft sono soggetti a un ulteriore aumento del 33% della codifica di traduzione. In tal caso le dimensioni massime dei messaggi sono di 112 MB.<br/> 
<sup>3</sup> In OWA i messaggi possono essere soggetti a un aumento del 33% della codifica e le dimensioni dei messaggi che è possibile inviare vengono ridotte del 25% rispetto all'impostazione configurata. Ad esempio, se si personalizzano le impostazioni per una dimensione massima dei messaggi di 100 MB, è possibile inviare messaggi di dimensioni non superiori a 75 MB. <br/> <sup>4</sup> La dimensione dei messaggi da spostare in Exchange Online viene calcolata da Exchange Online. Le versioni di Exchange precedenti a Exchange Server 2013 possono riportare una dimensione dell'articolo più piccola. Questo limite si applica alle migrazioni basate sullo spostamento che utilizzano i servizi di replica delle cassette postali supportati da Exchange. Altri metodi di migrazione (Cutover, Staged, IMAP, PST) e altri strumenti di terze parti sono limitati dal limite generale delle dimensioni dei messaggi. <br/> 
<sup>5</sup> Per informazioni su OME con nuove funzionalità, vedere [Configurare le nuove funzionalità di Crittografia messaggi di Office 365 basate su Azure Information Protection](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).<br/> 
<sup>6</sup> I file allegati classici hanno un limite di 112 MB, ma i file allegati di OneDrive possono essere fino a 2 GB.


### <a name="message-limits-across-standalone-options"></a>Limiti dei messaggi nelle opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite per la dimensione del messaggio - Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Limite per la dimensione del messaggio - OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Limite per la dimensione del messaggio - Outlook per Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Limite per la dimensione del messaggio - migrazione|Non applicabile|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|Limite per la dimensione del messaggio - Outlook per iOS e Android |25 MB |33 MB |33 MB |33 MB |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano Crittografia messaggi di Office 365 con nuove funzionalità)<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano una versione legacy Crittografia messaggi di Office 365)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|Lunghezza massima dell'oggetto|255 caratteri|255 caratteri|255 caratteri|255 caratteri|
|Limite massimo dei file allegati|1024 attachments<sup>4</sup>|250 allegati|250 allegati|250 allegati|
|Limite di dimensione massima dei file allegati - Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|Limite di dimensione massima dei file allegati - OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|Limite di dimensione massima dei file allegati - Outlook per Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Limite di dimensione massima dei file allegati - Outlook per iOS e Android|25 MB |33 MB|33 MB|33 MB|
|Limite dei messaggi a più parti|250 parti|250 parti|250 parti|250 parti|
|Limite di profondità del messaggio incorporato|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|

> [!NOTE]
> <sup>1</sup> Gli amministratori di Microsoft possono specificare un limite personalizzato compreso tra 1 MB e 150 MB. Tuttavia, le dimensioni dei messaggi che è possibile inviare o ricevere dipende anche da cosa è supportato dal client o dalla soluzione di posta elettronica in uso. Per ulteriori informazioni sulla personalizzazione della dimensione massima consentita dei messaggi per l'organizzazione, vedere [Microsoft supports larger email messages](https://go.microsoft.com/fwlink/?linkid=2144144) (Microsoft supporta messaggi di posta elettronica più grandi). <br/> <sup>2</sup> È possibile inviare e ricevere messaggi di dimensioni fino a 150 MB tra utenti (dove il messaggio non lascia mai i data center di Microsoft). I messaggi indirizzati al di fuori dei data center di Microsoft sono soggetti a un ulteriore aumento del 33% della codifica di traduzione. In tal caso le dimensioni massime dei messaggi sono di 112 MB.<br/> 
<sup>3</sup> In OWA i messaggi possono essere soggetti a un aumento del 33% della codifica e le dimensioni dei messaggi che è possibile inviare vengono ridotte del 25% rispetto all'impostazione configurata. Ad esempio, se si personalizzano le impostazioni per una dimensione massima dei messaggi di 100 MB, è possibile inviare messaggi di dimensioni non superiori a 75 MB. <br/> 
<sup>4</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. <br/> 
<sup>5</sup> Le dimensioni dei messaggi da spostare in Exchange Online vengono calcolate da Exchange Online. Versioni di Exchange precedenti a Exchange Server 2013 possono riportare dimensioni più piccole dell'elemento. <br/> 
<sup>6</sup> Per informazioni su OME con nuove funzionalità, vedere [Configurare le nuove funzionalità di Crittografia messaggi di Office 365 basate su Azure Information Protection](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).

## <a name="receiving-and-sending-limits"></a>Limiti di invio e ricezione

I limiti di invio e ricezione sono applicati come protezione dalla posta indesiderata e dall'invio in massa di messaggi contenenti worm o virus. Questi limiti consentono di proteggere l'integrità dei sistemi e di mantenere gli utenti sicuri.

### <a name="receiving-limits"></a>Limiti di ricezione

I limiti di ricezione si applicano al numero di messaggi che un utente, un gruppo o una cartella pubblica di Exchange Online può ricevere.

- **Limite di ricezione:** questo limite si applica al numero di messaggi all'ora *da una o tutte le origini*. Sono inclusi i messaggi da mittenti interni, da Internet e da server locali. Una volta superato il limite di ricezione in una cassetta postale, i messaggi inviati alla cassetta postale torneranno al mittente in un rapporto di mancato recapito (noto anche come NDR o notifica di mancato recapito) indicante che la cassetta postale ha superato la soglia massima consentita di recapiti. Dopo un'ora, il limite verrà aggiornato e la cassetta postale potrà ricevere messaggi.
- **Limita coppia mittente-destinatario:** questo limite si applica al numero di messaggi all'ora da *un singolo mittente*. Questo valore stabilisce un rapporto del limite di ricezione complessivo per la protezione da un flusso di messaggi da un singolo mittente.

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard Office | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Messaggi ricevuti|3,600 messaggi all'ora|3,600 messaggi all'ora|3,600 messaggi all'ora|3,600 messaggi all'ora|3.600 messaggi all'ora|3.600 messaggi all'ora|
|Messaggi ricevuti da un singolo mittente|33% dei messaggi ricevuti|33% dei messaggi ricevuti|33% dei messaggi ricevuti|33% dei messaggi ricevuti|33% dei messaggi ricevuti|33% dei messaggi ricevuti|

### <a name="sending-limits"></a>Limiti di invio

I limiti di invio si applicano al numero di destinatari, di messaggi e di destinatari per messaggio che un utente può inviare dal proprio account Exchange Online.

> [!NOTE]
> Per i gruppi di distribuzione archiviati nella rubrica dell'organizzazione, il gruppo viene conteggiato come un unico destinatario. Per i gruppi di distribuzione archiviati nella cartella Contatti di una cassetta postale, i membri del gruppo vengono conteggiati singolarmente.

- **Limite numero di destinatari**: per ridurre il recapito di messaggi in blocco non desiderati, in Exchange Online sono presenti dei limiti per il numero di destinatari che impediscono a utenti e applicazioni di inviare un gran numero di messaggi di posta elettronica. Questi limiti vengono applicati per singolo utente a tutti i messaggi in uscita e interni.

    > [!NOTE]
    > Per gli utenti di Exchange Online con l'esigenza di inviare messaggi di posta commerciale in blocco legittima (ad esempio, le newsletter ai clienti) è consigliabile continuare a utilizzare provider di terze parti specializzati in tali servizi.

- **Limite destinatari**: Numero massimo di destinatari del che possono essere inseriti nei campi A:, Cc: e Bcc: di ciascun messaggio di posta elettronica.

    > [!NOTE]
    > Per quanto riguarda i limiti sul numero di destinatari, un gruppo di distribuzione memorizzato nella rubrica condivisa dell'organizzazione viene contato come un singolo destinatario. In un gruppo di distribuzione personale, ciascun destinatario viene conteggiato separatamente.

- **Limite di indirizzi proxy del destinatario**: il limite degli indirizzi proxy dei destinatari è il numero massimo di alias (indirizzi di posta elettronica) che può avere una cassetta postale del destinatario. 

- **Limite di frequenza dei messaggi** I limiti alla frequenza dei messaggi determinano il numero massimo di messaggi che un utente può inviare dal proprio account Exchange Online in un determinato periodo di tempo. Questo limite consente di evitare il consumo di risorse di sistema da un mittente singolo. Se un utente invia messaggi a una velocità che supera il limite tramite invio client SMTP, verranno rifiutati i messaggi e il client dovrà riprovare.

#### <a name="sending-limits"></a>Limiti di invio

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite numero di destinatari<sup>1</sup>|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|
|Limite destinatari<sup>2</sup>|Personalizzabile fino a 1000 destinatari|Personalizzabile fino a 1000 destinatari|Personalizzabile fino a 1000 destinatari|Personalizzabile fino a 1000 destinatari|Personalizzabile fino a 1000 destinatari|Personalizzabile fino a 1000 destinatari|
|Limite di indirizzi proxy del destinatario|400|400|400|400|400|400|
|Limite di frequenza dei messaggi<sup>3</sup>|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|

> [!NOTE]
> <sup>1</sup>: Al raggiungimento del limite massimo, non è possibile inviare ulteriori messaggi dalla cassetta postale fino a quando il numero di destinatari a cui sono stati inviati messaggi nelle ultime 24 ore non scende al di sotto del limite. Ad esempio, un utente invia un messaggio di posta elettronica a 5000 destinatari alle 09:00, quindi invia un altro messaggio a 2500 destinatari alle 10.00 e quindi invia un altro messaggio a 2500 destinatari alle 11.00, fino a raggiungere il limite di 10.000 messaggi. L'utente non potrà inviare di nuovo messaggi fino alle 09:00 del giorno successivo.  
> <sup>2</sup>È possibile personalizzare i limiti dei destinatari tra 1 e 1000 per le cassette postali esistenti e per quelle nuove che verranno create in futuro. Modificare il limite dei destinatari per le cassette postali esistenti singolarmente o in blocco usando l'interfaccia di amministrazione di Exchange e personalizzare l'impostazione predefinita per le nuove cassette postali tramite una sessione remota di PowerShell. Per altre informazioni, vedere [Destinatari personalizzabili in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).  
> <sup>3</sup> Quando i volumi dei messaggi in uscita supereranno il limite di frequenza impostato, gli eventuali messaggi in eccesso verranno limitate e riportati in seguito nei minuti seguenti. Questo in genere non blocca l'account del mittente, ma Exchange Online non è adatto per scenari di invio di posta in blocco. Per questo caso di utilizzo, le opzioni 2 e 3 [qui](/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) sono le opzioni consigliate.

#### <a name="sending-limits-across-standalone-options"></a>Limiti di invio nelle opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite numero di destinatari|Nessun limite<sup>1</sup>|10.000 destinatari al giorno<sup>2</sup>|10.000 destinatari al giorno<sup>2</sup>|10.000 destinatari al giorno<sup>2</sup>|
|Limite destinatari|1000 destinatari<sup>1</sup>|1000 destinatari|1000 destinatari|1000 destinatari|
|Limite di indirizzi proxy del destinatario|400|400|400|400|
|Limite di frequenza dei messaggi|Nessun limite|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.<br/>
<sup>2</sup>: Al raggiungimento del limite massimo di frequenza destinatari, non è possibile inviare ulteriori messaggi dalla cassetta postale fino a quando il numero di destinatari a cui sono stati inviati messaggi nelle ultime 24 ore non scende al di sotto del limite. Ad esempio, un utente invia un messaggio di posta elettronica a 5000 destinatari alle 09:00, quindi invia un altro messaggio a 2500 destinatari alle 10.00 e quindi invia un altro messaggio a 2500 destinatari alle 11.00, fino a raggiungere il limite di 10.000 messaggi. L'utente non potrà inviare di nuovo messaggi fino alle 09:00 del giorno successivo.

## <a name="reporting-and-message-trace-limits"></a>Limiti relativi alla creazione di rapporti e traccia dei messaggi

Per informazioni sui limiti relativi alla creazione di rapporti e traccia dei messaggi, vedere la sezione "Disponibilità e latenza della creazione di rapporti e traccia dei messaggi" nell'articolo [Creazione di rapporti e traccia dei messaggi in Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).

## <a name="retention-limits"></a>Limiti di conservazione

Questi limiti controllano il periodo di tempo durante il quale è possibile accedere agli elementi presenti in cartelle specifiche nella Posta in arrivo.

- **Periodo di mantenimento per la cartella Posta eliminata**: Numero massimo di giorni in cui gli elementi possono rimanere nella cartella Posta eliminata prima di essere rimossi automaticamente.

- **Periodo di mantenimento per gli elementi rimossi dalla cartella Posta eliminata**: Numero massimo di giorni prima che gli elementi rimossi dalla cartella Posta eliminata vengano eliminati in modo definitivo.

- **Periodo di mantenimento per la cartella Posta indesiderata**: Numero massimo di giorni in cui gli elementi possono rimanere nella cartella Posta indesiderata prima di essere rimossi automaticamente.

> [!NOTE]
> Una cassetta postale utente eliminata in modo reversibile&mdash;una cassetta postale eliminata tramite l'interfaccia di amministrazione di Microsoft 365 o il cmdlet Remove-Mailbox nella PowerShell di Exchange Online e che si trova ancora nel Cestino di Azure Active Directory&mdash;sarà recuperabile entro 30 giorni.

### <a name="retention-limits"></a>Limiti di conservazione

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Periodo di mantenimento per la cartella Posta eliminata|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|
|Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|
|Periodo di conservazione per la cartella Posta indesiderata|30 giorni|30 giorni|30 giorni|30 giorni|30 giorni|30 giorni|

> [!NOTE]
> <sup>1</sup> Questo è il valore predefinito per le organizzazioni di Microsoft 365. Gli amministratori possono modificare questo valore in un massimo di 30 giorni per le cassette postali dell'organizzazione.

### <a name="retention-limits-across-standalone-options"></a>Limiti di mantenimento nelle opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Periodo di mantenimento per la cartella Posta eliminata|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|
|Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata|14 giorni<sup>1</sup>|14 giorni<sup>2</sup>|14 giorni<sup>2</sup>|14 giorni<sup>2</sup>|
|Periodo di mantenimento per la cartella Posta indesiderata|2 anni<sup>1</sup>|30 giorni|30 giorni|30 giorni|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito. Gli amministratori possono modificare questo valore per l'organizzazione.<br/> <sup>2</sup> Questo è il valore predefinito per le organizzazioni di Exchange Online. Gli amministratori possono modificare questo valore in un massimo di 30 giorni per le cassette postali dell'organizzazione.

## <a name="distribution-group-limits"></a>Limiti dei gruppi di distribuzione

Questi limiti si applicano ai gruppi di distribuzione nella rubrica condivisa dell'organizzazione.

- **Numero massimo di membri del gruppo di distribuzione**: Il numero totale di destinatari viene determinato dopo l'espansione del gruppo di distribuzione.

- **Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni**: per i gruppi di distribuzione che contengono il numero di membri specificato da questo limite è necessario che siano configurate le opzioni di gestione recapito o di approvazione messaggi. La gestione recapito specifica un elenco di mittenti a cui è consentito inviare messaggi al gruppo di distribuzione. L'approvazione messaggi specifica uno o più moderatori che devono approvare tutti i messaggi inviati al gruppo di distribuzione.

- **Dimensione massima dei messaggi per gruppi di distribuzione di grandi dimensioni**: se un messaggio viene inviato a 5.000 o più destinatari, la dimensione del messaggio non può superare questo limite. Se la dimensione del messaggio supera questo limite, il messaggio non verrà recapitato e il mittente riceverà un rapporto di mancato recapito.

### <a name="distribution-group-limits"></a>Limiti dei gruppi di distribuzione

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Numero massimo di membri del gruppo di distribuzione<sup>1</sup>|100.000 membri|100.000 membri|100.000 membri|100.000 membri|100.000 membri|100.000 membri|
|Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni.|5.000 membri o più|5.000 membri o più|5.000 membri o più|5.000 membri o più|5.000 membri o più|5.000 membri o più|
|Dimensione massima dei messaggi per gruppi di distribuzione da 5.000 a 99.999 membri.|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Dimensione massima dei messaggi per gruppi di distribuzione con 100.000 membri.|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Numero massimo di proprietari del gruppo di distribuzione|10|10|10|10|10|10|
|Numero massimo di gruppi che è possibile creare|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Se si utilizza Azure Active Directory DirSync, il numero massimo di membri del gruppo di distribuzione che è possibile sincronizzare da Active Directory locale ad Azure Active Directory è pari a 15.000. Se si utilizza Azure AD Connect, tale numero è pari a 50.000. <br/> <sup>2</sup> Questo limite si applica anche agli amministratori.

### <a name="distribution-group-limits-across-standalone-options"></a>Limiti dei gruppi di distribuzione nelle opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Numero massimo di membri del gruppo di distribuzione|100.000 membri<sup>1</sup>|100.000 membri|100.000 membri|100.000 membri|
|Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni.|5.000 membri o più<sup>1</sup>|5.000 membri o più|5.000 membri o più|5.000 membri o più|
|Numero massimo di proprietari del gruppo di distribuzione|10|10|10|10|
|Numero massimo di gruppi che è possibile creare|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.<br/> <sup>2</sup> Questo limite si applica anche agli amministratori.

## <a name="journal-transport-and-inbox-rule-limits"></a>Limiti delle regole di diario, trasporto e posta in arrivo

Il seguente elenco include i limiti validi per le regole del journal, quelle di trasporto (note anche come regole all'interno dell'organizzazione) e i limiti validi per le regole di posta in arrivo. Le regole di Posta in arrivo vengono configurate da utenti singoli e applicate ai messaggi inviati e ricevuti dalla cassetta postale del singolo utente.

- **Numero massimo di regole di diario**: Numero massimo di regole di diario che possono esistere nell'organizzazione.

- **Numero massimo di regole di trasporto**: Numero massimo di regole che possono esistere nell'organizzazione.

- **Dimensione massima di una singola regola di trasporto**: numero massimo di caratteri che possono essere utilizzati in una singola regola di trasporto. I caratteri vengono utilizzati nelle condizioni, nelle eccezioni e nelle azioni.

- **Limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto**: il numero totale di caratteri utilizzati da tutte le espressioni regolari in tutte le condizioni e le eccezioni delle regole di trasporto nell'organizzazione. È possibile avere poche regole che utilizzano espressioni regolari lunghe e complesse o molte regole che utilizzano espressioni regolari semplici.

- **Limiti di analisi per i contenuti allegati**: le condizioni della regola di trasporto consentono di esaminare il contenuto degli allegati dei messaggi. Tuttavia, viene controllato solo il primo MB del testo estratto da un allegato. Il limite di 1 MB si riferisce al testo estratto dall'allegato e non alla dimensione del file dell'allegato. Ad esempio, un file di 2 MB può contenere meno di 1 MB di testo, quindi tutto il testo verrà esaminato.

- **Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto**: quando un messaggio è interessato da diverse regole di trasporto, è possibile aggiungere solo un numero limitato di destinatari al messaggio. Una volta raggiunto tale limite, i destinatari rimanenti non verranno aggiunti al messaggio. Non è inoltre possibile aggiungere i gruppi di distribuzione a un messaggio mediante una regola di trasporto.

- **Limiti di inoltro**: numero massimo di destinatari configurabili per una regola di posta in arrivo o di trasporto con un'azione di reindirizzamento. Se una regola viene configurata per reindirizzare un messaggio a un numero maggiore di destinatari, la regola non verrà applicata e tutti i messaggi che soddisfano la condizione della regola non verranno reindirizzati a nessuno dei destinatari elencati nella regola.
    
- **Numero di reindirizzamenti di un messaggio**: numero di volte in cui un messaggio verrà reindirizzato, inoltrato o a cui verrà risposto automaticamente sulla base delle regole di Posta in arrivo. Ad esempio, l'utente A ha una regola di Posta in arrivo basata sul mittente che reindirizza i messaggi all'utente B. L'utente B ha una regola di Posta in arrivo che inoltra i messaggi all'utente C sulla base di parole chiave presenti nella riga dell'oggetto. Se un messaggio soddisfa entrambe queste condizioni, il messaggio viene inviato soltanto all'utente B. Non viene inoltrato all'utente C in quanto è consentito solo un reindirizzamento. In questo caso, il messaggio viene eliminato senza inviare un rapporto di mancato recapito all'utente B per indicare che il messaggio non è stato recapitato all'utente C. L'intestazione X-MS-Exchange-Inbox-Rules-Loop viene utilizzata per determinare il numero di reindirizzamenti di un messaggio. Questa intestazione rimane anche oltre i confini dell'organizzazione di Exchange.

- **Numero di reindirizzamenti di un messaggio da una regola di trasporto**: Numero di volte in cui un messaggio verrà reindirizzato sulla base delle regole di trasporto. Ad esempio, l'organizzazione di Exchange Tailspin Toys ha una regola di trasporto per reindirizzare ogni messaggio inviato all'utente A all'utente B, che si trova nell'organizzazione di Exchange Contoso. All’interno dell'organizzazione di Exchange Contoso esiste una regola di trasporto per reindirizzare ogni messaggio inviato all'utente B all'utente C, che si trova nell'organizzazione di Exchange Società A. Datum. In questo caso, il messaggio viene eliminato e un rapporto di mancato recapito con codice di stato e il messaggio di rifiuto viene inviato all’utente A. *550 5.7.128 TRANSPORT. Regole. RejectMessage; Numero di cicli delle regole di trasporto superato e messaggio rifiutato*. L'intestazione X-MS-Exchange-Transport-Rules-Loop viene utilizzata per determinare il numero di volte in cui un messaggio è stato reindirizzato dalle regole di trasporto. Questa intestazione rimane anche oltre i limiti dell'organizzazione di Exchange.

### <a name="journal-transport-and-inbox-rule-limits"></a>Limiti delle regole di diario, trasporto e posta in arrivo

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Numero massimo di regole di diario|300 regole|300 regole|300 regole|300 regole|300 regole|300 regole|
|Numero massimo di regole di trasporto|300 regole|300 regole|300 regole|300 regole|300 regole|300 regole|
|Dimensione massima di una singola regola di trasporto|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|Il limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|Limiti di analisi per il contenuto degli allegati|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto|100 destinatari|100 destinatari|100 destinatari|100 destinatari|100 destinatari|100 destinatari|
|Limite di inoltri|10 destinatari|10 destinatari|10 destinatari|10 destinatari|10 destinatari|10 destinatari|
|Numero di reindirizzamenti di un messaggio|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|
|Numero di reindirizzamenti di un messaggio da una regola di trasporto|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|
|Numero di reindirizzamenti di un messaggio|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|
|Regola Posta in arrivo|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> Se è stata eseguita la migrazione di una cassetta postale a Exchange Online, il limite relativo alla regola della posta in arrivo potrebbe essere impostato sul valore minore del valore EXO predefinito. In questo caso, è possibile aumentare il valore della regola della posta in arrivo. Per istruzioni, vedere [Modificare lo spazio usato dalle regole Posta in arrivo in Exchange Online](/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules). 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limiti delle regole di diario, trasporto e posta in arrivo nelle opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Numero massimo di regole di journal|Nessun limite|50 regole|50 regole|50 regole|
|Numero massimo di regole di trasporto|Nessun limite|300 regole|300 regole|300 regole|
|Dimensione massima di una singola regola di trasporto|40 KB|8 KB|8 KB|8 KB|
|Il limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto|Nessun limite|20 KB|20 KB|20 KB|
|Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto|Nessun limite|100 destinatari|100 destinatari|100 destinatari|
|Limite di inoltri|Nessun limite|10 destinatari|10 destinatari|10 destinatari|
|Numero di reindirizzamenti di un messaggio|3 reindirizzamenti|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|
|Numero di reindirizzamenti di un messaggio da una regola di trasporto|Nessun limite|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|

## <a name="moderation-limits"></a>Limiti di moderazione

Questi limiti controllano le impostazioni di moderazione utilizzate per l'approvazione di messaggi applicata ai gruppi di distribuzione e alle regole di trasporto.

- **Dimensione massima della cassetta postale di arbitraggio**: Se la cassetta postale di arbitraggio supera questo limite, i messaggi che richiedono moderazione vengono restituiti al mittente in un rapporto di mancato recapito.

- **Numero massimo di moderatori**: numero massimo di moderatori che è possibile assegnare a un singolo gruppo di distribuzione con moderatore o che è possibile aggiungere a un messaggio utilizzando una singola regola di trasporto. Si noti che non è possibile specificare un gruppo di distribuzione come moderatore.

- **Scadenza dei messaggi in attesa di moderazione**: per impostazione predefinita, un messaggio in attesa di moderazione scade dopo due giorni. Tuttavia, l'elaborazione dei messaggi moderati scaduti viene eseguita ogni sette giorni. Ciò significa che un messaggio moderato può scadere in qualsiasi momento compreso tra due e nove giorni.

- **Frequenza massima per i messaggi di notifica di moderazione scaduta**: questo limite imposta il numero massimo di messaggi di notifica per i messaggi moderati scaduti in un'ora. Questo limite viene specificato per ogni database delle cassette postali nel centro dati.

Durante i periodi di intenso utilizzo è possibile che alcuni mittenti non ricevano messaggi di notifica per i messaggi moderati scaduti. Tuttavia, tali notifiche saranno sempre disponibili mediante i rapporti di recapito.

### <a name="moderation-limits"></a>Limiti di moderazione

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Dimensione massima della cassetta postale di arbitraggio|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|Numero massimo di moderatori|10 moderatori|10 moderatori|10 moderatori|10 moderatori|10 moderatori|10 moderatori|
|Scadenza per i messaggi in attesa di moderazione|2 giorni|2 giorni|2 giorni|2 giorni|2 giorni|2 giorni|
|Frequenza massima per i messaggi di notifica di moderazione scaduta|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|

### <a name="moderation-limits-across-standalone-options"></a>Limiti di moderazione nelle opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Dimensione massima della cassetta postale di arbitraggio|Nessun limite<sup>1</sup>|10 GB|10 GB|10 GB|
|Numero massimo di moderatori|Nessun limite|10 moderatori|10 moderatori|10 moderatori|
|Scadenza per i messaggi in attesa di moderazione|5 giorni<sup>1</sup>|2 giorni|2 giorni|2 giorni|
|Frequenza massima per i messaggi di notifica di moderazione scaduta|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.

## <a name="exchange-activesync-limits"></a>Limiti di Exchange ActiveSync

I seguenti limiti sono validi per Microsoft Exchange ActiveSync, un protocollo client che sincronizza i dati della cassetta postale tra dispositivi mobili ed Exchange.

- **Limite di dispositivi Exchange ActiveSync**: Il numero massimo di dispositivi Exchange ActiveSync per cassetta postale.

- **Limite di eliminazione di dispositivi Exchange ActiveSync**: Il numero massimi di dispositivi Exchange ActiveSync che un amministratore Exchange può eliminare in un mese.

### <a name="exchange-activesync-limits"></a>Limiti di Exchange ActiveSync

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite di dispositivi Exchange ActiveSync|100|100|100|100|100|100|
|Limite di eliminazione di dispositivi Exchange ActiveSync|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Limiti di Exchange ActiveSync tra le opzioni autonome

| Funzionalità | Exchange Server 2013 | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite di dispositivi Exchange ActiveSync|100|100|100|100|
|Limite di eliminazione di dispositivi Exchange ActiveSync|20|20|20|20|