---
title: SharePoint per ambienti governativi statunitensi
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Informazioni sulla disponibilità delle SharePoint per i clienti cloud del governo statunitense.
ms.openlocfilehash: 1c584c3bfd62b7573f4c9bcc0c0fb5402b2d9bef
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59673004"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint per ambienti governativi statunitensi

In questo articolo viene fornita una panoramica delle differenze di funzionalità tra il cloud governativo statunitense e il cloud commerciale, come indicato nella descrizione SharePoint [servizio.](../../sharepoint-online-service-description/sharepoint-online-service-description.md) SharePoint è disponibile per gli ambienti Government Community Cloud (GCC), GCC High e DoD. 

Per altre info sul cloud per enti pubblici, inclusi l'idoneità e l'acquisto, vedi [Microsoft 365 Government - come acquistare](./microsoft-365-government-how-to-buy.md). Per confrontare Office 365 Government piani, vedere [Office 365 Government piani.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Per informazioni sugli endpoint necessari per la gestione della connettività di rete, vedere Office 365 [U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) o [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche degli ambienti cloud governativi statunitensi:

-   Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi Office 365 commerciali da Microsoft.
-   Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
-   L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
-   Gli ambienti cloud governativi sono conformi alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

L'obiettivo è fornire tutte le funzionalità SharePoint commerciali agli ambienti cloud governativi. Alcune funzionalità non sono disponibili a causa dei requisiti dei clienti cloud per enti pubblici. Altre funzionalità sono disponibili negli ambienti governativi, ma non sono ancora disponibili. Fare riferimento alle sezioni seguenti per informazioni sulla disponibilità delle funzionalità negli ambienti cloud per enti pubblici.

## <a name="developer-features"></a>Funzionalità per sviluppatori

Non esistono differenze note tra le funzionalità di sviluppo per i clienti commerciali e le funzionalità di sviluppo per i clienti cloud per enti pubblici.

- Le connessioni ad applicazioni esterne, ad esempio origini dati per i componenti aggiuntivi, sono limitate alle origini che si trovano all'interno dei limiti di sicurezza del sistema supportati dall'ambiente governativo.
- Servizi di integrazione applicativa (BCS) è supportata per gli scenari di connettività in cui le origini dati rimangono raggiungibili entro il limite di sicurezza per il servizio cloud.

Se si utilizzano applicazioni di terze parti nei siti, esaminare le istruzioni sulla privacy e conformità fornite da terze parti durante la valutazione dell'uso appropriato di questi servizi per l'organizzazione. Le applicazioni e i servizi di terze parti potrebbero comportare l'archiviazione, la trasmissione e l'elaborazione dei dati dei clienti dell'organizzazione in sistemi di terze parti esterni al cloud pubblico e pertanto non coperti dagli impegni di conformità e protezione dei dati. 

## <a name="it-admin-features"></a>Funzionalità di amministrazione IT

Ecco le differenze tra le funzionalità di amministrazione IT per i clienti commerciali e le funzionalità di amministrazione IT per i clienti cloud governativi.

- La modifica dell'indirizzo di un sito non è disponibile GCC clienti high
- Lo strumento SharePoint migrazione e Gestione migrazione richiedono una modifica della configurazione. Per info, vedi Supporto del cloud per enti [pubblici di SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io non è ancora supportato
- Multi-geo non è disponibile per tutti i clienti del cloud per enti pubblici

Per info sulla FastTrack migrazione, vedi la [descrizione](./office-365-us-government.md#data-migrations-performed-by-fasttrack)Office 365 servizio us government .

## <a name="security-and-compliance-features"></a>Funzionalità di sicurezza e conformità

Non esistono differenze note tra le funzionalità di sicurezza e conformità per i clienti commerciali e le funzionalità di sicurezza e conformità per i clienti cloud governativi.

Per informazioni sulle funzionalità di sicurezza e conformità, vedere [Il Centro sicurezza & conformità](../office-365-securitycompliance-center.md).

Per informazioni sulle Azure Active Directory per enti pubblici, vedere la documentazione relativa a [Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Per informazioni sulle funzionalità di Azure Information Protection per enti pubblici, vedere Descrizione del servizio [Azure Information Protection Premium Government](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description). 

Per informazioni sulle funzionalità SharePoint Syntex, vedere la SharePoint Syntex [Descrizione del servizio.](/office365/servicedescriptions/sharepoint-syntex-service-description/sharepoint-syntex-features)

## <a name="sites-and-content"></a>Siti e contenuto

Ecco le differenze tra i siti e le caratteristiche di contenuto per i clienti commerciali e le caratteristiche di siti e contenuti per i clienti cloud per enti pubblici:

- Le web part che si basano su connessioni a servizi Internet, ad esempio le web part Amazon Kindle, Bing Maps, Twitter e YouTube, non funzionano come previsto
- La raccolta risorse dell'organizzazione non è disponibile
- L'aggiunta di elenchi e pagine Teams non è disponibile per GCC clienti High e DoD
- Graph funzionalità all'interno di SharePoint Online per GCC High è attualmente disabilitata. Qualsiasi servizio che si basa su Microsoft Graph potrebbe non essere attualmente disponibile
- Le funzionalità che si basano sulle connessioni ai servizi Internet, ad esempio la scheda Immagini azionarie, non funzionano come previsto
- Le notifiche per le attività di file e siti non sono disponibili
- La web part notizie estrarrà solo le notizie dal sito corrente. Le notizie dai siti selezionati o dagli aggiornamenti cumulativi delle notizie hub dai siti associati non sono disponibili per i GCC High e DoD

## <a name="search-features"></a>Caratteristiche per la ricerca

Ecco le differenze tra le funzionalità di ricerca per i clienti commerciali e le funzionalità di ricerca per i clienti cloud governativi:

- Microsoft Search non è disponibile in GCC.

## <a name="sharing-and-sync"></a>Condivisione e sincronizzazione

Per le differenze di funzionalità tra il cloud commerciale e gli ambienti cloud per enti pubblici, vedi [Condivisione di file.](./gcc-high-and-dod.md#file-sharing)

## <a name="plan-for-governance"></a>Pianificare la governance

Il passaggio al cloud offre esperienze trasformative con i controlli di amministrazione incorporati. Determinare i requisiti per la governance e come soddisfarli. Vai a [Pianificare la governance per trasformare il lavoro in team con Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) per altre informazioni. Troverai indicazioni su Office 365 gruppi, SharePoint, Teams e altro ancora.

## <a name="deploy-sharepoint-for-collaboration"></a>Distribuire SharePoint per la collaborazione

Dopo aver configurato l'organizzazione nel cloud di Microsoft US Government, seguire il percorso di distribuzione consigliato descritto nel Centro risorse per l'adozione SharePoint [di distribuzione.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Assicurati di interagire con i tuoi campioni di adozione e gestione delle modifiche.
È inoltre possibile collaborare con [FastTrack](https://www.microsoft.com/fasttrack) o con il partner scelto per implementare il servizio agli utenti.
Visita il Centro protezione [Microsoft](https://www.microsoft.com/trust-center) per saperne di più su come Microsoft si approccia alla sicurezza, alla privacy e alla conformità, principi fondamentali per il modo in cui consentiamo alle organizzazioni di servire i propri clienti.

## <a name="configuring-sharepoint-hybrid-configuration-wizard-support-for-all-government-cloud-customers"></a>Configurazione del SharePoint configurazione ibrida guidata per tutti i clienti del cloud per enti pubblici

La SharePoint guidata di configurazione ibrida SharePoint supporto per le funzionalità ibride con ambienti SPO speciali.

È necessario modificare il valore di un parametro correlato all'ambiente in un file **.config** per rendere disponibili le funzionalità ibride SharePoint per tale ambiente. Vedere [Modifica del file di configurazione](#editing-configuration-file).

> [!NOTE]
> Per informazioni sugli ambienti spo speciali per i quali le SharePoint ibride offrono supporto, vedere [Supported Environments.](#supported-environments)

## <a name="editing-configuration-file"></a>Modifica del file di configurazione

1. Installare o aggiornare la procedura guidata SharePoint configurazione ibrida.
2. Passare alla cartella in cui è installata la SharePoint configurazione ibrida guidata. Per esempio `%LOCALAPPDATA%\Apps\HybridSP\HybridSP`
3. Avvia il **microsoft.online.cse.hybridsp.common.dll.config** file in un editor di testo, ad esempio Blocco note.
Il contenuto di questo file è illustrato nello screenshot seguente:

:::image type="content" source="../../media/content.png" alt-text="Contenuto nel file di configurazione":::

4. Modificare il valore del `SPOEnvironmentType` parametro.
5. Salvare le modifiche nel file **microsoft.online.cse.hybridsp.common.dll.config** file.
6. Avviare di nuovo la SharePoint configurazione ibrida guidata.
   Le impostazioni vengono applicate e le SharePoint ibride sono disponibili nell'ambiente spo configurato.

## <a name="supported-environments"></a>Ambienti supportati

SharePoint le funzionalità ibride supportano i seguenti ambienti SPO:

- Pubblico
- PPE
- GCC
- GccHigh
- DoD
- Personalizzato

Se un cliente imposta il valore su Custom, le chiavi , e vengono utilizzate per impostare tali `SPOEnvironmentType` endpoint per  `AuthorityEndPoint` `AADGraphEndPoint` `MSGraphEndPoint` l'ambiente spo personalizzato.

Se il valore è impostato su un valore diverso da Custom , le chiavi , e vengono ignorate e la procedura guidata di configurazione ibrida di SharePoint utilizza valori hardcoded appropriati per tali tipi di ambiente `SPOEnvironmentType`  `AuthorityEndPoint` di `AADGraphEndPoint` `MSGraphEndPoint` SharePoint Server.
