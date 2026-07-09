---
layout: default
title: Financial analysis
nav_exclude: true
---

# Financial analysis

In questa analisi si valuteranno i principali costi da sostenere, i rischi finanziari correlati e il potenziale ritorno economico del progetto. Tutte le valutazioni qui sotto riportate si riferiscono a delle stime effettuate durante la fase di scoping.

## Obiettivi finanziari del progetto
- Ridurre i costi invisibili di gestione.
- Garantire la data integrity, azzerando le perdite finanziarie o reputazionali derivanti da errori di punteggio o smarrimento dei dati dei partecipanti.
- Aumentare l'attrattività commerciale di HackIT Community, incrementando il numero di sponsor e aziende partner disposte a finanziare gli hackathon grazie a una piattaforma professionale proprietaria.
- Predisporre l'applicativo per una futura monetizzazione di tipo SaaS (Software-as-a-Service).

## Costi di sviluppo
La stima dei costi di sviluppo (commisurati ai 3 mesi di durata del progetto) si divide in due categorie: costi interni (legati al personale) e costi esterni (infrastruttura e servizi). 

### Costi interni
Rappresentano la quota principale dell'investimento. La stima viene eseguita sulla base del valore di mercato/RAL di riferimento dei singoli componenti del team per i 3 mesi di pendenza del progetto.

| Nome | Ruolo | Mensilità | Totale | Carico di lavoro
|---|---|---|---|---|
| Diego Colì | CEO - Product Owner | €1900 | €5700 | Definizione requisiti, validazione MVP e gestione stakeholder. Direzione strategica
| Gabriele Arcese | CTO - Project Manager - Scrum Master | €2000 | €6000 | Gestione roadmap e sprint, risoluzione blocchi tecnici e comunicazione con stakeholder.
| Daniele Merighi | Backend Developer | €2250 | €6750 | Progettazione completa architettura del DB ed API
| Daniel Meco | Frontend Developer | €2250 | €6750 | Responsabilità totale di UI, UX ed integrazione API
| Davide Dionisi | Mental Coach - Psychology Supporter | €800 | €2400 | Part-time poche ore a settimana, sessioni mirate nei momenti critici degli sprint

### Costi esterni
Costi vivi per le licenze di sviluppo, il deployment e l'infrastruttura cloud necessaria per il lancio e il primo anno di esercizio.

| Tecnologia | Costo annuo | Descrizione
|---|---|---|
| Infrastruttura cloud (server+DB) | €600 | Servizi cloud scalabili (AWS) per gestire picchi di traffico  
| Cloud storage | €100 | Spazio di archiviazione sicuro per submission dei progetti 
| Dominio, email e certificati SSL | €100 | Gestione dominio istituizione e casella di posta 
| Licenze software e tool | €300 | Asset di sviluppo frontend/backend e tool di monitoraggio crash
| Fondo di riserva | €1000 | Eventuali imprevisti

Il costo totale stimato per lo sviluppo dell'MVP e il mantenimento della piattaforma per il primo anno è pari a circa €29.900, rientrando perfettamente nel budget massimo previsto dal committente.

## Risk analysis
I rischi sono gestiti e categorizzati associandoli ai vertici dello _Scope triangle_. Inoltre, le azioni sono classificabili come:
- **Accettazione**: accettazione del rischio e delle sue conseguenze.
- **Mitigazione**: creazione di un piano operativo (a priori) per minimizzare l'impatto negativo.
- **Pianificazione d'emergenza**: azione di intervento decidendo cosa fare nell'esatto momento in cui l'evento si verifica.

| Rischio | Scope triangle | Impatto | Azione
|---|---|---|---|
| Sforamento della deadline | Tempo | Alta | Mitigazione
| Abbandono di un developer | Risorse/Costo | Critica | Mitigazione
| Esplosione costi cloud | Risorse/Costo | Media | Pianificazione d'emergenza
| Crash del backend durante upload progetti | Scopo/Qualità | Critica | Mitigazione
| Scarsa adozione piattaforma | Scopo/Qualità | Alta | Mitigazione

## Ritorno economico (ROI) atteso
Il ritorno economico sull'investimento di €30.000 si svilupperà nel medio-lungo termine. Per il committente, questo valore si divide in ritorni diretti (monetizzabili) e indiretti (operativi e di efficienza).

### Ritorni diretti
- Una volta consolidata internamente, la piattaforma verrà concessa in licenza a università, incubatori e altre community con un modello Pay-per-Event (es: €500/evento). Con una stima di 15 eventi gestiti da terzi nel primo anno, si prevede un rientro diretto di €7.500/anno.
- Incremento delle sponsorizzazione, poichè l'adozione di una piattaforma proprietaria e professionale permette di offrire alle aziende partner spazi di branding digitali dedicati e tracciamento dei talenti. Si stima un aumento dell'attrattività commerciale per gli hackathon di HackIT pari a un 15% sul fatturato degli sponsor (circa €4.000 in più ad evento).

### Ritorni indiretti
- Drastica riduzione delle ore/uomo, grazie all'automazione dei flussi critici di ogni evento. Si stimano circa 60 ore uomo risparmiate dagli organizzatori per ogni singolo hackathon.
- Aumento della soddisfazione di partecipanti e mentor, grazie ad un'esperienza fluida e senza attriti digitali.

# [⬅️ Scoping](../../1-scoping.md)
