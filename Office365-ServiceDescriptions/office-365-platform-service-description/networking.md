---
title: Rete
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft supporta le funzionalità di rete seguenti.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132330"
---
# <a name="networking"></a>Rete

Microsoft supporta le funzionalità di rete seguenti.
  
## <a name="ports-protocols-and-ip-addresses"></a>Porte, protocolli e indirizzi IP

Microsoft utilizza gli indirizzi IPv4 e IPv6. L'utilizzo degli indirizzi IPv6 è facoltativo e non richiesto per la connettività con Office 365. Non tutte le funzionalità di Microsoft 365 sono abilitate completamente tramite IPv6. Per ulteriori informazioni sul supporto IPv6, vedere [supporto IPv6 nei servizi Microsoft](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
Microsoft gestisce un elenco di indirizzi IP consentiti nella Guida di Microsoft. Per ulteriori informazioni, vedere [URL e intervalli di indirizzi IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Per Office 365 gestito da 21Vianet, vedere [URL e indirizzi IP per Office 365 gestito da 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Per Office 365 Germany, vedere [Endpoint di Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>Requisiti di larghezza di banda

Per informazioni sui requisiti relativi alla larghezza di banda, vedere [Pianificazione della larghezza di banda di Internet](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Connessione a Microsoft

Tutte le connessioni a Microsoft vengono eseguite su Internet pubblico o su una connessione ExpressRoute di Azure privata e sono protette da SSL in base alle esigenze. In Azure ExpressRoute è possibile connettersi direttamente alla rete Microsoft globale, ignorando Internet. Un partner di rete Microsoft offre connettività alla rete globale Microsoft.
  
Per ulteriori informazioni su Azure ExpressRoute, vedere [Azure ExpressRoute per Office 365.](https://aka.ms/expressrouteoffice365)
  
### <a name="wan-accelerators"></a>Acceleratori WAN

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Rete globale di Microsoft

L'infrastruttura di rete Microsoft è costituita da un vasto portafoglio globale di Data Center, server, reti di distribuzione del contenuto, nodi di calcolo Edge e reti in fibra ottica per garantire la distribuzione globale dei servizi. Il monitoraggio e i sofisticati strumenti di servizio si integrano con ciascun componente, garantendo la visibilità su datacenter, struttura di rete e scambi su Internet e molto altro ancora per facilitare l'individuazione, la diagnosi e la gestione degli eventuali problemi riscontrati. La rete è stata costruita in modo da garantire una capacità sufficiente anche in caso di interruzioni su larga scala, senza che questo provochi una riduzione delle prestazioni. Per ulteriori informazioni, vedere [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Per mantenere la riservatezza e l'integrità dei dati del cliente, Microsoft mantiene le reti dei servizi consumer separate dalle reti Microsoft. Per controllare il flusso delle informazioni sono applicate diverse tecniche, tra cui:
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- Firewall. I firewall e altri punti di applicazione della sicurezza della rete vengono utilizzati per limitare gli scambi di dati con i sistemi esposti a Internet e per isolare i sistemi dai sistemi back-end gestiti da Microsoft. 
    
- Limitazioni dei protocolli.
    
Per ulteriori informazioni, visitare il [Centro protezione di Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani, vedere [Microsoft 365 e Office 365 Platform Service Description](office-365-platform-service-description.md).
  

