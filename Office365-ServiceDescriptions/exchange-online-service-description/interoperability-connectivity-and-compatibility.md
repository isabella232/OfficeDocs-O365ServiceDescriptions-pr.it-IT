---
title: Interoperabilità, connettività e compatibilità
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 75e607242e42a6c621bc87c62bf28f5e8c6f3b31
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035993"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilità, connettività e compatibilità

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilità con altri prodotti Microsoft

### <a name="skype-for-business-online"></a>Skype for Business online

Per gli utenti che hanno distribuito Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 locale, Microsoft Office Communicator può stabilire una connessione a Microsoft Exchange Online utilizzando i Servizi Web Exchange per accedere ai messaggi Fuori sede e ai dati del calendario.
  
Lync Server 2010 e Lync Server 2013 locale possono interagire con Exchange Online in due ulteriori modalità:
  
- Messaggistica istantanea e interoperabilità con la presenza in Outlook Web App
    
- Interoperabilità posta vocale
    
Per ulteriori informazioni sulla configurazione di Skype for Business Server 2015 con Exchange Online, vedere [Configurazione dell'integrazione di Skype for Business Server 2015 locale con Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Per configurazioni ibride, vedere [Configurazioni ibride di Skype for Business Server 2015 supportate](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Per gli utenti che hanno distribuito Microsoft SharePoint Server o SharePoint Online nel piano di sottoscrizione di Office 365, SharePoint può stabilire una connessione a Exchange Online per i servizi integrati.
  
Per ulteriori informazioni sul collegamento di SharePoint a Exchange Online, vedere [Usare SharePoint Online su un dominio personalizzato insieme ad altri servizi](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Funzionalità per la connettività esterna

Exchange Online offre le seguenti funzionalità per il collegamento alle applicazioni e ai dispositivi esterni:
  
- **Mediante protocolli di messaggistica come MAPI tramite HTTP, SMTP, POP3, IMAP4 o servizi Exchange Web** Le applicazioni esterne eseguite in locale, in Azure o in altri servizi ospitati possono accedere ai dati archiviati con Exchange Online utilizzando protocolli di messaggistica come MAPI tramite HTTP, SMTP, POP3 e IMAPv4. Servizi Web Exchange o Exchange Web Services Managed API sono consigliati per lo sviluppo delle applicazioni. 
    
- **Come relay SMTP** È possibile configurare Exchange Online come servizio di recapito SMTP per l'inoltro dei messaggi di posta elettronica inviati da gateway fax, network appliance e applicazioni personalizzate. 
    
### <a name="exchange-web-services"></a>Servizi Web Exchange

Servizi Web Exchange (EWS) è l'API di sviluppo consigliata per Exchange Server ed Exchange Online. Utilizzando Servizi Web Exchange o Exchange Web Services Managed API, gli amministratori possono accedere ai dati archiviati con Exchange Online dalle applicazioni eseguite in locale, in Azure o in altri servizi ospitati. Servizi Web Exchange consente agli amministratori di eseguire azioni specializzate come l'esecuzione di query sul contenuto di una cassetta postale, l'inserimento di eventi del calendario, la creazione di attività o l'attivazione di un'azione specifica in base al contenuto di un messaggio di posta elettronica. Exchange Online abilita la funzionalità EWS concedendo autorizzazioni per le applicazioni agli account dei clienti. Tali autorizzazioni consentono all'applicazione del cliente di accedere alla cassetta postale dell'applicazione e aggiungere contenuto. Exchange Impersonation è un metodo utilizzato per concedere autorizzazioni per le applicazioni. Per ulteriori informazioni sull'utilizzo dei Servizi Web Exchange con Exchange Online, vedere gli articoli tecnici in Exchange Online Developer Center.
  
### <a name="smtp-relay"></a>Relay SMTP

È possibile utilizzare Exchange Online come servizio di recapito SMTP per inoltrare messaggi di posta elettronica da gateway fax, network appliance e applicazioni personalizzate. Ad esempio, se un'applicazione line-of-business invia avvisi di posta elettronica agli utenti, può essere configurata per l'utilizzo di Exchange Online come sistema di recapito della posta. L'applicazione o servizio deve eseguire l'autenticazione con il nome utente e la password di una cassetta postale di Exchange Online valida e con licenza e connettersi utilizzando Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

