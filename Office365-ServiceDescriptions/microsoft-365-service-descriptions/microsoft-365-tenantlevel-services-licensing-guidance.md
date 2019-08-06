---
title: Guida alla gestione delle licenze di servizi a livello di Microsoft 365
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: In questo articolo vengono fornite indicazioni per la gestione delle licenze per i servizi a livello di tenant di Microsoft 365 per evitare potenziali interruzioni del servizio a causa dell'accesso senza licenza.
ms.openlocfilehash: 3c77928869c3735a5bad14eafeac0a248455f5e0
ms.sourcegitcommit: 61b4778f15b4b793b41033c4692e632a0351a0e3
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2019
ms.locfileid: "36206866"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Guida alla gestione delle licenze di servizi a livello di Microsoft 365

Ai fini di questo articolo, un servizio a livello di tenant è un servizio online che&mdash;, quando è stato acquistato per qualsiasi utente del tenant (autonomo o come parte di Office 365 o Microsoft&mdash;365), viene attivato parzialmente o integralmente per tutti gli utenti del tenant. Sebbene alcuni utenti senza licenza possano tecnicamente essere in grado di accedere al servizio, è necessaria una licenza per qualsiasi utente che si intende trarre vantaggio dal servizio.

> [!NOTE]
> Alcuni servizi tenant non sono attualmente in grado di limitare i vantaggi per utenti specifici. È necessario compiere sforzi per limitare i vantaggi del servizio agli utenti con licenza. In questo modo si eviterà possibili interruzioni del servizio nell'organizzazione una volta che sono disponibili le funzionalità di assegnazione.

## <a name="azure-active-directory-identity-protection"></a>Protezione dell'identità di Azure Active Directory

Azure Active Directory Identity Protection (AADIP) è una funzionalità del piano di Azure Active Directory Premium P2 che consente di rilevare potenziali vulnerabilità che interessano le identità dell'organizzazione, configurare le risposte automatiche per rilevare sospetti azioni correlate alle identità dell'organizzazione e analisi degli incidenti sospetti e intraprendere azioni appropriate per risolverli.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Azure Active Directory Premium Plan 2 possono trarre vantaggio da AADIP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli analisti e i professionisti della sicurezza di secops traggono vantaggio dalle visualizzazioni consolidate degli utenti contrassegnati e degli eventi di rischio basati su algoritmi di apprendimento automatico. Gli utenti finali usufruiscono della protezione automatica fornita tramite l'accesso condizionale basato sui rischi e la maggiore sicurezza fornita agendo sulle vulnerabilità.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di AADIP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di AADIP, vedere Abilitazione di [Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono assegnare un ambito AADIP assegnando criteri di rischio che definiscono il livello per la reimpostazione delle password e che consentono l'accesso solo per gli utenti con licenza. Per istruzioni su come ambito delle distribuzioni di AADIP, vedere [Configure the Sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Protezione avanzata dalle minacce di Azure

Azure Advanced Threat Protection (ATP) è un servizio cloud che consente di proteggere gli ambienti ibridi aziendali da più tipi di attacchi informatici e minacce privilegiate avanzate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e la protezione avanzata dalle minacce di Azure per gli utenti possono trarre vantaggio da Azure ATP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli analisti di SecOp e i professionisti della sicurezza traggono vantaggio dalla capacità di Azure ATP di rilevare ed esaminare minacce avanzate, identità compromesse e azioni Insider dannose. Gli utenti finali usufruiscono del monitoraggio dei dati da parte di Azure ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Azure ATP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Azure ATP, vedere [creare l'istanza di Azure ATP](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Microsoft non si impegna a fornire funzionalità di rilevamento delle minacce agli utenti che non dispongono di una licenza. Nel corso del tempo, i controlli delle licenze o degli strumenti mirati verranno aggiunti a Azure ATP per garantire che la funzionalità di Azure ATP sia applicabile solo agli utenti con licenza.

## <a name="azure-information-protection"></a>Azure Information Protection

Azure Information Protection (AIP) consente alle organizzazioni di individuare, classificare, etichettare e proteggere i documenti e i messaggi di posta elettronica sensibili. Gli amministratori possono definire regole e condizioni per applicare automaticamente le etichette, gli utenti possono applicare le etichette manualmente oppure è possibile utilizzare&mdash;una combinazione di due, in cui gli utenti ricevono suggerimenti per l'applicazione delle etichette.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Microsoft 365 F1, Microsoft 365 business, Microsoft 365 E3/a3/G3 e AIP Plan 1 possono trarre vantaggio da AIP piano 1. Gli utenti con licenza di Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e AIP piano 2 possono trarre vantaggio da AIP piano 2.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

La funzionalità di scansione AIP consente di classificare, contrassegnare e proteggere automaticamente i file che risiedono in archivi di file locali.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità AIP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri di AIP per gli utenti con licenza, vedere [attivazione di Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service).
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

I criteri di funzionalità AIP (eccetto la caratteristica scanner) possono essere inclusi nell'ambito di gruppi o utenti specifici; i registri possono essere modificati per impedire agli utenti senza licenza di eseguire le funzionalità di classificazione o etichettatura di AIP. Per istruzioni su come ambito delle distribuzioni AIP, vedere [Configuring the Azure Information Protection Policy](https://docs.microsoft.com/azure/information-protection/configure-policy).

Per la funzionalità di scanner AIP, Microsoft non si impegna a fornire la classificazione dei file, le etichette o le funzionalità di protezione per gli utenti che non dispongono di una licenza. Nel corso del tempo, i controlli delle licenze o degli strumenti mirati verranno aggiunti a AIP per garantire che la funzionalità dello scanner sia assegnabile agli utenti con licenza.

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

Advanced Threat Protection (ATP) consente di proteggere le organizzazioni da attacchi sofisticati, come il phishing e il malware zero-day. Inoltre, fornisce informazioni utili per la correlazione dei segnali provenienti da una vasta gamma di dati per identificare, definire in modo prioritario e fornire suggerimenti su come affrontare potenziali minacce.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 business e Office 365 ATP piani 1 e 2 possono trarre vantaggio da ATP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

ATP protegge gli utenti da attacchi sofisticati, come il phishing e il malware zero-day. Per l'elenco completo dei servizi forniti in piano 1 e piano 2, vedere [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità ATP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri ATP per gli utenti con licenza, vedere [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Per l'ambito ATP, seguire i collegamenti sicuri e i criteri di distribuzione degli allegati sicuri:

  - Per informazioni sulla configurazione dei collegamenti sicuri per gli utenti con licenza, vedere [set up Office 365 ATP Safe Links Policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies).

  - Per informazioni sulla configurazione degli allegati sicuri per gli utenti con licenza, vedere Configurare i criteri per gli [allegati sicuri ATP di Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 cloud app Security (OCAS) è un sottoinsieme di Microsoft cloud app Security, con funzionalità limitate a Office 365 e senza ulteriore sicurezza per le app cloud di terze parti e i servizi di IaaS.

OCAS offre alle organizzazioni visibilità nelle app e nei servizi cloud per la produttività, fornisce analisi sofisticate per identificare e combattere le minacce cibernetiche e consente&mdash;loro di controllare il modo in cui i dati viaggiano tra Office 365.

Per confrontare le funzionalità, vedere [differenze tra Microsoft cloud app Security e Office 365 cloud app Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5 possono trarre vantaggio da OCAS.

Per ulteriori informazioni, vedere il [foglio dati di Microsoft cloud app Security Licensing](http://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

OCAS rileva Shadow IT, fornisce una protezione dalle minacce in Office 365 e può controllare quali app dispongono dell'autorizzazione per accedere ai dati di Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di OCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione del servizio, vedere [configurazione di base per cloud app Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono accedere alle distribuzioni di OCAS per applicare la modalità di accesso a determinate app e limitare i gruppi di utenti monitorati da Office 365 cloud app Security. Per ulteriori informazioni, vedere [distribuzione con ambito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft cloud app Security (MCAS) è una soluzione CASB (cloud Access Security Broker) che offre alle organizzazioni visibilità nelle app e nei servizi cloud, fornisce analisi sofisticate per identificare e combattere le minacce cibernetiche e consente loro di controllare il modo in cui i dati si&mdash;sposta su qualsiasi app cloud.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security possono trarre vantaggio da MCAS.

Gli utenti con licenza di Azure AD P1 possono trarre vantaggio dalle funzionalità di individuazione di MCAS.

Per usufruire delle funzionalità di [controllo delle app con accesso condizionale](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) in MCAS, è necessario che gli utenti dispongano di una licenza per Azure Active Directory P1, incluso in Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/ Sicurezza di a3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5.

Per usufruire dell' [etichettatura automatica](https://docs.microsoft.com/cloud-app-security/data-protection-policies), gli utenti devono essere concessi in licenza per Azure Information Protection P2, incluso in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Compliance.

Per ulteriori informazioni, vedere il [foglio dati di Microsoft cloud app Security Licensing](http://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

MCAS rileva e valuta Shadow IT, fornisce una protezione dalle minacce tra le app cloud di primo e di terze parti e protegge le informazioni tra le app cloud di primo e di terze parti.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di MCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione dei criteri di protezione delle app di Microsoft Cloud per gli utenti con licenza, vedere [Microsoft cloud app Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono applicare le distribuzioni di MCAS agli utenti con licenza utilizzando le funzionalità di distribuzione con ambito disponibili nel servizio. Per ulteriori informazioni, vedere [distribuzione con ambito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="office-365-advanced-data-governance"></a>Office 365 Advanced Data Governance

Advanced Data Governance (ADG) consente alle organizzazioni di soddisfare i requisiti di governance delle informazioni con i criteri per abilitare la conservazione e l'eliminazione. ADG consente alle organizzazioni di assegnare etichette automatiche in base al tipo di informazioni riservate e di applicare criteri di governance al contenuto.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio da ADG.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

ADG consente agli utenti di applicare etichette a dati specifici per mantenere criteri specifici, etichettare automaticamente il contenuto come record e gestire il processo dei record completi dalla dichiarazione allo smaltimento.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di ADG sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di ADG per l'applicazione di etichette automatiche e dei criteri per gli utenti con licenza, vedere [Overview of](https://docs.microsoft.com/office365/securitycompliance/labels)retention labels.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

I criteri di conservazione di ADG possono essere applicati agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via) tramite classificazione automatica. Per istruzioni sull'applicazione dei criteri di conservazione di ADG, vedere [applicazione di un criterio di conservazione a un'intera organizzazione o a posizioni specifiche](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations).

## <a name="office-365-advanced-ediscovery"></a>Office 365 Advanced eDiscovery

Office 365 Advanced eDiscovery fornisce soluzioni di analisi e di eDiscovery per i servizi IT e legali all'interno delle società per identificare, raccogliere, preservare, ridurre ed esaminare i contenuti relativi a un'indagine o a una controversia preliminare prima dell'esportazione Sistema Office 365.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio da Advanced eDiscovery.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Un utente beneficia di Advanced eDiscovery quando l'utente viene selezionato come custode dei dati (una persona che ha il controllo amministrativo di un documento o di un file elettronico) per un caso.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità avanzate di eDiscovery sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant quando gli amministratori assegnano le autorizzazioni di eDiscovery nel centro sicurezza & conformità.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

gli amministratori di eDiscovery possono selezionare utenti specifici come depositari dei dati per un caso utilizzando lo strumento di gestione del custode incorporato in Advanced eDiscovery, come descritto in [aggiungere i depositari a un caso avanzato di eDiscovery](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case).

## <a name="office-365-customer-key"></a>Chiave cliente per Office 365

Con il codice "Customer Key", è possibile controllare le chiavi di crittografia dell'organizzazione e configurare Office 365 per utilizzarle per crittografare i dati a riposo nei data center di Microsoft. In altre parole, la chiave del cliente consente di aggiungere un livello di crittografia che appartiene all'utente, utilizzando le proprie chiavi. Data at rest include i dati di Exchange Online e Skype for business archiviati nelle cassette postali e nei file in SharePoint Online e OneDrive for business.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio dalla chiave del cliente. Per ottenere il massimo vantaggio dalla chiave del cliente, è necessario disporre anche di una sottoscrizione per Azure Key Vault.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dalla chiave del cliente, con i dati a riposo crittografati a livello di applicazione usando le chiavi di crittografia fornite, controllate e gestite dalla propria organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Le chiavi di crittografia per i clienti di Office 365 possono essere abilitate per tutti i dati archiviati in cassette postali di Exchange Online e Skype for business e per i file di SharePoint Online e OneDrive for business. Per informazioni sulla configurazione di Office 365 Customer Key per crittografare i dati a riposo, vedere Controlling [your data in Office 365 using Customer Key](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Per assegnare le chiavi di crittografia ai dati all'interno di un tenant di Office 365 e/o Microsoft 365 per gli utenti con licenza, seguire i criteri di distribuzione delle chiavi di crittografia dei clienti:

  - Per SharePoint Online, i file in uno o più siti possono essere crittografati utilizzando la chiave del cliente come descritto di seguito: [impostazione della chiave del cliente per SharePoint Online e OneDrive for business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business).

  - Per Exchange Online e Skype for business online, le cassette postali possono essere crittografate utilizzando la chiave del cliente come descritto di seguito: [impostazione della chiave del cliente per Exchange Online e Skype for business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Customer Lockbox di Office 365

L'archivio protetto dei clienti fornisce un ulteriore livello di controllo offrendo ai clienti la possibilità di concedere autorizzazioni di accesso esplicito per le operazioni del servizio. Dimostrando che le procedure sono disponibili per l'autorizzazione di accesso ai dati esplicita, l'archivio protetto dei clienti può anche aiutare le organizzazioni a soddisfare determinati obblighi di conformità, come HIPAA e FEDRAMP.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio dall'archivio protetto dei clienti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dall'archivio protetto dei clienti assicurando che nessuno può accedere al proprio contenuto per eseguire un'operazione di servizio senza l'approvazione esplicita del cliente. L'archivio protetto dei clienti porta il cliente nel flusso di lavoro di approvazione per le richieste di accesso al contenuto. In alcuni casi, gli ingegneri Microsoft sono coinvolti durante il processo di supporto per risolvere i problemi segnalati dai clienti. Nella maggior parte dei casi, i problemi vengono risolti tramite una vasta gamma di telemetria e strumenti di debug per i servizi di Microsoft. Tuttavia, potrebbe essere necessario che un tecnico Microsoft acceda ai contenuti dei clienti per determinare la causa principale e risolvere il problema. L'archivio protetto dei clienti richiede all'ingegnere di richiedere l'accesso da parte del cliente come passaggio finale del flusso di lavoro di approvazione. Questo fornisce alle organizzazioni la possibilità di approvare o rifiutare queste richieste, in modo da consentire loro di controllare direttamente se un tecnico Microsoft può accedere ai dati degli utenti finali dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori possono abilitare i controlli archivio clienti all'interno dell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere [archivio protetto dei clienti in Office 365](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests). Quando l'archivio protetto dei clienti è attivato, è necessario che Microsoft ottenga l'approvazione di un'organizzazione prima di accedere a qualsiasi contenuto.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Microsoft non si impegna a fornire le richieste di approvazione per il controllo dell'accesso dei clienti per gli utenti che non dispongono di una licenza. Nel tempo, i controlli delle licenze o gli strumenti mirati verranno aggiunti all'archivio protetto dei clienti per assicurarsi che l'archivio protetto dei clienti sia assegnabile agli utenti con licenza.

## <a name="privileged-access-management-in-office-365"></a>Gestione degli accessi con privilegi in Office 365

Gestione accessi con privilegi (PAM) fornisce il controllo di accesso granulare sulle attività di amministratore privilegiate in Office 365. Dopo aver abilitato PAM, gli utenti dovranno richiedere l'accesso just-in-time tramite un flusso di lavoro di approvazione estremamente ambito e con un limite di tempo per completare le attività elevate e con privilegi.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio da PAM.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

L'abilitazione di PAM consente alle organizzazioni di operare con zero privilegi permanenti. Gli utenti traggono vantaggio dal livello aggiunto di difesa dalle vulnerabilità derivanti dall'accesso amministrativo permanente che fornisce accesso illimitato ai propri dati.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità PAM sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri PAM, vedere Configuring [Privileged Access Management in Office 365](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

I clienti possono gestire PAM per ogni singolo utente tramite il gruppo di approvatori e i criteri di accesso, che possono essere applicati agli utenti con licenza. Per ulteriori informazioni, vedere [gestione degli accessi con privilegi in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenzione della perdita di dati per Exchange Online, SharePoint Online e OneDrive for business

Con la prevenzione della perdita di dati (DLP) per Exchange Online, SharePoint Online e OneDrive for business, le organizzazioni possono identificare, monitorare e proteggere automaticamente le informazioni riservate tra i messaggi di posta elettronica e i file (inclusi i file archiviati nel file di Microsoft Teams repository).

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E3/a3/G3, Microsoft 365 business, Microsoft 365 E3/a3/G3 e la prevenzione della perdita di dati di Office 365 possono trarre vantaggio da DLP per Exchange Online, SharePoint Online e OneDrive for business.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio da DLP per Exchange Online, SharePoint Online e OneDrive for business quando i messaggi di posta elettronica e i file vengono controllati per ottenere informazioni riservate, come configurato nei criteri DLP dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, i messaggi di posta elettronica di Exchange Online, i siti di SharePoint e gli account di OneDrive sono *posizioni abilitate (carichi di lavoro)* per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of Data Loss Prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel centro sicurezza & conformità di Office 365, in**posizioni**di **prevenzione** > della perdita di dati.

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>Prevenzione della perdita di dati per i messaggi di chat e canali dei team

Con la prevenzione della perdita di dati (DLP) per i messaggi di chat e di canale dei team, le organizzazioni possono bloccare chat e messaggi di canale che contengono informazioni riservate, ad esempio informazioni finanziarie, informazioni di identificazione personale, informazioni relative all'integrità o Altre informazioni riservate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio da DLP per i messaggi di chat e di canale di teams.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

I mittenti possono usufruire delle informazioni riservate nella chat in uscita e nei messaggi del canale ispezionati per ottenere informazioni riservate, come configurato nel criterio DLP dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, i messaggi chat e il canale dei team sono un *percorso abilitato (carico di lavoro)* per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of Data Loss Prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel centro sicurezza & conformità di Office 365, in**posizioni**di **prevenzione** > della perdita di dati.

## <a name="information-barriers"></a>Barriere informative

Le barriere informative sono criteri che un amministratore può configurare per impedire agli utenti o ai gruppi di comunicare tra loro. Ciò è utile se, ad esempio, un reparto gestisce informazioni che non devono essere condivise con altri reparti oppure che è necessario impedire a un gruppo di comunicare con i contatti esterni. I criteri barriera di informazioni impediscono anche le ricerche e l'individuazione. Questo significa che se si tenta di comunicare con un utente che non deve essere comunicante, non sarà possibile trovare tale utenti nello strumento di selezione utenti.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio dalle barriere informative.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dalle funzionalità di conformità avanzate delle barriere informative quando sono limitate dalla comunicazione con gli altri. Ad esempio:

| Scenario                                                                                                                                                                                                              | Chi ha bisogno di una licenza? |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Due gruppi (gruppo 1 e gruppo 2) non sono in grado di comunicare tra loro, ovvero gli utenti del gruppo 1 sono limitati dalla comunicazione con gli utenti del gruppo 2 e gli utenti del gruppo 2 sono limitati dalla comunicazione con gli utenti del gruppo 1. | Utenti sia del gruppo 1 che del gruppo 2                    |
| Gli utenti del gruppo 1 sono limitati dalla comunicazione con il resto della società.                                                                                                                                       | Solo gli utenti del gruppo 1                                |
| La parte restante della società è limitata dalla comunicazione con il gruppo 1.                                                                                                                                                 | Tutti gli utenti ad eccezione di quelli del gruppo 1                    |
| Gli utenti del gruppo 1 sono limitati dalla comunicazione con gli utenti del gruppo 2, ma gli utenti del gruppo 2 possono comunicare con gli utenti del gruppo 1.                                                                                              | Solo gli utenti del gruppo 1                                |

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di barriera delle informazioni utilizzando i cmdlet di PowerShell nel centro sicurezza & conformità. Gli amministratori devono essere assegnati all'amministratore globale di Microsoft 365 Enterprise, all'amministratore globale di Office 365 o al ruolo di amministratore di conformità per creare un criterio barriera informativo. Per impostazione predefinita, questi criteri si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulle barriere informative, vedere barriere informative [in Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel centro sicurezza & conformità di Office 365. Ad esempio, se tutti gli utenti sono concessi in licenza per Office 365 E3 e nessuno viene concesso in licenza per Office 365 Advanced Compliance/E5, non è necessario creare criteri di barriera delle informazioni per l'organizzazione. Per ulteriori informazioni, vedere [barriere informative in Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Crittografia messaggi di Office 365 (OME) è un servizio basato su Azure Rights Management (Azure RMS) che consente di inviare posta elettronica crittografata a destinatari interni o esterni all'organizzazione, indipendentemente dall'indirizzo di posta elettronica di destinazione (Gmail, Yahoo! Mail, Outlook.com e così via).

Per visualizzare i messaggi crittografati, i destinatari possono ottenere un passcode monouso, eseguire l'accesso con un account Microsoft o accedere con un account di lavoro o scolastico associato a Office 365. I destinatari possono inoltre inviare risposte crittografate. Non è necessario un abbonamento a Office 365 per visualizzare i messaggi crittografati o inviare risposte crittografate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E3/a3/G3, Microsoft 365 E3/a3/G3 e Azure Information Protection Plan 1 possono trarre vantaggio dalla crittografia dei messaggi di Office 365.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

I mittenti dei messaggi usufruiscono del controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia dei messaggi di Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia dei messaggi di Office 365 nell'interfaccia di amministrazione di Exchange in**regole**del **flusso** > di posta. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione delle nuove funzionalità di crittografia dei messaggi di Office 365, vedere [configurare le nuove funzionalità di crittografia dei messaggi di office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per la crittografia dei messaggi di Office 365 solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [definire le regole del flusso di posta per crittografare i messaggi di posta elettronica in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).


## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Crittografia avanzata dei messaggi consente ai clienti di soddisfare gli obblighi di conformità che richiedono controlli più flessibili su destinatari esterni e l'accesso ai messaggi di posta elettronica crittografati. Grazie alla crittografia avanzata dei messaggi, gli amministratori possono controllare i messaggi di posta elettronica sensibili condivisi all'esterno dell'organizzazione tramite criteri automatici in grado di rilevare tipi di informazioni riservate (ad esempio, informazioni di identificazione personale o ID finanziari o di integrità) oppure sono in grado di utilizzare parole chiave per migliorare la protezione applicando modelli di posta elettronica personalizzati e l'accesso a messaggi crittografati tramite un portale web sicuro. Gli amministratori possono inoltre controllare ulteriori messaggi di posta elettronica crittografati accessibili esternamente tramite un portale web sicuro, revocando l'accesso in qualsiasi momento.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio dalla crittografia avanzata dei messaggi.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

I mittenti dei messaggi usufruiscono del controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia avanzata dei messaggi.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia dei messaggi avanzati nell'interfaccia di amministrazione di Exchange in regole del flusso di posta. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione delle nuove funzionalità di crittografia dei messaggi, vedere [configurare le nuove funzionalità di crittografia messaggi di Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per la crittografia dei messaggi avanzata solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [definire le regole del flusso di posta per crittografare i messaggi di posta elettronica in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="supervision-policies"></a>Criteri di supervisione

I criteri di supervisione in Office 365 consentono di acquisire le comunicazioni dei dipendenti per l'esame da revisori designati. È possibile definire criteri specifici che consentono di acquisire messaggi di posta elettronica interni ed esterni, Microsoft teams o comunicazioni di terze parti nell'organizzazione. I revisori possono quindi esaminare i messaggi per assicurarsi che siano conformi agli standard dei messaggi dell'organizzazione e risolverli con il tipo di classificazione.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Office 365 Advanced compliance possono trarre vantaggio dai criteri di supervisione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti usufruiscono del servizio tramite le comunicazioni monitorate dai criteri di supervisione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano criteri di supervisione nel centro sicurezza & conformità. Questi criteri definiscono le comunicazioni e gli utenti soggetti a revisione nell'organizzazione, definiscono le condizioni personalizzate che devono soddisfare le comunicazioni e specificano chi deve eseguire le revisioni.
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori scelgono utenti o gruppi specifici da includere in un criterio di supervisione. Quando si sceglie un gruppo, è possibile selezionare anche utenti specifici del gruppo da escludere dai criteri di supervisione. Per ulteriori informazioni sulle politiche di supervisione, vedere [criteri di supervisione in Office 365](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies).
