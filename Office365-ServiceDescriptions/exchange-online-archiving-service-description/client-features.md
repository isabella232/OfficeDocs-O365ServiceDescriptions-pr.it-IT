---
title: Funzionalità client in Archiviazione Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Leggere questo articolo per informazioni sulle funzionalità client disponibili in Microsoft Exchange Online archiviazione.
ms.openlocfilehash: df71da18d5eb2304496bc72ac2556bb3cc325e50e49cccb14ba6b5191cc95b1d
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664669"
---
# <a name="client-features-in-exchange-online-archiving"></a>Funzionalità client in Archiviazione Exchange Online

Microsoft Exchange Online L'archiviazione consente agli utenti di connettersi alle cassette postali di archiviazione da un'ampia gamma di dispositivi e piattaforme. Tutta la connettività di rete all'archivio dell'utente avviene tramite Internet e le connessioni VPN (Virtual Private Network) non sono necessarie. Le organizzazioni possono pubblicare un server Client Access in locale per consentire agli utenti di accedere alla cassetta postale principale tramite Outlook Anywhere, senza richiedere una connessione VPN. Se viene richiesto l'accesso VPN per accedere alla cassetta postale principale dell'utente situata su un server in locale, tale requisito non viene modificato.
  
> [!IMPORTANT]
> Microsoft si riserva il diritto di bloccare o limitare le connessioni da qualunque software client che impatta negativamente l'integrità del Archiviazione Exchange Online servizio.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook è un programma di posta elettronica arricchito che include il supporto per il calendario, i contatti e le attività. Supporto Archiviazione Exchange Online per Outlook 2013, Outlook 2010 e Outlook 2007. Le funzionalità principali includono:
  
- **Outlook via Internet** - Outlook via Internet consente agli Outlook di connettersi a Exchange Server e Archiviazione Exchange Online tramite Internet senza bisogno di una connessione VPN. La comunicazione tra Outlook e Archiviazione Exchange Online avviene tramite un tunnel protetto da SSL, utilizzando il componente di rete di Windows RPC su HTTP.    
- **Individuazione** automatica : il Exchange di individuazione automatica configura automaticamente Outlook per l'utilizzo con Archiviazione Exchange Online. L'individuazione Outlook consente agli utenti di ricevere le impostazioni del profilo richieste direttamente da Exchange la prima volta (e Exchange intervalli fissi successivi) di accedere con il proprio indirizzo di posta elettronica e la password. 

Outlook 2010 e versioni successive e Outlook sul web fornire agli utenti tutte le funzionalità dell'archivio, nonché funzionalità correlate come i criteri di conservazione e archiviazione.
  
Outlook 2007 offre funzionalità di supporto di base per l'archivio, ma non include tutte le funzionalità di archiviazione e conformità. In Outlook 2007, ad esempio, gli utenti non possono applicare criteri di conservazione o di archiviazione agli elementi nelle loro cassette postali, ma devono basarsi su criteri configurati dall'amministratore. Gli utenti di Outlook 2007 devono disporre dell'aggiornamento cumulativo di Office 2007 del febbraio 2011 per poter accedere all'archivio.
  
> [!NOTE]
> Outlook non viene fornito con Archiviazione Exchange Online. Microsoft 365 Apps for enterprise (che include Microsoft Outlook) è incluso in alcuni piani e può essere acquistato come abbonamento separato. Per ulteriori informazioni, vedere [opzioni Microsoft 365 piano.](../office-365-platform-service-description/office-365-plan-options.md) Per ulteriori informazioni sulle Microsoft 365 Apps for enterprise, vedere la [descrizione del servizio Office applicazioni.](../office-applications-service-description/office-applications-service-description.md) 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Client supportati da Archiviazione Exchange Online

Nella tabella seguente sono elencati i client supportati da Archiviazione Exchange Online:<br><br>
  
| Client | Supporto EOA |
|:-----|:-----|
|Outlook 2013 e versioni successive  <br/> |Supporta le funzionalità più recenti in Archiviazione Exchange Online.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Supporta le funzionalità più recenti di Archiviazione Exchange Online solo fino al 13 ottobre 2020|
|Outlook 2007  <br/> |Non supportato |
|Outlook 2003  <br/> |Non supportata  <br/> |
|Outlook per Mac 2011  <br/> |Non supportata  <br/> |
|Outlook per Mac  <br/> |Supportato per l'uso con Archiviazione Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Web Services Edition  <br/> |Non supportata  <br/> |
|IMAP e POP  <br/> |Non supportata  <br/> |
|Exchange ActiveSync (dispositivi mobili)  <br/> |Non supportata  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook incluso con Microsoft Office Standard non è supportato. Per informazioni, vedere [Requisiti per la concessione delle licenze per l'archivio personale e i criteri di conservazione](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Richiede l'aggiornamento per abilitare il supporto di archiviazione. Gli utenti Outlook 2007 non possono visualizzare o applicare i criteri di conservazione e archiviazione per gli elementi nelle cassette postali di archiviazione; devono basarsi sui criteri predisposti dall'amministratore. Inoltre, gli utenti di Outlook 2007 non possono ricercare contemporaneamente la cassetta postale in locale e l'archivio. <br/> 
<sup>3</sup> Non è possibile utilizzare Outlook 2016 per Mac o Outlook per Mac per spostare o copiare cartelle, elementi del calendario, contatti, attività o note nell'archivio o visualizzarli nella cassetta postale di archiviazione, se gli elementi sono stati spostati in precedenza utilizzando qualsiasi altra versione di Outlook (ad esempio Outlook 2016 per Windows). Per ulteriori informazioni, vedere [Use your online archive with Outlook 2016 per Mac.](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238) 

## <a name="outlook-on-the-web"></a>Outlook sul Web

Outlook sul Web è una versione basata sul Web del programma di posta elettronica Outlook, che viene utilizzata con Exchange Online. Ovunque gli utenti siano connessi a Internet a casa, in ufficio o in viaggio, possono accedere alla posta elettronica &mdash; &mdash; tramite Outlook sul web.
  
Gli utenti possono accedere all'archivio accedendo Outlook sul web locale (usando lo stesso URL). L'archivio viene visualizzato insieme alla cassetta postale principale in Outlook sul web. Non esiste un modo esplicito per accedere all'archivio direttamente da Outlook sul web.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Archiviazione Exchange Online [service description](exchange-online-archiving-service-description.md).