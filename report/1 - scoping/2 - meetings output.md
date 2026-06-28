## Meetings output

### SWOT analysis
Questa tipologia di analisi permette di mappare i fattori interni ed esterni per capire come posizionare HackVillage e minimizzare i rischi di sviluppo.

- **Fattori interni**:
  - **Strengths (punti di forza)**:
    - Presenza di ruoli chiari (CEO/PO, CTO/PM, sviluppatori dedicati) e una figura unica come il Mental Coach per preservare la produttività e la coesione del team.
    - Forte allineamento con il committente: questo garantisce una conoscenza approfondita e diretta dei reali problemi legati alla gestione degli hackathon.
    - Centralizzazione nativa: l'architettura è pensata fin dall'inizio per coprire l'intero ciclo di vita dell'evento in un unico ecosistema.
  - **Weaknesses (punti di debolezza)**:
    - Team di sviluppo ridotto: solo due sviluppatori effettivi (un backend e un frontend). C'è un forte rischio di bottleneck se uno dei due si assenta o se sorgono imprevisti complessi.
    - Dipendenza iniziale da un unico committente: il software nasce tarato su determinate specifiche, rischiando di mancare inizialmente di flessibilità per scopi commerciali esterni.

- **Fattori esterni**:
  - **Opportunities**:
    - Trend in forte crescita: università, aziende e startup utilizzano sempre più gli hackathon per innovare e acquisire nuovi talenti emergenti.
    - Inefficienza dei competitor generici: molte organizzazioni usano ancora strumenti frammentati. HackVillage si posiziona come soluzione verticale e specializzata (all-in-one).

  - **Threats (minacce)**:
    - Competitor strutturati e consolidati: esistono già piattaforme internazionali con forti capitali alle spalle.
    - Picchi di carico critici: gli hackathon generano un traffico "a impulsi" (centinaia di utenti che caricano progetti nello stesso identico minuto alla scadenza). Un crash del sistema durante la sottomissione distruggerebbe la reputazione della piattaforma.

### CoS (Conditions of Satisfation)
Queste condizioni, stabilite dai rappresentanti degli stakeholder (Marco Costantini e Davide Guidotti), definiscono i criteri minimi obbligatori affinché il progetto sia considerato un successo.

- **Tempistiche di rilascio**: la piattaforma (o quantomeno il MVP) deve essere completata, testata e pronta al rilascio in produzione entro e non oltre 3 mesi dall'avvio dei lavori, per consentire il collaudo prima del prossimo hackathon.
- **Vincoli di budget e costi operativi**: il costo totale di sviluppo non deve superare il budget massimo stanziato dal committente (€30.000). I costi di manutenzione devono rimanere al di sotto di una soglia mensile definita (poco meno di €700/mese) per garantire la sostenibilità economica della community sul lungo periodo.
- **Indipendenza dai tool esterni**: la piattaforma deve permettere di completare un hackathon dall'inizio alla fine, senza dover ricorrere a strumenti esterni.
- **Scalabilità e performance**: il sistema deve garantire alte performance e stabilità durante la finestra critica di submission dei progetti. L'architettura deve reggere il caricamento simultaneo di file pesanti da parte di tutti i team iscritti senza subire rallentamenti.
- **User experience organizzativa**: la formazione dei team e l'assegnazione dei mentor devono essere flessibili e richiedere al massimo pochi click da parte dell'organizzatore, riducendo drasticamente il tempo di coordinamento rispetto alla vecchia gestione manuale.


### PoS (Project Overview Statement)
- **Problema**: attualmente, HackIT Community si trova ad affrontare gravi inefficienze operative e difficoltà di coordinamento durante l'organizzazione dei propri hackathon. La gestione delle attività è frammentata su strumenti eterogenei e non integrati:
  - La registrazione avviene tramite moduli isolati (Google Forms).
  - La formazione dei team e l'assegnazione dei mentor sono gestite manualmente su complessi fogli Excel, ad alto rischio di errore umano.
  - La sottomissione dei progetti e la valutazione da parte dei giudici avvengono tramite piattaforme terze (GitHub o form dedicati), costringendo gli organizzatori a faticosi travasi manuali di dati per stilare le classifiche finali.

  Questo scenario si traduce in una perdita di dati, in un sovraccarico amministrativo per gli organizzatori e in un'esperienza utente disorganizzata per partecipanti e mentor. Vedere _Market analysis_ per ulteriori dettagli.

- **Opportunità**: gli hackathon stanno vivendo una crescita esponenziale come strumenti di open innovation e talent acquisition per università, startup e aziende. Sviluppare una piattaforma proprietaria verticale consente a HackIT Community non solo di azzerare le proprie inefficienze interne, ma di posizionarsi sul mercato con un prodotto "all-in-one" testato sul campo. Una volta consolidata, la piattaforma rappresenterà un asset commerciale scalabile, concedibile in licenza (SaaS) ad altre organizzazioni, trasformando un centro di costo in una potenziale fonte di ricavo. Vedere _Market analysis_ per ulteriori dettagli.

- **Goal**: progettare, sviluppare e rilasciare la piattaforma web HackVillage per supportare e automatizzare in un unico ecosistema digitale le 7 fasi operative chiave degli hackathon di HackIT Community (gestione eventi, registrazioni, formazione team, assegnazione mentor, raccolta submission, valutazione progetti, classifiche finali), riducendo del 50% il tempo di gestione amministrativa degli organizzatori.

- **Success criteria**: il successo del progetto sarà misurato in base a indicatori quantitativi e qualitativi legati all'adozione dell'MVP:
  - Conduzione di un intero hackathon dall'inizio alla fine utilizzando esclusivamente HackVillage, con il totale abbandono di strumenti esterni.
  - Riduzione del tempo necessario per il completamento di fasi operative automatizzabili, quali l'assegnazione dei mentor e per il calcolo automatizzato delle classifiche finali.
  - Raggiungimento del 100% di disponibilità della piattaforma durante la delicata finestra temporale di sottomissione dei progetti, supportando il caricamento simultaneo di file senza crash del server.
  - Raggiungimento di un punteggio di soddisfazione pari o superiore all'80% tramite un sondaggio post-evento somministrato a partecipanti, mentor e giudici.

- **Assunzioni e rischi**:
  - Si assume che gli stakeholder siano costantemente disponibili per fornire feedback rapidi alla fine di ogni iterazione/sprint.
  - Si assume che le tecnologie scelte dal CTO Gabriele Arcese siano pienamente padroneggiate dai due developer (Daniele e Daniel) per evitare colli di bottiglia formativi in fase di sviluppo.
  - Si assume la possibilità di configurare servizi Cloud di terze parti con scalabilità automatica per gestire i picchi di traffico.

  Vedere _Financial analysis_ per ulteriori dettagli.

### Desideri e bisogni

### RBS (Requirement Breakdown Structure)

### Stato del progetto
