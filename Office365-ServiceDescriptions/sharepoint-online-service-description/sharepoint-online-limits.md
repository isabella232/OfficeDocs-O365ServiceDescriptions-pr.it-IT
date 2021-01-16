---
title: Limiti di SharePoint
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Informazioni sui limiti di SharePoint per Microsoft 365 e piani autonomi.
ms.openlocfilehash: 8e8931c77f7ceda2b1aed90d4804f98355fd6caa
ms.sourcegitcommit: b735b2419e81c635b5f116125dd0bc38d2bb91d4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/15/2021
ms.locfileid: "49878699"
---
# <a name="sharepoint-limits"></a>Limiti di SharePoint

Informazioni sui limiti di servizio in SharePoint per Microsoft 365.
  
## <a name="limits-by-plan"></a>Limiti in base alla pianificazione 

| Funzionalità | Microsoft 365 Business Basic, business standard o Business Premium | Microsoft 365 E3 o E5, Office 365 E1, E3 o E5 oppure SharePoint piano 1 o 2 | Microsoft 365 F1 o F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Spazio di archiviazione totale per ogni organizzazione<sup>1, 2, 6</sup> <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup>  <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Spazio di archiviazione massimo per sito (raccolta siti)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Siti (raccolte siti) per ogni organizzazione  <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<br/> |
|Numero di utenti  <br/> |Fino a 300  <br/> |1- 500.000<sup>7</sup> <br/> |1- 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [informazioni su come trovare l'archiviazione totale e disponibile per l'organizzazione](/sharepoint/manage-site-collection-storage-limits). È possibile acquistare una quantità illimitata di ulteriore spazio di archiviazione di SharePoint. Vedere [Modificare lo spazio di archiviazione per l'abbonamento](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Si consiglia di monitorare il Cestino e svuotarlo regolarmente. Lo spazio di archiviazione utilizzato è parte integrante del limite di archiviazione totale dell'organizzazione. 
<br/> <sup>3</sup> se si dispone di un abbonamento a Microsoft 365 e di un componente aggiuntivo di archiviazione file aggiuntivo di Office 365, vengono aggiunti gli importi di archiviazione. 
<br/> <sup>4</sup> questo è il *limite* di archiviazione per un singolo sito (in precedenza denominato "raccolta siti"), non la quantità di spazio di archiviazione *disponibile* per ogni sito. Questo limite si applica a tutti i tipi di siti, inclusi i siti del team connessi a un gruppo di Office 365 e OneDrive. Gli amministratori di SharePoint possono [impostare manualmente limiti di spazio di archiviazione inferiori](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> i lavoratori di FIRSTLINE non possono amministrare i siti di SharePoint. 
<br/> <sup>6</sup> non include il OneDrive creato per ogni utente con licenza. 
<br/> <sup>7</sup> se si dispone di più di 500.000 utenti, contattare un rappresentante Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limiti di servizio per tutti i piani

### <a name="items-in-lists-and-libraries"></a>Elementi in elenchi e raccolte

Un elenco può avere fino a 30 milioni elementi e una raccolta può avere fino a 30 milioni file e cartelle. Quando un elenco, una raccolta o una cartella contiene più di 100.000 elementi, non è possibile interrompere l'ereditarietà delle autorizzazioni nell'elenco, nella raccolta o nella cartella. Non è possibile ereditare nuovamente le autorizzazioni su di essa. Tuttavia, è comunque possibile interrompere l'ereditarietà nei singoli elementi all'interno di tale elenco, raccolta o cartella fino al numero massimo di autorizzazioni univoche nell'elenco o nella raccolta (vedere la sezione successiva). Per ulteriori informazioni sulle altre limitazioni per la visualizzazione di elenchi di grandi dimensioni, vedere [gestire elenchi di grandi dimensioni e raccolte in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Ambiti di sicurezza univoci per elenco o raccolta

Per gli elenchi di grandi dimensioni, la progettazione può disporre di poche autorizzazioni esclusive e rimanere al di sotto di 5.000 in totale.

### <a name="file-size-and-file-path-length"></a>Dimensione del file e lunghezza del percorso del file

100 GB. Per ulteriori informazioni sulle restrizioni e sui limiti quando si utilizza la nuova app di sincronizzazione di OneDrive (OneDrive.exe), vedere [nomi di file e tipi di file non validi](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Spostamento e copia tra siti

La copia o lo spostamento di più file in una singola operazione ha tre requisiti:

- Non più di 100 GB di dimensioni totali dei file
- Non più di 30.000 file
- Ogni file deve essere inferiore a 15 GB

### <a name="sync"></a>Sincronizza

Per ottenere prestazioni ottimali, è consigliabile archiviare non più di 300.000 file in una singola raccolta siti di OneDrive o del team. Anche se SharePoint Online può archiviare 30 milioni documenti per raccolta, per ottenere prestazioni ottimali, è consigliabile sincronizzare non più di 300.000 file in tutte le raccolte documenti. Inoltre, gli stessi problemi di prestazioni possono verificarsi se sono presenti 300.000 elementi o più in tutte le raccolte di cui si esegue la sincronizzazione, anche se non si sincronizzano tutti gli elementi di tali raccolte. Se si utilizza il client di sincronizzazione di OneDrive for business precedente (Groove.exe), il limite di sincronizzazione per ogni raccolta è 20.000 elementi (inclusi 5.000 elementi per sito del team).

### <a name="versions"></a>Versioni

50.000 versioni principali e versioni secondarie 511.

### <a name="sharepoint-groups"></a>Gruppi di SharePoint

Un utente può appartenere a 5.000 gruppi per sito (raccolta siti) e ogni gruppo può avere fino a 5.000 utenti. È possibile disporre di un massimo di 10.000 gruppi per sito (raccolta siti).

> [!NOTE]
> Per i limiti dei gruppi di Azure AD, vedere [limiti e limitazioni del servizio di Azure ad](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) in quanto tali limiti possono influire sulla gestione dell'appartenenza dei siti del gruppo pubblico e privato.

### <a name="managed-metadata"></a>Metadati gestiti

200.000 termini in archivio terminologico, set di termini globali 1.000, gruppi 1.000.

### <a name="overall-site-metadata"></a>Metadati del sito complessivi

1000 GB per sito (i metadati raggiungono raramente queste dimensioni).

### <a name="subsites"></a>Siti secondari

2.000 per sito (raccolta siti). Si consiglia di creare siti e di organizzarli in hub anziché in siti secondari. Se si utilizzano i siti secondari, è consigliabile limitarne il numero (in particolare in luoghi fortemente trafficati).

> [!NOTE]
> Il limite è di 2.000 siti hub per organizzazione. Potrebbe non essere necessario un sito hub per tutte le funzioni ed è importante eseguire alcune operazioni di pianificazione prima di creare hub. Per ulteriori informazioni, vedere [Planning your SharePoint Hub sites](https://docs.microsoft.com/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Applicazioni ospitate da SharePoint

20.000 istanze per ogni organizzazione.

### <a name="users"></a>Utenti

2 milioni per raccolta siti.

> [!NOTE]
> Non vi sono limiti distinti per il numero di ospiti che è possibile invitare a siti di SharePoint. Per ulteriori informazioni sulla condivisione esterna, vedere [Panoramica della condivisione esterna](https://docs.microsoft.com/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vedere anche

[Limiti della ricerca per SharePoint](https://docs.microsoft.com/sharepoint/search-limits)
