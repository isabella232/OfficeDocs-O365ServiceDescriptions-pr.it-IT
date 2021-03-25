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
description: Microsoft Exchange Online supporto completo per la conservazione e il ripristino per l'infrastruttura di posta elettronica di un'organizzazione. Questo supporto include la replica delle cassette postali presso i data center e la capacità di ripristinare le cassette postali e gli elementi eliminati.
ms.openlocfilehash: e205f26bfa611e388cc22557db98eeb84505ef9c
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173681"
---
# <a name="high-availability-and-business-continuity"></a>Disponibilità elevata e continuità aziendale

Microsoft Exchange Online supporto completo per la conservazione e il ripristino per l'infrastruttura di posta elettronica di un'organizzazione. Questo supporto include la replica delle cassette postali presso i data center e la capacità di ripristinare le cassette postali e gli elementi eliminati.
  
## <a name="mailbox-replication-at-data-centers"></a>Replica delle cassette postali presso i data center

Le cassette postali di Exchange Online vengono continuamente replicate con copie inserite in diversi database, residenti in data center Microsoft geograficamente distribuiti, che ne consentono il ripristino in caso di danneggiamento di un'infrastruttura di messaggistica locale. Per problemi su vasta scala, vengono avviate le procedure di gestione della continuità del servizio.
  
Per ulteriori informazioni su come Microsoft protegge i dati dei clienti, visitare il [Centro protezione di Office 365](https://go.microsoft.com/fwlink/p/?LinkId=299135). Se si utilizza Office 365 gestito da 21Vianet, vedere [Centro protezione di 21Vianet](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Recupero di cassette postali eliminate

Gli amministratori possono eliminare le cassette postali di Exchange Online utilizzando l'interfaccia di amministrazione di Microsoft 365 per eliminare l'account utente corrispondente o rimuovere la licenza di Exchange Online oppure utilizzando il cmdlet **Remove-Mailbox** in Windows PowerShell remoto. Quando una cassetta postale viene eliminata, Exchange Online conserva la cassetta postale e il contenuto per un periodo predefinito di 30 giorni. Dopo 30 giorni, la cassetta postale non è più recuperabile. Una cassetta postale recuperata contiene tutti i dati in essa archiviati nel momento in cui è stata eliminata. Gli amministratori possono ripristinare una cassetta postale eliminata entro il periodo di conservazione utilizzando l'interfaccia di amministrazione di Microsoft 365. Per ripristinare una cassetta postale eliminata, gli amministratori devono ripristinare l'account utente corrispondente o riassegnare una licenza di Exchange Online all'account utente. Per ulteriori informazioni, vedere la sezione sull' [eliminazione o il ripristino delle cassette postali degli utenti di Exchange Online](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes).
  
## <a name="deleted-item-recovery"></a>Recupero di elementi eliminati

Exchange Online consente agli utenti di ripristinare gli elementi eliminati da qualsiasi cartella di posta elettronica, inclusa la cartella Posta eliminata. Quando un elemento viene eliminato, è trasferito nella cartella Posta eliminata. L'elemento rimane in tale cartella finché non viene eliminato manualmente dall'utente o automaticamente a seguito dei criteri di conservazione impostati. Gli amministratori possono personalizzare i criteri di conservazione utilizzando l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto.
  
Una volta rimosso dalla cartella Posta eliminata, un elemento viene conservato in una cartella Elementi ripristinabili per altri 14 giorni prima di essere rimosso definitivamente, ma gli amministratori possono aumentarlo fino a un massimo di 30 giorni utilizzando l'Windows PowerShell. Gli utenti possono ripristinare l'elemento durante questo periodo di tempo utilizzando la funzionalità Recupera posta eliminata in Outlook sul Web o Outlook. Informazioni su come modificare [il periodo di conservazione degli elementi eliminati.](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention)
  
Se un utente ha rimosso manualmente un elemento dalla cartella Elementi recuperabili, un amministratore è in grado di recuperare quell'elemento entro lo stesso periodo tramite la funzionalità di recupero di un singolo elemento con Windows PowerShell remoto. Per impostazione predefinita, il ripristino di un singolo elemento viene abilitato quando viene creata una cassetta postale. Per ulteriori informazioni, vedere [Abilitare o disabilitare il ripristino di un singolo elemento per una cassetta postale](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery).
  
Per conservare i messaggi per più di 30 giorni nella cartella Elementi recuperabili, le organizzazioni possono implementare un periodo di tempo più lungo per la conservazione della posta elettronica o per l'archiviazione a tempo sul posto. Ulteriori informazioni su [sull'attivazione della conservazione in locale per una cassetta postale](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Descrizione del servizio [Exchange Online.](exchange-online-service-description.md)
