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
description: Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una protezione zero-day affidabile e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale.
ms.openlocfilehash: c736ac7c107c91c720737c569a3e41fe5bb0c98f
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173011"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrizione del servizio Microsoft Defender per Office 365

Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una protezione zero-day affidabile e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale. Defender per Office 365 include funzionalità avanzate di creazione di report e traccia url che consentono agli amministratori di comprendere il tipo di attacchi che si verificano nell'organizzazione.

Di seguito sono riportati i modi principali per usare Defender per Office 365 per la protezione dei messaggi:

- In uno scenario di solo filtro di Defender per Office 365, Defender per Office 365 fornisce la protezione della posta elettronica basata su cloud per l'ambiente Exchange Server locale o qualsiasi altra soluzione di posta elettronica SMTP locale.

- Defender per Office 365 può essere abilitato per proteggere le cassette postali ospitate sul cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere la [descrizione del servizio Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- In una distribuzione ibrida, Defender per Office 365 può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud con Exchange Online Protection per il filtro della posta elettronica in ingresso.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilità di Microsoft Defender per Office 365

Microsoft Defender per Office 365 Piano 2 è incluso in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security e Microsoft 365 E5 come specificato qui: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender per Office 365 Piano 1 è incluso in Microsoft 365 Business Premium.

È possibile aggiungere Defender per Office 365 ai seguenti piani di sottoscrizione di Exchange e Microsoft 365:

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

Per acquistare Microsoft Defender per Office 365, vedere [Microsoft Defender per Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Microsoft Defender per Office 365, vedere la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novità di Microsoft Defender per Office 365

Stiamo continuando ad aggiungere nuove funzionalità a Defender per Office 365. Per altre informazioni sulle nuove funzionalità disponibili in Defender per Office 365 (o Microsoft 365 in generale), vedere le risorse seguenti:

- [Roadmap di Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novità di Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisiti per Microsoft Defender per Office 365

Defender per Office 365 può essere utilizzato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportati da Defender per Office 365, vedere le sezioni "Browser supportati" e "Lingue supportate" nell'interfaccia di amministrazione di [Exchange in Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilità delle funzionalità tra i piani di Defender per Office 365

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.<br><br>

| Funzionalità | Defender per Office 365 Piano 1 | Defender per Office 365 Piano 2 | Microsoft 365 E5 / A5 Security|
|:-----|:-----|:-----|:-----|
|*Configurazione, protezione e rilevamento*|
|[Allegati sicuri](#safe-attachments)|Sì|Sì|Sì|
|Allegati sicuri in Teams|Sì|Sì|Sì|
|[Collegamenti sicuri](#safe-links)|Sì|Sì|Sì|
|[Sicurezza documenti](#safe-documents)|No|No|Sì|
|Collegamenti sicuri in Teams|Sì|Sì|Sì|
|[ATP per SharePoint, OneDrive e Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sì|Sì|Sì|
|[Criteri anti-phishing](#anti-phishing-policies)|Sì|Sì|Sì|
|[Report in tempo reale](#real-time-reports)|Sì|Sì|Sì|
|*Automazione, indagine, correzione ed istruzione*|
|[Tracker delle minacce](#threat-trackers)|No|Sì|Sì|
|Indagine sulle minacce (indagine avanzata sulle minacce)|[Rilevamenti in tempo reale](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Risposta automatica agli eventi imprevisti](#automated-incident-response)|No|Sì|Sì|
|[Simulatore di attacchi](#attack-simulator)|No|Sì|Sì|
|*Integrazione con [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sì|Sì|

> [!NOTE]
> Se il tenant dispone solo della licenza di valutazione di Microsoft Defender per Office Plan P2 o office 365 E5, senza altre licenze idonee per Microsoft 365 Defender, non sarà possibile accedere a Microsoft 365 Defender. Per altre informazioni sulla licenza MTP, vedi [Requisiti di Microsoft 365 Defender.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Funzionalità di Defender per Office 365

### <a name="safe-attachments"></a>Allegati sicuri

[Gli allegati sicuri](/microsoft-365/security/office-365-security/atp-safe-attachments) proteggono da malware e virus sconosciuti e forniscono una protezione zero-day per proteggere il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui Defender per Office 365 usa un'ampia gamma di tecniche di apprendimento automatico e analisi per rilevare intenti dannosi. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale.

> [!NOTE]
> L'analisi degli allegati sicuri avviene nella stessa area in cui si trovano i dati di Office 365. Per ulteriori informazioni sull'area geografica del data center, vedere [Dove si trovano i dati?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Collegamenti sicuri

La [funzionalità Collegamenti sicuri](/microsoft-365/security/office-365-security/atp-safe-links) protegge in modo proattivo gli utenti da URL dannosi in un messaggio o in un documento di Office. La protezione rimane attiva ogni volta che l'utente seleziona il collegamento, perché i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

I collegamenti sicuri sono disponibili per gli URL nelle seguenti app:

- Microsoft 365 Apps for enterprise in Windows o Mac

- Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web)

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre di una licenza per Defender per Office 365, devono essere inclusi nei criteri collegamenti sicuri e devono accedere ai propri dispositivi perché la protezione sia <sup>\*</sup> in atto.
>
> <sup>\*</sup> Per le licenze di Defender per Office 365 a livello di organizzazione (ad esempio, ATP_ENTERPRISE_FACULTY), non è necessario assegnare le licenze defender per Office 365 ai singoli utenti.
>
> Per ulteriori informazioni sulla protezione dei collegamenti sicuri, vedere [Collegamenti sicuri in Microsoft Defender per Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Sicurezza documenti

La [funzionalità Documenti](/microsoft-365/security/office-365-security/safe-docs) sicuri usa Microsoft Defender for [Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per analizzare i documenti e i file aperti in [Visualizzazione protetta.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Che cosa è necessario sapere prima di iniziare

- Documenti sicuri è ora disponibile in genere per gli utenti con Office versione 2004 (12730.x) o versione successiva. Questa funzionalità è disattivata per impostazione predefinita e dovrà essere abilitata dall'amministratore della sicurezza.

- Questa funzionalità è disponibile solo per gli utenti con la licenza Microsoft 365 E5 o Microsoft 365 E5 Security (non inclusa nei piani Defender per Office 365).

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Microsoft 365 E5 o Microsoft 365 E5 Security, devono essere inclusi nei criteri Documenti sicuri e devono essere connessi ai propri dispositivi per consentire la <sup>\*</sup> protezione.
>
> Per ulteriori informazioni sulla protezione dei documenti sicuri, vedere [Documenti sicuri in Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[ATP per SharePoint, OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  e Microsoft Teams consente di rilevare e bloccare i file identificati come dannosi nei siti del team e nelle raccolte documenti. Inoltre, la protezione dei collegamenti sicuri è ora disponibile nei canali e nelle chat di Microsoft Teams.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) controlla la presenza di indicatori che un messaggio potrebbe essere un tentativo di phishing nei messaggi in arrivo. Quando gli utenti sono coperti dai criteri di Defender per Office 365 (allegati sicuri, collegamenti sicuri o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di machine learning che analizzano i messaggi e viene eseguita l'azione appropriata, in base ai criteri configurati.

### <a name="real-time-reports"></a>Report in tempo reale

Le funzionalità di monitoraggio disponibili nel Centro sicurezza & e conformità ( ) includono report e informazioni dettagliate in tempo reale che consentono agli amministratori di sicurezza e conformità di concentrarsi su problemi ad alta priorità, ad esempio attacchi alla sicurezza o attività [https://protection.office.com](https://protection.office.com) sospette. [](/microsoft-365/security/office-365-security/view-reports-for-atp) Oltre ad evidenziare le aree di problema, i report intelligenti e le informazioni dettagliate includono suggerimenti e collegamenti per visualizzare ed esplorare i dati ed eseguire azioni rapide.

### <a name="explorer"></a>Explorer

Explorer (anche noto come Esplora minacce) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni. Tuttavia, le visualizzazioni possono essere modificate per visualizzare i dati degli ultimi 30 giorni.

Explorer contiene visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii, Phish e Tutti i messaggi di posta elettronica. Per vedere il confronto tra Esplora risorse e i rilevamenti in tempo reale, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedere Threat Explorer e rilevamenti in tempo [reale.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Rilevamenti in tempo reale

I rilevamenti in tempo reale consentono agli utenti autorizzati di identificare e analizzare le minacce recenti. Analogamente a Explorer, per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni.

I rilevamenti in tempo reale contengono visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii e Phish. Per vedere come vengono confrontati i rilevamenti in tempo reale con Explorer, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedere [Threat Explorer (e](/microsoft-365/security/office-365-security/threat-explorer)rilevamenti in tempo reale).

### <a name="threat-trackers"></a>Tracker delle minacce

[I tracker delle minacce](/microsoft-365/security/office-365-security/threat-trackers) sono widget informativi e visualizzazioni che forniscono agli utenti autorizzati informazioni sui problemi di cybersecurity che potrebbero influire sull'organizzazione.

### <a name="automated-incident-response"></a>Risposta automatica agli eventi imprevisti

Le funzionalità AIR [(Automated Incident Response)](/microsoft-365/security/office-365-security/office-365-air) disponibili in Defender per Office 365 Piano 2 consentono di eseguire processi di indagine automatizzati in risposta alle minacce note attualmente esistenti. Automatizzando determinate attività di indagine, il team delle operazioni di sicurezza può operare in modo più efficiente ed efficace. Le azioni di correzione, ad esempio l'eliminazione di messaggi di posta elettronica dannosi, vengono intraprese dopo l'approvazione da parte del team delle operazioni di sicurezza. Per ulteriori informazioni, vedere [Funzionamento di AIR in Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulator"></a>Simulatore di attacchi

[Il simulatore di](/microsoft-365/security/office-365-security/attack-simulator) attacco consente agli utenti autorizzati di eseguire scenari di attacco realistici nell'organizzazione. Sono disponibili diversi tipi di attacchi, tra cui un attacco di spear-phishing con nome visualizzato, un attacco di tipo password spray e un attacco con password di forza bruta.