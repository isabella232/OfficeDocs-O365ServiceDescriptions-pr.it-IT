---
title: Continuità e integrità del servizio
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Gli amministratori di Microsoft Office 365 possono visualizzare lo stato dei servizi e per scoprire tutto momento della pianificazione di manutenzione. Informazioni di stato del servizio sono disponibile in qualsiasi momento eseguendo l'accesso a Office 365.
ms.openlocfilehash: 5744d0f0390aee046c63309c2395e2225c4d9342
ms.sourcegitcommit: ac81ba091876af9c42828faf9f5eb989a3a2cc58
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 12/13/2018
ms.locfileid: "27258738"
---
# <a name="service-health-and-continuity"></a>Continuità e integrità del servizio

Gli amministratori di Microsoft Office 365 possono visualizzare lo stato dei servizi e per scoprire tutto momento della pianificazione di manutenzione. Informazioni di stato del servizio sono disponibile in qualsiasi momento eseguendo l'accesso a Office 365.
  
> [!NOTE]
> Se si utilizza Office 365 gestito da 21Vianet, alcune delle informazioni seguenti potrebbero non essere valide. In alternativa, consultare il [contratto di servizio di 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Visualizzazione dello stato dei servizi

La sezione dello stato del servizio di Office 365 indicato lo stato corrente del servizio e informazioni dettagliate sulle interruzioni del servizio e interruzioni. Informazioni di manutenzione pianificate sono disponibili per il centro di messaggio. Per ulteriori informazioni, vedere [visualizzare lo stato dei servizi](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidenti di servizio

Un problema di servizio è un evento che interessa il recapito di un servizio. Risolte servizio possono essere causati da un errore hardware o software nel data center Microsoft, una connessione di rete presenta tra il cliente e Microsoft o un'attività molto impegnativa centro dati principale, ad esempio incendi, da attacchi flood o calamità regionali. La maggior parte dei problemi di servizio possono essere risolti tramite soluzioni di processo e tecnologia Microsoft e vengono risolti all'interno di un breve periodo di tempo. Tuttavia, alcuni problemi di servizio sono più gravi e possono causare interruzioni termini più tempo.
  
Esistono due tipi di notifiche sui tempi quando servizi potrebbero non essere disponibili:
  
- **Gli eventi di manutenzione pianificate:** Manutenzione pianificata è aggiornamenti dei servizi Microsoft ha avviato regolari per le applicazioni software e l'infrastruttura. Notifiche di manutenzione pianificate informano lavoro servizio che potrebbe influire sulla funzionalità di un servizio di Office 365. I clienti vengono comunicati entro cinque giorni prima tutti manutenzione pianificata utilizzando il centro messaggi nel portale di amministrazione di Office 365. Microsoft in genere piani di manutenzione per orari quando uso dei servizi viene passato al relativo minimo in base a internazionali diverse aree geografiche. 
    
- **Tempi di inattività non pianificati:** gli incidenti relativi al servizio non pianificati si verificano quando uno dei servizi nella famiglia di prodotti di Office 365 non è disponibile o non risponde. 
    
## <a name="notification-policy"></a>Criteri di notifica

Quando si verifica un problema di servizio, Microsoft riconosce che tempestivo, mirati e precisi communications sono essenziali per i clienti. Microsoft informa gli amministratori di Office 365 aggiornando specifiche del tenant del servizio sanitario Dashboard (SHD) nel portale di amministrazione di Office 365. Operazioni non consentiti aggiornamenti dei servizi forniti su una frequenza oraria o, se è necessaria una frequenza diversa, sarà indicato nella registrazione di comunicazione SHD. 
  
## <a name="service-health-communication-channels"></a>Canali di comunicazione del servizio di integrità

### <a name="office-365-admin-app"></a>Applicazione Office 365 Admin

L'applicazione Amministrazione per gli amministratori tenant Office 365 offre la possibilità di connettersi con stato del servizio Office 365 dell'organizzazione in viaggio. Gli amministratori di Office 365 tenant avrà la possibilità di visualizzare servizio integrità informazioni e la manutenzione aggiornamenti dello stato dai dispositivi mobili. Per ulteriori informazioni, vedere [Domande frequenti su applicazioni di amministrazione](https://docs.microsoft.com/en-us/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Management Pack di Office 365 per Microsoft System Center 2012 R2

Microsoft System Center è una piattaforma di gestione integrata che consente di gestire centro dati, i dispositivi client e ibride cloud ambienti IT. Gli amministratori di Office 365 che utilizzano ora System Center hanno la possibilità di importare il Management Pack 365 Office che consente di visualizzare tutte le comunicazioni di servizio in Operations Manager in System Center. Con questo strumento consente di accedere allo stato dei servizi sottoscrittori, servizio attivi e risolti risolte e le comunicazioni centro messaggi. Per ulteriori informazioni, vedere post di blog [gli strumenti di amministrazione di nuovo Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) . 
  
### <a name="office-365-service-communications-api"></a>API delle comunicazioni del servizio di Office 365

L'API delle comunicazioni del servizio di Office 365 consente di accedere alle comunicazioni di servizio di Office 365 nel modo desiderato. Con questo nuovo strumento di amministrazione, è ora possibile creare gli strumenti per le comunicazioni di servizio di Office 365 o connettersi ad essi, potenzialmente semplificando il modo di monitorare l'ambiente. L'API delle comunicazioni di servizio consente di monitorare quanto segue nel proprio ambiente:
  
- Integrità del servizio in tempo reale
    
- Comunicazioni del Centro messaggi
    
- Notifiche di manutenzione pianificata
    
Per ulteriori informazioni, leggere il post del blog [Nuovi strumenti di amministrazione di Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/). 
  
## <a name="post-incident-reviews"></a>Analisi a posteriori degli incidenti

L'impegno di Microsoft per il miglioramento continuo prevede l'analisi degli incidenti di servizio non pianificati che interessano i clienti, al fine di minimizzare la probabilità che si verifichino di nuovo in futuro. 
  
Problemi di servizio non pianificato sono definiti come interruzioni del servizio multi-tenant che siano state dichiarate in quanto tali nel Dashboard di integrità del servizio e influire sull'utilizzo del servizio come definito dai contratti di servizio del servizio.
  
 Per non pianificato incidono sulla customer service risolte in cui si è verificato impatto ampia e notevole tra un numero elevato di organizzazioni, una verifica di post-incidente preliminare (PIR) devono essere recapitati tramite il Dashboard di integrità del servizio all'interno di 48 ore di evento imprevisto risoluzione, seguita da un PIR finale entro cinque giorni lavorativi. Il rapporto dettagliato PIR include: 
  
- Impatto sul cliente e sull'esperienza utente
    
- Data e ora di inizio e fine dell'incidente
    
- Sequenza temporale dettagliata delle misure impatto e la risoluzione
    
- Analisi e misure adottate per il miglioramento continuo delle cause
    
Per tutti gli altri interventi di servizio, il Dashboard di integrità del servizio fornirà un riepilogo degli eventi imprevisti chiusura incluso un riepilogo finale dell'evento causa preliminare, inizio e fine e informazioni dettagliate passaggi successivi. Per questa categoria di evento imprevisto del servizio, non verrà generato un PIR. 
  
## <a name="service-continuity"></a>Continuità del servizio

Le offerte di Microsoft Office 365 vengono rese disponibili tramite sistemi altamente resilienti utili per mantenere le prestazioni del servizio a un livello ottimale. Le disposizioni di continuità del servizio fanno parte della progettazione di Office 365. Tali disposizioni consentono a Office 365 di riprendere tempestivamente a funzionare in seguito a eventi imprevisti, quali guasti hardware o errori di applicazione, danneggiamento dei dati o altri incidenti che colpiscono gli utenti. Queste soluzioni per la continuità del servizio vengono applicate anche in caso di interruzioni estremamente gravi, ad esempio in seguito a disastri naturali o a un incidente in un data center Microsoft che compromette il funzionamento dell'intero data center.
  
Notare che dopo il recupero da interruzioni estremamente gravi, può essere necessario prevedere un intervallo di tempo prima che per il servizio venga ripristinata la ridondanza completa del data center. Ad esempio, in caso di errore del Data Center 1, i servizi vengono ripristinati utilizzando le risorse nel Data Center 2. Tuttavia, ci potrebbe essere un intervallo di tempo prima che il Data Center 2 riprenda la continuità del servizio a causa delle risorse ripristinate nel Data Center 1 o delle nuove risorse nel Data Center 3. In questa fase si applica il [Contratto di servizio](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) per Office 365. Office 365 gestito da 21Vianet è caratterizzato da un contratto di servizio differente. Per ulteriori informazioni, consultare il [sito di 21Vianet site](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Garantire la disponibilità dei dati

Microsoft assicura che i dati dei clienti saranno sempre disponibili quando necessario, tramite le seguenti funzionalità:
  
- **Ridondanza e archiviazione dei dati:** i dati dei clienti vengono archiviati in un ambiente ridondante, dotato di affidabili funzioni di protezione dei dati che assicurano disponibilità, continuità aziendale e velocità di ripristino. Sono stati implementati più livelli di ridondanza dei dati, dall'uso di dischi ridondanti alla protezione dagli errori locali dei dischi, fino alla replica completa e continua dei dati in un data center geograficamente distante. 
    
- **Monitoraggio dei dati:** i servizi di Office 365 mantengono livelli elevati delle prestazioni tramite: 
    
  - **Monitoraggio dei database:**
    
  - Processi bloccati
    
  - Perdita di pacchetti
    
  - Processi in coda
    
  - Latenza delle query
    
- **Interventi di manutenzione preventiva:** la manutenzione preventiva include verifiche di coerenza dei database, compressione periodica dei dati e analisi dei log degli errori. 
    
## <a name="support"></a>Supporto

I team di sviluppo e gestione di Office 365 sono supportati da un'organizzazione di assistenza dedicata per Office 365, che svolge un ruolo essenziale per assicurare la continuità aziendale ai clienti. Il personale di supporto possiede una conoscenza approfondita del servizio e delle applicazioni associate, oltre a disporre di accesso diretto agli esperti Microsoft in materia di architettura, sviluppo e testing.
  
L'organizzazione di assistenza è perfettamente allineata con lo sviluppo di prodotti e operazioni, assicura tempi di risoluzione rapidi e fornisce ai clienti un canale per esprimere le proprie opinioni. Il feedback dei clienti fornisce l'input per la pianificazione, lo sviluppo e i processi operativi.
  
- **Gestione dei problemi online:** i clienti devono sapere che i loro problemi sono in fase di risoluzione e devono essere in grado di verificare la tempestività del processo di risoluzione. Il portale di Office 365 fornisce una singola interfaccia basata sul Web per il supporto. I clienti possono utilizzare il portale per aggiungere e monitorare le richieste di assistenza e per ricevere feedback dai team di supporto Microsoft. 
    
- **Supporto "Self-help online", eseguito costantemente dal personale di supporto:** Office 365 offre una vasta gamma di risorse e strumenti di supporto "Self-help online" ai clienti per consentire loro di risolvere i problemi del servizio senza richiedere il supporto di Microsoft. 
    
Prima di immettere una richiesta di assistenza, i clienti possono accedere ad articoli della Knowledge Base e domande frequenti che forniscono soluzioni immediate ai problemi più comuni. Tali risorse vengono continuamente aggiornate con le ultime informazioni, e questo aiuta a evitare ritardi fornendo soluzioni ai problemi noti. Se tuttavia si verifica un problema che richiede l'intervento di un tecnico, il personale è disponibile per fornire assistenza immediata per telefono e tramite il portale di amministrazione, 24 ore al giorno per 7 giorni la settimana.
  
Per ulteriori informazioni sul supporto, vedere l'argomento [Supporto](https://technet.microsoft.com/en-us/library/office-365-support.aspx). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, vedere [Descrizione dei servizi della piattaforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

