---
title: Client e dispositivi mobili
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 1701c399fe351356ff8813af8003632402dc2adc
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442701"
---
# <a name="clients-and-mobile-devices"></a>Client e dispositivi mobili

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook è un programma di posta elettronica che include il supporto per il calendario, i contatti, le attività e le caratteristiche chiave seguenti:
  
- **MAPI su http** L'interfaccia MAPI (Messaging Application Program Interface) su HTTP consente agli utenti di Outlook di connettersi alle cassette postali di Exchange Online su Internet dall'esterno del firewall dell'organizzazione. MAPI su HTTP, la sostituzione a lungo termine per Outlook via Internet. Questo metodo di connettività offre una resilienza della connessione migliorata, un accesso più sicuro, l'estensibilità, nonché miglioramenti per il supporto tecnico e IT. Per ulteriori informazioni, vedere [RPC su http raggiunge la fine del supporto in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) e [MAPI su http](https://go.microsoft.com/fwlink/?linkid=393041).

- **Individuazione automatica** La funzionalità di servizio Individuazione automatica configura automaticamente Outlook per l'interazione con Exchange Online. Gli utenti di Outlook possono ricevere le impostazioni necessarie del proprio profilo direttamente da Exchange Online la prima volta che effettuano l'accesso con il proprio indirizzo di posta elettronica e la propria password. Queste impostazioni aggiornano automaticamente il client Outlook con le informazioni necessarie per creare e gestire il profilo dell'utente. Per utilizzare il servizio di individuazione automatica è necessario un certificato SSL. Tale certificato SSL è limitato a un singolo dominio primario di SSL. 

- **Modalità cache** La funzionalità modalità cache consente agli utenti di Outlook di accedere alle copie locali delle cassette postali di Exchange Online quando non sono connesse a Internet. La Modalità cache gestisce una copia lato client delle cassette postali di Exchange degli utenti in Outlook e sincronizza automaticamente tale copia con il server di posta elettronica. È consigliabile utilizzare Outlook in Modalità cache perché consente l'accesso offline e offre un'esperienza utente reattiva anche quando le condizioni della rete fra client e server non sono ottimali. 

L'accesso tramite Outlook è abilitato per tutti gli utenti per impostazione predefinita. Gli amministratori possono disabilitare l'accesso per utenti o gruppi specifici tramite Windows PowerShell. Per accedere d Exchange Online è consigliabile utilizzare la versione più recente di Outlook con l'ultimo Service Pack installato. 
  
Per informazioni su quali client Outlook sono supportati da Exchange 2016 ed Exchange Online, vedere "Client supportati" in [Requisiti di sistema di Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook non rientra nel prezzo della sottoscrizione a Exchange Online. Alcuni piani di Office 365 includono Microsoft Office Pro Plus, che contiene Microsoft Outlook e può essere acquistato tramite una sottoscrizione separata. Se si utilizza la funzionalità POP per connettersi a un account di posta elettronica di Exchange Online, verranno visualizzate le limitazioni seguenti: > nessuna informazione del calendario > nessuna informazione sulla disponibilità > nessun elenco indirizzi globale > nessun messaggio di posta elettronica push > quando si effettua la connessione tramite POP, tutti i messaggi verranno scaricati da t o il client e non verrà eseguita alcuna sincronizzazione tra più computer o dispositivi (ad esempio tra un computer portatile e un telefono). 
  
## <a name="outlook-on-the-web"></a>Outlook sul Web

Outlook sul Web è una versione basata sul Web del programma di posta elettronica Outlook, che viene utilizzata con Exchange Online. Consente agli utenti di accedere alla posta elettronica, al calendario e ai contatti tramite un Web browser da qualsiasi luogo in cui si connettono a Internet. Per informazioni sui browser supportati, vedere [Browser supportati da Outlook sul Web per le aziende](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook sul Web è disponibile in due versioni client, entrambe utilizzabili con Exchange Online:
  
- **Outlook sul Web** La versione standard di Outlook sul Web offre agli utenti di Exchange Online un'esperienza di messaggistica più simile a quella di Outlook. Supporta la maggior parte dei Web browser più recenti ed è ottimizzata per l'uso con tablet e smartphone, oltre che in computer desktop e portatili. Gli utenti possono leggere e inviare messaggi, organizzare i contatti e pianificare appuntamenti e riunioni. Il timeout predefinito basato sull'attività è impostato su sei ore ma può essere [configurato da un amministratore in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) da 5 minuti a 8 ore. Questo timeout dipende dalle interazioni degli utenti all'interno dell'applicazione Web, ad esempio la selezione di un pulsante o la selezione di un messaggio. È presente anche un timeout separato in base alla sicurezza, non configurabile e che si verifica indipendentemente dall'attività dell'utente. Se un utente ha effettuato l'accesso da 8 ore, OWA chiude automaticamente la sessione e chiede di effettuare nuovamente l'autenticazione. 

- **Versione Light di Outlook sul Web** La versione Light di Outlook sul Web permette agli utenti di Exchange Online di accedere alla cassetta postale praticamente con qualsiasi Web browser. Gli utenti possono leggere e inviare messaggi, organizzare i contatti e pianificare appuntamenti e riunioni. Il timeout predefinito basato sull'attività è impostato su sei ore ma può essere [configurato da un amministratore in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) da 5 minuti a 8 ore. Questo timeout dipende dalle interazioni degli utenti all'interno dell'applicazione Web, ad esempio la selezione di un pulsante o la selezione di un messaggio. È presente anche un timeout separato in base alla sicurezza, non configurabile e che si verifica indipendentemente dall'attività dell'utente. Se un utente ha effettuato l'accesso da 8 ore, la versione light di OWA chiude automaticamente la sessione e chiede di effettuare nuovamente l'autenticazione. 

Outlook sul Web è disponibile anche in versioni per dispositivi mobili. Per ulteriori informazioni, vedere [questa pagina](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook per Mac

Exchange Online supporta Microsoft Outlook per Mac, che fornisce la posta elettronica, il calendario, una rubrica, un elenco attività e un elenco di note.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook per iOS, Android e Windows Phone

Exchange Online funziona con le app di Outlook disponibili per iOS, Android e Windows Phone. In uno di questi dispositivi, utilizzare l'App Store per trovare l'app di Outlook. Ecco una scomposizione in base al sistema operativo per dispositivi mobili.
  
|||||
|:-----|:-----|:-----|:-----|
|Dispositivo  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilità delle app per dispositivi mobili di Outlook  <br/> |Sì  <br/> [Ottenere Outlook per Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sì  <br/> [Ottenere Outlook per iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Built-in  <br/> |
|App di posta elettronica incorporate compatibili con Exchange Online  <br/> |App di posta elettronica di Gmail app/Samsung  <br/> |app di posta elettronica iOS  <br/> |Posta di Outlook, calendario, contatti  <br/> |
|Ulteriori informazioni  <br/> |[Configurazione per dispositivi mobili Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[configurazione di iPhone o iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Configurazione di Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Sono inoltre disponibili opzioni per l'utilizzo di Exchange Online con dispositivi, tra cui BlackBerry.
  
### <a name="feature-availability"></a>Disponibilità delle funzionalità

Outlook offre agli utenti l'esperienza di posta elettronica e calendario rapida e intuitiva che si aspettano da una moderna app per dispositivi mobili, essendo l'unica app che fornisce supporto per le migliori funzionalità di Office 365. È l'unica applicazione di posta elettronica appositamente progettata per supportare l'intera esperienza di Office 365, offrendo agli utenti un'esperienza coerente da desktop a mobile. Outlook è integrato con Intune, Enterprise Mobility and Security ed Exchange Controls per garantire la sicurezza dei dati e degli utenti.
  
Outlook consente agli utenti di:
  
- Gestire l'intera giornata da un dispositivo mobile.

- Connettersi alle applicazioni e ai servizi di cui hanno bisogno per essere produttivi, mantenendo il lavoro e le informazioni personali separate e sicure.

Con Outlook per iOS, Outlook per Android o Outlook per Windows Phone, gli utenti possono: 
  
- Trarre vantaggio da una posta in arrivo evidenziata che priorità importanti per la posta elettronica

- Personalizzare i gesti swipe per soddisfare le proprie abitudini di posta elettronica esclusive

- Creare itinerari di viaggio che possono essere aggiunti direttamente al calendario, con le informazioni chiave disponibili a colpo d'occhio

- RSVP a riunioni dalla posta in arrivo.

- Usare icone intuitive negli appuntamenti del calendario e della posta elettronica che consentono loro di elaborare rapidamente le informazioni

- Utilizzo di un'esperienza di Outlook coerente e familiare in tutti i dispositivi

- Avviare e unire facilmente le riunioni Skype dal calendario

- Leggere e rispondere a messaggi di posta elettronica crittografati e protetti da IRM

- Condividere file archiviati in OneDrive for business

- Impostare le risposte automatiche con un tap

- Visualizzare e gestire i calendari condivisi e delegati

- Cercare l'elenco indirizzi globale dell'azienda con alcuni tocchi

- Visualizzazione della disponibilità del collega e pianificazione di un'ora di riunione che funziona per tutti

- Vedere lo stato degli invitati accetta, provvisorio e declino

- Condividere i calendari direttamente dai propri telefoni

- Avviare e partecipare a riunioni Skype direttamente da un calendario

- Accedere al lavoro e ai calendari personali in un'unica posizione, senza passare dalle app
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online supporta il protocollo Microsoft Exchange ActiveSync, che sincronizza i dati delle cassette postali fra dispositivi mobili ed Exchange Online, per consentire agli utenti di accedere a posta elettronica, calendario, contatti e attività anche mentre viaggiano.
  
Sul mercato è disponibile un'ampia gamma di dispositivi mobili che supportano Exchange ActiveSync, inclusi i dispositivi Microsoft Windows Phone, i dispositivi Apple iPhone e iPad, nonché i telefoni e i tablet Android. Oltre ai telefoni e ai dispositivi mobili, l'applicazione di posta elettronica in Windows Phone utilizza Exchange ActiveSync per connettersi a Exchange Online. Nel sito dedicato alle licenze di Exchange ActiveSync è disponibile un elenco completo dei licenziatari correnti di Exchange ActiveSync.
  
Per ulteriori informazioni su Exchange ActiveSync, vedere [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
> [!IMPORTANT]
> Il numero massimo di dispositivi Exchange ActiveSync per cassetta postale è 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Applicazioni sviluppate con Servizi Web Exchange (EWS)

 Le applicazioni sviluppate con Servizi Web Exchange (EWS) o l'API gestita da EWS consentono agli amministratori di accedere ai dati archiviati in Exchange Online dalle applicazioni eseguite in locale, in Azure o in altri servizi ospitati. 
  
Per ulteriori informazioni sulle applicazioni sviluppate con Servizi Web Exchange, vedere l'articolo relativo ai [servizi Web disponibili in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).
  
## <a name="pop-and-imap"></a>POP e IMAP

Exchange Online supporta l'accesso alle cassette postali tramite i protocolli POP3 e IMAP4. L'accesso basato su POP e IMAP richiede la crittografia tramite SSL. Il protocollo POP è abilitato per impostazione predefinita per tutti gli utenti. Gli utenti possono visualizzare le proprie impostazioni di connessione POP e IMAP in Outlook sul Web. Gli amministratori possono disabilitare l'accesso tramite POP e IMAP a livello di utente.
  
Per ulteriori informazioni sulla connettività POP3 e IMAP4, vedere l'articolo relativo a [POP3 e IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).
  
## <a name="smtp"></a>SMTP

Il protocollo SMTP (Simple Mail Transfer Protocol) viene utilizzato per inviare la posta in uscita dai client che si connettono a Exchange Online tramite IMAP o POP. È il protocollo principale per il routing e il recapito tramite Exchange Server. Exchange Online supporta due tipi di servizi di inoltro SMTP per le applicazioni autorizzate interne dei clienti che richiedono l'invio della posta tramite SMTP:
  
- Invio dei messaggi tramite SMTP agli utenti situati all'interno dell'ambiente gestito.

- Inoltro di messaggi SMTP autenticati a indirizzi situati all'esterno dell'ambiente gestito.

> [!IMPORTANT]
> Per consentire l'inoltro SMTP sono necessari gli indirizzi IP dei server di origine autorizzati. Quando si utilizza SMTP per l'invio della posta elettronica, sono necessarie l'autenticazione e la crittografia TLS (Transport Layer Security). 
  
## <a name="blackberry-devices"></a>Dispositivi BlackBerry®

La posta elettronica di Office 365 è disponibile nei dispositivi BlackBerry® tramite Exchange ActiveSync. Per sapere quali sono le opzioni disponibili, vedere gli argomenti seguenti:
  
- [Configurare la posta elettronica in un dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurare la posta elettronica su un dispositivo BlackBerry 7,1 OS e versioni precedenti](https://go.microsoft.com/fwlink/?linkid=863403)

Per ulteriori informazioni, vedi [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Se si utilizza Office 365 gestito da 21Vianet in Cina, BlackBerry Business Cloud Services non è disponibile. Tuttavia, è possibile utilizzare i dispositivi Exchange ActiveSync o un'offerta di Research in Motion (RIM, la soluzione wireless di posta elettronica per BlackBerry) per eseguire Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  