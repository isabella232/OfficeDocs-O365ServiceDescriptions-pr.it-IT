---
title: Descrizione del servizio Exchange Online Protection
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: 6e7ffd6a2248acfc763a71e35ce0daba0f9b0308
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036058"
---
# <a name="exchange-online-protection-service-description"></a>Descrizione del servizio Exchange Online Protection

Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. Viene fornito un elenco di piani che offrono Exchange Online Protection e un confronto tra le funzionalità dei vari piani.
  
Microsoft Exchange Online Protection (EOP) è un servizio di filtro della posta elettronica che aiuta l'organizzazione a proteggersi da spam e malware e include funzionalità in grado di tutelare l'organizzazione dalle violazioni dei criteri di messaggistica. EOP è in grado di semplificare la gestione dell'ambiente di messaggistica e ridurre molte delle responsabilità associate alla gestione di componenti hardware e software locali.
  
Di seguito sono riportati i modi principali in cui è possibile utilizzare EOP per la protezione dei messaggi:
  
- **In uno scenario autonomo** EOP offre protezione della posta elettronica basata sul cloud per l'ambiente di Exchange Server 2013 locale, versioni di Exchange Server legacy o per qualsiasi altro locale soluzione di posta elettronica SMTP. 
    
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
  
- [Prevenzione della perdita di dati (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services)
    
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
|[Autorizzazioni del gruppo di ruolo Admin](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |Yes<sup>2</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Gestione del dominio](recipient-domain-and-company-management.md#domain-management) <br/> |Yes<sup>3</sup> <br/> |Yes<sup>3</sup> <br/> |Yes<sup>3</sup> <br/> |
|[Corrispondenza sottodomini](recipient-domain-and-company-management.md#match-subdomains) <br/> |Sì  <br/> |Sì  <br/> |No  <br/> |
|[DBEB (Directory Based Edge Blocking)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Regole di trasporto](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |Sì<sup>3, 4, 14</sup> <br/> |Sì<sup>3, 4, 14</sup> <br/> |Sì  <br/> |
|[Registrazione di controllo](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Yes<sup>5</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Prevenzione della perdita di dati (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |No  <br/> |Sì  <br/> |Yes<sup>6</sup> <br/> |
|[Crittografia dei messaggi di Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |Yes<sup>12</sup> <br/> |Sì  <br/> |Yes<sup>12</sup> <br/> |
|[Protezione dalla posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (incorporata)  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Personalizzazione dei criteri di protezione da posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |Sì<sup>7</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Protezione anti-malware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (incorporata)  <br/> |Yes<sup>13</sup> <br/> |Sì  <br/> |Sì  <br/> |
|[Personalizzare i criteri antimalware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): gestione dell'amministratore  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autogestione dell'utente finale  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Componente aggiuntivo di report di posta indesiderata di Microsoft Office Outlook](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Segnalazione della posta indesiderata in Outlook Web App](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Yes<sup>8</sup> <br/> |Nessun<sup>8</sup> <br/> |Nessun<sup>8</sup> <br/> |
|[Instradare la posta tra Office 365 e i server di posta elettronica della propria organizzazione](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Messaggistica sicura presso un partner di fiducia](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Elenco sicuro indirizzi IP del partner](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Routing condizionale della posta](mail-flow-eop.md#conditional-mail-routing) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Routing posta ibrida](mail-flow-eop.md#hybrid-mail-routing) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Rapporti dell'interfaccia di amministrazione di Office 365](reporting-and-message-trace.md#office-365-admin-center-reports) <br/> |Yes<sup>9</sup> <br/> |Yes<sup>10</sup> <br/> |Sì <sup>9, 10</sup> <br/> |
|[Rapporti applicazione download di Excel](reporting-and-message-trace.md#excel-download-application-reports) <br/> |Sì  <br/> |Sì  <br/> |Yes<sup>11</sup> <br/> |
|[Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services) <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |
|[Traccia dei messaggi](reporting-and-message-trace.md#message-trace) <br/> |Yes<sup>15</sup> <br/> |Yes<sup>15</sup> <br/> |Sì  <br/> |
|[Accesso all'interfaccia di amministrazione di Office 365](administration-and-management-eop.md#access-to-the-office-365-admin-center) <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Accesso all'interfaccia di amministrazione di Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center)  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|[Accesso a Windows PowerShell remoto](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |Yes<sup>2</sup> <br/> |Sì  <br/> |Sì  <br/> |
   
> [!NOTE]
> <sup>1</sup> posta elettronica agli utenti vengono definiti come "Cassette postali" e, insieme ai contatti di posta esterni, possono essere aggiunti, rimossi e altrimenti gestiti direttamente nell'interfaccia di amministrazione di Exchange (EAC). <br/>Personalizzazione No RBAC <sup>2</sup> . Solo ruoli di amministratore. <br/> <sup>3</sup> domini gestiti possono essere visualizzati e tipi di dominio possono essere modificati in EAC. Tutti gli altri gestione del dominio deve essere eseguita nell'interfaccia di amministrazione di Office 365. <br/><sup>4</sup> criteri flessibili disponibili e le azioni sono diverse EOP ed Exchange Online. Per un elenco dei criteri disponibili e le azioni in EOP, vedere [Criteri della regola di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320392) e [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393). Per un elenco dei criteri disponibili e le azioni in Exchange Online, vedere [Criteri della regola di trasporto](https://go.microsoft.com/fwlink/p/?LinkId=320394) e [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395). <br/><sup>5</sup> rapporti di controllo di EOP sono un sottoinsieme dei report di controllo Exchange Online che non includono informazioni sulle cassette postali. <br/> <sup>7</sup> L'azione predefinita del filtro del contenuto prevede di spostare i messaggi di posta indesiderata nella cartella Posta indesiderata dei destinatari.<br/><sup>7</sup> l'azione del filtro contenuto predefinito è per spostare messaggi di posta indesiderata nella cartella posta indesiderata per i destinatari. Per il funzionamento con cassette postali locali, è inoltre necessario configurare due regole di trasporto di Exchange sui server locali per rilevare le intestazioni di posta indesiderata aggiunte da EOP. Per ulteriori informazioni, vedere [verificare che la posta indesiderata sia instradata alla cartella posta indesiderata dell'utente ogni](https://go.microsoft.com/fwlink/p/?LinkId=320396). <br/><sup>8</sup> questa funzionalità è disponibile per i clienti di Exchange Server 2013 Service Pack 1 (SP1) le cui cassette postali vengono filtrate da EOP e saranno presto disponibile per i clienti di Exchange Online. <br/><sup>9</sup> i report di EOP sono un sottoinsieme dei report di Exchange Online che non includono informazioni sulle cassette postali. <br/>Rapporti DLP include <sup>10</sup> . <br/><sup>11</sup> Exchange Enterprise CAL con i clienti Services devono installare la cartella di lavoro selezionando il servizio **Exchange Online** anziché il servizio **Exchange Online Protection** . <br/><sup>12</sup> supportato per clienti locali che hanno acquistato Azure Information Protection e utilizzare Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. <br/> <sup>13</sup> analizza i messaggi in ingresso e in uscita, ma non analizza i messaggi inviati da un mittente all'interno dell'organizzazione a un destinatario nella propria organizzazione. <br/><sup>14</sup> i predicati disponibili e le azioni sono diverse EOP ed Exchange Online. <br/> <sup>15</sup> Configurazione ibrida non è disponibile con procedura guidata ibrida, ma è possibile configurare manualmente se si dispone di Exchange SP1. 