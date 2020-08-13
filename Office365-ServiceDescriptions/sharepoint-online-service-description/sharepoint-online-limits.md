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
ms.openlocfilehash: a8b42885b558d04aee0ed3743cffc203dde2f248
ms.sourcegitcommit: 3ad5d292cc16367a4b7ecd60aad6329130cc594a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/12/2020
ms.locfileid: "46649596"
---
# <a name="sharepoint-limits"></a>Limiti di SharePoint

Informazioni sui limiti di servizio in SharePoint per Microsoft 365.
  
## <a name="limits-by-plan"></a>Limiti in base alla pianificazione 

|||||
|:-----|:-----|:-----|:-----|
|**Caratteristica** <br/> |**Microsoft 365 Business Basic, business standard o Business Premium** <br/> |**Microsoft 365 E3 o E5, Office 365 Enterprise E1, E3 o E5 oppure SharePoint piano 1 o 2** <br/> | **Microsoft 365 F1 o F3, Office 365 Enterprise F3** <br/> |
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
<br/> <sup>7</sup> Se si dispone di più di 500.000 utenti, contattare un rappresentante Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limiti di servizio per tutti i piani

### <a name="items-in-lists-and-libraries"></a>Elementi in elenchi e raccolte

Un elenco può avere fino a 30 milioni elementi e una raccolta può avere fino a 30 milioni file e cartelle. Quando un elenco, una raccolta o una cartella contiene più di 100.000 elementi, non è possibile interrompere l'ereditarietà delle autorizzazioni nell'elenco, nella raccolta o nella cartella. Non è possibile ereditare nuovamente le autorizzazioni su di essa. Tuttavia, è comunque possibile interrompere l'ereditarietà nei singoli elementi all'interno di tale elenco, raccolta o cartella fino al numero massimo di autorizzazioni univoche nell'elenco o nella raccolta (vedere la sezione successiva). Per ulteriori informazioni sulle altre limitazioni per la visualizzazione di elenchi di grandi dimensioni, vedere [gestire elenchi di grandi dimensioni e raccolte in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

> [!NOTE]
> Non esiste alcun limite al numero di raccolte documenti che è possibile utilizzare in un sito.

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>Autorizzazioni esclusive per gli elementi di un elenco o di una raccolta

Il limite supportato è di 50.000 elementi con autorizzazioni univoche, ma il limite generale consigliato è 5.000. L'esecuzione di modifiche a più di 5.000 elementi con autorizzazioni univoche alla volta richiede più tempo. Per gli elenchi di grandi dimensioni, la progettazione deve disporre di un numero di autorizzazioni univoco possibile.

Un altro limite è 5.000 assegnazioni di ruolo per elemento con autorizzazioni univoche. 

### <a name="file-size-and-file-path-length"></a>Dimensione del file e lunghezza del percorso del file

100 GB. La dimensione massima per i file allegati alle voci di elenco è di 250 MB. Per ulteriori informazioni sulle restrizioni e sui limiti quando si utilizza la nuova app di sincronizzazione di OneDrive (OneDrive.exe), vedere [nomi di file e tipi di file non validi](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Spostamento e copia tra siti

La copia o lo spostamento di più file in una singola operazione ha tre requisiti: 

- Non più di 100 GB di dimensioni totali dei file 
- Non più di 30.000 file
- Ogni file deve essere inferiore a 2 GB

### <a name="sync"></a>Sincronizza

**Nuova app di sincronizzazione di OneDrive** -per ottenere prestazioni ottimali, è consigliabile archiviare non più di 300.000 file per utente in tutte le raccolte documenti sincronizzate, anche se si utilizzano file su richiesta o si sceglie solo alcune cartelle all'interno delle raccolte da sincronizzare.

**App di sincronizzazione di OneDrive for business precedente (Groove.exe)** : è possibile sincronizzare fino a 20.000 elementi totali in tutte le raccolte sincronizzate. Sono incluse le raccolte di OneDrive, le raccolte siti del team o entrambe. Indipendentemente dal limite di sincronizzazione globale, esistono limiti al numero di elementi che possono essere sincronizzati per ogni tipo di raccolta:

   - È possibile sincronizzare fino a 20.000 elementi in una raccolta di OneDrive. Sono inclusi i file e le cartelle. 
   - È possibile sincronizzare fino a 5.000 elementi in una raccolta di SharePoint. Sono inclusi i file e le cartelle. Si tratta di raccolte che si trovano in vari siti di SharePoint, ad esempio siti del team e siti community, raccolte create da altre persone o create dalla pagina siti. È possibile sincronizzare più raccolte di SharePoint. Tutti i siti del team sincronizzati conteranno anche rispetto al limite totale di 20.000 elementi in tutte le raccolte sincronizzate.

> [!NOTE]
> Se gli utenti devono sincronizzare i file nelle raccolte documenti che dispongono di centinaia di migliaia di file, è possibile "nascondere" le cartelle dall'app di sincronizzazione impostando il livello di autorizzazione delle cartelle su "lettura con restrizioni". 

### <a name="versions"></a>Versioni

50.000 versioni principali e versioni secondarie 511.

### <a name="sharepoint-groups"></a>Gruppi di SharePoint

Un utente può appartenere a 5.000 gruppi per sito (raccolta siti) e ogni gruppo può avere fino a 5.000 utenti. È possibile disporre di un massimo di 10.000 gruppi per sito (raccolta siti).

> [!NOTE]
> Per i limiti dei gruppi di Azure AD, vedere [limiti e limitazioni del servizio di Azure ad](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) in quanto tali limiti possono influire sulla gestione dell'appartenenza dei siti del gruppo pubblico e privato. 

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

### <a name="people-editing-a-document-at-the-same-time"></a>Utenti che modificano contemporaneamente un documento

99 gli utenti possono disporre di un documento aperto per la modifica nello stesso momento. Se più di 10 persone modificano un documento contemporaneamente, è più probabile che le modifiche siano in conflitto e l'esperienza utente diminuirà gradualmente.

### <a name="users"></a>Utenti

2 milioni per sito (raccolta siti).
   
> [!NOTE]
> Non esiste alcun limite al numero di ospiti che è possibile invitare a siti di SharePoint. Per ulteriori informazioni sulla condivisione esterna, vedere [Panoramica della condivisione esterna](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Vedere anche

[Limiti della ricerca per SharePoint](/sharepoint/search-limits)
