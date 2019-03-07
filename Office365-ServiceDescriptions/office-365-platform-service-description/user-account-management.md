---
title: Gestione degli account utente
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365 supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti.
ms.openlocfilehash: edb1f321761409eda0ae6b0e7180bc317f4a7bd5
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467743"
---
# <a name="user-account-management"></a>Gestione degli account utente

Microsoft Office 365 supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti. 
  
> [!NOTE]
> Questo argomento non include informazioni sulle funzionalità di sicurezza che consentono o impediscono l'accesso a singole risorse di Office 365 (ad esempio, il controllo di accesso basato sui ruoli di Microsoft Exchange Online o le opzioni di configurazione della sicurezza in Microsoft SharePoint Online). Per informazioni dettagliate su tali funzionalità, vedere le descrizioni dei servizi [Descrizione del servizio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) e [Descrizione del servizio SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Per ulteriori informazioni sugli strumenti che consentono di eseguire attività amministrative, vedere [Strumenti per gestire gli account di Office 365](https://go.microsoft.com/fwlink/?linkid=847777). Per scoprire come eseguire operazioni di gestione giornaliera, vedere [Attività di gestione comuni per Office 365](https://go.microsoft.com/fwlink/?linkid=847778).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>È necessario ricevere assistenza per l'accesso, per l'installazione o la disinstallazione o per l'annullamento della sottoscrizione?

È possibile ottenere assistenza [eseguendo l'accesso a Office 365](http://go.microsoft.com/fwlink/?LinkID=529144&amp;clcid=0x409) | [Installare o disinstallare Office](http://go.microsoft.com/fwlink/?LinkID=827202&amp;clcid=0x409) | [Annullare Office 365](https://support.office.com/en-us/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Per altri problemi con Office 365, visitare il [Supporto Tecnico Microsoft](https://go.microsoft.com/fwlink/?LinkID=808783). Per ottenere supporto per Office 365 gestito da 21Vianet in Cina, contattare il [team di supporto di 21Vianet](https://support.office.com/en-US/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Per Office 365 Germany, contattare il [team di supporto di Office 365 Germany](https://support.office.com/en-us/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Opzioni di accesso

Office 365 dispone di due sistemi da poter utilizzare per le identità degli utenti:
  
- **Account aziendale o dell'istituto di istruzione (identità cloud)** Gli utenti ricevono credenziali cloud di Azure Active Directory (diverse dalle altre credenziali desktop o aziendali) per accedere a Office 365 e agli altri Servizi cloud Microsoft. Si tratta dell'identità predefinita che viene consigliata per poter minimizzare la complessità della distribuzione. Le password per account aziendali o dell'istituto di istruzioni utilizzano il Azure Active Directory [criterio password](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409).
    
- **Account federato (identità federata)** Per tutte le sottoscrizioni nelle organizzazioni con Active Directory in locale che utilizzano single sign-on (SSO), gli utenti possono accedere ai servizi Office 365 utilizzando le proprie credenziali di Active Directory. I criteri password sono memorizzati e controllati dall'implementazione di Active Directory dell'azienda. Per ulteriori informazioni sull'accesso Single Sign-On, vedere [Single Sign-On: roadmap](https://go.microsoft.com/fwlink/p/?LinkID=270015).
    
Il tipo di identità influisce sull'esperienza utente e sulle opzioni di gestione degli account utente, oltre che sui requisiti hardware e software e su altre considerazioni di distribuzione.
  
### <a name="custom-domains-and-identity-options"></a>Domini personalizzati e opzioni di gestione delle identità

Quando si crea un nuovo utente, il nome di accesso e l'indirizzo di posta elettronica dell'utente vengono assegnati al dominio predefinito come impostato nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere[Aggiungere utenti e dominio in Office 365](https://support.office.com/en-us/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Per impostazione predefinita, la sottoscrizione Office 365 utilizza il dominio \< _company name_\> **.onmicrosoft.com** creato con l'account.\*. Anziché mantenere il dominio onmicrosoft.com, è possibile aggiungere uno o più domini personalizzati a Office 365 e consentire agli utenti di effettuare l'accesso a qualsiasi dominio convalidato. Il dominio assegnato a ogni utente corrisponde all'indirizzo di posta elettronica visualizzato nei messaggi di posta elettronica inviati e ricevuti. 
  
In Office 365 è possibile ospitare fino a 900 domini Internet registrati, ciascuno dei quali è rappresentato da uno spazio dei nomi diverso. 
  
Per le organizzazioni che utilizzano l'accesso Single Sign-On, tutti gli utenti in un dominio devono utilizzare lo stesso sistema di identità: l'identità cloud o l'identità federata. Possono essere presenti ad esempio un gruppo di utenti che necessita solo di un'identità cloud, perché non accede ai sistemi locali, e un altro gruppo di utenti che utilizza sia Office 365, sia i sistemi locali. In questo caso è necessario aggiungere due domini a Office 365, ad esempio contractors.contoso.com e staff.contoso.com, e configurare l'accesso Single Sign-On solo per uno di questi domini. L'intero dominio può essere convertito da cloud a federato o viceversa.
  
Per ulteriori informazioni sui domini in Office 365, vedere la descrizione del servizio [Domini](domains.md). 
  
\* Se si utilizza Office 365 gestito da 21Vianet in Cina, il dominio predefinito è \<nomesocietà\> **.onmsChina.cn**. Se si utilizza Office 365 Germany, il dominio predefinito è \<nomesocietà\> **.onmicrosoft.de**
  
## <a name="authentication"></a>Autenticazione

Ad eccezione dei siti Internet per l'accesso anonimo creati con SharePoint Online, gli utenti che accedono ai servizi di Office 365 devono essere autenticati. 
  
- **Autenticazione moderna** L'autenticazione moderna abilita l'accesso basato su Active Directory Authentication Library (ADAL) per le applicazioni client di Office tra piattaforme. In questo modo, vengono abilitate le funzionalità di accesso, ad esempio, Multi-Factor Authentication (MFA), provider di identità di terze parti basati su SAML con applicazioni client di Office e autenticazione basata su smart card e certificato. Inoltre, Microsoft Outlook non deve più utilizzare il protocollo di autenticazione di base. Per ulteriori informazioni, compresa la disponibilità dell'autenticazione moderna tra le applicazioni di Office, vedere [Come funziona l'autenticazione moderna per le app client di Office 2013 e Office 2016](http://go.microsoft.com/fwlink/?LinkID=717892&amp;clcid=0x409) and [Utilizzo dell'autenticazione moderna di Office 365 con i client di Office](http://go.microsoft.com/fwlink/?LinkID=717893&amp;clcid=0x409).
    
    Per Exchange Online, l'autenticazione moderna non è attivata per impostazione predefinita. Per informazioni su come attivarla, vedere [Abilitare l'autenticazione moderna per Exchange Online](http://go.microsoft.com/fwlink/?LinkID=717894&amp;clcid=0x409).
    
- **Autenticazione dell'identità cloud** Per gli utenti con identità cloud viene utilizzata la tradizionale autenticazione challenge/response. Il Web browser viene reindirizzato al servizio di accesso di Office 365, che richiede l'immissione di nome utente e password per l'account professionale o dell'istituto di istruzione. Il servizio di accesso autentica le credenziali dell'utente e genera un token di servizio, che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. 
    
- **Autenticazione dell'identità federata** Gli utenti con identità federate vengono autenticati tramite Active Directory Federation Services (ADFS) 2.0 o un altro servizio token di sicurezza. Il Web browser viene reindirizzato al servizio di accesso di Office 365, che richiede l'immissione dell'ID aziendale dell'utente sotto forma di nome dell'entità utente (UPN, User Principal Name), ad esempio isabel@contoso.com. Il servizio di accesso determina che l'utente fa parte di un dominio federato e chiede se desidera essere reindirizzato al server federativo locale per l'autenticazione. Se l'utente ha effettuato l'accesso a un computer desktop (appartenente a un dominio), viene autenticato tramite Kerberos o NTLMv2 e il servizio token di sicurezza locale genera un token di accesso, che viene inviato al servizio di accesso di Office 365 dal Web browser. Utilizzando il token di accesso, il servizio di accesso genera un token di servizio che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. Per un elenco dei servizi token di sicurezza disponibili, vedere [Single Sign-On: Roadmap](https://go.microsoft.com/fwlink/p/?LinkID=270015).
    
Office 365 utilizza l'autenticazione basata su moduli e il traffico di autenticazione trasmesso in rete viene sempre crittografato con TLS/SSL tramite la porta 443. Il traffico di autenticazione per i servizi di Office 365 utilizza una percentuale trascurabile della larghezza di banda. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Autenticazione a più fattori per Office 365

Con Autenticazione a più fattori per Office 365\*, agli utenti viene richiesto di confermare telefonate, messaggi di testo o un'app di notifica sullo smartphone dopo aver immesso correttamente la password. L'utente può accedere solo dopo la seconda autenticazione. Gli amministratori di Office 365 possono registrare gli utenti per l'autenticazione a più fattori nell'interfaccia di amministrazione di Microsoft 365. Ulteriori informazioni su [Autenticazioni a più fattori in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=392429).
  
### <a name="rich-client-authentication"></a>Autenticazione dei rich client

L'autenticazione dei rich client, come le applicazioni desktop Microsoft Office, può avvenire in due modi:
  
- **Assistente per l'accesso ai Microsoft Online Services** Assistente per l'accesso, installato da configurazione desktop Office 365, contiene un servizio client che riceve da Office 365 un token di servizio dal servizio di accesso e lo restituisce al rich client. 
    
  - Se l'utente usa un'identità cloud viene richiesta l'immissione delle credenziali, che vengono quindi inviate dal servizio client al servizio di accesso di Office 365 per l'autenticazione tramite WS-Trust.
    
  - Se si utilizza un'identità federata, il servizio client contatta innanzitutto il server ADFS 2.0 per autenticare le credenziali tramite Kerberos o NTLMv2 e ottenere un token di accesso che viene quindi inviato al servizio di accesso di Office 365 tramite WS-Federation e WS-Trust.
    
- **Autenticazione di base o proxy su SSL** Il client Outlook invia le credenziali per l'autenticazione di base su SSL a Exchange Online. Exchange Online inoltra la richiesta di autenticazione alla piattaforma di gestione delle identità di Office 365 e quindi al server Active Directory Federation Service locale. 
    
Per assicurare che il rilevamento e l'autenticazione dei servizi Office 365 vengano eseguiti correttamente, gli amministratori devono applicare una serie di componenti e aggiornamenti a tutte le workstation che utilizzano rich client (ad esempio Microsoft Office 2010) e si connettono a Office 365. Lo strumento di configurazione desktop Office 365 è uno strumento automatico che configura le workstation con gli aggiornamenti necessari. Per ulteriori informazioni, vedere [Usare le app desktop correnti di Office con Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270049).
  
### <a name="sign-in-experience"></a>Esperienza di accesso

L'esperienza di accesso varia a seconda del tipo di identità di Office 365 in uso:
  
||**Identità cloud**|**Identità federata**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2010 o Office 2007 in Windows 7  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2010 o Office Outlook 2007 in Windows Vista  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|POP, IMAP, Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Esperienze Web: Portale Office 365 / Outlook Web App/ SharePoint Online / Office Online  <br/> |Richiede l'accesso a ogni sessione del browser <sup>4</sup> <br/> |Richiede l'accesso a ogni sessione <sup>3</sup> <br/> |
|Office 2010 o Office 2007 con SharePoint Online  <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>4</sup> <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>3</sup> <br/> |
|Skype for Business online  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Nessuna richiesta  <br/> |
|Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Alla prima richiesta è possibile salvare la password per l'uso futuro. Non verranno visualizzate altre richieste finché non si cambia password. > <sup>2</sup> Immettere le credenziali aziendali. È possibile salvare la password, per evitare che vengano visualizzate altre richieste finché non si cambia password. > <sup>3</sup> Tutte le app richiedono l'immissione del nome utente o la selezione di un pulsante di accesso. Se il computer appartiene al dominio, la password non viene richiesta. Se si fa clic su **Resta connesso**, non verranno visualizzate altre richieste finché non ci si disconnette. > <sup>4</sup> Se si fa clic su **Resta connesso**, non verranno visualizzate altre richieste finché non ci si disconnette. 
  
## <a name="creating-user-accounts"></a>Creazione di account utente

È possibile aggiungere utenti a Office 365 in molti modi. Per ulteriori informazioni, vedere [aggiungere utenti singolarmente o in blocco a Office 365-Guida](https://go.microsoft.com/fwlink/p/?linkid=860006) per [gli amministratori e aggiungere, rimuovere e gestire gli utenti nell'anteprima dell'interfaccia di amministrazione di Microsoft 365](http://go.microsoft.com/fwlink/?LinkID=624101&amp;clcid=0x409). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o modificare gli account utente in Office 365 gestito da 21Vianet - Guida di Amministrazione](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409).
  
## <a name="deleting-accounts"></a>Eliminazione di account

La modalità di eliminazione degli account varia a seconda che si utilizzi o meno la sincronizzazione con Active Directory: 
  
- Se non si utilizza la sincronizzazione con Active Directory, per eliminare gli account è possibile utilizzare la pagina di amministrazione di Office 365 o Windows PowerShell.
    
- Se si utilizza la sincronizzazione con Active Directory, è necessario eliminare gli utenti dalla struttura di Active Directory locale, anziché da Office 365.
    
Gli account eliminati diventano inattivi. Dopo circa 30 giorni dall'eliminazione è possibile ripristinare l'account. Per ulteriori informazioni sull'eliminazione e sul ripristino degli account, vedere [Eliminare o ripristinare utenti in Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270053); in alternativa, se utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o modificare gli account utente in Office 365 gestito da 21Vianet - Guida di Amministrazione](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409).
  
## <a name="password-management"></a>Gestione delle password

I criteri e le procedure per la gestione delle password dipendono dal sistema di identità.
  
 **Gestione delle password tramite identità cloud:**
  
Quando si utilizzano identità cloud, le password vengono generate automaticamente alla creazione dell'account.
  
- Per i requisiti di complessità delle password per le identità cloud, vedere [criterio password](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409).
    
- Per aumentare la sicurezza, gli utenti devono cambiare la propria password al primo accesso ai servizi di Office 365. Prima di accedere ai servizi Office 365 gli utenti devono pertanto effettuare l'accesso al portale di Office 365 e modificare la propria password.
    
- Gli amministratori possono impostare il criterio di scadenza per le password. Per ulteriori informazioni, vedere [Impostazione di criteri di scadenza della password per l'utente](https://go.microsoft.com/fwlink/p/?LinkID=285381).
    
Sono disponibili numerosi strumenti per la reimpostazione delle password per gli utenti con identità cloud:
  
- **Password reimpostata dall'amministratore** Se gli utenti perdono o dimenticano la loro password, gli amministratori possono reimpostarle nel portale Office 365 oppure utilizzando Windows PowerShell. Gli utenti possono cambiare la password solo se conoscono quella corrente. 
    
    Per i piani Enterprise, se gli amministratori perdono o dimenticano le password, un amministratore diverso con il ruolo di amministratore globale può reimpostare le password degli amministratori nell'interfaccia di amministrazione di Microsoft 365 o tramite Windows PowerShell. Per ulteriori informazioni, vedere [Reimpostare la password dell'amministratore](https://go.microsoft.com/fwlink/p/?LinkID=270062). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o ripristinare le password in Office 365 gestito da 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409).
    
- **Password cambiata dall'utente con Outlook Web App** La pagina delle opzioni di Outlook Web App include il collegamento ipertestuale Cambia password che reindirizza gli utenti alla pagina **Cambia password**. L'utente deve conoscere la password precedente. Per ulteriori informazioni, vedere [Modificare la password](https://go.microsoft.com/fwlink/p/?LinkID=270063). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Modificare o ripristinare le password in Office 365 gestito da 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409).
    
- **Diritti di reimpostazione della password basati sul ruolo** Per i piani Enterprise, gli utenti autorizzati, come il personale del supporto tecnico, possono ricevere diritti utente di **Reimpostazione password** e l'autorizzazione a cambiare le password tramite i ruoli predefiniti o personalizzati di Office 365, senza diventare amministratori dei servizi con diritti completi. Per impostazione predefinita nei piani Enterprise, gli amministratori con ruolo Amministratore globale, Amministratore password o Amministratore Gestione utenti possono cambiare le password. Per ulteriori informazioni, vedere [Assegnazione di ruoli di amministratore](https://go.microsoft.com/fwlink/p/?LinkID=270061).
    
- **Reimpostazione delle password tramite Windows PowerShell** Gli amministratori dei servizi possono utilizzare Windows PowerShell per reimpostare le password. 
    
 **Gestione delle password tramite identità federata:**
  
Quando si utilizza l'identità federata, le password vengono gestite in Active Directory. Il servizio token di sicurezza locale negozia l'autenticazione con Office 365 Federation Gateway senza inviare le password locali di Active Directory su Internet a Office 365. Vengono utilizzati criteri password locali o, per i client Web, l'identificazione a due fattori. Outlook Web App non include il collegamento ipertestuale Cambia password. Gli utenti possono cambiare password utilizzando gli strumenti standard locali o tramite le opzioni di accesso del proprio PC desktop.
  
Se lo [Scenario di sincronizzazione della directory con Single Sign-On (SSO)](https://go.microsoft.com/fwlink/p/?LinkId=509831) è attivo nell'ambiente Office 365 e si verifica un'interruzione che influisce sul provider di identità federato, il backup di sincronizzazione della password per l'accesso federato fornisce l'opzione per trasferire il dominio sulla sincronizzazione delle password manualmente. L'utilizzo della sincronizzazione delle password consentirà agli utenti di accedere a Office 365 mentre l'interruzione viene risolta. Informazioni su [come passare da Single Sign-On alla sincronizzazione delle password](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Gestione delle licenze

Una licenza di Office 365 consente all'utente di accedere a una serie di servizi Office 365. Un amministratore assegna una licenza a ogni utente per il servizio al quale desidera accedere. Per esempio, è possibile assegnare a un utente l'accesso a Skype for Business online, ma non a SharePoint Online.
  
Gli amministratori fatturazione di Office 365 possono modificare i dettagli della sottoscrizione come il numero di licenze utente e il numero di servizi aggiuntivi usati dalla propria società. Consultare [Assegnare o rimuovere licenze o visualizzare un elenco di utenti senza licenza in Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270069). Se si utilizza Office 365 gestito da 21Vianet, vedere [Assegnare o rimuovere le licenze in Office 365 gestito da 21Vianet](http://go.microsoft.com/fwlink/?LinkID=730747&amp;clcid=0x409).
  
## <a name="group-management"></a>Gestione dei gruppi

SharePoint Online utilizza i gruppi di sicurezza per controllare l'accesso ai siti. È possibile creare i gruppi di sicurezza nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni sui gruppi di protezione, vedere [Creare, modificare o eliminare un gruppo di sicurezza](http://go.microsoft.com/fwlink/?LinkID=733611&amp;clcid=0x409).
  
## <a name="administrator-roles"></a>Ruoli di amministratore

Office 365 Enterprise e utilizza un modello di controllo dell'accesso basato su ruoli: le autorizzazioni e le funzionalità sono definite dai ruoli di gestione. La persona che si iscrive a Office 365 per la propria organizzazione diventa automaticamente un amministratore globale, o di livello superiore. Ci sono cinque ruoli di amministratore: amministratore globale, amministratore fatturazione, amministratore password, amministratore del servizio e amministratore di gestione utenti. Per ulteriori informazioni sui ruoli amministratore in Office 365 Enterprise, inclusa la modalità di registrazione per l'amministrazione di Exchange Online, SharePoint Online e Skype for Business online, vedere [Assegnazione di ruoli di amministratore](https://go.microsoft.com/fwlink/p/?LinkID=282732). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Assegnazione di ruoli di amministratore in Office 365 per le aziende](https://go.microsoft.com/fwlink/p/?linkid=270061)
  
## <a name="delegated-administration-and-support-for-partners"></a>Amministrazione delegata e supporto per i partner

I partner possono essere autorizzati ad amministrare account per conto dei clienti. Quando autorizza l'amministrazione delegata, il cliente non richiede un account utente per i partner e non utilizza alcuna licenza di Office 365. Il partner possono assegnare l'accesso completo o limitato agli utenti della propria organizzazione. L'accesso limitato include i diritti di reimpostazione delle password, gestione delle richieste di servizio e monitoraggio dello stato del sistema. Per ulteriori informazioni, vedere [Aggiungere o rimuovere amministratori delegati](https://go.microsoft.com/fwlink/p/?LinkID=270055).
  
> [!NOTE]
> La possibilità di utilizzare e indicare un partner come un amministratore delegato varia in base al paese. 
  
## <a name="azure-active-directory-services"></a>Servizi di Azure Active Directory

Azure Active Directory (AD) offre funzionalità complete di gestione dell'identità e dell'accesso a Office 365. Unisce servizi di directory, governance d'identità avanzata, gestione degli accessi all'applicazione e una piattaforma basata su standard compositi per sviluppatori. Per ulteriori informazioni sulle funzionalità di AD in Office 365, vedere [Personalizzazione della pagina di accesso e ripristino autonomo della password](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Altre informazioni sulle [ versioni Free Basic e Premium di Azure Active Directory ](https://msdn.microsoft.com/en-us/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani, le opzioni autonome e le soluzioni locali di Office 365, vedere [Descrizione dei servizi della piattaforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  
