---
title: Flusso di posta [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e indica che tutte le cassette postali e i filtri vengono gestiti da Office 365. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Exchange Online Protection (EOP) consente di eseguire questa operazione e fornisce l'elaborazione della posta elettronica antispamming e antivirus nel cloud.
ms.openlocfilehash: c6a41df3e8b8c157d599f6a9d55be4b7f826e1d9
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/17/2020
ms.locfileid: "42688069"
---
# <a name="mail-floweop"></a>Flusso di posta [EOP]

Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e indica che tutte le cassette postali e i filtri vengono gestiti da Office 365. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Exchange Online Protection (EOP) consente di eseguire questa operazione e fornisce l'elaborazione della posta elettronica antispamming e antivirus nel cloud. Per ulteriori informazioni e per acquistare EOP, visitare [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Sono necessarie informazioni sulla gestione dei domini o su Directory Based Edge Blocking (DBEB)? Vedere [destinatario, dominio e gestione aziendale](recipient-domain-and-company-management.md). Per ulteriori informazioni su tutte le funzionalità di EOP, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Instradare la posta tra Office 365 e i server di posta elettronica della propria organizzazione

È possibile configurare un connettore per abilitare il flusso di posta tra Office 365 (compreso Exchange Online o EOP) e il server di posta elettronica basato su SMTP, ad esempio, Exchange. Per ulteriori informazioni, vedere [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? e [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messaggistica sicura presso un partner di fiducia

Come cliente EOP, è possibile configurare il flusso di posta sicura con un partner di fiducia utilizzando i connettori di Office 365. Office 365 supporta la comunicazione sicura attraverso il protocollo Transport Layer Security (TLS) ed è possibile creare un connettore per forzare la crittografia tramite TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) è un protocollo crittografico che fornisce sicurezza per le comunicazioni via Internet. Utilizzando i connettori, è possibile forzare il protocollo TSL sia per la posta in entrata che per quella in uscita utilizzando certificati autofirmati o convalidati da un'autorità di certificazione. È inoltre possibile applicare altre restrizioni, ad esempio specificando nomi di dominio o intervalli di indirizzi IP dai quali l'organizzazione partner invia messaggi di posta. 
  
Per ulteriori informazioni, vedere [Configurazione dei connettori per proteggere il flusso di posta con un'organizzazione partner](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Elenco sicuro indirizzi IP del partner

È possibile aggiungere l'indirizzo IP di un partner attendibile a un elenco di indirizzi attendibili al fine di assicurarsi che i messaggi inviati dal partner non siano soggetti al filtro posta indesiderata. A tale scopo, è possibile utilizzare l'elenco di indirizzi IP consentiti del filtro connessioni. Per ulteriori informazioni, vedere [Configurazione dei criteri di filtro delle connessioni](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Routing condizionale della posta

È possibile configurare un connettore con una regola di trasporto che instrada la posta verso un sito specifico, a seconda delle condizioni. Per maggiori informazioni, vedere [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Routing posta ibrida

Per ibrido si intende che una parte delle cassette postali si trova a livello locale e un'altra parte si trova nel cloud (Exchange Online). È possibile passare da una distribuzione autonoma (locale) a una ibrida.
  
In caso di distribuzione ibrida, è possibile proteggere le cassette postali cloud e locali con EOP. Per le cassette postali locali sono necessarie licenze autonome, quando sono protette da EOP. Per ulteriori informazioni sul routing della posta in una distribuzione ibrida, vedere [Transport routing nelle distribuzioni ibride di Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Informazioni dettagliate sul provisioning della distribuzione ibrida e sul trasporto dei messaggi ibridi sono disponibili anche in [Assistente per la distribuzione di Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
