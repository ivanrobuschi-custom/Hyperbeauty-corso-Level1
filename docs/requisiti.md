---
title: Requisiti di Sistema
---

# Requisiti di Sistema

## Requisiti hardware e software

HyperBeauty è un software **cloud-based**: non richiede installazione locale e funziona direttamente dal browser su qualsiasi dispositivo connesso a Internet.

### Dispositivo

| Tipo | Requisito |
|------|-----------|
| **Computer** | PC Windows o Mac, con browser aggiornato |
| **Tablet** | iPad o tablet Android, schermo ≥ 10" consigliato |
| **Smartphone** | Android (app PrimoUp disponibile — vedi Level 4) |
| **Browser consigliato** | Google Chrome o Microsoft Edge (ultimi aggiornamenti) |
| **Connessione** | Internet stabile — minimo 5 Mbps |

> 💡 **Consiglio:** Per l'utilizzo quotidiano alla reception si consiglia un monitor da almeno 21" per visualizzare l'agenda in modo comodo. Su schermi piccoli alcune funzioni avanzate potrebbero risultare meno leggibili.

---

## Requisiti per la stampante fiscale

!!! warning "Verifica preliminare obbligatoria"
    L'integrazione nativa HyperBeauty è disponibile **esclusivamente** con i dispositivi Custom dotati di **protocollo WebService**. Sono esclusi i registratori di cassa a tastiera e le stampanti di seconda generazione. Verificare sempre il modello del dispositivo prima di procedere.

HyperBeauty è l'unico gestionale beauty sul mercato italiano con integrazione **nativa e certificata** con le stampanti fiscali **Custom** dotate di protocollo WebService. Questa integrazione consente di emettere scontrini e documenti commerciali direttamente da HyperBeauty, senza software intermedi.

### Prerequisiti di rete per la stampante

- La stampante Custom deve essere connessa alla **stessa rete locale** (LAN/Wi-Fi) del computer che esegue HyperBeauty
- Assegnare alla stampante un **indirizzo IP statico** (o una prenotazione DHCP nel router) per evitare che l'IP cambi al riavvio
- Annotare l'indirizzo IP della stampante (es. `192.168.1.100`) prima di procedere con la configurazione

### Configurazione della stampante in HyperBeauty

**Percorso:** Menu laterale → **Configurazione** → **Stampante** (o **Dispositivi Fiscali**)

1. Selezionare il tipo di dispositivo: **Custom RT / WebService**
2. Inserire l'**indirizzo IP** della stampante nel campo dedicato
3. Inserire la **porta** di comunicazione (solitamente `80`)
4. Cliccare su **Test connessione** — il sistema comunica con la stampante e restituisce esito positivo o negativo
5. Se il test ha esito positivo, cliccare su **Salva**

### Se il test di connessione fallisce

Verificare nell'ordine:

1. La stampante è **accesa e pronta** (display attivo, nessun errore)?
2. Il **cavo di rete è collegato** correttamente (o la Wi-Fi è attiva e connessa alla stessa rete)?
3. L'**indirizzo IP** inserito è corretto? Verificarlo nel pannello della stampante o nell'elenco dispositivi del router.
4. Il **firewall del PC** blocca la comunicazione sulla porta 80? Provare a disabilitarlo temporaneamente per il test.
5. Il modello della stampante **supporta il protocollo WebService**? In caso di dubbio contattare il supporto Custom S.p.a.

### Impostazioni fiscali

Prima di emettere il primo documento fiscale, verificare che i dati della sede (Partita IVA, Ragione Sociale) siano stati inseriti correttamente nella sezione [Configurazione Iniziale](configurazione.md#13--configurazione-sede-e-orari-di-lavoro). Questi dati vengono trasmessi automaticamente alla stampante Custom ad ogni documento emesso.

---

## Piani HyperBeauty

| Piano | Operatori inclusi | Funzioni principali |
|-------|------------------|---------------------|
| **Essential** | fino a 6 | Agenda, cassa base, anagrafiche, listino |
| **Advanced** | fino a 6 | Essential + statistiche avanzate, marketing base |
| **Enterprise** | illimitati | Advanced + magazzino, multi-sede, fatturazione elettronica |

> 📌 Per centri con più di 6 operatori è necessario il modulo aggiuntivo **Operatori/Risorse aggiuntive** — verificare con Custom S.p.a.
