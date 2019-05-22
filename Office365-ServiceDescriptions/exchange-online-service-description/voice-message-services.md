---
title: Servizi di messaggistica vocale
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: c49a55f3278465a33e0caf3120edf454d985de0c
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/22/2019
ms.locfileid: "34343025"
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
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Reimpostazione PIN posta vocale da Web App e Outlook (vedere l'articolo relativo a come [reimpostare il PIN della posta vocale](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Indicatore di messaggi in attesa (vedere l'articolo relativo a [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271795) per i dettagli). 
    
- Regole di ricezione delle chiamate (vedere le [informazioni sulle regole di ricezione delle chiamate](https://go.microsoft.com/fwlink/p/?LinkId=271796) per i dettagli). 
    
- Posta vocale protetta in Exchange Online (vedere l'argomento relativo alla [posta vocale protetta in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271797) per i dettagli). 
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Accesso tramite comandi vocali a posta elettronica, calendario, contatti personali e gruppi di contatti personali.
    
- Ricerca nelle directory tramite Outlook Voice Access o un operatore automatico.
    
For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilità posta vocale di terze parti

Interoperabilità posta vocale di terze parti
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information. 
  
## <a name="skype-for-business-integration"></a>Integrazione con Skype for Business

Le organizzazioni possono acquistare Skype for Business Online come un servizio autonomo o come parte di Microsoft Office 365. Per ulteriori informazioni su Skype for Business Online, vedere [Descrizione del servizio Lync Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

