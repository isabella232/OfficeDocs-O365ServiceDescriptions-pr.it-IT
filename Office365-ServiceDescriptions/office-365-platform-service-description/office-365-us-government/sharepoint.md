---
title: SharePoint per gli ambienti del governo statunitense
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Informazioni sulla disponibilità delle funzionalità di SharePoint per i clienti cloud del governo statunitense.
ms.openlocfilehash: b0f36ea92b856a3fa9c1bf4ddd4cb4265655d1ae
ms.sourcegitcommit: 9961f5111b2b8b871183afcd03fcfb7fc05da4fc
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/21/2021
ms.locfileid: "49919749"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint per gli ambienti del governo statunitense

In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud per enti pubblici degli Stati Uniti e il cloud commerciale, come indicato nella descrizione [del servizio SharePoint.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) SharePoint è disponibile per gli ambienti Government Community Cloud (GCC), GCC High e DoD. 

Per altre info sul cloud per enti pubblici, inclusi l'idoneità e l'acquisto, vedi [Microsoft 365 Government - come acquistare.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy) Per confrontare i piani di Office 365 Government, vedere [Piani di Office 365 Government.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Per informazioni sugli endpoint necessari per la gestione della connettività di rete, vedere gli endpoint GCC High di [Office 365 U.S. Government](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o Office [365 U.S. Government DoD.](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche degli ambienti cloud del governo statunitense:

-   I contenuti dei clienti dell'organizzazione sono logicamente separati dai contenuti dei clienti nei servizi commerciali di Office 365 da Microsoft.
-   Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
-   L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
-   Gli ambienti cloud per enti pubblici sono conformi alle certificazioni e agli accrediti necessari per i clienti del settore pubblico statunitense.

L'obiettivo è fornire tutte le funzionalità commerciali e di SharePoint agli ambienti cloud per enti pubblici. Alcune funzionalità non sono disponibili a causa dei requisiti dei clienti del cloud per enti pubblici. Altre funzionalità saranno disponibili negli ambienti per enti pubblici, ma non ancora disponibili. Fare riferimento alle sezioni seguenti per informazioni sulla disponibilità delle funzionalità negli ambienti cloud per enti pubblici.

## <a name="developer-features"></a>Funzionalità per sviluppatori

Non esistono differenze note tra le funzionalità per sviluppatori per i clienti commerciali e quelle per i clienti cloud per enti pubblici.

- Le connessioni ad applicazioni esterne, ad esempio le origini dati per i componenti aggiuntivi, sono limitate alle origini che si trovano all'interno dei limiti di sicurezza del sistema supportati dall'ambiente per enti pubblici.
- Servizi di integrazione applicativa (BCS) è supportata per gli scenari di connettività in cui le origini dati rimangono raggiungibili entro i limiti di sicurezza per il servizio cloud.

Se si utilizzano applicazioni di terze parti nei siti, esaminare le dichiarazioni sulla privacy e conformità fornite da terze parti durante la valutazione dell'uso appropriato di questi servizi per l'organizzazione. Le applicazioni e i servizi di terze parti potrebbero includere l'archiviazione, la trasmissione e l'elaborazione dei dati dei clienti dell'organizzazione in sistemi di terze parti esterni al cloud per enti pubblici e pertanto non coperti dagli impegni di conformità e protezione dei dati. 

## <a name="it-admin-features"></a>Funzionalità di amministrazione IT

Ecco le differenze tra le funzionalità di amministrazione IT per i clienti commerciali e quelle per i clienti cloud per enti pubblici.

- La modifica dell'indirizzo di un sito non è disponibile per i clienti GCC High
- SharePoint Server ibrido non è disponibile per tutti i clienti del cloud per enti pubblici
- Lo Strumento di migrazione di SharePoint e Gestione migrazione richiedono una modifica della configurazione. Per informazioni, vedere Supporto [del cloud per enti pubblici di SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io non è ancora supportato
- Multi-geo non è disponibile per tutti i clienti del cloud per enti pubblici

Per informazioni sulla migrazione FastTrack, vedere la descrizione del servizio [Office 365 US Government.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Funzionalità di sicurezza e conformità

Non esistono differenze note tra le funzionalità di sicurezza e conformità per i clienti commerciali e quelle per i clienti cloud per enti pubblici.

Per informazioni sulle funzionalità di sicurezza e conformità, vedere il [Centro sicurezza & conformità.](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)

Per informazioni sulle funzionalità di Azure Active Directory per enti pubblici, vedere la documentazione relativa a [Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Per informazioni sulle funzionalità di Azure Information Protection per enti pubblici, vedere la descrizione del [servizio Azure Information Protection Premium per enti pubblici.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Siti e contenuto

Ecco le differenze tra i siti e le funzionalità dei contenuti per i clienti commerciali e quelli per i clienti cloud per enti pubblici:

- Le web part che si basano su connessioni a servizi Internet, ad esempio le web part Amazon Amazon, Bing Maps, Twitter e YouTube, non funzionano come previsto
- La raccolta di risorse dell'organizzazione non è disponibile
- L'aggiunta di elenchi e pagine a Teams non è disponibile per i clienti GCC High e DoD
- La funzionalità graph all'interno di SharePoint Online per GCC High è attualmente disabilitata. I servizi che si basano su Microsoft Graph potrebbero non essere attualmente disponibili

## <a name="search-features"></a>Caratteristiche per la ricerca

Ecco le differenze tra le funzionalità di ricerca per i clienti commerciali e quelle per i clienti cloud per enti pubblici:

- L'integrazione di Microsoft Search non è disponibile.

## <a name="sharing-and-sync"></a>Condivisione e sincronizzazione

Per le differenze di funzionalità tra il cloud commerciale e gli ambienti cloud per enti pubblici, vedere [Condivisione di file.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)

## <a name="plan-for-governance"></a>Pianificare la governance

Il passaggio al cloud offre esperienze trasformative con i controlli di amministrazione predefiniti. Determinare i requisiti per la governance e come soddisfarli. Per altre informazioni, vedere Pianificare la governance per trasformare il [lavoro in team con Microsoft 365.](https://resources.techcommunity.microsoft.com/teamwork-governance/) Sono disponibili indicazioni su Gruppi di Office 365, SharePoint, Teams e altro ancora.

## <a name="deploy-sharepoint-for-collaboration"></a>Distribuire SharePoint per la collaborazione

Dopo aver configurato l'organizzazione nel cloud microsoft us government, seguire il percorso di distribuzione consigliato descritto nel Centro risorse per l'adozione [di SharePoint.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Assicurati di interagire con i tuoi campioni dell'adozione e della gestione delle modifiche.
È inoltre possibile collaborare con [FastTrack](https://www.microsoft.com/fasttrack) o con il partner scelto per implementare il servizio agli utenti.
Visitare il Centro protezione [Microsoft](https://www.microsoft.com/trust-center) per saperne di più su come Microsoft si approccia a sicurezza, privacy e conformità, principi fondamentali per il modo in cui microsoft consente alle organizzazioni di servire i propri clienti.
