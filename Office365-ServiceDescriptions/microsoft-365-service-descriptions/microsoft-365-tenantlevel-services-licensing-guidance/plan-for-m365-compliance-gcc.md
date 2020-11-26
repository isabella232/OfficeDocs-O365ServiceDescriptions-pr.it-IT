---
title: Pianificare la conformità Microsoft 365 - GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità governative degli Stati Uniti, statali, locali, tribali o territoriali o in altre entità che gestiscono i dati soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government-GCC è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: 15e533e9a0484d494ee9430d057df9dcd847fffd
ms.sourcegitcommit: ace6cd97a0d3823959e1629929be77489f79b520
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/25/2020
ms.locfileid: "49411645"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Pianificare la conformità a Microsoft 365 – GCC

Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità governative degli Stati Uniti, statali, locali, tribali o territoriali o in altre entità che gestiscono i dati soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government-GCC è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se nell'organizzazione sono già stati soddisfatti i requisiti di idoneità del governo di Microsoft 365 e sono stati richiesti e accettati nel programma, è possibile ignorare i passaggi 1 e 2 e passare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve disporre di Microsoft 365 Government-GCC e soddisfare i requisiti di idoneità

L'ambiente Government-GCC di Microsoft 365 è conforme ai requisiti del governo degli Stati Uniti per i servizi cloud, tra cui FedRAMP moderati e requisiti per la giustizia penale e i sistemi informativi federali (CJI e FTI).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità che sono esclusive di Microsoft 365 Government-GCC:

- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi di Office 365 commerciali da Microsoft.

- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Microsoft 365 Government-GCC è conforme alle certificazioni e agli accreditamenti necessari per i clienti del settore pubblico degli Stati Uniti.

Per ulteriori informazioni sull'offerta governo-GCC di Microsoft 365 per i clienti del governo degli Stati Uniti, vedere i [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans), inclusi i requisiti di idoneità.

La [Descrizione del servizio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descrive i vantaggi della piattaforma, che sono incentrati sui requisiti di conformità conformi all'interno degli Stati Uniti.

> [!TIP]
> Potrebbe essere necessario trasferire le tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: **rilevanti per l'organizzazione y/n** e **soddisfano le esigenze dell'organizzazione y/n**. È quindi possibile esaminare questo elenco con i colleghi per confermare che questo servizio soddisfi le esigenze dell'organizzazione.

> [!NOTE]
> Microsoft 365 Government-GCC è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra una serie di [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans).

**Punti decisionali**: <br/>
- *Decidere se Microsoft 365 Government-GCC è appropriato per la propria organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Passaggio 2. Richiedi Microsoft 365 Government-GCC

Dopo aver deciso che questo servizio è appropriato per la propria organizzazione, avviare il processo di [applicazione per questo servizio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Passaggio 3. Informazioni sulle impostazioni di protezione predefinite di Microsoft 365 Government-GCC

È consigliabile richiedere tempo per esaminare attentamente le impostazioni di protezione e di amministratore prima di modificarle e considerare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di protezione predefinite.

**Punto decisionale**: *decidere se modificare una delle impostazioni di protezione predefinite di Microsoft 365 Government-GCC, risolvendo in primo luogo l'impatto di eventuali modifiche apportate.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Passaggio 4. Comprendere quali funzionalità non sono attualmente disponibili o disattivate per impostazione predefinita in Microsoft 365 Government – GCC<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud governativo, esistono alcune differenze tra i piani di Microsoft 365 Government-GCC e Enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) per gli ultimi aggiornamenti del prodotto di conformità pubblicati su Microsoft 365 roadmap.<br><br>

| Area | Funzionalità | Stato GCC |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protezione delle informazioni**              | Client e scanner Unified Labeling         | Disponibili              |
|                                         | Corrispondenza esatta dei dati          | Disponibili              |
|                                         | Classificazione ed etichettatura automatica per Exchange Online, SharePoint Online e OneDrive                      | Distribuzione              |
|                                         | Classificazione ed etichettatura automatica per le app di Office (Word, Excel, PowerPoint, Outlook) tra piattaforme (Web, Android, iOS, Windows e Mac) |  In sviluppo              |
|                                         | Classificazione ed etichettatura automatica per i client di Office (mobile)                                       | In ingegneria backlog              |
|                                         | Classificazione automatica ed etichettatura per i team                            | In ingegneria backlog |
|                                         | Analisi di classificazione dei dati: panoramica e Esplora contenuto                            | In ingegneria backlog |
|                                         | Analisi: classificatori di apprendimento automatico con etichettatura automatica sul fianco del servizio                           | In ingegneria backlog  |
|                                         | Analisi: classificatori di apprendimento automatico con etichettatura automatica su applicazioni di Office/client side                           | In ingegneria backlog  |
|                                         | Crittografia dei messaggi di base di Office 365 (E3)                            | Disponibili              |
|                                         | Crittografia dei messaggi di Office 365 avanzata (E5)  | Disponibili              |
|                                         | Chiave cliente per Office 365    | Disponibili |
|                                         | Portare la propria chiave (BYOK) per il ciclo di vita del provisioning dei tasti gestiti dal cliente                            | Disponibili |
|                                         | Mantenere la propria chiave (HYOK) che si estende su Azure Information Protection e Active Directory (AD) Rights Management per scenari altamente regolamentati (anteprima)                         | Disponibili |
|                                         | Crittografia a chiave doppia                           | Disponibili |
|                                         | Crittografia: creazione condivisa in documenti crittografati tramite le app Web di WXP                           | In ingegneria backlog |
|                                         | Prevenzione della perdita di dati (DLP) per file e messaggi di posta elettronica         | Disponibili |
|                                         | DLP per la chat di team e le conversazioni dei canali         | In sviluppo |
|                                         | Endpoint DLP | In ingegneria backlog |
| **Governance delle informazioni** | Governance delle informazioni: archiviazione della posta elettronica                                       | Disponibili              |
|                                         | Governance delle informazioni: blocco per la conservazione          | Disponibili              |
|                                         | Governance delle informazioni: importazione di file PST                      | Disponibili              |
|                                         | Governance delle informazioni: etichette di conservazione manuali non registrate            | Disponibili |
|                                         | Governance delle informazioni: etichette di conservazione predefinite per SharePoint, raccolte di OneDrive for business, cartelle e set di documenti. Cassette postali di Exchange; e gruppi di Office 365 | Disponibili              |
|                                         | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; percorsi o utenti specifici; automaticamente in base a una condizione specifica (ad esempio, parole chiave o informazioni riservate); e in base a un evento                                       | Disponibili              |
|                                         | Governance delle informazioni: criteri di conservazione per i team                            | Disponibili |
|                                         | Governance delle informazioni: etichette di conservazione con classificazione di Syntex di SharePoint                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione con classificatori addestrabili                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione per la registrazione riunione di Teams                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione per Yammer                            | In ingegneria backlog |
|                                         | Gestione dei record: classificazione manuale per le etichette dei record                           | Disponibili              |
|                                         | Gestione dei record: etichette di record predefinite per SharePoint, raccolte di OneDrive for business, cartelle e set di documenti. e gruppi di Office 365                              | Disponibili              |
|                                         | Gestione dei record: criteri di registrazione automatici basati su specifiche condizioni (ad esempio, parole chiave o informazioni riservate); e in base a un evento                            | Disponibili              |
|                                         | Gestione dei record: recensione sulla disposizione  | Disponibili              |
|                                         | Gestione dei record: gestione del piano file    | Disponibili |
|                                         | Gestione dei record: prova dello smaltimento                            | Disponibili |
|                                         | Gestione record: controllo delle versioni dei record                            | Disponibili |
|                                         | Gestione dei record: record regolatori (anteprima pubblica)                         | In sviluppo |
|                                         | Gestione dei record: Revisione della disposizione in più fasi | In ingegneria backlog |
|                                         | Gestione dei record: utilizzare la classificazione di Syntex di SharePoint per applicare etichette di record | In ingegneria backlog |
| **Gestione dei rischi Insider**             | Customer Lockbox                                | Disponibili            |
|                                         | Gestione dei rischi Insider: indicatori di Office per Team, siti di SharePoint, messaggistica di posta elettronica                         | In sviluppo |
|                                         | Gestione dei rischi Insider: furto di dati da parte degli utenti                        | In sviluppo |
|                                         | Gestione dei rischi Insider: perdite di dati generali                                | In sviluppo              |
|                                         | Gestione dei rischi Insider: studiare avvisi di gestione dei rischi Insider                                   | In sviluppo              |
|                                         | Gestione dei rischi Insider: Dashboard del caso, Content Explorer e modelli di avviso | In sviluppo |
|                                         | Gestione dei rischi Insider: decrescente per le indagini per Advanced eDiscovery | In sviluppo|
|                                         | Gestione dei rischi Insider: indicatori del dispositivo per attività in Windows 10 Build 1809 e versioni successive | In ingegneria backlog|
|                                         | Gestione dei rischi Insider: indicatori per la violazione dei criteri di sicurezza (anteprima) | In ingegneria backlog|
|                                         | Gestione dei rischi Insider: indicatori per avvisi di Windows Defender ATP (anteprima) | In ingegneria backlog|
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte di utenti prioritari (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte di utenti scontenti (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per violazioni generali dei criteri di sicurezza (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per violazioni dei criteri di sicurezza da parte di utenti prioritari, utenti che departono, utenti scontenti (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: personalizzazione del criterio (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: avvisi di esportazione (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: gruppi di utenti prioritari (anteprima) | In ingegneria backlog |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): creare criteri per i clienti, 3 preconfigurati  | Distribuzione |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): supporto per il messaggio teams, Exchange e Rimuovi Teams | Distribuzione |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): avvisi di accesso; modelli di avviso; Dashboard per i criteri di comunicazione | Distribuzione  |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): escalation per l'analisi per Advanced eDiscovery | Distribuzione |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): individuare il contenuto per adulti | Distribuzione |
|                                         | Conformità alla comunicazione: rileva la violazione del codice di condotta nel corso del tempo | Distribuzione |
|                                         | Conformità alla comunicazione: supporto per autorizzazioni più granulari | Distribuzione |
|                                         | Conformità della comunicazione: analizzare i dati di chat dei team degli utenti con la cassetta postale di on-Prem | Distribuzione |
|                                         | Conformità alla comunicazione: modello di conflitto di interessi | In ingegneria backlog |
|                                         | Conformità comunicazione: possibilità di ignorare la firma di posta elettronica o la dichiarazione di non responsabilità | In ingegneria backlog |
|                                         | Conformità alla comunicazione: gestione dei rischi Insider hand-off | In ingegneria backlog |
|                                         | Conformità della comunicazione: verifica dell'integrità del criterio e possibilità di sospendere i criteri | In ingegneria backlog |
|                                         | Conformità della comunicazione: tradurre il contenuto di integrità durante l'analisi | In ingegneria backlog |
|                                         | Conformità alla comunicazione: Burnout and Suicide Detection | In ingegneria backlog |
|                                         | Barriere informative | In ingegneria backlog |
|                                         | Gestione accessi con privilegi                    | In ingegneria backlog |
| **Scoprire & rispondere**                  | EDiscovery Core: conservazione sul posto                            | Disponibili              |
|                                         | EDiscovery di base: controllo                                 | Disponibili              |
|                                         | EDiscovery di base: gestione dei casi                                 | Disponibili              |
|                                         | EDiscovery Core: Export                                          | Disponibili              |
|                                         | EDiscovery di base: esportazione nativa                                  | Disponibili              |
|                                         | EDiscovery Core: decrittografia RMS                                   | Disponibili              |
|                                         | EDiscovery Core: supporto di Microsoft Compliance esteso per la ricerca e l'esportazione di elementi nel cestino di SharePoint e OneDrive for business                                        | In sviluppo              |
|                                         | Advanced eDiscovery: elaborazione avanzata                             | Disponibili |
|                                         | Advanced eDiscovery: Dashboard                                 | Disponibili |
|                                         | Advanced eDiscovery: Threading della posta elettronica                   | Disponibili |
|                                         | Advanced eDiscovery: Export (download, esportazione, aggiunta a un altro set di visualizzazioni)                                          | Disponibili |
|                                         | Advanced eDiscovery: filtro                               | Disponibili |
|                                         | Advanced eDiscovery: conservazione legale dei messaggi per i canali privati dei team                 | Disponibili |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                                         | Disponibili |
|                                         | Advanced eDiscovery: origini dati non detentive                                         | Disponibili |
|                                         | Advanced eDiscovery: ingestione non Office 365                                      | Disponibili |
|                                         | Advanced eDiscovery: codifica predittiva                                       | Disponibili |
|                                         | Advanced eDiscovery: esportazione elaborata con il file di carico                   | Disponibili |
|                                         | Advanced eDiscovery: redazioni                        | Disponibili |
|                                         | Advanced eDiscovery: set di Revisione                                     | Disponibili |
|                                         | Advanced eDiscovery: esaminare i dati (query data, smart tag, dashboard) e annotazioni (redigere)                             | Disponibili |
|                                         | Advanced eDiscovery: rapporto termini di ricerca                        | Disponibili |
|                                         | Advanced eDiscovery: correzione degli errori di un singolo elemento                              | Disponibili |
|                                         | Advanced eDiscovery: supporto per l'esportazione di PST                              | Disponibili |
|                                         | Advanced eDiscovery: supporto di contenuto collegato da OneDrive e SharePoint Online (allegati moderni)                              | Disponibili |
|                                         | Advanced eDiscovery: tagging                              | Disponibili |
|                                         | Advanced eDiscovery: rapporti tenant                              | Disponibili |
|                                         | Advanced eDiscovery: temi                              | Disponibili |
|                                         | Advanced eDiscovery: visualizzatori                              | Disponibili |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery nel centro conformità di Microsoft                              | Disponibili |
|                                         | Advanced eDiscovery: supporto di Microsoft Compliance Expanded Support to Search and Export items in SharePoint and OneDrive for business cestino                              | In sviluppo |
|                                         | Advanced eDiscovery: supporto per le reazioni di Teams                              | In sviluppo |
|                                         | Audit di base                              | Disponibili |
|                                         | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)                              | Disponibili |
|                                         | Controllo avanzato: maggiore larghezza di banda per l'API di attività di gestione                              | Disponibili |
|                                         | Controllo avanzato: conservazione legale dei messaggi per i canali privati dei team                               | Disponibili |
|                                         | Controllo avanzato: conservazione dei registri (1 anno)                               | Disponibili |
|                                         | Controllo avanzato: Centro sicurezza e conformità                               | Disponibili |
|                                         | Controllo avanzato: conservazione a lungo termine sui registri di controllo                               | In ingegneria backlog |
|                                         | Controllo avanzato: eventi di inoltro della posta elettronica e posta elettronica                               | In ingegneria backlog |
|                                         | Controllo avanzato: approfondimenti di controllo elaborati                               | In ingegneria backlog |
|                                         | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online                              | In ingegneria backlog |
|    **Gestione della conformità**            | Centro sicurezza e conformità di Microsoft 365                              | Disponibili |
|                                         | Compliance Manager                              | Disponibili |
|                                         | Microsoft Cloud App Security                              | In ingegneria backlog |
|                                         | Supporto per i caratteri a byte doppio                              | In ingegneria backlog |
|    **Ecosistema**            | API del grafico per Advanced eDiscovery                              | In sviluppo |
|                                         | Connettori di dati di First-Party                              | In ingegneria backlog |
|                                         | Connettori dati di terze parti                              | In ingegneria backlog |
|                                         | API del grafico per i dati di esportazione dei team                              | In ingegneria backlog |




<sup>1</sup> lo stato identificato è soggetto a modifiche man mano che i piani di progetto e le priorità vengono rivalutati.<br/>

**Punto decisionale**: *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
