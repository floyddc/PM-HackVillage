---
layout: default
title: Monitoring & Control
nav_order: 5
---

# Monitoring & Controlling

L'obiettivo di questa fase è controllare e monitorare sistematicamente l’avanzamento delle attività per verificare che i tempi (3 mesi), i costi (€30.000) e gli obiettivi dell'MVP di HackVillage siano rigorosamente rispettati. Attraverso il monitoraggio è possibile individuare tempestivamente eventuali scostamenti o criticità rispetto al percorso critico stabilito, intervenendo con azioni correttive immediate per garantire la corretta realizzazione del progetto secondo quanto pianificato nella baseline.

## Reporting

L'adozione del framework SCRUM garantisce al team un flusso costante di informazioni grazie a riunioni settimanali strutturate (Sprint Planning, Review e Retro) e alla suddivisione degli obiettivi in sprint brevi, incrementali e misurabili. Questo approccio agevola la trasparenza sull'avanzamento dei due binari di sviluppo (Backend e Frontend) e il monitoraggio sistematico dei progressi legati alle macro-aree della WBS.

Per il monitoring quotidiano, il team utilizza **YouTrack**, configurato con board SCRUM dedicate e campi su misura per priorità, stati di avanzamento, stime in Story Points (tarate sulla velocity di 38 SP per sprint) e assegnazioni specifiche per gli sviluppatori. Qualsiasi attività o deliverable tecnico viene tracciato in modo puntuale all'interno dello sprint corrente, consentendo a Gabriele Arcese (nel doppio ruolo di PM e CTO) di avere sempre sotto controllo il quadro aggiornato dei compiti in corso e delle singole responsabilità di sviluppo.

La scelta di YouTrack si basa sulla sua affidabilità, sulla semplicità di utilizzo e sulla perfetta integrazione con le metodologie Agile, ottimizzando il coordinamento di un team snello ed evitando dispersioni comunicative.

L'interfaccia di YouTrack permette di visualizzare i principali stati dei ticket e di tenere sotto controllo l'allocazione delle attività ai diversi membri del team. I ticket eventualmente non completati nello sprint corrente vengono automaticamente ripianificati e riposizionati nel backlog dello sprint successivo, garantendo una gestione agile delle priorità e salvaguardando il margine di scorrimento (*Slack*) a disposizione delle lavorazioni client-side. In questo modo, il reporting diventa un processo continuo di allineamento, revisione e miglioramento.

## ISSUE LOG

Per la gestione strutturata delle problematiche tecniche, degli ostacoli organizzativi e delle richieste emerse durante lo sviluppo, il team utilizza l'**Issue Log** integrato in YouTrack.

L'Issue Log centralizza la lista dei problemi, dei bug architetturali o delle anomalie riscontrate. Serve a monitorare le problematiche aperte, mappandole in base ai criteri di impatto sullo *Scope Triangle* e registrando le decisioni prese per risolverle. Ogni issue viene documentata con dettagli specifici quali:

*   **ID Number**: Codice identificativo univoco del ticket di errore.
*   **Date logged**: Data di rilevazione del problema durante lo sprint.
*   **Descrizione del problema**: Dettaglio tecnico del bug 
*   **Descrizione dell’impatto sul progetto**: Valutazione degli effetti sulla timeline, sulle milestone o sull'eventuale minaccia di slittamento del percorso critico di backend.
*   **Definizione del “Proprietario”**: Assegnazione della responsabilità della risoluzione.
*   **Azione intrapresa**: Piano d'azione correttivo e dettagliato volto a risolvere l'anomalia.
*   **Stato**: Condizione del ticket (Aperto, In Corso, In Verifica, Chiuso).
*   **Esito**: Risoluzione formale e impatto finale sulla baseline dell'MVP.

L’Issue Log è accessibile a tutti i membri del team, favorisce la trasparenza collaborativa ed è consultato regolarmente sia durante i Daily SCRUM mattutini, sia nelle sessioni di Sprint Review e nelle retrospettive. Il monitoraggio costante di questo log si estende su tutto il ciclo di vita del progetto, assicurando tempestività nella risoluzione degli ostacoli tecnici e salvaguardando il benessere operativo del team supervisionato dal Mental Coach.