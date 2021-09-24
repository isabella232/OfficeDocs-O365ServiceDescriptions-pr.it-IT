---
title: Pianificare la conformità Microsoft 365 - GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 in enti governativi federali, statali, locali, tribali o territoriali o altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government - GCC è appropriato per soddisfare questi requisiti.
ms.openlocfilehash: aeae0c38301a26d77d82adce492b6651153e3fab
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671514"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Pianificare la conformità Microsoft 365- GCC

Queste indicazioni sono per i professionisti IT che guidano le distribuzioni di Office 365 in enti governativi federali, statali, locali, tribali o territoriali o altre entità che gestiscono dati soggetti a normative e requisiti governativi, dove l'uso di Microsoft 365 Government - GCC è appropriato per soddisfare questi requisiti.

> [!NOTE]
> Se l'organizzazione ha già soddisfatto i requisiti di idoneità di Microsoft 365 Government - GCC ed è stata richiesta e accettata nel programma, è possibile ignorare i passaggi 1 e 2 e andare direttamente al passaggio 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Passaggio 1. Determinare se l'organizzazione deve Microsoft 365 government - GCC e soddisfi i requisiti di idoneità

L'ambiente Microsoft 365 Government - GCC è conforme ai requisiti del governo statunitense per i servizi cloud, tra cui FedRAMP Moderate, e ai requisiti per la giustizia penale e i sistemi di informazioni fiscali federali (tipi di dati CJI e FTI).

Oltre a usufruire delle funzionalità e delle funzionalità di Office 365, le organizzazioni traggono vantaggio dalle seguenti funzionalità specifiche di Microsoft 365 Government - GCC:

- Il contenuto dei clienti dell'organizzazione è logicamente segregato dal contenuto dei clienti nei servizi Office 365 commerciali da Microsoft.

- Il contenuto del cliente dell'organizzazione viene archiviato negli Stati Uniti.

- L'accesso al contenuto del cliente dell'organizzazione è limitato a personale Microsoft selezionato.

- Microsoft 365 Government : GCC le certificazioni e gli accreditamenti necessari per i clienti del settore pubblico statunitense.

Puoi trovare ulteriori informazioni sull'offerta Microsoft 365 Government - GCC per i clienti del governo statunitense nei piani [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)inclusi i requisiti di idoneità.

La [Office 365 del servizio us government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descrive i vantaggi della piattaforma, che sono centrati sul rispetto dei requisiti di conformità all'interno degli Stati Uniti.

> [!TIP]
> È possibile trasferire gli tabelle delle informazioni nella descrizione del servizio in una cartella di lavoro di Excel e aggiungere due colonne: Rilevante per l'organizzazione **Y/N** e Soddisfa le esigenze dell'organizzazione **Y/N.** È quindi possibile esaminare l'elenco con i colleghi per verificare che questo servizio soddisfi le esigenze dell'organizzazione.

> [!NOTE]
> Microsoft 365 Government - GCC è disponibile solo negli Stati Uniti. I clienti non governativi degli Stati Uniti possono scegliere tra diversi Office 365 Government [piani.](https://products.office.com/government/compare-office-365-government-plans)

**Punti decisionali**: <br/>
- *Decidere se Microsoft 365 government - GCC appropriato per l'organizzazione.*
- *Verificare che l'organizzazione soddisfi i requisiti di idoneità.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Passaggio 2. Candidarsi Microsoft 365 governo - GCC

Dopo aver deciso che questo servizio è giusto per l'organizzazione, avviare il processo di [richiesta per questo servizio.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Passaggio 3. Informazioni Microsoft 365 per enti pubblici - GCC di sicurezza predefinite

È consigliabile prendere tempo per esaminare attentamente le impostazioni di sicurezza e di amministratore prima di modificarle e valutare l'impatto sulla conformità prima di apportare modifiche alle impostazioni di sicurezza predefinite.

**Punto di** decisione: decidere se modificare le impostazioni di sicurezza di Microsoft 365 Government - GCC predefinite, risolvendo per prima cosa *l'impatto* di eventuali modifiche che potrebbero essere apportate.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Passaggio 4. Informazioni sulle funzionalità attualmente non disponibili o disabilitate per impostazione predefinita in Microsoft 365 Government - GCC<sup>1</sup>

Per soddisfare i requisiti dei clienti del cloud per enti pubblici, esistono alcune differenze tra i piani Microsoft 365 government - GCC e enterprise. Fare riferimento alla tabella seguente per vedere quali funzionalità sono disponibili. Vedere [qui per](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) gli aggiornamenti più recenti dei prodotti di conformità pubblicati Microsoft 365 roadmap.<br><br>

| Area | Funzionalità | GCC Stato |
| ---- | ------- | ---------- |
| **Protezione delle informazioni** | | |
| Tipi di informazioni sensibili | Corrispondenza esatta dei dati | Disponibile |
| Etichettatura di riservatezza | Client e scanner di etichettatura unificati | Disponibile |
| | Classificazione e etichettatura automatiche per Exchange Online, SharePoint Online e OneDrive | Disponibile |
| | Classificazione ed etichettatura automatiche per app Office (Word, Excel, PowerPoint, Outlook) tra piattaforme (Web, Windows e Mac) | Disponibile |
| | Classificazione ed etichettatura automatiche per Office client (mobile) | Backlog di progettazione |
| | Classificazione automatica ed etichettatura per Teams, Microsoft 365 gruppi, SharePoint siti | Disponibile |
| Analisi | Analisi della classificazione dei dati: panoramica ed Esplora contenuto | Disponibile |
| | Analisi: classificatori di machine learning con etichettatura automatica Office app/lato client | In fase di sviluppo |
| Crittografia | Basic Office 365 Message Encryption (E3) | Disponibile |
| | Advanced Office 365 Message Encryption (E5) | Disponibile |
| | Chiave cliente per Office 365 | Disponibile |
| | Chiave cliente per la Microsoft 365 multi-carico di lavoro | Disponibile |
| | Customer Key per SharePoint Online e OneDrive for Business | Disponibile |
| | Bring Your Own Key (BYOK) per il ciclo di vita del provisioning delle chiavi gestito dal cliente | Disponibile |
| | Crittografia a chiave doppia | Disponibile |
| | Exchange Online servizio di crittografia tramite chiavi gestite Microsoft | Disponibile |
| Prevenzione della perdita di dati | Prevenzione della perdita dei dati (DLP) per file e posta elettronica | Disponibile |
| | DLP per Teams conversazioni di chat e canali | Disponibile |
| | DLP Endpoint | Anteprima pubblica |
| | Dashboard degli avvisi DLP e esperienza di avviso | Disponibile |
| | Pagina Panoramica DLP | In fase di sviluppo |
| **Governance delle informazioni** | | |
| Governance delle informazioni | Governance delle informazioni: ambiti adattivi per i criteri di conservazione ed etichettatura | Backlog di progettazione |
| | Governance delle informazioni: Archiviazione posta elettronica | Disponibile |
| | Governance delle informazioni: etichette di conservazione predefinite per SharePoint, OneDrive for Business raccolte, cartelle e set di documenti; Exchange posta in arrivo; e Office 365 gruppi | Disponibile |
| | Governance delle informazioni: importare PST | Disponibile |
| | Governance delle informazioni: etichette di conservazione manuali non record | Disponibile |
| | Governance delle informazioni: blocco di conservazione | Disponibile |
| | Governance delle informazioni: criteri di conservazione per l'intera organizzazione; posizioni o utenti specifici; automaticamente in base a condizioni specifiche (ad esempio parole chiave o informazioni riservate); e in base a un evento | Disponibile |
| | Governance delle informazioni: criteri di conservazione per Teams | Disponibile |
| | Governance delle informazioni: criteri di conservazione per la Teams delle riunioni | Disponibile |
| | Governance delle informazioni: criteri di conservazione per Teams canali privati | Disponibile |
| | Governance delle informazioni: criteri di conservazione per Teams canali condivisi | Backlog di progettazione |
| | Governance delle informazioni: criteri di conservazione con classificatori addestrabili | In distribuzione |
| | Governance delle informazioni: criteri di conservazione per Yammer | Backlog di progettazione |
| Gestione dei record | Gestione record: possibilità di eliminare un'etichetta di record | Disponibile |
| | Gestione record: applicare manualmente un'etichetta di record | Disponibile |
| | Gestione record: applicare etichette di record predefinite per SharePoint, OneDrive for Business raccolte, cartelle e set di documenti; e Office 365 gruppi | Disponibile |
| | Gestione dei record: applicare automaticamente i criteri record in base a condizioni specifiche (ad esempio, parole chiave o informazioni riservate); e in base a un evento | Disponibile |
| | Gestione dei record: applicare automaticamente i criteri di record con classificatori addestrabili | In fase di sviluppo |
| | Gestione dei record: revisione dell'eliminazione | Disponibile |
| | Gestione dei record: Gestione piano di file | Disponibile |
| | Gestione dei record: revisione dell'eliminazione in più fasi | In fase di sviluppo |
| | Gestione dei record: Outlook client per la gestione dei record | In fase di sviluppo |
| | Gestione dei record: conservazione e etichettatura automatica degli allegati cloud | Backlog di progettazione |
| | Gestione dei record: prova di eliminazione | Disponibile |
| | Gestione record: controllo delle versioni dei record | Disponibile |
| | Gestione dei record: record normativi | Disponibile |
| **Gestione dei rischi** | | |
| Customer Lockbox | Customer Lockbox | Disponibile |
| Conformità delle comunicazioni | Conformità delle comunicazioni: possibilità di impostare un periodo di conservazione per un criterio di conformità delle comunicazioni | In fase di sviluppo |
| | Conformità delle comunicazioni: avvisi di accesso; modelli di avviso; dashboard dei criteri di comunicazione | Disponibile |
| | Conformità delle comunicazioni: analizzare Teams chat degli utenti con una cassetta postale locale | Disponibile |
| | Conformità delle comunicazioni: monitorare automaticamente Teams un utente è membro di | Disponibile |
| | Conformità delle comunicazioni: modello conflitto di interesse | Disponibile |
| | Conformità delle comunicazioni: creare criteri per i clienti, 3 preconfigurato | Disponibile |
| | Conformità delle comunicazioni: rilevare i contenuti per adulti | Disponibile |
| | Conformità delle comunicazioni: rileva la violazione del codice di condotta ripetuto nel tempo | Disponibile |
| | Conformità delle comunicazioni: inoltrare le indagini per Advanced eDiscovery | Disponibile |
| | Conformità delle comunicazioni: controllo dell'integrità dei criteri e possibilità di sospendere i criteri | In fase di sviluppo |
| | Conformità delle comunicazioni: Power Automate integrazione | In fase di sviluppo |
| | Conformità delle comunicazioni: tipi di informazioni riservate per report percorso | In fase di sviluppo |
| | Conformità delle comunicazioni: supporto per autorizzazioni più granulari | Disponibile |
| | Conformità alle comunicazioni: supporta sette lingue per i classificatori di minacce, molestie mirate e volgarità | Disponibile |
| | Conformità delle comunicazioni: supporto per Teams, Exchange e la possibilità di rimuovere Teams messaggio | Disponibile |
| | Conformità delle comunicazioni: Teams di conversazione | In fase di sviluppo |
| | Conformità delle comunicazioni: tradurre il contenuto durante l'indagine | Disponibile |
| Ostacoli alle informazioni | Ostacoli alle informazioni | Disponibile |
| Gestione dei rischi Insider | Insider Risk Management: Log di controllo | Anteprima pubblica |
| | Gestione dei rischi Insider: dashboard del caso | Disponibile |
| | Gestione dei rischi Insider: miglioramenti di Esplora contenuto ed Esplora contenuto | Disponibile |
| | Gestione dei rischi insider: dati evasi in Esplora attività | Disponibile |
| | Insider Risk Management: furto di dati da parte di utenti in partenza | Disponibile |
| | Gestione dei rischi insider: indicatori del dispositivo per l'attività Windows 10 endpoint | Anteprima pubblica |
| | Insider Risk Management: inoltrare le indagini per Advanced eDiscovery | Disponibile |
| | Gestione dei rischi Insider: esportare gli avvisi | Anteprima pubblica |
| | Insider Risk Management: perdite di dati generali | Disponibile |
| | Insider Risk Management: indicatori per la violazione dei criteri di sicurezza | In fase di sviluppo |
| | Insider Risk Management: indicatori per gli avvisi di Microsoft Defender per endpoint | Backlog di progettazione |
| | Insider Risk Management: indicatori per l'attività Windows 10 endpoint | Anteprima pubblica |
| | Insider Risk Management: supporto intelligente per le impostazioni del dominio in Insider Risk Management | Anteprima pubblica |
| | Insider Risk Management: analizzare gli avvisi di gestione dei rischi insider | Disponibile |
| | Insider Risk Management: Microsoft Teams e Power Automate integrazione | In fase di sviluppo |
| | Gestione dei rischi Insider: il supporto dei trigger nativi per l'eliminazione Azure Active Directory account | Anteprima pubblica |
| | Gestione dei rischi Insider: modelli di avviso | Disponibile |
| | Insider Risk Management: indicatori Office per Teams, SharePoint siti, messaggi di posta elettronica | Disponibile |
| | Gestione dei rischi insider: personalizzazione dei criteri, controllo dell'integrità dei criteri e creazione guidata dei criteri avanzata | Anteprima pubblica |
| | Insider Risk Management: modelli di criteri per le perdite di dati da parte di utenti scontenti | Anteprima pubblica |
| | Gestione dei rischi insider: modelli di criteri per le perdite di dati da parte degli utenti con priorità | Anteprima pubblica |
| | Insider Risk Management: modelli di criteri per violazioni generali dei criteri di sicurezza | Backlog di progettazione |
| | Gestione dei rischi insider: modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti con priorità e utenti in partenza | Anteprima pubblica |
| | Gestione dei rischi insider: modelli di criteri per le violazioni dei criteri di sicurezza da parte di utenti scontenti | Backlog di progettazione |
| | Gestione dei rischi insider: gruppi di utenti con priorità | Anteprima pubblica |
| **Individuare & rispondere** | | |
| eDiscovery | Core eDiscovery: Controllo | Disponibile |
| | Core eDiscovery: Gestione dei casi | Disponibile |
| | Core eDiscovery: limiti di conformità per OneDrive for Business | Disponibile |
| | Core eDiscovery: Esportazione | Disponibile |
| | Core eDiscovery: conservazione sul posto | Disponibile |
| | Core eDiscovery: esportazione nativa | Disponibile |
| | Core eDiscovery: decrittografia RMS | Disponibile |
| | Core eDiscovery: Ricerca | Disponibile |
| | Core eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi SharePoint e OneDrive for Business Cestino | Disponibile |
| | Advanced eDiscovery: elaborazione avanzata | Disponibile |
| | Advanced eDiscovery: mapping tra custodia e carico di lavoro | Disponibile |
| | Advanced eDiscovery: Comunicazioni di custodia | Disponibile |
| | Advanced eDiscovery: Dashboard | Disponibile |
| | Advanced eDiscovery: funzionalità di eliminazione dei dati per Microsoft Teams | Backlog di progettazione |
| | Advanced eDiscovery: ricerca per indicizzazione/indicizzazione approfondita | Disponibile |
| | Advanced eDiscovery: supporto dei caratteri a byte doppio (cinese, giapponese, coreano) | Disponibile |
| | Advanced eDiscovery: Threading della posta elettronica | Disponibile |
| | Advanced eDiscovery: Esportare (scaricare, esportare, aggiungere a un altro set di visualizzazione) | Disponibile |
| | Advanced eDiscovery: Filtro | Disponibile |
| | Advanced eDiscovery: ottimizzazioni del blocco | In fase di sviluppo |
| | Advanced eDiscovery: blocco legale per i messaggi Teams canali privati | Disponibile |
| | Advanced eDiscovery: Il Centro conformità Microsoft ha esteso il supporto per la ricerca e l'esportazione di elementi in SharePoint e OneDrive for Business Cestino | In fase di sviluppo |
| | Advanced eDiscovery: identificazione quasi duplicata | Disponibile |
| | Advanced eDiscovery: nuova esperienza di esportazione per Core e Advanced eDiscovery | In fase di sviluppo |
| | Advanced eDiscovery: nuovo modulo di codifica predittiva | Backlog di progettazione |
| | Advanced eDiscovery: origini dati non di custodia | Disponibile |
| | Advanced eDiscovery: inserimento di Office 365 non Office 365 | Disponibile |
| | Advanced eDiscovery: codifica predittiva | Disponibile |
| | Advanced eDiscovery: esportazione elaborata con file di caricamento | Disponibile |
| | Advanced eDiscovery: Redactions | Disponibile |
| | Advanced eDiscovery: Rivedere i set | Disponibile |
| | Advanced eDiscovery: esaminare i dati (dati di query, smart tag, dashboard) e annotare (redact) | Disponibile |
| | Advanced eDiscovery: report termini di ricerca | Disponibile |
| | Advanced eDiscovery: correzione degli errori di un singolo elemento | Disponibile |
| | Advanced eDiscovery: Supportare l'esportazione PST | Disponibile |
| | Advanced eDiscovery: supporto del contenuto collegato da OneDrive e SharePoint Online (allegati moderni) | Disponibile |
| | Advanced eDiscovery: supporto Teams reazioni | Backlog di progettazione |
| | Advanced eDiscovery: Tagging | Disponibile |
| | Advanced eDiscovery: Report tenant | Disponibile |
| | Advanced eDiscovery: Temi | Disponibile |
| | Advanced eDiscovery: Visualizzatori | Disponibile |
| | Advanced eDiscovery: Yammer Advanced eDiscovery nel Centro conformità Microsoft | Disponibile |
| Audit | Audit di base | Disponibile |
| | Controllo avanzato: accesso a eventi cruciali (ad esempio, *MailItemsAccessed*) | Disponibile |
| | Controllo avanzato: aumento della larghezza di banda per l'API delle attività di gestione | Disponibile |
| | Controllo avanzato: blocco legale per i messaggi Teams canali privati | Disponibile |
| | Controllo avanzato: conservazione dei registri (1 anno) | Disponibile |
| | Controllo avanzato: conservazione a più lungo termine nei log di controllo (10 anni) | In distribuzione |
| | Controllo avanzato: eventi di inoltro della posta e invio della posta | Disponibile |
| | Controllo avanzato: Microsoft 365 sicurezza e conformità | Disponibile |
| | Controllo avanzato: eventi dei termini di ricerca in Exchange Online e SharePoint Online | In fase di sviluppo |
| | Controllo avanzato: Teams reazioni ai messaggi | Backlog di progettazione |
| **Gestione della conformità** | | |
| Gestione della conformità | Centro conformità Microsoft 365 | Disponibile |
| | Compliance Manager | Disponibile |
| | Supporto dei caratteri a byte doppio | Disponibile |
| | Microsoft Cloud App Security | Disponibile |
| **Ecosistema** | | |
| Ecosistema | Connettori dati di prima parte: HR | In fase di sviluppo |
| | Connettori dati di prima parte: badging fisico | In fase di sviluppo |
| | Graph API per Advanced eDiscovery | Backlog di progettazione |
| | Connettori dati di terze parti (17a-4 e connettori CellTrust) | In fase di sviluppo |
| | Connettori dati di terze parti (Telemessage) | Disponibile |
| | Connettori dati di terze parti (Veritas) | In distribuzione |
| | Connettori dati di terze parti (connettori 17a-4 e CellTrust) | In fase di sviluppo |

<sup>1</sup> Lo stato identificato è soggetto a modifiche in seguito alla rivalutazione dei piani e delle priorità del progetto.<br/>

**Punto di decisione:** *decidere se le funzionalità di conformità soddisfano le esigenze dell'organizzazione.*
