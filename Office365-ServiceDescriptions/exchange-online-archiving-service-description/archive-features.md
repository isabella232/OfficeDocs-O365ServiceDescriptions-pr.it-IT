---
title: Funzionalità di archiviazione di Archiviazione Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
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
ms.openlocfilehash: 7cbaaf81106084795630ced11837f4f9a56dcf85
ms.sourcegitcommit: 7a67ef94d2f9101a7f9d8989bfd5013bc89dce00
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/07/2019
ms.locfileid: "34780675"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="3db27-103">Funzionalità di archiviazione di Archiviazione Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3db27-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="3db27-104">Nelle sezioni seguenti vengono descritte le funzionalità di archiviazione di Microsoft Exchange Online Archiving.</span><span class="sxs-lookup"><span data-stu-id="3db27-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="3db27-105">Cassetta postale di archiviazione</span><span class="sxs-lookup"><span data-stu-id="3db27-105">Archive mailbox</span></span>

<span data-ttu-id="3db27-p101">Archiviazione Exchange Online offre agli utenti funzionalità di archiviazione avanzate tramite la funzionalità della cassetta postale di archiviazione. Una cassetta postale di archiviazione viene visualizzata insieme alla cassetta postale principale dell'utente in Outlook o in Outlook Web App. Gli utenti possono accedere all'archivio esattamente come fanno per le cassette postali principali. Inoltre, possono ricercare sia gli archivi che le cassette postali principali.</span><span class="sxs-lookup"><span data-stu-id="3db27-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="3db27-p102">Gli amministratori possono utilizzare l'interfaccia di amministrazione di Exchange (EAC, Exchange Admin Center) o Windows PowerShell remoto per abilitare la funzionalità di archiviazione per specifici utenti. Per ulteriori informazioni, vedere [Abilitare o disabilitare una cassetta postale di archiviazione in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="3db27-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="3db27-112">L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito.</span><span class="sxs-lookup"><span data-stu-id="3db27-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="3db27-113">Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente.</span><span class="sxs-lookup"><span data-stu-id="3db27-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="3db27-114">Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti.</span><span class="sxs-lookup"><span data-stu-id="3db27-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="3db27-115">Spostamento dei messaggi su Archiviazione Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3db27-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="3db27-116">Gli utenti possono trascinare e rilasciare i messaggi dai file. pst nell'archivio per semplificare l'accesso online.</span><span class="sxs-lookup"><span data-stu-id="3db27-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="3db27-117">Gli utenti possono anche spostare automaticamente gli elementi di posta elettronica dalla cassetta postale principale alla cassetta postale di archiviazione, utilizzando la polizia di archiviazione, per ridurre le dimensioni e migliorare le prestazioni della cassetta postale principale.</span><span class="sxs-lookup"><span data-stu-id="3db27-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="3db27-118">Importazione di dati nell'archivio</span><span class="sxs-lookup"><span data-stu-id="3db27-118">Import data to the archive</span></span>

<span data-ttu-id="3db27-119">Gli utenti possono importare i dati nell'archivio nei modi riportati di seguito:</span><span class="sxs-lookup"><span data-stu-id="3db27-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="3db27-120">Importare i dati da un file .pst utilizzando la funzionalità Importazione/Esportazione guidata di Outlook.</span><span class="sxs-lookup"><span data-stu-id="3db27-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="3db27-121">Trascinare i messaggi di posta elettronica dai file .pst all'archivio.</span><span class="sxs-lookup"><span data-stu-id="3db27-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="3db27-122">Trascinare i messaggi di posta elettronica dalla cassetta postale principale all'archivio.</span><span class="sxs-lookup"><span data-stu-id="3db27-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="3db27-p106">Utilizzare i criteri di archiviazione per lo spostamento automatico dei messaggi di posta elettronica dalla cassetta postale principale in base all'età dei messaggi. Per ulteriori informazioni, vedere [Tag di conservazione e criteri di conservazione](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span><span class="sxs-lookup"><span data-stu-id="3db27-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="3db27-p107">Gli amministratori possono anche utilizzare il servizio d'importazione di Office 365 per importare i file pst nelle cassette postali di archiviazione basate sul cloud dell'utente. Per ulteriori informazioni, vedere [Usare il caricamento di rete per importare i file PST in Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="3db27-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="3db27-127">Recupero di elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="3db27-127">Deleted item recovery</span></span>

<span data-ttu-id="3db27-p108">Gli utenti possono recuperare elementi eliminati da qualsiasi cartella di posta elettronica presente nei loro archivi. Quando un elemento viene eliminato, va a finire nella cartella Posta eliminata dell'archivio. L'elemento rimane in quella cartella fino a quando non viene eliminato manualmente dall'utente o automaticamente a seguito dei criteri di conservazione impostati.</span><span class="sxs-lookup"><span data-stu-id="3db27-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="3db27-p109">Dopo che un elemento è stato rimosso dalla cartella Posta eliminata dell'archivio, viene conservato in una cartella Elementi ripristinabili dell'archivio per altri 14 giorni prima di essere rimosso definitivamente. Gli utenti possono recuperare tali elementi utilizzando la funzionalità **Recupera elementi eliminati** in Microsoft Outlook o Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="3db27-p109">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="3db27-p110">Se un utente ha rimosso manualmente un elemento dalla cartella Elementi recuperabili, un amministratore è in grado di recuperare quell'elemento entro lo stesso periodo di 14 giorni tramite la funzionalità di recupero di un singolo elemento. Questa funzionalità consente agli amministratori di effettuare una ricerca su più cassette postali per trovare gli elementi eliminati e utilizzare il cmdlet  `Search-Mailbox` di Windows PowerShell per spostare gli elementi dalla cassetta postale di individuazione a quella degli utenti. Per ulteriori informazioni, vedere [Abilitare o disabilitare il ripristino di un singolo elemento per una cassetta postale](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="3db27-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="3db27-136">Per impostazione predefinita, il periodo di Ripristino di un singolo elemento è pari a 14 giorni, ma in alcuni casi può essere personalizzato.</span><span class="sxs-lookup"><span data-stu-id="3db27-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="3db27-137">Se un amministratore ha posizionato la cassetta postale di un utente sull'archiviazione sul posto o sul blocco per controversia legale, gli elementi eliminati vengono mantenuti per un periodo di tempo indefinito e la finestra di 14 giorni non viene applicata.</span><span class="sxs-lookup"><span data-stu-id="3db27-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="3db27-138">Recupero di cassette postali eliminate</span><span class="sxs-lookup"><span data-stu-id="3db27-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="3db27-p112">Quando gli amministratori eliminano gli utenti da un server di Exchange locale, vengono eliminati anche gli archivi degli utenti. Nel caso in cui sia necessario recuperare le cassette postali di archiviazione eliminate, il team di supporto per Office 365 può effettuare tale operazione. Un archivio recuperato contiene tutti i dati in esso memorizzati nel momento in cui è stato eliminato.</span><span class="sxs-lookup"><span data-stu-id="3db27-p112">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="3db27-p113">Per richiedere il recupero della cassetta postale di archiviazione, gli amministratori hanno a disposizione 30 giorni dal momento in cui la cassetta postale dell'utente è stata eliminata. Dopo 30 giorni, la cassetta postale di archiviazione non è più recuperabile.</span><span class="sxs-lookup"><span data-stu-id="3db27-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="3db27-144">Ridondanza servizio Cassetta postale</span><span class="sxs-lookup"><span data-stu-id="3db27-144">Mailbox service redundancy</span></span>

<span data-ttu-id="3db27-145">Le cassette postali di archiviazione in Archiviazione Exchange Online vengono replicate con copie inserite in diversi database, residenti in data center Microsoft geograficamente distribuiti, che ne consentono il ripristino in caso di danneggiamento di un'infrastruttura di messaggistica locale.</span><span class="sxs-lookup"><span data-stu-id="3db27-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="3db27-146">Per errori su larga scala, viene avviata la continuità di business.</span><span class="sxs-lookup"><span data-stu-id="3db27-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="3db27-147">Disponibilità delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="3db27-147">Feature Availability</span></span>

<span data-ttu-id="3db27-148">Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Archiviazione Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="3db27-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
