---
title: Descrizione del servizio Office 365 Advanced Threat Protection
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 01/02/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) è il servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da virus e malware sconosciuti fornendo una protezione zero-day affidabile e include funzionalità di salvaguardia dell'organizzazione da collegamenti dannosi in tempo reale. ATP dispone di funzionalità di creazione report e traccia URL avanzate che consentono agli amministratori di analizzare i tipi di attacchi che si verificano nell'organizzazione.
ms.openlocfilehash: f8a44cdebebafe575f5c22a3a491671f57b05d49
ms.sourcegitcommit: d1d7309e864398e7d029956231cbaee054a2a0cf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/09/2019
ms.locfileid: "27784868"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descrizione del servizio Office 365 Advanced Threat Protection

Microsoft Office 365 Advanced Threat Protection (ATP) è il servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da virus e malware sconosciuti fornendo una protezione zero-day affidabile e include funzionalità di salvaguardia dell'organizzazione da collegamenti dannosi in tempo reale. ATP dispone di funzionalità di creazione report e traccia URL avanzate che consentono agli amministratori di analizzare i tipi di attacchi che si verificano nell'organizzazione.
  
Di seguito sono i modi principali in strumenti di analisi è possibile utilizzare per la protezione dei messaggi:
  
- In una situazione esclusivamente di filtro di Office 365 ATP, quest'ultimo fornisce la protezione della posta elettronica basata sul cloud per l'ambiente di Exchange Server 2013 locale, versioni legacy di Exchange Server o per qualsiasi altra soluzione di posta elettronica SMTP locale.
    
- Office 365 ATP può essere abilitato per proteggere le cassette postali ospitate nel cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description/exchange-online-service-description.md).
    
- In una distribuzione ibrida, ATP può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si utilizza una combinazione di cassette postali locali e cloud in Exchange Online Protection per il filtro di posta elettronica in ingresso.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilità di Office 365 Advanced Threat Protection (ATP)

Degli strumenti di analisi è incluso in Office 365 Enterprise E5, A5 Education di Office 365 e Microsoft 365 Business. 
  
> [!NOTE]
> Caratteristiche degli strumenti di analisi dipende dal client di Microsoft 365 Business è disponibile l'estate 2018. 
  
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
    
Per acquistare Office 365 Advanced Threat Protection, vedere [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Per un confronto tra le funzionalità offerte dai vari piani, vedere la pagina relativa al [confronto tra i piani di Office 365 for business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Novità in Office 365 Advanced Threat Protection (ATP)

Per informazioni sulle nuove funzionalità in strumenti di analisi, vedere [nuove funzionalità disponibili in strumenti di analisi](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisiti per Office 365 Advanced Threat Protection (ATP)

ATP può essere utilizzato con qualsiasi agente di trasferimento posta SMTP, ad esempio Microsoft Exchange Server 2013. Per informazioni sui sistemi operativi, i browser Web e le lingue supportate da ATP, vedere le sezioni "Browser supportati" e "Lingue supportate" in [Interfaccia di amministrazione di Exchange in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilità delle funzionalità tra i piani di Advanced Threat Protection (ATP)

Di seguito sono elencate tutte le funzionalità. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.
  
|**Funzionalità**|**ATP autonomo**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|Collegamenti sicuri  <br/> |Sì  <br/> |No  <br/> |
|Allegati sicuri  <br/> |Sì  <br/> |No  <br/> |
|Intelligence per lo spoofing  <br/> |Sì  <br/> |No  <br/> |
|Quarantena  <br/> |Sì  <br/> |Sì  <br/> |
|Funzionalità avanzate di anti-phishing  <br/> |Sì  <br/> |No  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funzionalità di Advanced Threat Protection (ATP)

### <a name="safe-links"></a>Collegamenti sicuri

La funzionalità Collegamenti sicuri di ATP protegge gli utenti in modo proattivo da collegamenti ipertestuali dannosi in un messaggio. La protezione rimane ogni volta che l'utente fa clic sul collegamento, in quanto i collegamenti dannosi vengono bloccati in modo dinamico mentre i collegamenti corretti continuano ad essere accessibili.
  
### <a name="safe-attachments"></a>Allegati sicuri

La funzionalità Allegati sicuri protegge da virus e malware sconosciuti e fornisce la protezione zero-day per salvaguardare il sistema di messaggistica. Tutti i messaggi e gli allegati che non dispongono di una firma virus/malware nota vengono instradati a un ambiente speciale in cui ATP utilizza una varietà di tecniche di apprendimento e analisi dei computer per rilevare attacchi dannosi. Se non viene rilevata alcuna attività sospetta, il messaggio viene rilasciato per il recapito alla cassetta postale. 
  
### <a name="spoof-intelligence"></a>Intelligence per lo spoofing

Business intelligence spoofing rileva quando viene visualizzato un mittente per l'invio della posta per conto di uno o più account utente all'interno di uno dei domini dell'organizzazione. Consente di esaminare tutti i mittenti che sono lo spoofing del dominio e quindi scegliere di consentire al mittente di continuare o bloccare il mittente. Business intelligence di spoofing è disponibile in sicurezza &amp; centro conformità della pagina Impostazioni di protezione da posta indesiderata.
  
### <a name="quarantine"></a>Quarantena

I messaggi identificati dal servizio di Office 365 come posta indesiderata, posta inviata in massa, phishing, che contengono malware o corrispondono a una regola del flusso di posta, possono essere messi in quarantena. Per impostazione predefinita, Office 365 invia i messaggi di phishing e i messaggi contenenti malware direttamente in quarantena. Gli utenti autorizzati possono esaminare, eliminare o gestire i messaggi di posta elettronica inviati in quarantena.
  
### <a name="advanced-anti-phishing-capabilities"></a>Funzionalità avanzate di anti-phishing

Questa funzionalità consente di utilizzare i modelli di apprendimento automatico per rilevare i messaggi di phishing. 
  
