---
title: Domini
ms.author: office365servicedesc
author: pamelaar
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
description: Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica e altri servizi nel nome dell'azienda. Al termine della procedura guidata, il messaggio di posta elettronica aziendale inizia a venire a Microsoft invece di passare al provider di posta elettronica corrente. Per ulteriori informazioni, vedere Aggiungere utenti e domini a Microsoft. Se si utilizza Office 365 gestito da 21Vianet, vedere Verificare il dominio.
ms.openlocfilehash: b6bbd87a1c3f303ceec0de90b42b322ba513d354
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132400"
---
# <a name="domains"></a>Domini

Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica e altri servizi nel nome dell'azienda. Al termine della procedura guidata, il messaggio di posta elettronica aziendale inizia a venire a Microsoft invece di passare al provider di posta elettronica corrente. Per ulteriori informazioni, vedere [aggiungere utenti e domini a Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Se si utilizza Office 365 gestito da 21Vianet, vedere [Verificare il dominio](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Domini personalizzati

È possibile aggiungere fino a 900 domini all'abbonamento. Tuttavia, non è possibile aggiungere un dominio Office 365 che viene già utilizzato in un altro servizio cloud di Microsoft. Ciò significa che non è possibile aggiungere lo stesso dominio a più sottoscrizioni. Per ulteriori informazioni, vedere [domande frequenti sui domini](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domini di secondo e terzo livello

Con Office 365 Enterprise e Microsoft 365 Apps for business, è possibile aggiungere qualsiasi dominio a livello, inclusi domini di terzo livello come marketing.contoso.com. Vedere [aggiungere sottodomini personalizzati o più domini a Microsoft](https://docs.microsoft.com/office365/admin/setup/domains-faq). Se si utilizza Office 365 gestito da 21Vianet, vedere [Aggiungere sottodomini o più domini personalizzati in Office 365 gestito da 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Verifica e gestione dei record DNS

Con Microsoft 365, è possibile gestire tutti i record DNS presso il provider di hosting DNS oppure scegliere di impostare Microsoft e gestire i record DNS del dominio. Se si continua a gestire i record, è necessario modificare i record specifici in modo che puntino ai servizi Microsoft in base alle esigenze. Per un elenco dei registrar per i quali vengono fornite istruzioni dettagliate per l'aggiunta dei record, inclusi i valori specifici da utilizzare per ogni record, vedere [creare record DNS](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) o, se si utilizza Office 365 gestito da 21ViaNet, vedere Create DNS Records at any provider for Office 365 gestito da 21ViaNet. 
  
Se Microsoft gestisce i record DNS del dominio per l'utente, è necessario innanzitutto cambiare i record del server dei nomi del dominio in modo che puntino a Microsoft e quindi Microsoft configura i servizi e quindi i record DNS del dominio vengono gestiti in Microsoft.
  
Se il dominio è registrato su GoDaddy, Microsoft è in grado di creare i record necessari in GoDaddy. 
  
Indipendentemente dal luogo in cui sono ospitati i record DNS, è possibile impostare i record DNS in modo che utilizzino il dominio per l'URL di un sito Web pubblico ospitato in Microsoft o con un altro provider di hosting. 
  
Microsoft controlla in modo proattivo i record DNS per individuare e risolvere i problemi relativi a DNS. Se i record DNS non corrispondono a ciò che si prevede di essere, si riceverà una notifica nell'interfaccia di amministrazione di Microsoft 365, insieme a informazioni che indicano come risolvere i possibili problemi identificati.
  
Per ulteriori informazioni, vedere in [che modo Microsoft gestisce i record DNS](https://docs.microsoft.com/office365/admin/setup/domains-faq) o, per Office 365 gestito da 21ViaNet, vedere [creare record dns per Office 365 quando si gestiscono i record DNS](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Condivisione di un dominio

È possibile pilotare alcuni indirizzi di posta elettronica per un dominio in Microsoft e alcuni nel provider di posta elettronica precedente. Questa procedura è consigliata solo per l'utilizzo durante un progetto pilota, poiché richiede ulteriori operazioni di installazione e presenta alcune limitazioni per i servizi Microsoft. Per altre informazioni, vedere:
  
- [Pilota Microsoft 365 per una piccola azienda](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilota Microsoft 365 per un'azienda di grandi dimensioni (tramite FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità tra i piani di Microsoft 365 per le aziende, opzioni autonome e soluzioni locali, vedere [Microsoft 365 and Office 365 Platform Service Description](office-365-platform-service-description.md).
  

