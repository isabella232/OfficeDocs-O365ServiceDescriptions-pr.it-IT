---
title: Limiti Exchange Online Limits
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Trovare i limiti di Exchange Online per diverse aree di servizio, compresi, a titolo esemplificativo, quelli relativi a rubrica, archiviazione delle cassette postali, creazione di rapporti e traccia dei messaggi.
ms.openlocfilehash: efab17a6513dac571abfd314549d0f90017564da
ms.sourcegitcommit: 4d1cc432b4ce292abeb926f88108937695ce619b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/15/2019
ms.locfileid: "37523451"
---
# <a name="exchange-online-limits"></a>Limiti Exchange Online Limits

Trovare i limiti di Exchange Online per diverse aree di servizio, compresi, a titolo esemplificativo, quelli relativi a rubrica, archiviazione delle cassette postali, creazione di rapporti e traccia dei messaggi.

> [!NOTE]
> Se si necessita assistenza con questa operazione o per risolvere un problema, potrebbe essere necessario trovare utili i seguenti articoli:  <br/> • [Posta elettronica](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (per informazioni su come creare e inviare messaggi di posta elettronica)  <br/> • [Messaggi di posta elettronica in Office 365 for Business-Guida per gli amministratori](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [Fix Outlook and office 365 problems with Microsoft Support and Recovery Assistant for office 365](https://diagnostics.office.com/) <br/>  • [Rapporti di mancato recapito tramite posta elettronica in Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Guida di Exchange Online](https://go.microsoft.com/fwlink/?linkid=825607)

I limiti in Microsoft Exchange Online rientrano in una delle categorie seguenti:

- [Limiti della rubrica](#address-book-limits)

- [Limiti di archiviazione delle cassette postali](#mailbox-storage-limits)

- [Avvisi di capacità](#capacity-alerts)

- [Limiti cartella delle cassette postali](#mailbox-folder-limits)

- [Limiti dei messaggi](#message-limits)

- [Limiti di invio e ricezione](#receiving-and-sending-limits)

- [Limiti relativi alla creazione di rapporti e traccia dei messaggi](#reporting-and-message-trace-limits)

- [Limiti di conservazione](#retention-limits)

- [Distribution group limits](#distribution-group-limits)

- [Limiti delle regole di journal, trasporto e Posta in arrivo ](#journal-transport-and-inbox-rule-limits)

- [Moderation limits](#moderation-limits)

- [Limiti di Exchange ActiveSync](#exchange-activesync-limits)

> [!IMPORTANT]
> • I limiti applicati a un'organizzazione di Microsoft Office 365 possono variare in base al tempo di registrazione dell'organizzazione nel servizio. <br/> • Quando un limite viene modificato nei Data Center Microsoft, può essere necessario un certo tempo per applicare la modifica a tutti i clienti esistenti. <br/> • Non è possibile modificare la maggior parte di questi limiti, ma gli utenti devono essere a conoscenza di essi. <br/> • Questi limiti si applicano ai destinatari sia interni che esterni. <br/> • Per impostazione predefinita, Exchange Online Protection (EOP) protegge le cassette postali di Exchange Online. Per i limiti che si applicano alle funzionalità di EOP in Exchange Online, vedere [Limiti Exchange Online Protection](../exchange-online-protection-service-description/exchange-online-protection-limits.md). <br/> • Per informazioni sui limiti di gruppi di Office 365, vedere "come gestire i gruppi?" in informazioni [sui gruppi di Office 365](https://go.microsoft.com/fwlink/?linkid=846714).

## <a name="address-book-limits"></a>Limiti della rubrica

- **Limite elenco indirizzi**: numero massimo di elenchi di indirizzi che è possibile creare in un'organizzazione di Exchange Online o exchange Server 2013. Questo numero include gli elenchi indirizzi predefiniti in Exchange Online, quali Tutti i contatti e Tutti i gruppi.

    > [!NOTE]
    > È possibile assegnare un massimo di 20 elenchi indirizzi a una singola rubrica offline (OAB).

- **Limite Rubrica offline**: numero massimo di rubriche offline che è possibile creare in un'organizzazione di Exchange Online o exchange Server 2013.

- **Limite dei criteri della rubrica**: il numero massimo di Criteri rubrica che è possibile creare in un'organizzazione di Exchange Online o exchange Server 2013.

- **Elenchi di indirizzi globali**: numero massimo di elenchi indirizzi globali (GAL, Global Address List) creati in un'organizzazione di Exchange Online o exchange Server 2013.

### <a name="address-book-limits-across-office-365-options"></a>Limiti della rubrica nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Limite elenco indirizzi|1000|1000|1000|1000|1000|1000|
|Limite rubrica offline (OAB, offline address book)|250|250|250|250|250|250|
|Limite criteri delle rubriche (ABP, address book policies)|250|250|250|250|250|250|
|Limite elenchi indirizzi globali|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Limiti della rubrica nei piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Limite elenco indirizzi|1000|1000|1000|1000|
|Limite rubrica offline (OAB, offline address book)|250|250|250|250|
|Limite criteri delle rubriche (ABP, address book policies)|250|250|250|250|
|Limite elenchi indirizzi globali|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Limiti di archiviazione delle cassette postali

Il volume di archiviazione delle cassette postali è determinato dal tipo di cassetta postale e dalla licenza di sottoscrizione dell'utente. Gli amministratori possono ridurre le dimensioni massime della cassetta postale per singolo utente o a livello globale.

> [!NOTE]
> L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a una cassetta postale di Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti.

### <a name="storage-limits-across-office-365-options"></a>Limiti di spazio di archiviazione per le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Cassette postali utente|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Archiviazione delle cassette postali<sup>7, 8</sup>|50 GB|50 GB|50 GB|Numero illimitato<sup>1</sup>|Numero illimitato<sup>1</sup>|Non disponibile<sup>4</sup>|
|Cassette postali condivise<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2, 9</sup>|50 GB<sup>2, 9</sup>|50 GB<sup>2</sup>|
|Cassette postali per le risorse|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3, 9</sup>|50 GB<sup>3, 9</sup>|50 GB<sup>3</sup>|
|Cassette postali del sito<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|Non disponibile|
|Cassette postali delle cartelle pubbliche|50 GB<sup>6</sup>|50 GB<sup>6</sup>|50 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|Non disponibile|
|Cassette postali di gruppo|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Inizialmente, ogni utente riceve 100 GB di memoria nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima di 100 GB. Office 365 fornisce fino a 1 TB di spazio di archiviazione aggiuntivo in una cassetta postale di archiviazione. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). <br/> <sup>2</sup> per accedere a una cassetta postale condivisa, un utente deve disporre di una licenza di Exchange Online, ma la cassetta postale condivisa non richiede una licenza separata. Senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare la dimensione massima di 100 GB, alla cassetta postale condivisa deve essere assegnata una licenza di Exchange Online piano 2 o una licenza di Exchange Online piano 1 con una licenza per il componente aggiuntivo di archiviazione Exchange Online. Ciò consentirà anche di abilitare l'archiviazione in espansione automatica per una quantità illimitata di capacità di archiviazione dell'archivio. Analogamente, se si desidera inserire una cassetta postale condivisa sul blocco per controversia legale o assegnare un criterio di conservazione, la cassetta postale condivisa deve disporre di una licenza di Exchange Online piano 2 o di una licenza di Exchange Online piano 1 con una licenza per il componente aggiuntivo di archiviazione Exchange Online. <br/> <sup>3</sup> Le cassette postali delle risorse non richiedono una licenza. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo aumenterà la cassetta postale a 100 GB. <br/> <sup>4</sup> le cassette postali di archiviazione non sono incluse nel chiosco di Exchange Online. Tuttavia, possono essere acquistati come componente aggiuntivo tramite archiviazione Exchange Online. Per ulteriori informazioni, vedere [Descrizione del servizio Archiviazione Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> le cassette postali del sito sono state rimosse da Exchange Online e SharePoint online in 2017. <br/> <sup>6</sup> l'utente ha un limite di 1.000 cassette postali delle cartelle pubbliche e le dimensioni totali massime di tutte le cassette postali delle cartelle pubbliche sono 50 TB. Le cassette postali di servizio gerarchia sono limitate a 100 cassette postali delle cartelle pubbliche. <br/> <sup>7</sup> le cassette postali di archiviazione possono essere utilizzate solo per archiviare la posta per un singolo utente o entità (ad esempio, una cassetta postale condivisa) per la quale è stata applicata una licenza. L'utilizzo delle cassette postali di archiviazione come mezzo per archiviare messaggi da più utenti o entità è vietato. Ad esempio, un amministratore IT non può creare cassette postali condivise e lasciare che gli utenti le copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) con l'esplicito scopo di archiviarle. Tenere presente che una cassetta postale condivisa da molti utenti non archivia automaticamente la posta elettronica dei singoli utenti. Numerosi utenti possono accedere e inviare posta elettronica come cassetta postale condivisa. Pertanto, vengono inviati e ricevuti soltanto i messaggi di posta elettronica archiviati nella cassetta postale condivisa, *come* cassetta postale condivisa. <br/> <sup>8</sup> Se in Exchange Online è stato creato un criterio di conservazione, i messaggi verranno spostati automaticamente nella cassetta postale di archiviazione dell'utente soltanto se la cassetta postale principale dispone di una dimensione superiore a 10 MB. Il criterio di conservazione non verrà eseguito automaticamente per le cassette postali con dimensione inferiore a 10 MB. <br/> <sup>9</sup> le cassette postali condivise e delle risorse non richiedono una licenza. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo aumenterà la cassetta postale a 100 GB. <br/> <sup>10</sup> per impostazione predefinita, le cassette postali condivise dispongono di un account utente attivo associato con una password generata dal sistema (sconosciuta). Per bloccare l'accesso per l'account della cassetta postale condivisa associato, vedere [Block Sign-in per l'account della cassetta postale condivisa](https://docs.microsoft.com/en-us/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

### <a name="storage-limits-across-standalone-plans"></a>Limiti di spazio di archiviazione nei piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Cassette postali degli utenti|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|Cassette postali di archiviazione<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|Unlimited<sup>2</sup>|Non disponibile<sup>5</sup>|
|Cassette postali condivise<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3, 10</sup>|50 GB<sup>3</sup>|
|Cassette postali per le risorse|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4, 10</sup>|50 GB<sup>4</sup>|
|Cassette postali delle cartelle pubbliche|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|Non disponibile|
|Cassette postali di gruppo|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Questa è la dimensione predefinita delle cassette postali per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. Non esiste un limite massimo di spazio di archiviazione per le cassette postali locali. <br/> <sup>2</sup> Inizialmente, ogni utente riceve 100 GB di memoria nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima di 100 GB. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli relativi alla disponibilità dell'archiviazione con espansione automatica. <br/> <sup>3</sup> per accedere a una cassetta postale condivisa, un utente deve disporre di una licenza di Exchange Online, ma la cassetta postale condivisa non richiede una licenza separata. Senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare la dimensione massima di 100 GB, alla cassetta postale condivisa deve essere assegnata una licenza di Exchange Online piano 2 o una licenza di Exchange Online piano 1 con una licenza per il componente aggiuntivo di archiviazione Exchange Online. Ciò consentirà anche di abilitare l'archiviazione in espansione automatica per una quantità illimitata di capacità di archiviazione dell'archivio. Analogamente, se si desidera inserire una cassetta postale condivisa sul blocco per controversia legale o assegnare un criterio di conservazione, la cassetta postale condivisa deve disporre di una licenza di Exchange Online piano 2 o di una licenza di Exchange Online piano 1 con una licenza per il componente aggiuntivo di archiviazione Exchange Online. <br/> <sup>4</sup> Le cassette postali delle risorse non richiedono una licenza. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza di Exchange Online piano 2. Questo aumenterà la cassetta postale a 100 GB. <br/> <sup>5</sup> le cassette postali di archiviazione non sono incluse nel chiosco di Exchange Online. Tuttavia, possono essere acquistati come componente aggiuntivo tramite archiviazione Exchange Online. Per ulteriori informazioni, vedere [Descrizione del servizio Archiviazione Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Questa è la dimensione predefinita delle cassette postali per le organizzazioni Microsoft Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. In Exchange Server 2013, l'utente ha un limite di 100 cassette postali per cartelle pubbliche e le dimensioni totali sono complessivamente pari a 50 TB. <br/> <sup>7</sup> in Exchange Online, l'utente ha un limite di 1.000 cassette postali delle cartelle pubbliche e le dimensioni totali massime di tutte le cassette postali delle cartelle pubbliche sono 50 TB. <br/> <sup>8</sup> le cassette postali di archiviazione possono essere utilizzate solo per archiviare la posta per un singolo utente o un'entità per la quale è stata applicata una licenza. L'utilizzo di una cassetta postale di archiviazione come mezzo per archiviare messaggi da più utenti o entità è vietato. Ad esempio, gli amministratori IT non possono creare cassette postali condivise e lasciare che gli utenti copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) una cassetta postale condivisa con l'esplicito scopo di archiviarla. <br/> <sup>9</sup> Se in Exchange Online è stato creato un criterio di conservazione, i messaggi verranno spostati automaticamente nella cassetta postale di archiviazione dell'utente soltanto se la cassetta postale principale dispone di una dimensione superiore a 10 MB. Il criterio di conservazione non verrà eseguito automaticamente per le cassette postali con dimensione inferiore a 10 MB. <br/> <sup>10</sup> le cassette postali condivise e delle risorse non richiedono l'assegnazione di una licenza. Tuttavia, senza una licenza, queste cassette postali sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza di Exchange Online piano 2. Questo aumenterà la cassetta postale a 100 GB. <br/> <sup>11</sup> per impostazione predefinita, le cassette postali condivise dispongono di un account utente attivo associato con una password generata dal sistema (sconosciuta). Per bloccare l'accesso per l'account della cassetta postale condivisa associato, vedere [Block Sign-in per l'account della cassetta postale condivisa](https://docs.microsoft.com/en-us/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

## <a name="capacity-alerts"></a>Avvisi di capacità

Exchange Online offre tre tipi di notifiche quando la capacità della cassetta postale di un utente è quasi o del tutto esaurita:

- **Avviso**: l'utente riceve un messaggio di avviso che indica che la cassetta postale sta raggiungendo il limite massimo di dimensioni. Questo avviso ha lo scopo di spingere gli utenti a eliminare la posta indesiderata.

- **Impedisci invio**: l'utente riceve un messaggio di posta elettronica di notifica di Proibisci quando viene raggiunto il limite di dimensione della cassetta postale. L'utente non potrà più inviare nuovi messaggi fino a quando non viene eliminata una quantità di posta sufficiente a riportare la cassetta postale al di sotto dei limiti di dimensione consentiti.

- **Impedisci invio/ricezione**: Exchange Online rifiuta qualsiasi posta in arrivo quando viene raggiunto il limite delle dimensioni della cassetta postale e invia un rapporto di mancato recapito al mittente. Il mittente ha la possibilità di provare a inviare di nuovo il messaggio in seguito. Per poter continuare a ricevere messaggi, l'utente deve eliminare i messaggi fino a riportare la cassetta postale al di sotto dei limiti di dimensione consentiti.

### <a name="capacity-alerts-across-office-365-options"></a>Avvisi di capacità nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Avviso|49 GB|49 GB|49 GB|98 GB|98 GB|1,96 GB|
|Invio non consentito|49,5 GB|49,5 GB|49,5 GB|99 GB|99 GB|1,98 GB|
|Invio e/o ricezione non consentiti|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>Avvisi di capacità nei piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Avviso|1,9 GB<sup>1</sup>|49 GB|98 GB|1,96 GB|
|Invio non consentito|2 GB<sup>1</sup>|49,5 GB|99 GB|1,98 GB|
|Invio e/o ricezione non consentiti|2,3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> Questo è il valore predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.

## <a name="mailbox-folder-limits"></a>Limiti cartella delle cassette postali

Tali limiti servono a delimitare, entro dimensioni note, le cassette postali che possono essere supportate in Exchange Online. L'obiettivo di tali limiti è di prevenire un numero infinito di elementi nella cassetta postale per cartella, un numero infinito di cartelle per cassetta postale o un numero infinito di cartelle pubbliche per organizzazione Exchange Online. Per scopi pratici, i limiti della cartella delle cassette postali non sono realmente limitati e sono sufficienti per supportare la maggior parte delle cassette postali di Exchange Online e in locale migrate su Exchange Online.

- **Numero massimo di messaggi per cartella delle cassette postali**: specifica il numero massimo di messaggi per una cartella della cassetta postale. Una volta raggiunto tale limite i nuovi messaggi non possono essere recapitati o salvati in una cartella.

- **Avviso per numero di messaggi per cartella delle cassette postali**: specifica il numero di messaggi che una cartella della cassetta postale può contenere prima che Exchange Online invii un messaggio di avviso al proprietario della cassetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

- **Numero massimo di messaggi per cartella nella cartella elementi ripristinabili**: specifica il numero massimo di messaggi che possono essere contenuti in ogni cartella nella cartella elementi ripristinabili. Quando una cartella supera il limite, non può archiviare nuovi messaggi. Ad esempio, se la cartella eliminazioni, presente nella cartella elementi ripristinabili, ha superato il numero massimo di messaggi e il proprietario della cassetta postale tenta di eliminare definitivamente degli elementi dalle loro cassette postali, l'eliminazione non riesce.

- **Avviso per numero di messaggi per cartella nella cartella elementi ripristinabili**: specifica il numero di messaggi che ogni cartella della cartella elementi ripristinabili può contenere prima che Exchange Online registri un evento nel registro eventi dell'applicazione.

- **Numero massimo di sottocartelle per cartella delle cassette postali**: specifica il numero massimo di sottocartelle che possono essere create in una cartella delle cassette postali. Una volta raggiunto il limite, il proprietario della cassetta postale non potrà creare una nuova sottocartella.

- **Avviso per numero di sottocartelle per cartella delle cassette postali**: specifica il numero di sottocartelle che possono essere create in una cartella delle cassette postali prima che Exchange Online invii un messaggio di avviso al proprietario della cassetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

- **Profondità massima gerarchia di cartelle**: specifica il numero massimo di livelli nella gerarchia di cartelle di una cassetta postale. Una volta raggiunto il limite, il proprietario della cassetta postale non potrà creare un altro livello nella gerarchia di cartelle della cartella delle cassette postali.

- **Avviso per la profondità della gerarchia di cartelle**: consente di specificare il numero di livelli nella gerarchia di cartelle di una cartella della cassetta postale che è possibile creare prima che Exchange Online invii un messaggio di avviso al proprietario della cassetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

- **Numero massimo di cartelle pubbliche**: consente di specificare il numero massimo di cartelle pubbliche nella gerarchia di cartelle pubbliche completa. Quando viene raggiunto questo limite, le cartelle pubbliche esistenti devono essere eliminate per poterne creare di nuove.

- **Numero massimo di sottocartelle per cartella pubblica**: specifica il numero massimo di sottocartelle che possono essere create in una cartella pubblica. È impossibile creare nuove sottocartelle in una cartella pubblica quando viene raggiunto questo limite.

- **Avviso per numero di sottocartelle per cartella pubblica**: specifica il numero di sottocartelle che possono essere create in una cartella pubblica prima che in Exchange Online venga inviato un messaggio di avviso al proprietario della cartella. Qualora quest'ultimo non esistesse, i messaggi di avviso vengono inviati agli utenti con le autorizzazioni di proprietario. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno.

### <a name="mailbox-folder-limits-across-office-365-options"></a>Limiti cartella delle cassette postali tra opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Numero massimo di messaggi per cartella di cassette postali|1 milione|1 milione|1 milione|1 milione|1 milione|1 milione|
|Avviso per numero di messaggi per cartella di cassette postali|900,000|900,000|900,000|900,000|900,000|900,000|
|Numero massimo di messaggi per cartella nella cartella Elementi ripristinabili|3 milioni|3 milioni|3 milioni|3 milioni|3 milioni|3 milioni|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (non in attesa)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (in attesa)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (non in attesa)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (in attesa)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Avviso per numero massimo di messaggi per cartella nella cartella Elementi ripristinabili|2,75 milioni|2,75 milioni|2,75 milioni|2,75 milioni|2,75 milioni|2,75 milioni|
|Numero massimo di sottocartelle per cartella delle cassette postali|10,000|10,000|10,000|10,000|10,000|10.000|
|Avviso per numero di sottocartelle per cartella di cassette postali|9000|9000|9000|9000|9000|9000|
|Massima profondità gerarchia cartella|300|300|300|300|300|300|
|Avviso per profondità della gerarchia di cartelle|250|250|250|250|250|250|
|Numero massimo di cartelle pubbliche| 500.000| 500.000| 500.000| 500.000| 500.000|Non disponibile|
|Numero massimo di sottocartelle per cartella pubblica|10,000|10.000|10.000|10.000|10,000|Non disponibile|
|Avviso per numero di sottocartelle per cartella pubblica|9000|9000|9000|9000|9000|Non disponibile|

> [!NOTE]
> <sup>1</sup> Si tratta della quota di archiviazione per la cartella Elementi ripristinabili, non la quota per l'intera cassetta postale di archiviazione. La quota di archiviazione per la cassetta postale di archivio è illimitata per gli utenti con una licenza di Exchange Online piano 2 o per gli utenti che dispongono sia di Exchange Online piano 1 che di una licenza di archiviazione di Exchange Online. Per informazioni sull'aumento della quota di Elementi ripristinabili, vedere [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> La quota di archiviazione iniziale per la cartella Elementi ripristinabili in una cassetta postale di archiviazione è di 100 GB. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima prevista per la cartella Elementi ripristinabili. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli relativi alla disponibilità dell'archiviazione con espansione automatica.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limiti cartella delle cassette postali tra piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Numero massimo di messaggi per cartella delle cassette postali|Nessun limite<sup>1</sup>|1 milione|1 milione|1 milione|
|Avviso per numero di messaggi per cartella delle cassette postali|Nessun limite|900,000|900,000|900,000|
|Numero massimo di messaggi per cartella nella cartella Elementi recuperabili|Nessun limite|3 milioni|3 milioni|3 milioni|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (non in attesa)|30 GB|30 GB|30 GB|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (in attesa)|100 GB|100 GB|100 GB|100 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (non in attesa)|30 GB|30 GB|30 GB|30 GB|
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (in attesa)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Illimitata<sup>3</sup>|Illimitata<sup>3</sup>|
|Avviso per numero massimo di messaggi per cartella nella cartella Elementi recuperabili|Nessun limite|2,75 milioni|2,75 milioni|2,75 milioni|
|Numero massimo di sottocartelle per cartella delle cassette postali|Nessun limite|1000|1000|1000|
|Avviso per numero di sottocartelle per cartella delle cassette postali|Nessun limite|900|900|900|
|Massima profondità gerarchia cartella|Nessun limite|300|300|300|
|Avviso per profondità gerarchia cartella|Nessun limite|250|250|250|
|Numero massimo di cartelle pubbliche|1,000,000|100.000|100,000|Non disponibile|
|Numero massimo di sottocartelle per cartella pubblica|N/D|1.000|1,000|Non disponibile|
|Avviso per numero di sottocartelle per cartella pubblica|N/D|900|900|Non disponibile|

> [!NOTE]
> <sup>1</sup> Microsoft consiglia di non conservare più di 1.000.000 di messaggi per ogni cartella della cassetta postale. > <br/> <sup>2</sup> Si tratta della quota di archiviazione per la cartella Elementi ripristinabili, non la quota per l'intera cassetta postale di archiviazione. La quota di archiviazione per la cassetta postale di archivio è illimitata per gli utenti con una licenza di Exchange Online piano 2 o per gli utenti che dispongono sia di Exchange Online piano 1 che di una licenza di archiviazione di Exchange Online. Per informazioni sull'aumento della quota di Elementi ripristinabili, vedere [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> La quota di archiviazione iniziale per la cartella Elementi ripristinabili in una cassetta postale di archiviazione è di 100 GB. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima prevista per la cartella Elementi ripristinabili. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli relativi alla disponibilità dell'archiviazione con espansione automatica.

## <a name="message-limits"></a>Limiti dei messaggi

I seguenti limiti sono applicati a ogni messaggio di posta elettronica.

- **Limite dimensione messaggio**: i limiti di dimensione dei messaggi sono necessari per impedire ai messaggi di grandi dimensioni di bloccare il recapito di altri messaggi e di influenzare le prestazioni del servizio per tutti gli utenti. I limiti includono gli allegati e sono validi a livello di organizzazione per tutti i messaggi (in ingresso, in uscita e interni). I messaggi che superano questo limite non verranno recapitati e il mittente riceverà un rapporto di mancato recapito (NDR). Sebbene limiti di dimensione dei messaggi possano essere configurati su valori più o meno alti o in base ai singoli utenti, gli amministratori possono creare regole di trasporto per limitare le dimensioni massime di ogni singolo allegato. Per ulteriori informazioni, vedere [Office 365 now supports larger email messages (Office 365 ora supporta messaggi di posta elettronica più grandi)](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).

    > [!NOTE]
    > Alcuni client di posta elettronica possono contenere limiti per la dimensione dei messaggi o limitare le dimensioni di un singolo file allegato a un valore inferiore al limite delle dimensioni del messaggio di Exchange Online.

- **Limite dimensione intestazione messaggio**: consente di specificare la dimensione massima di tutti i campi di intestazione del messaggio in un messaggio. Il limite corrente è 256 KB. Se la dimensione totale di tutte le intestazioni dei messaggi è superiore a 256 KB, Exchange Online rifiuterà il messaggio con errore "552 le dimensioni delle intestazioni di 5.3.4 superano le dimensioni massime fisse". La dimensione del corpo o degli allegati del messaggio non è considerata. Dato che i campi di intestazione sono testo normale, la dimensione dell'intestazione viene determinata dal numero di caratteri in ogni campo di intestazione e dal numero totale di campi di intestazione. Ciascun carattere di testo utilizza 1 byte.

- **Limite lunghezza oggetto**: il numero massimo di caratteri di testo consentito nella riga dell'oggetto di un messaggio di posta elettronica.

- **Limite file allegati**: numero massimo di allegati di file consentiti in un messaggio di posta elettronica. Anche se la dimensione totale di tutti i file allegati non supera la dimensione massima del messaggio, esiste comunque un limite sul numero di allegati consentiti nel messaggio. Tale limite viene contrallato dal limite dei messaggi a più parti.

- **Limite per la dimensione del file allegato**: dimensioni massime dei file di un singolo allegato.

    > [!NOTE]
    > Dimensione massima di un singolo file allegato. I singoli programmi client, incluso Outlook Web App, potrebbero limitare ulteriormente la dimensione degli allegati. Exchange ActiveSync non applica limiti per la dimensione degli allegati a ogni singolo allegato. È la dimensione totale di tutti gli allegati a un messaggio Exchange ActiveSync che deve essere minore del limite di dimensione dei messaggi consentita.

- **Limite dei messaggi multipart**: numero massimo di parti del corpo del messaggio consentite in un messaggio multipart MIME. Tale limite consente anche di controllare il numero massimo di file che è possibile allegare a un messaggio.

- **Limite di profondità dei messaggi incorporati**: il numero massimo di messaggi di posta elettronica inoltrati consentiti in un messaggio di posta elettronica.

### <a name="message-limits-across-office-365-options"></a>Limiti di messaggi per le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Limite per la dimensione del messaggio - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Limite per la dimensione del messaggio - OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Limite per la dimensione del messaggio - Outlook per Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Limite per la dimensione del messaggio - migrazione|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Limite per la dimensione del messaggio-Outlook per iOS e Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano Crittografia messaggi di Office 365 con nuove funzionalità)<sup>5</sup>|150 MB|150 MB |150 MB |150 MB |150 MB |150 MB|
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano una versione legacy Crittografia messaggi di Office 365)<sup>5</sup>|25 MB|25 MB |25 MB |25 MB |25 MB |25 MB|
|Lunghezza massima dell'oggetto|255 caratteri|255 caratteri|255 caratteri|255 caratteri|255 caratteri|255 caratteri|
|Limite massimo dei file allegati|250 allegati|250 allegati|250 allegati|250 allegati|250 allegati|250 allegati|
|Limite di dimensione massima dei file allegati - Outlook|150 MB |150 MB |150 MB |150 MB |150 MB |150 MB |
|Limite di dimensione massima dei file allegati - OWA <sup>6</sup>|35 MB|35 MB|35 MB|35 MB|35 MB|35 MB|
|Limite di dimensione massima dei file allegati - Outlook per Mac|150 MB |150 MB |150 MB |150 MB |150 MB |150 MB |
|Limite per la dimensione dei file allegati-Outlook per iOS e Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Limite dei messaggi a più parti|250 parti|250 parti|250 parti|250 parti|250 parti|250 parti|
|Limite di profondità del messaggio incorporato|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|

> [!NOTE]
> <sup>1</sup> la dimensione massima predefinita dei messaggi per le cassette postali di Office 365 è 25 MB. Gli amministratori di Office 365 possono specificare un limite personalizzato compreso tra 1 MB e 150 MB. Tuttavia, le dimensioni dei messaggi che è possibile inviare o ricevere dipende anche da cosa è supportato dal client o dalla soluzione di posta elettronica in uso. Per ulteriori informazioni sulla personalizzazione delle dimensioni massime consentite per i messaggi dell'organizzazione, vedere [Office 365 now supports larger email messages (Office ora supporta messaggi di posta elettronica di dimensioni maggiori)](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/). <br/> <sup>2</sup> È possibile inviare e ricevere messaggi di dimensioni fino a 150 MB tra utenti di Office 365 (dove il messaggio non lascia mai i datacenter di Office 365). I messaggi indirizzati al di fuori dei datacenter di Office 365 sono soggetti a un ulteriore aumento del 33% della codifica di traduzione, nel caso in cui le dimensioni massime dei messaggi siano di 112 MB. <br/> <sup>3</sup> In OWA i messaggi possono essere soggetti a un aumento del 33% della codifica e le dimensioni dei messaggi che è possibile inviare vengono ridotte del 25% rispetto all'impostazione configurata. Ad esempio, se si personalizzano le impostazioni per una dimensione massima dei messaggi di 100 MB, è possibile inviare messaggi di dimensioni non superiori a 75 MB. <br/> <sup>4</sup> Le dimensioni dei messaggi da spostare in Exchange Online vengono calcolate da Exchange Online. Versioni di Exchange precedenti a Exchange Server 2013 possono riportare dimensioni più piccole dell'elemento. Questo limite si applica per spostare le migrazioni di base utilizzando uno dei servizi replica delle cassette postali supportati di Exchange. Altri metodi di migrazione (completa, a fasi, IMAP, PST) e altri strumenti di terze parti dipendono dal limite per la dimensione dei messaggi generale. <br/> <sup>5</sup> Per informazioni su OME con nuove funzionalità, vedere [Configurare le nuove funzionalità di Crittografia messaggi di Office 365 basate su Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). <br/> <sup>6</sup> Non è possibile allegare un singolo file di dimensioni superiori a 35 MB. Inoltre, non è possibile allegare file le cui dimensioni superano complessivamente 35 MB. Ad esempio, se si allega un file di 34 MB, è possibile allegare solo un altro file di 1 MB.

### <a name="message-limits-across-standalone-options"></a>Limiti dei messaggi nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Limite per la dimensione del messaggio - Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Limite per la dimensione del messaggio - OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Limite per la dimensione del messaggio - Outlook per Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Limite per la dimensione del messaggio - migrazione|Non applicabile|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|Limite per la dimensione del messaggio-Outlook per iOS e Android |25 MB |33 MB |33 MB |33 MB |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano Crittografia messaggi di Office 365 con nuove funzionalità)<sup>6</sup>|150 MB |150 MB |150 MB |150 MB |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano una versione legacy Crittografia messaggi di Office 365)<sup>6</sup>|25 MB|25 MB |25 MB |25 MB|
|Lunghezza massima dell'oggetto|255 caratteri|255 caratteri|255 caratteri|255 caratteri|
|Limite massimo dei file allegati|1024 allegati<sup>4</sup>|250 allegati|250 allegati|250 allegati|
|Limite di dimensione massima dei file allegati - Outlook|35 MB<sup>4</sup>|150 MB|150 MB |150 MB |
|Limite di dimensione massima dei file allegati - OWA|35 MB<sup>4</sup>|35 MB|35 MB|35 MB|
|Limite di dimensione massima dei file allegati - Outlook per Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Limite per la dimensione dei file allegati-Outlook per iOS e Android|25 MB |33 MB|33 MB|33 MB|
|Limite dei messaggi a più parti|250 parti|250 parti|250 parti|250 parti|
|Limite di profondità del messaggio incorporato|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|30 messaggi incorporati|

> [!NOTE]
> <sup>1</sup> Gli amministratori di Office 365 possono specificare un limite personalizzato compreso tra 150 MB e 1 MB. Tuttavia, le dimensioni dei messaggi che è possibile inviare o ricevere dipende anche da cosa è supportato dal client o dalla soluzione di posta elettronica in uso. Per ulteriori informazioni sulla personalizzazione delle dimensioni massime consentite per i messaggi dell'organizzazione, vedere [Office 365 now supports larger email messages (Office ora supporta messaggi di posta elettronica di dimensioni maggiori)](https://www.microsoft.com/en-us/microsoft-365/blog/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/). <br/> <sup>2</sup> È possibile inviare e ricevere messaggi di dimensioni fino a 150 MB tra utenti di Office 365 (dove il messaggio non lascia mai i datacenter di Office 365). I messaggi indirizzati al di fuori dei datacenter di Office 365 sono soggetti a un ulteriore aumento del 33% della codifica di traduzione, nel caso in cui le dimensioni massime dei messaggi siano di 112 MB. <br/> <sup>3</sup> In OWA i messaggi possono essere soggetti a un aumento del 33% della codifica e le dimensioni dei messaggi che è possibile inviare vengono ridotte del 25% rispetto all'impostazione configurata. Ad esempio, se si personalizzano le impostazioni per una dimensione massima dei messaggi di 100 MB, è possibile inviare messaggi di dimensioni non superiori a 75 MB. <br/> <sup>4</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. <br/> <sup>5</sup> Le dimensioni dei messaggi da spostare in Exchange Online vengono calcolate da Exchange Online. Versioni di Exchange precedenti a Exchange Server 2013 possono riportare dimensioni più piccole dell'elemento. <br/> <sup>6</sup> Per informazioni su OME con nuove funzionalità, vedere [Configurare le nuove funzionalità di Crittografia messaggi di Office 365 basate su Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US).

## <a name="receiving-and-sending-limits"></a>Limiti di invio e ricezione

I limiti di invio e ricezione sono applicati come protezione dalla posta indesiderata e dall'invio in massa di messaggi contenenti worm o virus. Questi limiti consentono di proteggere l'integrità dei sistemi e di mantenere gli utenti sicuri.

### <a name="receiving-limits"></a>Limiti di ricezione

I limiti di ricezione si applicano al numero di messaggi che un utente, un gruppo o una cartella pubblica possono ricevere ogni ora. Ciò vale sia per i messaggi ricevuti da Internet che per i server locali. Quando si supera il limite di ricezione, tutte le e-mail inviate a quella cassetta postale riceveranno un rapporto di mancato recapito in cui è indicato che la cassetta postale ha superato la soglia minima di recapito. Dopo un'ora, il limite viene azzerato e la cassetta postale sarà di nuovo in grado di ricevere messaggi.

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funzionalità**|**Office 365 Business Essentials**|**Office 365 Business Premium Office**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Messaggi ricevuti|3.600 messaggi all'ora|3.600 messaggi all'ora|3.600 messaggi all'ora|3.600 messaggi all'ora|3.600 messaggi all'ora|3.600 messaggi all'ora|

### <a name="sending-limits"></a>Limiti di invio

I limiti di invio si applicano al numero di destinatari, di messaggi e di destinatari per messaggio che un utente può inviare dal proprio account Exchange Online.

> [!NOTE]
> Per i gruppi di distribuzione archiviati nella rubrica dell'organizzazione, il gruppo viene conteggiato come un unico destinatario. Per i gruppi di distribuzione archiviati nella cartella Contatti di una cassetta postale, i membri del gruppo vengono conteggiati singolarmente.

- **Limite di frequenza destinatario**: per scoraggiare il recapito di messaggi in blocco non richiesti, Exchange Online ha limiti per i destinatari che impediscono agli utenti e alle applicazioni di inviare grandi volumi di posta elettronica. Questi limiti vengono applicati per singolo utente a tutti i messaggi in uscita e interni.

    > [!NOTE]
    > Per gli utenti di Exchange Online con l'esigenza di inviare messaggi di posta commerciale in blocco legittima (ad esempio, le newsletter ai clienti) è consigliabile continuare a utilizzare provider di terze parti specializzati in tali servizi.

- **Limite destinatario**: numero massimo di destinatari consentiti nei campi a:, CC: e Ccn: per un singolo messaggio di posta elettronica.

    > [!NOTE]
    > Per quanto riguarda i limiti sul numero di destinatari, un gruppo di distribuzione memorizzato nella rubrica condivisa dell'organizzazione viene contato come un singolo destinatario. In un gruppo di distribuzione personale, ciascun destinatario viene conteggiato separatamente.

- **Limite indirizzo proxy destinatario**: il limite di indirizzi del proxy del destinatario è il numero massimo di alias (indirizzi di posta elettronica) che una cassetta postale del destinatario può avere. 

- **Limite di frequenza**messaggi: i limiti di frequenza dei messaggi determinano il numero di messaggi che un utente può inviare dal proprio account Exchange Online entro un determinato periodo di tempo. Questo limite consente di evitare il consumo di risorse di sistema da parte di un singolo mittente. Se un utente invia messaggi a una velocità che supera il limite tramite invio client SMTP, verranno rifiutati i messaggi e il client dovrà riprovare.

#### <a name="sending-limits-across-office-365-options"></a>Limiti di invio per le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Limite di frequenza destinatario<sup>1</sup>|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|10.000 destinatari al giorno|
|Limite destinatari|500 destinatari|500 destinatari|500 destinatari|500 destinatari|500 destinatari|500 destinatari|
|Limite di indirizzi proxy del destinatario|400|400|400|400|400|400|
|Limite di frequenza dei messaggi|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|

> [!NOTE]
> <sup>1</sup> dopo il raggiungimento del limite di frequenza dei destinatari, i messaggi non possono essere inviati dalla cassetta postale fino a quando il numero di destinatari inviati nelle ultime 24 ore non scende al di sotto del limite. Ad esempio, un utente invia un messaggio di posta elettronica a 5.000 destinatari alle 09:00, quindi Invia un altro messaggio a 2.500 destinatari alle 10:00 del mattino e quindi Invia un altro messaggio ai destinatari 2.500 a 11:00 AM, colpendo il limite dei messaggi 10.000. L'utente non sarà in grado di inviare nuovamente i messaggi fino a quando 09:00 il giorno successivo.

#### <a name="sending-limits-across-standalone-options"></a>Limiti di invio nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Limite numero di destinatari|Nessun limite<sup>1</sup>|10.000 destinatari al giorno<sup>2</sup>|10.000 destinatari al giorno<sup>2</sup>|10.000 destinatari al giorno<sup>2</sup>|
|Limite destinatari|500 destinatari<sup>1</sup>|500 destinatari|500 destinatari|500 destinatari|
|Limite di indirizzi proxy del destinatario|400|400|400|400|
|Limite di frequenza dei messaggi|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|30 messaggi al minuto|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.<br/>
<sup>2</sup> dopo che è stato raggiunto il limite di frequenza dei destinatari, i messaggi non possono essere inviati dalla cassetta postale fino a quando il numero di destinatari inviati nelle ultime 24 ore non scende al di sotto del limite. Ad esempio, un utente invia un messaggio di posta elettronica a 5.000 destinatari alle 09:00, quindi Invia un altro messaggio a 2.500 destinatari alle 10:00 del mattino e quindi Invia un altro messaggio ai destinatari 2.500 a 11:00 AM, colpendo il limite dei messaggi 10.000. L'utente non sarà in grado di inviare nuovamente i messaggi fino a quando 09:00 il giorno successivo.

## <a name="reporting-and-message-trace-limits"></a>Limiti relativi alla creazione di rapporti e traccia dei messaggi

Per informazioni sui limiti relativi alla creazione di rapporti e traccia dei messaggi, vedere la sezione "Disponibilità e latenza della creazione di rapporti e traccia dei messaggi" nell'articolo [Creazione di rapporti e traccia dei messaggi in Exchange Online Protection](http://go.microsoft.com/fwlink/p/?LinkId=394248).

## <a name="retention-limits"></a>Limiti di conservazione

Questi limiti controllano il periodo di tempo durante il quale è possibile accedere agli elementi presenti in cartelle specifiche nella Posta in arrivo.

- **Periodo di conservazione per la cartella Posta eliminata**: numero massimo di giorni in cui gli elementi possono rimanere nella cartella Posta eliminata prima di essere rimossi automaticamente.

- **Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata**: il numero massimo di giorni in cui gli elementi rimossi dalla cartella Posta eliminata vengono conservati prima di essere eliminati definitivamente.

- **Periodo di conservazione della cartella posta indesiderata**: il numero massimo di giorni in cui gli elementi possono rimanere nella cartella posta indesiderata prima di essere rimossi automaticamente.

### <a name="retention-limits-across-office-365-options"></a>Limiti di mantenimento nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Periodo di mantenimento per la cartella Posta eliminata|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|
|Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|14 giorni<sup>1</sup>|
|Periodo di conservazione per la cartella Posta indesiderata|30 giorni|30 giorni|30 giorni|30 giorni|30 giorni|30 giorni|

> [!NOTE]
> <sup>1</sup> questo è il valore predefinito per le organizzazioni di Office 365. Gli amministratori possono modificare questo valore di un massimo di 30 giorni per le cassette postali dell'organizzazione.

### <a name="retention-limits-across-standalone-options"></a>Limiti di mantenimento nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Periodo di mantenimento per la cartella Posta eliminata|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|Nessun limite<sup>1</sup>|
|Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata|14 giorni<sup>1</sup>|14 giorni<sup>2</sup>|14 giorni<sup>2</sup>|14 giorni<sup>2</sup>|
|Periodo di mantenimento per la cartella Posta indesiderata|2 anni<sup>1</sup>|30 giorni|30 giorni|30 giorni|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito. Gli amministratori possono modificare questo valore per l'organizzazione.<br/> <sup>2</sup> Questo è il valore predefinito per le organizzazioni di Exchange Online. Gli amministratori possono modificare questo valore di un massimo di 30 giorni per le cassette postali dell'organizzazione.

## <a name="distribution-group-limits"></a>Limiti dei gruppi di distribuzione

Questi limiti si applicano ai gruppi di distribuzione nella rubrica condivisa dell'organizzazione.

- **Numero massimo di membri del gruppo di distribuzione**: il conteggio totale dei destinatari viene determinato dopo l'espansione del gruppo di distribuzione.

- **Limitare l'invio di messaggi a gruppi di distribuzione di grandi dimensioni**: i gruppi di distribuzione che contengono il numero di membri specificati da questo limite devono essere configurati per la gestione del recapito o l'approvazione dei messaggi La gestione recapito specifica un elenco di mittenti a cui è consentito inviare messaggi al gruppo di distribuzione. L'approvazione messaggi specifica uno o più moderatori che devono approvare tutti i messaggi inviati al gruppo di distribuzione.

- **Dimensione massima dei messaggi per gruppi di distribuzione di grandi dimensioni**: se un messaggio viene inviato a 5.000 o più destinatari, la dimensione del messaggio non può superare questo limite. Se supera questo limite, il messaggio non verrà recapitato e il mittente riceverà un rapporto di mancato recapito.

### <a name="distribution-group-limits-across-office-365-options"></a>Limiti dei gruppi di distribuzione nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Numero massimo di membri del gruppo di distribuzione<sup>1</sup>|100.000 membri|100.000 membri|100.000 membri|100.000 membri|100.000 membri|100.000 membri|
|Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni.|5.000 membri o più|5.000 membri o più|5.000 membri o più|5.000 membri o più|5.000 membri o più|5.000 membri o più|
|Dimensione massima dei messaggi per i gruppi di distribuzione con 5.000 a 99.999 membri|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Dimensione massima dei messaggi per i gruppi di distribuzione con 100.000 membri|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Numero massimo di proprietari del gruppo di distribuzione|10 |10 |10 |10 |10 |10 |
|Numero massimo di gruppi che è possibile creare|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Se si utilizza Azure Active Directory DirSync, il numero massimo di membri del gruppo di distribuzione che è possibile sincronizzare da Active Directory locale ad Azure Active Directory è pari a 15.000. Se si utilizza Azure AD Connect, tale numero è pari a 50.000. <br/> <sup>2</sup> Questo limite si applica anche agli amministratori.

### <a name="distribution-group-limits-across-standalone-options"></a>Limiti dei gruppi di distribuzione nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Numero massimo di membri del gruppo di distribuzione|100.000 membri<sup>1</sup>|100.000 membri|100.000 membri|100.000 membri|
|Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni.|5.000 membri o più<sup>1</sup>|5.000 membri o più|5.000 membri o più|5.000 membri o più|
|Numero massimo di proprietari del gruppo di distribuzione|10 |10 |10 |10 |
|Numero massimo di gruppi che è possibile creare|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. <br/> <sup>2</sup> Questo limite si applica anche agli amministratori.

## <a name="journal-transport-and-inbox-rule-limits"></a>Limiti del delle regole di journal, trasporto e Posta in arrivo 

Il seguente elenco include i limiti validi per le regole del journal, quelle di trasporto (note anche come regole all'interno dell'organizzazione) e i limiti validi per le regole di Posta in arrivo. Le regole di Posta in arrivo vengono configurate da utenti singoli e applicate ai messaggi inviati e ricevuti dalla cassetta postale del singolo utente.

- **Numero massimo di regole di journal** Numero massimo di regole di journal che possono esistere nell'organizzazione.

- **Numero massimo di regole di trasporto** Numero massimo di regole che possono esistere nell'organizzazione.

- **Dimensione massima di una singola regola di trasporto** Numero massimo di caratteri che possono essere utilizzati in una singola regola di trasporto. I caratteri vengono utilizzati nelle condizioni, nelle eccezioni e nelle azioni.

- **Limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto** Numero totale di caratteri utilizzati da tutte le espressioni regolari in tutte le condizioni e le eccezioni delle regole di trasporto nell'organizzazione. È possibile avere poche regole che utilizzano espressioni regolari lunghe e complesse o molte regole che utilizzano espressioni regolari semplici.

- **Limiti di analisi per il contenuto degli allegati** Le condizioni delle regole di trasporto consentono di esaminare il contenuto degli allegati dei messaggi, ma vengono controllati solo i primi 1 MB del testo Estratto da un allegato. Questo limite di 1 MB si riferisce al testo estratto dall'allegato, non alle dimensioni dei file dell'allegato. Ad esempio, un file di 2 MB può contenere meno di 1 MB di testo, in modo che venga controllato tutto il testo.

- **Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto** Quando un messaggio è interessato da diverse regole di trasporto, è possibile aggiungere solo un numero limitato di destinatari al messaggio. Una volta raggiunto tale limite, i destinatari rimanenti non verranno aggiunti al messaggio. Non è inoltre possibile aggiungere i gruppi di distribuzione a un messaggio mediante una regola di trasporto.

- **Limiti di inoltro** Numero massimo di destinatari configurabili per una regola di Posta in arrivo o di trasporto con un'azione di reindirizzamento. Se una regola viene configurata per reindirizzare un messaggio a un numero maggiore di destinatari, la regola non verrà applicata e tutti i messaggi che soddisfano la condizione della regola non verranno reindirizzati a nessuno dei destinatari elencati nella regola.
    
- **Numero di reindirizzamenti di un messaggio** Numero di volte in cui un messaggio verrà reindirizzato, inoltrato o a cui verrà risposto automaticamente sulla base delle regole di Posta in arrivo. L'Utente A ha, ad esempio, una regola di Posta in arrivo basata sul mittente che reindirizza i messaggi all'Utente B. L'Utente B ha una regola di Posta in arrivo che inoltra i messaggi all'Utente C sulla base di parole chiave presenti nella riga dell'oggetto. Se un messaggio soddisfa entrambe queste condizioni, il messaggio viene inviato soltanto all'Utente B; non viene inoltrato all'Utente C in quanto è consentito solo un reindirizzamento. In questo caso, il messaggio viene eliminato senza inviare un rapporto di mancato recapito (NDR) all'utente B che indica che il messaggio non è stato recapitato all'utente C. È possibile utilizzare l'intestazione X-MS-Exchange-Inbox-rules-loop per determinare il numero di reindirizzamenti di un messaggio. Questa intestazione rimane anche tra i limiti dell'organizzazione di Exchange.

- **Numero di volte in cui un messaggio viene reindirizzato dalle regole di trasporto** Il numero di volte in cui un messaggio verrà reindirizzato in base alle regole di trasporto. Ad esempio, l'organizzazione di Exchange Tilt Toys dispone di una regola di trasporto per reindirizzare tutti i messaggi inviati dall'utente a all'utente B che si trova nell'organizzazione di Exchange Contoso. All'interno dell'organizzazione di Exchange Contoso è presente una regola di trasporto per reindirizzare tutti i messaggi inviati all'utente B all'utente C che si trova nell'organizzazione di Exchange A. Datum Corporation. In questo caso, il messaggio viene eliminato e un rapporto di mancato recapito (NDR) con codice di stato e rifiuto del messaggio *550 trasporto 5.7.128. Regole. RejectMessage Il numero di cicli delle regole di trasporto superato e il messaggio rifiutato* viene inviato all'utente a. È possibile utilizzare l'intestazione X-MS-Exchange-Transport-Rules-loop per determinare il numero di volte in cui un messaggio è stato reindirizzato dalle regole di trasporto. Questa intestazione rimane anche tra i limiti dell'organizzazione di Exchange.

### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Limiti delle regole di journal, trasporto e Posta in arrivo nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Numero massimo di regole di journal|50 regole|50 regole|50 regole|50 regole|50 regole|50 regole|
|Numero massimo di regole di trasporto|300 regole|300 regole|300 regole|300 regole|300 regole|300 regole|
|Dimensione massima di una singola regola di trasporto|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|Il limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|Limiti di analisi per il contenuto degli allegati|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto|100 destinatari|100 destinatari|100 destinatari|100 destinatari|100 destinatari|100 destinatari|
|Limite di inoltri|10 destinatari|10 destinatari|10 destinatari|10 destinatari|10 destinatari|10 destinatari|
|Numero di reindirizzamenti di un messaggio|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|
|Numero di volte in cui un messaggio viene reindirizzato dalle regole di trasporto|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limiti delle regole di journal, trasporto e Posta in arrivo nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Numero massimo di regole di journal|Nessun limite|50 regole|50 regole|50 regole|
|Numero massimo di regole di trasporto|Nessun limite|300 regole|300 regole|300 regole|
|Dimensione massima di una singola regola di trasporto|40 KB|8 KB|8 KB|8 KB|
|Il limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto|Nessun limite|20 KB|20 KB|20 KB|
|Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto|Nessun limite|100 destinatari|100 destinatari|100 destinatari|
|Limite di inoltri|Nessun limite|10 destinatari|10 destinatari|10 destinatari|
|Numero di reindirizzamenti di un messaggio|3 reindirizzamenti|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|
|Numero di volte in cui un messaggio viene reindirizzato dalle regole di trasporto|Nessun limite|1 reindirizzamento|1 reindirizzamento|1 reindirizzamento|

## <a name="moderation-limits"></a>Limiti di moderazione

Questi limiti controllano le impostazioni di moderazione utilizzate per l'approvazione di messaggi applicata ai gruppi di distribuzione e alle regole di trasporto.

- **Dimensione massima della cassetta postale di arbitraggio**: se la cassetta postale di arbitraggio supera questo limite, i messaggi che richiedono la moderazione vengono restituiti al mittente in un rapporto di mancato recapito (NDR).

- **Numero massimo di moderatori**: numero massimo di moderatori che è possibile assegnare a un singolo gruppo di distribuzione con moderatore o che può essere aggiunto a un messaggio utilizzando una singola regola di trasporto. Si noti che non è possibile specificare un gruppo di distribuzione come moderatore.

- **Scadenza per i messaggi in attesa di moderazione**: per impostazione predefinita, un messaggio in attesa di moderazione scade dopo due giorni. Tuttavia, l'elaborazione dei messaggi moderati scaduti viene eseguita ogni sette giorni. Ciò significa che un messaggio moderato può scadere in qualsiasi momento compreso tra due e nove giorni.

- **Velocità massima per i messaggi di notifica di moderazione scaduti**: questo limite consente di impostare il numero massimo di messaggi di notifica per i messaggi con moderazione scaduta in un periodo di un'ora. Questo limite viene specificato per ogni database delle cassette postali nel centro dati.

Durante i periodi di intenso utilizzo è possibile che alcuni mittenti non ricevano messaggi di notifica per i messaggi moderati scaduti. Tuttavia, tali notifiche saranno sempre disponibili mediante i rapporti di recapito.

### <a name="moderation-limits-across-office-365-options"></a>Limiti di moderazione nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Dimensione massima della cassetta postale di arbitraggio|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|Numero massimo di moderatori|10 moderatori|10 moderatori|10 moderatori|10 moderatori|10 moderatori|10 moderatori|
|Scadenza per i messaggi in attesa di moderazione|2 giorni|2 giorni|2 giorni|2 giorni|2 giorni|2 giorni|
|Frequenza massima per i messaggi di notifica di moderazione scaduta|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|

### <a name="moderation-limits-across-standalone-options"></a>Limiti di moderazione nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Dimensione massima della cassetta postale di arbitraggio|Nessun limite<sup>1</sup>|10 GB|10 GB|10 GB|
|Numero massimo di moderatori|Nessun limite|10 moderatori|10 moderatori|10 moderatori|
|Scadenza per i messaggi in attesa di moderazione|5 giorni<sup>1</sup>|2 giorni|2 giorni|2 giorni|
|Frequenza massima per i messaggi di notifica di moderazione scaduta|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|300 notifiche di scadenza all'ora|

> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione.

## <a name="exchange-activesync-limits"></a>Limiti di Exchange ActiveSync

I seguenti limiti sono validi per Microsoft Exchange ActiveSync, un protocollo client che sincronizza i dati della cassetta postale tra dispositivi mobili ed Exchange.

- **Limite del dispositivo Exchange ActiveSync**: numero massimo di dispositivi Exchange ActiveSync per cassetta postale.

- **Limite di eliminazione del dispositivo Exchange ActiveSync**: numero massimo di dispositivi Exchange ActiveSync che un amministratore di Exchange può eliminare in un solo mese.

### <a name="exchange-activesync-limits-across-office-365-options"></a>Limiti di Exchange ActiveSync tra le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Office 365 Business Essentials**|**Office 365 Business Premium**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F1**|
|Limite di dispositivi Exchange ActiveSync|100|100|100|100|100|100|
|Limite di eliminazione di dispositivi Exchange ActiveSync|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Limiti di Exchange ActiveSync tra le opzioni autonome 

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica**|**Exchange Server 2013**|**Exchange Online piano 1**|**Exchange Online piano 2**|**Chiosco Exchange Online**|
|Limite di dispositivi Exchange ActiveSync|100|100|100|100|
|Limite di eliminazione di dispositivi Exchange ActiveSync|20|20|20|20|
