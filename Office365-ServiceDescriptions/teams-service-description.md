---
title: Descrizione del servizio Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Informazioni sulla disponibilità Microsoft Teams servizio e funzionalità tra Microsoft 365 e Office 365 piani.
ms.openlocfilehash: 0c1a7e833e257f9dff2f4123cc5142b99a85cf9799bc2e526d8d6e4d9e90f8ed
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702905"
---
# <a name="microsoft-teams-service-description"></a>Descrizione del servizio Microsoft Teams

Microsoft Teams è l'hub per il lavoro di squadra in Microsoft 365. Il Teams consente la messaggistica istantanea, le chiamate audio e video, le riunioni online avanzate, le esperienze per dispositivi mobili e le ampie funzionalità di conferenza Web. Inoltre, Teams offre funzionalità di collaborazione ed estendibilità di file e dati e si integra con Microsoft 365 e altre app Microsoft e partner.

## <a name="available-plans"></a>Piani disponibili

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Microsoft Stream, vedi la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="feature-availability"></a>Disponibilità delle funzionalità

Nella tabella seguente sono elencate le principali Microsoft Teams disponibili tra i piani. Si applicano alcune avvertenze. Per ulteriori informazioni, vedi le note a piè di pagina. La tabella è soggetta a modifica senza preavviso. Fare riferimento a Microsoft 365 notifiche del Centro messaggi per la messaggistica di modifica del servizio di base e alla documentazione di riferimento sulle condizioni [di licenza Microsoft.](https://www.microsoft.com/licensing/product-licensing/products)<br><br>

| Funzionalità | Azienda di piccole dimensioni | Enterprise piani | GCC | GCC - Alta | DOD | Formazione |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat |Sì |Sì |Sì |Sì |Sì |Sì |
|Teams |Sì|Sì|Sì|Sì<sup>1</sup> |Sì<sup>1</sup> |Sì |
|Canali - Standard |Sì |Sì |Sì |Sì |Sì |Sì |
|Canali - Privati |Sì |Sì<sup>2</sup> |Sì|No |No|Sì |
|Riunioni |Sì |Sì |Sì |Sì |Sì |Sì |
|Webinar |Sì |Sì |No |No |No |Sì |
|Condivisione dello schermo PowerPoint Desktop audio/video|Sì |Sì |Sì |Sì |Sì |Sì |
|Voce |Sì |Sì |Sì |Sì<sup>3</sup> |Sì<sup>3</sup> |Sì |
|Audioconferenza |Sì |Sì |Sì |Sì<sup>3</sup> |Sì<sup>3</sup> |Sì |
|App, bot, & connettori |Sì |Sì |Sì<sup>5</sup> |Sì<sup>5</sup> |Sì<sup>4,5</sup> |Sì |
|Eventi live |No |Sì |Sì |No<sup>6</sup> |No<sup>6</sup> |Sì |

<sup>1</sup> Microsoft Teams in GCC-High e DOD supportano 2500 membri in un singolo team.<br/>
<sup>2</sup> Microsoft Planner non è attualmente disponibile per l'accesso nei canali privati.<br/>
<sup>3</sup> Il routing diretto deve essere configurato per Microsoft Teams audioconferenza e vocali per funzionare in GCCH e DoD.<br/>
<sup>4</sup> Microsoft OneNote non è disponibile nei cloud DOD.<br/>
<sup>5</sup> Le applicazioni di terze parti e la pubblicazione di applicazioni non sono attualmente disponibili in questi cloud.<br/>
<sup>6</sup> Gli eventi live non sono disponibili in GCC-High o DOD al momento.<br/>

## <a name="learn-more"></a>Altre informazioni

Skype for Business Online verrà ritirato il 31 luglio 2021, annunciato il 30 luglio 2019. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams è un servizio completamente nuovo, creato per il cloud da zero sfruttando Azure e altre innovazioni di servizio di Microsoft. Microsoft Teams è basato su Microsoft 365, Microsoft Graph e con la stessa sicurezza, conformità e gestibilità a livello aziendale del resto della Office 365. Teams sfrutta le identità archiviate in Azure Active Directory (Azure AD). Questi servizi sono disponibili dai data center Microsoft e sono accessibili agli utenti su un'ampia gamma di dispositivi dall'interno di una rete aziendale o tramite Internet. Per ulteriori informazioni, vedere i poster relativi [Microsoft Teams'architettura IT e alle soluzioni di telefonia.](/microsoftteams/teams-architecture-solutions-posters)

Microsoft si impegna a garantire la sicurezza dei dati e la [l'accessibilità](https://www.microsoft.com/trust-center/compliance/accessibility) dei propri servizi. Per ulteriori informazioni, vedi il [Centro protezione Microsoft](https://www.microsoft.com/trust-center)e l’[Office Accessibility Center](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).

Per informazioni dettagliate sui piani sulle sottoscrizioni che consentono agli utenti di Microsoft Teams, vedere la tabella di confronto [completa delle sottoscrizioni.](https://go.microsoft.com/fwlink/?linkid=2139145) Per ulteriori Office 365 nei piani per enti pubblici, vedere [Office 365 Government plan](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). Office 365 Da G1 a G5 includono l'accesso Teams funzionalità.

Per istruzioni dettagliate sull'implementazione delle funzionalità del [prodotto, vedere](/MicrosoftTeams)la documentazione Microsoft Teams admin . Questa descrizione del servizio dettaglia le differenze principali tra i servizi forniti nelle varie installazioni cloud. Microsoft Teams funzionalità principali non differiscono tra le sottoscrizioni. La disponibilità delle funzionalità di conformità dipende dal livello di sottoscrizione. Per ulteriori informazioni, vedere [Sicurezza e conformità in Microsoft Teams.](/microsoftteams/security-compliance-overview) Per un elenco dettagliato delle funzionalità disponibili in ogni sottoscrizione, vedere Microsoft 365 [e Office 365 del servizio della piattaforma](/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description).

**Funzionalità vocali cloud:** Per le audioconferenze, l'organizzazione deve acquistare e assegnare una licenza di audioconferenza a ogni utente che configura le riunioni con accesso esterno. Per Teams che richiedono piani di chiamata, ogni utente ha bisogno di un sistema telefonico e di un piano per chiamate nazionali o nazionali e internazionali. Per ulteriori informazioni, [vedere Microsoft Teams licenze dei componenti aggiuntivi.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

**Eventi live:** Questa offerta in Office 365 sostituisce il Riunione Skype Broadcast ritirato. Le funzionalità degli eventi live sono disponibili per i piani di licenza, come descritto nel servizio Stream. Leggi i dettagli [sulla licenza di Microsoft Stream qui](/stream/license-overview). È possibile accedere al servizio Eventi live tramite Stream, Yammer o Microsoft Teams. Per altre informazioni sulle funzionalità degli eventi live, vedi Eventi live tra Microsoft 365 [in Yammer, Microsoft Teams e Microsoft Stream.](/stream/live-event-m365)

Tutti i piani di sottoscrizione supportati sono idonei per l'accesso Microsoft Teams client Web, client desktop e app per dispositivi mobili.

Microsoft Teams non è disponibile come servizio autonomo.

Per informazioni tecniche su Microsoft Teams, vedere le risorse seguenti:

- Iniziare a pianificare la Microsoft Teams distribuzione visitando la [Microsoft Teams tecnica](https://aka.ms/SuccessWithTeams)
- Per ulteriori informazioni sulle funzionalità Teams per piattaforma del sistema operativo, vedere l'articolo Teams funzionalità per piattaforma [per piattaforma](https://aka.ms/teamsfeaturesbyplatform)
- Rimanere aggiornati sulle funzionalità Teams e sulle funzionalità, partecipando alla community e [visitando il nostro blog Microsoft Teams web](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Condizioni di licenza

Per le condizioni di licenza di prodotti e servizi acquistati tramite i Contratti multilicenza commerciali di Microsoft, consulta il [sito Condizioni del prodotto](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Messaggistica

Per tenere traccia delle modifiche imminenti, comprese le funzionalità nuove e modificate, la manutenzione pianificata o altri annunci importanti, visita il Centro messaggi. Per ulteriori informazioni, vedi [Centro messaggi](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Accessibilità

Microsoft si impegna a garantire la sicurezza dei dati e la [l'accessibilità](https://www.microsoft.com/trust-center/compliance/accessibility) dei propri servizi. Per ulteriori informazioni, vedi il [Centro protezione Microsoft](https://www.microsoft.com/trust-center)e l’[Office Accessibility Center](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
