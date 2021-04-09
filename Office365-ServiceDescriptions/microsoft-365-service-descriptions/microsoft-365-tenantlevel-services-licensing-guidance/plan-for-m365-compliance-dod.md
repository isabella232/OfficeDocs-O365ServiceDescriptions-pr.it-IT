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
description: Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, in cui l'uso di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: 74907afc24dd468111e3f530dc316346784b2996
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652620"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Pianificare la conformità Microsoft 365 - Distribuzion DoD

Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, in cui l'uso di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di idoneità di Microsoft 365 Government – DoD e ha applicato e accettato il programma, è possibile ignorare i passaggi 1 e 2 e andare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione necessita di Microsoft 365 Government - DoD e soddisfa i requisiti di idoneità

L'ambiente Microsoft 365 Government - DoD è conforme ai requisiti del governo statunitense per i servizi cloud.

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche di Microsoft 365 Government – DoD:

- Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi commerciali di Office 365 da Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Government - DoD è conforme alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

È possibile trovare ulteriori informazioni sull'offerta Microsoft 365 Government - DoD per i clienti del governo degli Stati Uniti nei piani di [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [descrizione del servizio Office 365 US Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descrive i vantaggi della piattaforma, che sono centrati sulla conformità dei requisiti all'interno degli Stati Uniti.

> [!TIP]
> È possibile trasferire gli tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: Rilevante per l'organizzazione **Y/N** e Soddisfa le esigenze dell'organizzazione **Y/N.** È quindi possibile esaminare l'elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali**:<br/>
- *Decidere se Microsoft 365 Government - DoD è appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government - DoD è disponibile solo negli Stati Uniti. I clienti non statunitensi possono scegliere tra diversi piani di [Office 365 Government.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Passaggio 2. Richiedere Microsoft 365 Government - DoD

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo di [richiesta per questo servizio.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Passaggio 3. Informazioni su Microsoft 365 Government - Impostazioni di sicurezza predefinite doD

È consigliabile prendere tempo per esaminare attentamente le impostazioni di sicurezza e di amministrazione prima di modificarle e valutare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto di** decisione: decidere se modificare le impostazioni di sicurezza predefinite di *Microsoft 365 Government - DoD,* risolvendo per prima cosa l'impatto di eventuali modifiche apportate.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government – DoD<sup>1</sup>

Per soddisfare i requisiti dei clienti cloud per enti pubblici, esistono alcune differenze tra i piani Microsoft 365 Government - DoD e Enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli ultimi aggiornamenti dei prodotti di conformità pubblicati sulla roadmap di Microsoft 365.<br><br>

| Area                                    | Funzionalità                                         | Stato GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protezione delle informazioni**              | Client e scanner di etichettatura unificati         | Disponibile              |
|                                         | Corrispondenza esatta dei dati          | Disponibile               |
|                                         | Classificazione ed etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive                      | Distribuzione              |
|                                         | Classificazione ed etichettatura automatiche per le app di Office (Word, Excel, PowerPoint, Outlook) su più piattaforme (Web, Android, iOS, Windows e Mac)            | In fase di sviluppo |
|                                         | Classificazione ed etichettatura automatiche per dispositivi mobili                                       | Backlog di progettazione              |
|                                         | Classificazione ed etichettatura automatiche per Teams                            | Backlog di progettazione |
|                                         | Classificazione dei dati: Panoramica ed Esplora contenuto                            | In fase di sviluppo |
|                                         | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio                           | Backlog di progettazione  |
|                                         | Analisi: classificatori di machine learning con etichettatura automatica sul lato client/app di Office                           | Backlog di progettazione  |
|                                         | Crittografia dei messaggi di Office 365 di base (E3)                            | Disponibile              |
|                                         | Crittografia avanzata dei messaggi di Office 365 (E5)  | Disponibile              |
|                                         | Chiave cliente per Office 365    | Disponibile |
|                                         | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente                            | Disponibile |
|                                         | Mantenere la propria chiave (HYOK) che si estende su Azure Information Protection e Active Directory (AD) Rights Management per scenari altamente regolamentati (Anteprima)                         | Disponibile |
|                                         | Crittografia a chiave doppia                           | Distribuzione |
|                                         | Prevenzione della perdita dei dati (DLP) per file e posta elettronica         | Disponibile |
|                                         | DLP per le conversazioni di chat e canali di Teams         | Backlog di progettazione |
|                                         | Corrispondenza esatta dei dati DLP         | Backlog di progettazione |
|                                         | DLP Endpoint | Backlog di progettazione |
| **Governance delle informazioni** | Governance delle informazioni: Archiviazione posta elettronica                                       | Disponibile              |
|                                         | Governance delle informazioni: blocco di conservazione          | Disponibile              |
|                                         | Governance delle informazioni: importare PST                      | Disponibile              |
|                                         | Governance delle informazioni: etichette di conservazione manuali non record            | Disponibile |
|                                         | Governance delle informazioni: etichette di conservazione predefinite per raccolte, cartelle e set di documenti di SharePoint/OneDrive for Business; Posta in arrivo di Exchange; e Gruppi di Office 365 | Disponibile              |
|                                         | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; posizioni o utenti specifici; e automaticamente in base a condizioni specifiche (ad esempio parole chiave o informazioni riservate)                                       | Disponibile              |
|                                         | Governance delle informazioni: criteri di conservazione con classificatori addestrabili                            | Backlog di progettazione |
|                                         | Governance delle informazioni: criteri di conservazione per la registrazione delle riunioni di Teams                            | Backlog di progettazione |
|                                         | Governance delle informazioni: criteri di conservazione per Yammer e Teams                           | Backlog di progettazione              |
|                                         | Gestione dei record: classificazione manuale per le etichette di record                              | Disponibile              |
|                                         | Gestione dei record: etichette di record predefinite per raccolte, cartelle e set di documenti di SharePoint, OneDrive for Business; e gruppi di Office 365                            | Disponibile              |
|                                         | Gestione dei record: criteri di record automatici basati su condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento  | Disponibile              |
|                                         | Gestione dei record: revisione dell'eliminazione    | Disponibile |
|                                         | Gestione dei record: Gestione piano di file                            | Disponibile |
|                                         | Gestione dei record: prova di eliminazione                         | Disponibile |
|                                         | Gestione dei record: record normativi | Backlog di progettazione |
|                                         | Gestione dei record: revisione dell'eliminazione in più fasi | Backlog di progettazione |
|                                         | Gestione record: utilizzare la classificazione Syntex di SharePoint per applicare etichette di record         | Backlog di progettazione |
| **Gestione dei rischi Insider**             | Customer Lockbox                                | Disponibile            |
|                                         | Insider Risk Management: indicatori di Office per Teams, siti di SharePoint, messaggi di posta elettronica                         | Backlog di progettazione |
|                                         | Insider Risk Management: furto di dati da parte di utenti in partenza                        | Backlog di progettazione |
|                                         | Insider Risk Management: perdite di dati generali                                | Backlog di progettazione              |
|                                         | Insider Risk Management: analizzare gli avvisi di gestione dei rischi insider                                   | Backlog di progettazione              |
|                                         | Gestione dei rischi insider: dashboard del caso, Esplora contenuto e modelli di avviso | Backlog di progettazione |
|                                         | Insider Risk Management: escalation per l'indagine per Advanced eDiscovery |Backlog di progettazione|
|                                         | Gestione dei rischi Insider: indicatori del dispositivo per l'attività in Windows 10 Build 1809 e versioni successive |Backlog di progettazione|
|                                         | Insider Risk Management: indicatori per la violazione dei criteri di sicurezza (anteprima) |Backlog di progettazione|
|                                         | Insider Risk Management: indicatori per gli avvisi di Microsoft Defender for Endpoint (anteprima) |Backlog di progettazione|
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte degli utenti con priorità (anteprima) | Backlog di progettazione |
|                                         | Insider Risk Management: modelli di criteri per le perdite di dati da parte di utenti scontenti (anteprima) | Backlog di progettazione |
|                                         | Insider Risk Management: modelli di criteri per violazioni generali dei criteri di sicurezza (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi Insider: modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità, utenti in partenza, utenti scontenti (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi Insider: personalizzazione dei criteri (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi Insider: esportare gli avvisi (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi insider: gruppi di utenti con priorità (anteprima) | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): creare criteri per i clienti, 3 preconfigurato  | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. Criteri di supervisione): supporto per Teams, Exchange e rimozione del messaggio di Teams | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione | Backlog di progettazione  |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): escalation per l'indagine per Advanced eDiscovery | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): rilevare i contenuti per adulti | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (criteri di supervisione incl.): rileva la violazione del codice di condotta ripetuto nel tempo | Distribuzione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): supporto per autorizzazioni più granulari | Distribuzione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): analizzare i dati di chat di Teams degli utenti con una cassetta postale locale | Distribuzione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): modello conflitto di interesse | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): possibilità di ignorare la firma di posta elettronica o la dichiarazione di non responsabilità | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): hand-off per la gestione dei rischi insider | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): controllo dell'integrità dei criteri e capacità di sospendere i criteri | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): tradurre il contenuto di integrità durante l'indagine | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): rilevamento di burnout e di morte | Backlog di progettazione |
|                                         | Barriere informative | Backlog di progettazione |
|                                         | Gestione accessi con privilegi                    | Backlog di progettazione |
| **Individuare & rispondere**                  | Core eDiscovery: conservazione sul posto                            | Disponibile              |
|                                         | Core eDiscovery: Gestione dei casi                                 | Disponibile              |
|                                         | Core eDiscovery: Ricerca                                          | Disponibile              |
|                                         | Core eDiscovery: Esportazione                                          | Disponibile              |
|                                         | Core eDiscovery: decrittografia RMS                                  | Disponibile              |
|                                         | Core eDiscovery: esportazione nativa                                   | Disponibile              |
|                                         | Core eDiscovery: Controllo                                        | Disponibile              |
|                                         | Advanced eDiscovery: Elaborazione avanzata                                 | Distribuzione |
|                                         | Advanced eDiscovery: mapping tra responsabile e carico di lavoro                                 | Distribuzione |
|                                         | Advanced eDiscovery: Comunicazioni di custodia                                 | Distribuzione |
|                                         | Advanced eDiscovery: Dashboard                   | Distribuzione |
|                                         | Advanced eDiscovery: Threading della posta elettronica                                          | Distribuzione |
|                                         | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di recensioni)                               | Distribuzione |
|                                         | Advanced eDiscovery: Filtro                 | Distribuzione |
|                                         | Advanced eDiscovery: blocco legale per i messaggi di canali privati di Teams                                         | Distribuzione |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                                         | Distribuzione |
|                                         | Advanced eDiscovery: inserimento non di Office 365                                      | Distribuzione |
|                                         | Advanced eDiscovery: codifica predittiva                                       | Distribuzione |
|                                         | Advanced eDiscovery: esportazione elaborata con file di caricamento                   | Distribuzione |
|                                         | Advanced eDiscovery: Redactions                        | Distribuzione |
|                                         | Advanced eDiscovery: set di revisione                                     | Distribuzione |
|                                         | Advanced eDiscovery: esaminare e annotare                             | Distribuzione |
|                                         | Advanced eDiscovery: report dei termini di ricerca                        | Distribuzione |
|                                         | Advanced eDiscovery: supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni)                        | Distribuzione |
|                                         | Advanced eDiscovery: Tagging                              | Distribuzione |
|                                         | Advanced eDiscovery: supporto per le reazioni di Teams                              | Distribuzione |
|                                         | Advanced eDiscovery: report tenant                              | Distribuzione |
|                                         | Advanced eDiscovery: Temi                              | Distribuzione |
|                                         | Advanced eDiscovery: Visualizzatori                              | Distribuzione |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft                              | Distribuzione |
|                                         | Advanced eDiscovery: supporto CJK/Double byte per Advanced eDiscovery                              | In fase di sviluppo |
|                                         | Controllo di base                              | Disponibile |
|                                         | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)                              | Distribuzione |
|                                         | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione                              | Distribuzione |
|                                         | Controllo avanzato: conservazione dei registri (1 anno)                              | Distribuzione |
|                                         | Controllo avanzato: disponibilità del Centro sicurezza e conformità                              | Disponibile |
|                                         | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni)                              | Backlog di progettazione |
|                                         | Controllo avanzato: eventi di inoltro della posta e invio della posta                              | Backlog di progettazione |
|                                         | Controllo avanzato: informazioni dettagliate sui controlli elaborati                              | Backlog di progettazione |
|                                         | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online                              | Backlog di progettazione |
|    **Gestione della conformità**            | Centro sicurezza e conformità di Microsoft 365                              | Disponibile |
|                                         | Microsoft Cloud App Security                              | Backlog di progettazione |
|                                         | Compliance Manager                              | Backlog di progettazione |
|                                         | Supporto dei caratteri a byte doppio                              | Backlog di progettazione |
|    **Ecosistema**            | API Graph per Advanced eDiscovery                              | In fase di sviluppo |
|                                         | Connettori dati di prima parte                              | Backlog di progettazione |
|                                         | Connettori dati di terze parti                              | Backlog di progettazione |
|                                         | API graph per i dati di esportazione di Teams                              | Backlog di progettazione |

<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*