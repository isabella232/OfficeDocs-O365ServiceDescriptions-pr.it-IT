---
title: Destinatari
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: In questo argomento sono descritte le funzionalità correlate ai destinatari incluse con Microsoft Exchange Online. Questo include le funzionalità di posta elettronica, contatti, gruppi di distribuzione, calendario e pianificazione.
ms.openlocfilehash: 32df1af7663f4a57419432b9c8a64a87ade4e857
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671780"
---
# <a name="recipients"></a>Destinatari

In questo argomento sono descritte le funzionalità correlate ai destinatari incluse con Microsoft Exchange Online. Questo include le funzionalità di posta elettronica, contatti, gruppi di distribuzione, calendario e pianificazione.
  
## <a name="email"></a>Posta elettronica

Ogni sottoscrittore di Microsoft Exchange Online riceve una cassetta postale e cassette postali speciali sono disponibili per la pianificazione delle risorse delle strutture (ad esempio, sale riunioni) e per l'accesso multiutente a indirizzi di posta elettronica condivisi. I limiti massimi di archiviazione sono validi per la maggior parte delle cassette postali e gli amministratori possono controllare le dimensioni massime consentite per le cassette postali. Notifiche e restrizioni automatiche possono segnalare all'utente quando la capacità della cassetta postale è quasi esaurita o esaurita. In Exchange Online sono inoltre disponibili diversi tipi di limitazioni per i messaggi: dimensioni e frequenza dei messaggi e limiti all'elenco dei destinatari. I dettagli di tutte le caratteristiche e di tutti i limiti sono forniti qui di seguito.
  
> [!NOTE]
> Gli indirizzi generali non sono più supportati in Exchange Online. A causa del filtro destinatario in atto per la protezione da potenziali messaggi di posta indesiderata, gli indirizzi di posta elettronica che non esistono nell'organizzazione verranno rifiutati. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Tipi di cassetta postale, limiti di archiviazione e avvisi di capacità

La quantità di spazio di archiviazione nella cassetta postale disponibile per un utente e le dimensioni predefinite della cassetta postale sono determinate dal tipo di cassetta postale e dalla licenza di sottoscrizione dell'utente. Gli amministratori possono ridurre le dimensioni massime della cassetta postale per ogni utente o a livello globale. Exchange Online fornisce inoltre tre tipi di notifiche quando la cassetta postale di un utente si avvicina o raggiunge la capacità massima.
  
Per ulteriori informazioni, vedere le sezioni "Limiti di archiviazione delle cassette postali" e "Avvisi di capacità" nell'argomento, [Exchange Online limiti](exchange-online-limits.md).
  
### <a name="mailtips"></a>Suggerimenti messaggio

Gli avvisi messaggio sono messaggi informativi automatizzati che vengono visualizzati sulla riga A: quando gli utenti compongono o inseriscono l'indirizzo in un messaggio. Lo scopo è impedire recapiti accidentali, violazioni dei criteri o rapporti di mancato recapito (NDR) non necessari. Ad esempio, gli avvisi messaggio possono generare un avviso se i mittenti provano a inviare messaggi a gruppi troppo grandi, a gruppi che contengono destinatari esterni o a un gruppo di distribuzione moderato o con restrizioni. Per ulteriori informazioni, vedere [Avviso messaggi](/exchange/clients-and-mobile-in-exchange-online/mailtips/mailtips).
  
### <a name="delegate-access"></a>Accesso delegato

Exchange Online supporta l'accesso delegato, ovvero la possibilità per gli utenti di delegare ad altri la gestione della propria posta elettronica e dei calendari. L'accesso delegato è in genere utilizzato tra manager e assistente, quando l'assistente si occupa dei messaggi di posta elettronica in arrivo del manager e ne coordina l'agenda. L'accesso delegato può essere abilitato Exchange Online utenti in Outlook o Outlook sul web o dagli amministratori nell'Exchange admin center. 
  
Per i delegati sono disponibili due tipi di accesso:
  
- **Autorizzazioni Invia per conto di** Il delegato può comporre messaggi di posta elettronica e immettere il nome dell'altra persona nel campo Da, in cui sarà visualizzato come "[nome delegato] per conto di [nome della persona]". 
    
- **Autorizzazioni Invia come** Il delegato può inviare i messaggi dalla cassetta postale dell'altra persona come se fosse il proprietario della cassetta postale. È uno scenario frequente in caso di cassetta postale condivisa da cui alcuni dipendenti inviano messaggi di posta elettronica anziché inviarli con i propri account Exchange Online. 
    
Per ulteriori informazioni su come concedere la delega di accesso, vedere [Gestire le autorizzazioni per i destinatari](/Exchange/recipients/mailbox-permissions).
  
### <a name="inbox-rules"></a>Regole di Posta in arrivo

Exchange Online consente agli utenti di creare regole di posta in arrivo che eseguono automaticamente azioni specifiche basate su criteri sui messaggi in arrivo. Ad esempio, è possibile creare una regola per spostare automaticamente tutta la posta in una cartella specifica se la posta è stata inviata a un determinato gruppo di distribuzione. Gli utenti gestiscono le regole della posta in arrivo Outlook o Outlook sul web. Gli amministratori possono bloccare determinati tipi di regole di posta in arrivo disabilitando l'inoltro e/o le risposte automatiche sul lato server. Ad esempio, disabilitando l'inoltro della posta elettronica sul lato server si impedisce agli utenti l'inoltro automatico dei messaggi di posta elettronica agli account personali. In modo analogo, disabilitando le risposte automatiche sul lato server si impedisce agli utenti esterni di utilizzare tali risposte allo scopo di identificare indirizzi di posta elettronica validi. Tali modifiche vengono effettuate tramite Windows PowerShell remoto.
  
### <a name="clutter"></a>Messaggi secondari

Messaggi secondari consente di concentrarsi sui messaggi più importanti nella posta in arrivo. Utilizza la tecnologia di apprendimento elettronico per eliminare gli elementi superflui dalla posta in arrivo, spostando i messaggi con priorità inferiore in una nuova cartella Messaggi secondari. Messaggi secondari rispetta le regole di posta elettronica esistenti di modo che, se sono state create regole per organizzare la posta elettronica, tali regole continuano a essere applicate e Messaggi secondari non agirà su tali messaggi. Messaggi secondari è disabilitata per impostazione predefinita. Per ulteriori informazioni, vedere il post su [come eliminare gli elementi superflui dalla posta in arrivo in Office 365](https://go.microsoft.com/fwlink/?linkid=2144145).
  
### <a name="connected-accounts"></a>Account connessi

La funzionalità Account connessi consente agli utenti Exchange Online di connettere account di posta elettronica esterni (ad esempio account personali) agli account di posta elettronica interni in Exchange Online e quindi di utilizzare Outlook sul web per interagire con tutti i messaggi in un'unica posizione. Gli account connessi vengono sincronizzati automaticamente all'accesso a Outlook sul web; gli utenti possono anche sincronizzare manualmente gli account da Outlook sul web. Gli amministratori possono abilitare e disabilitare questa funzionalità per determinati utenti o per tutti gli utenti nell'[Interfaccia di amministrazione di Exchange](/exchange/exchange-admin-center).
  
### <a name="inactive-mailboxes"></a>Cassette postali inattive

Exchange Online fornisce la possibilità di conservare illimitatamente i contenuti delle cassette postali eliminate. Questa funzionalità è denominata cassette postali inattive. Una cassetta postale diventa inattiva quando un'archiviazione sul posto o un blocco per controversie viene posizionato nella casetta postale prima della sua eliminazione. Di conseguenza, il contenuto della cassetta postale viene conservato illimitatamente. Gli amministratori, i responsabili della conformità e i responsabili dei record possono utilizzare la funzionalità eDiscovery in locale disponibile in Exchange Online per accedere al contenuto di una cassetta postale inattiva.
  
L'abilitazione di una cassetta postale inattiva prevede che alla cassetta venga assegnata una licenza di Exchange Online (Piano 2) o una sottoscrizione per l'archiviazione in Exchange Online in modo che sia possibile applicare alla cassetta postale l'attributo per la conservazione o un blocco per controversie prima che venga eliminata.
  
> [!IMPORTANT]
> Se non si applica la conservazione alla cassetta postale prima della sua eliminazione, il contenuto non verrà conservato e non potrà essere trovato. È possibile recuperare la cassetta postale entro 30 giorni dall'eliminazione; se non viene recuperata entro 30 giorni, la cassetta postale e il suo contenuto vengono eliminati definitivamente. 
  
Per ulteriori informazioni, vedere:
  
- [Gestire le cassette postali inattive in Exchange Online](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
    
- [Conservazione in locale e per controversia legale](/exchange/security-and-compliance/in-place-and-litigation-holds)
    
- l'articolo relativo a [eDiscovery sul posto](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)
    
## <a name="contacts-and-distribution-groups"></a>Contatti e gruppi di distribuzione

### <a name="offline-address-book"></a>Rubrica offline

La funzionalità rubrica offline fornisce uno snapshot delle informazioni di Active Directory disponibili nell'Outlook globale (GAL, Global Address List). Lo snapshot è memorizzato nella cache locale in Outlook per essere disponibile quando l'utente lavora fuori rete.
  
### <a name="address-book-policies"></a>Criteri delle rubriche

Exchange Online supporta i criteri della rubrica. I criteri della rubrica consentono di suddividere gli utenti in gruppi specifici per fornire viste personalizzate dell'Elenco indirizzi globale dell'organizzazione. Quando si crea un criterio delle rubriche, si assegna un Elenco indirizzi globale, una Rubrica offline, un elenco di sale e uno o più elenchi indirizzi al criterio. È quindi possibile assegnare il criterio rubrica agli utenti delle cassette postali, fornendo loro l'accesso a un elenco indirizzi globale personalizzato in Outlook e Outlook sul web. Gli amministratori possono configurare questi criteri utilizzando Windows PowerShell Remote. Per ulteriori informazioni sui criteri della rubrica, vedere [Rubriche in Exchange Online](/exchange/address-books/address-books).
  
### <a name="address-lists"></a>Elenchi di indirizzi

Exchange Online supporta la personalizzazione degli elenchi indirizzi e degli elenchi indirizzi globali. Un elenco indirizzi globale è una directory a livello di organizzazione di tutti gli utenti, i gruppi di distribuzione e i contatti esterni abilitati alla posta elettronica. Gli amministratori possono nascondere utenti, gruppi di distribuzione e contatti dall'elenco indirizzi globale utilizzando lo strumento di sincronizzazione della directory o Windows PowerShell.
  
### <a name="hierarchical-address-books"></a>Rubriche gerarchiche

 Le rubriche gerarchiche consentono agli utenti finali di cercare i destinatari nell'organizzazione Exchange tramite una gerarchia organizzativa. Gli amministratori possono personalizzare la rubrica in base all'anzianità e alla classifica piuttosto che all'ordine alfabetico. 
  
### <a name="distribution-groups-global"></a>Gruppi di distribuzione (globali)

Un gruppo di distribuzione (o elenco di distribuzione) è una raccolta di utenti, contatti e altri gruppi di distribuzione disponibili in una società. Per inviare messaggi a tutti i componenti di un gruppo di distribuzione, gli utenti indirizzano la posta elettronica all'alias del gruppo. I gruppi di distribuzione sono simili ai gruppi di distribuzione personali creati dai singoli utenti in Outlook, con la differenza che gli elenchi dei membri sono disponibili per la società a livello globale. I gruppi di distribuzione vengono creati dagli amministratori nell'interfaccia di amministrazione di Exchange. I gruppi possono inoltre essere sincronizzati con Exchange Online da Active Directory locale. Vengono visualizzati nell'elenco indirizzi globale in Outlook. Exchange Online supporta le funzionalità dei gruppi di distribuzione avanzate, tra cui quelle descritte qui di seguito:
  
- **Gruppi di distribuzione con restrizioni** Per impostazione predefinita, tutti possono inviare messaggi di posta elettronica a qualsiasi gruppo di distribuzione. Gli amministratori hanno la possibilità di modificare le autorizzazioni per consentire solo a utenti specifici di inviare messaggi di posta elettronica a un determinato gruppo, ad esempio per scoraggiare l'uso non appropriato di elenchi di distribuzione di grandi dimensioni. Possono anche impedire a origini esterne di inviare posta elettronica ai gruppi di distribuzione per evitare la posta indesiderata. Per i gruppi di distribuzione sincronizzati da Active Directory locale utilizzando lo strumento di sincronizzazione della directory, gli attributi della restrizione sono sincronizzati automaticamente con il cloud. Per ulteriori informazioni, vedere [Gestire i gruppi di distribuzione](/Exchange/recipients/distribution-groups).
    
- **Gruppi di distribuzione dinamici** L'elenco dei membri di un gruppo di distribuzione dinamico (noto anche come elenco di distribuzione dinamico o elenco di distribuzione basato su query) viene calcolato ogni volta che un messaggio viene inviato a un gruppo. Il calcolo si basa sui filtri e sulle condizioni definiti dall'amministratore. Sono gestiti in Exchange Online tramite Windows PowerShell remoto. Per ulteriori informazioni sui gruppi di distribuzione dinamici, vedere [Gestire i gruppi di distribuzione dinamici](/Exchange/recipients/dynamic-distribution-groups/dynamic-distribution-groups).
    
    > [!IMPORTANT]
    > Lo strumento di sincronizzazione della directory di Office 365 ignora i gruppi di distribuzione dinamici in Active Directory locale e non li sincronizza con Exchange Online. Per le organizzazioni che utilizzano lo strumento di sincronizzazione della direcory, è consigliabile utilizzare una convenzione di denominazione in grado di prevenire i conflitti tra i gruppi di distribuzione regolari gestiti in locale e i gruppi di distribuzione dinamici gestiti in Exchange Online. 
  
- **Gruppi di distribuzione moderati** Gli amministratori possono selezionare un moderatore per regolare il flusso dei messaggi a un gruppo di distribuzione. Con i gruppi di distribuzione moderati, tutti possono inviare messaggi di posta elettronica all'alias del gruppo di distribuzione, ma prima che il messaggio venga recapitato ai membri del gruppo deve essere esaminato e approvato da un moderatore. Per ulteriori informazioni sulla moderazione, vedere la sezione Approvazione del messaggio in [Gestire i gruppi di distribuzione](/Exchange/recipients/distribution-groups).
    
- **Gruppi di distribuzione self-service** Gli amministratori possono consentire agli utenti di gestire la propria appartenenza ai gruppi di distribuzione da un'interfaccia basata sul Web. Gli utenti possono essere autorizzati a creare, eliminare, partecipare o abbandonare i gruppi di distribuzione. Queste funzionalità sono abilitate per impostazione predefinita per tutti gli utenti di Exchange Online. Possono essere disabilitate dagli amministratori e sarà quindi prerogativa del reparto IT gestire i gruppi di distribuzione. Gli amministratori possono anche creare criteri di denominazione per standardizzare e gestire i nomi dei gruppi di distribuzione creati dagli utenti. Ad esempio, è possibile aggiungere un prefisso o suffisso specifico al nome del gruppo di distribuzione al momento della creazione o non consentire che vengano utilizzate determinate parole nel nome del gruppo. 
    
    > [!IMPORTANT]
    > Le funzionalità self-service non sono disponibili per i gruppi di distribuzione sincronizzati da Active Directory locale a Exchange Online. Per le organizzazioni che utilizzano lo strumento di sincronizzazione della directory, è consigliabile utilizzare una convenzione di denominazione in grado di prevenire i conflitti tra i gruppi di distribuzione gestiti in locale e i gruppi di distribuzione gestiti nel cloud. 
  
### <a name="external-contacts-global"></a>Contatti esterni (globali)

Per contatto esterno si intende un record con informazioni su una persona che lavora esternamente all'organizzazione specificata. I contatti esterni sono simili ai contatti personali creati dai singoli utenti in Outlook, con la differenza che i contatti esterni sono disponibili per la società a livello globale. I contatti esterni vengono creati dagli amministratori nell'interfaccia di amministrazione di Exchange o in Windows PowerShell Remote. I contatti possono inoltre essere sincronizzati con Exchange Online da Active Directory locale. Vengono visualizzati nell'elenco indirizzi globale in Outlook.
  
Per ulteriori informazioni sui contatti esterni, vedere [Creazione di una relazione dell'organizzazione in Exchange Online.](/exchange/sharing/organization-relationships/create-an-organization-relationship).
  
## <a name="calendar-and-scheduling"></a>Calendario e pianificazione

### <a name="resource-mailboxes"></a>Cassette postali per la risorsa

Le cassette postali per le risorse (ad esempio per sale runioni e attrezzature) rappresentano le sale riunioni oppure altre strutture o risorse di una società. Gli utenti possono prenotare sale o risorse aggiungendo l'alias di posta elettronica della risorsa alle convocazioni di riunione in Outlook o Outlook sul web. Le sale riunioni e le risorse vengono visualizzate nell'elenco indirizzi globale Outlook e Outlook sul web.
  
Gli amministratori creano cassette postali delle risorse utilizzando l'interfaccia di amministrazione di Exchange o Windows PowerShell Remote. Le cassette postali possono anche essere sincronizzate con Exchange Online da Active Directory locale.
  
Per ulteriori informazioni sulle cassette postali per le risorse, vedere:
  
- [Creazione e gestione delle cassette postali della sala](/Exchange/recipients/room-mailboxes)
    
- [Gestire le cassette postali dell’attrezzatura](/Exchange/recipients/equipment-mailboxes)
    
### <a name="conference-room-management"></a>Gestione delle sale riunioni

In Exchange Online è disponibile l'Operatore Prenotazione risorse (RBA, Resource Booking Attendant), che automatizza la pianificazione delle sale riunioni e di altre risorse. Una cassetta postale per la risorsa configurata per Operatore Prenotazione risorse accetta, rifiuta o conferma le convocazioni di riunioni nell'organizzatore della riunione basato sulla disponibilità del calendario della risorsa. 
  
Gli amministratori possono personalizzare le risposte automatiche alle sale riunioni e configurare i criteri di prenotazione in Outlook sul web. Nei criteri sono inclusi l'autore della programmazione, l'ora e il giorno della programmazione, le informazioni sulla riunione visibili nel calendario della risorsa e la percentuale di conflitti di programmazione consentiti. Gli amministratori possono disabilitare Operatore Prenotazione risorse e assegnare a utenti specifici la gestione manuale delle convocazioni di riunioni.
  
Gli amministratori devono definire e gestire le impostazioni RBA mediante Windows PowerShell remoto.
  
### <a name="out-of-office-replies"></a>Risposte Fuori sede

I messaggi Fuori sede sono risposte automatiche ai messaggi in arrivo inviati da Exchange Online per conto dell'utente. Gli utenti possono pianificare i messaggi Fuori sede in anticipo, con date e ore di inizio e di fine specifiche, e configurare messaggi Fuori sede separati per destinatari interni ed esterni. Possono anche impostare messaggi Fuori sede da dispositivi mobili che supportano questa funzionalità di Exchange ActiveSync. Con l'attenzione particolare rivolta alla posta indesiderata e alle liste di distribuzione in Exchange Online, agli utenti non è consentito inviare messaggi di posta elettronica Fuori sede esterni a liste di distribuzione estese e potenziali spammer. Gli amministratori possono inoltre impedire agli utenti di inviare messaggi Fuori sede a utenti esterni tramite Windows PowerShell remoto.
  
### <a name="calendar-sharing"></a>Condivisione del calendario

Gli utenti possono condividere il calendario personale in uno dei due modi seguenti:
  
- **Condivisione calendario federata** La federazione fa riferimento all'infrastruttura di trust sottostante che supporta la condivisione federata, un metodo semplice per gli utenti di Exchange per condividere le informazioni relative al calendario e ai contatti con i destinatari in altre organizzazioni esterne federate. Sono incluse le organizzazioni di Exchange Online oppure organizzazioni di Exchange Server 2010 o Exchange Server 2013 locali. Exchange Online amministratori non devono configurare un trust con il Microsoft Federation Gateway perché questo trust è preconfigurato per tutti i clienti Exchange Online quando viene creato il servizio Microsoft. Un criterio di condivisione predefinito consente agli utenti di inviare inviti di condivisione del calendario da Outlook sul web o Outlook 2010. In Windows PowerShell remoto, gli amministratori possono disabilitare il criterio o configurare il livello dei dati del calendario relativi alla disponibilità che gli utenti possono condividere. Possono inoltre creare una relazione tra organizzazioni con un'altra organizzazione federata, che consente la visibilità tra le organizzazioni del livello desiderato di informazioni sulla disponibilità per ogni utente senza alcun invito alla condivisione da parte dei singoli utenti. Nell'ambito dei criteri di condivisione definiti dagli amministratori e/o delle relazioni tra organizzazioni, gli utenti possono definire individualmente i dettagli delle future condivisioni. 
    
- **Condivisione calendario su Internet** In Exchange Online gli utenti possono pubblicare i propri calendari utilizzando il formato iCal per l'accesso anonimo di tutti gli utenti, internamente o esternamente all'organizzazione. I destinatari possono utilizzare Exchange, una piattaforma diversa o semplicemente un browser Web. Exchange Online gli utenti possono anche sottoscrivere calendari pubblicati da altri in posizioni Internet tramite iCal. La condivisione dei calendari personali è diversa dalla condivisione dei calendari federata, che viene configurata da un amministratore e offre condivisione della disponibilità tra organizazioni. Nessun utente può pubblicare i dati del calendario in formato iCal finché l'amministratore non ha impostato e applicato un criterio di condivisione che lo consente. Gli amministratori possono disabilitare la pubblicazione e le sottoscrizioni iCal per gli utenti di un'organizzazione utilizzando Windows PowerShell remoto.
    
Per ulteriori informazioni sulla condivisione federata, vedere [Condivisione in Exchange Online](/exchange/sharing/sharing).
  
### <a name="outlook-2010-room-finder"></a>Ricerca sala di Outlook 2010

Exchange Online supporta la funzionalità Ricerca sala di Outlook 2010, che consente di catalogare le sale in appositi elenchi (ad esempio, un elenco denominato "Sale dell'edificio 5") per agevolare la ricerca di una sala nelle vicinanze durante la programmazione di una riunione. Per essere visualizzato nell'elenco delle sale, un gruppo di distribuzione deve essere appositamente contrassegnato utilizzando uno dei due metodi seguenti: 
  
- Per creare un nuovo elenco di sale, utilizzare Windows PowerShell remoto. 
    
- I gruppi di distribuzione che contengono esclusivamente sale possono essere convertiti in elenchi di sale utilizzando Windows PowerShell remoto.
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Exchange Online [descrizione del servizio.](exchange-online-service-description.md)
