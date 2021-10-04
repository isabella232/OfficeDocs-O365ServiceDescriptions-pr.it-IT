---
title: Microsoft 365 guida per la sicurezza & conformità
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: In questo articolo vengono fornite indicazioni per Microsoft 365 per evitare potenziali interruzioni del servizio a causa dell'accesso senza licenza.
ms.openlocfilehash: 7da0766c19169e54c7377bfd7f97d34407a03658
ms.sourcegitcommit: b47c4912a47ce47bb3c20e696cc3700b14464c7b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/04/2021
ms.locfileid: "60088499"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>Microsoft 365 guida per la conformità della &amp; sicurezza

Ai fini di questo articolo, un servizio a livello di tenant è un servizio online che, se acquistato per qualsiasi utente nel tenant (autonomo o come parte dei piani Office 365 o Microsoft 365) viene attivato in parte o per intero per tutti gli utenti nel &mdash; &mdash; tenant. Anche se alcuni utenti senza licenza possono tecnicamente essere in grado di accedere al servizio, è necessaria una licenza per qualsiasi utente che si intende trarre vantaggio dal servizio.

> [!NOTE]
> Alcuni servizi tenant non sono attualmente in grado di limitare i vantaggi a utenti specifici. È necessario fare sforzi per limitare i vantaggi del servizio agli utenti con licenza. Ciò consente di evitare potenziali interruzioni del servizio per l'organizzazione una volta che le funzionalità di destinazione sono disponibili.

Per visualizzare le opzioni per consentire agli utenti di usufruire delle Microsoft 365 di conformità, scaricare la tabella Microsoft 365 [Comparison.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="advanced-audit"></a>Audit avanzato

Advanced Audit in Microsoft 365 consente la conservazione di un anno dei log di controllo per le attività di utenti e amministratori e offre la possibilità di creare criteri di conservazione dei log di controllo personalizzati per gestire la conservazione dei log di controllo per altri servizi Microsoft 365. Fornisce inoltre l'accesso agli eventi cruciali per le indagini e all'accesso a larghezza di banda elevata all'API Office 365 Attività di gestione. Per ulteriori informazioni, vedere [Advanced Audit in Microsoft 365.](/microsoft-365/compliance/advanced-audit)

È inoltre possibile abilitare un periodo di conservazione di 10 anni con una SKU del componente aggiuntivo.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

Gli utenti con licenza di Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance e Microsoft 365 E5/A5/G5 eDiscovery and Audit possono trarre vantaggio da Advanced Audit.

Gli utenti con licenza con controllo avanzato e il componente aggiuntivo di conservazione del log di controllo per 10 anni possono trarre vantaggio dalla conservazione del log di controllo di 10 anni.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dal controllo avanzato perché i record di controllo correlati all'attività degli utenti nei Microsoft 365 possono essere conservati fino a un anno. Vengono inoltre registrati eventi di controllo di valore elevato, ad esempio quando si accede o si leggono elementi nella cassetta postale di un utente. Per ulteriori informazioni, vedere [Advanced Audit in Microsoft 365.](/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, Advanced Audit è abilitato a livello di tenant per tutti gli utenti che beneficiano del servizio e fornisce automaticamente la conservazione di un anno dei log di controllo per le attività (eseguite dagli utenti con la licenza appropriata) in Azure Active Directory, Exchange e SharePoint. Inoltre, le organizzazioni possono utilizzare i criteri di conservazione dei log di controllo per gestire il periodo di conservazione per i record di controllo generati dall'attività in altri Microsoft 365 servizi. La funzionalità di conservazione del log di controllo per 10 anni viene abilitata anche utilizzando gli stessi criteri di conservazione. Per altre informazioni, vedere [Gestire i criteri di conservazione dei log di controllo](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

La conservazione di un anno dei log di controllo e il controllo degli eventi cruciali si applicano solo agli utenti con la licenza appropriata. Inoltre, gli amministratori possono utilizzare i criteri di conservazione dei log di controllo per specificare durate di conservazione più brevi per i log di controllo di utenti specifici.

La conservazione di 10 anni dei log di controllo si applica solo agli utenti con la licenza del componente aggiuntivo appropriata. La SKU del componente aggiuntivo sarà necessaria a partire dall'inizio del 2021.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection è una funzionalità del piano Azure Active Directory Premium P2 che consente di rilevare potenziali vulnerabilità che influiscono sulle identità dell'organizzazione, configurare risposte automatizzate alle azioni sospette rilevate correlate alle identità dell'organizzazione e analizzare gli incidenti sospetti e intraprendere azioni appropriate per risolverli.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOps traggono vantaggio dall'avere visualizzazioni consolidate degli utenti contrassegnati ed eventi di rischio basati su algoritmi di machine learning. Gli utenti finali traggono vantaggio dalla protezione automatica fornita tramite l'accesso condizionale basato sui rischi e dalla sicurezza migliorata fornita agendo sulle vulnerabilità.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

- Azure Active Directory Piano 1: Microsoft 365 E3/A3/G3/F1/F3, Enterprise Mobility & Security E3 e Microsoft 365 Business Premium
- Azure Active Directory Piano 2: Microsoft 365 E5/A5/G5, Enterprise Mobility & Security E5, Microsoft 365 E5/F5 Security and Microsoft 365 F5 Security & Compliance

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Azure AD Identity Protection sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni su Azure AD Identity Protection, vedere [Che cos'è Identity Protection?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono definire l'ambito di Azure AD Identity Protection assegnando criteri di rischio che definiscono il livello per le reimpostazioni delle password e consentendo l'accesso solo agli utenti con licenza. Per istruzioni su come eseguire l'ambito delle distribuzioni di Azure AD Identity Protection, vedere [Come configurare e abilitare i criteri di rischio.](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Governance dell'identità

Azure Active Directory La governance delle identità consente di bilanciare le esigenze di sicurezza e produttività dei dipendenti dell'organizzazione con i processi e la visibilità necessari. Usa la gestione dei diritti, le verifiche di accesso, la gestione delle identità con privilegi e i criteri di condizioni per l'uso per garantire che le persone giuste siano in grado di accedere alle risorse giuste.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Azure Active Directory Identity Governance aumenta la produttività degli utenti rendendo più semplice richiedere l'accesso ad app, gruppi e Microsoft Teams in un unico pacchetto di accesso. Gli utenti possono anche essere configurati come responsabili approvazione, senza coinvolgere gli amministratori. Per le revisioni di accesso, gli utenti possono esaminare le appartenenze ai gruppi con suggerimenti intelligenti per intervenire a intervalli regolari.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 Security and F5 Security & Compliance e Azure Active Directory Premium Plan 2 forniscono a un utente i diritti per trarre vantaggio dalla governance delle identità di Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Le funzionalità di governance dell'identità di Azure AD sono abilitate a livello di tenant, ma implementate per utente. Per informazioni sulla governance dell'identità di Azure AD, vedere [Che cos'è Azure AD Identity Governance?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono ambito governance dell'identità di Azure AD assegnando pacchetti di accesso, verifiche di accesso o gestione delle identità con privilegi solo per gli utenti con licenza. Per istruzioni su come eseguire l'ambito delle distribuzioni di Governance dell'identità di Azure AD, vedere:

- [Requisiti di licenza per la gestione dei diritti di Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisiti di licenza per la revisione dell'accesso di Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisiti di licenza per l'utilizzo Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="communication-compliance"></a>Conformità delle comunicazioni

La conformità delle comunicazioni in Microsoft 365 consente di ridurre al minimo i rischi di comunicazione consentendo di rilevare, acquisire ed eseguire azioni di correzione per i messaggi inappropriati nell'organizzazione. È possibile definire criteri specifici che acquisiscono messaggi di posta elettronica interni ed esterni, Microsoft Teams o comunicazioni di terze parti nell'organizzazione. I revisori possono intraprendere azioni correttive appropriate per assicurarsi che siano conformi agli standard dei messaggi dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli esperti di conformità traggono vantaggio dal servizio facendo in modo che le comunicazioni dell'organizzazione vengono monitorate dai criteri di conformità delle comunicazioni.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono a un utente i diritti per trarre vantaggio dalla conformità delle comunicazioni.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori e gli esperti di conformità creano criteri di conformità delle comunicazioni nella Centro conformità Microsoft 365. Questi criteri definiscono quali comunicazioni e utenti sono soggetti a revisione nell'organizzazione, definiscono le condizioni personalizzate che le comunicazioni devono soddisfare e specificano chi deve eseguire le revisioni.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori scelgono utenti o gruppi specifici da includere in un criterio di conformità delle comunicazioni. Quando si sceglie un gruppo, possono anche selezionare utenti specifici nel gruppo da escludere dai criteri di conformità delle comunicazioni. Per ulteriori informazioni sui criteri di conformità delle comunicazioni, vedere Introduzione alla conformità [delle comunicazioni in Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="compliance-manager"></a>Compliance Manager

[Microsoft Compliance Manager](https://compliance.microsoft.com/compliancemanager) è [](/microsoft-365/compliance/microsoft-365-compliance-center) una funzionalità del Centro conformità Microsoft 365 che consente di gestire i requisiti di conformità dell'organizzazione con maggiore facilità e comodità. Compliance Manager può aiutare l’utente durante tutto il percorso di conformità, dall'inventario dei rischi per la protezione dei dati alla gestione, delle complessità dell'implementazione dei controlli all'aggiornamento su normative e certificazioni e alla segnalazione ai revisori.

Compliance Manager consente di semplificare la conformità e ridurre i rischi fornendo:

- Valutazioni predefinite per standard e normative di settore e locali comuni oppure valutazioni personalizzate per soddisfare specifiche esigenze di conformità.
- Funzionalità del flusso di lavoro che consentono di completare in modo efficiente la valutazione dei rischi tramite uno singolo strumento.
- Istruzioni dettagliate sulle azioni di miglioramento suggerite per garantire la conformità agli standard e alle normative più rilevanti per l'organizzazione. Per le azioni gestite da Microsoft, vedrai i dettagli dell'implementazione e i risultati del controllo.
- Un punteggio di conformità basato sui rischi che consente di comprendere la propria posizione di conformità misurando i progressi nel completamento delle azioni di miglioramento.

### <a name="who-can-access-compliance-manager"></a>Who possibile accedere a Compliance Manager?

Compliance Manager è disponibile per le organizzazioni con licenze Office 365 e Microsoft 365 e per i clienti us Government Community Cloud (GCC), GCC High e Department of Defense (DoD). La disponibilità della valutazione e le funzionalità di gestione dipendono dal contratto di licenza.

### <a name="what-are-premium-assessments"></a>Che cosa sono le valutazioni premium?

Premium valutazioni sono un valore aggiuntivo per Compliance Manager e guida:

- Tradurre requisiti normativi complessi in controlli specifici
- Suggerisci azioni di miglioramento consigliate
- Fornire una misura quantificabile della conformità rispetto alle normative

Compliance Manager dispone di oltre 300 valutazioni premium che i clienti possono usare per valutare la conformità a un'ampia gamma di normative e standard globali, regionali e industriali.

Qualsiasi cliente con una sottoscrizione che include una licenza Microsoft Exchange Online può acquistare valutazioni premium di Compliance Manager.

### <a name="which-premium-assessments-are-available"></a>Quali valutazioni premium sono disponibili?

Ecco [l'elenco delle valutazioni premium.](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates)

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>Quali valutazioni sono incluse per impostazione predefinita (gratuitamente)?

Alcune valutazioni sono incluse come parte di Compliance Manager e il tipo di licenza del cliente. Per informazioni dettagliate, vedere la tabella seguente:

| Tipo licenza | Modelli di valutazione (inclusi per impostazione predefinita) |
|:-----|:-----|
|<ul><li>Microsoft 365 o Office 365 A1/E1/F1/G1</li><li>Microsoft 365 o Office 365 A3/E3/F3/G3</li></ul>|<ul><li>Protezione dei dati di base</li></ul>|
|<ul><li>Microsoft 365 o Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 Compliance</li><li>Microsoft 365 A5/E5/F5/G5 eDiscovery and Audit</li><li>Microsoft 365 A5/E5/F5/G5 Insider Risk Management</li><li>Microsoft 365 A5/E5/F5/G5 Information Protection and Governance</li></ul>|<ul><li>Protezione dei dati di base</li><li>GDPR Unione Europea</li><li>NIST 800-53</li><li>ISO 27001</li><li>CMMC Livello 1-5 (disponibile solo per G5)</li><li>Valutazioni personalizzate</li></ul>|

### <a name="what-are-custom-assessments"></a>Che cosa sono le valutazioni personalizzate?

Le valutazioni personalizzate sono una funzionalità di Compliance Manager che consente di creare un nuovo modello o personalizzare un modello di valutazione esistente, inclusa l'aggiunta o l'aggiornamento di controlli e azioni di miglioramento.

### <a name="who-can-access-custom-assessments"></a>Who possibile accedere alle valutazioni personalizzate?

La funzionalità di valutazione personalizzata è disponibile per i clienti con una sottoscrizione E5, come indicato di seguito:

- Microsoft 365 o Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 Compliance
- Microsoft 365 A5/E5/F5/G5 eDiscovery and Audit
- Microsoft 365 A5/E5/F5/G5 Insider Risk Management
- Microsoft 365 A5/E5/F5/G5 Information Protection and Governance

## <a name="customer-key-for-microsoft-365"></a>Codice Cliente per Microsoft 365

Con Customer Key puoi controllare le chiavi di crittografia dell'organizzazione e configurare le Microsoft 365 per usarle per crittografare i dati in pausa nei data center Microsoft. In altre parole, Customer Key consente di aggiungere un livello di crittografia che appartiene a te, usando le tue chiavi. Customer Key fornisce il supporto della [](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies) crittografia data-at-rest per più carichi di lavoro Microsoft 365 tramite Microsoft 365 di crittografia data-at-rest. Inoltre, Customer Key fornisce la crittografia per SharePoint online e OneDrive for Business e la Exchange Online a livello di cassetta postale.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio da Customer Key, grazie alla crittografia dei dati a livello di applicazione tramite chiavi di crittografia fornite, controllate e gestite dalla propria organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance e Office 365 E5/A5/G5 forniscono i diritti per un utente a beneficiare del Codice cliente. Per ottenere il vantaggio completo di Customer Key, devi anche avere una sottoscrizione per Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

[L'articolo Set up Customer Key](/microsoft-365/compliance/customer-key-set-up) descrive i passaggi da seguire per creare e configurare le risorse di Azure necessarie e quindi illustra i passaggi per la configurazione del codice "Customer Key".

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Microsoft 365 servizio data-at-rest che fornisce il supporto della crittografia a più carichi di lavoro è un servizio a livello di tenant. Anche se alcuni utenti senza licenza possono tecnicamente essere in grado di accedere al servizio, è necessaria una licenza per qualsiasi utente che si intende trarre vantaggio dal servizio. Per Exchange Online crittografia a livello di cassetta postale, la cassetta postale dell'utente deve essere concessa in licenza per assegnare un criterio di crittografia dei dati.

## <a name="data-connectors"></a>Connettori dati

Microsoft fornisce connettori dati di terze parti che possono essere configurati nella Centro conformità Microsoft 365. Per un elenco dei connettori dati forniti da Microsoft, vedere [la tabella Dei](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) connettori dati di terze parti. In questa tabella vengono inoltre riepilogate le soluzioni di conformità che è possibile applicare ai dati di terze parti dopo l'importazione e l'archiviazione dei dati in Microsoft 365 e i collegamenti alle istruzioni dettagliate per ogni connettore.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Il vantaggio principale dell'utilizzo dei connettori dati per importare e archiviare dati di terze parti in Microsoft 365 è che è possibile applicare diverse soluzioni di conformità Microsoft 365 ai dati dopo l'importazione. In questo modo si garantisce che i dati non Microsoft dell'organizzazione siano conformi alle normative e agli standard che influiscono sull'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Le licenze seguenti forniscono a un utente i diritti per trarre vantaggio dai connettori di dati:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5/F5 Compliance
- Microsoft 365 F5 Sicurezza & conformità
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 eDiscovery and Audit
- Office 365 E5/A5/G5

Per i connettori di dati nel Centro sicurezza e conformità di Microsoft 365 forniti da un partner Microsoft, l'organizzazione avrà bisogno di una relazione commerciale con il partner prima di poter distribuire &amp; tali connettori.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

I connettori vengono configurati utilizzando il Centro &amp; sicurezza e conformità e il Catalogo connettori.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

I servizi connettori dati sono un valore a livello di tenant. Tutti gli utenti che desiderano usufruire di questo servizio devono essere concessi in licenza.

## <a name="data-classification-analytics-overview-content-amp-activity-explorer"></a>Analisi della classificazione dei dati: Panoramica di Esplora &amp; attività contenuto

Le funzionalità analitiche per la classificazione dei dati sono disponibili Centro conformità Microsoft 365 esperienza. Panoramica mostra le posizioni del contenuto digitale e i tipi di informazioni riservate più comuni e le etichette presenti. Esplora contenuto offre visibilità sulla quantità e sui tipi di dati sensibili e consente agli utenti di filtrare in base all'etichetta o al tipo di riservatezza per ottenere una visualizzazione dettagliata delle posizioni in cui sono archiviati i dati sensibili. Esplora attività mostra le attività correlate ai dati sensibili e alle etichette, ad esempio il downgrade delle etichette o la condivisione esterna che potrebbe esporre il contenuto a rischi.

Esplora attività offre un singolo riquadro di vetro per consentire agli amministratori di ottenere visibilità sulle attività correlate alle informazioni riservate utilizzate dagli utenti finali. Questi dati includono le attività delle etichette, i registri di prevenzione della perdita dei dati (DLP), l'etichettatura automatica, endpoint DLP e altro ancora.

Esplora contenuto offre agli amministratori la possibilità di indicizzare i documenti sensibili archiviati all'interno dei carichi di lavoro Microsoft 365 e identificare le informazioni riservate che stanno archiviando. Esplora contenuto consente inoltre di identificare i documenti classificati con etichette di riservatezza ed archiviazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli amministratori della protezione delle informazioni e della conformità possono accedere al servizio per ottenere l'accesso a questi log e dati indicizzati per comprendere dove sono archiviati i dati sensibili e quali attività sono correlate a questi dati ed eseguite dagli utenti finali.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Gli utenti con licenza di Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection Governance e Office 365 E5 possono trarre vantaggio dall'analisi della classificazione dei dati di &amp; Microsoft 365.

Microsoft 365 E3/A3/G3 e Office 365 E3/A3/G3 consentono agli utenti di trarre vantaggio solo dall'aggregazione dei dati di Esplora contenuto.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità Di riepilogo contenuto ed Esplora attività sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dell'analisi della classificazione dei dati per gli utenti con licenza, vedere:

- **Esplora contenuto**: [Introduzione a Esplora contenuto - Microsoft 365 conformità | Documenti Microsoft](/microsoft-365/compliance/data-classification-content-explorer).
- **Esplora attività**: [Introduzione a Esplora attività - Microsoft 365 conformità | Documenti Microsoft](/microsoft-365/compliance/data-classification-activity-explorer).
- **Note sulla versione di classificazione dei dati**: Note sulla versione di classificazione dei dati - Microsoft 365 conformità [| Documenti Microsoft](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Questa funzionalità deve essere in ambito per gli utenti che usano attivamente la soluzione all'interno del Microsoft 365 di conformità.

## <a name="data-loss-prevention-for-teams"></a>Prevenzione della perdita dei dati per Teams

Con Communication DLP per Teams, le organizzazioni possono bloccare le chat e i messaggi di canale che contengono informazioni riservate, ad esempio informazioni finanziarie, informazioni di identificazione personale, informazioni correlate all'integrità o altre informazioni riservate.

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti traggono vantaggio dal fatto che le informazioni riservate nei messaggi di chat e canali in uscita vengono ispezionate alla ricerca di informazioni riservate, come configurato nel criterio DLP dell'organizzazione.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, Teams messaggi di chat e canali sono un percorso *abilitato (carico* di lavoro) per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of data loss prevention.](/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro sicurezza e conformità, in Posizioni di prevenzione &amp; della **perdita**  >  **di dati**.

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenzione della perdita dei dati Exchange Online, SharePoint Online e OneDrive for Business

Con Office 365 prevenzione della perdita dei dati (DLP) per Exchange Online, SharePoint Online e OneDrive for Business, le organizzazioni possono identificare, monitorare e proteggere automaticamente le informazioni riservate tra messaggi di posta elettronica e file (inclusi i file archiviati in archivi di file Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla prevenzione della perdita dei dati per Exchange Online, SharePoint Online e OneDrive for Business quando i messaggi di posta elettronica e i file vengono esaminati alla ricerca di informazioni riservate, come configurato nel criterio DLP dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 e Office 365 Data Loss Prevention e F5 Compliance e F5 Security & Compliance forniscono a un utente i diritti di usufruire di Office 365 DLP per Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, Exchange Online posta elettronica, siti SharePoint e account OneDrive sono posizioni *abilitate (carichi* di lavoro) per queste funzionalità DLP per tutti gli utenti all'interno del tenant. Per ulteriori informazioni sull'utilizzo dei criteri DLP, vedere [Overview of data loss prevention.](/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro sicurezza e conformità, in Posizioni di prevenzione &amp; della **perdita**  >  **di dati**.

## <a name="double-key-encryption-for-microsoft-365"></a>Crittografia a chiave doppia per Microsoft 365

Double Key Encryption for Microsoft 365 consente di proteggere i dati altamente sensibili per soddisfare requisiti specifici e mantenere il controllo completo della chiave di crittografia. Double Key Encryption usa due chiavi per proteggere i dati, con una chiave nel controllo e la seconda chiave archiviata in modo sicuro da Microsoft Azure. Per visualizzare i dati, è necessario disporre dell'accesso a entrambe le chiavi. Poiché Microsoft può accedere a una sola chiave, la chiave e anche i dati non sono disponibili per Microsoft, garantendo il controllo completo sulla privacy e sulla sicurezza dei dati.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla crittografia a chiave doppia grazie alla possibilità di eseguire la migrazione dei dati crittografati nel cloud, impedendo così l'accesso a terze parti finché la chiave rimane sotto il controllo degli utenti. Gli utenti possono proteggere e utilizzare il contenuto crittografato a chiave doppia in modo analogo a qualsiasi altro contenuto protetto da etichette di riservatezza.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance, Office 365 E5/A5/G5 ed EMS E5 forniscono i diritti per un utente di usufruire della crittografia a chiave doppia.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

La crittografia a chiave doppia supporta la versione desktop di Microsoft Office per Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Per assegnare chiavi di crittografia ai dati all'interno di Office 365 e/o Microsoft 365 per gli utenti con licenza, seguire le istruzioni per la distribuzione della crittografia a chiave doppia.

## <a name="ediscovery"></a>eDiscovery

eDiscovery fornisce soluzioni di indagine ed eDiscovery per i reparti IT e legali all'interno delle aziende per identificare, raccogliere, conservare, ridurre ed esaminare i contenuti relativi a un'indagine o a un contenzioso prima dell'esportazione dal sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Un utente trae vantaggio Advanced eDiscovery quando l'utente viene selezionato come responsabile dei dati (una persona che ha il controllo amministrativo di un documento o di un file elettronico) per un caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 e F5 Compliance e F5 Security & Compliance forniscono a un utente i diritti per trarre vantaggio da Core eDiscovery.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance, Microsoft 365 E5/A5/G5 eDiscovery and Audit e Office 365 E5/A5/G5 forniscono a un utente i diritti per usufruire di Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, Advanced eDiscovery funzionalità sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant quando gli amministratori assegnano le autorizzazioni di eDiscovery nel Centro &amp; sicurezza e conformità.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori di eDiscovery possono selezionare utenti specifici come responsabili dei dati per un caso utilizzando lo strumento di gestione dei responsabili incorporato in Advanced eDiscovery, come descritto in Aggiungere responsabili a un caso [Advanced eDiscovery](/microsoft-365/compliance/add-custodians-to-case).

## <a name="information-barriers"></a>Ostacoli alle informazioni

Le barriere alle informazioni sono criteri che un amministratore può configurare per impedire a singoli utenti o gruppi di comunicare tra loro. Ciò è utile se, ad esempio, un reparto gestisce informazioni che non devono essere condivise con altri reparti o se è necessario impedire a un gruppo di comunicare con contatti esterni. I criteri di barriera delle informazioni impediscono inoltre ricerche e individuazione. Ciò significa che se tenti di comunicare con qualcuno con cui non dovresti comunicare, non troverai tale utente nella selezione utenti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalle funzionalità avanzate di conformità delle barriere alle informazioni quando non possono comunicare con altri utenti. I criteri delle barriere alle informazioni possono essere definiti per impedire a determinati segmenti di utenti di comunicare con ognuno di essi o consentire a segmenti specifici di comunicare solo con determinati altri segmenti. Per ulteriori informazioni sulla definizione dei criteri di barriera delle informazioni, vedere [Define information barrier policies.](/microsoft-365/compliance/information-barriers-policies) Per gli scenari in cui due gruppi non possono comunicare tra loro, gli utenti di entrambi i gruppi richiedono una licenza per trarre vantaggio dal servizio (vedere l'esempio seguente).<br><br>

| Scenario | Who richiede una licenza? |
|:------|:------|
| Due gruppi (Gruppo 1 e Gruppo 2) non possono comunicare tra loro, ovvero agli utenti del Gruppo 1 è limitata la comunicazione con gli utenti del Gruppo 2 e agli utenti del Gruppo 2 è limitata la comunicazione con gli utenti del &nbsp; &nbsp; Gruppo &nbsp; &nbsp; &nbsp; &nbsp; 1. | Utenti nel gruppo &nbsp; 1 e nel &nbsp; gruppo 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management e Office 365 E5/A5/G5, forniscono a un utente i diritti per trarre vantaggio dalle barriere in fatto di informazioni.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di barriera delle informazioni utilizzando i cmdlet di PowerShell nel Centro &amp; sicurezza e conformità. Agli amministratori deve essere assegnato il Microsoft 365 Enterprise amministratore globale, Office 365 amministratore globale o amministratore di conformità per creare un criterio di protezione delle informazioni. Per impostazione predefinita, questi criteri si applicano a tutti gli utenti nel tenant. Per ulteriori informazioni sulle barriere alle informazioni, vedere [Ostacoli alle informazioni in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono personalizzare le posizioni (carichi di lavoro), gli utenti inclusi e gli utenti esclusi nel Centro &amp; sicurezza e conformità. Ad esempio, se tutti gli utenti sono concessi in licenza per Office 365 E3 e nessuno è concesso in licenza per Office 365 Advanced Compliance/E5, non sarà necessario creare criteri di barriera delle informazioni per l'organizzazione. Per altre informazioni, vedere [Barriere informative in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="information-protection"></a>Protezione dei dati

Information Protection consente alle organizzazioni di individuare, classificare, etichettare e proteggere documenti e messaggi di posta elettronica sensibili. Gli amministratori possono definire regole e condizioni per applicare automaticamente le etichette, gli utenti possono applicare le etichette manualmente oppure è possibile utilizzare una combinazione di queste due condizioni, in cui agli utenti vengono forniti consigli sull'applicazione delle etichette.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di applicare manualmente etichette di riservatezza al contenuto o di classificare automaticamente il contenuto.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, F5 Compliance e F5 Security & Compliance, Enterprise Mobility + Security E3/E5, M365 E5/A5/G5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 e AIP Plan 2 forniscono i diritti per un utente di trarre vantaggio dall'etichettatura di riservatezza manuale.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium and Enterprise Mobility + Security E3/E5, AIP Plan 1 e AIP Plan 2 and F5 Compliance e F5 Security & Compliance forniscono a un utente i diritti per trarre vantaggio dall'applicazione e dalla visualizzazione delle etichette di riservatezza in Power BI e per proteggere i dati quando sono esportato da Power BI a Excel, PowerPoint o PDF.

Microsoft 365 Business Premium e Enterprise Mobility forniscono i diritti per usare il modulo [AIPService](/powershell/azure/aip/overview#aipservice) PowerShell per amministrare il servizio Azure Rights Management protection per Azure Information Protection.

> [!NOTE]
> Power BI è incluso con Microsoft 365 E5/A5/G5; in tutti gli altri piani, Power BI licenza separatamente.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance and F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 e Il piano AIP 2 fornisce a un utente i diritti per trarre vantaggio dall'etichettatura automatica della riservatezza.

Information Protection non include i diritti per la classificazione automatica in base Machine Learning (classificatori addestrabili).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di protezione delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri per gli utenti con licenza, vedere Attivazione di Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Tranne quando si utilizza la funzionalità scanner AIP, i criteri possono essere applicati a gruppi o utenti specifici e i registri possono essere modificati per impedire agli utenti senza licenza di eseguire funzionalità di classificazione o di etichettatura.

Per la funzionalità scanner AIP, Microsoft non si impegna a fornire funzionalità di classificazione, etichettatura o protezione dei file agli utenti che non dispongono di licenza.

Per ulteriori informazioni, vedere [Create and publish sensitivity labels](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) e Understanding the Azure Information Protection [unified labeling scanner](/azure/information-protection/deploy-aip-scanner).

## <a name="information-governance"></a>Governance delle informazioni

La governance delle informazioni consente alle organizzazioni di gestire i propri rischi attraverso l'individuazione, la classificazione, l'etichettatura e la gestione dei dati. La governance delle informazioni consente alle organizzazioni di soddisfare i requisiti aziendali e normativi, nonché di ridurre la superficie di attacco fornendo funzionalità di conservazione ed eliminazione tra i dati di Microsoft 365 e di terze parti.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di classificare i dati ai fini della conservazione per rispettare criteri e normative specifici.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 F3/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 e i piani Exchange autonomi offrono a un utente i diritti per trarre vantaggio dall'applicazione manuale di etichette di conservazione non record ai dati delle cassette postali.

Microsoft 365 F3/F1/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 e i piani SharePoint autonomi offrono a un utente i diritti per trarre vantaggio dall'applicazione manuale di etichette di conservazione non record ai file in SharePoint o OneDrive.

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3/ A3, Exchange Piano 2 e Archiviazione Exchange Online forniscono a un utente i diritti per trarre vantaggio da un criterio di conservazione delle cassette postali di base a livello di organizzazione o di posizione.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 e SharePoint Piano 2 forniscono a un utente i diritti per trarre vantaggio da un criterio di conservazione SharePoint o OneDrive di base e/o per applicare manualmente un'etichetta di conservazione non record ai file in SharePoint o OneDrive.

Le organizzazioni possono utilizzare i criteri di conservazione per mantenere o eliminare Teams messaggi in base ai criteri. Ciò include la gestione dei messaggi Teams chat e conversazioni.

Le licenze seguenti forniscono a un utente i diritti di usufruire di un Teams di conservazione:

- Microsoft 365 E5/G5/A5/E3/G3/A3/F3/F1, Business Basic, Business Standard e Business Premium
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

Per gli utenti con le licenze seguenti, il periodo di conservazione o eliminazione minimo supportato è 30 giorni:

- Microsoft 365 F1/F3, Business Basic, Business Standard e Business Premium
- Office 365 E1/G1 e F3

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 e Office 365 E5/A5 forniscono a un utente i diritti per trarre vantaggio dall'applicazione automatica di etichette o criteri di conservazione, applicazione della conservazione predefinita etichette o criteri, iniziando il periodo di conservazione di un'etichetta di conservazione in base a un evento personalizzato, attivando una revisione manuale dell'eliminazione alla fine del periodo di conservazione dell'etichetta, importando dati di terze parti tramite connettori di dati nativi, dichiarando un file un record, individuando il contenuto etichettato e monitorando l'attività di etichettatura.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance forniscono a un utente i diritti per trarre vantaggio dall'applicazione automatica di etichette di conservazione basate su classificatori addestrabili.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di governance delle informazioni sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Information Governance per applicare l'etichettatura automatica e i criteri per gli utenti con licenza, vedere Governance delle informazioni [Microsoft in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Le funzionalità di governance delle informazioni possono essere applicate agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione di Information Governance per applicare l'etichettatura automatica e i criteri per gli utenti con licenza, vedere Governance delle informazioni [Microsoft in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="insider-risk-management"></a>Gestione dei rischi Insider

La gestione dei rischi insider è una soluzione in Microsoft 365 che consente di ridurre al minimo i rischi interni consentendo di rilevare, analizzare e intervenire sulle attività rischiose nell'organizzazione.

I criteri personalizzati consentono di rilevare ed eseguire azioni su attività dannose e inavvertitamente rischiose nell'organizzazione, tra cui l'escalation dei casi a Microsoft Advanced eDiscovery, se necessario. Gli analisti dei rischi nell'organizzazione possono intraprendere rapidamente azioni appropriate per assicurarsi che gli utenti siano conformi agli standard di conformità dell'organizzazione.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dal fatto che le attività vengono monitorate per i rischi.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono i diritti a un utente di beneficiare di Insider Risk Management.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

I criteri di gestione dei rischi Insider devono essere creati nel Centro conformità Microsoft 365 e assegnati agli utenti.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Quando si crea un criterio nel Centro conformità Microsoft 365, nella pagina  Scegli utenti e gruppi selezionare Scegli utenti o gruppi per selezionare solo  gli utenti con licenza oppure, se tutti gli utenti dispongono di una licenza, è possibile selezionare la casella di controllo Tutti gli utenti e i gruppi abilitati alla posta elettronica.  Per ulteriori informazioni, vedere [Introduzione alla gestione dei rischi insider.](/microsoft-365/compliance/insider-risk-management-configure)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender per identità

Microsoft Defender for Identity (in precedenza Azure Advanced Threat Protection) è un servizio cloud che consente di proteggere gli ambienti ibridi aziendali da più tipi di attacchi informatici mirati avanzati e minacce insider.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza secOp traggono vantaggio dalla capacità di Microsoft Defender for Identity di rilevare e analizzare minacce avanzate, identità compromesse e azioni insider dannose. Gli utenti finali traggono vantaggio dal monitoraggio dei dati da Parte di Microsoft Defender per l'identità.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Security, Microsoft F5 Security & Compliance e Microsoft Defender for Identity for Users forniscono i diritti per usufruire di Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender for Identity sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Azure ATP, vedere [Creare l'istanza di Microsoft Defender per l'identità.](/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Microsoft Defender for Identity services non è attualmente in grado di limitare le funzionalità a utenti specifici. È necessario ottenere una licenza per ogni utente che si intende trarre vantaggio.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender per Office 365

Microsoft Defender per Office 365 (in precedenza Office 365 Advanced Threat Protection) aiuta le organizzazioni a proteggere le organizzazioni da attacchi sofisticati come phishing e malware zero-day. Microsoft Defender per Office 365 fornisce anche informazioni utili correlando i segnali provenienti da un'ampia gamma di dati per identificare, definire le priorità e fornire consigli su come affrontare potenziali minacce.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Microsoft Defender per Office 365 protegge gli utenti da attacchi sofisticati come phishing e malware zero-day. Per l'elenco completo dei servizi forniti nel piano 1 e nel piano 2, vedere [Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio? 

Microsoft Defender per Office 365 Piani 1 e 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/G5/G5/F5 Security, Microsoft 365 F5 Security & Compliance e Microsoft 365 Business Premium forniscono i diritti per un utente a beneficiare di Microsoft Defender per Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender Office 365 sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Microsoft Defender per Office 365 per gli utenti con licenza, vedi [Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Per l'ambito di Microsoft Defender per Office 365, seguire i criteri di distribuzione Cassaforte collegamenti Cassaforte allegati:

- Per informazioni sulla configurazione dei collegamenti Cassaforte per gli utenti con licenza, vedere collegamenti Cassaforte [in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Per informazioni sulla configurazione degli allegati Cassaforte per gli utenti con licenza, vedere Cassaforte [allegati in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) è una soluzione CasB (Cloud Access Security Broker) che offre alle organizzazioni visibilità sulle proprie app e servizi cloud, fornisce analisi sofisticate per identificare e contrastare le minacce informatiche e consente loro di controllare il modo in cui i dati viaggiano in qualsiasi &mdash; app cloud.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

MCAS individua e valuta Shadow IT, fornisce protezione dalle minacce nelle app cloud di prima e di terze parti e protegge le informazioni nelle app cloud di prima e terza parte.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Enterprise Mobility + Security E5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Security, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Compliance e Microsoft 365 Information Protection and Governance forniscono i diritti per un utente a beneficiare di MCAS.

Azure AD P1 offre a un utente i diritti per trarre vantaggio dalle funzionalità di individuazione in MCAS.

Per usufruire delle funzionalità di controllo dell'app di accesso condizionale in MCAS, gli utenti devono disporre anche della licenza per Azure Active Directory P1, inclusa in Enterprise Mobility + Security F1/F3/E3/A3/G3, Enterprise Mobility + Security E5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5/F5 Security e Microsoft 365 Sicurezza & Conformità.

Per usufruire dell'etichettatura automatica sul lato client, gli utenti devono disporre della licenza per Azure Information Protection P2, incluso in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance, Microsoft 365 F5 Security & Conformità e Microsoft 365 e governance delle informazioni.

> [!NOTE]
> L'etichettatura automatica sul lato server richiede Information Protection Office 365 - Premium licenze ( `MIP_S_CLP2` o `efb0351d-3b08-4503-993d-383af8de41e3` ). Per informazioni di riferimento, vedere [Product names and service plan identifiers for licensing](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

Per ulteriori informazioni, vedere il Microsoft Cloud App Security [Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità MCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione dei criteri Microsoft Cloud App Security per gli utenti con licenza, vedere [Microsoft Cloud App Security panoramica.](/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono impostare l'ambito delle distribuzioni MCAS agli utenti con licenza utilizzando le funzionalità di distribuzione con ambito disponibili nel servizio. Per ulteriori informazioni, vedere [Distribuzione con ambito](/cloud-app-security/scoped-deployment).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender per endpoint

Microsoft Defender for Endpoint (in precedenza Microsoft Defender ATP) è una soluzione di sicurezza degli endpoint che include l'gestione delle vulnerabilità e la valutazione basati sui rischi; funzionalità di riduzione della superficie di attacco; protezione basata sul comportamento e basata sul cloud di nuova generazione; rilevamento e risposta degli endpoint (EDR); analisi e correzione automatiche; e servizi di ricerca gestiti. Per [altre informazioni, vedi la pagina Microsoft Defender for Endpoint.](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Quali utenti traggono vantaggio dal servizio?

Gli utenti con licenza di Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, che include Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5/F5 Security e Microsoft 365 F5 Security & Compliance possono trarre vantaggio da Microsoft Defender for Endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli analisti e i professionisti della sicurezza di SecOps traggono vantaggio dalle funzionalità di sicurezza degli endpoint di Microsoft Defender for Endpoint per eseguire la protezione preventiva, il rilevamento post-violazione, l'indagine automatizzata e la risposta alle minacce avanzate. Gli utenti finali traggono vantaggio da eventi dannosi monitorati da Microsoft Defender per Endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di Microsoft Defender for Endpoint sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla distribuzione, vedere [Fasi di distribuzione](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori di Microsoft Defender for Endpoint possono utilizzare il controllo degli accessi in base ai ruoli (RBAC) per creare ruoli e gruppi all'interno del team delle operazioni di sicurezza per concedere l'accesso appropriato al Microsoft Defender Security Center. Per ulteriori informazioni, vedere [Manage portal access using role-based access control](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>API microsoft Graph per Teams prevenzione della perdita dei dati (DLP) e per Teams esportazione

Queste API consentono agli sviluppatori di creare app di sicurezza e conformità che possono "ascoltare" i messaggi di Microsoft Teams in tempo quasi reale o esportare i messaggi dei team in 1:1/chat di gruppo o canali Teams. Queste API abilitano DLP e altri scenari di information protection e governance sia per i clienti che per gli ISV. Inoltre, Microsoft Graph Patch API consente di applicare azioni DLP ai Teams messaggi.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Le funzionalità di prevenzione della perdita dei dati [(DLP)](/microsoft-365/compliance/dlp-microsoft-teams) sono ampiamente utilizzate Microsoft Teams, in particolare quando le organizzazioni si sono spostate sul lavoro remoto. Se l'organizzazione dispone di DLP, è ora possibile definire criteri che impediscono agli utenti di condividere informazioni riservate in un canale Microsoft Teams o una sessione di chat.

Le funzionalità di protezione delle informazioni e governance sono ampiamente utilizzate Microsoft Teams, in particolare quando le organizzazioni si sono spostate sul lavoro remoto. Con [Teams'API](/microsoftteams/export-teams-content)di esportazione, i dati possono essere esportati in un'applicazione di eDiscovery o Archiviazione conformità di terze parti per garantire che le procedure di conformità siano soddisfatte.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

- Microsoft 365 (E5/A5)
- Conformità di Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Security
- Microsoft 365 E5/A5 Information Protection and Governance

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

L'accesso api è configurato a livello di tenant.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Le API di Microsoft Graph per Teams DLP e Teams l'esportazione forniscono un valore a livello di tenant. Tutti gli utenti che desiderano usufruire di questo servizio devono essere concessi in licenza. Come valore aggiunto, stiamo aggiungendo capacità seeded per utente con licenza, calcolata al mese e aggregata a livello di tenant. Per l'uso oltre la capacità di seeded, i proprietari delle app verranno fatturati per l'uso delle API.

Per ulteriori informazioni sui costi di capacità e consumo seeded, vedere Graph [requisiti per l'accesso ai messaggi di chat.](/graph/teams-licenses)

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Office 365 Advanced Message Encryption aiuta i clienti a rispettare gli obblighi di conformità che richiedono controlli più flessibili sui destinatari esterni e sul loro accesso ai messaggi di posta elettronica crittografati. Con crittografia avanzata dei messaggi, gli amministratori possono controllare i messaggi di posta elettronica sensibili condivisi all'esterno dell'organizzazione utilizzando criteri automatici in grado di rilevare tipi di informazioni riservate (ad esempio, informazioni di identificazione personale o ID finanziari o sanitari) oppure possono utilizzare parole chiave per migliorare la protezione applicando modelli di posta elettronica personalizzati e scadendo l'accesso ai messaggi di posta elettronica crittografati tramite un portale Web sicuro. Inoltre, gli amministratori possono controllare ulteriormente i messaggi di posta elettronica crittografati a cui si accede esternamente tramite un portale Web sicuro revocando l'accesso in qualsiasi momento.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti dei messaggi beneficiano del controllo aggiunto sui messaggi di posta elettronica sensibili forniti dalla crittografia avanzata dei messaggi.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance e Microsoft 365 E5/A5/G5 Information Protection and Governance forniscono a un utente i diritti per usufruire della crittografia avanzata dei messaggi.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori creano e gestiscono i criteri di crittografia avanzata dei messaggi nell'Exchange di amministrazione in **Regole del flusso di**  >  **posta**. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione di nuove funzionalità di crittografia dei messaggi, vedere [Set up new Office 365 Message Encryption capabilities](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori devono applicare regole del flusso di posta per la crittografia avanzata dei messaggi solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [Define mail flow rules to encrypt email messages in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) è un sottoinsieme di Microsoft Cloud App Security, con funzionalità limitate a Office 365 e senza ulteriore sicurezza per le app cloud di terze parti e i servizi IaaS.

OCAS offre alle organizzazioni visibilità sulle proprie app e servizi cloud di produttività, fornisce analisi sofisticate per identificare e contrastare le minacce informatiche e consente loro di controllare il modo in cui i dati viaggiano &mdash; Office 365.

Per confrontare le funzionalità, vedere [Differenze tra Microsoft Cloud App Security e Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

OCAS individua Shadow IT, fornisce protezione dalle minacce Office 365 e può controllare quali app dispongono dell'autorizzazione per accedere ai dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Office 365 E5/A3/A5/G5 forniscono i diritti per un utente a beneficiare di OCAS.
Per ulteriori informazioni, vedere il Microsoft Cloud App Security [Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità OCAS sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant.

Per informazioni sulla configurazione del servizio, vedere [Configurazione di base per Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori possono applicare l'ambito alle distribuzioni OCAS per applicare l'accesso a determinate app e limitare i gruppi di utenti monitorati da Office 365 Cloud App Security. Per ulteriori informazioni, vedere [Distribuzione con ambito](/cloud-app-security/scoped-deployment).

## <a name="office-365-customer-lockbox"></a>Customer Lockbox di Office 365

Customer Lockbox offre un ulteriore livello di controllo offrendo ai clienti la possibilità di concedere autorizzazioni di accesso esplicite per le operazioni di servizio. Dimostrando che sono in atto procedure per l'autorizzazione esplicita di accesso ai dati, Customer Lockbox può anche aiutare le organizzazioni a rispettare determinati obblighi di conformità come HIPAA e FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Customer Lockbox garantisce che nessuno di Microsoft possa accedere al contenuto del cliente per eseguire un'operazione di servizio senza l'approvazione esplicita del cliente. Customer Lockbox consente al cliente di accedere al flusso di lavoro di approvazione per le richieste di accesso al contenuto. Occasionalmente, i tecnici Microsoft sono coinvolti durante il processo di supporto per risolvere i problemi segnalati dai clienti e risolverli. Nella maggior parte dei casi, i problemi vengono risolti tramite strumenti di telemetria e debug estesi che Microsoft ha in atto per i suoi servizi. Tuttavia, possono verificarsi casi che richiedono a un tecnico Microsoft di accedere al contenuto del cliente per determinare la causa principale e risolvere il problema. Customer Lockbox richiede che il tecnico richieda l'accesso al cliente come fase finale del flusso di lavoro di approvazione. In questo modo le organizzazioni possono approvare o rifiutare queste richieste, in modo da controllare direttamente se un tecnico Microsoft può accedere ai dati dell'utente finale dell'organizzazione.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management forniscono i diritti per un utente di usufruire di Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori possono attivare Customer Lockbox nella interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere [Customer Lockbox in Office 365](/microsoft-365/compliance/customer-lockbox-requests). Quando Customer Lockbox è attivato, Microsoft deve ottenere l'approvazione di un'organizzazione prima di accedere a qualsiasi contenuto.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Attualmente, il servizio Customer Lockbox non può essere limitato a utenti specifici. Anche se i servizi tenant non sono attualmente in grado di limitare i vantaggi a utenti specifici, è consigliabile eseguire sforzi per limitare i vantaggi del servizio agli utenti con licenza. Ciò consente di evitare potenziali interruzioni del servizio quando le funzionalità di destinazione sono disponibili.

## <a name="office-365-message-encryption"></a>Crittografia dei messaggi di Office 365

Crittografia messaggi di Office 365 (OME) è un servizio basato su Azure Rights Management (Azure RMS) che consente di inviare posta elettronica crittografata a destinatari interni o esterni all'organizzazione, indipendentemente dall'indirizzo di posta elettronica di destinazione (Gmail, Yahoo! Mail, Outlook.com e così via).

Per visualizzare messaggi crittografati, i destinatari possono ottenere un passcode monouso, accedere con un account Microsoft oppure accedere con un account aziendale o dell'istituto di istruzione associato a Office 365. I destinatari possono anche inviare risposte crittografate. Non è necessaria una sottoscrizione per visualizzare i messaggi crittografati o inviare risposte crittografate.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

I mittenti dei messaggi beneficiano del controllo aggiunto sui messaggi di posta elettronica sensibili forniti da Office 365 Message Encryption.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 e Azure Information Protection Piano 1 forniscono a un utente i diritti per trarre vantaggio da Office 365 Message Encryption.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Gli amministratori creano e gestiscono Office 365 Message Encryption nell'Exchange di amministrazione in **Regole del flusso di**  >  **posta**. Per impostazione predefinita, queste regole si applicano a tutti gli utenti del tenant. Per ulteriori informazioni sulla configurazione di nuove Office 365 Message Encryption, vedere [Set up new Message Encryption capabilities](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Gli amministratori devono applicare regole del flusso di posta Office 365 Message Encryption solo agli utenti con licenza. Per ulteriori informazioni sulla definizione delle regole del flusso di posta, vedere [Define mail flow rules to encrypt email messages](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="privileged-access-management-in-office-365"></a>Gestione degli accessi privilegiati in Office 365

[La gestione degli accessi con privilegi (PAM, Privileged Access Management)](/microsoft-365/compliance/privileged-access-management-configuration) offre un controllo granulare dell'accesso sulle attività di amministrazione con privilegi in Office 365. Dopo aver abilitato PAM, per completare le attività con privilegi elevati e con privilegi, gli utenti dovranno richiedere l'accesso just-in-time tramite un flusso di lavoro di approvazione con un ambito elevato e associato a tempo.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

L'abilitazione di PAM consente alle organizzazioni di operare senza privilegi permanenti. Gli utenti traggono vantaggio dal livello aggiunto di difesa dalle vulnerabilità derivanti dall'accesso amministrativo permanente che consente l'accesso senza limiti ai propri dati.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 Compliance e F5 Security & Compliance e Microsoft 365 E5/A5 Information Protection and Governance forniscono i diritti per un utente a beneficiare di PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità PAM sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione dei criteri PAM, vedere [Introduzione alla gestione degli accessi con privilegi.](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

I clienti possono gestire PAM per utente tramite i criteri di accesso e il gruppo di responsabili approvazione, che possono essere applicati agli utenti con licenza. Per ulteriori informazioni, vedere [Privileged access management in Office 365.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="records-management"></a>Gestione record

Gestione dei record consente alle organizzazioni di soddisfare gli obblighi aziendali e normativi di conservazione dei record tramite l'individuazione, la classificazione, l'etichettatura, la conservazione e le funzionalità di eliminazione defensibile tra i dati di Microsoft 365 e di terze parti.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quali licenze forniscono a un utente i diritti di usufruire del servizio?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 e Office 365 E5/A5/G5 forniscono a un utente i diritti per trarre vantaggio dalla gestione dei record, inclusa la dichiarazione di elementi come record o record normativi, applicazione automatica di etichette di conservazione o record ed esecuzione di processi di revisione dell'eliminazione (escludendo l'applicazione automatica di un'etichetta di conservazione in base a classificatori addestrabili).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 Compliance e F5 Security & Compliance e Microsoft 365 Information Protection and Governance forniscono a un utente i diritti per trarre vantaggio dall'applicazione automatica di etichette di conservazione o record basate su classificatori addestrabili.

### <a name="how-do-users-benefit-from-the-service"></a>In che modo gli utenti traggono vantaggio dal servizio?

Gli utenti traggono vantaggio dalla possibilità di dichiarare il contenuto come record e di gestire il processo di registrazione completo dalla definizione e dalla dichiarazione dei criteri attraverso l'eliminazione defensibile.

### <a name="how-is-the-service-provisioneddeployed"></a>Come viene eseguito il provisioning/distribuzione del servizio?

Per impostazione predefinita, le funzionalità di gestione dei record sono abilitate a livello di tenant per tutti gli utenti all'interno del tenant. Per informazioni sulla configurazione di Gestione record da applicare agli utenti con [licenza,](/microsoft-365/compliance/records-management)vedere Informazioni sulla gestione dei record in Microsoft 365 .

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Come è possibile applicare il servizio solo agli utenti del tenant con licenza per il servizio?

Le funzionalità di gestione dei record possono essere applicate agli utenti con licenza in posizioni specifiche (siti del team, siti di gruppo e così via). Per informazioni sulla configurazione di Gestione record da applicare agli utenti con [licenza,](/microsoft-365/compliance/records-management)vedere Informazioni sulla gestione dei record in Microsoft 365 .
