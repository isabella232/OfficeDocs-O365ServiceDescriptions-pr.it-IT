---
title: Gestione degli account utente
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: Microsoft Office 365 supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti.
ms.openlocfilehash: bd6e701c8ff4c699d305bfcde8a68e1867dd0bb2
ms.sourcegitcommit: d6c7836299ee5e86e890cab1c41f3bc21fd282de
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/22/2019
ms.locfileid: "37631655"
---
# <a name="user-account-management"></a>Gestione degli account utente

Microsoft Office 365 supporta i metodi seguenti per la creazione, la gestione e l'autenticazione degli utenti. 
  
> [!NOTE]
> Questo argomento non include informazioni sulle funzionalità di sicurezza che consentono o impediscono l'accesso a singole risorse di Office 365 (ad esempio, il controllo di accesso basato sui ruoli di Microsoft Exchange Online o le opzioni di configurazione della sicurezza in Microsoft SharePoint Online). Per informazioni dettagliate su tali funzionalità, vedere le descrizioni dei servizi [Descrizione del servizio Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) e [Descrizione del servizio SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Per ulteriori informazioni sugli strumenti che consentono di eseguire attività amministrative, vedere [Strumenti per gestire gli account di Office 365](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts). Per scoprire come eseguire operazioni di gestione giornaliera, vedere [Attività di gestione comuni per Office 365](https://docs.microsoft.com/office365/admin/manage/manage).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>È necessario ricevere assistenza per l'accesso, per l'installazione o la disinstallazione o per l'annullamento della sottoscrizione?

È possibile ottenere assistenza [eseguendo l'accesso a Office 365](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) | [Installare o disinstallare Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) | [Annullare Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Per altri problemi con Office 365, visitare il [Supporto Tecnico Microsoft](https://support.microsoft.com/contactus/). Per ottenere supporto per Office 365 gestito da 21Vianet in Cina, contattare il [team di supporto di 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Per Office 365 Germany, contattare il [team di supporto di Office 365 Germany](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Opzioni di accesso

Office 365 dispone di due sistemi da poter utilizzare per le identità degli utenti:
  
- **Account aziendale o dell'istituto di istruzione (identità cloud)** Gli utenti ricevono credenziali cloud di Azure Active Directory (diverse dalle altre credenziali desktop o aziendali) per accedere a Office 365 e agli altri Servizi cloud Microsoft. Si tratta dell'identità predefinita che viene consigliata per poter minimizzare la complessità della distribuzione. Le password per account aziendali o dell'istituto di istruzioni utilizzano il Azure Active Directory [criterio password](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- **Account federato (identità federata)** Per tutte le sottoscrizioni nelle organizzazioni con Active Directory in locale che utilizzano single sign-on (SSO), gli utenti possono accedere ai servizi Office 365 utilizzando le proprie credenziali di Active Directory. I criteri password sono memorizzati e controllati dall'implementazione di Active Directory dell'azienda. Per ulteriori informazioni sull'accesso Single Sign-On, vedere [Single Sign-On: roadmap](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Il tipo di identità influisce sull'esperienza utente e sulle opzioni di gestione degli account utente, oltre che sui requisiti hardware e software e su altre considerazioni di distribuzione.
  
### <a name="custom-domains-and-identity-options"></a>Domini personalizzati e opzioni di gestione delle identità

Quando si crea un nuovo utente, il nome di accesso e l'indirizzo di posta elettronica dell'utente vengono assegnati al dominio predefinito come impostato nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni, vedere[Aggiungere utenti e dominio in Office 365](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Per impostazione predefinita, la sottoscrizione Office 365 utilizza il dominio \< _company name_\> **.onmicrosoft.com** creato con l'account.\*. Anziché mantenere il dominio onmicrosoft.com, è possibile aggiungere uno o più domini personalizzati a Office 365 e consentire agli utenti di effettuare l'accesso a qualsiasi dominio convalidato. Il dominio assegnato a ogni utente corrisponde all'indirizzo di posta elettronica visualizzato nei messaggi di posta elettronica inviati e ricevuti. 
  
È possibile ospitare fino a 900 domini Internet registrati in Office 365, ognuno rappresentato da uno spazio dei nomi diverso. 
  
Per le organizzazioni che utilizzano l'accesso Single Sign-On, tutti gli utenti in un dominio devono utilizzare lo stesso sistema di identità: l'identità cloud o l'identità federata. Possono essere presenti ad esempio un gruppo di utenti che necessita solo di un'identità cloud, perché non accede ai sistemi locali, e un altro gruppo di utenti che utilizza sia Office 365, sia i sistemi locali. È necessario aggiungere due domini a Office 365, ad esempio contractors.contoso.com e staff.contoso.com, e configurare solo SSO per uno di essi. L'intero dominio può essere convertito da cloud a federato o viceversa.
  
Per ulteriori informazioni sui domini in Office 365, vedere la descrizione del servizio [Domini](domains.md). 
  
\* Se si utilizza Office 365 gestito da 21Vianet in Cina, il dominio predefinito è \<nomesocietà\> **.onmsChina.cn**. Se si utilizza Office 365 Germany, il dominio predefinito è \<nomesocietà\> **.onmicrosoft.de**
  
## <a name="authentication"></a>Autenticazione

Ad eccezione dei siti Internet per l'accesso anonimo creati con SharePoint Online, gli utenti che accedono ai servizi di Office 365 devono essere autenticati. 
  
- **Autenticazione moderna** L'autenticazione moderna abilita l'accesso basato su Active Directory Authentication Library (ADAL) per le applicazioni client di Office tra piattaforme. In questo modo, vengono abilitate le funzionalità di accesso, ad esempio, Multi-Factor Authentication (MFA), provider di identità di terze parti basati su SAML con applicazioni client di Office e autenticazione basata su smart card e certificato. Inoltre, Microsoft Outlook non deve più utilizzare il protocollo di autenticazione di base. Per ulteriori informazioni, compresa la disponibilità dell'autenticazione moderna tra le applicazioni di Office, vedere [Come funziona l'autenticazione moderna per le app client di Office 2013 e Office 2016](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) and [Utilizzo dell'autenticazione moderna di Office 365 con i client di Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    Per Exchange Online, l'autenticazione moderna non è attivata per impostazione predefinita. Per informazioni su come attivarla, vedere [Abilitare l'autenticazione moderna per Exchange Online](https://docs.microsoft.com/Exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticazione dell'identità cloud** Per gli utenti con identità cloud viene utilizzata la tradizionale autenticazione challenge/response. Il Web browser viene reindirizzato al servizio di accesso di Office 365, che richiede l'immissione di nome utente e password per l'account professionale o dell'istituto di istruzione. Il servizio di accesso autentica le credenziali dell'utente e genera un token di servizio, che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. 
    
- **Autenticazione dell'identità federata** Gli utenti con identità federate vengono autenticati tramite Active Directory Federation Services (ADFS) 2.0 o un altro servizio token di sicurezza. Il Web browser viene reindirizzato al servizio di accesso di Office 365, che richiede l'immissione dell'ID aziendale dell'utente sotto forma di nome dell'entità utente (UPN, User Principal Name), ad esempio isabel@contoso.com. Il servizio di accesso determina che l'utente fa parte di un dominio federato e chiede se desidera essere reindirizzato al server federativo locale per l'autenticazione. Se l'utente ha effettuato l'accesso a un computer desktop (appartenente a un dominio), viene autenticato tramite Kerberos o NTLMv2 e il servizio token di sicurezza locale genera un token di accesso, che viene inviato al servizio di accesso di Office 365 dal Web browser. Utilizzando il token di accesso, il servizio di accesso genera un token di servizio che viene inviato dal Web browser al servizio richiesto per effettuare l'accesso. Per un elenco dei servizi token di sicurezza disponibili, vedere [Single Sign-On: Roadmap](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Office 365 utilizza l'autenticazione basata su moduli e il traffico di autenticazione trasmesso in rete viene sempre crittografato con TLS/SSL tramite la porta 443. Il traffico di autenticazione per i servizi di Office 365 utilizza una percentuale trascurabile della larghezza di banda. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Autenticazione a più fattori per Office 365

Con l'autenticazione a più fattori per Office 365, gli utenti sono tenuti a riconoscere una telefonata, un messaggio di testo o una notifica sull'app nel proprio smartphone dopo aver inserito correttamente la propria password. L'utente può accedere solo dopo la seconda autenticazione. Gli amministratori di Office 365 possono registrare gli utenti per l'autenticazione a più fattori nell'interfaccia di amministrazione di Microsoft 365. Ulteriori informazioni su [Autenticazioni a più fattori in Office 365](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Autenticazione dei rich client

L'autenticazione dei rich client, come le applicazioni desktop Microsoft Office, può avvenire in due modi:
  
- **Assistente per l'accesso ai Microsoft Online Services** Assistente per l'accesso, installato da configurazione desktop Office 365, contiene un servizio client che riceve da Office 365 un token di servizio dal servizio di accesso e lo restituisce al rich client. 
    
  - Se l'utente usa un'identità cloud viene richiesta l'immissione delle credenziali, che vengono quindi inviate dal servizio client al servizio di accesso di Office 365 per l'autenticazione tramite WS-Trust.
    
  - Se si utilizza un'identità federata, il servizio client contatta innanzitutto il server ADFS 2.0 per autenticare le credenziali tramite Kerberos o NTLMv2 e ottenere un token di accesso che viene quindi inviato al servizio di accesso di Office 365 tramite WS-Federation e WS-Trust.
    
- **Autenticazione di base o proxy su SSL** Il client Outlook invia le credenziali per l'autenticazione di base su SSL a Exchange Online. Exchange Online inoltra la richiesta di autenticazione alla piattaforma di gestione delle identità di Office 365 e quindi al server Active Directory Federation Service locale. 
    
Per assicurare che il rilevamento e l'autenticazione dei servizi Office 365 vengano eseguiti correttamente, gli amministratori devono applicare una serie di componenti e aggiornamenti a tutte le workstation che utilizzano rich client (ad esempio Microsoft Office 2010) e si connettono a Office 365. Lo strumento di configurazione desktop Office 365 è uno strumento automatico che configura le workstation con gli aggiornamenti necessari. Per ulteriori informazioni, vedere [Usare le app desktop correnti di Office con Office 365](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US).
  
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
|Esperienze Web: Office 365 portal/Outlook sul Web/SharePoint Online/Office per il Web  <br/> |Richiede l'accesso a ogni sessione del browser <sup>4</sup> <br/> |Richiede l'accesso a ogni sessione <sup>3</sup> <br/> |
|Office 2010 o Office 2007 con SharePoint Online  <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>4</sup> <br/> |Richiede l'accesso a ogni sessione SharePoint Online<sup>3</sup> <br/> |
|Skype for Business online  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Nessuna richiesta  <br/> |
|Outlook per Mac  <br/> |Richiede l'accesso a ogni sessione <sup>1</sup> <br/> |Richiede l'accesso a ogni sessione <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> quando viene richiesto per la prima volta, è possibile salvare la password per un utilizzo futuro. Non verranno visualizzate altre richieste finché non si cambia password. <br/> 
<sup>2</sup> Immetti le credenziali aziendali. È possibile salvare la password, per evitare che vengano visualizzate altre richieste finché non si cambia password. <br/> 
<sup>3</sup> tutte le app richiedono di immettere o selezionare il nome utente per l'accesso. Se il computer appartiene al dominio, la password non viene richiesta. Se si seleziona Mantieni l'accesso, non verrà richiesto di nuovo fino a quando non viene **disconnesso** . <br/> 
<sup>4</sup> se si seleziona **Mantieni** l'accesso, non verrà richiesto di nuovo finché non si effettua l'accesso. 
  
## <a name="creating-user-accounts"></a>Creazione di account utente

È possibile aggiungere utenti a Office 365 in molti modi. Per ulteriori informazioni, vedere [aggiungere utenti singolarmente o in blocco a Office 365-Guida](https://docs.microsoft.com/office365/admin/add-users/add-users) per [gli amministratori e aggiungere, rimuovere e gestire gli utenti nell'anteprima dell'interfaccia di amministrazione di Microsoft 365](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o modificare gli account utente in Office 365 gestito da 21Vianet - Guida di Amministrazione](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="deleting-accounts"></a>Eliminazione di account

La modalità di eliminazione degli account varia a seconda che si utilizzi o meno la sincronizzazione con Active Directory: 
  
- Se non si utilizza la sincronizzazione con Active Directory, per eliminare gli account è possibile utilizzare la pagina di amministrazione di Office 365 o Windows PowerShell.
    
- Se si utilizza la sincronizzazione con Active Directory, è necessario eliminare gli utenti dalla struttura di Active Directory locale, anziché da Office 365.
    
Gli account eliminati diventano inattivi. Dopo circa 30 giorni dall'eliminazione è possibile ripristinare l'account. Per ulteriori informazioni sull'eliminazione e il ripristino degli account, vedere [eliminare gli utenti in office 365](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) e [ripristinare gli utenti in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user) oppure, se si utilizza Office 365 gestito da 21ViaNet in Cina, vedere [creare o modificare gli account utente in Office 365 gestito da 21Vianet-guida](https://docs.microsoft.com/office365/admin/add-users/add-users)per gli amministratori.
  
## <a name="password-management"></a>Gestione delle password

I criteri e le procedure per la gestione delle password dipendono dal sistema di identità.
  
 **Gestione delle password tramite identità cloud:**
  
Quando si utilizzano identità cloud, le password vengono generate automaticamente alla creazione dell'account.
  
- Per i requisiti di complessità delle password per le identità cloud, vedere [criterio password](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- Per aumentare la sicurezza, gli utenti devono cambiare la propria password al primo accesso ai servizi di Office 365. Prima di accedere ai servizi Office 365 gli utenti devono pertanto effettuare l'accesso al portale di Office 365 e modificare la propria password.
    
- Gli amministratori possono impostare il criterio di scadenza per le password. Per ulteriori informazioni, vedere [Impostazione di criteri di scadenza della password per l'utente](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy).
    
Sono disponibili numerosi strumenti per la reimpostazione delle password per gli utenti con identità cloud:
  
- **Password reimpostata dall'amministratore** Se gli utenti perdono o dimenticano la loro password, gli amministratori possono reimpostarle nel portale Office 365 oppure utilizzando Windows PowerShell. Gli utenti possono cambiare la password solo se conoscono quella corrente. 
    
    Per i piani Enterprise, se gli amministratori perdono o dimenticano le password, un amministratore diverso con il ruolo di amministratore globale può reimpostare le password degli amministratori nell'interfaccia di amministrazione di Microsoft 365 o tramite Windows PowerShell. Per ulteriori informazioni, vedere [Reimpostare la password dell'amministratore](https://docs.microsoft.com/office365/admin/add-users/reset-passwords). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Creare o ripristinare le password in Office 365 gestito da 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **L'utente modifica le password con Outlook sul Web** Nella pagina Opzioni di Outlook sul Web è incluso un collegamento ipertestuale Cambia password, che reindirizza gli utenti alla pagina **Cambia password** . L'utente deve conoscere la password precedente. Per ulteriori informazioni, vedere [Modificare la password](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Modificare o ripristinare le password in Office 365 gestito da 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Diritti di reimpostazione della password basati sul ruolo** Per i piani Enterprise, gli utenti autorizzati, come il personale del supporto tecnico, possono ricevere diritti utente di **Reimpostazione password** e l'autorizzazione a cambiare le password tramite i ruoli predefiniti o personalizzati di Office 365, senza diventare amministratori dei servizi con diritti completi. Per impostazione predefinita nei piani Enterprise, gli amministratori con ruolo Amministratore globale, Amministratore password o Amministratore Gestione utenti possono cambiare le password. Per ulteriori informazioni, vedere [Assegnazione di ruoli di amministratore](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **Reimpostazione delle password tramite Windows PowerShell** Gli amministratori dei servizi possono utilizzare Windows PowerShell per reimpostare le password. 
    
 **Gestione delle password tramite identità federata:**
  
Quando si utilizza l'identità federata, le password vengono gestite in Active Directory. Il servizio token di sicurezza locale negozia l'autenticazione con Office 365 Federation Gateway senza passare le password locali degli utenti di Active Directory tramite Internet a Office 365. Vengono utilizzati criteri password locali o, per i client Web, l'identificazione a due fattori. Outlook sul Web non include un collegamento ipertestuale Cambia password. Gli utenti possono cambiare password utilizzando gli strumenti standard locali o tramite le opzioni di accesso del proprio PC desktop.
  
Se lo [Scenario di sincronizzazione della directory con Single Sign-On (SSO)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) è attivo nell'ambiente Office 365 e si verifica un'interruzione che influisce sul provider di identità federato, il backup di sincronizzazione della password per l'accesso federato fornisce l'opzione per trasferire il dominio sulla sincronizzazione delle password manualmente. L'utilizzo della sincronizzazione delle password consentirà agli utenti di accedere a Office 365 mentre l'interruzione viene risolta. Informazioni su [come passare da Single Sign-On alla sincronizzazione delle password](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Gestione delle licenze

Una licenza di Office 365 consente all'utente di accedere a una serie di servizi Office 365. Un amministratore assegna una licenza a ogni utente per il servizio al quale desidera accedere. Per esempio, è possibile assegnare a un utente l'accesso a Skype for Business online, ma non a SharePoint Online.
  
Gli amministratori fatturazione di Office 365 possono modificare i dettagli della sottoscrizione come il numero di licenze utente e il numero di servizi aggiuntivi usati dalla propria società. Consultare [Assegnare o rimuovere licenze o visualizzare un elenco di utenti senza licenza in Office 365](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Se si utilizza Office 365 gestito da 21Vianet, vedere [Assegnare o rimuovere le licenze in Office 365 gestito da 21Vianet](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gestione dei gruppi

SharePoint Online utilizza i gruppi di sicurezza per controllare l'accesso ai siti. È possibile creare i gruppi di sicurezza nell'interfaccia di amministrazione di Microsoft 365. Per ulteriori informazioni sui gruppi di protezione, vedere [Creare, modificare o eliminare un gruppo di sicurezza](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Ruoli di amministratore

Office 365 Enterprise e utilizza un modello di controllo dell'accesso basato su ruoli: le autorizzazioni e le funzionalità sono definite dai ruoli di gestione. La persona che si iscrive a Office 365 per la propria organizzazione diventa automaticamente un amministratore globale, o di livello superiore. Ci sono cinque ruoli di amministratore: amministratore globale, amministratore fatturazione, amministratore password, amministratore del servizio e amministratore di gestione utenti. Per ulteriori informazioni sui ruoli amministratore in Office 365 Enterprise, inclusa la modalità di registrazione per l'amministrazione di Exchange Online, SharePoint Online e Skype for Business online, vedere [Assegnazione di ruoli di amministratore](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Se si utilizza Office 365 gestito da 21Vianet in Cina, vedere [Assegnazione di ruoli di amministratore in Office 365 per le aziende](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles)
  
## <a name="delegated-administration-and-support-for-partners"></a>Amministrazione delegata e supporto per i partner

I partner possono essere autorizzati ad amministrare account per conto dei clienti. Quando autorizza l'amministrazione delegata, il cliente non richiede un account utente per i partner e non utilizza alcuna licenza di Office 365. Il partner possono assegnare l'accesso completo o limitato agli utenti della propria organizzazione. L'accesso limitato include i diritti di reimpostazione delle password, gestione delle richieste di servizio e monitoraggio dello stato del sistema. 
  
> [!NOTE]
> La possibilità di utilizzare e indicare un partner come un amministratore delegato varia in base al paese. 
  
## <a name="azure-active-directory-services"></a>Servizi di Azure Active Directory

Azure Active Directory (AD) offre funzionalità complete di gestione dell'identità e dell'accesso a Office 365. Unisce servizi di directory, governance d'identità avanzata, gestione degli accessi all'applicazione e una piattaforma basata su standard compositi per sviluppatori. Per ulteriori informazioni sulle funzionalità di AD in Office 365, vedere [Personalizzazione della pagina di accesso e ripristino autonomo della password](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Altre informazioni sulle [ versioni Free Basic e Premium di Azure Active Directory ](https://msdn.microsoft.com/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [office 365 Platform Service Description](office-365-platform-service-description.md).
  
