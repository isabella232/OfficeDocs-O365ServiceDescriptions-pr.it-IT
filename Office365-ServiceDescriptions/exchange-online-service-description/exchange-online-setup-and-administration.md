---
title: Installazione e amministrazione di Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: In questo articolo vengono descritti i controlli e il supporto di amministrazione disponibili per personalizzare le impostazioni di Exchange Online e mantenere l'ambiente Exchange Online di un'organizzazione in alto, in esecuzione e corrente. Include anche le informazioni relative agli strumenti di amministrazione self-service e alle funzionalità disponibili per le organizzazioni, agli obiettivi di prestazioni e alle responsabilità amministrative di Microsoft e agli aggiornamenti dei prodotti e servizi.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133001"
---
# <a name="exchange-online-setup-and-administration"></a>Installazione e amministrazione di Exchange Online

In questo articolo vengono descritti i controlli e il supporto di amministrazione disponibili per personalizzare le impostazioni di Exchange Online e mantenere l'ambiente Exchange Online di un'organizzazione in alto, in esecuzione e corrente. Include anche le informazioni relative agli strumenti di amministrazione self-service e alle funzionalità disponibili per le organizzazioni, agli obiettivi di prestazioni e alle responsabilità amministrative di Microsoft e agli aggiornamenti dei prodotti e servizi.
  
## <a name="self-service-administration-tools"></a>Strumenti di amministrazione self-service

Anche se Microsoft controlla direttamente tutti i Data Center di Exchange Online ed è responsabile delle prestazioni complessive del sistema, è in grado di controllare solo una parte degli elementi che si combinano per fornire la totale esperienza per gli utenti. Le organizzazioni stesse sono responsabili delle connessioni di rete verso i data center, della rete WAN (Wide Area Network) del cliente e delle reti LAN (Local Area Network) del cliente. Le organizzazioni sono altresì responsabili dei dispositivi degli utenti e della loro configurazione.  Sono inoltre responsabili del mantenimento delle licenze necessarie a ciascun utente per la funzionalità desiderata, tra cui la capacità di gestione di tali funzionalità, finché l'utente necessiti di accedere alla funzionalità.
  
Pertanto, Exchange Online fornisce agli amministratori dei clienti i seguenti strumenti per gestire un'ampia gamma di attività relative alla messaggistica:
  
- [Il portale di Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Interfaccia di amministrazione di Microsoft 365](#microsoft-365-admin-center)
    
- [Interfaccia di amministrazione di Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Windows PowerShell remoto per Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Il portale di Microsoft Office 365

Il portale Microsoft Office 365, disponibile all'indirizzo [https://portal.office.com](https://portal.office.com), è il sito Web tramite il quale gli amministratori e i partner acquistano e gestiscono i servizi di Office 365 e dal quale avviano e utilizzano gli strumenti collaborativi di Office 365.
  
### <a name="microsoft-365-admin-center"></a>Interfaccia di amministrazione di Microsoft 365

L'interfaccia di amministrazione di Microsoft 365 è il portale Web da cui l'amministratore del servizio di ogni azienda può gestire gli account utente e le impostazioni per ognuno dei servizi Microsoft a cui sono sottoscritti. Dall'interfaccia di amministrazione di Microsoft 365 gli amministratori possono seguire i collegamenti all'interfaccia di amministrazione di Exchange (EAC), in cui è possibile gestire le impostazioni specifiche di Exchange Online. Per ulteriori informazioni sull'utilizzo dell'interfaccia di amministrazione di Microsoft 365, vedere il video seguente: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Interfaccia di amministrazione di Exchange

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
Per ulteriori informazioni sull'utilizzo dell'interfaccia di amministrazione di Exchange per la gestione di Exchange Online, vedere [Interfaccia di amministrazione di Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell remoto per Exchange Online

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> Per evitare attacchi DoS (Denial of Service), è possibile aprire massimo tre connessioni Windows PowerShell all'organizzazione Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Funzionalità self-service per Exchange Online

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Criteri di sicurezza per i dispositivi mobili per Exchange Online

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Verifica messaggi per Exchange Online

La verifica dei messaggi tramite la caratteristica rapporti di recapito è descritta nel seguente argomento: [Reporting features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Report utilizzo per Exchange Online

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- Visualizzazione della dimensione della cassetta postale per ogni utente dell'organizzazione.
    
- Visualizzazione delle autorizzazioni personalizzate impostate sulle cassette postali, come l'accesso delegato.
    
- L'estrazione dei dati relativi all'accesso ai dispositivi mobili, come. ad esempio, quali utenti si stanno connettendo tramite Exchange ActiveSync, quali dispositivi stanno utilizzando e quando si sono connessi per l'ultima volta.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Per ulteriori informazioni sui cmdlet di Windows PowerShell disponibili in Exchange Online, vedere [Cmdlet di Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Controllo per Exchange Online

La funzionalità di registrazione di controllo è descritta nel seguente argomento: [funzionalità di Reporting e strumenti di risoluzione dei problemi](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Aggiornamenti dei servizi e dei prodotti per Exchange Online

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Quando Microsoft rilascia una nuova versione di Exchange, i clienti hanno tempo fino a 12 mesi per aggiornare i loro servizi alla nuova versione.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  