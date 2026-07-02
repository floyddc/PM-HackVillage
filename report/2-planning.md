---
layout: default
title: Planning
nav_order: 3
---

# Planning

La fase di pianificazione definisce la strategia operativa necessaria a trasformare i requisiti in una roadmap di rilascio concreta e sostenibile. Per rispondere con efficacia ai vincoli di tempo e di budget dettati dagli stakeholder, il progetto adotta un approccio iterativo e incrementale calibrato sulle dimensioni del team. Questo garantisce la flessibilità necessaria a integrare i feedback continui del committente senza perdere di vista l'obiettivo principale.

Il processo di pianificazione si articola in 4 direttrici fondamentali:
1. **Evoluzione dei requisiti**: traduzione diretta della [RBS](scoping/deliverables/RBS.md) in una [WBS](planning/deliverables/WBS.md) analitica, convertendo i requisiti funzionali in task operativi pronti per lo sviluppo.
2. **Ottimizzazione del flusso**: scomposizione tecnica del lavoro per identificare tempestivamente le dipendenze tecnologiche e blindare il Percorso Critico.
3. **Bilanciamento del carico**: distribuzione mirata delle attività per massimizzare la produttività dell'unico sviluppatore backend e dell'unico sviluppatore frontend, azzerando i rischi di saturazione delle risorse.
4. **Gestione dei rischi**: metodologie mirate alla gestione dei possibili rischi analizzati in fase di scooping, impedendo ad essi di interrompere o di rallentare il flusso di lavoro del team.

## JPPS (Joint Project Planning Session)

Il JPPS è l'insieme di incontri collaborativi volti a definire la strategia di esecuzione tecnica, stimare lo sforzo operativo e raccogliere l'impegno formale di tutto il team di progetto prima dell'inizio delle attività di sviluppo. Tale sessione di pianificazione è stata suddivisa in 3 meeting sequenziali, ognuno finalizzato all'ottenimento di un output matematico e operativo ben preciso.

### Definizione team
A differenza dei progetti tradizionali su larga scala, questa sessione _non si avvale di un facilitatore esterno dedicato_. Data la natura snella del team e la doppia competenza di Gabriele Arcese (che unisce le capacità organizzative del Project Manager alle competenze tecniche del CTO), è lo stesso PM a guidare le sessioni. Questa scelta azzera le ridondanze comunicative, accelera il processo decisionale e permette di calibrare immediatamente le scelte di business con i vincoli tecnologici e di budget. 

La presenza di ogni singolo partecipante è strettamente necessaria per blindare la fattibilità del piano, considerando che il team di sviluppo è ridotto al minimo e non sono ammessi margini di errore nell'allocazione delle risorse.

| Risorsa | Ruolo | Contributo |
| --- | --- | --- |
| **Diego Colì** | Product Owner / CEO | Garantisce l'allineamento con gli obiettivi di HackIT Community e valida le priorità di business durante la scomposizione delle attività. |
| **Gabriele Arcese** | Project Manager / CTO | Gestisce e conduce il JPPS senza facilitatori esterni. Cura la transizione logica dai requisiti alle tempistiche e presidia l'architettura tecnica del software. |
| **Daniele Merighi** | Backend Developer (Server-side) | Stima lo sforzo del database, delle logiche di business e per definisce la fattibilità tecnica dei pacchetti di lavoro. |
| **Daniel Meco** | Frontend Developer (Client-side) | Quantifica i tempi di sviluppo delle interfacce e garantisce che la UX sia allineata con i tempi di rilascio. |
| **Davide Dionisi** | Mental Coach | Valuta la sostenibilità psicologica del piano, prevenendo il burnout derivante dal carico di lavoro concentrato su soli due developer. |

## Meeting #1 - Dai requisiti alle attività
Nella prima JPPS lo scopo principale è stato quello di avviare il lavoro sul progetto e di iniziare a strutturare la base per la fase di pianificazione.

### Obiettivi
- Scomporre analiticamente i requisiti funzionali della [RBS](scoping/deliverables/RBS.md) in compiti operativi e task tecnici elementari per i programmatori.

### Tematiche di discussione
- Analisi dettagliata delle 7 macro-aree della [RBS](scoping/deliverables/RBS.md) per estrarre i singoli task necessari alla creazione dell'MVP.
- Definizione dell'approccio *API-first* per permettere al team di sviluppatori di lavorare in parallelo minimizzando le interdipendenze bloccanti.

### Output
- [WBS - Work Breakdown Structure](planning/deliverables/WBS.md) approvata.

## Meeting #2 - Sequenziamento e roadmap temporale
Una volta individuate le attività tramite il diagramma [WBS](planning/deliverables/WBS.md), è stato necessario capire come svolgere queste attività e stabilire il tempo necessario per l'esecuzione di essi.

### Obiettivi
- Determinare l'ordine logico di esecuzione delle attività mappate nella WBS.
- Calcolare le stime temporali.
- Strutturare il calendario dei rilasci.

### Tematiche di discussione
- Stima delle durate dei singoli work packages espressa in ore/uomo e giorni di sviluppo effettivi.
- Costruzione del diagramma reticolare ([PND](planning/deliverables/PND.md)) per stabilire i legami di precedenza tecnologica. 
- Identificazione del percorso critico per blindare la consegna finale entro la scadenza invalicabile dei 3 mesi.

### Output
- [PND - Project Network Diagram](planning/deliverables/PND.md)
- [Diagramma di Gantt](planning/deliverables/Gantt.md).

## Meeting #3 - Valutazione impatti e protezione baseline
Nell'ultimo meeting il team ha discusso su come gestire le potenziali criticità individuate durante la fase di scooping.

### Obiettivi
- Sottoporre la pianificazione temporale e finanziaria a uno stress-test teorico, individuando i potenziali ostacoli e definendo i piani di mitigazione.

### Tematiche di discussione
- Analisi dei rischi specifici legati alla pianificazione (es. collo di bottiglia dovuto all'assenza di uno dei due sviluppatori o complessità impreviste nell'integrazione con GitHub).
- Pianificazione anticipata degli stress test per il sistema di sottomissione progetti (punto critico della SWOT), fissandoli a metà della timeline.
- Strutturazione dei cuscinetti temporali (buffer) e allocazione delle riserve di contingenza sul budget.
- Validazione finale del Mental Coach sulla sostenibilità del ritmo di lavoro stabilito.

### Output
- [Risk analysis](planning/deliverables/Risks.md) approvata.
- Firma della baseline operativa.