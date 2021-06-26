---
title: Descrizione del servizio Microsoft Defender per Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una protezione zero-day affidabile e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale.
ms.openlocfilehash: a4a83e8be24d0afd07f453a5e0fafd3c19aaa6ba
ms.sourcegitcommit: 9d524917a76a7a8677c727142771eaeedd47a626
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/25/2021
ms.locfileid: "53140818"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrizione del servizio Microsoft Defender per Office 365

Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una protezione zero-day affidabile e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale. Defender for Office 365 dispone di funzionalità avanzate di creazione di report e traccia url che consentono agli amministratori di comprendere il tipo di attacchi che si verificano nell'organizzazione.

Di seguito sono riportati i modi principali per usare Defender per Office 365 protezione dei messaggi:

- In uno scenario defender per Office 365 solo filtro, Defender per Office 365 fornisce protezione della posta elettronica basata su cloud per l'ambiente Exchange Server locale o qualsiasi altra soluzione di posta elettronica SMTP locale.

- Defender for Office 365 può essere abilitato per proteggere Exchange Online cassette postali ospitate nel cloud. Per ulteriori informazioni sulle Exchange Online, vedere la [descrizione Exchange Online servizio.](exchange-online-service-description/exchange-online-service-description.md)

- In una distribuzione ibrida, Defender per Office 365 può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud con Exchange Online Protection per il filtro della posta elettronica in ingresso.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender per Office 365 disponibilità

Microsoft Defender per Office 365 Piano 2 è incluso in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security e Microsoft 365 E5 come specificato qui: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender per Office 365 Piano 1 è incluso in Microsoft 365 Business Premium.

Puoi aggiungere Defender per Office 365 ai piani di sottoscrizione Exchange e Microsoft 365 seguenti:

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

Per acquistare Microsoft Defender per Office 365, vedi [Microsoft Defender per Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Microsoft Defender per Office 365, vedere la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novità di Microsoft Defender per Office 365

Stiamo continuando ad aggiungere nuove funzionalità a Defender per Office 365. Per altre informazioni sulle nuove funzionalità disponibili in Defender per Office 365 (o Microsoft 365 in generale), vedi le risorse seguenti:

- [Roadmap di Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novità di Microsoft Defender per Office 365 - Office 365 | Documenti Microsoft](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisiti per Microsoft Defender per Office 365

Defender for Office 365 può essere usato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportati da Defender per Office 365, vedere le sezioni "Browser supportati" e "Lingue supportate" nell'interfaccia di amministrazione di [Exchange in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="which-users-or-mailboxes-need-to-be-licensed"></a>Quali utenti o cassette postali devono essere concessi in licenza?

Per i tenant di Microsoft Defender per Office 365 Piano 1, le licenze devono essere acquisite per gli utenti o le cassette postali che cadono in uno o più degli scenari seguenti:

- Qualsiasi utente che accede a una cassetta postale che beneficia di Defender per Office 365 protezioni.
- Cassette postali condivise che beneficiano di Defender per Office 365 protezioni.
- Se Cassaforte protezione degli allegati per SharePoint, OneDrive for Business o Teams è attivata, tutti gli utenti che accedono a SharePoint, OneDrive for Business o Teams.
- Qualsiasi utente che utilizza Microsoft 365 Apps o Teams quando Cassaforte sono abilitate le protezioni dei collegamenti.

Per i tenant di Microsoft Defender per Office 365 Piano 2, le licenze devono essere acquisite per gli utenti o le cassette postali che cadono in uno o più degli scenari seguenti:

- Tutti Exchange Online utenti nel tenant. Ciò è dovuto al fatto che le funzionalità e le funzionalità del piano 2 proteggono tutti gli utenti nel tenant.
- Tutte le cassette postali condivise nel tenant.
- Se Cassaforte protezione degli allegati per SharePoint, OneDrive for Business o Teams è attivata, tutti gli utenti che accedono a SharePoint, OneDrive for Business o Teams.
- Qualsiasi utente che utilizza Microsoft 365 Apps o Teams quando Cassaforte sono abilitate le protezioni dei collegamenti.

> [!NOTE]
> Office 365 E5, Microsoft 365 E5 Security e Microsoft 365 E5 includono le licenze di Microsoft Defender per Office P2 e Microsoft 365 Business Premium include le licenze di Microsoft Defender per Office 365 P1.

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilità delle funzionalità in Defender per Office 365 piani

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.<br><br>

| Funzionalità | Defender per Office 365 Piano 1 | Defender per Office 365 Piano 2 | Microsoft 365 E5 / Sicurezza A5|
|:-----|:-----|:-----|:-----|
|*Configurazione, protezione e rilevamento*|
|[Allegati sicuri](#safe-attachments)|Sì|Sì|Sì|
|Cassaforte Allegati in Teams|Sì|Sì|Sì|
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
|[Formazione sulla simulazione degli attacchi](#attack-simulation-training)|No|Sì|Sì|
|*Integrazione con [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sì|Sì|

> [!NOTE]
> Se il tenant dispone solo della licenza di valutazione di Microsoft Defender per Office Piano P2 o della licenza di valutazione di Office 365 E5, senza altre licenze idonee per Microsoft 365 Defender, non sarà possibile accedere Microsoft 365 Defender. Per ulteriori informazioni sulla licenza MTP, vedere [Microsoft 365 Defender requisiti.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Defender per Office 365 funzionalità

### <a name="safe-attachments"></a>Allegati sicuri

[Cassaforte allegati protegge](/microsoft-365/security/office-365-security/atp-safe-attachments) da malware e virus sconosciuti e fornisce protezione zero-day per proteggere il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui Defender per Office 365 usa un'ampia gamma di tecniche di apprendimento automatico e analisi per rilevare intenti dannosi. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale.

> [!NOTE]
> Cassaforte L'analisi degli allegati avviene nella stessa area in cui si trovano Office 365 dati. Per ulteriori informazioni sull'area geografica del data center, vedere [Dove si trovano i dati?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Collegamenti sicuri

La [Cassaforte collegamenti](/microsoft-365/security/office-365-security/atp-safe-links) consente di proteggere in modo proattivo gli utenti da URL dannosi in un messaggio o in un Office documento. La protezione rimane attiva ogni volta che l'utente seleziona il collegamento, perché i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

I collegamenti sicuri sono disponibili per gli URL nelle seguenti app:

- Microsoft 365 Apps for enterprise su Windows o Mac

- Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web)

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Defender per Office 365 , devono essere inclusi nei criteri dei collegamenti di Cassaforte e devono accedere ai propri dispositivi perché la protezione sia <sup>\*</sup> in atto.
>
> <sup>\*</sup>Per le licenze defender per Office 365 a livello di organizzazione (ad esempio, ATP_ENTERPRISE_FACULTY), non è necessario assegnare le licenze defender per Office 365 a singoli utenti.
>
> Per ulteriori informazioni sulla Cassaforte dei collegamenti, vedere Cassaforte [collegamenti in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sicurezza documenti

La [Cassaforte documenti utilizza](/microsoft-365/security/office-365-security/safe-docs) [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per analizzare i documenti e i file aperti in Visualizzazione [protetta.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Che cosa è necessario sapere prima di iniziare?

- Cassaforte I documenti sono ora disponibili per gli utenti con Office versione 2004 (12730.x) o successiva. Questa funzionalità è disattivata per impostazione predefinita e dovrà essere abilitata dall'amministratore della sicurezza.

- Questa funzionalità è disponibile solo per gli utenti con la licenza Microsoft 365 E5 o Microsoft 365 E5 Security (non inclusa in Defender per Office 365 piani).

- Word, Excel e PowerPoint in Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono disporre della licenza per Microsoft 365 E5 o Microsoft 365 E5 Security , devono essere inclusi nei criteri di Cassaforte Documents e devono essere connessi nei propri dispositivi perché la protezione sia <sup>\*</sup> in atto.
>
> Per ulteriori informazioni sulla protezione Cassaforte documenti, vedere [Cassaforte Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[ATP per SharePoint, OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) e Microsoft Teams consente di rilevare e bloccare i file identificati come dannosi nei siti del team e nelle raccolte documenti. Inoltre, la Cassaforte dei collegamenti è ora disponibile Microsoft Teams canali e chat.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) controlla la presenza di indicatori che un messaggio potrebbe essere un tentativo di phishing nei messaggi in arrivo. Quando gli utenti sono coperti da Defender per i criteri di Office 365 (allegati Cassaforte, collegamenti Cassaforte o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di machine learning che analizzano i messaggi e viene eseguita l'azione appropriata, in base ai criteri configurati.

### <a name="real-time-reports"></a>Report in tempo reale

Le funzionalità di monitoraggio disponibili nel Centro sicurezza & e conformità ( ) includono report e informazioni dettagliate in tempo reale che consentono agli amministratori di sicurezza e conformità di concentrarsi su problemi ad alta priorità, ad esempio attacchi alla sicurezza o attività [https://protection.office.com](https://protection.office.com) sospette. [](/microsoft-365/security/office-365-security/view-reports-for-atp) Oltre ad evidenziare le aree di problema, i report intelligenti e le informazioni dettagliate includono suggerimenti e collegamenti per visualizzare ed esplorare i dati ed eseguire azioni rapide.

### <a name="explorer"></a>Explorer

Explorer (anche noto come Esplora minacce) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni. Tuttavia, le visualizzazioni possono essere modificate per visualizzare i dati degli ultimi 30 giorni.

Explorer contiene visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii, Phish e Tutti i messaggi di posta elettronica. Per vedere il confronto tra Esplora risorse e i rilevamenti in tempo reale, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per altre informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedi Threat Explorer e rilevamenti in tempo [reale.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Rilevamenti in tempo reale

I rilevamenti in tempo reale consentono agli utenti autorizzati di identificare e analizzare le minacce recenti. Analogamente a Explorer, per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni.

I rilevamenti in tempo reale contengono visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii e Phish. Per vedere come vengono confrontati i rilevamenti in tempo reale con Explorer, [scarica questo PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Per altre informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), vedi [Threat Explorer (e](/microsoft-365/security/office-365-security/threat-explorer)rilevamenti in tempo reale).

### <a name="threat-trackers"></a>Tracker delle minacce

[I tracker delle minacce](/microsoft-365/security/office-365-security/threat-trackers) sono widget informativi e visualizzazioni che forniscono agli utenti autorizzati informazioni sui problemi di cybersecurity che potrebbero influire sull'organizzazione.

### <a name="automated-incident-response"></a>Risposta automatica agli eventi imprevisti

Le funzionalità AIR [(Automated Incident Response)](/microsoft-365/security/office-365-security/office-365-air) disponibili in Defender per Office 365 Piano 2 ti consentono di eseguire processi di indagine automatizzati in risposta alle minacce note che esistono oggi. Automatizzando determinate attività di indagine, il team delle operazioni di sicurezza può operare in modo più efficiente ed efficace. Le azioni di correzione, ad esempio l'eliminazione di messaggi di posta elettronica dannosi, vengono intraprese dopo l'approvazione da parte del team delle operazioni di sicurezza. Per ulteriori informazioni, vedere [Funzionamento di AIR in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Formazione sulla simulazione degli attacchi

[La formazione sulla simulazione](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) degli attacchi è uno strumento intelligente per la gestione dei rischi sociali che automatizza la creazione e la gestione delle simulazioni di phishing. Le simulazioni consentono ai clienti di rilevare, definire le priorità e correggere i rischi di phishing utilizzando esche di phishing reali e una formazione iper mirata per modificare i comportamenti dei dipendenti.

- L'addestramento alla simulazione di attacchi è ora disponibile in WW e GCC (sarà disponibile GCC dal 21 giugno).
- Per altre informazioni su come iniziare, vedi Introduzione all'uso del training [di simulazione degli attacchi.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Sono disponibili varie tecniche di attacco che applicano payload phish de-armati e reali che replicano il comportamento degli utenti malintenzionati reali per rendere rilevanti le simulazioni di phishing.
- Questo servizio è disponibile per le organizzazioni con licenze Microsoft 365 E5, Office 365 E5 o Microsoft Defender per Office 365 [Piano 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Un sottoinsieme di funzionalità viene offerto ai clienti E3 come versione di valutazione.
- Per ulteriori informazioni e provare una simulazione, vedere [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).