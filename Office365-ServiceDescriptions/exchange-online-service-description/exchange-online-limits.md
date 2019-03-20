---
title: Limiti Exchange Online Limits
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 03/18/2019
ms.audience: ITPro
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
ms.openlocfilehash: ee23a4b17807d6df80d853b7b460820a020aec99
ms.sourcegitcommit: 3b1255f83c3e9314f5c891e200b8b0eccdea40d1
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/19/2019
ms.locfileid: "30641471"
---
# <a name="exchange-online-limits"></a>Limiti Exchange Online Limits

Trovare i limiti di Exchange Online per diverse aree di servizio, compresi, a titolo esemplificativo, quelli relativi a rubrica, archiviazione delle cassette postali, creazione di rapporti e traccia dei messaggi.
  
> [!NOTE]
>  Se si necessita assistenza con questa operazione o per risolvere un problema, potrebbe essere necessario trovare utili i seguenti articoli:  <br/> • [Posta elettronica](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (per informazioni su come creare e inviare messaggi di posta elettronica)  <br/> • [Messaggi di posta elettronica in Office 365 for Business-Guida per gli amministratori](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [Fix Outlook and office 365 problems with Microsoft Support and Recovery Assistant for office 365](https://diagnostics.office.com/) <br/>  • [Rapporti di mancato recapito tramite posta elettronica in Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Guida di Exchange Online](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
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
>  • I limiti applicati a un'organizzazione di Microsoft Office 365 possono variare in base al tempo di registrazione dell'organizzazione nel servizio. <br/> • Quando un limite viene modificato nei Data Center Microsoft, può essere necessario un certo tempo per applicare la modifica a tutti i clienti esistenti. <br/> • Non è possibile modificare la maggior parte di questi limiti, ma gli utenti devono essere a conoscenza di essi. <br/> • Questi limiti si applicano ai destinatari sia interni che esterni. <br/> • Per impostazione predefinita, Exchange Online Protection (EOP) protegge le cassette postali di Exchange Online. Per i limiti che si applicano alle funzionalità di EOP in Exchange Online, vedere [Limiti Exchange Online Protection](../exchange-online-protection-service-description/exchange-online-protection-limits.md). <br/> • Per informazioni sui limiti di gruppi di Office 365, vedere "come gestire i gruppi?" in informazioni [sui gruppi di Office 365](https://go.microsoft.com/fwlink/?linkid=846714). 
  
## <a name="address-book-limits"></a>Limiti della rubrica

- **Limite elenchi indirizzi** Il numero massimo di elenchi indirizzi che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013. Questo numero include gli elenchi indirizzi predefiniti in Exchange Online, quali Tutti i contatti e Tutti i gruppi. 
    
    > [!NOTE]
    > È possibile assegnare un massimo di 20 elenchi indirizzi a una singola rubrica offline (OAB). 
  
- **Limite rubrica offline** Il numero massimo di rubriche offline (OAB) che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013. 
    
- **Limite criteri delle rubriche** Il numero massimo di criteri delle rubriche (ABP) che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013. 
    
- **Elenchi indirizzi globali** Il numero massimo di elenchi indirizzi globali (GAL) che è possibile creare in un'organizzazione di Exchange Online o Exchange Server 2013. 
    
### <a name="address-book-limits-across-office-365-options"></a>Limiti della rubrica nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite elenco indirizzi  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Limite rubrica offline (OAB, offline address book)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite criteri delle rubriche (ABP, address book policies)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite elenchi indirizzi globali  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>Limiti della rubrica nei piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Limite elenco indirizzi  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Limite rubrica offline (OAB, offline address book)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite criteri delle rubriche (ABP, address book policies)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite elenchi indirizzi globali  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>Limiti di archiviazione delle cassette postali

Il volume di archiviazione delle cassette postali è determinato dal tipo di cassetta postale e dalla licenza di sottoscrizione dell'utente. Gli amministratori possono ridurre le dimensioni massime della cassetta postale per singolo utente o a livello globale.
  
> [!NOTE]
> L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a una cassetta postale di Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti. 
  
### <a name="storage-limits-across-office-365-options"></a>Limiti di spazio di archiviazione per le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Cassette postali utente  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Cassette postali di archiviazione<sup>7, 8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Numero illimitato<sup>1</sup> <br/> |Numero illimitato<sup>1</sup> <br/> |Non disponibile<sup>4</sup> <br/> |
|Cassette postali condivise  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2, 9</sup> <br/> |50 GB<sup>2, 9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|Cassette postali per la risorsa  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3, 9</sup> <br/> |50 GB<sup>3, 9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Cassette postali del sito<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Non disponibile  <br/> |
|Cassette postali delle cartelle pubbliche  <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |Non disponibile  <br/> |
|Cassette postali di gruppo  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Inizialmente, ogni utente riceve 100 GB di memoria nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima di 100 GB. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli sulla disponibilità. <br/>  <sup>2</sup> Per accedere a una cassetta postale condivisa, un utente deve disporre di una licenza di Exchange Online. Le cassette postali condivise non richiedono una licenza separata. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo aumenterà la cassetta postale a 100 GB. Se si desidera abilitare la cassetta postale di archiviazione o inserire un blocco per controversia legale su una cassetta postale condivisa, è necessaria una licenza di Exchange Online piano 2 o un Exchange Online piano 1 con licenza di archiviazione Exchange Online. Se si Abilita la cassetta postale di archiviazione e l'archiviazione automatica per una cassetta postale condivisa, l'archiviazione aggiuntiva viene aggiunta automaticamente quando viene raggiunta la capacità di archiviazione di 100 GB per la cassetta postale di archivio. <br/>  <sup>3</sup> Le cassette postali delle risorse non richiedono una licenza. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo aumenterà la cassetta postale a 100 GB. <br/>  <sup>4</sup> le cassette postali di archiviazione non sono incluse nel chiosco di Exchange Online. Tuttavia, possono essere acquistati come componente aggiuntivo tramite archiviazione Exchange Online. Per ulteriori informazioni, vedere [Descrizione del servizio Archiviazione Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/>  <sup>5</sup> Le cassette postali del sito vengono create e gestite in SharePoint Online. Per ulteriori informazioni, vedere [Preparazione per l'utilizzo delle cassette postali di sito in Office 365](http://go.microsoft.com/fwlink/p/?LinkId=299131). <br/>  <sup>6</sup> l'utente ha un limite di 1.000 cassette postali delle cartelle pubbliche e le dimensioni totali massime di tutte le cassette postali delle cartelle pubbliche sono 50 TB. Le cassette postali di servizio gerarchia sono limitate a 100 cassette postali delle cartelle pubbliche. <br/>  <sup>7</sup> le cassette postali di archiviazione possono essere utilizzate solo per archiviare la posta per un singolo utente o entità (ad esempio, una cassetta postale condivisa) per la quale è stata applicata una licenza. L'utilizzo delle cassette postali di archiviazione come mezzo per archiviare messaggi da più utenti o entità è vietato. Ad esempio, un amministratore IT non può creare cassette postali condivise e lasciare che gli utenti le copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) con l'esplicito scopo di archiviarle. Tenere presente che una cassetta postale condivisa da molti utenti non archivia automaticamente la posta elettronica dei singoli utenti. Numerosi utenti possono accedere e inviare posta elettronica come cassetta postale condivisa. Pertanto, vengono inviati e ricevuti soltanto i messaggi di posta elettronica archiviati nella cassetta postale condivisa,  *come*  cassetta postale condivisa. <br/>  <sup>8</sup> Se in Exchange Online è stato creato un criterio di conservazione, i messaggi verranno spostati automaticamente nella cassetta postale di archiviazione dell'utente soltanto se la cassetta postale principale dispone di una dimensione superiore a 10 MB. Il criterio di conservazione non verrà eseguito automaticamente per le cassette postali con dimensione inferiore a 10 MB. <br/>  <sup>9</sup> le cassette postali condivise e delle risorse non richiedono una licenza. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza E3 o E5. Questo aumenterà la cassetta postale a 100 GB. 
  
### <a name="storage-limits-across-standalone-plans"></a>Limiti di spazio di archiviazione nei piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Cassette postali degli utenti  <br/> |2 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Cassette postali di archiviazione<sup>8, 9</sup> <br/> |100 GB<sup>1</sup> <br/> |50 GB  <br/> |UnLimited<sup>2</sup> <br/> |Non disponibile<sup>5</sup> <br/> |
|Cassette postali condivise  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3, 10</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Cassette postali per le risorse  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>4</sup> <br/> |50 GB<sup>4, 10</sup> <br/> |50 GB<sup>4</sup> <br/> |
|Cassette postali delle cartelle pubbliche  <br/> |2 GB<sup>6</sup> <br/> |50 GB<sup>7</sup> <br/> |100 GB<sup>7</sup> <br/> |Non disponibile  <br/> |
|Cassette postali di gruppo  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Questa è la dimensione predefinita delle cassette postali per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. Non esiste un limite massimo di spazio di archiviazione per le cassette postali locali. <br/>  <sup>2</sup> Inizialmente, ogni utente riceve 100 GB di memoria nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima di 100 GB. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli relativi alla disponibilità dell'archiviazione con espansione automatica. <br/> <sup>3</sup> Per accedere a una cassetta postale condivisa, un utente deve avere una licenza di Exchange Online. Le cassette postali condivise non richiedono una licenza separata. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza di Exchange Online piano 2. Questo aumenterà la cassetta postale a 100 GB. Se si desidera abilitare la cassetta postale di archiviazione o inserire un blocco per controversia legale su una cassetta postale condivisa, è necessaria una licenza di Exchange Online piano 2 o un Exchange Online piano 1 con licenza di archiviazione Exchange Online. Se si Abilita la cassetta postale di archiviazione e l'archiviazione automatica per una cassetta postale condivisa, l'archiviazione aggiuntiva viene aggiunta automaticamente quando viene raggiunta la capacità di archiviazione di 100 GB per la cassetta postale di archivio. <br/> <sup>4</sup> Le cassette postali delle risorse non richiedono una licenza. Tuttavia, senza una licenza, le cassette postali condivise sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza di Exchange Online piano 2. Questo aumenterà la cassetta postale a 100 GB.  <br/>  <sup>5</sup> le cassette postali di archiviazione non sono incluse nel chiosco di Exchange Online. Tuttavia, possono essere acquistati come componente aggiuntivo tramite archiviazione Exchange Online. Per ulteriori informazioni, vedere [Descrizione del servizio Archiviazione Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).  <br/>  <sup>6</sup> Questa è la dimensione predefinita delle cassette postali per le organizzazioni Microsoft Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. In Exchange Server 2013, l'utente ha un limite di 100 cassette postali per cartelle pubbliche e le dimensioni totali sono complessivamente pari a 50 TB.  <br/>  <sup>7</sup> in Exchange Online, l'utente ha un limite di 1.000 cassette postali delle cartelle pubbliche e le dimensioni totali massime di tutte le cassette postali delle cartelle pubbliche sono 50 TB.  <br/>  <sup>8</sup> le cassette postali di archiviazione possono essere utilizzate solo per archiviare la posta per un singolo utente o un'entità per la quale è stata applicata una licenza. L'utilizzo di una cassetta postale di archiviazione come mezzo per archiviare messaggi da più utenti o entità è vietato. Ad esempio, gli amministratori IT non possono creare cassette postali condivise e lasciare che gli utenti copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) una cassetta postale condivisa con l'esplicito scopo di archiviarla.  <br/>  <sup>9</sup> Se in Exchange Online è stato creato un criterio di conservazione, i messaggi verranno spostati automaticamente nella cassetta postale di archiviazione dell'utente soltanto se la cassetta postale principale dispone di una dimensione superiore a 10 MB. Il criterio di conservazione non verrà eseguito automaticamente per le cassette postali con dimensione inferiore a 10 MB.  <br/>  <sup>10</sup> le cassette postali condivise e delle risorse non richiedono l'assegnazione di una licenza. Tuttavia, senza una licenza, queste cassette postali sono limitate a 50 GB. Per aumentare le dimensioni delle cassette postali, è necessario assegnare una licenza di Exchange Online piano 2. Questo aumenterà la cassetta postale a 100 GB. 
  
> [!NOTE]
> Una cassetta postale condivisa non è progettata per l'accesso diretto. L'account utente per la cassetta postale condivisa deve rimanere in uno **** stato disabilitato (o "disconnesso"). 
  
## <a name="capacity-alerts"></a>Avvisi di capacità

Exchange Online offre tre tipi di notifiche quando la capacità della cassetta postale di un utente è quasi o del tutto esaurita:
  
- **Avviso** L'utente riceve un avviso mediante posta elettronica con la segnalazione che la cassetta postale sta raggiungendo il limite massimo di dimensioni. Questo avviso ha lo scopo di spingere gli utenti a eliminare la posta indesiderata. 
    
- **Invio non consentito** L'utente riceve la notifica di invio non consentito quando la cassetta postale ha raggiunto il limite massimo di dimensione. L'utente non potrà più inviare nuovi messaggi fino a quando non viene eliminata una quantità di posta sufficiente a riportare la cassetta postale al di sotto dei limiti di dimensione consentiti. 
    
- **Invio e ricezione non consentiti** Exchange Online rifiuta la posta elettronica in arrivo quando la cassetta postale ha raggiunto il limite massimo di dimensioni e invia un rapporto di mancato recapito (NDR) al mittente. Il mittente ha la possibilità di provare a inviare di nuovo il messaggio in seguito. Per poter continuare a ricevere messaggi, l'utente deve eliminare i messaggi fino a riportare la cassetta postale al di sotto dei limiti di dimensione consentiti. 
    
### <a name="capacity-alerts-across-office-365-options"></a>Avvisi di capacità nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Avviso  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Invio non consentito  <br/> |49,5 GB  <br/> |49,5 GB  <br/> |49,5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1,98 GB  <br/> |
|Invio e/o ricezione non consentiti  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>Avvisi di capacità nei piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Avviso  <br/> |1,9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Invio non consentito  <br/> |2 GB<sup>1</sup> <br/> |49,5 GB  <br/> |99 GB  <br/> |1,98 GB  <br/> |
|Invio e/o ricezione non consentiti  <br/> |2,3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Questo è il valore predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. 
  
## <a name="mailbox-folder-limits"></a>Limiti cartella delle cassette postali

Tali limiti servono a delimitare, entro dimensioni note, le cassette postali che possono essere supportate in Exchange Online. L'obiettivo di tali limiti è di prevenire un numero infinito di elementi nella cassetta postale per cartella, un numero infinito di cartelle per cassetta postale o un numero infinito di cartelle pubbliche per organizzazione Exchange Online. Per scopi pratici, i limiti della cartella delle cassette postali non sono realmente limitati e sono sufficienti per supportare la maggior parte delle cassette postali di Exchange Online e in locale migrate su Exchange Online.
  
- **Numero massimo di messaggi per cartella delle cassette postali** Specifica il numero massimo di messaggi per una cartella cassetta postale. Una volta raggiunto tale limite i nuovi messaggi non possono essere recapitati o salvati in una cartella. 
    
- **Avviso numero di messaggi per cartella delle cassette postali** Specifica il numero di messaggi che una cartella cassetta postale può contenere prima che Exchange Online invii un messaggio di avviso al proprietario della casetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno. 
    
- **Numero massimo di messaggi per cartella nella cartella Elementi recuperabili** Specifica il numero massimo di messaggi che possono essere contenuti in ciascuna cartella nella cartella Elementi recuperabili. Quando una cartella supera il limite, non può archiviare nuovi messaggi. Ad esempio, se la cartella eliminazioni, presente nella cartella elementi ripristinabili, ha superato il numero massimo di messaggi e il proprietario della cassetta postale tenta di eliminare definitivamente degli elementi dalle loro cassette postali, l'eliminazione non riesce. 
    
- **Avviso per numero di messaggi per cartella nella cartella Elementi recuperabili** Specifica il numero di messaggi che ciascuna cartella, nella cartella Elementi recuperabili, può mantenere prima che Exchange Online registri un evento nel registro evento dell'applicazione. 
    
- **Numero massimo di sottocartelle per cartella delle cassette postali** Specifica il numero di sottocartelle che possono essere create nella cartella cassetta postale. Una volta raggiunto il limite, il proprietario della cassetta postale non potrà creare una nuova sottocartella. 
    
- **Avviso numero di sottocartelle per cartella delle cassette postali** Specifica il numero di sottocartelle che possono essere create in una cartella cassetta postale prima che Exchange Online invii un messaggio di avviso al proprietario della casetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno. 
    
- **Massima profondità gerarchia cartella** Specifica il numero massimo di livelli nella gerarchia della cartella di una cassetta postale. Una volta raggiunto il limite, il proprietario della cassetta postale non potrà creare un altro livello nella gerarchia di cartelle della cartella delle cassette postali. 
    
- **Avviso profondità gerarchia cartella** Specifica il numero di livelli nella gerarchia della cartella delle cassette postali che può essere creata prima che Exchange Online invii un messaggio di avviso al proprietario della cassetta postale. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno. 
    
- **Numero massimo di cartelle pubbliche** Indica il numero massimo di cartelle pubbliche nella gerarchia completa di cartelle pubbliche. Quando viene raggiunto questo limite, le cartelle pubbliche esistenti devono essere eliminate per poterne creare di nuove. 
    
- **Numero massimo di sottocartelle per cartella pubblica** Specifica il numero di sottocartelle che possono essere create in una cartella pubblica. È impossibile creare nuove sottocartelle in una cartella pubblica quando viene raggiunto questo limite. 
    
- **Avviso numero di sottocartelle per cartella pubblica** Specifica il numero di sottocartelle che possono essere create in una cartella pubblica prima che Exchange Online invii un messaggio di avviso al proprietario della cartella. Qualora quest'ultimo non esistesse, i messaggi di avviso vengono inviati agli utenti con le autorizzazioni di proprietario. Quando viene raggiunta tale quota, viene inviato un messaggio di avviso al giorno. 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Limiti cartella delle cassette postali tra opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Numero massimo di messaggi per cartella di cassette postali  <br/> |1 milione  <br/> |1 milione  <br/> |1 milione  <br/> |1 milione  <br/> |1 milione  <br/> |1 milione  <br/> |
|Avviso per numero di messaggi per cartella di cassette postali  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|Numero massimo di messaggi per cartella nella cartella Elementi ripristinabili  <br/> |3 milioni  <br/> |3 milioni  <br/> |3 milioni  <br/> |3 milioni  <br/> |3 milioni  <br/> |3 milioni  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (non in attesa)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (in attesa)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (non in attesa)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |UnLimited<sup>2</sup> <br/> |UnLimited<sup>2</sup> <br/> |30 GB  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (in attesa)  <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |UnLimited<sup>2</sup> <br/> |UnLimited<sup>2</sup> <br/> |100 GB<sup>1</sup> <br/> |
|Avviso per numero massimo di messaggi per cartella nella cartella Elementi ripristinabili  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |
|Numero massimo di sottocartelle per cartella delle cassette postali  <br/> |10,000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |
|Avviso per numero di sottocartelle per cartella di cassette postali  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|Massima profondità gerarchia cartella  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Avviso per profondità della gerarchia di cartelle  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Numero massimo di cartelle pubbliche  <br/> | 500.000  <br/> | 500.000  <br/> | 500.000  <br/> | 500.000  <br/> | 500.000  <br/> |Non disponibile  <br/> |
|Numero massimo di sottocartelle per cartella pubblica  <br/> |10,000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10,000  <br/> |Non disponibile  <br/> |
|Avviso per numero di sottocartelle per cartella pubblica  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |Non disponibile  <br/> |
   
> [!NOTE]
> <sup>1</sup> Si tratta della quota di archiviazione per la cartella Elementi ripristinabili, non la quota per l'intera cassetta postale di archiviazione. La quota di archiviazione per la cassetta postale di archivio è illimitata per gli utenti con una licenza di Exchange Online piano 2 o per gli utenti che dispongono sia di Exchange Online piano 1 che di una licenza di archiviazione di Exchange Online. Per informazioni sull'aumento della quota di Elementi ripristinabili, vedere [Increase the Recoverable Items quota for mailboxes on hold](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx). <br/> <sup>2</sup> La quota di archiviazione iniziale per la cartella Elementi ripristinabili in una cassetta postale di archiviazione è di 100 GB. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima prevista per la cartella Elementi ripristinabili. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli relativi alla disponibilità dell'archiviazione con espansione automatica. 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limiti cartella delle cassette postali tra piani autonomi

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Numero massimo di messaggi per cartella delle cassette postali  <br/> |Nessun limite<sup>1</sup> <br/> |1 milione  <br/> |1 milione  <br/> |1 milione  <br/> |
|Avviso per numero di messaggi per cartella delle cassette postali  <br/> |Nessun limite  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|Numero massimo di messaggi per cartella nella cartella Elementi recuperabili  <br/> |Nessun limite  <br/> |3 milioni  <br/> |3 milioni  <br/> |3 milioni  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (non in attesa)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale principale (in attesa)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (non in attesa)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Quota di archiviazione per la cartella Elementi ripristinabili nella cassetta postale di archiviazione (in attesa)  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |Illimitata<sup>3</sup> <br/> |Illimitata<sup>3</sup> <br/> |
|Avviso per numero massimo di messaggi per cartella nella cartella Elementi recuperabili  <br/> |Nessun limite  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |2,75 milioni  <br/> |
|Numero massimo di sottocartelle per cartella delle cassette postali  <br/> |Nessun limite  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Avviso per numero di sottocartelle per cartella delle cassette postali  <br/> |Nessun limite  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Massima profondità gerarchia cartella  <br/> |Nessun limite  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Avviso per profondità gerarchia cartella  <br/> |Nessun limite  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Numero massimo di cartelle pubbliche  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |Non disponibile  <br/> |
|Numero massimo di sottocartelle per cartella pubblica  <br/> |N/D  <br/> |1,000  <br/> |1,000  <br/> |Non disponibile  <br/> |
|Avviso per numero di sottocartelle per cartella pubblica  <br/> |N/D  <br/> |900  <br/> |900  <br/> |Non disponibile  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft consiglia di non conservare più di 1.000.000 di messaggi per ogni cartella della cassetta postale. > <br/> <sup>2</sup> Si tratta della quota di archiviazione per la cartella Elementi ripristinabili, non la quota per l'intera cassetta postale di archiviazione. La quota di archiviazione per la cassetta postale di archivio è illimitata per gli utenti con una licenza di Exchange Online piano 2 o per gli utenti che dispongono sia di Exchange Online piano 1 che di una licenza di archiviazione di Exchange Online. Per informazioni sull'aumento della quota di Elementi ripristinabili, vedere [Increase the Recoverable Items quota for mailboxes on hold](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx). <br/> <sup>3</sup> La quota di archiviazione iniziale per la cartella Elementi ripristinabili in una cassetta postale di archiviazione è di 100 GB. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima prevista per la cartella Elementi ripristinabili. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli relativi alla disponibilità dell'archiviazione con espansione automatica. 
  
## <a name="message-limits"></a>Limiti dei messaggi

I seguenti limiti sono applicati a ogni messaggio di posta elettronica.
  
- **Limite dimensione messaggio** I limiti di dimensione dei messaggi sono indispensabili per impedire ai messaggi di grandi dimensioni di bloccare il recapito di altri messaggi e compromettere le prestazioni del servizio a discapito di tutti gli utenti. I limiti includono gli allegati e sono validi a livello di organizzazione per tutti i messaggi (in ingresso, in uscita e interni). I messaggi che superano questo limite non verranno recapitati e il mittente riceverà un rapporto di mancato recapito (NDR). Sebbene limiti di dimensione dei messaggi possano essere configurati su valori più o meno alti o in base ai singoli utenti, gli amministratori possono creare regole di trasporto per limitare le dimensioni massime di ogni singolo allegato. Per ulteriori informazioni, vedere [Office 365 now supports larger email messages (Office 365 ora supporta messaggi di posta elettronica più grandi)](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).
    
    > [!NOTE]
    > Per determinati client di posta elettronica, i limiti di dimensione dei messaggi possono essere inferiori o il limite di dimensione di un singolo file allegato può essere impostato su un valore inferiore al limite stabilito in Exchange Online. 
  
- **Limite delle dimensioni dell'intestazione del messaggio** Specifica la dimensione massima di tutti i campi di intestazione del messaggio in un messaggio. Il limite corrente è 256 KB. Se la dimensione totale di tutte le intestazioni dei messaggi è superiore a 256 KB, Exchange Online rifiuterà il messaggio con errore "552 le dimensioni delle intestazioni di 5.3.4 superano le dimensioni massime fisse". La dimensione del corpo o degli allegati del messaggio non è considerata. Dato che i campi di intestazione sono testo normale, la dimensione dell'intestazione viene determinata dal numero di caratteri in ogni campo di intestazione e dal numero totale di campi di intestazione. Ciascun carattere di testo utilizza 1 byte.

- **Lunghezza massima dell'oggetto** Il numero massimo di caratteri di testo consentito nella riga dell'oggetto di un messaggio di posta elettronica. 
    
- **Limite massimo di file allegati** Numero massimo di allegati consentito in un messaggio di posta elettronica. Anche se la dimensione totale di tutti i file allegati non supera la dimensione massima del messaggio, esiste comunque un limite sul numero di allegati consentiti nel messaggio. Tale limite viene contrallato dal limite dei messaggi a più parti. 
    
- **Limite di dimensione massima dei file allegati** Dimensione massima di un singolo allegato. 
    
    > [!NOTE]
    > Dimensione massima di un singolo file allegato. I singoli programmi client, incluso Outlook Web App, potrebbero limitare ulteriormente la dimensione degli allegati. Exchange ActiveSync non applica limiti per la dimensione degli allegati a ogni singolo allegato. È la dimensione totale di tutti gli allegati a un messaggio Exchange ActiveSync che deve essere minore del limite di dimensione dei messaggi consentita. 
  
- **Limite dei messaggi a più parti** Numero massimo di parti del corpo del messaggio consentito in un messaggio a più parti MIME. Tale limite consente anche di controllare il numero massimo di file che è possibile allegare a un messaggio. 
    
- **Limite di profondità dei messaggi incorporati** Numero massimo di messaggi di posta elettronica inoltrati consentito in un messaggio di posta elettronica. 
    
### <a name="message-limits-across-office-365-options"></a>Limiti di messaggi per le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite per la dimensione del messaggio - Outlook  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Limite per la dimensione del messaggio - OWA  <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |
|Limite per la dimensione del messaggio - Outlook per Mac  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Limite per la dimensione del messaggio - migrazione  <br/> |150 MB <sup>1, 4</sup> <br/> |150 MB <sup>1, 4</sup> <br/> |150 MB <sup>1, 4</sup> <br/> |150 MB <sup>1, 4</sup> <br/> |150 MB <sup>1, 4</sup> <br/> |150 MB <sup>1, 4</sup> <br/> |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano Crittografia messaggi di Office 365 con nuove funzionalità)<sup>5</sup> <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano una versione legacy Crittografia messaggi di Office 365)<sup>5</sup> <br/> |25 MB  <br/> |25 MB   <br/> |25 MB   <br/> |25 MB   <br/> |25 MB   <br/> |25 MB  <br/> |
|Lunghezza massima dell'oggetto  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |
|Limite massimo dei file allegati  <br/> |250 allegati  <br/> |250 allegati  <br/> |250 allegati  <br/> |250 allegati  <br/> |250 allegati  <br/> |250 allegati  <br/> |
|Limite di dimensione massima dei file allegati - Outlook  <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |
|Limite di dimensione massima dei file allegati - OWA <sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Limite di dimensione massima dei file allegati - Outlook per Mac  <br/> |150 MB  <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB  <br/> |
|Limite dei messaggi a più parti  <br/> |250 parti  <br/> |250 parti  <br/> |250 parti  <br/> |250 parti  <br/> |250 parti  <br/> |250 parti  <br/> |
|Limite di profondità del messaggio incorporato  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |
   
> [!NOTE]
> <sup>1</sup> la dimensione massima predefinita dei messaggi per le cassette postali di Office 365 è 25 MB. Gli amministratori di Office 365 possono specificare un limite personalizzato compreso tra 1 MB e 150 MB. Tuttavia, le dimensioni dei messaggi che è possibile inviare o ricevere dipende anche da cosa è supportato dal client o dalla soluzione di posta elettronica in uso. Per ulteriori informazioni sulla personalizzazione delle dimensioni massime consentite per i messaggi dell'organizzazione, vedere [Office 365 now supports larger email messages (Office ora supporta messaggi di posta elettronica di dimensioni maggiori)](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/). <br/> <sup>2</sup> È possibile inviare e ricevere messaggi di dimensioni fino a 150 MB tra utenti di Office 365 (dove il messaggio non lascia mai i datacenter di Office 365). I messaggi indirizzati al di fuori dei datacenter di Office 365 sono soggetti a un ulteriore aumento del 33% della codifica di traduzione, nel caso in cui le dimensioni massime dei messaggi siano di 112 MB. <br/> <sup>3</sup> In OWA i messaggi possono essere soggetti a un aumento del 33% della codifica e le dimensioni dei messaggi che è possibile inviare vengono ridotte del 25% rispetto all'impostazione configurata. Ad esempio, se si personalizzano le impostazioni per una dimensione massima dei messaggi di 100 MB, è possibile inviare messaggi di dimensioni non superiori a 75 MB. <br/> <sup>4</sup> Le dimensioni dei messaggi da spostare in Exchange Online vengono calcolate da Exchange Online. Versioni di Exchange precedenti a Exchange Server 2013 possono riportare dimensioni più piccole dell'elemento. Questo limite si applica per spostare le migrazioni di base utilizzando uno dei servizi replica delle cassette postali supportati di Exchange. Altri metodi di migrazione (completa, a fasi, IMAP, PST) e altri strumenti di terze parti dipendono dal limite per la dimensione dei messaggi generale. <br/> <sup>5</sup> Per informazioni su OME con nuove funzionalità, vedere [Configurare le nuove funzionalità di Crittografia messaggi di Office 365 basate su Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). <br/> <sup>6</sup> Non è possibile allegare un singolo file di dimensioni superiori a 35 MB. Inoltre, non è possibile allegare file le cui dimensioni superano complessivamente 35 MB. Ad esempio, se si allega un file di 34 MB, è possibile allegare solo un altro file di 1 MB. 
  
### <a name="message-limits-across-standalone-options"></a>Limiti dei messaggi nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Limite per la dimensione del messaggio - Outlook  <br/> |10 MB<sup>4</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|Limite per la dimensione del messaggio - OWA  <br/> |10 MB<sup>4</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Limite per la dimensione del messaggio - Outlook per Mac  <br/> |10 MB<sup>4</sup> <br/> |150 MB   <br/> |150 MB   <br/> ||
|Limite per la dimensione del messaggio - migrazione  <br/> |Non applicabile  <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano Crittografia messaggi di Office 365 con nuove funzionalità)<sup>6</sup> <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |150 MB   <br/> |
|Dimensione massima per i messaggi crittografati (per gli abbonati che utilizzano una versione legacy Crittografia messaggi di Office 365)<sup>6</sup> <br/> |25 MB  <br/> |25 MB   <br/> |25 MB   <br/> |25 MB  <br/> |
|Lunghezza massima dell'oggetto  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |255 caratteri  <br/> |
|Limite massimo dei file allegati  <br/> |1024 allegati<sup>4</sup> <br/> |250 allegati  <br/> |250 allegati  <br/> |250 allegati  <br/> |
|Limite di dimensione massima dei file allegati - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB   <br/> |150 MB   <br/> |
|Limite di dimensione massima dei file allegati - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Limite di dimensione massima dei file allegati - Outlook per Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|Limite dei messaggi a più parti  <br/> |250 parti  <br/> |250 parti  <br/> |250 parti  <br/> |250 parti  <br/> |
|Limite di profondità del messaggio incorporato  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |30 messaggi incorporati  <br/> |
   
> [!NOTE]
> <sup>1</sup> Gli amministratori di Office 365 possono specificare un limite personalizzato compreso tra 150 MB e 1 MB. Tuttavia, le dimensioni dei messaggi che è possibile inviare o ricevere dipende anche da cosa è supportato dal client o dalla soluzione di posta elettronica in uso. Per ulteriori informazioni sulla personalizzazione delle dimensioni massime consentite per i messaggi dell'organizzazione, vedere [Office 365 now supports larger email messages (Office ora supporta messaggi di posta elettronica di dimensioni maggiori)](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/). <br/> <sup>2</sup> È possibile inviare e ricevere messaggi di dimensioni fino a 150 MB tra utenti di Office 365 (dove il messaggio non lascia mai i datacenter di Office 365). I messaggi indirizzati al di fuori dei datacenter di Office 365 sono soggetti a un ulteriore aumento del 33% della codifica di traduzione, nel caso in cui le dimensioni massime dei messaggi siano di 112 MB. <br/> <sup>3</sup> In OWA i messaggi possono essere soggetti a un aumento del 33% della codifica e le dimensioni dei messaggi che è possibile inviare vengono ridotte del 25% rispetto all'impostazione configurata. Ad esempio, se si personalizzano le impostazioni per una dimensione massima dei messaggi di 100 MB, è possibile inviare messaggi di dimensioni non superiori a 75 MB. <br/> <sup>4</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. <br/> <sup>5</sup> Le dimensioni dei messaggi da spostare in Exchange Online vengono calcolate da Exchange Online. Versioni di Exchange precedenti a Exchange Server 2013 possono riportare dimensioni più piccole dell'elemento. <br/> <sup>6</sup> Per informazioni su OME con nuove funzionalità, vedere [Configurare le nuove funzionalità di Crittografia messaggi di Office 365 basate su Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). 
  
## <a name="receiving-and-sending-limits"></a>Limiti di invio e ricezione

I limiti di invio e ricezione sono applicati come protezione dalla posta indesiderata e dall'invio in massa di messaggi contenenti worm o virus. Questi limiti consentono di proteggere l'integrità dei sistemi e di mantenere gli utenti sicuri.
  
### <a name="receiving-limits"></a>Limiti di ricezione

I limiti di ricezione si applicano al numero di messaggi che un utente, un gruppo o una cartella pubblica possono ricevere ogni ora. Ciò vale sia per i messaggi ricevuti da Internet sia per quelli provenienti da server locali. Quando si supera il limite di ricezione, tutte le e-mail inviate a quella cassetta postale riceveranno un rapporto di mancato recapito in cui è indicato che la cassetta postale ha superato la soglia minima di recapito. Dopo un'ora, il limite viene azzerato e la cassetta postale sarà di nuovo in grado di ricevere messaggi.
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium Office** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Messaggi ricevuti  <br/> |3.600 messaggi all'ora  <br/> |3.600 messaggi all'ora  <br/> |3.600 messaggi all'ora  <br/> |3.600 messaggi all'ora  <br/> |3.600 messaggi all'ora  <br/> |3.600 messaggi all'ora  <br/> |
   
### <a name="sending-limits"></a>Limiti di invio

I limiti di invio si applicano al numero di destinatari, di messaggi e di destinatari per messaggio che un utente può inviare dal proprio account Exchange Online.
  
> [!NOTE]
> Per i gruppi di distribuzione archiviati nella rubrica dell'organizzazione, il gruppo viene conteggiato come un unico destinatario. Per i gruppi di distribuzione archiviati nella cartella Contatti di una cassetta postale, i membri del gruppo vengono conteggiati singolarmente. 
  
- **Limite numero di destinatari** Per ridurre il recapito di messaggi in blocco non desiderati, in Exchange Online sono presenti dei limiti per il numero di destinatari che impediscono a utenti e applicazioni di inviare un gran numero di messaggi di posta elettronica. Questi limiti vengono applicati per singolo utente a tutti i messaggi in uscita e interni. 
    
    > [!NOTE]
    > Per gli utenti di Exchange Online con l'esigenza di inviare messaggi di posta commerciale in blocco legittima (ad esempio, le newsletter ai clienti) è consigliabile continuare a utilizzare provider di terze parti specializzati in tali servizi. 
  
- **Limite destinatari** Numero massimo di destinatari del messaggio che possono essere inseriti nei campi A:, Cc: e Bcc: di ciascun messaggio. 
    
    > [!NOTE]
    > Per quanto riguarda i limiti sul numero di destinatari, un gruppo di distribuzione memorizzato nella rubrica condivisa dell'organizzazione viene contato come un singolo destinatario. In un gruppo di distribuzione personale, ciascun destinatario viene conteggiato separatamente. 
  
- **Limite di frequenza dei messaggi** I limiti alla frequenza dei messaggi determinano il numero massimo di messaggi che un utente può inviare dal proprio account Exchange Online in un determinato periodo di tempo. Questo limite consente di evitare il consumo di risorse di sistema da un mittente singolo. Se un utente invia messaggi a una velocità che supera il limite tramite invio client SMTP, verranno rifiutati i messaggi e il client dovrà riprovare. 
    
#### <a name="sending-limits-across-office-365-options"></a>Limiti di invio per le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite numero di destinatari  <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |
|Limite destinatari  <br/> |500 destinatari  <br/> |500 destinatari  <br/> |500 destinatari  <br/> |500 destinatari  <br/> |500 destinatari  <br/> |500 destinatari  <br/> |
|Limite di indirizzi proxy del destinatario  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|Limite di frequenza dei messaggi  <br/> |30 messaggi al minuto  <br/> |30 messaggi al minuto  <br/> |30 messaggi al minuto  <br/> |30 messaggi al minuto  <br/> |30 messaggi al minuto  <br/> |30 messaggi al minuto  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>Limiti di invio nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Limite numero di destinatari  <br/> |Nessun limite<sup>1</sup> <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |10.000 destinatari al giorno  <br/> |
|Limite destinatari  <br/> |500 destinatari<sup>1</sup> <br/> |500 destinatari  <br/> |500 destinatari  <br/> |500 destinatari  <br/> |
|Limite di indirizzi proxy del destinatario  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. 
  
## <a name="reporting-and-message-trace-limits"></a>Limiti relativi alla creazione di rapporti e traccia dei messaggi
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

Per informazioni sui limiti relativi alla creazione di rapporti e traccia dei messaggi, vedere la sezione "Disponibilità e latenza della creazione di rapporti e traccia dei messaggi" nell'articolo [Creazione di rapporti e traccia dei messaggi in Exchange Online Protection](http://go.microsoft.com/fwlink/p/?LinkId=394248).
  
## <a name="retention-limits"></a>Limiti di conservazione
<a name="RetentionLimits"> </a>

Questi limiti controllano il periodo di tempo durante il quale è possibile accedere agli elementi presenti in cartelle specifiche nella Posta in arrivo.
  
- **Periodo di mantenimento per la cartella Posta eliminata** Numero massimo di giorni in cui gli elementi possono rimanere nella cartella Posta eliminata prima di essere rimossi automaticamente. 
    
- **Periodo di mantenimento per gli elementi rimossi dalla cartella Posta eliminata** Numero massimo di giorni prima che gli elementi rimossi dalla cartella Posta eliminata vengano eliminati in modo definitivo. 
    
- **Periodo di mantenimento per la cartella Posta indesiderata** Numero massimo di giorni in cui gli elementi possono rimanere nella cartella Posta indesiderata prima di essere rimossi automaticamente. 
    
### <a name="retention-limits-across-office-365-options"></a>Limiti di mantenimento nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Periodo di mantenimento per la cartella Posta eliminata  <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |
|Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata  <br/> |14 giorni<sup>1</sup> <br/> |14 giorni<sup>1</sup> <br/> |14 giorni<sup>1</sup> <br/> |14 giorni<sup>1</sup> <br/> |14 giorni<sup>1</sup> <br/> |14 giorni<sup>1</sup> <br/> |
|Periodo di conservazione per la cartella Posta indesiderata  <br/> |30 giorni  <br/> |30 giorni  <br/> |30 giorni  <br/> |30 giorni  <br/> |30 giorni  <br/> |30 giorni  <br/> |
   
> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito. Gli amministratori possono modificare questo valore per l'organizzazione. 
  
### <a name="retention-limits-across-standalone-options"></a>Limiti di mantenimento nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Periodo di mantenimento per la cartella Posta eliminata  <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |Nessun limite<sup>1</sup> <br/> |
|Periodo di conservazione per gli elementi rimossi dalla cartella Posta eliminata  <br/> |14 giorni<sup>1</sup> <br/> |14 giorni<sup>2</sup> <br/> |14 giorni<sup>2</sup> <br/> |14 giorni<sup>2</sup> <br/> |
|Periodo di mantenimento per la cartella Posta indesiderata  <br/> |2 anni<sup>1</sup> <br/> |30 giorni  <br/> |30 giorni  <br/> |30 giorni  <br/> |
   
> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito. Gli amministratori possono modificare questo valore per l'organizzazione.<br/> <sup>2</sup> Questo è il valore predefinito per le organizzazioni di Exchange Online. Gli amministratori possono modificare questo valore di un massimo di 30 giorni per le cassette postali dell'organizzazione. 
  
## <a name="distribution-group-limits"></a>Limiti dei gruppi di distribuzione

Questi limiti si applicano ai gruppi di distribuzione nella rubrica condivisa dell'organizzazione.
  
- **Maximum number of distribution group members** The total recipient count is determined after distribution group expansion. 
    
- **Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni** Per i gruppi di distribuzione che contengono il numero di membri specificato da questo limite è necessario che siano configurate le opzioni di gestione recapito o di approvazione messaggi. La gestione recapito specifica un elenco di mittenti a cui è consentito inviare messaggi al gruppo di distribuzione. L'approvazione messaggi specifica uno o più moderatori che devono approvare tutti i messaggi inviati al gruppo di distribuzione. 
    
- **Dimensione massima dei messaggi per gruppi di distribuzione di grandi dimensioni** Se un messaggio viene inviato a oltre 5.000 destinatari, la dimensione del messaggio non può superare questo limite. Se supera questo limite, il messaggio non verrà recapitato e il mittente riceverà un rapporto di mancato recapito. Il numero totale di destinatari viene determinato dopo l'espansione del gruppo di distribuzione. 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Limiti dei gruppi di distribuzione nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Numero massimo di membri del gruppo di distribuzione<sup>1</sup> <br/> |100.000 membri  <br/> |100.000 membri  <br/> |100.000 membri  <br/> |100.000 membri  <br/> |100.000 membri  <br/> |100.000 membri  <br/> |
|Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni.  <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |
|Dimensione massima dei messaggi per i gruppi di distribuzione con 5.000 a 99.999 membri  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Dimensione massima dei messaggi per i gruppi di distribuzione con 100.000 membri  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|Numero massimo di proprietari del gruppo di distribuzione  <br/> |10  <br/> |10  <br/> |10  <br/> |10  <br/> |10  <br/> |10  <br/> |
|Numero massimo di gruppi che è possibile creare  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Se si utilizza Azure Active Directory DirSync, il numero massimo di membri del gruppo di distribuzione che è possibile sincronizzare da Active Directory locale ad Azure Active Directory è pari a 15.000. Se si utilizza Azure AD Connect, tale numero è pari a 50.000. <br/> <sup>2</sup> Questo limite si applica anche agli amministratori. 
  
### <a name="distribution-group-limits-across-standalone-options"></a>Limiti dei gruppi di distribuzione nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Numero massimo di membri del gruppo di distribuzione  <br/> |100.000 membri<sup>1</sup> <br/> |100.000 membri  <br/> |100.000 membri  <br/> |100.000 membri  <br/> |
|Limite di invio messaggi a gruppi di distribuzione di grandi dimensioni.  <br/> |5.000 membri o più<sup>1</sup> <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |5.000 membri o più  <br/> |
|Numero massimo di proprietari del gruppo di distribuzione  <br/> |10  <br/> |10  <br/> |10  <br/> |10  <br/> |
|Numero massimo di gruppi che è possibile creare  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. <br/> <sup>2</sup> Questo limite si applica anche agli amministratori. 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>Limiti del delle regole di journal, trasporto e Posta in arrivo 

Il seguente elenco include i limiti validi per le regole del journal, quelle di trasporto (note anche come regole all'interno dell'organizzazione) e i limiti validi per le regole di Posta in arrivo. Le regole di Posta in arrivo vengono configurate da utenti singoli e applicate ai messaggi inviati e ricevuti dalla cassetta postale del singolo utente.
  
- **Numero massimo di regole di journal** Numero massimo di regole di journal che possono esistere nell'organizzazione. 
    
- **Numero massimo di regole di trasporto** Numero massimo di regole che possono esistere nell'organizzazione. 
    
- **Dimensione massima di una singola regola di trasporto** Numero massimo di caratteri che possono essere utilizzati in una singola regola di trasporto. I caratteri vengono utilizzati nelle condizioni, nelle eccezioni e nelle azioni. 
    
- **Limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto** Numero totale di caratteri utilizzati da tutte le espressioni regolari in tutte le condizioni e le eccezioni delle regole di trasporto nell'organizzazione. È possibile avere poche regole che utilizzano espressioni regolari lunghe e complesse o molte regole che utilizzano espressioni regolari semplici. 
    
- **Limiti di analisi per i contenuti allegati** Le condizioni della regola di trasporto consentono di esaminare il contenuto degli allegati dei messaggi. Tuttavia, viene controllato soltanto 1 MB di testo estratto dall'allegato. Questo limite di 1 MB fa riferimento al testo estratto dall'allegato e non alla dimensione del file allegato. Ad esempio, un file di 2 MB potrebbe includere meno di 1 MB di testo. In questo caso, tutto viene esaminato tutto il testo. 
    
- **Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto** Quando un messaggio è interessato da diverse regole di trasporto, è possibile aggiungere solo un numero limitato di destinatari al messaggio. Una volta raggiunto tale limite, i destinatari rimanenti non verranno aggiunti al messaggio. Non è inoltre possibile aggiungere i gruppi di distribuzione a un messaggio mediante una regola di trasporto. 
    
- **Limiti di inoltro** Numero massimo di destinatari configurabili per una regola di Posta in arrivo o di trasporto con un'azione di reindirizzamento. Se una regola viene configurata per reindirizzare un messaggio a un numero maggiore di destinatari, la regola non verrà applicata e tutti i messaggi che soddisfano la condizione della regola non verranno reindirizzati a nessuno dei destinatari elencati nella regola. 
    
- **Numero di reindirizzamenti di un messaggio** Numero di volte in cui un messaggio verrà reindirizzato, inoltrato o a cui verrà risposto automaticamente sulla base delle regole di Posta in arrivo. L'Utente A ha, ad esempio, una regola di Posta in arrivo basata sul mittente che reindirizza i messaggi all'Utente B. L'Utente B ha una regola di Posta in arrivo che inoltra i messaggi all'Utente C sulla base di parole chiave presenti nella riga dell'oggetto. Se un messaggio soddisfa entrambe queste condizioni, il messaggio viene inviato soltanto all'Utente B; non viene inoltrato all'Utente C in quanto è consentito solo un reindirizzamento. In questo caso, il messaggio viene interrotto senza inviare un rapporto di mancato recapito all'utente B che lo informa che il messaggio non è stato recapitato all'utente C. 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Limiti delle regole di journal, trasporto e Posta in arrivo nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Numero massimo di regole di journal  <br/> |10 regole  <br/> |10 regole  <br/> |10 regole  <br/> |10 regole  <br/> |10 regole  <br/> |10 regole  <br/> |
|Numero massimo di regole di trasporto  <br/> |300 regole  <br/> |300 regole  <br/> |300 regole  <br/> |300 regole  <br/> |300 regole  <br/> |300 regole  <br/> |
|Dimensione massima di una singola regola di trasporto  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Il limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Limiti di analisi per il contenuto degli allegati  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |
|Limite di inoltri  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |
|Numero di reindirizzamenti di un messaggio  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limiti delle regole di journal, trasporto e Posta in arrivo nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Numero massimo di regole di journal  <br/> |Nessun limite  <br/> |10 regole  <br/> |10 regole  <br/> |10 regole  <br/> |
|Numero massimo di regole di trasporto  <br/> |Nessun limite  <br/> |300 regole  <br/> |300 regole  <br/> |300 regole  <br/> |
|Dimensione massima di una singola regola di trasporto  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Il limite di caratteri per tutte le espressioni regolari utilizzate in tutte le regole di trasporto  <br/> |Nessun limite  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Numero massimo di destinatari aggiunti a un messaggio da tutte le regole di trasporto  <br/> |Nessun limite  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |100 destinatari  <br/> |
|Limite di inoltri  <br/> |Nessun limite  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |10 destinatari  <br/> |
|Numero di reindirizzamenti di un messaggio  <br/> |3 reindirizzamenti  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |1 reindirizzamento  <br/> |
  
## <a name="moderation-limits"></a>Limiti di moderazione
<a name="ModerationLimits"> </a>

Questi limiti controllano le impostazioni di moderazione utilizzate per l'approvazione di messaggi applicata ai gruppi di distribuzione e alle regole di trasporto.
  
- **Dimensione massima della cassetta postale di arbitraggio** Se la cassetta postale di arbitraggio supera questo limite, i messaggi che richiedono moderazione vengono restituiti al mittente in un rapporto di mancato recapito. 
    
- **Numero massimo di moderatori** Numero massimo di moderatori che è possibile assegnare a un singolo gruppo di distribuzione con moderatore o che è possibile aggiungere a un messaggio utilizzando una singola regola di trasporto. Si noti che non è possibile specificare un gruppo di distribuzione come moderatore. 
    
- **Scadenza dei messaggi in attesa di moderazione** Per impostazione predefinita, un messaggio in attesa di moderazione scade dopo due giorni. Tuttavia, l'elaborazione dei messaggi moderati scaduti viene eseguita ogni sette giorni. Ciò significa che un messaggio moderato può scadere in qualsiasi momento compreso tra due e nove giorni. 
    
- **Frequenza massima per i messaggi di notifica di moderazione scaduta** Questo limite imposta il numero massimo di messaggi di notifica per i messaggi moderati scaduti in un'ora. Questo limite viene specificato per ogni database delle cassette postali nel centro dati. 
    
    Durante i periodi di intenso utilizzo è possibile che alcuni mittenti non ricevano messaggi di notifica per i messaggi moderati scaduti. Tuttavia, tali notifiche saranno sempre disponibili mediante i rapporti di recapito.
    
### <a name="moderation-limits-across-office-365-options"></a>Limiti di moderazione nelle opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Dimensione massima della cassetta postale di arbitraggio  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Numero massimo di moderatori  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |
|Scadenza per i messaggi in attesa di moderazione  <br/> |2 giorni  <br/> |2 giorni  <br/> |2 giorni  <br/> |2 giorni  <br/> |2 giorni  <br/> |2 giorni  <br/> |
|Frequenza massima per i messaggi di notifica di moderazione scaduta  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>Limiti di moderazione nelle opzioni autonome

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Dimensione massima della cassetta postale di arbitraggio  <br/> |Nessun limite<sup>1</sup> <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Numero massimo di moderatori  <br/> |Nessun limite  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |10 moderatori  <br/> |
|Scadenza per i messaggi in attesa di moderazione  <br/> |5 giorni<sup>1</sup> <br/> |2 giorni  <br/> |2 giorni  <br/> |2 giorni  <br/> |
|Frequenza massima per i messaggi di notifica di moderazione scaduta  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |300 notifiche di scadenza all'ora  <br/> |
   
> [!NOTE]
> <sup>1</sup> Questo è il limite predefinito per le organizzazioni Exchange Server 2013. Gli amministratori possono modificare questo valore per l'organizzazione. 
  
## <a name="exchange-activesync-limits"></a>Limiti di Exchange ActiveSync
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

I seguenti limiti sono validi per Microsoft Exchange ActiveSync, un protocollo client che sincronizza i dati della cassetta postale tra dispositivi mobili ed Exchange. 
  
- Limite di dispositivi **Exchange ActiveSync** Il numero massimo di dispositivi Exchange ActiveSync per cassetta postale. 
    
- Limite di eliminazione di dispositivi **Exchange ActiveSync** Il numero massimi di dispositivi Exchange ActiveSync che un amministratore Exchange può eliminare in un mese. 
    
- **Limite per il file allegato di Exchange ActiveSync** La dimensione massima del file allegato che può essere inviato o ricevuto da un dispositivo Exchange ActiveSync. 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Limiti di Exchange ActiveSync tra le opzioni di Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite di dispositivi Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Limite di eliminazione di dispositivi Exchange ActiveSync  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Limite del file allegato di Exchange ActiveSync  <br/> |25 MB  <br/> |25 MB   <br/> |25 MB   <br/> |25 MB   <br/> |25 MB   <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>Limiti di Exchange ActiveSync tra le opzioni autonome 

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Exchange Server 2013** <br/> |**Exchange Online piano 1** <br/> |**Exchange Online piano 2** <br/> |**Chiosco Exchange Online** <br/> |
|Limite di dispositivi Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Limite di eliminazione di dispositivi Exchange ActiveSync  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Limite del file allegato di Exchange ActiveSync  <br/> |25 MB  <br/> |25 MB   <br/> |25 MB   <br/> |25 MB   <br/> |
