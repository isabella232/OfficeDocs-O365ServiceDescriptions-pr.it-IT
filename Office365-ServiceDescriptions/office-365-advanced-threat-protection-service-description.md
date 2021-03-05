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
description: Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una solida protezione zero-day e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale.
ms.openlocfilehash: 6116ffdce71686575258c19c7d70159bcefa2134
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460245"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrizione del servizio Microsoft Defender per Office 365

Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una solida protezione zero-day e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale. Defender per Office 365 include funzionalità avanzate di creazione di report e traccia url che consentono agli amministratori di comprendere il tipo di attacchi che si verificano nell'organizzazione.

Di seguito sono riportati i modi principali per usare Defender per Office 365 per la protezione dei messaggi:

- In uno scenario di solo filtro di Defender per Office 365, Defender per Office 365 fornisce protezione della posta elettronica basata sul cloud per l'ambiente Exchange Server locale o qualsiasi altra soluzione di posta elettronica SMTP locale.

- Defender per Office 365 può essere abilitato per proteggere le cassette postali ospitate nel cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere la descrizione [del servizio Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- In una distribuzione ibrida, Defender per Office 365 può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud con Exchange Online Protection per il filtro della posta elettronica in ingresso.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilità di Microsoft Defender per Office 365

Microsoft Defender per Office 365 Piano 2 è incluso in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security e Microsoft 365 E5 come specificato qui: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) . Defender per Office 365 Piano 1 è incluso in Microsoft 365 Business Premium.

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

Per confrontare le funzionalità tra piani, vedere [Potenti strumenti per supportare l'azienda](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) e [Trasformare l'azienda con Microsoft 365.](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novità di Microsoft Defender per Office 365

We are continuing to add new features to Defender for Office 365. Per altre informazioni sulle nuove funzionalità disponibili in Defender per Office 365 (o Microsoft 365 in generale), vedere le risorse seguenti:

- [Roadmap di Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novità di Microsoft Defender per Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisiti per Microsoft Defender per Office 365

Defender per Office 365 può essere usato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportati da Defender per Office 365, vedere le sezioni "Browser supportati" e "Lingue supportate" nell'interfaccia di amministrazione di [Exchange in Exchange Online Protection.](https://go.microsoft.com/fwlink/p/?LinkId=282381)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilità delle funzionalità tra i piani di Defender per Office 365

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.<br><br>

| Funzionalità | Defender per Office 365 Piano 1 | Defender per Office 365 Piano 2 | Microsoft 365 E5 /A5 Security|
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
|Analisi delle minacce (indagine avanzata sulle minacce)|[Rilevamenti in tempo reale](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Risposta automatica agli eventi imprevisti](#automated-incident-response)|No|Sì|Sì|
|[Simulatore di attacchi](#attack-simulator)|No|Sì|Sì|
|*Integrazione con [Microsoft 365 Defender](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sì|Sì|

> [!NOTE]
> Se il tenant dispone solo della licenza di valutazione Microsoft Defender for Office Plan P2 o office 365 E5, senza altre licenze idonee per Microsoft 365 Defender, non sarà possibile accedere a Microsoft 365 Defender. Per altre informazioni sulla licenza MTP, vedere i requisiti di [Microsoft 365 Defender.](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Funzionalità di Defender per Office 365

### <a name="safe-attachments"></a>Allegati sicuri

[Allegati sicuri](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protegge da virus e malware sconosciuti e fornisce protezione zero-day per proteggere il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui Defender per Office 365 usa un'ampia gamma di tecniche di apprendimento automatico e analisi per rilevare intenti dannosi. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale.

> [!NOTE]
> L'analisi degli allegati sicuri avviene nella stessa area geografica in cui si trovano i dati di Office 365. Per altre informazioni sull'area geografica del data center, vedere [Dove si trovano i dati?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Collegamenti sicuri

La [funzionalità Collegamenti](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) sicuri protegge in modo proattivo gli utenti da URL dannosi in un messaggio o in un documento di Office. La protezione rimane attiva ogni volta che l'utente seleziona il collegamento, perché i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

I collegamenti sicuri sono disponibili per gli URL nelle seguenti app:

- Microsoft 365 Apps for enterprise in Windows o Mac

- Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web)

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Defender per Office 365, devono essere inclusi nei criteri collegamenti sicuri e devono essere connessi ai propri dispositivi perché la protezione sia <sup>\*</sup> sul posto.
>
> <sup>\*</sup> Per le licenze di Defender per Office 365 a livello di organizzazione (ad esempio, ATP_ENTERPRISE_FACULTY), non è necessario assegnare le licenze di Defender per Office 365 ai singoli utenti.
>
> Per ulteriori informazioni sulla protezione dei collegamenti sicuri, vedere [Collegamenti sicuri in Microsoft Defender per Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Sicurezza documenti

La [funzionalità Documenti](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) sicuri usa Microsoft Defender for [Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per analizzare i documenti e i file aperti in [Visualizzazione protetta.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Che cosa è necessario sapere prima di iniziare

- Documenti sicuri è ora disponibile in genere per gli utenti con Office versione 2004 (12730.x) o versione successiva. Questa funzionalità è disattivata per impostazione predefinita e dovrà essere abilitata dall'amministratore della sicurezza.

- Questa funzionalità è disponibile solo per gli utenti con licenza Microsoft 365 E5 o Microsoft 365 E5 Security (non inclusa nei piani di Defender per Office 365).

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Microsoft 365 E5 o Microsoft 365 E5 Security, devono essere inclusi nei criteri documenti sicuri e devono essere connessi ai propri dispositivi per la protezione sul <sup>\*</sup> posto.
>
> Per ulteriori informazioni sulla protezione dei documenti sicuri, vedere [Documenti sicuri in Microsoft 365 E5.](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[ATP per SharePoint, OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  e Microsoft Teams consente di rilevare e bloccare i file identificati come dannosi nei siti del team e nelle raccolte documenti. Inoltre, la protezione collegamenti sicuri è ora disponibile nei canali e nelle chat di Microsoft Teams.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[L'anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) controlla la presenza di indicatori che un messaggio potrebbe essere un tentativo di phishing nei messaggi in arrivo. Quando gli utenti sono coperti dai criteri di Defender per Office 365 (allegati sicuri, collegamenti sicuri o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di machine learning che analizzano i messaggi e vengono intraprese le azioni appropriate, in base ai criteri configurati.

### <a name="real-time-reports"></a>Report in tempo reale

Le funzionalità di monitoraggio disponibili nel Centro sicurezza & e conformità ( ) includono report e approfondimenti in tempo reale che consentono agli amministratori della sicurezza e della conformità di concentrarsi su problemi ad alta priorità, ad esempio attacchi alla sicurezza o maggiore attività [https://protection.office.com](https://protection.office.com) sospette. [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) Oltre ad evidenziare le aree problematice, i report e le informazioni dettagliate intelligenti includono suggerimenti e collegamenti per visualizzare ed esplorare i dati e intraprendere azioni rapide.

### <a name="explorer"></a>Explorer

Explorer (anche noto come Esplora minacce) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni. Tuttavia, le visualizzazioni possono essere modificate per mostrare i dati degli ultimi 30 giorni.

Explorer contiene visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii, Phish e Tutta la posta elettronica. Per informazioni sul confronto tra Esplora risorse e i rilevamenti in tempo reale, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedere [Esplora](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)minacce e rilevamenti in tempo reale.

### <a name="real-time-detections"></a>Rilevamenti in tempo reale

I rilevamenti in tempo reale consentono agli utenti autorizzati di identificare e analizzare le minacce recenti. Analogamente a Explorer, per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni.

I rilevamenti in tempo reale contengono visualizzazioni, ad esempio malware (per posta elettronica e contenuto), invii e phish. Per vedere il confronto tra i rilevamenti in tempo reale e Explorer, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedere Esplora minacce (e rilevamenti in tempo [reale).](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Tracker delle minacce

[I tracker delle minacce](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sono widget informativi e visualizzazioni che forniscono agli utenti autorizzati informazioni sui problemi di cybersecurity che potrebbero influire sull'organizzazione.

### <a name="automated-incident-response"></a>Risposta automatica agli eventi imprevisti

Le funzionalità AIR [(Automated Incident Response)](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) disponibili in Defender per Office 365 Piano 2 consentono di eseguire processi di indagine automatizzati in risposta alle minacce note che esistono oggi. Con determinate attività di indagine automatizzate, il team delle operazioni di sicurezza può operare in modo più efficiente ed efficace. Le azioni di correzione, ad esempio l'eliminazione di messaggi di posta elettronica dannosi, vengono intraprese dopo l'approvazione da parte del team delle operazioni di sicurezza. Per altre informazioni, vedere [Funzionamento di AIR in Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulator"></a>Simulatore di attacchi

[Il simulatore di](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) attacchi consente agli utenti autorizzati di eseguire scenari di attacco realistici nell'organizzazione. Sono disponibili diversi tipi di attacchi, tra cui un attacco di phishing con nome visualizzato, un attacco di tipo password spray e un attacco con password di forza bruta.
