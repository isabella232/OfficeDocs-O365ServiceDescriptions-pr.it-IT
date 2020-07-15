---
title: Limiti di Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: I limiti seguenti sono attualmente disponibili per Exchange Online Protection. Questi limiti non sono configurabili, se non diversamente specificato.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133010"
---
# <a name="exchange-online-protection-limits"></a>Limiti di Exchange Online Protection

I limiti seguenti sono attualmente disponibili per Exchange Online Protection. Questi limiti non sono configurabili, se non diversamente specificato. 
  
> [!TIP]
> Per ulteriori informazioni sui limiti in Exchange Online, vedere [limiti di Exchange Online](../exchange-online-service-description/exchange-online-limits.md). I limiti delle regole di trasporto si applicano anche ai clienti EOP autonomi. I limiti relativi alla frequenza di destinatari e di messaggi validi in Exchange Online non sono invece applicabili per i clienti che utilizzano EOP in uno scenario autonomo. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Limite dimensioni messaggio** Per i clienti che utilizzano EOP in uno scenario autonomo, la dimensione massima dei messaggi è 150 MB, inclusi gli allegati. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **Limite elenco IP consentiti o IP non consentiti** Quando si configura un elenco indirizzi IP consentiti o un elenco indirizzi IP non consentiti nel filtro di connessione, è possibile specificare un massimo di 1273 voci (una voce può essere un singolo indirizzo IP o un intervallo CIDR di indirizzi IP compresi tra 24 e 32). 
    
- **Limite di rinvio del messaggio** I messaggi in differimento rimarranno nelle code per 24 ore. I tentativi di invio dei messaggi variano in base al tipo di errore ricevuto dal sistema di posta elettronica del destinatario. I messaggi vengono recuperati ogni 15 minuti. 
    
- **Periodo di conservazione della quarantena della posta indesiderata** Per impostazione predefinita, i messaggi di posta indesiderata inviati alla quarantena vengono conservati per 30 giorni. Gli amministratori possono ridurre tale valore tramite i criteri di filtro del contenuto. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **Creazione di report e limiti di traccia dei messaggi** Per i limiti relativi alla creazione di rapporti e alla traccia dei messaggi, vedere "Reporting and Message Trace Data Availability and latence" nella sezione [Reporting and Message Trace in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limiti tra opzioni EOP

|**Funzionalità**|****EOP autonomo****|****Caratteristiche EOP in Exchange Online****|****Exchange Enterprise CAL con servizi****|
|:-----|:-----|:-----|:-----|
|Limiti dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limiti dimensioni messaggio (inclusi gli allegati)  <br/> |150 MB  <br/> |150 MB   <br/> |150 MB  <br/> |
|Limiti destinatario  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |500 destinatari quando si invia da una cassetta postale ospitata; vedere "Limite destinatari" sopra riportato per ulteriori scenari  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |
|Limite dei mittenti attendibili  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limite del mittente bloccato per ogni criterio  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limiti elenco IP consentito o IP non consentito  <br/> |1273 voci  <br/> |1273 voci  <br/> |1273 voci  <br/> |
|Limiti ritardo messaggio  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |
|Periodo di mantenimento in quarantena della posta indesiderata  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |
|Notifiche di quarantena della posta indesiderata dell'utente finale  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |
   

