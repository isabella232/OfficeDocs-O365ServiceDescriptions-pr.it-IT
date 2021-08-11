---
title: Pianificare la conformità Microsoft 365 - GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, in cui l'uso di Microsoft 365 Government – GCC High è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: ba60ebf026ed3985ead28abba1c426bd8de53e7ba1acf51501b63c1d4c6d1d27
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663289"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Pianificare la conformità Microsoft 365- GCC alta

Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 nelle entità del governo federale degli Stati Uniti o in altre entità che gestiscono dati soggetti a normative e requisiti governativi, in cui l'uso di Microsoft 365 Government – GCC High è appropriato per soddisfare questi requisiti.

> [!NOTE]
>Se l'organizzazione ha già soddisfatto i requisiti di idoneità Microsoft 365 Government – GCC High e ha applicato e accettato il programma, è possibile ignorare i passaggi 1 e 2 e andare direttamente al passaggio 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve Microsoft 365 Government – GCC High e soddisfi i requisiti di idoneità

Il Microsoft 365 Government - GCC High è conforme ai requisiti del governo statunitense per i servizi cloud. Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche di Microsoft 365 Government – GCC High:

- Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi Office 365 commerciali da Microsoft.
- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.
- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.
- Microsoft 365 Government: GCC High è conforme alle certificazioni e accreditamenti necessari per i clienti del settore pubblico statunitense.

Puoi trovare ulteriori informazioni sull'offerta Microsoft 365 Government – GCC High offering per i clienti del governo statunitense nei piani [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [Office 365 del servizio us government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descrive i vantaggi della piattaforma, che sono centrati sul rispetto dei requisiti di conformità all'interno degli Stati Uniti.

> [!TIP]
> È possibile trasferire gli tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: Rilevante per l'organizzazione **Y/N** e Soddisfa le esigenze dell'organizzazione **Y/N.** È quindi possibile esaminare l'elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

**Punti decisionali**:<br/>
- *Decidere se Microsoft 365 government - GCC-High è appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

> [!NOTE]
> Microsoft 365 Government - GCC High è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra diversi Office 365 Government [piani.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Passaggio 2. Candidarsi Microsoft 365 government – GCC-High

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo di [richiesta per questo servizio.](https://products.office.com/government/eligibility-validation)
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Passaggio 3. Informazioni Microsoft 365 government : GCC-High impostazioni di sicurezza predefinite

È consigliabile prendere tempo per esaminare attentamente le impostazioni di sicurezza e di amministrazione prima di modificarle e valutare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto di** decisione: decidere se modificare le impostazioni di sicurezza Microsoft 365 Government – GCC-High predefinite, risolvendo per prima cosa *l'impatto* di eventuali modifiche che potrebbero essere apportate.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government – GCC-High<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud per enti pubblici, esistono alcune differenze tra i piani Microsoft 365 government GCC-High e enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli aggiornamenti più recenti dei prodotti di conformità pubblicati nella roadmap Microsoft 365 conformità.<br><br>

| Area | Funzionalità | GCC Stato elevato |
|------|---------|-----------------|
| **Protezione delle informazioni** | Client e scanner di etichettatura unificati | Disponibile |
| | Corrispondenza esatta dei dati | Disponibile |
| Etichettatura di riservatezza | Classificazione e etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive | Disponibile |
| Etichettatura di riservatezza | Classificazione ed etichettatura automatiche per Office app (Word, Excel, PowerPoint, Outlook) su Web, Android, iOS, Windows e Mac | Disponibile |
| Etichettatura di riservatezza | Classificazione ed etichettatura automatiche per Office client (mobile) | Backlog di progettazione |
| Etichettatura di riservatezza | Classificazione ed etichettatura automatiche per Teams, Microsoft 365 gruppi e SharePoint siti | Disponibile |
| Analisi | Analisi della classificazione dei dati: panoramica ed Esplora contenuto | Disponibile |
| Analisi | Analisi: classificatori di machine learning con etichettatura automatica sul lato servizio | Backlog di progettazione |
| Analisi | Analisi: classificatori di machine learning con etichettatura automatica Office app/lato client | In distribuzione |
| Crittografia | Basic Office 365 Message Encryption (E3) | Disponibile |
| Crittografia | Advanced Office 365 Message Encryption (E5) | Disponibile |
| Crittografia | Chiave cliente per Office 365 | Disponibile |
| Crittografia | Chiave cliente: crittografia dei dati in fase di Microsoft 365 | In distribuzione |
| Crittografia | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente | Disponibile |
| Crittografia | Crittografia a chiave doppia | Disponibile |
| Crittografia | Exchange Online servizio di crittografia tramite chiavi gestite Microsoft | Disponibile |
| Prevenzione della perdita dei dati | Prevenzione della perdita dei dati (DLP) per file e posta elettronica | Disponibile |
| Prevenzione della perdita dei dati | DLP per Teams conversazioni di chat e canali | Disponibile |
| Prevenzione della perdita dei dati | DLP Endpoint | In fase di sviluppo |
| Prevenzione della perdita dei dati | Dashboard avvisi | In fase di sviluppo |
| Prevenzione della perdita dei dati | Pagina Panoramica | In fase di sviluppo |
| **Governance delle informazioni** | Ambiti adattivi per i criteri di conservazione ed etichettatura | Backlog di progettazione |
| | Governance delle informazioni: Archiviazione posta elettronica | Disponibile |
| | Governance delle informazioni: etichette di conservazione predefinite per SharePoint/OneDrive for Business raccolte, cartelle e set di documenti; Exchange posta in arrivo; e Office 365 gruppi | Disponibile |
| | Governance delle informazioni: importare PST | Disponibile |
| | Governance delle informazioni: etichette di conservazione manuali non record | Disponibile |
| | Governance delle informazioni: blocco di conservazione | Disponibile |
| | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; posizioni o utenti specifici; automaticamente in base a condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento | Disponibile |
| | Governance delle informazioni: criteri di conservazione per Teams | In distribuzione |
| | Governance delle informazioni: criteri di conservazione per la Teams delle riunioni | In fase di sviluppo |
| | Governance delle informazioni: criteri di conservazione per Teams canali privati | Backlog di progettazione |
| | Governance delle informazioni: criteri di conservazione per Teams canali condivisi | Backlog di progettazione |
| | Governance delle informazioni: criteri di conservazione con classificatori addestrabili | In fase di sviluppo |
| | Governance delle informazioni: criteri di conservazione per Yammer | Backlog di progettazione |
| Gestione record | Possibilità di eliminare un'etichetta di record | In fase di sviluppo |
| Gestione record | Applicare manualmente un'etichetta di record | Disponibile |
| Gestione record | Applicare etichette di record predefinite SharePoint, OneDrive for Business raccolte, cartelle e set di documenti; e Office 365 gruppi | Disponibile |
| Gestione record | Applicare i criteri di record automaticamente in base a condizioni specifiche (ad esempio, parole chiave o informazioni riservate); e in base a un evento | Disponibile |
| Gestione record | Applicare automaticamente i criteri di record con classificatori addestrabili | In fase di sviluppo |
| Gestione record | Revisione per l'eliminazione | Disponibile |
| Gestione dei record | Gestione del piano di archiviazione | Disponibile |
| Gestione record | Revisione dell'eliminazione in più fasi | Backlog di progettazione |
| Gestione record | Prova di eliminazione | Disponibile |
| Gestione record | Power Automate Flow al termine del periodo di conservazione | Backlog di progettazione |
| Gestione record | Conservazione e etichettatura automatica degli allegati cloud | Backlog di progettazione |
| Gestione record | Controllo delle versioni dei record | Disponibile |
| Gestione record | Record normativi | Disponibile |
| Gestione record | Utilizzare SharePoint Syntex classificazione per applicare etichette di record | Backlog di progettazione |
| **Gestione dei rischi Insider** | Customer Lockbox | Disponibile |
| Conformità delle comunicazioni | Possibilità di ignorare la firma di posta elettronica o la dichiarazione di non responsabilità | In fase di sviluppo |
| Conformità delle comunicazioni | Possibilità di impostare un periodo di conservazione per un criterio di conformità delle comunicazioni | In fase di sviluppo |
| Conformità delle comunicazioni | Avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione | Disponibile |
| Conformità delle comunicazioni | Analizzare Teams di chat degli utenti con una cassetta postale locale | Disponibile |
| Conformità delle comunicazioni | Modello conflitto di interesse | Disponibile |
| Conformità delle comunicazioni | Creare criteri per i clienti, 3 preconfigurato | Disponibile |
| Conformità delle comunicazioni | Rilevare contenuto per adulti | Backlog di progettazione |
| Conformità delle comunicazioni | Rileva la violazione del codice di condotta ripetuto nel tempo | Disponibile |
| Conformità delle comunicazioni | Escalation per l'indagine per Advanced eDiscovery | Disponibile |
| Conformità delle comunicazioni | Gestione dei rischi insider | Backlog di progettazione |
| Conformità delle comunicazioni | Sfruttare il riconoscimento ottico dei caratteri per estrarre e valutare i messaggi | In fase di sviluppo |
| Conformità delle comunicazioni | Nuova visualizzazione semplificata per le aziende di piccole dimensioni | In fase di sviluppo |
| Conformità delle comunicazioni | Controllo dell'integrità dei criteri e possibilità di sospendere i criteri | Backlog di progettazione |
| Conformità delle comunicazioni | Integrazione Power Automate | Backlog di progettazione |
| Conformità delle comunicazioni | Supporta sette lingue per classificatori di minacce, molestie mirate e volgarità | Backlog di progettazione |
| Conformità delle comunicazioni | Supporto per autorizzazioni più granulari | Disponibile |
| Conformità delle comunicazioni | Supporto per Teams, Exchange e la possibilità di rimuovere Teams messaggio | Disponibile |
| Conformità delle comunicazioni | Microsoft Teams integrazione | Backlog di progettazione |
| Conformità delle comunicazioni | Teams di conversazione | Backlog di progettazione |
| Conformità delle comunicazioni | Tradurre il contenuto durante l'analisi | Backlog di progettazione |
| Customer Lockbox | Customer Lockbox | Disponibile |
| Barriere informative | Barriere informative | In fase di sviluppo |
| Gestione dei rischi Insider | Dashboard dei casi | Disponibile |
| Gestione dei rischi Insider | Furto di dati da parte di utenti che lasciano l'organizzazione | Disponibile |
| Gestione dei rischi Insider | Indicatori di dispositivo per l'attività Windows 10 Build 1809 e versioni successive | Backlog di progettazione |
| Gestione dei rischi Insider | Escalation per l'indagine per Advanced eDiscovery | Disponibile |
| Gestione dei rischi Insider | Esportare avvisi | Backlog di progettazione |
| Gestione dei rischi Insider | Fughe di dati generali | Disponibile |
| Gestione dei rischi Insider | Indicatori per la violazione dei criteri di sicurezza | Backlog di progettazione |
| Gestione dei rischi Insider | Indicatori per gli avvisi di Microsoft Defender per endpoint | Backlog di progettazione |
| Gestione dei rischi Insider | Gestione dei rischi insider Esplora attività | In fase di sviluppo |
| Gestione dei rischi Insider | Gestione dei rischi insider Esplora contenuto | In fase di sviluppo |
| Gestione dei rischi Insider | Analizzare gli avvisi di gestione dei rischi insider | Disponibile |
| Gestione dei rischi Insider | Modelli di avviso | Disponibile |
| Gestione dei rischi Insider | Office indicatori per Teams, SharePoint, messaggi di posta elettronica | Disponibile |
| Gestione dei rischi Insider | Modelli di criteri per le perdite di dati per utenti con priorità | Backlog di progettazione |
| Gestione dei rischi Insider | Modelli di criteri per le perdite di dati da parte di utenti scontenti | Backlog di progettazione |
| Gestione dei rischi Insider | Modelli di criteri per violazioni generali dei criteri di sicurezza | Backlog di progettazione |
| Gestione dei rischi Insider | Modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità, utenti in partenza, utenti scontenti | Backlog di progettazione |
| Gestione dei rischi Insider | Personalizzazione dei criteri | Backlog di progettazione |
| Gestione dei rischi Insider | Gruppi di utenti con priorità | Backlog di progettazione |
| Gestione dei rischi Insider | Integrazione Power Automate | In fase di sviluppo |
| Gestione dei rischi Insider | Microsoft Teams integrazione | Backlog di progettazione |
| Gestione accessi con privilegi | Gestione accessi con privilegi | Backlog di progettazione |
| **Individuazione &amp; della risposta** | Core eDiscovery: Controllo | Disponibile |
| eDiscovery | Core eDiscovery: Gestione dei casi | Disponibile |
| eDiscovery | Core eDiscovery: Esportazione | Disponibile |
| eDiscovery | Core eDiscovery: conservazione sul posto | Disponibile |
| eDiscovery | Core eDiscovery: esportazione nativa | Disponibile |
| eDiscovery | Core eDiscovery: decrittografia RMS | Disponibile |
| eDiscovery | Core eDiscovery: Ricerca | Disponibile |
| eDiscovery | Advanced eDiscovery: Elaborazione avanzata | Disponibile |
| eDiscovery | Advanced eDiscovery: mapping tra responsabile e carico di lavoro | Disponibile |
| eDiscovery | Advanced eDiscovery: Comunicazioni di custodia | Disponibile |
| eDiscovery | Advanced eDiscovery: Dashboard | Disponibile |
| eDiscovery | Advanced eDiscovery: supporto a byte doppio per cinese, giapponese e coreano | Disponibile |
| eDiscovery | Advanced eDiscovery: Threading della posta elettronica | Disponibile |
| eDiscovery | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di recensioni) | Disponibile |
| eDiscovery | Advanced eDiscovery: Filtro | Disponibile |
| eDiscovery | Advanced eDiscovery: ottimizzazioni di blocco | In fase di sviluppo |
| eDiscovery | Advanced eDiscovery: blocco legale per i messaggi Teams canali privati | Disponibile |
| eDiscovery | Advanced eDiscovery: il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi SharePoint e OneDrive for Business Cestino | In fase di sviluppo |
| eDiscovery | Advanced eDiscovery: Identificazione quasi duplicata | Disponibile |
| eDiscovery | Advanced eDiscovery: nuovo modulo di codifica predittiva | Backlog di progettazione |
| eDiscovery | Advanced eDiscovery: origini dati non di custodia | Disponibile |
| eDiscovery | Advanced eDiscovery: inserimento non Office 365 | Disponibile |
| eDiscovery | Advanced eDiscovery: codifica predittiva | Disponibile |
| eDiscovery | Advanced eDiscovery: esportazione elaborata con file di caricamento | Disponibile |
| eDiscovery | Advanced eDiscovery: Redactions | Disponibile |
| eDiscovery | Advanced eDiscovery: Rivedere i set | Disponibile |
| eDiscovery | Advanced eDiscovery: esaminare i dati (dati di query, smart tag, dashboard) e annotare (redact) | Disponibile |
| eDiscovery | Advanced eDiscovery: report Termini di ricerca | Disponibile |
| eDiscovery | Advanced eDiscovery: correzione degli errori di un singolo elemento | Disponibile |
| eDiscovery | Advanced eDiscovery: Supportare l'esportazione PST | Disponibile |
| eDiscovery | Advanced eDiscovery: supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni) | Disponibile |
| eDiscovery | Advanced eDiscovery: supporto Teams reazioni | Backlog di progettazione |
| eDiscovery | Advanced eDiscovery: Tagging | Disponibile |
| eDiscovery | Advanced eDiscovery: report tenant | Disponibile |
| eDiscovery | Advanced eDiscovery: Temi | Disponibile |
| eDiscovery | Advanced eDiscovery: Visualizzatori | Disponibile |
| eDiscovery | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft | Disponibile |
| Audit | Audit di base | Disponibile |
| Audit | Controllo avanzato: accesso a eventi cruciali (ad esempio, *MailItemsAccessed*) | Disponibile |
| Audit | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione | Disponibile |
| Audit | Controllo avanzato: blocco legale per i messaggi Teams canali privati | Disponibile |
| Audit | Controllo avanzato: conservazione dei registri (1 anno) | Disponibile |
| Audit | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni) | In fase di sviluppo |
| Audit | Controllo avanzato: eventi di inoltro della posta e invio della posta | Disponibile |
| Audit | Controllo avanzato: disponibilità Microsoft 365 centro sicurezza e conformità | Disponibile |
| Audit | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online | Backlog di progettazione |
| **Gestione della conformità** | Microsoft 365 Centro sicurezza e conformità | Disponibile |
| | Compliance Manager | Disponibile |
| | Supporto dei caratteri a byte doppio | Disponibile |
| | Microsoft Cloud App Security | Disponibile |
| **Ecosistema** | Graph API per Advanced eDiscovery | In fase di sviluppo |
| | Graph API per l'esportazione Teams dati | Backlog di progettazione |
| | Connettori dati di prima parte | Backlog di progettazione |
| | Connettori dati di terze parti | In fase di sviluppo |

<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*