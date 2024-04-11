# DealHunter

## Table of Contents
- [Descrizione del Progetto](#descrizione-del-progetto)
- [Requisiti Funzionali](#requisiti-funzionali)
- [Requisiti Non Funzionali](#requisiti-non-funzionali)
- [Requisiti di Dominio](#requisiti-di-dominio)
- [Diagramma dei casi d'uso](#diagramma-dei-casi-d'uso)
- [User story](#user-story)
- [WBS](#wbs)

## Descrizione del Progetto

DealHunter è un'applicazione web che consente agli utenti di cercare, confrontare i prezzi e ricevere notifiche sugli sconti per una vasta gamma di prodotti da diversi siti di e-commerce. Gli utenti possono salvare i loro prodotti preferiti, monitorare i prezzi storici e impostare notifiche personalizzate quando i prodotti raggiungono i prezzi desiderati.

## Requisiti Funzionali

1. **Ricerca di prodotti:** Gli utenti devono essere in grado di cercare prodotti specifici utilizzando parole chiave o categorie.

2. **Confronto dei prezzi:** L'applicazione deve mostrare i prezzi di un prodotto da diversi siti di e-commerce per consentire agli utenti di confrontarli.

3. **Registrazione e gestione dell'account:** Gli utenti dovrebbero poter creare un account, effettuare l'accesso e gestire il proprio profilo.

4. **Storico dei prezzi:** L'applicazione dovrebbe registrare e visualizzare il prezzo storico di ciascun prodotto.

5. **Salvataggio tra i preferiti:** Gli utenti devono poter salvare i prodotti di loro interesse nella lista dei preferiti.

6. **Notifiche sugli sconti:** Gli utenti possono impostare notifiche per essere avvisati quando un prodotto raggiunge un prezzo target o riceve uno sconto.

7. **Gestione delle notifiche:** Gli utenti devono poter gestire le proprie preferenze per le notifiche, tra cui il tipo di notifica (e-mail, push, SMS, ecc.) e la frequenza.

8. **Recensioni e valutazioni:** Gli utenti possono lasciare recensioni e valutazioni dei prodotti, e visualizzare recensioni di altri utenti.

## Requisiti Non Funzionali

1. **Prestazioni:** L'applicazione deve essere veloce nel caricamento dei risultati di ricerca e nella visualizzazione dei prezzi.

2. **Sicurezza:** Deve essere garantita la sicurezza dei dati degli utenti.

3. **Disponibilità:** L'applicazione deve essere accessibile in modo affidabile, con una disponibilità elevata.

4. **Usabilità:** L'interfaccia utente deve essere intuitiva e facile da usare, con una buona user experience.

5. **Compatibilità:** L'applicazione dovrebbe funzionare su diversi dispositivi e browser web.

6. **Scalabilità:** Deve essere in grado di gestire un numero crescente di utenti e dati senza perdita di prestazioni.

7. **Conformità alle leggi sulla privacy:** L'applicazione deve rispettare le leggi sulla protezione dei dati personali e la privacy degli utenti.

8. **Integrazione con API di terze parti:** Se necessario, l'applicazione dovrebbe integrarsi con le API dei siti di e-commerce e di altri servizi.

9. **Backup e ripristino dei dati:** Deve essere prevista una strategia di backup e ripristino dei dati per evitare la perdita di informazioni importanti.

10. **Test e manutenzione:** Deve essere pianificata una regolare manutenzione dell'applicazione, compresi test e correzioni dei bug.

## Requisiti di Dominio

- **Fonti di Dati E-commerce:** L'applicazione deve accedere ai dati dei vari siti di e-commerce per ottenere informazioni sui prodotti e prezzi.
- **Gestione delle Notifiche:** Deve essere implementato un sistema di gestione delle notifiche per inviare avvisi agli utenti in modo tempestivo.
- **Rispetto delle norme GDPR:** L'applicazione deve rispettare le norme GDPR.

## Diagramma dei casi d'uso
[<a name="diagramma-dei-casi-d'uso"></a>]
![Diagramma dei casi d'uso](https://yuml.me/678f3fae.jpg)

## User story
1. Come **utente**, voglio **poter cercare facilmente prodotti su diversi siti di e-commerce tramite DealHunter**.
2. Come **utente**, voglio **poter confrontare i prezzi dei prodotti cercati su diversi siti di e-commerce tramite DealHunter**.
3. Come **utente**, voglio **poter ricevere notifiche sugli sconti e le offerte speciali per i prodotti che ho cercato tramite DealHunter**.
4. Come **utente**, voglio **poter salvare i prodotti che mi interessano su DealHunter** per poterli **ritrovare facilmente in seguito**.
5. Come **utente**, voglio **poter monitorare i prezzi storici dei prodotti salvati su DealHunter** per capire **se ci sono variazioni di prezzo nel tempo**.
6. Come **utente**, voglio **poter impostare notifiche personalizzate su DealHunter**, in modo da sapere **quando i prezzi dei prodotti raggiungono il mio prezzo desiderato**.

## WBS
### 1. Pianificazione e Gestione del Progetto
   - Definizione degli obiettivi del progetto
   - Creazione del piano di progetto
   - Assegnazione delle risorse
   - Monitoraggio e controllo del progetto

### 2. Analisi e Raccolta dei Requisiti
   - Identificazione dei requisiti utente
   - Analisi dei requisiti funzionali
   - Analisi dei requisiti non funzionali
   - Analisi dei requisiti di dominio

### 3. Sviluppo del Backend
   - Progettazione dell'architettura del backend
   - Implementazione delle funzionalità del backend
   - Integrazione con le API dei siti di e-commerce
   - Implementazione della gestione dei dati utente
   - Implementazione della sicurezza dei dati
   - Implementazione delle notifiche push e email
   - Implementazione delle funzionalità di backup e ripristino

### 4. Sviluppo del Frontend
   - Progettazione dell'interfaccia utente
   - Implementazione delle pagine e dei componenti frontend
   - Implementazione delle funzionalità di ricerca e confronto prezzi
   - Implementazione delle funzionalità di registrazione e gestione dell'account
   - Implementazione delle funzionalità di gestione delle notifiche e dei preferiti
   - Implementazione delle funzionalità di recensioni e valutazioni

### 5. Test e Qualità
   - Pianificazione dei test
   - Esecuzione dei test funzionali
   - Esecuzione dei test di usabilità
   - Esecuzione dei test di prestazioni
   - Risoluzione dei bug e delle problematiche emerse dai test

### 6. Deploy e Manutenzione
   - Preparazione per il deployment
   - Deployment dell'applicazione
   - Monitoraggio delle prestazioni e della disponibilità
   - Manutenzione preventiva e correzione dei bug
   - Aggiornamento dell'applicazione secondo feedback utente e nuove funzionalità
