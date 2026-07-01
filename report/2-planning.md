# Planning

La fase di pianificazione definisce la strategia operativa necessaria a trasformare i requisiti in una roadmap di rilascio concreta e sostenibile. Per rispondere con efficacia ai vincoli di tempo (3 mesi) e di budget (€15.000) dettati dagli stakeholder, il progetto adotta un approccio iterativo e incrementale calibrato sulle dimensioni del team. Questo garantisce la flessibilità necessaria a integrare i feedback continui del committente senza perdere di vista l'obiettivo principale: il rilascio di un MVP stabile e testato prima del prossimo hackathon.

Il processo di pianificazione si articola in tre direttrici fondamentali:
1. **Evoluzione dei Requisiti**: Traduzione diretta della RBS (Requirement Breakdown Structure) in una WBS (Work Breakdown Structure) analitica, convertendo i requisiti funzionali in task operativi pronti per lo sviluppo.
2. **Ottimizzazione del Flusso**: Scomposizione tecnica del lavoro per identificare tempestivamente le dipendenze tecnologiche e blindare il Percorso Critico.
3. **Bilanciamento del Carico**: Distribuzione mirata delle attività per massimizzare la produttività dell'unico sviluppatore Backend e dell'unico sviluppatore Frontend, azzerando i rischi di saturazione delle risorse.

## JPPS (Joint Project Planning Session)

Il JPPS è l'insieme di incontri collaborativi volti a definire la strategia di esecuzione tecnica, stimare lo sforzo operativo e raccogliere l'impegno formale di tutto il team di progetto prima dell'inizio delle attività di sviluppo.

### Partecipanti alla Sessione
| Risorsa | Ruolo nel Progetto | Contributo nel JPPS |
| :--- | :--- | :--- |
| **Diego Colì** | Product Owner (PO) / CEO | Validazione delle priorità di business e approvazione dei rilasci dei Work Packages della WBS. |
| **Gabriele Arcese** | Project Manager (PM) / CTO | Conduzione delle sessioni, facilitazione della stima tecnica e blindatura del Percorso Critico. |
| **Daniele Merighi** | Backend Developer | Scomposizione e stima dei task lato server, database e contratti delle API. |
| **Daniel Meco** | Frontend Developer | Scomposizione e stima dei task relativi all'interfaccia utente e integrazione delle API. |
| **Davide Dionisi** | Mental Coach | Monitoraggio e bilanciamento del carico cognitivo per garantire la sostenibilità del piano. |

---

### Struttura dei Meeting di Pianificazione

La sessione di pianificazione congiunta è stata strutturata in 3 meeting sequenziali e mirati, per passare progressivamente dalla strategia macroscopica ai singoli task di sviluppo.

#### Meeting #1: Definizione della Strategia di Sviluppo e Logica di Schedulazione
*   **Obiettivi**: Stabilire le regole d'ingaggio del team di sviluppo, la frequenza delle milestone e le strategie per neutralizzare i vincoli di risorse (solo due programmatori effettivi).
*   **Tematiche di Discussione**:
    *   **Sviluppo API-First**: Accordo per disaccoppiare il lavoro BE/FE; Daniele (BE) definirà i contratti delle API all'inizio di ogni blocco funzionale della WBS, consentendo a Daniel (FE) di lavorare in parallelo con dati mockati.
    *   **Avanzamento basato su Milestone**: Abbandono di logiche a sprint fissi in favore di rilasci incrementali basati sul completamento dei macro-moduli della WBS.
    *   **Mitigazione preventiva dei rischi della SWOT**: Pianificazione di stress test di carico sul server per il sistema di sottomissione dei progetti già a metà della timeline (circa 1.5 mesi dall'avvio), per evitare crash critici alla fine del progetto.
    *   **Sostenibilità del lavoro**: Definizione dei parametri di monitoraggio del carico cognitivo con il Mental Coach per prevenire colli di bottiglia e burnout.

#### Meeting #2: Transizione da RBS a WBS e Stima dello Sforzo
*   **Obiettivi**: Trasformare i requisiti funzionali emersi nello Scoping (RBS) in compiti operativi concreti (WBS) e stimare le relative durate.
*   **Tematiche di Discussione**:
    *   **Scomposizione in Work Packages**: Analisi di ciascuno dei 7 macro-requisiti della RBS e mappatura delle componenti tecniche necessarie per realizzarli.
    *   **Pianificazione e Stima delle Durate**: Assegnazione delle stime temporali (in ore/uomo o giorni) a ciascun task elementare della WBS, basandosi sul confronto diretto tra il developer Backend e il developer Frontend.
    *   **Identificazione delle Dipendenze**: Mappatura di quali task backend devono necessariamente precedere lo sviluppo frontend per evitare blocchi operativi.

#### Meeting #3: Blindatura della Baseline di Progetto e Approvazione
*   **Obiettivi**: Consolidare la schedulazione temporale definitiva, identificare il Percorso Critico e formalizzare l'impegno del team.
*   **Tematiche di Discussione**:
    *   **Definizione del Percorso Critico**: Individuazione della sequenza di task della WBS che non può subire alcun ritardo per non compromettere la consegna dell'MVP entro il limite invalicabile dei 3 mesi.
    *   **Allocazione Finale del Budget**: Associazione dei costi stimati ai pacchetti di lavoro della WBS per non superare il tetto dei €15.000.
    *   **Firma della Baseline**: Approvazione formale del piano di sviluppo da parte del Product Owner e avvio ufficiale dei lavori.
