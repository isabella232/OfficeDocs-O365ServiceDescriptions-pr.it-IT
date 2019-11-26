---
title: Funzionalità di Reporting e strumenti di risoluzione dei problemi
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online offre una vasta gamma di funzionalità di Reporting sia all'interno che all'esterno dell'interfaccia di amministrazione di Exchange (EAC).
ms.openlocfilehash: d7560a95d127731bc8354c8be73aa016ee0aecfd
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262709"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Funzionalità di Reporting e strumenti di risoluzione dei problemi

Microsoft Exchange Online offre una vasta gamma di funzionalità di Reporting sia all'interno che all'esterno dell'interfaccia di amministrazione di Exchange (EAC).
  
## <a name="reporting-features"></a>Funzionalità di reporting

I clienti di Exchange Online possono accedere ai rapporti nell'interfaccia di amministrazione di Microsoft 365 scaricando una cartella di lavoro di report di Excel o utilizzando i servizi Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Creazione di rapporti nell'interfaccia di amministrazione di Microsoft 365

Sono presenti report nella pagina report nell'interfaccia di amministrazione di Microsoft 365 che forniscono informazioni di riepilogo su cassette postali e gruppi. Ad esempio, un rapporto indica il numero di gruppi creati ed eliminati al giorno, alla settimana, al mese e all'anno. Sono disponibili anche dei rapporti sintetici per le cassette postali nuove ed eliminate e per le cassette postali attive e inattive. 
  
Inoltre, la pagina report nell'interfaccia di amministrazione di Microsoft 365 contiene rapporti sui dati di messaggistica, che forniscono informazioni sul traffico dei messaggi, sui rilevamenti di posta indesiderata e antimalware e sui messaggi interessati dalle regole di trasporto di Exchange o dalla prevenzione della perdita di dati (DLP) generali. I report migliorati per la protezione, le regole e DLP offrono un'esperienza di report interattiva agli amministratori di Exchange Online. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.
  
Per ulteriori informazioni sui report disponibili con ciascuna sottoscrizione Office 365, vedere [Report](../office-365-platform-service-description/reports.md). Per informazioni più dettagliate sulla pagina report nell'interfaccia di amministrazione di Microsoft 365, vedere [visualizzare e scaricare report sull'uso dei servizi in office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [utilizzare i rapporti di protezione della posta elettronica in Office 365 per visualizzare i dati relativi a malware, posta indesiderata e rilevamenti di regole](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Reporting con la relativa cartella di lavoro Excel

È anche possibile utilizzare la cartella di lavoro Excel 2013 per visualizzare rapporti di riepilogo con funzionalità di drill-down. Tuttavia, si consiglia di utilizzare i report dell'interfaccia di amministrazione avanzata di Microsoft 365. La cartella di lavoro per la creazione dei report di Excel 2013 diventerà obsoleta. Per una panoramica sulla cartella di lavoro e per i collegamenti per scaricarla e installarla, vedere la seguente [pagina di download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Per informazioni su come utilizzare la cartella di lavoro, vedere [Rapporti sulla protezione della posta utilizzando la cartella di lavoro per reporting di Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

L'accesso ai report di riepilogo e dettagliati relativi a cassette postali, gruppi e dati di messaggistica è disponibile tramite il servizio Web Reporting tenant REST/OData, che è un'interfaccia a livello di programmazione che consente di creare report personalizzati. Per ulteriori informazioni, vedere [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Funzionalità di reporting e strumenti di risoluzione dei problemi nell'interfaccia di amministrazione di Exchange

Nell'interfaccia di amministrazione di Exchange sono disponibili le seguenti funzionalità di reporting e risoluzione dei problemi.
  
### <a name="trace-an-email-message"></a>Traccia di un messaggio di posta elettronica

La funzionalità di traccia dei messaggi consente, come amministratore, di seguire i messaggi di posta elettronica che passano attraverso il servizio Exchange Online. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Ciò consente all'amministratore di rispondere in modo preciso alle domande dei propri utenti e di risolvere i problemi del flusso di posta elettronica, riducendo la necessità di rivolgersi al supporto tecnico per assistenza.
  
> [!IMPORTANT]
> Per la risoluzione di problemi generici, utilizzare gli strumenti di reporting per ottenere i dati necessari. Per problemi più specifici, per i quali è necessario avere i dettagli relativi a un determinato messaggio, utilizzare lo strumento di traccia dei messaggi. 
  
Per ulteriori informazioni sulla funzionalità di tracciamento dei messaggi, vedere [Tracciamento di un messaggio di posta elettronica](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Rapporti di controllo

Utilizzare la registrazione di controllo per risolvere i problemi di configurazione tenendo traccia delle modifiche specifiche apportate dagli amministratori e contribuire al rispetto dei requisiti normativi, di conformità e legali. In Exchange Online sono disponibili due tipi di registrazione di controllo:
  
- Registrazione di controllo dell'amministratore i registra qualsiasi azione eseguita da un amministratore. In questo modo è possibile risolvere problemi di configurazione o individuare la causa di problemi relativi alla sicurezza o alla conformità. 
    
- Nella registrazione di controllo della cassetta postale viene registrato ogni accesso a una cassetta postale da parte di un utente diverso dal proprietario della cassetta stessa. In questo modo è possibile stabilire chi ha effettuato l'accesso a una cassetta postale e quali operazioni ha eseguito. 
    
Per informazioni sulla registrazione di controllo, vedere [Rapporti di controllo](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Rapporti di messaggistica unificata

È possibile utilizzare questi rapporti per monitorare e risolvere i problemi della messaggistica unificata nell'organizzazione Exchange Online. Per ulteriori informazioni, vedere [Esecuzione di report per le chiamate alla casella vocale](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

