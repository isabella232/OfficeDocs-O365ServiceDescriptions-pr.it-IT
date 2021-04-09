---
title: Limiti di Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Per Exchange Online Protection sono attualmente disponibili i limiti seguenti. Questi limiti non sono configurabili se non diversamente specificato.
ms.openlocfilehash: c4bce8f7b501a7a00eea723464e20964899b3560
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653054"
---
# <a name="exchange-online-protection-limits"></a>Limiti di Exchange Online Protection

Per Exchange Online Protection sono attualmente disponibili i limiti seguenti. Questi limiti non sono configurabili se non diversamente specificato. 
  
> [!TIP]
> Per ulteriori informazioni sui limiti in Exchange Online, vedere [Limiti di Exchange Online.](../exchange-online-service-description/exchange-online-limits.md) I limiti delle regole di trasporto si applicano anche ai clienti EOP autonomi. I limiti relativi alla frequenza di destinatari e di messaggi validi in Exchange Online non sono invece applicabili per i clienti che utilizzano EOP in uno scenario autonomo. 
  
- **Limite dominio:** è possibile aggiungere fino a 900 domini per tenant. I sottodomini possono essere inclusi nello stesso limite o, se necessario, come parte di un'opzione generale, adatta a tutti i sottodomini. Per ulteriori informazioni, vedere [Gestione domini accettati in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).

- **Limite dominio remoto** - È possibile aggiungere fino a 200 domini remoti per tenant.
    
- **Limite di dimensione dei** messaggi - La dimensione massima dei messaggi per i clienti autonomi di EOP, inclusi gli allegati, è di 150 MB. 
    
- **Numero di messaggi in uscita inviati** - Il limite per il numero di messaggi in uscita inviati tramite EOP è sufficientemente elevato da garantire che le normali comunicazioni di posta elettronica non siano trattate come posta indesiderata. Se si desidera inviare messaggi di posta elettronica in blocco a scopo commerciale, anzichè tramite EOP, è consigliabile inviarli tramite un provider di servizi di posta elettronica di terze parti oppure tramite i server di posta elettronica locali. 
    
- **Limite destinatari:** purché l'host di invio possa dividere il messaggio in "blocchi" di meno di 500 destinatari, non viene definito alcun limite esplicito. Tuttavia, ogni "blocco" viene considerato come un nuovo messaggio. Un numero eccessivo di messaggi in un breve periodo di tempo, i messaggi provenienti da un host con una reputazione dubbia o i messaggi con un contenuto discutibile potrebbero essere limitati o bloccati. 
    
- **Ip Allow or IP Block list limit** - Quando si configura un elenco indirizzi IP consentiti o un elenco indirizzi IP non consentiti nel filtro connessioni, è possibile specificare un massimo di 1273 voci, dove una voce è un singolo indirizzo IP o un intervallo CIDR di indirizzi IP da /24 a /32. 
    
- **Limite di rinvio dei messaggi** - I messaggi in differimento rimarranno nelle code per 24 ore. I tentativi di invio dei messaggi variano in base al tipo di errore ricevuto dal sistema di posta elettronica del destinatario. I messaggi vengono recuperati ogni 15 minuti. 
    
- **Periodo di conservazione della quarantena** della posta indesiderata - Per impostazione predefinita, i messaggi di posta indesiderata inviati alla quarantena vengono conservati per 30 giorni. Gli amministratori possono ridurre tale valore tramite i criteri di filtro del contenuto. 
    
- **Notifiche di quarantena della posta indesiderata dell'utente** finale - Per impostazione predefinita, se abilitate, le notifiche di quarantena della posta indesiderata dell'utente finale vengono inviate ogni 3 giorni. Possono essere configurate per essere inviate a intervalli da 1 o 15 giorni. 
    
- **Limiti di segnalazione** e traccia dei messaggi - Per i limiti di segnalazione e traccia dei messaggi, vedere la sezione "Disponibilità e latenza dei dati di segnalazione e traccia dei messaggi" [in Reporting and message trace in Exchange Online Protection.](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection)
    
### <a name="limits-across-eop-options"></a>Limiti tra opzioni EOP

| Funzionalità | EOP autonomo | Funzionalità di EOP in Exchange Online | Exchange Enterprise CAL con servizi |
|:-----|:-----|:-----|:-----|
|Limiti dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite dominio remoto  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Limiti dimensioni messaggio (inclusi gli allegati)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limiti destinatario  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |500 destinatari quando si invia da una cassetta postale ospitata; vedere "Limite destinatari" sopra riportato per ulteriori scenari  <br/> |Vedere "Limite destinatari" sopra riportato  <br/> |
|Limite dei mittenti attendibili  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limite mittente bloccato per criterio  <br/> |1024 voci  <br/> |1024 voci  <br/> ||
|Limiti elenco IP consentito o IP non consentito  <br/> |1273 voci  <br/> |1273 voci  <br/> |1273 voci  <br/> |
|Limiti ritardo messaggio  <br/> |1 giorno, ripetuto ogni 15 minuti  <br/> |1 giorno, ripetuto ogni 15 minuti  <br/> |1 giorno, ripetuto ogni 15 minuti  <br/> |
|Periodo di mantenimento in quarantena della posta indesiderata  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |30 giorni per impostazione predefinita, ma può essere abbassato  <br/> |
|Notifiche di quarantena della posta indesiderata dell'utente finale  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |3 giorni per impostazione predefinita, configurabile in un intervallo da 1 a 15 giorni  <br/> |
