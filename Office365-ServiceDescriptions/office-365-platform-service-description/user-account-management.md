---
title: User account management
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti.
ms.openlocfilehash: 5a4b242046503df691587919284454a670f817821eab1b3a6692f542bdcefadb
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702045"
---
# <a name="user-account-management"></a>User account management

Microsoft supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti. 
  
> [!NOTE]
> In questo argomento non sono incluse informazioni sulle funzionalità di sicurezza che consentono o proibiscono l'accesso a singole risorse Microsoft(ad esempio, il controllo dell'accesso basato sui ruoli in Microsoft Exchange Online o la configurazione della sicurezza in Microsoft SharePoint Online). Per informazioni dettagliate su queste funzionalità, vedere la [descrizione del Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) e la [descrizione del servizio SharePoint Online.](../sharepoint-online-service-description/sharepoint-online-service-description.md) 
  
Per informazioni sugli strumenti che consentono di eseguire attività amministrative, vedere [Strumenti per gestire gli account Microsoft.](/office365/enterprise/manage-office-365-accounts) Per informazioni su come eseguire attività di gestione quotidiane, vedere [Attività di gestione comuni](/office365/admin/manage/manage).
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Serve assistenza per l'accesso, l'installazione o la disinstallazione o l'annullamento dell'abbonamento?

Informazioni su: [accesso all'installazione](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)  |  [o disinstallazione](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)Office  |  [annullamento Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Per altri problemi, visitare il [centro di supporto Microsoft.](https://support.microsoft.com/contactus/) Per ottenere supporto per Office 365 gestito da 21Vianet in Cina, contattare il [team di supporto di 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Per Office 365 Germany, contattare il [team di supporto di Office 365 Germany](https://support.office.com/article/83ef2266-2543-48d7-a41a-1b56b403a8e9). 
  
## <a name="sign-in-options"></a>Opzioni di accesso

Microsoft dispone di due sistemi che possono essere utilizzati per le identità degli utenti:
  
- Account aziendale o dell'istituto di istruzione **(identità cloud):** gli utenti ricevono Azure Active Directory credenziali cloud, separate da altre credenziali desktop o aziendali, per accedere ai servizi cloud Microsoft. Si tratta dell'identità predefinita che viene consigliata per poter minimizzare la complessità della distribuzione. Le password per account aziendali o dell'istituto di istruzioni utilizzano il Azure Active Directory [criterio password](/previous-versions/azure/jj943764(v=azure.100)).
    
- **Account federato (identità federata):** per tutte le sottoscrizioni nelle organizzazioni con Active Directory locale che utilizzano single sign-on (SSO), gli utenti possono accedere a servizi Microsoft utilizzando le credenziali di Active Directory. I criteri password sono memorizzati e controllati dall'implementazione di Active Directory dell'azienda. Per ulteriori informazioni sull'accesso Single Sign-On, vedere [Single Sign-On: roadmap](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Il tipo di identità influisce sull'esperienza utente e sulle opzioni di gestione degli account utente, oltre che sui requisiti hardware e software e su altre considerazioni di distribuzione.
  
### <a name="custom-domains-and-identity-options"></a>Domini personalizzati e opzioni di gestione delle identità

Quando si crea un nuovo utente, il nome di accesso e l'indirizzo di posta elettronica dell'utente vengono assegnati al dominio predefinito come impostato nella interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere [Aggiungere utenti e dominio.](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611) 
  
Per impostazione predefinita, la sottoscrizione utilizza il <.onmicrosoft.com aziendale creato >  con l'account. Se si utilizza un Office 365 gestito da 21Vianet in Cina, il dominio predefinito è <*companyname* > **.onmsChina.cn**. Se si utilizza Office 365 Germania, il dominio predefinito è <*companyname* > **.onmicrosoft.de**. È possibile aggiungere uno o più domini personalizzati a Microsoft anziché conservare il dominio onmicrosoft.com e assegnare agli utenti l'accesso **con** uno qualsiasi dei domini convalidati. Il dominio assegnato a ogni utente è l'indirizzo di posta elettronica che verrà visualizzato nei messaggi di posta elettronica inviati e ricevuti. 
  
È possibile ospitare fino a 900 domini Internet registrati, ognuno rappresentato da uno spazio dei nomi diverso. 
  
Per le organizzazioni che utilizzano l'accesso Single Sign-On, tutti gli utenti in un dominio devono utilizzare lo stesso sistema di identità: l'identità cloud o l'identità federata. Ad esempio, è possibile avere un gruppo di utenti che necessita solo di un'identità cloud perché non accede ai sistemi locali e di un altro gruppo di utenti che usano Microsoft e i sistemi locali. È necessario aggiungere due domini a Office 365, ad esempio **contractors.contoso.com** e staff.contoso.com , **e** configurare SSO solo per uno di essi. L'intero dominio può essere convertito da cloud a federato o viceversa.
  
Per ulteriori informazioni sui domini in Office 365, vedere la descrizione del servizio [Domini](domains.md). 
  
## <a name="authentication"></a>Autenticazione

Ad eccezione dei siti Internet per l'accesso anonimo creati con SharePoint Online, gli utenti devono essere autenticati quando accedono servizi Microsoft. 
  
- **Autenticazione moderna:** l'autenticazione moderna consente l'accesso basato su Libreria di autenticazione Microsoft Office app client su più piattaforme. In questo modo, vengono abilitate le funzionalità di accesso, ad esempio, Multi-Factor Authentication (MFA), provider di identità di terze parti basati su SAML con applicazioni client di Office e autenticazione basata su smart card e certificato. Inoltre, Microsoft Outlook non deve più utilizzare il protocollo di autenticazione di base. Per ulteriori informazioni, inclusa la disponibilità dell'autenticazione moderna tra le applicazioni Office, vedere Funzionamento dell'autenticazione moderna per Office [2013 e Office 2016.](/office365/enterprise/modern-auth-for-office-2013-and-2016)
    
    L'autenticazione moderna è attivata per impostazione predefinita per Exchange Online. Per informazioni su come attivarla o disattivarla, vedere [Abilitare l'autenticazione moderna in Exchange Online](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticazione dell'identità cloud:** gli utenti con identità cloud vengono autenticati tramite challenge/response tradizionali.Cloud identity authentication - Users with cloud identities are authenticated using traditional challenge/response. Il Web browser viene reindirizzato al servizio di accesso Microsoft, in cui si digita il nome utente e la password per l'account aziendale o dell'istituto di istruzione. Il servizio di accesso autentica le credenziali dell'utente e genera un token di servizio, che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. 
    
- **Autenticazione dell'identità federata** - Gli utenti con identità federate vengono autenticati tramite Active Directory Federation Services (AD FS) 2.0 o altri servizi token di sicurezza. Il Web browser viene reindirizzato al servizio di accesso Microsoft, in cui si digita l'ID aziendale nel formato nome dell'entità utente (UPN), ad esempio: *isabel@contoso.com*. Il servizio di accesso determina che l'utente fa parte di un dominio federato e chiede se desidera essere reindirizzato al server federativo locale per l'autenticazione. Se si è connessi al desktop (aggiunto a un dominio), si è autenticati (utilizzando Kerberos o NTLMv2) e il servizio token di sicurezza locale genera un token di accesso, che il Web browser invia al servizio di accesso Microsoft. Utilizzando il token di accesso, il servizio di accesso genera un token di servizio che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. Per un elenco dei servizi token di sicurezza disponibili, vedere [Single Sign-On: Roadmap](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Microsoft utilizza l'autenticazione basata su moduli e il traffico di autenticazione sulla rete viene sempre crittografato con TLS/SSL tramite la porta 443. Il traffico di autenticazione utilizza una percentuale trascurabile di larghezza di banda per servizi Microsoft. 
  
### <a name="multi-factor-authentication"></a>Multi-Factor Authentication

Con Multi-Factor Authentication, gli utenti devono confermare una chiamata telefonica, un SMS o una notifica dell'app sullo smartphone dopo aver immesso correttamente la password. L'utente può accedere solo dopo la seconda autenticazione. Gli amministratori Microsoft possono registrare gli utenti per l'autenticazione a più fattori nella interfaccia di amministrazione di Microsoft 365. Ulteriori informazioni su [Multi-Factor Authentication.](/office365/admin/security-and-compliance/set-up-multi-factor-authentication)
  
### <a name="rich-client-authentication"></a>Autenticazione dei rich client

L'autenticazione dei rich client, come le applicazioni desktop Microsoft Office, può avvenire in due modi:
  
- **Microsoft Online Services Sign-In Assistant** - L'Assistente per l'accesso, installato dalla configurazione desktop, contiene un servizio client che ottiene un token di servizio dal servizio di accesso e lo restituisce al rich client. 
    
  - Se si dispone di un'identità cloud, viene visualizzato un prompt per le credenziali, che il servizio client invia al servizio di accesso per l'autenticazione (utilizzando WS-Trust).
    
  - Se si dispone di un'identità federata, il servizio client contatta innanzitutto il server AD FS 2.0 per autenticare le credenziali (utilizzando Kerberos o NTLMv2) e ottenere un token di accesso inviato al servizio di accesso (utilizzando WS-Federation e WS-Trust).
    
- **Autenticazione di base/proxy su SSL** - Il client Outlook le credenziali di autenticazione di base su SSL per Exchange Online. Exchange Online proxy la richiesta di autenticazione alla piattaforma di identità e quindi al server federativo Active Directory locale (per SSO). 
    
Per garantire l'individuazione e l'autenticazione corrette di servizi Microsoft, gli amministratori devono applicare un set di componenti e aggiornamenti a ogni workstation che utilizza rich client (ad esempio Microsoft Office 2010) e si connette a Office 365. La configurazione desktop è uno strumento automatizzato per configurare le workstation con gli aggiornamenti necessari. Per altre informazioni, vedi [Usare le app desktop Office corrente.](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7)
  
### <a name="sign-in-experience"></a>Esperienza di accesso

L'esperienza di accesso cambia a seconda del tipo di identità in uso:<br><br>
  
| Servizio | Identità cloud | Identità federativa |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2010 o Office 2007 in Windows 7  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2010 o Office Outlook 2007 in Windows Vista  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|POP, IMAP, Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Esperienze Web: interfaccia di amministrazione di Microsoft 365 / Outlook sul web/ SharePoint Online / Office per il web  <br/> |Richiede l'accesso a ogni sessione del browser <sup>4</sup> <br/> |Richiede l'accesso a ogni sessione <sup>3</sup> <br/> |
|Office 2010 o Office 2007 con SharePoint Online  <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>4</sup> <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>3</sup> <br/> |
|Skype for Business online  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Nessuna richiesta  <br/> |
|Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Quando richiesto per la prima volta, è possibile salvare la password per un uso futuro. Non verranno visualizzate altre richieste finché non si cambia password. <br/> 
<sup>2</sup> Immettere le credenziali aziendali. È possibile salvare la password, per evitare che vengano visualizzate altre richieste finché non si cambia password. <br/> 
<sup>3</sup> Tutte le app richiedono l'immissione o la selezione del nome utente per l'accesso. Se il computer appartiene al dominio, la password non viene richiesta. Se si seleziona **Mantieni l'accesso,** non verrà richiesto di nuovo fino alla disconnessione. <br/> 
<sup>4</sup> Se si seleziona **Mantieni l'accesso,** non verrà richiesto di nuovo fino alla disconnessione. 
  
## <a name="create-user-accounts"></a>Create user accounts

Esistono diversi modi per aggiungere utenti. Per ulteriori informazioni, vedere Aggiungere utenti singolarmente o in blocco [-](/office365/admin/add-users/add-users) Guida per gli amministratori e Aggiungere, rimuovere e gestire gli utenti [in interfaccia di amministrazione di Microsoft 365 Preview.](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3) Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o modificare gli account utente in Office 365 gestito da 21Vianet - Guida di Amministrazione](/office365/admin/add-users/add-users).
  
## <a name="delete-user-accounts"></a>Eliminare gli account utente

La modalità di eliminazione degli account varia a seconda che si utilizzi o meno la sincronizzazione con Active Directory: 
  
- Se non si utilizza la sincronizzazione della directory, gli account possono essere eliminati utilizzando la pagina di amministrazione o Windows PowerShell.
    
- Se si utilizza la sincronizzazione con Active Directory, è necessario eliminare gli utenti dalla struttura di Active Directory locale, anziché da Office 365.
    
Gli account eliminati diventano inattivi. Dopo circa 30 giorni dall'eliminazione è possibile ripristinare l'account. Per ulteriori informazioni sull'eliminazione e il ripristino degli account, vedere Delete [users](/office365/admin/add-users/delete-a-user) e [Restore users](/office365/admin/add-users/restore-user) oppure, se si utilizza Office 365 gestito da 21Vianet in Cina, vedere Create or edit user accounts in Office 365 operated [by 21Vianet - Admin Help.](/office365/admin/add-users/add-users)
  
## <a name="password-management"></a>Gestione delle password

I criteri e le procedure per la gestione delle password dipendono dal sistema di identità.
  
### <a name="cloud-identity-password-management"></a>Gestione delle password delle identità cloud
  
Quando si utilizzano identità cloud, le password vengono generate automaticamente alla creazione dell'account.
  
- Per i requisiti di complessità delle password per le identità cloud, vedere [criterio password](/previous-versions/azure/jj943764(v=azure.100)).
    
- Per aumentare la sicurezza, gli utenti devono modificare le password al primo accesso servizi Microsoft. Di conseguenza, prima che gli utenti possano accedere servizi Microsoft, devono accedere al interfaccia di amministrazione di Microsoft 365, dove viene richiesto di modificare le password.
    
- Gli amministratori possono impostare il criterio di scadenza per le password. Per ulteriori informazioni, vedere [Impostazione di criteri di scadenza della password per l'utente](/office365/admin/manage/set-password-expiration-policy).
    
Sono disponibili numerosi strumenti per la reimpostazione delle password per gli utenti con identità cloud:
  
- **L'amministratore reimposta la password:** se gli utenti perdono o dimenticano le password, gli amministratori possono reimpostare le password degli utenti nell'interfaccia di amministrazione o usando Windows PowerShell. Gli utenti possono cambiare la password solo se conoscono quella corrente. 
    
    Per i piani aziendali, se gli amministratori perdono o dimenticano le password, un amministratore diverso con il ruolo amministratore globale può reimpostare le password degli amministratori nel interfaccia di amministrazione di Microsoft 365 o utilizzando Windows PowerShell. Per ulteriori informazioni, vedere [Reimpostare la password dell'amministratore](/office365/admin/add-users/reset-passwords). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o ripristinare le password in Office 365 gestito da 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **User changes passwords with Outlook sul web** - La pagina Outlook sul web opzioni include un collegamento ipertestuale Cambia password, che reindirizza gli utenti alla pagina **Cambia** password. L'utente deve conoscere la password precedente. Per ulteriori informazioni, vedere [Modificare la password](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Modificare o ripristinare le password in Office 365 gestito da 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- Diritti per la **reimpostazione** della password basata sui ruoli - Per i piani aziendali, agli utenti autorizzati come il personale dell'helpdesk può essere assegnato il diritto utente Reimposta **password** e il diritto di modificare le password utilizzando ruoli predefiniti o personalizzati senza diventare amministratori di servizi completi. Per impostazione predefinita nei piani aziendali, gli amministratori con il ruolo Amministratore globale, Amministratore password o Amministratore gestione utenti possono modificare le password. Per ulteriori informazioni, vedere [Assegnazione di ruoli di amministratore](/office365/admin/add-users/assign-admin-roles).
    
- **Reimpostare le password Windows PowerShell** - Gli amministratori del servizio possono usare Windows PowerShell per reimpostare le password. 
    
### <a name="federated-identity-password-management"></a>Gestione delle password delle identità federate
  
Quando si utilizza l'identità federata, le password vengono gestite in Active Directory. Il servizio token di sicurezza locale negozia l'autenticazione con Federation Gateway senza passare le password locali di Active Directory degli utenti tramite Internet Office 365. Vengono utilizzati criteri password locali o, per i client Web, l'identificazione a due fattori. Outlook sul web non include un collegamento ipertestuale Cambia password. Gli utenti possono cambiare password utilizzando gli strumenti standard locali o tramite le opzioni di accesso del proprio PC desktop.
  
Se nell'ambiente dell'organizzazione è abilitata la sincronizzazione della directory con [single sign-on (SSO)](/previous-versions/azure/azure-services/dn441213(v=azure.100)) e si verifica un'interruzione che influisce sul provider di identità federate, Il backup della sincronizzazione delle password per l'accesso federato consente di passare manualmente al dominio in Sincronizzazione password. L'utilizzo di Sincronizzazione password consentirà agli utenti di accedere mentre l'interruzione è stata corretta. Informazioni [su come passare da Single Sign-On a Sincronizzazione password](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Gestione delle licenze

Una licenza consente a un utente di accedere a un set di servizi Microsoft. Un amministratore assegna una licenza a ogni utente per il servizio al quale desidera accedere. Per esempio, è possibile assegnare a un utente l'accesso a Skype for Business online, ma non a SharePoint Online.
  
Gli amministratori della fatturazione Microsoft possono apportare modifiche ai dettagli dell'abbonamento, ad esempio il numero di licenze utente e il numero di servizi aggiuntivi utilizzati dall'azienda. Vedere [Assegnare o rimuovere una licenza](/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Se si utilizza Office 365 gestito da 21Vianet, vedere [Assegnare o rimuovere le licenze in Office 365 gestito da 21Vianet](/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gestione dei gruppi

SharePoint Online utilizza i gruppi di sicurezza per controllare l'accesso ai siti. I gruppi di sicurezza possono essere creati nella interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni sui gruppi di protezione, vedere [Creare, modificare o eliminare un gruppo di sicurezza](/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Ruoli di amministratore

Office 365 per le aziende segue un modello RBAC (Role-Based Access Control): le autorizzazioni e le funzionalità sono definite dai ruoli di gestione. La persona che si iscrive a Office 365 per la propria organizzazione diventa automaticamente un amministratore globale, o di livello superiore. Ci sono cinque ruoli di amministratore: amministratore globale, amministratore fatturazione, amministratore password, amministratore del servizio e amministratore di gestione utenti. Per ulteriori informazioni sui ruoli di amministratore in Office 365 for enterprise, inclusa la modalità di applicazione a Exchange Online, SharePoint Online e all'amministrazione di Skype for Business Online, vedere [Assigning administrator roles](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Assegnazione di ruoli di amministratore in Office 365 per le aziende](/office365/admin/add-users/assign-admin-roles)
  
## <a name="delegated-administration-and-support-for-partners"></a>Amministrazione delegata e supporto per i partner

I partner possono essere autorizzati ad amministrare account per conto dei clienti. Il cliente non richiede un account utente per l'utilizzo da parte dei partner e non utilizza una licenza quando concede l'autorità di amministrazione delegata. Il partner possono assegnare l'accesso completo o limitato agli utenti della propria organizzazione. L'accesso limitato include i diritti di reimpostazione delle password, gestione delle richieste di servizio e monitoraggio dello stato del sistema. 
  
> [!NOTE]
> La possibilità di utilizzare e indicare un partner come un amministratore delegato varia in base al paese. 
  
## <a name="azure-active-directory-services"></a>Servizi di Azure Active Directory

Azure Active Directory (AD) offre funzionalità complete di gestione dell'identità e dell'accesso a Office 365. Unisce servizi di directory, governance d'identità avanzata, gestione degli accessi all'applicazione e una piattaforma basata su standard compositi per sviluppatori. Per ulteriori informazioni sulle funzionalità di Active Directory in Office 365, vedere [Sign in page branding and cloud user self-service password reset]() https://go.microsoft.com/fwlink/?linkid=2144147 . Altre informazioni sulle [ versioni Free Basic e Premium di Azure Active Directory ](/previous-versions/azure/dn532272(v=azure.100)). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Microsoft 365 [e Office 365 descrizione del servizio della piattaforma.](office-365-platform-service-description.md)
