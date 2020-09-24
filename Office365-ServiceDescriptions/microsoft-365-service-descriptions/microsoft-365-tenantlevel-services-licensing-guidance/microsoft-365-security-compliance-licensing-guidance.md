---
title: Guida alla gestione delle licenze Microsoft 365 per la conformità & di sicurezza
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: In questo articolo vengono fornite indicazioni per la gestione delle licenze per la conformità a Microsoft 365 per evitare possibili interruzioni del servizio a causa dell'accesso senza licenza.
ms.openlocfilehash: f2da71ee9bdc8f8250d3f4a98e8f09b0a43edede
ms.sourcegitcommit: 1e0e3f5a43431e9a732ee2ca4459332c410b07e7
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2020
ms.locfileid: "48245731"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Guida alla gestione delle licenze Microsoft 365 per la conformità & di sicurezza

Ai fini di questo articolo, un servizio a livello di tenant è un servizio online che, &mdash; quando è stato acquistato per qualsiasi utente del tenant (autonomo o come parte di Office 365 o Microsoft 365), &mdash; viene attivato parzialmente o integralmente per tutti gli utenti del tenant. Sebbene alcuni utenti senza licenza possano tecnicamente essere in grado di accedere al servizio, è necessaria una licenza per qualsiasi utente che si intende trarre vantaggio dal servizio.

> [!NOTE]
> Alcuni servizi tenant non sono attualmente in grado di limitare i vantaggi per utenti specifici. È necessario compiere sforzi per limitare i vantaggi del servizio agli utenti con licenza. In questo modo si eviterà possibili interruzioni del servizio nell'organizzazione una volta che sono disponibili le funzionalità di assegnazione.

Per visualizzare le opzioni per la concessione delle licenze agli utenti per usufruire delle funzionalità di conformità di Microsoft 365 del 1 ° aprile 2020, scaricare il confronto dettagliato di Microsoft 365 Compliance Licensing. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection è una funzionalità del piano di Azure Active Directory Premium P2 che consente di rilevare potenziali vulnerabilità che interessano le identità dell'organizzazione, configurare le risposte automatiche alle azioni sospette individuate correlate alle identità dell'organizzazione ed esaminare gli incidenti sospetti e intraprendere le azioni appropriate per risolverli.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli analisti e i professionisti della sicurezza di secops traggono vantaggio dalle visualizzazioni consolidate degli utenti contrassegnati e degli eventi di rischio basati su algoritmi di apprendimento automatico. Gli utenti finali usufruiscono della protezione automatica fornita tramite l'accesso condizionale basato sui rischi e la maggiore sicurezza fornita agendo sulle vulnerabilità.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e Azure Active Directory Premium Plan 2 forniscono i diritti per un utente di trarre vantaggio dalla protezione delle identità di Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le caratteristiche di Azure AD Identity Protection sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni su Azure AD Identity Protection, vedere [che cos'è Azure Active Directory Identity Protection?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono accedere a Azure AD Identity Protection assegnando criteri di rischio che definiscono il livello per la reimpostazione delle password e consentendo l'accesso solo per gli utenti con licenza. Per istruzioni su come ambito delle distribuzioni di Azure AD Identity Protection, vedere [Configure the Sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure Advanced Threat Protection (ATP) è un servizio cloud che consente di proteggere gli ambienti ibridi aziendali da più tipi di attacchi informatici e minacce privilegiate avanzate.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli analisti di SecOp e i professionisti della sicurezza traggono vantaggio dalla capacità di Azure ATP di rilevare ed esaminare minacce avanzate, identità compromesse e azioni Insider dannose. Gli utenti finali usufruiscono del monitoraggio dei dati da parte di Azure ATP.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

La sicurezza di Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 e la protezione avanzata dalle minacce di Azure per gli utenti offrono i diritti per trarre vantaggio da Azure ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Azure ATP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Azure ATP, vedere [creare l'istanza di Azure ATP](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

I servizi ATP di Azure attualmente non sono in grado di limitare le funzionalità a utenti specifici. È necessario concedere una licenza per ogni utente che si intende trarre vantaggio.

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

Advanced Threat Protection (ATP) consente di proteggere le organizzazioni da attacchi sofisticati, come il phishing e il malware zero-day. ATP fornisce anche informazioni utili per la correlazione dei segnali provenienti da una vasta gamma di dati per identificare, definire in modo prioritario e fornire suggerimenti su come affrontare potenziali minacce.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

ATP protegge gli utenti da attacchi sofisticati, come il phishing e il malware zero-day. Per l'elenco completo dei servizi forniti in piano 1 e piano 2, vedere [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio? 

Office 365 Advanced Threat Protection, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 Business Premium e Office 365 ATP piani 1 e 2 forniscono i diritti per un utente di trarre vantaggio dalla protezione avanzata dalle minacce.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità ATP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri ATP per gli utenti con licenza, vedere [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Per l'ambito ATP, seguire i collegamenti sicuri e i criteri di distribuzione degli allegati sicuri:

- Per informazioni sulla configurazione dei collegamenti sicuri per gli utenti con licenza, vedere [set up Office 365 ATP Safe Links Policies](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies).

- Per informazioni sulla configurazione degli allegati sicuri per gli utenti con licenza, vedere Configurare i criteri per gli [allegati sicuri ATP di Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 cloud app Security (OCAS) è un sottoinsieme di Microsoft cloud app Security, con funzionalità limitate a Office 365 e senza ulteriore sicurezza per le app cloud di terze parti e i servizi di IaaS.

OCAS offre alle organizzazioni visibilità nelle app e nei servizi cloud per la produttività, fornisce analisi sofisticate per identificare e combattere le minacce cibernetiche e consente loro di controllare il modo in cui i dati viaggiano &mdash; tra Office 365.

Per confrontare le funzionalità, vedere [differenze tra Microsoft cloud app Security e Office 365 cloud app Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

OCAS rileva Shadow IT, fornisce protezione dalle minacce in Office 365 e può controllare quali app dispongono dell'autorizzazione per l'accesso ai dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Office 365 E5/A5/G5 fornisce i diritti per un utente di trarre vantaggio da OCAS.
Per ulteriori informazioni, vedere il [foglio dati di Microsoft cloud app Security Licensing](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di OCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione del servizio, vedere [configurazione di base per cloud app Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono accedere alle distribuzioni di OCAS per applicare la modalità di accesso a determinate app e limitare i gruppi di utenti monitorati da Office 365 cloud app Security. Per ulteriori informazioni, vedere [distribuzione con ambito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft cloud app Security (MCAS) è una soluzione CASB (cloud Access Security Broker) che offre alle organizzazioni visibilità nelle app e nei servizi cloud, fornisce analisi sofisticate per identificare e combattere le minacce cibernetiche e consente loro di controllare il modo in cui i dati passano &mdash; attraverso qualsiasi app cloud.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

MCAS rileva e valuta Shadow IT, fornisce una protezione dalle minacce tra le app cloud di primo e di terze parti e protegge le informazioni tra le app cloud di primo e di terze parti.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 compliance e Microsoft 365 Information Protection and Governance offrono i diritti per un utente di trarre vantaggio da MCAS.

Azure AD P1 fornisce i diritti per un utente di trarre vantaggio dalle funzionalità di individuazione in MCAS.

Per usufruire delle funzionalità di controllo delle app con accesso condizionale in MCAS, è necessario che gli utenti dispongano di una licenza per Azure Active Directory P1, inclusa in Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/a3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security.

Per usufruire dell'etichettatura automatica, gli utenti devono essere concessi in licenza per Azure Information Protection P2, incluso in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 compliance e Microsoft 365 Information Protection and Governance.

Per ulteriori informazioni, vedere il [foglio dati di Microsoft cloud app Security Licensing](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di MCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione dei criteri di protezione delle app di Microsoft Cloud per gli utenti con licenza, vedere [Microsoft cloud app Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono applicare le distribuzioni di MCAS agli utenti con licenza utilizzando le funzionalità di distribuzione con ambito disponibili nel servizio. Per ulteriori informazioni, vedere [distribuzione con ambito](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Compliance Manager

Semplificare la conformità e ridurre i rischi con Compliance Manager. Compliance Manager consente alle organizzazioni di soddisfare i requisiti delle normative, degli standard, dei criteri aziendali o di altri Framework di controllo desiderati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Di seguito sono riportati i vantaggi per gli utenti dal servizio Compliance Manager:

- Traduce regolamenti complicati, standard, criteri aziendali o altri Framework di controllo desiderati in un linguaggio semplice
- Consente di accedere a una vasta raccolta di valutazioni e valutazioni personalizzate fuori dalla casella per soddisfare esigenze di conformità esclusive
- Mapping dei controlli normativi alle azioni di miglioramento consigliate
- Viene fornita una guida dettagliata su come implementare le soluzioni per soddisfare i requisiti normativi
- Consente agli utenti di assegnare priorità alle azioni che avranno il massimo impatto sulla conformità organizzativa associando un punteggio a ogni azione

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

I clienti con licenza di Office 365 E1/A1/E3/a3 e Microsoft 365 E3/a3 saranno in grado di accedere alla valutazione della linea di base per la protezione dei dati. I clienti con licenze Office 365 E5/A5 e Microsoft 365 E5/A5 saranno in grado di accedere alle valutazioni di protezione dei dati, GDPR, NIST 800-53 e ISO 22701. Le valutazioni dei premi saranno disponibili per l'acquisto ai clienti di Office 365 E5/A5 e Microsoft 365 E5/A5.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Compliance Manager è provisioning per impostazione predefinita per il tenant. Gli amministratori configurano le autorizzazioni utente e assegnano i ruoli in modo che gli utenti non amministratori dell'organizzazione possano iniziare a usare Compliance Manager. Per ulteriori informazioni, vedere [Introduzione a Compliance Manager: impostare le autorizzazioni utente e assegnare i ruoli](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

L'accesso a Compliance Manager è controllato mediante l'impostazione delle autorizzazioni utente e l'assegnazione dei ruoli. Per ulteriori informazioni, vedere [Introduzione a Compliance Manager: impostare le autorizzazioni utente e assegnare i ruoli](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-atp"></a>Microsoft Defender ATP

Microsoft Defender ATP è una soluzione di sicurezza per endpoint che include la valutazione e la gestione delle vulnerabilità basate sui rischi; funzionalità di riduzione della superficie di attacco; protezione comportamentale e basata su cloud di prossima generazione; rilevamento e risposta dell'endpoint (EDR); analisi e correzione automatica; e servizi di caccia gestiti. Per ulteriori informazioni, vedere pagina [Microsoft Defender ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) .

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Windows 10 Enterprise E5, Windows 10 Education a5, Microsoft 365 E5 (M365 E5), che include Windows 10 Enterprise E5, Microsoft 365 E5 Security, Microsoft 365 a5 (M365 a5) possono trarre vantaggio da Microsoft Defender ATP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli analisti di secops e i professionisti della sicurezza traggono vantaggio dalle funzionalità di sicurezza di endpoint di Microsoft Defender ATP per la protezione preventiva, il rilevamento post-violazione, l'analisi automatizzata e la risposta alle minacce avanzate. Gli utenti finali possono usufruire di eventi dannosi monitorati da Microsoft Defender ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le caratteristiche di Microsoft Defender ATP sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla distribuzione, vedere [Guida alla distribuzione](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori ATP di Microsoft Defender possono utilizzare il [controllo di accesso basato sui ruoli (RBAC)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) per creare ruoli e gruppi all'interno del team delle operazioni di sicurezza per concedere l'accesso appropriato al centro sicurezza Microsoft Defender.

## <a name="information-protection"></a>Protezione delle informazioni

La protezione delle informazioni consente alle organizzazioni di individuare, classificare, etichettare e proteggere documenti e messaggi di posta elettronica sensibili. Gli amministratori possono definire regole e condizioni per applicare automaticamente le etichette, gli utenti possono applicare le etichette manualmente oppure è possibile utilizzare una combinazione di due, in cui gli utenti vengono forniti suggerimenti per l'applicazione delle etichette.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti usufruiscono della possibilità di applicare manualmente le etichette di riservatezza al contenuto o di classificare automaticamente il contenuto.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/a3/F3, AIP Plan 1 e AIP Plan 2 forniscono i diritti per un utente di trarre vantaggio dall'etichetta di riservatezza manuale.

Microsoft 365 E5/A5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 e AIP Plan 2 forniscono i diritti per un utente di trarre vantaggio dall'applicazione e visualizzazione di etichette di riservatezza in Power BI e proteggere i dati quando viene esportato da Power BI a Excel, PowerPoint o PDF. 

> [!NOTE]
> Power BI è incluso in Microsoft 365 E5/A5/G5; in tutti gli altri piani, Power BI deve essere concesso in licenza separatamente.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 e AIP Plan 2 forniscono i diritti per un utente di trarre vantaggio dall'etichettatura di sensitivity automatico.

Per i diritti specifici per licenza, vedere il confronto dettagliato Microsoft 365 Compliance Licensing. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Non include i diritti sulla classificazione automatica basata sull'apprendimento automatico (classificatori addestrabili).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di protezione delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri per gli utenti con licenza, vedere attivazione di Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Eccetto quando si utilizza la funzionalità di scanner AIP, è possibile applicare i criteri a specifici gruppi o utenti e i registri possono essere modificati per impedire agli utenti senza licenza di eseguire le funzionalità di classificazione o etichettatura. Per istruzioni su come ambito delle distribuzioni AIP, vedere [Configuring the Azure Information Protection Policy](https://docs.microsoft.com/azure/information-protection/configure-policy).

Per la funzionalità di scanner AIP, Microsoft non si impegna a fornire la classificazione dei file, le etichette o le funzionalità di protezione per gli utenti che non dispongono di una licenza.

## <a name="information-governance"></a>Governance delle informazioni

La governance delle informazioni consente alle organizzazioni di gestire i propri rischi attraverso la scoperta, classificazione, etichettatura e governance dei dati. La governance delle informazioni consente alle organizzazioni di soddisfare i requisiti aziendali e normativi e di ridurre la superficie di attacco fornendo funzionalità di conservazione ed eliminazione nei dati di Microsoft 365 e di terze parti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti possono trarre vantaggio dalla possibilità di classificare i dati a scopo di conservazione per mantenere criteri e normative specifiche.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 F3/Business Premium, Office 365 E1/a1/F3 e i piani di Exchange autonomo offrono i diritti per un utente di trarre vantaggio dall'applicazione manuale di etichette di conservazione non registrate ai dati delle cassette postali.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/a1/F3 e i piani di SharePoint autonomo offrono i diritti per un utente di trarre vantaggio dall'applicazione manuale di etichette di conservazione non registrate ai file in SharePoint o OneDrive. 

Microsoft 365 E5/A5/E3/a3/Business Premium, Office 365 E5/A5/E3/a3, Exchange piano 2 ed Exchange Online Archiving forniscono i diritti per un utente di trarre vantaggio da un criterio di conservazione delle cassette postali di base a livello di organizzazione o a livello di posizione e/o per applicare manualmente un'etichetta di conservazione non record ai dati delle cassette postali.

Microsoft 365 E5/A5/E3/a3, Office 365 E5/A5/E3/a3 e SharePoint piano 2 forniscono i diritti per un utente di trarre vantaggio da un criterio di conservazione di base di SharePoint o OneDrive e/o di applicare manualmente un'etichetta di conservazione non record ai file in SharePoint o OneDrive.

Microsoft 365 E5/A5/E3/a3 e Office 365 E5/A5/E3/a3 forniscono i diritti per un utente di trarre vantaggio da un criterio di conservazione dei team.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dall'applicazione automatica di etichette o criteri di conservazione, applicazione di etichette o criteri di conservazione predefiniti, avvio del periodo di conservazione di un'etichetta di conservazione basata su un evento personalizzato, attivazione di una revisione di disposizione manuale alla fine del periodo di conservazione dell'etichetta, importazione di dati di terze parti mediante connettori di dati nativi, dichiarazione di un record, individuazione del contenuto contrassegnato e monitoraggio dell'attività di etichettatura.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance forniscono i diritti per un utente di trarre vantaggio dall'applicazione automatica delle etichette di conservazione in base ai classificatori addestrabili.

Per i diritti specifici per licenza, vedere il confronto dettagliato Microsoft 365 Compliance Licensing. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di governance delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione della governance delle informazioni per applicare i criteri e le etichette AutoLabel per gli utenti con licenza, vedere [Manage information governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Le funzionalità di governance delle informazioni possono essere applicate agli utenti con licenza in determinate posizioni (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione della governance delle informazioni per applicare i criteri e le etichette AutoLabel per gli utenti con licenza, vedere [Manage information governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gestione record

La gestione dei record consente alle organizzazioni di rispettare i propri obblighi di registrazione per le aziende e le normative tramite la scoperta, classificazione, etichettatura, conservazione e eliminazione difendibile tra i dati di Microsoft 365 e di terze parti.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5, Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dalla gestione dei record, tra cui la dichiarazione di elementi come record, l'applicazione automatica della conservazione o la registrazione delle etichette e l'esecuzione di processi di revisione della disposizione (escludendo l'applicazione

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance forniscono i diritti per un utente di trarre vantaggio dall'applicazione automatica di etichette di conservazione o di record in base ai classificatori addestrabili.

Per i diritti specifici per licenza, vedere il confronto dettagliato Microsoft 365 Compliance Licensing. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti possono trarre vantaggio dalla possibilità di dichiarare il contenuto come record e gestire il processo dei record completi dalla definizione e dalla dichiarazione dei criteri tramite lo smaltimento difendibile.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di gestione dei record sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione della gestione dei record da applicare per gli utenti con licenza, vedere [Records Management in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Le funzionalità di gestione dei record possono essere applicate agli utenti con licenza in determinate posizioni (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione della gestione dei record da applicare per gli utenti con licenza, vedere [Records Management in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Connettori dati 

Microsoft fornisce connettori di dati di terze parti che possono essere configurati nel centro conformità di Microsoft 365. Per un elenco dei connettori di dati forniti da Microsoft, vedere la tabella [dei connettori di dati di terze parti](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data) . In questa tabella vengono riepilogate anche le soluzioni di conformità che è possibile applicare ai dati di terze parti dopo l'importazione e l'archiviazione dei dati in Microsoft 365 e i collegamenti alle istruzioni dettagliate per ogni connettore.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Il vantaggio principale dell'utilizzo dei connettori di dati per l'importazione e l'archiviazione dei dati di terze parti in Microsoft 365 è che è possibile applicare diverse soluzioni di conformità a Microsoft 365 dopo che è stato importato. In questo modo, i dati non Microsoft dell'organizzazione sono conformi alle normative e agli standard che influiscono sull'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Le licenze seguenti forniscono i diritti per un utente di usufruire dei connettori di dati:

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 info Protection & governance
- Conformità Microsoft 365 E5/A5
- Microsoft 365 E5/A5 gestione dei rischi Insider 
- Microsoft 365 E5/A5 eDiscovery e audit 
- Office 365 E5/A5
- Office 365 Advanced Compliance

Per i connettori dati nel centro sicurezza & conformità di M365 forniti da uno dei partner di Microsoft, è necessario che l'organizzazione abbia una relazione commerciale con il partner prima di poter distribuire tali connettori.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

I connettori sono configurati utilizzando il Centro sicurezza & conformità e il catalogo connettore.

### <a name="how-can-the-service-be-applied-only---to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

I servizi dei connettori dati sono un valore tenant Level. Tutti gli utenti destinati a usufruire di questo servizio devono essere concessi in licenza.

## <a name="microsoft-graph-apis-for-teams-dlp"></a>API di Microsoft Graph per Team DLP

All'inizio di quest'anno è stata [annunciata l'anteprima pubblica dell'API di notifica delle modifiche di Microsoft Graph per i messaggi in teams](https://developer.microsoft.com/en-us/graph/blogs/announcing-change-notifications-for-microsoft-teams-messages). Questa API consente agli sviluppatori di creare app in grado di ascoltare i messaggi di Microsoft teams in tempo quasi reale e di abilitare le implementazioni dello scenario DLP sia per i clienti che per gli ISV. Inoltre, Microsoft Graph patch API consente di applicare azioni DLP ai messaggi dei team.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Le funzionalità di [prevenzione della perdita di dati (DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams?view=o365-worldwide) sono ampiamente utilizzate in Microsoft teams in particolare, in quanto le organizzazioni hanno spostato il lavoro a distanza. Se l'organizzazione ha DLP, è ora possibile definire criteri che impediscono agli utenti di condividere le informazioni riservate in un canale di Microsoft teams o in una sessione di chat.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

È necessaria una delle seguenti licenze E5 per disporre del supporto per la protezione di prevenzione della perdita di dati (DLP) in teams chat:

- Microsoft 365 E5/A5
- Conformità Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Information Protection and Governance
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

L'accesso API è configurato a livello di tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

L'API di Microsoft Graph per i team DLP è un valore a livello di tenant. Tutti gli utenti destinati a usufruire di questo servizio devono essere concessi in licenza.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fornisce soluzioni di ricerca e eDiscovery per i servizi IT e legali all'interno delle aziende per identificare, raccogliere, conservare, ridurre e esaminare i contenuti relativi a un'indagine o a una controversia preliminare all'esportazione dal sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Un utente beneficia di Advanced eDiscovery quando l'utente viene selezionato come custode dei dati (una persona che ha il controllo amministrativo di un documento o di un file elettronico) per un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5/G5/E3/a3/G3, Office 365 E5/A5/G5/E3/a3/G3 e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio da Core eDiscovery.
Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5 eDiscovery and audit, Office 365 E5/A5/G5 e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio da Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità avanzate di eDiscovery sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant quando gli amministratori assegnano le autorizzazioni di eDiscovery nel centro sicurezza & conformità.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

gli amministratori di eDiscovery possono selezionare utenti specifici come depositari dei dati per un caso utilizzando lo strumento di gestione del custode incorporato in Advanced eDiscovery, come descritto in [aggiungere i depositari a un caso avanzato di eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case).

## <a name="office-365-customer-key"></a>Chiave cliente per Office 365

Con il codice "Customer Key", è possibile controllare le chiavi di crittografia dell'organizzazione e configurare Office 365 per utilizzarle per crittografare i dati a riposo nei data center di Microsoft. In altre parole, la chiave del cliente consente di aggiungere un livello di crittografia che appartiene all'utente, utilizzando le proprie chiavi. Data at rest include i dati di Exchange Online e Skype for business archiviati nelle cassette postali e nei file in SharePoint Online e OneDrive for business.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dalla chiave del cliente, con i dati a riposo crittografati a livello di applicazione usando le chiavi di crittografia fornite, controllate e gestite dalla propria organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dalla chiave del cliente. Per ottenere il massimo vantaggio dalla chiave del cliente, è necessario disporre anche di una sottoscrizione per Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Le chiavi di crittografia per i clienti di Office 365 possono essere abilitate per tutti i dati archiviati in cassette postali di Exchange Online e Skype for business e per i file di SharePoint Online, OneDrive for business e teams. Per ulteriori informazioni sulla chiave del cliente di Office 365, inclusa la procedura per iniziare, vedere [Service Encryption with Customer Key in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Per assegnare le chiavi di crittografia ai dati all'interno di un'organizzazione di Office 365 e/o Microsoft 365 per gli utenti con licenza, seguire le istruzioni per la distribuzione delle chiavi di crittografia del cliente.

- Per i file di SharePoint Online, OneDrive for business e teams, i file in uno o più siti possono essere crittografati utilizzando la chiave del cliente.

- Per Exchange Online e Skype for business, le cassette postali possono essere crittografate utilizzando la chiave del cliente.

## <a name="office-365-customer-lockbox"></a>Customer Lockbox di Office 365

L'archivio protetto dei clienti fornisce un ulteriore livello di controllo offrendo ai clienti la possibilità di concedere autorizzazioni di accesso esplicito per le operazioni del servizio. Dimostrando che le procedure sono disponibili per l'autorizzazione di accesso ai dati esplicita, l'archivio protetto dei clienti può anche aiutare le organizzazioni a soddisfare determinati obblighi di conformità, come HIPAA e FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dall'archivio protetto dei clienti assicurando che nessuno può accedere al proprio contenuto per eseguire un'operazione di servizio senza l'approvazione esplicita del cliente. L'archivio protetto dei clienti porta il cliente nel flusso di lavoro di approvazione per le richieste di accesso al contenuto. In alcuni casi, gli ingegneri Microsoft sono coinvolti durante il processo di supporto per risolvere i problemi segnalati dai clienti. Nella maggior parte dei casi, i problemi vengono risolti tramite una vasta gamma di telemetria e strumenti di debug per i servizi di Microsoft. Tuttavia, potrebbe essere necessario che un tecnico Microsoft acceda ai contenuti dei clienti per determinare la causa principale e risolvere il problema. L'archivio protetto dei clienti richiede all'ingegnere di richiedere l'accesso da parte del cliente come passaggio finale del flusso di lavoro di approvazione. Questo fornisce alle organizzazioni la possibilità di approvare o rifiutare queste richieste, in modo da consentire loro di controllare direttamente se un tecnico Microsoft può accedere ai dati degli utenti finali dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Insider Risk Management e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dall'archivio protetto dei clienti.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori possono abilitare i controlli archivio clienti all'interno dell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere [archivio protetto dei clienti in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests). Quando l'archivio protetto dei clienti è attivato, è necessario che Microsoft ottenga l'approvazione di un'organizzazione prima di accedere a qualsiasi contenuto.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Il servizio Archivio clienti non può essere limitato attualmente a utenti specifici. È necessario concedere una licenza per ogni utente che si intende trarre vantaggio.

## <a name="privileged-access-management-in-office-365"></a>Gestione degli accessi privilegiati in Office 365

[Gestione accessi con privilegi (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) fornisce il controllo di accesso granulare sulle attività di amministratore privilegiate in Office 365. Dopo aver abilitato PAM, gli utenti dovranno richiedere l'accesso just-in-time tramite un flusso di lavoro di approvazione estremamente ambito e con un limite di tempo per completare le attività elevate e con privilegi.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

L'abilitazione di PAM consente alle organizzazioni di operare con zero privilegi permanenti. Gli utenti traggono vantaggio dal livello aggiunto di difesa dalle vulnerabilità derivanti dall'accesso amministrativo permanente che fornisce accesso illimitato ai propri dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 compliance e Microsoft 365 E5/A5 Information Protection and Governance forniscono i diritti per un utente di trarre vantaggio da PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità PAM sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri PAM, vedere [Introduzione alla gestione degli accessi con privilegi](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

I clienti possono gestire PAM per ogni singolo utente tramite il gruppo di approvatori e i criteri di accesso, che possono essere applicati agli utenti con licenza. Per ulteriori informazioni, vedere [gestione degli accessi con privilegi in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Crittografia a chiave doppia per Microsoft 365 

La crittografia a doppio tasto per Microsoft 365 consente di proteggere i dati altamente riservati per soddisfare i requisiti specializzati e mantenere il controllo completo della chiave di crittografia. La crittografia a chiave doppia utilizza due tasti per proteggere i dati, con una chiave nel controllo e la seconda chiave archiviati in modo sicuro Microsoft Azure. Per visualizzare i dati, è necessario avere accesso a entrambe le chiavi. Poiché Microsoft può accedere a un solo tasto, la chiave e anche i dati non sono disponibili per Microsoft, garantendo di avere il controllo completo sulla privacy e la sicurezza dei dati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dalla crittografia a chiave doppia tramite la possibilità di migrare i dati crittografati nel cloud e impedire l'accesso di terze parti purché la chiave resti in controllo degli utenti. Gli utenti finali possono proteggere e utilizzare il doppio contenuto crittografato con la chiave simile a qualsiasi altro contenuto protetto da un'etichetta di riservatezza.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dalla crittografia a chiave doppia.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

La crittografia a chiave doppia supporta la versione desktop di Microsoft Office per Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Per assegnare le chiavi di crittografia ai dati all'interno di un'organizzazione di Office 365 e/o Microsoft 365 per gli utenti con licenza, seguire le istruzioni per la distribuzione di crittografia a chiave doppia.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenzione della perdita dei dati di Office 365 per Exchange Online, SharePoint Online e OneDrive for business

Con Office 365 per la prevenzione della perdita di dati (DLP) per Exchange Online, SharePoint Online e OneDrive for business, le organizzazioni possono identificare, monitorare e proteggere automaticamente le informazioni riservate tra i messaggi di posta elettronica e i file (inclusi i file archiviati nei repository di file di Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio da DLP per Exchange Online, SharePoint Online e OneDrive for business quando i messaggi di posta elettronica e i file vengono controllati per ottenere informazioni riservate, come configurato nei criteri DLP dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 a1/E3/a3/business, Office 365 E3/a3 e la prevenzione della perdita di dati di Office 365 forniscono i diritti per un utente di usufruire di Office 365 DLP per Exchange Online, SharePoint Online e OneDrive for business.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, i messaggi di posta elettronica di Exchange Online, i siti di SharePoint e gli account di OneDrive sono *posizioni abilitate (carichi di lavoro)* per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of Data Loss Prevention](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel centro sicurezza & conformità, in posizioni di **prevenzione della perdita di dati**  >  **Locations**.

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenzione della perdita dei dati di comunicazione per i team

Con la comunicazione DLP per i team, le organizzazioni possono bloccare le chat e i messaggi di canale che contengono informazioni riservate, ad esempio informazioni finanziarie, informazioni di identificazione personale, informazioni relative all'integrità o altre informazioni riservate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 Information Protection and Governance e Office 365 Advanced compliance possono trarre vantaggio dalla comunicazione DLP per i team.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

I mittenti possono usufruire delle informazioni riservate nella chat in uscita e nei messaggi del canale ispezionati per ottenere informazioni riservate, come configurato nel criterio DLP dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, i messaggi chat e il canale dei team sono un *percorso abilitato (carico di lavoro)* per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of Data Loss Prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel centro sicurezza & conformità, in posizioni di **prevenzione della perdita di dati**  >  **Locations**.

## <a name="information-barriers"></a>Barriere informative

Le barriere informative sono criteri che un amministratore può configurare per impedire agli utenti o ai gruppi di comunicare tra loro. Ciò è utile se, ad esempio, un reparto gestisce informazioni che non devono essere condivise con altri reparti oppure che è necessario impedire a un gruppo di comunicare con i contatti esterni. I criteri barriera di informazioni impediscono anche le ricerche e l'individuazione. Questo significa che se si tenta di comunicare con un utente che non deve essere comunicante, non sarà possibile trovare tale utenti nello strumento di selezione utenti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dalle funzionalità di conformità avanzate delle barriere informative quando sono limitate dalla comunicazione con gli altri. Ad esempio:<br><br>

| Scenario | Chi ha bisogno di una licenza? |
|:------|:------|:------|
| Due gruppi (gruppo &nbsp; 1 e gruppo &nbsp; 2) non sono in grado di comunicare tra loro, ovvero &nbsp; gli utenti del gruppo 1 sono limitati dalla comunicazione con &nbsp; gli utenti del gruppo 2 e &nbsp; gli utenti del gruppo 2 sono limitati dalla comunicazione con &nbsp; gli utenti del gruppo 1. | Utenti sia del gruppo &nbsp; 1 che del gruppo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Insider Risk Management, Office 365 E5/A5 e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dalle barriere informative.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di barriera delle informazioni utilizzando i cmdlet di PowerShell nel centro sicurezza & conformità. Gli amministratori devono essere assegnati all'amministratore globale di Microsoft 365 Enterprise, all'amministratore globale di Office 365 o al ruolo di amministratore di conformità per creare un criterio barriera informativo. Per impostazione predefinita, questi criteri si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulle barriere informative, vedere [barriere informative in Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel centro sicurezza & Compliance. Ad esempio, se tutti gli utenti sono concessi in licenza per Office 365 E3 e nessuno viene concesso in licenza per Office 365 Advanced Compliance/E5, non è necessario creare criteri di barriera delle informazioni per l'organizzazione. Per ulteriori informazioni, vedere [barriere informative in Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Crittografia messaggi di Office 365 (OME) è un servizio basato su Azure Rights Management (Azure RMS) che consente di inviare posta elettronica crittografata a destinatari interni o esterni all'organizzazione, indipendentemente dall'indirizzo di posta elettronica di destinazione (Gmail, Yahoo! Mail, Outlook.com e così via).

Per visualizzare messaggi crittografati, i destinatari possono ottenere un passcode monouso, accedere con un account Microsoft oppure accedere con un account aziendale o dell'istituto di istruzione associato a Office 365. I destinatari possono anche inviare risposte crittografate. Non è necessario un abbonamento per visualizzare i messaggi crittografati o inviare risposte crittografate.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

I mittenti dei messaggi usufruiscono del controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia dei messaggi di Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E3/a3, Office 365 E3/a3 e Azure Information Protection Plan 1 offrono i diritti per un utente di trarre vantaggio dalla crittografia dei messaggi di Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia dei messaggi di Office 365 nell'interfaccia di amministrazione di Exchange in regole del **flusso di posta**  >  **Rules**. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione delle nuove funzionalità di crittografia dei messaggi di Office 365, vedere [configurare le nuove funzionalità di crittografia dei messaggi di office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per la crittografia dei messaggi di Office 365 solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [definire le regole del flusso di posta per crittografare i messaggi di posta elettronica in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

La crittografia avanzata dei messaggi di Office 365 consente ai clienti di soddisfare i requisiti di conformità che richiedono controlli più flessibili su destinatari esterni e l'accesso ai messaggi di posta elettronica crittografati. Con la crittografia avanzata dei messaggi, gli amministratori possono controllare i messaggi di posta elettronica sensibili condivisi all'esterno dell'organizzazione tramite criteri automatici in grado di rilevare i tipi di informazioni riservate (ad esempio, identificare personalmente le informazioni o gli ID finanziari o di integrità) oppure utilizzare parole chiave per migliorare la protezione applicando modelli di e-mail personalizzati e terminando l'accesso a messaggi di posta crittografati tramite un portale Web Gli amministratori possono inoltre controllare ulteriori messaggi di posta elettronica crittografati accessibili esternamente tramite un portale web sicuro, revocando l'accesso in qualsiasi momento.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

I mittenti dei messaggi usufruiscono del controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia avanzata dei messaggi.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance e Office 365 Advanced Compliance offrono i diritti per un utente di trarre vantaggio dalla crittografia avanzata dei messaggi.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia dei messaggi avanzati nell'interfaccia di amministrazione di Exchange in regole del flusso di posta. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione delle nuove funzionalità di crittografia dei messaggi, vedere [configurare le nuove funzionalità di crittografia messaggi di Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori devono applicare le regole del flusso di posta per la crittografia dei messaggi avanzata solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [definire le regole del flusso di posta per crittografare i messaggi di posta elettronica in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformità delle comunicazioni

La conformità alla comunicazione in Microsoft 365 consente di ridurre al minimo i rischi di comunicazione contribuendo a rilevare, acquisire e intraprendere azioni correttive per i messaggi inopportuni nell'organizzazione. È possibile definire criteri specifici che consentono di acquisire messaggi di posta elettronica interni ed esterni, Microsoft teams o comunicazioni di terze parti nell'organizzazione. I revisori possono eseguire azioni correttive appropriate per assicurarsi che siano conformi agli standard dei messaggi dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli specialisti di conformità usufruiscono del servizio tramite le comunicazioni dell'organizzazione monitorate dai criteri di conformità della comunicazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 compliance e Microsoft 365 Insider Risk Management offrono i diritti per un utente di trarre vantaggio dalla conformità alla comunicazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Gli amministratori e gli specialisti della conformità creano criteri di conformità della comunicazione nel centro conformità di Microsoft 365. Questi criteri definiscono le comunicazioni e gli utenti soggetti a revisione nell'organizzazione, definiscono le condizioni personalizzate che devono soddisfare le comunicazioni e specificano chi deve eseguire le revisioni.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Gli amministratori scelgono utenti o gruppi specifici da includere in un criterio di conformità della comunicazione. Quando si sceglie un gruppo, è possibile selezionare anche utenti specifici del gruppo da escludere dal criterio di conformità della comunicazione. Per ulteriori informazioni sui criteri di conformità della comunicazione, vedere [Communication compliance in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gestione dei rischi Insider

La gestione dei rischi Insider è una soluzione in Microsoft 365 che consente di ridurre al minimo i rischi interni, consentendo di rilevare, indagare ed eseguire azioni sulle attività a rischio nell'organizzazione.
I criteri personalizzati consentono di rilevare e intervenire su attività dannose e involontariamente rischiose nell'organizzazione, inclusi i casi di escalation a Microsoft Advanced eDiscovery, se necessario. Gli analisti di rischio nell'organizzazione possono rapidamente prendere le azioni appropriate per garantire che gli utenti siano conformi agli standard di conformità dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli utenti traggono vantaggio dalle attività monitorate a rischio.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze offrono i diritti per un utente di usufruire del servizio?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 compliance e Microsoft 365 Insider Risk Management offrono i diritti per un utente di trarre vantaggio dalla gestione dei rischi Insider.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

I criteri di gestione dei rischi Insider devono essere creati nel centro conformità di Microsoft 365 e assegnati agli utenti.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Quando si crea un criterio nel centro conformità di Microsoft 365, nella pagina Selezione **utenti e gruppi** selezionare Seleziona **utenti o gruppi** per selezionare solo gli utenti con licenza oppure, se tutti gli utenti sono concessi in licenza, è possibile selezionare la casella di controllo **tutti gli utenti e i gruppi abilitati alla posta elettronica** . Per ulteriori informazioni, vedere [Introduzione alla gestione dei rischi Insider](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Criteri di accesso condizionale

L'accesso condizionale è lo strumento utilizzato da Azure Active Directory per riunire i segnali, per prendere decisioni e applicare i criteri dell'organizzazione. L'accesso condizionale è il fulcro del piano di controllo Identity Driven. I criteri di accesso condizionale con le istruzioni più semplici sono if-then. Se un utente desidera accedere a una risorsa, è necessario completare un'azione. Esempio: un responsabile della gestione delle retribuzioni desidera accedere all'applicazione Payroll ed è necessario per eseguire l'autenticazione a più fattori per accedervi.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Enterprise Mobility + Security E3/a3, Microsoft 365 F3/E3/a3/Business Premium e Azure Active Directory Premium Plan 1 possono usufruire dei criteri di accesso condizionale. Gli utenti con licenza di Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security e Azure Active Directory Premium piano 2 possono trarre vantaggio dalla protezione delle identità (criteri di accesso condizionale basato sul rischio).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Gli analisti delle operazioni di sicurezza e i professionisti della sicurezza sono avvantaggiati dalla possibilità di applicare i criteri organizzativi per gli utenti, richiedendo loro di soddisfare determinati criteri prima di concedere l'accesso al contenuto aziendale. Gli utenti finali usufruiscono della possibilità di accedere al proprio lavoro ovunque e in qualsiasi momento, proteggendo gli asset dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, le funzionalità di accesso condizionale sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

Per la protezione delle identità e l'accesso condizionale in particolare, un utente deve essere incluso in un gruppo o essere aggiunto a un criterio di accesso condizionale. La condizione degli utenti e dei gruppi è obbligatoria in un criterio di accesso condizionale. Nei criteri è possibile selezionare **tutti gli utenti** o gli utenti e i gruppi specifici. È necessario selezionare solo gli utenti e i gruppi con licenza appropriata. Per ulteriori informazioni, vedere [quali sono le condizioni nell'accesso condizionale di Azure Active Directory?](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Audit avanzato

Advanced audit in Microsoft 365 fornisce una conservazione annuale dei registri di controllo per le attività di utenti e amministratori e fornisce la possibilità di creare criteri di conservazione del registro di controllo personalizzati per gestire la conservazione del registro di controllo per altri servizi di Microsoft 365. Consente inoltre di accedere a eventi cruciali per le indagini e l'accesso a larghezza di banda elevata all'API di attività di gestione di Office 365. Per ulteriori informazioni, vedere [Advanced audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

È inoltre possibile abilitare un periodo di conservazione di 10 anni con un SKU del componente aggiuntivo. L'SKU del componente aggiuntivo sarà necessario a partire dall'inizio del 2021.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti usufruiscono del servizio?

Gli utenti con licenza di Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 compliance e Microsoft 365 eDiscovery and audit possono trarre vantaggio da Advanced audit.

Gli utenti con licenza con controllo avanzato e il componente aggiuntivo per la conservazione dei log di controllo di 10 anni possono trarre vantaggio da una conservazione dei log di controllo di 10 anni.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti usufruiscono del servizio?

Un utente beneficia del controllo avanzato perché i record di controllo relativi all'attività degli utenti nei servizi Microsoft 365 possono essere conservati per un massimo di un anno. Inoltre, gli eventi di controllo di alto valore vengono registrati, ad esempio quando si accede o si leggono gli elementi della cassetta postale di un utente. Per ulteriori informazioni, vedere [Advanced audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning e la distribuzione del servizio?

Per impostazione predefinita, il controllo avanzato è abilitato a livello di tenant per tutte le organizzazioni che dispongono di un abbonamento a Office 365 o Microsoft 365 E5 e fornisce automaticamente una conservazione annuale dei registri di controllo per le attività (eseguite dagli utenti con la licenza appropriata) in Azure Active Directory, Exchange e SharePoint. Inoltre, le organizzazioni possono utilizzare i criteri di conservazione dei registri di controllo per gestire il periodo di conservazione dei record di controllo generati dall'attività in altri servizi Microsoft 365. La funzionalità di conservazione dei log di controllo di 10 anni è abilitata anche utilizzando gli stessi criteri di conservazione. Per altre informazioni, vedere [Gestire i criteri di conservazione dei log di controllo](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>In che modo il servizio può essere applicato solo agli utenti del tenant che dispongono della licenza per il servizio?

La conservazione di un anno dei registri di controllo e il controllo degli eventi cruciali si applicano solo agli utenti con la licenza appropriata. Gli amministratori possono inoltre utilizzare i criteri di conservazione dei registri di controllo per specificare una durata di conservazione più breve per i log di controllo di utenti specifici.

la conservazione di 10 anni dei registri di controllo si applica solo agli utenti che dispongono della licenza del componente aggiuntivo appropriata. L'SKU del componente aggiuntivo sarà necessario a partire dall'inizio del 2021.
