---
title: Condivisione e collaborazione
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 13ab2163b76b5ccc4732659a64be5fcead01dc9d
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036013"
---
# <a name="sharing-and-collaboration"></a>Condivisione e collaborazione

## <a name="federated-sharing"></a>Condivisione federata

La Federazione fa riferimento all'infrastruttura di trust sottostante che supporta la condivisione federata, un metodo per gli utenti di Microsoft Exchange Online per condividere le informazioni di calendario e di contatto con i destinatari in altre organizzazioni federate esterne o con gli utenti che hanno accesso a Internet. Sono incluse anche le organizzazione che sono ospitate da Exchange Online oppure le organizzazioni Microsoft Exchange Server 2010 o Exchange Server 2013. Utilizzando le relazioni tra organizzazioni e i criteri di condivisione, gli amministratori di Exchange Online possono abilitare gli utenti all'invio di inviti alla condivisione del calendario da Microsoft Outlook Web App o Microsoft Outlook 2010 o versioni successive.
  
> [!IMPORTANT]
>  Le organizzazione Exchange 2010 e Exchange 2013 esterne devono configurare una relazione di trust federativa con Microsoft Federation Gateway come parte della condivisione federata. Per le organizzazioni Exchange Online non occorre configurare una relazione di trust federativa; la relazione di trust federativa con Microsoft Federation Gateway viene creata automaticamente quando viene creato il tenant di Office 365. >  Le organizzazioni Exchange Online devono configurare una relazione tra organizzazioni o i criteri di condivisione per abilitare la condivisione federata. >  La condivisione dell'elenco indirizzi globale o lo spostamento delle cassette postali degli utenti tra organizzazioni Exchange Online che si trovano in tenant di Office 365 differenti non è supportato nella condivisione federata. 
  
Per ulteriori informazioni sulla condivisione federata, vedere [Condivisione in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Cassette postali del sito

Generalmente i messaggi di posta elettronica e i documenti sono conservati in due repository univoci e separati. La maggior parte dei team di lavoro collaborano tramite messaggi di posta elettronica e documenti. La sfida è rappresentata dall'esigenza di accedere ai messaggi di posta elettronica e ai documenti utilizzando diversi client. Generalmente questa situazione implica una riduzione della produttività e un'interfaccia meno intuitiva.
  
La cassetta postale del sito è un nuovo concetto in Exchange 2013 che tenta di risolvere questo problema. Le cassette postali dei siti migliorano la collaborazione e la produttività degli utenti in quanto consentono l'utilizzo delle stessa interfaccia client per accedere ai documenti di Microsoft SharePoint 2013 e alla posta elettronica di Exchange. Una cassetta postale del sito è costituita dall'appartenenza a un sito SharePoint 2013 (proprietari e membri), dall'archiviazione condivisa tramite una cassetta postale di Exchange 2013 per i messaggi di posta elettronica, da un sito SharePoint 2013 per i documenti e da un'interfaccia di gestione per il provisioning e il ciclo di vita.
  
> [!IMPORTANT]
> Il piano di Office 365 deve includere SharePoint. Le cassette postali dei siti richiedono che gli utenti abbiano le licenze sia di SharePoint sia di Exchange. 
  
Per ulteriori informazioni sulle cassette postali dei siti, vedere [Cassette postali dei siti](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Cartelle pubbliche

Cartelle pubbliche in Exchange Online sono state modernizzate per sfruttare le tecnologie di archiviazione e disponibilità elevate esistente del database delle cassette postali. L'architettura delle cartelle pubbliche vengono utilizzate le cassette postali progettate appositamente per la memorizzazione della gerarchia e il contenuto delle cartelle pubbliche. Ciò significa che non è più un database delle cartelle pubbliche separato. Replica delle cartelle pubbliche ora utilizza il modello di replica continua. Disponibilità elevata per le cassette postali gerarchia e del contenuto è disponibile un gruppo di disponibilità del database (DAG) nel centro dati. In Exchange Online sono limitate a 1000 cassette postali di cartelle pubbliche. Ogni cassetta postale delle cartelle pubbliche anche con una dimensione massima di memoria. Per ulteriori informazioni, vedere la sezione "Limiti cartella delle cassette postali" in [Exchange Online Limits](exchange-online-limits.md). Cassette postali delle cartelle pubbliche avere lo stesso messaggio, destinatario e limiti della capacità di avviso le cassette postali regolari. Per ulteriori informazioni, vedere [Recipients](recipients.md). 
  
Per ulteriori informazioni sulle cartelle pubbliche, vedere [Cartelle pubbliche](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Cassette postali di gruppo e condivise

Le cassette postali di gruppo e condivise consentono a un gruppo specifico di utenti di monitorare e inviare messaggi di posta elettronica con più facilità da un account comune, come gli indirizzi di posta elettronica pubblici (ad esempio info@contoso.com o contact@contoso.com). Quando una persona nel gruppo risponde a un messaggio inviato alla cassetta postale condivisa, il messaggio di posta elettronica appare come inviato dalla cassetta postale condivisa e non dall'utente.
  
Le cassette postali condivise o di gruppo generalmente non richiedono alcuna licenza utente separata. Tuttavia, per abilitare un archivio sul posto per una cassetta postale condivisa o di gruppo, è necessario assegnarle una licenza Exchange Online, piano 1 o Exchange Online, piano 2. Una volta assegnata la licenza, la dimensione della cassetta postale diventa corrispondente a quella previsto dal piano concesso in licenza. Per attivare il blocco sul posto di una cassetta postale condivisa, è necessario assegnarle una licenza Exchange Online, piano 2. Si noti che le cassette postali di gruppo non possono essere assegnate al momento ma devono essere incluse nelle licenze totali.
  
Archivio sul posto può essere utilizzato solo per archiviare messaggi per un singolo utente o entità (ad esempio, una cassetta postale condivisa) per il quale è stata applicata una licenza. Non è consentito utilizzare un'Archiviazione sul posto come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, un amministratore IT non può creare cassette postali condivise e lasciare che gli utenti le copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) con l'esplicito scopo di archiviarle. Tenere presente che una cassetta postale condivisa da molti utenti non archivia automaticamente la posta elettronica dei singoli utenti. Numerosi utenti possono accedere e inviare posta elettronica come cassetta postale condivisa. Pertanto, vengono inviati e ricevuti soltanto i messaggi di posta elettronica archiviati nella cassetta postale condivisa, come cassetta postale condivisa.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  
