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
ms.openlocfilehash: baf6bc688492ca340442ee2d14f98bd9e135c43d
ms.sourcegitcommit: 5bad2698c44963874c993181ef7f2e468ea7fb16
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2020
ms.locfileid: "48134053"
---
# <a name="exchange-online-protection-limits"></a>Limiti di Exchange Online Protection

I limiti seguenti sono attualmente disponibili per Exchange Online Protection. Questi limiti non sono configurabili, se non diversamente specificato. 
  
> [!TIP]
> Per ulteriori informazioni sui limiti in Exchange Online, vedere [limiti di Exchange Online](../exchange-online-service-description/exchange-online-limits.md). I limiti delle regole di trasporto si applicano anche ai clienti EOP autonomi. I limiti relativi alla frequenza di destinatari e di messaggi validi in Exchange Online non sono invece applicabili per i clienti che utilizzano EOP in uno scenario autonomo. 
  
- **Limite dominio** È possibile aggiungere fino a 900 domini per tenant. I sottodomini possono essere inclusi nello stesso limite o, se necessario, come parte di un'opzione generale, adatta a tutti i sottodomini. Per ulteriori informazioni, vedere [Gestione domini accettati in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).

- **Limite del dominio remoto** È possibile aggiungere fino a 200 domini remoti per tenant.
    
- **Limite dimensioni messaggio** Per i clienti che utilizzano EOP in uno scenario autonomo, la dimensione massima dei messaggi è 150 MB, inclusi gli allegati. 
    
- **Numero di messaggi in uscita inviati** Il limite relativo al numero di messaggi in uscita inviati tramite EOP è sufficientemente alto da garantire che le comunicazioni di posta elettronica normali non vengano gestite come posta indesiderata. Se si desidera inviare messaggi di posta elettronica in blocco a scopo commerciale, anzichè tramite EOP, è consigliabile inviarli tramite un provider di servizi di posta elettronica di terze parti oppure tramite i server di posta elettronica locali. 
    
- **Limite destinatari** Finché l'host che effettua l'invio è in grado di dividere il messaggio in "blocchi" di meno di 500 destinatari, non viene definito nessun limite esplicito. Tuttavia, ogni "blocco" viene considerato come un nuovo messaggio. Un numero eccessivo di messaggi in un breve periodo di tempo, i messaggi provenienti da un host con una reputazione dubbia o i messaggi con un contenuto discutibile potrebbero essere limitati o bloccati. 
    
- **Limite elenco IP consentiti o IP non consentiti** Quando si configura un elenco indirizzi IP consentiti o un elenco indirizzi IP non consentiti nel filtro di connessione, è possibile specificare un massimo di 1273 voci (una voce può essere un singolo indirizzo IP o un intervallo CIDR di indirizzi IP compresi tra 24 e 32). 
    
- **Limite di rinvio del messaggio** I messaggi in differimento rimarranno nelle code per 24 ore. I tentativi di invio dei messaggi variano in base al tipo di errore ricevuto dal sistema di posta elettronica del destinatario. I messaggi vengono recuperati ogni 15 minuti. 
    
- **Periodo di conservazione della quarantena della posta indesiderata** Per impostazione predefinita, i messaggi di posta indesiderata inviati alla quarantena vengono conservati per 30 giorni. Gli amministratori possono ridurre tale valore tramite i criteri di filtro del contenuto. 
    
- **Notifiche di quarantena della posta indesiderata dell'utente finale** Per impostazione predefinita, se abilitata, le notifiche di quarantena della posta indesiderata dell'utente finale vengono inviate ogni 3 giorni. Possono essere configurate per essere inviate a intervalli da 1 o 15 giorni. 
    
- **Creazione di report e limiti di traccia dei messaggi** Per i limiti relativi alla creazione di rapporti e alla traccia dei messaggi, vedere "Reporting and Message Trace Data Availability and latence" nella sezione [Reporting and Message Trace in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limiti tra opzioni EOP

|**Funzionalità**|****EOP autonomo****|****Caratteristiche EOP in Exchange Online****|****Exchange Enterprise CAL con servizi****|
|:-----|:-----|:-----|:-----|
|Limiti dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limiti dimensioni messaggio (inclusi gli allegati)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limiti destinatario  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |500 destinatari quando si invia da una cassetta postale ospitata; vedere "Limite destinatari" sopra riportato per ulteriori scenari  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |
|Limite dei mittenti attendibili  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limite del mittente bloccato per ogni criterio  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limiti elenco IP consentito o IP non consentito  <br/> |1273 voci  <br/> |1273 voci  <br/> |1273 voci  <br/> |
|Limiti ritardo messaggio  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |1 giorno, riprovato ogni 15 minuti  <br/> |
|Periodo di mantenimento in quarantena della posta indesiderata  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |
|Notifiche di quarantena della posta indesiderata dell'utente finale  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |
   

