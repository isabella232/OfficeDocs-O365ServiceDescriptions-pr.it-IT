---
title: Integrità dei servizi e continuità
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Gli amministratori Microsoft possono visualizzare lo stato dei servizi e scoprire quando è pianificata la manutenzione. Le informazioni sull'integrità del servizio sono disponibili in qualsiasi momento accedendo.
ms.openlocfilehash: 1bfe01361cb2968b51ff49f2f04ec814f0c59d68d7f4f392c97d60c48f50f14f
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54701815"
---
# <a name="service-health-and-continuity"></a>Integrità dei servizi e continuità

Gli amministratori Microsoft possono visualizzare lo stato dei servizi e scoprire quando è pianificata la manutenzione. Le informazioni sull'integrità del servizio sono disponibili in qualsiasi momento accedendo.
  
> [!NOTE]
> Se si utilizza Office 365 gestito da 21Vianet, alcune delle informazioni seguenti potrebbero non essere valide. In alternativa, consultare il [contratto di servizio di 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Visualizzare lo stato dei servizi

La sezione Integrità servizio mostra lo stato corrente del servizio e i dettagli sulle interruzioni e le interruzioni del servizio. Le informazioni sulla manutenzione pianificata sono disponibili nel Centro messaggi. Per ulteriori informazioni, vedere [Visualizzare lo stato dei servizi](/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidenti di servizio

Un incidente di servizio è un evento che influisce sulla fornitura di un servizio. Gli incidenti di servizio possono essere causati da un errore hardware o software nel data center Microsoft, da una connessione di rete difettosa tra il cliente e Microsoft o da una grave sfida del data center, ad esempio incendio, alluvioni o catastrofi regionali. La maggior parte degli incidenti può essere affrontata tramite le tecnologie e le soluzioni di elaborazione Microsoft e viene risolta entro breve tempo. Tuttavia, alcuni incidenti sono più gravi e possono determinare interruzioni a lungo termine.
  
Esistono due tipi di notifiche sui casi in cui i servizi potrebbero non essere disponibili:
  
- **Eventi di manutenzione pianificata:** La manutenzione pianificata è un normale aggiornamento dei servizi avviato da Microsoft per l'infrastruttura e le applicazioni software. Le notifiche di manutenzione pianificata informano i clienti sulle attività di servizio che potrebbero influire sulla funzionalità di un servizio Microsoft. I clienti vengono avvisati non più di cinque giorni prima di tutta la manutenzione pianificata tramite il Centro messaggi interfaccia di amministrazione di Microsoft 365. Microsoft pianifica in genere la manutenzione per gli orari in cui l'utilizzo del servizio è storicamente ai minimi in base ai fusi orari regionali. 

- **Tempo di inattività non pianificato:** Gli incidenti di servizio non pianificati si verificano quando uno dei servizi non è disponibile o non risponde. 

### <a name="recent-worldwide-uptimes"></a>Tempi di attività recenti a livello mondiale

Passare a un servizio cloud non significa perdere la capacità di sapere cosa sta succedendo. Con Office 365, non lo fa. L'obiettivo è essere trasparenti nelle nostre operazioni, in modo da poter monitorare lo stato del servizio, tenere traccia dei problemi e avere una visualizzazione cronologica della disponibilità. Le tabelle seguenti mostrano i dati recenti relativi ai tempi di attività a livello mondiale.

**2021**

| D1 | Q2 | D3 | D4 |
|:-----|:-----|:-----|:-----|
| 99.97%  | 99.98% | | |

<br>

**2020**

| D1 | Q2 | D3 | D4 |
|:-----|:-----|:-----|:-----|
| 99.98% | 99.99% | 99.97% | 99.97% |

<br>

**2019**

| D1 | Q2 | D3 | D4 |
|:-----|:-----|:-----|:-----|
| 99.97% | 99.97% | 99.98% | 99.98% |

<br>

**2018**

| D1 | Q2 | D3 | D4 |
|:-----|:-----|:-----|:-----|
| 99.99% | 99.98% | 99.97% | 99.98% |

<br>

**2017**

| D1 | Q2 | D3 | D4 |
|:-----|:-----|:-----|:-----|
| 99.99% | 99.97% | 99.98% | 99.99% |

## <a name="notification-policy"></a>Criteri di notifica

Quando si verifica un incidente di servizio, Microsoft riconosce che per i clienti sono essenziali comunicazioni tempestive, mirate e precise. Microsoft invia una notifica agli amministratori aggiornando il dashboard di integrità del servizio specifico del tenant nel interfaccia di amministrazione di Microsoft 365. Gli aggiornamenti degli eventi imprevisti del servizio vengono forniti a cadenza oraria o, se è necessaria una cadenza diversa, verranno indicati nel distacco di comunicazione SHD. 
  
## <a name="service-health-communication-channels"></a>Canali di comunicazione dell'integrità dei servizi

### <a name="admin-app"></a>App di amministrazione

L'app Amministratore per gli amministratori dell'organizzazione consente di connettersi con lo stato del servizio Microsoft dell'organizzazione in viaggio. Gli amministratori Microsoft avranno la possibilità di visualizzare le informazioni sull'integrità del servizio e gli aggiornamenti dello stato di manutenzione dai dispositivi mobili. Per altre informazioni consultare le [Domande frequenti dell’app Amministrazione](/office365/admin/admin-overview/admin-mobile-app).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Management Pack di Office 365 per Microsoft System Center 2012 R2

Microsoft System Center è una piattaforma di gestione integrata che consente di gestire data center, dispositivi client e ambienti IT cloud ibridi. Gli amministratori Microsoft che usano System Center ora hanno la possibilità di importare il Management Pack di Office 365, che consente loro di visualizzare tutte le comunicazioni di servizio all'interno di Operations Manager in System Center. Utilizzando questo strumento è possibile accedere allo stato dei servizi sottoscritti, agli incidenti di servizio attivi e risolti e alle comunicazioni del Centro messaggi. Per ulteriori informazioni, ottenere [Microsoft System Center Management Pack per](https://www.microsoft.com/download/details.aspx?id=43708) Office 365 nell'Area download Microsoft. 
  
### <a name="office-365-service-communications-api"></a>API delle comunicazioni del servizio di Office 365

L'API Office 365 Service Communications consente di accedere alle comunicazioni di servizio nel modo desiderato. Con questa API puoi creare o connettere gli strumenti alle comunicazioni di servizio, semplificando potenzialmente il modo in cui monitori l'ambiente. L'API Service Communications consente di monitorare gli elementi seguenti nell'ambiente:
  
- Integrità del servizio in tempo reale

- Comunicazioni del Centro messaggi

Per ulteriori informazioni, vedere la guida di riferimento [Office 365 Service Communications API](/office/office-365-management-api/office-365-service-communications-api-reference). 
  
## <a name="post-incident-reviews"></a>Analisi a posteriori degli incidenti

L'impegno di Microsoft per il miglioramento continuo prevede l'analisi degli incidenti di servizio non pianificati che interessano i clienti, al fine di minimizzare la probabilità che si verifichino di nuovo in futuro. 
  
Gli incidenti di servizio non pianificati sono definiti come interruzioni del servizio multi-tenant che influiscono sull'utilizzo del servizio come definito dai contratti di servizio e sono stati dichiarati come tali nel dashboard di integrità del servizio.
  
 Per gli incidenti di servizio non pianificati con impatto sui clienti in cui si è verificata un'ampia e notevole influenza su un numero elevato di organizzazioni, una revisione preliminare post-incidente (PIR) verrà recapitata tramite il dashboard di integrità del servizio entro 48 ore dalla risoluzione degli incidenti, seguita da un PIR finale entro cinque giorni lavorativi. Il report PIR dettagliato include: 
  
- Impatto sul cliente e sull'esperienza utente

- Data e ora di inizio e fine dell'incidente

- Sequenza temporale dettagliata delle misure di impatto e risoluzione

- Analisi e misure adottate per il miglioramento continuo delle cause

Per tutti gli altri eventi imprevisti del servizio, il dashboard di integrità del servizio fornirà un riepilogo della chiusura degli eventi, incluso un riepilogo finale dell'evento, la causa principale preliminare, l'ora di inizio e di fine e le informazioni dettagliate sui passaggi successivi. Per questa categoria di incidente di servizio, non verrà generato un report PIR. 
  
## <a name="service-continuity"></a>Service continuity

Le offerte Microsoft sono offerte da sistemi altamente resilienti che consentono di mantenere le massime prestazioni del servizio. Le disposizioni di continuità del servizio fanno parte della progettazione del sistema. Queste disposizioni consentono a Microsoft di eseguire rapidamente il ripristino da eventi imprevisti come errori hardware o applicazioni, danneggiamenti dei dati o altri eventi imprevisti che interessano gli utenti. Queste soluzioni per la continuità del servizio vengono applicate anche in caso di interruzioni estremamente gravi, ad esempio in seguito a disastri naturali o a un incidente in un data center Microsoft che compromette il funzionamento dell'intero data center.
  
Notare che dopo il recupero da interruzioni estremamente gravi, può essere necessario prevedere un intervallo di tempo prima che per il servizio venga ripristinata la ridondanza completa del data center. Ad esempio, in caso di errore del Data Center 1, i servizi vengono ripristinati utilizzando le risorse nel Data Center 2. Tuttavia, ci potrebbe essere un intervallo di tempo prima che il Data Center 2 riprenda la continuità del servizio a causa delle risorse ripristinate nel Data Center 1 o delle nuove risorse nel Data Center 3. Il Contratto [di servizio](service-level-agreement.md) Microsoft si applica durante questo periodo. Office 365 gestito da 21Vianet è caratterizzato da un contratto di servizio differente. Per ulteriori informazioni, vedere il [sito 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Garantire la disponibilità dei dati

Microsoft assicura che i dati dei clienti saranno sempre disponibili quando necessario, tramite le seguenti funzionalità:
  
- **Ridondanza e archiviazione dei dati:** i dati dei clienti vengono archiviati in un ambiente ridondante, dotato di affidabili funzioni di protezione dei dati che assicurano disponibilità, continuità aziendale e velocità di ripristino. Sono stati implementati più livelli di ridondanza dei dati, dall'uso di dischi ridondanti alla protezione dagli errori locali dei dischi, fino alla replica completa e continua dei dati in un data center geograficamente distante. 

- **Monitoraggio dei dati:** servizi Microsoft livelli elevati di prestazioni tramite il monitoraggio: 

  - Database

  - Processi bloccati

  - Perdita di pacchetti

  - Processi in coda

  - Latenza delle query

- **Interventi di manutenzione preventiva:** la manutenzione preventiva include verifiche di coerenza dei database, compressione periodica dei dati e analisi dei log degli errori. 

## <a name="support"></a>Supporto tecnico

I team di sviluppo e operazioni Microsoft sono integrati da un'organizzazione di supporto dedicata, che svolge un ruolo importante nel fornire ai clienti la continuità aziendale. Il personale di supporto possiede una conoscenza approfondita del servizio e delle applicazioni associate, oltre a disporre di accesso diretto agli esperti Microsoft in materia di architettura, sviluppo e testing.
  
L'organizzazione di assistenza è perfettamente allineata con lo sviluppo di prodotti e operazioni, assicura tempi di risoluzione rapidi e fornisce ai clienti un canale per esprimere le proprie opinioni. Il feedback dei clienti fornisce l'input per la pianificazione, lo sviluppo e i processi operativi.
  
- **Gestione dei problemi online:** i clienti devono sapere che i loro problemi sono in fase di risoluzione e devono essere in grado di verificare la tempestività del processo di risoluzione. Il interfaccia di amministrazione di Microsoft 365 fornisce una singola interfaccia basata sul Web per il supporto. I clienti possono utilizzare il portale per aggiungere e monitorare le richieste di assistenza e per ricevere feedback dai team di supporto Microsoft. 

- **Supporto in autonomia, supportato dal supporto continuo del personale:** Microsoft offre un'ampia gamma di risorse e strumenti di supporto in autonomia che possono aiutare i clienti a risolvere i problemi relativi ai servizi senza richiedere supporto Microsoft. 

Prima di immettere una richiesta di assistenza, i clienti possono accedere ad articoli della Knowledge Base e domande frequenti che forniscono soluzioni immediate ai problemi più comuni. Tali risorse vengono continuamente aggiornate con le ultime informazioni, e questo aiuta a evitare ritardi fornendo soluzioni ai problemi noti. Se tuttavia si verifica un problema che richiede l'intervento di un tecnico, il personale è disponibile per fornire assistenza immediata per telefono e tramite il portale di amministrazione, 24 ore al giorno per 7 giorni la settimana.
  
Per ulteriori informazioni sul supporto, vedere [l'articolo supporto.](support.md) 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani, vedere [Microsoft 365 e Office 365 del servizio della piattaforma.](office-365-platform-service-description.md)
