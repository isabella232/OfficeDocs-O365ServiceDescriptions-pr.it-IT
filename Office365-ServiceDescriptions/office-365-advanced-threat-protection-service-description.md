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
ms.openlocfilehash: 5781f34419eb697cb97634c55fa486fd141d76dd
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204843"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrizione del servizio Microsoft Defender per Office 365

Microsoft Defender per Office 365 è un servizio di filtro della posta elettronica basato sul cloud che consente di proteggere l'organizzazione da minacce avanzate agli strumenti di posta elettronica e collaborazione, ad esempio phishing, compromissione della posta elettronica aziendale e attacchi di malware. Defender for Office 365 offre anche funzionalità di analisi, ricerca e correzione per aiutare i team di sicurezza a identificare, definire le priorità, analizzare e rispondere in modo efficiente alle minacce.

Di seguito sono riportati i modi principali per usare Defender per Office 365 protezione dei messaggi:

- In uno scenario defender per Office 365 solo filtro, Defender per Office 365 fornisce protezione della posta elettronica basata su cloud per l'ambiente Exchange Server locale o qualsiasi altra soluzione di posta elettronica SMTP locale.

- Defender for Office 365 può essere abilitato per proteggere Exchange Online cassette postali ospitate nel cloud. Per ulteriori informazioni sulle Exchange Online, vedere la [descrizione Exchange Online servizio.](exchange-online-service-description/exchange-online-service-description.md)

- In una distribuzione ibrida, Defender per Office 365 può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud con Exchange Online Protection per il filtro della posta elettronica in ingresso.

## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Microsoft Defender per Office 365, vedere la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="feature-availability"></a>Disponibilità delle funzionalità

Nella tabella seguente sono elencate le principali funzionalità di Microsoft Defender Office 365 disponibili tra i piani. Si applicano alcune avvertenze. Per ulteriori informazioni, vedere le note a piè di pagina. Questa tabella può cambiare senza preavviso. Per l'elenco completo e aggiornato delle funzionalità di Microsoft Defender per Office 365 tra piani, vedi Descrizione del servizio [Microsoft Defender for Office 365 Features.](microsoft-defender-for-office-365-features.md)

| Funzionalità | Defender per Office 365 Piano 1 | Defender per Office 365 Piano 2 | Microsoft 365 E5 / Sicurezza A5 |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *Configurazione, protezione e rilevamento* | | | |
| Criteri di sicurezza predefiniti e Analizzatore configurazione | Sì | Sì | Sì |
| [Allegati sicuri](microsoft-defender-for-office-365-features.md#safe-attachments) | Sì | Sì | Sì |
| Cassaforte Allegati in Teams | Sì | Sì | Sì |
| [Collegamenti sicuri](microsoft-defender-for-office-365-features.md#safe-links) | Sì | Sì | Sì |
| [Sicurezza documenti](microsoft-defender-for-office-365-features.md#safe-documents) | No | No | Sì |
| Collegamenti sicuri in Teams | Sì | Sì | Sì |
| Segnala messaggio Add-In | Sì | Sì | Sì |
| [Protezione per SharePoint, OneDrive e Microsoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | Sì | Sì | Sì |
| [Criteri anti-phishing](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | Sì | Sì | Sì |
| [Report in tempo reale](microsoft-defender-for-office-365-features.md#real-time-reports) | Sì | Sì | Sì |
| Protezione avanzata per la posta interna | Sì | Sì | Sì |
| *Automazione, indagine, correzione ed istruzione* | | | |
| [Tracker delle minacce](microsoft-defender-for-office-365-features.md#threat-trackers) | No | Sì | Sì |
| Visualizzazioni campagna | No | Sì | Sì |
| Indagine sulle minacce (indagine avanzata sulle minacce) | [Rilevamenti in tempo reale](microsoft-defender-for-office-365-features.md#real-time-detections) | [Explorer](microsoft-defender-for-office-365-features.md#threat-explorer) | [Explorer](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [Analisi automatizzata & risposta](microsoft-defender-for-office-365-features.md#automated-investigation--response) | No | Sì | Sì |
| [Formazione sulla simulazione degli attacchi](microsoft-defender-for-office-365-features.md#attack-simulation-training) | No | Sì | Sì |
| *Integrazione con [Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender)* | No | Sì | Sì |

> [!NOTE]
> Microsoft Defender per Office 365 è un componente di Microsoft 365 Defender. Per ulteriori informazioni sulla sicurezza automatizzata tra domini con Microsoft 365 Defender, vedere [Microsoft 365 Defender requisiti.](/microsoft-365/security/mtp/prerequisites)

## <a name="learn-more"></a>Ulteriori informazioni

Per ulteriori informazioni su Microsoft Defender per Office 365, vedere le risorse seguenti:

- [Microsoft Defender per Office 365 documenti Microsoft](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Sito Web Microsoft Defender per Office 365](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [Blog di Microsoft Defender Office 365](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Forum di Microsoft Defender Office 365](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>Condizioni di licenza

Per le condizioni e le condizioni di licenza per i prodotti e i servizi acquistati tramite i Programmi Microsoft Commercial Volume Licensing, vedere il [sito condizioni del prodotto](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Messaggistica

Per rimanere informati sulle modifiche imminenti, incluse funzionalità nuove e modificate, manutenzione pianificata o altri annunci importanti, visitare il Centro messaggi. Per ulteriori informazioni, vedere [Centro messaggi.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Accessibilità

Microsoft continua a impegnarsi per la sicurezza dei dati e [l'accessibilità](https://www.microsoft.com/trust-center/compliance/accessibility) dei nostri servizi. Per ulteriori informazioni, vedere Centro protezione [Microsoft](https://www.microsoft.com/trust-center) e Centro [Office Accessibilità.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
