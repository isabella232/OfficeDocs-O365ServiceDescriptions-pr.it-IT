---
title: Rete
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft supporta le seguenti funzionalità di rete.
ms.openlocfilehash: 9a10afd58fb61aafc4513baff25b9b6e4c0bb122808c56c12c98f5d62637ea76
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663079"
---
# <a name="networking"></a>Rete

Microsoft supporta le seguenti funzionalità di rete.
  
## <a name="ports-protocols-and-ip-addresses"></a>Porte, protocolli e indirizzi IP

Microsoft utilizza gli indirizzi IPv4 e IPv6. L'utilizzo degli indirizzi IPv6 è facoltativo e non richiesto per la connettività con Office 365. Non tutte Microsoft 365 funzionalità sono completamente abilitate tramite IPv6. Per ulteriori informazioni sul supporto Ipv6, vedere [Supporto IPv6 in servizi Microsoft](/office365/enterprise/ipv6-support).
  
Microsoft gestisce un elenco di indirizzi IP consentiti nella Guida di Microsoft. Per ulteriori informazioni, vedere [URL e intervalli di indirizzi IP.](/office365/enterprise/urls-and-ip-address-ranges) Per Office 365 gestito da 21Vianet, vedere [URL e indirizzi IP per Office 365 gestito da 21Vianet](/office365/enterprise/managing-office-365-endpoints). Per Office 365 Germany, vedere [Endpoint di Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Si consiglia di abilitare il reindirizzamento a nomi di dominio radice elencati negli articoli preedenti (quali \*.Outlook.com, \*.MicrosoftOnline.com e \*.SharePoint.com) anzichè a subnet con specifichi indirizzi IP. L'utilizzo di indirizzi IP di subnet potrebbe comportare il rischio di interruzioni per gli utenti in caso di modifiche. 
  
## <a name="bandwidth-requirements"></a>Requisiti di larghezza di banda

Per informazioni sui requisiti relativi alla larghezza di banda, vedere [Pianificazione della larghezza di banda di Internet](/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Connessione a Microsoft

Tutte le connessioni a Microsoft vengono eseguite tramite Internet pubblico o tramite una connessione Azure ExpressRoute privata e sono protette da SSL in base alle esigenze. Azure ExpressRoute consente di connettersi direttamente alla rete Microsoft globale, ignorando Internet. Un partner di rete Microsoft offre connettività alla rete globale Microsoft.
  
Per ulteriori informazioni su Azure ExpressRoute, vedere [Azure ExpressRoute per Office 365.](/microsoft-365/enterprise/azure-expressroute)
  
### <a name="wan-accelerators"></a>Acceleratori WAN

Microsoft non fornisce il supporto per i dispositivi di memorizzazione nella cache e accelerazione WAN di proprietà del cliente con Office 365. Se si sceglie di utilizzare un controller di ottimizzazione WAN per migliorare le prestazioni in caso di alta latenza o larghezza di banda ridotta, è necessario disabilitarlo in caso di richieste di assistenza a Microsoft e rivolgersi al fornitore per il supporto del dispositivo. Per ulteriori informazioni, vedere [Dispositivi di memorizzazione nella cache e accelerazione WAN con Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Rete globale di Microsoft

L'infrastruttura di rete Microsoft è costituita da un ampio portfolio globale di data center, server, reti di distribuzione del contenuto, nodi di elaborazione perimetrale e reti in fibra ottica per fornire la distribuzione globale dei servizi. Il monitoraggio e i sofisticati strumenti di servizio si integrano con ciascun componente, garantendo la visibilità su datacenter, struttura di rete e scambi su Internet e molto altro ancora per facilitare l'individuazione, la diagnosi e la gestione degli eventuali problemi riscontrati. La rete è stata costruita in modo da garantire una capacità sufficiente anche in caso di interruzioni su larga scala, senza che questo provochi una riduzione delle prestazioni. Per ulteriori informazioni, vedere [Microsoft Global Network.](/azure/networking/microsoft-global-network) 
  
Per mantenere la riservatezza e l'integrità dei dati dei clienti, Microsoft mantiene le reti dei servizi per i consumatori separate dalle reti Microsoft. Per controllare il flusso delle informazioni sono applicate diverse tecniche, tra cui:
  
- Separazione fisica. I segmenti di rete sono separati fisicamente da router configurati per evitare determinati modelli di comunicazioni.
    
- Separazione logica. La tecnologia VLAN (LAN virtuale) viene utilizzata per separare ulteriormente le comunicazioni.
    
- Firewall. I firewall e altri punti di imposizione della sicurezza di rete vengono utilizzati per limitare gli scambi di dati con i sistemi esposti a Internet e per isolare i sistemi dai sistemi back-end gestiti da Microsoft. 
    
- Limitazioni dei protocolli.
    
Per ulteriori informazioni, visitare il [Centro protezione di Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani, vedere [Microsoft 365 e Office 365 del servizio della piattaforma.](office-365-platform-service-description.md)
