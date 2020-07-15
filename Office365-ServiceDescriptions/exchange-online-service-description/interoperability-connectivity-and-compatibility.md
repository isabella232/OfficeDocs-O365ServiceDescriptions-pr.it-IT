---
title: Interoperabilità, connettività e compatibilità
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132750"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilità, connettività e compatibilità

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilità con altri prodotti Microsoft

### <a name="skype-for-business-online"></a>Skype for Business Online

Per gli utenti che hanno distribuito Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 locale, Microsoft Office Communicator può stabilire una connessione a Microsoft Exchange Online utilizzando i Servizi Web Exchange per accedere ai messaggi Fuori sede e ai dati del calendario.
  
Lync Server 2010 e Lync Server 2013 locale possono interagire con Exchange Online in due ulteriori modalità:
  
- Interoperabilità della messaggistica istantanea e della presenza in Outlook sul Web
    
- Interoperabilità posta vocale
    
For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Per i clienti che hanno distribuito Microsoft SharePoint Server o SharePoint Online come parte di un piano di sottoscrizione, SharePoint è in grado di connettersi a Exchange Online per i servizi integrati.
  
Per ulteriori informazioni sul collegamento di SharePoint a Exchange Online, vedere [Usare SharePoint Online su un dominio personalizzato insieme ad altri servizi](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Funzionalità per la connettività esterna

Exchange Online offre le seguenti funzionalità per il collegamento alle applicazioni e ai dispositivi esterni:
  
- **Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development. 
    
- **Come relay SMTP** È possibile configurare Exchange Online come servizio di recapito SMTP per l'inoltro dei messaggi di posta elettronica inviati da gateway fax, network appliance e applicazioni personalizzate. 
    
### <a name="exchange-web-services"></a>Servizi Web Exchange

Servizi Web Exchange (EWS) è l'API di sviluppo consigliata per Exchange Server ed Exchange Online. Utilizzando Servizi Web Exchange o Exchange Web Services Managed API, gli amministratori possono accedere ai dati archiviati con Exchange Online dalle applicazioni eseguite in locale, in Azure o in altri servizi ospitati. EWS consente agli amministratori di eseguire azioni specializzate, ad esempio l'esecuzione di query sui contenuti di una cassetta postale, la registrazione di un evento del calendario, la creazione di un'attività o l'attivazione di un'azione specifica in base al contenuto di un messaggio di posta elettronica. Exchange Online abilita la funzionalità EWS concedendo autorizzazioni per le applicazioni agli account dei clienti. Tali autorizzazioni consentono all'applicazione del cliente di accedere alla cassetta postale dell'applicazione e aggiungere contenuto. Exchange Impersonation è un metodo utilizzato per concedere autorizzazioni per le applicazioni. Per ulteriori informazioni sull'utilizzo dei Servizi Web Exchange con Exchange Online, vedere gli articoli tecnici in Exchange Online Developer Center.
  
### <a name="smtp-relay"></a>Relay SMTP

Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

