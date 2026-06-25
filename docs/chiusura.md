---
title: Chiusura Giornaliera
tipologia: software
nome: HyperBeauty
produttore: Custom S.p.A.
argomento: Come eseguire la chiusura fiscale giornaliera (Chiusura Z) del Registratore Telematico Custom direttamente dal Planning di HyperBeauty
autore: Robuschi Ivan
documento_destinato_a: partner
data_creazione: 2026-06-25
revisione: "1.0"
lingua: it
livello_corso: level_1
tipo_contenuto: guida-operativa
sezione_ordine: 21
prodotto_versione: "2026"
keywords:
  - chiusura_fiscale
  - chiusura_z
  - registratore_telematico
  - chiusura_giornaliera
  - planning
  - azioni
  - stampante_rt
  - conta_soldi
---

# Chiusura Giornaliera

La chiusura fiscale giornaliera — detta **Chiusura Z** — azzera i totali del Registratore Telematico e trasmette i corrispettivi all'Agenzia delle Entrate. Va eseguita **ogni sera a fine turno**, dopo l'ultimo incasso della giornata. In HyperBeauty si avvia direttamente dal Planning senza uscire dal gestionale.

!!! warning "Obbligo fiscale"
    La Chiusura Z è un adempimento fiscale obbligatorio. Deve essere eseguita ogni giorno lavorativo in cui sono stati emessi scontrini. Non eseguirla equivale a mancata trasmissione telematica dei corrispettivi.

---

<video controls width="100%" style="border-radius:8px; margin-bottom:1.5rem;">
  <source src="../assets/resources/chiusura.mp4" type="video/mp4">
</video>

---

## Aprire il pannello Azioni dal Planning

![Planning a fine giornata — appuntamenti incassati visibili](assets/images/chiusura/step_01.png)

**Percorso:** Planning → icona **⚙️ ingranaggio** in alto a destra → tab **Azioni**

Il pannello laterale si apre sulla destra con il tab Azioni selezionato.

---

## Il pannello Azioni

![Pannello Azioni — schede disponibili a fine turno](assets/images/chiusura/step_03.png)

Il pannello mostra una scheda per ogni azione disponibile:

| Scheda | Funzione |
|--------|----------|
| **Chiusura Fiscale su [nome stampante]** | Invia il comando di Chiusura Z al Registratore Telematico indicato. Appare una scheda per ogni RT configurato nel salone (es. RECEPTION, BANCO). |
| **Funzione CONTA-SOLDI** | Strumento per contare e registrare il contante presente in cassa a fine turno. |
| **MEMO sullo SIZE corrente** | Permette di visualizzare o inserire note/memo relativi al turno corrente. |

---

## Eseguire la Chiusura Fiscale

Cliccare il pulsante **STAMPA** sulla scheda **Chiusura Fiscale su [nome stampante]** corrispondente all'RT da chiudere.

![Modal di conferma — Invio richiesta di stampa chiusura](assets/images/chiusura/step_04.png)

Il sistema mostra brevemente una finestra **STAMPANTE** con il messaggio *"Invio Richiesta di Stampa/operazione..."* — la comunicazione con l'RT è in corso.

![Pannello Azioni dopo chiusura — operazione completata](assets/images/chiusura/step_05.png)

Quando il modal si chiude automaticamente, la Chiusura Z è stata inviata con successo. Il Registratore Telematico stampa il documento di chiusura fiscale e trasmette i dati all'Agenzia delle Entrate.

!!! tip "Salone con più RT"
    Se il salone ha più Registratori Telematici (es. uno alla reception e uno al banco), nel pannello Azioni appare una scheda **Chiusura Fiscale** per ognuno. Eseguire la chiusura su ciascun RT separatamente.

---

## Riepilogo

| Passo | Azione |
|-------|--------|
| 1 | Terminare tutti gli incassi della giornata |
| 2 | Planning → ⚙️ ingranaggio → tab **Azioni** |
| 3 | Cliccare **STAMPA** sulla scheda Chiusura Fiscale |
| 4 | Attendere il completamento (modal si chiude automaticamente) |
| 5 | Verificare la stampa del documento di chiusura dall'RT |

---

*Documento a cura di Custom S.p.a. — HyperBeauty Training Program — Versione 1.0 — Giugno 2026*
