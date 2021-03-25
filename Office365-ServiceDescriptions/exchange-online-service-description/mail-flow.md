---
title: Flusso di posta
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Per la maggior parte delle organizzazioni, microsoft ospita le cassette postali e si occupa del flusso di posta. Si tratta della configurazione più semplice e significa che Microsoft gestisce tutte le cassette postali e il filtro. Tuttavia, alcune organizzazioni necessitano di configurazioni del flusso di posta più complesse per garantire la conformità con esigenze aziendali o normative specifiche. Opzioni con tali caratteristiche sono presenti in questa sezione.
ms.openlocfilehash: cc00cd942f3b5b6ad5e919b981879ca44c48cec9
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173651"
---
# <a name="mail-flow"></a>Flusso di posta

Per la maggior parte delle organizzazioni, microsoft ospita le cassette postali e si occupa del flusso di posta. Si tratta della configurazione più semplice e significa che Microsoft gestisce tutte le cassette postali e il filtro. Tuttavia, alcune organizzazioni necessitano di configurazioni del flusso di posta più complesse per garantire la conformità con esigenze aziendali o normative specifiche. Opzioni con tali caratteristiche sono presenti in questa sezione. 
  
## <a name="custom-routing-of-outbound-email"></a>Routing personalizzato della posta in uscita

Microsoft Exchange Online può effettuare il routing del flusso di posta dall'organizzazione tramite un server locale o un servizio ospitato (talvolta denominato "smart hosting"). In questo modo l'organizzazione può utilizzare le appliance di prevenzione della perdita dei dati (DLP), eseguire post-elaborazione personalizzata della posta elettronica in uscita e recapitare la posta elettronica ai partner aziendali tramite reti private. Exchange Online supporta anche la funzionalità di riscrittura degli indirizzi, nella quale la posta in uscita viene inviata attraverso un gateway locale che ne modifica gli indirizzi. Questa funzionalità consente di nascondere i sottodomini, fare in modo che la posta elettronica di un'organizzazione multidominio venga visualizzata come un singolo dominio o che la posta elettronica inoltrata dal partner venga visualizzata come se fosse stata inviata dall'interno dell'organizzazione. Gli amministratori possono personalizzare il routing della posta dall'interfaccia di amministrazione di Exchange.
  
Per ulteriori informazioni, vedere [Set up connectors to route mail between Microsoft and your own email servers](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> Exchange Online può recapitare il flusso di posta all'interno e all'esterno dell'organizzazione. Se il dominio del destinatario è ospitato in Exchange Online con record MX DNS che puntano a Exchange Online Protection, il flusso di posta dal tenant al destinatario non viaggia su Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messaggistica sicura presso un partner di fiducia

In quanto cliente di Exchange Online, è possibile configurare un flusso di posta sicuro con un partner attendibile utilizzando i connettori Microsoft. Microsoft supporta la comunicazione sicura tramite TLS (Transport Layer Security) ed è possibile creare un connettore per applicare la crittografia tramite TLS. [TLS](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) è un protocollo crittografico che garantisce la sicurezza per le comunicazioni su Internet. Utilizzando i connettori, è possibile forzare il protocollo TSL sia per la posta in entrata che per quella in uscita utilizzando certificati autofirmati o convalidati da un'autorità di certificazione. È inoltre possibile applicare altre restrizioni, ad esempio specificando nomi di dominio o intervalli di indirizzi IP dai quali l'organizzazione partner invia messaggi di posta. 
  
Per ulteriori informazioni, vedere [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Potrebbe essere obbligatorio utilizzare un certificato convalidato da un'autorità di certificazione. 
  
## <a name="conditional-mail-routing"></a>Routing condizionale della posta

È possibile indirizzare la posta diretta a siti specifici utilizzando i connettori e le regole di trasporto. Con il routing basato su criteri, è possibile scegliere un connettore in base a specifiche condizioni.
  
Per ulteriori informazioni, vedere [Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Elenco indirizzi attendibili della posta in arrivo:

È possibile aggiungere l'indirizzo IP di un partner attendibile a un elenco di indirizzi attendibili al fine di assicurarsi che i messaggi inviati dal partner non siano soggetti al filtro posta indesiderata. A tale scopo, è possibile utilizzare l'elenco di indirizzi IP consentiti del filtro connessioni.
  
Per ulteriori informazioni, vedere [Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Routing posta ibrida

La distribuzione ibrida offre alle organizzazioni la possibilità di estendere al cloud le numerose funzionalità e il controllo amministrativo che hanno nell'organizzazione Microsoft Exchange locale. Con il trasporto ibrido i messaggi scambiati dagli utenti di qualsiasi organizzazione vengono autenticati, crittografati e trasferiti usando Transport Layer Security (TLS) e appaiono come interni a componenti di Exchange quali i ruoli di trasporto, journal e criteri antispam. Il trasporto ibrido viene configurato dalla procedura guidata di configurazione ibrida in Exchange Server.
  
Per ulteriori informazioni sul routing della posta in una distribuzione ibrida, vedere [Routing del trasporto nelle distribuzioni ibride di Exchange](/exchange/transport-routing).
  
Informazioni dettagliate sul provisioning della distribuzione ibrida e sul trasporto dei messaggi ibridi sono disponibili anche in [Assistente per la distribuzione di Microsoft Exchange Server](/exchange/exchange-deployment-assistant). 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Spazio indirizzo condiviso con controllo routing locale (il record MX punta a Exchange locale)

Lo spazio di indirizzi condiviso con il controllo del routing locale (MX punta a locale) è uno scenario di distribuzione ibrida del routing della posta in cui le cassette postali sono ospitate parzialmente in Exchange Online e parzialmente in locale e il flusso di posta Internet in arrivo e in uscita viene instradato attraverso l'organizzazione exchange locale. Questo scenario viene anche detto trasporto posta centralizzato. In questo scenario, Viene eseguito il provisioning di Exchange Online con EOP e la posta Internet in arrivo viene instradata al server di posta locale prima di essere instradata a EOP e infine alle cassette postali ospitate in Exchange Online. Inoltre, la posta in uscita dalle cassette postali di Exchange Online passa attraverso l'organizzazione Exchange locale relativamente ai messaggi inviati a destinatari esterni. Con questa configurazione, è possibile utilizzare un singolo spazio dei nomi di dominio SMTP per tutte le cassette postali sia dell'organizzazione Exchange locale sia dell'organizzazione Exchange Online. 
  
Per ulteriori informazioni sulle opzioni di trasporto in una distribuzione ibrida, vedere [Opzioni di trasporto nelle distribuzioni ibride di Exchange](/exchange/transport-options).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Spazio indirizzo condiviso con controllo routing locale (il record MX punta a EOP)

Lo spazio di indirizzi condiviso senza controllo routing locale (il record MX punta a EOP) è uno scenario di routing della posta ibrida, in cui le cassette postali sono ospitate in parte sul cloud tramite Exchange Online e in parte localmente mentre il record MX punta a Exchange Online Protection (EOP). Questo scenario è appropriato quando si utilizza Microsoft per ospitare alcune delle cassette postali dell'organizzazione e si desidera che EOP protegga sia le cassette postali locali che le cassette postali cloud. In questo scenario la posta inviata a destinatari interni all'organizzazione viene inizialmente instradata attraverso l'EOP, dove avviene il filtraggio anti-spam e in base ai criteri, prima di essere recapitata alle cassette postali locali e sul cloud. 
  
Per ulteriori informazioni sulle opzioni di trasporto in una distribuzione ibrida, vedere [Opzioni di trasporto nelle distribuzioni ibride di Exchange](/exchange/transport-options).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Risoluzione dei problemi di una distribuzione con la procedura guidata di configurazione ibrida

L'utilizzo della procedura guidata di configurazione ibrida per configurare una distribuzione ibrida in Microsoft Exchange Server riduce al minimo il rischio di avere problemi durante la distribuzione ibrida. Tuttavia, ci sono alcune aree tipiche fuori dall'ambito della configurazione guidata ibrida che, se configurate male, possono dare origine a parecchi problemi durante la distribuzione ibrida. Queste aree sono la configurazione del server Accesso client e l'installazione e configurazione dei certificati.
  
Per ulteriori informazioni sulla risoluzione dei problemi di una distribuzione con la configurazione guidata per distribuzioni ibride, vedere [Risolvere i problemi di una distribuzione ibrida](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment).
  
### <a name="managing-a-hybrid-configuration"></a>Gestione di una configurazione ibrida

È possibile modificare una configurazione ibrida esistente modificando le impostazione della configurazione guidata ibrida. Gli scenari possibili includono la disattivazione del trasporto centralizzato o del trasporto della posta sicura.
  
Per ulteriori informazioni sulla gestione della configurazione di una distribuzione ibrida, vedere [Gestire una distribuzione ibrida](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150)).
  
### <a name="hybrid-deployment-requirements"></a>Requisiti di una distribuzione ibrida

Per ulteriori informazioni sui requisiti di una distribuzione ibrida, vedere [Prerequisiti per la distribuzione ibrida](/exchange/hybrid-deployment-prerequisites).
  
> [!IMPORTANT]
> In alcune configurazioni ibride, potrebbe essere necessario acquistare le licenze di Exchange Online Protection per le cassette postali locali. 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere la descrizione del servizio [Exchange Online.](exchange-online-service-description.md)
