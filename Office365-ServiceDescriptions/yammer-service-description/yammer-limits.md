---
title: Limiti in Yammer
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- yammer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Informazioni sui limiti del servizio in Yammer per Microsoft 365.
ms.openlocfilehash: 390bb642e45e2ac4868069698530d7c43a171762
ms.sourcegitcommit: c061620e1ccabec8ee97d49f25d575cde54fbc9b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/30/2021
ms.locfileid: "53661648"
---
# <a name="limits-in-yammer"></a>Limiti in Yammer

Informazioni sui limiti del servizio in Yammer per Microsoft 365.

## <a name="network-limits"></a>Limiti di rete

| Funzionalità | Dettagli |
|---------|---------|
| Modalità nativa | [La modalità](/yammer/configure-your-yammer-network/overview-native-mode) nativa è consigliata per il miglior supporto a lungo termine. Yammer reti in Microsoft 365 native hanno funzionalità diverse rispetto alle reti Yammer legacy. |
| Aggiornamento in blocco per gli amministratori di rete | Gli aggiornamenti in blocco per gli utenti sono supportati per reti non in modalità nativa di 2000 utenti o meno. |
| Reti domestiche | Le reti domestiche non possono essere eliminate e ricreate. |

## <a name="file-limits"></a>Limiti dei file

| Funzionalità | Dettagli |
|---------|---------|
| Dimensioni massime file e spazio di archiviazione | La migrazione alla Microsoft 365 nativa per Yammer è consigliata per garantire che tutti i file siano archiviati in SharePoint Online. <br/>Per Yammer file archiviati in SharePoint: <ul><li>La dimensione massima per un singolo file allegato è 15 gigabyte (GB).</li><li>Non esistono limitazioni di dimensione per le immagini, ma SharePoint le impostazioni delle dimensioni massime nell'organizzazione.</li><li>È possibile aggiungere qualsiasi tipo di file, ma l'anteprima e la modifica sono limitate a determinati tipi di file.</li> </ul><br/>[SharePoint limiti si](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits) applicano alle Microsoft 365 [connesse](/yammer/manage-yammer-groups/yammer-and-office-365-groups) in Yammer. <br/>Per i file archiviati in Yammer di archiviazione file: <br/><ul><li>La dimensione massima per un singolo file allegato è di 5 gigabyte (GB) per le reti Yammer Enterprise e 100 MEGABYTE (MB) per le reti Yammer Basic.</li><li>Le dimensioni massime sono 7.680 pixel di larghezza e 4.320 pixel di altezza e la dimensione massima dell'immagine è 10 megabyte (MB).</li></ul> <br/>Per altre informazioni sull'uso delle immagini, inclusi modelli e dimensioni per le foto di copertina, vedi risorse [Yammer adoption.](https://adoption.microsoft.com/yammer/) |
| Numero di file allegati per post | Ogni post può avere un massimo di 100 file. |
| Formati video supportati | Per la riproduzione in linea sono supportati i seguenti tipi di video: .wmv, .avi, .mpeg, .3gp, .flv, .mov, .mp4, .mpg, .ogm, .mkv, .ogv e .ogg. <br/>Yammer usa Servizi multimediali di Azure per visualizzare i video caricati in Yammer. |
| Riproduzione video in linea | Microsoft Stream, SharePoint Online, YouTube e Vimeo sono supportati per la riproduzione in linea. |
| Accesso guest | Microsoft 365 La modalità nativa per Yammer è necessaria per il supporto guest completo. <br/>Guest a livello di rete legacy potrebbero verificarsi problemi di accesso ai file. |
| Anteprime dei collegamenti (oggetti Graph aperti) | I collegamenti a sistemi interni che non possono essere risolti pubblicamente o che richiedono l'autenticazione non visualizzano anteprime valide perché i metadati non possono essere estratti. |

## <a name="yammer-live-event-limits"></a>Yammer degli eventi live

| Funzionalità | Dettagli |
|---------|---------|
| Numero di visualizzatori di eventi live | Attualmente, il limite è di 10.000 partecipanti. Per eventi di dimensioni superiori, utilizzare il [Programma di assistenza eventi live.](https://resources.techcommunity.microsoft.com/live-events/assistance/) |
| Autorizzazioni per la creazione di eventi live | È necessaria l'autorizzazione per creare eventi live in Stream. <br/>Community amministratori in Yammer creare o pianificare eventi live. |
| Accesso guest | I membri della rete canonica possono creare o partecipare a eventi live in Yammer. |
| Sottotitoli codificati | I sottotitoli non sono disponibili per gli eventi live in Yammer. Un aggiornamento futuro aggiungerà il supporto per i sottotitoli codificati. |
| Durata dell'evento | 4 ore |
| Eventi live simultanei in Microsoft 365 o Office 365 organizzazione | 50 eventi per tenant |
| Limite di relatori? | 100 relatori |

Per ulteriori limiti relativi Microsoft Teams eventi live e riunioni, vedere [Teams Live Events](/microsoftteams/limits-specifications-teams#teams-live-events).

## <a name="yammer-community-limits"></a>Yammer limiti della community

| Funzionalità | Dettagli |
|---------|---------|
| Numero di membri di una community | Varia a seconda che la community sia connessa [a](/yammer/manage-yammer-groups/yammer-and-office-365-groups)un Microsoft 365, sia una [community](/yammer/manage-yammer-groups/create-a-dynamic-group)dinamica o sia la community [All Company.](/yammer/manage-yammer-groups/yammer-all-company-yammer-community) <br/>Limite di appartenenza alla community dinamico: 500.000 |
| Numero di community di cui è possibile essere membri | 7,000 |
| Numero di aggiornamenti tramite importazione rubrica per aggiungere più utenti contemporaneamente | 200 membri della community per caricamento in batch. |
| Limite delle community dinamiche | Nessun limite |
| Numero di amministratori per community | In modalità nativa, gli amministratori possono impostare un valore minimo. Le reti in modalità non nativa hanno un limite di 100 amministratori per community. |
| Numero di amministratori di rete | Varia a seconda della configurazione in modalità nativa. Nessun limite di amministratori di rete. |
| Community connesse e Azure AD Sync | La latenza con la sincronizzazione può verificarsi con un'appartenenza alla community superiore a 100.000. |
| Membri in Tutte le società | Include tutti gli utenti nel tenant. |
| Numero di community ufficiali | Nessun limite |
| Numero di community preferite | 10  |
| Community di caratteri del nome | Dipende dalla convenzione di denominazione della rete. <br/>Massimo 255 caratteri, inclusi eventuali prefissi. |
| Community di caratteri per la descrizione | 150 caratteri |
| Community info | Nessun limite di caratteri (fino a 1 GB) |
| Limite delle risorse aggiunte | Nessun limite |
| Limite delle community correlate | Nessun limite per le community normali, ma le procedure consigliate sono 3-5 community correlate. <br/>Le community correlate non sono disponibili per Tutte le società. |
| Limite per i membri in sospeso per le community private | Nessun limite. |
| Limiti alla gestione della community in modalità nativa | I gruppi connessi devono essere gestiti usando strumenti progettati per aggiornare Microsoft 365 gruppi, tra cui il portale di amministrazione di Microsoft 365, il portale di Azure AD e il modulo Azure AD PowerShell. |
| Pubblicare tramite posta elettronica | Nessun limite |

## <a name="yammer-messaging-limitations"></a>Yammer di messaggistica unificata

| Funzionalità | Dettagli |
|---------|---------|
| Limite caratteri per messaggio | Limite di 10.000 caratteri |
| Eliminazione di conversazioni | L'eliminazione di un intero thread richiede l'eliminazione di tutti i messaggi. L'eliminazione dell'avvio della conversazione promuoverà la prima risposta in modo che diventi l'avvio del thread. <br/>Gli amministratori di rete possono eliminare i messaggi da qualsiasi thread di conversazione se [è abilitata la](/yammer/manage-security-and-compliance/monitor-private-content) modalità contenuto privato. <br/>Community amministratori possono eliminare i messaggi nella community che amministrano. <br/>L'autore originale può eliminare solo i propri post. |
| Limite messaggi per thread di conversazione | Una conversazione può avere fino a 10.000 post. |
| Anteprime dei collegamenti (Graph metadati aperti) |<ul><li>Le anteprime del contenuto dei collegamenti possono essere generate solo per il contenuto pubblico e alcune risorse Microsoft 365 supportate.</li><li>La generazione dell'anteprima dipende dall'estrazione corretta dei metadati al momento della pubblicazione, che può variare in base alla disponibilità del sito a cui viene collegato.</li><li>I collegamenti ai sistemi all'interno del firewall dell'organizzazione o che richiedono l'autenticazione non sono supportati. </li><li>I metadati dell'anteprima dei collegamenti potrebbero non essere aggiornati dopo il primo utilizzo del collegamento all'interno della rete.</li></ul> |
| Modalità contenuto privato | Gli amministratori verificati non possono accedere al contenuto privato per impostazione predefinita. La modalità contenuto privato deve essere abilitata per accedere ai messaggi privati e alle community private. |
| Risposte annidate e thread legacy | I thread legacy consentiranno la creazione di nuove risposte annidate. Per il momento, i messaggi "in risposta a" precedenti rimarranno come commenti di primo livello. |

## <a name="external-network-limits"></a>Limiti della rete esterna

| Funzionalità | Dettagli |
|---------|---------|
| Reti esterne | Limitazione di 5 reti esterne che un amministratore può creare se tali 5 reti esterne hanno un singolo membro (in genere, che un membro è l'autore della rete). <br/> Se in una rete esterna è presente almeno un altro utente, non viene conteggiato per tale limite. |
| File | I file vengono archiviati in Yammer di archiviazione e non sono accessibili tramite SharePoint. |
| Community | Le community non sono connesse a Microsoft 365 gruppi. |
| Modalità nativa | [Le funzionalità e le restrizioni della modalità nativa](/yammer/configure-your-yammer-network/overview-native-mode) non si applicano alle reti esterne. |