---
title: Troubleshooting Livello 1
tipologia: software
nome: HyperBeauty
produttore: Custom S.p.A.
argomento: Risoluzione dei problemi comuni in fase di installazione e primo utilizzo di HyperBeauty
autore: Robuschi Ivan
documento_destinato_a: partner
data_creazione: 2026-06-20
revisione: "1.0"
lingua: it
livello_corso: level_1
tipo_contenuto: troubleshooting
sezione_ordine: 6
prodotto_versione: "2026"
tags:
  - troubleshooting
  - errori
  - problemi
  - supporto
  - risoluzione
  - assistenza
  - ticket
  - debug
---

# Troubleshooting Livello 1

Raccolta dei problemi più comuni durante l'installazione e la prima configurazione di HyperBeauty.

---

## Accesso e account

??? question "Non riesco ad accedere — le credenziali non funzionano"
    1. Verificare che l'indirizzo email inserito sia quello comunicato da Custom S.p.a. al momento dell'attivazione
    2. Verificare che la password sia quella ricevuta via email (attenzione a maiuscole/minuscole)
    3. Se la password è stata cambiata e non si ricorda, usare la funzione **Password dimenticata** nella schermata di login
    4. Se il problema persiste, contattare Custom S.p.a. per il ripristino dell'account

??? question "La pagina si carica lentamente o non si apre"
    1. Verificare la connessione internet (aprire un altro sito per confermare)
    2. Provare a ricaricare la pagina con **F5** o **Ctrl+R**
    3. Svuotare la cache del browser (Ctrl+Shift+Canc) e riprovare
    4. Provare con un browser diverso (Chrome o Edge aggiornati)

??? question "Non vedo tutte le sezioni del menu laterale"
    Il menu potrebbe essere collassato. Cliccare sull'icona ☰ in alto a sinistra per espanderlo. Se alcune sezioni non compaiono, verificare che il piano acquistato le includa — alcune funzioni sono disponibili solo sui piani Advanced ed Enterprise.

---

## Agenda e appuntamenti

??? question "L'agenda è vuota — non vedo le colonne degli operatori"
    Gli operatori non sono stati ancora configurati, oppure non hanno orari di lavoro impostati per il giorno visualizzato.
    
    1. Verificare che gli operatori siano stati creati in **Anagrafiche → Operatori**
    2. Verificare che abbiano orari di lavoro impostati per il giorno corrente
    3. Verificare che gli orari della sede (1.3) siano stati configurati correttamente

??? question "Non riesco a creare un appuntamento — il trattamento non compare"
    Il listino trattamenti è vuoto o il trattamento cercato non è stato inserito.
    
    1. Andare in **Anagrafiche → Trattamenti** e verificare che esistano trattamenti configurati
    2. Verificare che il trattamento non sia disabilitato o archiviato
    3. Assicurarsi di digitare correttamente il nome nel campo di ricerca

??? question "Non riesco a salvare un appuntamento — viene mostrato un errore"
    Verificare che tutti i campi obbligatori siano compilati: cliente, trattamento, operatore. Se l'errore persiste, aprire un ticket di assistenza.

---

## Stampante fiscale

??? question "Il test di connessione con la stampante fallisce"
    Seguire nell'ordine:
    
    1. La stampante è **accesa** e il display mostra lo stato "pronta"?
    2. Il **cavo di rete** è inserito correttamente nella stampante e nel router/switch?
    3. L'**indirizzo IP** inserito in HyperBeauty corrisponde a quello della stampante? Verificare nel pannello della stampante o nell'elenco dispositivi del router.
    4. La stampante e il computer sono sulla **stessa rete locale**? (entrambi connessi allo stesso router)
    5. La **porta** impostata è corretta? Solitamente è la `80`.
    6. C'è un **firewall** o antivirus che blocca la comunicazione? Provare a disabilitarlo temporaneamente per il test.
    7. Il modello di stampante **supporta il protocollo WebService**? Contattare Custom S.p.a. per la verifica.

??? question "La stampante era connessa ma ora non risponde più"
    Il problema più comune è il cambio di indirizzo IP della stampante dopo il riavvio del router.
    
    1. Verificare l'attuale indirizzo IP della stampante nel suo pannello di controllo
    2. Se l'IP è cambiato, aggiornarlo in **Configurazione → Stampante**
    3. Per evitare che si ripeta, impostare un **IP statico** nella stampante o configurare una prenotazione DHCP nel router

??? question "Lo scontrino viene emesso ma i dati della sede sono errati"
    I dati della sede non sono stati inseriti correttamente o non sono stati salvati.
    
    1. Andare in **Configurazione → Sede → Dati Sede**
    2. Verificare Ragione Sociale e Partita IVA
    3. Cliccare **Salva** e riprovare ad emettere un documento di prova

---

## Cassa e documenti fiscali

??? question "Ho emesso uno scontrino per errore — come lo annullo?"
    Vedere la sezione [1.11 — Annullare un documento commerciale](operativita.md#111--annullare-un-documento-commerciale).
    
    !!! warning "Ricorda"
        L'annullamento è possibile solo **prima della chiusura Z giornaliera**.

??? question "Non riesco ad annullare il documento — l'opzione non è disponibile"
    La chiusura Z è già stata eseguita. In questo caso è necessario emettere un **documento di reso** dalla stampante Custom. Contattare il supporto Custom S.p.a. per la procedura specifica del modello di stampante in uso.

---

## Supporto

Per problemi non risolti con questa guida, aprire un ticket di assistenza direttamente da HyperBeauty:

**Percorso:** Menu laterale → **Utility** → **Assistenza** → **Apri Ticket**

Consultare anche le **68 video-guide** nella Guida integrata (icona in alto a destra) per trovare soluzioni ai problemi più comuni.
