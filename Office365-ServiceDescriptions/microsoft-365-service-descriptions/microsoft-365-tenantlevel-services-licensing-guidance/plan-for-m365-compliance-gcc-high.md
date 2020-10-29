---
title: Pianificare la conformità Microsoft 365 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità governative degli Stati Uniti o in altre entità che gestiscono i dati che sono soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government – GCC High è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: 3cbe9271b8e23467fc7934e5847d8433ea5a6768
ms.sourcegitcommit: 9794350861e41d80980ecf6b9000a730b5564988
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/29/2020
ms.locfileid: "48793667"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Pianificare la conformità a Microsoft 365-GCC High

Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità governative degli Stati Uniti o in altre entità che gestiscono i dati che sono soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government – GCC High è appropriato per soddisfare questi requisiti.

> [!NOTE]
>Se nell'organizzazione sono già stati soddisfatti i requisiti di eleggibilità di Microsoft 365 Government (GCC High eleggibility) e sono stati accettati nel programma, è possibile ignorare i passaggi 1 e 2 e passare direttamente al passaggio 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve disporre di Microsoft 365 Government – GCC High e soddisfare i requisiti di idoneità

Microsoft 365 Government-GCC High Environment è conforme ai requisiti del governo degli Stati Uniti per i servizi cloud. Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità che sono esclusive di Microsoft 365 Government – GCC High:

- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi di Office 365 commerciali da Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Government – GCC High è conforme alle certificazioni e agli accreditamenti necessari per i clienti del settore pubblico degli Stati Uniti.

Per ulteriori informazioni sull'offerta Microsoft 365 Government-GCC High per i clienti del governo degli Stati Uniti, vedere i [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans), inclusi i requisiti di eleggibilità.

La [Descrizione del servizio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descrive i vantaggi della piattaforma, che sono incentrati sui requisiti di conformità conformi all'interno degli Stati Uniti.

> [!TIP]
> Potrebbe essere necessario trasferire le tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: **rilevanti per l'organizzazione y/n** e **soddisfano le esigenze dell'organizzazione y/n** . È quindi possibile esaminare questo elenco con i colleghi per confermare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali** :<br/>
- *Decidere se Microsoft 365 Government – GCC-High è appropriato per la propria organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government-GCC High è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra una serie di [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Passaggio 2. Richiedi Microsoft 365 Government-GCC-High

Dopo aver deciso che questo servizio è appropriato per la propria organizzazione, avviare il processo di [applicazione per questo servizio](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Passaggio 3. Informazioni su Microsoft 365 Government-GCC-High impostazioni di protezione predefinite

È consigliabile richiedere tempo per esaminare attentamente le impostazioni di protezione e di amministratore prima di modificarle e considerare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di protezione predefinite.

**Punto decisionale** : *decidere se modificare le impostazioni di protezione predefinite di Microsoft 365-GCC-High, risolvendo in primo luogo l'impatto di eventuali modifiche apportate.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Passaggio 4. Comprendere quali funzionalità non sono attualmente disponibili o disattivate per impostazione predefinita in Microsoft 365 Government – GCC-High<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud governativo, esistono alcune differenze tra i piani di Microsoft 365 Government – GCC-High e Enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili.<br><br>

| Area                                    | Funzionalità                                         | Stato GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protezione delle informazioni**              | Client e scanner Unified Labeling         | Disponibili              |
|                                         | Corrispondenza esatta dei dati          | Disponibili              |
|                                         | Classificazione ed etichettatura automatica per Exchange Online, SharePoint Online e OneDrive                      | Distribuzione              |
|                                         | Classificazione ed etichettatura automatica per le app di Office (Word, Excel, PowerPoint, Outlook) tra Web, Android, iOS, Windows e Mac            | In sviluppo |
|                                         | Criteri di classificazione basati su gruppi di Office 365 |  Distribuzione              |
|                                         | Classificazione ed etichettatura automatica per dispositivi mobili                                       |In ingegneria backlog              |
|                                         | Classificazione automatica ed etichettatura per i team                            |In ingegneria backlog |
|                                         | Classificazione dei dati: panoramica e gestione attività contenuto                            | In ingegneria backlog |
|                                         | Classificatori di apprendimento automatico con etichettatura automatica                           | In ingegneria backlog  |
|                                         | Crittografia dei messaggi di base di Office 365 (E3)                            | Disponibili              |
|                                         | Crittografia dei messaggi di Office 365 avanzata (E5)  | Disponibili              |
|                                         | Chiave cliente per Office 365    | Disponibili |
|                                         | Portare la propria chiave (BYOK) per il ciclo di vita del provisioning dei tasti gestiti dal cliente                            | Disponibili |
|                                         | Mantenere la propria chiave (HYOK) che si estende su Azure Information Protection e Active Directory (AD) Rights Management per scenari altamente regolamentati (anteprima)                         | Disponibili |
|                                         | Crittografia a chiave doppia                           | In sviluppo |
|                                         | Creazione condivisa di documenti crittografati tramite le app Web di WXP         | In ingegneria backlog |
|                                         | Prevenzione della perdita di dati per file e messaggi di posta elettronica         | Disponibili |
|                                         | Prevenzione della perdita di dati per le conversazioni tra chat e canali di Teams | In ingegneria backlog |
|                                         | Endpoint di prevenzione della perdita di dati | In ingegneria backlog |
| **Governance delle informazioni** | Governance delle informazioni: archiviazione della posta elettronica                                       | Disponibili              |
|                                         | Governance delle informazioni: blocco per la conservazione          | Disponibili              |
|                                         | Governance delle informazioni: importazione di file PST                      | Disponibili              |
|                                         | Governance delle informazioni: etichette di conservazione manuali non registrate            | Disponibili |
|                                         | Governance delle informazioni: etichette di conservazione predefinite per SharePoint/OneDrive for business Libraries, Folders, and Document sets; Cassette postali di Exchange; e gruppi di Office 365 | Disponibili              |
|                                         | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; percorsi o utenti specifici; automaticamente in base a una condizione specifica (ad esempio, parole chiave o informazioni riservate); e in base a un evento                                       | Disponibili              |
|                                         | Governance delle informazioni: etichette di conservazione con classificazione di Syntex di SharePoint                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione con classificatore addestrabile                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione per Yammer e teams                            | In ingegneria backlog |
|                                         | Gestione dei record: classificazione manuale per le etichette dei record                           | Disponibili              |
|                                         | Gestione dei record: etichette di record predefinite per SharePoint, raccolte di OneDrive for business, cartelle e set di documenti. e gruppi di Office 365                              | Disponibili              |
|                                         | Gestione dei record: criteri di registrazione automatici basati su specifiche condizioni (ad esempio, parole chiave o informazioni riservate); e in base a un evento                            | Disponibili              |
|                                         | Gestione dei record: recensione sulla disposizione  | Disponibili              |
|                                         | Gestione dei record: gestione del piano file    | Disponibili |
|                                         | Gestione dei record: prova dello smaltimento                            | Disponibili |
|                                         | Gestione record: controllo delle versioni dei record                         | Disponibili |
|                                         | Gestione dei record: record normativi                         | In ingegneria backlog |
|                                         | Gestione dei record: applicazione delle licenze                           | In ingegneria backlog |
|                                         | Gestione dei record: Revisione della disposizione in più fasi | In ingegneria backlog |
|                                         | Gestione dei record: Esplora attività etichette | In ingegneria backlog |
|                                         | Gestione dei record: classificatori addestrabili | In ingegneria backlog |
| **Gestione dei rischi Insider**             | Customer Lockbox                                | Disponibili            |
|                                         | Gestione dei rischi Insider: indicatori di Office per Team, siti di SharePoint, messaggistica di posta elettronica                         | In sviluppo |
|                                         | Gestione dei rischi Insider: furto di dati da parte degli utenti                        | In sviluppo |
|                                         | Gestione dei rischi Insider: perdite di dati generali                                | In sviluppo              |
|                                         | Gestione dei rischi Insider: studiare avvisi di gestione dei rischi Insider                                   | In sviluppo              |
|                                         | Gestione dei rischi Insider: Dashboard del caso, Content Explorer e modelli di avviso | In sviluppo |
|                                         | Gestione dei rischi Insider: decrescente per le indagini per Advanced eDiscovery | In sviluppo|
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte di utenti prioritari (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte di utenti scontenti (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per violazioni generali dei criteri di sicurezza (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per violazioni dei criteri di sicurezza da parte di utenti prioritari, utenti che departono, utenti scontenti (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: personalizzazione del criterio (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: avvisi di esportazione (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: gruppi di utenti prioritari (anteprima) | In ingegneria backlog |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): creare criteri per i clienti, 3 preconfigurati  | In sviluppo |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): supporto per il messaggio teams, Exchange e Rimuovi Teams | In sviluppo |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): avvisi di accesso; modelli di avviso; Dashboard per i criteri di comunicazione | In sviluppo  |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): escalation per l'analisi per Advanced eDiscovery | In sviluppo |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): individuare il contenuto per adulti | In sviluppo |
|                                         | Barriere informative | In ingegneria backlog |
|                                         | Gestione accessi con privilegi                    | In ingegneria backlog |
| **Scoprire & rispondere**                  | EDiscovery Core: conservazione sul posto                            | Disponibili              |
|                                         | EDiscovery di base: gestione dei casi                                 | Disponibili              |
|                                         | EDiscovery Core: ricerca                                          | Disponibili              |
|                                         | EDiscovery Core: Export                                          | Disponibili              |
|                                         | EDiscovery Core: decrittografia RMS                                  | Disponibili              |
|                                         | EDiscovery di base: esportazione nativa                                   | Disponibili              |
|                                         | EDiscovery di base: controllo                                        | Disponibili              |
|                                         | EDiscovery Core: supporto di Microsoft Compliance esteso per la ricerca e l'esportazione di elementi nel cestino di SharePoint e OneDrive for business                                        | In sviluppo              |
|                                         | Advanced eDiscovery: elaborazione avanzata                             | Disponibili |
|                                         | Advanced eDiscovery: Dashboard                             | Disponibili |
|                                         | Advanced eDiscovery: Threading della posta elettronica                                 | Disponibili |
|                                         | Advanced eDiscovery: Export (download, esportazione, aggiunta a un altro set di revisione)                   | Disponibili |
|                                         | Advanced eDiscovery: filtro                                          | Disponibili |
|                                         | Advanced eDiscovery: conservazione legale dei messaggi per i canali privati dei team                               | Disponibili |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                 | Disponibili |
|                                         | Advanced eDiscovery: origini dati non detentive                                         | Disponibili |
|                                         | Advanced eDiscovery: ingestione non Office 365                                         | Disponibili |
|                                         | Advanced eDiscovery: codifica predittiva                                      | Disponibili |
|                                         | Advanced eDiscovery: esportazione elaborata con il file di carico                                       | Disponibili |
|                                         | Advanced eDiscovery: redazioni                   | Disponibili |
|                                         | Advanced eDiscovery: set di Revisione                        | Disponibili |
|                                         | Advanced eDiscovery: esaminare i dati (query data, smart tag, dashboard) e annotazioni (redigere)                                     | Disponibili |
|                                         | Advanced eDiscovery: rapporto termini di ricerca                             | Disponibili |
|                                         | Advanced eDiscovery: correzione degli errori di un singolo elemento                        | Disponibili |
|                                         | Advanced eDiscovery: supporto per l'esportazione di PST                              | Distribuzione |
|                                         | Advanced eDiscovery: tagging                              | Disponibili |
|                                         | Advanced eDiscovery: rapporti tenant                              | Disponibili |
|                                         | Advanced eDiscovery: temi                               | Disponibili |
|                                         | Advanced eDiscovery: visualizzatori                              | Disponibili |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery nel centro conformità di Microsoft                              | Disponibili |
|                                         | Advanced eDiscovery: supporto per CJK/Double byte per Advanced eDiscovery                              | In sviluppo |
|                                         | Advanced eDiscovery: API del grafico                              | In sviluppo |
|                                         | Advanced eDiscovery: reazioni del team di supporto                             | In sviluppo |
|                                         | Advanced eDiscovery: supporto di Microsoft Compliance Expanded Support to Search and Export items in SharePoint and OneDrive for business cestino                               | In ingegneria backlog |
|                                         | Audit di base                              | Disponibili |
|                                         | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)                              | Disponibili |
|                                         | Controllo avanzato: maggiore larghezza di banda per l'API di attività di gestione                              | Disponibili |
|                                         | Controllo avanzato: conservazione legale dei messaggi per i canali privati dei team                              | Disponibili |
|                                         | Controllo avanzato: conservazione dei registri (1 anno)                              | Disponibili |
|                                         | Controllo avanzato: disponibilità del Centro sicurezza e conformità                              | Disponibili |
|                                         | Controllo avanzato: conservazione a lungo termine sui registri di controllo                              | In ingegneria backlog |
|                                         | Controllo avanzato: eventi di inoltro della posta elettronica e posta elettronica                              | In ingegneria backlog |
|                                         | Controllo avanzato: approfondimenti di controllo elaborati                              | In ingegneria backlog |
|                                         | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online                              | In ingegneria backlog |
|    **Gestione della conformità**            | Centro sicurezza e conformità di Microsoft 365                              | Disponibili |
|                                         | Compliance Manager (anteprima)                                 | In ingegneria backlog              |
|                                         | Microsoft Cloud App Security                                 | In ingegneria backlog              |
|                                         | Supporto per i caratteri a byte doppio                                 | In ingegneria backlog              |

<sup>1</sup> lo stato identificato è soggetto a modifiche man mano che i piani di progetto e le priorità vengono rivalutati.<br/>
<sup>2</sup> l'applicazione manuale delle etichette richiede la [versione 1 del client di Azure Information Protection (AIP)](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history). 


**Punto decisionale** : *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
