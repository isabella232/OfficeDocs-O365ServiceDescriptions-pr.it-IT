---
title: Pianificare la conformità Microsoft 365 - GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 in enti governativi federali, statali, locali, tribali o territoriali o altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government - GCC è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: d3be49d3171e07cfc11e6d6924a8b5ec2395d920
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001902"
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
| Etichettatura di riservatezza                    | Classificazione ed etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive                      | Disponibile         |
| Etichettatura di riservatezza                    | Classificazione automatica ed etichettatura per le app di Office (Word, Excel, PowerPoint, Outlook) su più piattaforme (Web, Android, iOS, Windows e Mac) |  Disponibile              |
| Etichettatura di riservatezza                    | Classificazione ed etichettatura automatiche per i client di Office (mobile)                                       | Backlog di progettazione              |
| Etichettatura di riservatezza                    | Classificazione ed etichettatura automatiche per Teams, gruppi di Microsoft 365, siti di SharePoint                            | Disponibile |
| Analisi                               | Analisi della classificazione dei dati: panoramica ed Esplora contenuto                            | Disponibile |
| Analisi                               | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio                           | Backlog di progettazione  |
| Analisi                               | Analisi: classificatori di machine learning con etichettatura automatica sul lato client/app di Office                           | Distribuzione |
| Crittografia                              | Crittografia dei messaggi di Office 365 di base (E3)                            | Disponibile              |
| Crittografia                              | Crittografia avanzata dei messaggi di Office 365 (E5)  | Disponibile              |
| Crittografia                              | Chiave cliente per Office 365    | Disponibile |
| Crittografia                              | Chiave del cliente: crittografia dei dati in fase di riposo per Microsoft 365    | Distribuzione |
| Crittografia                              | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente                            | Disponibile |
| Crittografia                              | Crittografia a chiave doppia                           | Disponibile |
| Crittografia                              | Crittografia del servizio Exchange Online con chiavi gestite Microsoft         | Disponibile |
| Prevenzione della perdita di dati                    | Prevenzione della perdita dei dati (DLP) per file e posta elettronica         | Disponibile |
| Prevenzione della perdita di dati                    | DLP per le conversazioni di chat e canali di Teams         | Disponibile |
| Prevenzione della perdita di dati                    | DLP Endpoint | Distribuzione |
| Prevenzione della perdita di dati                    | Dashboard avvisi | In fase di sviluppo |
| Prevenzione della perdita di dati                    | Pagina Panoramica | In fase di sviluppo |
| **Governance delle informazioni** | Ambiti adattivi per i criteri di conservazione ed etichettatura                 | Backlog di progettazione              |
| Governance delle informazioni                 | Archiviazione posta elettronica          | Disponibile              |
| Governance delle informazioni                 | Etichette di conservazione predefinite per raccolte, cartelle e set di documenti di SharePoint, OneDrive for Business; Posta in arrivo di Exchange; e Gruppi di Office 365          | Disponibile              |
| Governance delle informazioni                 | Importa PST                      | Disponibile              |
| Governance delle informazioni                 | Etichette di conservazione manuali non record            | Disponibile |
| Governance delle informazioni                 | Blocco di conservazione            | Disponibile |
| Governance delle informazioni                 | Criteri di conservazione per l'intera organizzazione; posizioni o utenti specifici; automaticamente in base a condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento                                       | Disponibile              |
| Governance delle informazioni                 | Criteri di conservazione per Teams                            | Disponibile |
| Governance delle informazioni                 | Criteri di conservazione per la registrazione delle riunioni di Teams                            | In fase di sviluppo |
| Governance delle informazioni                 | Criteri di conservazione per i canali privati di Teams                            | Backlog di progettazione |
| Governance delle informazioni                 | Criteri di conservazione per i canali condivisi di Teams                            | Backlog di progettazione |
| Governance delle informazioni                 | Criteri di conservazione con classificatori addestrabili                            | Backlog di progettazione |
| Governance delle informazioni                 | Criteri di conservazione per Yammer                            | Backlog di progettazione |
| Gestione dei record                     | Possibilità di eliminare un'etichetta di record                           | In fase di sviluppo              |
| Gestione dei record                     | Applicare manualmente un'etichetta di record                            | Disponibile              |
| Gestione dei record                     | Applicare etichette di record predefinite per raccolte, cartelle e set di documenti di SharePoint, OneDrive for Business; e gruppi di Office 365                              | Disponibile              |
| Gestione dei record                     | Applicare i criteri di record automaticamente in base a condizioni specifiche (ad esempio, parole chiave o informazioni riservate); e in base a un evento                            | Disponibile              |
| Gestione dei record                     | Applicare automaticamente i criteri di record con classificatori addestrabili  | In fase di sviluppo              |
| Gestione dei record                     | Revisione per l'eliminazione  | Disponibile              |
| Gestione dei record                     | Gestione del piano di archiviazione    | Disponibile |
| Gestione dei record                     | Revisione dell'eliminazione in più fasi    | Backlog di progettazione |
| Gestione dei record                     | Supporto client Outlook per Gestione record    | Backlog di progettazione |
| Gestione dei record                     | Power Automate Flow alla fine del periodo di conservazione    | Backlog di progettazione |
| Gestione dei record                     | Conservazione e etichettatura automatica degli allegati cloud    | Backlog di progettazione |
| Gestione dei record                     | Prova di eliminazione                            | Disponibile |
| Gestione dei record                     | Controllo delle versioni dei record                            | Disponibile |
| Gestione dei record                     | Record normativi                         | Disponibile |
| Gestione dei record                     | Usare la classificazione Syntex di SharePoint per applicare etichette di record | Backlog di progettazione |
| **Gestione dei rischi Insider**             | Customer Lockbox                                | Disponibile            |
| Conformità delle comunicazioni                | Possibilità di ignorare la firma di posta elettronica o la dichiarazione di non responsabilità                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Possibilità di impostare un periodo di conservazione per un criterio di conformità delle comunicazioni                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione                         | Disponibile |
| Conformità delle comunicazioni                | Analizzare i dati della chat di Teams degli utenti con una cassetta postale locale                         | Disponibile |
| Conformità delle comunicazioni                | Monitorare automaticamente tutti i team di cui un utente è membro                         | Disponibile |
| Conformità delle comunicazioni                | Modello conflitto di interesse                         | Disponibile |
| Conformità delle comunicazioni                | Creare criteri per i clienti, 3 preconfigurato                         | Disponibile |
| Conformità delle comunicazioni                | Rilevare contenuto per adulti                         | Disponibile |
| Conformità delle comunicazioni                | Rileva la violazione del codice di condotta ripetuto nel tempo                         | Disponibile |
| Conformità delle comunicazioni                | Escalation per l'indagine per Advanced eDiscovery                         | Disponibile |
| Conformità delle comunicazioni                | Gestione dei rischi insider                         | Backlog di progettazione |
| Conformità delle comunicazioni                | Sfruttare il riconoscimento ottico dei caratteri per estrarre e valutare i messaggi                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Nuova visualizzazione semplificata per le aziende di piccole dimensioni                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Controllo dell'integrità dei criteri e possibilità di sospendere i criteri                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Integrazione Power Automate                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Supporto per autorizzazioni più granulari                         | Disponibile |
| Conformità delle comunicazioni                | Supporta sette lingue per classificatori di minacce, molestie mirate e volgarità                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Integrazione di Microsoft Teams                         | Backlog di progettazione |
| Conformità delle comunicazioni                | Contesto di conversazione di Teams                         | In fase di sviluppo |
| Conformità delle comunicazioni                | Tradurre il contenuto durante l'analisi                         | Backlog di progettazione |
| Customer Lockbox                | Customer Lockbox                         | Disponibile |
| Ostacoli alle informazioni                | Barriere informative                         | Disponibile |
| Gestione dei rischi Insider             | Dashboard dei casi                         | Disponibile |
| Gestione dei rischi Insider             | Furto di dati da parte di utenti in partenza                        | Disponibile |
| Gestione dei rischi Insider             | Indicatori di dispositivo per l'attività in Windows 10 Build 1809 e versioni successive                        | Backlog di progettazione |
| Gestione dei rischi Insider             | Escalation per l'indagine per Advanced eDiscovery                        | Disponibile |
| Gestione dei rischi Insider             | Esportare avvisi                        | Backlog di progettazione |
| Gestione dei rischi Insider             | Perdite di dati generali                                | Disponibile              |
| Gestione dei rischi Insider             | Indicatori per la violazione dei criteri di sicurezza                   | Backlog di progettazione              |
| Gestione dei rischi Insider             | Indicatori per gli avvisi di Microsoft Defender per endpoint      | Backlog di progettazione              |
| Gestione dei rischi Insider             | Gestione dei rischi insider Esplora attività      | In fase di sviluppo              |
| Gestione dei rischi Insider             | Insider risk Management Content Explorer      | In fase di sviluppo              |
| Gestione dei rischi Insider             | Analizzare gli avvisi di gestione dei rischi insider      | Disponibile              |
| Gestione dei rischi Insider             | Modelli di avviso      | Disponibile              |
| Gestione dei rischi Insider             | Indicatori di Office per Teams, siti di SharePoint, messaggistica di posta elettronica      | Disponibile              |
| Gestione dei rischi Insider             | Personalizzazione dei criteri      | Backlog di progettazione              |
| Gestione dei rischi Insider             | Modelli di criteri per le perdite di dati da parte di utenti scontenti      | Backlog di progettazione              |
| Gestione dei rischi Insider             | Modelli di criteri per le perdite di dati per utenti con priorità | Backlog di progettazione |
| Gestione dei rischi Insider             | Modelli di criteri per violazioni generali dei criteri di sicurezza | Backlog di progettazione |
| Gestione dei rischi Insider             | Modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità, utenti in partenza, utenti scontenti | Backlog di progettazione |
| Gestione dei rischi Insider             | Gruppi di utenti con priorità | Backlog di progettazione |
| Gestione dei rischi Insider             | Integrazione Power Automate | In fase di sviluppo |
| Gestione dei rischi Insider             | Integrazione di Microsoft Teams | Backlog di progettazione |
| Gestione degli accessi con privilegi        | Gestione accessi con privilegi | Backlog di progettazione |
| **Individuare & rispondere**                  | Core eDiscovery: Controllo                            | Disponibile              |
| eDiscovery                              | Core eDiscovery: Gestione dei casi                                 | Disponibile              |
| eDiscovery                              | Core eDiscovery: Esportazione                                          | Disponibile              |
| eDiscovery                              | Core eDiscovery: conservazione sul posto                           | Disponibile              |
| eDiscovery                              | Core eDiscovery: esportazione nativa                                  | Disponibile              |
| eDiscovery                              | Core eDiscovery: decrittografia RMS                                   | Disponibile              |
| eDiscovery                              | Core eDiscovery: Ricerca                                   | Disponibile              |
| eDiscovery                              | Core eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi nel Cestino di SharePoint e OneDrive for Business                                        | Disponibile              |
| eDiscovery                              | Advanced eDiscovery: Elaborazione avanzata                             | Disponibile |
| eDiscovery                              | Advanced eDiscovery: mapping tra custodia e carico di lavoro                             | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Comunicazioni di custodia                             | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Dashboard                                 | Disponibile |
| eDiscovery                              | Advanced eDiscovery: supporto dei caratteri a byte doppio (cinese, giapponese, coreano)                                 | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Threading della posta elettronica                   | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di visualizzazione)                                          | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Filtro                               | Disponibile |
| eDiscovery                              | Advanced eDiscovery: ottimizzazioni del blocco                      | In fase di sviluppo |
| eDiscovery                              | Advanced eDiscovery: blocco legale per i messaggi di canali privati di Teams            | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi nel Cestino di SharePoint e OneDrive for Business            | In fase di sviluppo |
| eDiscovery                              | Advanced eDiscovery: identificazione quasi duplicata                               | Disponibile |
| eDiscovery                              | Advanced eDiscovery: nuovo modulo di codifica predittiva                   | Backlog di progettazione |
| eDiscovery                              | Advanced eDiscovery: origini dati non di custodia                                  | Disponibile |
| eDiscovery                              | Advanced eDiscovery: inserimento non di Office 365                                    | Disponibile |
| eDiscovery                              | Advanced eDiscovery: codifica predittiva                                       | Disponibile |
| eDiscovery                              | Advanced eDiscovery: esportazione elaborata con file di caricamento                   | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Redactions                        | Disponibile |
| eDiscovery                              | Advanced eDiscovery: set di revisione                                     | Disponibile |
| eDiscovery                              | Advanced eDiscovery: esaminare i dati (dati di query, smart tag, dashboard) e annotare (redact)                             | Disponibile |
| eDiscovery                              | Advanced eDiscovery: report dei termini di ricerca                        | Disponibile |
| eDiscovery                              | Advanced eDiscovery: correzione degli errori di un singolo elemento                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: supportare l'esportazione PST                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni)                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: supportare le reazioni di Teams                      | Backlog di progettazione |
| eDiscovery                              | Advanced eDiscovery: Tagging                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: report tenant                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Temi                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Visualizzatori                              | Disponibile |
| eDiscovery                              | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft                              | Disponibile |
| Audit                                   | Controllo di base                              | Disponibile |
| Audit                                   | Controllo avanzato: accesso a eventi cruciali (ad esempio, *MailItemsAccessed*)                              | Disponibile |
| Audit                                   | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione                   | Disponibile |
| Audit                                   | Controllo avanzato: blocco legale per i messaggi dei canali privati di Teams                   | Disponibile |
| Audit                                   | Controllo avanzato: conservazione dei registri (1 anno)                               | Disponibile |
| Audit                                   | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni)              | In fase di sviluppo |
| Audit                                   | Controllo avanzato: eventi di inoltro della posta e invio della posta                               | Disponibile |
| Audit                                   | Controllo avanzato: Centro sicurezza e conformità di Microsoft 365                    | Disponibile |
| Audit                                   | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online                              | Backlog di progettazione |
|    **Gestione della conformità**            | Centro sicurezza e conformità di Microsoft 365                              | Disponibile |
|                                         | Compliance Manager                              | Disponibile |
|                                         | Supporto dei caratteri a byte doppio                              | Disponibile |
|                                         | Microsoft Cloud App Security                              | Backlog di progettazione |
|    **Ecosistema**            | API Graph per Advanced eDiscovery                              | In fase di sviluppo |
|                                         | API graph per i dati di esportazione di Teams                              | Backlog di progettazione |
|                                         | Connettori dati di prima parte                              | Backlog di progettazione |
|                                         | Connettori dati di terze parti                              | In fase di sviluppo |




<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
