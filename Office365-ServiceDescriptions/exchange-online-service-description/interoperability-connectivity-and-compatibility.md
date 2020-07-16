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
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="efc1d-102">Interoperabilità, connettività e compatibilità</span><span class="sxs-lookup"><span data-stu-id="efc1d-102">Interoperability, connectivity, and compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="efc1d-103">Interoperabilità con altri prodotti Microsoft</span><span class="sxs-lookup"><span data-stu-id="efc1d-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="efc1d-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="efc1d-104">Skype for Business Online</span></span>

<span data-ttu-id="efc1d-105">Per gli utenti che hanno distribuito Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 locale, Microsoft Office Communicator può stabilire una connessione a Microsoft Exchange Online utilizzando i Servizi Web Exchange per accedere ai messaggi Fuori sede e ai dati del calendario.</span><span class="sxs-lookup"><span data-stu-id="efc1d-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="efc1d-106">Lync Server 2010 e Lync Server 2013 locale possono interagire con Exchange Online in due ulteriori modalità:</span><span class="sxs-lookup"><span data-stu-id="efc1d-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="efc1d-107">Interoperabilità della messaggistica istantanea e della presenza in Outlook sul Web</span><span class="sxs-lookup"><span data-stu-id="efc1d-107">IM and presence interoperability in Outlook on the web</span></span>
    
- <span data-ttu-id="efc1d-108">Interoperabilità posta vocale</span><span class="sxs-lookup"><span data-stu-id="efc1d-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="efc1d-p101">Per ulteriori informazioni sulla configurazione di Skype for Business Server 2015 con Exchange Online, vedere [Configurazione dell'integrazione di Skype for Business Server 2015 locale con Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Per configurazioni ibride, vedere [Configurazioni ibride di Skype for Business Server 2015 supportate](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="efc1d-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="efc1d-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="efc1d-111">Microsoft SharePoint</span></span>

<span data-ttu-id="efc1d-112">Per i clienti che hanno distribuito Microsoft SharePoint Server o SharePoint Online come parte di un piano di sottoscrizione, SharePoint è in grado di connettersi a Exchange Online per i servizi integrati.</span><span class="sxs-lookup"><span data-stu-id="efc1d-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="efc1d-113">Per ulteriori informazioni sul collegamento di SharePoint a Exchange Online, vedere [Usare SharePoint Online su un dominio personalizzato insieme ad altri servizi](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="efc1d-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="efc1d-114">Funzionalità per la connettività esterna</span><span class="sxs-lookup"><span data-stu-id="efc1d-114">Features for external connectivity</span></span>

<span data-ttu-id="efc1d-115">Exchange Online offre le seguenti funzionalità per il collegamento alle applicazioni e ai dispositivi esterni:</span><span class="sxs-lookup"><span data-stu-id="efc1d-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="efc1d-p102">**Mediante protocolli di messaggistica come MAPI tramite HTTP, SMTP, POP3, IMAP4 o servizi Exchange Web** Le applicazioni esterne eseguite in locale, in Azure o in altri servizi ospitati possono accedere ai dati archiviati con Exchange Online utilizzando protocolli di messaggistica come MAPI tramite HTTP, SMTP, POP3 e IMAPv4. Servizi Web Exchange o Exchange Web Services Managed API sono consigliati per lo sviluppo delle applicazioni.</span><span class="sxs-lookup"><span data-stu-id="efc1d-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="efc1d-118">**Come relay SMTP** È possibile configurare Exchange Online come servizio di recapito SMTP per l'inoltro dei messaggi di posta elettronica inviati da gateway fax, network appliance e applicazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="efc1d-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="efc1d-119">Servizi Web Exchange</span><span class="sxs-lookup"><span data-stu-id="efc1d-119">Exchange Web Services</span></span>

<span data-ttu-id="efc1d-120">Servizi Web Exchange (EWS) è l'API di sviluppo consigliata per Exchange Server ed Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="efc1d-120">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online.</span></span> <span data-ttu-id="efc1d-121">Utilizzando Servizi Web Exchange o Exchange Web Services Managed API, gli amministratori possono accedere ai dati archiviati con Exchange Online dalle applicazioni eseguite in locale, in Azure o in altri servizi ospitati.</span><span class="sxs-lookup"><span data-stu-id="efc1d-121">Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> <span data-ttu-id="efc1d-122">EWS consente agli amministratori di eseguire azioni specializzate, ad esempio l'esecuzione di query sui contenuti di una cassetta postale, la registrazione di un evento del calendario, la creazione di un'attività o l'attivazione di un'azione specifica in base al contenuto di un messaggio di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="efc1d-122">EWS lets administrators perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message.</span></span> <span data-ttu-id="efc1d-123">Exchange Online abilita la funzionalità EWS concedendo autorizzazioni per le applicazioni agli account dei clienti.</span><span class="sxs-lookup"><span data-stu-id="efc1d-123">Exchange Online enables EWS functionality by granting application permissions to customer accounts.</span></span> <span data-ttu-id="efc1d-124">Tali autorizzazioni consentono all'applicazione del cliente di accedere alla cassetta postale dell'applicazione e aggiungere contenuto.</span><span class="sxs-lookup"><span data-stu-id="efc1d-124">These permissions allow the customer application to access the application mailbox and add content.</span></span> <span data-ttu-id="efc1d-125">Exchange Impersonation è un metodo utilizzato per concedere autorizzazioni per le applicazioni.</span><span class="sxs-lookup"><span data-stu-id="efc1d-125">Exchange Impersonation is one method used to grant application permissions.</span></span> <span data-ttu-id="efc1d-126">Per ulteriori informazioni sull'utilizzo dei Servizi Web Exchange con Exchange Online, vedere gli articoli tecnici in Exchange Online Developer Center.</span><span class="sxs-lookup"><span data-stu-id="efc1d-126">For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="efc1d-127">Relay SMTP</span><span class="sxs-lookup"><span data-stu-id="efc1d-127">SMTP relay</span></span>

<span data-ttu-id="efc1d-p104">È possibile utilizzare Exchange Online come servizio di recapito SMTP per inoltrare messaggi di posta elettronica da gateway fax, network appliance e applicazioni personalizzate. Ad esempio, se un'applicazione line-of-business invia avvisi di posta elettronica agli utenti, può essere configurata per l'utilizzo di Exchange Online come sistema di recapito della posta. L'applicazione o servizio deve eseguire l'autenticazione con il nome utente e la password di una cassetta postale di Exchange Online valida e con licenza e connettersi utilizzando Transport Layer Security (TLS).</span><span class="sxs-lookup"><span data-stu-id="efc1d-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="efc1d-131">Disponibilità delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="efc1d-131">Feature availability</span></span>

<span data-ttu-id="efc1d-132">Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="efc1d-132">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

