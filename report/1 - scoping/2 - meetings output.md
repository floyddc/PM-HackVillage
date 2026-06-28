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
- **Desideri**:
  * **Notifiche real-time**: sistema di avvisi automatici (email o in-app) per comunicare ai partecipanti l'apertura delle iscrizioni, l'assegnazione dei mentor o la pubblicazione dei risultati.
  * **Dashboard delle performance**: visualizzazione grafica del trend di partecipazione e delle statistiche relative alla qualità dei progetti sottomessi.
  * **Supporto multilingua**: interfaccia disponibile in più lingue per favorire la partecipazione internazionale agli hackathon.
  * **Ottimizzazione mobile-first**: piattaforma perfettamente responsiva per permettere ai partecipanti di monitorare scadenze e comunicazioni anche da dispositivi mobile.
  * **Gamification**: aggiunta di elementi ludici (badge o barre di progresso) per aumentare il coinvolgimento dei partecipanti durante le fasi di sviluppo.
  * **Tutorial e FAQ interattive**: sezione dedicata all'interno della piattaforma per guidare gli utenti nell'utilizzo delle funzioni principali e nello svolgimento corretto della competizione.

- **Bisogni**:
  * **Gestione centralizzata dell'evento**: possibilità per l'organizzatore di creare, gestire e pubblicare eventi in un unico pannello di controllo.
  * **Sistema di registrazione e profilazione**: accesso differenziato per ruolo (Organizzatore, Partecipante, Mentor, Giudice) con dashboard dedicate a seconda delle autorizzazioni.
  * **Workflow di formazione team**: funzionalità intuitiva per consentire ai partecipanti di creare team e agli organizzatori di validarne la composizione.
  * **Gestione digitale delle submission**: sistema sicuro e scalabile per il caricamento dei progetti e dei file associati entro le scadenze prestabilite.
  * **Motore di valutazione**: strumento integrato per i giudici per inserire punteggi, commenti e feedback in tempo reale sui progetti.
  * **Calcolo automatizzato delle classifiche**: generazione in tempo reale delle classifiche finali sulla base dei voti inseriti dai giudici, eliminando i calcoli manuali.
  * **Compliance e sicurezza**: protezione dei dati personali in conformità con la normativa GDPR.
  * **Stabilità sotto carico**: architettura resiliente in grado di supportare picchi di traffico simultaneo, specialmente durante le submission dei progetti.

### RBS (Requirement Breakdown Structure)

### Stato del progetto
- **AS-IS**: attualmente, l'organizzazione degli hackathon da parte di HackIT Community soffre di una forte frammentazione operativa, che causa inefficienze e rallentamenti:
  * **Gestione destrutturata**: Le attività sono distribuite su strumenti eterogenei (Excel, GitHub, Google Forms, email), senza una base di dati comune.
  * **Processi manuali**: la formazione dei team e l'assegnazione dei mentor avvengono tramite fogli di calcolo, comportando un alto rischio di errore umano e una gestione complessa.
  * **Comunicazione frammentata**: le informazioni sono disperse tra diversi canali, rendendo difficile il coordinamento tra organizzatori, mentor e partecipanti.
  * **Valutazione complessa**: i giudici operano su piattaforme terze, costringendo gli organizzatori a operazioni di "travaso" manuale dei dati per stilare le classifiche finali.

- **TO-BE**: la visione di HackVillage mira a trasformare l'ecosistema digitale della community in una piattaforma web centralizzata:
  * **Piattaforma web all-in-one**: unico ambiente digitale per gestire l'intero ciclo di vita dell'hackathon (eventi, registrazione, team, mentor, submission e classifiche).
  * **Automazione dei processi**: automazione delle fasi critiche (assegnazione mentor, calcolo classifiche) per ridurre drasticamente il carico amministrativo.
  * **Ecosistema integrato**: eliminazione totale degli strumenti esterni, centralizzando ogni flusso operativo all'interno di HackVillage.
  * **Stabilità e scalabilità**: architettura resiliente in grado di supportare picchi di traffico simultaneo durante la sottomissione dei progetti.

- **NICE-TO-HAVE**: funzionalità opzionali pianificate per cicli di rilascio successivi al completamento dell'MVP:
  * **App mobile dedicata**: sviluppo di un'applicazione nativa per migliorare l'esperienza utente on-the-go.
  * **Notifiche avanzate**: implementazione di avvisi automatici tramite SMS o canali di messaggistica istantanea (es: Telegram).
  * **Integrazione con API esterne**: ulteriori integrazioni con tool di terze parti per analisi avanzate delle performance.
  * **SaaS commerciale**: evoluzione della piattaforma in una soluzione licenziabile per altre organizzazioni esterne alla community.
