---
layout: default
title: Gantt
nav_exclude: true
---

# Diagramma di Gantt

### Diagramma di Gantt Compatto (Timeline 1-12 Settimane / 3 Mesi)

| ID WBS - Descrizione Task | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 | S11 | S12 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **WP-SETUP** - Configurazione Cloud & DB | ██ | | | | | | | | | | | |
| **WP-MOCK** - Contratti & Mock API Core | | ██ | | | | | | | | | | |
| **1.1.1** - Schema DB & Config. Evento | | | ██ | | | | | | | | | |
| **1.1.2** - Sviluppo API & Regole Bozza | | | ██ | | | | | | | | | |
| 1.1.3 - UI Grafica Form Creazione | | | ▒▒ | | | | | | | | | |
| 1.1.4 - Integrazione Form & API | | | ▒▒ | | | | | | | | | |
| **1.2.1** - API Aggregazione Dati Real-Time | | | ██ | | | | | | | | | |
| 1.2.2 - Pannello Grafico Metriche | | | ▒▒ | | | | | | | | | |
| 1.2.3 - Collegamento Widget Dashboard | | | ▒▒ | | | | | | | | | |
| **1.3.1** - Logica Stati Server BE | | | ██ | | | | | | | | | |
| 1.3.2 - Controlli Interfaccia Client | | | ▒▒ | | | | | | | | | |
| *Slk WBS 1-F - Margine scorrimento* | | | | .. | | | | | | | | |
| **2.1.1** - Autenticazione & Cifratura BE | | | | ██ | | | | | | | | |
| **2.1.2** - API Login & Registrazione | | | | ██ | | | | | | | | |
| 2.1.3 - Schermate UI Login/Auth | | | | ▒▒ | | | | | | | | |
| 2.1.4 - Gestione Token Browser | | | | ▒▒ | | | | | | | | |
| **2.2.1** - Modellazione Skill Utente DB | | | | ██ | | | | | | | | |
| **2.2.2** - API Lettura/Update Profilo | | | | ██ | | | | | | | | |
| 2.2.3 - Pagina Profilo & Skill Form | | | | ▒▒ | | | | | | | | |
| **2.3.1** - Controllo Accessi RBAC | | | | ██ | | | | | | | | |
| **2.3.2** - Middleware Sicurezza Rotte BE | | | | ██ | | | | | | | | |
| 2.3.3 - Routing Condizionale Client | | | | ▒▒ | | | | | | | | |
| *Slk WBS 2-F - Margine scorrimento* | | | | | .. | | | | | | | |
| **3.1.1** - Relazioni N-N Team DB | | | | | ██ | ██ | | | | | | |
| **3.1.2** - API Creazione & Codice Invito | | | | | | ██ | | | | | | |
| 3.1.3 - Interfaccia Creazione Team UI | | | | | ▒▒ | ▒▒ | | | | | | |
| **3.2.1** - Endpoint Gestione Membri Team | | | | | | ██ | | | | | | |
| 3.2.2 - UI Componenti e Stati Invito | | | | | | ▒▒ | | | | | | |
| **3.3.1** - API Validazione Admin Organizzatore | | | | | | ██ | | | | | | |
| 3.3.2 - Interfaccia Supervisione Admin | | | | | | ▒▒ | | | | | | |
| *Slk WBS 3-F - Margine scorrimento* | | | | | | | .. | | | | | |
| **4.1.1** - Logica Matching Mentor DB | | | | | | | ██ | | | | | |
| **4.1.2** - API Assegnazione Competenze | | | | | | | ██ | | | | | |
| 4.1.3 - Interfaccia Drag-and-Drop UX | | | | | | | ▒▒ | | | | | |
| **4.2.1** - API Scambio Note/Messaggi BE | | | | | | | ██ | | | | | |
| 4.2.2 - UI Sezione Supporto Mentor | | | | | | | ▒▒ | | | | | |
| *Slk WBS 4-F - Margine scorrimento* | | | | | | | | .. | | | | |
| **5.1.1** - Configurazione Storage Cloud | | | | | | | | ██ | ██ | | | |
| **5.1.2** - API Invio Metadati & Upload File | | | | | | | | | ██ | | | |
| 5.1.3 - UI Sottomissione Drag-and-Drop | | | | | | | | ▒▒ | ▒▒ | | | |
| **5.2.1** - Blocco Lato Server Scadenze | | | | | | | | | ██ | | | |
| 5.2.2 - Countdown Visivo Server-Time | | | | | | | | | ▒▒ | | | |
| **5.3.1** - Isolation Policy Cartelle Team | | | | | | | | | ██ | | | |
| *Slk WBS 5-F - Margine scorrimento* | | | | | | | | | | .. | | |
| **6.1.1** - Endpoint Distribuzione Progetti | | | | | | | | | | ██ | | |
| 6.1.2 - UI Giudice Elenco Progetti | | | | | | | | | | ▒▒ | | |
| **6.2.1** - DB Criteri Ponderati Voti | | | | | | | | | | ██ | | |
| **6.2.2** - API Invio Votazioni Giuria | | | | | | | | | | ██ | | |
| 6.2.3 - UI Slider Inserimento Voti | | | | | | | | | | ▒▒ | | |
| **6.3.1** - Note Qualitative DB e Voto | | | | | | | | | | ██ | | |
| 6.3.2 - UI Form Area Testo Commenti | | | | | | | | | | ▒▒ | | |
| **7.1.1** - Query SQL Classifiche Medie | | | | | | | | | | ██ | | |
| **7.1.2** - API Esposizione Graduatoria | | | | | | | | | | ██ | | |
| 7.2.1 - UI Pagina Risultati Finali | | | | | | | | | | ▒▒ | | |
| 7.2.2 - UI Rendering Grafici Podio | | | | | | | | | | ▒▒ | | |
| *Slk WBS 6/7-F - Margine scorrimento* | | | | | | | | | | | .. | |
| **WP-INTEGRATION** - Allineamento dati reali | | | | | | | | | | | ██ | |
| **WP-TEST** - Carico Simultaneo Modulo 5 | | | | | | | | | | | | ██ |
| **WP-DEPLOY** - Collaudo UAT & Go-Live | | | | | | | | | | | | ██ |