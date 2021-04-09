---
title: Descrizione del servizio Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. È incluso un elenco di piani che forniscono Exchange Online Protection, nonché un confronto delle funzionalità tra tali piani.
ms.openlocfilehash: 172e07db12590e51720c2446974418244f3234e4
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653038"
---
# <a name="exchange-online-protection-service-description"></a>Descrizione del servizio Exchange Online Protection

Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. È incluso un elenco di piani che forniscono Exchange Online Protection, nonché un confronto delle funzionalità tra tali piani.

Microsoft Exchange Online Protection (EOP) è un servizio di filtro della posta elettronica che aiuta l'organizzazione a proteggersi da spam e malware e include funzionalità in grado di tutelare l'organizzazione dalle violazioni dei criteri di messaggistica. EOP è in grado di semplificare la gestione dell'ambiente di messaggistica e ridurre molte delle responsabilità associate alla gestione di componenti hardware e software locali.

Nell'elenco seguente vengono descritti i principali modi in cui è possibile utilizzare EOP per la protezione della messaggistica:

- **In uno scenario** autonomo: EOP fornisce protezione della posta elettronica basata sul cloud per l'ambiente di posta elettronica locale (Exchange Server o altre soluzioni di posta elettronica SMTP locali).

- **Come parte di Microsoft Exchange Online:** per impostazione predefinita, EOP protegge le cassette postali ospitate sul cloud di Exchange Online. Per ulteriori informazioni su Exchange Online, vedere la [descrizione del servizio Exchange Online.](../exchange-online-service-description/exchange-online-service-description.md)

- **In una distribuzione ibrida:** EOP può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud.

## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Exchange Online Protection, vedere la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)

Per acquistare Exchange Online Protection, vedere [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP ha sostituito Forefront Online Protection for Exchange (FOPE). Il trasferimento da FOPE a EOP è stato eseguito per tutti i clienti.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Novità di Exchange Online Protection (EOP)

La [roadmap di Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) è una buona risorsa per trovare informazioni sulle nuove funzionalità future.

## <a name="exchange-online-protection-eop-plans"></a>Piani di Exchange Online Protection (EOP)

EOP è disponibile attraverso i seguenti piani di sottoscrizione:<br><br>

| Piano | Descrizione |
|:-----|:-----|
|[EOP autonomo](https://products.office.com/exchange/exchange-email-security-spam-protection)|Un servizio separato basato sul cloud che protegge l'organizzazione di posta elettronica locale.|
|[Funzionalità di EOP in Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Protezione incorporata per le cassette postali ospitate sul cloud di Exchange Online.|
|[Exchange Enterprise CAL con servizi](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Licenze dei componenti aggiuntivi acquistate per l'organizzazione exchange locale che includono EOP e altre funzionalità basate sul cloud (vedere la sezione successiva per informazioni dettagliate).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Funzionalità di Exchange Enterprise CAL with Services

Microsoft Exchange Enterprise CAL with Services offre le funzionalità di protezione della posta elettronica di EOP e le seguenti funzionalità aggiuntive basate sul cloud:

- [Prevenzione della perdita di dati (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services)

Per ulteriori informazioni sulla licenza Enterprise CAL with Services di Exchange, vedere [Domande frequenti sulle licenze di Exchange](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Se si dispone delle licenze Enterprise CAL with Services di Exchange e si desidera effettuare il provisioning di EOP, seguire le istruzioni in [Set up your EOP service](/microsoft-365/security/office-365-security/set-up-your-eop-service). I passaggi di configurazione sono gli stessi dello scenario autonomo di EOP.

> [!NOTE]
> Nuove funzionalità per Exchange Enterprise CAL con servizi sono distribuite contemporaneamente come Exchange Online, non come EOP autonomo. Considerare che le pianificazioni di distribuzione per EOP autonomo e Exchange Online/Exchange Enterprise CAL con servizi possono essere leggermente differenti.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisiti per Exchange Online Protection (EOP)

EOP può essere utilizzato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportati da EOP, vedere le sezioni "Browser supportati" e "Lingue supportate" nell'interfaccia di amministrazione di [Exchange in Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="limits"></a>Limiti

Per i limiti in EOP, vedere [Limiti di Exchange Online Protection](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilità delle funzionalità tra i piani di Exchange Online Protection (EOP)

Di seguito sono elencate tutte le funzionalità. Per informazioni più dettagliate sulle funzionalità di EOP, fare clic sui collegamenti nella tabella. Quando è menzionato Exchange Online, in genere si intende la famiglia di servizi di Office 365 Enterprise.<br><br>

| Funzionalità | EOP autonomo | Funzionalità di EOP in Exchange Online | Exchange Enterprise CAL con servizi|
|:-----|:-----|:-----|:-----|
|[destinatari posta](recipient-domain-and-company-management.md#mail-recipients)|Sì<sup>1</sup>|Sì<sup>1</sup>|Sì|
|[Autorizzazioni del gruppo di ruolo Admin](recipient-domain-and-company-management.md#admin-role-group-permissions)|Sì<sup>2</sup>|Sì|Sì|
|[Gestione del dominio](recipient-domain-and-company-management.md#domain-management)|Sì<sup>3</sup>|Sì<sup>3</sup>|Sì<sup>3</sup>|
|[Corrispondenza sottodomini](recipient-domain-and-company-management.md#match-subdomains)|Sì|Sì|No|
|[DBEB (Directory Based Edge Blocking)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Sì|Sì|Sì|
|[Regole del flusso di posta](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Sì<sup>4</sup>|Sì<sup>4, 6</sup>|Sì|
|[Registrazione di controllo](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Sì<sup>5</sup>|Sì|Sì|
|[Prevenzione della perdita di dati (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|No|Sì|Sì<sup>6</sup>|
|[Crittografia dei messaggi di Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Sì<sup>12</sup>|Sì|Sì<sup>12</sup>|
|[Protezione dalla posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (incorporata)|Sì|Sì|Sì|
|[Personalizzazione dei criteri di protezione da posta indesiderata](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Sì<sup>7</sup>|Sì|Sì|
|[Protezione anti-malware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (incorporata)|Sì<sup>13</sup>|Sì|Sì|
|[Personalizzare i criteri antimalware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Sì|Sì|Sì|
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): gestione dell'amministratore|Sì|Sì|Sì|
|[Quarantena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autogestione dell'utente finale|Sì|Sì|Sì|
|[Invio](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|No|Sì|No|
|[Componente aggiuntivo Segnala messaggio per Outlook](/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Sì|Sì|Sì|
|[Segnalazione della posta indesiderata in Outlook sul Web](/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Sì|Sì|Sì|
|[Routing della posta elettronica tra Microsoft e i propri server di posta elettronica](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Sì|Sì|Sì|
|[Messaggistica sicura presso un partner di fiducia](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Sì|Sì|Sì|
|[Elenco sicuro indirizzi IP del partner](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Sì|Sì|Sì|
|[Routing condizionale della posta](mail-flow-eop.md#conditional-mail-routing)|Sì|Sì|Sì|
|[Routing posta ibrida](mail-flow-eop.md#hybrid-mail-routing)|Sì|Sì|Sì|
|[Report dell'interfaccia di amministrazione di Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sì<sup>9</sup>|Sì<sup>10</sup>|Sì <sup>9, 10</sup>|
|[Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services)|No|Sì|Sì|
|[Traccia dei messaggi](reporting-and-message-trace.md#message-trace)|Sì<sup>15</sup>|Sì<sup>15</sup>|Sì|
|[Accesso all'interfaccia di amministrazione di Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Sì|Sì|Sì|
|[Accesso all'interfaccia di amministrazione di Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|Sì|Sì|Sì|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Sì|Sì|Sì|

<sup>1</sup> Gli utenti di posta elettronica vengono definiti come "cassette postali" e, insieme ai contatti di posta elettronica esterni, possono essere aggiunti, rimossi e altrimenti gestiti direttamente nell'interfaccia di amministrazione di Exchange. <br/>
<sup>2</sup> Non sono consentite personalizzazioni di Controllo degli accessi in base al ruolo, solo ruoli di amministratore. 3 È possibile visualizzare i domini gestiti e modificare i tipi di dominio nell'interfaccia di amministrazione di Exchange. <br/>
<sup>3</sup> I domini gestiti possono essere visualizzati e i tipi di dominio possono essere modificati nell'interfaccia di amministrazione di Exchange. Tutte le altre attività di gestione del dominio devono essere eseguite nell'interfaccia di amministrazione di Microsoft 365.<br/>
<sup>4</sup> Le regole del flusso di posta (note anche come regole di trasporto) in EOP sono descritte in [Mail flow rules (transport rules) in Exchange Online Protection.](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0) Le condizioni, le eccezioni e le azioni delle regole del flusso di posta disponibili sono leggermente diverse tra EOP ed Exchange Online. Queste differenze vengono notate nelle condizioni e nelle eccezioni delle regole del flusso di posta [(predicati) in Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) e nelle azioni delle regole del flusso di posta [in Exchange Online.](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)<br/>
<sup>6</sup> I suggerimenti relativi ai criteri DLP non sono disponibili per i clienti che dispongono di Exchange Enterprise CAL with Services. <br/>
<sup>7</sup> L'azione predefinita del filtro del contenuto prevede di spostare i messaggi di posta indesiderata nella cartella Posta indesiderata dei destinatari.  <br/>
<sup>7</sup> L'azione predefinita per il filtro del contenuto è lo spostamento dei messaggi di posta indesiderata nella cartella Posta indesiderata dei destinatari. Per utilizzare le cassette postali di Exchange locali, è inoltre necessario configurare due regole di trasporto nell'organizzazione exchange locale per rilevare le intestazioni di posta indesiderata aggiunte da EOP. Per ulteriori informazioni, vedere [Configure standalone EOP to deliver spam to the Junk Email folder in hybrid environments](/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>10</sup> Include report DLP.<br/>
<sup>10</sup> Include i report DLP. <br/>
<sup>12</sup> Supportato per i clienti locali che acquistano Azure Information Protection e usano Exchange Online Protection per instradare la posta elettronica tramite Exchange Online. <br/>
<sup>14</sup> I predicati e le azioni disponibili in EOP e in Exchange Online sono diversi. <br/>
<sup>15</sup> L'installazione ibrida non è disponibile tramite la procedura guidata ibrida, ma può essere impostata manualmente se si dispone di Exchange SP1.