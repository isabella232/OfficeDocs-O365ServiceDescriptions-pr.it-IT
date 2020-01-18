---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: In risposta ai requisiti univoci e in evoluzione del settore pubblico degli Stati Uniti, Microsoft ha creato Office 365 US Government plans (o Office 365 Government). In questo articolo viene fornita una panoramica delle funzionalità specifiche per gli ambienti governativi US di Office 365.
ms.openlocfilehash: 7fdf83fc7cd4ededf28826861ef0202aca6185bf
ms.sourcegitcommit: 66e0fa8f265fe5cdb0d94c340fef5cb5431fc600
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/18/2020
ms.locfileid: "41233359"
---
# <a name="office-365-us-government"></a>Office 365 US Government

In risposta ai requisiti univoci e in evoluzione del settore pubblico degli Stati Uniti, Microsoft ha creato Office 365 US Government plans (o Office 365 Government). In questa sezione viene fornita una panoramica delle funzionalità specifiche per gli ambienti governativi US di Office 365. Si consiglia di leggere questa sezione supplementare insieme alle descrizioni dei [servizi di Office 365 ](../../office-365-service-descriptions-technet-library.md).
  
## <a name="how-to-use-this-service-description"></a>Informazioni su come utilizzare questa descrizione del servizio

La descrizione del servizio Office 365 US Government è progettata per essere utilizzato come sovrapposizione alla descrizione generale del servizio Office 365. Il documento definisce gli impegni univoci ed evidenzia le differenze rispetto alle offerte Office 365 Enterprise.
  
## <a name="about-office-365-us-government-environments"></a>Informazioni sugli ambienti governativi degli Stati Uniti di Office 365

I piani di Office 365 US Government sono sottoscrizioni mensili e vengono concessi a un numero illimitato di utenti. 
  
- L'ambiente **Office 365 GCC** garantisce la conformità ai requisiti federali per i servizi cloud, tra cui FedRAMP moderate e i requisiti per la giustizia penale e i sistemi informativi federali (CJI e FTI). 
    
- Gli ambienti **Office 365 GCC High e DOD** offrono la conformità con le linee guida sui requisiti di sicurezza del dipartimento per la difesa, la Defense Federal Acquisition Regulations Supplement (DFARS) e il traffico internazionale di armi (ITAR). 
    
Oltre alle funzionalità e caratteristiche di Office 365, le organizzazioni beneficeranno del vantaggio Office 365 US Government dalle seguenti funzionalità uniche in Office 365 US Government:
  
- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi Office 365 commerciali di Microsoft.
    
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
    
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
    
- Office 365 US Government è conforme alle certificazioni e riconoscimenti necessari per i clienti del settore pubblico degli Stati Uniti.
  
## <a name="customer-eligibility"></a>Idoneità del cliente

Office 365 US Government è disponibile per (1) entità governative federali, statali, locali, comunali e territoriali, e (2) altre entità (che necessitano di una convalida di idoneità) che gestiscono dati soggetti a requisiti e normative e alle quali viene richiesto l'utilizzo di Office 365 US Government per soddisfare tali requisiti e normative. La convalida di idoneità da parte di Microsoft include la conferma per la gestione di dati soggetti ai regolamenti ITAR (International Traffic in Arms Regulations), dati legali soggetti ai criteri di sicurezza CJIS (Criminal Justice Information Services) dell'FBI o altri dati governativi. La convalida potrebbe richiedere la prova della registrazione presso il Dipartimento di Stato degli Stati Uniti d'America responsabile dell'amministrazione dei dati ITAR o la sponsorizzazione da parte di un'entità governativa con requisiti specifici per la gestione di dati. Office 365 DoD-Environment è per l'utilizzo esclusivo del dipartimento della difesa degli Stati Uniti.
  
Anche se i criteri di eleggibilità sono coerenti tra le offerte governative di Office 365, Microsoft accetterà solo di DFARS e ITAR contratto lingua per l'ambiente GCC High Environment.
  
Le entità con domande sull'idoneità per Office 365 US Government devono consultare il proprio team degli account.
  
Al rinnovo del contratto di un cliente per Office 365 US Government, è richiesta una nuova convalida di idoneità.
  
## <a name="customer-content-located-within-the-united-states"></a>Il contenuto del cliente si trova all'interno del territorio degli Stati Uniti

I servizi Office 365 US Government sono offerti da centri dati che si trovano negli Stati Uniti. Il seguente contenuto del cliente viene archiviato da centri dati che si trovano fisicamente negli Stati Uniti: 
  
- Contenuto delle cassette postali di Exchange Online (corpo di posta elettronica, voci del calendario e contenuto degli allegati di posta elettronica)
    
- Contenuto del sito di SharePoint Online e file archiviati all'interno del sito
    
- Conversazioni archiviate in Skype for business, documenti caricati e sessioni di lavagna

- Thread di chat persistente di Microsoft Teams
    
> [!NOTE]
> Con uso tipico, Skype for Business non archivia contenuto, ma se avvenisse un'archiviazione, sarebbe nei centri dati degli Stati Uniti. 
  
Se gli utenti si trovano all'interno degli Stati Uniti durante l'utilizzo di Office per il Web (in precedenza noto come Office Web Apps) oppure se si adotta l'utilizzo di Active Directory Federation Services (AD FS) 2,0 e si configurano i criteri per garantire che gli utenti si connettono ai servizi tramite single si GN-on, qualsiasi contenuto del cliente temporaneamente memorizzato nella cache in Office per il Web sarà disponibile negli Stati Uniti.
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government e i servizi di terze parti

Office 365 fornisce la capacità di integrare applicazioni di terze parti in siti SharePoint Online, Skype for Business, applicazioni Office incluse in Office 365 ProPlus (come Word, Excel, PowerPoint e Outlook) e Outlook Web App. Inoltre, Office 365 supporta l'integrazione con provider di servizi di terze parti. Tali applicazioni e servizi di terze parti potrebbero includere archiviazione, trasmissione ed elaborazione di dati cliente dell'organizzazione su sistemi di terze parti esterne all'infrastruttura di Office 365 e quindi non coperte dagli impegni di conformità e protezione dei dati di Office 365. Si raccomanda di consultare le dichiarazioni sulla privacy e conformità fornite dalle terze parti quando si valuta l'uso adatto di tali servizi per la propria organizzazione.
  
## <a name="restricted-data-access-by-administrators"></a>Accesso ai dati riservati da parte degli amministratori

Accesso al contenuto del cliente del governo degli Stati Uniti di Office 365 da parte di Microsoft Administrators è limitato al personale schermato. Per i dettagli sui livelli di screening, fare riferimento alla pagina di descrizione del servizio per ciascun ambiente (GCC o GCC High e DoD). 

  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Center onboarding Assistance

Con FastTrack Center benefit per Office 365<sup>1</sup>, è possibile lavorare in remoto con gli specialisti di FastTrack per ottenere l'ambiente Office 365 pronto per l'utilizzo e la pianificazione dell'implementazione e dell'utilizzo all'interno dell'organizzazione. Il processo FastTrack fornisce assistenza per onboarding e servizi di adozione da parte dell'utente. 
  
L'onboarding consiste di:
  
- Onboarding di base-queste sono le attività necessarie per la configurazione del tenant e l'integrazione con Azure Active Directory (Azure AD), se necessario. L'onboarding di base fornisce, inoltre, la linea di base per l'onboarding di altri servizi.
    
- Le attività di onboarding e servizio di migrazione dei servizi consentono di abilitare gli scenari nel tenant. La migrazione dei dati (inclusi i messaggi di posta elettronica e i file) è inclusa nella [migrazione dei dati](https://aka.ms/whatcanmigrate). <sup>2</sup>

I servizi di adozioni degli utenti sono costituiti da attività che forniscono indicazioni per garantire agli utenti di essere a conoscenza dei servizi idonei e possono utilizzarli per guidare il valore aziendale. Questa assistenza viene fornita parallelamente alle attività di onboarding.
  
È possibile trovare informazioni specifiche sul processo di FastTrack Center [.](https://aka.ms/whatistheprocess) Per una ripartizione dei ruoli e delle responsabilità per l'impegno, esaminare le [responsabilità di FastTrack](https://aka.ms/whatdoesftcdo) e [le](https://aka.ms/whatdowedo)responsabilità.
  
> <sup>1</sup> è necessario acquistare almeno 50 licenze dall'elenco dei [piani idonei](https://aka.ms/whocanbenefit) per ricevere i servizi di FastTrack.
<br/><sup>2</sup> i servizi di migrazione dei dati sono disponibili per i tenant di Office 365 con 500 o più licenze.
  
## <a name="data-migrations-performed-by-fasttrack"></a>Migrazioni di dati eseguite da FastTrack

I clienti che scelgono il beneficio per la migrazione di [FastTrack](https://fasttrack.microsoft.com/) dovranno concedere l'accesso al team che gestisce la migrazione dei dati. Questo personale è cittadino degli Stati Uniti ed è sottoposto ai precedenti controlli in background prima di eseguire migrazioni per i clienti di Office 365 servizi governativi degli Stati Uniti.
  
||||
|:-----|:-----|:-----|
|**Screening del background** <br/> |**GCC** <br/> |**GCC High e DoD** <br/> |
|Verifica della cittadinanza degli Stati Uniti  <br/> |Sì  <br/> |Sì  <br/> |
|Verifica della cronologia del lavoro  <br/> |Sì  <br/> |Sì  <br/> |
|Verifica dell'istruzione  <br/> |Sì  <br/> |Sì  <br/> |
|Ricerca del numero di previdenza sociale (SSN)  <br/> |Sì  <br/> |Sì  <br/> |
|Controllo di precedenti penali (7 anni)  <br/> |Sì  <br/> |Sì  <br/> |
     
## <a name="office-365-us-government-and-azure-government-expressroute"></a>ExpressRoute per Office 365 US Government e Azure Government

Office 365 i clienti del governo degli Stati Uniti possono utilizzare i servizi di Azure Government ExpressRoute per connettersi privatamente ai servizi di Office 365 supportati anziché connettersi tramite Internet pubblico.
  
Per informazioni dettagliate, ad esempio i provider supportati, i modelli di prezzi e altro ancora, vedere [Azure ExpressRoute Information](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).
  
Per informazioni dettagliate sul supporto di Office 365 per Azure ExpressRoute, vedere [Azure ExpressRoute per office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)
  
## <a name="system-requirements"></a>Requisiti di sistema

Per i requisiti di sistema per i piani di Office 365 US Government, vedere [Requisiti di sistema di Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) sul sito di prodotti [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409). 
  
## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

For information about the Security &amp; Compliance Center and links to additional information and availability, see [Office 365 Security &amp; Compliance Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).
  
## <a name="service-availability-for-each-plan"></a>Disponibilità del servizio per ogni piano

Ogni piano di Office 365 include una serie di servizi individuali, come Exchange Online e SharePoint Online. Nella seguente tabella sono indicati i servizi disponibili in ogni piano di Office 365 US Government.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Servizi di Office 365** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Office per il Web  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Office 365 ProPlus  <br/> |No <br/> |Sì <br/> |Sì <br/> |No  <br/> |
|Exchange Online  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Exchange Online Protection  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|SharePoint Online  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|OneDrive for Business  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |Sì<sup>1</sup> <br/> |Sì  <br/> |Sì  <br/> |Sì<sup>1</sup> <br/> |
| Sistema di segreteria telefonica, audioconferenza  <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |Sì <sup>5</sup> <br/> |No  <br/> |
|Power BI Pro  <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |Sì  <br/> |N.<sup>2</sup> <br/> |
|Project Online  <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |
|Visio per il Web  <br/> |N.<sup>6</sup> <br/> |N.<sup>6</sup> <br/> |N.<sup>6</sup> <br/> |N.<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |N.<sup>4</sup> <br/> |N.<sup>4</sup> <br/> |N.<sup>4</sup> <br/> |N.<sup>4</sup> <br/> |
   
> <sup>1</sup> Skype for Business Basic è disponibile per tutti i clienti. Il client desktop Skype for Business è un'applicazione installata localmente che fornisce funzionalità di presenza, messaggistica istantanea e conferenza per i piani di Office 365 contenenti Skype for Business online. Office 365 ProPlus, G3 e G5 includono l'applicazione Skype completa, che include funzionalità aggiuntive come il supporto di telefonia avanzato, l'archiviazione e le funzionalità di conformità. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> non incluso, ma può essere acquistato come componente aggiuntivo separato. Project Online include client desktop di Project online come parte della sottoscrizione.
<br/> <sup>3</sup> non ancora disponibile nei piani GCC High o DOD, ma lo sarà presto. 
<br/><sup>4</sup> Yammer Enterprise non è un componente di Office 365 US Government, ma può essere acquisito gratuitamente come offerta autonoma per ogni utente concesso in licenza per Office 365 in GCC. Questa offerta è attualmente limitata ai clienti che acquistano Office 365 GCC in contratti Enterprise e contratti di sottoscrizione Enterprise. Yammer non è disponibile in GCC High o DoD.
<br/><sup>5</sup> il piano di chiamata è un componente aggiuntivo. 
<br/><sup>6</sup> non incluso, ma può essere acquistato come componente aggiuntivo separato. Visio per il Web include l'app desktop di Visio come parte della sottoscrizione.

## <a name="platform-features"></a>Funzionalità della piattaforma 

Nella tabella seguente sono elencati i servizi e le funzionalità della piattaforma disponibili nei piani di Office 365 US Government.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|**Amministrazione di Office 365** <br/> |||||
|Utilizzo dell'interfaccia di amministrazione di Microsoft 365 per l'amministrazione di Office 365  <br/> |Sì<sup>16</sup> <br/> |Sì<sup>16</sup> <br/> |Sì  <br/> |Sì<sup>16</sup> <br/> |
|Gestione delle impostazioni dei principali servizi da Office 365  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Utilizzare Windows PowerShell per gestire Office 365  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Proteggere i contenuti utilizzando Protezione delle informazioni di Azure  <br/> |N<sup>° 1</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup>  <br/> |N<sup>° 1</sup> <br/> |
|**[Funzionalità della famiglia di prodotti Office 365](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Microsoft Bookings  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|Messaggi di posta elettronica Microsoft Briefing  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|Microsoft Power automatizzato  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |Sì <br/> |Sì <br/> |Sì<br/> |Sì</sup> <br/> |
|API di Microsoft Graph  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Microsoft MyAnalytics  <br/> |No <br/> |No <br/> |Sì<sup>17</sup> <br/> |No <br/> |
|Microsoft Planner  <br/> |Sì <br/> |Sì <br/> |Sì <br/> |Sì <br/> |
|App di Microsoft Power  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |No <br/> |No <br/> |No <br/> |No<br/> |
|Microsoft Stream  <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |No  <br/> |
|Microsoft Sway  <br/> |No <br/> |No <br/> |No <br/> |No <br/> |
|Microsoft Teams  <br/> |Sì <br/> |Sì <br/> |Sì <br/> |Sì <br/> |
|Office Delve  <br/> |Sì<sup>17</sup> <br/> |Sì<sup>17</sup> <br/> |Sì  <br/> |Sì<sup>17</sup> <br/> |
|Gruppi di Office 365  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[Gestione degli account utente](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Identità cloud  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Identità federata (Single Sign-On)  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Autenticazione a più fattori  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Autenticazione del fattore di telefonia  <br/> |Sì<sup>9</sup> <br/> |Sì<sup>9</sup> <br/> |Sì  <br/> |Sì<sup>9</sup> <br/> |
|Strumento di configurazione desktop Office 365  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Gestione degli utenti con Office 365  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Caricamento in massa tramite file csv  <br/> |Sì<sup>9</sup> <br/> |Sì<sup>9</sup> <br/> |Sì  <br/> |Sì<sup>9</sup> <br/> |
|Strumento di sincronizzazione della directory  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Migrazione semplice (completa) di Exchange  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Eliminazione degli account tramite Office 365  <br/> |Sì <sup>3</sup> <br/> |Sì <sup>3</sup> <br/> |Sì <sup>3</sup> <br/> |Sì <sup>3</sup> <br/> |
|L'amministratore può reimpostare la password dell'utente da Office 365 o tramite Windows PowerShell  <br/> |Sì <sup>4</sup> <br/> |Sì <sup>4</sup> <br/> |Sì <sup>4</sup> <br/> |Sì <sup>4</sup> <br/> |
|Gli utenti possono modificare la propria password  <br/> |Sì <sup>5</sup> <br/> |Sì <sup>5</sup> <br/> |Sì <sup>5</sup> <br/> |Sì <sup>5</sup> <br/> |
|Gestione delle licenze  <br/> |Sì<sup>7, 8</sup> <br/> |Sì<sup>7, 8</sup> <br/> |Sì<sup>7, 8</sup> <br/> |Sì<sup>7,8</sup> <br/> |
|Gestione dei gruppi di sicurezza da Office 365  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Disponibilità di più ruoli amministratore  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Possibilità di permettere a un partner di gestire Office 365  <br/> |Sì<sup>11</sup> <br/> |Sì<sup>11</sup> <br/> |Sì<sup>11</sup> <br/> |Sì<sup>11</sup> <br/> |
|Servizi di Azure Active Directory  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[Domini](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Aggiunta di domini di secondo livello personalizzati, come fourthcoffee.com  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Aggiunta di domini di terzo livello personalizzati, come marketing.fourthcoffee.com  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Aggiunta di un massimo di 900 domini personalizzati  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Verifica della proprietà obbligatoria per i domini personalizzati  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[Continuità e integrità del servizio](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Le informazioni sullo stato sono disponibili sulla pagina **Integrità dei servizi** o **Stato dei servizi**  <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |
|Stato dei singoli avvisi disponibili nel dashboard dell'interfaccia di amministrazione di Microsoft 365  <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |
|Feed RSS per l' **integrità dei servizi**  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[Report](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Cassette postali attive e inattive  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Cassette postali nuove ed eliminate  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Gruppi nuovi ed eliminati  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Utilizzo delle cassette postali  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Tipi di connessioni delle cassette postali  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Posta inviata e ricevuta  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Destinatari e mittenti principali  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Rilevamenti di posta indesiderata  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Rilevamenti di malware  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Malware principali nella posta  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Corrispondenze alle regole nella posta  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Corrispondenze alle regole principali per la posta  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Corrispondenze di criteri DLP principali nella posta  <br/> |No  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Corrispondenze di criteri DLP per livello di gravità per la posta  <br/> |No  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Corrispondenza, sostituzioni e falsi positivi dei criteri DLP per la posta  <br/> |No  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Corrispondenze alle regole DLP principali nella posta  <br/> |No  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Sessioni di messaggistica immediata e audio  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Conferenze di condivisione applicazioni, Web e telefoniche con accesso esterno  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Sessioni video, di condivisione applicazioni e di trasferimento file  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Conferenze di messaggistica immediata e audio/video  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Rapporti sulla protezione della posta scaricabile  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Browser utilizzato  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Sistema operativo utilizzato  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Creare i propri rapporti utilizzando il sito Web dei servizi di reporting di Office 365  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|**[Aggiornamenti dei servizi](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Aggiornamenti regolari forniti a tutti i clienti  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Notifiche inviate a Centro messaggi quando l'azione è obbligatoria  <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |
|Roadmap.office.com per alcuni aggiornamenti del servizio  <br/> |N<sup>. 10, 13</sup> <br/> |N<sup>. 10, 13</sup> <br/> |N<sup>. 10, 13</sup> <br/> |N<sup>. 10, 13</sup> <br/> |
|Opzione per abilitare la versione di destinazione  <br/> |Sì<sup>10</sup> <br/> |Sì<sup>10</sup> <br/> |Sì<sup>10</sup> <br/> |Sì<sup>10</sup> <br/> |
|**[Guida e formazione](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Guida online  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Community  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Altre risorse di supporto in autonomia  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Formazione autonoma  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[Rete](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Protocolli IPv4 e IPv6  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**Attendibilità** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|**[Privacy, sicurezza e trasparenza](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|Governance dei dati avanzata  <br/> |N.<sup>12</sup> <br/> |N.<sup>12</sup> <br/> |Sì <br/> |N.<sup>12</sup> <br/> |
|Cloud App Security  <br/> |N.<sup>12, 15, 19</sup> <br/> |N.<sup>12, 15, 19</sup> <br/> |Sì<sup>15, 19</sup> <br/> |N.<sup>12, 15, 19</sup> <br/> |
|Protezione avanzata dalle minacce  <br/> |N<sup>. 12, 18</sup> <br/> |N<sup>. 12, 18</sup> <br/> |Sì<sup>18</sup>  <br/> |N<sup>. 12, 18</sup> <br/> |
|Archivio protetto del cliente  <br/> |N.<sup>12</sup> <br/> |N.<sup>12</sup> <br/> |Sì <br/> |N.<sup>12</sup> <br/> |
|Office 365 Advanced eDiscovery  <br/> |N.<sup>12</sup> <br/> |N.<sup>12</sup> <br/> |Sì  <br/> |N.<sup>12</sup> <br/> |
|Punteggio sicuro<sup>14</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9</sup> <br/> |Sì<sup>9, 15</sup> <br/> |Sì<sup>9, 15</sup> <br/> |
|Crittografia dei messaggi di Office  <br/> |No  <br/> |Sì <br/> |Sì <br/> |No  <br/> |
|Intelligence per le minacce  <br/> |N.<sup>12</sup> <br/> |N.<sup>12</sup> <br/> |Sì <br/> |N.<sup>12</sup> <br/> |
|**[Conformità](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|Valutazioni SAS 70 / SSAE16  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Certificato ISO 27001  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Clausole modello UE  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|EU Safe Harbor  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|HIPAA-Business Associate Agreement  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|FISMA Authority to Operate  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Contratto sull'elaborazione dati di Microsoft  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|PCI DSS Livello Uno  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Dati PAN conformi allo standard PCI  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|**[Continuità del servizio](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Utilizzo di BlackBerry Internet Service (BIS)  <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |N.<sup>2</sup> <br/> |
|**[Partner](../../office-365-platform-service-description/partners.md)** <br/> |||||
|Creazione di inviti e ordini di acquisto di prova per un cliente che utilizza uno specifico piano  <br/> |N.<sup>11</sup> <br/> |N.<sup>11</sup> <br/> |N.<sup>11</sup> <br/> |N.<sup>11</sup> <br/> |
|Amministrazione delegata  <br/> |N.<sup>11</sup> <br/> |N.<sup>11</sup> <br/> |N.<sup>11</sup> <br/> |N.<sup>11</sup> <br/> |
|**[Contratto di servizio](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|**[Diritti di utilizzo del prodotto](../../office-365-platform-service-description/product-use-rights.md)** <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
   
> <sup>1</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e consente di abilitare le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono un abbonamento a Office 365 ProPlus, che non è incluso in Office 365 Government G1 o Office 365 Government F1. > 
<br/><sup>2</sup> I clienti BBCS e BIS esistenti possono continuare a usare il servizio. I nuovi clienti non vengono accettati. 
<br/><sup>3</sup> Se si utilizza la sincronizzazione della directory, per eliminare gli account o cambiare le password è necessario utilizzare Active Directory, anziché il portale di Office 365 o il modulo di Azure Active Directory per Windows PowerShell. 
<br/><sup>4</sup> Se si utilizza la sincronizzazione delle password, gli utenti devono modificare le password in Active Directory locale. 
<br/><sup>5</sup> Per informazioni su come impostare i criteri di gestione della password self-service per gli utenti, vedere [Gestire password in Azure Active Directory](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/). 
<br/><sup>6</sup> È possibile utilizzare un solo sito Web pubblico con Office 365, a meno che non sia stato eseguito l'aggiornamento da una versione precedente di Office 365. In tal caso, sono presenti due siti Web pubblici, dei quali solo uno può essere ospitato con un nome di dominio personalizzato. Per ulteriori informazioni sull'utilizzo di due siti Web con sottoscrizioni di tipo Business, vedere [Utilizzo di due siti Web pubblici di Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Se si dispone di una sottoscrizione diversa, vedere [Informazioni sull'hosting in un sito Web di un partner e sui siti Web pubblici in Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009) per ulteriori informazioni sui siti Web pubblici. 
<br/><sup>7</sup> La riduzione delle postazioni acquistate con un'offerta a termine può essere soggetta a un addebito per rescissione anticipata. Non è applicabile alle sottoscrizioni mensili. 
<br/><sup>8</sup> i piani riportati di seguito non supportano le modifiche del seggiolino di licenza dall'interfaccia di amministrazione di Microsoft 365: Office 365 Government G1, Office 365 Government G3, Office 365 Government F1. 
<br/><sup>9</sup> non ancora disponibile in GCC High, ma lo sarà presto.
<br/><sup>10</sup> per la Guida di orientamento di Office 365 per il governo G1, G3 e F1, è applicabile la versione mirata e la roadmap di Office 365 for business; Tuttavia, potrebbero verificarsi alcune differenze o ritardi per gli aggiornamenti specifici del servizio a causa dei [requisiti di conformità](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> non ancora disponibile nelle offerte governative di Office 365, ma verrà presto. 
<br/><sup>12</sup> non incluso, ma può essere acquistato come componente aggiuntivo separato in GCC. 
<br/><sup>13</sup> non supportato per le offerte governative di Office 365. 
<br/><sup>14</sup> disponibile all' [https://securescore.office.com](https://securescore.office.com)indirizzo. Richiede autorizzazioni amministrative. Per ulteriori informazioni, vedere [Introducing the Office 365 Secure Score](https://go.microsoft.com/fwlink/?linkid=836894). 
<br/><sup>15</sup> non ancora disponibile in DOD Environment, ma lo sarà presto. 
<br/><sup>16</sup> l'interfaccia di amministrazione non include l'analisi dell'utilizzo negli ambienti DOD o GCC High.
<br/><sup>17</sup> non supportato per gli ambienti GCC High e DOD.
<br/><sup>18</sup> la funzionalità di anti-phishing per gli utenti e i domini e la falsificazione delle informazioni non sono ancora disponibili in GCC High e DOD.
<br/><sup>19</sup> non ancora disponibile nell'ambiente GCC, ma lo sarà presto.
  
## <a name="office-application-availability-and-enterprise-value"></a>Disponibilità delle applicazioni di Office e valore Enterprise

Nella tabella seguente vengono mostrate le funzionalità delle applicazioni di Office disponibili nei piani di Office 365 US Government.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|**Applicazioni di Office** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup> <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup> <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup> <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup> <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup> <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Microsoft Forms<sup>7</sup>| Sì <br/> | Sì <br/>| Sì <br/> | No <br/> |
|Microsoft lavagna<sup>7</sup>| No <br/> | Sì <br/> | Sì <br/> | No <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |Sì<sup>3</sup> <br/> |Sì  <br/> |Sì  <br/> |Sì<sup>3</sup> <br/> |
|[Office per Mac per Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[Office Mobile per iPhone/iPad](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |Sì  <br/> |Sì<sup></sup> <br/> |Sì<sup></sup> <br/> |Sì  <br/> |
|[Office Mobile per Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |Sì  <br/> |Sì<sup></sup> <br/> |Sì<sup></sup> <br/> |Sì  <br/> |
|[Office Mobile per Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |Sì  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |Sì  <br/> |
|Office Mobile per tablet con Windows 10 <br/> |Sì  <br/> |Sì<sup></sup> <br/> |Sì<sup></sup> <br/> |Sì  <br/> |
|Outlook per iOS e Android<sup>5, 4</sup>  <br/> |Sì <br/> |Sì <br/> |Sì <br/> |Sì <br/> |
|**Valore Enterprise** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|5 installazioni per ogni utente su PC o Mac  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Provisioning dell'account utente automatizzato  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Interfaccia utente multilingue  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Distribuzione push del client  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|Supporto client per server Exchange locale  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Supporto client per SharePoint on-premises  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Controllo degli aggiornamenti software  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Confronto di database  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Virtualizzazione Desktop  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Confronto fogli di calcolo Excel  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Verifica fogli di calcolo Excel  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Archiviazione e conformità Exchange Online e SharePoint Online  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Supporto di Criteri di gruppo  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Information Rights Management tramite Azure Information Protection  <br/> |N<sup>° 1</sup> <br/> |Sì<sup>6</sup> <br/> |Sì<sup>6</sup> <br/> |N<sup>° 1</sup> <br/> |
|Information Rights Management tramite Windows Server AD RMS  <br/> |Sì<sup>2</sup> <br/> |Sì<sup>2</sup> <br/> |Sì<sup>2</sup> <br/> |Sì<sup>2</sup> <br/> |
|Supporto dei componenti aggiuntivi di Office, ActiveX e oggetto browser helper (BHO)  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Accesso client di OneNote ai blocchi appunti in SharePoint Server, SharePoint Online, OneDrive for Business e Office 365  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Office Lens  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
|Telemetria di Office  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|Supporto non in linea per le applicazioni client  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Installazione client side-by-side ottimizzata  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Power Map per Excel  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|PowerPivot per Excel  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|Power Query per Excel  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|Power View per Excel  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|Impostazioni roaming  <br/> |No  <br/> |Sì<sup></sup> <br/> |Sì<sup></sup> <br/> |No  <br/> |
|Attivazione di computer condivisi  <br/> |No  <br/> |Sì <br/> |Sì <br/> |No  <br/> |
|Supporto per il blocco dell'archiviazione file basata su cloud  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|Aggiornamenti della versione  <br/> |No  <br/> |Sì<sup>4</sup> <br/> |Sì<sup>4</sup> <br/> |No  <br/> |
|Volume activation (KMS/MAK)  <br/> |No  <br/> |No  <br/> |No  <br/> |No  <br/> |
   
> <sup>1</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e consente di abilitare le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono un abbonamento a Office 365 ProPlus, che non è incluso in Office 365 Government G1 o Office 365 Government F1. 
<br/><sup>2</sup> Windows Server ad RMS è un server in locale che deve essere acquistato e gestito separatamente per abilitare le funzionalità IRM supportate. 
<br/><sup>3</sup>Skype for Business Basic è disponibile per tutti i clienti. Il client desktop Skype for Business è un'applicazione installata localmente che fornisce funzionalità di presenza, messaggistica istantanea e conferenza per i piani di Office 365 contenenti Skype for Business online. Office 365 ProPlus e Office 365 Enterprise E3 includono l'applicazione Skype completa, che include funzionalità aggiuntive come il supporto di telefonia avanzato, l'archiviazione e le funzionalità di conformità. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup> non è ancora disponibile negli ambienti GCC High o DOD, ma verrà presto.
<br/><sup>5</sup> vedere [utilizzo di Outlook per iOS e Android nel cloud della community del governo](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) per ulteriori dettagli.
<br/><sup>6</sup> non ancora disponibile in Office 365 DOD Environment, ma verrà presto.
<br/><sup>7</sup> le applicazioni sono completamente disponibili nelle cloud di stato, ad eccezione delle caratteristiche specifiche non disponibili in questo momento. Per informazioni dettagliate, vedere [disponibilità delle funzionalità di Office Application](#office-application-and-feature-availability-in-government-plans) .

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilità delle funzionalità e delle applicazioni di Office nei piani governativi

Le applicazioni di Office seguenti sono disponibili nelle cloud del governo. Tuttavia, alcune funzionalità basate sul cloud potrebbero non essere attualmente disponibili, come indicato nella tabella.

|||||
|-----|-----|-----|-----|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che non sono disponibili in questo momento: | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|animazioni e modelli 3D incorporati 3D | No <br/> | No <br/> | No <br/> |
|Tipi di dati | No <br/> | No <br/> | No <br/> |
|Riempimento istantaneo | No <br/> | No <br/> | No <br/> |
|Idee (servizi Insight) | No <br/> | No <br/> | No <br/> |
|Integrazione migliorata con PowerBI (grafica personalizzata, creazione di grafici PBI direttamente da Excel) | No <br/> | No <br/> | No <br/> |
|Inchiostro digitale intelligente | No <br/> | No <br/> | No <br/> |
|Gruppi di Office 365 | No <br/> | No <br/> | No <br/> |
|Dati di grafici pivot connessi alle tabelle pivot | No <br/> | No <br/> | No <br/> |
|PowerPivot | No <br/> | No <br/> | No <br/> |
|Pubblicare in PowerBI | No <br/> | No <br/> | No <br/> |
|Collaborazione in tempo reale (presenza, CoAuthoring normale, chat in-Document) | No <br/> | No <br/> | No <br/> |
|Shared with Me | No <br/> | No <br/> | No <br/> |
|Ricerca intelligente | No <br/> | No <br/> | No <br/> |
|Grafici: Sunburst TreeMap, cascata, istogramma, mappe, sequenza temporale, imbuto | No <br/> | No <br/> | No <br/> |
|Cronologia versioni | No <br/> | No <br/> | No <br/> |
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che non sono disponibili al momento: | **GCC** <br/> | **GCC High** <br/> | **DOD**<sup>3</sup> <br/> |
|Notifica tramite posta elettronica | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | No <br/> | 
|Inserire un'immagine | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | No <br/> |
|Inserire un video | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | No <br/> |
|Matematiche | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | No <br/> |
|Integrazione di Office | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | No <br/> |
|Moduli di gruppo più recenti | Sì <br/> | Sì <br/> | No <br/> |
|Condivisione esterna <sup>4</sup> | Sì <br/> | No <br/> | No <br/> |
|Moduli Pro | No | No | No |
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che non sono disponibili in questo momento: | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Strumento ricerche | No <br/> | No <br/> | No <br/> |
|Inchiostro digitale intelligente | No <br/> | No <br/> | No <br/> |
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che non sono disponibili in questo momento: | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Suoni di Office (alcuni) | No <br/> | No <br/> | No <br/> |
|DDE (Dynamic Data Exchange) disabilitato per impostazione predefinita | No <br/> | No <br/> | No <br/> |
|Dettatura | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> |
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che non sono disponibili in questo momento: | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Ricerca intelligente | No <br/> | No <br/> | No <br/> |
|Suoni di Office (alcuni) | No <br/> | No <br/> | No <br/> |
|modelli 3D e animazioni 3D incorporate | No <br/> | No <br/> | No <br/> |
|Grafici: mappe | No <br/> | No <br/> | No <br/> |
|Inchiostro digitale intelligente | No <br/> | No <br/> | No <br/> |
|Didascalie e sottotitoli in tempo reale in PowerPoint | No <br/> | No <br/> | No <br/> |
|Coach relatore | No <br/> | No <br/> | No <br/> |
|Shared with Me | No <br/> | No <br/> | No <br/> |
|Integrazione di Skype for business con condivisione | No <br/> | No <br/> | No <br/> |
|Cronologia versioni | No <br/> | No <br/> | No <br/> |
|Gruppi di Office 365 | No <br/> | No <br/> | No <br/> |
|Collaborazione in tempo reale (presenza, CoAuthoring normale, chat in-Document) | No <br/> | No <br/> | No <br/> |
|Dettatura | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> |
|Riutilizzo delle diapositive | No <br/> | No <br/> | No <br/> |
|La **lavagna Microsoft** in cloud governativi è attualmente disponibile solo sui client Hub e non sul desktop. | **GCC**<sup>2</sup> <br/> | **GCC High**<sup>2</sup> <br/> | **DOD**<sup>2</sup> <br/> |
|Inserire note, testo e immagini adesive | Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>|
|Input penna per la forma e l'input penna nella tabella | Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>|
|Abbellimento inchiostro | Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>|
|Convertire l'immagine in input penna | Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>|
|Verifica accessibilità | Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>| Sì<sup>2</sup> <br/>|
|Modelli dinamici (KANBAN, SWOT e così via) | No <br/> | No <br/> | No <br/> |
|Collaborazione in tempo reale | No <br/> | No <br/> | No <br/> |
|Presenza in tempo reale | No <br/> | No <br/> | No <br/> |
|Reazioni sul contenuto | No <br/> | No <br/> | No <br/> |
|Raccolta schede di lavagne, inclusa la condivisione con l'utente | No <br/> | No <br/> | No <br/> |
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che non sono disponibili in questo momento: | **GCC** <br/> | **GCC High** <br/> | **DOD** <br/> |
|Ricerca intelligente | No <br/> | No <br/> | No <br/> |
|Strumento ricerche | No <br/> | No <br/> | No <br/> |
|Suoni di Office  | No <br/> | No <br/> | No <br/> |
|modelli 3D | No <br/> | No <br/> | No <br/> |
|animazioni 3D incorporate  | No <br/> | No <br/> | No <br/> |
|Tocco  | No <br/> | No <br/> | No <br/> |
|Assistente curriculum | No <br/> | No <br/> | No <br/> |
|Grafici delle mappe | No <br/> | No <br/> | No <br/> |
|Inchiostro digitale intelligente | No <br/> | No <br/> | No <br/> |
|Shared with Me | No <br/> | No <br/> | No <br/> |
|Translation | No <br/> | No <br/> | No <br/> |
|Integrazione di Skype for business con condivisione | No <br/> | No <br/> | No <br/> |
|Cronologia versioni | No <br/> | No <br/> | No <br/> |
|Gruppi di Office 365 | No <br/> | No <br/> | No <br/> |
|Chat contestuale con i coautori: chattare con i coautori all'interno del documento | No <br/> | No <br/> | No <br/> |
|Dettatura | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> | N<sup>° 1</sup> <br/> |

> <sup>1</sup> disponibilità imminente.<br/>
<sup>2</sup> disponibilità su Hub superficie locale (non connesso).<br/>
<sup>3</sup> l'applicazione non è attualmente disponibile nel cloud DOD.<br/>
<sup>4</sup> la condivisione esterna è disponibile per l'ambiente GCC. Per ulteriori informazioni, vedere Disattivazione [o attivazione di Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) per l'organizzazione. La condivisione esterna è disattivata per gli ambienti GCC High e DOD; Gli utenti all'interno dell'organizzazione possono eseguire le operazioni seguenti: completare una maschera e inviare risposte, [duplicare e condividere un modulo come modello](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [creare un coautore o collaborare a un modulo](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)e [accedere ai risultati dei moduli](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
