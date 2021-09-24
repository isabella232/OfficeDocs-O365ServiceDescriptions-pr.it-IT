---
title: Descrizione del servizio Funzionalità di Microsoft Defender per Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Informazioni sulle funzionalità disponibili in Microsoft Defender per Office 365.
ms.openlocfilehash: 591236d6028d57025d2dd7a9cfc5ef80d3617176
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671456"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Descrizione del servizio Funzionalità di Microsoft Defender per Office 365

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novità di Microsoft Defender per Office 365

Stiamo continuando ad aggiungere nuove funzionalità a Defender per Office 365. Per altre informazioni sulle nuove funzionalità disponibili in Defender per Office 365 (o Microsoft 365 in generale), vedi le risorse seguenti:

- [Roadmap di Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap)

- [Novità di Microsoft Defender per Office 365 - Office 365 | Documenti Microsoft](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Funzionalità defender per Office 365

### <a name="safe-attachments"></a>Allegati sicuri

[Cassaforte allegati protegge](/microsoft-365/security/office-365-security/atp-safe-attachments) da malware e virus sconosciuti e fornisce protezione zero-day per proteggere il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui Defender per Office 365 usa un'ampia gamma di tecniche di apprendimento automatico e analisi per rilevare intenti dannosi. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale.

> [!NOTE]
> Cassaforte L'analisi degli allegati avviene nella stessa area in cui si trovano Office 365 dati. Per ulteriori informazioni sull'area geografica del data center, vedere [Dove si trovano i dati?](/microsoft-365/enterprise/o365-data-locations)

### <a name="safe-links"></a>Collegamenti sicuri

La [Cassaforte collegamenti](/microsoft-365/security/office-365-security/atp-safe-links) consente di proteggere in modo proattivo gli utenti da URL dannosi in un messaggio o in Office documento. La protezione rimane attiva ogni volta che l'utente seleziona il collegamento, perché i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

I collegamenti sicuri sono disponibili per gli URL nelle seguenti app:

- Microsoft 365 Apps for enterprise su Windows o Mac

- Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web)

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Defender per Office 365 , devono essere inclusi nei criteri dei collegamenti di Cassaforte e devono essere connessi nei propri dispositivi perché la protezione sia <sup>\*</sup> in atto.
>
> <sup>\*</sup>Per le licenze defender per Office 365 a livello di organizzazione (ad esempio, ATP_ENTERPRISE_FACULTY), non è necessario assegnare le licenze defender per Office 365 a singoli utenti.
>
> Per ulteriori informazioni sulla protezione Cassaforte collegamenti, vedere Cassaforte [collegamenti in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sicurezza documenti

La [Cassaforte documenti utilizza](/microsoft-365/security/office-365-security/safe-docs) [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per analizzare i documenti e i file aperti in Visualizzazione [protetta.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Che cosa è necessario sapere prima di iniziare?

- Cassaforte I documenti sono ora disponibili per gli utenti con Office versione 2004 (12730.x) o successiva. Questa funzionalità è disattivata per impostazione predefinita e dovrà essere abilitata dall'amministratore della sicurezza.

- Questa funzionalità è disponibile solo per gli utenti con la licenza Microsoft 365 E5 o Microsoft 365 E5 Security (non inclusa in Defender per Office 365 piani).

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Microsoft 365 E5 o Microsoft 365 E5 Security , devono essere inclusi nei criteri di Cassaforte Documents e devono essere connessi nei propri dispositivi per la protezione. <sup>\*</sup>
>
> Per ulteriori informazioni sulla protezione Cassaforte documenti, vedere [Cassaforte Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>Protezione per SharePoint, OneDrive e Microsoft Teams

[La protezione per SharePoint, OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) e Microsoft Teams consente di rilevare e bloccare i file identificati come dannosi nei siti del team e nelle raccolte documenti. Inoltre, la Cassaforte dei collegamenti è ora disponibile in Microsoft Teams e chat.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) controlla la presenza di indicatori che un messaggio potrebbe essere un tentativo di phishing nei messaggi in arrivo. Quando gli utenti sono coperti da Defender per i criteri di Office 365 (allegati Cassaforte, collegamenti Cassaforte o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di machine learning che analizzano i messaggi e viene eseguita l'azione appropriata, in base ai criteri configurati.

### <a name="real-time-reports"></a>Report in tempo reale

Le funzionalità di monitoraggio disponibili nel Centro [](/microsoft-365/security/office-365-security/view-reports-for-atp) sicurezza & conformità includono report e informazioni dettagliate [in](https://protection.office.com) tempo reale che consentono agli amministratori di sicurezza e conformità di concentrarsi su problemi ad alta priorità, ad esempio attacchi alla sicurezza o attività sospette. Oltre ad evidenziare le aree di problema, i report intelligenti e le informazioni dettagliate includono suggerimenti e collegamenti per visualizzare ed esplorare i dati ed eseguire azioni rapide.

### <a name="threat-explorer"></a>Esplora minacce

Threat Explorer (noto anche come Explorer) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni. Tuttavia, le visualizzazioni possono essere modificate per visualizzare i dati degli ultimi 30 giorni.

Explorer contiene visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii, Phish e Tutti i messaggi di posta elettronica. Per vedere il confronto tra Esplora risorse e i rilevamenti in tempo reale, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per altre informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedi Threat Explorer e rilevamenti in tempo [reale.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Rilevamenti in tempo reale

I rilevamenti in tempo reale consentono agli utenti autorizzati di identificare e analizzare le minacce recenti. Analogamente a Explorer, per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni.

I rilevamenti in tempo reale contengono visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii e Phish. Per vedere come vengono confrontati i rilevamenti in tempo reale con Explorer, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per altre informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedi Threat Explorer e rilevamenti in tempo [reale.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Tracker delle minacce

[I tracker delle minacce](/microsoft-365/security/office-365-security/threat-trackers) sono widget informativi e visualizzazioni che forniscono agli utenti autorizzati informazioni sui problemi di cybersecurity che potrebbero influire sull'organizzazione.

### <a name="automated-investigation--response"></a>Analisi automatizzata & risposta

[Le funzionalità AIR (Automated Investigation & Response)](/microsoft-365/security/office-365-security/office-365-air) disponibili in Defender per Office 365 Piano 2 ti consentono di eseguire processi di indagine automatizzati in risposta alle minacce note che esistono oggi. Automatizzando determinate attività di indagine, il team delle operazioni di sicurezza può operare in modo più efficiente ed efficace. Le azioni di correzione, ad esempio l'eliminazione di messaggi di posta elettronica dannosi, vengono intraprese dopo l'approvazione da parte del team delle operazioni di sicurezza. Per ulteriori informazioni, vedere [Funzionamento di AIR in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Formazione sulla simulazione degli attacchi

[La formazione sulla simulazione](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) degli attacchi è uno strumento intelligente per la gestione dei rischi sociali che automatizza la creazione e la gestione delle simulazioni di phishing. Le simulazioni consentono ai clienti di rilevare, definire le priorità e correggere i rischi di phishing utilizzando esche di phishing reali e una formazione iper mirata per modificare i comportamenti dei dipendenti.

- La simulazione di attacchi è ora disponibile in WW e GCC (sarà disponibile GCC dal 21 giugno).
- Per altre informazioni su come iniziare, vedi Introduzione all'uso del training [di simulazione degli attacchi.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Sono disponibili varie tecniche di attacco che applicano payload phish de-armati e reali che replicano il comportamento degli utenti malintenzionati reali per rendere rilevanti le simulazioni di phishing.
- Questo servizio è disponibile per le organizzazioni con licenze Microsoft 365 E5, Office 365 E5 [o Microsoft Defender per Office 365 Piano 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Un sottoinsieme di funzionalità viene offerto ai clienti E3 come versione di valutazione.
- Per ulteriori informazioni e provare una simulazione, vedere [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).