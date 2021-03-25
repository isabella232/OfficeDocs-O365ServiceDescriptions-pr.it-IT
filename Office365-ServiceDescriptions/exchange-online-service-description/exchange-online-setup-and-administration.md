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
description: In questo articolo vengono descritti i controlli di amministrazione e il supporto disponibili per personalizzare le impostazioni di Exchange Online e mantenere l'ambiente Exchange Online di un'organizzazione operativo, in esecuzione e corrente. Include anche le informazioni relative agli strumenti di amministrazione self-service e alle funzionalità disponibili per le organizzazioni, agli obiettivi di prestazioni e alle responsabilità amministrative di Microsoft e agli aggiornamenti dei prodotti e servizi.
ms.openlocfilehash: 169752df12564131e4b5fb0f95b94f62273cd5ff
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173671"
---
# <a name="exchange-online-setup-and-administration"></a>Installazione e amministrazione di Exchange Online

In questo articolo vengono descritti i controlli di amministrazione e il supporto disponibili per personalizzare le impostazioni di Exchange Online e mantenere l'ambiente Exchange Online di un'organizzazione operativo, in esecuzione e corrente. Include anche le informazioni relative agli strumenti di amministrazione self-service e alle funzionalità disponibili per le organizzazioni, agli obiettivi di prestazioni e alle responsabilità amministrative di Microsoft e agli aggiornamenti dei prodotti e servizi.
  
## <a name="self-service-administration-tools"></a>Strumenti di amministrazione self-service

Anche se Microsoft controlla direttamente tutti i data center di Exchange Online ed è responsabile delle prestazioni globali del sistema, può controllare solo una parte degli elementi che si combinano per offrire agli utenti l'esperienza totale. Le organizzazioni stesse sono responsabili delle connessioni di rete verso i data center, della rete WAN (Wide Area Network) del cliente e delle reti LAN (Local Area Network) del cliente. Le organizzazioni sono altresì responsabili dei dispositivi degli utenti e della loro configurazione.  Sono inoltre responsabili del mantenimento delle licenze necessarie a ciascun utente per la funzionalità desiderata, tra cui la capacità di gestione di tali funzionalità, finché l'utente necessiti di accedere alla funzionalità.
  
Pertanto, Exchange Online fornisce agli amministratori dei clienti i seguenti strumenti per gestire un'ampia gamma di attività relative alla messaggistica:
  
- [Il portale di Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Interfaccia di amministrazione di Microsoft 365](#microsoft-365-admin-center)
    
- [Interfaccia di amministrazione di Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Windows PowerShell remoto per Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Il portale di Microsoft Office 365

Il portale Microsoft Office 365, disponibile all'indirizzo [https://portal.office.com](https://portal.office.com), è il sito Web tramite il quale gli amministratori e i partner acquistano e gestiscono i servizi di Office 365 e dal quale avviano e utilizzano gli strumenti collaborativi di Office 365.
  
### <a name="microsoft-365-admin-center"></a>Interfaccia di amministrazione di Microsoft 365

L'interfaccia di amministrazione di Microsoft 365 è il portale Web da cui l'amministratore del servizio di ogni società può gestire gli account utente e le impostazioni per ognuno dei servizi Microsoft a cui sottoscrive. Dall'interfaccia di amministrazione di Microsoft 365, gli amministratori possono seguire i collegamenti all'interfaccia di amministrazione di Exchange (EAC), dove possono gestire le impostazioni specifiche di Exchange Online. Per ulteriori informazioni sull'utilizzo dell'interfaccia di amministrazione di Microsoft 365, vedere il video seguente: Introduzione a [Office 365 Enterprise.](https://go.microsoft.com/fwlink/p/?LinkId=271806)
  
### <a name="exchange-admin-center"></a>Interfaccia di amministrazione di Exchange

Exchange Online offre una singola console di gestione unificata pensata per la facilità di utilizzo e ottimizzata per la gestione di distribuzioni ibride locali, online o ibride. L'interfaccia di amministrazione di Exchange consente agli amministratori di gestire le impostazioni specifiche di Exchange.
  
Per ulteriori informazioni sull'utilizzo dell'interfaccia di amministrazione di Exchange per la gestione di Exchange Online, vedere [Interfaccia di amministrazione di Exchange](/exchange/exchange-admin-center).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell remoto per Exchange Online

Tramite Windows PowerShell remoto, gli amministratori possono connettersi a Exchange Online per eseguire attività di gestione non disponibili o più difficilmente utilizzabili nell'interfaccia di amministrazione di Exchange. Tra queste attività sono incluse l'automazione delle attività ripetitive, le personalizzazione dei criteri e la connessione di Exchange Online a infrastrutture e processi esistenti. Per ulteriori informazioni, vedere [Connessione a Exchange Online tramite Remote PowerShell](/powershell/exchange/connect-to-exchange-online-powershell).
  
In Exchange Online vengono utilizzati gli stessi cmdlet di Windows PowerShell utilizzati in Exchange Server 2013, con l'esclusione di alcuni comandi e parametri non disponibili in quanto le relative funzionalità non sono previste in Exchange Online. Per un elenco dei cmdlet disponibili in Exchange Online, vedere [Cmdlet di Exchange Online](/powershell/exchange/exchange-online-powershell).
  
Gli amministratori non hanno bisogno di installare alcuno strumento di gestione o migrazione di Exchange Server per utilizzare Windows PowerShell remoto. Tuttavia, sui computer degli amministratori deve essere installato Windows Management Framework 3.0, che include Windows PowerShell v3 e WinRM 3.0, e Windows .NET Framework 4.5. Questi componenti sono già installati sui computer con Windows 8 o Windows Server 2012. Gli amministratori possono scaricare manualmente questi componenti per i computer con Windows 7 o Windows Server 2008 R2.
  
> [!IMPORTANT]
> Per evitare attacchi DoS (Denial of Service), è possibile aprire massimo tre connessioni Windows PowerShell all'organizzazione Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Funzionalità self-service per Exchange Online

Di seguito sono illustrate importanti funzionalità per la gestione di Exchange Online disponibili nell'interfaccia di amministrazione di Exchange, in Windows PowerShell remoto e in altri strumenti. Questi strumenti consentono di controllare anche molte altre impostazioni, seconde le modalità descritte nel presente documento.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Criteri di sicurezza per i dispositivi mobili per Exchange Online

Exchange Online supporta gli stessi criteri ActiveSync per i dispositivi mobili di Exchange Server 2013. Gli amministratori possono applicare e personalizzare questi criteri di sicurezza per specifici utenti e gruppi tramite l'interfaccia di amministrazione di Exchange o Windows PowerShell remoto.
  
### <a name="message-tracking-for-exchange-online"></a>Verifica messaggi per Exchange Online

La verifica dei messaggi tramite la funzionalità Rapporti di recapito è descritta nell'argomento seguente: [Funzionalità di report e strumenti di risoluzione dei problemi.](reporting-features-and-troubleshooting-tools.md)
  
### <a name="usage-reporting-for-exchange-online"></a>Report utilizzo per Exchange Online

Gli amministratori possono utilizzare Windows PowerShell remoto per recuperare informazioni sul modo in cui gli utenti dell'organizzazione utilizzano il servizio Exchange Online. Tali informazioni includono:
  
- Visualizzazione della dimensione della cassetta postale per ogni utente dell'organizzazione.
    
- Visualizzazione delle autorizzazioni personalizzate impostate sulle cassette postali, come l'accesso delegato.
    
- L'estrazione dei dati relativi all'accesso ai dispositivi mobili, come. ad esempio, quali utenti si stanno connettendo tramite Exchange ActiveSync, quali dispositivi stanno utilizzando e quando si sono connessi per l'ultima volta.
    
I cmdlet di Windows PowerShell remoto che iniziano con "get-" possono recuperare i dati dal sistema Exchange Online. Gli amministratori possono esportare queste informazioni da Windows PowerShell in formato csv a scopo di analisi o reporting.
  
Per ulteriori informazioni sui cmdlet di Windows PowerShell disponibili in Exchange Online, vedere [Cmdlet di Exchange Online](/powershell/exchange/exchange-online-powershell).
  
### <a name="auditing-for-exchange-online"></a>Controllo per Exchange Online

La funzionalità di registrazione dei controlli è descritta nell'argomento seguente: [Funzionalità di creazione di report e strumenti di risoluzione dei problemi.](reporting-features-and-troubleshooting-tools.md)
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Aggiornamenti dei servizi e dei prodotti per Exchange Online

I clienti di Exchange Online possono beneficiare di aggiornamenti periodici della tecnologia Exchange, incluse le nuove versioni di Exchange Server. Questi aggiornamenti sono disponibili gratuitamente e garantiscono ai clienti un software Exchange sempre aggiornato.
  
Quando Microsoft rilascia una nuova versione di Exchange, i clienti hanno tempo fino a 12 mesi per aggiornare i loro servizi alla nuova versione.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Descrizione del servizio [Exchange Online.](exchange-online-service-description.md)
