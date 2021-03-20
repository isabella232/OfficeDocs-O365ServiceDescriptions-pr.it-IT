---
title: Descrizione del servizio Archiviazione Exchange Online
ms.author: office365servicedesc
author: pamelaar
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
ms.openlocfilehash: bf2d54bab85725b2d2e334bf17c2b6611a410c59
ms.sourcegitcommit: ab82834030929e1583074b3f5b0b27182746fff4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/19/2021
ms.locfileid: "50901901"
---
# <a name="exchange-online-archiving-service-description"></a>Descrizione del servizio Archiviazione Exchange Online

Archiviazione Microsoft Exchange Online è una soluzione di archiviazione aziendale basata su cloud di Microsoft 365 per le organizzazioni che hanno distribuito Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 e versioni successive) o sottoscrivere determinati piani di Exchange Online o Microsoft365. Archiviazione Exchange Online agevola le attività correlate ad archiviazione, conformità, regolamentazione ed eDiscovery e al tempo stesso semplifica l'infrastruttura locale riducendo i costi e il carico per l'IT.
  
In qualità di servizio online Microsoft, Archiviazione Exchange Online è progettato per soddisfare le esigenze di sicurezza, affidabilità e produttività degli utenti. Per ulteriori informazioni su Microsoft 365, incluse le funzionalità comuni a tutti i servizi online Microsoft, vedere Descrizione dei servizi della piattaforma [Microsoft 365 e Office 365.](../office-365-platform-service-description/office-365-platform-service-description.md)
  
Per acquistare Archiviazione Exchange Online, vedere [Archiviazione Exchange Online per server](https://products.office.com/exchange/microsoft-exchange-online-archiving-email).
  
## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Archiviazione Exchange Online, vedere la tabella di confronto completa [delle sottoscrizioni.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)
  
> [!TIP]
> È possibile esportare, salvare e stampare pagine nelle descrizioni dei servizi. Informazioni su come [esportare i risultati della ricerca contenuto.](https://docs.microsoft.com/office365/securitycompliance/export-search-results) 
  
## <a name="exchange-online-archiving-plans"></a>Piani di sottoscrizione di Archiviazione Exchange Online

Archiviazione Exchange Online è disponibile attraverso i piani di sottoscrizione elencati di seguito.<br><br>
  
| Pianificare | Descrizione |
|:-----|:-----|
|**Archiviazione Exchange Online per Exchange Server** <br/> |Archivio basato su cloud per gli utenti con cassette postali principali in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva).  <br/> Per aggiungere un archivio basato sul cloud a una cassetta postale principale che si trova su un server Exchange locale, è necessario configurare la distribuzione ibrida. Per ulteriori informazioni sulle distribuzioni ibride, [vedere Exchange Server distribuzioni ibride](https://docs.microsoft.com/exchange/exchange-hybrid).  <br/> |
|**Archiviazione Exchange Online per Exchange Server (tramite Enterprise CAL Suite)** <br/> |Archivio basato su cloud per gli utenti con cassette postali principali in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange 2010 (SP2 o versione successiva). Per informazioni dettagliate, vedere [Client Access Licenses and Management Licenses](https://www.microsoft.com/licensing/product-licensing/client-access-license).  <br/> |
|**Archiviazione Exchange Online per Exchange Online** <br/> | Archiviazione basata su cloud e archiviazione sul posto come componente aggiuntivo per i piani<sup>1, 2 seguenti:</sup><br/>  Exchange Online Piano 1  <br/>  Chiosco Exchange Online  <br/>  Microsoft 365 Business Basic  <br/>  Microsoft 365 Business Standard  <br/>  Office 365 Enterprise E1  <br/>  Office 365 Enterprise F3  <br/> Microsoft 365 Enterprise F3<br/> <b>Nota:</b> I piani seguenti includono già l'archiviazione e non richiedono Archiviazione Exchange Online come componente aggiuntivo:<br/>Office 365 Education A1 <br/>Office 365 Education A3 <br/>  Office 365 Education A5 <br/>  Office 365 Enterprise E3 <br/>  Office 365 Enterprise E5 <br/>  Exchange Online, piano 2 <br/> Microsoft 365 Business Premium <br/>Microsoft 365 Enterprise E3 <br/> Microsoft 365 Enterprise E5 <br/>Per informazioni dettagliate sulle funzionalità di archiviazione delle cassette postali di Exchange Online, vedere [Archive features in Archiviazione Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features).           |
   
>[!NOTE]
><sup>1</sup> Per organizzazioni basate solo sul cloud in cui il server Exchange locale non contiene cassette postali, non è necessaria una distribuzione ibrida. Tuttavia, se sono presenti cassette postali locali, è necessaria la distribuzione ibrida.
<br/>
<sup>2</sup> Il piano Exchange Online Piano 1 e Microsoft 365 Apps hanno un limite di dimensione per la cassetta postale e l'archivio. Per ulteriori informazioni, vedere [Limiti di Exchange Online.](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits) Archiviazione Exchange Online per Exchange Online aggiunge un archivio illimitato basato sul cloud e il [Archiviazione sul posto e conservazione per controversia legale](compliance-and-security-features.md#in-place-hold-and-litigation-hold).
  
Per informazioni su tutti i piani di Microsoft 365? Microsoft 365 è disponibile in diversi piani per soddisfare al meglio le esigenze dell'organizzazione. Per informazioni sui diversi piani, incluse le opzioni di piano autonomo e le informazioni sullo spostamento da un piano a un altro, vedere Opzioni del piano di [Office 365.](../office-365-platform-service-description/office-365-plan-options.md)
  
## <a name="requirements"></a>Requisiti

Per utilizzare Archiviazione Exchange Online per Exchange Server, le cassette postali degli utenti devono risiedere Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 o Exchange Server 2010 (SP2 o versione successiva).
  
### <a name="federated-identity-and-single-sign-on"></a>Identità federative e Single Sign-On

Gli amministratori possono utilizzare un approccio Single Sign-On per l'autenticazione con Active Directory locale. A tale scopo, gli amministratori possono configurare Active Directory Federation Services locale, un servizio di Microsoft Windows Server &reg; 2008, per la federazione con Microsoft Federation Gateway. Dopo la configurazione di Active Directory Federation Services, tutti gli utenti le cui identità sono basate sul dominio federato possono utilizzare l'accesso aziendale esistente per eseguire automaticamente l'autenticazione in Office 365.
  
### <a name="user-subscriptions"></a>Sottoscrizioni degli utenti

Ogni utente che accede al servizio Archiviazione Exchange Online deve disporre di una sottoscrizione di Archiviazione Exchange Online. Ogni sottoscrizione dell'archivio di posta elettronica può essere utilizzata per l'archiviazione dei dati di messaggistica di un solo utente.
  
## <a name="unlimited-archive-storage-quota"></a>Quota di spazio di archiviazione illimitata

 La funzionalità di archiviazione illimitata (denominata archiviazione con espansione *automatica)* offre ulteriore spazio di archiviazione nelle cassette postali di archiviazione. Inizialmente, ogni sottoscrittore di Archiviazione Exchange Online riceve 100 GB di spazio nella cassetta postale di archiviazione. Quando l'archiviazione con espansione automatica è attivata, viene aggiunto automaticamente ulteriore spazio di archiviazione quando viene raggiunta la capacità di archiviazione di 100 GB. Nelle distribuzioni ibride di Exchange, l'archiviazione con espansione automatica è supportata solo per le cassette postali di archiviazione basate su cloud quando la cassetta postale dell'utente locale risiede su Exchange Server 2019, Exchange Server 2016 o Exchange Server 2013 (SP1 o versione successiva). Per altre informazioni, vedere [Panoramica dell'archiviazione illimitata](https://docs.microsoft.com/office365/securitycompliance/unlimited-archiving).
  
> [!IMPORTANT]
> Gli amministratori non possono modificare la quota di archiviazione.<br/>
> L'archiviazione con espansione automatica non è supportata per le cassette postali che risiedono Exchange Server 2010.
  
> [!IMPORTANT]
> L'espansione automatica dell'archivio è supportata solo per le cassette postali utilizzate per singoli utenti o cassette postali condivise con un tasso di crescita che non supera *1 &nbsp; GB al giorno.* L'utilizzo dell'inserimento nel journal, delle regole di trasporto e delle regole di inoltro automatico per inviare una copia dei messaggi a Archiviazione Exchange Online a scopo di archiviazione non è consentito. Una cassetta postale di archiviazione di un utente è destinata esclusivamente a quell'utente. Microsoft si riserva il diritto di negare l'archiviazione illimitata nei casi in cui la cassetta postale di archiviazione di un utente viene utilizzata per archiviare i dati di archiviazione per altri utenti o in altri casi di utilizzo inappropriato.
  
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
<sup>3</sup> Per un elenco delle versioni supportate di Microsoft Outlook, vedere [Funzionalità client in Archiviazione Exchange Online](client-features.md). <br/>
<sup>4</sup> Azure Information Protection non è incluso, ma può essere acquistato come componente aggiuntivo separato e abiliterà le funzionalità supportate di Information Rights Management (IRM). Alcune funzionalità di Azure Information Protection richiedono un abbonamento a Microsoft 365 Apps for enterprise, che non è incluso in Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education o Office 365 Enterprise F3. <br/>
<sup>5</sup> Windows Server AD RMS è un server in locale che deve essere acquistato e gestito separatamente per poter abilitare le funzionalità IRM supportate. <br/>
<sup>6</sup> Quando imposta una cassetta postale sull'archiviazione sul posto o sul blocco per controversia legale, la conservazione interessa sia la cassetta postale primaria che quella di archiviazione. 
