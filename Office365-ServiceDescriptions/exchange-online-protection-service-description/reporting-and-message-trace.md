---
title: Creazione di report e traccia messaggio
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft (EOP) Exchange Online Protection offre diversi rapporti che consentono di determinare lo stato generale e l'integrità dell'organizzazione. Alcuni rapporti sono disponibili nell'interfaccia di amministrazione di Microsoft 365, mentre altri sono disponibili nell'interfaccia di amministrazione di Exchange (EAC).
ms.openlocfilehash: d4e0f1104bfc87f5641cc241d2a526e8d56f0d1a
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545859"
---
# <a name="reporting-and-message-trace"></a>Creazione di report e traccia messaggio

Microsoft (EOP) Exchange Online Protection offre diversi rapporti che consentono di determinare lo stato generale e l'integrità dell'organizzazione. Alcuni rapporti sono disponibili nell'interfaccia di amministrazione di Microsoft 365, mentre altri sono disponibili nell'interfaccia di amministrazione di Exchange (EAC).

Per informazioni su tutte le funzionalità di EOP? Vedere la [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Rapporti dell'interfaccia di amministrazione di Microsoft 365

La pagina report nell'interfaccia di amministrazione di Microsoft 365 fornisce informazioni sul traffico dei messaggi, sui rilevamenti di posta indesiderata e malware e sui messaggi interessati dalle regole del flusso di posta (note anche come regole di trasporto) o dai criteri di prevenzione della perdita di dati (DLP). I report migliorati per la protezione, le regole e DLP forniscono un'esperienza di report interattiva agli amministratori di EOP. Tali report forniscono i dati di riepilogo e la capacità di eseguire il drill-down dei dettagli sui singoli messaggi.

Per informazioni più dettagliate su questi rapporti, vedere [Use Mail Protection Reports in Office 365 to view data about malware, spam, and Rule detections](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> Molte delle funzionalità di creazione di rapporti basate su REST e dei relativi cmdlet sono state deprecate nel gennaio 2018. Per informazioni sui report di Microsoft Graph sostitutivi disponibili in Office 365, vedere l'argomento relativo ai [report sull'utilizzo di office 365 in Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).

Non disponibili per gli utenti EOP autonomi. È possibile utilizzare il servizio Web di Reporting tenant REST/OData per raccogliere a livello di programmazione report di riepilogo e dettagliati sui dati di messaggistica ed è possibile visualizzare i dati in una pagina Web in un portale di gestione Web personalizzato.

## <a name="message-trace"></a>Traccia dei messaggi

La funzionalità di traccia dei messaggi nell'interfaccia di amministrazione di Exchange consente, come amministratore, di seguire i messaggi di posta elettronica che passano attraverso il EOP. Questa funzionalità consente di stabilire se un determinato messaggio di posta elettronica è stato ricevuto, rifiutato, differito o recapitato dal servizio. Mostra inoltre quali azioni sono state eseguite sul messaggio prima del raggiungimento dello stato finale. La disponibilità di informazioni dettagliate su un messaggio specifico consente di rispondere in modo efficiente alle domande dell'utente, risolvere i problemi relativi al flusso di posta, convalidare le modifiche apportate ai criteri e ridurre la necessità di contattare il supporto tecnico per assistenza. Per ulteriori informazioni, vedere [eseguire una traccia dei messaggi e visualizzare i risultati nell'](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)interfaccia di amministrazione di Exchange.

## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
