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
ms.openlocfilehash: 4d8e4b7600abe8b41baa94462f4e8dfbebf8b277
ms.sourcegitcommit: e3b492f18443921ed33776b2db51b888bd3bc230
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/30/2021
ms.locfileid: "58702288"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Pianificare la conformità Microsoft 365 - Distribuzion DoD

Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di idoneità di Microsoft 365 Government – DoD e ha applicato e accettato il programma, è possibile ignorare i passaggi 1 e 2 e andare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve Microsoft 365 government - DoD e soddisfi i requisiti di idoneità

L Microsoft 365 Government - DoD è conforme ai requisiti del governo statunitense per i servizi cloud.

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche di Microsoft 365 Government – DoD:

- I contenuti dei clienti dell'organizzazione sono logicamente separati dal contenuto dei clienti nei servizi Office 365 commerciali da Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Government - DoD è conforme alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

Puoi trovare ulteriori informazioni sull'offerta Microsoft 365 Government - DoD per i clienti del governo degli Stati Uniti all'indirizzo Office 365 Government [piani,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [Office 365 del servizio us government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descrive i vantaggi della piattaforma, centrati sul rispetto dei requisiti di conformità all'interno degli Stati Uniti.

> [!TIP]
> È possibile trasferire gli tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: Rilevante per l'organizzazione **Y/N** e Soddisfa le esigenze dell'organizzazione **Y/N.** È quindi possibile esaminare l'elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali**:<br/>
- *Decidere se Microsoft 365 government - DoD è appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government - DoD è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra diversi Office 365 Government [piani.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Passaggio 2. Candidarsi Microsoft 365 government - DoD

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo di [richiesta per questo servizio.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Passaggio 3. Informazioni Microsoft 365 per enti pubblici - Impostazioni di sicurezza predefinite doD

È consigliabile prendere tempo per esaminare attentamente le impostazioni di sicurezza e di amministratore prima di modificarle e valutare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto di** decisione: decidere se modificare le impostazioni di sicurezza predefinite di *Microsoft 365 Government - DoD,* risolvendo per prima cosa l'impatto di eventuali modifiche che potrebbero essere apportate.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government – DoD<sup>1</sup>

Per soddisfare i requisiti dei clienti cloud per enti pubblici, esistono alcune differenze tra i piani Microsoft 365 government - DoD e enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli aggiornamenti dei prodotti di conformità più recenti pubblicati Microsoft 365 roadmap.<br><br>

| Area  | Funzionalità  | Stato DoD  |
|-------|----------|-------------|
| **Protezione delle informazioni**  | | |
| Tipi di informazioni sensibili  | Corrispondenza esatta dei dati  | Disponibile  |
| Etichettatura di riservatezza  | Classificazione e etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive for Business  | Disponibile |
| | Classificazione e etichettatura automatiche per Office app (Word, Excel, PowerPoint, Outlook) tra piattaforme (Web, Windows e Mac)  | Disponibile  |
| | Classificazione ed etichettatura automatiche per Office client - Mobile  | Backlog di progettazione  |
| | Classificazione e etichettatura automatiche per Teams, Microsoft 365 e SharePoint siti  | Disponibile  |
| | Etichettatura obbligatoria  | Disponibile  |
| | Etichettatura manuale della riservatezza nelle app Office (iOS, Android, Windows)  | Disponibile  |
| | Configurazione dell'etichetta di riservatezza per la protezione solo crittografia Outlook messaggi  | Disponibile  |
| | Client e scanner di etichettatura unificati  | Disponibile  |
| Analisi  | Classificazione dei dati: Panoramica ed Esplora contenuto  | In distribuzione  |
| | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio  | In fase di sviluppo  |
| | Analisi: classificatori di machine learning con etichettatura automatica Office app/lato client  | In fase di sviluppo |
| Crittografia  | Basic Office 365 Message Encryption (E3)  | Disponibile  |
| | Advanced Office 365 Message Encryption (E5)  | Disponibile  |
| | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente  | Disponibile  |
| | Chiave cliente per Office 365  | Disponibile  |
| | Chiave cliente per la Microsoft 365 multi-carico di lavoro | In fase di sviluppo  |
| | Customer Key per SharePoint Online e OneDrive for Business | Disponibile |
| | Crittografia a chiave doppia  | Disponibile  |
| Prevenzione della perdita di dati  | Prevenzione della perdita dei dati (DLP) per file e posta elettronica  | Disponibile  |
| | DLP: dashboard degli avvisi e esperienza di avviso  | Disponibile  |
| | DLP per Teams conversazioni di chat e canali  | Disponibile  |
| | Endpoint DLP (anteprima pubblica)  | Anteprima pubblica |
| | Pagina Panoramica DLP  | In distribuzione  |
| **Governance delle informazioni**  | | |
| Governance delle informazioni  | Governance delle informazioni: ambiti adattivi per i criteri di conservazione ed etichettatura | Backlog di progettazione  |
| | Governance delle informazioni: applicare un'etichetta predefinita per Exchange posta in arrivo  | Disponibile  |
| | Governance delle informazioni: Archiviazione della posta elettronica  | Disponibile  |
| | Governance delle informazioni: importare PST  | Disponibile  |
| | Governance delle informazioni: blocco di conservazione  | Disponibile  |
| | Governance delle informazioni: criteri di conservazione con classificatori addestrabili  | In fase di sviluppo  |
| | Governance delle informazioni: criteri di conservazione per Teams chat  | Disponibile  |
| | Governance delle informazioni: criteri di conservazione per la Teams delle riunioni  | Disponibile  |
| | Governance delle informazioni: criteri di conservazione per Teams di canale privato  | In fase di sviluppo  |
| | Governance delle informazioni: ambiti adattivi per i criteri di conservazione e di etichettatura  | In fase di sviluppo  |
| Gestione record  | Gestione record: applicare manualmente l'etichetta record  | Disponibile  |
| | Gestione record: applicare un'etichetta record predefinita per SharePoint, OneDrive for Business raccolte, cartelle e set di documenti; e Office 365 gruppi  | Disponibile  |
| | Gestione dei record: criteri di record automatici basati su condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento  | Disponibile  |
| | Gestione dei record: revisione dell'eliminazione  | Disponibile  |
| | Gestione dei record: Gestione piano di file  | Disponibile  |
| | Gestione dei record: revisione dell'eliminazione in più fasi  | In fase di sviluppo  |
| | Gestione dei record: conservazione e etichettatura automatica degli allegati cloud  | In fase di sviluppo  |
| | Gestione dei record: prova di eliminazione  | Disponibile  |
| | Gestione record: controllo delle versioni dei record  | Disponibile  |
| | Gestione dei record: record normativi  | Disponibile  |
| | Gestione record: utilizzare la SharePoint Syntex per applicare etichette di record  | Backlog di progettazione  |
| **Gestione dei rischi**  | | |
| Gestione dei rischi  | Customer Lockbox  | Disponibile  |
| Conformità delle comunicazioni  | Conformità delle comunicazioni: possibilità di impostare un periodo di conservazione per un criterio di conformità della comunicazione (anteprima pubblica)  | Backlog di progettazione  |
| | Conformità delle comunicazioni: avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione  | Disponibile  |
| | Conformità delle comunicazioni: analizzare Teams chat degli utenti con una cassetta postale locale  | Disponibile  |
| | Conformità delle comunicazioni: modello conflitto di interesse  | Disponibile  |
| | Conformità delle comunicazioni: creare criteri per i clienti, 3 preconfigurato  | Disponibile  |
| | Conformità delle comunicazioni: rilevare i contenuti per adulti  | Backlog di progettazione  |
| | Conformità delle comunicazioni: rileva la violazione del codice di condotta ripetuto nel tempo  | Disponibile  |
| | Conformità delle comunicazioni: inoltrare le indagini per Advanced eDiscovery  | Disponibile  |
| | Conformità alle comunicazioni: sfruttare il riconoscimento ottico dei caratteri (OCR) per estrarre e valutare i messaggi  | Disponibile  |
| | Conformità delle comunicazioni: Microsoft Teams integrazione  | In fase di sviluppo  |
| | Conformità delle comunicazioni: controllo dell'integrità dei criteri e possibilità di sospendere i criteri  | In fase di sviluppo  |
| | Conformità delle comunicazioni: Power Automate integrazione  | Backlog di progettazione  |
| | Conformità delle comunicazioni: tipi di informazioni riservate per report percorso  | In fase di sviluppo  |
| | Conformità delle comunicazioni: supporto per Teams, Exchange e rimuovere Teams messaggio  | Disponibile  |
| | Conformità delle comunicazioni: supporto per autorizzazioni più granulari  | Disponibile  |
| | Conformità alle comunicazioni: supporto di 7 lingue per classificatori di minacce, molestie mirate e volgarità  | Disponibile  |
| | Conformità delle comunicazioni: tradurre il contenuto dell'integrità durante l'indagine  | In fase di sviluppo  |
| Ostacoli alle informazioni  | Ostacoli alle informazioni  | In distribuzione  |
| Gestione dei rischi Insider  | Insider Risk Management: Log di controllo  | Anteprima pubblica  |
| | Insider Risk Management: Case Dashboard  | Disponibile  |
| | Gestione dei rischi insider: dati evasi in Esplora attività  | Anteprima pubblica  |
| | Gestione dei rischi Insider: i dati sono stati evasi in Esplora contenuto  | In fase di sviluppo  |
| | Insider Risk Management: furto di dati da parte di utenti in partenza  | Disponibile  |
| | Gestione dei rischi insider: indicatori del dispositivo per l'attività Windows 10 endpoint  | In fase di sviluppo  |
| | Gestione dei rischi insider: escalation per Advanced eDiscovery  | Disponibile  |
| | Gestione dei rischi Insider: esportare gli avvisi  | Anteprima pubblica  |
| | Insider Risk Management: perdite di dati generali  | Disponibile  |
| | Insider Risk Management: supporto intelligente per le impostazioni del dominio in Insider Risk Management  | Anteprima pubblica  |
| | Insider Risk Management: indicatori per gli avvisi di Microsoft Defender per endpoint  | Backlog di progettazione  |
| | Insider Risk Management: indicatori per la violazione dei criteri di sicurezza  | In fase di sviluppo  |
| | Insider Risk Management: indicatori per l'attività Windows 10 endpoint | Anteprima pubblica  |
| | Insider Risk Management: analizzare gli avvisi di gestione dei rischi insider  | Disponibile  |
| | Insider Risk Management: Microsoft Teams e Power Automate integrazione  | In fase di sviluppo  |
| | Gestione dei rischi insider: il supporto dei trigger nativi per l Azure Active Directory elizione dell'account | Anteprima pubblica  |
| | Gestione dei rischi Insider: modelli di avviso  | Disponibile  |
| | Insider Risk Management: indicatori Office per Teams, siti SharePoint, messaggi di posta elettronica  | Disponibile  |
| | Insider Risk Management: modelli di criteri per le perdite di dati da parte di utenti scontenti  | Backlog di progettazione  |
| | Gestione dei rischi insider: modelli di criteri per le perdite di dati da parte degli utenti con priorità  | Anteprima pubblica  |
| | Insider Risk Management: modelli di criteri per violazioni generali dei criteri di sicurezza  | Backlog di progettazione  |
| | Gestione dei rischi insider: modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità, utenti in partenza, utenti scontenti (anteprima)  | Backlog di progettazione  |
| | Gestione dei rischi insider: personalizzazione dei criteri, controllo dell'integrità dei criteri e creazione guidata dei criteri avanzata  | Anteprima pubblica  |
| | Gestione dei rischi insider: gruppi di utenti con priorità  | Anteprima pubblica  |
| | Insider Risk Management: supportare i trigger nativi per Azure Active Directory'account | Anteprima pubblica  |
| | Insider Risk Management: audit trail "Watcher" | Anteprima pubblica  |
| **Individuare & rispondere**  | | |
| eDiscovery | Core eDiscovery: Controllo  | Disponibile  |
| | Core eDiscovery: Gestione dei casi  | Disponibile  |
| | Core eDiscovery: limiti di conformità in OneDrive for Business  | Disponibile  |
| | Core eDiscovery: Esportazione  | Disponibile  |
| | Core eDiscovery: conservazione sul posto  | Disponibile  |
| | Core eDiscovery: esportazione nativa  | Disponibile  |
| | Core eDiscovery: decrittografia RMS  | Disponibile  |
| | Core eDiscovery: Ricerca  | Disponibile  |
| | Advanced eDiscovery: Elaborazione avanzata  | Disponibile  |
| | Advanced eDiscovery: mapping tra responsabile e carico di lavoro  | Disponibile  |
| | Advanced eDiscovery: Comunicazioni di custodia  | Disponibile  |
| | Advanced eDiscovery: Dashboard  | Disponibile  |
| | Advanced eDiscovery: funzionalità di eliminazione dei dati per Microsoft Teams  | Backlog di progettazione  |
| | Advanced eDiscovery: ricerca per indicizzazione/indicizzazione approfondita  | Disponibile  |
| | Advanced eDiscovery: supporto a byte doppio per cinese, giapponese e coreano  | Disponibile  |
| | Advanced eDiscovery: Threading della posta elettronica  | Disponibile  |
| | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di recensioni)  | Disponibile  |
| | Advanced eDiscovery: Filtro  | Disponibile  |
| | Advanced eDiscovery: ottimizzazioni del blocco  | In fase di sviluppo  |
| | Advanced eDiscovery: blocco legale per i messaggi Teams canali privati  | In fase di sviluppo  |
| | Advanced eDiscovery: il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi in SharePoint, OneDrive for Business, Cestino in Core e Advanced eDiscovery  | In fase di sviluppo  |
| | Advanced eDiscovery: identificazione quasi duplicata  | Disponibile  |
| | Advanced eDiscovery: nuovo modulo di codifica predittiva  | In fase di sviluppo  |
| | Advanced eDiscovery: origini dati non di custodia  | Disponibile  |
| | Advanced eDiscovery: inserimento Office 365 non Office 365  | Backlog di progettazione  |
| | Advanced eDiscovery: codifica predittiva  | Disponibile  |
| | Advanced eDiscovery: esportazione elaborata con file di caricamento  | Disponibile  |
| | Advanced eDiscovery: Redactions  | Disponibile  |
| | Advanced eDiscovery: rivedere i set  | Disponibile  |
| | Advanced eDiscovery: esaminare i dati (dati di query, smart tag, dashboard) e annotare (redact)  | Disponibile  |
| | Advanced eDiscovery: report termini di ricerca  | Disponibile  |
| | Advanced eDiscovery: Supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni)  | Disponibile  |
| | Advanced eDiscovery: supporto Teams reazioni  | Backlog di progettazione  |
| | Advanced eDiscovery: Tagging  | Disponibile  |
| | Advanced eDiscovery: report tenant  | Disponibile  |
| | Advanced eDiscovery: Temi  | Disponibile  |
| | Advanced eDiscovery: Visualizzatori  | Disponibile  |
| | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft  | Disponibile  |
| Audit  | Audit di base  | Disponibile  |
| | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)  | Disponibile  |
| | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione  | Disponibile  |
| | Controllo avanzato: conservazione dei registri (1 anno)  | Disponibile  |
| | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni)  | In distribuzione  |
| | Controllo avanzato: eventi di inoltro della posta e invio della posta  | Disponibile  |
| | Controllo avanzato: disponibilità del Centro sicurezza e conformità  | Disponibile  |
| | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online  | In distribuzione  |
| | Controllo avanzato: Teams reazioni ai messaggi  | Backlog di progettazione  |
| **Gestione della conformità** | | |
| Gestione della conformità  | Centro conformità Microsoft 365  | Disponibile  |
| | Microsoft Cloud App Security  | Disponibile  |
| | Compliance Manager  | Disponibile  |
| | Supporto dei caratteri a byte doppio  | Disponibile  |
| **Ecosistema** | | |
| Ecosistema  | Connettori dati di prima parte: HR  | Disponibile  |
| | Connettori di dati di prima parte: Instant Bloomberg, Bloomberg Mail, pagine LinkedIn Business, ICE Chat  | In fase di sviluppo  |
| | Graph API per Advanced eDiscovery  | Backlog di progettazione  |

<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
