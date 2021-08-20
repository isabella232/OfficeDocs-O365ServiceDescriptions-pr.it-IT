---
title: Office 365 US Government
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: In risposta ai requisiti univoci e in evoluzione del settore pubblico degli Stati Uniti, Microsoft ha creato piani Office 365 US Government (o Office 365 Government). In questo articolo viene fornita una panoramica delle funzionalità specifiche per gli Office 365 Government stati Uniti.
ms.openlocfilehash: f2bdc4ed9d73cda00b4dbf9ecaf79434bc928c4c
ms.sourcegitcommit: 40a8e3be736d1177d046da50639a5685aca18707
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/19/2021
ms.locfileid: "58402760"
---
# <a name="office-365-government"></a>Office 365 Government

> [!IMPORTANT]
> Microsoft Teams sta riscontrando un enorme picco di chiamate online e conferenze audio/video a causa della pandemia del coronavirus (COVID-19).<br/>
>
>In risposta all'aumento senza precedenti delle chiamate e per garantire continuità e disponibilità, Microsoft consente ai server audio/video di Microsoft Teams GCC di sfruttare la capacità di elaborazione nei datacenter commerciali e nei datacenter governativi.<br/>
>
>Questi server audio/video risiedono nei Microsoft Azure fedRAMP High accreditation boundary negli Stati Uniti e non archiviano alcun contenuto del cliente. Tuttavia, questi server elaborano audio e video per chiamate e conferenze e operano sotto il nostro personale commerciale durante questo periodo intermedio.<br/>
>
>Personale qualificato e schermato sta monitorando questi server per l'accesso potenziale ai dati dei clienti esaminando eventuali accessi interattivi a questi server. Il personale qualificato soddisfa GCC requisiti per l'accesso ai contenuti dei clienti. Per informazioni dettagliate sui requisiti di screening, vedere la [descrizione GCC servizio.](gcc.md)<br/>
>
>Grazie per il supporto dato che microsoft prende misure per garantire che i nostri servizi rimangano disponibili e affidabili in questi tempi straordinari.<br/>

In risposta ai requisiti univoci e in evoluzione del settore pubblico degli Stati Uniti, Microsoft ha creato piani Office 365 Government (o Office 365 Government). Questa descrizione del servizio fornisce una panoramica delle funzionalità specifiche per gli Office 365 Government stati Uniti. È consigliabile leggere questa descrizione del servizio insieme ad altre [Microsoft 365 e Office 365 servizio.](../../office-365-service-descriptions-technet-library.md)

## <a name="how-to-use-this-service-description"></a>Come utilizzare la descrizione del servizio

La Office 365 Government del servizio è progettata per fungere da sovrimpressione alla descrizione generale Office 365 servizio. Il documento definisce gli impegni univoci ed evidenzia le differenze rispetto alle offerte Office 365 Enterprise.

## <a name="about-office-365-government-environments"></a>Informazioni Office 365 Government ambienti

Office 365 Government piani sono abbonamenti mensili e possono essere concessi in licenza a un numero illimitato di utenti.

- **L'ambiente Office 365 GCC** fornisce la conformità ai requisiti federali per i servizi cloud, tra cui FedRAMP High, e ai requisiti per la giustizia penale e i sistemi di informazioni fiscali federali (tipi di dati CJI e FTI).

- Gli ambienti Office 365 GCC High and **DoD** offrono conformità alle linee guida per i requisiti di sicurezza del Dipartimento della Difesa, al DFARS (Defense Federal Acquisition Regulations Supplement) e alle normative ITAR (International Traffic in Arms Regulations).

Oltre alle funzionalità e alle funzionalità di Office 365, le organizzazioni che utilizzano Office 365 Government beneficiano delle seguenti funzionalità specifiche per Office 365 Government:

- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi Office 365 commerciali di Microsoft.

- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Office 365 Government è conforme alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

## <a name="customer-eligibility"></a>Idoneità del cliente

Office 365 Government è disponibile per (1) enti governativi federali, statali, locali, tribali e territoriali degli Stati Uniti e (2) altre entità che gestiscono dati soggetti a normative e requisiti governativi e in cui l'uso di Office 365 Government è appropriato per soddisfare questi requisiti, in base alla convalida dell'idoneità. La convalida di idoneità da parte di Microsoft include la conferma per la gestione di dati soggetti ai regolamenti ITAR (International Traffic in Arms Regulations), dati legali soggetti ai criteri di sicurezza CJIS (Criminal Justice Information Services) dell'FBI o altri dati governativi. La convalida potrebbe richiedere la prova della registrazione presso il Dipartimento di Stato degli Stati Uniti d'America responsabile dell'amministrazione dei dati ITAR o la sponsorizzazione da parte di un'entità governativa con requisiti specifici per la gestione di dati. L Office 365 ambiente DoD è per l'uso esclusivo del Dipartimento della Difesa degli Stati Uniti.

Sebbene i criteri di idoneità siano coerenti Office 365 Government offerte, Microsoft accetterà solo la lingua del contratto DFARS e ITAR per l'ambiente GCC High.

Le entità con domande sull'idoneità per Office 365 Government devono consultare il team dell'account.

Al rinnovo del contratto di un cliente per Office 365 Government, è necessaria la riconvalida dell'idoneità.

## <a name="customer-content-located-within-the-united-states"></a>Il contenuto del cliente si trova all'interno del territorio degli Stati Uniti

Office 365 Government servizi vengono forniti da datacenter situati fisicamente negli Stati Uniti. Il seguente contenuto del cliente viene archiviato da centri dati che si trovano fisicamente negli Stati Uniti:

- Exchange Online contenuto della cassetta postale (corpo della posta elettronica, voci del calendario e contenuto degli allegati di posta elettronica)

- SharePoint Contenuto del sito online e file archiviati in tale sito

- Skype for Business conversazioni archiviate, documenti caricati e sessioni di lavagna

- Microsoft Teams thread di chat persistente

> [!NOTE]
> Con uso tipico, Skype for Business non archivia contenuto, ma se avvenisse un'archiviazione, sarebbe nei centri dati degli Stati Uniti.

Se gli utenti si trovano negli Stati Uniti durante l'utilizzo di Office per il web (in precedenza noto come Office Web Apps) o se si adotta l'utilizzo di Active Directory Federation Services (AD FS) 2.0 e si configurano criteri per garantire che gli utenti si connettono ai servizi tramite single sign-on, tutti i contenuti dei clienti temporaneamente memorizzati nella cache in Office per il web si trovano negli Stati Uniti.

La pagina Utilizzo sito per i siti SharePoint è disponibile per i piani governativi, anche se per conformità esistono alcune caratteristiche di questa pagina che sono disponibili solo per i clienti commerciali. Per ulteriori informazioni, vedere [Site usage page for SharePoint sites in Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Office 365 Government e servizi di terze parti

Office 365 consente di integrare applicazioni di terze parti in siti di SharePoint Online, applicazioni Skype for Business, Office incluse in Microsoft 365 Apps for enterprise (ad esempio Word, Excel, PowerPoint e Outlook) e Outlook Web App. Inoltre, Office 365 supporta l'integrazione con provider di servizi di terze parti. Tali applicazioni e servizi di terze parti potrebbero includere archiviazione, trasmissione ed elaborazione di dati cliente dell'organizzazione su sistemi di terze parti esterne all'infrastruttura di Office 365 e quindi non coperte dagli impegni di conformità e protezione dei dati di Office 365. Si raccomanda di consultare le dichiarazioni sulla privacy e conformità fornite dalle terze parti quando si valuta l'uso adatto di tali servizi per la propria organizzazione.

## <a name="restricted-data-access-by-administrators"></a>Accesso ai dati riservati da parte degli amministratori

L'accesso Office 365 Government contenuto dei clienti da parte degli amministratori Microsoft è limitato al personale selezionato. Per i dettagli sui livelli di screening, fare riferimento alla pagina di descrizione del servizio per ogni ambiente (GCC o GCC High e DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Assistenza per l'onboarding del centro

Con il vantaggio FastTrack Center per Office 365<sup>1,</sup>si lavora in remoto con gli esperti di FastTrack per ottenere l'ambiente Office 365 pronto per l'uso e pianificare l'implementazione e l'utilizzo all'interno dell'organizzazione. Il processo FastTrack fornisce assistenza per onboarding e servizi di adozione da parte dell'utente.

L'onboarding consiste di:

- Onboarding di base: si tratta di attività necessarie per la configurazione del tenant e l'integrazione con Azure Active Directory (Azure AD), se necessario. L'onboarding di base fornisce, inoltre, la linea di base per l'onboarding di altri servizi.

- Onboarding del servizio e migrazione: le attività di onboarding del servizio abilitano gli scenari nel tenant. La migrazione dei dati (inclusi la posta elettronica e i file) è trattata in [Migrazione dei dati](/FastTrack/data-migration). <sup>2</sup>

I servizi di adozione degli utenti sono costituiti da attività che forniscono indicazioni per assicurarsi che gli utenti siano a conoscenza dei servizi idonei e possano usarli per guidare il valore aziendale. Questa assistenza viene fornita parallelamente alle attività di onboarding.

Informazioni specifiche sul processo FastTrack Center sono disponibili [qui.](/FastTrack/us-gov-appendix-overview) Per una suddivisione dei ruoli e delle responsabilità di coinvolgimento, FastTrack [responsabilità](/FastTrack/us-gov-appendix-fasttrack-responsibilities) e [responsabilità dell'utente.](/FastTrack/us-gov-appendix-your-responsibilities)

> <sup>1</sup> È necessario acquistare almeno 150 licenze [](/fasttrack/eligibility) dall'elenco dei piani idonei per ricevere FastTrack servizi.
<br/><sup>2</sup> I servizi di migrazione dei dati sono disponibili Office 365 tenant con 500 o più licenze.

## <a name="data-migrations-performed-by-fasttrack"></a>Migrazioni dei dati eseguite da FastTrack

I clienti che scelgono il [vantaggio FastTrack](https://fasttrack.microsoft.com/) migrazione dovranno concedere l'accesso al team che gestisce le migrazioni dei dati. Questi membri del personale sono cittadini statunitensi e vengono sottoposti ai seguenti controlli in background prima di eseguire le migrazioni per i clienti Office 365 servizi del governo statunitense.<br><br>

|Screening in background|GCC|GCC High e DoD|
|---|---|---|
|Verifica della cittadinanza statunitense|Sì|Sì|
|Controllo della cronologia dell'impiego|Sì|Sì|
|Verifica dell'istruzione|Sì|Sì|
|Ricerca di numeri di previdenza sociale (SSN)|Sì|Sì|
|Controllo della cronologia penale (7 anni)|Sì|Sì|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>ExpressRoute per Office 365 US Government e Azure Government

Office 365 I clienti del governo statunitense possono usare i servizi Azure Government ExpressRoute per connettersi privatamente ai servizi Office 365 supportati invece di connettersi tramite Internet pubblico.

Per informazioni dettagliate, ad esempio i provider supportati, i modelli di prezzi e altro ancora, esaminare le informazioni [di Azure ExpressRoute.](/azure/expressroute/)

Per informazioni dettagliate sul Office 365 per Azure ExpressRoute, vedere [Azure ExpressRoute per Office 365](/microsoft-365/enterprise/azure-expressroute)

## <a name="system-requirements"></a>Requisiti di sistema

Per i requisiti di sistema per i piani di Office 365 US Government, vedere [Requisiti di sistema di Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) sul sito di prodotti [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Per informazioni sul Centro sicurezza e conformità e collegamenti a ulteriori informazioni e &amp; disponibilità, vedere [Centro sicurezza &amp; e conformità.](../../office-365-platform-service-description/office-365-securitycompliance-center.md)

## <a name="service-availability-for-each-plan"></a>Disponibilità del servizio per ogni piano

Ogni piano di Office 365 include una serie di servizi individuali, come Exchange Online e SharePoint Online. Nella seguente tabella sono indicati i servizi disponibili in ogni piano di Office 365 US Government.<br><br>

|Servizio Office 365|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|Exchange Online|Sì|Sì|Sì|Sì|
|Exchange Online Protection|Sì|Sì|Sì|Sì|
|Microsoft 365 Apps for enterprise|No|Sì|Sì|No|
|Office per il web|Sì|Sì|Sì|Sì|
|OneDrive for Business|Sì|Sì|Sì|Sì|
|Power BI Pro|No<sup>2</sup>|No<sup>2</sup>|Sì|No<sup>2</sup>|
|Project Online|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|
|SharePoint Online|Sì|Sì|Sì|Sì|
|SharePoint Syntex|Sì|Sì|Sì|Sì|
|Skype for Business (Instant Messaging &amp; Presence)|Sì<sup>1</sup>|Sì|Sì|Sì<sup>1</sup>|
|Voce - Sistema telefonico audioconferenza|No<sup>2</sup>|No<sup>2</sup>|Sì<sup>5</sup>|No|
|Visio per il Web|No<sup>6</sup>|No<sup>6</sup>|No<sup>6</sup>|No<sup>6</sup>|
|Yammer Enterprise|No<sup>4</sup>|No<sup>4</sup>|No<sup>4</sup>|No<sup>4</sup>|

> <sup>1</sup> Skype for Business Basic è disponibile per tutti i clienti. Il client desktop Skype for Business è un'applicazione installata localmente che fornisce funzionalità di presenza, messaggistica istantanea e conferenza per i piani di Office 365 contenenti Skype for Business online. Microsoft 365 Apps for enterprise, G3 e G5 includono l'applicazione Skype completa, che include funzionalità aggiuntive come il supporto avanzato della telefonia, le funzionalità di archiviazione e conformità. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> Non incluso, ma può essere acquistato come componente aggiuntivo separato. Project Online include Project Online Desktop Client come parte della sottoscrizione.
<br/> <sup>3</sup> Non ancora disponibile nei GCC High o DoD, ma presto disponibile.
<br/><sup>4</sup> Yammer Enterprise non è un componente di Office 365 US Government, ma può essere acquistato senza costi aggiuntivi come offerta autonoma per ogni utente concesso in licenza per Office 365 in GCC. Questa offerta è attualmente limitata ai clienti che acquistano Office 365 GCC contratti Enterprise e Enterprise contratti di sottoscrizione. Yammer non è disponibile in GCC High o DoD.
<br/><sup>5</sup> Piano di chiamata è un componente aggiuntivo.
<br/><sup>6</sup> Non incluso, ma può essere acquistato come componente aggiuntivo separato. Visio per il Web include l Visio app desktop come parte dell'abbonamento.

## <a name="platform-features"></a>Funzionalità della piattaforma 

Nella tabella seguente sono elencati i servizi e le funzionalità della piattaforma disponibili nei piani di Office 365 US Government.<br><br>

|Funzionalità|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Amministrazione di Office 365**|||||
|Utilizzare il interfaccia di amministrazione di Microsoft 365 per amministrare Office 365|Sì<sup>16</sup>|Sì<sup>16</sup>|Sì|Sì<sup>16</sup>|
|Gestione delle impostazioni dei principali servizi da Office 365|Sì|Sì|Sì|Sì|
|Utilizzare Windows PowerShell per gestire Office 365|Sì|Sì|Sì|Sì|
|Proteggere i contenuti utilizzando Protezione delle informazioni di Azure|No<sup>1</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|No<sup>1</sup>|
|**[Funzionalità della famiglia di prodotti Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Microsoft Bookings|No|Sì<sup>21</sup>|Sì<sup>21</sup>|No|
|Messaggio di posta elettronica di Microsoft Briefing|No|No|No|No|
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
|**[Gestione degli account utente](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Identità cloud|Sì|Sì|Sì|Sì|
|Identità federata (Single Sign-On)|Sì|Sì|Sì|Sì|
|Autenticazione a più fattori|Sì|Sì|Sì|Sì|
|Telefono factor authentication|Sì<sup>9</sup>|Sì<sup>9</sup>|Sì|Sì<sup>9</sup>|
|Strumento di configurazione desktop Office 365|No|Sì|Sì|No|
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
|**[Domini](../../office-365-platform-service-description/domains.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Aggiunta di domini di secondo livello personalizzati, come fourthcoffee.com|Sì|Sì|Sì|Sì|
|Aggiunta di domini di terzo livello personalizzati, come marketing.fourthcoffee.com|Sì|Sì|Sì|Sì|
|Aggiunta di un massimo di 900 domini personalizzati|Sì|Sì|Sì|Sì|
|Verifica della proprietà obbligatoria per i domini personalizzati|Sì|Sì|Sì|Sì|
|**[Continuità e integrità del servizio](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Le informazioni sullo stato sono disponibili sulla pagina **Integrità dei servizi** o **Stato dei servizi**|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|
|Stato dei singoli avvisi disponibili nel dashboard interfaccia di amministrazione di Microsoft 365 utente|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|
|Feed RSS per l' **integrità dei servizi**|Sì|Sì|Sì|Sì|
|**[Report](../../office-365-platform-service-description/reports.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
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
|Creare report personalizzati utilizzando i servizi Web Microsoft 365 report|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|**[Aggiornamenti dei servizi](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Aggiornamenti regolari forniti a tutti i clienti|Sì|Sì|Sì|Sì|
|Notifiche inviate a Centro messaggi quando l'azione è obbligatoria|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì<sup>15</sup>|
|Roadmap.office.com per alcuni aggiornamenti del servizio|No<sup>10, 13</sup>|No<sup>10, 13</sup>|No<sup>10, 13</sup>|No<sup>10, 13</sup>|
|Opzione per attivare Rilascio mirato|Sì<sup>10</sup>|Sì<sup>10</sup>|Sì<sup>10</sup>|Sì<sup>10</sup>|
|**[Guida e formazione](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Guida online|Sì|Sì|Sì|Sì|
|Community|Sì|Sì|Sì|Sì|
|Altre risorse di supporto in autonomia|Sì|Sì|Sì|Sì|
|Formazione autonoma|Sì|Sì|Sì|Sì|
|**[Rete](../../office-365-platform-service-description/networking.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Protocolli IPv4 e IPv6|Sì|Sì|Sì|Sì|
|**Attendibilità**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|**[Privacy, sicurezza e trasparenza](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Governance dei dati avanzata|No<sup>12</sup>|No<sup>12</sup>|Sì|No<sup>12</sup>|
|Cloud App Security|No<sup>12, 19</sup>|No<sup>12, 19</sup>|Sì<sup>19</sup>|No<sup>12, 19</sup>|
|Microsoft Defender per Office 365|No<sup>12, 18</sup>|No<sup>12, 18</sup>|Sì<sup>18</sup>|No<sup>12, 18</sup>|
|Customer Lockbox|No<sup>12</sup>|No<sup>12</sup>|Sì|No<sup>12</sup>|
|Advanced eDiscovery|No<sup>12</sup>|No<sup>12</sup>|Sì|No<sup>12</sup>|
|Punteggio sicuro<sup>14</sup>|Sì<sup>9, 15</sup>|Sì<sup>9</sup>|Sì<sup>9, 15</sup>|Sì<sup>9, 15</sup>|
|Office Crittografia dei messaggi|No|Sì|Sì|No|
|Intelligence per le minacce|No<sup>12</sup>|No<sup>12</sup>|Sì|No<sup>12</sup>|
|**[Conformità](/microsoft-365/compliance/offering-home)**|||||
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
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Utilizzo di BlackBerry Internet Service (BIS)|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|No<sup>2</sup>|
|**[Partner](../../office-365-platform-service-description/partners.md)**|||||
|Creazione di inviti e ordini di acquisto di prova per un cliente che utilizza uno specifico piano|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|Amministrazione delegata|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|**[Contratto di servizio](../../office-365-platform-service-description/service-level-agreement.md)**|Sì|Sì|Sì|Sì|
|**[Diritti di utilizzo del prodotto](../../office-365-platform-service-description/product-use-rights.md)**|Sì|Sì|Sì|Sì|

> <sup>1</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e abiliterà le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono una sottoscrizione a Microsoft 365 Apps for enterprise, che non è inclusa in Office 365 Government G1 o Office 365 Government F3. >
<br/><sup>2</sup> I clienti BBCS e BIS esistenti possono continuare a usare il servizio. I nuovi clienti non vengono accettati.
<br/><sup>3</sup> Se si utilizza la sincronizzazione della directory, per eliminare gli account o cambiare le password è necessario utilizzare Active Directory, anziché il portale di Office 365 o il modulo di Azure Active Directory per Windows PowerShell.
<br/><sup>4</sup> Se si utilizza la sincronizzazione delle password, gli utenti devono modificare le password in Active Directory locale.
<br/><sup>5</sup> Per informazioni su come impostare i criteri di gestione della password self-service per gli utenti, vedere [Gestire password in Azure Active Directory](/azure/active-directory/user-help/active-directory-passwords-update-your-own-password).
<br/><sup>6</sup> È possibile utilizzare un solo sito Web pubblico con Office 365, a meno che non sia stato eseguito l'aggiornamento da una versione precedente di Office 365. In tal caso, sono presenti due siti Web pubblici, dei quali solo uno può essere ospitato con un nome di dominio personalizzato. Per ulteriori informazioni sull'utilizzo di due siti Web con sottoscrizioni di tipo Business, vedere [Utilizzo di due siti Web pubblici di Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Se si dispone di una sottoscrizione diversa, vedere [Informazioni sull'hosting in un sito Web di un partner e sui siti Web pubblici in Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009) per ulteriori informazioni sui siti Web pubblici.
<br/><sup>7</sup> La riduzione delle postazioni acquistate con un'offerta a termine può essere soggetta a un addebito per rescissione anticipata. Non è applicabile alle sottoscrizioni mensili.
<br/><sup>8</sup> I piani seguenti non supportano le modifiche delle postazione delle licenze interfaccia di amministrazione di Microsoft 365: Office 365 Government G1, Office 365 Government G3, Office 365 Government F3.
<br/><sup>9</sup> Non ancora disponibile in GCC High, ma presto disponibile.
<br/><sup>10</sup> Per Office 365 Government G1, G3 e F3, si applicano il rilascio mirato e la roadmap Office 365 per le aziende; tuttavia, potrebbero verificarsi alcune differenze o ritardi per specifici aggiornamenti del servizio a causa dei [requisiti di conformità.](https://www.microsoft.com/trust-center)
<br/><sup>11</sup> Non ancora disponibile nelle Office 365 Government, ma presto disponibile.
<br/><sup>12</sup> Non incluso, ma può essere acquistato come componente aggiuntivo separato GCC.
<br/><sup>13</sup> Non supportato per Office 365 Government offerte.
<br/><sup>14</sup> Disponibile all'indirizzo [https://securescore.office.com](https://securescore.office.com) . Richiede autorizzazioni amministrative. Per ulteriori informazioni, vedere [Introduzione al Office 365 punteggio sicuro](/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> Non ancora disponibile in ambiente DoD, ma presto disponibile.
<br/><sup>16</sup> L'interfaccia di amministrazione non include l'analisi dei dati di utilizzo negli ambienti DoD GCC High.
<br/><sup>17</sup> Non supportato per gli GCC High o DoD.
<br/><sup>18</sup> L'anti-phishing per la rappresentazione di utenti e domini e l'intelligence di spoofing non sono ancora disponibili in GCC High e DoD.
<br/><sup>19</sup> Non ancora disponibile in GCC, ma presto disponibile.
<br/><sup>20</sup> Consumo solo per Microsoft Stream: nessuna pubblicazione o condivisione.
<br/><sup>21</sup> Non disponibile per l'API di Microsoft Graph o Microsoft Teams.

## <a name="office-application-availability-and-enterprise-value"></a>Office disponibilità dell'applicazione e valore aziendale

Nella tabella seguente vengono mostrate le funzionalità delle applicazioni di Office disponibili nei piani di Office 365 US Government.<br><br>

|Applicazione/funzionalità|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Applicazioni di Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|No|Sì|Sì|No|
|Microsoft Forms<sup>7</sup>|Sì|Sì <br/>|Sì|No|
|Microsoft Whiteboard<sup>7</sup>|No|Sì|Sì|No|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|No|Sì|Sì|No|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|No|Sì|Sì|No|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|Sì<sup>3</sup>|Sì|Sì|Sì<sup>3</sup>|
|[Office per Mac per Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|No|Sì|Sì|No|
|[Office Mobile per iPhone/iPad](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|Sì|Sì<sup></sup>|Sì<sup></sup>|Sì|
|[Office Mobile per Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|Sì|Sì<sup></sup>|Sì<sup></sup>|Sì|
|[Office Mobile per Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|Sì|Sì<sup>4</sup>|Sì<sup>4</sup>|Sì|
|Office Mobile per tablet con Windows 10|Sì|Sì<sup></sup>|Sì<sup></sup>|Sì|
|Outlook per iOS e Android<sup>5, 4</sup>|Sì|Sì|Sì|Sì|
|**Enterprise valore**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
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
|Information Rights Management con Azure Information Protection|No<sup>1</sup>|Sì<sup>6</sup>|Sì<sup>6</sup>|No<sup>1</sup>|
|Information Rights Management tramite Windows Server AD RMS|Sì<sup>2</sup>|Sì<sup>2</sup>|Sì<sup>2</sup>|Sì<sup>2</sup>|
|Supporto dei componenti aggiuntivi di Office, ActiveX e oggetto browser helper (BHO)|No|Sì|Sì|No|
|Accesso client di OneNote ai blocchi appunti in SharePoint Server, SharePoint Online, OneDrive for Business e Office 365|No|Sì|Sì|No|
|Office Lens|No|No|No|No|
|Telemetria di Office|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Supporto non in linea per le applicazioni client|No|Sì|Sì|No|
|Installazione client side-by-side ottimizzata|No|Sì|Sì|No|
|Power Map per Excel|No|No|No|No|
|PowerPivot per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Power Query per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Power View per Excel|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Impostazioni roaming|No|Sì<sup></sup>|Sì<sup></sup>|No|
|Attivazione di computer condivisi|No|Sì|Sì|No|
|Supporto per il blocco dell'archiviazione file basata su cloud|No|Sì|Sì|No|
|Aggiornamenti della versione|No|Sì<sup>4</sup>|Sì<sup>4</sup>|No|
|Volume activation (KMS/MAK)|No|No|No|No|

> <sup>1</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e abiliterà le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità di Azure Information Protection richiedono una sottoscrizione a Microsoft 365 Apps for enterprise, che non è inclusa in Office 365 Government G1 o Office 365 Government F3.
<br/><sup>2</sup> Windows Server AD RMS è un server locale che deve essere acquistato e gestito separatamente per abilitare le funzionalità IRM supportate.
<br/><sup>3</sup>Skype for Business Basic è disponibile per tutti i clienti. Il client desktop Skype for Business è un'applicazione installata localmente che fornisce funzionalità di presenza, messaggistica istantanea e conferenza per i piani di Office 365 contenenti Skype for Business online. Microsoft 365 Apps for enterprise e Office 365 Enterprise E3 includono l'applicazione Skype completa, che include funzionalità aggiuntive come il supporto avanzato della telefonia, le funzionalità di archiviazione e conformità. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> Non ancora disponibile in GCC High o DoD, ma presto disponibile.
<br/><sup>5</sup> Vedere [Uso Outlook per iOS e Android](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) nella Government Community Cloud per altri dettagli.
<br/><sup>6</sup> Non ancora disponibile in Office 365 DoD, ma presto disponibile.
<br/><sup>7</sup> Le applicazioni sono completamente disponibili nei cloud per enti pubblici, ad eccezione delle funzionalità specifiche non disponibili al momento. Per [informazioni Office sulla disponibilità delle funzionalità dell'applicazione,](#office-application-and-feature-availability-in-government-plans) vedere .

## <a name="office-application-and-feature-availability-in-government-plans"></a>Office delle applicazioni e delle funzionalità nei piani per enti pubblici

Le applicazioni Office seguenti sono disponibili nei cloud governativi; tuttavia, alcune funzionalità basate sul cloud potrebbero non essere attualmente disponibili, come indicato nella tabella.<br><br>

|Applicazione/funzionalità|Funzionalità di accessibilità|GCC|GCC High|DOD|
|---|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) è completamente disponibile nei cloud per enti pubblici ad eccezione delle funzionalità seguenti, che al momento **non** sono disponibili:|||||
|Animazioni 3D incorporate e modelli 3D|Sì|No|No|No|
|Tipi di dati||No|No|No|
|Riempimento flash||No|No|No|
|Idee (Insight Services)|Sì|No|No|No|
|Integrazione migliorata con Power BI (oggetti visivi personalizzati, creare grafici PBI direttamente da Excel)||No|No|No|
|Intelligent Digital Ink|Sì|No|No|No|
|Gruppi di Office 365||No|No|No|
|Dati di grafici pivot connessi a tabelle pivot||No|No|No|
|PowerPivot||No|No|No|
|Pubblica in Power BI||No|No|No|
|Collaborazione in tempo reale (presenza, creazione condivisa regolare, chat in-document)|Alcuni|No|No|No|
|Shared with Me||No|No|No|
|Ricerca intelligente|Sì|No|No|No|
|Grafici: sunburst treemap, cascata, istogramma, mappe, sequenza temporale, imbuto||No|No|No|
|Cronologia versioni|Sì|No|No|No|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) è completamente disponibile nei cloud per enti pubblici, ad eccezione delle funzionalità seguenti, che al momento **non** sono disponibili:||**GCC**|**GCC High**|**DOD**|
|Notifica tramite posta elettronica||No<sup>1</sup>|No<sup>1</sup>|No|
|Inserire un'immagine||No<sup>1</sup>|No<sup>1</sup>|No|
|Inserire un video||No<sup>1</sup>|No<sup>1</sup>|No|
|Matematica||No<sup>1</sup>|No<sup>1</sup>|No|
|Office integrazione||No<sup>1</sup>|No<sup>1</sup>|No|
|Moduli di gruppo più recenti||No<sup>4</sup>|Sì|Sì|
|Condivisione esterna<sup>3</sup>||Sì|No|No|
|Moduli Pro||No|No|No|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) è completamente disponibile nei cloud per enti pubblici, ad eccezione delle funzionalità seguenti, che al momento **non** sono disponibili:||**GCC**|**GCC High**|**DOD**|
|Strumento ricerche|Sì|No|No|No|
|Intelligent Digital Ink|Sì|No|No|No|
|Invia posta elettronica a OneNote (me@onenote.com)|Sì|No|No|No|
|Web Clipper||No|No|No|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) è completamente disponibile nei cloud per enti pubblici ad eccezione delle funzionalità seguenti, che non sono disponibili in tutti i cloud per enti pubblici, come indicato nella tabella seguente.||**GCC**|**GCC High**|**DOD**|
|Office suoni (alcuni)|Sì|No|No|No|
|Dynamic Data Exchange (DDE) disabilitato per impostazione predefinita||No|No|No|
|Dettatura|Sì|Sì|Sì|No<sup>1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) è completamente disponibile nei cloud per enti pubblici ad eccezione delle funzionalità seguenti, che non sono disponibili in tutti i cloud per enti pubblici, come indicato nella tabella seguente.||**GCC**|**GCC High**|**DOD**|
|Ricerca intelligente|Sì|No|No|No|
|Office suoni (alcuni)||No|No|No|
|Modelli 3D e animazioni incorporate 3D||No|No|No|
|Grafici: mappe||No|No|No|
|Intelligent Digital Ink|Sì|No|No|No|
|Sottotitoli in tempo reale in PowerPoint|Sì|Sì|Sì|No|
|Presentazioni live||No|No|No|
|Strumento di lettura immersiva|Sì|No|No|No|
|Presenter Coach|Sì|No|No|No|
|Shared with Me||No|No|No|
|Skype for Business integrazione con la condivisione||No|No|No|
|Cronologia versioni|Sì|No|No|No|
|Gruppi di Office 365||No|No|No|
|Collaborazione in tempo reale (presenza, creazione condivisa regolare, chat in-document)|Alcuni|No|No|No|
|Dettatura|Sì|Sì|Sì|No<sup>1</sup>|
|Riutilizzare diapositive||No|No|No|
|**Microsoft Whiteboard** nei cloud per enti pubblici è attualmente disponibile solo nei client Hub e non nel desktop.||**GCC**<sup>2</sup>|**GCC High**<sup>2</sup>|**DOD**<sup>2</sup>|
|Inserire sticky notes, testo e immagini||Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Da input penna a forma e input penna a tabella|Sì|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Abbellimento dell'inchiostro|Sì|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Convertire l'immagine in input penna|Sì|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Verifica accessibilità|Sì|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|Sì<sup>2</sup> <br/>|
|Modelli dinamici (KANBAN, SWOT e così via)|Sì|No|No|No|
|Collaborazione in tempo reale|Sì|No|No|No|
|Presenza in tempo reale|Sì|No|No|No|
|Reazioni sul contenuto|Sì|No|No|No|
|Raccolta bacheche di lavagne, inclusa la condivisione con l'utente||No|No|No|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) è completamente disponibile nei cloud per enti pubblici, ad eccezione delle funzionalità seguenti, che non sono disponibili in tutti i cloud per enti pubblici, come indicato nella tabella seguente.||**GCC**|**GCC High**|**DOD**|
|Ricerca intelligente|Sì|No|No|No|
|Strumento ricerche|Sì|No|No|No|
|Office suoni||No|No|No|
|Modelli 3D||No|No|No|
|Animazioni 3D incorporate||No|No|No|
|Tocco||No|No|No|
|Assistente curriculum|Sì|No|No|No|
|Grafici mappa||No|No|No|
|Intelligent Digital Ink|Sì|No|No|No|
|Shared with Me||No|No|No|
|Conversione||Sì<sup>5</sup>|Sì<sup>5</sup>|Sì<sup>5</sup>|
|Skype for Business integrazione con la condivisione||No|No|No|
|Cronologia versioni|Sì|No|No|No|
|Gruppi di Office 365||No|No|No|
|Chat contestuale con co-autori: chat con co-autori all'interno del documento||No|No|No|
|Dettatura|Sì|Sì|Sì|No<sup>1</sup>|

Per la disponibilità delle funzionalità Microsoft Teams in GCC/GCC High/DoD, visitare la Microsoft Teams [service description](../../teams-service-description.md).
> <sup>1</sup> Disponibilità in arrivo.
<br/><sup>2</sup> Disponibilità in Surface Hub locale (non connesso).
<br/><sup>3</sup> La condivisione esterna è disponibile per l'GCC locale. Ulteriori informazioni su come [disattivare o attivare Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) per l'organizzazione. La condivisione esterna è disabilitata per GCC high e dod; Gli utenti all'interno dell'organizzazione possono eseguire le operazioni seguenti: compilare un modulo e inviare [risposte,](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)duplicare e condividere un modulo come modello, creare insieme o collaborare [a](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)un modulo e accedere ai risultati [del modulo.](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)
<br/><sup>4</sup> La funzionalità Moduli di gruppo recenti è disabilitata per l'GCC locale. Gli utenti, tuttavia, possono comunque accedere ai moduli di gruppo selezionando un gruppo specifico nella scheda Moduli di gruppo.
<br/><sup>5</sup> Word, Excel PowerPoint Windows solo client, non Web, MacOS, iOS o Android.
