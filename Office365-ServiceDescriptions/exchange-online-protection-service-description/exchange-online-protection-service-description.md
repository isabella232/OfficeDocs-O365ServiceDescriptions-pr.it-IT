---
title: Descrizione del servizio Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. È incluso un elenco di piani che forniscono Exchange Online Protection, oltre a un confronto tra le caratteristiche di tali piani.
ms.openlocfilehash: 3a52d682c4aa181c549e3e2d96ea8645ccae6260
ms.sourcegitcommit: 1a212a9f9c8d28090bc0b7c6e20e76d1353dad2e
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/13/2020
ms.locfileid: "44213978"
---
# <a name="exchange-online-protection-service-description"></a>Descrizione del servizio Exchange Online Protection

Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. È incluso un elenco di piani che forniscono Exchange Online Protection, oltre a un confronto tra le caratteristiche di tali piani.

Microsoft Exchange Online Protection (EOP) è un servizio di filtro della posta elettronica che aiuta l'organizzazione a proteggersi da spam e malware e include funzionalità in grado di tutelare l'organizzazione dalle violazioni dei criteri di messaggistica. EOP è in grado di semplificare la gestione dell'ambiente di messaggistica e ridurre molte delle responsabilità associate alla gestione di componenti hardware e software locali.

Nell'elenco seguente vengono illustrati i modi principali in cui è possibile utilizzare EOP per la protezione della messaggistica:

- **In uno scenario autonomo**: EOP fornisce la protezione della posta elettronica basata sul cloud per l'ambiente di posta elettronica locale (Exchange Server o altre soluzioni di posta elettronica SMTP locali).

- **Come parte di Microsoft Exchange Online**: per impostazione predefinita, EOP protegge le cassette postali ospitate sul cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere la [Descrizione del servizio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).

- **In una distribuzione ibrida**: EOP può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud.

Per confrontare le funzionalità tra i piani, vedere [strumenti potenti per supportare l'organizzazione](https://products.office.com/business/compare-more-office-365-for-business-plans).

Per acquistare Exchange Online Protection, vedere [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP ha sostituito Forefront Online Protection for Exchange (FOPE). Il trasferimento da FOPE a EOP è stato eseguito per tutti i clienti.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Novità di Exchange Online Protection (EOP)

La [Roadmap di Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) è una buona risorsa per trovare informazioni sulle nuove funzionalità imminenti.

## <a name="exchange-online-protection-eop-plans"></a>Piani di Exchange Online Protection (EOP)

EOP è disponibile attraverso i seguenti piani di sottoscrizione:

|**Piano**|**Descrizione**|
|:-----|:-----|
|[EOP autonomo](https://products.office.com/exchange/exchange-email-security-spam-protection)|Servizio separato basato sul cloud che protegge l'organizzazione di posta elettronica locale.|
|[Funzionalità di EOP in Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Protezione integrata per le cassette postali ospitate sul cloud di Exchange Online.|
|[Exchange Enterprise CAL con servizi](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Licenze per i componenti aggiuntivi acquistati per l'organizzazione di Exchange locale che includono EOP e altre funzionalità basate su cloud (vedere la sezione successiva per i dettagli).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Funzionalità di Exchange Enterprise CAL with Services

Microsoft Exchange Enterprise CAL with Services fornisce le funzionalità di protezione della posta elettronica di EOP e le seguenti funzionalità aggiuntive basate su cloud:

- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services)

Per ulteriori informazioni sulle licenze di Exchange Enterprise CAL con servizi, vedere [domande frequenti sulla gestione delle licenze](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)di Exchange.

Se si dispone di licenze di Exchange Enterprise CAL con servizi e si desidera eseguire il provisioning di EOP, seguire le istruzioni riportate in [set up your EOP Service](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service). I passaggi di configurazione sono gli stessi dello scenario autonomo di EOP.

> [!NOTE]
> Nuove funzionalità per Exchange Enterprise CAL con servizi sono distribuite contemporaneamente come Exchange Online, non come EOP autonomo. Considerare che le pianificazioni di distribuzione per EOP autonomo e Exchange Online/Exchange Enterprise CAL con servizi possono essere leggermente differenti.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisiti per Exchange Online Protection (EOP)

EOP può essere utilizzato con qualsiasi agente di trasferimento posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportate da EOP, vedere le sezioni "browser supportati" e "lingue supportate" nell'interfaccia di [amministrazione di Exchange in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Limiti

Per i limiti in EOP, vedere [limiti di Exchange Online Protection](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilità delle funzionalità tra i piani di Exchange Online Protection (EOP)

Di seguito sono elencate tutte le funzionalità. Per informazioni più dettagliate sulle funzionalità di EOP, fare clic sui collegamenti nella tabella. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.

|||||
|:-----|:-----|:-----|:-----|
|**Funzionalità**|**EOP autonomo**|**Funzionalità di EOP in <br/> Exchange Online**|**Exchange Enterprise <br/> CAL con servizi**|
|[destinatari posta](recipient-domain-and-company-management.md#mail-recipients)|Sì<sup>1</sup>|Sì<sup>1</sup>|Sì|
|[Autorizzazioni del gruppo di ruolo Admin](recipient-domain-and-company-management.md#admin-role-group-permissions)|Sì<sup>2</sup>|Sì|Sì|
|[Gestione del dominio](recipient-domain-and-company-management.md#domain-management)|Sì<sup>3</sup>|Sì<sup>3</sup>|Sì<sup>3</sup>|
|[Corrispondenza sottodomini](recipient-domain-and-company-management.md#match-subdomains)|Sì|Sì|No|
|[DBEB (Directory Based Edge Blocking)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Sì|Sì|Sì|
|[Regole dei flussi di posta](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Sì<sup>4</sup>|Sì<sup>4, 6</sup>|Sì|
|[Registrazione di controllo](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Sì<sup>5</sup>|Sì|Sì|
|[Prevenzione della perdita di dati (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|No|Sì|Sì<sup>6</sup>|
|[Crittografia dei messaggi di Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Sì<sup>12</sup>|Sì|Sì<sup>12</sup>|
|[Protezione dalla posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (incorporata)|Sì|Sì|Sì|
|[Personalizzazione dei criteri di protezione da posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Sì<sup>7</sup>|Sì|Sì|
|[Protezione anti-malware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (incorporata)|Sì<sup>13</sup>|Sì|Sì|
|[Personalizzare i criteri antimalware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Sì|Sì|Sì|
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): gestione dell'amministratore|Sì|Sì|Sì|
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autogestione dell'utente finale|Sì|Sì|Sì|
|[Componente aggiuntivo per i messaggi di report per Outlook](anti-spam-and-anti-malware-protection-eop.md#report-message-add-in-for-outlook)|Sì|Sì|Sì|
|[Report di posta indesiderata in Outlook sul Web](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-on-the-web)|Sì|Sì|Sì|
|[Routing della posta elettronica tra Microsoft e i server di posta elettronica personali](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Sì|Sì|Sì|
|[Messaggistica sicura presso un partner di fiducia](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Sì|Sì|Sì|
|[Elenco sicuro indirizzi IP del partner](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Sì|Sì|Sì|
|[Routing condizionale della posta](mail-flow-eop.md#conditional-mail-routing)|Sì|Sì|Sì|
|[Routing posta ibrida](mail-flow-eop.md#hybrid-mail-routing)|Sì|Sì|Sì|
|[Rapporti dell'interfaccia di amministrazione di Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sì<sup>9</sup>|Sì<sup>10</sup>|Sì <sup>9, 10</sup>|
|[Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services)|No|Sì|Sì|
|[Traccia dei messaggi](reporting-and-message-trace.md#message-trace)|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì|
|[Accesso all'interfaccia di amministrazione di Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Sì|Sì|Sì|
|[Accesso all'interfaccia di amministrazione di Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|Sì|Sì|Sì|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Sì|Sì|Sì|

<sup>1</sup> Gli utenti di posta elettronica vengono definiti come "cassette postali" e, insieme ai contatti di posta elettronica esterni, possono essere aggiunti, rimossi e altrimenti gestiti direttamente nell'interfaccia di amministrazione di Exchange. <br/>
<sup>2</sup> Non sono consentite personalizzazioni di Controllo degli accessi in base al ruolo, solo ruoli di amministratore. 3 È possibile visualizzare i domini gestiti e modificare i tipi di dominio nell'interfaccia di amministrazione di Exchange. <br/>
<sup>3</sup> i domini gestiti possono essere visualizzati e i tipi di dominio possono essere modificati nell'interfaccia di amministrazione di Exchange. Tutte le altre attività di gestione dei domini devono essere eseguite nell'interfaccia di amministrazione di Microsoft 365.<br/>
<sup>4</sup> le regole del flusso di posta (note anche come regole di trasporto) in EOP sono descritte in [regole del flusso di posta (regole di trasporto) in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0). Le condizioni, le eccezioni e le azioni delle regole del flusso di posta disponibili differiscono leggermente tra EOP e Exchange Online. Queste differenze sono indicate nelle [condizioni ed eccezioni (predicati) delle regole del flusso di posta in](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) Exchange Online e le [azioni delle regole del flusso di posta in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).<br/>
<sup>6</sup> I suggerimenti relativi ai criteri DLP non sono disponibili per i clienti che dispongono di Exchange Enterprise CAL with Services. <br/>
<sup>7</sup> L'azione predefinita del filtro del contenuto prevede di spostare i messaggi di posta indesiderata nella cartella Posta indesiderata dei destinatari.  <br/>
<sup>7</sup> l'azione predefinita del filtro contenuto consiste nello spostare i messaggi di posta indesiderata nella cartella posta indesiderata dei destinatari. Affinché ciò funzioni con le cassette postali di Exchange locali, è inoltre necessario configurare due regole di trasporto nell'organizzazione di Exchange locale per rilevare le intestazioni di posta indesiderata aggiunte da EOP. Per ulteriori informazioni, vedere [Configure standalone EOP per recapitare la posta indesiderata nella cartella posta indesiderata in ambienti ibridi](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>10</sup> Include report DLP.<br/>
<sup>10</sup> include report DLP. <br/>
<sup>12</sup> supportato per clienti locali che hanno acquistato Azure Information Protection e utilizzano Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. <br/>
<sup>14</sup> I predicati e le azioni disponibili in EOP e in Exchange Online sono diversi. <br/>
<sup>15</sup> l'installazione ibrida non è disponibile tramite la procedura guidata ibrida, ma può essere configurata manualmente se si dispone di Exchange SP1.
