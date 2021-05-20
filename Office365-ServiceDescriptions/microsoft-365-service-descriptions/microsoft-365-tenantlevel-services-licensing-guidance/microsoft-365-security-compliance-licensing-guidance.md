---
title: Microsoft 365 sulle licenze per la conformità ai & sicurezza
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: In questo articolo vengono fornite indicazioni sulle licenze per Microsoft 365 conformità per evitare potenziali interruzioni del servizio dovute all'accesso senza licenza.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546013"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 sulle licenze per la conformità alla &amp; sicurezza

Ai fini di questo articolo, un servizio a livello di tenant è un servizio online che, se acquistato per qualsiasi utente &mdash; nel tenant (autonomo o come parte di piani Office 365 o Microsoft 365) viene &mdash; attivato in parte o per intero per tutti gli utenti del tenant. Sebbene alcuni utenti senza licenza possano tecnicamente essere in grado di accedere al servizio, è necessaria una licenza per qualsiasi utente che si intende beneficiare del servizio.

> [!NOTE]
> Alcuni servizi tenant non sono attualmente in grado di limitare i vantaggi a utenti specifici. Si dovrebbero compiere sforzi per limitare i vantaggi del servizio agli utenti con licenza. Ciò consentirà di evitare potenziali interruzioni del servizio per l'organizzazione una volta disponibili le funzionalità di targeting.

Per visualizzare le opzioni per la concessione in licenza agli utenti per beneficiare Microsoft 365 funzionalità di conformità, scaricare il confronto dettagliato Microsoft 365 conformità delle licenze. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [Signor Presidente, signor Presidente, signor Presidente, signor Presidente in Excel](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection è una funzionalità del piano P2 di Azure Active Directory Premium che consente di rilevare potenziali vulnerabilità che influiscono sulle identità dell'organizzazione, configurare risposte automatiche alle azioni sospette rilevate correlate alle identità dell'organizzazione e analizzare gli incidenti sospetti e intraprendere le azioni appropriate per risolverli.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOps traggono vantaggio dall'avere visualizzazioni consolidate degli utenti contrassegnati e degli eventi di rischio basati su algoritmi di machine learning. Gli utenti finali beneficiano della protezione automatica fornita attraverso l'accesso condizionale basato sul rischio e della maggiore sicurezza fornita agendo sulle vulnerabilità.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e Azure Active Directory Premium Plan 2 forniscono a un utente il diritto di beneficiare della protezione Azure Active Directory identità.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di Protezione identità di Azure AD sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni su Azure AD Identity Protection, vedere [Che cos'è identity protection?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono ambito Azure AD Identity Protection assegnando criteri di rischio che definiscono il livello per la reimpostazione delle password e consentendo l'accesso solo per gli utenti con licenza. Per istruzioni su come ambito delle distribuzioni di Azure AD Identity Protection, vedere Come [configurare e abilitare i criteri di rischio](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Governance dell'identità

Azure Active Directory Identity Governance consente di bilanciare le esigenze di sicurezza e produttività dei dipendenti dell'organizzazione con i processi e la visibilità giusti. Utilizza la gestione dei diritti, le revisioni degli accessi, la gestione delle identità privilegiate e i criteri delle condizioni d'uso per garantire che le persone giuste abbiano il giusto accesso alle risorse giuste.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Azure Active Directory Identity Governance aumenta la produttività degli utenti semplificando la richiesta di accesso ad app, gruppi e Microsoft Teams in un unico pacchetto di accesso. Gli utenti possono anche essere configurati come approvatori, senza coinvolgere gli amministratori. Per le revisioni degli accessi, gli utenti possono esaminare le appartenenze ai gruppi con consigli intelligenti per agire a intervalli regolari.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e Azure Active Directory Premium Plan 2 forniscono a un utente i diritti di beneficiare della governance dell Azure Active Directory identità.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Le funzionalità di governance delle identità di Azure AD sono abilitate a livello di tenant ma implementate per utente. Per informazioni sulla governance delle identità di Azure AD, vedere [Che cos'è la governance delle identità di Azure AD?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono ambito Azure AD Identity Governance assegnando pacchetti di accesso, revisioni degli accessi o gestione delle identità privilegiate solo per gli utenti con licenza. Per istruzioni su come ambito delle distribuzioni di Governance delle identità di Azure AD, vedere:

- [Requisiti della licenza per la gestione dei diritti di Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisiti di licenza per la revisione dell'accesso ad Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisiti di licenza per l'utilizzo Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender per identità

Microsoft Defender for Identity (in precedenza Azure Advanced Threat Protection) è un servizio cloud che consente di proteggere gli ambienti ibridi aziendali da più tipi di attacchi informatici mirati avanzati e minacce interne.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOp beneficiano della capacità di Microsoft Defender for Identity di rilevare e indagare su minacce avanzate, identità compromesse e azioni insider dannose. Gli utenti finali traggono vantaggio dal monitoraggio dei dati da parte di Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Microsoft Defender for Identity for Users forniscono i diritti per beneficiare di Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender for Identity sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Azure ATP, vedere [Creare l'istanza di Microsoft Defender for Identity](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

I servizi Microsoft Defender for Identity non sono attualmente in grado di limitare le funzionalità a utenti specifici. È necessario concedere in licenza ogni utente a cui si intende beneficiare.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender per Office 365

Microsoft Defender per Office 365 (in precedenza Office 365 Advanced Threat Protection) consente di proteggere le organizzazioni da attacchi sofisticati come phishing e malware zero-day. Microsoft Defender per Office 365 fornisce inoltre informazioni utili correlando i segnali provenienti da un'ampia gamma di dati per identificare, assegnare priorità e fornire consigli su come affrontare potenziali minacce.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Microsoft Defender per Office 365 protegge gli utenti da attacchi sofisticati come phishing e malware zero-day. Per l'elenco completo dei servizi forniti nel piano 1 e nel piano 2, [vedere Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio? 

Microsoft Defender per i piani Office 365 1 e 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 Business Premium fornisce a un utente i diritti di beneficiare di Microsoft Defender per Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, Microsoft Defender per Office 365 funzionalità sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Microsoft Defender per Office 365 criteri per gli utenti con licenza, [vedere Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Per ambito di Microsoft Defender per Office 365, seguire i criteri di distribuzione collegamenti sicuri e allegati sicuri:

- Per informazioni sulla configurazione dei collegamenti sicuri per gli utenti con licenza, [vedere Collegamenti sicuri in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Per informazioni sulla configurazione degli allegati sicuri per gli utenti con licenza, [vedere Allegati sicuri in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) è un sottoinsieme di Microsoft Cloud App Security, con funzionalità limitate a Office 365 e senza sicurezza aggiuntiva per app cloud di terze parti e servizi IaaS.

OCAS offre alle organizzazioni visibilità sulle loro app e servizi cloud di produttività, fornisce analisi sofisticate per identificare e combattere le minacce informatiche e consente loro di controllare il modo in cui &mdash; i dati viaggiano attraverso Office 365.

Per confrontare le funzionalità, [vedere Differenze tra Microsoft Cloud App Security e Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

OCAS individua Shadow IT, fornisce protezione dalle minacce in Office 365 e può controllare quali app hanno l'autorizzazione per accedere ai dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Office 365 E5/A3/A5/G5 forniscono a un utente il diritto di beneficiare dell'OCAS.
Per ulteriori informazioni, vedere la [scheda Microsoft Cloud App Security licenze](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità OCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione del servizio, vedere [Configurazione di base per Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono ambito le distribuzioni OCAS per applicare il modo in cui si accede a determinate app e limitare i gruppi di utenti monitorati Office 365 Cloud App Security. Per ulteriori informazioni, vedere [Distribuzione con ambito](/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) è una soluzione CASB (Cloud Access Security Broker) che offre alle organizzazioni visibilità sulle proprie app e servizi cloud, fornisce analisi sofisticate per identificare e combattere le minacce informatiche e consente loro di controllare il modo in cui i dati &mdash; viaggiano su qualsiasi app cloud.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

MCAS individua e valuta Shadow IT, fornisce protezione dalle minacce nelle app cloud di prima e terza parte e protegge le informazioni tra app cloud di prima e terza parte.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance forniscono ai cittadini il diritto di beneficiare di MCAS.

Azure AD P1 fornisce i diritti per un utente per beneficiare delle funzionalità di individuazione in MCAS.

Per beneficiare delle funzionalità di controllo delle app ad accesso condizionale in MCAS, gli utenti devono anche essere concessi in licenza per Azure Active Directory P1, incluso in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security.

Per beneficiare dell'etichettatura automatica lato client, gli utenti devono essere concessi in licenza per Azure Information Protection P2, incluso in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance.

> [!NOTE]
> L'etichettatura automatica sul lato server richiede protezione delle informazioni per Office 365 - Premium licenze ( `MIP_S_CLP2` o `efb0351d-3b08-4503-993d-383af8de41e3` ). Per riferimento, vedere Nomi [dei prodotti e identificatori del piano di servizio per la licenza](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

Per ulteriori informazioni, vedere la [scheda Microsoft Cloud App Security licenze](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità MCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione dei Microsoft Cloud App Security per gli utenti con licenza, [vedere Microsoft Cloud App Security panoramica](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono ambito le distribuzioni MCAS agli utenti con licenza utilizzando le funzionalità di distribuzione con ambito disponibili nel servizio. Per ulteriori informazioni, vedere [Distribuzione con ambito](/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Compliance Manager

Semplifica la conformità e contribuisci a ridurre i rischi con Compliance Manager. Compliance Manager aiuta le organizzazioni a soddisfare i requisiti di normative, standard, criteri aziendali o altri framework di controllo desiderati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Di seguito sono riportato i vantaggi per gli utenti del servizio Compliance Manager:

- Traduce regolamenti complicati, standard, politiche aziendali o altri framework di controllo desiderati in un linguaggio semplice
- Fornisce l'accesso a una vasta libreria di valutazioni out-of-the-box e valutazioni personalizzate per soddisfare esigenze di conformità uniche
- Mappe controlli normativi alle azioni di miglioramento raccomandate
- Fornisce indicazioni dettagliate su come implementare le soluzioni per soddisfare i requisiti normativi
- Aiuta gli utenti a dare la priorità alle azioni che avranno il maggiore impatto sulla conformità dell'organizzazione associando un punteggio a ogni azione

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

I clienti con licenze E1 ed E3/G3 potranno accedere solo alla valutazione predefinita della baseline sulla protezione dei dati. I clienti con licenze Office 365 E5/A5 e Microsoft 365 E5/A5 (conformità, governance di Info Protection & e SKU di eDiscovery e audit inclusi) potranno accedere alle valutazioni out-of-the-box di Data Protection Baseline, GDPR, NIST 800-53 e ISO 27001. I clienti con Office 365 G5 e Microsoft 365 G5 potranno accedere ai livelli di base per la protezione dei dati, GDPR, NIST 800-53, ISO 27001 e CMMC (Cybersecurity Maturity Model Certification) da 1 a 5 valutazioni out-of-the-box. La funzione di valutazione personalizzata e le valutazioni premium sono riservate Office 365 clienti E5/A5/G5 Microsoft 365 E5/A5/G5. Premium valutazioni, come FedRAMP Moderate, FedRAMP High e altre, saranno disponibili per l'acquisto ai clienti con licenze E5/A5/G5 durante la prima metà del 2021 fino a VL, CSP e WebDirect. Contattare il venditore Microsoft o il partner Microsoft per acquistare tramite i canali VL o CSP, rispettivamente. Per acquistare tramite WebDirect, vedere [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, è previsto il provisioning di Compliance Manager per il tenant. Gli amministratori impostano le autorizzazioni utente e assegnano ruoli in modo che gli utenti non amministratori dell'organizzazione possano iniziare a utilizzare Compliance Manager. Per ulteriori informazioni, vedere [Introduzione a Compliance Manager: Impostare le autorizzazioni utente e assegnare ruoli](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender per endpoint

Microsoft Defender for Endpoint (in precedenza Microsoft Defender ATP) è una soluzione di sicurezza degli endpoint che include servizi basati sul gestione delle vulnerabilità e valutazione; capacità di riduzione della superficie di attacco; protezione di nuova generazione basata sul comportamento e basata sul cloud; rilevamento e risposta degli endpoint (EDR); indagine e bonifica automatica; e gestiva i servizi di caccia. Per [ulteriori informazioni, vedere la pagina Microsoft Defender for Endpoint.](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Quali utenti beneficiano del servizio?

Gli utenti con licenza di Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, che include la protezione Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5, possono beneficiare di Microsoft Defender for Endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOps beneficiano delle funzionalità di sicurezza degli endpoint di Microsoft Defender for Endpoint per eseguire la protezione preventiva, il rilevamento post-violazione, l'indagine automatizzata e la risposta a minacce avanzate. Gli utenti finali traggono vantaggio dal monitoraggio di eventi dannosi da parte di Microsoft Defender for Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender for Endpoint sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla distribuzione, vedere [Fasi di distribuzione](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori di Microsoft Defender for Endpoint possono utilizzare il controllo degli accessi basato sui ruoli (RBAC) per creare ruoli e gruppi all'interno del team delle operazioni di sicurezza per concedere l'accesso appropriato al Microsoft Defender Security Center. Per ulteriori informazioni, vedere Manage [portal access using role-based access control](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 di classificazione dei dati: Panoramica di Content &amp; Activity Explorer

Le funzionalità analitiche di classificazione dei dati sono disponibili all'interno Microsoft 365 esperienza del centro di conformità. Panoramica mostra le posizioni del contenuto digitale e i tipi di informazioni riservate più comuni e le etichette presenti. Content Explorer offre visibilità sulla quantità e sui tipi di dati sensibili e consente agli utenti di filtrare in base all'etichetta o al tipo di sensibilità per ottenere una visualizzazione dettagliata delle posizioni in cui sono archiviati i dati sensibili. Activity Explorer mostra attività relative a dati ed etichette sensibili, ad esempio downgrade di etichette o condivisione esterna che potrebbero esporre il contenuto a rischi.

Activity Explorer fornisce un singolo riquadro di vetro per gli amministratori per ottenere visibilità sulle attività correlate alle informazioni riservate utilizzate dagli utenti finali. Questi dati includono attività di etichette, registri di prevenzione della perdita di dati (DLP), etichettatura automatica, DLP endpoint e altro ancora.

Esplora contenuto offre agli amministratori la possibilità di indicizzare i documenti riservati archiviati all'interno dei carichi di lavoro Microsoft 365 supportati e identificare le informazioni riservate archiviate. Esplora contenuto consente inoltre di identificare i documenti classificati con etichette di riservatezza e conservazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli amministratori della protezione delle informazioni e della conformità possono accedere al servizio per accedere a questi registri e dati indicizzati per capire dove vengono archiviati i dati sensibili e quali attività sono correlate a questi dati ed eseguite dagli utenti finali.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Gli utenti con licenza di conformità Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5, governance della protezione delle informazioni Microsoft 365 E5/A5/G5 &amp; e Office 365 E5 possono beneficiare di un'Microsoft 365 analisi della classificazione dei dati. 

Microsoft 365 E3/A3/G3 e Office 365 E3/A3/G3 consentono agli utenti di beneficiare solo dell'aggregazione dei dati di Content Explorer.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità Contenuto panoramica ed Esplora attività sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dell'analisi della classificazione dei dati per gli utenti con licenza, vedere:

- **Esplora contenuto:** [introduzione a Esplora contenuto - Microsoft 365 conformità | Documenti Microsoft](/microsoft-365/compliance/data-classification-content-explorer).
- **Esplora attività:** [introduzione a Esplora attività - Microsoft 365 conformità | Documenti Microsoft](/microsoft-365/compliance/data-classification-activity-explorer).
- **Note sulla versione della classificazione dei** dati : Note sulla versione della classificazione dei dati - Microsoft 365 Compliance [| Documenti Microsoft](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Questa funzionalità deve essere con ambito per gli utenti che utilizzano attivamente la soluzione all'interno Microsoft 365 portale di conformità.

## <a name="information-protection"></a>Azure Information Protection

Protezione delle informazioni consente alle organizzazioni di individuare, classificare, etichettare e proteggere documenti ed e-mail sensibili. Gli amministratori possono definire regole e condizioni per applicare automaticamente le etichette, gli utenti possono applicare le etichette manualmente o una combinazione delle due può essere utilizzata, in cui agli utenti vengono forniti consigli sull'applicazione delle etichette.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di applicare manualmente etichette di riservatezza al proprio contenuto o dalla classificazione automatica del contenuto.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 e AIP Plan 2 forniscono all'utente il diritto di beneficiare dell'etichettatura di sensibilità manuale.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 e AIP Plan 2 offrono all'utente il diritto di beneficiare dell'applicazione e della visualizzazione di etichette di riservatezza nel Power BI e di proteggere i dati quando vengono esportati da Power BI a Excel, PowerPoint o PDF. 

> [!NOTE]
> Power BI è incluso in Microsoft 365 E5/A5/G5; in tutti gli altri piani, Power BI essere concesso in licenza separatamente.

Microsoft 365 E5/A5/G5, conformità Microsoft 365 E5/A5/G5, protezione delle informazioni Microsoft 365 E5/A5/G5 e governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 e piano AIP 2 forniscono all'utente il diritto di beneficiare dell'etichettatura di sensibilità automatica.

Per diritti specifici per licenza, vedere la descrizione dettagliata Microsoft 365 delle licenze di conformità. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [Signor Presidente, signor Presidente, signor Presidente, signor Presidente in Excel](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Non include i diritti di classificazione automatica in base Machine Learning (classificatori addestrabili).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di protezione delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri per gli utenti con licenza, vedere Activating Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Ad eccezione dell'utilizzo della funzionalità scanner AIP, è possibile modificare i criteri per gruppi specifici o utenti e registri per impedire agli utenti senza licenza di eseguire funzionalità di classificazione o etichettatura. Per istruzioni su come ambito delle distribuzioni AIP, vedere Configurazione [dei criteri di Azure Information Protection](/azure/information-protection/configure-policy).

Per la funzionalità scanner AIP, Microsoft non si impegna a fornire funzionalità di classificazione, etichettatura o protezione dei file agli utenti che non dispongono di licenza.

## <a name="information-governance"></a>Governance dell'informazione

La governance delle informazioni consente alle organizzazioni di gestire i propri rischi scoprendo, classificando, etichettando e regolando i propri dati. La governance delle informazioni consente alle organizzazioni di soddisfare i requisiti aziendali e normativi e di ridurre la superficie di attacco fornendo funzionalità di conservazione ed eliminazione in tutti i Microsoft 365 e di terze parti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di classificare i dati a scopo di conservazione per rispettare criteri e regolamenti specifici.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 e i piani Exchange autonomi offrono all'utente il diritto di trarre vantaggio dall'applicazione manuale di etichette di conservazione non record ai dati delle cassette postali.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 e i piani SharePoint autonomi offrono all'utente il diritto di trarre vantaggio dall'applicazione manuale di etichette di conservazione non record ai file in SharePoint o OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 e Archiviazione Exchange Online forniscono all'utente il diritto di beneficiare di criteri di conservazione delle cassette postali di base a livello di organizzazione o di posizione e/o di applicare manualmente un'etichetta di conservazione non record ai dati delle cassette postali.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3/A3 e SharePoint Piano 2 forniscono all'utente il diritto di beneficiare di un criterio di conservazione SharePoint o OneDrive di base e/o di applicare manualmente un'etichetta di conservazione non record ai file in SharePoint o OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 e Office 365 E5/A5/G5/E3/A3 forniscono all'utente il diritto di beneficiare di un criterio di conservazione Teams dati.

Microsoft 365 E5/A5/G5, conformità Microsoft 365 E5/A5/G5, protezione e governance delle Microsoft 365 e governance E5/A5/G5, e Office 365 E5/A5 forniscono a un utente i diritti di beneficiare dell'applicazione automatica di etichette o criteri di conservazione, dell'applicazione di etichette o criteri di conservazione predefiniti, dell'avvio del periodo di conservazione di un'etichetta di conservazione in base a un evento personalizzato, dell'attivazione di una revisione manuale della disposizione alla fine del periodo di conservazione dell'etichetta, dell'importazione di dati di terze parti tramite connettori di dati nativi, della dichiarazione di un file di un record, dell'individuazione di contenuto etichettato e del monitoraggio dell'attività di etichettatura.

Microsoft 365 E5/A5/G5, conformità Microsoft 365 E5/A5/G5, protezione delle informazioni Microsoft 365 E5/A5/G5 e governance offrono all'utente il diritto di beneficiare dell'applicazione automatica di etichette di conservazione basate su classificatori addestrabili.

Per diritti specifici per licenza, vedere la descrizione dettagliata Microsoft 365 delle licenze di conformità. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [Signor Presidente, signor Presidente, signor Presidente, signor Presidente in Excel](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di governance delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione della governance delle informazioni per l'applicazione dell'etichettatura automatica e dei criteri per gli utenti con licenza, [vedere Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Le funzionalità di governance delle informazioni possono essere applicate agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione della governance delle informazioni per l'applicazione dell'etichettatura automatica e dei criteri per gli utenti con licenza, [vedere Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gestione record

Gestione dei record consente alle organizzazioni di soddisfare i propri obblighi aziendali e normativi di conservazione dei record attraverso l'individuazione, la classificazione, l'etichettatura, la conservazione e le funzionalità di eliminazione difendibili nei dati Microsoft 365 e di terze parti.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 e Office 365 E5/A5/G5 forniscono all'utente il diritto di beneficiare della gestione dei record, inclusa la dichiarazione di elementi come record o record normativi, l'applicazione automatica di etichette di conservazione o di registrazione e l'esecuzione di processi di revisione della disposizione (esclusa l'applicazione automatica di un'etichetta di conservazione basata su classificatori addestrabili).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance forniscono all'utente il diritto di beneficiare dell'applicazione automatica di etichette di conservazione o di registrazione basate su classificatori addestrabili.

Per diritti specifici per licenza, vedere la descrizione dettagliata Microsoft 365 delle licenze di conformità. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [Signor Presidente, signor Presidente, signor Presidente, signor Presidente in Excel](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di dichiarare il contenuto come record e gestire il processo di record completo dalla definizione e dichiarazione dei criteri allo smaltimento difendibile.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di gestione dei record sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Gestione record per la richiesta di utenti con licenza, [vedere Informazioni sulla gestione dei record in Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Le funzionalità di gestione dei record possono essere applicate agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione di Gestione record per la richiesta di utenti con licenza, [vedere Informazioni sulla gestione dei record in Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Connettori dati 

Microsoft fornisce connettori dati di terze parti che possono essere configurati nel centro Microsoft 365 conformità. Per un elenco dei connettori dati forniti da Microsoft, vedere la [tabella Connettori dati di terze](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) parti. In questa tabella vengono inoltre riepilogate le soluzioni di conformità che è possibile applicare ai dati di terze parti dopo l'importazione e l'archiviazione dei dati in Microsoft 365 e i collegamenti alle istruzioni dettagliate per ogni connettore.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Il vantaggio principale dell'utilizzo dei connettori dati per importare e archiviare dati di terze parti in Microsoft 365 è che è possibile applicare varie soluzioni di conformità Microsoft 365 ai dati dopo che sono stati importati. Ciò consente di garantire che i dati non Microsoft dell'organizzazione siano conformi alle normative e agli standard che influiscono sull'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Le licenze seguenti forniscono all'utente i diritti di beneficiare dei connettori dati:

- Microsoft 365 E5/A5/G5
- Governance di Microsoft 365 E5 informazioni Microsoft 365 E5/A5/G5 &amp;
- conformità Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5 e Audit Microsoft 365 E5/A5/G5
- Office 365 E5/A5/G5

Per i connettori dati nel Centro conformità sicurezza Microsoft 365 forniti &amp; da un partner Microsoft, l'organizzazione avrà bisogno di una relazione commerciale con il partner prima di poter distribuire tali connettori.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

I connettori vengono configurati utilizzando il Centro conformità &amp; sicurezza e il catalogo dei connettori.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

I servizi Data Connectors sono un valore a livello di tenant. Ogni utente destinato a beneficiare di questo servizio deve essere concesso in licenza.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>API Graph Microsoft per la prevenzione Teams dati (DLP)

All'inizio di [quest'anno abbiamo annunciato l'anteprima pubblica dell'API di notifica delle modifiche Graph Microsoft per i messaggi in Teams](https://go.microsoft.com/fwlink/?linkid=2143888). Questa API consente agli sviluppatori di creare app in grado di ascoltare Microsoft Teams messaggi in tempo quasi reale e abilitare implementazioni di scenari DLP sia per i clienti che per gli ISV. Inoltre, l'API Graph patch Microsoft consente di applicare azioni DLP Teams messaggi.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

[Le funzionalità di prevenzione della perdita di dati (DLP)](/microsoft-365/compliance/dlp-microsoft-teams) sono ampiamente utilizzate in Microsoft Teams, in particolare perché le organizzazioni si sono spostate verso il lavoro remoto. Se l'organizzazione dispone di DLP, è ora possibile definire criteri che impediscano agli utenti di condividere informazioni riservate in un canale Microsoft Teams o in una sessione di chat.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Per ottenere il supporto per la protezione DLP in Teams Chat è necessaria una delle licenze seguenti:

- Microsoft 365 E5/A5/G5
- conformità Microsoft 365 E5/A5/G5
- Microsoft 365 E5 e governance delle informazioni Microsoft 365 E5/A5/G5
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

L'accesso alle API è configurato a livello di tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Microsoft Graph API per Teams DLP è un valore a livello di tenant. Ogni utente destinato a beneficiare di questo servizio deve essere concesso in licenza.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fornisce soluzioni di indagine ed eDiscovery per i reparti IT e legali all'interno delle società per identificare, raccogliere, conservare, ridurre ed esaminare i contenuti relativi a un'indagine o a un contenzioso prima dell'esportazione dal sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Un utente beneficia di Advanced eDiscovery quando l'utente viene selezionato come custode dei dati (una persona che ha il controllo amministrativo di un documento o di un file elettronico) per un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 forniscono a un utente i diritti di beneficiare di Core eDiscovery.

Microsoft 365 E5/A5/G5, conformità Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 eDiscovery and Audit e Office 365 E5/A5/G5 forniscono a un utente il diritto di beneficiare di Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, Advanced eDiscovery funzionalità di protezione vengono abilitate a livello di tenant per tutti gli utenti all'interno del tenant quando gli amministratori assegnano autorizzazioni di eDiscovery nel Centro conformità &amp; sicurezza.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori di eDiscovery possono selezionare utenti specifici come custodi dei dati per un caso utilizzando lo strumento di gestione dei custodi incorporato in Advanced eDiscovery come descritto in Aggiungere custodi a [un caso Advanced eDiscovery .](/microsoft-365/compliance/add-custodians-to-case)

## <a name="customer-key-for-microsoft-365"></a>Chiave cliente per Microsoft 365

Con Customer Key, è possibile controllare le chiavi di crittografia dell'organizzazione e configurare Microsoft 365 per utilizzarle per crittografare i dati a riposo nei data center Microsoft. In altre parole, Customer Key ti consente di aggiungere un livello di crittografia che ti appartiene, utilizzando le tue chiavi. I dati a riposo includono i dati Exchange Online e Skype for Business archiviati in cassette postali e file all'interno di SharePoint Online e OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla chiave del cliente crittografando i propri dati a livello di applicazione utilizzando chiavi di crittografia fornite, controllate e gestite dalla propria organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5, conformità Microsoft 365 E5/A5/G5, protezione e governance delle informazioni Microsoft 365 E5/A5/G5 e Office 365 E5/A5/G5 forniscono a un utente il diritto di beneficiare della chiave del cliente. Per ottenere il massimo vantaggio da Customer Key, è necessario avere anche una sottoscrizione per Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Le chiavi di crittografia customer key for Microsoft 365 possono essere abilitate per tutti i dati archiviati nelle cassette postali di Exchange Online e Skype for Business e per i file SharePoint Online, OneDrive for Business e Teams. Per ulteriori informazioni sulla chiave del cliente, inclusa la procedura per iniziare, vedere [Crittografia del servizio con chiave del cliente](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Per Exchange Online e Skype for Business, le cassette postali possono essere crittografate utilizzando la chiave del cliente. È necessario configurare Azure prima di poter usare la chiave del cliente per Microsoft 365. Per [i passaggi da seguire per](/microsoft-365/compliance/customer-key-set-up) creare e configurare le risorse di Azure necessarie e i passaggi per configurare la chiave del cliente in Microsoft 365. Dopo aver completato la configurazione di Azure, determinare quali criteri e, pertanto, quali chiavi assegnare alle cassette postali e ai file nell'organizzazione. Per ulteriori informazioni sulla chiave del cliente e sui contenuti relativi ai dati di Exchange Online, Skype for Business, SharePoint Online, OneDrive for Business e Teams, vedere [Crittografia del servizio con chiave del cliente](/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Customer Lockbox di Office 365

Customer Lockbox offre un ulteriore livello di controllo offrendo ai clienti la possibilità di concedere un'autorizzazione di accesso esplicita per le operazioni di servizio. Dimostrando che sono in atto procedure per l'autorizzazione esplicita all'accesso ai dati, Customer Lockbox può anche aiutare le organizzazioni a rispettare determinati obblighi di conformità come HIPAA e FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Customer Lockbox garantisce che nessuno in Microsoft possa accedere al contenuto del cliente per eseguire un'operazione di servizio senza l'approvazione esplicita del cliente. Customer Lockbox porta il cliente nel flusso di lavoro di approvazione per le richieste di accesso al contenuto. Occasionalmente, i tecnici Microsoft sono coinvolti durante il processo di supporto per risolvere e risolvere i problemi segnalati dai clienti. Nella maggior parte dei casi, i problemi vengono risolti tramite ampi strumenti di telemetria e debug disponibili da Microsoft per i propri servizi. Tuttavia, potrebbero esserci casi che richiedono a un tecnico Microsoft di accedere al contenuto del cliente per determinare la causa principale e risolvere il problema. Con Customer Lockbox, il tecnico deve richiedere al cliente l'accesso come fase finale del flusso di lavoro di approvazione. Ciò offre alle organizzazioni la possibilità di approvare o negare queste richieste, il che offre loro il controllo diretto sulla possibilità per un tecnico Microsoft di accedere ai dati dell'utente finale delle organizzazioni.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono ai clienti il diritto di beneficiare di Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Gli amministratori possono attivare Customer Lockbox nell'interfaccia di amministrazione Microsoft 365 di amministrazione. Per ulteriori informazioni, vedere [Customer Lockbox in Office 365](/microsoft-365/compliance/customer-lockbox-requests). Quando Customer Lockbox è attivato, Microsoft è tenuta a ottenere l'approvazione di un'organizzazione prima di accedere a qualsiasi contenuto.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Attualmente, il servizio Customer Lockbox non può essere limitato a utenti specifici. È necessario concedere in licenza ogni utente a cui si intende beneficiare.

## <a name="privileged-access-management-in-office-365"></a>Gestione degli accessi privilegiati in Office 365

[La gestione degli accessi privilegiati (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) fornisce un controllo granulare degli accessi sulle attività di amministrazione con privilegi Office 365. Dopo aver abilitato PAM, per completare attività elevate e privilegiate, gli utenti dovranno richiedere l'accesso just-in-time tramite un flusso di lavoro di approvazione con ambito elevato e con limiti di tempo.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

L'abilitazione di PAM consente alle organizzazioni di operare con privilegi zero standing. Gli utenti beneficiano dell'ulteriore livello di difesa contro le vulnerabilità derivanti dall'accesso amministrativo permanente che fornisce un accesso illimitato ai propri dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio? 

Office 365 E5/A5, Microsoft 365 E5/A5, conformità Microsoft 365 E5/A5 e protezione e governance delle informazioni Microsoft 365 E5/A5 forniscono a un utente il diritto di beneficiare di PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità PAM sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri PAM, vedere [Introduzione alla gestione degli accessi con privilegi](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

I clienti possono gestire PAM in base all'utente tramite il gruppo di approvatori e i criteri di accesso, che possono essere applicati agli utenti con licenza. Per ulteriori informazioni, vedere [Gestione degli accessi privilegiati in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Crittografia a doppia chiave per Microsoft 365 

Double Key Encryption per Microsoft 365 consente di proteggere i dati altamente sensibili per soddisfare requisiti specializzati e mantenere il pieno controllo della chiave di crittografia. Crittografia a doppia chiave utilizza due chiavi per proteggere i dati, con una chiave nel controllo e la seconda chiave archiviata in modo sicuro da Microsoft Azure. Per visualizzare i dati, è necessario avere accesso a entrambe le chiavi. Poiché Microsoft può accedere a una sola chiave, la chiave e anche i dati non sono disponibili per Microsoft, assicurandosi di avere il pieno controllo sulla privacy e sulla sicurezza dei dati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti beneficiano della crittografia a doppia chiave essendo in grado di migrare i propri dati crittografati nel cloud, il che impedisce l'accesso di terze parti finché la chiave rimane in controllo degli utenti. Gli utenti possono proteggere e utilizzare contenuti crittografati a doppia chiave simili a qualsiasi altro contenuto protetto da etichette di riservatezza.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance e Office 365 E5/A5/G5 forniscono ai consumatori il diritto di beneficiare della crittografia a doppia chiave.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Double Key Encryption supporta la versione desktop di Microsoft Office per Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Per assegnare chiavi di crittografia ai dati all'interno di un Office 365 e/o Microsoft 365 per utenti con licenza, seguire le istruzioni di distribuzione Crittografia a doppia chiave.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 prevenzione della perdita di dati per Exchange Online, SharePoint online e OneDrive for Business

Con Office 365 prevenzione della perdita di dati (DLP) per Exchange Online, SharePoint Online e OneDrive for Business, le organizzazioni possono identificare, monitorare e proteggere automaticamente le informazioni riservate tra e-mail e file (inclusi i file archiviati in repository di file Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti beneficiano di DLP per Exchange Online, SharePoint Online e OneDrive for Business quando i messaggi di posta elettronica e i file vengono ispezionati alla ricerca di informazioni riservate, come configurato nei criteri DLP dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 e Office 365 Data Loss Prevention forniscono all'utente il diritto di beneficiare di un DLP Office 365 per Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, Exchange Online di posta elettronica, SharePoint siti e account OneDrive sono *percorsi abilitati (carichi di lavoro)* per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of data loss prevention](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono personalizzare i percorsi (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro conformità &amp; sicurezza, in Percorsi di prevenzione della perdita **di**  >  **dati**.

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenzione della perdita di dati di comunicazione per Teams

Con Communication DLP per Teams, le organizzazioni possono bloccare chat e messaggi di canale che contengono informazioni riservate, ad esempio informazioni finanziarie, informazioni di identificazione personale, informazioni relative alla salute o altre informazioni riservate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti beneficiano del servizio?

Gli utenti autorizzati di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Information Protection and Governance possono beneficiare di Communication DLP per Teams.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti traggono vantaggio dal fatto che le informazioni riservate nei messaggi di chat e canale in uscita siano ispezionate alla ricerca di informazioni riservate, come configurato nei criteri DLP dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, Teams chat e i messaggi di canale sono una *posizione (carico di lavoro) abilitata* per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of data loss prevention](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono personalizzare i percorsi (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro conformità &amp; sicurezza, in Percorsi di prevenzione della perdita **di**  >  **dati**.

## <a name="information-barriers"></a>Barriere informative

Le barriere informative sono criteri che un amministratore può configurare per impedire a singoli utenti o a gruppi di comunicare tra loro. Ciò è utile se, ad esempio, un reparto gestisce informazioni che non devono essere condivise con altri reparti o se è necessario impedire a un gruppo di comunicare con contatti esterni. I criteri di barriera delle informazioni impediscono anche le ricerca e l'individuazione. Ciò significa che se tenti di comunicare con qualcuno con cui non dovresti comunicare, non troverai quell'utente nella selezione utenti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti beneficiano delle funzionalità avanzate di conformità delle barriere informative quando è loro limitato comunicare con gli altri. Le politiche sulle barriere informative possono essere definite per impedire a determinati segmenti di utenti di comunicare con ciascuno o consentire a segmenti specifici di comunicare solo con determinati altri segmenti. Per ulteriori informazioni sulla definizione dei criteri di barriera delle informazioni, vedere [Define information barrier policies](/microsoft-365/compliance/information-barriers-policies). Per gli scenari in cui due gruppi non possono comunicare tra loro, gli utenti di entrambi i gruppi richiedono una licenza per beneficiare del servizio (vedere l'esempio seguente).<br><br>

| Scenario | Who richiede una licenza? |
|:------|:------|
| Due gruppi (Gruppo 1 e Gruppo 2) non possono comunicare tra loro, o o meglio gli utenti del Gruppo 1 non possono &nbsp; comunicare con gli utenti del Gruppo &nbsp; &nbsp; &nbsp; 2 e agli utenti del Gruppo &nbsp; 2 è limitata la comunicazione con gli utenti &nbsp; del Gruppo 1. | Utenti sia nel Gruppo &nbsp; 1 che nel Gruppo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management e Office 365 E5/A5/G5, forniscono il diritto per un utente di beneficiare delle barriere informative.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Gli amministratori creano e gestiscono criteri di barriera delle informazioni utilizzando i cmdlet di PowerShell nel Centro conformità &amp; alla sicurezza. Agli amministratori deve essere assegnato il ruolo Microsoft 365 Enterprise Amministratore globale, Office 365 Amministratore globale o Amministratore conformità per creare un criterio di barriera delle informazioni. Per impostazione predefinita, questi criteri si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulle barriere informative, vedere [Barriere informative in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori possono personalizzare i percorsi (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro conformità &amp; sicurezza. Ad esempio, se tutti gli utenti hanno la licenza per Office 365 E3 e nessuno è concesso in licenza per Office 365 Advanced Compliance/E5, non dovrebbero creare criteri di barriera delle informazioni per l'organizzazione. Per altre informazioni, vedere [Barriere informative in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Crittografia messaggi di Office 365 (OME) è un servizio basato su Azure Rights Management (Azure RMS) che consente di inviare posta elettronica crittografata a destinatari interni o esterni all'organizzazione, indipendentemente dall'indirizzo di posta elettronica di destinazione (Gmail, Yahoo! Mail, Outlook.com e così via).

Per visualizzare messaggi crittografati, i destinatari possono ottenere un passcode monouso, accedere con un account Microsoft oppure accedere con un account aziendale o dell'istituto di istruzione associato a Office 365. I destinatari possono anche inviare risposte crittografate. Non hanno bisogno di un abbonamento per visualizzare i messaggi crittografati o inviare risposte crittografate.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti dei messaggi beneficiano del controllo aggiunto sui messaggi di posta elettronica sensibili forniti Office 365 Message Encryption.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 e Azure Information Protection Plan 1 forniscono i diritti di un utente per beneficiare di Office 365 Message Encryption.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Gli amministratori creano e gestiscono Office 365 Message Encryption nell'interfaccia di amministrazione Exchange in Regole **flusso di**  >  **posta**. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione di nuove funzionalità Office 365 Message Encryption, vedere [Configurare nuove funzionalità di crittografia dei messaggi](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori devono applicare regole del flusso di posta per Office 365 Message Encryption solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere Define [mail flow rules to encrypt email messages](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Office 365 Advanced Message Encryption i clienti a rispettare gli obblighi di conformità che richiedono controlli più flessibili sui destinatari esterni e sul loro accesso alle e-mail crittografate. Con crittografia avanzata dei messaggi, gli amministratori possono controllare i messaggi di posta elettronica sensibili condivisi all'esterno dell'organizzazione utilizzando criteri automatici in grado di rilevare tipi di informazioni riservate (ad esempio, informazioni di identificazione personale o ID finanziari o sanitari) oppure possono utilizzare parole chiave per migliorare la protezione applicando modelli di posta elettronica personalizzati e l'accesso in scadenza ai messaggi di posta elettronica crittografati tramite un portale Web sicuro. Inoltre, gli amministratori possono controllare ulteriormente le e-mail crittografate a cui si accede esternamente tramite un portale Web sicuro revocando l'accesso in qualsiasi momento.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti dei messaggi beneficiano del controllo aggiunto sui messaggi di posta elettronica sensibili forniti da Crittografia avanzata messaggi.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Office 365 La conformità E5/A5/G5, Microsoft 365 E5/A5/G5, la conformità Microsoft 365 E5/A5/G5 e la protezione e la governance delle informazioni Microsoft 365 E5/A5/G5 forniscono ai cittadini i diritti di beneficiare della crittografia avanzata dei messaggi.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Gli amministratori creano e gestiscono criteri di crittografia avanzata dei messaggi nell'Exchange di amministrazione in **Regole flusso di**  >  **posta**. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione di nuove funzionalità di crittografia dei messaggi, [vedere Configurare nuove funzionalità Office 365 Message Encryption messaggi](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per crittografia avanzata dei messaggi solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [Define mail flow rules to encrypt email messages in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformità delle comunicazioni

La conformità alle comunicazioni Microsoft 365 consente di ridurre al minimo i rischi di comunicazione aiutandoti a rilevare, acquisire e intraprendere azioni correttive per messaggi inappropriati nell'organizzazione. È possibile definire criteri specifici che acquisiscono posta elettronica interna ed esterna, Microsoft Teams o comunicazioni di terze parti nell'organizzazione. I revisori possono intraprendere le azioni correttive appropriate per assicurarsi che siano conformi agli standard dei messaggi dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli specialisti della conformità beneficiano del servizio facendo monitorare le comunicazioni dell'organizzazione dai criteri di conformità delle comunicazioni.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono a un utente il diritto di beneficiare della conformità alle comunicazioni.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Gli amministratori e gli specialisti della conformità creano criteri di conformità alle comunicazioni nel centro Microsoft 365 conformità di conformità. Questi criteri definiscono quali comunicazioni e utenti sono soggetti a revisione nell'organizzazione, definiscono le condizioni personalizzate che le comunicazioni devono soddisfare e specificano chi deve eseguire le revisioni.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Gli amministratori scelgono utenti o gruppi specifici da includere in un criterio di conformità delle comunicazioni. Quando si sceglie un gruppo, è anche possibile selezionare utenti specifici del gruppo da escludere dai criteri di conformità delle comunicazioni. Per ulteriori informazioni sui criteri di conformità delle comunicazioni, [vedere Introduzione alla conformità delle comunicazioni in Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gestione dei rischi Insider

La gestione dei rischi insider è una soluzione in Microsoft 365 che consente di ridurre al minimo i rischi interni consentendo di rilevare, analizzare e intervenire sulle attività rischiose nell'organizzazione.

I criteri personalizzati consentono di rilevare e intervenire su attività dannose e inavvertitamente rischiose nell'organizzazione, inclusa l'escalation di casi a Microsoft Advanced eDiscovery, se necessario. Gli analisti dei rischi dell'organizzazione possono eseguire rapidamente le azioni appropriate per assicurarsi che gli utenti siano conformi agli standard di conformità dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dal fatto che le loro attività siano monitorate per il rischio.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di beneficiare del servizio?

Microsoft 365 E5/A5/G5, la conformità Microsoft 365 E5/A5/G5 e la gestione dei rischi insider Microsoft 365 E5/A5/G5 forniscono all'utente il diritto di beneficiare della gestione dei rischi insider.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

I criteri di gestione dei rischi insider devono essere creati nel centro Microsoft 365 conformità e assegnati agli utenti.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Quando si crea un criterio nel Centro conformità Microsoft 365, nella **pagina Scegliere utenti e gruppi** selezionare Scegli utenti o **gruppi** per selezionare solo utenti con licenza oppure, se tutti gli utenti hanno la licenza, è possibile selezionare la casella di controllo Tutti gli utenti e i **gruppi abilitati** alla posta elettronica. Per ulteriori informazioni, vedere [Introduzione alla gestione dei rischi insider](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Criteri di accesso condizionale

L'Accesso condizionale è uno strumento utilizzato da Azure Active Directory per riunire i segnali, per prendere decisioni e far rispettare i criteri aziendali. L'accesso condizionale è al centro del controllo basato sull'identità. I criteri di accesso condizionale, nella loro forma più semplice, sono istruzioni if-then. Se un utente desidera accedere a una risorsa, deve completare un'azione. Esempio: un responsabile delle retribuzioni desidera accedere all'applicazione retributiva ed è tenuto a eseguire l'autenticazione a più fattori per accedervi.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti beneficiano del servizio?

Gli utenti con licenza Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium e Azure Active Directory Premium Plan 1 possono beneficiare dei criteri di accesso condizionale. Gli utenti con licenza di Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security e Azure Active Directory Premium Plan 2 possono beneficiare di Identity Protection (criteri di accesso condizionale basati sul rischio).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti delle operazioni di sicurezza e i professionisti della sicurezza traggono vantaggio dalla possibilità di applicare criteri organizzativi agli utenti, richiedendo loro di soddisfare determinati criteri prima di concedere l'accesso ai contenuti aziendali. Gli utenti finali traggono vantaggio dalla possibilità di accedere al proprio lavoro ovunque e quando lo desiderano, proteggendo al contempo le risorse dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, le funzionalità di accesso condizionale sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

Per la protezione delle identità e l'accesso condizionale in modo specifico, un utente deve essere incluso in un gruppo o essere aggiunto a un criterio di accesso condizionale. La condizione utenti e gruppi è obbligatoria in un criterio di accesso condizionale. Nei criteri è possibile selezionare Tutti gli **utenti o** utenti e gruppi specifici. È necessario selezionare solo utenti e gruppi con licenza appropriata. Per ulteriori informazioni, vedere [Accesso condizionale: Condizioni](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Audit avanzato

Advanced Audit in Microsoft 365 fornisce la conservazione di un anno dei registri di controllo per le attività di utenti e amministratori e consente di creare criteri di conservazione del log di controllo personalizzati per gestire la conservazione del log di controllo per altri servizi Microsoft 365 di controllo. Fornisce inoltre l'accesso a eventi cruciali per le indagini e l'accesso ad alta larghezza di banda all'API Office 365 management activity. Per ulteriori informazioni, vedere [Controllo avanzato in Microsoft 365](/microsoft-365/compliance/advanced-audit).

È inoltre possibile abilitare un periodo di conservazione di 10 anni con uno SKU aggiuntivo. L'USK aggiuntivo sarà richiesto a partire dall'inizio del 2021.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti beneficiano del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 eDiscovery and Audit possono beneficiare di Advanced Audit.

Gli utenti con licenza con controllo avanzato e il componente aggiuntivo di conservazione del registro di controllo di 10 anni possono beneficiare della conservazione del registro di controllo di 10 anni.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti vengono avvantaggiati da Controllo avanzato perché i record di controllo relativi all'attività degli utenti nei Microsoft 365 servizi possono essere conservati per un massimo di un anno. Inoltre, vengono registrati eventi di controllo di alto valore, ad esempio quando si accede o si leggeno elementi nella cassetta postale di un utente. Per ulteriori informazioni, vedere [Controllo avanzato in Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene esorato/distribuito il servizio?

Per impostazione predefinita, Controllo avanzato è abilitato a livello di tenant per tutte le organizzazioni che hanno una sottoscrizione Office 365 o Microsoft 365 E5/A5/G5 e fornisce automaticamente la conservazione di un anno dei registri di controllo per le attività (eseguite dagli utenti con la licenza appropriata) in Azure Active Directory, Exchange e SharePoint. Inoltre, le organizzazioni possono utilizzare i criteri di conservazione del log di controllo per gestire il periodo di conservazione per i record di controllo generati dall'attività in altri Microsoft 365 servizi. Anche la funzionalità di conservazione del registro di controllo di 10 anni è abilitata utilizzando gli stessi criteri di conservazione. Per altre informazioni, vedere [Gestire i criteri di conservazione dei log di controllo](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come può il servizio essere applicato solo agli utenti del tenant che hanno la licenza per il servizio?

La conservazione di un anno dei registri di controllo e il controllo degli eventi cruciali si applicano solo agli utenti con la licenza appropriata. Inoltre, gli amministratori possono utilizzare i criteri di conservazione del log di controllo per specificare durate di conservazione più brevi per i registri di controllo di utenti specifici.

La conservazione di 10 anni dei registri di controllo si applica solo agli utenti con la licenza del componente aggiuntivo appropriata. L'USK aggiuntivo sarà necessario a partire dall'inizio del 2021.