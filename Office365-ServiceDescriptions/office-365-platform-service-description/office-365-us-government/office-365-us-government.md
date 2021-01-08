---
title: Office 365 US Government
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: In risposta ai requisiti univoci e in evoluzione del settore pubblico degli Stati Uniti, Microsoft ha creato Office 365 US Government plans (o Office 365 Government). In questo articolo viene fornita una panoramica delle funzionalità specifiche per gli ambienti governativi US di Office 365.
ms.openlocfilehash: 92d2bd7b4197c096f6f87cc792e6f052247d7274
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/07/2021
ms.locfileid: "49780000"
---
# <a name="office-365-government"></a>Office 365 Government

> [!IMPORTANT]
> Microsoft teams sta vivendo un picco tremendo delle chiamate online e delle conferenze audio/video a causa della pandemia di coronavirus (COVID-19).<br/>
>
>In risposta all'aumento senza precedenti delle chiamate e al fine di garantire la continuità e la disponibilità, Microsoft consente ai server audio/video di Microsoft teams GCC di sfruttare la capacità di elaborazione nei datacenter commerciali, nonché nei datacenter del governo.<br/>
>
>Questi server audio/video risiedono all'interno dei server perimetrali di certificazione di Microsoft Azure FedRAMP High Accreditation negli Stati Uniti e non memorizzano alcun contenuto del cliente. Tuttavia, questi server stanno elaborando audio e video per le chiamate e le conferenze e operano sotto il nostro staff commerciale durante questo periodo intermedio.<br/>
>
>Il personale qualificato e schermato sta monitorando questi server per poter accedere ai dati dei clienti tramite la revisione di eventuali log-ons interattivi su questi server. Personale qualificato soddisfare i requisiti di GCC per accedere al contenuto del cliente. Per informazioni dettagliate sulla schermatura dei requisiti, vedere la [Descrizione del servizio GCC](gcc.md).<br/>
>
>La ringrazio per il supporto dato che è necessario eseguire le operazioni necessarie per garantire che i servizi rimangano disponibili e affidabili in questi periodi straordinari.<br/>

In risposta ai requisiti univoci e in evoluzione del settore pubblico degli Stati Uniti, Microsoft ha creato i piani governativi di Office 365 (o Office 365 Government). Questa descrizione del servizio fornisce una panoramica delle caratteristiche specifiche per gli ambienti governativi degli Stati Uniti di Office 365. Si consiglia di leggere questa descrizione del servizio insieme [ad altre descrizioni del servizio Microsoft 365 e Office 365](../../office-365-service-descriptions-technet-library.md).

## <a name="how-to-use-this-service-description"></a>Come utilizzare la descrizione del servizio

La descrizione del servizio governativo di Office 365 è progettata per essere utilizzato come sovrapposizione alla descrizione generale del servizio Office 365. Il documento definisce gli impegni univoci ed evidenzia le differenze rispetto alle offerte Office 365 Enterprise.

## <a name="about-office-365-government-environments"></a>Informazioni sugli ambienti governativi di Office 365

I piani governativi di Office 365 sono abbonamenti mensili e possono essere concessi in licenza a un numero illimitato di utenti.

- L'ambiente **Office 365 GCC** garantisce la conformità ai requisiti federali per i servizi cloud, tra cui FedRAMP High e i requisiti per la giustizia penale e i sistemi informativi federali (CJI e FTI).

- Gli ambienti **Office 365 GCC High e DOD** offrono la conformità con le linee guida sui requisiti di sicurezza del dipartimento per la difesa, la Defense Federal Acquisition Regulations Supplement (DFARS) e il traffico internazionale di armi (ITAR).

Oltre alle caratteristiche e alle funzionalità di Office 365, le organizzazioni che utilizzano Office 365 Government traggono vantaggio dalle seguenti funzionalità esclusive di Office 365 Government:

- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi Office 365 commerciali di Microsoft.

- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Office 365 Government è conforme alle certificazioni e agli accreditamenti necessari per i clienti del settore pubblico degli Stati Uniti.

## <a name="customer-eligibility"></a>Idoneità del cliente

Office 365 Government è disponibile per (1) entità governative degli Stati Uniti, statale, locale, tribale e territoriale e (2) altre entità che gestiscono i dati soggetti alle normative e ai requisiti governativi e in cui l'utilizzo di Office 365 Government è appropriato per soddisfare questi requisiti, in base alla convalida di idoneità. La convalida di idoneità da parte di Microsoft include la conferma per la gestione di dati soggetti ai regolamenti ITAR (International Traffic in Arms Regulations), dati legali soggetti ai criteri di sicurezza CJIS (Criminal Justice Information Services) dell'FBI o altri dati governativi. La convalida potrebbe richiedere la prova della registrazione presso il Dipartimento di Stato degli Stati Uniti d'America responsabile dell'amministrazione dei dati ITAR o la sponsorizzazione da parte di un'entità governativa con requisiti specifici per la gestione di dati. L'ambiente Office 365 DoD è a uso esclusivo del dipartimento della difesa degli Stati Uniti.

Anche se i criteri di eleggibilità sono coerenti tra le offerte governative di Office 365, Microsoft accetterà solo di DFARS e ITAR contratto lingua per l'ambiente GCC High Environment.

Le entità con domande sull'idoneità per il governo di Office 365 devono consultare il proprio team di account.

Dopo il rinnovo del contratto di un cliente per il governo di Office 365, è richiesta la riconvalida dell'idoneità.

## <a name="customer-content-located-within-the-united-states"></a>Il contenuto del cliente si trova all'interno del territorio degli Stati Uniti

I servizi governativi di Office 365 sono forniti da centri dati che si trovano fisicamente negli Stati Uniti. Il seguente contenuto del cliente viene archiviato da centri dati che si trovano fisicamente negli Stati Uniti:

- Contenuto delle cassette postali di Exchange Online (corpo di posta elettronica, voci del calendario e contenuto degli allegati di posta elettronica)

- Contenuto del sito di SharePoint Online e file archiviati all'interno del sito

- Conversazioni archiviate in Skype for business, documenti caricati e sessioni di lavagna

- Thread di chat persistente di Microsoft Teams

> [!NOTE]
> Con uso tipico, Skype for Business non archivia contenuto, ma se avvenisse un'archiviazione, sarebbe nei centri dati degli Stati Uniti.

Se gli utenti si trovano all'interno degli Stati Uniti durante l'utilizzo di Office per il Web (in precedenza noto come Office Web Apps) oppure se si adotta l'utilizzo di Active Directory Federation Services (AD FS) 2,0 e si configurano i criteri per garantire che gli utenti si connettono ai servizi tramite Single Sign-on, tutti i contenuti dei clienti temporaneamente memorizzati nella cache di Office per il

La pagina di utilizzo del sito per i siti di SharePoint è disponibile per i piani governativi, anche se per conformità, esistono alcune caratteristiche di questa pagina che sono disponibili solo per i clienti commerciali. Per ulteriori informazioni, vedere [Page Usage Site for SharePoint sites in Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Servizi governativi e di terze parti di Office 365

Office 365 offre la possibilità di integrare le applicazioni di terze parti nei siti di SharePoint Online, in Skype for business, nelle applicazioni di Office incluse in Microsoft 365 Apps for Enterprise (come Word, Excel, PowerPoint e Outlook) e in Outlook Web App. Inoltre, Office 365 supporta l'integrazione con provider di servizi di terze parti. Tali applicazioni e servizi di terze parti potrebbero includere archiviazione, trasmissione ed elaborazione di dati cliente dell'organizzazione su sistemi di terze parti esterne all'infrastruttura di Office 365 e quindi non coperte dagli impegni di conformità e protezione dei dati di Office 365. Si raccomanda di consultare le dichiarazioni sulla privacy e conformità fornite dalle terze parti quando si valuta l'uso adatto di tali servizi per la propria organizzazione.

## <a name="restricted-data-access-by-administrators"></a>Accesso ai dati riservati da parte degli amministratori

L'accesso al contenuto del cliente governativo di Office 365 da parte di Microsoft Administrators è limitato al personale sottoposto a screening. Per i dettagli sui livelli di screening, fare riferimento alla pagina di descrizione del servizio per ciascun ambiente (GCC o GCC High e DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Center onboarding Assistance

Con FastTrack Center benefit per Office 365<sup>1</sup>, è possibile lavorare in remoto con gli specialisti di FastTrack per ottenere l'ambiente Office 365 pronto per l'utilizzo e la pianificazione dell'implementazione e dell'utilizzo all'interno dell'organizzazione. Il processo FastTrack fornisce assistenza per onboarding e servizi di adozione da parte dell'utente.

L'onboarding consiste di:

- Onboarding di base-queste sono le attività necessarie per la configurazione del tenant e l'integrazione con Azure Active Directory (Azure AD), se necessario. L'onboarding di base fornisce, inoltre, la linea di base per l'onboarding di altri servizi.

- Le attività di onboarding e servizio di migrazione dei servizi consentono di abilitare gli scenari nel tenant. La migrazione dei dati (inclusi i messaggi di posta elettronica e i file) è inclusa nella [migrazione dei dati](https://aka.ms/whatcanmigrate). <sup>2</sup>

I servizi di adozioni degli utenti sono costituiti da attività che forniscono indicazioni per garantire agli utenti di essere a conoscenza dei servizi idonei e possono utilizzarli per guidare il valore aziendale. Questa assistenza viene fornita parallelamente alle attività di onboarding.

È possibile trovare informazioni specifiche sul processo di FastTrack Center [.](https://aka.ms/whatistheprocess) Per una ripartizione dei ruoli e delle responsabilità di ingaggio, esaminare le [responsabilità di FastTrack](https://aka.ms/whatdoesftcdo) e [le](https://aka.ms/whatdowedo)responsabilità.

> <sup>1</sup> è necessario acquistare almeno 50 licenze dall'elenco dei [piani idonei](https://aka.ms/whocanbenefit) per ricevere i servizi di FastTrack.
<br/><sup>2</sup> i servizi di migrazione dei dati sono disponibili per i tenant di Office 365 con 500 o più licenze.

## <a name="data-migrations-performed-by-fasttrack"></a>Migrazioni di dati eseguite da FastTrack

I clienti che scelgono il beneficio per la migrazione di [FastTrack](https://fasttrack.microsoft.com/) dovranno concedere l'accesso al team che gestisce la migrazione dei dati. Questo personale è cittadino degli Stati Uniti ed è sottoposto ai precedenti controlli in background prima di eseguire migrazioni per i clienti di Office 365 servizi governativi degli Stati Uniti.<br><br>

|Screening del background|GCC|GCC High e DoD|
|---|---|---|
|Verifica della cittadinanza degli Stati Uniti|Sì|Sì|
|Verifica della cronologia del lavoro|Sì|Sì|
|Verifica dell'istruzione|Sì|Sì|
|Ricerca del numero di previdenza sociale (SSN)|Sì|Sì|
|Controllo di precedenti penali (7 anni)|Sì|Sì|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>ExpressRoute per Office 365 US Government e Azure Government

Office 365 i clienti del governo degli Stati Uniti possono utilizzare i servizi di Azure Government ExpressRoute per connettersi privatamente ai servizi di Office 365 supportati anziché connettersi tramite Internet pubblico.

Per informazioni dettagliate, ad esempio i provider supportati, i modelli di prezzi e altro ancora, vedere [Azure ExpressRoute Information](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).

Per informazioni dettagliate sul supporto di Office 365 per Azure ExpressRoute, vedere [Azure ExpressRoute per office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)

## <a name="system-requirements"></a>Requisiti di sistema

Per i requisiti di sistema per i piani di Office 365 US Government, vedere [Requisiti di sistema di Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) sul sito di prodotti [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Per informazioni sul &amp; centro conformità di sicurezza e sui collegamenti a ulteriori informazioni e disponibilità, [vedere &amp; Centro sicurezza e conformità](../../office-365-platform-service-description/office-365-securitycompliance-center.md).

## <a name="service-availability-for-each-plan"></a>Disponibilità del servizio per ogni piano

Ogni piano di Office 365 include una serie di servizi individuali, come Exchange Online e SharePoint Online. Nella seguente tabella sono indicati i servizi disponibili in ogni piano di Office 365 US Government.<br><br>

|Servizio Office 365|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 governo F3|
|---|---|---|---|---|
|Office per il web|Sì|Sì|Sì|Sì|
|Microsoft 365 Apps for enterprise|No|Sì|Sì|No|
|Exchange Online|Sì|Sì|Sì|Sì|
|Exchange Online Protection|Sì|Sì|Sì|Sì|
|SharePoint Online|Sì|Sì|Sì|Sì|
|OneDrive for Business|Sì|Sì|Sì|Sì|
|Skype for Business (Instant Messaging &amp; Presence)|Sì<sup>1</sup>|Sì|Sì|Sì<sup>1</sup>|
|Sistema di segreteria telefonica, audioconferenza|N.<sup>2</sup>|N.<sup>2</sup>|Sì<sup>5</sup>|No|
|Power BI Pro|N.<sup>2</sup>|N.<sup>2</sup>|Sì|N.<sup>2</sup>|
|Project Online|N.<sup>2</sup>|N.<sup>2</sup>|N.<sup>2</sup>|N.<sup>2</sup>|
|Visio per il Web|N.<sup>6</sup>|N.<sup>6</sup>|N.<sup>6</sup>|N.<sup>6</sup>|
|Yammer Enterprise|N.<sup>4</sup>|N.<sup>4</sup>|N.<sup>4</sup>|N.<sup>4</sup>|

> <sup>1</sup> Skype for Business Basic è disponibile per tutti i clienti. Il client desktop Skype for Business è un'applicazione installata localmente che fornisce funzionalità di presenza, messaggistica istantanea e conferenza per i piani di Office 365 contenenti Skype for Business online. Le app Microsoft 365 per Enterprise, G3 e G5 includono l'applicazione Skype completa, che include funzionalità aggiuntive come il supporto di telefonia avanzato, l'archiviazione e le funzionalità di conformità. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> non incluso, ma può essere acquistato come componente aggiuntivo separato. Project Online include client desktop di Project online come parte della sottoscrizione.
<br/> <sup>3</sup> non ancora disponibile nei piani GCC High o DOD, ma lo sarà presto.
<br/><sup>4</sup> Yammer Enterprise non è un componente di Office 365 US Government, ma può essere acquisito gratuitamente come offerta autonoma per ogni utente concesso in licenza per Office 365 in GCC. Questa offerta è attualmente limitata ai clienti che acquistano Office 365 GCC in contratti Enterprise e contratti di sottoscrizione Enterprise. Yammer non è disponibile in GCC High o DoD.
<br/><sup>5</sup> il piano di chiamata è un componente aggiuntivo.
<br/><sup>6</sup> non incluso, ma può essere acquistato come componente aggiuntivo separato. Visio per il Web include l'app desktop di Visio come parte della sottoscrizione.

## <a name="platform-features"></a>Funzionalità della piattaforma 

Nella tabella seguente sono elencati i servizi e le funzionalità della piattaforma disponibili nei piani di Office 365 US Government.<br><br>

|Funzionalità|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 governo F3|
|---|---|---|---|---|
|**Amministrazione di Office 365**|||||
|Utilizzo dell'interfaccia di amministrazione di Microsoft 365 per l'amministrazione di Office 365|Sì<sup>16</sup>|Sì<sup>16</sup>|Sì|Sì<sup>16</sup>|
|Gestione delle impostazioni dei principali servizi da Office 365|Sì|Sì|Sì|Sì|
|Utilizzare Windows PowerShell per gestire Office 365|Sì|Sì|Sì|Sì|
|Proteggere i contenuti utilizzando Protezione delle informazioni di Azure|N<sup>° 1</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|N<sup>° 1</sup>|
|**[Funzionalità della famiglia di prodotti Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Microsoft Bookings|No|Sì<sup>21</sup>|Sì<sup>21</sup>|No|
|Messaggi di posta elettronica Microsoft Briefing|No|No|No|No|
|Microsoft Power Automate|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Microsoft Forms|Sì|Sì|Sì<br/>|Sì</sup>|
|API di Microsoft Graph|Sì|Sì|Sì|Sì|
|Microsoft MyAnalytics|No|No|Sì<sup>17</sup>|No|
|Microsoft Planner|Sì|Sì|Sì|Sì|
|App di Microsoft Power|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Microsoft StaffHub|No|No|No|No<br/>|
|Microsoft Stream|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15, 20</sup>|
|Microsoft Sway|No|No|No|No|
|Microsoft Teams|Sì|Sì|Sì|Sì|
|Office Delve|Sì<sup>17</sup>|Sì<sup>17</sup>|Sì|Sì<sup>17</sup>|
|Gruppi di Office 365|Sì|Sì|Sì|Sì|
|**[Gestione degli account utente](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Identità cloud|Sì|Sì|Sì|Sì|
|Identità federata (Single Sign-On)|Sì|Sì|Sì|Sì|
|Autenticazione a più fattori|Sì|Sì|Sì|Sì|
|Autenticazione del fattore di telefonia|Sì<sup>9</sup>|Sì<sup>9</sup>|Sì|Sì<sup>9</sup>|
|Strumento di configurazione desktop Office 365|Sì|Sì|Sì|Sì|
|Gestione degli utenti con Office 365|Sì|Sì|Sì|Sì|
|Caricamento in massa tramite file csv|Sì<sup>9</sup>|Sì<sup>9</sup>|Sì|Sì<sup>9</sup>|
|Strumento di sincronizzazione della directory|Sì|Sì|Sì|Sì|
|Migrazione semplice (completa) di Exchange|Sì|Sì|Sì|Sì|
|Eliminazione degli account tramite Office 365|Sì<sup>3</sup>|Sì<sup>3</sup>|Sì<sup>3</sup>|Sì<sup>3</sup>|
|L'amministratore può reimpostare la password dell'utente da Office 365 o tramite Windows PowerShell|Sì<sup>4</sup>|Sì<sup>4</sup>|Sì<sup>4</sup>|Sì<sup>4</sup>|
|Gli utenti possono modificare la propria password|Sì<sup>5</sup>|Sì<sup>5</sup>|Sì<sup>5</sup>|Sì<sup>5</sup>|
|Gestione delle licenze|Sì<sup>7, 8</sup>|Sì<sup>7, 8</sup>|Sì<sup>7, 8</sup>|Sì<sup>7,8</sup>|
|Gestione dei gruppi di sicurezza da Office 365|Sì|Sì|Sì|Sì|
|Disponibilità di più ruoli amministratore|Sì|Sì|Sì|Sì|
|Possibilità di permettere a un partner di gestire Office 365|Sì<sup>11</sup>|Sì<sup>11</sup>|Sì<sup>11</sup>|Sì<sup>11</sup>|
|Servizi di Azure Active Directory|Sì|Sì|Sì|Sì|
|**[Domini](../../office-365-platform-service-description/domains.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Aggiunta di domini di secondo livello personalizzati, come fourthcoffee.com|Sì|Sì|Sì|Sì|
|Aggiunta di domini di terzo livello personalizzati, come marketing.fourthcoffee.com|Sì|Sì|Sì|Sì|
|Aggiunta di un massimo di 900 domini personalizzati|Sì|Sì|Sì|Sì|
|Verifica della proprietà obbligatoria per i domini personalizzati|Sì|Sì|Sì|Sì|
|**[Continuità e integrità del servizio](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Le informazioni sullo stato sono disponibili sulla pagina **Integrità dei servizi** o **Stato dei servizi**|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|
|Stato dei singoli avvisi disponibili nel dashboard dell'interfaccia di amministrazione di Microsoft 365|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|
|Feed RSS per l' **integrità dei servizi**|Sì|Sì|Sì|Sì|
|**[Report](../../office-365-platform-service-description/reports.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Cassette postali attive e inattive|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Cassette postali nuove ed eliminate|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Gruppi nuovi ed eliminati|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Utilizzo delle cassette postali|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Tipi di connessioni delle cassette postali|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Posta inviata e ricevuta|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Destinatari e mittenti principali|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Rilevamenti di posta indesiderata|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Rilevamenti di malware|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Malware principali nella posta|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Corrispondenze alle regole nella posta|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Corrispondenze alle regole principali per la posta|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Corrispondenze di criteri DLP principali nella posta|No|Sì<sup>15</sup>|Sì<sup>15</sup>|No|
|Corrispondenze di criteri DLP per livello di gravità per la posta|No|Sì<sup>15</sup>|Sì<sup>15</sup>|No|
|Corrispondenza, sostituzioni e falsi positivi dei criteri DLP per la posta|No|Sì<sup>15</sup>|Sì<sup>15</sup>|No|
|Corrispondenze alle regole DLP principali nella posta|No|Sì<sup>15</sup>|Sì<sup>15</sup>|No|
|Sessioni di messaggistica immediata e audio|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Conferenze di condivisione applicazioni, Web e telefoniche con accesso esterno|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Sessioni video, di condivisione applicazioni e di trasferimento file|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Conferenze di messaggistica immediata e audio/video|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Rapporti sulla protezione della posta scaricabile|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Browser utilizzato|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Sistema operativo utilizzato|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Creare report personalizzati utilizzando i servizi Web di Reporting Microsoft 365|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|**[Aggiornamenti dei servizi](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Aggiornamenti regolari forniti a tutti i clienti|Sì|Sì|Sì|Sì|
|Notifiche inviate a Centro messaggi quando l'azione è obbligatoria|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Roadmap.office.com per alcuni aggiornamenti del servizio|N<sup>. 10, 13</sup>|N<sup>. 10, 13</sup>|N<sup>. 10, 13</sup>|N<sup>. 10, 13</sup>|
|Opzione per abilitare la versione di destinazione|Sì<sup>10</sup>|Sì<sup>10</sup>|Sì<sup>10</sup>|Sì<sup>10</sup>|
|**[Guida e formazione](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Guida online|Sì|Sì|Sì|Sì|
|Community|Sì|Sì|Sì|Sì|
|Altre risorse di supporto in autonomia|Sì|Sì|Sì|Sì|
|Formazione autonoma|Sì|Sì|Sì|Sì|
|**[Rete](../../office-365-platform-service-description/networking.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Protocolli IPv4 e IPv6|Sì|Sì|Sì|Sì|
|**Attendibilità**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|**[Privacy, sicurezza e trasparenza](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Governance dei dati avanzata|N.<sup>12</sup>|N.<sup>12</sup>|Sì|N.<sup>12</sup>|
|Cloud App Security|N.<sup>12, 15, 19</sup>|N.<sup>12, 15, 19</sup>|Sì<sup>15, 19</sup>|N.<sup>12, 15, 19</sup>|
|Microsoft Defender per Office 365|N<sup>. 12, 18</sup>|N<sup>. 12, 18</sup>|Sì<sup>18</sup>|N<sup>. 12, 18</sup>|
|Customer Lockbox|N.<sup>12</sup>|N.<sup>12</sup>|Sì|N.<sup>12</sup>|
|Advanced eDiscovery|N.<sup>12</sup>|N.<sup>12</sup>|Sì|N.<sup>12</sup>|
|Punteggio sicuro<sup>14</sup>|Sì<sup>9, 15</sup>|Sì<sup>9</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|
|Crittografia dei messaggi di Office|No|Sì|Sì|No|
|Intelligence per le minacce|N.<sup>12</sup>|N.<sup>12</sup>|Sì|N.<sup>12</sup>|
|**[Conformità](https://docs.microsoft.com/microsoft-365/compliance/offering-home)**|||||
|Valutazioni SAS 70 / SSAE16|Sì|Sì|Sì|Sì|
|Certificato ISO 27001|Sì|Sì|Sì|Sì|
|Clausole modello UE|Sì|Sì|Sì|Sì|
|EU Safe Harbor|Sì|Sì|Sì|Sì|
|HIPAA-Business Associate Agreement|Sì|Sì|Sì|Sì|
|FISMA Authority to Operate|Sì|Sì|Sì|Sì|
|Contratto sull'elaborazione dati di Microsoft|Sì|Sì|Sì|Sì|
|PCI DSS Livello Uno|Sì|Sì|Sì|Sì|
|Dati PAN conformi allo standard PCI|No|No|No|No|
|**[Continuità del servizio](../../office-365-platform-service-description/service-health-and-continuity.md)**|Sì|Sì|Sì|Sì|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Utilizzo di BlackBerry Internet Service (BIS)|N.<sup>2</sup>|N.<sup>2</sup>|N.<sup>2</sup>|N.<sup>2</sup>|
|**[Partner](../../office-365-platform-service-description/partners.md)**|||||
|Creazione di inviti e ordini di acquisto di prova per un cliente che utilizza uno specifico piano|N.<sup>11</sup>|N.<sup>11</sup>|N.<sup>11</sup>|N.<sup>11</sup>|
|Amministrazione delegata|N.<sup>11</sup>|N.<sup>11</sup>|N.<sup>11</sup>|N.<sup>11</sup>|
|**[Contratto di servizio](../../office-365-platform-service-description/service-level-agreement.md)**|Sì|Sì|Sì|Sì|
|**[Diritti di utilizzo del prodotto](../../office-365-platform-service-description/product-use-rights.md)**|Sì|Sì|Sì|Sì|

> <sup>1</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e consente di abilitare le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono un abbonamento a Microsoft 365 Apps for Enterprise, che non è incluso in Office 365 Government G1 o Office 365 Government F3. >
<br/><sup>2</sup> I clienti BBCS e BIS esistenti possono continuare a usare il servizio. I nuovi clienti non vengono accettati.
<br/><sup>3</sup> Se si utilizza la sincronizzazione della directory, per eliminare gli account o cambiare le password è necessario utilizzare Active Directory, anziché il portale di Office 365 o il modulo di Azure Active Directory per Windows PowerShell.
<br/><sup>4</sup> Se si utilizza la sincronizzazione delle password, gli utenti devono modificare le password in Active Directory locale.
<br/><sup>5</sup> Per informazioni su come impostare i criteri di gestione della password self-service per gli utenti, vedere [Gestire password in Azure Active Directory](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/).
<br/><sup>6</sup> È possibile utilizzare un solo sito Web pubblico con Office 365, a meno che non sia stato eseguito l'aggiornamento da una versione precedente di Office 365. In tal caso, sono presenti due siti Web pubblici, dei quali solo uno può essere ospitato con un nome di dominio personalizzato. Per ulteriori informazioni sull'utilizzo di due siti Web con sottoscrizioni di tipo Business, vedere [Utilizzo di due siti Web pubblici di Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Se si dispone di una sottoscrizione diversa, vedere [Informazioni sull'hosting in un sito Web di un partner e sui siti Web pubblici in Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009) per ulteriori informazioni sui siti Web pubblici.
<br/><sup>7</sup> La riduzione delle postazioni acquistate con un'offerta a termine può essere soggetta a un addebito per rescissione anticipata. Non è applicabile alle sottoscrizioni mensili.
<br/><sup>8</sup> i piani riportati di seguito non supportano le modifiche del seggiolino di licenza dall'interfaccia di amministrazione di Microsoft 365: Office 365 Government G1, Office 365 Government G3, Office 365 Government F3.
<br/><sup>9</sup> non ancora disponibile in GCC High, ma lo sarà presto.
<br/><sup>10</sup> per la Guida di orientamento di Office 365 per il governo G1, G3 e F3, la versione mirata e la roadmap di Office 365 for business sono valide; Tuttavia, potrebbero verificarsi alcune differenze o ritardi per gli aggiornamenti specifici del servizio a causa dei [requisiti di conformità](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> non ancora disponibile nelle offerte governative di Office 365, ma verrà presto.
<br/><sup>12</sup> non incluso, ma può essere acquistato come componente aggiuntivo separato in GCC.
<br/><sup>13</sup> non supportato per le offerte governative di Office 365.
<br/><sup>14</sup> disponibile all'indirizzo [https://securescore.office.com](https://securescore.office.com) . Richiede autorizzazioni amministrative. Per ulteriori informazioni, vedere [Introducing the Office 365 Secure Score](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> non ancora disponibile in DOD Environment, ma lo sarà presto.
<br/><sup>16</sup> l'interfaccia di amministrazione non include l'analisi dell'utilizzo negli ambienti DOD o GCC High.
<br/><sup>17</sup> non supportato per gli ambienti GCC High e DOD.
<br/><sup>18</sup> la funzionalità di anti-phishing per gli utenti e i domini e la falsificazione delle informazioni non sono ancora disponibili in GCC High e DOD.
<br/><sup>19</sup> non ancora disponibile nell'ambiente GCC, ma lo sarà presto.
<br/><sup>20</sup> consumi solo per Microsoft Stream: nessuna pubblicazione o condivisione.
<br/><sup>21</sup> non disponibile per l'API di Microsoft Graph o Microsoft teams.

## <a name="office-application-availability-and-enterprise-value"></a>Disponibilità delle applicazioni di Office e valore Enterprise

Nella tabella seguente vengono mostrate le funzionalità delle applicazioni di Office disponibili nei piani di Office 365 US Government.<br><br>

|Applicazione/caratteristica|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 governo F3|
|---|---|---|---|---|
|**Applicazioni di Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|No|Sì|Sì|No|
|Microsoft Forms<sup>7</sup>|Sì|Sì <br/>|Sì|No|
|Microsoft lavagna<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|No|Sì|Sì|No|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|No|Sì|Sì|No|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|Sì<sup>3</sup>|Sì|Sì|Sì<sup>3</sup>|
|[Office per Mac per Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|No|Sì|Sì|No|
|[Office Mobile per iPhone/iPad](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|Sì|Sì<sup></sup>|Sì<sup></sup>|Sì|
|[Office Mobile per Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|Sì|Sì<sup></sup>|Sì<sup></sup>|Sì|
|[Office Mobile per Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|Sì|Sì<sup>4</sup>|Sì<sup>4</sup>|Sì|
|Office Mobile per tablet con Windows 10|Sì|Sì<sup></sup>|Sì<sup></sup>|Sì|
|Outlook per iOS e Android<sup>5, 4</sup>|Sì|Sì|Sì|Sì|
|**Valore Enterprise**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|5 installazioni per ogni utente su PC o Mac|No|Sì|Sì|No|
|Provisioning dell'account utente automatizzato|Sì|Sì|Sì|Sì|
|Interfaccia utente multilingue|No|Sì|Sì|No|
|Distribuzione push del client|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Supporto client per server Exchange locale|No|Sì|Sì|No|
|Supporto client per SharePoint on-premises|No|Sì|Sì|No|
|Controllo degli aggiornamenti software|No|Sì|Sì|No|
|Confronto di database|No|Sì|Sì|No|
|Virtualizzazione Desktop|No|Sì|Sì|No|
|Confronto fogli di calcolo Excel|No|Sì|Sì|No|
|Verifica fogli di calcolo Excel|No|Sì|Sì|No|
|Archiviazione e conformità Exchange Online e SharePoint Online|No|Sì|Sì|No|
|Supporto di Criteri di gruppo|No|Sì|Sì|No|
|Information Rights Management tramite Azure Information Protection|N<sup>° 1</sup>|Sì<sup>6</sup>|Sì<sup>6</sup>|N<sup>° 1</sup>|
|Information Rights Management tramite Windows Server AD RMS|Sì<sup>2</sup>|Sì<sup>2</sup>|Sì<sup>2</sup>|Sì<sup>2</sup>|
|Supporto dei componenti aggiuntivi di Office, ActiveX e oggetto browser helper (BHO)|No|Sì|Sì|No|
|Accesso client di OneNote ai blocchi appunti in SharePoint Server, SharePoint Online, OneDrive for Business e Office 365|No|Sì|Sì|No|
|Office Lens|No|No|No|No|
|Telemetria di Office|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Supporto non in linea per le applicazioni client|No|Sì|Sì|No|
|Installazione client side-by-side ottimizzata|No|Sì|Sì|No|
|Power Map per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|PowerPivot per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Power Query per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Power View per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Impostazioni roaming|No|Sì<sup></sup>|Sì<sup></sup>|No|
|Attivazione di computer condivisi|No|Sì|Sì|No|
|Supporto per il blocco dell'archiviazione file basata su cloud|No|Sì|Sì|No|
|Aggiornamenti della versione|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Volume activation (KMS/MAK)|No|No|No|No|

> <sup>1</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e consente di abilitare le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono un abbonamento a Microsoft 365 Apps for Enterprise, che non è incluso in Office 365 Government G1 o Office 365 Government F3.
<br/><sup>2</sup> Windows Server ad RMS è un server in locale che deve essere acquistato e gestito separatamente per abilitare le funzionalità IRM supportate.
<br/><sup>3</sup>Skype for Business Basic è disponibile per tutti i clienti. Il client desktop Skype for Business è un'applicazione installata localmente che fornisce funzionalità di presenza, messaggistica istantanea e conferenza per i piani di Office 365 contenenti Skype for Business online. Microsoft 365 Apps for Enterprise e Office 365 Enterprise E3 includono l'applicazione Skype completa, che include funzionalità aggiuntive come il supporto di telefonia avanzato, l'archiviazione e le funzionalità di conformità. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> non è ancora disponibile negli ambienti GCC High o DOD, ma verrà presto.
<br/><sup>5</sup> vedere [utilizzo di Outlook per iOS e Android nel cloud della community del governo](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) per ulteriori dettagli.
<br/><sup>6</sup> non ancora disponibile in Office 365 DOD Environment, ma verrà presto.
<br/><sup>7</sup> le applicazioni sono completamente disponibili nelle cloud di stato, ad eccezione delle caratteristiche specifiche non disponibili in questo momento. Per informazioni dettagliate, vedere [disponibilità delle funzionalità di Office Application](#office-application-and-feature-availability-in-government-plans) .

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilità delle funzionalità e delle applicazioni di Office nei piani governativi

Le applicazioni di Office seguenti sono disponibili nelle cloud del governo. Tuttavia, alcune funzionalità basate sul cloud potrebbero non essere attualmente disponibili, come indicato nella tabella.<br><br>

|Applicazione/caratteristica|GCC|GCC High|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che **non sono** disponibili in questo momento:||||
|animazioni e modelli 3D incorporati 3D|No|No|No|
|Tipi di dati|No|No|No|
|Riempimento istantaneo|No|No|No|
|Idee (servizi Insight)|No|No|No|
|Integrazione migliorata con Power BI (grafica personalizzata, creazione di grafici di PBI direttamente da Excel)|No|No|No|
|Inchiostro digitale intelligente|No|No|No|
|Gruppi di Office 365|No|No|No|
|Dati di grafici pivot connessi alle tabelle pivot|No|No|No|
|PowerPivot|No|No|No|
|Pubblica in Power BI|No|No|No|
|Collaborazione in tempo reale (presenza, CoAuthoring normale, chat in-Document)|No|No|No|
|Shared with Me|No|No|No|
|Ricerca intelligente|No|No|No|
|Grafici: Sunburst TreeMap, cascata, istogramma, mappe, sequenza temporale, imbuto|No|No|No|
|Cronologia versioni|No|No|No|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che **non sono** disponibili al momento:|**GCC**|**GCC High**|**DOD**|
|Notifica tramite posta elettronica|N<sup>° 1</sup>|N<sup>° 1</sup>|No|
|Inserire un'immagine|N<sup>° 1</sup>|N<sup>° 1</sup>|No|
|Inserire un video|N<sup>° 1</sup>|N<sup>° 1</sup>|No|
|Matematiche|N<sup>° 1</sup>|N<sup>° 1</sup>|No|
|Integrazione di Office|N<sup>° 1</sup>|N<sup>° 1</sup>|No|
|Moduli di gruppo più recenti|N.<sup>4</sup>|Sì|Sì|
|Condivisione esterna<sup>3</sup>|Sì|No|No|
|Moduli Pro|No|No|No|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che **non sono** disponibili in questo momento:|**GCC**|**GCC High**|**DOD**|
|Strumento ricerche|No|No|No|
|Inchiostro digitale intelligente|No|No|No|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che **non sono** disponibili in questo momento:|**GCC**|**GCC High**|**DOD**|
|Suoni di Office (alcuni)|No|No|No|
|DDE (Dynamic Data Exchange) disabilitato per impostazione predefinita|No|No|No|
|Dettatura|N<sup>° 1</sup>|N<sup>° 1</sup>|N<sup>° 1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che **non sono** disponibili in questo momento:|**GCC**|**GCC High**|**DOD**|
|Ricerca intelligente|No|No|No|
|Suoni di Office (alcuni)|No|No|No|
|modelli 3D e animazioni 3D incorporate|No|No|No|
|Grafici: mappe|No|No|No|
|Inchiostro digitale intelligente|No|No|No|
|Didascalie e sottotitoli in tempo reale in PowerPoint|No|No|No|
|Coach relatore|No|No|No|
|Shared with Me|No|No|No|
|Integrazione di Skype for business con condivisione|No|No|No|
|Cronologia versioni|No|No|No|
|Gruppi di Office 365|No|No|No|
|Collaborazione in tempo reale (presenza, CoAuthoring normale, chat in-Document)|No|No|No|
|Dettatura|N<sup>° 1</sup>|N<sup>° 1</sup>|N<sup>° 1</sup>|
|Riutilizzo delle diapositive|No|No|No|
|La **lavagna Microsoft** in cloud governativi è attualmente disponibile solo sui client Hub e non sul desktop.|**GCC**<sup>2</sup>|**GCC High**<sup>2</sup>|**DOD**<sup>2</sup>|
|Inserire note, testo e immagini adesive|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Input penna per la forma e l'input penna nella tabella|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Abbellimento inchiostro|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Convertire l'immagine in input penna|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Verifica accessibilità|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Modelli dinamici (KANBAN, SWOT e così via)|No|No|No|
|Collaborazione in tempo reale|No|No|No|
|Presenza in tempo reale|No|No|No|
|Reazioni sul contenuto|No|No|No|
|Raccolta schede di lavagne, inclusa la condivisione con l'utente|No|No|No|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) è completamente disponibile nei cloud governativi, ad eccezione delle caratteristiche seguenti, che **non sono** disponibili in questo momento:|**GCC**|**GCC High**|**DOD**|
|Ricerca intelligente|No|No|No|
|Strumento ricerche|No|No|No|
|Suoni di Office|No|No|No|
|modelli 3D|No|No|No|
|animazioni 3D incorporate|No|No|No|
|Tocco|No|No|No|
|Assistente curriculum|No|No|No|
|Grafici delle mappe|No|No|No|
|Inchiostro digitale intelligente|No|No|No|
|Shared with Me|No|No|No|
|Translation|Sì<sup>5</sup>|Sì<sup>5</sup>|Sì<sup>5</sup>|
|Integrazione di Skype for business con condivisione|No|No|No|
|Cronologia versioni|No|No|No|
|Gruppi di Office 365|No|No|No|
|Chat contestuale con i coautori: chattare con i coautori all'interno del documento|No|No|No|
|Dettatura|N<sup>° 1</sup>|N<sup>° 1</sup>|N<sup>° 1</sup>|

Per la disponibilità delle funzionalità per Microsoft teams all'interno di GCC/GCC High/DoD, visitare la [Descrizione del servizio Microsoft teams](https://docs.microsoft.com/office365/servicedescriptions/teams-service-description).
> <sup>1</sup> disponibilità imminente.
<br/><sup>2</sup> disponibilità su Hub superficie locale (non connesso).
<br/><sup>3</sup> la condivisione esterna è disponibile per l'ambiente GCC. Per ulteriori informazioni, vedere Disattivazione [o attivazione di Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) per l'organizzazione. La condivisione esterna è disattivata per gli ambienti GCC High e DOD; Gli utenti all'interno dell'organizzazione possono eseguire le operazioni seguenti: completare una maschera e inviare risposte, [duplicare e condividere un modulo come modello](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [creare un coautore o collaborare a un modulo](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)e [accedere ai risultati dei moduli](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> la caratteristica dei moduli di gruppo recente è disattivata per l'ambiente GCC. Tuttavia, gli utenti possono comunque accedere ai moduli di gruppo selezionando un gruppo specifico nella scheda moduli di gruppo.
<br/><sup>5</sup> Word, solo client Windows PowerPoint di Excel, non Web, MacOS, iOS o Android.
