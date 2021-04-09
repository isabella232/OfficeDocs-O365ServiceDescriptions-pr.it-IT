---
title: Creazione di rapporti e traccia dei messaggi in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Leggere questo articolo per informazioni su Reporting and message trace in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 383c222563e76d4a5613c9faac5b68417fa64b8a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653128"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Creazione di rapporti e traccia dei messaggi in Exchange Online Protection

Microsoft (EOP) Exchange Online Protection offre diversi rapporti che consentono di determinare lo stato generale e l'integrità dell'organizzazione. Alcuni report sono disponibili nell'interfaccia di amministrazione di Microsoft 365, mentre altri sono disponibili nell'interfaccia di amministrazione di Exchange (EAC).

Per informazioni su tutte le funzionalità di EOP? Vedere la [descrizione del servizio Exchange Online Protection.](exchange-online-protection-service-description.md)

## <a name="microsoft-365-admin-center-reports"></a>Report dell'interfaccia di amministrazione di Microsoft 365

La pagina Report nell'interfaccia di amministrazione di Microsoft 365 fornisce informazioni sul traffico dei messaggi, sui rilevamenti di posta indesiderata e malware e sui messaggi interessati dalle regole del flusso di posta (note anche come regole di trasporto) o dai criteri di prevenzione della perdita dei dati (DLP). I report migliorati per la protezione, le regole e DLP forniscono un'esperienza di report interattiva agli amministratori di EOP. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.

Per informazioni più dettagliate su questi report, vedere [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> Molte delle funzionalità di creazione di report basate su REST e i cmdlet correlati sono stati deprecati a gennaio 2018. Per informazioni sui report di Microsoft Graph sostitutivi disponibili in Office 365, vedere i sottoargomenti di Utilizzo dei report [di utilizzo in Microsoft Graph.](/graph/api/resources/report)

Non disponibili per gli utenti EOP autonomi. È possibile utilizzare il servizio Web REST/OData Tenant Reporting per raccogliere a livello di programmazione report di riepilogo e dettagliati sui dati di messaggistica e visualizzare i dati in una pagina Web in un portale di gestione Web personalizzato.

## <a name="message-trace"></a>Traccia dei messaggi

La funzionalità di traccia dei messaggi nell'interfaccia di amministrazione di Exchange consente all'amministratore di seguire i messaggi di posta elettronica mentre passano attraverso EOP. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Mostra inoltre quali azioni sono state eseguite sul messaggio prima del raggiungimento dello stato finale. La disponibilità di informazioni dettagliate su un messaggio specifico consente di rispondere in modo efficiente alle domande dell'utente, risolvere i problemi relativi al flusso di posta, convalidare le modifiche apportate ai criteri e ridurre la necessità di contattare il supporto tecnico per assistenza. Per ulteriori informazioni, vedere [Run a message trace and view the results in the Exchange admin center.](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)

## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Descrizione del servizio [Exchange Online Protection.](exchange-online-protection-service-description.md)