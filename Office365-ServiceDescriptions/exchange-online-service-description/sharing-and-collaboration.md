---
title: Condivisione e collaborazione
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: bd1baaf7d6d2a7cc0757f156f2931d7725ee8e2c
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262719"
---
# <a name="sharing-and-collaboration"></a>Condivisione e collaborazione

## <a name="federated-sharing"></a>Condivisione federata

La Federazione si riferisce all'infrastruttura di trust sottostante che supporta la condivisione federata, un metodo per gli utenti di Microsoft Exchange Online per condividere dati del calendario di disponibilità e informazioni di contatto con i destinatari in altre organizzazioni esterne federate o con utenti che dispongono di accesso a Internet. Sono incluse anche le organizzazione che sono ospitate da Exchange Online oppure le organizzazioni Microsoft Exchange Server 2010 o Exchange Server 2013. Utilizzando le relazioni tra organizzazioni e i criteri di condivisione, gli amministratori di Exchange Online possono consentire agli utenti di inviare inviti di condivisione del calendario da Microsoft Outlook sul Web o Microsoft Outlook 2010 o versione successiva.
  
> [!IMPORTANT]
>  Le organizzazione Exchange 2010 e Exchange 2013 esterne devono configurare una relazione di trust federativa con Microsoft Federation Gateway come parte della condivisione federata. Per le organizzazioni Exchange Online non occorre configurare una relazione di trust federativa; la relazione di trust federativa con Microsoft Federation Gateway viene creata automaticamente quando viene creato il tenant di Office 365. 
>
>  Le organizzazioni Exchange Online devono configurare una relazione tra organizzazioni o i criteri di condivisione per abilitare la condivisione federata. 
>
>  La condivisione degli elenchi di accesso globale o lo spostamento delle cassette postali degli utenti tra le organizzazioni di Exchange online in diversi tenant di Office 365 non è supportato nella condivisione federata. 
  
Per ulteriori informazioni sulla condivisione federata, vedere [Condivisione in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Cassette postali del sito

Generalmente i messaggi di posta elettronica e i documenti sono conservati in due repository univoci e separati. La maggior parte dei team di lavoro collaborano tramite messaggi di posta elettronica e documenti. La sfida è rappresentata dall'esigenza di accedere ai messaggi di posta elettronica e ai documenti utilizzando diversi client. Generalmente questa situazione implica una riduzione della produttività e un'interfaccia meno intuitiva.
  
La cassetta postale del sito è un nuovo concetto in Exchange 2013 che tenta di risolvere questo problema. Le cassette postali dei siti migliorano la collaborazione e la produttività degli utenti in quanto consentono l'utilizzo delle stessa interfaccia client per accedere ai documenti di Microsoft SharePoint 2013 e alla posta elettronica di Exchange. Una cassetta postale del sito è costituita dall'appartenenza a un sito SharePoint 2013 (proprietari e membri), dall'archiviazione condivisa tramite una cassetta postale di Exchange 2013 per i messaggi di posta elettronica, da un sito SharePoint 2013 per i documenti e da un'interfaccia di gestione per il provisioning e il ciclo di vita.
  
> [!IMPORTANT]
> Il piano di Office 365 deve includere SharePoint. Le cassette postali dei siti richiedono che gli utenti abbiano le licenze sia di SharePoint sia di Exchange. 
  
Per ulteriori informazioni sulle cassette postali dei siti, vedere [Cassette postali dei siti](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Cartelle pubbliche

Le cartelle pubbliche in Exchange Online sono state modernizzate per sfruttare l'elevata disponibilità esistente e le tecnologie di archiviazione del database delle cassette postali. L'architettura delle cartelle pubbliche utilizza cassette postali speciali per archiviare sia la gerarchia sia il contenuto della cartella pubblica. Ciò significa che non è più disponibile un database delle cartelle pubbliche separato. La replica delle cartelle pubbliche ora utilizza il modello di replica continua. L'elevata disponibilità della gerarchia e delle cassette postali del contenuto è fornita dal gruppo di disponibilità del database (DAG) che si trova nel data center. In Exchange Online, l'utente ha un limite di 1000 cassette postali delle cartelle pubbliche. Anche ciascuna cassetta postale di cartelle pubbliche possiede dimensioni di archiviazione massime. Per ulteriori informazioni, vedere la sezione "limiti della cartella delle cassette postali" in [limiti Exchange Online limits](exchange-online-limits.md). Le cassette postali di cartelle pubbliche hanno i medesimi avvisi per limiti di spazio di archiviazione, messaggi, destinatari e avvisi di capacità delle cassette postali normali. Per ulteriori informazioni, vedere [Destinatari](recipients.md). 
  
Per ulteriori informazioni sulle cartelle pubbliche, vedere [Cartelle pubbliche](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Cassette postali di gruppo e condivise

Le cassette postali di gruppo e condivise consentono a un gruppo specifico di utenti di monitorare e inviare messaggi di posta elettronica da un account comune, come gli indirizzi di posta elettronica pubblici (ad esempio, info@contoso.com o contact@contoso.com). Quando una persona del gruppo risponde a un messaggio inviato alla cassetta postale condivisa, la posta elettronica sembra provenire dalla cassetta postale condivisa, non dal singolo utente.
  
In genere, le cassette postali di gruppo o condivise non richiedono una licenza utente separata. Tuttavia, per abilitare l'archiviazione sul posto di un gruppo o di una cassetta postale condivisa, è necessario assegnare una licenza di Exchange Online piano 1 o Exchange Online piano 2. Una volta assegnata la licenza, la dimensione della cassetta postale diventa corrispondente a quella previsto dal piano concesso in licenza. Per inserire una cassetta postale condivisa sull'archiviazione sul posto, è necessario assegnare una licenza di Exchange Online piano 2. Tenere presente che non è possibile assegnare le cassette postali di gruppo in questo momento, ma che devono essere contabilizzate nelle licenze totali.
  
Archivio sul posto può essere utilizzato solo per archiviare messaggi per un singolo utente o entità (ad esempio, una cassetta postale condivisa) per il quale è stata applicata una licenza. Non è consentito utilizzare un'Archiviazione sul posto come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, un amministratore IT non può creare cassette postali condivise e lasciare che gli utenti le copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) con l'esplicito scopo di archiviarle. Tenere presente che una cassetta postale condivisa da molti utenti non archivia automaticamente la posta elettronica dei singoli utenti. Numerosi utenti possono accedere e inviare posta elettronica come cassetta postale condivisa. Di conseguenza, gli unici messaggi di posta elettronica archiviati nella cassetta postale condivisa sono quelli inviati o ricevuti da esso, come cassetta postale condivisa.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

