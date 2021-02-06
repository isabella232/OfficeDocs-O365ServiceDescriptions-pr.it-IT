---
title: Centro sicurezza e conformità
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: Il Centro sicurezza e conformità è progettato per facilitare la gestione delle funzionalità di &amp; conformità in Office 365 per l'organizzazione. Nei collegamenti relativi alle funzionalità di conformità per SharePoint ed Exchange vengono raggruppate le funzionalità di conformità di Office 365.
ms.openlocfilehash: 0116ecf3f46c2d870d88a5d1ef53e18452a53e7b
ms.sourcegitcommit: f98239a5631ba312d63753ffce83a7413a143ee5
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/05/2021
ms.locfileid: "50122196"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Il [Centro sicurezza e &amp; conformità](https://protection.office.com/) è progettato per facilitare la gestione delle funzionalità di conformità in Office 365 per l'organizzazione. Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Per visualizzare le opzioni per la concessione delle licenze agli utenti per trarre vantaggio dalle funzionalità di conformità di Microsoft 365 a partire dal 1° aprile 2020, scaricare il confronto dettagliato delle licenze di conformità di Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>Disponibilità &amp; del Centro sicurezza e conformità per i piani aziendali e aziendali

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1, Office 365 US Government G1 | Office 365 E3, Office 365 US Government G3 | Office 365 E5 | Office 365 F3, Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Prevenzione della perdita dei dati per Exchange Online, SharePoint Online e OneDrive for Business](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup> | No | No  |No   | Sì | Sì | Sì | No  |
|[Etichette di riservatezza manuali](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | No | No  |No   | Sì | Sì | Sì | No  |
|[Casi di eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Blocchi di eDiscovery (inclusi i blocchi di eDiscovery basati su query)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |No   |No   |No  |No   |Sì   |Sì   |No   |
|[Esportazione eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |No   |No   |No   |Sì   |Sì   |No   |
|[Controllo di base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |Sì   |Sì   |Sì|Sì   |Sì   |Sì   |Sì   |
|[Office 365 Message Encryption (OME) Basic](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |No   |No   |No   |Sì  |Sì   |No   |

<sup>1</sup> I registri di controllo per tutti i piani che includono il controllo di base (ad eccezione di E5) vengono conservati per 90 giorni. Poiché E5 include Advanced Audit, i log di controllo vengono conservati per un massimo di un anno. Inoltre, è possibile usare [l'API office 365 Management Activity](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) per recuperare gli eventi dal log di controllo unificato.

<sup>2</sup> Richiede il componente aggiuntivo di prevenzione della perdita dei dati di Office 365.

<sup>3</sup> Le etichette di riservatezza sono incluse anche in Azure Information Protection P1 e P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>Disponibilità &amp; del Centro sicurezza e conformità per i piani autonomi

| Funzionalità | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online | SharePoint Online Piano 1 | SharePoint Online Piano 2 | OneDrive for Business Piano 1 | OneDrive for Business Piano 2 | Skype for Business online Piano 1 | Skype for Business online Piano 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |No   |No   |No   |No   |No   |No   |No   |No   |Sì   |
|[Gestione delle minacce,](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)ad esempio filtro della posta e antimalware   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Gestione avanzata delle minacce,](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)ad esempio Esplora minacce per campagne di phishing   |No   |No   |No   |No   |No   |No   |No   |No   |No  |
|[Customer Lockbox](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Gestione dei dispositivi mobili](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Prevenzione della perdita dei dati per Exchange Online, SharePoint Online e OneDrive for Business](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>  |No   |Sì   |No   |No   |Sì <sup>7<sup>  |No  |Sì<sup>10</sup> |No   |Sì   |
|[Prevenzione della perdita dei dati di comunicazione per Microsoft Teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Barriere informative](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Governance delle](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>informazioni 1</sup>  |Sì<sup>2</sup>  |Sì   |Sì   |Sì   |Sì   |Sì<sup>10</sup>  |Sì<sup>10</sup>  |Sì   |Sì   |
|[Governance avanzata delle](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>informazioni 3</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Ricerca contenuto](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Sì   |Sì   |Sì   |Sì   |Sì  | Sì<sup>10</sup>  |Sì<sup>10</sup>  |Sì   |Sì   |
|[Casi di eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì<sup>10</sup>  |Sì<sup>10</sup>  |No   |No   |
|[Esportazione eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |Sì   |No   |No   |Sì   |No  |Sì<sup>10</sup> |No<sup>4</sup>  |No<sup>4</sup>  |
|[Blocchi di eDiscovery (inclusi i blocchi di eDiscovery basati su query)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |No   |Sì   |No   |No   |Sì   |No  |Sì<sup>10</sup> |No<sup>4</sup>  |No<sup>4</sup>  |
|[Advanced eDiscovery](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Archiviazione](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |No   |Sì   |No   |Sì   |Sì   |Sì<sup>10</sup> |Sì<sup>10</sup>  |No   |No   |
|[Controllo di base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Sì|Sì|Sì|Sì|Sì|Sì<sup>10</sup>|Sì<sup>10</sup>|No|No|
|Audit avanzato|No|No|No|No|No|No|No|No|No|
|[Conformità delle comunicazioni (criteri di supervisione)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Office 365 Message Encryption (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |Sì   |No   |No   |Sì   |No   |No|No|No|
|[Office 365 Advanced Message Encryption](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |No   |No   |No   |No   |Sì   |No   |No|No|No|
|[Privileged Access Management](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |No   |No   |No   |No   |Sì   |No   |No|No|No|

<sup>1</sup> La governance delle informazioni consente agli utenti di creare, pubblicare e applicare manualmente etichette ai documenti; importare dati usando la spedizione unità o in rete. Queste funzionalità sono disponibili in E3 ed E5, con disponibilità limitata solo in E1. Per un elenco completo delle funzionalità disponibili in E1, E3 ed E5, vedere il confronto dettagliato delle licenze di conformità di Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> Richiede l'acquisto del componente aggiuntivo Archiviazione Exchange Online.

<sup>3</sup> Governance avanzata delle informazioni consente di conservare informazioni importanti ed eliminare informazioni non importanti classificando le informazioni in base a criteri di conservazione o eliminazione o entrambi. Include azioni intelligenti/automatizzate, ad esempio la raccomandazione di criteri, l'applicazione automatica di etichette ai dati, l'applicazione di etichette basate su tipi di dati sensibili o query, la revisione dell'eliminazione e l'uso di filtri per l'importazione intelligente. Include inoltre la funzionalità supervisione per la revisione delle comunicazioni dei dipendenti per motivi di sicurezza e conformità.

<sup>4</sup> Le conversazioni di Skype vengono memorizzate come parte della cassetta postale.

<sup>5</sup> Advanced eDiscovery richiede Office 365 E5 o una licenza per i componenti aggiuntivi.

<sup>6 L'archiviazione</sup> Skype è all'interno della cassetta postale dell'utente.

<sup>7</sup> Include i file archiviati negli archivi di Microsoft Teams.

<sup>8</sup> I registri di controllo per tutti i piani che includono il controllo di base vengono conservati per 90 giorni. Inoltre, è possibile usare [l'API office 365 Management Activity](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) per recuperare gli eventi dal log di controllo unificato.

<sup>9</sup> Richiede il componente aggiuntivo di prevenzione della perdita dei dati di Office 365.

<sup>10</sup> Limitato ai file archiviati in OneDrive for Business.

<sup>11</sup> È necessaria una licenza di Exchange Online Piano 2 o Archiviazione Exchange Online per mettere in attesa una cassetta postale utente utilizzando un criterio di conservazione.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

Centro conformità è disponibile nel piano E3 per Office 365 gestito da 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

Il Centro sicurezza & conformità è disponibile per Office 365 Germany. Per informazioni su Office 365 Germany, vedere [Office 365 Germany.](office-365-germany.md)
