---
layout: default
title: Monitoring & Control
nav_order: 5
---

# Monitoring & Controlling

L'obiettivo di questa fase è controllare e monitorare sistematicamente l’avanzamento delle attività per verificare che i tempi, i costi e gli obiettivi dell'MVP di HackVillage siano rigorosamente rispettati. Attraverso il monitoraggio è possibile individuare tempestivamente eventuali scostamenti o criticità rispetto al percorso critico stabilito, intervenendo con azioni correttive immediate per garantire la corretta realizzazione del progetto secondo quanto pianificato nella baseline.

## Reporting

Il progetto adotta il framework SCRUM, che assicura un monitoraggio continuo attraverso Sprint Planning, Daily SCRUM, Sprint Review e Sprint Retrospective. La suddivisione dello sviluppo in sprint incrementali permette di verificare costantemente l'avanzamento delle attività e il raggiungimento delle milestone previste.

## Monitoring quotidiano - YouTrack
Per la gestione operativa e il monitoraggio quotidiano viene utilizzato YouTrack, configurato con una Scrum Board dedicata al progetto HackVillage. Ogni attività derivata dalla WBS viene registrata come ticket e associata allo sprint di riferimento. Per ciascun ticket vengono tracciate informazioni quali:

- Priorità.
- Stato di avanzamento (*To Do, In Progress, In Review, Done*).
- Story Points, stimati sulla base della velocity del team (38 SP per sprint).
- Assegnatario.
- Componente di sviluppo (backend o frontend).
- Data di scadenza.

La scelta di YouTrack si basa sulla sua affidabilità, sulla semplicità di utilizzo e sulla perfetta integrazione con le metodologie Agile, ottimizzando il coordinamento di un team snello ed evitando dispersioni comunicative.

YouTrack mette inoltre a disposizione dashboard personalizzate e report automatici che consentono al Project Manager di monitorare costantemente lo stato del progetto. In particolare vengono utilizzati:

| **Tipologia di report** | **Tool** | **Utilizzo** |
| --- | --- | --- |
| **Current Period**	| Burndown Chart | Verifica dell'andamento dello sprint confrontando il lavoro completato con quello ancora da svolgere.
| **Current Period**	| Activity Stream | Monitoraggio delle modifiche effettuate ai ticket e delle attività svolte dal team.
| **Cumulative**	| Cumulative Flow Diagram | Analisi del flusso delle attività nei diversi stati per individuare eventuali colli di bottiglia.
| **Exception** | Saved Searches e Dashboard | Individuazione automatica di ticket bloccanti, scaduti o ad alta priorità.
| **Variance** | Time Report (Estimated vs Actual) | Confronto tra le stime iniziali e il lavoro effettivamente svolto per evidenziare eventuali scostamenti dalla pianificazione.

Durante i Daily SCRUM il team consulta la Scrum Board per verificare l'avanzamento delle attività e aggiornare lo stato dei ticket. Nelle Sprint Review e nelle Retrospettive vengono invece analizzati i report prodotti da YouTrack per valutare le prestazioni dello sprint, identificare eventuali criticità e pianificare azioni di miglioramento.

Le attività non completate entro la fine dello sprint vengono riportate automaticamente nel backlog e rivalutate durante lo Sprint Planning successivo, mantenendo allineata la pianificazione con le priorità del progetto e preservando il margine di flessibilità disponibile per le attività di sviluppo.

### Issue Log
Per la gestione delle problematiche tecniche e organizzative viene utilizzato l'Issue Log integrato in YouTrack. Ogni bug, impedimento o anomalia viene registrato come issue dedicata, consentendo al team di monitorarne lo stato durante l'intero ciclo di vita del progetto.

Per ogni issue vengono registrate le seguenti informazioni:

*   **ID Number**: codice identificativo univoco del ticket di errore.
*   **Data di apertura**: data di rilevazione del problema durante lo sprint.
*   **Descrizione del problema**: dettaglio tecnico del bug. 
*   **Impatto sul progetto**: valutazione degli effetti sulla timeline, sulle milestone o sull'eventuale minaccia di slittamento del percorso critico di backend.
*   **Assegnatario**: assegnazione della responsabilità della risoluzione.
*   **Azione intrapresa**: piano d'azione correttivo e dettagliato volto a risolvere l'anomalia.
*   **Stato**: condizione del ticket (*Aperto, In Corso, In Verifica, Chiuso*).
*   **Esito**: risoluzione formale e impatto finale sulla baseline dell'MVP.
*   **Data di chiusura**: conclusione della risoluzione.

L'Issue Log viene consultato quotidianamente durante i Daily SCRUM e riesaminato nelle Sprint Review e nelle Retrospettive per verificare l'evoluzione delle problematiche aperte e pianificare eventuali azioni correttive.

### Scope Bank
Le richieste di nuove funzionalità non comprese nello scope iniziale dell'MVP vengono registrate in uno Scope Bank gestito tramite un backlog dedicato in YouTrack. Ogni richiesta viene documentata con una descrizione, una valutazione preliminare dell'impatto e una priorità, senza influenzare la pianificazione dello sprint in corso.

Lo Scope Bank viene riesaminato al termine di ogni sprint e le nuove funzionalità vengono eventualmente inserite nel Product Backlog soltanto se risultano compatibili con i vincoli di tempo, costo e qualità definiti nella baseline del progetto. Questo approccio consente di gestire le richieste di cambiamento senza compromettere gli obiettivi dell'MVP.