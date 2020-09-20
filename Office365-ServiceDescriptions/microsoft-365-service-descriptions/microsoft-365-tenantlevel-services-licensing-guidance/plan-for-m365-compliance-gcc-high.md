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
ms.openlocfilehash: 3fecae08a3cdc53e71a68d5181b9d8c2fa8c8008
ms.sourcegitcommit: 638bacac9e663444f7a094d5887476d8a87e3b58
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/18/2020
ms.locfileid: "47962105"
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
> Potrebbe essere necessario trasferire le tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: **rilevanti per l'organizzazione y/n**   e **soddisfano le esigenze dell'organizzazione y/n**. È quindi possibile esaminare questo elenco con i colleghi per confermare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali**:<br/>
- *Decidere se Microsoft 365 Government – GCC-High è appropriato per la propria organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government-GCC High è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra una serie di [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Passaggio 2. Richiedi Microsoft 365 Government-GCC-High

Dopo aver deciso che questo servizio è appropriato per la propria organizzazione, avviare il processo di [applicazione per questo servizio](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Passaggio 3. Informazioni su Microsoft 365 Government-GCC-impostazioni di protezione predefinite elevate

È consigliabile richiedere tempo per esaminare attentamente le impostazioni di protezione e di amministratore prima di modificarle e considerare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di protezione predefinite.

**Punto decisionale**: *decidere se modificare una delle impostazioni di protezione predefinite di Microsoft 365 (GCC-High Security), in modo da poter capire in primo luogo l'impatto delle eventuali modifiche che potrebbero essere apportate.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Passaggio 4. Comprendere quali funzionalità non sono attualmente disponibili o disattivate per impostazione predefinita in Microsoft 365 Government – GCC-High<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud governativo, esistono alcune differenze tra Microsoft 365 Government – GCC-High e Enterprise plans. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili.


|                                         | Funzionalità                                         | Stato GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Protezione delle informazioni**              | Etichettatura unificata e etichette di riservatezza         | Disponibili              |
|                                         | Etichette dei contenitori per SharePoint Online, gruppi di Office          | Distribuzione              |
|                                         | Etichettatura automatica in base ai tipi di dati riservati per Excel online, SharePoint Online, OneDrive for business                      | Distribuzione              |
|                                         | Etichette in base ai tipi di dati riservati per client di Office Win32 e Mac            | In ingegneria backlog |
|                                         | Etichettatura automatica in base ai tipi di dati riservati per Win 32, Mac |  In ingegneria backlog              |
|                                         | Etichettatura automatica in base ai tipi di dati riservati per i team                                       |In ingegneria backlog              |
|                                         | Etichettatura automatica in base ai tipi di dati riservati per dispositivi mobili                            |In ingegneria backlog |
|                                         | Etichette e criteri associati basati su query                            | Disponibili |
|                                         | Esplora attività con etichette                           | In ingegneria backlog  |
|                                         | Classificatori sottoponibili a training                              | In ingegneria backlog              |
|                                         | Crittografia dei messaggi di base di Office 365 (E3)                            | Disponibili              |
|                                         | Crittografia dei messaggi di Office 365 avanzata (E5)  | Disponibili              |
|                                         | Chiave cliente per Office 365    | Disponibili |
|                                         | Portare la propria chiave (BYOK) per il ciclo di vita del provisioning dei tasti gestiti dal cliente                            | Disponibili |
|                                         | Mantenere la propria chiave (HYOK) che si estende su Azure Information Protection e Active Directory (AD) Rights Management per scenari altamente regolamentati (anteprima)                         | Disponibili |
|                                         | Crittografia a chiave doppia                           | In ingegneria backlog |
|                                         | Prevenzione della perdita di dati (DLP) per file e messaggi di posta elettronica         | Disponibili |
|                                         | DLP per la chat di team e le conversazioni dei canali         | Distribuzione |
|                                         | Corrispondenza dati esatta DLP | In ingegneria backlog |
|                                         | Endpoint DLP | In ingegneria backlog |
| **Governance delle informazioni** | Archiviazione di posta elettronica                                       | Disponibili              |
|                                         | Blocco conservazione          | Disponibili              |
|                                         | Importazione PST                      | Disponibili              |
|                                         | Etichette di conservazione manuali non registrate            | Disponibili |
|                                         | Etichette di conservazione predefinite per SharePoint/OneDrive per le raccolte di business, le cartelle e i set di documenti. Cassette postali di Exchange; e gruppi di Office 365 | Disponibili              |
|                                         | Criteri di conservazione per l'intera organizzazione; percorsi o utenti specifici; e automaticamente in base a una condizione specifica (ad esempio, parole chiave o informazioni riservate)                                       | Disponibili              |
|                                         | Criteri di conservazione con classificatore addestrabile                            | In ingegneria backlog |
|                                         | Criteri di conservazione per Yammer e teams                            | In ingegneria backlog |
|                                         | Etichette di record manuali                           | Disponibili              |
|                                         | Etichette di record predefinite per SharePoint, raccolte di OneDrive for business, cartelle e set di documenti. e gruppi di Office 365                              | Disponibili              |
|                                         | Criteri di registrazione automatici basati su specifiche condizioni (ad esempio, parole chiave o informazioni riservate); e in base a un evento                            | Disponibili              |
|                                         | Revisione per l'eliminazione  | Disponibili              |
|                                         | Gestione del piano di archiviazione    | Disponibili |
|                                         | Prova dello smaltimento                            | Disponibili |
|                                         | Record normativi                         | In ingegneria backlog |
|                                         | Applicazione delle licenze per la gestione dei record                           | In ingegneria backlog |
|                                         | Revisione delle funzionalità di gestione dei record in più fasi | In ingegneria backlog |
|                                         | Esplora attività con etichette | In ingegneria backlog |
|                                         | Classificatori sottoponibili a training | In ingegneria backlog |
|                                         | Etichettatura unificata e etichette di riservatezza         | In ingegneria backlog |
| **Gestione dei rischi Insider**             | Customer Lockbox                                | Disponibili            |
|                                         | Indicatori di Office per Team, siti di SharePoint, messaggi di posta elettronica                         | Distribuzione |
|                                         | Furto dei dati da parte degli utenti                        | Distribuzione |
|                                         | Perdite di dati generali                                | Distribuzione              |
|                                         | Esaminare gli avvisi di gestione dei rischi Insider                                   | Distribuzione              
|                                         | Dashboard del caso di gestione dei rischi Insider, Content Explorer e modelli di avviso | Distribuzione |
|                                         | Escalation per l'analisi per Advanced eDiscovery | Distribuzione|
|                                         | Perdite di dati da parte di utenti prioritari (anteprima) | in ingegneria backlog |
|                                         | Perdite di dati da parte di utenti scontenti (anteprima) | in ingegneria backlog |
|                                         | Violazioni generali dei criteri di sicurezza (anteprima) | in ingegneria backlog |
|                                         | Violazioni dei criteri di sicurezza per gli utenti con priorità, la partenza degli utenti, gli utenti scontenti (anteprima) | in ingegneria backlog |
|                                         | Personalizzazione del criterio (anteprima) | in ingegneria backlog |
|                                         | Avvisi di esportazione (anteprima) | in ingegneria backlog |
|                                         | Gruppi di utenti prioritari (anteprima) | in ingegneria backlog |
|                                         | Creare criteri per i clienti, 3 preconfigurati per la conformità alla comunicazione (inclusi i criteri di supervisione)  | Distribuzione |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione) supporto per il messaggio teams, Exchange e Remove Teams | Distribuzione |
|                                         | Conformità alla comunicazione (compresi i criteri di supervisione) accedere agli avvisi; modelli di avviso; Dashboard per i criteri di comunicazione | Distribuzione  |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione) escalation per le indagini per Advanced eDiscovery | Distribuzione |
|                                         | Conformità alla comunicazione (inclusi i criteri di supervisione) rilevare i contenuti per adulti | Distribuzione |
|                                         | Barriere informative | In ingegneria backlog |
|                                         | Gestione accessi con privilegi                    | In ingegneria backlog |
| **Scoprire & rispondere**                  | EDiscovery Core: conservazione sul posto                            | Disponibili              |
|                                         | EDiscovery di base: gestione dei casi                                 | Disponibili              |
|                                         | EDiscovery Core: ricerca                                          | Disponibili              |
|                                         | EDiscovery Core: Export                                          | Disponibili              |
|                                         | EDiscovery Core: decrittografia RMS                                  | Disponibili              |
|                                         | EDiscovery di base: esportazione nativa                                   | Disponibili              |
|                                         | EDiscovery di base: controllo                                        | Disponibili              |
|                                         | Advanced eDiscovery: elaborazione avanzata                             | Distribuzione |
|                                         | Advanced eDiscovery: Threading della posta elettronica                                 | Distribuzione |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                   | Distribuzione |
|                                         | Advanced eDiscovery: temi                                          | Distribuzione |
|                                         | Advanced eDiscovery: codifica predittiva                               | Distribuzione |
|                                         | Advanced eDiscovery: esportazione elaborata con il file di carico                 | Distribuzione |
|                                         | Advanced eDiscovery: tagging                                         | Distribuzione |
|                                         | Advanced eDiscovery: visualizzatori                                         | Distribuzione |
|                                         | Advanced eDiscovery: redazioni                                      | Distribuzione |
|                                         | Advanced eDiscovery: filtro                                       | Distribuzione |
|                                         | Advanced eDiscovery: mapping del custode al carico di lavoro                   | Distribuzione |
|                                         | Advanced eDiscovery: comunicazioni del custode                        | Distribuzione |
|                                         | Advanced eDiscovery: set di Revisione                                     | Distribuzione |
|                                         | Advanced eDiscovery: esaminare e annotare                             | Distribuzione |
|                                         | Advanced eDiscovery: ingestione non Office 365                        | Distribuzione |
|                                         | Advanced eDiscovery: rapporto termini di ricerca                              | Distribuzione |
|                                         | Audit di base                              | Disponibili |
|                                         | Controllo avanzato: accesso a eventi cruciali (ad esempio, mailitemsaccessed)                              | Distribuzione |
|                                         | Conservazione avanzata dei log di controllo (1 anno)                               | Distribuzione |
|                                         | Controllo avanzato maggiore larghezza di banda per l'API di gestione attività                              | Distribuzione |
|    **Gestione della conformità**            | Compliance Manager and Score                              | In ingegneria backlog |

<sup>1</sup> lo stato identificato è soggetto a modifiche man mano che i piani di progetto e le priorità vengono rivalutati.<br/>
<sup>2</sup> l'applicazione manuale delle etichette richiede la [versione 1 del client di Azure Information Protection (AIP)](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history). 


**Punto decisionale**: *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
