---
title: Funzionalità client in Archiviazione Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Archiviazione Microsoft Exchange Online consente agli utenti di connettersi alle cassette postali di archiviazione da una vasta gamma di dispositivi e piattaforme. Tutta la connettività di rete all'archivio dell'utente si verifica su Internet e le connessioni VPN (Virtual Private Network) non sono necessarie. Le organizzazioni possono pubblicare un server Client Access in locale per consentire agli utenti di accedere alla cassetta postale principale tramite Outlook Anywhere, senza richiedere una connessione VPN. Se viene richiesto l'accesso VPN per accedere alla cassetta postale principale dell'utente situata su un server in locale, tale requisito non viene modificato.
ms.openlocfilehash: dfe2ebf3b329d99f3166aa2d965603987205054c
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442501"
---
# <a name="client-features-in-exchange-online-archiving"></a>Funzionalità client in Archiviazione Exchange Online

Archiviazione Microsoft Exchange Online consente agli utenti di connettersi alle cassette postali di archiviazione da una vasta gamma di dispositivi e piattaforme. Tutta la connettività di rete all'archivio dell'utente si verifica su Internet e le connessioni VPN (Virtual Private Network) non sono necessarie. Le organizzazioni possono pubblicare un server Client Access in locale per consentire agli utenti di accedere alla cassetta postale principale tramite Outlook Anywhere, senza richiedere una connessione VPN. Se viene richiesto l'accesso VPN per accedere alla cassetta postale principale dell'utente situata su un server in locale, tale requisito non viene modificato.
  
> [!IMPORTANT]
> Microsoft si riserva il diritto di bloccare o limitare le connessioni da qualunque software client che impatta negativamente l'integrità del Archiviazione Exchange Online servizio.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook è un programma di posta elettronica arricchito che include il supporto per il calendario, i contatti e le attività. Supporto Archiviazione Exchange Online per Outlook 2013, Outlook 2010 e Outlook 2007. Le funzionalità principali includono:
  
- **Outlook via Internet** Outlook via Internet consente agli utenti di Outlook di connettersi a Exchange Server e all'archiviazione Exchange Online tramite rete senza alcuna necessità di una connessione VPN. La comunicazione tra Outlook e Archiviazione Exchange Online avviene tramite un tunnel protetto da SSL, utilizzando il componente di rete di Windows RPC su HTTP.    
- **Individuazione automatica** Il servizio Individuazione automatica di Exchange configura automaticamente Outlook per l'interazione conArchiviazione Exchange Online. Individuazione automatica consente agli utenti di Outlook di ricevere le impostazioni del profilo necessarie direttamente da Exchange la prima volta (e a intervalli fissi successivamente) che accedono con l'indirizzo di posta elettronica e la password. 

Outlook 2010 o versione successiva e Outlook Web App offrono funzionalità complete agli utenti con l'archivio, oltre a funzionalità correlate come i criteri di conservazione e di archiviazione.
  
Outlook 2007 offre funzionalità di supporto di base per l'archivio, ma non include tutte le funzionalità di archiviazione e conformità. In Outlook 2007, ad esempio, gli utenti non possono applicare criteri di conservazione o di archiviazione agli elementi nelle loro cassette postali, ma devono basarsi su criteri configurati dall'amministratore. Gli utenti di Outlook 2007 devono disporre dell'aggiornamento cumulativo di Office 2007 del febbraio 2011 per poter accedere all'archivio.
  
> [!NOTE]
> Outlook non viene fornito con Archiviazione Exchange Online. Alcuni piani di Office 365 includono Microsoft Office 365 ProPlus, che contiene Microsoft Outlook, e può essere acquistato tramite una sottoscrizione separata. Per ulteriori informazioni, consultare [Opzioni di piani di Office 365](../office-365-platform-service-description/office-365-plan-options.md). Per ulteriori informazioni su Office 365 ProPlus, vedere [Descrizione servizio applicazioni Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Client supportati da Archiviazione Exchange Online

Nella tabella seguente sono elencati i client supportati da Archiviazione Exchange Online:
  
|**Client**|**Supporto EOA**|
|:-----|:-----|
|Outlook 2010 e versioni successive  <br/> |Supporta le funzionalità più recenti in Archiviazione Exchange Online.<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Supportato per l'utilizzo con Archiviazione Exchange Online.<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |Non supportato  <br/> |
|Outlook per Mac 2011  <br/> |Non supportato  <br/> |
|Outlook per Mac  <br/> |Supportato per l'utilizzo con archiviazione Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Web Services Edition  <br/> |Non supportato  <br/> |
|IMAP e POP  <br/> |Non supportato  <br/> |
|Exchange ActiveSync (dispositivi mobili)  <br/> |Non supportata  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook incluso con Microsoft Office Standard non è supportato. Per informazioni, vedere [Requisiti per la concessione delle licenze per l'archivio personale e i criteri di conservazione](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Richiede l'aggiornamento per abilitare il supporto di archiviazione. Gli utenti Outlook 2007 non possono visualizzare o applicare i criteri di conservazione e archiviazione per gli elementi nelle cassette postali di archiviazione; devono basarsi sui criteri predisposti dall'amministratore. Inoltre, gli utenti di Outlook 2007 non possono ricercare contemporaneamente la cassetta postale in locale e l'archivio. <br/> 
<sup>3</sup> non è possibile utilizzare Outlook 2016 per Mac o Outlook per Mac per spostare o copiare cartelle, elementi del calendario, contatti, attività o note nell'archivio oppure visualizzarli nella cassetta postale di archiviazione, se gli elementi sono stati precedentemente spostati tramite qualsiasi altra versione di Outlook, ad esempio Outlook 2016 per Windows). Per ulteriori informazioni, vedere [use your online Archive with Outlook 2016 for Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App è una versione basata sul Web del programma di posta elettronica Outlook, che viene utilizzata con Exchange Online. Laddove gli utenti sono connessi a Internet, a casa, in ufficio o in viaggio, possono accedere alla posta elettronica tramite Outlook Web App.
  
Gli utenti possono anche accedere all'archivio tramite Outlook Web App in locale (utilizzando lo stesso URL). L'archivio viene visualizzato accanto alla cassetta postale principale in Outlook Web App. Non esiste alcun modo esplicito per accedere all'archivio direttamente da Outlook Web App.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Archiviazione Exchange Online](exchange-online-archiving-service-description.md).