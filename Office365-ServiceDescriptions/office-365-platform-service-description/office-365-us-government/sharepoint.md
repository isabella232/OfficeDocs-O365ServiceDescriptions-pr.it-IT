---
title: Ambienti di SharePoint per enti pubblici statunitensi
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Informazioni sulla disponibilità delle funzionalità di SharePoint per i clienti del cloud per enti pubblici statunitensi.
ms.openlocfilehash: fc782a01c99165fbf19156250e09220656d46ba3
ms.sourcegitcommit: ab82834030929e1583074b3f5b0b27182746fff4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/19/2021
ms.locfileid: "50902026"
---
# <a name="sharepoint-for-us-government-environments"></a>Ambienti di SharePoint per enti pubblici statunitensi

In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud del governo statunitense e il cloud commerciale, come indicato nella descrizione [del servizio SharePoint.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) SharePoint è disponibile per gli ambienti Government Community Cloud (GCC), GCC High e DoD. 

Per altre info sul cloud per enti pubblici, inclusi l'idoneità e l'acquisto, vedi [Microsoft 365 Government - come acquistare](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Per confrontare i piani di Office 365 Government, vedere Piani di [Office 365 Government.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Per informazioni sugli endpoint necessari per la gestione della connettività di rete, vedere gli [endpoint Office 365 U.S. Government GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o Office [365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche degli ambienti cloud del governo statunitense:

-   Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi commerciali di Office 365 da Microsoft.
-   Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
-   L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
-   Gli ambienti cloud governativi sono conformi alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

L'obiettivo è fornire tutte le funzionalità e le funzionalità commerciali di SharePoint agli ambienti cloud per enti pubblici. Alcune funzionalità non sono disponibili a causa dei requisiti dei clienti cloud per enti pubblici. Altre funzionalità sono disponibili negli ambienti governativi, ma non sono ancora disponibili. Fare riferimento alle sezioni seguenti per informazioni sulla disponibilità delle funzionalità negli ambienti cloud per enti pubblici.

## <a name="developer-features"></a>Funzionalità per sviluppatori

Non esistono differenze note tra le funzionalità di sviluppo per i clienti commerciali e quelle per i clienti cloud governativi.

- Le connessioni ad applicazioni esterne, ad esempio origini dati per i componenti aggiuntivi, sono limitate alle origini che si trovano all'interno dei limiti di sicurezza del sistema supportati dall'ambiente governativo.
- Servizi di integrazione applicativa (BCS) è supportata per gli scenari di connettività in cui le origini dati rimangono raggiungibili entro il limite di sicurezza per il servizio cloud.

Se si utilizzano applicazioni di terze parti nei siti, esaminare le istruzioni sulla privacy e conformità fornite da terze parti durante la valutazione dell'uso appropriato di questi servizi per l'organizzazione. Le applicazioni e i servizi di terze parti potrebbero comportare l'archiviazione, la trasmissione e l'elaborazione dei dati dei clienti dell'organizzazione in sistemi di terze parti esterni al cloud pubblico e pertanto non coperti dagli impegni di conformità e protezione dei dati. 

## <a name="it-admin-features"></a>Funzionalità di amministrazione IT

Ecco le differenze tra le funzionalità di amministrazione IT per i clienti commerciali e quelle per i clienti cloud governativi.

- La modifica dell'indirizzo di un sito non è disponibile per i clienti GCC High
- SharePoint Server ibrido non è disponibile per tutti i clienti del cloud per enti pubblici
- Lo Strumento di migrazione di SharePoint e Gestione migrazione richiedono una modifica della configurazione. Per info, vedi [Supporto del cloud per enti pubblici di SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io non è ancora supportato
- Multi-geo non è disponibile per tutti i clienti del cloud per enti pubblici

Per informazioni sulla migrazione di FastTrack, vedere la descrizione del servizio [Office 365 US Government.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Funzionalità di sicurezza e conformità

Non esistono differenze note tra le funzionalità di sicurezza e conformità per i clienti commerciali e quelle per i clienti cloud governativi.

Per informazioni sulle funzionalità di sicurezza e conformità, vedere [il Centro sicurezza & conformità](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center).

Per informazioni sulle funzionalità di Azure Active Directory per enti pubblici, vedere la documentazione relativa a [Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Per informazioni sulle funzionalità di Azure Information Protection per enti pubblici, vedere Descrizione del servizio Azure [Information Protection Premium Per enti pubblici.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Siti e contenuto

Ecco le differenze tra i siti e le funzionalità di contenuto per i clienti commerciali e quelli per i clienti cloud per enti pubblici:

- Le web part che si basano su connessioni a servizi Internet, ad esempio le web part Amazon Kindle, Bing Maps, Twitter e YouTube, non funzionano come previsto
- La raccolta risorse dell'organizzazione non è disponibile
- L'aggiunta di elenchi e pagine a Teams non è disponibile per i clienti GCC High e DoD
- La funzionalità grafico all'interno di SharePoint Online per GCC High è attualmente disabilitata. I servizi che si basano su Microsoft Graph potrebbero non essere attualmente disponibili
- Le funzionalità che si basano sulle connessioni ai servizi Internet, ad esempio la scheda Immagini azionarie, non funzionano come previsto
- Le notifiche per le attività di file e siti non sono disponibili

## <a name="search-features"></a>Caratteristiche per la ricerca

Ecco le differenze tra le funzionalità di ricerca per i clienti commerciali e quelle per i clienti cloud governativi:

- L'integrazione di Microsoft Search non è disponibile.

## <a name="sharing-and-sync"></a>Condivisione e sincronizzazione

Per le differenze di funzionalità tra il cloud commerciale e gli ambienti cloud per enti pubblici, vedi [Condivisione di file.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)

## <a name="plan-for-governance"></a>Pianificare la governance

Il passaggio al cloud offre esperienze trasformative con i controlli di amministrazione incorporati. Determinare i requisiti per la governance e come soddisfarli. Per ulteriori [informazioni, vedere Plan for governance to transform teamwork with Microsoft 365.](https://resources.techcommunity.microsoft.com/teamwork-governance/) Sono disponibili indicazioni su Gruppi di Office 365, SharePoint, Teams e altro ancora.

## <a name="deploy-sharepoint-for-collaboration"></a>Distribuire SharePoint per la collaborazione

Dopo aver configurato l'organizzazione nel cloud microsoft us government, seguire il percorso di distribuzione consigliato descritto nel Centro risorse per l'adozione [di SharePoint.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Assicurati di interagire con i tuoi campioni di adozione e gestione delle modifiche.
Puoi anche collaborare con [FastTrack](https://www.microsoft.com/fasttrack) o il partner scelto per implementare il servizio agli utenti.
Visita il Centro protezione [Microsoft](https://www.microsoft.com/trust-center) per saperne di più su come Microsoft si approccia alla sicurezza, alla privacy e alla conformità, principi fondamentali per il modo in cui consentiamo alle organizzazioni di servire i propri clienti.
