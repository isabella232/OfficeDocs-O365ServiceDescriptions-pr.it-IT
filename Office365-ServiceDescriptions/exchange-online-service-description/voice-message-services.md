---
title: Servizi di messaggistica vocale
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132550"
---
# <a name="voice-message-services"></a>Servizi di messaggistica vocale

## <a name="voice-mail"></a>Posta vocale

Microsoft Exchange Online offre servizi di posta vocale con le seguenti funzionalità:
  
- Microsoft Exchange Online offre servizi di posta vocale con le seguenti funzionalità:
    
- Risposta alle chiamate (segreteria telefonica)
    
- Interfaccia utente di chiamata verso Exchange (Outlook Voice Access)
    
Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.
  
The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:
  
- Le funzionalità dei servizi di messaggistica vocale disponibili in Exchange Online sono simili a quelle offerte in Exchange Server 2013 locale. Queste funzionalità sono:
    
- Possibilità di giocare sul cellulare da Outlook e Outlook Web App.
    
- Notifiche di chiamata senza risposta.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Reimpostazione PIN posta vocale da Web App e Outlook (vedere l'articolo relativo a come [reimpostare il PIN della posta vocale](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Regole di ricezione chiamata (vedere [Consenti agli utenti di posta vocale di inoltrare le chiamate](https://go.microsoft.com/fwlink/p/?LinkId=271795) per i dettagli).
    
- Casella vocale protetta in Exchange Online (vedere [Protect Voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) per i dettagli).
    
- Anteprima casella vocale (vedere [consentire agli utenti di visualizzare una trascrizione](https://go.microsoft.com/fwlink/p/?LinkId=271797) della segreteria telefonica per un elenco di lingue supportate).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Accesso tramite comandi vocali a posta elettronica, calendario, contatti personali e gruppi di contatti personali.
    
- Ricerca nelle directory tramite Outlook Voice Access o un operatore automatico.
    
Per ulteriori informazioni sulle funzionalità di segreteria telefonica, vedere segreteria telefonica [in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> Il cliente deve fornire una connessione telefonica dalla rete PSTN (Public Switched Telephone Network) utilizzando un gateway VoIP e PBX, IP PBX o Skype for Business Server 2015. 
>
> The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. 
>
> La segreteria telefonica ospitata è disponibile solo per i sottoscrittori di Exchange Online piano 2 e Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilità posta vocale di terze parti

On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Integrazione con Skype for Business

Le organizzazioni possono acquistare Skype for Business Online come un servizio autonomo o come parte di Microsoft Office 365. È supportato anche Skype for business 2015 in locale. Per ulteriori informazioni su Skype for business online, vedere [Descrizione del servizio Skype for business online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra piani, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

