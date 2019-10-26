---
title: Cerca
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online è una raccolta di tecnologie e strumenti basati sul Web che consentono all'organizzazione di archiviare, condividere e gestire le informazioni digitali. Concepito per Microsoft SharePoint Server 2013, è un servizio ospitato ideale per elaborare progetti, archiviare dati e documenti in una posizione centrale e condividere le informazioni. Le seguenti funzionalità di ricerca consentono agli utenti di individuare le informazioni necessarie per il proprio lavoro. La ricerca è una combinazione di pertinenza, perfezionamento e contatti.
ms.openlocfilehash: 39fdeaac67d1c7261e93dd45c4181613910d5ed0
ms.sourcegitcommit: 05458701350d269dce45c9a0812d67d653c52621
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/25/2019
ms.locfileid: "37726202"
---
# <a name="search"></a>Ricerca

SharePoint Online è una raccolta di tecnologie e strumenti basati sul Web che consentono all'organizzazione di archiviare, condividere e gestire le informazioni digitali. Concepito per Microsoft SharePoint Server 2013, è un servizio ospitato ideale per elaborare progetti, archiviare dati e documenti in una posizione centrale e condividere le informazioni. Le seguenti funzionalità di ricerca consentono agli utenti di individuare le informazioni necessarie per il proprio lavoro. La ricerca è una combinazione di pertinenza, perfezionamento e contatti.
  
## <a name="continuous-crawls"></a>Ricerche per indicizzazione continue

Le ricerche per indicizzazione continue aiutano a mantenere i risultati della ricerca aggiornati grazie a frequenti ricerche per indicizzazione del contenuto nei siti di SharePoint. Si tratta di ricerche abilitate in SharePoint Online, la cui frequenza di ricerca per indicizzazione è gestita da Microsoft. In SharePoint Server 2013, gli amministratori possono attivare le ricerche per indicizzazione continue e gestire le frequenze di ricerca per indicizzazione continue. Ulteriori informazioni sulle [estensioni file predefinite per la ricerca per indicizzazione e tipi di file in SharePoint analizzati](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types). Ulteriori informazioni sulla [gestione delle ricerche per indicizzazione continue](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls).
  
## <a name="deep-links"></a>Collegamenti diretti

Il sistema di ricerca crea collegamenti in modo automatico direttamente alle sottosezioni di una pagina principale visitata di frequente. Tali collegamenti sono chiamati "collegamenti diretti". Ulteriori informazioni sul [sistema di ricerca di SharePoint](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint).
  
## <a name="event-based-relevancy"></a>Pertinenza basata su eventi

Il sistema di ricerca determina in parte la pertinenza dei risultati della ricerca in base al modo in cui il contenuto viene connesso, alla frequenza con cui un elemento viene visualizzato nei risultati di ricerca e ai risultati della ricerca selezionati dalle persone. Il componente analisi tiene traccia e analizza i dati, utilizzandoli per migliorare continuamente la pertinenza. Ulteriori informazioni sull'[elaborazione dell'analisi](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing).
  
## <a name="expertise-search"></a>Ricerca per esperienze

In SharePoint, è più facile trovare persone con competenze o conoscenze specifiche nel segmento verticale Ricerca utenti. I risultati della ricerca si basano su informazioni quali i metadati con informazioni personali immessi dagli utenti nei siti personali e le informazioni ricavate dal contenuto creato dagli utenti. Ulteriori informazioni sulla [modifica delle impostazioni verticali di ricerca](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part).
  
## <a name="graphical-refiners"></a>Criteri di affinamento grafici

I nuovi criteri di affinamento grafici offrono una modalità più visiva di filtrare i risultati della ricerca. Ulteriori informazioni sulla [configurazione di web part di perfezionamento](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).
  
## <a name="hybrid-search"></a>Ricerca ibrida

Nella distribuzione ibrida di SharePoint, il contenuto dei risultati della ricerca può provenire dai siti locali di SharePoint Online e di SharePoint Server 2013. Per ulteriori informazioni su un ambiente SharePoint ibrido, vedere [Ambiente ibrido per SharePoint Server 2013](https://docs.microsoft.com/SharePoint/hybrid/hybrid).
  
## <a name="manage-search-schema"></a>Gestire lo schema di ricerca

Quando gli utenti ricercano contenuti sui siti di SharePoint, è il contenuto dell'indice a determinare i risultati della ricerca. L'indice di ricerca contiene informazioni provenienti da documenti e pagine del sito ed è generato tramite ricerca per indicizzazione dei contenuti sul sito di SharePoint. Lo schema di ricerca consente alla ricerca per indicizzazione di decidere quali contenuti e metadati scegliere e come indicizzarli. Modificando lo schema di ricerca è possibile creare un'esperienza di ricerca personalizzata per gli utenti. Ulteriori informazioni sulla [gestione dello schema di ricerca in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema).
  
## <a name="on-hover-preview"></a>Anteprima al passaggio del mouse

Gli utenti possono soffermarsi con il puntatore su un risultato della ricerca per visualizzare l'anteprima del contenuto di un documento o di un sito e interagirvi nel pannello sensibile al passaggio del mouse a destra dei risultati. Nell'anteprima vengono mostrati diversi metadati e collegamenti diretti alle sezioni principali del documento o del sito. Ulteriori informazioni sui [suggerimenti di ricerca](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9).
  
## <a name="phonetic-name-matching"></a>Nome fonetico corrispondente

Grazie ai miglioramenti apportati alla corrispondenza fonetica del nome, la ricerca viene effettuata in base ai nomi pronunciati in modo simile (ad esempio, John oppure Jon). Ulteriori informazioni sulla [gestione delle origini dei risultati](https://docs.microsoft.com/sharepoint/manage-result-sources).
  
## <a name="query-rulesadd-promoted-results"></a>Regole di query — aggiungere i risultati innalzati di livello

In una regola di query, vengono specificate le condizioni e le azioni correlate. Quando una query soddisfa le condizioni di una regola di query, il sistema di ricerca esegue le azioni specificate nella regola. L'azione "Aggiungere risultati alzati di livello" consente di innalzare di livello i risultati per visualizzarli tra i primi risultati della ricerca. Ulteriori informazioni sulla [gestione delle regole di query](https://docs.microsoft.com/SharePoint/search/manage-query-rules).
  
## <a name="query-rulesadvanced-actions"></a>Regole di query — azioni avanzate

In una regola di query, è possibile specificare le condizioni e le azioni correlate. L'azione per aggiungere blocchi di risultati consente di visualizzare un sottoinsieme di risultati della ricerca come gruppo. L'azione "Modificare i risultati classificati modificando la query" consente di modificare la classificazione dei risultati della ricerca restituiti. Ulteriori informazioni sulla [gestione delle regole di query](https://docs.microsoft.com/SharePoint/search/manage-query-rules).
  
## <a name="query-spelling-correction"></a>Correzione degli errori di ortografia nelle query

Consente di modificare gli elenchi di inclusione ed esclusione allo scopo di determinare per quali query visualizzare un'ortografia alternativa nella pagina dei risultati della ricerca. Questa funzionalità è spesso denominata "Forse intendevi dire?". Ulteriori informazioni sulla [correzione degli errori di ortografia nelle query](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction).
  
## <a name="query-suggestions"></a>Suggerimenti di query

I suggerimenti di query sono frasi suggerite che gli utenti hanno già cercato. I suggerimenti vengono visualizzati in un elenco sotto la casella di ricerca mentre l'utente digita la query. I suggerimenti alle query sono generati automaticamente e le frasi possono essere aggiunte come suggerimento "sempre" o "mai". Ulteriori informazioni sulla [gestione dei suggerimenti di query](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions).
  
## <a name="ranking-models"></a>Modelli di classificazione

SharePoint utilizza i modelli di classificazione assegnando un valore di ricerca dei risultati in modo che gli elementi più rilevanti appaiano prima. Un modello di classificazione è un insieme di fattori di classificazione che calcolano la valutazione di classificazione di un particolare elemento. Sia SharePoint Online, sia SharePoint Server 2013 includono diversi modelli di classificazione in grado di fornire classificazioni efficaci senza ulteriori personalizzazioni. Tuttavia, è possibile personalizzare i modelli di classificazione se è necessario rendere i risultati di ricerca ancora più rilevanti per gli utenti finali. L'app Regolazione modello di classificazione consente ai clienti di SharePoint Online di creare un modello di classificazione personalizzato. L'app fornisce un'interfaccia utente per copiare un modello di classificazione esistente, giudicare i risultati per un insieme di query e "regolarlo" aggiungendo o rimuovendo funzionalità di classificazione e impostando il peso di tali funzionalità. Ulteriori informazioni sulla [classificazione dei risultati della ricerca](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking).
  
## <a name="refiners"></a>Criteri di affinamento

I criteri di affinamento categorizzano i primi documenti nei risultati della ricerca in SharePoint Server in gruppi che consentono agli utenti di filtrare i risultati della ricerca. Ulteriori informazioni sulla [configurazione web part di perfezionamento](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).
  
## <a name="restful-query-apiquery-om"></a>RESTful API Query/Query OM

Gli sviluppatori possono creare codice .NET per accedere al modello a oggetti di ricerca pubblico. Sono incluse le operazioni di amministrazione della ricerca oltre all'invio delle query di ricerca. Per interagire con il modello a oggetti sul lato servizio, il codice .NET deve essere eseguito su un server Web nella farm. È possibile accedere a un sottoinsieme del modello a oggetti da un computer remoto utilizzando il modello a oggetti laterali client (CSOM). È possibile accedere alle funzionalità del modello a oggetti del client (CSOM) utilizzando un servizio Web basato su REST o oData. In questo modo, gli sviluppatori possono inviare query alla farm SharePoint Server 2013 utilizzando gli strumenti di sviluppo Web più comuni.

## <a name="search-results-sorting"></a>Ordinamento dei risultati della ricerca

Gli utenti possono scegliere di ordinare i risultati della ricerca&mdash;in base a criteri diversi, ad esempio, pertinenza, aggiornamento e distanza sociale (nomi di utenti). Ulteriori informazioni sull'[ordinamento dei risultati della ricerca](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e).
  
## <a name="this-list-searches"></a>Ricerche "questo elenco"

In SharePoint Online e SharePoint Server 2013, una ricerca può essere limitata all'elenco o alla raccolta dove è stata eseguita la ricerca. In SharePoint Foundation 2013, una ricerca restituisce i risultati da tutti gli elenchi e raccolte pari o inferiori al sito di esecuzione della ricerca.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio SharePoint Online](sharepoint-online-service-description.md).
  

