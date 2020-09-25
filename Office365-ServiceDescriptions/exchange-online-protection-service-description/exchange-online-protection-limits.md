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
ms.openlocfilehash: 555177349005c275fcbf91a1e70467ebcc25f2be
ms.sourcegitcommit: 0f17ea421190f52bf55e530e9374543fd59b8665
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2020
ms.locfileid: "48261494"
---
# <a name="exchange-online-protection-limits"></a>Limiti di Exchange Online Protection

I limiti seguenti sono attualmente disponibili per Exchange Online Protection. Questi limiti non sono configurabili, se non diversamente specificato. 
  
> [!TIP]
> Per ulteriori informazioni sui limiti in Exchange Online, vedere [limiti di Exchange Online](../exchange-online-service-description/exchange-online-limits.md). I limiti delle regole di trasporto si applicano anche ai clienti EOP autonomi. I limiti relativi alla frequenza di destinatari e di messaggi validi in Exchange Online non sono invece applicabili per i clienti che utilizzano EOP in uno scenario autonomo. 
  
- **Limite di dominio** : è possibile aggiungere fino a 900 domini per tenant. I sottodomini possono essere inclusi nello stesso limite o, se necessario, come parte di un'opzione generale, adatta a tutti i sottodomini. Per ulteriori informazioni, vedere [Gestione domini accettati in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).

- **Limite del dominio remoto** : è possibile aggiungere fino a 200 domini remoti per tenant.
    
- **Limite dimensione messaggio** -la dimensione massima dei messaggi per i clienti autonomi di EOP, inclusi gli allegati, è 150 MB. 
    
- **Numero di messaggi in uscita inviati** : il limite per il numero di messaggi in uscita inviati tramite EOP è sufficientemente elevato per garantire che la normale comunicazione tramite posta elettronica non venga trattata come posta indesiderata. Se si desidera inviare messaggi di posta elettronica in blocco a scopo commerciale, anzichè tramite EOP, è consigliabile inviarli tramite un provider di servizi di posta elettronica di terze parti oppure tramite i server di posta elettronica locali. 
    
- **Limite destinatario** -finché l'host di invio può suddividere il messaggio in "blocchi" di meno di 500 destinatari, non viene definito alcun limite esplicito. Tuttavia, ogni "blocco" viene considerato come un nuovo messaggio. Un numero eccessivo di messaggi in un breve periodo di tempo, i messaggi provenienti da un host con una reputazione dubbia o i messaggi con un contenuto discutibile potrebbero essere limitati o bloccati. 
    
- **Limite dell'elenco indirizzi IP consentiti o IP bloccati** -quando si configura un elenco IP consentiti o un elenco IP bloccati nel filtro di connessione, è possibile specificare un massimo di 1273 voci, in cui una voce è costituita da un singolo indirizzo IP o da un intervallo CIDR compreso tra/24 e/32. 
    
- **Limite di rinvio del messaggio** -i messaggi in differimento rimarranno nelle code per 24 ore. I tentativi di invio dei messaggi variano in base al tipo di errore ricevuto dal sistema di posta elettronica del destinatario. I messaggi vengono recuperati ogni 15 minuti. 
    
- **Periodo di conservazione per la quarantena della posta indesiderata** : i messaggi di posta indesiderata inviati alla quarantena vengono conservati per 30 giorni. Gli amministratori possono ridurre tale valore tramite i criteri di filtro del contenuto. 
    
- **Notifiche di quarantena della posta indesiderata dell'utente finale** -per impostazione predefinita, se attivata, le notifiche di quarantena della posta indesiderata dell'utente finale vengono inviate ogni 3 giorni Possono essere configurate per essere inviate a intervalli da 1 o 15 giorni. 
    
- **Reporting and Message Trace limits** -for Reporting and Message Trace limits, vedere la sezione "Reporting and Message Trace Data Availability and latence" in [Reporting and Message Trace in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limiti tra opzioni EOP

| Funzionalità | EOP autonomo | Funzionalità di EOP in Exchange Online | Exchange Enterprise CAL con servizi |
|:-----|:-----|:-----|:-----|
|Limiti dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite del dominio remoto  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Limiti dimensioni messaggio (inclusi gli allegati)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limiti destinatario  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |500 destinatari quando si invia da una cassetta postale ospitata; vedere "Limite destinatari" sopra riportato per ulteriori scenari  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |
|Limite dei mittenti attendibili  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limite del mittente bloccato per ogni criterio  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limiti elenco IP consentito o IP non consentito  <br/> |1273 voci  <br/> |1273 voci  <br/> |1273 voci  <br/> |
|Limiti ritardo messaggio  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |
|Periodo di mantenimento in quarantena della posta indesiderata  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |
|Notifiche di quarantena della posta indesiderata dell'utente finale  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |
   

