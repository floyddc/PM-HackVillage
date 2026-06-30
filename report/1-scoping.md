---
layout: default
title: Scoping
nav_order: 2
---

# Scoping

La definizione dei requisiti, del perimetro operativo e delle linee guida strategiche di HackVillage è stata strutturata attraverso una serie di tre meeting principali. Questa fase ha visto la collaborazione sinergica e attiva del team di sviluppo, del management e dei rappresentanti del committente (HackIT Community).

L'approccio iterativo e incrementale adottato ha permesso di allineare progressivamente la visione di business alle specifiche tecniche e architetturali, riducendo al minimo le ambiguità e strutturando un percorso di sviluppo chiaro, tracciabile e orientato al rilascio di valore reale per la community.

## Meeting #1 - Identificazione problema e allineamento strategico

### Obiettivi
- Comprendere il problema di fondo della frammentazione degli strumenti di HackIT Community.
- Allineare il team e gli stakeholder sulla direzione strategica del brand. 
- Definire l'identità ad alto livello del progetto HackVillage.

### Descrizione
Il Product Owner (Diego Colì) e il Project Manager (Gabriele Arcese) hanno incontrato gli stakeholder (Marco Costantini e Davide Guidotti) e il team per analizzare il contesto attuale. È stata effettuata un'analisi strategica del mercato e del posizionamento dell'idea. Attraverso un brainstorming incentrato sulle aspettative del committente, sono stati delineati i confini generali del successo del progetto e si è stilato il documento quadro che fa da "carta d'identità" all'iniziativa. Un focus speciale è stato dedicato alle dinamiche del team e alla sostenibilità psicologica delle attività lavorative, grazie al contributo del Mental Coach (Davide Dionisi).

### Output 
- [SWOT analysis](deliverables/SWOT.md): mappatura dei punti di forza/debolezza interni e opportunità/minacce esterne del mercato rispetto a HackVillage.
- [CoS - Conditions of Satisfaction](deliverables/CoS.md): criteri di successo qualitativi e quantitativi minimi richiesti dagli stakeholder per ritenere il progetto soddisfacente.
- [POS - Project Overview Statement](deliverables/POS.md): sintesi esecutiva ufficiale del progetto che racchiude il problema, il macro obiettivo, i vincoli. Include al suo interno:
  - [Market analysis](deliverables/analysis/Market.md).
  - [Financial analysis](deliverables/analysis/Financial.md).

## Meeting #2 - Analisi requisiti e scomposizione funzionale
### Obiettivi 
- Tradurre le aspettative di business e i desideri degli utenti in requisiti tecnici concreti.
- Definire in modo analitico cosa farà e cosa non farà la piattaforma.

### Descrizione
In questo incontro spiccatamente operativo, i developer (Daniele Merighi e Daniel Meco) sono intervenuti per analizzare le 7 macro-aree del progetto (eventi, iscritti, team, mentor, submission, valutazioni, classifiche). Sono state catalogate le richieste e mappata analiticamente la struttura dei requisiti del software. 

### Output
- [Desideri e bisogni](deliverables/DesideriBisogni.md): documentazione dettagliata delle necessità degli utenti, al fine di per comprendere a fondo le priorità dei fruitori della piattaforma (organizzatori, mentor, partecipanti).
- [RBS Requirement Breakdown Structure](deliverables/RBS.md): scomposizione gerarchica ad albero di tutti i requisiti del sistema (funzionali e non), che definisce nel dettaglio l'architettura delle funzionalità necessarie.

**Nota**: si è scelto arbitrariamente di effettuare una [SWOT analysis](deliverables/SWOT.md) prima della definizione di [desideri e bisogni](deliverables/DesideriBisogni.md) per evitare di promettere funzionalità irrealizzabili e scongiurare false aspettative nel committente fin dal primo momento. (richieste che poi andrebbero cestinate nel momento in cui si dovessero scontrare con la realtà finanziaria/strategica).

## Meeting #3 - Validazione architetturare e avanzamento

### Output
- Definire l'infrastruttura tecnica e la roadmap di sviluppo.
- Fotografare il posizionamento del progetto nel ciclo di vita dello sviluppo.
- Formalizzare l'accordo finale prima di scrivere il codice.

### Descrizione 
Sotto la guida del CTO (Gabriele Arcese), sono state approvate le scelte architetturali (database, stack frontend/backend) per garantire stabilità. È stata presentata la roadmap temporale definitiva agli stakeholder ed è stata definita la situazione di partenza rispetto a quella di arrivo desiderata. L'incontro si è concluso con la firma della baseline.

### Output
- [Stato del progetto](deliverables/StatoProgetto.md): documento di posizionamento e di avanzamento che definisce formalmente lo scenario _AS-IS_ (la situazione attuale frammentata), lo scenario _TO-BE_ (il sistema centralizzato HackVillage post-rilascio dell'_MVP_) e l'elenco dei _NICE-TO-HAVE_ (funzionalità opzionali o future da implementare in cicli successivi).
- **PMLC adottato**: si è scelto un Project Management Life Cycle adattivo/iterativo, individuando nel framework SCRUM la metodologia ideale per la conduzione dei lavori. La scelta di tale framework, inserito in una pianificazione rigorosa, risponde a una duplice necessità emersa durante la fase di scoping:
  - _Stabilità dei vincoli_: i macro-obiettivi e i vincoli finanziari e temporali rimangono rigidi e stabili.
  - _Flessibilità del prodotto_: sebbene il perimetro finanziario sia blindato, le singole funzionalità software necessitano di flessibilità. Trattandosi di un ecosistema che centralizza 7 fasi operative complesse, il team di sviluppo ha bisogno di rilasciare il software in modo incrementale per testarne l'usabilità sul campo e correggere l'implementazione senza stravolgere il piano.
