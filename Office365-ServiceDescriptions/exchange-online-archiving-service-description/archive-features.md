---
title: Funzionalità di archiviazione di Archiviazione Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: Nelle sezioni seguenti vengono descritte le funzionalità di archiviazione di archiviazione di Microsoft Exchange Online.
ms.openlocfilehash: f14d8e5c6acefef6fd08cf8e8edf5f33acb9f9df
ms.sourcegitcommit: 433b170b26fbd9c2e9b0e520adfef6f0804df25a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/08/2018
ms.locfileid: "26215351"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Funzionalità di archiviazione di Archiviazione Exchange Online

Nelle sezioni seguenti vengono descritte le funzionalità di archiviazione di archiviazione di Microsoft Exchange Online.
  
## <a name="archive-mailbox"></a>Cassetta postale di archiviazione

Archiviazione Exchange Online offre agli utenti funzionalità di archiviazione avanzate tramite la funzionalità della cassetta postale di archiviazione. Una cassetta postale di archiviazione viene visualizzata insieme alla cassetta postale principale dell'utente in Outlook o in Outlook Web App. Gli utenti possono accedere all'archivio esattamente come fanno per le cassette postali principali. Inoltre, possono ricercare sia gli archivi che le cassette postali principali.
  
Gli amministratori possono utilizzare l'interfaccia di amministrazione di Exchange (EAC, Exchange Admin Center) o Windows PowerShell remoto per abilitare la funzionalità di archiviazione per specifici utenti. Per ulteriori informazioni, vedere [Abilitare o disabilitare una cassetta postale di archiviazione in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).
  
> [!IMPORTANT]
>  L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito. >  Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti. 
  
### <a name="move-messages-to-exchange-online-archiving"></a>Spostamento dei messaggi su Archiviazione Exchange Online

Gli utenti possono trascinare e rilasciare i messaggi dai file pst all'archivio, per semplificare l'accesso in linea. Gli utenti inoltre possono spostare gli elementi di posta elettronica dalla cassetta postale principale la cassetta postale di archiviazione automatica, con quelli di archiviazione, per ridurre le dimensioni e migliorare le prestazioni della cassetta postale principale. Durante questo comportamento è diverso da quello di Exchange Hosted Archive, che verrà creata una copia secondaria di ogni messaggio nell'archivio, è possono ottenere i requisiti di conservazione in entrambi gli scenari. 
  
### <a name="import-data-to-the-archive"></a>Importazione di dati nell'archivio

Gli utenti possono importare i dati nell'archivio nei modi riportati di seguito:
  
- Importare i dati da un file .pst utilizzando la funzionalità Importazione/Esportazione guidata di Outlook.
    
- Trascinare i messaggi di posta elettronica dai file .pst all'archivio.
    
- Trascinare i messaggi di posta elettronica dalla cassetta postale principale all'archivio.
    
- Utilizzare i criteri di archiviazione per lo spostamento automatico dei messaggi di posta elettronica dalla cassetta postale principale in base all'età dei messaggi. Per ulteriori informazioni, vedere [Tag di conservazione e criteri di conservazione](https://go.microsoft.com/fwlink/p/?LinkId=314153).
    
> [!NOTE]
> Gli amministratori possono anche utilizzare il servizio d'importazione di Office 365 per importare i file pst nelle cassette postali di archiviazione basate sul cloud dell'utente. Per ulteriori informazioni, vedere [Usare il caricamento di rete per importare i file PST in Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074). 
  
## <a name="deleted-item-recovery"></a>Recupero di elementi eliminati

Gli utenti possono recuperare elementi eliminati da qualsiasi cartella di posta elettronica presente nei loro archivi. Quando un elemento viene eliminato, va a finire nella cartella Posta eliminata dell'archivio. L'elemento rimane in quella cartella fino a quando non viene eliminato manualmente dall'utente o automaticamente a seguito dei criteri di conservazione impostati.
  
Dopo che un elemento è stato rimosso dalla cartella Posta eliminata dell'archivio, viene conservato in una cartella Elementi ripristinabili dell'archivio per altri 14 giorni prima di essere rimosso definitivamente. Gli utenti possono recuperare tali elementi utilizzando la funzionalità **Recupera elementi eliminati** in Microsoft Outlook o Outlook Web App. 
  
Se un utente ha rimosso manualmente un elemento dalla cartella Elementi recuperabili, un amministratore è in grado di recuperare quell'elemento entro lo stesso periodo di 14 giorni tramite la funzionalità di recupero di un singolo elemento. Questa funzionalità consente agli amministratori di effettuare una ricerca su più cassette postali per trovare gli elementi eliminati e utilizzare il cmdlet  `Search-Mailbox` di Windows PowerShell per spostare gli elementi dalla cassetta postale di individuazione a quella degli utenti. Per ulteriori informazioni, vedere [Abilitare o disabilitare il ripristino di un singolo elemento per una cassetta postale](https://go.microsoft.com/fwlink/p/?LinkId=314155).
  
> [!NOTE]
>  Per impostazione predefinita, il periodo di Ripristino di un singolo elemento è pari a 14 giorni, ma in alcuni casi può essere personalizzato. >  Se un amministratore ha bloccato la cassetta postale sul posto o per una controversia legale, gli elementi eliminati vengono mantenuti per un periodo indefinito e il periodo di 14 giorni non è valido. 
  
## <a name="deleted-mailbox-recovery"></a>Recupero di cassette postali eliminate

Quando gli amministratori eliminano gli utenti da un server di Exchange locale, vengono eliminati anche gli archivi degli utenti. Nel caso in cui sia necessario recuperare le cassette postali di archiviazione eliminate, il team di supporto per Office 365 può effettuare tale operazione. Un archivio recuperato contiene tutti i dati in esso memorizzati nel momento in cui è stato eliminato.
  
> [!IMPORTANT]
> Per richiedere il recupero della cassetta postale di archiviazione, gli amministratori hanno a disposizione 30 giorni dal momento in cui la cassetta postale dell'utente è stata eliminata. Dopo 30 giorni, la cassetta postale di archiviazione non è più recuperabile. 
  
## <a name="mailbox-service-redundancy"></a>Ridondanza servizio Cassetta postale

Cassette postali di archiviazione in archiviazione Exchange Online vengono replicate in più copie del database, in geograficamente distribuiti data center Microsoft, per fornire funzionalità di ripristino di dati in caso di errore dell'infrastruttura di messaggistica. Per gli errori su larga scala, viene avviata la gestione della continuità aziendale. 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Archiviazione Exchange Online](exchange-online-archiving-service-description.md).
  
