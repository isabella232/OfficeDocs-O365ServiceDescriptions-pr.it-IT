---
title: Descrizione del servizio Office 365 Advanced Threat Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) è il servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da virus e malware sconosciuti fornendo una protezione zero-day affidabile e include funzionalità di salvaguardia dell'organizzazione da collegamenti dannosi in tempo reale. ATP dispone di funzionalità di creazione report e traccia URL avanzate che consentono agli amministratori di analizzare i tipi di attacchi che si verificano nell'organizzazione.
ms.openlocfilehash: a54d0fddae4430b450b944781cbeca1cbb1e414f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776417"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descrizione del servizio Office 365 Advanced Threat Protection

Microsoft Office 365 Advanced Threat Protection (ATP) è il servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da virus e malware sconosciuti fornendo una protezione zero-day affidabile e include funzionalità di salvaguardia dell'organizzazione da collegamenti dannosi in tempo reale. ATP dispone di funzionalità di creazione report e traccia URL avanzate che consentono agli amministratori di analizzare i tipi di attacchi che si verificano nell'organizzazione.
  
Di seguito sono riportati i modi principali in cui è possibile utilizzare ATP per la protezione dei messaggi:
  
- In uno scenario di solo filtro ATP di Office 365, ATP fornisce la protezione della posta elettronica basata sul cloud per l'ambiente Exchange Server locale o per qualsiasi altra soluzione di posta elettronica SMTP locale.
    
- Office 365 ATP può essere abilitato per proteggere le cassette postali ospitate nel cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- In una distribuzione ibrida, ATP può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si utilizza una combinazione di cassette postali locali e cloud in Exchange Online Protection per il filtro di posta elettronica in ingresso.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilità di Office 365 Advanced Threat Protection (ATP)

ATP è incluso in Office 365 Enterprise E5, Office 365 Education a5 e Microsoft 365 business. 
  
È possibile aggiungere ATP ai seguenti piani di abbonamento di Exchange e Office 365: 
  
- Exchange Online Piano 1
    
- Exchange Online, piano 2
    
- Chiosco Exchange Online
    
- Exchange Online Protection
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 Enterprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Per acquistare Office 365 Advanced Threat Protection, vedere [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).
  
Per confrontare le funzionalità tra i piani, vedere [confrontare i piani di Office 365 per le aziende](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) e [individuare la soluzione Microsoft 365 Enterprise adatta all'utente](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Novità in Office 365 Advanced Threat Protection (ATP)

Stiamo continuando ad aggiungere nuove funzionalità a Office 365 ATP. Di seguito è riportato un elenco di diverse nuove funzionalità, alcune delle quali richiedono la revisione e l'aggiornamento di un criterio ATP. Per ulteriori informazioni sulle nuove funzionalità di ATP (o Microsoft 365 in generale), visitare la Guida di [orientamento di microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365).

|Aggiornamenti delle funzionalità  |Elementi azione  |
|---------|---------|
|[Office 365 Threat Intelligence](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) (TI) le funzionalità sono ora le funzionalità di ricerca e di risposta alle minacce nell'ambito del piano ATP 2. Sono disponibili nuove funzionalità, ad esempio l' [analisi e la risposta automatizzate](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office)e i miglioramenti apportati a [Threat Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance).<br/><br/>Se l'organizzazione attualmente non dispone di ATP o se si dispone di ATP, ma non di TI, sono disponibili diverse opzioni da prendere in considerazione, con la disponibilità di ATP piano 1 e ATP piano 2. Per ulteriori informazioni, vedere [disponibilità delle funzionalità tra i piani di Advanced Threat Protection (ATP)](#feature-availability-across-advanced-threat-protection-atp-plans) (in questo articolo) e i [piani e i prezzi di Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection). |Esaminare la sottoscrizione dell'organizzazione e, se necessario, [acquistare o modificare un componente aggiuntivo](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on).  |
|Quando gli utenti utilizzano Outlook o Outlook Web Application (OWA), i [collegamenti sicuri di ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) eseguono il rendering degli URL originali e non degli URL riscritti. (Viene chiamato il rendering del collegamento nativo).<br>Quando il rendering dei collegamenti nativi è disponibile per l'organizzazione, questa funzionalità funzionerà in Outlook 365 (a portata di clic), OWA e in Windows e Mac OS. |Nessuno         |
|Le [pagine di avviso ATP di Office 365](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) dispongono di una nuova combinazione di colori, maggiori dettagli e la possibilità di continuare a un sito nonostante gli avvisi e i consigli specificati. |Nessuno         |
|La protezione dei [collegamenti sicuri ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) è estesa per essere applicata agli URL di Office per il Web (Word per il Web, Excel per il Web, PowerPoint per il Web e OneNote per il Web) e Office 365 ProPlus su Mac.   |[Esaminare e modificare i criteri dei collegamenti sicuri di ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|Le funzionalità di quarantena nel &amp; Centro sicurezza e conformità sono estese a [ATP per SharePoint Online, OneDrive for business e Microsoft teams](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams). |[Esaminare e modificare i criteri per gli allegati sicuri di ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|La protezione di [collegamenti sicuri ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) è estesa per essere applicata ai messaggi di posta elettronica inviati tra gli utenti all'interno di un'organizzazione. |[Esaminare e modificare i criteri dei collegamenti sicuri di ATP](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|La protezione dei [collegamenti sicuri di ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) è estesa per essere applicata agli URL nella posta elettronica e negli URL dei documenti di Office 365 ProPlus, ad esempio Word, Excel, PowerPoint e Visio su Windows, nonché le app di Office sui dispositivi iOS e Android.  |Assicurarsi [di utilizzare l'autenticazione moderna per Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisiti per Office 365 Advanced Threat Protection (ATP)

ATP può essere utilizzato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i browser Web e le lingue supportate da ATP, vedere le sezioni "Browser supportati" e "Lingue supportate" in [Interfaccia di amministrazione di Exchange in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilità delle funzionalità tra i piani di Advanced Threat Protection (ATP)

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.
  
|**Funzionalità**|**ATP piano 1**<br>(in precedenza ATP autonomo)|**ATP piano 2**<br>(in precedenza Threat Intelligence <br>standalone | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *Configurazione, protezione e rilevamento* | 
|Allegati sicuri |Sì|Sì |Sì|
|Collegamenti sicuri |Sì|Sì |Sì | 
|Criteri di anti-phishing |Sì |Sì |Sì |
|ATP per SharePoint, OneDrive e Microsoft Teams |Sì |Sì |Sì|
|Collegamenti sicuri nei team |Sì|Sì |Sì |
|Rapporti in tempo reale |Sì |Sì |Sì|
|*Automazione, indagine, correzione e formazione* |
|Tracker delle minacce |No |Sì |Sì |
|Explorer (Advanced Threat Investigation) |No |Sì |Sì |
|Analisi e risposta alle minacce automatizzate  |No |Sì |Sì |
|Simulatore di attacco |No |Sì |Sì |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funzionalità di Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Allegati sicuri

Gli [allegati sicuri di ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) proteggono da malware e virus sconosciuti e offrono una protezione zero-day per salvaguardare il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui ATP utilizza una varietà di tecniche di apprendimento e analisi dei computer per rilevare attacchi dannosi. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale. 

> [!NOTE]
> L'analisi degli allegati sicuri ATP si verifica nella stessa area in cui si trovano i dati di Office 365. Per ulteriori informazioni sulla geografia del Data Center, vedere [dove si trovano i dati?](https://products.office.com/where-is-your-data-located?geo=All) 

### <a name="safe-links"></a>Collegamenti sicuri

La funzionalità [ATP Safe Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) protegge in modo proattivo gli utenti da URL dannosi in un messaggio o in un documento di Office. La protezione rimane ogni volta che l'utente fa clic sul collegamento, in quanto i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.

### <a name="anti-phishing-policies"></a>Criteri di anti-phishing

Il [anti-phishing ATP](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) verifica i messaggi in arrivo per gli indicatori che un messaggio potrebbe essere un tentativo di phishing. Quando gli utenti sono coperti da criteri ATP (allegati sicuri, collegamenti sicuri o anti-phishing), i messaggi in arrivo vengono valutati da più modelli di apprendimento automatico che analizzano i messaggi e viene eseguita l'azione appropriata, in base ai criteri configurati.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[ATP per SharePoint, OneDrive e Microsoft teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) aiuta a rilevare e bloccare i file identificati come dannosi nei siti e nelle raccolte documenti del team.

### <a name="real-time-reports"></a>Rapporti in tempo reale

Le funzionalità di monitoraggio disponibili nel centro sicurezza & conformità di Office 365 includono [rapporti in tempo reale e approfondimenti](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) che consentono agli amministratori della sicurezza e della conformità di concentrarsi su problemi di elevata priorità, ad esempio gli attacchi alla sicurezza o l'aumento attività sospette. Oltre a evidenziare aree problematiche, Smart report e Insight includono suggerimenti e collegamenti per visualizzare ed esplorare i dati e per eseguire azioni rapide. 
  
### <a name="threat-trackers"></a>Tracker delle minacce

I Tracker di [minacce](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sono widget e visualizzazioni informativi che forniscono agli utenti autorizzati informazioni sui problemi di Cybersecurity che possono influire sull'organizzazione.

### <a name="explorer"></a>Explorer

[Gestione risorse](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (noto anche come Esplora minacce) è un report in tempo reale che consente agli utenti autorizzati di identificare e analizzare le minacce recenti. Per impostazione predefinita, questo report Visualizza i dati negli ultimi 7 giorni. Tuttavia, è possibile modificare le visualizzazioni per visualizzare i dati negli ultimi 30 giorni. 

### <a name="attack-simulator"></a>Simulatore di attacco
  
[Simulatore di attacco](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) consente agli utenti autorizzati di eseguire scenari di attacco realistici nell'organizzazione. Sono disponibili diversi tipi di attacchi, tra cui un attacco per il nome visualizzato Spear-phishing, un attacco spray per la password e un attacco per la password di forza bruta.