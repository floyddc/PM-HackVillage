---
layout: default
title: Planning
nav_order: 3
---

# Planning

La fase di pianificazione definisce la strategia operativa necessaria a trasformare i requisiti in una roadmap di rilascio concreta e sostenibile. Per rispondere con efficacia ai vincoli di tempo (3 mesi) e di budget (€15.000) dettati dagli stakeholder, il progetto adotta un approccio iterativo e incrementale calibrato sulle dimensioni del team. Questo garantisce la flessibilità necessaria a integrare i feedback continui del committente senza perdere di vista l'obiettivo principale.

Il processo di pianificazione si articola in quattro direttrici fondamentali:
1. **Evoluzione dei Requisiti**: Traduzione diretta della RBS (Requirement Breakdown Structure) in una WBS (Work Breakdown Structure) analitica, convertendo i requisiti funzionali in task operativi pronti per lo sviluppo.
2. **Ottimizzazione del Flusso**: Scomposizione tecnica del lavoro per identificare tempestivamente le dipendenze tecnologiche e blindare il Percorso Critico.
3. **Bilanciamento del Carico**: Distribuzione mirata delle attività per massimizzare la produttività dell'unico sviluppatore Backend e dell'unico sviluppatore Frontend, azzerando i rischi di saturazione delle risorse.
4. **Gestione dei Rischi**: Metodologie mirate alla gestione dei possibili rischi analizzati in fase di scooping, impedendo ad essi di interrompere o di rallentare il flusso di lavoro del team.

## JPPS (Joint Project Planning Session)

Il JPPS è l'insieme di incontri collaborativi volti a definire la strategia di esecuzione tecnica, stimare lo sforzo operativo e raccogliere l'impegno formale di tutto il team di progetto prima dell'inizio delle attività di sviluppo. 

### Scelta del Team e Assenza di un Facilitatore Esterno
A differenza dei progetti tradizionali su larga scala, questa sessione non si avvale di un facilitatore esterno dedicato. Data la natura snella del team e la doppia competenza di Gabriele Arcese (che unisce le capacità organizzative del Project Manager alle competenze tecniche del CTO), è lo stesso PM a guidare le sessioni. Questa scelta azzera le ridondanze comunicative, accelera il processo decisionale e permette di calibrare immediatamente le scelte di business con i vincoli tecnologici e di budget. 

La presenza di ogni singolo partecipante è strettamente necessaria per blindare la fattibilità del piano, considerando che il team di sviluppo è ridotto al minimo e non sono ammessi margini di errore nell'allocazione delle risorse.

### Partecipanti alla Sessione

| Risorsa | Ruolo nel Progetto | Contributo e Necessità nel JPPS |
| :--- | :--- | :--- |
| **Diego Colì** | Product Owner (PO) / CEO | Essenziale per garantire l'allineamento con gli obiettivi di HackIT Community e validare le priorità di business durante la scomposizione delle attività. |
| **Gabriele Arcese** | Project Manager (PM) / CTO | Gestisce e conduce il JPPS senza facilitatori esterni. Cura la transizione logica dai requisiti alle tempistiche e presidia l'architettura tecnica del software. |
| **Daniele Merighi** | Backend Developer | Unica risorsa lato server. La sua presenza è critica per stimare lo sforzo del database, delle logiche di business e per definire la fattibilità tecnica dei pacchetti di lavoro. |
| **Daniel Meco** | Frontend Developer | Unica risorsa lato client. Indispensabile per quantificare i tempi di sviluppo delle interfacce e garantire che l'esperienza utente sia allineata con i tempi di rilascio. |
| **Davide Dionisi** | Mental Coach | Figura strategica per valutare la sostenibilità psicologica del piano. Il suo contributo serve a prevenire il burnout derivante dal carico di lavoro concentrato su soli due developer. |

---

### Struttura dei Meeting di Pianificazione

La sessione di pianificazione congiunta è stata suddivisa in 3 meeting sequenziali, ognuno finalizzato all'ottenimento di un output matematico e operativo ben preciso.

#### Meeting #1: Transizione da Requisiti ad Attività
Nella prima JPPS lo scopo principale è stato quello di avviare il lavoro sul progetto e di iniziare a strutturare la base per la fase di pianificazione.
*   **Obiettivi**: Scomporre analiticamente i requisiti funzionali della RBS (Requirement Breakdown Structure) in compiti operativi e task tecnici elementari per i programmatori.
*   **Tematiche di Discussione**:
    *   Analisi dettagliata delle 7 macro-aree della RBS per estrarre i singoli task necessari alla creazione dell'MVP.
    *   Definizione dell'approccio *API-first* per permettere al team di sviluppatori di lavorare in parallelo minimizzando le interdipendenze bloccanti.
*   **Output Raggiunto**: Approvazione della **WBS (Work Breakdown Structure)** completa.

Aggiungere link a WBS

#### Meeting #2: Sequenziamento e Roadmap Temporale
Una volta individuate le attività tramite il diagramma WBS, è stato necessario capire come svolgere queste attività e stabilire il tempo necessario per l'esecuzione di essi.
*   **Obiettivi**: Determinare l'ordine logico di esecuzione delle attività mappate nella WBS, calcolare le stime temporali e strutturare il calendario dei rilasci.
*   **Tematiche di Discussione**:
    *   Stima delle durate dei singoli Work Packages espressa in ore/uomo e giorni di sviluppo effettivi.
    *   Costruzione del diagramma reticolare (PND - Project Network Diagram) per stabilire i legami di precedenza tecnologica.
    *   Identificazione del Percorso Critico per blindare la consegna finale entro la scadenza invalicabile dei 3 mesi.

 **Output Raggiunto**: Definizione del **PND** e del diagramma di **Gantt** di progetto.

Aggiungere link a pnd e gantt 

#### Meeting #3: Valutazione degli Impatti e Protezione della Baseline
Nell'ultimo meeting il team ha discusso su come gestire le potenziali criticità individuate durante la fase di scooping.
*   **Obiettivi**: Sottoporre la pianificazione temporale e finanziaria a uno stress-test teorico, individuando i potenziali ostacoli e definendo i piani di mitigazione.

*   **Tematiche di Discussione**:
    *   Analisi dei rischi specifici legati alla pianificazione (es. collo di bottiglia dovuto all'assenza di uno dei due sviluppatori o complessità impreviste nell'integrazione con GitHub).
    *   Pianificazione anticipata degli stress test per il sistema di sottomissione progetti (punto critico della SWOT), fissandoli a metà della timeline.
    *   Strutturazione dei cuscinetti temporali (buffer) e allocazione delle riserve di contingenza sul budget di €15.000.
    *   Validazione finale del Mental Coach sulla sostenibilità del ritmo di lavoro stabilito.
    *   **Output Raggiunto**: Approvazione del documento definitivo di **Risk Analysis** e firma della baseline operativa.

 Aggiungere link a rink analysis 
