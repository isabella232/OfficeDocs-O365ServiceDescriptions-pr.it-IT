---
title: Flusso di posta [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e indica che tutte le cassette postali e i filtri vengono gestiti da Office 365. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Per questo motivo, possono usare Exchange Online Protection (EOP) e ottenere anche controlli antivirus e contro la posta indesiderata nel cloud. Per ulteriori informazioni e per acquistare EOP, visitare Exchange Online Protection.
ms.openlocfilehash: c55d1d376d617b863a75ff609cbc3f064418746b
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341825"
---
# <a name="mail-floweop"></a>Flusso di posta [EOP]

Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e indica che tutte le cassette postali e i filtri vengono gestiti da Office 365. Tuttavia, alcune organizzazioni hanno la necessità di tenere in locale tutte le cassette postali. Per questo motivo, possono usare Exchange Online Protection (EOP) e ottenere anche controlli antivirus e contro la posta indesiderata nel cloud. Per ulteriori informazioni e per acquistare EOP, visitare [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
Sono necessarie informazioni sulla gestione dei domini o su Directory Based Edge Blocking (DBEB)? Vedere [Gestione destinatari, dominio e società](recipient-domain-and-company-management.md). Per ulteriori informazioni su tutte le funzionalità EOP, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Instradare la posta tra Office 365 e i server di posta elettronica della propria organizzazione
<a name="BKMK_outboundmailrouting"> </a>

È possibile configurare un connettore per abilitare il flusso di posta tra Office 365 (compreso Exchange Online o EOP) e il server di posta elettronica basato su SMTP, ad esempio, Exchange. Per ulteriori informazioni, vedere [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? e [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messaggistica sicura presso un partner di fiducia
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

Come cliente EOP, è possibile configurare il flusso di posta sicura con un partner di fiducia utilizzando i connettori di Office 365. Office 365 supporta la comunicazione sicura attraverso il protocollo Transport Layer Security (TLS) ed è possibile creare un connettore per forzare la crittografia tramite TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) è un protocollo crittografico che protegge le comunicazioni via Internet. Utilizzando i connettori, è possibile forzare il protocollo TSL sia per la posta in entrata che per quella in uscita utilizzando certificati autofirmati o convalidati da un'autorità di certificazione. È inoltre possibile applicare altre restrizioni, ad esempio specificando nomi di dominio o intervalli di indirizzi IP dai quali l'organizzazione partner invia messaggi di posta. 
  
Per ulteriori informazioni, vedere [Configurazione dei connettori per proteggere il flusso di posta con un'organizzazione partner](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).
  
## <a name="safe-listing-a-partners-ip-address"></a>Elenco sicuro indirizzi IP del partner
<a name="BKMK_safelistingapartnersipaddress"> </a>

È possibile aggiungere l'indirizzo IP di un partner attendibile a un elenco di indirizzi attendibili al fine di assicurarsi che i messaggi inviati dal partner non siano soggetti al filtro posta indesiderata. A tale scopo, è possibile utilizzare l'elenco di indirizzi IP consentiti del filtro connessioni. Per ulteriori informazioni, vedere [Configurazione dei criteri di filtro delle connessioni](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Routing condizionale della posta
<a name="BKMK_conditionalmailrouting"> </a>

È possibile configurare un connettore con una regola di trasporto che instrada la posta verso un sito specifico, a seconda delle condizioni. Per maggiori informazioni, vedere [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="hybrid-mail-routing"></a>Hybrid mail routing
<a name="BKMK_hybridmailrouting"> </a>

Per ibrido si intende che una parte delle cassette postali si trova a livello locale e un'altra parte si trova nel cloud (Exchange Online). È possibile passare da una distribuzione autonoma (locale) a una ibrida.
  
In caso di distribuzione ibrida, è possibile proteggere le cassette postali cloud e locali con EOP. Per le cassette postali locali sono necessarie licenze autonome, quando sono protette da EOP. Per ulteriori informazioni sul routing della posta in una distribuzione ibrida, vedere [Transport routing nelle distribuzioni ibride di Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Informazioni dettagliate sul provisioning della distribuzione ibrida e sul trasporto dei messaggi ibridi sono disponibili anche in [Assistente per la distribuzione di Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità
<a name="BKMK_hybridmailrouting"> </a>

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).
  

