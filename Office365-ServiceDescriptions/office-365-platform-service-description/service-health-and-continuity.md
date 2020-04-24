---
title: Service health and continuity
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Gli amministratori di Microsoft possono visualizzare lo stato dei servizi e scoprire quando è pianificata la manutenzione. Le informazioni sull'integrità del servizio sono disponibili in qualsiasi momento accedendo.
ms.openlocfilehash: 2873c3a16e08ac0fd71876f365cc38be91d7effd
ms.sourcegitcommit: 54360e40fb1ef938aa8c6647eae4a8c8dda11f95
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/23/2020
ms.locfileid: "43796717"
---
# <a name="service-health-and-continuity"></a>Service health and continuity

Gli amministratori di Microsoft possono visualizzare lo stato dei servizi e scoprire quando è pianificata la manutenzione. Le informazioni sull'integrità del servizio sono disponibili in qualsiasi momento accedendo.
  
> [!NOTE]
> Se si utilizza Office 365 gestito da 21Vianet, alcune delle informazioni seguenti potrebbero non essere valide. In alternativa, consultare il [contratto di servizio di 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Visualizzazione dello stato dei servizi

La sezione Health Service consente di visualizzare lo stato corrente del servizio e i dettagli relativi alle interruzioni dei servizi e all'interruzioni del servizio. Le informazioni di manutenzione pianificate sono disponibili nel centro messaggi. Per ulteriori informazioni, vedere [Visualizzare lo stato dei servizi](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidenti di servizio

Un incidente di servizio è un evento che influisce sulla fornitura di un servizio. Gli incidenti di servizio possono essere causati da un errore hardware o software nel Data Center Microsoft, da una connessione di rete errata tra il cliente e Microsoft o da una principale sfida per il Data Center, ad esempio incendi, alluvioni o catastrofi regionali. La maggior parte degli incidenti può essere affrontata tramite le tecnologie e le soluzioni di elaborazione Microsoft e viene risolta entro breve tempo. Tuttavia, alcuni incidenti sono più gravi e possono determinare interruzioni a lungo termine.
  
Esistono due tipi di notifiche sugli orari in cui i servizi potrebbero non essere disponibili:
  
- **Eventi di manutenzione pianificata:** La manutenzione pianificata è una regolare aggiornamento dei servizi avviati da Microsoft all'infrastruttura e alle applicazioni software. Le notifiche di manutenzione pianificate informano i clienti sui lavori di servizio che potrebbero influire sulla funzionalità di un servizio Microsoft. I clienti vengono informati entro cinque giorni di anticipo rispetto a tutte le operazioni di manutenzione pianificata tramite il centro messaggi nell'interfaccia di amministrazione di Microsoft 365. Microsoft pianifica in genere la manutenzione per periodi in cui l'utilizzo del servizio è storicamente al livello più basso in base ai fusi orari regionali. 
    
- **Tempi di inattività non pianificati:** Gli incidenti di servizio non pianificati si verificano quando uno dei servizi non è disponibile o non risponde. 

### <a name="recent-worldwide-uptimes"></a>Tempi di inesecuzione recenti in tutto il mondo

Lo spostamento in un servizio cloud non implica la possibilità di perdere la capacità di sapere cosa succede. Con Office 365, non lo è. Il nostro obiettivo è di essere trasparenti nelle nostre operazioni in modo da poter monitorare lo stato del servizio, tenere conto dei problemi e avere una visione storica della disponibilità. Nelle tabelle seguenti vengono illustrati i dati di tempo di uptime recenti.

<br/>

|**2020** <br/> ||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99,98% <br/> | <br/> | <br/> |<br/> |

<br/>

|**2019** <br/> ||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99,97% <br/> | 99,97% <br/> | 99,98% <br/> | 99,98% <br/> |

<br/>

|**2018** <br/>||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.99% <br/> | 99,98% <br/> | 99,97% <br/> | 99,98% <br/> |

<br/>

|**2017** <br/> ||||
|:-----|:-----|:-----|:-----|
| **T1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.99% <br/> | 99,97% <br/> | 99,98% <br/> | 99.99% <br/> |

<br/>

## <a name="notification-policy"></a>Criteri di notifica

Quando si verifica un incidente di servizio, Microsoft riconosce che per i clienti sono essenziali comunicazioni tempestive, mirate e precise. Microsoft informa gli amministratori dell'aggiornamento del dashboard dell'integrità del servizio specifico del tenant nell'interfaccia di amministrazione di Microsoft 365. Gli aggiornamenti degli incidenti di servizio sono forniti su una cadenza oraria o, se è necessaria una cadenza diversa, verranno indicati nel messaggio di comunicazione SHD. 
  
## <a name="service-health-communication-channels"></a>Canali di comunicazione del servizio di integrità

### <a name="admin-app"></a>App di amministrazione

L'app di amministrazione per gli amministratori dell'organizzazione offre la possibilità di connettersi con lo stato del servizio Microsoft dell'organizzazione in viaggio. Gli amministratori di Microsoft avranno la possibilità di visualizzare le informazioni sull'integrità dei servizi e gli aggiornamenti dello stato di manutenzione dai propri dispositivi mobili. Per altre informazioni consultare le [Domande frequenti dell’app Amministrazione](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Management Pack di Office 365 per Microsoft System Center 2012 R2

Microsoft System Center è una piattaforma di gestione integrata che consente di gestire data center, dispositivi client e ambienti IT cloud ibridi. Gli amministratori di Microsoft che utilizzano System Center ora hanno la possibilità di importare il Management Pack di Office 365, che consente di visualizzare tutte le comunicazioni di servizio all'interno di Operations Manager in System Center. Utilizzando questo strumento è possibile accedere allo stato dei servizi sottoscritti, agli incidenti di servizio attivi e risolti e alle comunicazioni del Centro messaggi. Per ulteriori informazioni, leggere il post del blog [Nuovi strumenti di amministrazione di Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/). 
  
### <a name="office-365-service-communications-api"></a>API delle comunicazioni del servizio di Office 365

L'API di Communications Service 365 di Office consente di accedere alle comunicazioni del servizio nel modo desiderato. Con questo nuovo strumento di amministrazione, è ora possibile creare o connettere gli strumenti per le comunicazioni di servizio, in modo da semplificare la modalità di monitoraggio dell'ambiente. L'API di Communications Service consente di monitorare quanto segue nell'ambiente in uso:
  
- Integrità del servizio in tempo reale
    
- Comunicazioni del Centro messaggi
    
- Notifiche di manutenzione pianificata
    
Per ulteriori informazioni, visitare il nuovo post di Blog [degli strumenti di amministrazione](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/) . 
  
## <a name="post-incident-reviews"></a>Analisi a posteriori degli incidenti

L'impegno di Microsoft per il miglioramento continuo prevede l'analisi degli incidenti di servizio non pianificati che interessano i clienti, al fine di minimizzare la probabilità che si verifichino di nuovo in futuro. 
  
Gli incidenti di servizio non pianificati sono definiti come interruzioni del servizio multi-tenant che influiscono sull'utilizzo del servizio, come definito dai contratti di servizio, e sono stati dichiarati come tali nel dashboard di integrità dei servizi.
  
 Per gli incidenti non pianificati del servizio con impatto sui clienti, in cui si è verificato un impatto ampio e notevole su un numero elevato di organizzazioni, una revisione preliminare post-incidente (PIR) verrà recapitata tramite il dashboard dell'integrità del servizio entro 48 ore dalla risoluzione degli incidenti, seguito da un ultimo PIR entro cinque giorni lavorativi. Il report PIR dettagliato include: 
  
- Impatto sul cliente e sull'esperienza utente
    
- Data e ora di inizio e fine dell'incidente
    
- Sequenza temporale dettagliata delle misure di impatto e risoluzione
    
- Analisi e misure adottate per il miglioramento continuo delle cause
    
Per tutti gli altri incidenti del servizio, il dashboard dell'integrità del servizio fornirà un riepilogo della chiusura degli incidenti che include un riepilogo finale dell'evento, la causa iniziale preliminare, i tempi di inizio e di fine e informazioni dettagliate sui passaggi successivi. Per questa categoria di incidente di servizio, non verrà generato un report PIR. 
  
## <a name="service-continuity"></a>Continuità del servizio

Le offerte Microsoft vengono recapitate da sistemi altamente resilienti che consentono di mantenere le prestazioni del servizio di picco. Le clausole di continuità dei servizi fanno parte della progettazione del sistema. Queste disposizioni consentono a Microsoft di recuperare rapidamente gli eventi inattesi, ad esempio l'errore hardware o dell'applicazione, il danneggiamento dei dati o altri incidenti che interessano gli utenti. Queste soluzioni per la continuità del servizio vengono applicate anche in caso di interruzioni estremamente gravi, ad esempio in seguito a disastri naturali o a un incidente in un data center Microsoft che compromette il funzionamento dell'intero data center.
  
Notare che dopo il recupero da interruzioni estremamente gravi, può essere necessario prevedere un intervallo di tempo prima che per il servizio venga ripristinata la ridondanza completa del data center. Ad esempio, in caso di errore del Data Center 1, i servizi vengono ripristinati utilizzando le risorse nel Data Center 2. Tuttavia, ci potrebbe essere un intervallo di tempo prima che il Data Center 2 riprenda la continuità del servizio a causa delle risorse ripristinate nel Data Center 1 o delle nuove risorse nel Data Center 3. Il [contratto di servizio](service-level-agreement.md) Microsoft (SLA) si applica durante questo periodo di tempo. Office 365 gestito da 21Vianet è caratterizzato da un contratto di servizio differente. Per ulteriori informazioni, consultare il [sito di 21Vianet site](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Garantire la disponibilità dei dati

Microsoft assicura che i dati dei clienti saranno sempre disponibili quando necessario, tramite le seguenti funzionalità:
  
- **Ridondanza e archiviazione dei dati:** i dati dei clienti vengono archiviati in un ambiente ridondante, dotato di affidabili funzioni di protezione dei dati che assicurano disponibilità, continuità aziendale e velocità di ripristino. Sono stati implementati più livelli di ridondanza dei dati, dall'uso di dischi ridondanti alla protezione dagli errori locali dei dischi, fino alla replica completa e continua dei dati in un data center geograficamente distante. 
    
- **Monitoraggio dei dati:** I servizi Microsoft mantengono livelli elevati di prestazioni: 
    
  - **Monitoraggio dei database:**
    
  - Processi bloccati
    
  - Perdita di pacchetti
    
  - Processi in coda
    
  - Latenza delle query
    
- **Interventi di manutenzione preventiva:** la manutenzione preventiva include verifiche di coerenza dei database, compressione periodica dei dati e analisi dei log degli errori. 
    
## <a name="support"></a>Supporto

I team di sviluppo e operazioni di Microsoft sono integrati da un'organizzazione di supporto dedicata, che svolge un ruolo importante nell'offrire ai clienti la continuità aziendale. Il personale di supporto possiede una conoscenza approfondita del servizio e delle applicazioni associate, oltre a disporre di accesso diretto agli esperti Microsoft in materia di architettura, sviluppo e testing.
  
L'organizzazione di assistenza è perfettamente allineata con lo sviluppo di prodotti e operazioni, assicura tempi di risoluzione rapidi e fornisce ai clienti un canale per esprimere le proprie opinioni. Il feedback dei clienti fornisce l'input per la pianificazione, lo sviluppo e i processi operativi.
  
- **Gestione dei problemi online:** i clienti devono sapere che i loro problemi sono in fase di risoluzione e devono essere in grado di verificare la tempestività del processo di risoluzione. Microsoft 365 padmin Center Ortal fornisce un'unica interfaccia basata sul Web per il supporto. I clienti possono utilizzare il portale per aggiungere e monitorare le richieste di assistenza e per ricevere feedback dai team di supporto Microsoft. 
    
- **Supporto di self-help, supportato da un servizio continuo del personale:** Microsoft offre una vasta gamma di risorse e strumenti di self-help che possono aiutare i clienti a risolvere i problemi relativi ai servizi senza richiedere il supporto tecnico Microsoft. 
    
Prima di immettere una richiesta di assistenza, i clienti possono accedere ad articoli della Knowledge Base e domande frequenti che forniscono soluzioni immediate ai problemi più comuni. Tali risorse vengono continuamente aggiornate con le ultime informazioni, e questo aiuta a evitare ritardi fornendo soluzioni ai problemi noti. Se tuttavia si verifica un problema che richiede l'intervento di un tecnico, il personale è disponibile per fornire assistenza immediata per telefono e tramite il portale di amministrazione, 24 ore al giorno per 7 giorni la settimana.
  
Per ulteriori informazioni sul supporto, vedere l'argomento [Supporto](support.md). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani, vedere la [Descrizione del servizio piattaforma Office 365](office-365-platform-service-description.md).
  