---
title: Domini
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica e altri servizi nel nome dell'azienda. Al termine della procedura guidata, la posta elettronica aziendale inizia a essere inviata a Microsoft anziché al provider di posta elettronica corrente. Per ulteriori informazioni, vedere Aggiungere utenti e domini a Microsoft. Se si utilizza Office 365 gestito da 21Vianet, vedere Verificare il dominio.
ms.openlocfilehash: 72ea4e88d659d7a6004888c45bb233832978fd34
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652570"
---
# <a name="domains"></a>Domini

Quando si aggiunge un dominio, una procedura guidata dettagliata consente di aggiungere utenti e convertire gli indirizzi di posta elettronica e altri servizi nel nome dell'azienda. Al termine della procedura guidata, la posta elettronica aziendale inizia a essere inviata a Microsoft anziché al provider di posta elettronica corrente. Per ulteriori informazioni, vedere [Aggiungere utenti e domini a Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Se si utilizza Office 365 gestito da 21Vianet, vedere [Verificare il dominio](/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Domini personalizzati

È possibile aggiungere fino a 900 domini alla sottoscrizione (inclusi i sottodomini). Non è possibile aggiungere a Microsoft 365 un dominio già in uso in un altro servizio cloud Microsoft. Ciò significa che non è possibile aggiungere lo stesso dominio a più sottoscrizioni. Per ulteriori informazioni, vedere [Domande frequenti sui domini.](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)
  
### <a name="second-and-third-level-domains"></a>Domini di secondo e terzo livello

Con Office 365 Enterprise e Microsoft 365 Apps for business, è possibile aggiungere qualsiasi dominio di livello, inclusi i domini di terzo livello, ad esempio marketing.contoso.com. Vedere [Aggiungere sottodomini personalizzati o più domini a Microsoft](/office365/admin/setup/domains-faq). Se si utilizza Office 365 gestito da 21Vianet, vedere [Aggiungere sottodomini o più domini personalizzati in Office 365 gestito da 21Vianet](/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Verifica e gestione dei record DNS

Con Microsoft 365, è possibile gestire tutti i record DNS presso il provider di hosting DNS oppure scegliere di configurare e gestire automaticamente i record DNS del dominio. Se si continua a gestire i record, si modificano record specifici in modo che puntino ai servizi Microsoft in base alle esigenze. Per un elenco dei registrar per i quali vengono fornite istruzioni dettagliate per l'aggiunta dei record, inclusi i valori specifici da utilizzare per ogni record, vedere [Create DNS records](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) or, if you are using Office 365 operated by 21Vianet, see Create DNS records at any provider for Office 365 operated by 21Vianet. 
  
Se Microsoft gestisce automaticamente i record DNS del dominio, è innanzitutto necessario cambiare i record del server dei nomi del dominio in modo che puntino a Microsoft e quindi Microsoft configura i servizi e quindi i record DNS del dominio vengono gestiti in Microsoft.
  
Se il dominio è registrato in GoDaddy, Microsoft può creare automaticamente i record necessari in GoDaddy. 
  
Indipendentemente da dove sono ospitati i record DNS, è possibile configurare i record DNS per l'utilizzo del dominio per l'URL di un sito Web pubblico ospitato in Microsoft o con un provider di hosting diverso. 
  
Microsoft controlla in modo proattivo i record DNS per individuare e risolvere i problemi DNS. Se i record DNS non corrispondono a quanto previsto, si riceverà una notifica nell'interfaccia di amministrazione di Microsoft 365, insieme alle informazioni che spiegano come risolvere i possibili problemi identificati.
  
Per ulteriori informazioni, vedere [How Microsoft manages DNS records](/office365/admin/setup/domains-faq) or, for Office 365 operated by 21Vianet, see Create DNS records for Office [365 when you manage your DNS records](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Condivisione di un dominio

È possibile pilotare alcuni indirizzi di posta elettronica per un dominio in Microsoft e altri nel provider di posta elettronica precedente. Questa opzione è consigliata solo per l'utilizzo durante un progetto pilota, perché richiede passaggi di configurazione aggiuntivi e presenta alcune limitazioni per i servizi Microsoft. Per altre informazioni, vedere:
  
- [Pilotare Microsoft 365 per una piccola azienda](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilotare Microsoft 365 per un'azienda di grandi dimensioni (con FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilità delle funzionalità

Per visualizzare la disponibilità delle funzionalità nei piani di Microsoft 365 per le aziende, opzioni autonome e soluzioni locali, vedere Descrizione del servizio della piattaforma [Microsoft 365 e Office 365.](office-365-platform-service-description.md)
