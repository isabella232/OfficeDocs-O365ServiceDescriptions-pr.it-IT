---
title: SharePoint per gli ambienti governativi degli Stati Uniti
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Informazioni sulla disponibilità delle funzionalità di SharePoint per i clienti del cloud governativo degli Stati Uniti.
ms.openlocfilehash: 4e09ec8fda62fb5ce7a6e886799c5f35edd32cf5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/28/2020
ms.locfileid: "48294192"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint per gli ambienti governativi degli Stati Uniti

In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud governativo degli Stati Uniti e il cloud commerciale, come elencato nella [Descrizione del servizio SharePoint](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description). SharePoint è disponibile per gli ambienti Government community Cloud (GCC), GCC High e DoD. 

Per ulteriori informazioni sul cloud governativo, tra cui l'eleggibilità e l'acquisto, vedere [Microsoft 365 Government-How to buy](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Per confrontare i piani governativi di Office 365, vedere [piani governativi di office 365](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Per informazioni sugli endpoint necessari per la gestione della connettività di rete, vedere gli endpoint di Office [365 US Government GCC High Endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o [Office 365 US Government](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle caratteristiche seguenti che sono esclusive per gli ambienti cloud del governo degli Stati Uniti:

-   Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi di Office 365 commerciali da Microsoft.
-   Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
-   L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
-   Gli ambienti cloud governativi sono conformi alle certificazioni e agli accreditamenti necessari per i clienti del settore pubblico degli Stati Uniti.

Il nostro obiettivo è offrire tutte le caratteristiche e le funzionalità commerciali di SharePoint agli ambienti cloud governativi. Alcune funzionalità non sono disponibili a causa dei requisiti dei clienti del cloud governativo. Altre caratteristiche vengono ritornate agli ambienti governativi, ma non ancora disponibili. Fare riferimento alle sezioni seguenti per informazioni sulla disponibilità delle funzionalità negli ambienti cloud governativi.

## <a name="developer-features"></a>Funzionalità per sviluppatori

Non esistono differenze note tra le funzionalità di sviluppo per i clienti commerciali e quelle per i clienti del cloud governativo.

- Le connessioni alle applicazioni esterne, ad esempio le origini dati per i componenti aggiuntivi, sono limitate alle origini che si trovano all'interno dei limiti di sicurezza del sistema supportati dall'ambiente governativo.
- La funzionalità di servizi di integrazione applicativa è supportata per gli scenari di connettività in cui le origini dati rimangono raggiungibili entro il limite di sicurezza per il servizio cloud.

Se si utilizzano applicazioni di terze parti nei siti, esaminare le istruzioni relative alla privacy e alla conformità fornite dalle terze parti durante la valutazione dell'utilizzo appropriato di questi servizi per la propria organizzazione. Le applicazioni e i servizi di terze parti possono comportare l'archiviazione, la trasmissione e l'elaborazione dei dati del cliente dell'organizzazione su sistemi di terze parti esterni al cloud governativo e pertanto non coperti dalla conformità e dagli impegni di protezione dei dati. 

## <a name="it-admin-features"></a>Funzionalità di amministrazione IT

Di seguito sono riportate le differenze tra le funzionalità di amministrazione IT per i clienti commerciali e quelle per i clienti del cloud governativo.

- La modifica di un indirizzo di sito non è disponibile per i clienti GCC High
- Il server ibrido di SharePoint non è disponibile per tutti i clienti del cloud governativo
- Lo strumento di migrazione di SharePoint e la gestione della migrazione richiedono una modifica di configurazione. Per informazioni, vedere [supporto per il cloud governativo di SPMT](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io non è ancora supportato
- Multi-Geo non è disponibile per tutti i clienti del cloud governativo

Per informazioni sulla migrazione di FastTrack, vedere la [Descrizione del servizio Office 365 US Government](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Funzionalità di sicurezza e conformità

Non esistono differenze note tra le funzionalità di sicurezza e conformità per i clienti commerciali e quelle per i clienti del cloud governativo.

Per informazioni sulle caratteristiche seguenti, vedere la [Descrizione del servizio Office 365 US Government](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features):
- Customer Lockbox
- Prevenzione della perdita di dati (DLP)
- eDiscovery (Ricerca contenuto, esenzione, esportazione)
- Office 365 Advanced Threat Protection (ATP)
- Etichette di riservatezza

Per informazioni sulle funzionalità di Azure Active Directory per il governo, vedere la [documentazione relativa alla sicurezza di Azure Government + Identity](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Per informazioni sulle funzionalità di protezione delle informazioni di Azure per Government, vedere la [Descrizione del servizio governativo di Azure Information Protection Premium](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Siti e contenuto

Di seguito sono rilevate le differenze tra i siti e le funzionalità di contenuto per i clienti commerciali e quelli per i clienti del cloud governativo:

- Le web part che si basano sulle connessioni a servizi Internet, ad esempio le web part Amazon Kindle, Bing Maps, Twitter e YouTube, non funzionano come previsto
- Raccolta di risorse dell'organizzazione non disponibile
- L'aggiunta di elenchi e pagine a team non è disponibile per i clienti GCC High e DoD

## <a name="search-features"></a>Caratteristiche per la ricerca

Di seguito sono rilevate le differenze tra le funzionalità di ricerca per i clienti commerciali e quelle per i clienti del cloud governativo:

- L'integrazione della ricerca di Microsoft non è disponibile.

## <a name="sharing-and-sync"></a>Condivisione e sincronizzazione

Per le differenze di funzionalità tra il cloud commerciale e gli ambienti cloud governativi, vedere [condivisione file](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).

## <a name="plan-for-governance"></a>Pianificare la governance

Lo spostamento nel cloud offre esperienze trasformative con i controlli di amministrazione incorporati. Determinare i requisiti per la governance e come raggiungerli. Andare a [pianificare la governance per trasformare il lavoro di squadra con Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) per ulteriori informazioni. Sono disponibili informazioni su gruppi di Office 365, SharePoint, teams e altro ancora.

## <a name="deploy-sharepoint-for-collaboration"></a>Distribuzione di SharePoint per la collaborazione

Dopo aver configurato l'organizzazione nel cloud di Microsoft US Government, seguire il percorso di distribuzione consigliato descritto nel [Centro risorse di adozione di SharePoint](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/). Assicurarsi di impegnarsi con i campioni di gestione per l'adozione e la modifica.
È inoltre possibile utilizzare [FastTrack](https://www.microsoft.com/fasttrack) o il partner scelto per implementare il servizio ai propri utenti.
Visitare il [Centro protezione Microsoft](https://www.microsoft.com/trust-center) per ulteriori informazioni sul modo in cui Microsoft approccia la sicurezza, la privacy e la conformità, principi fondamentali per il modo in cui le organizzazioni possono servire i propri clienti.
