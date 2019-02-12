---
title: Limiti di SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Trovare i limiti di SharePoint Online per piani di Office 365 Enterprise e per piani autonomi.
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848691"
---
# <a name="sharepoint-online-limits"></a>Limiti di SharePoint Online

Trova i limiti di SharePoint per piani di Office 365 e i piani SharePoint Online autonomi.
  
## <a name="limits-by-plan"></a>Limiti in base alla pianificazione

|||||
|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Office 365 nozioni di base sulla Business o Business Premium** <br/> |**Office 365 Enterprise E1, E3, o E5 o SharePoint Online, piano 1 o 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Spazio di archiviazione<sup>1, 2</sup> <br/> |1 TB per organizzazione più di 10 GB per acquistato la licenza  <br/> |1 TB per organizzazione più di 10 GB per la licenza acquistata<sup>3</sup> <br/> |1 TB per ogni organizzazione<sup>3</sup> <br/> |
|Spazio di archiviazione per raccolte siti  <br/> |Fino a 25 TB per raccolta siti o gruppo<sup>4</sup> <br/> |Fino a 25 TB per raccolta siti o gruppo<sup>4</sup> <br/> |Fino a 25 TB per raccolta siti o gruppo<sup>5</sup> <br/> |
|Raccolte siti per l'organizzazione  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> | 500.000<br/> |
|Numero di utenti  <br/> |Fino a 300  <br/> |1- 500.000<sup>7</sup> <br/> |1- 500.000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> è possibile acquistare una quantità di spazio di archiviazione aggiuntivo SharePoint Online illimitata. Vedere [spazio di archiviazione di modifica per la sottoscrizione](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C).<br/><sup>2</sup> si consiglia di monitoraggio del Cestino e svuotamento regolarmente. Lo spazio di archiviazione che viene utilizzato il metodo fa parte del limite di archiviazione totale di file dell'organizzazione.<br/> <sup>3</sup> Quando si dispone di una sottoscrizione a Office 365 e di un piano autonomo SharePoint Online, vengono aggiunte quantità di spazio di archiviazione.<br/><sup>4</sup> gli amministratori di SharePoint Online è possono impostare limiti di archiviazione per siti e raccolte siti.<br/> <sup>5</sup> dipendenti dei chioschi possono amministrare le raccolte siti di SharePoint Online. È necessario almeno una licenza utente aziendale per gestire le raccolte siti chiosco multimediale.<br/> <sup>6</sup> Sono escluse le raccolte siti di OneDrive for Business create per ogni licenza utente.<br/><sup>7</sup> Se si dispone di più di 500.000 utenti, contattare un rappresentante Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Limiti relativi al servizio per tutti i piani

- **Gli elementi in elenchi e raccolte** - un elenco può avere fino a 30 milioni di elementi e una raccolta può avere fino a 30 milioni di file e cartelle. Visualizzazioni possono avere fino a 12 colonne di ricerca. Per ulteriori informazioni sulle limitazioni aggiuntive per la visualizzazione di elenchi di grandi dimensioni, vedere [gestire elenchi di grandi dimensioni e le raccolte di Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Per informazioni sui caratteri che non possono essere utilizzati nei nomi di file, vedere [caratteri non validi in nomi di file e cartelle](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Dimensioni dei file e lunghezza del percorso del file** - 15 GB. Per ulteriori informazioni sui limiti e restrizioni quando si utilizza il nuovo client di sincronizzazione OneDrive (OneDrive.exe), vedere [i nomi di file valido e tipi di file in OneDrive, OneDrive for Business e SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Sync** - per garantire prestazioni ottimali, è consigliabile archiviare i file non più di 300.000 in una singola raccolta siti di team o OneDrive. Sebbene SharePoint Online può archiviare i documenti di 30 milioni per raccolta, per ottimizzare le prestazioni è consigliabile sincronizzare i file non più di 300.000 tra tutte le raccolte documenti. Inoltre, gli stessi problemi di prestazioni possono verificarsi se si dispone di più di 300.000 elementi tra tutte le raccolte che vengono sincronizzazione in corso, anche se non si sono sincronizzazione tutti gli elementi in tali raccolte. Se si utilizza il precedente OneDrive per client di sincronizzazione Business (Groove.exe), il limite di sincronizzazione per ogni raccolta è 20.000 elementi (inclusi 5.000 voci per sito del team).

- **Versioni** : 50.000 versioni principali e 511 versioni secondarie.

- **Gruppi di SharePoint** - un utente può appartenere ai 5.000 gruppi e ogni gruppo può avere fino a 5.000 utenti. È possibile creare gruppi fino a 10.000 per raccolta siti.

- **Metadati gestiti** - 200.000 termini nell'archivio termini, set di termini globali 1.000, 1.000 gruppi.

- **I siti secondari** - fino a 2.000 per raccolta siti.

- **Applicazioni ospitate SharePoint** - 20.000 istanze per ogni organizzazione.

- **Gli ambiti di ricerca univoci per ogni elenco o raccolta** - 5.000. Per gli elenchi di grandi dimensioni, progettazione disporre di autorizzazioni esclusive il minor numero possibile.

- **Gli utenti** - 2 milioni per raccolta siti.

> [!NOTE]
> [!NOTA] Non sono previsti limiti per il numero di utenti esterni che è possibile invitare per le raccolte siti di SharePoint Online. Per altre informazioni, vedere [Gestire la condivisione esterna per l'ambiente di SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vedere anche

[Limiti relativi alla ricerca per SharePoint Online](/sharepoint/search-limits)