---
layout: default
title: Launching & Execution
nav_order: 4
---

# Launching & Execution

Questa sezione ufficializza l'ingresso del progetto HackVillage nella sua fase operativa, definendo l'assetto iniziale concordato tra il team di sviluppo e HackIT Community per l'avvio della pianificazione agile.

## Kick-off Meeting

L'esecuzione del progetto ha inizio formale con il **Kick-off Meeting**, un incontro di allineamento strategico volto a mappare obiettivi, flussi decisionali, scadenze e aspettative operative dell'MVP. 

L'ordine del giorno ha seguito i seguenti punti chiave:
1. **Visione del committente**: allineamento sugli obiettivi di centralizzazione delle 7 macro-aree operative.
2. **Roadmap di progetto**: analisi del percorso critico guidato dallo sviluppo backend e approvazione dei vincoli temporali.
3. **Presentazione del team**: definizione dei flussi operativi tra le 5 risorse assegnate all'iniziativa.
4. **Metodologia Agile**: introduzione del framework SCRUM adattato alla forte parallelizzazione garantita dall'approccio *API-first*.
5. **Regole di collaborazione**: approvazione dei protocolli interni per la gestione delle emergenze e delle modifiche tecniche.


## Matrice RASCI
Per evitare colli di bottiglia e ottimizzare il coordinamento dei due sviluppatori backend e frontend, viene formalizzata la distribuzione dei carichi di lavoro tramite logica RASCI:

* **(R) Responsible**: chi esegue materialmente il task.
* **(A) Accountable**: chi ha la responsabilità ultima dell'approvazione del deliverable.
* **(S) Support**: chi interviene operativamente a supporto del responsabile per sbloccare le attività.
* **(C) Consulted**: chi fornisce pareri specialistici o requisiti funzionali.
* **(I) Informed**: chi deve ricevere gli aggiornamenti di stato sull'avanzamento dei lavori.

| Macro-attività | Arcese | Colì | Merighi | Meco | Dionisi | Stakeholder |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Studio e Formazione Stack Cloud** | **A** | I | **R** | **R** | C | I |
| **Avvio & Configurazione Setup Cloud** | **A** | I | **R** | I | I | I |
| **Definizione Contratti & Mock API Core** | **A** | C | **R** | **R** | I | I |
| **Sviluppo Componenti Backend** | **A** | C | **R** | I | I | I |
| **Sviluppo Componenti Frontend** | **A** | C | I | **R** | C | I |
| **Integrazione Flussi** | **A** | I | **R** | **R** | I | I |
| **Testing, Stress Test & Validazione Carico** | **A** | I | **R** | **R** | **S** | I |
| **Documentazione Tecnica e Report di Progetto** | **A** | C | **R** | **R** | I | I |
| **Collaudo UAT, Consegna & Go-Live Finale** | **A** | **R** | **S** | **S** | I | **C** |

## Strumenti utilizzati per l'esecuzione

La conduzione operativa si appoggia su quattro pilastri tecnologici per garantire la massima trasparenza informativa:

* **GitHub**: piattaforma centralizzata per il controllo di versione del codice. Sfrutta branch separati per backend e frontend per consentire lo sviluppo parallelo, integrando pipeline di Continuous Integration per monitorare la stabilità dei rilasci intermedi.
* **YouTrack**: hub di tracciamento per la metodologia SCRUM. Viene utilizzato per suddividere i work packages della WBS in task elementari, pianificare i cicli settimanali e misurare la velocity del team rispetto ai 38 Story Points stimati per sprint.
* **Microsoft Teams / Slack**: canale dedicato alla comunicazione interna quotidiana. Ospita i meeting formali ed evita disallineamenti sui contratti delle rotte scritte in fase di mock.
* **Draw.io / Lucidchart**: software di modellazione grafica impiegato per la documentazione visiva degli schemi logici del database, dei flussi di autenticazione RBAC e della topologia del Project Network Diagram.

## Regole operative del team

### 1. Problem solving
Per evitare che imprevisti tecnici o bug bloccanti sul percorso critico rallentino la consegna dell'MVP, il team adotta un flusso strutturato di risoluzione prima di registrare le azioni nell'Issue Log:
1. **Definizione**: si chiarisce e si delimita il problema in modo preciso, descrivendo contesto, impatti e obiettivi della risoluzione.
2. **Analisi delle cause**: Identificare l'origine tecnica o logica del problema.
3. **Brainstorming**: sessione rapida di proposte per soluzioni creative senza filtri, coinvolgendo attivamente tutti i membri.
4. **Valutazione**: selezione dell'idea migliore pesandone la fattibilità rispetto al budget e ai tempi rimanenti della baseline.
5. **Piano d'azione**: allocazione immediata del fix all'interno del codice per ripristinare il flusso di sviluppo.

### 2. Decision making
Le scelte relative all'architettura software o alle priorità operative non vengono prese in modo gerarchico. Ogni membro del team partecipa attivamente esprimendo il proprio parere tecnico. Il Mental Coach interviene specificamente per valutare l'impatto cognitivo ed evitare fenomeni di burnout derivanti da un carico lavorativo eccessivo concentrato su soli due programmatori. Tutte le decisioni vincolanti vengono registrate dal PM a tutela dei criteri di successo qualitativi.

### 3. Team meetings
Lo sviluppo segue una programmazione incrementale scandita da sprint settimanali per mantenere reattivo il ciclo di feedback:
* **Daily SCRUM**: sessioni di allineamento di 10-15 minuti ogni mattina. Si analizzano i progressi sul codice e si verifica la tenuta dei contratti API finti per non bloccare il frontend. I problemi complessi emersi in questa sede vengono rimandati a riunioni tecniche pomeridiane ad-hoc per non frammentare il focus della giornata.
* **Sprint planning**: definizione degli obiettivi all'inizio di ogni sprint e sblocco dei task dal product backlog in base alle priorità fissate.
* **Sprint review**: si svolge alla fine di ogni sprint per presentare i risultati ottenuti agli stakeholder e raccogliere feedback utili per i cicli successivi.

### 4. Gestione dei cambiamenti di scope 
Data l'inflessibilità del budget economico e dei 3 mesi di calendario, i cambi di perimetro seguono un iter rigido:
1. **Richiesta formale**: la risorsa propone la modifica al PM documentando benefici e motivazioni (es: implementazione di notifiche in-app o gamification, inizialmente catalogate tra i semplici desideri opzionali).
2. **Analisi degli impatti**: il CEO e il PM calcolano l'impatto sui giorni residui del percorso critico, valutano eventuali benefici e rischi associati e valutano l'eventuale sblocco della riserva di contingenza di €3.000.
3. **Confronto straordinario**: convocazione degli stakeholder per valutare la sostenibilità strategica della modifica.
4. **Verdetto**: il PM decreta l'esito:
    * *Approvata*: modifica inserita a backlog e Gantt aggiornato.
    * *Parzialmente Approvata*: funzionalità ridimensionata o spostata nella lista dei futuri *NICE-TO-HAVE*.
    * *Rifiutata*: istanza respinta con motivazione formale se rischia di compromettere la stabilità del Go-Live.
