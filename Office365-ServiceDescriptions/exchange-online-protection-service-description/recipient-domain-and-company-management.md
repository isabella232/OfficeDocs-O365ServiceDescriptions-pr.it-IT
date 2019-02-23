---
title: Gestione destinatari, dominio e società
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) offre diversi mezzi per la gestione delle informazioni relative a destinatari, dominio e società. In qualità di amministratore, è possibile eseguire alcune attività di gestione all'interno dell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguite nell'interfaccia di amministrazione di Microsoft 365.
ms.openlocfilehash: fcae2c3ad93b977fb197089e2c8809b74ada7bd7
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210329"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="75c27-104">Gestione destinatari, dominio e società</span><span class="sxs-lookup"><span data-stu-id="75c27-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="75c27-p102">Microsoft Exchange Online Protection (EOP) offre diversi mezzi per la gestione delle informazioni relative a destinatari, dominio e società. In qualità di amministratore, è possibile eseguire alcune attività di gestione all'interno dell'interfaccia di amministrazione di Exchange (EAC) e verificare altre attività di gestione eseguite nell'interfaccia di amministrazione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="75c27-p102">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information. As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="75c27-p103">Per informazioni su tutte le funzionalità di EOP? vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="75c27-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="75c27-109">destinatari posta</span><span class="sxs-lookup"><span data-stu-id="75c27-109">Mail recipients</span></span>
<span data-ttu-id="75c27-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="75c27-110"></span></span>

<span data-ttu-id="75c27-p104">I destinatari di posta vengono categorizzati come utenti o gruppi di posta elettronica e possono essere gestiti tramite la sincronizzazione della directory, direttamente nell'interfaccia di amministrazione di Exchange o tramite Windows PowerShell remoto. Se si gestiscono i destinatari in locale, è necessario eseguire la sincronizzazione della directory in modo che i destinatari di posta elettronica vengano riflessi nell'interfaccia di amministrazione di Exchange. Gli utenti gestiti esclusivamente nell'interfaccia di amministrazione di Microsoft 365 non sono visualizzabili in EAC, ma possono essere aggiunti o rimossi dall'appartenenza a un gruppo di ruoli amministratore in EAC. Per ulteriori informazioni sui destinatari in EOP, vedere [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="75c27-p104">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell. If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC. Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC. For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="75c27-115">Autorizzazioni del gruppo di ruolo Admin</span><span class="sxs-lookup"><span data-stu-id="75c27-115">Admin role group permissions</span></span>
<span data-ttu-id="75c27-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="75c27-116"></span></span>

<span data-ttu-id="75c27-p105">In EOP, è possibile configurare solo ruoli amministrativi. Gli utenti possono essere aggiunti e rimossi da gruppi di regole predefinite direttamente in EAC. Non è disponibile alcuna personalizzazione RBAC. Per ulteriori informazioni, vedere [Gestione autorizzazioni gruppo di ruoli di amministratore in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="75c27-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="75c27-121">Gestione del dominio</span><span class="sxs-lookup"><span data-stu-id="75c27-121">Domain management</span></span>
<span data-ttu-id="75c27-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="75c27-122"></span></span>

<span data-ttu-id="75c27-p106">I domini gestiti sono domini protetti da EOP. I domini gestiti possono essere visualizzati e i tipi di dominio possono essere modificati nell'interfaccia di amministrazione di Exchange. Il provisioning e la gestione dei domini si verificano nell'interfaccia di amministrazione di Microsoft 365 e le modifiche vengono riflesse nell'EAC. Per ulteriori informazioni, vedere [View or Edit managEd Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="75c27-p106">Managed domains are domains that are protected by EOP. Managed domains can be viewed and domain types can be edited in the EAC. Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC. For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="75c27-127">Corrispondenza sottodomini</span><span class="sxs-lookup"><span data-stu-id="75c27-127">Match subdomains</span></span>
<span data-ttu-id="75c27-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="75c27-128"></span></span>

<span data-ttu-id="75c27-p107">In EOP, puoi abilitare il flusso di posta nei sottodomini di un dominio gestito. Per ulteriori informazioni, vedi [Abilitare il flusso di posta nei sottodomini in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="75c27-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="75c27-131">DBEB (Directory Based Edge Blocking)</span><span class="sxs-lookup"><span data-stu-id="75c27-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="75c27-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="75c27-132"></span></span>

<span data-ttu-id="75c27-p108">La funzionalità Directory Based Edge Blocking consente di rifiutare messaggi per destinatari non validi nel perimetro della rete di servizio. DBEB consente agli amministratori di aggiungere destinatari a Office 365 e bloccare tutti i messaggi inviati a indirizzi di posta elettronica che non sono presenti in Office 365. Se un messaggio viene inviato a un indirizzo di posta elettronica valido presente in Office 365, il messaggio passa attraverso gli altri livelli del filtro del servizio (antimalware, antispam, regole di trasporto). Se l'indirizzo non è presente, il servizio blocca il messaggio prima che venga applicato il filtro e un rapporto di mancato recapito viene inviato al mittente per informarlo che il messaggio non è stato recapitato.</span><span class="sxs-lookup"><span data-stu-id="75c27-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="75c27-p109">L'attivazione DBEB richiede alcuni utenti e la configurazione del dominio. Per ulteriori informazioni, vedere [Utilizzare Directory Based Edge Blocking per rifiutare i messaggi inviati ai destinatari non validi](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="75c27-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="75c27-139">Disponibilità delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="75c27-139">Feature Availability</span></span>
<span data-ttu-id="75c27-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="75c27-140"></span></span>

<span data-ttu-id="75c27-141">Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online Protection](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="75c27-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

