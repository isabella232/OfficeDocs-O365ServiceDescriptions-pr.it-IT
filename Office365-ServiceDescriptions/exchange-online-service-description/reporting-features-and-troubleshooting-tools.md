---
title: Funzionalità di creazione dei report e strumenti di risoluzione problemi
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online offre un'ampia gamma di funzionalità di creazione di report sia all'Exchange admin center (EAC).
ms.openlocfilehash: fa80cd6c7d8e9e5f0527c478474cffe17e9204af
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652690"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Funzionalità di creazione dei report e strumenti di risoluzione problemi

Microsoft Exchange Online offre un'ampia gamma di funzionalità di creazione di report sia all'Exchange admin center (EAC).
  
## <a name="reporting-features"></a>Funzionalità di creazione di report

Exchange Online i clienti possono accedere ai report nell'interfaccia di amministrazione di Microsoft 365, scaricando una cartella Excel di report o utilizzando i servizi Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Creazione di report nell'Microsoft 365 di amministrazione

Nella pagina Report dell'interfaccia di amministrazione di Microsoft 365 sono disponibili report di riepilogo sulle cassette postali e sui gruppi. Ad esempio, un rapporto indica il numero di gruppi creati ed eliminati al giorno, alla settimana, al mese e all'anno. Sono disponibili anche dei rapporti sintetici per le cassette postali nuove ed eliminate e per le cassette postali attive e inattive. 
  
Inoltre, la pagina Report nell'interfaccia di amministrazione di Microsoft 365 contiene report sui dati di messaggistica, che forniscono informazioni sul traffico dei messaggi, sui rilevamenti di posta indesiderata e malware e sui messaggi interessati dalle regole di trasporto di Exchange o dai criteri di prevenzione della perdita dei dati (DLP). I report migliorati per la protezione, le regole e DLP offrono un'esperienza di report interattiva agli amministratori di Exchange Online. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.
  
Per ulteriori informazioni sui report disponibili con ogni sottoscrizione, vedere [Reports](../office-365-platform-service-description/reports.md). Per informazioni più dettagliate sulla pagina Report nell'interfaccia di amministrazione di Microsoft 365, vedere View [and download reports about service usage in Office 365](/microsoft-365/admin/activity-reports/activity-reports) e Use mail protection reports to view data about [malware, spam, and rule detections.](/exchange/monitoring/use-mail-protection-reports)
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Reporting con la relativa cartella di lavoro Excel

È anche possibile utilizzare la cartella di lavoro Excel 2013 per visualizzare rapporti di riepilogo con funzionalità di drill-down. Tuttavia, ti consigliamo di usare i report dell'interfaccia Microsoft 365'interfaccia di amministrazione avanzata. La cartella di lavoro per la creazione dei report di Excel 2013 diventerà obsoleta. Per una panoramica sulla cartella di lavoro e per i collegamenti per scaricarla e installarla, vedere la seguente [pagina di download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Per informazioni su come utilizzare la cartella di lavoro, vedere [Rapporti sulla protezione della posta utilizzando la cartella di lavoro per reporting di Excel](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150)). 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

L'accesso a report di riepilogo e dettagliati su cassette postali, gruppi e dati di messaggistica è disponibile tramite il servizio Web REST/OData Tenant Reporting, un'interfaccia programmatica che consente di creare report personalizzati. Per ulteriori informazioni, vedere [Office 365 Reporting web services](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15)).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Funzionalità di reporting e strumenti di risoluzione dei problemi nell'interfaccia di amministrazione di Exchange

Nell'interfaccia di amministrazione di Exchange sono disponibili le seguenti funzionalità di reporting e risoluzione dei problemi.
  
### <a name="trace-an-email-message"></a>Traccia di un messaggio di posta elettronica

La funzionalità di traccia dei messaggi consente all'amministratore di seguire i messaggi di posta elettronica mentre passano attraverso il Exchange Online servizio. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Ciò consente all'amministratore di rispondere in modo preciso alle domande dei propri utenti e di risolvere i problemi del flusso di posta elettronica, riducendo la necessità di rivolgersi al supporto tecnico per assistenza.
  
> [!IMPORTANT]
> Per la risoluzione di problemi generici, utilizzare gli strumenti di reporting per ottenere i dati necessari. Per problemi più specifici, per i quali è necessario avere i dettagli relativi a un determinato messaggio, utilizzare lo strumento di traccia dei messaggi. 
  
Per ulteriori informazioni sulla funzionalità di tracciamento dei messaggi, vedere [Tracciamento di un messaggio di posta elettronica](/exchange/monitoring/trace-an-email-message/trace-an-email-message).
  
### <a name="auditing-reports"></a>Rapporti di controllo

Utilizzare la registrazione di controllo per risolvere i problemi di configurazione tenendo traccia delle modifiche specifiche apportate dagli amministratori e contribuire al rispetto dei requisiti normativi, di conformità e legali. In Exchange Online sono disponibili due tipi di registrazione di controllo:
  
- Registrazione di controllo dell'amministratore i registra qualsiasi azione eseguita da un amministratore. In questo modo è possibile risolvere problemi di configurazione o individuare la causa di problemi relativi alla sicurezza o alla conformità. 
    
- Nella registrazione di controllo della cassetta postale viene registrato ogni accesso a una cassetta postale da parte di un utente diverso dal proprietario della cassetta stessa. In questo modo è possibile stabilire chi ha effettuato l'accesso a una cassetta postale e quali operazioni ha eseguito. 
    
Per informazioni sulla registrazione di controllo, vedere [Rapporti di controllo](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
### <a name="unified-messaging-reports"></a>Rapporti di messaggistica unificata

È possibile utilizzare questi rapporti per monitorare e risolvere i problemi della messaggistica unificata nell'organizzazione Exchange Online. Per ulteriori informazioni, vedere [Esecuzione di report per le chiamate alla casella vocale](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Exchange Online [descrizione del servizio.](exchange-online-service-description.md)
