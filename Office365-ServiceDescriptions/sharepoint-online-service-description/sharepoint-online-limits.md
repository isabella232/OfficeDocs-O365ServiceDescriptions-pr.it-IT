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
description: Informazioni sui limiti di SharePoint per Microsoft 365 e i piani autonomi.
ms.openlocfilehash: 60a9fc63c60952ef8a71706d79ddac055fecc887
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172611"
---
# <a name="sharepoint-limits"></a>Limiti di SharePoint

Informazioni sui limiti del servizio in SharePoint per Microsoft 365.
  
## <a name="limits-by-plan"></a>Limiti per piano 

| Funzionalità | Microsoft 365 Business Basic, Business Standard o Business Premium | Microsoft 365 E3 o E5, Office 365 E1, E3 o E5 o SharePoint Piano 1 o 2 | Microsoft 365 F1 o F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Spazio di archiviazione totale per<sup>organizzazione 1, 2, 6</sup> <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup>  <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Spazio di archiviazione massimo per sito (raccolta siti)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Siti (raccolte siti) per organizzazione  <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<br/> |
|Numero di utenti  <br/> |Fino a 300  <br/> |1- 500.000<sup>7</sup> <br/> |1- 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [Informazioni su come trovare lo spazio di archiviazione totale e disponibile per l'organizzazione.](/sharepoint/manage-site-collection-storage-limits) È possibile acquistare una quantità illimitata di spazio di archiviazione aggiuntivo di SharePoint. Vedere [Modificare lo spazio di archiviazione per l'abbonamento](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Si consiglia di monitorare il Cestino e svuotarlo regolarmente. Lo spazio di archiviazione utilizzato fa parte del limite totale di archiviazione dell'organizzazione. 
<br/> <sup>3</sup> Se si dispone di un abbonamento a Microsoft 365 e di un componente aggiuntivo Di archiviazione file aggiuntivo di Office 365, vengono aggiunte le quantità di spazio di archiviazione. 
<br/> <sup>4</sup> Questo è il limite *di* archiviazione per un singolo sito (in precedenza denominato "raccolta siti"), non la quantità di spazio di archiviazione fornita *per* ogni sito. Questo limite si applica a tutti i tipi di siti, inclusi i siti del team connessi a gruppi di Office 365 e OneDrive. Gli amministratori di SharePoint possono [impostare manualmente limiti di archiviazione inferiori.](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits) 
<br/> <sup>5</sup> Firstline Workers non può amministrare i siti di SharePoint. 
<br/> <sup>6</sup> Non è incluso OneDrive creato per ogni utente con licenza. 
<br/> <sup>7</sup> Se si dispone di più di 500.000 utenti, contattare un rappresentante Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limiti del servizio per tutti i piani

### <a name="items-in-lists-and-libraries"></a>Elementi in elenchi e raccolte

Un elenco può contenere fino a 30 milioni di elementi e una raccolta può contenere fino a 30 milioni di file e cartelle. Quando un elenco, una raccolta o una cartella contiene più di 100.000 elementi, non è possibile interrompere l'ereditarietà delle autorizzazioni per l'elenco, la raccolta o la cartella. Non è inoltre possibile ereditare nuovamente le autorizzazioni su di esso. Tuttavia, è comunque possibile interrompere l'ereditarietà per i singoli elementi all'interno di tale elenco, raccolta o cartella, fino al numero massimo di autorizzazioni univoche nell'elenco o nella raccolta (vedere la sezione successiva). Per ulteriori informazioni sulle altre restrizioni per la visualizzazione di elenchi di grandi dimensioni, vedere Gestire elenchi e raccolte di grandi dimensioni [in Office 365.](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)

### <a name="unique-security-scopes-per-list-or-library"></a>Ambiti di sicurezza univoci per elenco o raccolta

Per gli elenchi di grandi dimensioni, progettare in modo da avere il maggior numero possibile di autorizzazioni univoche e rimanere al di sotto di 5.000 in totale.

### <a name="file-size-and-file-path-length"></a>Dimensioni e lunghezza del percorso del file

250 GB. Per altre informazioni sulle restrizioni e sui limiti quando si usa la nuova app di sincronizzazione di OneDrive (OneDrive.exe), vedere Nomi di file e tipi [di file non validi.](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)

### <a name="moving-and-copying-across-sites"></a>Spostamento e copia tra siti

La copia/lo spostamento di più file in una singola operazione presenta tre requisiti:

- Non più di 100 GB di dimensione totale dei file
- Non più di 30.000 file
- Ogni file deve essere inferiore a 15 GB

### <a name="sync"></a>Sincronizza

Per ottenere prestazioni ottimali, è consigliabile archiviare non più di 300.000 file in una singola raccolta di OneDrive o del sito del team. Sebbene SharePoint Online sia in grado di archiviare 30 milioni di documenti per raccolta, per ottenere prestazioni ottimali è consigliabile sincronizzare non più di 300.000 file in tutte le raccolte documenti. Inoltre, gli stessi problemi di prestazioni possono verificarsi se si dispone di 300.000 elementi o più in tutte le raccolte che si sta sincronizzando, anche se non si sincronizzano tutti gli elementi in tali raccolte. Se si utilizza il client di sincronizzazione di OneDrive for Business precedente (Groove.exe), il limite di sincronizzazione per raccolta è 20.000 elementi (inclusi 5.000 elementi per sito del team).

### <a name="versions"></a>Versioni

50.000 versioni principali e 511 versioni secondarie.

### <a name="sharepoint-groups"></a>Gruppi di SharePoint

Un utente può appartenere a 5.000 gruppi per sito (raccolta siti) e ogni gruppo può avere fino a 5.000 utenti. È possibile avere fino a 10.000 gruppi per sito (raccolta siti).

> [!NOTE]
> Per i limiti dei gruppi di Azure AD, vedere Limiti e restrizioni del servizio [Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) in quanto tali limiti possono influire sulla gestione dell'appartenenza a siti di gruppi pubblici e privati.

### <a name="managed-metadata"></a>Metadati gestiti

200.000 termini nell'archivio termini, 1.000 set di termini globali, 1.000 gruppi.

### <a name="overall-site-metadata"></a>Metadati complessivi del sito

1000 GB per sito (i metadati raggiungono raramente queste dimensioni).

### <a name="subsites"></a>Siti secondari

2.000 per sito (raccolta siti). È consigliabile creare siti e organizzarli in hub anziché creare siti secondari. Se si utilizzano siti secondari, è consigliabile limitarne il numero(soprattutto nei siti con traffico intenso).

> [!NOTE]
> Il limite è di 2.000 siti hub per organizzazione. Potrebbe non essere necessario un sito hub per ogni funzione ed è importante eseguire alcune attività di pianificazione prima di creare hub. Per ulteriori informazioni, visitare [Pianificazione dei siti hub di SharePoint.](/sharepoint/planning-hub-sites)

### <a name="sharepoint-hosted-applications"></a>Applicazioni ospitate in SharePoint

20.000 istanze per organizzazione.

### <a name="users"></a>Utenti

2 milioni per raccolta siti.

> [!NOTE]
> Non esiste un limite distinto al numero di guest che è possibile invitare nei siti di SharePoint. Per ulteriori informazioni sulla condivisione esterna, vedere [Panoramica della condivisione esterna.](/sharepoint/external-sharing-overview)

## <a name="see-also"></a>Vedere anche

[Limiti di ricerca per SharePoint](/sharepoint/search-limits)