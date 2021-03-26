---
title: Descrizione del servizio Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Informazioni sulla disponibilità dei servizi e delle funzionalità di Microsoft Teams nei piani di Microsoft 365 e Office 365.
ms.openlocfilehash: 59eaee9a36eaff8dd79d5ff9690bf04e966f3dfe
ms.sourcegitcommit: ec02d469f5815efa65bdb4f17bd4a6f89af13d3a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/25/2021
ms.locfileid: "51215729"
---
# <a name="microsoft-teams-service-description"></a>Descrizione del servizio Microsoft Teams

Microsoft Teams è l'hub per il lavoro di squadra in Microsoft 365. Il servizio Teams consente la messaggistica istantanea, le chiamate audio e video, le riunioni online avanzate, le esperienze per dispositivi mobili e le ampie funzionalità di conferenza Web. Teams offre inoltre funzionalità di collaborazione ed estendibilità di file e dati e si integra con Microsoft 365 e altre app Microsoft e partner.

Skype for Business Online si ritira il 31 luglio [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) 2021, annunciato il 30 luglio 2019. Microsoft Teams è un servizio completamente nuovo, creato per il cloud da zero sfruttando Azure e altre innovazioni di servizio di Microsoft. Microsoft Teams è basato sui gruppi di Microsoft 365, Microsoft Graph e con la stessa sicurezza, conformità e gestibilità a livello aziendale del resto di Office 365. Teams sfrutta le identità archiviate in Azure Active Directory (Azure AD). Questi servizi sono disponibili dai data center Microsoft e sono accessibili agli utenti su un'ampia gamma di dispositivi dall'interno di una rete aziendale o tramite Internet. Per ulteriori informazioni, vedere i poster relativi all'architettura IT e alle soluzioni di telefonia di [Microsoft Teams.](/microsoftteams/teams-architecture-solutions-posters)

Questa descrizione del servizio dettaglia le differenze principali tra i servizi forniti nelle varie installazioni cloud. Le funzionalità principali di Microsoft Teams non differiscono tra le sottoscrizioni. La disponibilità delle funzionalità di conformità dipende dal livello di sottoscrizione. Per ulteriori informazioni sulla sicurezza e la conformità di Teams, vedere [Sicurezza e conformità in Microsoft Teams.](/microsoftteams/security-compliance-overview)

## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sulle sottoscrizioni che consentono agli utenti di Teams, vedere [Trovare Microsoft Teams giusto per la propria azienda.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) Ulteriori dettagli sono disponibili nella tabella di confronto [delle soluzioni Microsoft.](https://go.microsoft.com/fwlink/?linkid=2139145)

I piani per enti pubblici che supportano Teams includono Da Office 365 G1 a G5. Per ulteriori informazioni, vedere [Piani di Office 365 Government.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)

Tutti i piani di sottoscrizione supportati sono idonei per l'accesso al client Web, ai client desktop e alle app per dispositivi mobili di Microsoft Teams.

Microsoft Teams non è disponibile come servizio autonomo.

## <a name="feature-availability"></a>Disponibilità delle funzionalità

Nella tabella seguente sono elencate le principali funzionalità di Teams disponibili nei piani. Si applicano alcune avvertenze. Per ulteriori informazioni, vedere le note a piè di pagina. Questa tabella può cambiare senza preavviso.

Per ulteriori informazioni sulle funzionalità di Teams per piattaforma del sistema operativo, vedere [Funzionalità di Teams per piattaforma.](https://aka.ms/teamsfeaturesbyplatform)

Per l'elenco completo e aggiornato delle funzionalità di Teams nei piani di Microsoft 365 e Office 365, vedere [Trovare Microsoft Teams giusto per la propria azienda.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Funzionalità | Piani per piccole imprese | Piani aziendali | GCC | GCC - High | DOD | Piani didattici |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Teams  <br/> |Sì <br/> |Sì <br/> |Sì <br/> |Sì<sup>1</sup>  <br/> |Sì<sup>1</sup>  <br/> |Sì  <br/> |
|Canali - Standard  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Canali - Privati  <br/> |Sì  <br/> |Sì<sup>2</sup>  <br/> |Sì <br/> |No  <br/> |No <br/> |Sì  <br/> |
|Riunioni  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Condivisione dello schermo Desktop audio/video di PowerPoint <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |
|Voce  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì<sup>3</sup>  <br/> |Sì<sup>3</sup>  <br/> |Sì  <br/> |
|Audioconferenza  <br/> |Sì  <br/> |Sì  <br/> |Sì  <br/> |Sì<sup>3</sup>  <br/> |Sì<sup>3</sup>  <br/> |Sì  <br/> |
|App, bot, & connettori  <br/> |Sì  <br/> |Sì  <br/> |Sì<sup>5</sup>  <br/> |Sì<sup>5</sup>  <br/> |Sì<sup>4,5</sup>  <br/> |Sì  <br/> |
|Eventi live  <br/> |No  <br/> |Sì  <br/> |Sì  <br/> |No<sup>6</sup>  <br/> |No<sup>6</sup>  <br/> |Sì  <br/> |

<sup>1</sup> Microsoft Teams in GCC-High e DOD supportano 2500 membri in un singolo team.<br/>
<sup>2</sup> Microsoft Planner non è attualmente disponibile per l'accesso nei canali privati.<br/>
<sup>3</sup> Il routing diretto deve essere configurato perché le audioconferenze vocali e audio di Microsoft Teams funzionino in GCCH e DoD.<br/>
<sup>4</sup> Microsoft OneNote non è disponibile nei cloud DOD.<br/>
<sup>5</sup> Le applicazioni di terze parti e la pubblicazione di applicazioni non sono attualmente disponibili in questi cloud.<br/>
<sup>6</sup> Gli eventi live non sono disponibili in GCC-High o DOD al momento.<br/>

### <a name="cloud-voice-features"></a>Funzionalità vocali cloud

Per le audioconferenze, l'organizzazione deve acquistare e assegnare una licenza di audioconferenza a ogni utente che configura riunioni con accesso esterno. Per le funzionalità di Teams che richiedono piani di chiamata, ogni utente ha bisogno di un sistema telefonico e di un piano per chiamate nazionali o nazionali e internazionali. Per ulteriori informazioni, vedere [Licenze per i componenti aggiuntivi di Microsoft Teams.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Eventi live

Questa offerta in Office 365 sostituisce Skype Meeting Broadcast ritirato. Le funzionalità degli eventi live sono disponibili per i piani di licenza, come descritto nel servizio Stream. Per altre informazioni, consulta la panoramica [delle licenze di Microsoft Stream.](/stream/license-overview) È possibile accedere al servizio eventi live tramite Stream, Yammer o Microsoft Teams. Per altre informazioni sulle funzionalità degli eventi live, vedi Eventi live in [Microsoft 365 in Yammer, Microsoft Teams e Microsoft Stream.](/stream/live-event-m365)

## <a name="learn-more"></a>Ulteriori informazioni

Per ulteriori informazioni su Teams, vedere le risorse seguenti:
 
- [Documentazione per gli amministratori di Microsoft Teams](/MicrosoftTeams)
- [Community tecnica di Microsoft Teams](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Blog di Microsoft Teams](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Condizioni di licenza

Per le condizioni e le condizioni di licenza per i prodotti e i servizi acquistati tramite i Programmi Microsoft Commercial Volume Licensing, vedere il [sito condizioni del prodotto](https://www.microsoft.com/licensing/terms/). 

### <a name="messaging"></a>Messaggistica

Per rimanere informati sulle modifiche imminenti, incluse funzionalità nuove e modificate, manutenzione pianificata o altri annunci importanti, visitare il Centro messaggi. Per ulteriori informazioni, vedere [Centro messaggi.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>Accessibilità

Microsoft continua a impegnarsi per la sicurezza dei dati e l'accessibilità dei nostri servizi. Per ulteriori informazioni, vedere Centro protezione [Microsoft](https://www.microsoft.com/trust-center) e [Centro accessibilità di Office.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)