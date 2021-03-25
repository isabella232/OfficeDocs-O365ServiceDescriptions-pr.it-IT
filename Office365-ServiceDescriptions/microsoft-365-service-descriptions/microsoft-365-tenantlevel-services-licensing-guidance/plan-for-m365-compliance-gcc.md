---
title: Pianificare la conformità Microsoft 365 - GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 in enti governativi federali, statali, locali, tribali o territoriali o altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government - GCC è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: 702ed14de312588aee1cad6094683fcada2333bc
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173511"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Pianificare la conformità di Microsoft 365 - GCC

Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 in enti governativi federali, statali, locali, tribali o territoriali o altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government - GCC è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di idoneità di Microsoft 365 Government - GCC ed è stata richiesta e accettata nel programma, è possibile ignorare i passaggi 1 e 2 e andare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione necessita di Microsoft 365 Government - GCC e soddisfa i requisiti di idoneità

L'ambiente Microsoft 365 Government - GCC è conforme ai requisiti del governo statunitense per i servizi cloud, tra cui FedRAMP Moderate, e ai requisiti per la giustizia penale e i sistemi di informazioni fiscali federali (tipi di dati CJI e FTI).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche di Microsoft 365 Government - GCC:

- Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi commerciali di Office 365 da Microsoft.

- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Microsoft 365 Government - GCC è conforme alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

Ulteriori informazioni sull'offerta Microsoft 365 Government - GCC per i clienti del governo statunitense sono disponibili nei piani di [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [descrizione del servizio Office 365 US Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descrive i vantaggi della piattaforma, che sono centrati sulla conformità dei requisiti all'interno degli Stati Uniti.

> [!TIP]
> È possibile trasferire gli tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: Rilevante per l'organizzazione **Y/N** e Soddisfa le esigenze dell'organizzazione **Y/N.** È quindi possibile esaminare l'elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

> [!NOTE]
> Microsoft 365 Government - GCC è disponibile solo negli Stati Uniti. I clienti non statunitensi possono scegliere tra diversi piani di [Office 365 Government.](https://products.office.com/government/compare-office-365-government-plans)

**Punti decisionali**: <br/>
- *Decidere se Microsoft 365 Government - GCC è appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Passaggio 2. Richiedere Microsoft 365 Government - GCC

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo di [richiesta per questo servizio.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Passaggio 3. Informazioni su Microsoft 365 Government - Impostazioni di sicurezza predefinite GCC

È consigliabile prendere tempo per esaminare attentamente le impostazioni di sicurezza e di amministrazione prima di modificarle e valutare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto di** decisione: decidere se modificare le impostazioni di sicurezza predefinite di *Microsoft 365 Government - GCC,* risolvendo per prima cosa l'impatto di eventuali modifiche apportate.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government – GCC<sup>1</sup>

Per soddisfare i requisiti dei clienti cloud per enti pubblici, esistono alcune differenze tra i piani di Microsoft 365 Government - GCC e enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli ultimi aggiornamenti dei prodotti di conformità pubblicati sulla roadmap di Microsoft 365.<br><br>

| Area | Funzionalità | Stato GCC |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protezione delle informazioni**              | Client e scanner di etichettatura unificati         | Disponibile              |
|                                         | Corrispondenza esatta dei dati          | Disponibile              |
|                                         | Classificazione ed etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive                      | Distribuzione              |
|                                         | Classificazione automatica ed etichettatura per le app di Office (Word, Excel, PowerPoint, Outlook) su più piattaforme (Web, Android, iOS, Windows e Mac) |  In fase di sviluppo              |
|                                         | Classificazione ed etichettatura automatiche per i client di Office (mobile)                                       | Backlog di progettazione              |
|                                         | Classificazione ed etichettatura automatiche per Teams                            | Backlog di progettazione |
|                                         | Analisi della classificazione dei dati: panoramica ed Esplora contenuto                            | Backlog di progettazione |
|                                         | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio                           | Backlog di progettazione  |
|                                         | Analisi: classificatori di machine learning con etichettatura automatica sul lato client/app di Office                           | Backlog di progettazione  |
|                                         | Crittografia dei messaggi di Office 365 di base (E3)                            | Disponibile              |
|                                         | Crittografia avanzata dei messaggi di Office 365 (E5)  | Disponibile              |
|                                         | Chiave cliente per Office 365    | Disponibile |
|                                         | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente                            | Disponibile |
|                                         | Mantenere la propria chiave (HYOK) che si estende su Azure Information Protection e Active Directory (AD) Rights Management per scenari altamente regolamentati (Anteprima)                         | Disponibile |
|                                         | Crittografia a chiave doppia                           | Disponibile |
|                                         | Crittografia: creazione condivisa su documenti crittografati tramite app Web WXP                           | Backlog di progettazione |
|                                         | Prevenzione della perdita dei dati (DLP) per file e posta elettronica         | Disponibile |
|                                         | DLP per le conversazioni di chat e canali di Teams         | In fase di sviluppo |
|                                         | DLP Endpoint | Backlog di progettazione |
| **Governance delle informazioni** | Governance delle informazioni: Archiviazione posta elettronica                                       | Disponibile              |
|                                         | Governance delle informazioni: blocco di conservazione          | Disponibile              |
|                                         | Governance delle informazioni: importare PST                      | Disponibile              |
|                                         | Governance delle informazioni: etichette di conservazione manuali non record            | Disponibile |
|                                         | Governance delle informazioni: etichette di conservazione predefinite per raccolte, cartelle e set di documenti di SharePoint, OneDrive for Business; Posta in arrivo di Exchange; e Gruppi di Office 365 | Disponibile              |
|                                         | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; posizioni o utenti specifici; automaticamente in base a condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento                                       | Disponibile              |
|                                         | Governance delle informazioni: criteri di conservazione per Teams                            | Disponibile |
|                                         | Governance delle informazioni: etichette di conservazione tramite la classificazione Syntex di SharePoint                            | Backlog di progettazione |
|                                         | Governance delle informazioni: criteri di conservazione con classificatori addestrabili                            | Backlog di progettazione |
|                                         | Governance delle informazioni: criteri di conservazione per la registrazione delle riunioni di Teams                            | Backlog di progettazione |
|                                         | Governance delle informazioni: criteri di conservazione per Yammer                            | Backlog di progettazione |
|                                         | Gestione dei record: classificazione manuale per le etichette di record                           | Disponibile              |
|                                         | Gestione dei record: etichette di record predefinite per raccolte, cartelle e set di documenti di SharePoint, OneDrive for Business; e gruppi di Office 365                              | Disponibile              |
|                                         | Gestione dei record: criteri di record automatici basati su condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento                            | Disponibile              |
|                                         | Gestione dei record: revisione dell'eliminazione  | Disponibile              |
|                                         | Gestione dei record: Gestione piano di file    | Disponibile |
|                                         | Gestione dei record: prova di eliminazione                            | Disponibile |
|                                         | Gestione record: controllo delle versioni dei record                            | Disponibile |
|                                         | Gestione dei record: record normativi (anteprima pubblica)                         | In fase di sviluppo |
|                                         | Gestione dei record: revisione dell'eliminazione in più fasi | Backlog di progettazione |
|                                         | Gestione record: utilizzare la classificazione Syntex di SharePoint per applicare etichette di record | Backlog di progettazione |
| **Gestione dei rischi insider**             | Customer Lockbox                                | Disponibile            |
|                                         | Insider Risk Management: indicatori di Office per Teams, siti di SharePoint, messaggi di posta elettronica                         | In fase di sviluppo |
|                                         | Insider Risk Management: furto di dati da parte di utenti in partenza                        | In fase di sviluppo |
|                                         | Insider Risk Management: perdite di dati generali                                | In fase di sviluppo              |
|                                         | Insider Risk Management: analizzare gli avvisi di gestione dei rischi insider                                   | In fase di sviluppo              |
|                                         | Gestione dei rischi insider: dashboard del caso, Esplora contenuto e modelli di avviso | In fase di sviluppo |
|                                         | Insider Risk Management: escalation per l'indagine per Advanced eDiscovery | In fase di sviluppo|
|                                         | Gestione dei rischi Insider: indicatori del dispositivo per l'attività in Windows 10 Build 1809 e versioni successive | Backlog di progettazione|
|                                         | Insider Risk Management: indicatori per la violazione dei criteri di sicurezza (anteprima) | Backlog di progettazione|
|                                         | Insider Risk Management: indicatori per gli avvisi di Microsoft Defender for Endpoint (anteprima) | Backlog di progettazione|
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte degli utenti con priorità (anteprima) | Backlog di progettazione |
|                                         | Insider Risk Management: modelli di criteri per le perdite di dati da parte di utenti scontenti (anteprima) | Backlog di progettazione |
|                                         | Insider Risk Management: modelli di criteri per violazioni generali dei criteri di sicurezza (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi Insider: modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità, utenti in partenza, utenti scontenti (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi Insider: personalizzazione dei criteri (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi Insider: esportare gli avvisi (anteprima) | Backlog di progettazione |
|                                         | Gestione dei rischi insider: gruppi di utenti con priorità (anteprima) | Backlog di progettazione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): creare criteri per i clienti, 3 preconfigurato  | Distribuzione |
|                                         | Conformità delle comunicazioni (incl. Criteri di supervisione): supporto per Teams, Exchange e rimozione del messaggio di Teams | Distribuzione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione | Distribuzione  |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): escalation per l'indagine per Advanced eDiscovery | Distribuzione |
|                                         | Conformità delle comunicazioni (incl. criteri di supervisione): rilevare i contenuti per adulti | Distribuzione |
|                                         | Conformità delle comunicazioni: rileva la violazione del codice di condotta ripetuto nel tempo | Distribuzione |
|                                         | Conformità delle comunicazioni: supporto per autorizzazioni più granulari | Distribuzione |
|                                         | Conformità delle comunicazioni: analizzare i dati di chat di Teams degli utenti con una cassetta postale locale | Distribuzione |
|                                         | Conformità delle comunicazioni: modello conflitto di interesse | Backlog di progettazione |
|                                         | Conformità delle comunicazioni: possibilità di ignorare la firma o la dichiarazione di non responsabilità della posta elettronica | Backlog di progettazione |
|                                         | Conformità delle comunicazioni: hand-off per la gestione dei rischi insider | Backlog di progettazione |
|                                         | Conformità delle comunicazioni: controllo dell'integrità dei criteri e possibilità di sospendere i criteri | Backlog di progettazione |
|                                         | Conformità delle comunicazioni: tradurre il contenuto dell'integrità durante l'indagine | Backlog di progettazione |
|                                         | Conformità delle comunicazioni: rilevamento di burnout e attacchi di morte | Backlog di progettazione |
|                                         | Barriere informative | Backlog di progettazione |
|                                         | Gestione accessi con privilegi                    | Backlog di progettazione |
| **Individuare & rispondere**                  | Core eDiscovery: conservazione sul posto                            | Disponibile              |
|                                         | Core eDiscovery: Controllo                                 | Disponibile              |
|                                         | Core eDiscovery: Gestione dei casi                                 | Disponibile              |
|                                         | Core eDiscovery: Esportazione                                          | Disponibile              |
|                                         | Core eDiscovery: esportazione nativa                                  | Disponibile              |
|                                         | Core eDiscovery: decrittografia RMS                                   | Disponibile              |
|                                         | Core eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi nel Cestino di SharePoint e OneDrive for Business                                        | In fase di sviluppo              |
|                                         | Advanced eDiscovery: Elaborazione avanzata                             | Disponibile |
|                                         | Advanced eDiscovery: Dashboard                                 | Disponibile |
|                                         | Advanced eDiscovery: Threading della posta elettronica                   | Disponibile |
|                                         | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di visualizzazione)                                          | Disponibile |
|                                         | Advanced eDiscovery: Filtro                               | Disponibile |
|                                         | Advanced eDiscovery: blocco legale per i messaggi di canali privati di Teams                 | Disponibile |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                                         | Disponibile |
|                                         | Advanced eDiscovery: origini dati non di custodia                                         | Disponibile |
|                                         | Advanced eDiscovery: inserimento non di Office 365                                      | Disponibile |
|                                         | Advanced eDiscovery: codifica predittiva                                       | Disponibile |
|                                         | Advanced eDiscovery: esportazione elaborata con file di caricamento                   | Disponibile |
|                                         | Advanced eDiscovery: Redactions                        | Disponibile |
|                                         | Advanced eDiscovery: set di revisione                                     | Disponibile |
|                                         | Advanced eDiscovery: esaminare i dati (dati di query, smart tag, dashboard) e annotare (redact)                             | Disponibile |
|                                         | Advanced eDiscovery: report dei termini di ricerca                        | Disponibile |
|                                         | Advanced eDiscovery: correzione degli errori di un singolo elemento                              | Disponibile |
|                                         | Advanced eDiscovery: supportare l'esportazione PST                              | Disponibile |
|                                         | Advanced eDiscovery: supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni)                              | Disponibile |
|                                         | Advanced eDiscovery: Tagging                              | Disponibile |
|                                         | Advanced eDiscovery: report tenant                              | Disponibile |
|                                         | Advanced eDiscovery: Temi                              | Disponibile |
|                                         | Advanced eDiscovery: Visualizzatori                              | Disponibile |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft                              | Disponibile |
|                                         | Advanced eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi nel Cestino di SharePoint e OneDrive for Business                              | In fase di sviluppo |
|                                         | Advanced eDiscovery: supporto per le reazioni di Teams                              | In fase di sviluppo |
|                                         | Controllo di base                              | Disponibile |
|                                         | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)                              | Disponibile |
|                                         | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione                              | Disponibile |
|                                         | Controllo avanzato: blocco legale per i messaggi dei canali privati di Teams                               | Disponibile |
|                                         | Controllo avanzato: conservazione dei registri (1 anno)                               | Distribuzione |
|                                         | Controllo avanzato: Centro sicurezza e conformità                               | Disponibile |
|                                         | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni)                               | Backlog di progettazione |
|                                         | Controllo avanzato: eventi di inoltro della posta e invio della posta                               | Backlog di progettazione |
|                                         | Controllo avanzato: informazioni dettagliate sui controlli elaborati                               | Backlog di progettazione |
|                                         | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online                              | Backlog di progettazione |
|    **Gestione della conformità**            | Centro sicurezza e conformità di Microsoft 365                              | Disponibile |
|                                         | Compliance Manager                              | Disponibile |
|                                         | Microsoft Cloud App Security                              | Backlog di progettazione |
|                                         | Supporto dei caratteri a byte doppio                              | Backlog di progettazione |
|    **Ecosistema**            | API Graph per Advanced eDiscovery                              | In fase di sviluppo |
|                                         | Connettori dati di prima parte                              | Backlog di progettazione |
|                                         | Connettori dati di terze parti                              | Backlog di progettazione |
|                                         | API graph per i dati di esportazione di Teams                              | Backlog di progettazione |




<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*