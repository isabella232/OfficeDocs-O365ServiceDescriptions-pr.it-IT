---
title: Client e dispositivi mobili
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online funziona con le versioni desktop e mobili di Outlook, nonché con Outlook sul web.
ms.openlocfilehash: 3e612d9f157cb4109dfc2bef9bfa462445674dd9d19954ca9fe6ac32004ad515
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664049"
---
# <a name="clients-and-mobile-devices"></a>Client e dispositivi mobili

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook è un programma di posta elettronica che include il supporto per calendario, contatti, attività e le seguenti funzionalità chiave:
  
- **MAPI su HTTP** - L'interfaccia MAPI (Messaging Application Program Interface) su HTTP consente agli utenti di Outlook di connettersi alle cassette postali di Exchange Online tramite Internet dall'esterno del firewall dell'organizzazione. MAPI su HTTP, la sostituzione a lungo termine per Outlook via Internet. Questo metodo di connettività offre resilienza della connessione migliorata, accesso più sicuro, estendibilità, nonché miglioramenti per l'IT e il supporto. Per ulteriori informazioni, vedere [RPC su HTTP raggiunge](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) la fine del supporto in Office 365 [MAPI su HTTP](/exchange/mapi-over-http-exchange-2013-help).

- **Individuazione** automatica: la funzionalità del servizio di individuazione automatica configura automaticamente Outlook per l'utilizzo con Exchange Online. Gli utenti di Outlook possono ricevere le impostazioni necessarie del proprio profilo direttamente da Exchange Online la prima volta che effettuano l'accesso con il proprio indirizzo di posta elettronica e la propria password. Queste impostazioni aggiornano automaticamente il client Outlook con le informazioni necessarie per creare e gestire il profilo dell'utente. Per utilizzare il servizio di individuazione automatica è necessario un certificato SSL. Tale certificato SSL è limitato a un singolo dominio primario di SSL. 

- **Cached Exchange Mode** - La funzionalità Cached Exchange Mode consente agli utenti di Outlook di accedere alle copie locali delle proprie cassette postali di Exchange Online quando non sono connessi a Internet. La Modalità cache gestisce una copia lato client delle cassette postali di Exchange degli utenti in Outlook e sincronizza automaticamente tale copia con il server di posta elettronica. È consigliabile utilizzare Outlook in Modalità cache perché consente l'accesso offline e offre un'esperienza utente reattiva anche quando le condizioni della rete fra client e server non sono ottimali. 

L'accesso tramite Outlook è abilitato per tutti gli utenti per impostazione predefinita. Gli amministratori possono disabilitare l'accesso per utenti o gruppi specifici tramite Windows PowerShell. Per accedere d Exchange Online è consigliabile utilizzare la versione più recente di Outlook con l'ultimo Service Pack installato. 
  
Per informazioni sui Outlook client supportati da Exchange 2016 e Exchange Online, vedere [System Requirements for Office](https://products.office.com/office-system-requirements). 

Microsoft 365 è progettato per funzionare con i browser e le versioni più recenti di Office. Se usi browser e versioni precedenti di Office che non sono nel supporto mainstream:

- Microsoft non impedisce deliberatamente di connettersi al servizio, ma la qualità dell'esperienza potrebbe diminuire nel tempo.
- Microsoft non fornirà aggiornamenti software per risolvere problemi non correlati alla sicurezza.

> [!IMPORTANT]
> Outlook non rientra nel prezzo della sottoscrizione a Exchange Online. Microsoft 365 Apps for enterprise (che include Microsoft Outlook) è incluso in alcuni piani e può essere acquistato come abbonamento separato. Se si utilizza POP per connettersi a un account di posta elettronica Exchange Online, vengono visualizzate le seguenti limitazioni:
> - Assenza di informazioni del calendario
>- Assenza di informazioni sulla disponibilità
>- Assenza dell'Elenco indirizzi globale
>- Nessuna funzionalità push per la posta elettronica
>- Quando ci si connette tramite POP, tutti i messaggi vengono scaricati nel client e non è possibile eseguire la sincronizzazione tra più computer o dispositivi (ad esempio tra un portatile e un telefono). 
  
## <a name="outlook-on-the-web"></a>Outlook sul Web

Outlook sul Web è una versione basata sul Web del programma di posta elettronica Outlook, che viene utilizzata con Exchange Online. Consente agli utenti di accedere alla posta elettronica, al calendario e ai contatti tramite un Web browser ovunque si connettano a Internet. Per informazioni sui browser supportati, vedere [Browser supportati da Outlook sul Web per le aziende](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook sul Web è disponibile in due versioni client, entrambe utilizzabili con Exchange Online:
  
- **Outlook sul web-** La versione standard di Outlook sul web fornisce agli Exchange Online un'esperienza di messaggistica più simile a quella degli Outlook utenti. Supporta la maggior parte dei Web browser più recenti ed è ottimizzata per l'uso con tablet e smartphone, oltre che in computer desktop e portatili. Gli utenti possono leggere e inviare messaggi, organizzare i contatti e pianificare appuntamenti e riunioni. Il timeout predefinito basato sull'attività è impostato su sei ore ma può essere [configurato da un amministratore in Windows PowerShell](/powershell/module/exchange/set-organizationconfig) da 5 minuti a 8 ore. Questo timeout dipende dalle interazioni dell'utente all'interno dell'app Web, ad esempio la selezione di un pulsante o la selezione di un messaggio. È presente anche un timeout separato in base alla sicurezza, non configurabile e che si verifica indipendentemente dall'attività dell'utente. Se un utente ha effettuato l'accesso da 8 ore, OWA chiude automaticamente la sessione e chiede di effettuare nuovamente l'autenticazione. 

- **La versione light di Outlook sul web** - La versione light di Outlook sul web consente agli Exchange Online utenti di accedere alla cassetta postale utilizzando quasi tutti i browser Web. Gli utenti possono leggere e inviare messaggi, organizzare i contatti e pianificare appuntamenti e riunioni. Il timeout predefinito basato sull'attività è impostato su sei ore ma può essere [configurato da un amministratore in Windows PowerShell](/powershell/module/exchange/set-organizationconfig) da 5 minuti a 8 ore. Questo timeout dipende dalle interazioni dell'utente all'interno dell'app Web, ad esempio la selezione di un pulsante o la selezione di un messaggio. È presente anche un timeout separato in base alla sicurezza, non configurabile e che si verifica indipendentemente dall'attività dell'utente. Se un utente ha effettuato l'accesso da 8 ore, la versione light di OWA chiude automaticamente la sessione e chiede di effettuare nuovamente l'autenticazione. 

Outlook sul Web è disponibile anche in versioni per dispositivi mobili. Per ulteriori informazioni, vedere [questa pagina](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook per Mac

Exchange Online supporta Microsoft Outlook per Mac, che fornisce posta elettronica, calendario, una rubrica, un elenco attività e un elenco note.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook per iOS, Android e Windows Phone

Exchange Online funziona con Outlook disponibili per iOS, Android e Windows Phone. In uno di questi dispositivi usa l'App Store per trovare l'app Outlook app. Ecco una suddivisione del sistema operativo per dispositivi mobili.<br><br>
  
| Dispositivo | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook disponibilità dell'app per dispositivi mobili  <br/> |Sì  <br/> [Ottenere Outlook per Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sì  <br/> [Ottenere Outlook per iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Built-in  <br/> |
|App di posta elettronica integrate compatibili con Exchange Online  <br/> |App Gmail/App Di posta elettronica Samsung  <br/> |App Posta iOS  <br/> |Outlook Posta, calendario, contatti  <br/> |
|Altre informazioni  <br/> |[Configurazione per dispositivi mobili Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone o iPad installazione](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone configurazione](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Sono inoltre disponibili opzioni per l'Exchange Online con i dispositivi, tra cui Blackberry.
  
### <a name="feature-availability"></a>Disponibilità delle funzionalità

Outlook agli utenti l'esperienza di posta elettronica e calendario veloce e intuitiva che si aspettano da un'app mobile moderna, pur essendo l'unica app a fornire supporto per le funzionalità migliori. È l'unica app di posta elettronica progettata appositamente per supportare l'esperienza Microsoft completa, offrendo agli utenti un'esperienza coerente dal desktop al dispositivo mobile. Outlook è integrato con Intune, dispositivi mobili e sicurezza aziendali e Exchange per mantenere al sicuro dati e utenti.
  
Con Outlook, gli utenti possono:
  
- Gestire l'intera giornata da un dispositivo mobile.

- Connessione le app e i servizi di cui hanno bisogno per essere produttivi, mantenendo le informazioni personali e di lavoro separate e sicure.

Con Outlook per iOS, Outlook per Android o Outlook per Windows Phone, gli utenti possono: 
  
- Trarre vantaggio da una posta in arrivo mirata che assegna priorità alla posta elettronica importante

- Personalizzare i movimenti di scorrimento rapido in base alle proprie abitudini di posta elettronica univoche

- Creare itinerari di viaggio che possono essere aggiunti direttamente al calendario, con informazioni chiave disponibili a colpo d'occhio

- RSVP alle riunioni dalla posta in arrivo.

- Usare icone intuitive negli appuntamenti di posta elettronica e calendario che consentono loro di elaborare rapidamente le informazioni

- Usare un'esperienza di Outlook coerente e familiare in tutti i dispositivi

- Avviare e partecipare facilmente Skype riunioni dal calendario

- Leggere e rispondere ai messaggi di posta elettronica protetti e crittografati tramite IRM

- Condividere file archiviati in OneDrive for Business

- Impostare le risposte automatiche con un tocco

- Visualizzare e gestire calendari condivisi e delegati

- Eseguire una ricerca nell'elenco indirizzi globale dell'azienda con pochi tocchi

- Visualizzare la disponibilità del collega e pianificare un orario di riunione che funzioni per tutti gli utenti

- Visualizzare lo stato di accettazione, provvisoria e rifiuto degli invitati

- Condividere calendari direttamente dai telefoni

- Avviare e partecipare Skype riunioni direttamente da un calendario

- Accedere ai calendari personali e lavorativi in un'unica posizione, senza cambiare app
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online supporta il protocollo Microsoft Exchange ActiveSync, che sincronizza i dati delle cassette postali fra dispositivi mobili ed Exchange Online, per consentire agli utenti di accedere a posta elettronica, calendario, contatti e attività anche mentre viaggiano.
  
Sul mercato è disponibile un'ampia gamma di dispositivi mobili che supportano Exchange ActiveSync, inclusi i dispositivi Microsoft Windows Phone, i dispositivi Apple iPhone e iPad, nonché i telefoni e i tablet Android. Oltre ai telefoni cellulari e ai dispositivi mobili, l'applicazione Mail in Windows Phone utilizza Exchange ActiveSync per connettersi a Exchange Online. Nel sito dedicato alle licenze di Exchange ActiveSync è disponibile un elenco completo dei licenziatari correnti di Exchange ActiveSync.
  
Per ulteriori informazioni sulle Exchange ActiveSync, [vedere Exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online).
  
> [!IMPORTANT]
> Il numero massimo di dispositivi Exchange ActiveSync per cassetta postale è 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Applicazioni sviluppate con Servizi Web Exchange (EWS)

 Le applicazioni sviluppate con Servizi Web Exchange (EWS) o l'API gestita da EWS consentono agli amministratori di accedere ai dati archiviati in Exchange Online dalle applicazioni eseguite in locale, in Azure o in altri servizi ospitati. 
  
Per ulteriori informazioni sulle applicazioni sviluppate con Servizi Web Exchange, vedere l'articolo relativo ai [servizi Web disponibili in Exchange](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange).
  
## <a name="pop-and-imap"></a>POP e IMAP

Exchange Online supporta l'accesso alle cassette postali tramite i protocolli POP3 e IMAP4. L'accesso basato su POP e IMAP richiede la crittografia tramite SSL. Il protocollo POP è abilitato per impostazione predefinita per tutti gli utenti. Gli utenti possono visualizzare le proprie impostazioni di connessione POP e IMAP in Outlook sul Web. Gli amministratori possono disabilitare l'accesso tramite POP e IMAP a livello di utente.
  
Per ulteriori informazioni sulla connettività POP3 e IMAP4, vedere l'articolo relativo a [POP3 e IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help).
  
## <a name="smtp"></a>SMTP

Il protocollo SMTP (Simple Mail Transfer Protocol) viene utilizzato per inviare la posta in uscita dai client che si connettono a Exchange Online tramite IMAP o POP. È il protocollo principale per il routing e il recapito tramite Exchange Server. Exchange Online supporta due tipi di servizi di inoltro SMTP per le applicazioni autorizzate interne dei clienti che richiedono l'invio della posta tramite SMTP:
  
- Invio dei messaggi tramite SMTP agli utenti situati all'interno dell'ambiente gestito.

- Inoltro di messaggi SMTP autenticati a indirizzi situati all'esterno dell'ambiente gestito.

> [!IMPORTANT]
> Per consentire l'inoltro SMTP sono necessari gli indirizzi IP dei server di origine autorizzati. Quando si utilizza SMTP per l'invio della posta elettronica, sono necessarie l'autenticazione e la crittografia TLS (Transport Layer Security). 
  
## <a name="blackberry-devices"></a>Dispositivi BlackBerry

La posta elettronica è disponibile nei dispositivi BlackBerry &reg; tramite Exchange ActiveSync. Per scoprire quali sono le opzioni disponibili, vedi questi argomenti:
  
- [Configurare la posta elettronica in un dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurare la posta elettronica in un sistema operativo BlackBerry 7.1 e versioni precedenti](https://go.microsoft.com/fwlink/?linkid=863403)

Per ulteriori informazioni, vedi [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Se si utilizza Office 365 gestito da 21Vianet in Cina, BlackBerry Business Cloud Services non è disponibile. Tuttavia, è possibile utilizzare i dispositivi Exchange ActiveSync o un'offerta di Research in Motion (RIM, la soluzione wireless di posta elettronica per BlackBerry) per eseguire Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Exchange Online [descrizione del servizio.](exchange-online-service-description.md)
