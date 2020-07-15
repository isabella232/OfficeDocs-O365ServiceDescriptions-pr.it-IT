---
title: Flusso di posta [EOP]
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e significa che Microsoft gestisce tutte le cassette postali e il filtro. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Exchange Online Protection (EOP) consente di eseguire questa operazione e fornisce l'elaborazione della posta elettronica antispamming e antivirus nel cloud.
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132820"
---
# <a name="mail-floweop"></a>Flusso di posta [EOP]

Per la maggior parte delle organizzazioni che utilizzano Microsoft, è necessario ospitare le cassette postali e prendersi cura del flusso di posta. È la configurazione più semplice e significa che Microsoft gestisce tutte le cassette postali e il filtro. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Exchange Online Protection (EOP) consente di eseguire questa operazione e fornisce l'elaborazione della posta elettronica antispamming e antivirus nel cloud. Per ulteriori informazioni e per acquistare EOP, visitare [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Sono necessarie informazioni sulla gestione dei domini o su Directory Based Edge Blocking (DBEB)? Vedere [destinatario, dominio e gestione aziendale](recipient-domain-and-company-management.md). Per ulteriori informazioni su tutte le funzionalità di EOP, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Routing della posta elettronica tra Microsoft e i server di posta elettronica personali

È possibile configurare un connettore per abilitare il flusso di posta tra Microsoft (incluso Exchange Online o EOP) e un server di posta elettronica basato su SMTP, ad esempio Exchange. Per ulteriori informazioni, vedere [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? E [impostare i connettori per instradare la posta tra Microsoft e i propri server di posta elettronica](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messaggistica sicura presso un partner di fiducia

Come cliente di EOP, è possibile configurare il flusso di posta sicura con un partner attendibile tramite i connettori Microsoft. Microsoft supporta la comunicazione sicura tramite TLS (Transport Layer Security) ed è possibile creare un connettore per applicare la crittografia tramite TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) è un protocollo crittografico che fornisce sicurezza per le comunicazioni via Internet. Utilizzando i connettori, è possibile forzare il protocollo TSL sia per la posta in entrata che per quella in uscita utilizzando certificati autofirmati o convalidati da un'autorità di certificazione. È inoltre possibile applicare altre restrizioni, ad esempio specificando nomi di dominio o intervalli di indirizzi IP dai quali l'organizzazione partner invia messaggi di posta. 
  
Per ulteriori informazioni, vedere [Configurazione dei connettori per proteggere il flusso di posta con un'organizzazione partner](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Elenco sicuro indirizzi IP del partner

You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Routing condizionale della posta

You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Routing posta ibrida

Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.
  
If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Informazioni dettagliate sul provisioning della distribuzione ibrida e sul trasporto dei messaggi ibridi sono disponibili anche in [Assistente per la distribuzione di Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
