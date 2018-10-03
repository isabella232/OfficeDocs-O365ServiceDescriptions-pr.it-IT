---
title: Flusso della posta
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 'Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e indica che tutte le cassette postali e il filtro vengono gestiti da Office 365. Tuttavia, alcune organizzazioni necessitano di configurazioni del flusso di posta più complesse per garantire la conformità con esigenze aziendali o normative specifiche. Opzioni con tali caratteristiche sono presenti in questa sezione. '
ms.openlocfilehash: 3decc04fb4c426e161541c1d24480cc0344b0a00
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036060"
---
# <a name="mail-flow"></a>Flusso della posta

Per la maggior parte delle organizzazioni che utilizzano Office 365, Microsoft ospita le cassette postali e gestisce la posta elettronica. È la configurazione più semplice e indica che tutte le cassette postali e il filtro vengono gestiti da Office 365. Tuttavia, alcune organizzazioni necessitano di configurazioni del flusso di posta più complesse per garantire la conformità con esigenze aziendali o normative specifiche. Opzioni con tali caratteristiche sono presenti in questa sezione.  
  
## <a name="custom-routing-of-outbound-email"></a>Routing personalizzato della posta in uscita

Microsoft Exchange Online può effettuare il routing del flusso di posta dall'organizzazione tramite un server locale o un servizio ospitato (talvolta denominato "smart hosting"). Ciò consente all'organizzazione di utilizzare le funzionalità di prevenzione della perdita dei dati, di eseguire una post elaborazione personalizzata della posta in uscita e di recapitare la posta ai propri partner tramite reti private. Exchange Online supporta anche la funzionalità di riscrittura degli indirizzi, nella quale la posta in uscita viene inviata attraverso un gateway locale che ne modifica gli indirizzi. Questa funzionalità permette di nascondere i sottodomini, di far apparire la posta proveniente da più domini come proveniente da un unico dominio o di far apparire la posta inviata da un partner dell'organizzazione come inviata dall'organizzazione stessa. Gli amministratori possono personalizzare il routing della posta dall'interfaccia di amministrazione di Exchange.
  
Per ulteriori informazioni, vedere [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
> [!IMPORTANT]
> Exchange Online può recapitare il flusso di posta all'interno e all'esterno dell'organizzazione. 
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Messaggistica sicura presso un partner di fiducia

Come cliente Exchange Online, è possibile configurare il flusso di posta sicura con un partner di fiducia utilizzando i connettori di Office 365. Office 365 supporta la comunicazione sicura attraverso il protocollo Transport Layer Security (TLS) ed è possibile creare un connettore per forzare la crittografia tramite TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) è un protocollo crittografico che protegge le comunicazioni via Internet. Utilizzando i connettori, è possibile forzare il protocollo TSL sia per la posta in entrata che per quella in uscita utilizzando certificati autofirmati o convalidati da un'autorità di certificazione. È inoltre possibile applicare altre restrizioni, ad esempio specificando nomi di dominio o intervalli di indirizzi IP dai quali l'organizzazione partner invia messaggi di posta. 
  
Per ulteriori informazioni, vedere [Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx).
  
> [!IMPORTANT]
> Potrebbe essere obbligatorio utilizzare un certificato convalidato da un'autorità di certificazione. 
  
## <a name="conditional-mail-routing"></a>Routing condizionale della posta

È possibile indirizzare la posta diretta a siti specifici utilizzando i connettori e le regole di trasporto. Con il routing basato su criteri, è possibile scegliere un connettore in base a specifiche condizioni.
  
Per ulteriori informazioni, vedere [Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="incoming-mail-safe-list"></a>Elenco indirizzi attendibili della posta in arrivo:

È possibile aggiungere l'indirizzo IP di un partner attendibile a un elenco di indirizzi attendibili al fine di assicurarsi che i messaggi inviati dal partner non siano soggetti al filtro posta indesiderata. A tale scopo, è possibile utilizzare l'elenco di indirizzi IP consentiti del filtro connessioni.
  
Per ulteriori informazioni, vedere [Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx).
  
## <a name="hybrid-email-routing"></a>Routing posta ibrida

La distribuzione ibrida offre alle organizzazioni la possibilità di estendere al cloud le numerose funzionalità e il controllo amministrativo che hanno nell'organizzazione Microsoft Exchange locale. Con il trasporto ibrido i messaggi scambiati dagli utenti di qualsiasi organizzazione vengono autenticati, crittografati e trasferiti usando Transport Layer Security (TLS) e appaiono come interni a componenti di Exchange quali i ruoli di trasporto, journal e criteri antispam. Il trasporto ibrido viene configurato dalla procedura guidata di configurazione ibrida in Exchange Server.
  
Per ulteriori informazioni sul routing della posta in una distribuzione ibrida, vedere [Routing del trasporto nelle distribuzioni ibride di Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Informazioni dettagliate sul provisioning della distribuzione ibrida e sul trasporto dei messaggi ibridi sono disponibili anche in [Assistente per la distribuzione di Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036). 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Spazio indirizzo condiviso con controllo routing locale (il record MX punta a Exchange locale)

Lo spazio indirizzo condiviso con controllo routing locale (il record MX punta a Exchange locale) è uno scenario di distribuzione ibrida per il routing della posta, in cui le cassette postali sono ospitate in parte in Exchange Online e in parte localmente e il flusso di posta Internet in entrata e in uscita passa attraverso l'organizzazione Exchange locale. Questo scenario viene anche detto trasporto posta centralizzato. In questo scenario, Exchange Online viene dotato di EOP e la posta Internet in entrata viene indirizzata al server di posta locale prima di essere reindirizzata all'EOP e infine alle cassette postali ospitate in Exchange Online. Inoltre, la posta in uscita dalle cassette postali di Exchange Online passa attraverso l'organizzazione Exchange locale relativamente ai messaggi inviati a destinatari esterni. Con questa configurazione, è possibile utilizzare un singolo spazio dei nomi di dominio SMTP per tutte le cassette postali sia dell'organizzazione Exchange locale sia dell'organizzazione Exchange Online. 
  
Per ulteriori informazioni sulle opzioni di trasporto in una distribuzione ibrida, vedere [Opzioni di trasporto nelle distribuzioni ibride di Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Spazio indirizzo condiviso con controllo routing locale (il record MX punta a EOP)

Lo spazio di indirizzi condiviso senza controllo routing locale (il record MX punta a EOP) è uno scenario di routing della posta ibrida, in cui le cassette postali sono ospitate in parte sul cloud tramite Exchange Online e in parte localmente mentre il record MX punta a Exchange Online Protection (EOP). Questo scenario è appropriato quando viene utilizzato il servizio Office 365 per ospitare alcune cassette postali dell'organizzazione e si desidera avere EOP per proteggere sia le cassette postali locali sia quelle sul cloud. In questo scenario la posta inviata a destinatari interni all'organizzazione viene inizialmente instradata attraverso l'EOP, dove avviene il filtraggio anti-spam e in base ai criteri, prima di essere recapitata alle cassette postali locali e sul cloud. 
  
Per ulteriori informazioni sulle opzioni di trasporto in una distribuzione ibrida, vedere [Opzioni di trasporto nelle distribuzioni ibride di Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Risoluzione dei problemi di una distribuzione con la procedura guidata di configurazione ibrida

L'utilizzo della procedura guidata di configurazione ibrida per configurare una distribuzione ibrida in Microsoft Exchange Server riduce al minimo il rischio di avere problemi durante la distribuzione ibrida. Tuttavia, ci sono alcune aree tipiche fuori dall'ambito della configurazione guidata ibrida che, se configurate male, possono dare origine a parecchi problemi durante la distribuzione ibrida. Queste aree sono la configurazione del server Accesso client e l'installazione e configurazione dei certificati.
  
Per ulteriori informazioni sulla risoluzione dei problemi di una distribuzione con la configurazione guidata per distribuzioni ibride, vedere [Risolvere i problemi di una distribuzione ibrida](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Gestione di una configurazione ibrida

È possibile modificare una configurazione ibrida esistente modificando le impostazione della configurazione guidata ibrida. Gli scenari possibili includono la disattivazione del trasporto centralizzato o del trasporto della posta sicura.
  
Per ulteriori informazioni sulla gestione della configurazione di una distribuzione ibrida, vedere [Gestire una distribuzione ibrida](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Requisiti di una distribuzione ibrida

Per ulteriori informazioni sui requisiti di una distribuzione ibrida, vedere [Prerequisiti per la distribuzione ibrida](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> In alcune configurazioni ibride, potrebbe essere necessario acquistare le licenze di Exchange Online Protection per le cassette postali locali. 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  
