---
title: Funzionalità client in Archiviazione Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Archiviazione di Microsoft Exchange Online consente agli utenti di connettersi alle cassette postali di archiviazione da una vasta gamma di piattaforme e dispositivi. Si verifica la connettività di rete per l'archivio dell'utente tramite Internet e connessioni di rete privata virtuale (VPN) non sono necessarie. Le organizzazioni possono pubblicare un server Accesso Client locale per consentire agli utenti di accedere alla cassetta postale principale utilizzando Outlook via Internet, senza la necessità di una connessione VPN. Se è necessario l'accesso di rete VPN per accedere alla cassetta postale principale dell'utente ubicata in un server locale, questo requisito non cambia.
ms.openlocfilehash: 90f384e990363294c8972a79e8b500d97ca4a839
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035961"
---
# <a name="client-features-in-exchange-online-archiving"></a>Funzionalità client in Archiviazione Exchange Online

Archiviazione di Microsoft Exchange Online consente agli utenti di connettersi alle cassette postali di archiviazione da una vasta gamma di piattaforme e dispositivi. Si verifica la connettività di rete per l'archivio dell'utente tramite Internet e connessioni di rete privata virtuale (VPN) non sono necessarie. Le organizzazioni possono pubblicare un server Accesso Client locale per consentire agli utenti di accedere alla cassetta postale principale utilizzando Outlook via Internet, senza la necessità di una connessione VPN. Se è necessario l'accesso di rete VPN per accedere alla cassetta postale principale dell'utente ubicata in un server locale, questo requisito non cambia.
  
> [!IMPORTANT]
> Microsoft si riserva il diritto di bloccare o limitare le connessioni da qualunque software client che impatta negativamente l'integrità del Archiviazione Exchange Online servizio. 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook è un programma di posta elettronica arricchito che include il supporto per il calendario, i contatti e le attività. Supporto Archiviazione Exchange Online per Outlook 2013, Outlook 2010 e Outlook 2007. Le funzionalità principali includono:
  
- **Outlook Anywhere** Outlook Anywhere consente agli utenti Outlook di connettersi a Exchange Server e Archiviazione Exchange Online su Internet senza bisogno di una connessione VPN. La comunicazione tra Outlook e Archiviazione Exchange Online avviene tramite un tunnel protetto da SSL, utilizzando il componente di rete di Windows RPC su HTTP. 
    
- **Individuazione automatica** Il servizio Individuazione automatica di Exchange configura automaticamente Outlook per l'interazione conArchiviazione Exchange Online. Per la prima volta, Individuazione automatica abilita gli utenti di Outlook a ricevere le impostazioni di profilo richieste direttamente da Exchange (e a intervalli fissi successivi) che accedono con il proprio indirizzo di posta elettronica e password. 
    
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
|Outlook 2003  <br/> |Non supportata  <br/> |
|Outlook per Mac 2011  <br/> |Non supportata  <br/> |
|Outlook per Mac  <br/> |Supportati da archiviazione Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008, Web Services Edition  <br/> |Non supportata  <br/> |
|IMAP e POP  <br/> |Non supportata  <br/> |
|Exchange ActiveSync (dispositivi mobili)  <br/> |Non supportata  <br/> |
   
> [!NOTE]
> <sup>1</sup> non è incluso in Microsoft Office Standard di outlook. Per ulteriori informazioni, vedere [requisiti relativi alle licenze per l'archivio personale e i criteri di conservazione](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> richiede l'aggiornamento per abilitare il supporto di archiviazione. Gli utenti di Outlook 2007 non possono visualizzare o applicare criteri di conservazione o archiviare i criteri per gli elementi nelle cassette postali di archiviazione; è necessario utilizzano criteri amministratore eseguito il provisioning. Agli utenti di Outlook 2007 è inoltre possono cercare la cassetta postale locale e l'archivio contemporaneamente. > <sup>3</sup> non è possibile utilizzare 2016 Outlook per Mac o Outlook per Mac per le cartelle di spostamento o copia, gli elementi del calendario, contatti, attività o note per l'archivio o visualizzare nella cassetta postale di archivio se gli elementi sono stati spostati in precedenza disponibili con altre versioni di Outlook ( ad esempio Outlook 2016 per Windows). Per ulteriori informazioni, vedere [Use l'archivio online con 2016 Outlook per Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App è una versione basata sul Web del programma di posta elettronica Outlook, che viene utilizzata con Exchange Online. Gli utenti connessi a Internet da casa, in ufficio o in strada possono accedere alla posta elettronica tramite Outlook Web App.
  
Gli utenti possono anche accedere all'archivio tramite Outlook Web App in locale (utilizzando lo stesso URL). L'archivio viene visualizzato accanto alla cassetta postale principale in Outlook Web App. Non esiste alcun modo esplicito per accedere all'archivio direttamente da Outlook Web App.
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Archiviazione Exchange Online](exchange-online-archiving-service-description.md).
  

