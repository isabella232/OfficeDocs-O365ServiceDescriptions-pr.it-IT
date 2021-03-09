---
title: Linee guida sulle licenze di Microsoft 365 per la sicurezza & conformità
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Questo articolo fornisce indicazioni sulle licenze per la conformità di Microsoft 365 per evitare potenziali interruzioni del servizio a causa dell'accesso senza licenza.
ms.openlocfilehash: 68bbb37734f1fc708e0b05ef3b152cf878757b48
ms.sourcegitcommit: 96a8a38f35778b455814b6174b8e68e2feda8746
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/09/2021
ms.locfileid: "50572722"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Guida alle licenze di Microsoft 365 per la conformità della &amp; sicurezza

Ai fini di questo articolo, un servizio a livello di tenant è un servizio online che, se acquistato per qualsiasi utente nel tenant (autonomo o come parte dei piani &mdash; di Office 365 o Microsoft 365), viene attivato in parte o per intero per tutti gli utenti nel &mdash; tenant. Anche se alcuni utenti senza licenza possono tecnicamente essere in grado di accedere al servizio, è necessaria una licenza per qualsiasi utente che si intende trarre vantaggio dal servizio.

> [!NOTE]
> Alcuni servizi tenant non sono attualmente in grado di limitare i vantaggi a utenti specifici. È necessario fare tutto il possibile per limitare i vantaggi del servizio agli utenti con licenza. Ciò consente di evitare potenziali interruzioni del servizio nell'organizzazione una volta che le funzionalità di destinazione sono disponibili.

Per vedere le opzioni per la concessione delle licenze agli utenti per trarre vantaggio dalle funzionalità di conformità di Microsoft 365 a partire dal 1° aprile 2020, scaricare il confronto dettagliato delle licenze di conformità di Microsoft 365. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection è una funzionalità del piano P2 di Azure Active Directory Premium che consente di rilevare potenziali vulnerabilità che influiscono sulle identità dell'organizzazione, configurare risposte automatizzate per rilevare azioni sospette correlate alle identità dell'organizzazione e analizzare gli incidenti sospetti e intraprendere le azioni appropriate per risolverli.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOps traggono vantaggio dall'avere visualizzazioni consolidate di utenti contrassegnati ed eventi di rischio basati su algoritmi di apprendimento automatico. Gli utenti finali traggono vantaggio dalla protezione automatica fornita tramite l'accesso condizionale basato sul rischio e dalla maggiore sicurezza fornita agendo sulle vulnerabilità.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e Azure Active Directory Premium Piano 2 forniscono a un utente i diritti per trarre vantaggio da Azure Active Directory Identity Protection.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Azure AD Identity Protection sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni su Azure AD Identity Protection, vedere [Che cos'è Identity Protection?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono definire l'ambito di Azure AD Identity Protection assegnando criteri di rischio che definiscono il livello di reimpostazione della password e consentendo l'accesso solo agli utenti con licenza. Per istruzioni su come impostare l'ambito delle distribuzioni di Azure AD Identity Protection, vedere [Come configurare e abilitare i criteri di rischio.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Identity Governance consente di bilanciare le esigenze di sicurezza e produttività dei dipendenti dell'organizzazione con i processi e la visibilità necessari. Utilizza la gestione dei diritti, le verifiche di accesso, la gestione delle identità privilegiate e i criteri di utilizzo per garantire che le persone giuste hanno il diritto di accedere alle risorse giuste.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Azure Active Directory Identity Governance aumenta la produttività degli utenti rendendo più semplice richiedere l'accesso ad app, gruppi e Microsoft Teams in un unico pacchetto di accesso. Gli utenti possono inoltre essere configurati come responsabili approvazione, senza coinvolgere gli amministratori. Per le verifiche di accesso, gli utenti possono esaminare le appartenenze ai gruppi con consigli intelligenti per intervenire a intervalli regolari.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e Azure Active Directory Premium Piano 2 forniscono a un utente i diritti per trarre vantaggio da Azure Active Directory Identity Governance.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Le funzionalità di Azure AD Identity Governance sono abilitate a livello di tenant, ma implementate per ogni utente. Per informazioni su Azure AD Identity Governance, vedere [Che cos'è Azure AD Identity Governance?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono impostare l'ambito di Azure AD Identity Governance assegnando pacchetti di accesso, verifiche di accesso o gestione delle identità privilegiate solo per gli utenti con licenza. Per istruzioni su come impostare l'ambito delle distribuzioni di Azure AD Identity Governance, vedere:

- [Requisiti di licenza per la gestione dei diritti di Azure AD](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisiti di licenza per la verifica dell'accesso di Azure AD](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisiti di licenza per l'utilizzo di Privileged Identity Management](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Che cosa è Microsoft Defender per identità?

Microsoft Defender for Identity (in precedenza Azure Advanced Threat Protection) è un servizio cloud che consente di proteggere gli ambienti ibridi aziendali da più tipi di attacchi informatici mirati avanzati e minacce Insider.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza SecOp traggono vantaggio dalla capacità di Microsoft Defender for Identity di rilevare e analizzare minacce avanzate, identità compromesse e azioni Insider dannose. Gli utenti finali traggono vantaggio dal monitoraggio dei dati da Parte di Microsoft Defender per l'identità.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Microsoft Defender for Identity for Users forniscono i diritti per trarre vantaggio da Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender for Identity sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Azure ATP, vedere [Creare l'istanza di Microsoft Defender for Identity.](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

I servizi Microsoft Defender for Identity non sono attualmente in grado di limitare le funzionalità a utenti specifici. Devi ottenere una licenza per ogni utente che intendi trarre vantaggio.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender per Office 365

Microsoft Defender per Office 365 (in precedenza Office 365 Advanced Threat Protection) consente di proteggere le organizzazioni da attacchi sofisticati come phishing e malware zero-day. Microsoft Defender per Office 365 fornisce anche informazioni utili correlando i segnali provenienti da un'ampia gamma di dati per identificare, definire le priorità e fornire consigli su come affrontare potenziali minacce.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Microsoft Defender per Office 365 protegge gli utenti da attacchi sofisticati come phishing e malware zero-day. Per l'elenco completo dei servizi forniti in Piano 1 e Piano 2, vedere [Microsoft Defender per Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio? 

Microsoft Defender per Office 365 Piani 1 e 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Microsoft 365 Business Premium forniscono a un utente i diritti per trarre vantaggio da Microsoft Defender per Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender per Office 365 sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri di Microsoft Defender per Office 365 per gli utenti con licenza, vedere [Microsoft Defender per Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Per impostare l'ambito di Microsoft Defender per Office 365, seguire i criteri di distribuzione Collegamenti sicuri e Allegati sicuri:

- Per informazioni sulla configurazione dei collegamenti sicuri per gli utenti con licenza, vedere [Collegamenti sicuri in Microsoft Defender per Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

- Per informazioni sulla configurazione degli allegati sicuri per gli utenti con licenza, vedere Allegati sicuri [in Microsoft Defender per Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) è un sottoinsieme di Microsoft Cloud App Security, con funzionalità limitate a Office 365 e senza ulteriore sicurezza per le app cloud di terze parti e i servizi IaaS.

OCAS offre alle organizzazioni visibilità sulle proprie app e servizi cloud di produttività, fornisce analisi sofisticate per identificare e contrastare le minacce informatiche e consente loro di controllare il modo in cui i dati viaggiano in &mdash; Office 365.

Per confrontare le funzionalità, vedere [Differenze tra Microsoft Cloud App Security e Office 365 Cloud App Security.](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

OCAS individua Shadow IT, fornisce protezione dalle minacce in Office 365 e può controllare quali app sono autorizzati ad accedere ai dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Office 365 E5/A3/A5/G5 fornisce a un utente i diritti per trarre vantaggio da OCAS.
Per altre informazioni, vedi il foglio dati sulle licenze di [Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità OCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione del servizio, vedere [Configurazione di base per Cloud App Security.](https://docs.microsoft.com/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono applicare l'ambito delle distribuzioni OCAS per applicare l'accesso a determinate app e limitare i gruppi di utenti monitorati da Office 365 Cloud App Security. Per ulteriori informazioni, vedere [Distribuzione con ambito.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) è una soluzione CasB (Cloud Access Security Broker) che offre alle organizzazioni visibilità sulle proprie app e servizi cloud, fornisce analisi sofisticate per identificare e contrastare le minacce informatiche e consente loro di controllare il modo in cui i dati viaggiano in qualsiasi &mdash; app cloud.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

MCAS individua e valuta Shadow IT, fornisce protezione dalle minacce nelle app cloud di prima e di terze parti e protegge le informazioni nelle app cloud di prima e di terze parti.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance, and Microsoft 365 Information Protection and Governance provide the rights for a user to benefit from MCAS.

Azure AD P1 fornisce a un utente i diritti per trarre vantaggio dalle funzionalità di individuazione in MCAS.

Per trarre vantaggio dalle funzionalità di controllo delle app di accesso condizionale in MCAS, gli utenti devono disporre anche della licenza per Azure Active Directory P1, incluso in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security.

Per trarre vantaggio dall'etichettatura automatica sul lato client, gli utenti devono disporre della licenza per Azure Information Protection P2, incluso in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance.

> [!NOTE]
> L'etichettatura automatica sul lato server richiede Information Protection per Office 365 - Licenze Premium ( `MIP_S_CLP2` o `efb0351d-3b08-4503-993d-383af8de41e3` ). Per informazioni di riferimento, vedere [Nomi dei prodotti e identificatori del piano di servizio per le licenze.](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Per altre informazioni, vedi il foglio dati sulle licenze di [Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità MCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione dei criteri di Microsoft Cloud App Security per gli utenti con licenza, vedere [Panoramica di Microsoft Cloud App Security.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono impostare come ambito le distribuzioni MCAS agli utenti con licenza usando le funzionalità di distribuzione con ambito disponibili nel servizio. Per ulteriori informazioni, vedere [Distribuzione con ambito.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Compliance Manager

Semplificare la conformità e ridurre i rischi con Compliance Manager. Compliance Manager consente alle organizzazioni di soddisfare i requisiti di normative, standard, criteri aziendali o altri framework di controllo desiderati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Di seguito sono riportati i vantaggi per gli utenti del servizio Compliance Manager:

- Converte normative complesse, standard, criteri aziendali o altri framework di controllo desiderati in un linguaggio semplice
- Fornisce l'accesso a una vasta raccolta di valutazioni out-of-the-box e di valutazioni personalizzate per soddisfare esigenze di conformità specifiche
- Mappa i controlli normativi alle azioni di miglioramento consigliate
- Fornisce indicazioni dettagliate su come implementare le soluzioni per soddisfare i requisiti normativi
- Aiuta gli utenti a definire le priorità delle azioni che avranno il massimo impatto sulla conformità dell'organizzazione associando un punteggio a ogni azione

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

I clienti con licenze E1 ed E3/G3 potranno accedere solo alla valutazione di base della protezione dei dati predefinita. I clienti con licenze di Office 365 E5/A5 e Microsoft 365 E5/A5 (conformità, Governance & Info Protection e eDiscovery e controllo inclusi) potranno accedere alle valutazioni out-of-the-box di Protezione dei dati, GDPR, NIST 800-53 e ISO 27001. I clienti con Office 365 G5 e Microsoft 365 G5 potranno accedere ai livelli di base di protezione dei dati, GDPR, NIST 800-53, ISO 27001 e CMMC (Cybersecurity Maturity Model Certification) da 1 a 5 valutazioni out-of-the-box. La funzionalità di valutazione personalizzata e le valutazioni premium sono riservate ai clienti di Office 365 E5/A5/G5 e Microsoft 365 E5/A5/G5. Le valutazioni Premium, come FedRAMP Moderate, FedRAMP High e altri, saranno disponibili per l'acquisto per i clienti con licenze E5/A5/G5 durante la prima metà del 2021 tramite VL, CSP e WebDirect. Contatta il venditore Microsoft o il partner Microsoft per acquistare rispettivamente tramite canali VL o CSP. Per acquistare tramite WebDirect, vedere [WebDirect.](https://aka.ms/ComplianceManager/WebDirect)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Il provisioning di Compliance Manager viene eseguito per impostazione predefinita per il tenant. Gli amministratori impostano le autorizzazioni utente e assegnano i ruoli in modo che gli utenti non amministratori dell'organizzazione possano iniziare a usare Compliance Manager. Per ulteriori informazioni, vedere [Introduzione a Compliance Manager: Impostare le autorizzazioni utente e assegnare ruoli.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender per endpoint

Microsoft Defender for Endpoint (in precedenza Microsoft Defender ATP) è una soluzione di sicurezza degli endpoint che include la gestione e la valutazione delle vulnerabilità basate sul rischio; funzionalità di riduzione della superficie di attacco; protezione di nuova generazione basata sul comportamento e basata sul cloud; rilevamento e risposta degli endpoint (EDR); analisi e correzione automatiche; e i servizi di ricerca gestiti. Per [altre informazioni, vedi la pagina Di Microsoft Defender](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per endpoint.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

Gli utenti con licenza di Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, che include Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 Security, possono trarre vantaggio da Microsoft Defender per Endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOps traggono vantaggio dalle funzionalità di sicurezza degli endpoint di Microsoft Defender for Endpoint per eseguire la protezione preventiva, il rilevamento post-violazione, l'indagine automatizzata e la risposta alle minacce avanzate. Gli utenti finali traggono vantaggio da eventi dannosi monitorati da Microsoft Defender per Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender per endpoint sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla distribuzione, vedere [Fasi di distribuzione.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori di Microsoft Defender per endpoint possono utilizzare il controllo dell'accesso basato sui ruoli (RBAC) per creare ruoli e gruppi all'interno del team delle operazioni di sicurezza per concedere l'accesso appropriato a Microsoft Defender Security Center. Per ulteriori informazioni, vedere [Gestire l'accesso al portale tramite il controllo dell'accesso basato sui ruoli.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Analisi della classificazione dei dati di Microsoft 365: Panoramica di Esplora &amp; attività contenuto  

Le funzionalità analitiche per la classificazione dei dati sono disponibili nell'esperienza del Centro conformità Microsoft 365. Panoramica mostra le posizioni dei contenuti digitali e le etichette e i tipi di informazioni sensibili più comuni. Esplora contenuto offre visibilità sulla quantità e sui tipi di dati sensibili e consente agli utenti di filtrare in base all'etichetta o al tipo di riservatezza per ottenere una visualizzazione dettagliata delle posizioni in cui sono archiviati i dati sensibili. Esplora attività mostra le attività relative a dati ed etichette sensibili, ad esempio downgrade delle etichette o condivisione esterna che potrebbero esporre il contenuto a rischi.

Esplora attività offre un unico riquadro di vetro per consentire agli amministratori di ottenere visibilità sulle attività correlate alle informazioni riservate utilizzate dagli utenti finali. Questi dati includono le attività di etichettatura, i registri di prevenzione della perdita dei dati (DLP), l'etichettatura automatica, Endpoint DLP e altro ancora.

Esplora contenuto consente agli amministratori di indicizzare i documenti sensibili archiviati all'interno dei carichi di lavoro di Microsoft 365 supportati e identificare le informazioni riservate archiviate. Esplora contenuto consente inoltre di identificare i documenti classificati con etichette di riservatezza e conservazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli amministratori della protezione delle informazioni e della conformità possono accedere al servizio per accedere a questi log e dati indicizzati per comprendere dove sono archiviati i dati sensibili e quali attività sono correlate a questi dati ed eseguite dagli utenti finali.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Gli utenti con licenza di Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection Governance e Office 365 E5 possono trarre vantaggio dall'analisi della classificazione dei dati di &amp; Microsoft 365. 

Microsoft 365 E3/A3/G3 e Office 365 E3/A3/G3 consentono agli utenti di trarre vantaggio solo dall'aggregazione dei dati di Esplora contenuto.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità Di riepilogo contenuto ed Esplora attività sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dell'analisi di classificazione dei dati per gli utenti con licenza, vedere:

- **Esplora contenuto:** introduzione a Esplora contenuto - Criteri di [conformità di Microsoft 365 | Microsoft Docs](https://docs.microsoft.com/microsoft-365/compliance/data-classification-content-explorer).
- **Esplora attività**: Introduzione a Esplora attività - Criteri di [conformità di Microsoft 365 | Microsoft Docs.](https://docs.microsoft.com/microsoft-365/compliance/data-classification-activity-explorer)
- **Note sulla versione per la classificazione dei** dati : note sulla versione della classificazione dei dati - Microsoft [365 Compliance | Microsoft Docs.](https://docs.microsoft.com/microsoft-365/compliance/data-classification-pub-preview-relnotes)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

L'ambito di questa funzionalità deve essere quello degli utenti che usano attivamente la soluzione nel portale di conformità di Microsoft 365.

## <a name="information-protection"></a>Protezione delle informazioni

Information Protection consente alle organizzazioni di individuare, classificare, etichettare e proteggere documenti e messaggi di posta elettronica sensibili. Gli amministratori possono definire regole e condizioni per applicare automaticamente le etichette, gli utenti possono applicare le etichette manualmente o una combinazione di queste due opzioni, in cui agli utenti vengono forniti consigli sull'applicazione delle etichette.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di applicare manualmente etichette di riservatezza al contenuto o di classificare automaticamente il contenuto.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 e AIP Plan 2 forniscono a un utente i diritti per trarre vantaggio dall'etichettatura manuale della riservatezza.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 e AIP Plan 2 forniscono a un utente i diritti di applicazione e visualizzazione delle etichette di riservatezza in Power BI e di proteggere i dati quando vengono esportati da Power BI a Excel, PowerPoint o PDF. 

> [!NOTE]
> Power BI è incluso in Microsoft 365 E5/A5/G5; in tutti gli altri piani, Power BI deve essere concesso in licenza separatamente.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection e Governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 e AIP Plan 2 forniscono a un utente i diritti per trarre vantaggio dall'etichettatura automatica della riservatezza.

Per diritti specifici in base alla licenza, vedere il confronto dettagliato delle licenze di conformità di Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Non include i diritti per la classificazione automatica basata su Machine Learning (classificatori formabili).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di protezione delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri per gli utenti con licenza, vedere Attivazione di Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Tranne quando si utilizza la funzionalità scanner AIP, i criteri possono essere applicati a gruppi o utenti specifici e i registri possono essere modificati per impedire agli utenti senza licenza di eseguire funzionalità di classificazione o di etichettatura. Per istruzioni su come impostare l'ambito delle distribuzioni AIP, vedere [Configurazione dei criteri di Azure Information Protection.](https://docs.microsoft.com/azure/information-protection/configure-policy)

Per la funzionalità scanner AIP, Microsoft non si impegna a fornire funzionalità di classificazione, etichettatura o protezione dei file agli utenti senza licenza.

## <a name="information-governance"></a>Governance delle informazioni

La governance delle informazioni consente alle organizzazioni di gestire i rischi individuando, classificando, etichettando e regolando i propri dati. La governance delle informazioni consente alle organizzazioni di soddisfare i requisiti aziendali e normativi e di ridurre la superficie di attacco fornendo funzionalità di conservazione ed eliminazione nei dati di Microsoft 365 e di terze parti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di classificare i dati ai fini della conservazione per rispettare normative e criteri specifici.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 e i piani di Exchange autonomi forniscono a un utente i diritti per trarre vantaggio dall'applicazione manuale di etichette di conservazione non record ai dati della cassetta postale.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 e i piani di SharePoint autonomi forniscono a un utente i diritti per trarre vantaggio dall'applicazione manuale di etichette di conservazione non record ai file in SharePoint o OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Piano 2 e Archiviazione Exchange Online forniscono a un utente i diritti per trarre vantaggio da un criterio di conservazione delle cassette postali di base a livello di organizzazione o a livello di posizione e/o per applicare manualmente un'etichettatura di conservazione non record ai dati della cassetta postale.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 e SharePoint Piano 2 forniscono a un utente i diritti per trarre vantaggio da un criterio di conservazione di base di SharePoint o OneDrive e/o per applicare manualmente un'etichetta di conservazione non record ai file in SharePoint o OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 e Office 365 E5/A5/G5/E3/A3 forniscono a un utente i diritti per trarre vantaggio dai criteri di conservazione di Teams.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5, e Office 365 E5/A5 forniscono a un utente i diritti per trarre vantaggio dall'applicazione automatica di etichette o criteri di conservazione, dall'applicazione di etichette o criteri di conservazione predefiniti, dall'avvio del periodo di conservazione di un'etichetta di conservazione basata su un evento personalizzato, dall'attivazione di una revisione manuale dell'eliminazione alla fine del periodo di conservazione dell'etichetta, dall'importazione di dati di terze parti tramite connettori di dati nativi, dalla dichiarazione di un file a un record, dall'individuazione di contenuto etichettato e dal monitoraggio dell'attività di etichettatura.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection e Governance forniscono a un utente i diritti per trarre vantaggio dall'applicazione automatica delle etichette di conservazione in base ai classificatori formabili.

Per diritti specifici in base alla licenza, vedere il confronto dettagliato delle licenze di conformità di Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Governance delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Information Governance per applicare l'etichettatura automatica e i criteri per gli utenti con licenza, vedere Governance delle informazioni [Microsoft in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Le funzionalità di governance delle informazioni possono essere applicate agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione di Information Governance per applicare l'etichettatura automatica e i criteri per gli utenti con licenza, vedere Governance delle informazioni [Microsoft in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

## <a name="records-management"></a>Gestione record

Gestione record consente alle organizzazioni di soddisfare gli obblighi aziendali e normativi di conservazione dei record individuando, classificando, etichettando, conservando ed eliminando in modo defensibile i dati di Microsoft 365 e di terze parti.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 e Office 365 E5/A5/G5 forniscono a un utente i diritti di trarre vantaggio dalla gestione dei record, tra cui la dichiarazione di elementi come record o record normativi, l'applicazione automatica di etichette di conservazione o record e l'esecuzione di processi di revisione dell'eliminazione (esclusa l'applicazione automatica di un'etichetta di conservazione basata su classificatori formabili).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance forniscono a un utente i diritti di trarre vantaggio dall'applicazione automatica di etichette di conservazione o record basate su classificatori formabili.

Per diritti specifici in base alla licenza, vedere il confronto dettagliato delle licenze di conformità di Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di dichiarare il contenuto come record e di gestire il processo di registrazione completo dalla definizione e dalla dichiarazione dei criteri attraverso l'eliminazione defensibile.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di gestione dei record sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Gestione record da applicare agli utenti con licenza, vedere Informazioni sulla gestione [dei record in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Le caratteristiche di gestione dei record possono essere applicate agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione di Gestione record da applicare agli utenti con licenza, vedere Informazioni sulla gestione [dei record in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>Connettori dati 

Microsoft fornisce connettori dati di terze parti che possono essere configurati nel Centro conformità Microsoft 365. Per un elenco dei connettori dati forniti da Microsoft, vedere la tabella dei connettori dati [di terze](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) parti. In questa tabella vengono riepilogate anche le soluzioni di conformità che è possibile applicare ai dati di terze parti dopo l'importazione e l'archiviazione dei dati in Microsoft 365 e vengono forniti collegamenti alle istruzioni dettagliate per ogni connettore.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Il vantaggio principale dell'uso dei connettori di dati per importare e archiviare dati di terze parti in Microsoft 365 è che è possibile applicare diverse soluzioni di conformità di Microsoft 365 ai dati dopo l'importazione. In questo modo si garantisce che i dati non Microsoft dell'organizzazione siano conformi alle normative e agli standard che influiscono sull'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Le licenze seguenti forniscono a un utente i diritti per trarre vantaggio dai connettori di dati:

- Microsoft 365 E5/A5/G5
- Governance della protezione delle informazioni di Microsoft 365 E5/A5/G5 &amp;
- Conformità Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Insider Risk Management
- eDiscovery e controllo di Microsoft 365 E5/A5/G5
- Office 365 E5/A5/G5

Per i connettori dati nel Centro conformità sicurezza Microsoft 365 forniti da un partner Microsoft, l'organizzazione avrà bisogno di una relazione aziendale con il partner prima di poter distribuire &amp; tali connettori.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

I connettori vengono configurati utilizzando il Centro &amp; sicurezza e il catalogo dei connettori.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

I servizi connettori dati sono un valore a livello di tenant. Ogni utente destinato a trarre vantaggio da questo servizio deve disporre di una licenza.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>API di Microsoft Graph per la prevenzione della perdita dei dati (DLP) di Teams

All'inizio di [quest'anno è stata annunciata l'anteprima pubblica dell'API](https://go.microsoft.com/fwlink/?linkid=2143888)di notifica delle modifiche di Microsoft Graph per i messaggi in Teams. Questa API consente agli sviluppatori di creare app in grado di ascoltare i messaggi di Microsoft Teams in tempo quasi reale e abilitare le implementazioni dello scenario DLP sia per i clienti che per gli ISV. Inoltre, l'API patch di Microsoft Graph consente di applicare azioni DLP ai messaggi di Teams.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Le funzionalità di prevenzione della perdita [di dati (DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) sono ampiamente utilizzate in Microsoft Teams, in particolare quando le organizzazioni sono passate al lavoro remoto. Se l'organizzazione dispone di DLP, è ora possibile definire criteri che impediscono agli utenti di condividere informazioni riservate in un canale di Microsoft Teams o in una sessione di chat.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Per ottenere il supporto per la protezione DLP in Teams Chat, è necessaria una delle licenze seguenti:

- Microsoft 365 E5/A5/G5
- Conformità Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

L'accesso api è configurato a livello di tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Microsoft Graph API for Teams DLP è un valore a livello di tenant. Ogni utente destinato a trarre vantaggio da questo servizio deve disporre di una licenza.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fornisce soluzioni di analisi ed eDiscovery per i reparti IT e legali all'interno delle aziende per identificare, raccogliere, conservare, ridurre ed esaminare i contenuti relativi a un'indagine o a una controversia legale prima dell'esportazione dal sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Un utente trae vantaggio da Advanced eDiscovery quando viene selezionato come responsabile dei dati (una persona che ha il controllo amministrativo di un documento o di un file elettronico) per un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 forniscono a un utente i diritti per trarre vantaggio da Core eDiscovery.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 eDiscovery and Audit e Office 365 E5/A5/G5 forniscono a un utente i diritti per trarre vantaggio da Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Advanced eDiscovery sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant quando gli amministratori assegnano le autorizzazioni di eDiscovery nel Centro &amp; sicurezza e conformità.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori di eDiscovery possono selezionare utenti specifici come responsabili dei dati per un caso utilizzando lo strumento di gestione dei responsabili incorporato in Advanced eDiscovery, come descritto in Aggiungere responsabili a un caso di [Advanced eDiscovery.](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)

## <a name="office-365-customer-key"></a>Codice Product Key per i clienti di Office 365

Con Customer Key, è possibile controllare le chiavi di crittografia dell'organizzazione e configurare Office 365 per usarle per crittografare i dati in stato di inquieto nei data center Microsoft. In altre parole, Customer Key consente di aggiungere un livello di crittografia che appartiene a te, usando le tue chiavi. I dati in pausa includono i dati di Exchange Online e Skype for Business archiviati nelle cassette postali e nei file all'interno di SharePoint Online e OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio da Customer Key grazie alla crittografia dei dati a livello di applicazione tramite chiavi di crittografia fornite, controllate e gestite dalla propria organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance e Office 365 E5/A5/G5 forniscono a un utente i diritti per trarre vantaggio da Customer Key. Per ottenere tutti i vantaggi di Customer Key, è necessario disporre anche di una sottoscrizione per Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Le chiavi di crittografia della chiave del cliente di Office 365 possono essere abilitate per tutti i dati archiviati nelle cassette postali di Exchange Online e Skype for Business e nei file di SharePoint Online, OneDrive for Business e Teams. Per altre informazioni su Office 365 Customer Key, inclusa la procedura per iniziare, vedere Crittografia del servizio [con Customer Key.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Per Exchange Online e Skype for Business, le cassette postali possono essere crittografate utilizzando Customer Key. È necessario configurare Azure prima di poter usare Customer Key per Office 365. Vedere [Configurare Customer Key](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) per i passaggi da seguire per creare e configurare le risorse di Azure necessarie e i passaggi per configurare Customer Key in Office 365. Dopo aver completato la configurazione di Azure, determinare quali criteri e, di conseguenza, quali chiavi assegnare alle cassette postali e ai file nell'organizzazione. Le cassette postali e i file per i quali non si assegna un criterio utilizzeranno i criteri di crittografia controllati e gestiti da Microsoft. Per ulteriori informazioni su Customer Key o per una panoramica generale, vedere [Crittografia del servizio con Customer Key.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Customer Lockbox di Office 365

Customer Lockbox offre un ulteriore livello di controllo offrendo ai clienti la possibilità di concedere l'autorizzazione di accesso esplicito per le operazioni di servizio. Dimostrando che sono in atto procedure per l'autorizzazione esplicita di accesso ai dati, Customer Lockbox può anche aiutare le organizzazioni a rispettare determinati obblighi di conformità come HIPAA e FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Customer Lockbox garantisce che nessuno di Microsoft possa accedere al contenuto del cliente per eseguire un'operazione di servizio senza l'approvazione esplicita del cliente. Customer Lockbox consente al cliente di accedere al flusso di lavoro di approvazione per le richieste di accesso al contenuto. Occasionalmente, i tecnici Microsoft sono coinvolti durante il processo di supporto per risolvere e risolvere i problemi segnalati dai clienti. Nella maggior parte dei casi, i problemi vengono risolti tramite strumenti di telemetria e debug estesi che Microsoft ha in atto per i suoi servizi. Tuttavia, in alcuni casi potrebbe essere necessario che un tecnico Microsoft possa accedere ai contenuti dei clienti per determinare la causa principale e risolvere il problema. Customer Lockbox richiede al tecnico di richiedere l'accesso al cliente come passaggio finale nel flusso di lavoro di approvazione. In questo modo le organizzazioni possono approvare o rifiutare queste richieste, in modo da controllare direttamente se un tecnico Microsoft può accedere ai dati dell'utente finale dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono a un utente i diritti per trarre vantaggio da Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori possono attivare Customer Lockbox nell'interfaccia di amministrazione di Microsoft 365. Per altre informazioni, vedere [Customer Lockbox in Office 365.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) Quando Customer Lockbox è attivato, Microsoft deve ottenere l'approvazione di un'organizzazione prima di accedere a qualsiasi contenuto.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Attualmente, il servizio Customer Lockbox non può essere limitato a utenti specifici. Devi ottenere una licenza per ogni utente che intendi trarre vantaggio.

## <a name="privileged-access-management-in-office-365"></a>Gestione degli accessi privilegiati in Office 365

[La gestione degli accessi privilegiati (PAM, Privileged Access Management)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) offre un controllo granulare degli accessi sulle attività di amministrazione con privilegi in Office 365. Dopo aver abilitato PAM, per completare le attività con privilegi elevati e privilegiati, gli utenti dovranno richiedere l'accesso just-in-time tramite un flusso di lavoro di approvazione con un ambito elevato e con limiti di tempo.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

L'abilitazione di PAM consente alle organizzazioni di operare senza privilegi permanenti. Gli utenti traggono vantaggio dall'ulteriore livello di difesa contro le vulnerabilità derivanti dall'accesso amministrativo permanente che consente l'accesso senza limiti ai propri dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance e Microsoft 365 E5/A5 Information Protection and Governance forniscono a un utente i diritti per trarre vantaggio da PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità PAM sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri PAM, vedere [Introduzione alla gestione degli accessi con privilegi.](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

I clienti possono gestire PAM per utente tramite criteri di accesso e gruppo di responsabili approvazione, che possono essere applicati agli utenti con licenza. Per altre informazioni, vedere [Privileged Access Management in Office 365.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="double-key-encryption-for-microsoft-365"></a>Crittografia a chiave doppia per Microsoft 365 

La crittografia a chiave doppia per Microsoft 365 consente di proteggere i dati altamente sensibili per soddisfare requisiti specializzati e mantenere il controllo completo della chiave di crittografia. La crittografia a chiave doppia usa due chiavi per proteggere i dati, con una chiave nel controllo e la seconda chiave archiviata in modo sicuro da Microsoft Azure. Per visualizzare i dati, è necessario avere accesso a entrambi i tasti. Poiché Microsoft può accedere a una sola chiave, la chiave e anche i dati non sono disponibili per Microsoft, garantendo il controllo completo sulla privacy e la sicurezza dei dati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla crittografia a chiave doppia grazie alla possibilità di eseguire la migrazione dei dati crittografati nel cloud, impedendo l'accesso a terze parti, purché la chiave rimanga sotto il controllo degli utenti. Gli utenti possono proteggere e utilizzare il contenuto crittografato a chiave doppia in modo analogo a qualsiasi altro contenuto protetto da etichette di riservatezza.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance e Office 365 E5/A5/G5 forniscono i diritti per un utente di usufruire della crittografia a chiave doppia.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

La crittografia a chiave doppia supporta la versione desktop di Microsoft Office per Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Per assegnare chiavi di crittografia ai dati all'interno di un'organizzazione di Office 365 e/o Microsoft 365 per gli utenti con licenza, seguire le istruzioni per la distribuzione della crittografia a chiave doppia.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenzione della perdita dei dati di Office 365 per Exchange Online, SharePoint Online e OneDrive for Business

Con office 365 data loss prevention (DLP) for Exchange Online, SharePoint Online, and OneDrive for Business, organizations can identify, monitor, and automatically protect sensitive information across emails and files (including files stored in Microsoft Teams file repositories).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla prevenzione della perdita dei dati per Exchange Online, SharePoint Online e OneDrive for Business quando i messaggi di posta elettronica e i file vengono esaminati per individuare informazioni riservate, come configurato nel criterio DLP dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 e Prevenzione della perdita dei dati di Office 365 forniscono a un utente i diritti per trarre vantaggio dalla prevenzione della perdita dei dati di Office 365 per Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, i messaggi di posta elettronica di Exchange Online, i siti di SharePoint e gli account di OneDrive sono posizioni *abilitate (carichi* di lavoro) per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of data loss prevention.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro sicurezza &amp; e conformità, in **Percorsi di prevenzione della** perdita di  >  **dati.**

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenzione della perdita dei dati di comunicazione per Teams

Con Communication DLP per Teams, le organizzazioni possono bloccare chat e messaggi di canale contenenti informazioni riservate, ad esempio informazioni finanziarie, informazioni di identificazione personale, informazioni correlate all'integrità o altre informazioni riservate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Information Protection e Governance possono trarre vantaggio dalla prevenzione della perdita dei dati delle comunicazioni per Teams.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti traggono vantaggio dal fatto che le informazioni riservate nei messaggi di chat e canali in uscita siano ispezionate alla ricerca di informazioni riservate, come configurato nel criterio DLP dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, i messaggi di chat e canali di Teams sono un percorso *abilitato (carico* di lavoro) per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of data loss prevention.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro sicurezza &amp; e conformità, in **Percorsi di prevenzione della** perdita di  >  **dati.**

## <a name="information-barriers"></a>Barriere informative

Le barriere di informazioni sono criteri che un amministratore può configurare per impedire a singoli utenti o gruppi di comunicare tra loro. Ciò è utile, ad esempio, se un reparto gestisce informazioni che non devono essere condivise con altri reparti o se è necessario impedire a un gruppo di comunicare con contatti esterni. I criteri delle barriere di informazioni impediscono inoltre ricerche e individuazione. Questo significa che se tenti di comunicare con qualcuno con cui non dovresti comunicare, non troverai tale utente nella selezione utenti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalle funzionalità avanzate di conformità delle barriere in fatto di informazioni quando non possono comunicare con altri utenti. I criteri delle barriere di informazioni possono essere definiti per impedire a determinati segmenti di utenti di comunicare con ognuno di essi o consentire a segmenti specifici di comunicare solo con determinati altri segmenti. Per ulteriori informazioni sulla definizione dei criteri delle barriere di informazioni, vedere [Definire i criteri delle barriere di informazioni.](https://docs.microsoft.com/microsoft-365/compliance/information-barriers-policies) Per gli scenari in cui due gruppi non possono comunicare tra loro, gli utenti di entrambi i gruppi richiedono una licenza per trarre vantaggio dal servizio (vedere l'esempio seguente).<br><br>

| Scenario | Chi richiede una licenza? |
|:------|:------|
| Due gruppi (Gruppo 1 e Gruppo 2) non possono comunicare tra loro, ovvero agli utenti del Gruppo 1 è limitata la comunicazione con gli utenti del Gruppo 2 e agli utenti del Gruppo 2 è consentita la comunicazione con gli utenti del &nbsp; &nbsp; Gruppo &nbsp; &nbsp; &nbsp; &nbsp; 1. | Utenti del gruppo &nbsp; 1 e del &nbsp; gruppo 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management e Office 365 E5/A5/G5, forniscono a un utente i diritti per trarre vantaggio dalle barriere di informazioni.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri delle barriere di informazioni utilizzando i cmdlet di PowerShell nel Centro &amp; sicurezza e conformità. Agli amministratori deve essere assegnato il ruolo di amministratore globale dell'organizzazione di Microsoft 365, amministratore globale di Office 365 o amministratore di conformità per creare un criterio di barriere di informazioni. Per impostazione predefinita, questi criteri si applicano a tutti gli utenti nel tenant. Per ulteriori informazioni sulle barriere in fatto di informazioni, vedere [Barriere informazioni in Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro &amp; sicurezza e conformità. Ad esempio, se tutti gli utenti hanno una licenza per Office 365 E3 e nessuno ha una licenza per Office 365 Advanced Compliance/E5, non è necessario creare criteri di barriere di informazioni per l'organizzazione. Per ulteriori informazioni, vedere [Barriere di informazioni in Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Crittografia messaggi di Office 365 (OME) è un servizio basato su Azure Rights Management (Azure RMS) che consente di inviare posta elettronica crittografata a destinatari interni o esterni all'organizzazione, indipendentemente dall'indirizzo di posta elettronica di destinazione (Gmail, Yahoo! Mail, Outlook.com e così via).

Per visualizzare messaggi crittografati, i destinatari possono ottenere un passcode monouso, accedere con un account Microsoft oppure accedere con un account aziendale o dell'istituto di istruzione associato a Office 365. I destinatari possono anche inviare risposte crittografate. Non è necessaria una sottoscrizione per visualizzare i messaggi crittografati o inviare risposte crittografate.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti dei messaggi traggono vantaggio dal controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia dei messaggi di Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 e Azure Information Protection Piano 1 forniscono a un utente i diritti per trarre vantaggio dalla crittografia dei messaggi di Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia dei messaggi di Office 365 nell'interfaccia di amministrazione di Exchange in **Regole del flusso di**  >  **posta.** Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione delle nuove funzionalità di crittografia dei messaggi di Office 365, vedere [Configurare le nuove funzionalità di crittografia dei messaggi.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per la crittografia dei messaggi di Office 365 solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere Definire le regole del [flusso di posta per crittografare i messaggi di posta elettronica.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

La crittografia avanzata dei messaggi di Office 365 consente ai clienti di rispettare gli obblighi di conformità che richiedono controlli più flessibili sui destinatari esterni e sul loro accesso ai messaggi di posta elettronica crittografati. Con La crittografia avanzata dei messaggi, gli amministratori possono controllare i messaggi di posta elettronica sensibili condivisi all'esterno dell'organizzazione utilizzando criteri automatici in grado di rilevare i tipi di informazioni riservate (ad esempio, informazioni di identificazione personale o ID finanziari o sanitari) oppure possono utilizzare le parole chiave per migliorare la protezione applicando modelli di posta elettronica personalizzati e facendo scadere l'accesso ai messaggi di posta elettronica crittografati tramite un portale Web sicuro. Inoltre, gli amministratori possono controllare ulteriormente i messaggi di posta elettronica crittografati a cui si accede esternamente tramite un portale Web sicuro revocando l'accesso in qualsiasi momento.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti dei messaggi traggono vantaggio dal controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia avanzata dei messaggi.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Information Protection and Governance forniscono a un utente i diritti per trarre vantaggio dalla crittografia avanzata dei messaggi.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia avanzata dei messaggi nell'interfaccia di amministrazione di Exchange in **Regole del flusso di**  >  **posta.** Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione delle nuove funzionalità di crittografia dei messaggi, vedere Configurare le nuove funzionalità di crittografia dei messaggi [di Office 365.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per la crittografia avanzata dei messaggi solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere Definire le regole del flusso di posta per crittografare i messaggi di posta [elettronica in Office 365.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Conformità delle comunicazioni

La conformità delle comunicazioni in Microsoft 365 consente di ridurre al minimo i rischi di comunicazione consentendo di rilevare, acquisire ed eseguire azioni correttive per i messaggi inappropriati nell'organizzazione. È possibile definire criteri specifici che acquisiscono la posta elettronica interna ed esterna, Microsoft Teams o comunicazioni di terze parti nell'organizzazione. I revisori possono intraprendere azioni correttive appropriate per assicurarsi che siano conformi agli standard dei messaggi dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli esperti di conformità traggono vantaggio dal servizio facendo in modo che le comunicazioni dell'organizzazione sia monitorate dai criteri di conformità delle comunicazioni.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono a un utente i diritti per trarre vantaggio dalla conformità delle comunicazioni.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori e gli esperti di conformità creano criteri di conformità delle comunicazioni nel Centro conformità Microsoft 365. Questi criteri definiscono quali comunicazioni e utenti sono soggetti a revisione nell'organizzazione, definiscono le condizioni personalizzate che le comunicazioni devono soddisfare e specificano chi deve eseguire le revisioni.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori scelgono utenti o gruppi specifici da includere nei criteri di conformità delle comunicazioni. Quando scelgono un gruppo, possono anche selezionare utenti specifici nel gruppo da escludere dai criteri di conformità delle comunicazioni. Per ulteriori informazioni sui criteri di conformità delle comunicazioni, vedere [Introduzione alla conformità delle comunicazioni in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Gestione dei rischi Insider

La gestione dei rischi Insider è una soluzione di Microsoft 365 che consente di ridurre al minimo i rischi interni consentendo di rilevare, analizzare e intervenire sulle attività rischiose nell'organizzazione.

I criteri personalizzati consentono di rilevare ed eseguire azioni su attività dannose e inavvertitamente rischiose nell'organizzazione, tra cui l'escalation dei casi a Microsoft Advanced eDiscovery, se necessario. Gli analisti dei rischi nell'organizzazione possono intraprendere rapidamente le azioni appropriate per assicurarsi che gli utenti siano conformi agli standard di conformità dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dal fatto che le attività vengono monitorate per il rischio.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti per trarre vantaggio dal servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono a un utente i diritti per trarre vantaggio dalla gestione dei rischi Insider.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

I criteri di gestione dei rischi Insider devono essere creati nel Centro conformità Microsoft 365 e assegnati agli utenti.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Quando si crea un criterio nel Centro conformità Microsoft 365,  nella pagina Scegli utenti e gruppi selezionare Scegli utenti o gruppi per  selezionare solo gli utenti con licenza oppure, se tutti gli utenti dispongono di una licenza, è possibile selezionare la casella di controllo Tutti gli utenti e i gruppi abilitati alla posta elettronica.  Per ulteriori informazioni, vedere [Introduzione alla gestione dei rischi Insider.](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Criteri di accesso condizionale

L'accesso condizionale è lo strumento usato da Azure Active Directory per riunire i segnali, prendere decisioni e applicare i criteri dell'organizzazione. L'accesso condizionale è alla base del controllo basato sull'identità. I criteri di accesso condizionale, nel modo più semplice, sono istruzioni if-then. Se un utente vuole accedere a una risorsa, deve completare un'azione. Esempio: un responsabile delle retribuzioni desidera accedere all'applicazione per le retribuzioni ed è necessario per eseguire l'autenticazione a più fattori per accedervi.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

Gli utenti con licenza di Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium e Azure Active Directory Premium Piano 1 possono trarre vantaggio dai criteri di accesso condizionale. Gli utenti con licenza di Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security e Azure Active Directory Premium Piano 2 possono trarre vantaggio da Identity Protection (criteri di accesso condizionale basati sul rischio).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti delle operazioni di sicurezza e i professionisti della sicurezza traggono vantaggio dalla possibilità di applicare criteri organizzativi agli utenti, richiedendo loro di soddisfare determinati criteri prima di concedere l'accesso ai contenuti aziendali. Gli utenti finali traggono vantaggio dalla possibilità di accedere al proprio lavoro ovunque e in qualsiasi momento, proteggendo al contempo le risorse dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di accesso condizionale sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Per Identity Protection e l'accesso condizionale in modo specifico, un utente deve essere incluso in un gruppo o essere aggiunto a un criterio di accesso condizionale. La condizione di utenti e gruppi è obbligatoria in un criterio di accesso condizionale. Nei criteri è possibile selezionare Tutti **gli utenti o** utenti e gruppi specifici. È consigliabile selezionare solo utenti e gruppi con licenza appropriata. Per ulteriori informazioni, vedere [Accesso condizionale: Condizioni.](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)

## <a name="advanced-audit"></a>Audit avanzato

Il controllo avanzato in Microsoft 365 fornisce la conservazione di un anno dei log di controllo per le attività di utenti e amministratori e consente di creare criteri di conservazione dei log di controllo personalizzati per gestire la conservazione dei log di controllo per altri servizi di Microsoft 365. Fornisce inoltre l'accesso agli eventi cruciali per le indagini e l'accesso a larghezza di banda elevata all'API Office 365 Management Activity. Per altre informazioni, vedere [Audit avanzato in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

È inoltre possibile abilitare un periodo di conservazione di 10 anni con uno SKU del componente aggiuntivo. Lo SKU del componente aggiuntivo sarà necessario a partire dall'inizio del 2021.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 eDiscovery e Audit possono trarre vantaggio da Advanced Audit.

Gli utenti con licenza con controllo avanzato e il componente aggiuntivo di conservazione dei log di controllo di 10 anni possono trarre vantaggio dalla conservazione dei log di controllo di 10 anni.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti trarranno vantaggio dal controllo avanzato perché i record di controllo correlati all'attività degli utenti nei servizi di Microsoft 365 possono essere conservati per un massimo di un anno. Inoltre, vengono registrati eventi di controllo di alto valore, ad esempio quando gli elementi nella cassetta postale di un utente sono accessibili o letti. Per altre informazioni, vedere [Audit avanzato in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, Controllo avanzato è abilitato a livello di tenant per tutte le organizzazioni con una sottoscrizione a Office 365 o Microsoft 365 E5/A5/G5 e fornisce automaticamente la conservazione di un anno dei log di controllo per le attività (eseguite dagli utenti con la licenza appropriata) in Azure Active Directory, Exchange e SharePoint. Inoltre, le organizzazioni possono usare i criteri di conservazione dei log di controllo per gestire il periodo di conservazione per i record di controllo generati dall'attività in altri servizi di Microsoft 365. La funzionalità di conservazione dei log di controllo di 10 anni viene abilitata anche utilizzando gli stessi criteri di conservazione. Per altre informazioni, vedere [Gestire i criteri di conservazione dei log di controllo](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

La conservazione di un anno dei log di controllo e il controllo degli eventi cruciali si applicano solo agli utenti con la licenza appropriata. Inoltre, gli amministratori possono utilizzare i criteri di conservazione dei log di controllo per specificare durate di conservazione più brevi per i log di controllo di utenti specifici.

La conservazione di 10 anni dei log di controllo si applica solo agli utenti con la licenza del componente aggiuntivo appropriata. Lo SKU del componente aggiuntivo sarà necessario a partire dall'inizio del 2021.
