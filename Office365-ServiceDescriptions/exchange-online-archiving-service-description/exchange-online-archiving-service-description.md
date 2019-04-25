---
title: Descrizione del servizio Archiviazione Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 02/14/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Archiviazione Microsoft Exchange Online è una soluzione di archiviazione di livello aziendale basata su cloud di Microsoft Office 365 per le organizzazioni che hanno distribuito Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 e versioni successive ) oppure abbonarsi a determinati piani di Exchange Online o Office 365. Archiviazione Exchange Online agevola le attività correlate ad archiviazione, conformità, regolamentazione ed eDiscovery e al tempo stesso semplifica l'infrastruttura locale riducendo i costi e il carico per l'IT.
ms.openlocfilehash: 20c22a644e43377c6a8b28011412ff78f802f742
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246152"
---
# <a name="exchange-online-archiving-service-description"></a>Descrizione del servizio Archiviazione Exchange Online

Archiviazione Microsoft Exchange Online è una soluzione di archiviazione di livello aziendale basata su cloud di Microsoft Office 365 per le organizzazioni che hanno distribuito Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 e versioni successive ) oppure abbonarsi a determinati piani di Exchange Online o Office 365. Archiviazione Exchange Online agevola le attività correlate ad archiviazione, conformità, regolamentazione ed eDiscovery e al tempo stesso semplifica l'infrastruttura locale riducendo i costi e il carico per l'IT.
  
Quale servizio online di Microsoft Office 365, Archiviazione Exchange Online è stato progettato in modo da rispondere a elevati requisiti di sicurezza, affidabilità e produttività degli utenti. Per ulteriori informazioni su Office 365, incluse funzionalità comuni a tutti i servizi online di Office 365, vedere [Descrizione dei servizi della piattaforma Office 365](../office-365-platform-service-description/office-365-platform-service-description.md).
  
Per acquistare l'Archiviazione Exchange Online, vedere [Archiviazione Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=314176).
  
Per un confronto tra le funzionalità offerte dai vari piani, vedere la pagina relativa al [confronto tra i piani di Office 365 for business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
> [!TIP]
> È possibile esportare, salvare e stampare le pagine della descrizione del servizio Office 365. Ulteriori informazioni su come [esportare più pagine](https://go.microsoft.com/fwlink/?LinkId=403349). 
  
## <a name="exchange-online-archiving-plans"></a>Piani di sottoscrizione di Archiviazione Exchange Online
<a name="bkmk_EOA_Plans"> </a>

Archiviazione Exchange Online è disponibile attraverso i piani di sottoscrizione elencati di seguito.
  
|**Piano**|**Descrizione**|
|:-----|:-----|
|**Archiviazione Exchange Online per Exchange Server** <br/> |Archivio basato sul cloud per utenti con cassette postali primarie in Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva).  <br/> Per aggiungere un archivio basato sul cloud a una cassetta postale principale che si trova su un server Exchange locale, è necessario configurare la distribuzione ibrida. Per ulteriori informazioni sulle distribuzioni ibride, vedere [Distribuzioni ibride di Exchange Server](https://technet.microsoft.com/library/jj200581%28v=exchg.150%29.aspx).  <br/> |
|**Archiviazione Exchange Online per Exchange Server (tramite Enterprise CAL Suite)** <br/> |Archivio basato sul cloud per utenti con cassette postali primarie in Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva). Per informazioni dettagliate, vedere le [indicazioni sulle licenze Core CAL Suite ed Enterprise CAL Suite](https://go.microsoft.com/fwlink/p/?LinkId=314160).  <br/> |
|**Archiviazione Exchange Online per Exchange Online** <br/> | Archiviazione basata sul cloud e blocco sul posto come componente aggiuntivo per i piani seguenti: <sup>1, 2</sup>,  <br/>  Exchange Online Piano 1  <br/>  Chiosco Exchange Online  <br/>  Office 365 Business Essentials  <br/>  Office 365 Business Premium  <br/>  Office 365 Enterprise E1  <br/>  Office 365 Enterprise F1  <br/>  <b>Nota:</b> I piani riportati di seguito includono già l'archiviazione e non richiedono l'archiviazione Exchange Online come componente aggiuntivo: > Office 365 Education a1 > Office 365 Education a3 > Office 365 Education a5 > Office 365 Enterprise E3 > Office 365 Enterprise E5 > Exchange on riga piano 2 > per informazioni dettagliate sulle funzionalità di archiviazione delle cassette postali di Exchange Online, vedere cassette postali di archiviazione [in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).           |
   
> [!NOTE]
> <sup>1</sup> Per organizzazioni basate solo sul cloud in cui il server Exchange locale non contiene cassette postali, non è necessaria una distribuzione ibrida. Tuttavia, se sono presenti cassette postali locali, è necessaria la distribuzione ibrida.
<br/> <sup>2</sup> I piani Exchange Online, piano 1 e Office 365 Business prevedono un [limite di dimensioni per la cassetta postale e l'archivio](https://go.microsoft.com/fwlink/?LinkId=330039). Archiviazione Exchange Online per Exchange Online aggiunge un archivio illimitato basato sul cloud e il [Archiviazione sul posto e conservazione per controversia legale](compliance-and-security-features.md#in-place-hold-and-litigation-hold).
  
Informazioni su tutti i piani di Office 365Sono disponibili diversi piani per Office 365, in modo da rispondere alle esigenze della propria organizzazione. Per informazioni relative ai diversi piani, ad esempio le opzioni dei piani autonomi e le informazioni su come passare da un piano a un altro, vedere [Opzioni di piani di Office 365](../office-365-platform-service-description/office-365-plan-options.md).
  
## <a name="requirements"></a>Requisiti
<a name="bkmk_EOA_Plans"> </a>

Per utilizzare l'archiviazione Exchange Online per Exchange Server, le cassette postali degli utenti devono risiedere in Exchange Server 2016, Exchange Server 2013 o Exchange Server 2010 (SP2 o versione successiva).
  
### <a name="federated-identity-and-single-sign-on"></a>Identità federative e Single Sign-On

Gli amministratori possono utilizzare un approccio di tipo Single Sign-On per l'autenticazione in Office 365 con l'ambiente Active Directory locale. A tale scopo, è possibile configurare un componente locale Active Directory Federation Services, ovvero un servizio di Microsoft Windows Server® 2008, per la federazione con Microsoft Federation Gateway. Al termine della configurazione di Active Directory Federation Services, tutti gli utenti di Office 365 le cui identità sono basate sul dominio federato possono utilizzare l'accesso aziendale esistente per eseguire l'autenticazione automatica in Office 365.
  
### <a name="user-subscriptions"></a>Sottoscrizioni degli utenti

Ogni utente che accede al servizio Archiviazione Exchange Online deve disporre di una sottoscrizione di Archiviazione Exchange Online. Ogni sottoscrizione dell'archivio di posta elettronica può essere utilizzata per l'archiviazione dei dati di messaggistica di un solo utente.
  
## <a name="unlimited-archive-storage-quota"></a>Quota di spazio di archiviazione illimitata
<a name="bkmk_EOA_Plans"> </a>

 La funzionalità di archiviazione illimitata in Office 365 (detta archiviazione ad espansione automatica) offre una quantità di memoria senza limiti per le cassette postali di archiviazione. L'archiviazione in espansione automatica è supportata solo in configurazione ibrida quando la cassetta postale dell'utente risiede in Exchange Server 2016 o Exchange Server 2013 (SP1 o versione successiva). Inizialmente, ogni sottoscrittore di Archiviazione Exchange Online riceve 100 GB di spazio nella cassetta postale di archiviazione. Quando si attiva l'archiviazione con espansione automatica, viene aggiunta ulteriore memoria al raggiungimento della capacità massima di 100 GB. Per ulteriori informazioni, vedere [Panoramica dell'archiviazione illimitata Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consultare la [roadmap di Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) per maggiori dettagli sulla disponibilità. 
  
> [!IMPORTANT]
> Gli amministratori non possono modificare la quota di archiviazione.
>
> L'archiviazione in espansione automatica non è supportata per le cassette postali che risiedono in Exchange Server 2010.
  
> [!IMPORTANT]
> L'espansione automatica dell'archivio è supportata solo per le cassette postali utilizzate per singoli utenti o per le cassette postali condivise con una frequenza di crescita *non superiore a 1&nbsp;GB al giorno*. L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti. 
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilità delle funzionalità tra i piani di Archiviazione Exchange Online
<a name="bkmk_EOA_Plans"> </a>

||||
|:-----|:-----|:-----|
|**Funzionalità** <br/> |**Archiviazione Exchange Online per Exchange Server<sup>1</sup>**          <br/> |**Archiviazione Exchange Online per Exchange Online<sup>2</sup>** <br/> |
|**[Funzionalità di archiviazione di Archiviazione Exchange Online](archive-features.md)** <br/> |||
|Cassetta postale di archiviazione  <br/> |Sì  <br/> |Sì  <br/> |
|Spostamento di messaggi in base ai criteri di archiviazione  <br/> |Sì  <br/> |Sì  <br/> |
|Importazione di dati nell'archivio  <br/> |Sì  <br/> |Sì  <br/> |
|Recupero di elementi eliminati  <br/> |Sì  <br/> |Sì  <br/> |
|Recupero di cassette postali eliminate  <br/> |Sì  <br/> |Sì  <br/> |
|Backup di cassetti postali  <br/> |Sì  <br/> |Sì  <br/> |
|**[Funzionalità client in Archiviazione Exchange Online](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Sì  <br/> |Sì  <br/> |
|Outlook Web App  <br/> |Sì  <br/> |Sì  <br/> |
|**[Funzionalità di conformità e sicurezza in Archiviazione Exchange Online](compliance-and-security-features.md)** <br/> |||
|Criteri di conservazione  <br/> |Sì  <br/> |Sì  <br/> |
|Archiviazione sul posto e conservazione per controversia legale<sup>6</sup> <br/> |Sì  <br/> |Sì  <br/> |
|eDiscovery sul posto  <br/> |Sì  <br/> |Sì  <br/> |
|Crittografia tra server locali e Archiviazione Exchange Online  <br/> |Sì  <br/> |Sì  <br/> |
|Crittografia tra client e Archiviazione Exchange Online  <br/> |Sì  <br/> |Sì  <br/> |
|Crittografia: S/MIME e PGP  <br/> |Sì  <br/> |Sì  <br/> |
|IRM con Protezione delle informazioni di Azure  <br/> |No  <br/> |N.<sup>4</sup> <br/> |
|IRM mediante Windows Server AD RMS  <br/> |Sì<sup>5</sup> <br/> |Sì<sup>5</sup> <br/> |
|Controllo  <br/> |Sì  <br/> |Sì  <br/> |
   

> <sup>1</sup> Le cassette postali degli utenti devono trovarsi in Exchange 2010 SP2 o versione successiva.
 <br/><sup>2</sup> un archivio sul posto può essere utilizzato solo per archiviare la posta per un singolo utente o un'entità per la quale è stata applicata una licenza. Non è consentito utilizzare un'Archiviazione sul posto come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, gli amministratori IT non possono creare cassette postali condivise e lasciare che gli utenti copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) una cassetta postale condivisa con l'esplicito scopo di archiviarla. 
 <br/> <sup>3</sup> Per un elenco delle versioni di Microsoft Outlook supportate, vedere [Funzionalità client in Archiviazione Exchange Online](client-features.md). 
 <br/><sup>4</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e consente di abilitare le funzionalità di Information Rights Management (IRM) supportate. Alcune funzionalità Protezione delle informazioni di Azure richiedono una sottoscrizione a Office 365 ProPlus che non è inclusa in Office 365 Business Essentials, Office 365 Business Premium, Office 365 Enterprise E1, Office 365 Education o Office 365 Enterprise F1. 
 <br/><sup>5</sup> Windows Server AD RMS è un server in locale che deve essere acquistato e gestito separatamente per poter abilitare le funzionalità IRM supportate. 
 <br/><sup>6</sup> Quando imposta una cassetta postale sull'archiviazione sul posto o sul blocco per controversia legale, la conservazione interessa sia la cassetta postale primaria che quella di archiviazione. 