---
title: Limiti di SharePoint Online
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Trovare i limiti di SharePoint Online per piani di Office 365 Enterprise e per piani autonomi.
ms.openlocfilehash: 5a75e3b8f51feb6b6dc7318355b09e3e3cc4909f
ms.sourcegitcommit: fcfec093e77bafd9940d94c8c3439b2fa3e007f8
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/02/2019
ms.locfileid: "37932010"
---
# <a name="sharepoint-online-limits"></a>Limiti di SharePoint Online

Trovare i limiti di SharePoint per i piani di Office 365 e i piani autonomi di SharePoint Online.
  
## <a name="limits-by-plan"></a>Limiti in base alla pianificazione 

|||||
|:-----|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Office 365 Business Essentials o Business Premium** <br/> |**Office 365 Enterprise E1, E3 o E5 o SharePoint Online (piano 1 o 2)** <br/> | **Office 365 Enterprise F1** <br/> |
|Spazio di archiviazione totale per ogni organizzazione<sup>1, 2</sup> <br/> |1 TB più 10 GB per licenza acquistata  <br/> |1 TB più 10 GB per licenza acquistata<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Archiviazione massima per raccolta siti<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Raccolte siti per ogni organizzazione  <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<sup>6</sup> <br/> |2 milioni<br/> |
|Numero di utenti  <br/> |Fino a 300  <br/> |1- 500.000<sup>7</sup> <br/> |1- 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [informazioni su come trovare l'archiviazione totale e disponibile per l'organizzazione](/sharepoint/manage-site-collection-storage-limits). È possibile acquistare una quantità illimitata di ulteriore spazio di archiviazione di SharePoint. Vedere [Modificare lo spazio di archiviazione per l'abbonamento](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Si consiglia di monitorare il Cestino e svuotarlo regolarmente. Lo spazio di archiviazione utilizzato è parte integrante del limite di archiviazione totale dell'organizzazione. 
<br/> <sup>3</sup> se si dispone di un abbonamento a Office 365 e di un componente aggiuntivo per l'archiviazione di file di Office 365, vengono aggiunti gli importi di archiviazione. 
<br/> <sup>4</sup> questo è il limite di archiviazione per una singola raccolta siti e non per la quantità di spazio di archiviazione disponibile per ogni raccolta siti. Questo limite si applica a tutti i tipi di raccolte siti, inclusi i siti del team connessi a un gruppo di Office 365 e OneDrive. Gli amministratori di SharePoint possono [impostare manualmente limiti di spazio di archiviazione inferiori](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> gli addetti di FIRSTLINE non possono amministrare le raccolte siti di SharePoint. 
<br/> <sup>6</sup> non include il OneDrive creato per ogni utente con licenza. 
<br/> <sup>7</sup> Se si dispone di più di 500.000 utenti, contattare un rappresentante Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limiti di servizio per tutti i piani

- **Elementi in elenchi e raccolte** : un elenco può avere fino a 30 milioni elementi e una raccolta può avere fino a 30 milioni file e cartelle. Dopo che sono stati aggiunti 100.000 elementi a un elenco, una raccolta o una cartella, non è possibile modificare l'ereditarietà delle autorizzazioni per l'elenco, la raccolta o la cartella. Per ulteriori informazioni sulle altre limitazioni per la visualizzazione di elenchi di grandi dimensioni, vedere [gestire elenchi di grandi dimensioni e raccolte in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

- **Dimensione del file e lunghezza del percorso del file** -15 GB. La dimensione massima per i file allegati alle voci di elenco è di 250 MB. Per ulteriori informazioni sulle restrizioni e sui limiti quando si utilizza il nuovo client di sincronizzazione di OneDrive (OneDrive. exe), vedere nomi di file [e tipi di file non validi](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Spostamento e copia tra raccolte siti** -100 GB per operazione. Il Web browser deve rimanere aperto.

- **Sincronizzazione** : per ottenere prestazioni ottimali, è consigliabile archiviare non più di 300.000 file in tutte le raccolte documenti sincronizzate, anche se si utilizzano file su richiesta oppure se si sceglie solo alcune cartelle all'interno delle raccolte da sincronizzare.

    Se si utilizza il client di sincronizzazione precedente di OneDrive for business (Groove. exe), è possibile sincronizzare fino a 20.000 elementi totali in tutte le raccolte sincronizzate. Sono incluse le librerie di OneDrive for business, le raccolte siti del team o entrambe. Indipendentemente dal limite di sincronizzazione globale, esistono limiti al numero di elementi che possono essere sincronizzati per ogni tipo di raccolta:
    - È possibile sincronizzare fino a 20.000 elementi in una raccolta di OneDrive for business. Sono inclusi i file e le cartelle. 
    - È possibile sincronizzare fino a 5.000 elementi in una raccolta di SharePoint. Sono inclusi i file e le cartelle. Si tratta di raccolte che si trovano in vari siti di SharePoint, ad esempio siti del team e siti community, raccolte create da altre persone o create dalla pagina siti. È possibile sincronizzare più raccolte di SharePoint. Tutti i siti del team sincronizzati conteranno anche rispetto al limite totale di 20.000 elementi in tutte le raccolte sincronizzate.

    > [!NOTE]
    > Se gli utenti devono sincronizzare i file nelle raccolte documenti che dispongono di centinaia di migliaia di file, è possibile "nascondere" le cartelle dal client di sincronizzazione impostando il livello di autorizzazione delle cartelle su "lettura con restrizioni". 

- **Versions-50.000** Major Versions e 511 versioni secondarie.

- **Gruppi di SharePoint** : un utente può appartenere a gruppi di 5.000 e ciascun gruppo può avere fino a 5.000 utenti. È possibile avere fino a 10.000 gruppi per ogni raccolta siti.
    > [!NOTE]
    > Per i limiti dei gruppi di Azure AD, vedere [limiti e limitazioni del servizio di Azure ad](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) in quanto tali limiti possono influire sulla gestione dell'appartenenza dei siti del gruppo pubblico e privato. 
- **Managed Metadata** -200.000 termini in Store termine, 1.000 set termini globali, 1.000 gruppi.

- **Siti secondari** -2.000 per raccolta siti.

- **Applicazioni ospitate in SharePoint** -20.000 istanze per ogni organizzazione.

- **Ambiti di sicurezza univoci per elenco o raccolta** -5.000. Per gli elenchi di grandi dimensioni, la progettazione deve disporre di un numero di autorizzazioni univoco possibile.

- **Users** -2 milioni per ogni raccolta siti.
    > [!NOTE]
    > Non esiste alcun limite al numero di ospiti che è possibile invitare alle raccolte siti di SharePoint. Per ulteriori informazioni sulla condivisione esterna, vedere [Panoramica della condivisione esterna](https://docs.microsoft.com/sharepoint/external-sharing-overview).
## <a name="see-also"></a>Vedere anche

[Limiti della ricerca per SharePoint Online](https://docs.microsoft.com/sharepoint/search-limits)
