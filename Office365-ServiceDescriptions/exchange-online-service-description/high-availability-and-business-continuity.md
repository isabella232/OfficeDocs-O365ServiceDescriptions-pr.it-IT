---
title: Disponibilità elevata e continuità aziendale
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online offre un supporto di conservazione e ripristino estensivo per l'infrastruttura di posta elettronica di un'organizzazione. Questo supporto include la replica delle cassette postali presso i data center e la capacità di ripristinare le cassette postali e gli elementi eliminati.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131970"
---
# <a name="high-availability-and-business-continuity"></a>Disponibilità elevata e continuità aziendale

Microsoft Exchange Online offre un supporto di conservazione e ripristino estensivo per l'infrastruttura di posta elettronica di un'organizzazione. Questo supporto include la replica delle cassette postali presso i data center e la capacità di ripristinare le cassette postali e gli elementi eliminati.
  
## <a name="mailbox-replication-at-data-centers"></a>Replica delle cassette postali presso i data center

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Recupero di cassette postali eliminate

Gli amministratori possono eliminare le cassette postali di Exchange Online utilizzando l'interfaccia di amministrazione di Microsoft 365 per eliminare l'account utente corrispondente oppure rimuovere la licenza di Exchange Online o utilizzando il cmdlet **Remove-Mailbox** in Windows PowerShell remoto. Quando una cassetta postale viene eliminata, Exchange Online conserva la cassetta postale e il contenuto per un periodo predefinito di 30 giorni. Dopo 30 giorni, la cassetta postale non è più recuperabile. Una cassetta postale recuperata contiene tutti i dati in essa archiviati nel momento in cui è stata eliminata. Gli amministratori possono recuperare una cassetta postale eliminata all'interno del periodo di conservazione tramite l'interfaccia di amministrazione di Microsoft 365. Per recuperare una cassetta postale eliminata, gli amministratori devono ripristinare l'account utente corrispondente o riassegnare una licenza di Exchange Online all'account utente. Per ulteriori informazioni, vedere la sezione sull' [eliminazione o il ripristino delle cassette postali degli utenti di Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Recupero di elementi eliminati

Exchange Online consente agli utenti di ripristinare gli elementi che sono stati eliminati da una cartella di posta elettronica, inclusa la cartella elementi eliminati. Quando un elemento viene eliminato, è trasferito nella cartella Posta eliminata. L'elemento rimane in tale cartella finché non viene eliminato manualmente dall'utente o automaticamente a seguito dei criteri di conservazione impostati. Gli amministratori possono personalizzare i criteri di conservazione utilizzando l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto.
  
Dopo la rimozione di un elemento dalla cartella Posta eliminata, questa viene conservata in una cartella elementi ripristinabili per altri 14 giorni prima di essere rimossa definitivamente, ma gli amministratori possono aumentare questo valore fino a un massimo di 30 giorni utilizzando Windows PowerShell remoto. Gli utenti possono recuperare l'elemento durante questo periodo di tempo utilizzando la funzionalità Recupera elementi eliminati in Outlook sul Web o Outlook. Informazioni su come [modificare il periodo di conservazione degli elementi eliminati](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  