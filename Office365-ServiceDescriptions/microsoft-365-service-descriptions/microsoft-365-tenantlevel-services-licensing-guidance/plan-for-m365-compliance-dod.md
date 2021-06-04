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
description: Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546003"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Pianificare la conformità Microsoft 365 - Distribuzion DoD

Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di idoneità di Microsoft 365 Government – DoD e ha applicato e accettato il programma, è possibile ignorare i passaggi 1 e 2 e andare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve Microsoft 365 government - DoD e soddisfi i requisiti di idoneità

L'Microsoft 365 Government - DoD è conforme ai requisiti del governo statunitense per i servizi cloud.

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche di Microsoft 365 Government – DoD:

- Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi Office 365 commerciali da Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Government - DoD è conforme alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

Puoi trovare ulteriori informazioni sull'offerta Microsoft 365 Government - DoD per i clienti del governo statunitense nei piani [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [Office 365 del servizio us government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descrive i vantaggi della piattaforma, che sono centrati sul rispetto dei requisiti di conformità all'interno degli Stati Uniti.

> [!TIP]
> È possibile trasferire gli tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: Rilevante per l'organizzazione **Y/N** e Soddisfa le esigenze dell'organizzazione **Y/N.** È quindi possibile esaminare l'elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali**:<br/>
- *Decidere se Microsoft 365 government - DoD è appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government - DoD è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra diversi Office 365 Government [piani.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Passaggio 2. Candidarsi Microsoft 365 government - DoD

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo di [richiesta per questo servizio.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Passaggio 3. Informazioni Microsoft 365 government - Impostazioni di sicurezza predefinite doD

È consigliabile prendere tempo per esaminare attentamente le impostazioni di sicurezza e di amministrazione prima di modificarle e valutare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto di** decisione: decidere se modificare le impostazioni di sicurezza di *Microsoft 365 Government - DoD predefinite,* risolvendo per prima cosa l'impatto di eventuali modifiche che potrebbero essere apportate.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government – DoD<sup>1</sup>

Per soddisfare i requisiti dei clienti cloud per enti pubblici, esistono alcune differenze tra i piani Microsoft 365 government - DoD e enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli aggiornamenti dei prodotti di conformità più recenti pubblicati Microsoft 365 roadmap.<br><br>

| Area | Funzionalità | Stato DoD |
|------|---------|------------|
| **Protezione delle informazioni** | Client e scanner di etichettatura unificati | Disponibile |
| | Corrispondenza esatta dei dati | Disponibile |
| | Classificazione e etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive for Business | In distribuzione |
| | Classificazione e etichettatura automatiche per le app Office (Word, Excel, PowerPoint, Outlook) tra piattaforme (Web, Windows e Mac) | Disponibile |
| | Classificazione ed etichettatura automatiche per Office client - Mobile | Backlog di progettazione |
| | Classificazione ed etichettatura automatiche per Teams, Microsoft 365 gruppi e SharePoint siti | Disponibile |
| | Etichettatura obbligatoria | Disponibile |
| | Etichettatura manuale della riservatezza nelle app Office (iOS, Android, Windows) | Disponibile |
| | Configurazione dell'etichetta di riservatezza per la protezione solo crittografia Outlook messaggi | In distribuzione |
| **Analisi** | Classificazione dei dati: Panoramica ed Esplora contenuto | In distribuzione |
| | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio | In fase di sviluppo |
| | Analisi: classificatori di machine learning con etichettatura automatica Office app/lato client | In distribuzione |
| **Crittografia** | Basic Office 365 Message Encryption (E3) | Disponibile |
| | Advanced Office 365 Message Encryption (E5) | Disponibile |
| | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente | Disponibile |
| | Chiave cliente per Office 365 | Disponibile |
| | Crittografia a chiave doppia | Disponibile |
| **Prevenzione della perdita dei dati** | Prevenzione della perdita dei dati (DLP) per file e posta elettronica | Disponibile |
| | DLP per Teams conversazioni di chat e canali | Disponibile |
| | DLP: dashboard degli avvisi | In distribuzione |
| | DLP Endpoint | In fase di sviluppo |
| | DLP On-prem | Backlog di progettazione |
| | Pagina Panoramica DLP | In fase di sviluppo |
| **Governance delle informazioni** | Governance delle informazioni: Archiviazione posta elettronica | Disponibile |
| | Governance delle informazioni: blocco di conservazione | Disponibile |
| | Governance delle informazioni: importare PST | Disponibile |
| | Governance delle informazioni: applicare manualmente etichette di conservazione non record | Disponibile |
| | Governance delle informazioni: applicare etichette di conservazione predefinite per SharePoint/OneDrive for Business raccolte, cartelle e set di documenti; Exchange posta in arrivo; e Office 365 gruppi | Disponibile |
| | Governance delle informazioni: applicare una singola etichetta di conservazione predefinita all'intera organizzazione; posizioni o utenti specifici; e automaticamente in base a condizioni specifiche (ad esempio parole chiave o informazioni riservate) | Disponibile |
| | Governance delle informazioni: applicare un'etichetta predefinita per Exchange posta in arrivo | Disponibile |
| | Governance delle informazioni: revisione dell'eliminazione in più fasi | Backlog di progettazione |
| | Governance delle informazioni: criteri di conservazione con classificatori addestrabili | In fase di sviluppo |
| | Governance delle informazioni: criteri di conservazione per Teams chat | In distribuzione |
| | Governance delle informazioni: criteri di conservazione per la Teams delle riunioni | Disponibile |
| | Governance delle informazioni: criteri di conservazione per Teams di canale privato | Backlog di progettazione |
| | Governance delle informazioni: ambiti adattivi per i criteri di conservazione e di etichettatura | In fase di sviluppo |
| | Gestione record: applicare manualmente l'etichetta record | Disponibile |
| | Gestione record: applicare un'etichetta di record predefinita per SharePoint, OneDrive for Business raccolte, cartelle e set di documenti; e Office 365 gruppi | Disponibile |
| | Gestione dei record: criteri di record automatici basati su condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento | Disponibile |
| | Gestione dei record: revisione dell'eliminazione | Disponibile |
| | Gestione dei record: Gestione piano di file | Disponibile |
| | Gestione dei record: prova di eliminazione | Disponibile |
| | Gestione record: controllo delle versioni dei record | Disponibile |
| | Gestione dei record: record normativi | Disponibile |
| | Gestione record: utilizzare la SharePoint Syntex per applicare etichette di record | Backlog di progettazione |
| **Gestione dei rischi insider** | Customer Lockbox | Disponibile |
| | Gestione dei rischi insider: dashboard del caso, Esplora contenuto e modelli di avviso | In distribuzione |
| | Insider Risk Management: inoltrare le indagini per Advanced eDiscovery | In distribuzione |
| | Insider Risk Management: furto di dati da parte di utenti in partenza | In distribuzione |
| | Insider Risk Management: perdite di dati generali | In distribuzione |
| | Insider Risk Management: analizzare gli avvisi di gestione dei rischi insider | In distribuzione |
| | Insider Risk Management: indicatori Office per Teams, siti SharePoint, messaggi di posta elettronica | In distribuzione |
| | Insider Risk Management Activity Explorer | Backlog di progettazione |
| | Insider Risk Management: indicatori dei dispositivi per l'attività Windows 10 Build 1809 e versioni successive | Backlog di progettazione |
| | Insider Risk Management: indicatori per gli avvisi di Microsoft Defender per endpoint | Backlog di progettazione |
| | Insider Risk Management: indicatori per la violazione dei criteri di sicurezza | Backlog di progettazione |
| | Insider Risk Management: modelli di criteri per le perdite di dati da parte di utenti scontenti | Backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per le perdite di dati da parte degli utenti con priorità | Backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per violazioni generali dei criteri di sicurezza | Backlog di progettazione |
| | Gestione dei rischi Insider: modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità, utenti in partenza, utenti scontenti (anteprima) | Backlog di progettazione |
| | Gestione dei rischi Insider: personalizzazione dei criteri | Backlog di progettazione |
| | Gestione dei rischi Insider: esportare gli avvisi | Backlog di progettazione |
| | Insider Risk Management: integrazione Microsoft Teams insider | Backlog di progettazione |
| | Gestione dei rischi insider: gruppi di utenti con priorità | Backlog di progettazione |
| | Conformità delle comunicazioni: creare criteri per i clienti, 3 preconfigurato | Disponibile |
| | Conformità delle comunicazioni: supporto per Teams, Exchange e rimuovere Teams messaggio | Disponibile |
| | Conformità delle comunicazioni: avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione | Disponibile |
| | Conformità delle comunicazioni: inoltrare le indagini per Advanced eDiscovery | Disponibile |
| | Conformità delle comunicazioni: rileva la violazione del codice di condotta ripetuto nel tempo | Disponibile |
| | Conformità delle comunicazioni: supporto per autorizzazioni più granulari | Disponibile |
| | Conformità delle comunicazioni: analizzare Teams chat degli utenti con una cassetta postale locale | Disponibile |
| | Conformità delle comunicazioni: modello conflitto di interesse | Disponibile |
| | Conformità delle comunicazioni: possibilità di ignorare la firma o la dichiarazione di non responsabilità della posta elettronica | In fase di sviluppo |
| | Conformità delle comunicazioni: possibilità di impostare un periodo di conservazione per un criterio di conformità delle comunicazioni | Backlog di progettazione |
| | Conformità delle comunicazioni: rilevare i contenuti per adulti | Backlog di progettazione |
| | Conformità delle comunicazioni: hand-off per la gestione dei rischi insider | In fase di sviluppo |
| | Conformità delle comunicazioni: controllo dell'integrità dei criteri e possibilità di sospendere i criteri | In fase di sviluppo |
| | Conformità alle comunicazioni: supporto di 7 lingue per classificatori di minacce, molestie mirate e volgarità | In fase di sviluppo |
| | Conformità delle comunicazioni: tradurre il contenuto dell'integrità durante l'indagine | In fase di sviluppo |
| | Barriere informative | In distribuzione |
| | Gestione accessi con privilegi | Backlog di progettazione |
| **Individuare & rispondere** | Core eDiscovery: conservazione sul posto | Disponibile |
| | Core eDiscovery: Gestione dei casi | Disponibile |
| | Core eDiscovery: Ricerca | Disponibile |
| | Core eDiscovery: Esportazione | Disponibile |
| | Core eDiscovery: decrittografia RMS | Disponibile |
| | Core eDiscovery: esportazione nativa | Disponibile |
| | Core eDiscovery: Controllo | Disponibile |
| | Core eDiscovery: limiti di conformità per OneDrive for Business | In distribuzione |
| | Advanced eDiscovery: Elaborazione avanzata | Disponibile |
| | Advanced eDiscovery: supporto CJK/Double byte per Advanced eDiscovery | Disponibile |
| | Advanced eDiscovery: mapping tra responsabile e carico di lavoro | Disponibile |
| | Advanced eDiscovery: Comunicazioni di custodia | Disponibile |
| | Advanced eDiscovery: Dashboard | Disponibile |
| | Advanced eDiscovery: Threading della posta elettronica | Disponibile |
| | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di recensioni) | Disponibile |
| | Advanced eDiscovery: Filtro | Disponibile |
| | Advanced eDiscovery: Identificazione quasi duplicata | Disponibile |
| | Advanced eDiscovery: codifica predittiva | Disponibile |
| | Advanced eDiscovery: esportazione elaborata con file di caricamento | Disponibile |
| | Advanced eDiscovery: Redactions | Disponibile |
| | Advanced eDiscovery: Rivedere i set | Disponibile |
| | Advanced eDiscovery: rivedere e annotare | Disponibile |
| | Advanced eDiscovery: report Termini di ricerca | Disponibile |
| | Advanced eDiscovery: supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni) | Disponibile |
| | Advanced eDiscovery: Tagging | Disponibile |
| | Advanced eDiscovery: supporto Teams reazioni | Disponibile |
| | Advanced eDiscovery: report tenant | Disponibile |
| | Advanced eDiscovery: Temi | Disponibile |
| | Advanced eDiscovery: Visualizzatori | Disponibile |
| | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft | Disponibile |
| | Advanced eDiscovery: ottimizzazioni di blocco | In fase di sviluppo |
| | Advanced eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi in SharePoint, OneDrive for Business, Cestino in Core e Advanced eDiscovery | In fase di sviluppo |
| | Advanced eDiscovery: blocco legale per i messaggi Teams canali privati | In fase di sviluppo |
| | Advanced eDiscovery: nuovo modulo di codifica predittiva | In fase di sviluppo |
| | Advanced eDiscovery: inserimento non Office 365 | Backlog di progettazione |
| | Advanced eDiscovery: report tenant | In fase di sviluppo |
| | Audit di base | Disponibile |
| | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed) | Disponibile |
| | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione | Disponibile |
| | Controllo avanzato: conservazione dei registri (1 anno) | Disponibile |
| | Controllo avanzato: eventi di inoltro della posta e invio della posta | Disponibile |
| | Controllo avanzato: disponibilità del Centro sicurezza e conformità | Disponibile |
| | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni) | In fase di sviluppo |
| | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online | Backlog di progettazione |
| **Gestione della conformità** | Microsoft 365 Centro sicurezza e conformità | Disponibile |
| | Microsoft Cloud App Security | In fase di sviluppo |
| | Compliance Manager | Disponibile |
| | Supporto dei caratteri a byte doppio | Disponibile |
| **Ecosistema** | Connettori dati di prima parte: HR | Disponibile |
| | Connettori di dati di prima parte: Instant Bloomberg, Bloomberg Mail, pagine LinkedIn Business, ICE Chat | Backlog di progettazione |
| | Connettori dati di terze parti | Backlog di progettazione |
| | Graph API per Advanced eDiscovery | In fase di sviluppo |
| | Graph API per l'esportazione Teams dati | Backlog di progettazione |

<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
