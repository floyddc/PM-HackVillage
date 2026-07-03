---
layout: default
title: Launching & Execution
nav_order: 4
---

# Launching & Execution

Questa sezione ufficializza l'ingresso del progetto HackVillage nella sua fase operativa, definendo l'assetto iniziale concordato tra il team di sviluppo e HackIT Community per l'avvio della pianificazione agile.

## Kick-off Meeting

L'esecuzione ha inizio formale con un incontro di allineamento strategico volto a mappare obiettivi, flussi decisionali e scadenze dell'MVP. 

L'ordine del giorno ha seguito i seguenti punti chiave:
1. **Visione del Committente**: Allineamento sugli obiettivi di centralizzazione delle 7 macro-aree operative (gestione eventi, iscritti, team, mentor, submission, valutazioni, classifiche).
2. **Roadmap di Progetto**: Analisi del percorso critico guidato dallo sviluppo backend e approvazione dei vincoli temporali.
3. **Presentazione del Team**: Definizione dei flussi operativi tra le 5 risorse assegnate all'iniziativa.
4. **Metodologia Agile**: Introduzione del framework SCRUM adattato alla forte parallelizzazione garantita dall'approccio *API-first*.
5. **Regole di Collaborazione**: Approvazione dei protocolli interni per la gestione delle emergenze e delle modifiche tecniche.


## Matrice RASCI di Assegnazione delle Responsabilità

Per evitare colli di bottiglia e ottimizzare il coordinamento dell'unico sviluppatore backend e dell'unico sviluppatore frontend, viene formalizzata la distribuzione dei carichi di lavoro tramite logica RASCI:

* **(R) Responsible**: Chi esegue materialmente il task.
* **(A) Accountable**: Chi ha la responsabilità ultima dell'approvazione del deliverable.
* **(S) Support**: Chi interviene operativamente a supporto del responsabile per sbloccare le attività.
* **(C) Consulted**: Chi fornisce pareri specialistici o requisiti funzionali.
* **(I) Informed**: Chi deve ricevere gli aggiornamenti di stato sull'avanzamento dei lavori.

| Macro-Attività del Progetto | G. Arcese | D. Colì | D. Merighi | D. Meco | D. Dionisi | Stakeholder |
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

---

## Strumenti Utilizzati (Da vedere bene)

La conduzione operativa si appoggia su quattro pilastri tecnologici per garantire la massima trasparenza informativa:

* **GitHub**: Piattaforma centralizzata per il controllo di versione del codice. Sfrutta branch separati per backend e frontend per consentire lo sviluppo parallelo, integrando pipeline di Continuous Integration per monitorare la stabilità dei rilasci intermedi.
* **YouTrack**: Hub di tracciamento per la metodologia SCRUM. Viene utilizzato per suddividere i work packages della WBS in task elementari, pianificare i cicli settimanali e misurare la velocity del team rispetto ai 38 Story Points stimati per sprint.
* **Microsoft Teams / Slack**: Canale dedicato alla comunicazione interna quotidiana. Ospita i meeting formali ed evita disallineamenti sui contratti delle rotte scritte in fase di mock.
* **Draw.io / Lucidchart**: Software di modellazione grafica impiegato per la documentazione visiva degli schemi logici del database, dei flussi di autenticazione RBAC e della topologia del Project Network Diagram.

## Regole Operative del Team

### 1. Problem Solving
Per evitare che imprevisti tecnici o bug bloccanti sul percorso critico rallentino la consegna dell'MVP, il team adotta un flusso strutturato di risoluzione:
1. **Definizione**: Si chiarisce e si delimita il problema in modo preciso, descrivendo contesto, impatti e obiettivi della risoluzione.
2. **Analisi delle Cause**: Identificare l'origine del problema.
3. **Brainstorming**: Sessione rapida di proposte per soluzioni creative senza filtri coinvolgendo tutti i membri in maniera attiva.
4. **Valutazione**: Selezione dell'idea migliore pesandone la fattibilità rispetto al budget e ai tempi rimanenti della baseline.
5. **Piano d'Azione**: Allocazione immediata del fix all'interno del codice per ripristinare il flusso di sviluppo.

### 2. Decision Making
Le scelte relative all'architettura software o alle priorità operative non vengono prese in modo gerarchico. Ogni membro del team partecipa attivamente esprimendo il proprio parere tecnico; il Mental Coach interviene specificamente per valutare l'impatto cognitivo ed evitare fenomeni di burnout derivanti da un carico lavorativo eccessivo concentrato su soli due programmatori. Tutte le decisioni vincolanti vengono registrate dal PM a tutela dei criteri di successo qualitativi.

### 3. Team Meetings
Lo sviluppo segue una programmazione incrementale scandita da sprint settimanali per mantenere reattivo il ciclo di feedback:
* **Daily SCRUM**: Sessioni di allineamento di 10-15 minuti ogni mattina. Si analizzano i progressi sul codice e si verifica la tenuta dei contratti API finti per non bloccare il frontend. I problemi complessi emersi in questa sede vengono rimandati a riunioni tecniche pomeridiane ad-hoc per non frammentare il focus della giornata.
* **Sprint Planning**: Definizione degli obiettivi all'inizio di ogni sprint e sblocco dei task dal product backlog in base alle priorità fissate.
* **Sprint Review**: si svolge alla fine di ogni sprint per presentare i risultati ottenuti agli stakeholder e raccogliere feedback utili per i cicli successivi.

### 4. Gestione dei Cambiamenti di Scope 
Data l'inflessibilità del budget economico e dei 3 mesi di calendario, i cambi di perimetro seguono un iter rigido:
1. **Richiesta formale**: La risorsa propone la modifica al PM documentando benefici e motivazioni (es. implementazione di notifiche in-app o gamification [HCI docet], inizialmente catalogate tra i semplici desideri opzionali).
2. **Analisi degli impatti**: Il PM e il CTO calcolano l'impatto sui giorni residui del percorso critico, valutano eventuali benefici e rischi associati e valutano l'eventuale sblocco della riserva di contingenza di €3.000.
3. **Confronto straordinario**: Convocazione degli stakeholder per valutare la sostenibilità strategica della modifica.
4. **Verdetto**: Il Project Manager decreta l'esito:
    * *Approvata*: Modifica inserita a backlog e Gantt aggiornato.
    * *Parzialmente Approvata*: Funzionalità ridimensionata o spostata nella lista dei futuri *Nice-To-Have*.
    * *Rifiutata*: Istanza respinta con motivazione formale se rischia di compromettere la stabilità del Go-Live.
