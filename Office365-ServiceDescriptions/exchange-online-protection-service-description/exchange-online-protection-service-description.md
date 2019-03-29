---
title: Descrizione del servizio Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. Viene fornito un elenco di piani che offrono Exchange Online Protection e un confronto tra le funzionalità dei vari piani.
ms.openlocfilehash: b90b480df4fb4116ab75f5d25428be86a9395ae0
ms.sourcegitcommit: de7d615d8967b1acc98a077337a0a2939c782481
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/29/2019
ms.locfileid: "30955765"
---
# <a name="exchange-online-protection-service-description"></a>Descrizione del servizio Exchange Online Protection

Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. Viene fornito un elenco di piani che offrono Exchange Online Protection e un confronto tra le funzionalità dei vari piani.
  
Microsoft Exchange Online Protection (EOP) è un servizio di filtro della posta elettronica che aiuta l'organizzazione a proteggersi da spam e malware e include funzionalità in grado di tutelare l'organizzazione dalle violazioni dei criteri di messaggistica. EOP è in grado di semplificare la gestione dell'ambiente di messaggistica e ridurre molte delle responsabilità associate alla gestione di componenti hardware e software locali.
  
Di seguito sono riportati i modi principali in cui è possibile utilizzare EOP per la protezione dei messaggi:
  
- **In uno scenario autonomo** EOP fornisce la protezione della posta elettronica basata sul cloud per l'ambiente di Exchange Server 2013 locale, le versioni legacy di Exchange Server o per qualsiasi altra soluzione di posta elettronica SMTP locale. 
    
- **Come componente di Microsoft Exchange Online** Per impostazione predefinita, EOP protegge le cassette postali ospitate sul cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere [Descrizione del servizio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).
    
- **In una distribuzione ibrida** EOP può essere configurato in modo da proteggere l'ambiente di messaggistica e controllare il routing della posta quando si utilizza una combinazione di cassette postali locali e basate sul cloud. 
    
Per un confronto tra le funzionalità offerte dai vari piani, vedere la pagina relativa al [confronto tra i piani di Office 365 for business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
Per acquistare Exchange Online Protection, vedere [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
È possibile esportare, salvare e stampare le pagine della descrizione del servizio Office 365. Ulteriori informazioni su come [esportare più pagine](https://go.microsoft.com/fwlink/?LinkId=403349).
  
> [!IMPORTANT]
> EOP sostituisce Forefront Online Protection for Exchange (FOPE). Tutti i clienti che utilizzano FOPE dovranno effettuare la transizione a EOP. EOP offre la protezione e il controllo di FOPE, insieme ad altre funzionalità. Per ulteriori informazioni sulla transizione da FOPE a EOP, vedere [Centro di transizione di Forefront Online Protection for Exchange (FOPE)](http://www.movetoeop.com). 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Novità di Exchange Online Protection (EOP)

Per informazioni sulle nuove funzionalità disponibili in EOP, vedere [Novità di Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=320390). Per un confronto tra le funzionalità disponibili in FOPE e in EOP, vedere [Confronto tra la funzionalità FOPE e EOP](https://go.microsoft.com/fwlink/p/?LinkId=320391).
  
## <a name="exchange-online-protection-eop-plans"></a>Piani di Exchange Online Protection (EOP)

EOP è disponibile attraverso i seguenti piani di sottoscrizione:
  
|**Piano**|**Descrizione**|
|:-----|:-----|
|[EOP autonomo](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |EOP protegge le cassette postali locali.  <br/> |
|[Funzionalità di EOP in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |EOP protegge le cassette postali ospitate sul cloud di Exchange Online.  <br/> |
|[Exchange Enterprise CAL with Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |EOP protegge le cassette postali locali, come nello scenario autonomo EOP e include funzionalità di prevenzione della perdita dei dati (DLP, Data Loss Prevention) e di creazione di report tramite servizi Web.  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Funzionalità di Exchange Enterprise CAL with Services

Microsoft Exchange Enterprise CAL with Services fornisce le funzionalità di protezione della posta elettronica di EOP per l'ambiente di messaggistica locale con in aggiunta le seguenti caratteristiche:
  
- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Reporting using web services](reporting-and-message-trace.md#reporting-using-web-services)
    
Per ulteriori informazioni sulle licenze Exchange Enterprise CAL with Services, vedere [Opzioni di licenza per Exchange Server 2013](https://go.microsoft.com/fwlink/p/?LinkId=293699).
  
Se si dispone di licenze Exchange Enterprise CAL with Services e si desidera effettuare il provisioning del servizio, attenersi alle istruzioni riportate in [Installazione del servizio EOP](https://go.microsoft.com/fwlink/p/?LinkId=320397). I passaggi di configurazione sono gli stessi dello scenario autonomo di EOP.
  
> [!NOTE]
> Nuove funzionalità per Exchange Enterprise CAL con servizi sono distribuite contemporaneamente come Exchange Online, non come EOP autonomo. Considerare che le pianificazioni di distribuzione per EOP autonomo e Exchange Online/Exchange Enterprise CAL con servizi possono essere leggermente differenti. 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Requisiti per Exchange Online Protection (EOP)

EOP può essere utilizzato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server 2013. Per informazioni sui sistemi operativi, i Web browser e le lingue supportati da EOP, vedere le sezioni "Browser supportati" e "Lingue supportate in EOP" nell'articolo [Interfaccia di amministrazione di Exchange in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="limits"></a>Limiti

Per i limiti in EOP, vedere [Limiti Exchange Online Protection](exchange-online-protection-limits.md).
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilità delle funzionalità tra i piani di Exchange Online Protection (EOP)

Di seguito sono elencate tutte le funzionalità. Per informazioni più dettagliate sulle funzionalità di EOP, fare clic sui collegamenti nella tabella. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.
  
|||||
|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**EOP autonomo** <br/> |**Funzionalità di EOP in Exchange Online** <br/> |**Exchange Enterprise CAL con servizi** <br/> |
|[destinatari posta](recipient-domain-and-company-management.md#mail-recipients) <br/> |Sì<sup>1</sup> <br/> |Sì<sup>1</sup> <br/> |Sì  <br/> |
|[Autorizzazioni del gruppo di ruolo Admin](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |Sì<sup>2</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Gestione del dominio](recipient-domain-and-company-management.md#domain-management) <br/> |Sì<sup>3</sup> <br/> |Sì<sup>3</sup> <br/> |Sì<sup>3</sup> <br/> |
|[Corrispondenza sottodomini](recipient-domain-and-company-management.md#match-subdomains) <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[DBEB (Directory Based Edge Blocking)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Regole di trasporto](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |Sì<sup>3, 4, 14</sup> <br/> |Sì<sup>3, 4, 14</sup> <br/> |Sì  <br/> |
|[Registrazione di controllo](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Sì<sup>5</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Prevenzione della perdita di dati (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |No  <br/> |Sì  <br/> |Sì<sup>6</sup> <br/> |
|[Crittografia dei messaggi di Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |Sì<sup>12</sup> <br/> |Sì  <br/> |Sì<sup>12</sup> <br/> |
|[Protezione dalla posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (incorporata)  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Personalizzazione dei criteri di protezione da posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |Sì<sup>7</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Protezione anti-malware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (incorporata)  <br/> |Sì<sup>13</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Personalizzare i criteri antimalware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): gestione dell'amministratore  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autogestione dell'utente finale  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Componente aggiuntivo di report di posta indesiderata di Microsoft Office Outlook](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Segnalazione della posta indesiderata in Outlook Web App](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Sì<sup>8</sup> <br/> |N.<sup>8</sup> <br/> |N.<sup>8</sup> <br/> |
|[Instradare la posta tra Office 365 e i server di posta elettronica della propria organizzazione](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Messaggistica sicura presso un partner di fiducia](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Elenco sicuro indirizzi IP del partner](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Routing condizionale della posta](mail-flow-eop.md#conditional-mail-routing) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Routing posta ibrida](mail-flow-eop.md#hybrid-mail-routing) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Rapporti dell'interfaccia di amministrazione di Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sì<sup>9</sup> <br/> |Sì<sup>10</sup> <br/> |Sì <sup>9, 10</sup> <br/> |
|[Rapporti applicazione download di Excel](reporting-and-message-trace.md#excel-download-application-reports) <br/> |Sì  <br/> |Sì  <br/> |Sì<sup>11</sup> <br/> |
|[Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services) <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |
|[Traccia dei messaggi](reporting-and-message-trace.md#message-trace) <br/> |Sì<sup>15</sup> <br/> |Sì<sup>15</sup> <br/> |Sì  <br/> |
|[Accesso all'interfaccia di amministrazione di Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Accesso all'interfaccia di amministrazione di Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center)  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Accesso a Windows PowerShell remoto](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |Sì<sup>2</sup> <br/> |Sì  <br/> |Sì  <br/> |
   
> [!NOTE]
> <sup>1</sup> Gli utenti di posta elettronica vengono definiti come "cassette postali" e, insieme ai contatti di posta elettronica esterni, possono essere aggiunti, rimossi e altrimenti gestiti direttamente nell'interfaccia di amministrazione di Exchange. 
 <br/><sup>2</sup> Non sono consentite personalizzazioni di Controllo degli accessi in base al ruolo, solo ruoli di amministratore. 3 È possibile visualizzare i domini gestiti e modificare i tipi di dominio nell'interfaccia di amministrazione di Exchange. 
 <br/> <sup>3</sup> i domini gestiti possono essere visualizzati e i tipi di dominio possono essere modificati nell'interfaccia di amministrazione di Exchange. Tutte le altre attività di gestione dei domini devono essere eseguite nell'interfaccia di amministrazione di Microsoft 365. 
 <br/><sup>4</sup> i criteri e le azioni flessibili disponibili sono diversi tra EOP e Exchange Online. Per un elenco dei criteri e delle azioni disponibili in Exchange Online, vedere [Criteri delle regole di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320392) e [Azioni delle regole di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320393). [](https://go.microsoft.com/fwlink/p/?LinkId=320394)[5](https://go.microsoft.com/fwlink/p/?LinkId=320395) I report di controllo di Exchange Online corrispondono a un sottoinsieme dei report di controllo di Exchange Online che non includono informazioni sulle cassette postali. 
 <br/><sup>6</sup> I suggerimenti relativi ai criteri DLP non sono disponibili per i clienti che dispongono di Exchange Enterprise CAL with Services. 
 <br/> <sup>7</sup> L'azione predefinita del filtro del contenuto prevede di spostare i messaggi di posta indesiderata nella cartella Posta indesiderata dei destinatari.  <br/><sup>7</sup> l'azione predefinita del filtro contenuto consiste nello spostare i messaggi di posta indesiderata nella cartella posta indesiderata dei destinatari. Per ulteriori informazioni, vedere Verifica del reindirizzamento della posta indesiderata nella cartella Posta indesiderata degli utenti. Per ulteriori informazioni, vedere Verificare che la posta indesiderata [venga instradata alla cartella posta indesiderata di ogni utente](https://go.microsoft.com/fwlink/p/?LinkId=320396). 
 <br/><sup>9</sup> I report di EOP corrispondono a un sottoinsieme dei report di Exchange Online che non includono informazioni sulle cassette postali. 
 <br/><sup>10</sup> Include report DLP.
 <br/><sup>10</sup> include report DLP. 
 <br/><sup>11</sup> i clienti di Exchange Enterprise CAL with Services devono installare la cartella di lavoro selezionando il servizio **Exchange Online** anziché il servizio **Exchange Online Protection** . 
 <br/><sup>12</sup> supportato per clienti locali che hanno acquistato Azure Information Protection e utilizzano Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. 
 <br/> <sup>14</sup> I predicati e le azioni disponibili in EOP e in Exchange Online sono diversi. 
 <br/><sup>15</sup> La configurazione ibrida non è disponibile tramite la procedura guidata ibrida. 
 <br/> <sup>15</sup> l'installazione ibrida non è disponibile tramite la procedura guidata ibrida, ma può essere configurata manualmente se si dispone di Exchange SP1. 