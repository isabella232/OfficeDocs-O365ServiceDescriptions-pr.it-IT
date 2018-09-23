---
title: Installazione e amministrazione di Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: In questa sezione vengono descritti i controlli di amministrazione e supporto disponibili per personalizzare le impostazioni di Exchange Online e Rimani ambiente Exchange Online dell'organizzazione, in esecuzione, e corrente. Sono incluse informazioni sulle funzionalità disponibili per le organizzazioni; e strumenti di amministrazione self-service Responsabilità di amministrazione di Microsoft e impegni di prestazioni. e gli aggiornamenti di servizi e dei prodotti.
ms.openlocfilehash: 6b7bb1d68e6d676c39e9ebb254305b2799cc0931
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035980"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="63165-104">Installazione e amministrazione di Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="63165-p102">In questa sezione vengono descritti i controlli di amministrazione e supporto disponibili per personalizzare le impostazioni di Exchange Online e Rimani ambiente Exchange Online dell'organizzazione, in esecuzione, e corrente. Sono incluse informazioni sulle funzionalità disponibili per le organizzazioni; e strumenti di amministrazione self-service Responsabilità di amministrazione di Microsoft e impegni di prestazioni. e gli aggiornamenti di servizi e dei prodotti.</span><span class="sxs-lookup"><span data-stu-id="63165-p102">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current. It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="63165-107">Strumenti di amministrazione self-service</span><span class="sxs-lookup"><span data-stu-id="63165-107">Self-service administration tools</span></span>

<span data-ttu-id="63165-p103">Sebbene Microsoft controlli direttamente tutti i data center Exchange Online e sia responsabile delle prestazioni globali del sistema, è in grado di controllare solo una parte degli elementi che interagiscono per determinare l'esperienza complessiva degli utenti di Office 365. Le organizzazioni stesse sono responsabili delle connessioni di rete verso i data center, della rete WAN (Wide Area Network) del cliente e delle reti LAN (Local Area Network) del cliente. Le organizzazioni sono altresì responsabili dei dispositivi degli utenti e della loro configurazione.  Sono inoltre responsabili del mantenimento delle licenze necessarie a ciascun utente per la funzionalità desiderata, tra cui la capacità di gestione di tali funzionalità, finché l'utente necessiti di accedere alla funzionalità.</span><span class="sxs-lookup"><span data-stu-id="63165-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="63165-112">Pertanto, Exchange Online fornisce agli amministratori dei clienti i seguenti strumenti per gestire un'ampia gamma di attività relative alla messaggistica:</span><span class="sxs-lookup"><span data-stu-id="63165-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="63165-113">Il portale di Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="63165-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="63165-114">Interfaccia di amministrazione di Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="63165-114">Microsoft Office 365 admin center</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-admin-center)
    
- [<span data-ttu-id="63165-115">Interfaccia di amministrazione di Exchange</span><span class="sxs-lookup"><span data-stu-id="63165-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="63165-116">Windows PowerShell remoto per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="63165-117">Il portale di Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="63165-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="63165-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="63165-118"></span></span>

<span data-ttu-id="63165-119">Il portale Microsoft Office 365, disponibile all'indirizzo [https://portal.office.com](https://portal.office.com), è il sito Web tramite il quale gli amministratori e i partner acquistano e gestiscono i servizi di Office 365 e dal quale avviano e utilizzano gli strumenti collaborativi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="63165-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-office-365-admin-center"></a><span data-ttu-id="63165-120">Interfaccia di amministrazione di Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="63165-120">Microsoft Office 365 admin center</span></span>
<span data-ttu-id="63165-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="63165-121"></span></span>

<span data-ttu-id="63165-p104">L'interfaccia di amministrazione di Microsoft Office 365 è il portale Web dal quale ciascun amministratore dei servizi di un'azienda può gestire gli account e le impostazioni degli utenti per ognuno dei servizi di Office 365 che ha sottoscritto. Dall'interfaccia di amministrazione di Office 365 gli amministratori possono seguire i collegamenti all'interfaccia di amministrazione di Exchange dalla quale è possibile gestire le impostazioni specifiche di Exchange Online. Per ulteriori informazioni sulle funzionalità dell'interfaccia di amministrazione di Office 365, guardare il seguente video: [Introduzione a Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="63165-p104">The Microsoft Office 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe. From within the Office 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online. For more information about getting up and running using the Office 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="63165-125">Interfaccia di amministrazione di Exchange</span><span class="sxs-lookup"><span data-stu-id="63165-125">Exchange admin center</span></span>
<span data-ttu-id="63165-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="63165-126"></span></span>

<span data-ttu-id="63165-p105">Exchange Online offre una singola console di gestione unificata pensata per la facilità di utilizzo e ottimizzata per la gestione di distribuzioni ibride locali, online o ibride. L'interfaccia di amministrazione di Exchange consente agli amministratori di gestire le impostazioni specifiche di Exchange.</span><span class="sxs-lookup"><span data-stu-id="63165-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="63165-129">Per ulteriori informazioni sull'utilizzo dell'interfaccia di amministrazione di Exchange per la gestione di Exchange Online, vedere [Interfaccia di amministrazione di Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span><span class="sxs-lookup"><span data-stu-id="63165-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="63165-130">Windows PowerShell remoto per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="63165-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="63165-131"></span></span>

<span data-ttu-id="63165-p106">Tramite Windows PowerShell remoto, gli amministratori possono connettersi a Exchange Online per eseguire attività di gestione non disponibili o più difficilmente utilizzabili nell'interfaccia di amministrazione di Exchange. Tra queste attività sono incluse l'automazione delle attività ripetitive, le personalizzazione dei criteri e la connessione di Exchange Online a infrastrutture e processi esistenti. Per ulteriori informazioni, vedere [Connessione a Exchange Online tramite Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="63165-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="63165-p107">In Exchange Online vengono utilizzati gli stessi cmdlet di Windows PowerShell utilizzati in Exchange Server 2013, con l'esclusione di alcuni comandi e parametri non disponibili in quanto le relative funzionalità non sono previste in Exchange Online. Per un elenco dei cmdlet disponibili in Exchange Online, vedere [Cmdlet di Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="63165-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="63165-p108">Gli amministratori non hanno bisogno di installare alcuno strumento di gestione o migrazione di Exchange Server per utilizzare Windows PowerShell remoto. Tuttavia, sui computer degli amministratori deve essere installato Windows Management Framework 3.0, che include Windows PowerShell v3 e WinRM 3.0, e Windows .NET Framework 4.5. Questi componenti sono già installati sui computer con Windows 8 o Windows Server 2012. Gli amministratori possono scaricare manualmente questi componenti per i computer con Windows 7 o Windows Server 2008 R2.</span><span class="sxs-lookup"><span data-stu-id="63165-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="63165-141">Per evitare attacchi DoS (Denial of Service), è possibile aprire massimo tre connessioni Windows PowerShell all'organizzazione Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="63165-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="63165-142">Funzionalità self-service per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="63165-p109">Di seguito sono illustrate importanti funzionalità per la gestione di Exchange Online disponibili nell'interfaccia di amministrazione di Exchange, in Windows PowerShell remoto e in altri strumenti. Questi strumenti consentono di controllare anche molte altre impostazioni, seconde le modalità descritte nel presente documento.</span><span class="sxs-lookup"><span data-stu-id="63165-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="63165-145">Criteri di sicurezza per i dispositivi mobili per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="63165-p110">Exchange Online supporta gli stessi criteri ActiveSync per i dispositivi mobili di Exchange Server 2013. Gli amministratori possono applicare e personalizzare questi criteri di sicurezza per specifici utenti e gruppi tramite l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto.</span><span class="sxs-lookup"><span data-stu-id="63165-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="63165-148">Verifica messaggi per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="63165-149">La verifica messaggi tramite la funzionalità Rapporti di recapito è descritta nei seguenti argomenti: [Funzionalità di reporting e risoluzione dei problemi](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="63165-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="63165-150">Report utilizzo per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="63165-p111">Gli amministratori possono utilizzare Windows PowerShell remoto per recuperare informazioni sul modo in cui gli utenti dell'organizzazione utilizzano il servizio Exchange Online. Tali informazioni includono:</span><span class="sxs-lookup"><span data-stu-id="63165-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="63165-153">Visualizzazione della dimensione della cassetta postale per ogni utente dell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="63165-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="63165-154">Visualizzazione delle autorizzazioni personalizzate impostate sulle cassette postali, come l'accesso delegato.</span><span class="sxs-lookup"><span data-stu-id="63165-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="63165-155">L'estrazione dei dati relativi all'accesso ai dispositivi mobili, come. ad esempio, quali utenti si stanno connettendo tramite Exchange ActiveSync, quali dispositivi stanno utilizzando e quando si sono connessi per l'ultima volta.</span><span class="sxs-lookup"><span data-stu-id="63165-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="63165-p112">I cmdlet di Windows PowerShell remoto che iniziano con "get-" possono recuperare i dati dal sistema Exchange Online. Gli amministratori possono esportare queste informazioni da Windows PowerShell in formato csv a scopo di analisi o reporting.</span><span class="sxs-lookup"><span data-stu-id="63165-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="63165-158">Per ulteriori informazioni sui cmdlet di Windows PowerShell disponibili in Exchange Online, vedere [Cmdlet di Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="63165-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="63165-159">Controllo per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="63165-160">La funzionalità di registrazione di controllo è descritta nel seguente argomento: [Funzionalità di reporting e risoluzione dei problemi](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="63165-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="63165-161">Aggiornamenti dei servizi e dei prodotti per Exchange Online</span><span class="sxs-lookup"><span data-stu-id="63165-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="63165-p113">I clienti di Exchange Online possono beneficiare di aggiornamenti periodici della tecnologia Exchange, incluse le nuove versioni di Exchange Server. Questi aggiornamenti sono disponibili gratuitamente e garantiscono ai clienti un software Exchange sempre aggiornato.</span><span class="sxs-lookup"><span data-stu-id="63165-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="63165-164">Quando Microsoft rilascia una nuova versione di Exchange, i clienti hanno tempo fino a 12 mesi per aggiornare i loro servizi alla nuova versione.</span><span class="sxs-lookup"><span data-stu-id="63165-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="63165-165">Disponibilità delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="63165-165">Feature Availability</span></span>

<span data-ttu-id="63165-166">Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="63165-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

