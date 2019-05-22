---
title: Rete
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 supporta le funzionalità di rete seguenti.
ms.openlocfilehash: 0a7956b5d59082f2f04f71ee2e349c2c3b238c83
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/22/2019
ms.locfileid: "34343625"
---
# <a name="networking"></a>Rete

Microsoft Office 365 supporta le funzionalità di rete seguenti.
  
## <a name="ports-protocols-and-ip-addresses"></a>Porte, protocolli e indirizzi IP

Office 365 utilizza gli indirizzi IPv4 e IPv6. L'utilizzo degli indirizzi IPv6 è facoltativo e non richiesto per la connettività con Office 365. Non tutte le funzionalità di Office 365 vengono abilitate completamente quando si utilizza IPv6. Per ulteriori informazioni sul supporto di IPv6 in Office 365, vedere [Supporto IPv6 nei servizi di Office 365](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).
  
Office 365 conserva l'elenco degli indirizzi IP consentiti nella guida di Office 365. Per ulteriori informazioni, vedere [URL e intervalli di indirizzi IP per Office 365](https://go.microsoft.com/fwlink/p/?LinkID=243567). Per Office 365 gestito da 21Vianet, vedere [URL e indirizzi IP per Office 365 gestito da 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Per Office 365 Germany, vedere [Endpoint di Office 365 Germany](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Si consiglia di abilitare il reindirizzamento a nomi di dominio radice elencati negli articoli preedenti (quali \*.Outlook.com, \*.MicrosoftOnline.com e \*.SharePoint.com) anzichè a subnet con specifichi indirizzi IP. L'utilizzo di indirizzi IP di subnet potrebbe comportare il rischio di interruzioni per gli utenti in caso di modifiche. 
  
## <a name="bandwidth-requirements"></a>Requisiti di larghezza di banda

Per informazioni sui requisiti relativi alla larghezza di banda, vedere [Pianificazione della larghezza di banda di Internet](https://go.microsoft.com/fwlink/p/?LinkID=282467).
  
## <a name="connecting-to-office-365"></a>Connessione a Office 365

Tutte le connessioni verso Office 365 vengono eseguite tramite Internet o tramite una connessione Azure ExpressRoute privata e sono protette da SSL, se necessario. ExpressRoute Azure consente di connettersi direttamente alla rete globale di Microsoft, senza ricorrere a Internet. Un partner di rete Microsoft offre connettività alla rete globale Microsoft.
  
Per ulteriori informazioni su Azure ExpressRoute, vedere [Azure ExpressRoute per Office 365.](https://aka.ms/expressrouteoffice365)
  
### <a name="wan-accelerators"></a>Acceleratori WAN

Microsoft non fornisce il supporto per i dispositivi di memorizzazione nella cache e accelerazione WAN di proprietà del cliente con Office 365. Se si sceglie di utilizzare un controller di ottimizzazione WAN per migliorare le prestazioni in caso di alta latenza o larghezza di banda ridotta, è necessario disabilitarlo in caso di richieste di assistenza a Microsoft e rivolgersi al fornitore per il supporto del dispositivo. Per ulteriori informazioni, vedere [Dispositivi di memorizzazione nella cache e accelerazione WAN con Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).
  
## <a name="the-global-microsoft-network"></a>Rete globale di Microsoft

L'infrastruttura di rete di Office 365 è costituita da un portfolio di dimensioni notevoli di datacenter, server, reti per la distribuzione dei contenuti, nodi di calcolo perimetrali e reti a fibre ottiche per garantire una distribuzione globale dei servizi. Il monitoraggio e i sofisticati strumenti di servizio si integrano con ciascun componente, garantendo la visibilità su datacenter, struttura di rete e scambi su Internet e molto altro ancora per facilitare l'individuazione, la diagnosi e la gestione degli eventuali problemi riscontrati. La rete è stata costruita in modo da garantire una capacità sufficiente anche in caso di interruzioni su larga scala, senza che questo provochi una riduzione delle prestazioni. Per ulteriori informazioni, vedere [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622). 
  
Per mantenere la riservatezza e l'integrità dei dati dei clienti, Microsoft mantiene le reti dedicate ai servizi ai clienti separate dalle reti di Office 365. Per controllare il flusso delle informazioni sono applicate diverse tecniche, tra cui:
  
- Separazione fisica. I segmenti di rete sono separati fisicamente da router configurati per evitare determinati modelli di comunicazioni.
    
- Separazione logica. La tecnologia VLAN (LAN virtuale) viene utilizzata per separare ulteriormente le comunicazioni.
    
- Firewall. I firewall e altri punti di applicazione della protezione della rete vengono utilizzati per limitare lo scambio di dati con i sistemi connessi a Internet e per isolare i sistemi dai sistemi back-end gestiti da Microsoft. 
    
- Limitazioni dei protocolli.
    
Per ulteriori informazioni, visitare il [Centro protezione di Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282621). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, vedere [Descrizione dei servizi della piattaforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

