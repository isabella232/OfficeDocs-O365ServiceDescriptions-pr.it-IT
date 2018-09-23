---
title: Client e dispositivi mobili
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036108"
---
# <a name="clients-and-mobile-devices"></a>Client e dispositivi mobili

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook è un programma di posta elettronica che includa il supporto per calendario, contatti, attività e le funzionalità chiave seguenti:
  
- **MAPI su HTTP** Messaging Application programma Interface (MAPI) su HTTP consente agli utenti di Outlook per connettersi alle cassette postali di Exchange Online tramite Internet dall'esterno del firewall dell'organizzazione. MAPI su HTTP, la sostituzione a lungo termine per Outlook via Internet. Questo metodo connettività offre resilienza connessione migliorata, in accesso più sicuro, estendibilità, nonché miglioramenti per IT e supporto tecnico. Per ulteriori informazioni, vedere [RPC su HTTP raggiunge fine del supporto per Office 365](https://go.microsoft.com/fwlink/?linkid=863890) e [MAPI su HTTP](https://go.microsoft.com/fwlink/?linkid=393041).
    
- **Individuazione automatica** La funzionalità di servizio Individuazione automatica configura automaticamente Outlook per l'interazione con Exchange Online. Gli utenti di Outlook possono ricevere le impostazioni necessarie del proprio profilo direttamente da Exchange Online la prima volta che effettuano l'accesso con il proprio indirizzo di posta elettronica e la propria password. Queste impostazioni aggiornano automaticamente il client Outlook con le informazioni necessarie per creare e gestire il profilo dell'utente. Per utilizzare il servizio di individuazione automatica è necessario un certificato SSL. Tale certificato SSL è limitato a un singolo dominio primario di SSL. 
    
- **Modalità cache** La Modalità cache permette agli utenti di Outlook di accedere alle copie locali delle proprie cassette postali di Exchange Online quando non sono connessi a Internet. La Modalità cache gestisce una copia lato client delle cassette postali di Exchange degli utenti in Outlook e sincronizza automaticamente tale copia con il server di posta elettronica. È consigliabile utilizzare Outlook in Modalità cache perché consente l'accesso offline e offre un'esperienza utente reattiva anche quando le condizioni della rete fra client e server non sono ottimali. 
    
L'accesso tramite Outlook è abilitato per tutti gli utenti per impostazione predefinita. Gli amministratori possono disabilitare l'accesso per utenti o gruppi specifici tramite Windows PowerShell. Per accedere d Exchange Online è consigliabile utilizzare la versione più recente di Outlook con l'ultimo Service Pack installato. 
  
Per informazioni su quali client Outlook sono supportati da Exchange 2016 ed Exchange Online, vedere "Client supportati" in [Requisiti di sistema di Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook non rientra nel prezzo della sottoscrizione a Exchange Online. Alcuni piani di Office 365 includono Microsoft Office Pro Plus, che contiene Microsoft Outlook e può essere acquistato tramite una sottoscrizione separata. >  Se si utilizza POP per connettersi a un account di posta elettronica Exchange Online, vengono visualizzate le seguenti limitazioni: >  Assenza di informazioni del calendario >  Assenza di informazioni sulla disponibilità >  Assenza dell'Elenco indirizzi globale >  Nessuna funzionalità push per la posta elettronica >  Quando ci si connette tramite POP, tutti i messaggi vengono scaricati nel client e non è possibile eseguire la sincronizzazione tra più computer o dispositivi (ad esempio tra un portatile e un telefono). 
  
## <a name="outlook-on-the-web"></a>Outlook sul Web

Outlook sul Web è una versione basata sul Web del programma di posta elettronica Outlook, che viene utilizzata con Exchange Online. Permette agli utenti di accedere alla posta elettronica, al calendario e ai contatti personali tramite un Web browser, ovunque sia possibile connettersi a Internet. Per informazioni sui browser supportati, vedere [Browser supportati da Outlook sul Web per le aziende](https://go.microsoft.com/fwlink/p/?LinkId=287032).
  
Outlook sul Web è disponibile in due versioni client, entrambe utilizzabili con Exchange Online:
  
- **Outlook sul Web** La versione standard di Outlook sul Web offre agli utenti di Exchange Online un'esperienza di messaggistica più simile a quella di Outlook. Supporta la maggior parte dei Web browser più recenti ed è ottimizzata per l'uso con tablet e smartphone, oltre che in computer desktop e portatili. Gli utenti possono leggere e inviare messaggi, organizzare i contatti e pianificare appuntamenti e riunioni. Il timeout predefinito basato sull'attività è impostato su sei ore ma può essere [configurato da un amministratore in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) da 5 minuti a 8 ore. Il timeout dipende dalle interazioni dell'utente nell'app Web, come facendo clic su un pulsante o selezionando un messaggio. È presente anche un timeout separato in base alla sicurezza, non configurabile e che si verifica indipendentemente dall'attività dell'utente. Se un utente ha effettuato l'accesso da 8 ore, OWA chiude automaticamente la sessione e chiede di effettuare nuovamente l'autenticazione. 
    
- **Versione Light di Outlook sul Web** La versione Light di Outlook sul Web permette agli utenti di Exchange Online di accedere alla cassetta postale praticamente con qualsiasi Web browser. Gli utenti possono leggere e inviare messaggi, organizzare i contatti e pianificare appuntamenti e riunioni. Il timeout predefinito basato sull'attività è impostato su sei ore ma può essere [configurato da un amministratore in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) da 5 minuti a 8 ore. Il timeout dipende dalle interazioni dell'utente nell'app Web, come facendo clic su un pulsante o selezionando un messaggio. È presente anche un timeout separato in base alla sicurezza, non configurabile e che si verifica indipendentemente dall'attività dell'utente. Se un utente ha effettuato l'accesso da 8 ore, la versione light di OWA chiude automaticamente la sessione e chiede di effettuare nuovamente l'autenticazione. 
    
Outlook sul Web è disponibile anche in versioni per dispositivi mobili. Per ulteriori informazioni, vedere [questa pagina](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook per Mac

Exchange Online supporta Microsoft Outlook per Mac, che consente di posta elettronica, calendario, una rubrica, un elenco di attività e un elenco di note.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook per Windows Phone, iOS e Android

Exchange Online può essere utilizzato con le app di Outlook disponibili per Windows Phone, iOS e Android. In uno di questi dispositivi, utilizzare l'archivio di app per individuare l'app di Outlook. Di seguito vengono illustrati dal sistema operativo per dispositivi mobili.
  
|||||
|:-----|:-----|:-----|:-----|
|Dispositivo  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilità di app per dispositivi mobili di Outlook  <br/> |Sì  <br/> [Ottenere Outlook per Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sì  <br/> [Ottenere Outlook per iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Incorporato  <br/> |
|App di posta elettronica incorporati compatibile con Exchange Online  <br/> |App di posta elettronica Gmail app/Samsung  <br/> |app di posta elettronica iOS  <br/> |Posta elettronica di Outlook, calendario, contatti  <br/> |
|Ulteriori informazioni  <br/> |[Programma di installazione per dispositivi mobili Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[programma di installazione iPhone o iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Programma di installazione di Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
Sono inoltre disponibili opzioni per l'utilizzo di Exchange Online con dispositivi, compresi Blackberry.
  
### <a name="feature-availability"></a>Disponibilità delle funzionalità

Outlook offre agli utenti l'esperienza posta elettronica e calendario veloce e intuitiva che si aspettano da un'app per dispositivi mobili moderna, pur essendo app solo per fornire il supporto per le migliori funzionalità di Office 365. È l'app di posta elettronica solo in modo specifico progettato per supportare l'esperienza completa di Office 365, offrendo agli utenti un'esperienza coerente dal desktop per dispositivi mobili. Outlook è integrato con Intune mobilità aziendale e sicurezza e controlli di Exchange per proteggere dati e gli utenti.
  
Outlook consente agli utenti di:
  
- Gestire la giornata intera da un dispositivo mobile.
    
- Connettersi alle applicazioni e ai servizi che necessarie per la produttività, mantenendo le informazioni personali e lavoro separato e sicura.
    
Con Outlook per iOS Outlook per Android o Outlook per Windows Phone, gli utenti possono: 
  
- Può risultare vantaggiosa una cartella Posta in arrivo mirati di posta elettronica importanti priorità
    
- Personalizzare movimenti scorrere rapidamente per soddisfare le specifiche esigenze di posta elettronica univoco
    
- Creare itinerari di viaggio che è possibile aggiungere direttamente al calendario, con le informazioni sulla chiave disponibile all'indirizzo immediatamente
    
- Conferma la partecipazione a riunioni dalla posta in arrivo.
    
- Utilizzare le icone intuitive nella posta elettronica e calendario gli appuntamenti che consentano di elaborare rapidamente informazioni
    
- Utilizzare un'esperienza di Outlook coerente e facili da tutti i dispositivi
    
- Avviare e partecipare alle riunioni Skype dal calendario facilmente
    
- Lettura e rispondere a IRM crittografati e protetti tramite posta elettronica
    
- Condividere i file archiviati in OneDrive for Business
    
- Impostare le risposte automatiche con un tocco
    
- Consente di visualizzare e gestire i calendari condivisi e disporre della delega
    
- Ricerca elenco indirizzi globale della propria azienda, con alcuni collegamenti
    
- Visualizzare disponibilità di collaboratore e pianificare una riunione che può essere utilizzato per tutti gli utenti
    
- Vedere invitati accettare, provvisorio e rifiutare sullo stato
    
- Condividere i calendari direttamente dal telefono
    
- Avviare e partecipare a destra di riunioni Skype da un calendario
    
- Lavoro l'accesso e dei calendari personali in un'unica posizione, senza passare App
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online supporta il protocollo Microsoft Exchange ActiveSync, che sincronizza i dati delle cassette postali fra dispositivi mobili ed Exchange Online, per consentire agli utenti di accedere a posta elettronica, calendario, contatti e attività anche mentre viaggiano.
  
Una vasta gamma di dispositivi mobili funziona con Exchange ActiveSync, inclusi Microsoft Windows Phone, Apple iPhone e iPad, Android telefoni e Tablet. Oltre ai telefoni e dispositivi mobili, l'applicazione di posta elettronica in Windows Phone utilizza Exchange ActiveSync per la connessione a Exchange Online. Un elenco completo dei licenziatari Exchange ActiveSync correnti è disponibile nel sito di gestione delle licenze di Exchange ActiveSync.
  
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

Posta elettronica di Office 365 è disponibile nei dispositivi BlackBerry® tramite Exchange ActiveSync. Per sapere quali sono le opzioni, vedere i seguenti argomenti:
  
- [Configurare la posta elettronica in un dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [Configurare la posta elettronica in un dispositivo BlackBerry 7.1 OS e versioni precedenti](https://go.microsoft.com/fwlink/?linkid=863403)
    
Per ulteriori informazioni, vedi [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Se si utilizza Office 365 gestito da 21Vianet in Cina, BlackBerry Business Cloud Services non è disponibile. Tuttavia, è possibile utilizzare i dispositivi Exchange ActiveSync o un'offerta di Research in Motion (RIM, la soluzione wireless di posta elettronica per BlackBerry) per eseguire Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

