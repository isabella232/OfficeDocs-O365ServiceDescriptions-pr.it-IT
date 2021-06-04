---
title: Servizi di messaggistica vocale
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 23cc82d51d1afcbd2662e86dd6bc2aeebfb22346
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652680"
---
# <a name="voice-message-services"></a>Servizi di messaggistica vocale

## <a name="voice-mail"></a>Posta vocale

Microsoft Exchange Online offre servizi di posta vocale con le seguenti funzionalità:
  
- Microsoft Exchange Online offre servizi di posta vocale con le seguenti funzionalità:
    
- Risposta alle chiamate (segreteria telefonica)
    
- Interfaccia utente di chiamata verso Exchange (Outlook Voice Access)
    
Interfaccia di chiamata per i chiamanti (operatore automatico)
  
I servizi di messaggistica vocale ospitati consentono a un'azienda di connettere il proprio sistema telefonico ai servizi di posta vocale forniti da Exchange Online. I messaggi vocali vengono registrati e archiviati nell'infrastruttura di Exchange Online, permettendo agli utenti di accedere ai propri messaggi vocali da Outlook, Outlook Web Access o dai telefoni cellulari. Tutte le connessioni di telefonia verso Exchange Online richiedono protocolli VoIP (Voice over IP). Gli amministratori possono connettere sistemi IP PBX locali o sistemi telefonici PBX a Exchange Online tramite gateway multimediali VoIP o SBC (Session Border Controller). Il gateway multimediale VoIP non è necessario se il cliente ha distribuito un IP PBX oppure se un PBX supporta direttamente il VoIP ed è in grado di interagire con i servizi di messaggistica vocale di Exchange. I Session Border Controller (SBC) vengono distribuiti nel perimetro della rete del cliente per connettere una rete telefonica locale e contribuire alla sicurezza delle comunicazioni (e della rete del cliente) contro i tentativi di intercettazione e intrusione. È supportata anche l'interoperabilità con le funzionalità vocali di Microsoft Lync Server 2010 e 2013.
  
- Le funzionalità dei servizi di messaggistica vocale disponibili in Exchange Online sono simili a quelle offerte in Exchange Server 2013 locale. Queste funzionalità sono:
    
- Possibilità di giocare sul cellulare da Outlook e Outlook Web App.
    
- Notifiche di chiamata senza risposta.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).
    
- Reimpostazione PIN posta vocale da Web App e Outlook (vedere l'articolo relativo a come [reimpostare il PIN della posta vocale](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)). 
    
- Regole di segreteria telefonica (vedere [Allow voice mail users to forward calls](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) for details).
    
- Segreteria telefonica protetta in Exchange Online (per informazioni dettagliate, vedere [Protect voice mail in Exchange Online).](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail)
    
- Anteprima casella vocale (vedere [Allow users to see a voice mail transcript](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) for a list of supported languages).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Accesso tramite comandi vocali a posta elettronica, calendario, contatti personali e gruppi di contatti personali.
    
- Ricerca nelle directory tramite Outlook Voice Access o un operatore automatico.
    
Per ulteriori informazioni sulle funzionalità della casella vocale, vedere [Voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> Il cliente deve fornire una connessione telefonica dalla rete PSTN (Public Switched Telephone Network) utilizzando un gateway VoIP e un PBX, un IP PBX o Skype for Business Server 2015. 
>
> Il cliente deve fornire i dispositivi hardware SBC e garantire che tali SBC siano correttamente configurati per connettersi ai servizi di posta vocale. Occorre configurare anche un livello appropriato di sicurezza utilizzando certificati e interfacce IP pubbliche e private e abilitando le corrette porte TCP attraverso i relativi firewall locali. 
>
> La segreteria telefonica ospitata è disponibile solo Exchange Online abbonati al Piano 2 e Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilità posta vocale di terze parti

Interoperabilità posta vocale di terze parti
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Integrazione con Skype for Business

Le organizzazioni possono acquistare Skype for Business Online come un servizio autonomo o come parte di Microsoft Office 365. Skype for Business 2015 locale è supportato anche. Per ulteriori informazioni su Skype for Business Online, vedere [Skype for Business Descrizione del servizio online.](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere Exchange Online [descrizione del servizio.](exchange-online-service-description.md)
