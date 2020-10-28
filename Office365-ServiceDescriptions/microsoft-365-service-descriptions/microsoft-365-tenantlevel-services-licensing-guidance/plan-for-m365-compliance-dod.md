---
title: Pianificare la conformità Microsoft 365 - Distribuzion DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o di altre entità che gestiscono i dati soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: d76e88aeeef105051d4c7c867e120fc6b300a888
ms.sourcegitcommit: 155fab0939dde68a8e1ac24bc5d6471be159943e
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/27/2020
ms.locfileid: "48769978"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Pianificare la conformità Microsoft 365 - Distribuzion DoD

Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o di altre entità che gestiscono i dati soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government – DoD è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di eleggibilità per il governo Microsoft 365 e viene applicato e accettato nel programma, è possibile ignorare i passaggi 1 e 2 e passare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve disporre di Microsoft 365 Government-DoD e soddisfare i requisiti di idoneità

L'ambiente Microsoft 365 Government-DoD è conforme ai requisiti del governo degli Stati Uniti per i servizi cloud.

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità che sono esclusive di Microsoft 365 Government – DoD:

- Il contenuto del cliente dell'organizzazione è logicamente separato dal contenuto del cliente nei servizi di Office 365 commerciali da Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Government-DoD è conforme alle certificazioni e agli accreditamenti necessari per i clienti del settore pubblico degli Stati Uniti.

Per ulteriori informazioni sull'offerta governo-DoD di Microsoft 365 per i clienti del governo degli Stati Uniti, vedere i [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans), inclusi i requisiti di idoneità.

La [Descrizione del servizio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descrive i vantaggi della piattaforma, che sono incentrati sui requisiti di conformità conformi all'interno degli Stati Uniti.

> [!TIP]
> Potrebbe essere necessario trasferire le tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: **rilevanti per l'organizzazione y/n** e **soddisfano le esigenze dell'organizzazione y/n** . È quindi possibile esaminare questo elenco con i colleghi per confermare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali** :<br/>
- *Decidere se Microsoft 365 Government-DoD è appropriato per la propria organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government-DoD è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra una serie di [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Passaggio 2. Richiedi Microsoft 365 Government-DoD

Dopo aver deciso che questo servizio è appropriato per la propria organizzazione, avviare il processo di [applicazione per questo servizio](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Passaggio 3. Informazioni sulle impostazioni di protezione predefinite di Microsoft 365 Government-DoD

È consigliabile richiedere tempo per esaminare attentamente le impostazioni di protezione e di amministratore prima di modificarle e considerare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di protezione predefinite.

**Punto decisionale** : *decidere se modificare una delle impostazioni di protezione predefinite di Microsoft 365 Government-DOD, risolvendo in primo luogo l'impatto di eventuali modifiche apportate.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Passaggio 4. Comprendere quali funzionalità non sono attualmente disponibili o disattivate per impostazione predefinita in Microsoft 365 Government – DoD<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud governativo, esistono alcune differenze tra i piani di Microsoft 365 Government-DoD e Enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili.


|                                         | Funzionalità                                         | Stato GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protezione delle informazioni**              | Client e scanner Unified Labeling         | Disponibili              |
|                                         | Corrispondenza esatta dei dati          | Disponibili               |
|                                         | Classificazione ed etichettatura automatica per Exchange Online, SharePoint Online, OneDrive                      | Distribuzione              |
|                                         | Classificazione ed etichettatura automatica per le app di Office (Word, Excel, PowerPoint, Outlook) tra Web, Android, iOS, Windows e Mac            | In sviluppo |
|                                         | Criteri di classificazione basati su gruppi di Office 365 |  Distribuzione              |
|                                         | Classificazione ed etichettatura automatica per dispositivi mobili                                       | In ingegneria backlog              |
|                                         | Classificazione automatica ed etichettatura per i team                            | In ingegneria backlog |
|                                         | Classificazione dei dati: panoramica e gestione attività contenuto                            | In ingegneria backlog |
|                                         | Classificatori di apprendimento automatico con etichettatura automatica                           | In ingegneria backlog  |
|                                         | Crittografia dei messaggi di base di Office 365 (E3)                            | Disponibili              |
|                                         | Crittografia dei messaggi di Office 365 avanzata (E5)  | Disponibili              |
|                                         | Chiave cliente per Office 365    | Disponibili |
|                                         | Portare la propria chiave (BYOK) per il ciclo di vita del provisioning dei tasti gestiti dal cliente                            | Disponibili |
|                                         | Mantenere la propria chiave (HYOK) che si estende su Azure Information Protection e Active Directory (AD) Rights Management per scenari altamente regolamentati (anteprima)                         | Disponibili |
|                                         | Crittografia a chiave doppia                           | In sviluppo |
|                                         | Prevenzione della perdita di dati (DLP) per file e messaggi di posta elettronica         | Disponibili |
|                                         | Prevenzione della perdita di dati per le conversazioni tra chat e canali di Teams         | In ingegneria backlog |
|                                         | Endpoint di prevenzione della perdita di dati | In ingegneria backlog |
| **Governance delle informazioni** | Governance delle informazioni: archiviazione della posta elettronica                                       | Disponibili              |
|                                         | Governance delle informazioni: blocco per la conservazione          | Disponibili              |
|                                         | Governance delle informazioni: importazione di file PST                      | Disponibili              |
|                                         | Governance delle informazioni: etichette di conservazione manuali non registrate            | Disponibili |
|                                         | Governance delle informazioni: etichette di conservazione predefinite per le raccolte di SharePoint/OneDrive for business, le cartelle e i set di documenti. Cassette postali di Exchange; e gruppi di Office 365 | Disponibili              |
|                                         | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; percorsi o utenti specifici; automaticamente in base a una condizione specifica (ad esempio, parole chiave o informazioni riservate); e in base a un evento                                       | Disponibili              |
|                                         | Governance delle informazioni: etichette di conservazione con classificazione di Syntex di SharePoint                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione con classificatore addestrabile                            | In ingegneria backlog |
|                                         | Governance delle informazioni: criteri di conservazione per Yammer e teams                           | In ingegneria backlog              |
|                                         | Gestione dei record: classificazione manuale per le etichette dei record                              | Disponibili              |
|                                         | Gestione dei record: etichette di record predefinite per SharePoint, raccolte di OneDrive for business, cartelle e set di documenti. e gruppi di Office 365                            | Disponibili              |
|                                         | Gestione dei record: criteri di registrazione automatici basati su specifiche condizioni (ad esempio, parole chiave o informazioni riservate); e in base a un evento  | Disponibili              |
|                                         | Gestione dei record: recensione sulla disposizione    | Disponibili |
|                                         | Gestione dei record: gestione del piano file                            | Disponibili |
|                                         | Gestione dei record: prova dello smaltimento                         | Disponibili |
|                                         | Gestione record: controllo delle versioni dei record                           | Disponibili |
|                                         | Gestione dei record: record normativi | In ingegneria backlog |
|                                         | Gestione dei record: applicazione delle licenze | In ingegneria backlog |
|                                         | Gestione dei record: Revisione della disposizione in più fasi | In ingegneria backlog |
|                                         | Gestione dei record: Esplora attività etichette         | In ingegneria backlog |
|                                         | Gestione dei record: classificatori addestrabili         | In ingegneria backlog |
| **Gestione dei rischi Insider**             | Customer Lockbox                                | Disponibili            |
|                                         | Gestione dei rischi Insider: indicatori di Office per Team, siti di SharePoint, messaggistica di posta elettronica                         | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: furto di dati da parte degli utenti                        | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: perdite di dati generali                                | In ingegneria backlog              |
|                                         | Gestione dei rischi Insider: studiare avvisi di gestione dei rischi Insider                                   | In ingegneria backlog              |
|                                         | Gestione dei rischi Insider: Dashboard del caso, Content Explorer e modelli di avviso | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: decrescente per le indagini per Advanced eDiscovery |In ingegneria backlog|
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte di utenti prioritari (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per le perdite di dati da parte di utenti scontenti (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per violazioni generali dei criteri di sicurezza (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: modelli di criteri per violazioni dei criteri di sicurezza da parte di utenti prioritari, utenti che departono, utenti scontenti (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: personalizzazione del criterio (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: avvisi di esportazione (anteprima) | In ingegneria backlog |
|                                         | Gestione dei rischi Insider: gruppi di utenti prioritari (anteprima) | In ingegneria backlog |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): creare criteri per i clienti, 3 preconfigurati  | In ingegneria backlog |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): supporto per il messaggio teams, Exchange e Rimuovi Teams | In ingegneria backlog |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): avvisi di accesso; modelli di avviso; Dashboard per i criteri di comunicazione | In ingegneria backlog  |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): escalation per l'analisi per Advanced eDiscovery | In ingegneria backlog |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione): individuare il contenuto per adulti | In ingegneria backlog |
|                                         | Barriere informative | In ingegneria backlog |
|                                         | Gestione accessi con privilegi                    | In ingegneria backlog |
| **Scoprire & rispondere**                  | EDiscovery Core: conservazione sul posto                            | Disponibili              |
|                                         | EDiscovery di base: gestione dei casi                                 | Disponibili              |
|                                         | EDiscovery Core: ricerca                                          | Disponibili              |
|                                         | EDiscovery Core: Export                                          | Disponibili              |
|                                         | EDiscovery Core: decrittografia RMS                                  | Disponibili              |
|                                         | EDiscovery di base: esportazione nativa                                   | Disponibili              |
|                                         | EDiscovery di base: controllo                                        | Disponibili              |
|                                         | EDiscovery Core: supporto di Microsoft Compliance esteso per la ricerca e l'esportazione di elementi nel cestino di SharePoint e OneDrive for business                             | In sviluppo |
|                                         | Advanced eDiscovery: elaborazione avanzata                                 | Distribuzione |
|                                         | Advanced eDiscovery: Dashboard                   | Distribuzione |
|                                         | Advanced eDiscovery: Threading della posta elettronica                                          | Distribuzione |
|                                         | Advanced eDiscovery: Export (download, esportazione, aggiunta a un altro set di revisione)                               | Distribuzione |
|                                         | Advanced eDiscovery: filtro                 | Distribuzione |
|                                         | Advanced eDiscovery: conservazione legale dei messaggi per i canali privati dei team                                         | Distribuzione |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                                         | Distribuzione |
|                                         | Advanced eDiscovery: origini dati non detentive                                      | Distribuzione |
|                                         | Advanced eDiscovery: codifica predittiva                                       | Distribuzione |
|                                         | Advanced eDiscovery: esportazione elaborata con il file di carico                   | Distribuzione |
|                                         | Advanced eDiscovery: redazioni                        | Distribuzione |
|                                         | Advanced eDiscovery: set di Revisione                                     | Distribuzione |
|                                         | Advanced eDiscovery: esaminare i dati (query data, smart tag, dashboard e annotazioni (redigere)                             | Distribuzione |
|                                         | Advanced eDiscovery: rapporto termini di ricerca                        | Distribuzione |
|                                         | Advanced eDiscovery: tagging                              | Distribuzione |
|                                         | Advanced eDiscovery: rapporti tenant                              | Distribuzione |
|                                         | Advanced eDiscovery: visualizzatori                              | Distribuzione |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery nel centro conformità di Microsoft                              | Distribuzione |
|                                         | Advanced eDiscovery: supporto per caratteri CJK/Double byte                              | In ingegneria backlog |
|                                         | Advanced eDiscovery: API del grafico                              | In ingegneria backlog |
|                                         | Advanced eDiscovery: supporto di Microsoft Compliance Expanded Support to Search and Export items in SharePoint and OneDrive for business cestino                              | In ingegneria backlog |
|                                         | Advanced eDiscovery: ingestione e elaborazione non Office 365 (ad esempio, OCR)                              | In ingegneria backlog |
|                                         | Advanced eDiscovery: reazioni del team di supporto                              | In ingegneria backlog |
|                                         | Audit di base                              | Disponibili |
|                                         | Controllo avanzato: disponibilità del Centro sicurezza e conformità                              | Disponibili |
|                                         | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)                              | Distribuzione |
|                                         | Controllo avanzato: maggiore larghezza di banda per l'API di attività di gestione                               | Distribuzione |
|                                         | Controllo avanzato: conservazione dei registri (1 anno)                              | Distribuzione |
|                                         | Controllo avanzato: conservazione a lungo termine sui registri di controllo                              | In ingegneria backlog |
|                                         | Controllo avanzato: eventi di inoltro della posta elettronica e posta elettronica                              | In ingegneria backlog |
|                                         | Controllo avanzato: approfondimenti di controllo elaborati                              | In ingegneria backlog |
|                                         | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online                              | In ingegneria backlog |
|    **Gestione della conformità**            | Centro sicurezza e conformità di Microsoft 365                              | Disponibili |
|                                         | Microsoft Cloud App Security                              | In ingegneria backlog |
|                                         | Compliance Manager (anteprima)                              | In ingegneria backlog |
|                                         | Supporto per i caratteri a byte doppio                              | In ingegneria backlog |

<sup>1</sup> lo stato identificato è soggetto a modifiche man mano che i piani di progetto e le priorità vengono rivalutati.<br/>
<sup>2</sup> l'applicazione manuale delle etichette richiede la [versione 1 del client di Azure Information Protection (AIP)](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Punto decisionale** : *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
