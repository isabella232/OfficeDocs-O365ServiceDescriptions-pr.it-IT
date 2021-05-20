---
title: Pianificare la conformità Microsoft 365 - Distribuzion DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Questa guida è per i professionisti IT che stanno guidando le distribuzioni di Office 365 in entità del governo federale degli Stati Uniti o altre entità che gestiscono dati soggetti a normative e requisiti governativi, in cui l'uso di Microsoft 365 Government - DoD è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546003"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Pianificare la conformità Microsoft 365 - Distribuzion DoD

Questa guida è per i professionisti IT che stanno guidando le distribuzioni di Office 365 in entità del governo federale degli Stati Uniti o altre entità che gestiscono dati soggetti a normative e requisiti governativi, in cui l'uso di Microsoft 365 Government - DoD è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di idoneità Microsoft 365 Government - DoD e ha richiesto e accettato nel programma, è possibile saltare i passaggi 1 e 2 e passare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione ha bisogno Microsoft 365 governativo - DoD e soddisfa i requisiti di idoneità

L Microsoft 365 Government - DoD è conforme ai requisiti del governo degli Stati Uniti per i servizi cloud.

Oltre a godere delle funzionalità e delle funzionalità di Office 365, le organizzazioni beneficiano delle seguenti funzionalità specifiche per Microsoft 365 Governo - DoD:

- Il contenuto dei clienti dell'organizzazione è logicamente separato dal contenuto dei clienti nei servizi Office 365 commerciali di Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Governo - DoD è conforme alle certificazioni e agli accreditamenti richiesti per i clienti del settore pubblico degli Stati Uniti.

Ulteriori informazioni sull'offerta Microsoft 365 - DoD per i clienti del governo degli Stati Uniti [sono disponibili Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [Office 365 del servizio governativo degli Stati](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) Uniti descrive i vantaggi della piattaforma, che sono in particolare sul soddisfacire i requisiti di conformità negli Stati Uniti.

> [!TIP]
> È possibile trasferire le tabelle di informazioni nella descrizione del servizio in una cartella di lavoro Excel e aggiungere due colonne: **Rilevante per l'organizzazione Y/N e** Soddisfa le esigenze **dell'organizzazione Y/N**. È quindi possibile esaminare questo elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti di decisione**:<br/>
- *Decidere se Microsoft 365 Government - DoD è appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government - DoD è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra una serie [di Office 365 Government piani](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Passaggio 2. Richiedi per Microsoft 365 governo - DoD

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo [di richiesta di questo servizio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Passaggio 3. Informazioni Microsoft 365 governo - Impostazioni di sicurezza predefinite DoD

È consigliabile esaminare attentamente le impostazioni di amministrazione e sicurezza prima di modificarle e considerare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto decisionale:** *decidere se modificare una delle impostazioni di sicurezza predefinite di Microsoft 365 Government - DoD, risolvendo per comprendere prima l'impatto delle eventuali modifiche.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government – DoD<sup>1</sup>

Per soddisfare i requisiti dei nostri clienti cloud governativi, ci sono alcune differenze tra Microsoft 365 government - DoD e piani aziendali. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedi [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli ultimi aggiornamenti dei prodotti di conformità pubblicati sulla Microsoft 365 roadmap.<br><br>

| Area | Funzionalità | Stato DoD |
|------|---------|------------|
| **Protezione delle informazioni** | Client e scanner di etichettatura unificati | disponibile |
| | Corrispondenza esatta dei dati | disponibile |
| | Classificazione ed etichettatura automatica per Exchange Online, SharePoint Online e OneDrive for Business | In distribuzione |
| | Classificazione ed etichettatura automatica per Office di distribuzione (Word, Excel, PowerPoint, Outlook) tra piattaforme (Web, Windows e Mac) | disponibile |
| | Classificazione ed etichettatura automatica per Office clienti - Mobile | Sul backlog di progettazione |
| | Classificazione ed etichettatura automatica per Teams, Microsoft 365 gruppi e SharePoint siti | disponibile |
| | Etichettatura obbligatoria | disponibile |
| | Etichettatura di sensibilità manuale nelle app Office (iOS, Android, Windows) | disponibile |
| | Configurazione dell'etichetta di riservatezza per la protezione solo crittografata Outlook messaggi | In distribuzione |
| **Analisi** | Classificazione dei dati: Panoramica ed Esplora contenuto | In distribuzione |
| | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio | Nello sviluppo |
| | Analisi: classificatori di machine learning con etichettatura automatica Office app/lato client | In distribuzione |
| **Crittografia** | Ricerca Office 365 Message Encryption (E3) | disponibile |
| | Advanced Office 365 Message Encryption (E5) | disponibile |
| | Porta la tua chiave (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente | disponibile |
| | Chiave cliente per Office 365 | disponibile |
| | Crittografia a chiave doppia | disponibile |
| **Prevenzione della perdita dei dati** | Prevenzione della perdita di dati (DLP) per file ed e-mail | disponibile |
| | DLP per Teams chat e conversazioni sul canale | disponibile |
| | DLP: dashboard avvisi | In distribuzione |
| | DLP Endpoint | Nello sviluppo |
| | DLP On-prem | Sul backlog di progettazione |
| | Pagina Panoramica di DLP | Nello sviluppo |
| **Governance delle informazioni** | Governance delle informazioni: Archiviazione della posta elettronica | disponibile |
| | Governance delle informazioni: blocco di conservazione | disponibile |
| | Governance delle informazioni: Importare pst | disponibile |
| | Governance delle informazioni: applicare manualmente etichette di conservazione non record | disponibile |
| | Governance delle informazioni: applicare etichette di conservazione predefinite per SharePoint/OneDrive for Business raccolte, cartelle e set di documenti; Exchange posta in arrivo; e Office 365 gruppi | disponibile |
| | Governance delle informazioni: applicare una singola etichetta di conservazione predefinita all'intera organizzazione; posizioni o utenti specifici; e automaticamente in base a condizioni specifiche (ad esempio, parole chiave o informazioni sensibili) | disponibile |
| | Governance delle informazioni: applicare un'etichetta predefinita per Exchange posta in arrivo | disponibile |
| | Governance delle informazioni: revisione della disposizione in più fasi | Sul backlog di progettazione |
| | Governance delle informazioni: criteri di conservazione con classificatori addestrabili | Nello sviluppo |
| | Governance delle informazioni: criteri di conservazione per Teams chat | In distribuzione |
| | Governance delle informazioni: criteri di conservazione per la registrazione Teams riunione | disponibile |
| | Governance delle informazioni: criteri di conservazione per Teams messaggi di canale privato | Sul backlog di progettazione |
| | Governance delle informazioni: criteri di conservazione ed etichettatura ambiti adattivi | Nello sviluppo |
| | Gestione dei record: applicare manualmente l'etichetta discografica | disponibile |
| | Gestione record: applicare un'etichetta di record predefinita per SharePoint, OneDrive for Business raccolte, cartelle e set di documenti; e Office 365 gruppi | disponibile |
| | Gestione dei record: criteri di registrazione automatici basati su condizioni specifiche (ad esempio, parole chiave o informazioni riservate); e sulla base di un evento | disponibile |
| | Gestione dei record: revisione della disposizione | disponibile |
| | Gestione dei record: Gestione piani di file | disponibile |
| | Gestione dei record: Prova di smaltimento | disponibile |
| | Gestione dei record: controllo delle versioni dei record | disponibile |
| | Gestione dei record: record normativi | disponibile |
| | Gestione dei record: utilizzare SharePoint classificazione Syntex per applicare etichette discografiche | Sul backlog di progettazione |
| **Gestione dei rischi Insider** | Customer Lockbox | disponibile |
| | Gestione dei rischi insider: dashboard dei casi, Esplora contenuti e modelli di avviso | In distribuzione |
| | Gestione dei rischi insider: escalation per le indagini per Advanced eDiscovery | In distribuzione |
| | Insider Risk Management: furto di dati da parte degli utenti in partenza | In distribuzione |
| | Insider Risk Management: perdite generali di dati | In distribuzione |
| | Gestione dei rischi insider: esaminare gli avvisi di gestione dei rischi insider | In distribuzione |
| | Gestione del rischio insider: indicatori Office per Teams, SharePoint, messaggi di posta elettronica | In distribuzione |
| | Esplora attività di gestione dei rischi insider | Sul backlog di progettazione |
| | Gestione del rischio insider: indicatori dei dispositivi per l'attività Windows 10 Build 1809 e superiore | Sul backlog di progettazione |
| | Gestione dei rischi insider: indicatori per Microsoft Defender per gli avvisi degli endpoint | Sul backlog di progettazione |
| | Gestione del rischio insider: indicatori per la violazione dei criteri di sicurezza | Sul backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per le perdite di dati da parte di utenti scontenti | Sul backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per le perdite di dati da parte degli utenti prioritari | Sul backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per violazioni generali dei criteri di sicurezza | Sul backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per violazioni dei criteri di sicurezza da parte di utenti prioritari, utenti in partenza, utenti scontenti (anteprima) | Sul backlog di progettazione |
| | Gestione dei rischi insider: personalizzazione dei criteri | Sul backlog di progettazione |
| | Gestione dei rischi insider: avvisi di esportazione | Sul backlog di progettazione |
| | Insider Risk Management: integrazione Microsoft Teams lavoro | Sul backlog di progettazione |
| | Gestione dei rischi insider: gruppi di utenti prioritari | Sul backlog di progettazione |
| | Conformità alle comunicazioni: creare criteri cliente, 3 preconfigurati | disponibile |
| | Conformità comunicazione: supporto per Teams, Exchange e rimuovere Teams messaggio | disponibile |
| | Conformità alle comunicazioni: avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione | disponibile |
| | Conformità comunicazione: escalation per l'indagine per Advanced eDiscovery | disponibile |
| | Conformità alle comunicazioni: rileva la violazione del codice di condotta ripetuta nel tempo | disponibile |
| | Conformità alle comunicazioni: supporto per autorizzazioni più granulari | disponibile |
| | Conformità alle comunicazioni: analizzare Teams dati di chat degli utenti con cassetta postale on-prem | disponibile |
| | Conformità alla comunicazione: modello conflitto di interessi | disponibile |
| | Conformità alle comunicazioni: possibilità di ignorare la firma o la dichiarazione di non responsabilità | Nello sviluppo |
| | Conformità comunicazione: possibilità di impostare un periodo di conservazione per un criterio di conformità delle comunicazioni | Sul backlog di progettazione |
| | Conformità alle comunicazioni: rileva contenuti per adulti | Sul backlog di progettazione |
| | Conformità alle comunicazioni: passaggio di mano per la gestione dei rischi insider | Nello sviluppo |
| | Conformità alla comunicazione: controllo dell'integrità dei criteri e possibilità di sospendere i criteri | Nello sviluppo |
| | Conformità alla comunicazione: supporta 7 lingue per classificatori di minacce, molestie mirate e volgarità | Nello sviluppo |
| | Conformità alle comunicazioni: tradurre il contenuto sanitario durante l'indagine | Nello sviluppo |
| | Barriere informative | In distribuzione |
| | Gestione accessi con privilegi | Sul backlog di progettazione |
| **Scopri & rispondi** | EDiscovery principale: conservazione sul posto | disponibile |
| | EDiscovery principale: gestione dei casi | disponibile |
| | EDiscovery principale: Ricerca | disponibile |
| | EDiscovery principale: Esportare | disponibile |
| | EDiscovery principale: decrittografia RMS | disponibile |
| | EDiscovery principale: esportazione nativa | disponibile |
| | EDiscovery principale: controllo | disponibile |
| | EDiscovery principale: limiti di conformità per i OneDrive for Business | In distribuzione |
| | Advanced eDiscovery: Elaborazione avanzata | disponibile |
| | Advanced eDiscovery: supporto CJK/doppio byte per Advanced eDiscovery | disponibile |
| | Advanced eDiscovery: Custode del mapping del carico di lavoro | disponibile |
| | Advanced eDiscovery: Comunicazioni custodian | disponibile |
| | Advanced eDiscovery: Dashboard | disponibile |
| | Advanced eDiscovery: Threading della posta elettronica | disponibile |
| | Advanced eDiscovery: Esporta (download, esportazione, aggiunta a un altro set di revisione) | disponibile |
| | Advanced eDiscovery: Filtraggio | disponibile |
| | Advanced eDiscovery: Identificazione quasi duplicata | disponibile |
| | Advanced eDiscovery: Codifica predittiva | disponibile |
| | Advanced eDiscovery: esportazione elaborata con file di caricamento | disponibile |
| | Advanced eDiscovery: Redazioni | disponibile |
| | Advanced eDiscovery: set di recensioni | disponibile |
| | Advanced eDiscovery: Rivedere e annotare | disponibile |
| | Advanced eDiscovery: Rapporto sui termini di ricerca | disponibile |
| | Advanced eDiscovery: Supporto di contenuti collegati da OneDrive e SharePoint Online (allegati moderni) | disponibile |
| | Advanced eDiscovery: Tagging | disponibile |
| | Advanced eDiscovery: Teams reazioni di sostegno | disponibile |
| | Advanced eDiscovery: rapporti tenant | disponibile |
| | Advanced eDiscovery: Temi | disponibile |
| | Advanced eDiscovery: Spettatori | disponibile |
| | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft | disponibile |
| | Advanced eDiscovery: Ottimizzazioni di attesa | Nello sviluppo |
| | Advanced eDiscovery: Microsoft Compliance Center ha ampliato il supporto per la ricerca e l'esportazione di elementi in SharePoint, OneDrive for Business, Cestino in Core e Advanced eDiscovery | Nello sviluppo |
| | Advanced eDiscovery: Trattenere per i Teams dei canali privati | Nello sviluppo |
| | Advanced eDiscovery: nuovo modulo di codifica predittiva | Nello sviluppo |
| | Advanced eDiscovery: Ingestione Office 365 non Office 365 non | Sul backlog di progettazione |
| | Advanced eDiscovery: rapporti tenant | Nello sviluppo |
| | Audit di base | disponibile |
| | Controllo avanzato: accesso a eventi cruciali (ad esempio, postaielementiaccessi) | disponibile |
| | Controllo avanzato: maggiore larghezza di banda all'API dell'attività di gestione | disponibile |
| | Controllo avanzato: conservazione del registro (1 anno) | disponibile |
| | Controllo avanzato: eventi di inoltro della posta e invio della posta | disponibile |
| | Controllo avanzato: disponibilità del Centro sicurezza e conformità | disponibile |
| | Controllo avanzato: conservazione a lungo termine nei registri di controllo (10 anni) | Nello sviluppo |
| | Controllo avanzato: ricerca di eventi di termine in Exchange Online e SharePoint Online | Sul backlog di progettazione |
| **Gestione della conformità** | Microsoft 365 Centro sicurezza e conformità | disponibile |
| | Microsoft Cloud App Security | Nello sviluppo |
| | Compliance Manager | disponibile |
| | Supporto di caratteri a byte doppio | disponibile |
| **ecosistema** | Connettori dati di prima parte: HR | disponibile |
| | Connettori dati di prima parte: Instant Bloomberg, Bloomberg Mail, LinkedIn Business pages, ICE Chat | Sul backlog di progettazione |
| | Connettori dati di terze parti | Sul backlog di progettazione |
| | Graph API per Advanced eDiscovery | Nello sviluppo |
| | Graph API per l Teams di esportazione | Sul backlog di progettazione |

<sup>1 Lo</sup> stato identificato è soggetto a modifiche man mano che i piani e le priorità del progetto vengono rivalutati.<br/>

**Punto decisionale:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
