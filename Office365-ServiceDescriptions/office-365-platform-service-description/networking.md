---
title: Rete
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 supporta le seguenti funzionalità di rete.
ms.openlocfilehash: 8a9a8d8b5276f4f4578fec625849410268f855ad
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035979"
---
# <a name="networking"></a><span data-ttu-id="aa2a8-103">Rete</span><span class="sxs-lookup"><span data-stu-id="aa2a8-103">Networking</span></span>

<span data-ttu-id="aa2a8-104">Microsoft Office 365 supporta le seguenti funzionalità di rete.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="aa2a8-105">Porte, protocolli e indirizzi IP</span><span class="sxs-lookup"><span data-stu-id="aa2a8-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="aa2a8-p101">Office 365 utilizza gli indirizzi IPv4 e IPv6. L'utilizzo degli indirizzi IPv6 è facoltativo e non richiesto per la connettività con Office 365. Non tutte le funzionalità di Office 365 vengono abilitate completamente quando si utilizza IPv6. Per ulteriori informazioni sul supporto di IPv6 in Office 365, vedere [Supporto IPv6 nei servizi di Office 365](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span></span>
  
<span data-ttu-id="aa2a8-p102">Office 365 conserva l'elenco degli indirizzi IP consentiti nella guida di Office 365. Per ulteriori informazioni, vedere [URL e intervalli di indirizzi IP per Office 365](https://go.microsoft.com/fwlink/p/?LinkID=243567). Per Office 365 gestito da 21Vianet, vedere [URL e indirizzi IP per Office 365 gestito da 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Per Office 365 Germany, vedere [Endpoint di Office 365 Germany](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://go.microsoft.com/fwlink/p/?LinkID=243567). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="aa2a8-p103">Si consiglia di abilitare il reindirizzamento a nomi di dominio radice elencati negli articoli preedenti (quali \*.Outlook.com, \*.MicrosoftOnline.com e \*.SharePoint.com) anzichè a subnet con specifichi indirizzi IP. L'utilizzo di indirizzi IP di subnet potrebbe comportare il rischio di interruzioni per gli utenti in caso di modifiche.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="aa2a8-116">Requisiti relativi alla larghezza di banda</span><span class="sxs-lookup"><span data-stu-id="aa2a8-116">Bandwidth requirements</span></span>

<span data-ttu-id="aa2a8-117">Per informazioni sui requisiti relativi alla larghezza di banda, vedere [Pianificazione della larghezza di banda di Internet](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="aa2a8-118">Connessione a Office 365</span><span class="sxs-lookup"><span data-stu-id="aa2a8-118">Connecting to Office 365</span></span>

<span data-ttu-id="aa2a8-p104">Tutte le connessioni verso Office 365 vengono eseguite tramite Internet o tramite una connessione Azure ExpressRoute privata e sono protette da SSL, se necessario. ExpressRoute Azure consente di connettersi direttamente alla rete globale di Microsoft, senza ricorrere a Internet. Un partner di rete Microsoft offre connettività alla rete globale Microsoft.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p104">All Connections to Office 365 are done over the public Internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate. Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the Internet. A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="aa2a8-122">Per ulteriori informazioni su Azure ExpressRoute, vedere [Azure ExpressRoute per Office 365.](https://aka.ms/expressrouteoffice365)</span><span class="sxs-lookup"><span data-stu-id="aa2a8-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="aa2a8-123">Acceleratori WAN</span><span class="sxs-lookup"><span data-stu-id="aa2a8-123">WAN accelerators</span></span>

<span data-ttu-id="aa2a8-p105">Microsoft non fornisce il supporto per i dispositivi di memorizzazione nella cache e accelerazione WAN di proprietà del cliente con Office 365. Se si sceglie di utilizzare un controller di ottimizzazione WAN per migliorare le prestazioni in caso di alta latenza o larghezza di banda ridotta, è necessario disabilitarlo in caso di richieste di assistenza a Microsoft e rivolgersi al fornitore per il supporto del dispositivo. Per ulteriori informazioni, vedere [Dispositivi di memorizzazione nella cache e accelerazione WAN con Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="aa2a8-127">Rete globale di Microsoft</span><span class="sxs-lookup"><span data-stu-id="aa2a8-127">The global Microsoft network</span></span>

<span data-ttu-id="aa2a8-p106">L'infrastruttura di rete di Office 365 è costituita da un portfolio di dimensioni notevoli di datacenter, server, reti per la distribuzione dei contenuti, nodi di calcolo perimetrali e reti a fibre ottiche per garantire una distribuzione globale dei servizi. Il monitoraggio e i sofisticati strumenti di servizio si integrano con ciascun componente, garantendo la visibilità su datacenter, struttura di rete e scambi su Internet e molto altro ancora per facilitare l'individuazione, la diagnosi e la gestione degli eventuali problemi riscontrati. La rete è stata costruita in modo da garantire una capacità sufficiente anche in caso di interruzioni su larga scala, senza che questo provochi una riduzione delle prestazioni. Per ulteriori informazioni, vedere [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p106">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services. Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise. The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance. For more information, see [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span></span> 
  
<span data-ttu-id="aa2a8-p107">Per mantenere la riservatezza e l'integrità dei dati dei clienti, Microsoft mantiene le reti dedicate ai servizi ai clienti separate dalle reti di Office 365. Per controllare il flusso delle informazioni sono applicate diverse tecniche, tra cui:</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="aa2a8-p108">Separazione fisica. I segmenti di rete sono separati fisicamente da router configurati per evitare determinati modelli di comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="aa2a8-p109">Separazione logica. La tecnologia VLAN (LAN virtuale) viene utilizzata per separare ulteriormente le comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="aa2a8-p110">Firewall. I firewall e altri punti di applicazione della protezione della rete vengono utilizzati per limitare lo scambio di dati con i sistemi connessi a Internet e per isolare i sistemi dai sistemi back-end gestiti da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-p110">Firewalls. Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the Internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="aa2a8-140">Limitazioni dei protocolli.</span><span class="sxs-lookup"><span data-stu-id="aa2a8-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="aa2a8-141">Per ulteriori informazioni, visitare il [Centro protezione di Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-141">For more information, see the [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="aa2a8-142">Disponibilità delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="aa2a8-142">Feature availability</span></span>

<span data-ttu-id="aa2a8-143">Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, vedere [Descrizione dei servizi della piattaforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span><span class="sxs-lookup"><span data-stu-id="aa2a8-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

