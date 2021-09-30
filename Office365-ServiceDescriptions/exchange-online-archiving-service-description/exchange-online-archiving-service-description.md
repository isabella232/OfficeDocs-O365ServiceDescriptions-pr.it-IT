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
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Leggere questo articolo per informazioni sull'Microsoft Exchange Online archiviazione.
ms.openlocfilehash: db1627fdb0955c00a504468841bff88f62e8a67c
ms.sourcegitcommit: 28c7d4dc2c98364ca9a2c9ba91744f2db89950bf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/30/2021
ms.locfileid: "60015680"
---
# <a name="exchange-online-archiving-service-description"></a>Descrizione del servizio Archiviazione Exchange Online

Microsoft Exchange Online L'archiviazione Microsoft 365 una soluzione di archiviazione di livello aziendale basata su cloud per le organizzazioni che hanno distribuito Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 e versioni successive) o sottoscrivere determinati piani Exchange Online o Microsoft365. Archiviazione Exchange Online agevola le attività correlate ad archiviazione, conformità, regolamentazione ed eDiscovery e al tempo stesso semplifica l'infrastruttura locale riducendo i costi e il carico per l'IT.
  
In quanto servizio online di Microsoft, Archiviazione Exchange Online è stato progettato in modo da rispondere a elevati requisiti di sicurezza, affidabilità e produttività degli utenti. Per ulteriori informazioni sulle Microsoft 365, incluse le funzionalità comuni a tutti i servizi online Microsoft, vedere Microsoft 365 [e Office 365 descrizione del servizio della piattaforma.](../office-365-platform-service-description/office-365-platform-service-description.md)
  
Per acquistare Archiviazione Exchange Online, vedere [Archiviazione Exchange Online per server](https://products.office.com/exchange/microsoft-exchange-online-archiving-email).
  
## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Archiviazione Exchange Online, vedere la tabella di confronto completa [delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)
  
> [!TIP]
> È possibile esportare, salvare e stampare pagine nelle descrizioni dei servizi. Informazioni su come [esportare i risultati della ricerca contenuto.](/microsoft-365/compliance/export-search-results)
  
## <a name="exchange-online-archiving-plans"></a>Piani di sottoscrizione di Archiviazione Exchange Online

Archiviazione Exchange Online è disponibile attraverso i piani di sottoscrizione elencati di seguito.<br><br>
  
| Piano | Descrizione |
|:-----|:-----|
|**Archiviazione Exchange Online per Exchange Server** |Archivio basato su cloud per gli utenti con cassette postali principali in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva). <br/> Per aggiungere un archivio basato sul cloud a una cassetta postale principale che si trova su un server Exchange locale, è necessario configurare la distribuzione ibrida. Per ulteriori informazioni sulle distribuzioni ibride, [vedere Exchange Server distribuzioni ibride](/exchange/exchange-hybrid). |
|**Archiviazione Exchange Online per Exchange Server (tramite Enterprise CAL Suite)** |Archivio basato su cloud per gli utenti con cassette postali principali in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva). Per informazioni dettagliate, vedere [Client Access Licenses and Management Licenses](https://www.microsoft.com/licensing/product-licensing/client-access-license). |
|**Archiviazione Exchange Online per Exchange Online** | Archiviazione basata su cloud e archiviazione sul posto come componente aggiuntivo per i piani<sup>1,2,3 seguenti:</sup><br/> Exchange Online Piano 1 <br/> Chiosco Exchange Online <br/> Microsoft 365 Business Basic <br/> Microsoft 365 Business Standard <br/> Microsoft 365 Business Premium <br/> Office 365 E1 <br/> Office 365 A1 <br/> Office 365 G1 <br/> Office 365 F3 <br/> Microsoft 365 F3<br/> <b>Nota:</b> I piani seguenti includono già l'archiviazione e non richiedono Archiviazione Exchange Online come componente aggiuntivo:<br/>Office 365 A3 <br/> Office 365 A5 <br/> Office 365 E3 <br/> Office 365 E5 <br/> Exchange Online, piano 2 <br/>Microsoft 365 E3 <br/> Microsoft 365 E5 <br/> Microsoft 365 Conformità F5 <br/> Per informazioni dettagliate sulle funzionalità di archiviazione Exchange Online cassette postali, vedere [Archive features in Archiviazione Exchange Online](./archive-features.md).|

<sup>1</sup> Per organizzazioni basate solo sul cloud in cui il server Exchange locale non contiene cassette postali, non è necessaria una distribuzione ibrida. Tuttavia, se sono presenti cassette postali locali, è necessaria la distribuzione ibrida.
<br/>
<sup>2</sup> Exchange Online piano 1, Office 365 E1/A1/G1 e Microsoft 365 Business Basic/Standard/Premium hanno un limite di dimensione per la cassetta postale e l'archivio. Per altre informazioni, vedere [Limiti di Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Archiviazione Exchange Online per Exchange Online componente aggiuntivo aggiunge archiviazione con espansione automatica e archiviazione sul posto [e conservazione per controversia legale.](compliance-and-security-features.md#in-place-hold-and-litigation-hold)
<br/>
<sup>3</sup> Include GCC, GCC High e DoD per il governo degli Stati Uniti.

Per informazioni su tutti i Microsoft 365? Microsoft 365 è disponibile in un'ampia gamma di piani per soddisfare al meglio le esigenze dell'organizzazione. Per informazioni sui diversi piani, incluse le opzioni di piano autonomo e le informazioni sullo spostamento da un piano a un altro, vedere Office 365 [opzioni del piano autonomo.](../office-365-platform-service-description/office-365-plan-options.md)
  
## <a name="requirements"></a>Requisiti

Per utilizzare Archiviazione Exchange Online per Exchange Server, le cassette postali degli utenti devono risiedere Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange Server 2010 (SP2 o versione successiva).
  
### <a name="federated-identity-and-single-sign-on"></a>Identità federative e Single Sign-On

Gli amministratori possono utilizzare un approccio Single Sign-On per l'autenticazione con Active Directory locale. A tale scopo, gli amministratori possono configurare Active Directory Federation Services locale, un servizio di Microsoft Windows Server 2008, per la federazione con il &reg; Microsoft Federation Gateway. Dopo la configurazione di Active Directory Federation Services, tutti gli utenti le cui identità sono basate sul dominio federato possono utilizzare l'accesso aziendale esistente per eseguire automaticamente l'autenticazione Office 365.
  
### <a name="user-subscriptions"></a>Sottoscrizioni degli utenti

Ogni utente che accede al servizio Archiviazione Exchange Online deve disporre di una sottoscrizione di Archiviazione Exchange Online. Ogni sottoscrizione dell'archivio di posta elettronica può essere utilizzata per l'archiviazione dei dati di messaggistica di un solo utente.
  
## <a name="auto-expanding-archiving"></a>Archiviazione con espansione automatica

 La funzionalità di archiviazione denominata *archiviazione con espansione automatica* offre ulteriore spazio di archiviazione nelle cassette postali di archiviazione. Ogni sottoscrittore di Archiviazione Exchange Online riceve inizialmente 100 GB di spazio nella cassetta postale di archiviazione. Quando l'archiviazione con espansione automatica è attivata, viene aggiunto automaticamente ulteriore spazio di archiviazione quando viene raggiunta la capacità di archiviazione di 100 GB. Questa aggiunta incrementale di spazio di archiviazione continua fino a quando l'archivio non raggiunge 1,5 TB. Nelle distribuzioni ibride di Exchange, l'archiviazione con espansione automatica è supportata solo per le cassette postali di archiviazione basate su cloud quando la cassetta postale dell'utente locale si trova Exchange Server 2019, Exchange Server 2016 o Exchange Server 2013 (SP1 o versione successiva). Per ulteriori informazioni, vedere [Overview of auto-expanding archiving](/microsoft-365/compliance/autoexpanding-archiving).
  
> [!IMPORTANT]
> Gli amministratori non possono modificare la quota di archiviazione.
>
> L'archiviazione con espansione automatica non è supportata per le cassette postali che risiedono Exchange Server 2010.
  
> [!IMPORTANT]
> L'espansione automatica dell'archivio è supportata solo per le cassette postali utilizzate per singoli utenti o cassette postali condivise con un tasso di crescita che non supera *1 &nbsp; GB al giorno.* L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di negare l'archiviazione aggiuntiva nei casi in cui la cassetta postale di archiviazione di un utente viene utilizzata per archiviare i dati di archiviazione per altri utenti o in altri casi di utilizzo inappropriato.
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilità delle funzionalità tra i piani di Archiviazione Exchange Online

| Funzionalità | Archiviazione Exchange Online per Exchange Server<sup>1</sup> | Archiviazione Exchange Online per Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Funzionalità di archiviazione in Archiviazione Exchange Online](archive-features.md)** |||
|Cassetta postale di archiviazione  |Sì  |Sì  |
|Spostare i messaggi utilizzando i criteri di archiviazione  |Sì  |Sì  |
|Importazione di dati nell'archivio  |Sì  |Sì  |
|Recupero di elementi eliminati  |Sì  |Sì  |
|Recupero di cassette postali eliminate  |Sì  |Sì  |
|Backup di cassetti postali  |Sì  |Sì  |
|**[Funzionalità client in Archiviazione Exchange Online](client-features.md)** |||
|Outlook<sup>3</sup> |Sì  |Sì  |
|Outlook sul web  |Sì  |Sì  |
|**[Funzionalità di conformità e sicurezza in Archiviazione Exchange Online](compliance-and-security-features.md)** |||
|Criteri di conservazione  |Sì  |Sì  |
|Archiviazione sul posto e conservazione per controversia legale<sup>6</sup> |Sì  |Sì  |
|eDiscovery sul posto  |Sì  |Sì  |
|Crittografia tra server locali e Archiviazione Exchange Online  |Sì  |Sì  |
|Crittografia tra client e Archiviazione Exchange Online  |Sì  |Sì  |
|Crittografia: S/MIME e PGP  |Sì  |Sì  |
|IRM con Protezione delle informazioni di Azure  |No  |No<sup>4</sup> |
|IRM mediante Windows Server AD RMS  |Sì<sup>5</sup> |Sì<sup>5</sup> |
|Controllo  |Sì  |Sì  |
   

<sup>1</sup> Le cassette postali degli utenti devono trovarsi in Exchange 2010 SP2 o versione successiva.
<br/>
<sup>2</sup> Un archivio In-Place può essere utilizzato solo per archiviare la posta per un singolo utente o entità per cui è stata applicata una licenza. Non è consentito utilizzare un'Archiviazione sul posto come mezzo per archiviare messaggi da più utenti o entità. Ad esempio, gli amministratori IT non possono creare cassette postali condivise e lasciare che gli utenti copino (tramite i campi Cc o Ccn oppure con una regola di trasporto) una cassetta postale condivisa con l'esplicito scopo di archiviarla. <br/> 
<sup>3</sup> Per un elenco delle versioni di Microsoft Outlook supportate, vedere [Funzionalità client in Archiviazione Exchange Online](client-features.md). <br/>
<sup>4</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e abiliterà le funzionalità supportate di Information Rights Management (IRM). Alcune funzionalità di Azure Information Protection richiedono una sottoscrizione a Microsoft 365 Apps for enterprise, che non è inclusa in Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education o Office 365 Enterprise F3. <br/>
<sup>5</sup> Windows Server AD RMS è un server in locale che deve essere acquistato e gestito separatamente per poter abilitare le funzionalità IRM supportate. <br/>
<sup>6</sup> Quando imposta una cassetta postale sull'archiviazione sul posto o sul blocco per controversia legale, la conservazione interessa sia la cassetta postale primaria che quella di archiviazione.