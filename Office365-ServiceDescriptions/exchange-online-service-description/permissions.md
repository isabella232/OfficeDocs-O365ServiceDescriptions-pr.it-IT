---
title: Autorizzazioni
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132690"
---
# <a name="permissions"></a>Autorizzazioni

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Per ulteriori informazioni sul modello di autorizzazioni per il controllo dell'accesso basato sui ruoli utilizzato in Exchange Online, vedere [Autorizzazioni](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Autorizzazioni basate sui ruoli

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
Esistono due tipi di ruoli, ruoli amministrativi e ruoli dell'utente finale:
  
- **Ruoli amministrativi** Tali ruoli contengono le autorizzazioni che possono essere assegnate agli amministratori o a utenti esperti che utilizzano i gruppi di ruoli che si occupano della gestione di una parte dell'organizzazione Exchange Online, ad esempio destinatari, server o database. 
    
- **Ruoli dell'utente finale** Questi ruoli, assegnati mediante i criteri di assegnazione dei ruoli, consentono agli utenti di gestire le proprie cassette postali e i gruppi di distribuzione di cui sono proprietari. I ruoli dell'utente finale iniziano con il prefisso  `My`.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Alcuni dei ruoli disponibili nella versione locale di Microsoft Exchange Server 2013 potrebbero non essere disponibili in Exchange Online. 
  
Per ulteriori informazioni sulle autorizzazioni in Exchange Online, vedere [Autorizzazioni basate sui ruoli](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Gruppi di ruoli

I gruppi di ruoli di gestione associano i ruoli di gestione a un gruppo di amministratori o utenti esperti. Gli amministratori gestiscono una configurazione del destinatario o dell'organizzazione di Exchange Online su vasta scala. Gli utenti specialisti gestiscono funzionalità specifiche di Exchange Online, come, ad esempio, la conformità, oppure possono avere capacità di gestione limitate, ad esempio, come membri dell'assistenza tecnica, ma senza autorizzazioni di gestione troppo ampie. I gruppi di ruoli in genere associano i ruoli di gestione amministrativa che consentono agli amministratori e agli utenti esperti di gestire la configurazione dell'organizzazione e dei destinatari. Ad esempio, la possibilità per gli amministratori di gestire i destinatari o di utilizzare le funzionalità di individuazione delle cassette postali viene controllata per mezzo dei gruppi di ruolo. 
  
> [!IMPORTANT]
> Alcuni dei gruppi di ruolo disponibili nella versione locale di Microsoft Exchange Server 2013 potrebbero non essere disponibili in Exchange Online. 
  
Per ulteriori informazioni sui gruppi di ruolo, vedere [Gruppi di ruolo e criteri di assegnazione dei ruoli](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Criteri di assegnazione dei ruoli

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Alcune assegnazioni di ruolo disponibili nella versione locale di Microsoft Exchange Server 2013 potrebbero non essere disponibili in Exchange Online. 
  
Per ulteriori informazioni sui criteri di assegnazione dei ruoli, vedere [Gruppi di ruolo e criteri di assegnazione dei ruoli](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

