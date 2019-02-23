---
title: Domini
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica e altri servizi di Office 365 nel nome dell'azienda. Al termine della procedura guidata, il messaggio di posta elettronica aziendale inizia a venire a Office 365 anziché andare al provider di posta elettronica corrente. Per ulteriori informazioni, vedere Aggiungere utenti e domini a Office 365. Se si utilizza Office 365 gestito da 21Vianet, vedere Verificare il dominio.
ms.openlocfilehash: 15254355d2bb7aed01d7be8c8e56d455409a51a5
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210239"
---
# <a name="domains"></a>Domini

Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica e altri servizi di Office 365 nel nome dell'azienda. Al termine della procedura guidata, il messaggio di posta elettronica aziendale inizia a venire a Office 365 anziché andare al provider di posta elettronica corrente. Per ulteriori informazioni, vedere [aggiungere utenti e domini a Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Se si utilizza Office 365 gestito da 21Vianet, vedere [verificare il dominio](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409).
  
## <a name="custom-domains"></a>Domini personalizzati
<a name="BKMK_CustomDomains"> </a>

È possibile aggiungere fino a 900 domini all'abbonamento a Office 365. Tuttavia, non è possibile aggiungere un dominio a Office 365 che si sta già utilizzando in un altro servizio cloud Microsoft. Ciò significa che non è possibile aggiungere lo stesso dominio a più sottoscrizioni di Office 365. Per ulteriori informazioni, vedere [domande frequenti sui domini](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domini di secondo e terzo livello
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Con Office 365 Enterprise e Office 365 Business, è possibile aggiungere domini di qualunque livello, inclusi domini di terzo livello come marketing.contoso.com. Vedere [Aggiungere sottodomini o più domini personalizzati in Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409). Se si utilizza Office 365 gestito da 21Vianet, vedere [Aggiungere sottodomini o più domini personalizzati in Office 365 gestito da 21Vianet](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409).
  
## <a name="domain-verification-and-managing-dns-records"></a>Verifica e gestione dei record DNS
<a name="BKMK_ManagingDNSRecords"> </a>

Con Office 365, è possibile gestire tutti i record DNS presso il provider di hosting DNS o permettere a Office 365 di configurare e gestire i record DNS del dominio per conto dell'utente. Se si continua a gestire i record, vengono modificati i record specifici in modo che puntino ai servizi di Office 365 in base alle specifiche esigenze. Per un elenco di registrar del dominio per i quali vengono fornite indicazioni dettagliate riguardo l'aggiunta dei record, compresi i valori specifici da utilizzare per ciascun record, vedere [Creare record DNS per Office 365 quando si gestiscono i record DNS](https://go.microsoft.com/fwlink/p/?LinkID=270173). Se invece si utilizza Office 365 gestito da 21Vianet, vedere Creare record DNS in qualsiasi provider per Office 365 gestito da 21Vianet. 
  
Se Office 365 gestisce i record DNS del dominio per conto dell'utente, è necessario innanzitutto modificare l'impostazione relativa ai record servernome del dominio in modo che puntino a Office 365. A questo punto, Office 365 configura i servizi di Office 365 e i record DNS del dominio vengono gestiti presso Office 365.
  
Se il dominio è registrato presso GoDaddy, in Office 365 è possibile creare automaticamente i record necessari in GoDaddy. 
  
Indipendentemente dalla posizione in cui sono ospitati i record DNS, è possibile impostarli in modo da utilizzare il dominio per l'URL di un sito Web pubblico ospitato in Office 365 oppure presso un provider di hosting diverso. 
  
Office 365 consente di controllare in modo proattivo i record DNS per individuare e risolvere i problemi relativi a DNS. Se i record DNS non corrispondono a ciò che si prevede di essere, si riceverà una notifica nell'interfaccia di amministrazione di Microsoft 365, insieme a informazioni che indicano come risolvere i possibili problemi identificati.
  
Per altre informazioni, vedere [Modalità di gestione dei record DNS da parte di Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270144). Per Office 365 gestito da 21Vianet, vedere [Creare record DNS per Office 365 quando si gestiscono i propri record DNS](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409).
  
## <a name="sharing-a-domain"></a>Condivisione di un dominio
<a name="BKMK_ManagingDNSRecords"> </a>

È possibile pilotare Office 365 con alcuni indirizzi di posta elettronica per un dominio in Office 365 e alcuni nel provider di posta elettronica precedente. Questa procedura è consigliata solo per l'utilizzo durante un progetto pilota di Office 365, poiché richiede ulteriori operazioni di installazione e presenta alcune limitazioni per i servizi di Office 365. Per ulteriori informazioni, vedere:
  
- [Eseguire una distribuzione pilota di Office 365 per una società di piccole dimensioni](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Eseguire una distribuzione pilota di Office 365 per una società di grandi dimensioni (tramite FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità
<a name="BKMK_ManagingDNSRecords"> </a>

Per visualizzare la disponibilità delle funzionalità tra i piani, le opzioni autonome e le soluzioni locali di Office 365, vedere [Descrizione dei servizi della piattaforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

