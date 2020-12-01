---
title: Descrizione del servizio Microsoft Defender per Office 365
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender per Office 365 è un servizio di filtraggio della posta elettronica basato sul cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una protezione affidabile per il giorno zero e include funzionalità che consentono di salvaguardare l'organizzazione da collegamenti nocivi in tempo reale.
ms.openlocfilehash: 1d99b59e089ecb351d436c49a4f4e3986aefa6cd
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519027"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrizione del servizio Microsoft Defender per Office 365

Microsoft Defender per Office 365 è un servizio di filtraggio della posta elettronica basato sul cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una protezione affidabile per il giorno zero e include funzionalità che consentono di salvaguardare l'organizzazione da collegamenti nocivi in tempo reale. Defender per Office 365 dispone di funzionalità di creazione di report e di traccia URL che forniscono agli amministratori informazioni sul tipo di attacchi che si verificano nell'organizzazione.

Di seguito sono riportati i modi principali in cui è possibile utilizzare Defender per Office 365 per la protezione dei messaggi:

- In uno scenario di solo filtro di protezione per Office 365, Defender per Office 365 fornisce la protezione della posta elettronica basata sul cloud per l'ambiente di Exchange Server locale o per qualsiasi altra soluzione di posta elettronica SMTP locale.

- Defender per Office 365 può essere abilitato per proteggere le cassette postali ospitate sul cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere la [Descrizione del servizio Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- In una distribuzione ibrida, il difensore per Office 365 può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud con Exchange Online Protection per il filtro della posta elettronica in ingresso.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender per la disponibilità di Office 365

Il difensore per Office 365 piano 2 è incluso in Office 365 E5, Office 365 a5 e Microsoft 365 E5. Il difensore per Office 365 piano 1 è incluso in Microsoft 365 Business Premium.

È possibile aggiungere Defender per Office 365 ai piani di sottoscrizione di Exchange e Microsoft 365 seguenti:

- Exchange Online Piano 1

- Exchange Online, piano 2

- Chiosco Exchange Online

- Exchange Online Protection

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Per acquistare Microsoft Defender per Office 365, vedere [Microsoft Defender per office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Per confrontare le funzionalità tra i piani, vedere [strumenti potenti per supportare l'organizzazione](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) e [trasformare la propria azienda con Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novità di Microsoft Defender per Office 365

Stiamo continuando ad aggiungere nuove funzionalità a Defender per Office 365. Per ulteriori informazioni sulle nuove funzionalità che vengono a Defender per Office 365 (o Microsoft 365 in generale), vedere le risorse seguenti:

- [Roadmap di Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novità di Microsoft Defender per Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisiti per Microsoft Defender per Office 365

Defender per Office 365 può essere utilizzato con qualsiasi agente di trasferimento posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportate da Defender per Office 365, vedere le sezioni "browser supportati" e "lingue supportate" nell'interfaccia di [amministrazione di Exchange in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilità delle funzionalità tra i piani di protezione per Office 365

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.<br><br>

| Funzionalità | Difensore per Office 365 piano 1 | Difensore per Office 365 piano 2 | Sicurezza di Microsoft 365 E5/E5|
|:-----|:-----|:-----|:-----|
|*Configurazione, protezione e rilevamento*|
|[Allegati sicuri](#safe-attachments)|Sì|Sì|Sì|
|Allegati sicuri nei team|Sì|Sì|Sì|
|[Collegamenti sicuri](#safe-links)|Sì|Sì|Sì|
|[Sicurezza documenti](#safe-documents)|No|No|Sì|
|Collegamenti sicuri in Teams|Sì|Sì|Sì|
|[ATP per SharePoint, OneDrive e Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sì|Sì|Sì|
|[Criteri anti-phishing](#anti-phishing-policies)|Sì|Sì|Sì|
|[Report in tempo reale](#real-time-reports)|Sì|Sì|Sì|
|*Automazione, analisi, correzione e formazione*|
|[Tracker delle minacce](#threat-trackers)|No|Sì|Sì|
|Indagine sulle minacce (Advanced Threat Investigation)|[Rilevamenti in tempo reale](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Risposta agli incidenti automatici](#automated-incident-response)|No|Sì|Sì|
|[Simulatore di attacchi](#attack-simulator)|No|Sì|Sì|
|*Integrazione con Microsoft 365 Defender*|No|No|Sì|

> [!TIP]
> Si desidera un elenco di differenze scaricabili tra Defender per Office 365 piano 1 e piano 2? [Ottenere il file PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="defender-for-office-365-capabilities"></a>Protezione per le funzionalità di Office 365

### <a name="safe-attachments"></a>Allegati sicuri

[Allegati sicuri](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protegge da malware e virus sconosciuti e fornisce una protezione zero-day per salvaguardare il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui Defender per Office 365 utilizza una vasta gamma di tecniche di apprendimento e analisi per rilevare eventuali intenzioni dannose. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale.

> [!NOTE]
> L'analisi degli allegati sicuri avviene nella stessa area in cui si trovano i dati di Office 365. Per ulteriori informazioni sulla geografia del Data Center, vedere [dove si trovano i dati?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Collegamenti sicuri

La funzionalità [collegamenti sicuri](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protegge attivamente gli utenti da URL dannosi in un messaggio o in un documento di Office. La protezione rimane attiva ogni volta che l'utente seleziona il collegamento, perché i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

I collegamenti sicuri sono disponibili per gli URL nelle seguenti app:

- Microsoft 365 Apps for Enterprise su Windows o Mac

- Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web)

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono essere concessi in licenza per il difensore per Office 365 <sup>\*</sup> , devono essere inclusi nei criteri dei collegamenti sicuri e devono essere firmati nei propri dispositivi affinché la protezione sia sul posto.
>
> <sup>\*</sup> Per il difensore dell'intera organizzazione per le licenze di Office 365, ad esempio ATP_ENTERPRISE_FACULTY, non è necessario assegnare le licenze Defender per Office 365 ai singoli utenti.
>
> Per ulteriori informazioni sulla protezione dei collegamenti sicuri, vedere [collegamenti sicuri in Microsoft Defender per Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sicurezza documenti

La funzionalità [documenti sicuri](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) utilizza [Microsoft Defender per endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per analizzare i documenti e i file aperti in [visualizzazione protetta](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

Che cosa è necessario sapere prima di iniziare?

- I documenti attendibili sono ora generalmente disponibili per gli utenti con Office versione 2004 (12730. x) o versioni successive. Questa funzionalità è disattivata per impostazione predefinita e dovrà essere abilitata dall'amministratore della sicurezza.

- Questa funzionalità è disponibile solo per gli utenti con licenza di sicurezza Microsoft 365 E5 o Microsoft 365 E5 (non incluso nei piani Defender per Office 365).

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono essere concessi in licenza per la sicurezza di Microsoft 365 E5 o Microsoft 365 E5 <sup>\*</sup> , devono essere inclusi nei criteri documenti attendibili e devono essere connessi ai propri dispositivi affinché la protezione sia sul posto.
>
> Per ulteriori informazioni sulla protezione dei documenti attendibili, vedere [documenti attendibili in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[ATP per SharePoint, OneDrive e Microsoft teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  aiuta a rilevare e bloccare i file identificati come dannosi nei siti e nelle raccolte documenti del team. Inoltre, la protezione per i collegamenti sicuri è ora disponibile nei canali e nelle chat di Microsoft teams.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[Anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) controlla i messaggi in arrivo per gli indicatori che un messaggio potrebbe essere un tentativo di phishing. Quando gli utenti sono coperti dai criteri di protezione per Office 365 (allegati sicuri, collegamenti sicuri o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di apprendimento automatico che analizzano i messaggi e viene eseguita l'azione appropriata, in base ai criteri configurati.

### <a name="real-time-reports"></a>Report in tempo reale

Le funzionalità di monitoraggio disponibili nel centro sicurezza & conformità includono [report in tempo reale e informazioni dettagliate](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) che consentono agli amministratori di sicurezza e conformità di concentrarsi su problemi di elevata priorità, ad esempio gli attacchi di sicurezza o l'aumento di attività sospette. Oltre a evidenziare aree problematiche, Smart report e Insight includono suggerimenti e collegamenti per visualizzare ed esplorare i dati e per eseguire azioni rapide.

### <a name="explorer"></a>Explorer

Explorer (anche noto come Esplora minacce) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, il report mostra i dati degli ultimi 7 giorni. Tuttavia, è possibile modificare l’impostazione e visualizzare i dati degli ultimi 30 giorni.

Explorer contiene visualizzazioni, ad esempio malware (per la posta elettronica e il contenuto), invii, phishing e tutti i messaggi di posta elettronica. Per visualizzare il confronto tra Explorer e i rilevamenti in tempo reale, [scaricare questo file PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 piano 1), vedere [Threat Explorer e Real-Time detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Rilevamenti in tempo reale

I rilevamenti in tempo reale consentono agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita e in modo analogo a Explorer, il report mostra i dati degli ultimi 7 giorni.

I rilevamenti in tempo reale contengono visualizzazioni, ad esempio malware (per la posta elettronica e il contenuto), invii e phishing. Per vedere come i rilevamenti in tempo reale si confrontano con Explorer, [scaricare questo file PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 piano 1), vedere [Threat Explorer (e Real-Time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Tracker delle minacce

I [Tracker di minacce](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sono widget e visualizzazioni informativi che forniscono agli utenti autorizzati informazioni sui problemi di Cybersecurity che possono influire sull'organizzazione.

### <a name="automated-incident-response"></a>Risposta agli incidenti automatici

Le funzionalità di [risposta agli incidenti automatici](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) disponibili in Defender per Office 365 piano 2 consentono di eseguire processi di analisi automatizzati in risposta a minacce ben note che esistono oggi. Automatizzando determinate attività investigative, il team delle operazioni di sicurezza può operare in modo più efficiente ed efficace. Le azioni correttive, ad esempio l'eliminazione di messaggi di posta elettronica dannosi, vengono apportate al momento dell'approvazione da parte del team di sicurezza. Per ulteriori informazioni, vedere [How Air Works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Simulatore di attacchi

[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) consente agli utenti autorizzati di eseguire scenari di attacco realistici nell'organizzazione. Sono disponibili diversi tipi di attacchi, tra cui un attacco per il nome visualizzato Spear-phishing, un attacco spray per la password e un attacco per la password di forza bruta.
