---
title: Domini
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica di Office 365 e altri servizi nel nome dell'azienda. Dopo aver completato la procedura guidata, la posta elettronica aziendale inizia ad arrivare in Office 365 invece che nel provider di posta elettronica corrente. Per ulteriori informazioni, vedere Aggiungere utenti e dominio in Office 365. Se si utilizza Office 365 gestito da 21Vianet, vedere Verificare il dominio.
ms.openlocfilehash: d4d2e0316960f6c3d91cbdb088bd154d6739c2f2
ms.sourcegitcommit: 4d1cc432b4ce292abeb926f88108937695ce619b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/15/2019
ms.locfileid: "37523404"
---
# <a name="domains"></a>Domini

Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica di Office 365 e altri servizi nel nome dell'azienda. Dopo aver completato la procedura guidata, la posta elettronica aziendale inizia ad arrivare in Office 365 invece che nel provider di posta elettronica corrente. Per ulteriori informazioni, vedere [Aggiungere utenti e dominio in Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Se si utilizza Office 365 gestito da 21Vianet, vedere [Verificare il dominio](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Domini personalizzati
<a name="BKMK_CustomDomains"> </a>

È possibile aggiungere fino a 900 domini alla propria sottoscrizione Office 365. Tuttavia, non è possibile aggiungere un dominio Office 365 che viene già utilizzato in un altro servizio cloud di Microsoft. Ciò significa che non è possibile aggiungere lo stesso dominio a diverse sottoscrizioni Office 365. Per ulteriori informazioni, vedere [domande frequenti sui domini](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domini di secondo e terzo livello
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Con Office 365 Enterprise e Office 365 Business, è possibile aggiungere domini di qualunque livello, inclusi domini di terzo livello come marketing.contoso.com. Vedere [Aggiungere sottodomini o più domini personalizzati in Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq). Se si utilizza Office 365 gestito da 21Vianet, vedere [Aggiungere sottodomini o più domini personalizzati in Office 365 gestito da 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Verifica e gestione dei record DNS
<a name="BKMK_ManagingDNSRecords"> </a>

Con Office 365, è possibile gestire tutti i record DNS presso il provider di hosting DNS o permettere a Office 365 di configurare e gestire i record DNS del dominio per conto dell'utente. Se si continua a gestire i record, vengono modificati i record specifici in modo che puntino ai servizi di Office 365 in base alle specifiche esigenze. Per un elenco di registrar del dominio per i quali vengono fornite indicazioni dettagliate riguardo l'aggiunta dei record, compresi i valori specifici da utilizzare per ciascun record, vedere [Creare record DNS per Office 365 quando si gestiscono i record DNS](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider). Se invece si utilizza Office 365 gestito da 21Vianet, vedere Creare record DNS in qualsiasi provider per Office 365 gestito da 21Vianet. 
  
Se Office 365 gestisce i record DNS del dominio per conto dell'utente, è necessario innanzitutto modificare l'impostazione relativa ai record servernome del dominio in modo che puntino a Office 365. A questo punto, Office 365 configura i servizi di Office 365 e i record DNS del dominio vengono gestiti presso Office 365.
  
Se il dominio è registrato presso GoDaddy, in Office 365 è possibile creare automaticamente i record necessari in GoDaddy. 
  
Indipendentemente dalla posizione in cui sono ospitati i record DNS, è possibile impostarli in modo da utilizzare il dominio per l'URL di un sito Web pubblico ospitato in Office 365 oppure presso un provider di hosting diverso. 
  
Office 365 controlla in modo proattivo i record DNS per individuare e risolvere i problemi relativi a DNS. Se i record DNS non corrispondono a ciò che si prevede di essere, si riceverà una notifica nell'interfaccia di amministrazione di Microsoft 365, insieme a informazioni che indicano come risolvere i possibili problemi identificati.
  
Per altre informazioni, vedere [Modalità di gestione dei record DNS da parte di Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq). Per Office 365 gestito da 21Vianet, vedere [Creare record DNS per Office 365 quando si gestiscono i propri record DNS](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Condivisione di un dominio
<a name="BKMK_ManagingDNSRecords"> </a>

È possibile creare un progetto pilota di Office 365 trasferendo alcuni indirizzi di posta elettronica di un dominio su Office 365 e mantenendone altri nel provider di posta elettronica precedente. Questa procedura è consigliata solo per l'utilizzo durante un progetto pilota di Office 365, poiché richiede ulteriori operazioni di installazione e presenta alcune limitazioni per i servizi di Office 365. Per ulteriori informazioni, vedere:
  
- [Eseguire una distribuzione pilota di Office 365 per una società di piccole dimensioni](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Eseguire una distribuzione pilota di Office 365 per una società di grandi dimensioni (tramite FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità
<a name="BKMK_ManagingDNSRecords"> </a>

Per visualizzare la disponibilità delle funzionalità tra i piani di Office 365, opzioni autonome e soluzioni locali, vedere [office 365 Platform Service Description](office-365-platform-service-description.md).
  

