---
title: Funzionalità di archiviazione in Exchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: Nelle sezioni seguenti vengono descritte le funzionalità di archiviazione di Microsoft Exchange Online Archiving.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131530"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Funzionalità di archiviazione in Exchange Online Archiving

Nelle sezioni seguenti vengono descritte le funzionalità di archiviazione di Microsoft Exchange Online Archiving.
  
## <a name="archive-mailbox"></a>Cassetta postale di archiviazione

Archiviazione Exchange Online offre agli utenti funzionalità di archiviazione avanzate tramite la funzionalità della cassetta postale di archiviazione. Una cassetta postale di archiviazione è una cassetta postale specializzata che viene visualizzata accanto alle cartelle principali delle cassette postali degli utenti in Outlook o Outlook sul Web. Gli utenti possono accedere all'archivio esattamente come fanno per le cassette postali principali. Inoltre, possono ricercare sia gli archivi che le cassette postali principali.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito. <br/>
>  Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di negare l'archiviazione illimitata nei casi in cui la cassetta postale di archiviazione di un utente viene utilizzata per archiviare i dati di archiviazione per altri utenti o in altri casi di utilizzo inappropriato.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Spostamento dei messaggi su Archiviazione Exchange Online

Gli utenti possono trascinare e rilasciare i messaggi dai file. pst nell'archivio per semplificare l'accesso online. Gli utenti possono anche spostare automaticamente gli elementi di posta elettronica dalla cassetta postale principale alla cassetta postale di archiviazione, utilizzando la polizia di archiviazione, per ridurre le dimensioni e migliorare le prestazioni della cassetta postale principale. 
  
### <a name="import-data-to-the-archive"></a>Importazione di dati nell'archivio

Gli utenti possono importare i dati nell'archivio nei modi riportati di seguito:
  
- Importare i dati da un file .pst utilizzando la funzionalità Importazione/Esportazione guidata di Outlook.
    
- Trascinare i messaggi di posta elettronica dai file .pst all'archivio.
    
- Trascinare i messaggi di posta elettronica dalla cassetta postale principale all'archivio.
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Recupero di elementi eliminati

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
Dopo che un elemento è stato rimosso dalla cartella Posta eliminata dell'archivio, viene conservato in una cartella Elementi ripristinabili dell'archivio per altri 14 giorni prima di essere rimosso definitivamente. Gli utenti possono recuperare questi elementi utilizzando la funzionalità **Recupera elementi eliminati** in Microsoft Outlook o Outlook sul Web. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  Per impostazione predefinita, il periodo di Ripristino di un singolo elemento è pari a 14 giorni, ma in alcuni casi può essere personalizzato. <br/>
>  Se un amministratore ha posizionato la cassetta postale di un utente sull'archiviazione sul posto o sul blocco per controversia legale, gli elementi eliminati vengono mantenuti per un periodo di tempo indefinito e la finestra di 14 giorni non viene applicata. 
  
## <a name="deleted-mailbox-recovery"></a>Recupero di cassette postali eliminate

Quando gli amministratori eliminano gli utenti da un server di Exchange locale, vengono eliminati anche gli archivi degli utenti. Se le cassette postali di archiviazione eliminate devono essere recuperate, il team del supporto tecnico Microsoft può eseguire questo ripristino. Un archivio recuperato contiene tutti i dati in esso memorizzati nel momento in cui è stato eliminato.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>Ridondanza servizio Cassetta postale

Le cassette postali di archiviazione in Archiviazione Exchange Online vengono replicate con copie inserite in diversi database, residenti in data center Microsoft geograficamente distribuiti, che ne consentono il ripristino in caso di danneggiamento di un'infrastruttura di messaggistica locale. Per errori su larga scala, viene avviata la continuità di business. 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).
  
