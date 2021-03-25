---
title: Descrizione del servizio Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Microsoft Teams offre funzionalità di messaggistica istantanea, collaborazione su file e dati, chiamate audio e video, riunioni online avanzate, esperienze per dispositivi mobili e ampie funzionalità di conferenza Web.
ms.openlocfilehash: ba8642a3b1260767fe4884a68d79aac5a511f4c4
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/24/2021
ms.locfileid: "51174041"
---
# <a name="microsoft-teams-service-description"></a>Descrizione del servizio Microsoft Teams

Microsoft Teams è l'hub per il lavoro di squadra in Microsoft 365. Il servizio Teams consente la messaggistica istantanea, le chiamate audio e video, le riunioni online avanzate, le esperienze per dispositivi mobili e le ampie funzionalità di conferenza Web. Teams offre inoltre funzionalità di collaborazione ed estendibilità di file e dati e si integra con Microsoft 365 e altre app Microsoft e partner.

Skype for Business Online verrà ritirato il 31 luglio [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) 2021, annunciato il 30 luglio 2019. Microsoft Teams è un servizio completamente nuovo, creato per il cloud da zero sfruttando Azure e altre innovazioni di servizio di Microsoft. Microsoft Teams è basato sui gruppi di Microsoft 365, Microsoft Graph e con la stessa sicurezza, conformità e gestibilità a livello aziendale del resto di Office 365. Teams sfrutta le identità archiviate in Azure Active Directory (Azure AD). Questi servizi sono disponibili dai data center Microsoft e sono accessibili agli utenti su un'ampia gamma di dispositivi dall'interno di una rete aziendale o tramite Internet. Per ulteriori informazioni, vedere i poster relativi all'architettura IT e alle soluzioni di telefonia di [Microsoft Teams.](/microsoftteams/teams-architecture-solutions-posters)

Microsoft continua a impegnarsi per la sicurezza dei dati e [l'accessibilità](https://www.microsoft.com/trust-center/compliance/accessibility) dei nostri servizi. Per ulteriori informazioni, vedere Centro protezione [Microsoft](https://www.microsoft.com/trust-center) e [Centro accessibilità di Office.](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Microsoft Teams, vedere la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145) Per altri piani di Office 365 per enti pubblici, vedere Piani di [Office 365 Per enti pubblici](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). Office 365 G1 e G5 includono l'accesso alle funzionalità di Teams.

Per informazioni dettagliate sull'implementazione delle funzionalità del prodotto, vedere la [documentazione dell'amministratore di Microsoft Teams.](/MicrosoftTeams) Questa descrizione del servizio dettaglia le differenze principali tra i servizi forniti nelle varie installazioni cloud. Le funzionalità principali di Microsoft Teams non differiscono tra le sottoscrizioni. La disponibilità delle funzionalità di conformità dipende dal livello di sottoscrizione. Per ulteriori informazioni, vedere [Sicurezza e conformità in Microsoft Teams.](/microsoftteams/security-compliance-overview) Per un elenco dettagliato delle funzionalità disponibili in ogni sottoscrizione, vedere Descrizione del servizio della piattaforma [Microsoft 365 e Office 365.](./office-365-platform-service-description/office-365-platform-service-description.md)

**Funzionalità vocali cloud:** per le audioconferenze, l'organizzazione deve acquistare e assegnare una licenza di audioconferenza a ogni utente che configura le riunioni con accesso esterno. Per le funzionalità di Teams che richiedono piani di chiamata, ogni utente ha bisogno di un sistema telefonico e di un piano per chiamate nazionali o nazionali e internazionali. Per ulteriori informazioni, vedere [Licenze per i componenti aggiuntivi di Microsoft Teams.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

**Eventi live:** questa offerta in Office 365 sostituisce Skype Meeting Broadcast ritirato. Le funzionalità degli eventi live sono disponibili per i piani di licenza, come descritto nel servizio Stream. Leggi i dettagli [sulla licenza di Microsoft Stream qui](/stream/license-overview). È possibile accedere al servizio Eventi live tramite Stream, Yammer o Microsoft Teams. Per altre informazioni sulle funzionalità degli eventi live, vedi Eventi live in [Microsoft 365 in Yammer, Microsoft Teams e Microsoft Stream.](/stream/live-event-m365)

Tutti i piani di sottoscrizione supportati sono idonei per l'accesso al client Web, ai client desktop e alle app per dispositivi mobili di Microsoft Teams.

Microsoft Teams non è disponibile come servizio autonomo.

## <a name="feature-category-reference"></a>Informazioni di riferimento sulla categoria di funzionalità

Questa tabella elenca la disponibilità delle funzionalità di Microsoft Teams nei piani di licenza o nelle istanze cloud. Si applicano alcune avvertenze. Per ulteriori informazioni, vedere le note a piè di pagina. Questa tabella può cambiare senza preavviso. Fare riferimento alle notifiche del Centro messaggi di Microsoft 365 per la messaggistica di modifica del servizio di base e alla documentazione di riferimento sulle condizioni [di licenza Microsoft.](https://www.microsoft.com/licensing/product-licensing/products)<br><br>

| Funzionalità | Azienda di piccole dimensioni | Piani aziendali | GCC | GCC - High | DOD | Istruzione |
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

> <sup>1</sup>  Microsoft Teams in GCC-High e DOD supportano 2500 membri in un singolo team.<br/>
> <sup>2</sup> Microsoft Planner non è attualmente disponibile per l'accesso nei canali privati.<br/>
> <sup>3</sup> Il routing diretto deve essere configurato perché le audioconferenze vocali e audio di Microsoft Teams funzionino in GCCH e DoD.<br/>
> <sup>4</sup> Microsoft OneNote non è disponibile nei cloud DOD.<br/>
> <sup>5</sup> Le applicazioni di terze parti e la pubblicazione di applicazioni non sono attualmente disponibili in questi cloud.<br/>
> <sup>6</sup> Gli eventi live non sono disponibili in GCC-High o DOD al momento.<br/>

## <a name="next-steps"></a>Passaggi successivi

Iniziare a pianificare la distribuzione di Microsoft Teams visitando la [documentazione tecnica di Microsoft Teams.](/MicrosoftTeams/) Rimanere aggiornati sulle funzionalità e sulle funzionalità di Teams partecipando alla community e [visitando il blog di Microsoft Teams.](https://aka.ms/TeamsBlog)

Per ulteriori informazioni sulle funzionalità di Teams in base alla piattaforma del sistema operativo, vedere l'articolo sulle funzionalità [di Teams per piattaforma.](https://aka.ms/teamsfeaturesbyplatform)