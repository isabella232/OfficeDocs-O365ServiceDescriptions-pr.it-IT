---
title: User account management
ms.author: office365servicedesc
author: pamelaar
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
ms.openlocfilehash: 38d9c247e54943599554e374bc3c9905f043361b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131660"
---
# <a name="user-account-management"></a>User account management

Microsoft supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti. 
  
> [!NOTE]
> In questo argomento non sono incluse informazioni sulle funzionalità di sicurezza che consentono o impediscono l'accesso alle singole risorse Microsoft (ad esempio, il controllo di accesso basato sui ruoli in Microsoft Exchange Online o la configurazione della sicurezza in Microsoft SharePoint Online). Per informazioni dettagliate su queste funzionalità, vedere la descrizione del [servizio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) e la [Descrizione del servizio SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Se sono necessarie informazioni sugli strumenti che consentono di eseguire attività amministrative, vedere [strumenti per gestire gli account Microsoft](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts). Per informazioni su come eseguire le attività di gestione quotidiane, vedere [attività di gestione comuni](https://docs.microsoft.com/office365/admin/manage/manage).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>È necessario ricevere assistenza per l'accesso, per l'installazione o la disinstallazione o per l'annullamento della sottoscrizione?

Ottenere assistenza per l' [accesso all'](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)  |  [installazione o alla disinstallazione di Office per l'](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)  |  [annullamento di Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Per altri problemi visitare il [Centro supporto tecnico Microsoft](https://support.microsoft.com/contactus/). Per ottenere supporto per Office 365 gestito da 21Vianet in Cina, contattare il [team di supporto di 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Per Office 365 Germany, contattare il [team di supporto di Office 365 Germany](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Opzioni di accesso

Microsoft dispone di due sistemi che è possibile utilizzare per le identità degli utenti:
  
- **Account aziendale o dell'Istituto di istruzione (identità cloud)** Gli utenti ricevono le credenziali cloud di Azure Active Directory, separate da altre credenziali desktop o aziendali, per l'accesso ai servizi cloud Microsoft. Si tratta dell'identità predefinita che viene consigliata per poter minimizzare la complessità della distribuzione. Le password per account aziendali o dell'istituto di istruzioni utilizzano il Azure Active Directory [criterio password](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- **Account federato (identità federata)** Per tutte le sottoscrizioni di organizzazioni con Active Directory locale che utilizzano Single Sign-on (SSO), gli utenti possono accedere ai servizi Microsoft utilizzando le credenziali di Active Directory. I criteri password sono memorizzati e controllati dall'implementazione di Active Directory dell'azienda. Per ulteriori informazioni sull'accesso Single Sign-On, vedere [Single Sign-On: roadmap](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Il tipo di identità influisce sull'esperienza utente e sulle opzioni di gestione degli account utente, oltre che sui requisiti hardware e software e su altre considerazioni di distribuzione.
  
### <a name="custom-domains-and-identity-options"></a>Domini personalizzati e opzioni di gestione delle identità

Quando si crea un nuovo utente, il nome di accesso e l'indirizzo di posta elettronica dell'utente vengono assegnati al dominio predefinito come impostato nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere [aggiungere gli utenti e il dominio](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Per impostazione predefinita, la sottoscrizione utilizza il \< _company name_\> dominio **. onmicrosoft.com** creato con l'account. \* È possibile aggiungere uno o più domini personalizzati a Microsoft anziché mantenere il dominio onmicrosoft.com, nonché assegnare agli utenti l'accesso con uno qualsiasi dei domini convalidati. Il dominio assegnato a ciascun utente è l'indirizzo di posta elettronica che verrà visualizzato nei messaggi di posta elettronica inviati e ricevuti. 
  
È possibile ospitare fino a 900 domini Internet registrati, ognuno dei quali è rappresentato da un altro namespace. 
  
Per le organizzazioni che utilizzano l'accesso Single Sign-On, tutti gli utenti in un dominio devono utilizzare lo stesso sistema di identità: l'identità cloud o l'identità federata. Ad esempio, è possibile disporre di un gruppo di utenti che richiede solo un'identità cloud poiché non accede ai sistemi locali e di un altro gruppo di utenti che utilizzano Microsoft e sistemi locali. È necessario aggiungere due domini a Office 365, ad esempio contractors.contoso.com e staff.contoso.com, e configurare solo SSO per uno di essi. L'intero dominio può essere convertito da cloud a federato o viceversa.
  
Per ulteriori informazioni sui domini in Office 365, vedere la descrizione del servizio [Domini](domains.md). 
  
\*Se si utilizza Office 365 gestito da 21Vianet in Cina, il dominio predefinito è \<companyname\> **. onmsChina.cn**. Se si utilizza Office 365 Germany, il dominio predefinito è \<companyname\> **. onmicrosoft.de**
  
## <a name="authentication"></a>Autenticazione

Ad eccezione dei siti Internet per l'accesso anonimo creati con SharePoint Online, gli utenti devono essere autenticati durante l'accesso ai servizi Microsoft. 
  
- **Autenticazione moderna** L'autenticazione moderna abilita l'accesso basato su Active Directory Authentication Library (ADAL) per le applicazioni client di Office tra piattaforme. In questo modo, vengono abilitate le funzionalità di accesso, ad esempio, Multi-Factor Authentication (MFA), provider di identità di terze parti basati su SAML con applicazioni client di Office e autenticazione basata su smart card e certificato. Inoltre, Microsoft Outlook non deve più utilizzare il protocollo di autenticazione di base. Per ulteriori informazioni, inclusa la disponibilità dell'autenticazione moderna tra le applicazioni di Office, vedere [come funziona l'autenticazione moderna per office 2013 e le app client di office 2016](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    L'autenticazione moderna è attivata per impostazione predefinita per Exchange Online. Per informazioni su come attivarla o disattivarla, vedere [abilitare l'autenticazione moderna in Exchange Online](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticazione dell'identità cloud** Per gli utenti con identità cloud viene utilizzata la tradizionale autenticazione challenge/response. Il Web browser viene reindirizzato al servizio di accesso di Microsoft, in cui si digita il nome utente e la password per l'account aziendale o dell'Istituto di istruzione. Il servizio di accesso autentica le credenziali dell'utente e genera un token di servizio, che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. 
    
- **Autenticazione dell'identità federata** Gli utenti con identità federate vengono autenticati tramite Active Directory Federation Services (ADFS) 2.0 o un altro servizio token di sicurezza. Il Web browser viene reindirizzato al servizio di accesso di Microsoft, in cui è possibile digitare l'ID aziendale nel formato nome dell'entità utente (UPN, ad esempio, isabel@contoso.com). Il servizio di accesso determina che l'utente fa parte di un dominio federato e chiede se desidera essere reindirizzato al server federativo locale per l'autenticazione. Se si è connessi al desktop (con dominio aggiunto), si è autenticati (tramite Kerberos o NTLMv2) e il servizio token di sicurezza locale genera un token di accesso che viene inviato dal Web browser al servizio di accesso di Microsoft. Utilizzando il token di accesso, il servizio di accesso genera un token di servizio che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. Per un elenco dei servizi token di sicurezza disponibili, vedere [Single Sign-On: Roadmap](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Microsoft utilizza l'autenticazione basata su moduli e il traffico di autenticazione tramite la rete viene sempre crittografato con TLS/SSL tramite la porta 443. Il traffico di autenticazione utilizza una percentuale trascurabile della larghezza di banda per i servizi Microsoft. 
  
### <a name="multi-factor-authentication"></a>Autenticazione a più fattori

Con l'autenticazione a più fattori, gli utenti sono tenuti a riconoscere una telefonata, un messaggio di testo o una notifica di app sul proprio smartphone dopo aver inserito correttamente la propria password. L'utente può accedere solo dopo la seconda autenticazione. Gli amministratori di Microsoft possono registrare gli utenti per l'autenticazione a più fattori nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere autenticazione a più [fattori](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Autenticazione dei rich client

L'autenticazione dei rich client, come le applicazioni desktop Microsoft Office, può avvenire in due modi:
  
- **Assistente per l'accesso ai Microsoft Online Services** L'assistente per l'accesso, installato dal programma di installazione desktop, contiene un servizio client che ottiene un token di servizio dal servizio di accesso e lo restituisce al rich client. 
    
  - Se si dispone di un'identità cloud, viene visualizzata una richiesta di credenziali, che il servizio client invia al servizio di accesso per l'autenticazione (tramite WS-Trust).
    
  - Se si dispone di un'identità federata, il servizio client contatterà prima il server AD FS 2,0 per autenticare le credenziali (tramite Kerberos o NTLMv2) e ottenere un token di accesso inviato al servizio accesso (tramite WS-Federation e WS-Trust).
    
- **Autenticazione di base o proxy su SSL** Il client Outlook invia le credenziali per l'autenticazione di base su SSL a Exchange Online. Exchange Online inoltra la richiesta di autenticazione alla piattaforma di identità e quindi al server federativo di Active Directory locale (per SSO). 
    
Per garantire l'individuazione e l'autenticazione appropriate dei servizi Microsoft, gli amministratori devono applicare un insieme di componenti e aggiornamenti a ogni workstation che utilizza client ricchi (come Microsoft Office 2010) e si connette a Office 365. Il programma di installazione desktop è uno strumento automatizzato per configurare le workstation con gli aggiornamenti necessari. Per ulteriori informazioni, vedere [Use My Current Office desktop apps](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US).
  
### <a name="sign-in-experience"></a>Esperienza di accesso

L'esperienza di accesso varia a seconda del tipo di identità in uso:
  
||**Identità cloud**|**Identità federata**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2010 o Office 2007 in Windows 7  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Outlook 2010 o Office Outlook 2007 in Windows Vista  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|POP, IMAP, Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
|Esperienze Web: interfaccia di amministrazione di Microsoft 365/Outlook sul Web/SharePoint Online/Office per il Web  <br/> |Richiede l'accesso a ogni sessione del browser <sup>4</sup> <br/> |Richiede l'accesso a ogni sessione <sup>3</sup> <br/> |
|Office 2010 o Office 2007 con SharePoint Online  <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>4</sup> <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>3</sup> <br/> |
|Skype for Business online  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Nessuna richiesta  <br/> |
|Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> quando viene richiesto per la prima volta, è possibile salvare la password per un utilizzo futuro. Non verranno visualizzate altre richieste finché non si cambia password. <br/> 
<sup>2</sup> Immetti le credenziali aziendali. È possibile salvare la password, per evitare che vengano visualizzate altre richieste finché non si cambia password. <br/> 
<sup>3</sup> tutte le app richiedono di immettere o selezionare il nome utente per l'accesso. Se il computer appartiene al dominio, la password non viene richiesta. Se si seleziona Mantieni l'accesso, non verrà richiesto di nuovo fino a quando non viene **disconnesso** . <br/> 
<sup>4</sup> se si seleziona **Mantieni** l'accesso, non verrà richiesto di nuovo finché non si effettua l'accesso. 
  
## <a name="creating-user-accounts"></a>Creazione di account utente

Sono disponibili diversi modi per aggiungere gli utenti. Per ulteriori informazioni, vedere [aggiungere utenti singolarmente o in blocco-guida](https://docs.microsoft.com/office365/admin/add-users/add-users) per l'amministratore e [aggiungere, rimuovere e gestire gli utenti nell'anteprima dell'interfaccia di amministrazione di Microsoft 365](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o modificare gli account utente in Office 365 gestito da 21Vianet - Guida di Amministrazione](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="deleting-accounts"></a>Eliminazione di account

La modalità di eliminazione degli account varia a seconda che si utilizzi o meno la sincronizzazione con Active Directory: 
  
- Se non si utilizza la sincronizzazione della directory, è possibile eliminare gli account utilizzando la pagina di amministrazione o Windows PowerShell.
    
- Se si utilizza la sincronizzazione con Active Directory, è necessario eliminare gli utenti dalla struttura di Active Directory locale, anziché da Office 365.
    
Gli account eliminati diventano inattivi. Dopo circa 30 giorni dall'eliminazione è possibile ripristinare l'account. Per ulteriori informazioni sull'eliminazione e il ripristino degli account, vedere [eliminare gli utenti](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) e [ripristinare gli utenti](https://docs.microsoft.com/office365/admin/add-users/restore-user) oppure, se si utilizza Office 365 gestito da 21ViaNet in Cina, vedere [creare o modificare gli account utente in Office 365 gestito da 21ViaNet-guida per gli amministratori](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Gestione delle password

I criteri e le procedure per la gestione delle password dipendono dal sistema di identità.
  
 **Gestione delle password tramite identità cloud:**
  
Quando si utilizzano identità cloud, le password vengono generate automaticamente alla creazione dell'account.
  
- Per i requisiti di complessità delle password per le identità cloud, vedere [criterio password](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- Per aumentare la sicurezza, gli utenti devono modificare le password al primo accesso ai servizi Microsoft. Di conseguenza, prima che gli utenti possano accedere ai servizi Microsoft, devono eseguire l'accesso all'interfaccia di amministrazione di Microsoft 365, in cui viene richiesto di modificare la password.
    
- Admins can set the password expiration policy. For more information, see [Set a user's password expiration policy](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy).
    
Sono disponibili numerosi strumenti per la reimpostazione delle password per gli utenti con identità cloud:
  
- **Amministratore reimposta la password** Se gli utenti perdono o dimenticano le password, gli amministratori possono reimpostare le password degli utenti nell'interfaccia di amministrazione o tramite Windows PowerShell. Gli utenti possono cambiare la password solo se conoscono quella corrente. 
    
    Per i piani Enterprise, se gli amministratori perdono o dimenticano le password, un amministratore diverso con il ruolo di amministratore globale può reimpostare le password degli amministratori nell'interfaccia di amministrazione di Microsoft 365 o tramite Windows PowerShell. Per ulteriori informazioni, vedere [Reimpostare la password dell'amministratore](https://docs.microsoft.com/office365/admin/add-users/reset-passwords). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o ripristinare le password in Office 365 gestito da 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **L'utente modifica le password con Outlook sul Web** Nella pagina Opzioni di Outlook sul Web è incluso un collegamento ipertestuale Cambia password, che reindirizza gli utenti alla pagina **Cambia password** . L'utente deve conoscere la password precedente. Per ulteriori informazioni, vedere [Modificare la password](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Modificare o ripristinare le password in Office 365 gestito da 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Diritti di reimpostazione della password di ripristino basati sui ruoli** Per i piani Enterprise, è possibile assegnare agli utenti autorizzati, come il personale del supporto tecnico, il diritto di **reimpostare la password** dell'utente e il diritto di modificare le password utilizzando ruoli predefiniti o personalizzati senza diventare amministratori dei servizi completi. Per impostazione predefinita nei piani Enterprise, gli amministratori con ruolo Amministratore globale, Amministratore password o Amministratore Gestione utenti possono cambiare le password. Per ulteriori informazioni, vedere [Assegnazione di ruoli di amministratore](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **Reimpostazione delle password tramite Windows PowerShell** Gli amministratori dei servizi possono utilizzare Windows PowerShell per reimpostare le password. 
    
 **Gestione delle password tramite identità federata:**
  
Quando si utilizza l'identità federata, le password vengono gestite in Active Directory. Il servizio token di sicurezza locale negozia l'autenticazione con il gateway federativo senza passare le password locali di Active Directory degli utenti tramite Internet a Office 365. Vengono utilizzati criteri password locali o, per i client Web, l'identificazione a due fattori. Outlook sul Web non include un collegamento ipertestuale Cambia password. Gli utenti possono cambiare password utilizzando gli strumenti standard locali o tramite le opzioni di accesso del proprio PC desktop.
  
Se si dispone della [sincronizzazione della directory con Single Sign-on (SSO)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) abilitato nell'ambiente dell'organizzazione ed è presente un'interruzione che influisce sul provider di identità federato, il backup della sincronizzazione delle password per l'accesso federato fornisce l'opzione per cambiare manualmente il dominio in sincronizzazione password. L'utilizzo di sincronizzazione password consentirà agli utenti di accedere mentre l'interruzione è fissa. Informazioni su [come passare dal servizio Single Sign-on alla sincronizzazione delle password](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Gestione delle licenze

Una licenza consente a un utente di accedere a un set di servizi Microsoft. Un amministratore assegna una licenza a ogni utente per il servizio al quale desidera accedere. Per esempio, è possibile assegnare a un utente l'accesso a Skype for Business online, ma non a SharePoint Online.
  
Gli amministratori di fatturazione Microsoft possono apportare modifiche ai dettagli della sottoscrizione, ad esempio il numero di licenze utente e il numero di servizi aggiuntivi che la società utilizza. Estrarre [o rimuovere una licenza](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Se si utilizza Office 365 gestito da 21Vianet, vedere [Assegnare o rimuovere le licenze in Office 365 gestito da 21Vianet](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gestione dei gruppi

SharePoint Online utilizza i gruppi di sicurezza per controllare l'accesso ai siti. È possibile creare i gruppi di sicurezza nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni sui gruppi di protezione, vedere [Creare, modificare o eliminare un gruppo di sicurezza](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Ruoli di amministratore

Office 365 Enterprise follows a role-based access control (RBAC) model: permissions and capabilities are defined by management roles. The person who signs up for Office 365 for his or her organization automatically becomes a global administrator, or top-level administrator. There are five administrator roles: global administrator, billing administrator, password administrator, service administrator, and user management administrator. For more information about administrator roles in Office 365 Enterprise, including how they apply to Exchange Online, SharePoint Online, and Skype for Business Online administration, see [Assigning administrator roles](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). If you are using Office 365 operated by 21Vianet in China, see [Assign admin roles in Office 365 for business](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Amministrazione delegata e supporto per i partner

I partner possono essere autorizzati ad amministrare account per conto dei clienti. Il cliente non richiede l'utilizzo di un account utente per i partner e non utilizza una licenza quando concede l'autorità di amministrazione delegata. Il partner possono assegnare l'accesso completo o limitato agli utenti della propria organizzazione. L'accesso limitato include i diritti di reimpostazione delle password, gestione delle richieste di servizio e monitoraggio dello stato del sistema. 
  
> [!NOTE]
> La possibilità di utilizzare e indicare un partner come un amministratore delegato varia in base al paese. 
  
## <a name="azure-active-directory-services"></a>Servizi di Azure Active Directory

Azure Active Directory (AD) brings comprehensive identity and access management capabilities to Office 365. It combines directory services, advanced identity governance, application access management and a rich standards-based platform for developers. To learn more about AD features in Office 365, see [Sign in page branding and cloud user self-service password reset](https://www.microsoft.com/en-us/microsoft-365/blog/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Learn more about the [Free, Basic, and Premium editions of Azure Active Directory](https://msdn.microsoft.com/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Microsoft 365 and Office 365 Platform Service Description](office-365-platform-service-description.md).
  
