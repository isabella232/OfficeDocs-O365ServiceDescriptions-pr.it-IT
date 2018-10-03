---
title: Funzionalità di reporting e risoluzione dei problemi
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online offre una serie di funzionalità e l'interfaccia di amministrazione di Exchange (EAC) di reporting.
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036006"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Funzionalità di reporting e risoluzione dei problemi

Microsoft Exchange Online offre una serie di funzionalità e l'interfaccia di amministrazione di Exchange (EAC) di reporting.
  
## <a name="reporting-features"></a>Funzionalità di reporting

I clienti di Exchange Online possono accedere ai rapporti nell'interfaccia di amministrazione di Office 365, scaricando una cartella di lavoro per reporting di Excel oppure utilizzando i servizi Web.
  
### <a name="reporting-in-the-office-365-admin-center"></a>Reporting nell'interfaccia di amministrazione di Office 365

La pagina Rapporti nell'interfaccia di amministrazione di Microsoft Office 365 contiene dei rapporti informativi sintetici su cassette postali e gruppi. Ad esempio, un rapporto indica il numero di gruppi creati ed eliminati al giorno, alla settimana, al mese e all'anno. Sono disponibili anche dei rapporti sintetici per le cassette postali nuove ed eliminate e per le cassette postali attive e inattive. 
  
Inoltre, la pagina Rapporti nell'interfaccia di amministrazione di Microsoft Office 365 contiene i rapporti sui dati di messaggistica che forniscono informazioni su traffico messaggi, spam e malware rilevati e messaggi interessati dalle regole di trasporto di Exchange o dai criteri per la prevenzione delle perdita dei dati. I report migliorati per la protezione, le regole e DLP offrono un'esperienza di report interattiva agli amministratori di Exchange Online. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.
  
Per ulteriori informazioni sui report disponibili con ciascuna sottoscrizione Office 365, vedere [Report](../office-365-platform-service-description/reports.md). Per informazioni più dettagliate sulla pagina Rapporti nell'interfaccia di amministrazione di Office 365, vedere [Visualizzare e scaricare rapporti sull'utilizzo del servizio in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [Utilizzare i rapporti di protezione della posta in Office 365 per visualizzare i dati relativi a malware, posta indesiderata e rilevamenti delle regole](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Reporting con la relativa cartella di lavoro Excel

È anche possibile utilizzare la cartella di lavoro Excel 2013 per visualizzare rapporti di riepilogo con funzionalità di drill-down. Tuttavia, è consigliabile utilizzare invece i rapporti dell'interfaccia di amministrazione di Office 365. La cartella di lavoro per la creazione dei report di Excel 2013 diventerà obsoleta. Per una panoramica sulla cartella di lavoro e per i collegamenti per scaricarla e installarla, vedere la seguente [pagina di download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Per informazioni su come utilizzare la cartella di lavoro, vedere [Rapporti sulla protezione della posta utilizzando la cartella di lavoro per reporting di Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Reporting tramite i servizi Web

L'accesso ai rapporti sintetici e dettagliati su cassette postali, gruppi e dati di messaggistica avviene tramite il servizio REST/OData Tenant Reporting Web, un'interfaccia di programmazione che consente di creare rapporti personalizzati. Per ulteriori informazioni, vedere [Servizio Web dei rapporti per Office 365](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Funzionalità di reporting e strumenti di risoluzione dei problemi nell'interfaccia di amministrazione di Exchange

Nell'interfaccia di amministrazione di Exchange sono disponibili le seguenti funzionalità di reporting e risoluzione dei problemi.
  
### <a name="trace-an-email-message"></a>Traccia di un messaggio di posta elettronica

La funzionalità di traccia dei messaggi permette a un amministratore di seguire l'iter dei messaggi di posta elettronica mentre attraversano il servizio Exchange Online. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Ciò consente all'amministratore di rispondere in modo preciso alle domande dei propri utenti e di risolvere i problemi del flusso di posta elettronica, riducendo la necessità di rivolgersi al supporto tecnico per assistenza.
  
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
  
