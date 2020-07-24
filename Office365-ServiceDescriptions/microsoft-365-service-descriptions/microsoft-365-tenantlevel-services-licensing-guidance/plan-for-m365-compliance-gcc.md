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
ms.openlocfilehash: 1e172588c21c15bd0422edb12d5024764f56ead7
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388102"
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
> Potrebbe essere necessario trasferire le tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: **rilevanti per l'organizzazione y/n**   e **soddisfano le esigenze dell'organizzazione y/n**. È quindi possibile esaminare questo elenco con i colleghi per confermare che questo servizio soddisfi le esigenze dell'organizzazione.

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

Per soddisfare i requisiti dei clienti del cloud governativo, esistono alcune differenze tra i piani di Microsoft 365 Government-GCC e Enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili.

|                                         | **Caratteristica**                                     | **Stato GCC**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Governance & di protezione delle informazioni** | Archiviazione                                       | Disponibili              |
|                                         | Etichette manuali e criteri<sup>2</sup>          | Disponibili              |
|                                         | Applicazione automatica delle etichette                      | Disponibili              |
|                                         | Etichette in base ai tipi di dati riservati            | In ingegneria backlog |
|                                         | Etichette e criteri associati basati su query | Disponibili              |
|                                         | Piano di archiviazione                                       | Disponibili              |
|                                         | Criteri consigliati                            | In ingegneria backlog |
|                                         | Filtri di importazione intelligenti                            | In ingegneria backlog |
|                                         | Conservazione basata su eventi                           | Disponibili              |
|                                         | Revisione per l'eliminazione                              | Disponibili              |
|                                         | Barriere informative                            | Disponibili              |
|                                         | Prevenzione della perdita di dati (DLP) per file e messaggi di posta elettronica  | Disponibili              |
|                                         | DLP per la chat di team e le conversazioni dei canali    | In ingegneria backlog |
|                                         | Corrispondenza dati esatta DLP                            | In ingegneria backlog |
|                                         | Esplora attività con etichette                         | In ingegneria backlog |
|                                         | Classificatori addestrabili                           | In ingegneria backlog |
|                                         | Etichettatura unificata e etichette di riservatezza         | In ingegneria backlog |
| **Gestione dei rischi Insider**             | Crittografia avanzata dei messaggi                     | Disponibili              |
|                                         | Gestione dei rischi Insider                         | In ingegneria backlog |
|                                         | Conformità delle comunicazioni                        | In ingegneria backlog |
|                                         | Customer Lockbox                                | Disponibili              |
|                                         | Customer Key                                    | Disponibili              |
|                                         | Gestione accessi con privilegi                    | In ingegneria backlog |
| **Scoprire & rispondere**                  | EDiscovery Core: conservazione sul posto                            | Disponibili              |
|                                         | EDiscovery di base: gestione dei casi                                 | Disponibili              |
|                                         | EDiscovery Core: ricerca                                          | Disponibili              |
|                                         | EDiscovery Core: Export                                          | Disponibili              |
|                                         | EDiscovery Core: decrittografia RMS                                  | Disponibili              |
|                                         | EDiscovery di base: esportazione nativa                                   | Disponibili              |
|                                         | EDiscovery di base: controllo                                        | Disponibili              |
|                                         | Advanced eDiscovery: elaborazione avanzata                             | Disponibili |
|                                         | Advanced eDiscovery: Threading della posta elettronica                                 | Disponibili |
|                                         | Advanced eDiscovery: identificazione quasi duplicata                   | Disponibili |
|                                         | Advanced eDiscovery: temi                                          | Disponibili |
|                                         | Advanced eDiscovery: codifica predittiva                               | Disponibili |
|                                         | Advanced eDiscovery: esportazione elaborata con il file di carico                 | Disponibili |
|                                         | Advanced eDiscovery: tagging                                         | Disponibili |
|                                         | Advanced eDiscovery: visualizzatori                                         | Disponibili |
|                                         | Advanced eDiscovery: redazioni                                      | Disponibili |
|                                         | Advanced eDiscovery: filtro                                       | Disponibili |
|                                         | Advanced eDiscovery: mapping del custode al carico di lavoro                   | Disponibili |
|                                         | Advanced eDiscovery: comunicazioni del custode                        | Disponibili |
|                                         | Advanced eDiscovery: set di Revisione                                     | Disponibili |
|                                         | Advanced eDiscovery: esaminare e annotare                             | Disponibili |
|                                         | Advanced eDiscovery: ingestione non Office 365                        | Disponibili |
|                                         | Advanced eDiscovery: rapporto termini di ricerca                              | Disponibili |

<sup>1</sup> lo stato identificato è soggetto a modifiche man mano che i piani di progetto e le priorità vengono rivalutati.<br/>
<sup>2</sup> l'applicazione manuale delle etichette richiede la [versione 1 del client di Azure Information Protection (AIP)](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Punto decisionale**: *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
