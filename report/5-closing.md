---
layout: default
title: Closing
nav_order: 6
---

# Closing

L'obiettivo di questa fase finale è formalizzare la conclusione di tutte le attività legate all'MVP di HackVillage, sancire il passaggio di consegne ufficiale a HackIT Community e raccogliere i feedback conclusivi del team per capitalizzare l'esperienza a beneficio di iniziative future. Con il superamento dell'ultimo sprint, il progetto congela la sua baseline e si prepara all'esercizio live.


## Inventario unico della Documentazione di Progetto

Durante l'intero ciclo di vita di HackVillage, il team ha prodotto e strutturato una suite documentale centralizzata, accessibile tramite GitHub Pages, che traccia l'evoluzione strategica, tecnica e di controllo del software:

1.  **Contesto**: presentazione dello scenario operativo, della community committente (HackIT) e dell'assetto delle risorse.
2.  **SWOT Analysis**: valutazione strategica dei punti di forza, debolezza interni e delle opportunità e minacce del mercato di riferimento.
3.  **Conditions of Satisfaction (CoS)**: criteri minimi qualitativi e quantitativi richiesti dagli stakeholder per decretare il successo dell'iniziativa.
4.  **Project Overview Statement (POS)**: sintesi esecutiva ufficiale contenente il problema cardine, il macro-obiettivo e i vincoli d'ambito.
5.  **Market Analysis**: analisi del posizionamento competitivo rispetto a software generici e piattaforme enterprise internazionali.
6.  **Financial Analysis**: stima analitica dei costi interni del personale, dei costi cloud AWS esterni e proiezioni sul ROI atteso.
7.  **Desideri e Bisogni**: mappatura, analisi e categorizzazione delle necessità funzionali ed emozionali dei diversi utenti della piattaforma.
8.  **Requirement Breakdown Structure (RBS)**: scomposizione gerarchica ad albero di tutti i requisiti funzionali e non funzionali del sistema.
9.  **Stato del Progetto**: definizione analitica dello scenario *AS-IS*, *TO-BE* e catalogo delle funzionalità future *NICE-TO-HAVE*.
10. **Work Breakdown Structure (WBS)**: scomposizione analitica dei requisiti in compiti operativi e task tecnici elementari sulle 7 macro-aree.
11. **Project Network Diagram (PND)**: mappa logica sequenziale delle precedenze tecnologiche (Finish-to-Start) con calcolo dello *Slack* e del percorso critico backend.
12. **Diagramma di Gantt**: pianificazione temporale analitica al singolo giorno lavorativo distribuita sulle 12 settimane di calendario.
13. **Risk Analysis**: registro delle minacce d'ambito valutate per probabilità e impatto, con annessi piani di mitigazione, contingenza e buffer dedicati.
14. **Launching & Execution**: regolamentazione formale del Kick-off meeting, matrice RASCI delle responsabilità e linee operative di collaborazione.
15. **Monitoring & Controlling**: protocolli di tracciamento metriche (Burndown, CFD) via YouTrack, gestione anomalie tramite *Issue Log* e blocco dello scope creep tramite *Scope Bank*.

## Accettazione e consegna del Progetto

Il trasferimento di responsabilità dell'applicativo viene strutturato secondo i seguenti passaggi operativi dopo il superamento dei collaudi UAT (User Acceptance Testing) eseguiti nel pacchetto `WP-DEPLOY`:
1. **Verifica dei Criteri di Successo**: Il Product Owner e il Project Manager esaminano il software rispetto alle *Conditions of Satisfaction* pattuite, accertando che l'intera competizione possa essere eseguita senza tool esterni.
2. **Firm-off e Chiusura Contabile**: Gli stakeholder firmano il verbale di accettazione finale, formalizzando il rispetto del budget di €30.000  e autorizzando la messa in produzione definitiva su cloud AWS.
3. **Archiviazione degli Strumenti**: I branch di sviluppo parallelo di GitHub (`feature/backend-*` e `feature/frontend-*`) vengono fusi nel branch `main` e taggati come release stabile `v1.0.0-MVP`. La board di YouTrack viene pulita e le richieste inevase nello *Scope Bank* vengono congelate nel backlog per le evolutive future.

## Post-Implementation Audit

Al termine del ciclo di vita del progetto, il team ha condotto un audit interno per analizzare gli scostamenti rispetto ai piani iniziali e valutare l'efficacia delle metodologie adottate:

### Cosa ha funzionato con successo

*   **Efficacia dell'Approccio API-First**: La progettazione iniziale dei contratti e delle rotte fittizie in `WP-MOCK` ha blindato il parallelismo dello sviluppo. Gli sviluppatori hanno lavorato senza interdipendenze bloccanti, riducendo drasticamente il time-to-market delle prime 4 macro-aree della WBS.
*   **Tenuta del Modello di Problem Solving**: L'applicazione rigorosa dei passi durante i Daily SCRUM ha permesso di circoscrivere tempestivamente le anomalie architetturali dell'Issue Log prima che potessero impattare la catena a scorrimento zero del percorso critico.
*   **Sostenibilità Psico-Cognitiva**: La supervisione attiva del Mental Coach ha evitato l'insorgere di colli di bottiglia legati al burnout. L'adozione di un decision-making partecipativo ha mantenuto alto il livello di motivazione dell'unico sviluppatore per lato.

### Cosa non ha funzionato e aree di miglioramento

*   **Sottostima della Complessità Algoritmica**: Il modulo di raccolta delle submission ha richiesto uno sforzo in Story Points superiore alle metriche del Planning Poker. Il monitoraggio tramite il *Cumulative Flow Diagram* ha evidenziato una saturazione temporanea sul binario di backend, costringendo il PM/CTO a intervenire operativamente in supporto al codice per non consumare la riserva dei tempi.
*   **Erosione dello Slack del Frontend**: A causa dei ritardi logici su alcune query SQL complesse ereditate dal motore di calcolo delle classifiche, lo sviluppatore frontend ha visto erodere quasi interamente il proprio margine di scorrimento (*Slack*) fluttuante, accumulando un forte carico di lavoro concentrato interamente nella settimana di convergenza di `WP-INTEGRATION`.

### Lezioni apprese per il futuro
1. Per progetti futuri con team ridotti all'osso, i pacchetti legati all'interazione con file system cloud e storage pesanti non devono essere stimati come singoli blocchi ma devono essere ulteriormente atomizzati in sotto-task all'interno della WBS.
2. Lo *Scope Bank* si è rivelato uno strumento indispensabile per proteggere la baseline dai desideri estranei degli stakeholder, salvaguardando il Go-Live entro il limite invalicabile dei 3 mesi.

## Conclusione

Il progetto **HackVillage** si conclude raggiungendo l'obiettivo prefissato: centralizzare e automatizzare l'intero ecosistema operativo di HackIT Community all'interno di un'unica piattaforma web proprietaria. L'integrazione delle 7 macro-aree originariamente frammentate elimina i travasi manuali di dati e mitiga drasticamente il rischio di errori nel calcolo delle classifiche, rispondendo pienamente ai requisiti funzionali della RBS e alle aspettative strategiche dei committenti. 

Il rigido controllo della baseline dei tempi e dei costi, supportato da un approccio metodologico SCRUM e da strumenti di monitoraggio come YouTrack, ha permesso di assorbire le criticità tecniche e di consegnare l'MVP entro i 3 mesi prestabiliti e nel pieno rispetto del budget di €30.000. Con il rilascio della versione `v1.0.0-MVP` e il superamento dei test UAT, la piattaforma è ufficialmente pronta per supportare il prossimo hackathon della community, posizionandosi al contempo come un asset tecnologico solido e scalabile per future monetizzazioni di tipo SaaS. Con questo ultimo atto di approvazione dei deliverables e la consegna delle chiavi architetturali, il progetto viene dichiarato **ufficialmente concluso**.