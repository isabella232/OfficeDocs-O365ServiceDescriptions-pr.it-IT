---
title: Pianificare la conformità a Microsoft 365-GCC High
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o di altre entità che gestiscono i dati che sono soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government – GCC High è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: 72819a1a2b62df681f8b08dd3049ab6d704b256e
ms.sourcegitcommit: 7ceeebe425223c2cc8d6bd26a4a79b1e1d329b6f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/14/2019
ms.locfileid: "38319504"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Pianificare la conformità a Microsoft 365-GCC High

Questa guida è destinata ai professionisti IT che stanno guidando le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o di altre entità che gestiscono i dati che sono soggetti alle normative e ai requisiti governativi, in cui l'utilizzo di Microsoft 365 Government – GCC High è appropriato per soddisfare questi requisiti.

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
> Potrebbe essere necessario trasferire le tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: **rilevanti per l'organizzazione y/n** e **soddisfano le esigenze dell'organizzazione y/n**. È quindi possibile esaminare questo elenco con i colleghi per confermare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali**:<br/>
- *Decidere se Microsoft 365 Government – GCC-High è appropriato per la propria organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government-GCC High è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra una serie di [piani governativi di Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Passaggio 2. Richiedi Microsoft 365 Government-GCC-High

Dopo aver deciso che questo servizio è appropriato per la propria organizzazione, avviare il processo di [applicazione per questo servizio](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Passaggio 3: Informazioni su Microsoft 365 Government-GCC-impostazioni di protezione predefinite elevate

È consigliabile richiedere tempo per esaminare attentamente le impostazioni di protezione e di amministratore prima di modificarle e considerare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di protezione predefinite.

**Punto decisionale**: *decidere se modificare una delle impostazioni di protezione predefinite di Microsoft 365 (GCC-High Security), in modo da poter capire in primo luogo l'impatto delle eventuali modifiche che potrebbero essere apportate.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Passaggio 4. Comprendere quali funzionalità non sono attualmente disponibili o disattivate per impostazione predefinita in Microsoft 365 Government – GCC-High<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud governativo, esistono alcune differenze tra Microsoft 365 Government – GCC-High e Enterprise plans. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili.

|                                         | Funzionalità                                         | Stato alto GCC        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Governance & di protezione delle informazioni** | Archiviazione                                       | Disponibili              |
|                                         | Etichette manuali e criteri<sup>2</sup>          | Disponibili              |
|                                         | Applicazione automatica delle etichette                      | In ingegneria backlog |
|                                         | Etichette in base ai tipi di dati riservati            | In ingegneria backlog |
|                                         | Etichette e criteri associati basati su query | In ingegneria backlog |
|                                         | Piano di archiviazione                                       | In ingegneria backlog |
|                                         | Criteri consigliati                            | In ingegneria backlog |
|                                         | Filtri di importazione intelligenti                            | In ingegneria backlog |
|                                         | Criteri di conservazione basati su eventi                           | In ingegneria backlog |
|                                         | Revisione della disposizione                              | In ingegneria backlog |
|                                         | Barriere informative                            | Disponibili              |
|                                         | Prevenzione della perdita di dati (DLP) per file e messaggi di posta elettronica  | Disponibili              |
|                                         | DLP per la chat di team e le conversazioni dei canali    | In ingegneria backlog |
| **Gestione dei rischi Insider**             | Crittografia avanzata dei messaggi                     | Disponibili              |
|                                         | Conformità delle comunicazioni                        | In ingegneria backlog |
|                                         | Archivio protetto del cliente                                | Disponibili              |
|                                         | Customer Key                                    | Disponibili              |
|                                         | Gestione accessi con privilegi                    | In ingegneria backlog |
| **Scoprire & rispondere**                  | Prenotazione sul posto                            | Disponibili              |
|                                         | Gestione dei casi                                 | Disponibili              |
|                                         | Ricerca                                          | Disponibili              |
|                                         | Esportazione                                          | Disponibili              |
|                                         | Decrittografia RMS                                  | Disponibili              |
|                                         | Esportazione nativa                                   | Disponibili              |
|                                         | Elaborazione avanzata                             | Disponibili              |
|                                         | Threading posta elettronica                                 | In ingegneria backlog |
|                                         | Quasi identificazione duplicata                   | In ingegneria backlog |
|                                         | Temi                                          | In ingegneria backlog |
|                                         | Codifica predittiva                               | In ingegneria backlog |
|                                         | Esportazione elaborata con il file di carico                 | In ingegneria backlog |
|                                         | Aggiunta di tag                                         | In ingegneria backlog |
|                                         | Spettatori                                         | In ingegneria backlog |
|                                         | Redazioni                                      | In ingegneria backlog |
|                                         | Filtro                                       | In ingegneria backlog |
|                                         | Mapping del custode al carico di lavoro                   | In ingegneria backlog |
|                                         | Comunicazioni del custode                        | In ingegneria backlog |
|                                         | Set di Revisione                                     | In ingegneria backlog |
|                                         | Esaminare e annotare                             | In ingegneria backlog |
|                                         | Ingestione non Office 365                        | In ingegneria backlog |
|                                         | Rapporto termini di ricerca                              | In ingegneria backlog |

<sup>1</sup> lo stato identificato è soggetto a modifiche man mano che i piani di progetto e le priorità vengono rivalutati.<br/>
<sup>2</sup> l'applicazione manuale delle etichette richiede la [versione 1 del client di Azure Information Protection (AIP)](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history). 


**Punto decisionale**: *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
