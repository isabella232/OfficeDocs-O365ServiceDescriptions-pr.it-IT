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
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="4d7b1-103">Funzionalità di reporting e risoluzione dei problemi</span><span class="sxs-lookup"><span data-stu-id="4d7b1-103">Reporting Features and Troubleshooting Tools</span></span>

<span data-ttu-id="4d7b1-104">Microsoft Exchange Online offre una serie di funzionalità e l'interfaccia di amministrazione di Exchange (EAC) di reporting.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="4d7b1-105">Funzionalità di reporting</span><span class="sxs-lookup"><span data-stu-id="4d7b1-105">Reporting features</span></span>

<span data-ttu-id="4d7b1-106">I clienti di Exchange Online possono accedere ai rapporti nell'interfaccia di amministrazione di Office 365, scaricando una cartella di lavoro per reporting di Excel oppure utilizzando i servizi Web.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-106">Exchange Online customers can access reports in the Office 365 admin center, by downloading an Excel reporting workbook, or by using Web services.</span></span>
  
### <a name="reporting-in-the-office-365-admin-center"></a><span data-ttu-id="4d7b1-107">Reporting nell'interfaccia di amministrazione di Office 365</span><span class="sxs-lookup"><span data-stu-id="4d7b1-107">Reporting in the Office 365 admin center</span></span>

<span data-ttu-id="4d7b1-p101">La pagina Rapporti nell'interfaccia di amministrazione di Microsoft Office 365 contiene dei rapporti informativi sintetici su cassette postali e gruppi. Ad esempio, un rapporto indica il numero di gruppi creati ed eliminati al giorno, alla settimana, al mese e all'anno. Sono disponibili anche dei rapporti sintetici per le cassette postali nuove ed eliminate e per le cassette postali attive e inattive.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p101">There are reports on the Reports page in the Microsoft Office 365 admin center that provide summary information about mailboxes and groups. For example, one report lists the number of groups created and deleted by day, week, month, or year. There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="4d7b1-p102">Inoltre, la pagina Rapporti nell'interfaccia di amministrazione di Microsoft Office 365 contiene i rapporti sui dati di messaggistica che forniscono informazioni su traffico messaggi, spam e malware rilevati e messaggi interessati dalle regole di trasporto di Exchange o dai criteri per la prevenzione delle perdita dei dati. I report migliorati per la protezione, le regole e DLP offrono un'esperienza di report interattiva agli amministratori di Exchange Online. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p102">Additionally, the Reports page in the Microsoft Office 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies. The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins. These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="4d7b1-p103">Per ulteriori informazioni sui report disponibili con ciascuna sottoscrizione Office 365, vedere [Report](../office-365-platform-service-description/reports.md). Per informazioni più dettagliate sulla pagina Rapporti nell'interfaccia di amministrazione di Office 365, vedere [Visualizzare e scaricare rapporti sull'utilizzo del servizio in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [Utilizzare i rapporti di protezione della posta in Office 365 per visualizzare i dati relativi a malware, posta indesiderata e rilevamenti delle regole](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p103">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md). For more detailed information about the Reports page in the Office 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="4d7b1-116">Reporting con la relativa cartella di lavoro Excel</span><span class="sxs-lookup"><span data-stu-id="4d7b1-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="4d7b1-p104">È anche possibile utilizzare la cartella di lavoro Excel 2013 per visualizzare rapporti di riepilogo con funzionalità di drill-down. Tuttavia, è consigliabile utilizzare invece i rapporti dell'interfaccia di amministrazione di Office 365. La cartella di lavoro per la creazione dei report di Excel 2013 diventerà obsoleta. Per una panoramica sulla cartella di lavoro e per i collegamenti per scaricarla e installarla, vedere la seguente [pagina di download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Per informazioni su come utilizzare la cartella di lavoro, vedere [Rapporti sulla protezione della posta utilizzando la cartella di lavoro per reporting di Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p104">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities. However, we recommend using the enhanced Office 365 admin center reports instead. The Excel 2013 reporting workbook is planned to be deprecated in the future. For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="4d7b1-122">Reporting tramite i servizi Web</span><span class="sxs-lookup"><span data-stu-id="4d7b1-122">Reporting using Web services</span></span>

<span data-ttu-id="4d7b1-p105">L'accesso ai rapporti sintetici e dettagliati su cassette postali, gruppi e dati di messaggistica avviene tramite il servizio REST/OData Tenant Reporting Web, un'interfaccia di programmazione che consente di creare rapporti personalizzati. Per ulteriori informazioni, vedere [Servizio Web dei rapporti per Office 365](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p105">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting Web service, which is a programmatic interface that enables you to create custom reports. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="4d7b1-125">Funzionalità di reporting e strumenti di risoluzione dei problemi nell'interfaccia di amministrazione di Exchange</span><span class="sxs-lookup"><span data-stu-id="4d7b1-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="4d7b1-126">Nell'interfaccia di amministrazione di Exchange sono disponibili le seguenti funzionalità di reporting e risoluzione dei problemi.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="4d7b1-127">Traccia di un messaggio di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="4d7b1-127">Trace an email message</span></span>

<span data-ttu-id="4d7b1-p106">La funzionalità di traccia dei messaggi permette a un amministratore di seguire l'iter dei messaggi di posta elettronica mentre attraversano il servizio Exchange Online. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Ciò consente all'amministratore di rispondere in modo preciso alle domande dei propri utenti e di risolvere i problemi del flusso di posta elettronica, riducendo la necessità di rivolgersi al supporto tecnico per assistenza.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p106">The message trace feature enables you as an administrator to follow email messages as they pass through your Exchange Online service. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="4d7b1-p107">Per la risoluzione di problemi generici, utilizzare gli strumenti di reporting per ottenere i dati necessari. Per problemi più specifici, per i quali è necessario avere i dettagli relativi a un determinato messaggio, utilizzare lo strumento di traccia dei messaggi.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="4d7b1-133">Per ulteriori informazioni sulla funzionalità di tracciamento dei messaggi, vedere [Tracciamento di un messaggio di posta elettronica](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="4d7b1-134">Rapporti di controllo</span><span class="sxs-lookup"><span data-stu-id="4d7b1-134">Auditing reports</span></span>

<span data-ttu-id="4d7b1-p108">Utilizzare la registrazione di controllo per risolvere i problemi di configurazione tenendo traccia delle modifiche specifiche apportate dagli amministratori e contribuire al rispetto dei requisiti normativi, di conformità e legali. In Exchange Online sono disponibili due tipi di registrazione di controllo:</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="4d7b1-p109">Registrazione di controllo dell'amministratore i registra qualsiasi azione eseguita da un amministratore. In questo modo è possibile risolvere problemi di configurazione o individuare la causa di problemi relativi alla sicurezza o alla conformità.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="4d7b1-p110">Nella registrazione di controllo della cassetta postale viene registrato ogni accesso a una cassetta postale da parte di un utente diverso dal proprietario della cassetta stessa. In questo modo è possibile stabilire chi ha effettuato l'accesso a una cassetta postale e quali operazioni ha eseguito.</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="4d7b1-141">Per informazioni sulla registrazione di controllo, vedere [Rapporti di controllo](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="4d7b1-142">Rapporti di messaggistica unificata</span><span class="sxs-lookup"><span data-stu-id="4d7b1-142">Unified Messaging reports</span></span>

<span data-ttu-id="4d7b1-p111">È possibile utilizzare questi rapporti per monitorare e risolvere i problemi della messaggistica unificata nell'organizzazione Exchange Online. Per ulteriori informazioni, vedere [Esecuzione di report per le chiamate alla casella vocale](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="4d7b1-145">Disponibilità delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="4d7b1-145">Feature Availability</span></span>

<span data-ttu-id="4d7b1-146">Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="4d7b1-146">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

