---
title: Descrizione del servizio Office 365 Advanced Threat Protection
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/08/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) è il servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da virus e malware sconosciuti fornendo una protezione zero-day affidabile e include funzionalità di salvaguardia dell'organizzazione da collegamenti dannosi in tempo reale. ATP dispone di funzionalità di creazione report e traccia URL avanzate che consentono agli amministratori di analizzare i tipi di attacchi che si verificano nell'organizzazione.
ms.openlocfilehash: aeddc27c0275cb21ec257878e0978961356e7a85
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/11/2019
ms.locfileid: "29884197"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descrizione del servizio Office 365 Advanced Threat Protection

Microsoft Office 365 Advanced Threat Protection (ATP) è il servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da virus e malware sconosciuti fornendo una protezione zero-day affidabile e include funzionalità di salvaguardia dell'organizzazione da collegamenti dannosi in tempo reale. ATP dispone di funzionalità di creazione report e traccia URL avanzate che consentono agli amministratori di analizzare i tipi di attacchi che si verificano nell'organizzazione.
  
Di seguito sono i modi principali in strumenti di analisi è possibile utilizzare per la protezione dei messaggi:
  
- In uno scenario degli strumenti di analisi di Office 365 solo il filtro degli strumenti di analisi offre protezione della posta elettronica basata sul cloud per l'ambiente di Exchange Server locale o qualsiasi altra soluzione posta elettronica SMTP locale.
    
- Office 365 ATP può essere abilitato per proteggere le cassette postali ospitate nel cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- In una distribuzione ibrida, ATP può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si utilizza una combinazione di cassette postali locali e cloud in Exchange Online Protection per il filtro di posta elettronica in ingresso.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilità di Office 365 Advanced Threat Protection (ATP)

Degli strumenti di analisi è incluso in Office 365 Enterprise E5, A5 Education di Office 365 e Microsoft 365 Business. 
  
È possibile aggiungere ATP ai seguenti piani di abbonamento di Exchange e Office 365: 
  
- Exchange Online, piano 1
    
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
  
Per un confronto tra le funzionalità offerte dai vari piani, vedere la pagina relativa al [confronto tra i piani di Office 365 for business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Novità in Office 365 Advanced Threat Protection (ATP)

A partire da febbraio 2019 e distribuzione sui prossimi mesi, funzionalità di Business Intelligence di rischio vengono aggiunti degli strumenti di analisi. Inoltre, se l'organizzazione non dispone attualmente degli strumenti di analisi, sarà necessario nuove opzioni da prendere in considerazione, tra cui degli strumenti di analisi piano 1 e degli strumenti di analisi piano 2. Per ulteriori informazioni, vedere [i piani Office 365 avanzate Threat Protection e i prezzi](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content) e le [funzionalità disponibili nei piani avanzate Threat Protection (degli strumenti di analisi)](#feature-availability-across-advanced-threat-protection-atp-plans).

Per informazioni sulle nuove funzionalità in strumenti di analisi, vedere [nuove funzionalità disponibili in strumenti di analisi](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisiti per Office 365 Advanced Threat Protection (ATP)

ATP può essere utilizzato con qualsiasi agente di trasferimento posta SMTP, ad esempio Microsoft Exchange Server 2013. Per informazioni sui sistemi operativi, i browser Web e le lingue supportate da ATP, vedere le sezioni "Browser supportati" e "Lingue supportate" in [Interfaccia di amministrazione di Exchange in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilità delle funzionalità tra i piani di Advanced Threat Protection (ATP)

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.
  
|**Funzionalità**|**Degli strumenti di analisi piano 1**<br>(precedentemente degli strumenti di analisi autonomo)|**Degli strumenti di analisi piano 2**<br>(precedentemente rischio Business Intelligence <br>autonomo) | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *Configurazione, la protezione e il rilevamento* | 
|Allegati sicuri |Sì|Sì  |Sì |
|Collegamenti sicuri |Sì|Sì  |Sì  | 
|Criteri Anti-Phishing |Sì |Sì  |Sì  |
|Degli strumenti di analisi di SharePoint, OneDrive e team di Microsoft |Sì |Sì  |Sì |
|Collegamenti sicuri in team |Sì|Sì  |Sì  |
|Rapporti in tempo reale |Sì |Sì  |Sì |
|*Automazione, indagini, risoluzione dei problemi e formazione* |
|Rischio Tracker |No |Sì |Sì  |
|Explorer (avanzato indagini rischio) |No |Sì |Sì  |
|Risposta e indagini automatizzata  |No |Sì |Sì  |
|Simulatore di attacco |No |Sì |Sì  |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funzionalità di Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Allegati sicuri

[Gli allegati sicuri degli strumenti di analisi](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protegge da virus e malware sconosciuto e zero-day è assicurata per proteggere il sistema di messaggistica. Tutti i messaggi e allegati che non dispongono di una firma virus/il malware noto vengono instradati a un ambiente speciale cui degli strumenti di analisi utilizza una serie di tecniche di apprendimento e analisi dei computer per rilevare le finalità dannose. Se non viene rilevata alcuna attività sospetti, il messaggio viene rilasciato per il recapito della cassetta postale. 

### <a name="safe-links"></a>Collegamenti sicuri

La funzionalità [Degli strumenti di analisi collegamenti sicuri](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) attivamente impedisce agli utenti URL dannosi in un messaggio o in un documento di Office. La protezione rimane ogni volta la selezione del collegamento come collegamenti dannosi sono bloccati in modo dinamico durante una buona collegamenti è possibile accedere.

### <a name="anti-phishing-policies"></a>Criteri anti-phishing

[Protezione anti-phishing degli strumenti di analisi](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) verifica messaggi in arrivo per gli indicatori di un messaggio potrebbe essere un tentativo di phishing. Quando gli utenti vengono trattati i criteri degli strumenti di analisi (gli allegati sicuri, collegamenti attendibili o anti-phishing), i messaggi in arrivo vengono valutati in base al computer più modelli che analizza i messaggi di apprendimento e viene eseguita l'azione appropriata, in base ai criteri configurati.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP per SharePoint, OneDrive e Microsoft Teams

[Degli strumenti di analisi di SharePoint, OneDrive e team Microsoft che](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) consente di rilevare e bloccare i file che vengono identificati come dannose in siti del team e raccolte documenti.

### <a name="real-time-reports"></a>Rapporti in tempo reale

Monitoraggio delle funzionalità disponibili in Office 365 Security & centro conformità includono [sui concetti e i rapporti in tempo reale](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) che consentono agli amministratori di sicurezza e conformità esaminare i problemi di ad alta priorità, ad esempio gli attacchi di tipo o aumentata sospetti attività. Oltre alle aree di problemi di evidenziazione, sui concetti e i report smart includono elementi consigliati e i collegamenti per visualizzare ed esplorare i dati e inoltre eseguire azioni rapide. 
  
### <a name="threat-trackers"></a>Rischio Tracker

[Rischio Tracker](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sono widget informativi e le visualizzazioni che forniscono agli utenti autorizzati a intelligence sui problemi relativi alla sicurezza informatica che potrebbero influire nell'organizzazione.

### <a name="explorer"></a>esploratore

[Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (anche noto come Explorer rischio) è un report in tempo reale che consente agli utenti per identificare e analizzare le minacce recenti autorizzati. Per impostazione predefinita, questo report mostra i dati per gli ultimi 7 giorni; visualizzazioni, tuttavia, possono essere modificate per visualizzare i dati negli ultimi 30 giorni. 

### <a name="attack-simulator"></a>Simulatore di attacco
  
[Simulatore di attacco](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) consente agli utenti autorizzati a eseguire scenari di attacco realistica della propria organizzazione. Diversi tipi di attacchi sono disponibili, tra cui un attacco di phishing spear nome visualizzato, un attacco spray password e un attacco di forza bruta password.