---
title: Disponibilità elevata e continuità aziendale
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online offre un supporto di conservazione e ripristino estensivo per l'infrastruttura di posta elettronica di un'organizzazione. Questo supporto include la replica delle cassette postali presso i data center e la capacità di ripristinare le cassette postali e gli elementi eliminati.
ms.openlocfilehash: 2da41ba335faa4cf18228a64fbb1b420d438e503
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466513"
---
# <a name="high-availability-and-business-continuity"></a>High Availability and Business Continuity

Microsoft Exchange Online offre un supporto di conservazione e ripristino estensivo per l'infrastruttura di posta elettronica di un'organizzazione. Questo supporto include la replica delle cassette postali presso i data center e la capacità di ripristinare le cassette postali e gli elementi eliminati.
  
## <a name="mailbox-replication-at-data-centers"></a>Replica delle cassette postali presso i data center

Le cassette postali di Exchange Online vengono continuamente replicate con copie inserite in diversi database, residenti in data center Microsoft geograficamente distribuiti, che ne consentono il ripristino in caso di danneggiamento di un'infrastruttura di messaggistica locale. Per problemi su vasta scala, vengono avviate le procedure di gestione della continuità del servizio.
  
Per ulteriori informazioni su come Microsoft protegge i dati dei clienti, visitare il [Centro protezione di Office 365](https://go.microsoft.com/fwlink/p/?LinkId=299135). Se si utilizza Office 365 gestito da 21Vianet, vedere [Centro protezione di 21Vianet](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Recupero di cassette postali eliminate

Gli amministratori possono eliminare le cassette postali di Exchange Online utilizzando l'interfaccia di amministrazione di Microsoft 365 per eliminare l'account utente corrispondente oppure rimuovere la licenza di Exchange Online o utilizzando il cmdlet **Remove-Mailbox** in Windows PowerShell remoto. Quando una cassetta postale viene eliminata, Exchange Online conserva la cassetta postale e il contenuto per un periodo predefinito di 30 giorni. Dopo 30 giorni, la cassetta postale non è più recuperabile. Una cassetta postale recuperata contiene tutti i dati in essa archiviati nel momento in cui è stata eliminata. Gli amministratori possono recuperare una cassetta postale eliminata all'interno del periodo di conservazione tramite l'interfaccia di amministrazione di Microsoft 365. Per recuperare una cassetta postale eliminata, gli amministratori devono ripristinare l'account utente di Office 365 corrispondente oppure riassegnare una licenza di Exchange Online all'account utente. Per ulteriori informazioni, vedere la sezione sull' [eliminazione o il ripristino delle cassette postali degli utenti di Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Recupero di elementi eliminati

Exchange Online consente agli utenti di ripristinare gli elementi eliminate da qualunque cartella della posta elettronica, inclusa la cartella Posta eliminata. Quando un elemento viene eliminato, è trasferito nella cartella Posta eliminata. L'elemento rimane in tale cartella finché non viene eliminato manualmente dall'utente o automaticamente a seguito dei criteri di conservazione impostati. Gli amministratori possono personalizzare i criteri di conservazione utilizzando l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto.
  
In seguito all'eliminazione dalla cartella Posta eliminata, un elemento viene conservato nella cartella Elementi recuperabili per ulteriori 14 giorni prima di essere eliminato in modo definitivo. Tuttavia, gli amministratori possono aumentare questo valore fino a un massimo di 30 giorni utilizzando Windows PowerShell remoto. Gli utenti possono ripristinare l'elemento durante questo periodo, utilizzando la funzionalità Recupera elementi eliminati Outlook Web App o Outlook. Informazioni su come [modificare il periodo di conservazione degli elementi eliminati](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
Se un utente ha rimosso manualmente un elemento dalla cartella Elementi recuperabili, un amministratore è in grado di recuperare quell'elemento entro lo stesso periodo tramite la funzionalità di recupero di un singolo elemento con Windows PowerShell remoto. Per impostazione predefinita, il ripristino di un singolo elemento viene abilitato quando viene creata una cassetta postale. Per ulteriori informazioni, vedere [Abilitare o disabilitare il ripristino di un singolo elemento per una cassetta postale](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
Per conservare i messaggi per più di 30 giorni nella cartella Elementi recuperabili, le organizzazioni possono implementare un periodo di tempo più lungo per la conservazione della posta elettronica o per l'archiviazione a tempo sul posto. Ulteriori informazioni su [sull'attivazione della conservazione in locale per una cassetta postale](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

