---
layout: default
title: Gantt
nav_exclude: true
---

# Diagramma di Gantt
Il diagramma di Gantt è stato realizzato a partire dal [PND](PND.md) definito in fase di pianificazione.

Tale diagramma rappresenta in modo chiaro e sintetico la pianificazione temporale del progetto. Attraverso il Gantt è stato possibile inoltre visualizzare i percorsi critici, che potrebbero portare a futuri rallentamenti.

```mermaid
gantt
    title Gantt Diagram
    dateFormat YYYY-MM-DD
    axisFormat %d/%m

    section Percorso critico
    WP-SETUP - Setup ambiente                 :crit, setup, 2026-07-07, 5d
    WP-MOCK - Mock API                        :crit, mock, after setup, 4d
    WBS 1-B - Gestione Eventi                  :crit, wbs1b, after mock, 5d
    WBS 3-B - Formazione Team                    :crit, wbs3b, after wbs1b, 7d
    WBS 5-B - Raccolta Submission              :crit, wbs5b, after wbs3b, 8d
    WBS 6/7-B - Valutazione & Classifiche           :crit, wbs67b, after wbs5b, 6d
    WP-INT - Integrazione                     :crit, integ, after wbs67b, 7d
    WP-TEST - Stress Test                     :crit, test, after integ, 5d
    WP-DEPLOY - Deploy                        :crit, deploy, after test, 8d

    section Attività non critiche
    WBS 1-F - Gestione Eventi                 :wbs1f, after wbs1b, 5d
    Slk                             :slack1f, after wbs1f, 4d

    WBS 2-B - Gestione Iscritti                :wbs2b, after wbs1b, 5d
    Slk                             :slack2b, after wbs2b, 2d

    WBS 2-F - Gestione Iscritti               :wbs2f, after wbs2b, 5d
    Slk                             :slack2f, after wbs2f, 6d

    WBS 3-F - Formazione Team                   :wbs3f, after wbs3b, 7d
    Slk                             :slack3f, after wbs3f, 4d

    WBS 4-B - Gestione Mentor                  :wbs4b, after wbs3b, 5d
    Slk                             :slack4b, after wbs4b, 3d

    WBS 4-F - Gestione Mentor                 :wbs4f, after wbs4b, 5d
    Slk                            :slack4f, after wbs4f, 7d

    WBS 5-F - Raccolta Submission             :wbs5f, after wbs5b, 8d
    Slk                             :slack5f, after wbs5f, 5d

    WBS 6/7-F - Valutazione & Classifiche          :wbs67f, after wbs67b, 6d
    Slk                           :slack67f, after wbs67f, 6d
```