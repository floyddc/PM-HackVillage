---
layout: default
title: Risks
nav_exclude: true
---

# Risk Analysis

Questo documento contiene il registro dei rischi e la strategia di gestione delle minacce approvata durante il Meeting #3 del JPPS. L'obiettivo è proteggere la baseline dei tempi (3 mesi) e del budget (€15.000) dalle potenziali deviazioni operative.

## Matrice di Valutazione dei Rischi

I rischi sono valutati in base alla **Probabilità** di accadimento, all'**Impatto** sul progetto e alla dimensione del vincolo d'ambito coinvolta (**Scope Triangle**).

| ID | Descrizione del Rischio | Scope Triangle | Probabilità | Impatto | Strategia / Azione | Descrizione dell'Impatto e Piano d'Azione |
| :---: | :--- | :---: | :---: | :---: | :---: | :--- |
| **R1** | **Interfaccia e UX non intuitiva** | Scopo/Qualità | Bassa | Critico | **Transfer** | Un'interfaccia complessa bloccherebbe l'adozione da parte di partecipanti e giudici, causando il fallimento dell'evento. Il rischio è considerato basso grazie ai continui test e alla supervisione del Mental Coach sulla UX cognitiva.
| **R2** | **Rallentamenti nello sviluppo (Collo di bottiglia)** | Tempo | Alta | Alta | **Mitigate** | Con un soli due sviluppatori, i ritardi sono un rischio concreto che minaccia la scadenza dei 3 mesi. L'impatto è alto perché il team è ridotto. Per mitigare il rischio, si adotta un approccio *API-first* per azzerare il context switch e lavorare in parallelo. In caso di blocco critico o assenza, è previsto l'innesto operativo del CTO a supporto del codice. |
| **R3** | **Cambiamenti improvvisi di mercato** | Scopo/Qualità | Minima | Alta | **Accept** | Vista la *Market analysis* iniziale che mostra un trend in forte crescita per gli hackathon aziendali e universitari, una contrazione improvvisa della domanda è considerata quasi impossibile. Il rischio viene accettato passivamente senza allocazione di budget o modifiche all'ambito. |
| **R4** | **Difficile integrazione con le API di GitHub** | Tempo | Medio | Medio | **Accept** | L'integrazione obbligatoria con GitHub per la raccolta delle submission potrebbe presentare complessità tecniche (rate-limiting o API complesse). Essendo una causa esterna, non è mitigabile direttamente all'avvio. Il rischio viene accettato: se dovesse causare ritardi, la feature di sincronizzazione automatica verrà declassata a "Nice-to-Have" e gestita tramite un fallback di upload manuale diretto. |
| **R5** | **Violazione o gestione non conforme dei dati (GDPR)** | Scopo/Qualità | Bassa | Critica | **Mitigate + Contingency** | Una violazione dei dati personali o degli iscritti comporterebbe sanzioni legali pesanti e un danno irreparabile alla reputazione di HackIT Community. Per mitigare, si implementano controlli rigidi sul trattamento e un'architettura di database protetta da middleware di sicurezza (RBAC). Il piano di contingenza prevede l'attivazione di una polizza assicurativa aziendale per coprire i danni economici derivanti da data-breach involontari. |
| **R6** | **Familiarizzazione con i database in Cloud** | Tempo | Medio | Bassa | **Accept** | La necessità di configurare e gestire i servizi cloud con scalabilità automatica richiede un periodo di adattamento per i developer. L'impatto è considerato basso in quanto lo stack tecnologico è supervisionato dal CTO e i tempi di setup iniziale sono già stati assorbiti nella pianificazione. Il rischio viene accettato. |

---

## Gestione dei Buffer e delle Riserve

Per assorbire gli impatti derivanti dai rischi sopra elencati (in particolare **R2** e **R4**), la pianificazione operativa prevede due barriere di protezione strutturali:

### 1. Riserva dei Tempi

* **Applicazione**: Margine di protezione del 10% applicato direttamente sulle attività del **Percorso Critico** (principalmente autenticazione, sottomissione progetti e motore di calcolo delle classifiche).
* **Scopo**: Assorbire eventuali ritardi minori legati alla curva di apprendimento tecnologica delle API senza far slittare la consegna dell'MVP.

### 2. Riserva Finanziaria

* **Applicazione**: Accantonamento di una quota di contingenza pari a €1.500 (10% del budget totale di €15.000).
* **Scopo**: Questa somma verrà sbloccata esclusivamente dal Project Manager in caso di attivazione dei piani di contingenza, come l'acquisto di servizi terzi per l'integrazione con GitHub o per coprire i costi di Auto-scaling del cloud in caso di picchi di carico.