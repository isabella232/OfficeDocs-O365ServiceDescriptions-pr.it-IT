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
description: Microsoft Defender for Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una solida protezione zero-day e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545973"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrizione del servizio Microsoft Defender per Office 365

Microsoft Defender for Office 365 è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da malware e virus sconosciuti fornendo una solida protezione zero-day e include funzionalità per proteggere l'organizzazione da collegamenti dannosi in tempo reale. Defender for Office 365 dispone di funzionalità avanzate di reporting e traccia url che forniscono agli amministratori informazioni dettagliate sul tipo di attacchi che si verificano nell'organizzazione.

Di seguito sono riportato i modi principali in cui è possibile utilizzare Defender per Office 365 protezione dei messaggi:

- In uno scenario di defender per Office 365 solo filtro, Defender for Office 365 fornisce protezione della posta elettronica basata su cloud per l'ambiente Exchange Server locale o qualsiasi altra soluzione di posta elettronica SMTP locale.

- Defender per Office 365 può essere abilitato per proteggere Exchange Online cassette postali ospitate nel cloud. Per ulteriori informazioni su Exchange Online, vedere la [descrizione Exchange Online servizio .](exchange-online-service-description/exchange-online-service-description.md)

- In una distribuzione ibrida, Defender for Office 365 può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud con Exchange Online Protection per il filtro della posta elettronica in ingresso.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender per la Office 365 disponibilità

Microsoft Defender per Office 365 Piano 2 è incluso in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security e Microsoft 365 E5 come specificato di seguito: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender per Office 365 piano 1 è incluso nel Microsoft 365 Business Premium.

È possibile aggiungere Defender per Office 365 ai seguenti piani di abbonamento Exchange e Microsoft 365 di sottoscrizione:

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

Per acquistare Microsoft Defender per Office 365, vedere [Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Per informazioni dettagliate sul piano sulle sottoscrizioni che consentono agli utenti di Microsoft Defender per Office 365, vedere la tabella di [confronto completo delle sottoscrizioni](https://go.microsoft.com/fwlink/?linkid=2139145).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novità di Microsoft Defender per Office 365

Continuiamo ad aggiungere nuove funzionalità a Defender per Office 365. Per altre informazioni sulle nuove funzionalità disponibili su Defender per Office 365 (o Microsoft 365 in generale), vedere le risorse seguenti:

- [Roadmap di Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novità di Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisiti per Microsoft Defender per Office 365

Defender per Office 365 può essere utilizzato con qualsiasi agente di trasferimento posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i web browser e le lingue supportati da Defender per Office 365, vedere le sezioni "Browser supportati" e "Lingue supportate" [nell'interfaccia di amministrazione di Exchange in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilità delle funzionalità in Defender per Office 365 piani

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.<br><br>

| Funzionalità | Defender per Office 365 Piano 1 | Defender per Office 365 Piano 2 | Microsoft 365 E5 / A5 Sicurezza|
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
|*Automazione, indagine, correzione e istruzione*|
|[Tracker delle minacce](#threat-trackers)|No|Sì|Sì|
|Indagine sulle minacce (indagine avanzata sulle minacce)|[Rilevamenti in tempo reale](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Risposta automatica agli incidenti](#automated-incident-response)|No|Sì|Sì|
|[Addestramento alla simulazione di attacco](#attack-simulation-training)|No|Sì|Sì|
|*Integrazione con [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|No|Sì|Sì|

> [!NOTE]
> Se il tenant dispone solo della licenza di valutazione di Microsoft Defender for Office Plan P2 o Office 365 di una licenza di valutazione E5, senza altre licenze idonee per Microsoft 365 Defender, non sarà possibile accedere Microsoft 365 Defender. Per ulteriori informazioni sulla licenza MTP, vedere [Microsoft 365 Defender requirements](/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Defender per Office 365 funzionalità

### <a name="safe-attachments"></a>Allegati sicuri

[Safe Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protegge da malware e virus sconosciuti e fornisce una protezione zero-day per salvaguardare il sistema di messaggistica. Tutti i messaggi e gli allegati che non hanno una firma antivirus/malware nota vengono instradati a un ambiente speciale in cui Defender for Office 365 utilizza una varietà di tecniche di machine learning e analisi per rilevare intenzioni dannose. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale.

> [!NOTE]
> La scansione degli allegati sicuri avviene nella stessa area in cui risiedono Office 365 dati personali. Per ulteriori informazioni sull'area geografica del data center, [vedere Dove si trovano i dati?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Collegamenti sicuri

La [funzione Collegamenti](/microsoft-365/security/office-365-security/atp-safe-links) sicuri protegge in modo proattivo gli utenti da URL dannosi in un messaggio o in un Office documento. La protezione rimane attiva ogni volta che l'utente seleziona il collegamento, perché i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

I collegamenti sicuri sono disponibili per gli URL nelle seguenti app:

- Microsoft 365 Apps for enterprise su Windows o Mac

- Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web)

- Parola, Excel e PowerPoint su Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono essere concessi in licenza per Defender per Office 365 , devono essere inclusi nei criteri collegamenti sicuri <sup>\*</sup> e devono essere connessi sui propri dispositivi affinché la protezione sia in atto.
>
> <sup>\*</sup>Per le licenze Defender for Office 365 a livello di organizzazione (ad esempio, ATP_ENTERPRISE_FACULTY), non è necessario assegnare Defender per Office 365 licenze a singoli utenti.
>
> Per ulteriori informazioni sulla protezione dei collegamenti sicuri, [vedere Collegamenti sicuri in Microsoft Defender per Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sicurezza documenti

La [funzionalità Documenti](/microsoft-365/security/office-365-security/safe-docs) sicuri utilizza Microsoft Defender for [Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) per analizzare documenti e file aperti in [Visualizzazione protetta](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

Che cosa è necessario sapere prima di iniziare

- Safe Documents è ora generalmente disponibile per gli utenti con Office versione 2004 (12730.x) o superiore! Questa funzionalità è disattivata per impostazione predefinita e dovrà essere abilitata dall'amministratore della sicurezza.

- Questa funzionalità è disponibile solo per gli utenti con Microsoft 365 E5 o Microsoft 365 E5 Security licenza (non inclusa in Defender per Office 365 piani).

- Parola, Excel e PowerPoint su Windows

- Canali e chat di Microsoft Teams

> [!NOTE]
> Gli utenti devono essere concessi in licenza per Microsoft 365 E5 o Microsoft 365 E5 Security <sup>\*</sup> , devono essere inclusi nei criteri documenti sicuri e devono essere connessi sui propri dispositivi affinché la protezione sia in atto.
>
> Per ulteriori informazioni sulla protezione dei documenti sicuri, [vedere Documenti sicuri in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[ATP per SharePoint, OneDrive e Microsoft Teams consente](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) di rilevare e bloccare i file identificati come dannosi nei siti del team e nelle raccolte documenti. Inoltre, la protezione dei collegamenti sicuri è ora disponibile nei Microsoft Teams e nelle chat.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[L'anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) controlla i messaggi in arrivo alla ricerca di indicatori che un messaggio potrebbe essere un tentativo di phishing. Quando gli utenti sono coperti dai criteri defender for Office 365 (allegati sicuri, collegamenti sicuri o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di machine learning che analizzano i messaggi e viene intrapresa l'azione appropriata, in base ai criteri configurati.

### <a name="real-time-reports"></a>Report in tempo reale

Le funzionalità di monitoraggio disponibili nel Centro conformità di Security & ( ) includono report e informazioni dettagliate in tempo reale che consentono agli amministratori della [https://protection.office.com](https://protection.office.com) sicurezza e della conformità di concentrarsi su problemi con priorità elevata, ad esempio attacchi di sicurezza o aumento delle attività sospette. [](/microsoft-365/security/office-365-security/view-reports-for-atp) Oltre a evidenziare le aree problematiche, i report intelligenti e le informazioni dettagliate includono consigli e collegamenti per visualizzare ed esplorare i dati e anche intraprendere azioni rapide.

### <a name="explorer"></a>Explorer

Explorer (anche noto come Esplora minacce) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni; tuttavia, le visualizzazioni possono essere modificate per mostrare i dati degli ultimi 30 giorni.

Explorer contiene visualizzazioni, ad esempio Malware (per posta elettronica e contenuto), Invii, Phish e Tutti i messaggi di posta elettronica. Per vedere come Explorer viene confrontato con i rilevamenti in tempo reale, [scaricare questo PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), [vedere Esplora minacce e rilevamenti](/microsoft-365/security/office-365-security/threat-explorer)in tempo reale .

### <a name="real-time-detections"></a>Rilevamenti in tempo reale

I rilevamenti in tempo reale consentono agli utenti autorizzati di identificare e analizzare le minacce recenti. Analogamente a Explorer, per impostazione predefinita, questo report mostra i dati degli ultimi sette giorni.

I rilevamenti in tempo reale contengono visualizzazioni, ad esempio Malware (per posta elettronica e contenuti), Invii e Phish. Per vedere come si confrontano i rilevamenti in tempo reale con Explorer, [scaricare questo PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Per ulteriori informazioni su Explorer (in Microsoft Defender per Office 365 Piano 2) e sui rilevamenti in tempo reale (in Microsoft Defender per Office 365 Piano 1), [vedere Threat Explorer (e rilevamenti](/microsoft-365/security/office-365-security/threat-explorer)in tempo reale) .

### <a name="threat-trackers"></a>Tracker delle minacce

[I Threat Tracker sono](/microsoft-365/security/office-365-security/threat-trackers) widget e visualizzazioni informativi che forniscono agli utenti autorizzati informazioni sui problemi di sicurezza informatica che potrebbero influire sull'organizzazione.

### <a name="automated-incident-response"></a>Risposta automatica agli incidenti

[Le funzionalità air (Automated Incident Response)](/microsoft-365/security/office-365-security/office-365-air) disponibili in Defender for Office 365 Plan 2 consentono di eseguire processi di indagine automatizzati in risposta a minacce ben note che esistono oggi. Automatizzatamente determinate attività di indagine, il team operativo di sicurezza può operare in modo più efficiente ed efficace. Le azioni correttive, ad esempio l'eliminazione di messaggi di posta elettronica dannosi, vengono intraprese dopo l'approvazione del team delle operazioni di sicurezza. Per ulteriori informazioni, vedere [Come funziona AIR in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Addestramento alla simulazione di attacco

[Il training di simulazione](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) degli attacchi è uno strumento intelligente di gestione del rischio sociale che automatizza la creazione e la gestione di simulazioni di phishing. Le simulazioni aiutano i clienti a rilevare, dare priorità e correggere i rischi di phishing utilizzando esche di phishing del mondo reale e formazione iper-mirata per modificare i comportamenti dei dipendenti.

- L'addestramento alla simulazione d'attacco è ora disponibile GCC WW e GCC (sarà in GCC dal 21 giugno).
- Per ulteriori informazioni su come iniziare, vedere Introduzione [all'utilizzo del training di simulazione di attacco](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).
- Sono disponibili varie tecniche di attacco che applicano payload phish de-armaizzati e reali che replicano il comportamento degli aggressori del mondo reale per rendere rilevanti le simulazioni di phishing.
- Questo servizio è disponibile per le organizzazioni che hanno Microsoft 365 E5, Office 365 E5 o [Microsoft Defender per Office 365 di piano 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Un sottoinsieme di funzionalità viene offerto ai clienti E3 come prova.
- Per ulteriori informazioni e provare una simulazione, vedere [Simulare un attacco di phishing](/microsoft-365/security/office-365-security/attack-simulation-training).