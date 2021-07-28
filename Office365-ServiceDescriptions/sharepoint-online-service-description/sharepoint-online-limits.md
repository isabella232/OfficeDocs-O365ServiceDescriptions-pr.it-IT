---
title: Limiti di SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Informazioni sui limiti di SharePoint per Microsoft 365 e i piani autonomi.
ms.openlocfilehash: 44571cedf74b2a094231173b87731916d9e26975
ms.sourcegitcommit: 10699cc17ddfed6af78ce1466f478b2bd67ba26a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/08/2021
ms.locfileid: "53338339"
---
# <a name="sharepoint-limits"></a>Limiti di SharePoint

Informazioni sui limiti del servizio in SharePoint per Microsoft 365.
  
## <a name="limits-by-plan"></a>Limiti in base al piano 

| Funzionalità | Microsoft 365 Business Basic, Business Standard o Business Premium | Microsoft 365 E3 o E5, Office 365 E1, E3 o E5 o SharePoint Piano 1 o Piano 2 | Microsoft 365 F1 o F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Spazio di archiviazione totale per organizzazione<sup>1, 2, 6</sup> <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup>  <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Spazio di archiviazione massimo per sito (raccolta siti)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Siti (raccolte siti) per organizzazione  <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<br/> |
|Numero di utenti  <br/> |Fino a 300  <br/> |1- 500.000<sup>7</sup> <br/> |1- 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [Informazioni su come individuare lo spazio di archiviazione totale disponibile per l'organizzazione](/sharepoint/manage-site-collection-storage-limits). È possibile acquistare una quantità illimitata di spazio di archiviazione di SharePoint aggiuntivo. Vedere [Aggiungere spazio di archiviazione all'abbonamento](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Si consiglia di monitorare il Cestino e di svuotarlo regolarmente. Lo spazio di archiviazione utilizzato è compreso nel limite di archiviazione totale dell'organizzazione. 
<br/> <sup>3</sup> Se si dispone di un abbonamento a Microsoft 365 e di un componente di archiviazione dei file aggiuntivo di Office 365, vengono aggiunte le quantità di archiviazione. 
<br/> <sup>4</sup> Questo è il *limite* di archiviazione per un singolo sito (in precedenza denominato "raccolta siti"), non la quantità di spazio di archiviazione *fornito* per ogni sito. Questo limite si applica a tutti i tipi di siti, inclusi i siti del team connessi al gruppo di Office 365 e OneDrive. Gli amministratori di SharePoint possono [impostare manualmente limiti di archiviazione più bassi](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> Gli operatori sul campo non possono amministrare i siti di SharePoint. 
<br/> <sup>6</sup> Non è incluso OneDrive creato per ogni utente con licenza. 
<br/> <sup>7</sup> Se si hanno più di 500.000 utenti, contattare un rappresentante Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limiti di servizio per tutti i piani

### <a name="items-in-lists-and-libraries"></a>Elementi negli elenchi e nelle raccolte

Un elenco può contenere fino a 30 milioni di elementi e una raccolta può contenere fino a 30 milioni di file e cartelle. Quando un elenco, una raccolta o una cartella contiene più di 100.000 elementi, non è possibile interrompere l'ereditarietà delle autorizzazioni nell'elenco, nella raccolta o nella cartella. Né è possibile ereditare di nuovo le autorizzazioni su di essi. Tuttavia, è comunque possibile interrompere l'ereditarietà dei singoli elementi all'interno dell'elenco, raccolta o cartella, fino al numero massimo di autorizzazioni univoche nell'elenco o nella raccolta (vedere la sezione successiva). Per maggiori informazioni su altre limitazioni per la visualizzazione di elenchi di grandi dimensioni, vedere [Gestire elenchi e raccolte di grandi dimensioni in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Ambiti di sicurezza univoci per elenchi o raccolte

Per gli elenchi di grandi dimensioni, fare in modo di disporre del minor numero possibile di autorizzazioni univoche e rimanere al di sotto di 5.000 autorizzazioni totali.

### <a name="file-size-and-file-path-length"></a>Dimensioni del file e lunghezza del percorso

- **250 GB - Limite caricamento file.** Si applica a ogni singolo file caricato nella scheda File di Microsoft Teams, nelle raccolte documenti di SharePoint, nelle cartelle di OneDrive e nelle conversazioni di Yammer.

- **250 MB - File allegato a una voce di elenco.** Si applica a Elenchi Microsoft e a Elenchi di SharePoint, entrambi basati sulla stessa piattaforma di elenchi.

Per altre informazioni sulle restrizioni e sui limiti durante l'uso della nuova app di sincronizzazione di OneDrive (OneDrive.exe), vedere [Nomi e tipi di file non validi](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Spostamento e copia tra siti

La copia o lo spostamento di più file con una singola operazione prevede tre requisiti:

- Dimensione totale del file non superiore a 100 GB
- Non più di 30.000 file
- La dimensione di ciascun file deve essere inferiore a 15 GB

### <a name="sync"></a>Sincronizzazione

Per ottenere prestazioni ottimali, è consigliabile archiviare non più di 300.000 file in ogni singola raccolta di OneDrive o raccolta documenti del sito del team. Anche se SharePoint Online può archiviare 30 milioni di documenti per ogni raccolta, per ottenere prestazioni ottimali è consigliabile sincronizzare non più di 300.000 file in tutte le raccolte documenti. Inoltre, gli stessi problemi di prestazioni possono verificarsi se sono presenti 300.000 o più elementi in tutte le raccolte sincronizzate, anche se non si stanno sincronizzando tutti gli elementi di tali raccolte. Se si usa il client di sincronizzazione di OneDrive for Business precedente (Groove.exe), il limite di sincronizzazione per ogni raccolta è di 20.000 elementi, inclusi 5.000 elementi per sito del team.

### <a name="versions"></a>Versioni

50.000 versioni principali e 511 versioni secondarie.

### <a name="sharepoint-groups"></a>Gruppi di SharePoint

Un utente può appartenere a 5.000 gruppi per sito (raccolta siti) e in ogni gruppo possono essere presenti fino a 5.000 utenti. Possono essere presenti fino a 10.000 gruppi in un sito (raccolta siti).

> [!NOTE]
> Per i limiti dei gruppi di Azure AD, vedere [Limiti e restrizioni del servizio di Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) poiché tali limiti possono influire sulla gestione delle appartenenze ai siti di gruppi pubblici e privati.

### <a name="managed-metadata"></a>Metadati gestiti

1 milione di termini totali, con un totale di 2 milioni di etichette dei termini e 1 milione di proprietà dei termini. Tali limiti sono combinati per termini globali e a livello di sito. 1.000 set di termini globali e 1.000 gruppi globali.

### <a name="overall-site-metadata"></a>Metadati complessivi del sito

1000 GB per sito (i metadati raramente raggiungono questa dimensione).

### <a name="subsites"></a>Siti secondari

2.000 per sito (raccolta siti). Anziché creare siti secondari, è consigliabile creare siti e organizzarli in hub. Se si usano siti secondari, è consigliabile limitarne il numero, soprattutto nei siti con traffico elevato.

> [!NOTE]
> Il limite è di 2.000 siti hub per organizzazione. Non è indispensabile avere un sito hub per ogni funzione e prima di creare hub è importante dedicare del tempo alla pianificazione. Per maggiori informazioni, visitare [Pianificazione dei siti hub di SharePoint](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Applicazioni ospitate in SharePoint

20.000 istanze per organizzazione.

### <a name="users"></a>Utenti

2 milioni per raccolta siti.

> [!NOTE]
> Non esiste un limite specifico al numero di utenti guest che è possibile invitare nei siti di SharePoint. Per altre informazioni sulla condivisione esterna, vedere [Panoramica della condivisione esterna](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vedere anche

[Limiti della ricerca in SharePoint ](/sharepoint/search-limits)