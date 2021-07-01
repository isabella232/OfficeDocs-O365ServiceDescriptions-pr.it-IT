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
description: Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. È incluso un elenco di piani che forniscono Exchange Online Protection, nonché un confronto delle funzionalità di tali piani.
ms.openlocfilehash: fbfbe39931e6037b358bb76c124937904a408783
ms.sourcegitcommit: 427dbb27426a12e8c5dba7d8b4cbaf2bedb3aaba
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/30/2021
ms.locfileid: "53222483"
---
# <a name="exchange-online-protection-service-description"></a>Descrizione del servizio Exchange Online Protection

Sono disponibili informazioni sulle funzionalità e sui requisiti per Exchange Online Protection. È incluso un elenco di piani che forniscono Exchange Online Protection, nonché un confronto delle funzionalità di tali piani.

Microsoft Exchange Online Protection (EOP) è un servizio di filtro della posta elettronica basato su cloud che consente di proteggere l'organizzazione da posta indesiderata e malware e include funzionalità per proteggere l'organizzazione dalle violazioni dei criteri di messaggistica. EOP può semplificare la gestione dell'ambiente di messaggistica e ridurre molte delle responsabilità associate alla gestione di componenti hardware e software locali.

Nell'elenco seguente vengono descritti i principali modi in cui è possibile utilizzare EOP per la protezione della messaggistica:

- **In uno scenario** autonomo: EOP fornisce protezione della posta elettronica basata sul cloud per l'ambiente di posta elettronica locale (Exchange Server o altre soluzioni di posta elettronica SMTP locali).

- **Come parte di Microsoft Exchange Online:** per impostazione predefinita, EOP protegge Exchange Online cassette postali ospitate nel cloud. Per ulteriori informazioni sulle Exchange Online, vedere la [descrizione Exchange Online servizio.](../exchange-online-service-description/exchange-online-service-description.md)

- **In una distribuzione ibrida:** EOP può essere configurato per proteggere l'ambiente di messaggistica e controllare il routing della posta quando si dispone di una combinazione di cassette postali locali e cloud.

## <a name="available-plans"></a>Piani disponibili

La tabella seguente mostra i piani che includono Exchange Online Protection in modo da poter scegliere la soluzione più adatta alle esigenze dell'organizzazione. Per informazioni dettagliate sul piano, [vedere Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Exchange Online Protection, vedere la tabella di confronto [completa delle sottoscrizioni.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)

### <a name="exchange-enterprise-cal-with-services-features"></a>Funzionalità di Exchange Enterprise CAL with Services

Microsoft Exchange Enterprise CAL with Services offre le funzionalità di protezione della posta elettronica di EOP e le seguenti funzionalità aggiuntive basate sul cloud:

- [Prevenzione della perdita dei dati](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Creazione di report tramite i servizi Web](reporting-and-message-trace.md#reporting-using-web-services)

Per ulteriori informazioni sulla licenza CAL Exchange Enterprise servizi, vedere domande Exchange [domande frequenti sulle licenze.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Se si dispone Exchange Enterprise licenze CAL con servizi e si desidera effettuare il provisioning di EOP, seguire le istruzioni in [Configurare il servizio EOP.](/microsoft-365/security/office-365-security/set-up-your-eop-service) I passaggi di configurazione sono gli stessi dello scenario autonomo di EOP.

> [!NOTE]
> Nuove funzionalità per Exchange Enterprise CAL con servizi sono distribuite contemporaneamente come Exchange Online, non come EOP autonomo. Considerare che le pianificazioni di distribuzione per EOP autonomo e Exchange Online/Exchange Enterprise CAL con servizi possono essere leggermente differenti.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisiti per Exchange Online Protection (EOP)

EOP può essere utilizzato con qualsiasi agente di trasferimento della posta SMTP, ad esempio Microsoft Exchange Server. Per informazioni sui sistemi operativi, i Web browser e le lingue supportati da EOP, vedere le sezioni "Browser supportati" e "Lingue supportate" nell'interfaccia di amministrazione di [Exchange in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Limiti

Per i limiti in EOP, vedere [Exchange Online Protection limiti](exchange-online-protection-limits.md).

## <a name="feature-availability"></a>Disponibilità delle funzionalità

Nella tabella seguente sono elencate le principali Exchange Online Protection disponibili tra i piani. Si applicano alcune avvertenze. Per ulteriori informazioni, vedere le note a piè di pagina. Questa tabella può cambiare senza preavviso. Per l'elenco completo e aggiornato delle funzionalità, vedere [Potenti strumenti per supportare l'azienda.](https://products.office.com/business/compare-more-office-365-for-business-plans)

| Funzionalità | EOP autonomo | EOP in edizione Enterprise CAL w/ Services | Funzionalità di EOP in Exchange Online |
|:-----|:-----|:-----|:-----|
|**Protezione**||||
|Criteri antimalware (incorporati e personalizzati)|Sì|Sì|Sì|
|Criteri di protezione da posta indesiderata in ingresso (incorporati e personalizzati)|Sì|Sì|Sì|
|Criteri di protezione da posta indesiderata in uscita (incorporati e personalizzati)|Sì|Sì|Sì|
|Filtro connessioni (elenco indirizzi IP consentiti ed elenco indirizzi IP non consentiti)|Sì|Sì|Sì|
|Criteri anti-phishing (predefiniti e personalizzati)|Sì|Sì|Sì|
|Protezione anti-spoofing (incorporata e personalizzata)|Sì|Sì|Sì|
|Eliminazione automatica a zero ore (ZAP) per i messaggi di malware, posta indesiderata e phishing recapitati<sup>10</sup>|No|No|Sì|
|Preimpostare i criteri di sicurezza.|Sì|Sì|Sì|
|Analizzatore della configurazione per i criteri di protezione|Sì|Sì|Sì|
|Elenco tenant consentiti/bloccati|Sì|Sì|Sì|
|Elenchi di indirizzi bloccati per i mittenti dei messaggi|Sì|Sì|Sì|
|Consenti elenchi per i mittenti dei messaggi|Sì|Sì|Sì|
|Blocco edge|Sì|Sì|Sì|
|Directory Based Edge Blocking (DBEB) per destinatari inesistenti|Sì|Sì|Sì|
|**Quarantena e invii**||||
|Invio<sup>dell'amministratore 10</sup>|No|No|Sì|
|Invio utente (cassetta postale personalizzata)<sup>10</sup>|No|No|Sì|
|Quarantena dell'amministratore|Sì|Sì|Sì|
|Quarantena degli utenti finali|Sì|Sì|Sì|
|Componente aggiuntivo Segnala messaggio e Segnala phishing per Outlook|Sì|Sì|Sì|
|**Flusso di posta**||||
|Regole del flusso di posta (regole di trasporto)<sup>4</sup>|Sì|Sì<sup>6</sup>|Sì|
|Domini<sup>accettati 3</sup> |Sì|Sì|Sì|
|Connettori|Sì|Sì|Sì|
|Filtro avanzato per i connettori (ignora elenco)|Sì|Sì|Sì|
|**Monitoraggio**||||
|Message trace|Sì|Sì|Sì|
|Report di posta elettronica e sicurezza nella interfaccia di amministrazione di Microsoft 365|Sì<sup>7</sup>|Sì<sup>7,8</sup>|Sì<sup>8</sup>|
|Report di sicurezza nel Centro sicurezza Microsoft 365 sicurezza|Sì<sup>7</sup>|Sì<sup>7,8</sup>|Sì<sup>8</sup>|
|Rapporti di posta elettronica nell'interfaccia di amministrazione di Exchange|Sì<sup>7</sup>|Sì<sup>7,8</sup>|Sì<sup>8</sup>|
|Registrazione di controllo<sup>dell'amministratore 5</sup>|Sì|Sì|Sì|
|**Utenti**||||
|Utenti di posta e contatti di posta<sup>1</sup>|Sì|Sì|Sì|
|Cassette postali|No|No|Sì<sup>1a</sup>|
|Controllo dell'accesso basato sui ruoli (RBAC)<sup>2</sup>|Sì|Sì|Sì|
|**Conformità**||||
|Prevenzione della perdita di dati per la posta elettronica|No|Sì|Sì|
|Crittografia dei messaggi di Office 365|No<sup>9</sup>|No<sup>9</sup>|Sì|
|**Amministrazione**||||
|Interfaccia di amministrazione di Microsoft 365|Sì|Sì|Sì|
|Interfaccia di amministrazione di Exchange|Sì|Sì|Sì|
|Centro sicurezza Microsoft 365|Sì|Sì|Sì|
|PowerShell Exchange Online Protection autonomo|Sì|No|No|
|Exchange Online PowerShell|No|Sì|Sì|

<sup>1</sup> Creare, rimuovere e modificare utenti di posta e contatti di posta nell'interfaccia di amministrazione di Exchange. <br/>
<sup>1a</sup> Si creano e rimuovono cassette postali nel interfaccia di amministrazione di Microsoft 365. È possibile modificare le cassette postali esistenti nell'interfaccia di amministrazione di Exchange. <br/>
<sup>2</sup> In EOP autonomo e edizione Enterprise cal con servizi, non sono disponibili ruoli dell'utente finale o criteri di assegnazione dei ruoli.<br/>
<sup>3</sup> Aggiungere e rimuovere domini nella interfaccia di amministrazione di Microsoft 365.  Nell'interfaccia di amministrazione di Exchange, configurare i domini come autorevoli o non autorevoli.<br/>
<sup>4</sup> Alcune condizioni, eccezioni e azioni delle regole non sono disponibili in EOP autonomo o in EOP in edizione Enterprise CAL con servizi. Queste differenze sono chiaramente notate nel contenuto Exchange Online delle regole del flusso di posta. <br/>
<sup>5</sup> In EOP autonomo e edizione Enterprise cal con servizi:

- I report di controllo delle cassette postali non sono disponibili.
- Il report del gruppo di ruoli Amministratore e il report del log di controllo dell'amministratore sono gli unici rapporti di controllo dell'amministratore nell'interfaccia di amministrazione di Exchange.
- Esportazione del log di controllo disponibile solo tramite PowerShell. <br/>

<sup>6</sup> I suggerimenti per i criteri DLP non sono disponibili in edizione Enterprise cal with Services. <br/>
<sup>7</sup> I report in EOP autonomo e edizione Enterprise CAL con servizi sono un sottoinsieme di Exchange Online report (report che si occupano delle cassette postali).<br/>
<sup>8</sup> Include report DLP. <br/>
<sup>9</sup> È possibile acquistare Azure Information Protection come sottoscrizione di componente aggiuntivo e usare OME se si configura l'ambiente di posta elettronica locale per instradare la posta elettronica da e verso Internet tramite EOP. <br/>
<sup>10</sup> Questa funzionalità richiede Exchange Online cassette postali. <br/>

## <a name="learn-more"></a>Ulteriori informazioni

Per informazioni tecniche su Exchange Online Protection, vedere le risorse seguenti:

La [Microsoft 365 roadmap è](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) una buona risorsa per trovare informazioni sulle nuove funzionalità future.

### <a name="licensing-terms"></a>Condizioni di licenza

Per le condizioni e le condizioni di licenza per i prodotti e i servizi acquistati tramite i Programmi Microsoft Commercial Volume Licensing, vedere il [sito condizioni del prodotto](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Messaggistica

Per tenere traccia delle modifiche imminenti, incluse funzionalità nuove e modificate, manutenzione pianificata o altri annunci importanti, visitare il Centro messaggi. Per ulteriori informazioni, vedere [Centro messaggi.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Accessibilità

Microsoft continua a impegnarsi per la sicurezza dei dati e [l'accessibilità](https://www.microsoft.com/trust-center/compliance/accessibility) dei nostri servizi. Per ulteriori informazioni, vedere Centro protezione [Microsoft](https://www.microsoft.com/trust-center) e Centro [Office Accessibilità.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
