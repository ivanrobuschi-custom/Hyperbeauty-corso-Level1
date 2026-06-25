---
title: Encoder Matricola RT
tipologia: software
nome: HyperBeauty
produttore: Custom S.p.A.
argomento: Tool per convertire la matricola del Registratore Telematico Custom nella stringa Base64 per la connessione WebServices
autore: Robuschi Ivan
documento_destinato_a: partner
data_creazione: 2026-06-24
revisione: "1.0"
lingua: it
livello_corso: level_1
tipo_contenuto: strumento-operativo
sezione_ordine: 12
prodotto_versione: "2026"
keywords:
  - matricola_rt
  - registratore_telematico
  - base64
  - webservices
  - stringa_autorizzazione
  - custom_rt
  - collegamento_stampante
---

# Encoder Matricola RT

Durante la configurazione del collegamento tra HyperBeauty e il Registratore Telematico Custom, il gestionale richiede una **Stringa di Autorizzazione** nel formato WebServices. Questa stringa si ottiene codificando in Base64 la matricola dell'RT.

Il tool qui sotto automatizza questo passaggio: inserisci la matricola (11 caratteri, es. `96IP3123456`), ottieni immediatamente la stringa pronta da incollare nel gestionale.

!!! info "Quando si usa"
    Solo in fase di collegamento iniziale dell'RT (Anagrafiche → Stampanti). Non è necessario ripetere l'operazione dopo la prima configurazione.

---

<iframe
  src="../assets/tools/matricola-encoder.html"
  width="100%"
  height="460"
  style="border:none; border-radius:8px;"
  title="Matricola RT — Encoder">
</iframe>

---

!!! tip "Formato matricola"
    La matricola dell'RT Custom è composta da **11 caratteri**: 2 cifre + 3 caratteri alfanumerici + 6 cifre (es. `96IP3123456`). La trovi sull'etichetta applicata sul corpo fisico del registratore o nella documentazione tecnica fornita con il dispositivo.

---

*Documento a cura di Custom S.p.a. — HyperBeauty Training Program — Versione 1.0 — Giugno 2026*
