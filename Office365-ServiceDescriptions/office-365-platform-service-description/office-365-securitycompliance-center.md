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
description: Il &amp; Centro sicurezza e conformità è stato creato per semplificare la gestione delle funzionalità di conformità tra Office 365 per l'organizzazione. Nei collegamenti relativi alle funzionalità di conformità per SharePoint ed Exchange vengono raggruppate le funzionalità di conformità di Office 365.
ms.openlocfilehash: 4537008977f19ef947ea0bae9a4164cfbe9991d4
ms.sourcegitcommit: ee08ab6a47235054d5029807ab79fba546326273
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 12/31/2020
ms.locfileid: "49740967"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Il [Centro sicurezza e &amp; conformità](https://protection.office.com/) è stato creato per semplificare la gestione delle funzionalità di conformità tra Office 365 per l'organizzazione. Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Per visualizzare le opzioni per la concessione delle licenze agli utenti per usufruire delle funzionalità di conformità di Microsoft 365 del 1 ° aprile 2020, scaricare il confronto dettagliato di Microsoft 365 Compliance Licensing. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>&amp;Disponibilità del Centro sicurezza e conformità per i piani business e Enterprise

| Funzionalità | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1, Office 365 US Government G1 | Office 365 E3, Office 365 US Government G3 | Office 365 E5 | Office 365 F3, Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Prevenzione della perdita di dati per Exchange Online, SharePoint Online e OneDrive for business](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup> | No | No  |No   | Sì | Sì | Sì | No  |
|[Etichette di riservatezza manuali](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | No | No  |No   | Sì | Sì | Sì | No  |
|[casi di eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[eDiscovery contiene (incluse le esenzioni di eDiscovery basate su query)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |No   |No   |No  |No   |Sì   |Sì   |No   |
|[Esportazione eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |No   |No   |No   |Sì   |Sì   |No   |
|[Controllo di base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |Sì   |Sì   |Sì|Sì   |Sì   |Sì   |Sì   |
|[Base di crittografia dei messaggi di Office 365 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |No   |No   |No   |Sì  |Sì   |No   |

<sup>1</sup> i registri di controllo per tutti i piani che includono il controllo di base (ad eccezione di E5) vengono conservati per 90 giorni. Poiché E5 include un controllo avanzato, i registri di controllo vengono conservati per un massimo di un anno. Inoltre, è possibile utilizzare l' [API di attività di gestione di Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) per recuperare gli eventi dal registro di controllo unificato.

<sup>2</sup> richiede un componente aggiuntivo di prevenzione della perdita di dati di Office 365.

<sup>3</sup> le etichette di riservatezza sono incluse anche in Azure Information Protection P1 e P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>&amp;Disponibilità del Centro sicurezza e conformità per i piani autonomi

| Funzionalità | Exchange Online Piano 1 | Exchange Online, piano 2 | Chiosco Exchange Online | SharePoint Online Piano 1 | SharePoint Online Piano 2 | OneDrive for Business Piano 1 | OneDrive for Business Piano 2 | Skype for Business online Piano 1 | Skype for Business online Piano 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |No   |No   |No   |No   |No   |No   |No   |No   |Sì   |
|[Gestione delle minacce](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security), ad esempio il filtro della posta e antimalware   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Gestione avanzata delle minacce](https://docs.microsoft.com/office365/securitycompliance/office-365-ti), ad esempio Esplora minacce per le campagne di phishing   |No   |No   |No   |No   |No   |No   |No   |No   |No  |
|[Customer Lockbox](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Gestione dei dispositivi mobili](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |Sì   |
|[Prevenzione della perdita di dati per Exchange Online, SharePoint Online e OneDrive for business](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>  |No   |Sì   |No   |No   |Sì <sup>7<sup>  |No  |Sì<sup>10</sup> |No   |Sì   |
|[Prevenzione della perdita dei dati di comunicazione per Microsoft Teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Barriere informative](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Information Governance](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |Sì<sup>2</sup>  |Sì   |Sì   |Sì   |Sì   |Sì<sup>10</sup>  |Sì<sup>10</sup>  |Sì   |Sì   |
|[Governance delle informazioni avanzate](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Ricerca contenuto](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Sì   |Sì   |Sì   |Sì   |Sì  | Sì<sup>10</sup>  |Sì<sup>10</sup>  |Sì   |Sì   |
|[casi di eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sì   |Sì   |Sì   |Sì   |Sì   |Sì<sup>10</sup>  |Sì<sup>10</sup>  |No   |No   |
|[Esportazione eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |No   |Sì   |No   |No   |Sì   |No  |Sì<sup>10</sup> |N.<sup>4</sup>  |N.<sup>4</sup>  |
|[eDiscovery contiene (incluse le esenzioni di eDiscovery basate su query)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |No   |Sì   |No   |No   |Sì   |No  |Sì<sup>10</sup> |N.<sup>4</sup>  |N.<sup>4</sup>  |
|[Advanced eDiscovery](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Archiviazione](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |No   |Sì   |No   |Sì   |Sì   |Sì<sup>10</sup> |Sì<sup>10</sup>  |No   |No   |
|[Audit di base](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Sì|Sì|Sì|Sì|Sì|Sì<sup>10</sup>|Sì<sup>10</sup>|No|No|
|Audit avanzato|No|No|No|No|No|No|No|No|No|
|[Conformità alla comunicazione (criteri di supervisione)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |No   |No   |No   |No   |No   |No   |No   |No   |No   |
|[Office 365 Message Encryption (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |No   |No   |No   |No   |Sì   |No   |No|No|No|
|[Office 365 Advanced Message Encryption](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |No   |No   |No   |No   |Sì   |No   |No|No|No|
|[Gestione degli accessi con privilegi](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |No   |No   |No   |No   |Sì   |No   |No|No|No|

<sup>1</sup> la governance delle informazioni consente agli utenti di creare, pubblicare e applicare manualmente etichette ai documenti; importare i dati utilizzando l'unità di trasporto o la rete. Queste funzionalità sono disponibili in E3 ed E5, con disponibilità limitata solo in E1. Per un elenco completo delle funzionalità disponibili in E1, E3 ed E5, vedere il confronto delle licenze di conformità di Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> Richiede l'acquisto del componente aggiuntivo Archiviazione Exchange Online.

<sup>3</sup> Advanced Information Governance consente di conservare informazioni importanti ed eliminare informazioni non importanti classificando le informazioni basate su un criterio di conservazione o eliminazione o entrambe. Include azioni intelligenti/automatiche come la raccomandazione di criteri, l'applicazione automatica di etichette ai dati, l'applicazione di etichette basate su query o tipi di dati sensibili, la revisione della disposizione e l'utilizzo di filtri di importazione intelligenti. Include inoltre la funzionalità di supervisione per la revisione delle comunicazioni dei dipendenti per motivi di sicurezza e conformità.

<sup>4</sup> Le conversazioni di Skype vengono memorizzate come parte della cassetta postale.

<sup>5</sup> Advanced eDiscovery richiede Office 365 E5 o una licenza del componente aggiuntivo.

<sup>6</sup> l'archiviazione Skype è all'interno della cassetta postale dell'utente.

<sup>7</sup> include i file archiviati nei repository di Microsoft teams.

<sup>8</sup> registri di controllo per tutti i piani che includono il controllo di base vengono conservati per 90 giorni. Inoltre, è possibile utilizzare l' [API di attività di gestione di Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) per recuperare gli eventi dal registro di controllo unificato.

<sup>9</sup> richiede un componente aggiuntivo di prevenzione della perdita di dati di Office 365.

<sup>10</sup> limitato ai file archiviati in OneDrive for business.

<sup>11</sup> è richiesta una licenza di archiviazione di Exchange Online piano 2 o Exchange Online per inserire una cassetta postale utente in attesa utilizzando un criterio di conservazione.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

Il centro conformità è disponibile nel piano E3 per Office 365 gestito da 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

Il Centro sicurezza & conformità è disponibile per Office 365 Germany. Per informazioni su Office 365 Germany, vedere [office 365 Germany](office-365-germany.md).
