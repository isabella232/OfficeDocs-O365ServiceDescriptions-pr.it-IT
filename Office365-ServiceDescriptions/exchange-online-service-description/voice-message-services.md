---
title: Servizi di messaggistica vocale
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036098"
---
# <a name="voice-message-services"></a>Servizi di messaggistica vocale

## <a name="voice-mail"></a>Posta vocale

Microsoft Exchange Online offre servizi di posta vocale con le seguenti funzionalità:
  
- Risposta alle chiamate (segreteria telefonica)
    
- Interfaccia utente di chiamata verso Exchange (Outlook Voice Access)
    
- Interfaccia utente di chiamata verso Exchange (Outlook Voice Access)
    
Interfaccia di chiamata per i chiamanti (operatore automatico)
  
I servizi di messaggistica vocale ospitati consentono a un'azienda di connettere il proprio sistema telefonico ai servizi di posta vocale forniti da Exchange Online. I messaggi vocali vengono registrati e archiviati nell'infrastruttura di Exchange Online, permettendo agli utenti di accedere ai propri messaggi vocali da Outlook, Outlook Web Access o dai telefoni cellulari. Tutte le connessioni di telefonia verso Exchange Online richiedono protocolli VoIP (Voice over IP). Gli amministratori possono connettere sistemi IP PBX locali o sistemi telefonici PBX a Exchange Online tramite gateway multimediali VoIP o SBC (Session Border Controller). Il gateway multimediale VoIP non è necessario se il cliente ha distribuito un IP PBX oppure se un PBX supporta direttamente il VoIP ed è in grado di interagire con i servizi di messaggistica vocale di Exchange. I Session Border Controller (SBC) vengono distribuiti nel perimetro della rete del cliente per connettere una rete telefonica locale e contribuire alla sicurezza delle comunicazioni (e della rete del cliente) contro i tentativi di intercettazione e intrusione. È supportata anche l'interoperabilità con le funzionalità vocali di Microsoft Lync Server 2010 e 2013.
  
- Le funzionalità dei servizi di messaggistica vocale disponibili in Exchange Online sono simili a quelle offerte in Exchange Server 2013 locale. Queste funzionalità sono:
    
- Possibilità di giocare sul cellulare da Outlook e Outlook Web App.
    
- Notifiche di chiamata senza risposta.
    
- Reimpostazione PIN posta vocale da Outlook sul web e Outlook (vedere [reimpostare il PIN posta vocale](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Reimpostazione PIN posta vocale da Web App e Outlook (vedere l'articolo relativo a come [reimpostare il PIN della posta vocale](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Regole di ricezione delle chiamate (vedere le [informazioni sulle regole di ricezione delle chiamate](https://go.microsoft.com/fwlink/p/?LinkId=271795) per i dettagli). 
    
- Posta vocale protetta in Exchange Online (vedere l'argomento relativo alla [posta vocale protetta in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) per i dettagli). 
    
- Anteprima posta vocale (per un elenco delle lingue supportate, vedere l'argomento relativo all'[anteprima della posta vocale per utenti finali](https://go.microsoft.com/fwlink/p/?LinkId=271797)). 
    
- Accesso tramite comandi vocali a posta elettronica, calendario, contatti personali e gruppi di contatti personali.
    
- Ricerca nelle directory tramite Outlook Voice Access o un operatore automatico.
    
- Gli amministratori configurano e gestiscono l'interoperabilità tra i servizi di messaggistica vocale tramite l'interfaccia di amministrazione di Exchange.
    
Per ulteriori informazioni sulle funzionalità della posta vocale, vedere l'argomento relativo alla [posta vocale in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> La funzionalità ASR (Automatic Speech Recognition) non è disponibile durante lo spostamento nei menu o la ricerca nelle directory per gli utenti di Outlook Voice Access o per i chiamanti dell'operatore automatica che utilizzano i comandi vocali. > Il cliente deve fornire una connessione telefonica alla rete pubblica commutata (PSTN) tramite gateway VoIP e PBX, IP PBX o Skype for Business Server 2015. > Il cliente deve fornire i dispositivi hardware SBC e garantire che tali SBC siano correttamente configurati per connettersi ai servizi di posta vocale. Occorre configurare anche un livello appropriato di sicurezza utilizzando certificati e interfacce IP pubbliche e private e abilitando le corrette porte TCP attraverso i relativi firewall locali. > La posta vocale ospitata è disponibile solo per i sottoscrittori di Exchange Online (piano 2) e Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilità posta vocale di terze parti

Le soluzioni di posta vocale locale di fornitori terzi possono interagire con Exchange Online, a condizione che esse siano in grado di inoltrare messaggi vocali tramite il server SMTP o supportino Microsoft Exchange Web Services. Se il sistema di posta vocale non supporta l'inoltro di messaggi vocali tramite SMTP, è possibile mantenere un server di posta elettronica locale per ricevere i messaggi dal sistema di posta vocale e quindi inoltrarli al cloud tramite SMTP. Poiché molti sistemi di posta vocale di terzi utilizzano MAPI/CDO per interagire con Exchange Server per le funzionalità più avanzate della messaggistica unificata, potrebbero non essere disponibili tutte le funzionalità di questi sistemi quando viene utilizzato il protocollo SMTP per l'interoperabilità con Exchange Online.
  
> [!NOTE]
> Supporto in linea di messaggistica unificata di Exchange per i sistemi PBX di terze parti tramite connessioni dirette dal cliente utilizzati SBCs terminerà in 2018 luglio. Per ulteriori informazioni, vedere [cessazione del supporto per i Session Border controller in Exchange Online la messaggistica unificata](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) . 
  
## <a name="skype-for-business-integration"></a>Integrazione con Skype for Business

Le organizzazioni possono acquistare Skype for Business Online come un servizio autonomo o come parte di Microsoft Office 365. Per ulteriori informazioni su Skype for Business Online, vedere [Descrizione del servizio Lync Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [Descrizione del servizio Exchange Online](exchange-online-service-description.md).
  

