---
title: Funzionalità di creazione dei report e strumenti di risoluzione problemi
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online offre una vasta gamma di funzionalità di Reporting sia all'interno che all'esterno dell'interfaccia di amministrazione di Exchange (EAC).
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132600"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Funzionalità di creazione dei report e strumenti di risoluzione problemi

Microsoft Exchange Online offre una vasta gamma di funzionalità di Reporting sia all'interno che all'esterno dell'interfaccia di amministrazione di Exchange (EAC).
  
## <a name="reporting-features"></a>Funzionalità di reporting

I clienti di Exchange Online possono accedere ai rapporti nell'interfaccia di amministrazione di Microsoft 365 scaricando una cartella di lavoro di report di Excel o utilizzando i servizi Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Creazione di rapporti nell'interfaccia di amministrazione di Microsoft 365

Sono presenti report nella pagina report nell'interfaccia di amministrazione di Microsoft 365 che forniscono informazioni di riepilogo su cassette postali e gruppi. Ad esempio, un rapporto indica il numero di gruppi creati ed eliminati al giorno, alla settimana, al mese e all'anno. Sono disponibili anche dei rapporti sintetici per le cassette postali nuove ed eliminate e per le cassette postali attive e inattive. 
  
Inoltre, la pagina report nell'interfaccia di amministrazione di Microsoft 365 contiene rapporti sui dati di messaggistica, che forniscono informazioni sul traffico dei messaggi, sui rilevamenti di posta indesiderata e malware e sui messaggi interessati dalle regole di trasporto di Exchange o dai criteri di prevenzione della perdita di dati (DLP). I report migliorati per la protezione, le regole e DLP offrono un'esperienza di report interattiva agli amministratori di Exchange Online. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.
  
Per ulteriori informazioni sui report disponibili con ogni sottoscrizione, vedere [report](../office-365-platform-service-description/reports.md). Per informazioni più dettagliate sulla pagina report nell'interfaccia di amministrazione di Microsoft 365, vedere [visualizzare e scaricare report sull'uso dei servizi in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [utilizzare i rapporti di protezione della posta elettronica per visualizzare i dati relativi a malware, posta indesiderata e rilevamenti di regole](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Reporting con la relativa cartella di lavoro Excel

È anche possibile utilizzare la cartella di lavoro Excel 2013 per visualizzare rapporti di riepilogo con funzionalità di drill-down. Tuttavia, si consiglia di utilizzare i report dell'interfaccia di amministrazione avanzata di Microsoft 365. La cartella di lavoro per la creazione dei report di Excel 2013 diventerà obsoleta. Per una panoramica sulla cartella di lavoro e per i collegamenti per scaricarla e installarla, vedere la seguente [pagina di download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Per informazioni su come utilizzare la cartella di lavoro, vedere [Rapporti sulla protezione della posta utilizzando la cartella di lavoro per reporting di Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

L'accesso ai report di riepilogo e dettagliati relativi a cassette postali, gruppi e dati di messaggistica è disponibile tramite il servizio Web Reporting tenant REST/OData, che è un'interfaccia a livello di programmazione che consente di creare report personalizzati. Per ulteriori informazioni, vedere [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Funzionalità di reporting e strumenti di risoluzione dei problemi nell'interfaccia di amministrazione di Exchange

Nell'interfaccia di amministrazione di Exchange sono disponibili le seguenti funzionalità di reporting e risoluzione dei problemi.
  
### <a name="trace-an-email-message"></a>Traccia di un messaggio di posta elettronica

La funzionalità di traccia dei messaggi consente, come amministratore, di seguire i messaggi di posta elettronica che passano attraverso il servizio Exchange Online. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Ciò consente all'amministratore di rispondere in modo preciso alle domande dei propri utenti e di risolvere i problemi del flusso di posta elettronica, riducendo la necessità di rivolgersi al supporto tecnico per assistenza.
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
Per ulteriori informazioni sulla funzionalità di tracciamento dei messaggi, vedere [Tracciamento di un messaggio di posta elettronica](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Rapporti di controllo

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
Per informazioni sulla registrazione di controllo, vedere [Rapporti di controllo](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Rapporti di messaggistica unificata

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

