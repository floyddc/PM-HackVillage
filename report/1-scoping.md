---
layout: default
title: Scoping
nav_order: 2
---

# Scoping

La definizione dei requisiti, del perimetro operativo e delle linee guida strategiche di HackVillage è stata strutturata attraverso una serie di tre meeting principali. Questa fase ha visto la collaborazione sinergica e attiva del team di sviluppo, del management e dei rappresentanti del committente (HackIT Community).

L'approccio iterativo adottato ha permesso di allineare progressivamente la visione di business alle specifiche tecniche e architetturali, riducendo al minimo le ambiguità e strutturando un percorso di sviluppo chiaro, tracciabile e orientato al rilascio di valore reale per la community.

## Meeting #1 - Identificazione problema e allineamento strategico

### Obiettivi
- Comprendere il problema di fondo della frammentazione degli strumenti di HackIT Community.
- Allineare il team e gli stakeholder sulla direzione strategica del brand. 
- Definire l'identità ad alto livello del progetto HackVillage.

### Descrizione
Il Product Owner (Diego Colì) e il Project Manager (Gabriele Arcese) hanno incontrato gli stakeholder (Marco Costantini e Davide Guidotti) e il team di sviluppo per analizzare il contesto attuale. È stata effettuata un'analisi strategica del mercato e del posizionamento dell'idea. Attraverso un brainstorming incentrato sulle aspettative del committente, sono stati delineati i confini generali del successo del progetto e si è stilato il documento quadro che fa da "carta d'identità" all'iniziativa. Un focus speciale è stato dedicato alle dinamiche del team e alla sostenibilità psicologica delle attività lavorative, grazie al contributo del Mental Coach (Davide Dionisi).

### Output
- [SWOT analysis](scoping/deliverables/SWOT.md): mappatura dei punti di forza/debolezza interni e opportunità/minacce esterne del mercato rispetto a HackVillage.
- [CoS - Conditions of Satisfaction](scoping/deliverables/CoS.md): criteri di successo qualitativi e quantitativi minimi richiesti dagli stakeholder per ritenere il progetto soddisfacente.
- [Stato del progetto](scoping/deliverables/StatoProgetto.md): documento di posizionamento che descrive lo scenario _AS-IS_ (gestione frammentata degli hackathon), lo scenario _TO-BE_ (piattaforma HackVillage centralizzata a seguito del rilascio dell'MVP) e individua i principali _Nice-to-Have_ da valutare nei successivi cicli evolutivi.

**Nota**: si è scelto arbitrariamente di effettuare una **SWOT analysis** prima della definizione di **Desideri e Bisogni** per evitare di promettere funzionalità irrealizzabili e scongiurare false aspettative nel committente fin dal primo momento. (richieste che poi andrebbero cestinate nel momento in cui si dovessero scontrare con la realtà finanziaria/strategica).

## Meeting #2 - Analisi requisiti e scomposizione funzionale

### Obiettivi 
- Tradurre le aspettative di business e i desideri degli utenti in requisiti tecnici concreti.
- Definire in modo analitico cosa farà e cosa non farà la piattaforma.

### Descrizione
In questo incontro spiccatamente operativo, i developer (Daniele Merighi e Daniel Meco) sono intervenuti per analizzare le 7 macro-aree del progetto (eventi, iscritti, team, mentor, submission, valutazioni, classifiche). La raccolta dei requisiti è stata condotta principalmente tramite facilitated group session integrate da interviste agli stakeholder. Sono state quindi catalogate le richieste e mappata analiticamente la struttura dei requisiti del software. 

### Output
- [Desideri e bisogni](scoping/deliverables/DesideriBisogni.md): documentazione dettagliata delle necessità degli utenti, al fine di per comprendere a fondo le priorità dei fruitori della piattaforma (organizzatori, mentor, partecipanti).
- [RBS - Requirement Breakdown Structure](scoping/deliverables/RBS.md): scomposizione gerarchica ad albero di tutti i requisiti del sistema (funzionali e non), che definisce nel dettaglio l'architettura delle funzionalità necessarie.

## Meeting #3 - Validazione architetturare e formalizzazione del progetto

### Obiettivi
- Definire l'infrastruttura tecnica della piattaforma.
- Selezionare il Project Management Life Cycle più adatto al progetto.
- Formalizzare il Project Overview Statement e ottenere l'approvazione finale dello scope prima dell'avvio dello sviluppo.

### Descrizione
Sotto la guida del CTO (Gabriele Arcese), il team ha validato le principali scelte architetturali (database, stack frontend/backend e organizzazione dell'infrastruttura) per garantire stabilità e scalabilità del sistema. Contestualmente sono stati riesaminati i requisiti emersi durante la fase di scoping al fine di individuare il Project Management Life Cycle più idoneo.

### Output
- **PMLC adottato**: è stato selezionato un Project Management Life Cycle iterativo, individuando nel framework SCRUM la metodologia più adatta alla conduzione del progetto. La scelta deriva dal fatto che i macro-obiettivi risultano definiti e stabili, mentre i requisiti di dettaglio potranno evolvere progressivamente durante lo sviluppo grazie ai feedback raccolti dagli stakeholder.
- [POS - Project Overview Statement](scoping/deliverables/POS.md): documento di sintesi del progetto che formalizza il problema, il goal, gli obiettivi, i criteri di successo, i principali rischi e i vincoli del progetto. Include inoltre:
  - [Market analysis](scoping/deliverables/Market.md).
  - [Financial analysis](scoping/deliverables/Financial.md).

# [⬆️ Contesto](0-contesto.md)
# [⬇️ Planning](2-planning.md)
