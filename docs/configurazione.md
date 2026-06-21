---
title: Configurazione Iniziale
tipologia: software
nome: HyperBeauty
produttore: Custom S.p.A.
argomento: Configurazione iniziale sede, orari di lavoro, operatori e listino trattamenti
autore: Robuschi Ivan
documento_destinato_a: partner
data_creazione: 2026-06-20
revisione: "1.0"
lingua: it
livello_corso: level_1
tipo_contenuto: guida-operativa
sezione_ordine: 4
prodotto_versione: "2026"
keywords:
  - configurazione
  - sede
  - orari
  - operatori
  - listino
  - trattamenti
  - prodotti
  - setup_iniziale
---

# Configurazione Iniziale

Questa sezione copre i passaggi obbligatori da completare prima di iniziare a lavorare con HyperBeauty: sede, operatori, listino trattamenti e prodotti.

---

## 1.3 — Configurazione sede e orari di lavoro

La configurazione della sede è il **punto di partenza obbligatorio**: senza questi dati, alcune funzioni dell'agenda e della cassa potrebbero non funzionare correttamente.

### Dati della sede

**Percorso:** Menu laterale → **Configurazione** → **Sede** → **Dati Sede**

**Campi da compilare:**

1. **Ragione sociale / Nome del centro** — come appare sullo scontrino fiscale
2. **Indirizzo completo** — via, numero civico, CAP, città, provincia
3. **Partita IVA** — obbligatoria per la corretta emissione dei documenti fiscali
4. **Codice Fiscale** — se diverso dalla Partita IVA
5. **Telefono** — numero principale del centro
6. **Email** — utilizzata per le comunicazioni automatiche verso i clienti
7. **Sito web** (facoltativo)

Dopo aver compilato tutti i campi, cliccare su **Salva**.

!!! warning "Attenzione"
    I dati della sede compaiono direttamente nei documenti fiscali emessi dalla stampante Custom. Verificare che Ragione Sociale e Partita IVA siano corretti prima di emettere qualsiasi scontrino.

### Orari di lavoro della sede

**Percorso:** Menu laterale → **Configurazione** → **Sede** → **Orari Sede**

Gli orari della sede definiscono la **griglia temporale dell'agenda**: HyperBeauty mostrerà solo le fasce orarie in cui il centro è aperto.

**Procedura:**

1. Per ogni giorno della settimana, indicare l'orario di apertura e di chiusura
2. Per i giorni di chiusura (es. domenica), lasciare il campo vuoto o selezionare "Chiuso"
3. Se il centro ha una pausa pranzo, inserire i due intervalli separatamente (mattina e pomeriggio)
4. Cliccare su **Salva**

> 💡 **Esempio pratico:** Un centro aperto lunedì-venerdì 9:00-19:00 e sabato 9:00-13:00 configurerà: lun-ven → 09:00/19:00, sab → 09:00/13:00, dom → Chiuso.

> 📌 **Nota — turni di lavoro:** Questa configurazione riguarda gli orari fissi della sede. La gestione dei turni variabili degli operatori è una funzione avanzata trattata nel modulo Level 3.

---

## 1.4 — Creazione operatori

Gli **operatori** sono i professionisti che erogano i trattamenti. In HyperBeauty ogni operatore ha una colonna dedicata nell'agenda e un colore identificativo.

**Percorso:** Menu laterale → **Anagrafiche** → **Operatori** → pulsante **Crea operatore**

### Procedura di creazione operatore

1. Cliccare su **Crea operatore**
2. Inserire il **nome** dell'operatore (es. "Sara", "Marco", "Operatore 1")
3. Selezionare un **colore identificativo** — si consiglia di usare colori chiaramente distinguibili tra loro
4. Cliccare su **OK** per creare il profilo base
5. Nella scheda operatore, inserire i **giorni e gli orari di lavoro** (es. lunedì-venerdì 9:00-18:00)
6. Cliccare su **Salva**

Ripetere la procedura per ogni operatore del centro.

> 💡 **Risorse:** Se il centro ha cabine estetiche o postazioni da gestire separatamente dagli operatori (es. cabina 1, lettino solare), queste si chiamano **Risorse** e si configurano con la stessa procedura. Compaiono nell'agenda come colonne aggiuntive accanto agli operatori.

> 📌 **Piano Essential:** include fino a 6 operatori e 6 risorse. Per centri con più di 6 operatori è necessario il modulo aggiuntivo — verificare con Custom S.p.a.

---

## 1.5 — Inserimento listino trattamenti

Il listino trattamenti è il **cuore del sistema di prenotazione**: senza trattamenti configurati non è possibile creare appuntamenti.

### Modalità semplificata (consigliata per iniziare)

**Percorso:** Menu laterale → **Anagrafiche** → **Trattamenti** → modalità **Semplificata**

**Procedura:**

1. Selezionare o creare una **categoria** (es. "Capelli", "Estetica Viso", "Corpo", "Nails")
2. Per ogni trattamento inserire:
    - **Nome** (es. "Piega", "Pulizia viso", "Manicure")
    - **Durata** in minuti (es. 45, 60, 90) — determina lo spazio occupato in agenda
    - **Prezzo** di vendita
3. Cliccare su **Aggiungi** per ogni trattamento

> 💡 **Consiglio:** Iniziare con i trattamenti più comuni. Il listino è sempre modificabile ed espandibile — non è necessario inserire tutto subito.

### Modalità avanzata

**Percorso:** Menu laterale → **Anagrafiche** → **Trattamenti** → modalità **Avanzata**

Offre opzioni aggiuntive:

- **IVA:** specificare l'aliquota IVA del trattamento
- **Colore:** assegnare un colore specifico al trattamento in agenda
- **Operatori abilitati:** limitare il trattamento agli operatori che possono eseguirlo
- **Risorse necessarie:** indicare se il trattamento richiede una cabina specifica
- **Note interne:** testo visibile agli operatori ma non ai clienti

### Modificare l'ordine dei trattamenti

**Percorso:** Menu laterale → **Anagrafiche** → **Trattamenti** → icona **Ordina**

Trascinare i trattamenti nella posizione desiderata. Si consiglia di mettere in cima i trattamenti più prenotati.

---

## 1.6 — Inserimento prodotti di vendita

I **prodotti** sono gli articoli fisici venduti al banco (shampoo, creme, smalti, ecc.), distinti dai trattamenti che sono servizi.

**Percorso:** Menu laterale → **Anagrafiche** → **Prodotti** → pulsante **Nuovo prodotto**

**Procedura:**

1. Inserire il **nome** del prodotto
2. Selezionare o creare una **categoria** (es. "Prodotti capelli", "Cosmetici viso", "Retail")
3. Inserire il **prezzo di vendita**
4. Inserire il **codice prodotto** o barcode (facoltativo)
5. Specificare l'**aliquota IVA** applicabile
6. Inserire la **quantità iniziale** in magazzino (facoltativo)
7. Cliccare su **Salva**

> 📌 **Nota magazzino:** La gestione completa del magazzino è una funzione del piano Enterprise approfondita nel modulo Level 4. In questa fase è sufficiente inserire i prodotti con il prezzo per poterli vendere dalla cassa.

---

## Video guida di riferimento

| Argomento | Video |
|-----------|-------|
| Configurare orari sede | `52-Hyperbeauty_configurare_gli_orari_di_lavoro_sede_no_turni.mp4` |
| Listino trattamenti — semplificata | `61-Hyperbeauty_inserimento_listinotrattamenti_semplificata.mp4` |
| Listino trattamenti — avanzata | `34-Hyperbeauty_inserimento_listino_trattamenti_vis_avanzata.mp4` |
