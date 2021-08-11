---
title: Descrizione del servizio Archiviazione Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Leggere questo articolo per informazioni sull'Microsoft Exchange Online archiviazione.
ms.openlocfilehash: 2d37cc6c7cd4f75ae9a4ffb3da994e5b942f294d2d12fde869910d5506c69738
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664579"
---
# <a name="exchange-online-archiving-service-description"></a>Descrizione del servizio Archiviazione Exchange Online

Microsoft Exchange Online L'archiviazione è una soluzione di archiviazione Microsoft 365 basata su cloud di livello aziendale per le organizzazioni che hanno distribuito Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 e versioni successive) o sottoscrivere determinati piani di Exchange Online o Microsoft365. Archiviazione Exchange Online agevola le attività correlate ad archiviazione, conformità, regolamentazione ed eDiscovery e al tempo stesso semplifica l'infrastruttura locale riducendo i costi e il carico per l'IT.
  
In quanto servizio online di Microsoft, Archiviazione Exchange Online è stato progettato in modo da rispondere a elevati requisiti di sicurezza, affidabilità e produttività degli utenti. Per ulteriori informazioni sulle Microsoft 365, incluse le funzionalità comuni a tutti i servizi online Microsoft, vedere Microsoft 365 [e Office 365 descrizione del servizio della piattaforma.](../office-365-platform-service-description/office-365-platform-service-description.md)
  
Per acquistare Archiviazione Exchange Online, vedere [Archiviazione Exchange Online per server](https://products.office.com/exchange/microsoft-exchange-online-archiving-email).
  
## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sulle sottoscrizioni che consentono agli utenti di Archiviazione Exchange Online, vedere la tabella di confronto completa [delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)
  
> [!TIP]
> È possibile esportare, salvare e stampare pagine nelle descrizioni dei servizi. Informazioni su come [esportare i risultati della ricerca contenuto.](/office365/securitycompliance/export-search-results) 
  
## <a name="exchange-online-archiving-plans"></a>Piani di sottoscrizione di Archiviazione Exchange Online

Archiviazione Exchange Online è disponibile attraverso i piani di sottoscrizione elencati di seguito.<br><br>
  
| Piano | Descrizione |
|:-----|:-----|
|**Archiviazione Exchange Online per Exchange Server** <br/> |Archivio basato su cloud per gli utenti con cassette postali principali in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva).  <br/> Per aggiungere un archivio basato sul cloud a una cassetta postale principale che si trova su un server Exchange locale, è necessario configurare la distribuzione ibrida. Per ulteriori informazioni sulle distribuzioni ibride, [vedere Exchange Server distribuzioni ibride](/exchange/exchange-hybrid).  <br/> |
|**Archiviazione Exchange Online per Exchange Server (tramite Enterprise CAL Suite)** <br/> |Archivio basato su cloud per gli utenti con cassette postali principali in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva). Per informazioni dettagliate, vedere [Client Access Licenses and Management Licenses](https://www.microsoft.com/licensing/product-licensing/client-access-license).  <br/> |
|**Archiviazione Exchange Online per Exchange Online** <br/> | Archiviazione basata su cloud e archiviazione sul posto come componente aggiuntivo per i piani<sup>1, 2 seguenti:</sup><br/>  Exchange Online Piano 1  <br/>  Chiosco Exchange Online  <br/>  Microsoft 365 Business Basic  <br/>  Microsoft 365 Business Standard  <br/>  Office 365 Enterprise E1  <br/>  Office 365 Enterprise F3  <br/> Microsoft 365 Enterprise F3<br/> <b>Nota:</b> I piani seguenti includono già l'archiviazione e non richiedono Archiviazione Exchange Online come componente aggiuntivo:<br/>Office 365 Education A1 <br/>Office 365 Education A3 <br/>  Office 365 Education A5 <br/>  Office 365 Enterprise E3 <br/>  Office 365 Enterprise E5 <br/>  Exchange Online, piano 2 <br/> Microsoft 365 Business Premium <br/>Microsoft 365 Enterprise E3 <br/> Microsoft 365 Enterprise E5 <br/>Per informazioni dettagliate sulle funzionalità di archiviazione Exchange Online cassette postali, vedere [Archive features in Archiviazione Exchange Online](./archive-features.md).           |
   
>[!NOTE]
><sup>1</sup> Per organizzazioni basate solo sul cloud in cui il server Exchange locale non contiene cassette postali, non è necessaria una distribuzione ibrida. Tuttavia, se sono presenti cassette postali locali, è necessaria la distribuzione ibrida.
<br/>
<sup>2 Exchange Online</sup> piano 1 e Microsoft 365 Apps hanno un limite di dimensione per la cassetta postale e l'archivio. Per ulteriori informazioni, vedere [Exchange Online limiti.](../exchange-online-service-description/exchange-online-limits.md) Archiviazione Exchange Online per Exchange Online aggiunge un archivio illimitato basato sul cloud e il [Archiviazione sul posto e conservazione per controversia legale](compliance-and-security-features.md#in-place-hold-and-litigation-hold).
  
Per informazioni su tutti i Microsoft 365? Microsoft 365 è disponibile in un'ampia gamma di piani per soddisfare al meglio le esigenze dell'organizzazione. Per informazioni sui diversi piani, incluse le opzioni di piano autonomo e le informazioni sullo spostamento da un piano a un altro, vedere Office 365 [opzioni del piano autonomo.](../office-365-platform-service-description/office-365-plan-options.md)
  
## <a name="requirements"></a>Requisiti

Per utilizzare Archiviazione Exchange Online per Exchange Server, le cassette postali degli utenti devono risiedere Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange Server 2010 (SP2 o versione successiva).
  
### <a name="federated-identity-and-single-sign-on"></a>Identità federative e Single Sign-On

Gli amministratori possono utilizzare un approccio Single Sign-On per l'autenticazione con Active Directory locale. A tale scopo, gli amministratori possono configurare Active Directory Federation Services locale, un servizio di Microsoft Windows Server 2008, per la federazione con il &reg; Microsoft Federation Gateway. Dopo la configurazione di Active Directory Federation Services, tutti gli utenti le cui identità sono basate sul dominio federato possono utilizzare l'accesso aziendale esistente per eseguire automaticamente l'autenticazione Office 365.
  
### <a name="user-subscriptions"></a>Sottoscrizioni degli utenti

Ogni utente che accede al servizio Archiviazione Exchange Online deve disporre di una sottoscrizione di Archiviazione Exchange Online. Ogni sottoscrizione dell'archivio di posta elettronica può essere utilizzata per l'archiviazione dei dati di messaggistica di un solo utente.
  
## <a name="unlimited-archive-storage-quota"></a>Quota di spazio di archiviazione illimitata

 La funzionalità di archiviazione illimitata (chiamata *archiviazione a espansione automatica*) offre spazio di archiviazione aggiuntivo per le cassette postali di archiviazione. Ogni sottoscrittore di Archiviazione Exchange Online riceve inizialmente 100 GB di spazio nella cassetta postale di archiviazione. Quando l'archiviazione con espansione automatica è attivata, viene aggiunto automaticamente ulteriore spazio di archiviazione quando viene raggiunta la capacità di archiviazione di 100 GB. Nelle distribuzioni ibride di Exchange l'archiviazione con espansione automatica è supportata solo per le cassette postali di archiviazione basate su cloud quando la cassetta postale dell'utente locale risiede su Exchange Server 2019, Exchange Server 2016 o Exchange Server 2013 (SP1 o versione successiva). Per altre informazioni, vedere [Panoramica dell'archiviazione illimitata](/office365/securitycompliance/unlimited-archiving).
  
> [!IMPORTANT]
> Gli amministratori non possono modificare la quota di archiviazione.<br/>
> L'archiviazione con espansione automatica non è supportata per le cassette postali che risiedono Exchange Server 2010.
  
> [!IMPORTANT]
> L'espansione automatica dell'archivio è supportata solo per le cassette postali utilizzate per singoli utenti o cassette postali condivise con un tasso di crescita che non supera *1 &nbsp; GB al giorno.* L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di non consentire uno spazio di archiviazione illimitato nei casi in cui una cassetta postale di archiviazione dell'utente sia utilizzata per l'archiviazione di dati di altri utenti, o in altri casi di usi inappropriati.
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilità delle funzionalità tra i piani di Archiviazione Exchange Online

| Funzionalità | Archiviazione Exchange Online per Exchange Server<sup>1</sup> | Archiviazione Exchange Online per Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Funzionalità di archiviazione in Archiviazione Exchange Online](archive-features.md)** <br/> |||
|Cassetta postale di archiviazione  <br/> |Sì  <br/> |Sì  <br/> |
|Spostare i messaggi utilizzando i criteri di archiviazione  <br/> |Sì  <br/> |Sì  <br/> |
|Importazione di dati nell'archivio  <br/> |Sì  <br/> |Sì  <br/> |
|Recupero di elementi eliminati  <br/> |Sì  <br/> |Sì  <br/> |
|Recupero di cassette postali eliminate  <br/> |Sì  <br/> |Sì  <br/> |
|Backup di cassetti postali  <br/> |Sì  <br/> |Sì  <br/> |
|**[Funzionalità client in Archiviazione Exchange Online](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Sì  <br/> |Sì  <br/> |
|Outlook sul Web  <br/> |Sì  <br/> |Sì  <br/> |
|**[Funzionalità di conformità e sicurezza in Archiviazione Exchange Online](compliance-and-security-features.md)** <br/> |||
|Criteri di conservazione  <br/> |Sì  <br/> |Sì  <br/> |
|Archiviazione sul posto e conservazione per controversia legale<sup>6</sup> <br/> |Sì  <br/> |Sì  <br/> |
|eDiscovery sul posto  <br/> |Sì  <br/> |Sì  <br/> |
|Crittografia tra server locali e Archiviazione Exchange Online  <br/> |Sì  <br/> |Sì  <br/> |
|Crittografia tra client e Archiviazione Exchange Online  <br/> |Sì  <br/> |Sì  <br/> |
|Crittografia: S/MIME e PGP  <br/> |Sì  <br/> |Sì  <br/> |
|IRM con Protezione delle informazioni di Azure  <br/> |No  <br/> |No<sup>4</sup> <br/> |
|IRM mediante Windows Server AD RMS  <br/> |Sì<sup>5</sup> <br/> |Sì<sup>5</sup> <br/> |
|Controllo  <br/> |Sì  <br/> |Sì  <br/> |
   

<sup>1</sup> Le cassette postali degli utenti devono trovarsi in Exchange 2010 SP2 o versione successiva.
<br/>
<sup>2</sup> Un archivio In-Place può essere utilizzato solo per archiviare la posta per un singolo utente o entità per cui è stata applicata una licenza. Non è consentito utilizzare un'Archiviazione sul posto come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, gli amministratori IT non possono creare cassette postali condivise e lasciare che gli utenti copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) una cassetta postale condivisa con l'esplicito scopo di archiviarla. <br/> 
<sup>3</sup> Per un elenco delle versioni di Microsoft Outlook supportate, vedere [Funzionalità client in Archiviazione Exchange Online](client-features.md). <br/>
<sup>4</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e abiliterà le funzionalità supportate di Information Rights Management (IRM). Alcune funzionalità di Azure Information Protection richiedono una sottoscrizione a Microsoft 365 Apps for enterprise, che non è inclusa in Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education o Office 365 Enterprise F3. <br/>
<sup>5</sup> Windows Server AD RMS è un server in locale che deve essere acquistato e gestito separatamente per poter abilitare le funzionalità IRM supportate. <br/>
<sup>6</sup> Quando imposta una cassetta postale sull'archiviazione sul posto o sul blocco per controversia legale, la conservazione interessa sia la cassetta postale primaria che quella di archiviazione.