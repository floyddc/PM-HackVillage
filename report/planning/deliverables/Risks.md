---
layout: default
title: Risks
nav_exclude: true
---

# Risk analysis

Questo documento contiene il registro dei rischi e la strategia di gestione delle minacce approvata durante il Meeting #3 del JPPS. L'obiettivo è proteggere la baseline dei tempi (3 mesi) e del budget (€30.000) dalle potenziali deviazioni operative.

## Matrice di valutazione dei rischi
I rischi sono valutati in base alla **probabilità** di accadimento, all'**impatto** sul progetto e alla dimensione del vincolo d'ambito coinvolta (**Scope Triangle**).

| ID | Descrizione del Rischio | Scope Triangle | Probabilità | Impatto | Strategia | Descrizione e piano d'azione |
| :---: | :--- | :---: | :---: | :---: | :---: | :--- |
| **R1** | **Interfaccia e UX non intuitiva** | Scopo/Qualità | Bassa | Critico | **Transfer** | Un'interfaccia complessa bloccherebbe l'adozione da parte di partecipanti e giudici, causando il fallimento dell'evento. Rischio basso grazie ai continui test e alla supervisione del Mental Coach sulla UX cognitiva.
| **R2** | **Rallentamenti nello sviluppo (collo di bottiglia)** | Tempo | Alta | Alta | **Mitigate** | Con un soli due sviluppatori, i ritardi sono un rischio concreto che minaccia la scadenza dei 3 mesi Per mitigare il rischio, si adotta un approccio *API-first* per azzerare il context switch e lavorare in parallelo. In caso di blocco critico o assenza, innesto operativo del CTO a supporto del codice. |
| **R3** | **Cambiamenti improvvisi di mercato** | Scopo/Qualità | Minima | Alta | **Accept** | Vista la [Market analysis](../../scoping/deliverables/Market.md) iniziale (trend hackathon in forte crescita) una contrazione improvvisa della domanda è considerata quasi impossibile. Rischio accettato passivamente senza allocazione di budget o modifiche all'ambito. |
| **R4** | **Difficile integrazione con le API di GitHub** | Tempo | Medio | Medio | **Accept** | L'integrazione obbligatoria con GitHub per la raccolta delle submission potrebbe presentare complessità tecniche. Essendo una causa esterna, non è mitigabile, è solo accettabile: se dovesse causare ritardi, la feature di sincronizzazione automatica verrà declassata a "NICE-TO-HAVE" e gestita tramite un fallback di upload manuale diretto. |
| **R5** | **Violazione o gestione non conforme dei dati (GDPR)** | Scopo/Qualità | Bassa | Critica | **Mitigate + Contingency** | Una violazione dei dati personali o degli iscritti comporterebbe sanzioni legali pesanti e un danno irreparabile alla reputazione del committente. Per mitigare, si implementano controlli rigidi sul trattamento e un'architettura di database protetta da middleware di sicurezza (RBAC). Il piano di contingenza prevede l'attivazione di una polizza assicurativa aziendale per coprire i danni economici derivanti da data-breach involontari. |
| **R6** | **Familiarizzazione con i database in cloud** | Tempo | Medio | Bassa | **Accept** | La necessità di configurare e gestire i servizi cloud con scalabilità automatica richiede un periodo di adattamento per i developer. Impatto basso in quanto lo stack tecnologico è supervisionato dal CTO e i tempi di setup iniziale sono già stati assorbiti nella pianificazione. Il rischio viene accettato. |

## Gestione dei buffer e delle riserve
Per assorbire gli impatti derivanti dai rischi sopra elencati (in particolare **R2** e **R4**), la pianificazione operativa prevede due barriere di protezione strutturali:

### 1. Riserva dei Tempi
* **Applicazione**: margine di protezione del 10% applicato direttamente sulle attività del **Percorso Critico** (principalmente autenticazione, sottomissione progetti e motore di calcolo delle classifiche).
* **Scopo**: assorbire eventuali ritardi minori legati alla curva di apprendimento tecnologica delle API senza far slittare la consegna dell'MVP.

### 2. Riserva Finanziaria
* **Applicazione**: accantonamento di una quota di contingenza pari a €3.000 (10% del budget totale di €30.000).
* **Scopo**: questa somma verrà sbloccata esclusivamente dal Project Manager in caso di attivazione dei piani di contingenza, come l'acquisto di servizi terzi per l'integrazione con GitHub o per coprire i costi di auto-scaling del cloud in caso di picchi di carico.