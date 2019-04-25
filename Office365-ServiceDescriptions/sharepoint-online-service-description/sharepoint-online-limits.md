---
title: Limiti di SharePoint Online
ms.author: sharik
author: skjerland
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Trovare i limiti di SharePoint Online per piani di Office 365 Enterprise e per piani autonomi.
ms.openlocfilehash: c1b6185c46be6f1343e6679a5b887bab5b393708
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246612"
---
# <a name="sharepoint-online-limits"></a>Limiti di SharePoint Online

Trovare i limiti di SharePoint per i piani di Office 365 e i piani autonomi di SharePoint Online.
  
## <a name="limits-by-plan"></a>Limiti in base alla pianificazione

|||||
|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Office 365 Business Essentials o Business Premium** <br/> |**Office 365 Enterprise E1, E3 o E5 o SharePoint Online (piano 1 o 2)** <br/> | **Office 365 Enterprise F1** <br/> |
|Spazio di archiviazione<sup>1, 2</sup> <br/> |1 TB per ogni organizzazione più 10 GB per licenza acquistata  <br/> |1 TB per ogni organizzazione più 10 GB per licenza acquistata<sup>3</sup> <br/> |1 TB per ogni organizzazione<sup>3</sup> <br/> |
|Spazio di archiviazione per raccolte siti  <br/> |Fino a 25 TB per raccolta siti o gruppo<sup>4</sup> <br/> |Fino a 25 TB per raccolta siti o gruppo<sup>4</sup> <br/> |Fino a 25 TB per raccolta siti o gruppo<sup>5</sup> <br/> |
|Raccolte siti per ogni organizzazione  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> | 500.000<br/> |
|Numero di utenti  <br/> |Fino a 300  <br/> |1- 500.000<sup>7</sup> <br/> |1- 500.000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> È possibile acquistare una quantità illimitata di spazio di archiviazione SharePoint Online aggiuntivo. Vedere [Modificare lo spazio di archiviazione per l'abbonamento](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C). 
<br/><sup>2</sup> Si consiglia di monitorare il Cestino e svuotarlo regolarmente. Lo spazio di archiviazione utilizzato è compreso nel limite di archiviazione file totale dell'organizzazione. 
<br/> <sup>3</sup> Quando si dispone di una sottoscrizione a Office 365 e di un piano autonomo SharePoint Online, vengono aggiunte quantità di spazio di archiviazione. 
<br/><sup>4</sup> gli amministratori di SharePoint Online possono impostare limiti di spazio di archiviazione per le raccolte e i siti del sito.
<br/> <sup>5</sup> Gli operatori di chioschi multimediali non possono amministrare le raccolte siti di SharePoint Online. È necessario disporre di almeno una licenza utente Enterprise per gestire le raccolte siti di chioschi multimediali. 
<br/> <sup>6</sup> Sono escluse le raccolte siti di OneDrive for Business create per ogni licenza utente. 
<br/><sup>7</sup> Se si dispone di più di 500.000 utenti, contattare un rappresentante Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Limiti di servizio per tutti i piani

- **Elementi in elenchi e raccolte** : un elenco può avere fino a 30 milioni elementi e una raccolta può avere fino a 30 milioni file e cartelle. Le visualizzazioni possono avere fino a 12 colonne di ricerca. Per ulteriori informazioni sulle altre limitazioni per la visualizzazione di elenchi di grandi dimensioni, vedere [gestire elenchi di grandi dimensioni e raccolte in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Per informazioni sui caratteri che non possono essere utilizzati nei nomi di file, vedere [caratteri non validi nei nomi di file e cartelle](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Dimensione del file e lunghezza del percorso del file** -15 GB. Per ulteriori informazioni sulle restrizioni e sui limiti quando si utilizza il nuovo client di sincronizzazione di OneDrive (OneDrive. exe), vedere nomi di file [e tipi di file non validi in OneDrive, OneDrive for business e SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Spostamento e copia tra raccolte siti** -100 GB per operazione. Il Web browser deve rimanere aperto.

- **Sincronizzazione** : per ottenere prestazioni ottimali, è consigliabile archiviare non più di 300.000 file in una singola raccolta siti di OneDrive o del team. Anche se SharePoint Online può archiviare 30 milioni documenti per raccolta, per ottenere prestazioni ottimali, è consigliabile sincronizzare non più di 300.000 file in tutte le raccolte documenti. Inoltre, gli stessi problemi di prestazioni possono verificarsi se sono presenti 300.000 elementi o più in tutte le raccolte di cui si esegue la sincronizzazione, anche se non si sincronizzano tutti gli elementi di tali raccolte. Se si utilizza il client di sincronizzazione precedente di OneDrive for business (Groove. exe), il limite di sincronizzazione per ogni raccolta è 20.000 elementi (inclusi 5.000 elementi per sito del team).

- **** Versions-50.000 Major Versions e 511 versioni secondarie.

- **Gruppi di SharePoint** : un utente può appartenere a gruppi di 5.000 e ciascun gruppo può avere fino a 5.000 utenti. È possibile avere fino a 10.000 gruppi per ogni raccolta siti.

- **Managed Metadata** -200.000 termini in Store termine, 1.000 set termini globali, 1.000 gruppi.

- **Siti secondari** : fino a 2.000 per ogni raccolta siti.

- **Applicazioni ospitate in SharePoint** -20.000 istanze per ogni organizzazione.

- **Ambiti di sicurezza univoci per elenco o raccolta** -5.000. Per gli elenchi di grandi dimensioni, la progettazione deve disporre di un numero di autorizzazioni univoco possibile.

- **Users** -2 milioni per ogni raccolta siti.

> [!NOTE]
> Non esiste alcun limite al numero di utenti esterni che è possibile invitare alle raccolte siti di SharePoint Online. Per ulteriori informazioni, vedere [gestire la condivisione esterna per l'ambiente di SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vedere anche

[Limiti della ricerca per SharePoint Online](/sharepoint/search-limits)