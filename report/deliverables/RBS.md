---
layout: default
title: RBS
nav_exclude: true
---

# Requirement Breakdown Structure
L'RBS definisce l'architettura funzionale di HackVillage, scomponendo il sistema nelle sue macro-aree operative per garantire una copertura completa del ciclo di vita dell'hackathon.

  1. **Gestione eventi**
      - **Creazione evento**: Configurazione di date, descrizione, regole e premi.
      - **Dashboard organizzatore**: Monitoraggio in tempo reale degli iscritti e dello stato di avanzamento.
      - **Pubblicazione**: Gestione dello stato dell'evento (bozza, aperto, in corso, concluso).

  2. **Gestione iscritti**
      * **Registrazione & Login**: Sistema di autenticazione sicuro per partecipanti, mentor e giudici.
      * **Profilazione**: Gestione delle competenze tecniche e dei ruoli utente.
      * **Ruoli & Permessi**: Controllo accessi differenziato (RBAC) per garantire la sicurezza dei dati.

  3. **Formazione team**
      * **Creazione team**: Funzionalità per la creazione autonoma dei team da parte dei partecipanti.
      * **Gestione membri**: Inviti, accettazione e rimozione dai team.
      * **Validazione organizzatore**: Strumenti per la supervisione e la validazione dei team formati.

  4. **Gestione mentor**
      * **Matching**: Assegnazione dei mentor ai team in base alle competenze necessarie.
      * **Comunicazione**: Canali dedicati per il supporto mentor-team.

  5. **Raccolta submission**
      * **Upload progetti**: Sistema sicuro per il caricamento di file, repository GitHub o link esterni.
      * **Gestione scadenze**: Blocco automatico dei caricamenti al termine della finestra temporale.
      * **Storage sicuro**: Archiviazione dei file sottomessi con protezione dei dati.

  6. **Valutazione**
      * **Pannello giudici**: Interfaccia dedicata per la visualizzazione dei progetti e l'assegnazione dei punteggi.
      * **Criteri di valutazione**: Configurazione dei parametri di voto (es. innovazione, fattibilità tecnica, design).
      * **Feedback**: Spazio per inserire commenti qualitativi oltre ai punteggi numerici.

  7. **Classifiche**
      * **Motore di calcolo**: Elaborazione automatica dei punteggi finali.
      * **Visualizzazione classifica**: Pubblicazione in tempo reale della classifica pubblica al termine della valutazione.

![RBS schema](/report/img/RBS.jpg)