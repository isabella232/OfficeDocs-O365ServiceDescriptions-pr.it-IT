---
title: Flusso di posta in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Leggere questo articolo per informazioni sul flusso di posta in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 0923f31ccb639271303654cbdccf4890b2a55062
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653138"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Flusso di posta in Exchange Online Protection

Per la maggior parte delle organizzazioni che utilizzano Microsoft, microsoft ospita le cassette postali e si occupa del flusso di posta. Si tratta della configurazione più semplice e significa che Microsoft gestisce tutte le cassette postali e il filtro. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Exchange Online Protection (EOP) consente di eseguire questa operazione e fornisce l'elaborazione della posta indesiderata e antivirus nel cloud. Per ulteriori informazioni e per acquistare EOP, visitare [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Sono necessarie informazioni sulla gestione dei domini o su Directory Based Edge Blocking (DBEB)? Vedere [Gestione di destinatari, domini e società.](recipient-domain-and-company-management.md) Per ulteriori informazioni su tutte le funzionalità di EOP, vedere la descrizione del [servizio Exchange Online Protection.](exchange-online-protection-service-description.md)
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Routing della posta elettronica tra Microsoft e i propri server di posta elettronica

È possibile configurare un connettore per abilitare il flusso di posta tra Microsoft (incluso Exchange Online o EOP) e un server di posta elettronica basato su SMTP, ad esempio Exchange. Per ulteriori informazioni, vedere [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? Configurare [i connettori per instradare la posta tra Microsoft e i server di posta elettronica.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messaggistica sicura presso un partner di fiducia

In quanto cliente EOP, è possibile configurare un flusso di posta sicuro con un partner attendibile utilizzando i connettori Microsoft. Microsoft supporta la comunicazione sicura tramite TLS (Transport Layer Security) ed è possibile creare un connettore per applicare la crittografia tramite TLS. [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) è un protocollo crittografico che garantisce la sicurezza per le comunicazioni su Internet. Utilizzando i connettori, è possibile forzare il protocollo TSL sia per la posta in entrata che per quella in uscita utilizzando certificati autofirmati o convalidati da un'autorità di certificazione. È inoltre possibile applicare altre restrizioni, ad esempio specificando nomi di dominio o intervalli di indirizzi IP dai quali l'organizzazione partner invia messaggi di posta. 
  
Per ulteriori informazioni, vedere [Configurazione dei connettori per proteggere il flusso di posta con un'organizzazione partner](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Elenco sicuro indirizzi IP del partner

È possibile aggiungere l'indirizzo IP di un partner attendibile a un elenco di indirizzi attendibili al fine di assicurarsi che i messaggi inviati dal partner non siano soggetti al filtro posta indesiderata. A tale scopo, è possibile utilizzare l'elenco di indirizzi IP consentiti del filtro connessioni. Per ulteriori informazioni, vedere [Configurazione dei criteri di filtro delle connessioni](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).
  
## <a name="conditional-mail-routing"></a>Routing condizionale della posta

È possibile configurare un connettore con una regola di trasporto che instrada la posta verso un sito specifico, a seconda delle condizioni. Per maggiori informazioni, vedere [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Routing posta ibrida

Per ibrido si intende che una parte delle cassette postali si trova a livello locale e un'altra parte si trova nel cloud (Exchange Online). È possibile passare da una distribuzione autonoma (locale) a una ibrida.
  
In caso di distribuzione ibrida, è possibile proteggere le cassette postali cloud e locali con EOP. Per le cassette postali locali sono necessarie licenze autonome, quando sono protette da EOP. Per ulteriori informazioni sul routing della posta in una distribuzione ibrida, vedere [Transport routing nelle distribuzioni ibride di Exchange](/exchange/transport-routing).
  
Informazioni dettagliate sul provisioning della distribuzione ibrida e sul trasporto dei messaggi ibridi sono disponibili anche in [Assistente per la distribuzione di Microsoft Exchange Server](/exchange/exchange-deployment-assistant). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Descrizione del servizio [Exchange Online Protection.](exchange-online-protection-service-description.md)