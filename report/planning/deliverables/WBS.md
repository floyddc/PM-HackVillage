---
layout: default
title: WBS
nav_exclude: true
---

# Work Breakdown Structure

La Work Breakdown Structure rappresenta la scomposizione analitica delle attività necessarie per la realizzazione dell'MVP di HackVillage, derivata direttamente dalla numerazione e dai requisiti della RBS.

## 1. Gestione Eventi
*   **1.1. Creazione Evento**
    *   1.1.1. Progettazione schema database e tabelle di configurazione evento
    *   1.1.2. Sviluppo API per inserimento, salvataggio in bozza e configurazione regole/premi
    *   1.1.3. Realizzazione interfaccia grafica del form di creazione e configurazione
    *   1.1.4. Integrazione del form con le API di salvataggio
*   **1.2. Dashboard Organizzatore**
    *   1.2.1. Sviluppo endpoint API per l'aggregazione dei dati di monitoraggio in tempo reale
    *   1.2.2. Sviluppo del pannello di controllo grafico per la visualizzazione delle metriche
    *   1.2.3. Collegamento dei widget della dashboard ai flussi dati dell'endpoint
*   **1.3. Pubblicazione**
    *   1.3.1. Implementazione della logica degli stati sul backend (Bozza, Aperto, In Corso, Concluso)
    *   1.3.2. Sviluppo controlli di attivazione e switch di stato nell'interfaccia organizzatore

## 2. Gestione Iscritti
*   **2.1. Registrazione e Login**
    *   2.1.1. Configurazione del sistema di autenticazione sicuro e cifratura password
    *   2.1.2. Sviluppo API di login, registrazione e generazione token di sessione
    *   2.1.3. Creazione delle schermate di Login e Registrazione
    *   2.1.4. Gestione dei token e delle sessioni nel browser utente
*   **2.2. Profilazione**
    *   2.2.1. Modellazione attributi utente e competenze tecniche nel database
    *   2.2.2. Sviluppo API per la lettura e l'aggiornamento del profilo
    *   2.2.3. Sviluppo della pagina "Profilo Utente" con form di aggiornamento competenze
*   **2.3. Ruoli e Permessi**
    *   2.3.1. Implementazione del controllo accessi basato sui ruoli (Organizzatore, Partecipante, Mentor, Giudice)
    *   2.3.2. Configurazione dei middleware di sicurezza sulle rotte protette
    *   2.3.3. Implementazione del routing condizionale sul client in base al ruolo dell'utente loggato

## 3. Formazione Team
*   **3.1. Creazione Team**
    *   3.1.1. Sviluppo logica di database per le relazioni molti-a-molti tra Utenti e Team
    *   3.1.2. Sviluppo API per la creazione del team e generazione codice univoco di invito
    *   3.1.3. Interfaccia di creazione team e input per il codice di invito
*   **3.2. Gestione Membri**
    *   3.2.1. Sviluppo endpoint per l'invio, l'accettazione e la rimozione dei membri
    *   3.2.2. Creazione della visualizzazione dei componenti del team con relativi stati (In attesa, Confermato)
*   **3.3. Validazione Organizzatore**
    *   3.3.1. Sviluppo API di approvazione/blocco dei team per l'amministratore
    *   3.3.2. Interfaccia di supervisione dei team all'interno del pannello organizzatore

## 4. Gestione Mentor
*   **4.1. Matching**
    *   4.1.1. Creazione algoritmo/logica di associazione Mentor-Team nel database
    *   4.1.2. Sviluppo API per l'assegnazione (manuale o automatica) basata sulle competenze
    *   4.1.3. Interfaccia di drag-and-drop o selezione per l'assegnazione dei mentor ai team
*   **4.2. Comunicazione**
    *   4.2.1. Predisposizione tabelle e API per lo scambio di messaggi o note interne
    *   4.2.2. Sviluppo della sezione "Supporto Mentor" nelle rispettive bacheche

## 5. Raccolta Submission
*   **5.1. Upload Progetti**
    *   5.1.1. Configurazione del servizio di cloud storage per il caricamento sicuro dei file
    *   5.1.2. Sviluppo API per l'invio dei metadati (link GitHub, descrizione) e l'upload dei file di progetto 
    *   5.1.3. Realizzazione dell'interfaccia di sottomissione con drag-and-drop del file e campi di testo 
*   **5.2. Gestione Scadenze**
    *   5.2.1. Implementazione del controllo lato server per il rifiuto automatico dei pacchetti oltre la scadenza 
    *   5.2.2. Sviluppo di un countdown visivo in tempo reale basato sul server-time 
*   **5.3. Storage Sicuro**
    *   5.3.1. Applicazione delle policy di isolamento dei file (un team può accedere/modificare solo la propria cartella) 

## 6. Valutazione
*   **6.1. Pannello Giudici**
    *   6.1.1. Sviluppo endpoint per la distribuzione dei progetti assegnati a ciascun giudice
    *   6.1.2. Progettazione dell'interfaccia dedicata per il ruolo Giudice con elenco dei progetti da esaminare 
*   **6.2. Criteri di Valutazione**
    *   6.2.1. Strutturazione delle tabelle dei punteggi ponderati (Innovazione, Tecnica, Design) 
    *   6.2.2. Sviluppo API di sottomissione dei voti 
    *   6.2.3. Interfaccia con slider o campi numerici per l'inserimento dei voti secondo i criteri definiti 
*   **6.3. Feedback**
    *   6.3.1. Integrazione del campo di testo per note qualitative nel database e nelle API di voto 
    *   6.3.2. Aggiunta dell'area di testo "Commenti" nel form di valutazione del giudice

## 7. Classifiche
*   **7.1. Motore di Calcolo**
    *   7.1.1. Sviluppo script/query SQL di calcolo automatizzato delle medie ponderate ed elaborazione dei posizionamenti
    *   7.1.2. Sviluppo API di esposizione della classifica finale aggregata 
*   **7.2. Visualizzazione Classifica**
    *   7.2.1. Creazione della pagina pubblica o riservata di visualizzazione dei risultati finali
    *   7.2.2. Integrazione dei dati della classifica con rendering grafici dei posizionamenti