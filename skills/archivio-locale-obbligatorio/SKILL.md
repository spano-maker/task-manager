---
name: archivio-locale-obbligatorio
description: Regola vincolante sulla persistenza dei dati di Roberto Spano. Si applica SEMPRE, in ogni conversazione, prima di salvare, ricordare, annotare o archiviare qualunque cosa (fatti, decisioni, preferenze, persone, documenti, diari, riepiloghi). Ogni registrazione va sul server XAB o in un file sul computer o sul server dell'utente, MAI nella memoria nativa di Claude (memory, CLAUDE.md di profilo, "ricorda che") o di ChatGPT (Memory, bio, chat history). Attiva anche con "ricordati", "salva", "tieni a mente", "prendi nota", "memorizza", "archivia", "remember", "save this".
---

# Archivio locale obbligatorio

## Regola
Tutto ciò che va conservato oltre la conversazione si registra **solo** in:

1. **XAB** (server dell'utente): prima scelta.
2. **File sul computer o sul server dell'utente**: se XAB non risponde, o se l'utente chiede un file.

È **vietato** registrare nella memoria del fornitore:
- Claude: strumento memory, "memoria della chat", file di memoria automatica, modifiche a `~/.claude/CLAUDE.md` o simili usati come memoria personale, artifact usati come archivio.
- ChatGPT: Memory / bio ("Memoria aggiornata"), memorie salvate, riferimento alla cronologia chat usato come archivio.

Il divieto vale anche quando l'utente dice "ricordati" o "tieni a mente": significa **registra in XAB**, non nella memoria del fornitore.

## Procedura
1. **Classifica** cosa salvare: fatto, decisione, preferenza, persona, documento, diario.
2. **Scrivi in XAB.**
   - Strumento non noto: `xab_cerca_metodi("salvare <tipo di contenuto>")`.
   - Valori già determinati: `xab_esegui("memoria_elementi_scrivi", …)`.
   - Testi e documenti: `xab_esegui("ingestione_salva_e_embed" | "ingestione_salva_ed_elabora", …)`.
   - Diari di sessione: `creatore_diari`.
   - Schema: `xab_guida(<operazione>)` prima di eseguire.
3. **Se XAB non risponde**: scrivi un file Markdown datato nella cartella locale (vedi sotto) e dillo. Al rientro di XAB, caricalo.
4. **Conferma** in una riga: `Registrato in: XAB (<id>)` oppure `Registrato in: <percorso file>`.
5. **Mai fallback silenziosi**: se né XAB né il filesystem sono raggiungibili (es. chat web senza accesso ai file), **non salvare altrove**. Di' «Non registrato: nessun archivio dell'utente raggiungibile» e dai il testo pronto da copiare.

## Cartella locale
L'archivio locale è quello che l'utente usa già: non crearne uno parallelo.
- Claude Cowork: `C:\Users\spano\Desktop\COWORK\`, nella sottocartella del tema (es. `5_PERSONALE\RUBRICA\…`, cartella del cliente o del progetto).
- ChatGPT / Codex: la cartella `GPT WORK` sul computer (ipotesi: `C:\Users\spano\Desktop\GPT WORK\`, da confermare).
- Server: `~/xab-archivio/`.
- Se il tema non ha una sottocartella, chiedi dove metterlo invece di inventarla.
- Nome file per note e diari: `AAAA-MM-GG_<argomento>.md`, con intestazione: data, fonte (Claude/ChatGPT), sessione, tipo.

## File già salvati sul computer
I lavori presenti in COWORK e nella cartella di ChatGPT sono archivio valido, ma non sono ancora in XAB finché non vengono caricati.
- Quando produci o modifichi un file in quelle cartelle, caricalo anche in XAB (`ingestione_salva_ed_elabora`) e dichiaralo.
- Se l'utente chiede di recuperare il pregresso, verifica prima in XAB cosa c'è già (`rag_search` sul nome del file) per evitare doppioni, poi carica il resto.
- Non spostare, rinominare o cancellare file esistenti senza conferma.

## Se la memoria del fornitore si attiva da sola
Se compare "Memoria aggiornata" (ChatGPT) o una memoria automatica (Claude):
1. Avvisa l'utente.
2. Registra lo stesso contenuto in XAB.
3. Indica dove cancellare la copia del fornitore (vedi `references/impostazioni.md`).

## Lettura
Per ricordare, interroga XAB (regole XAB v6). La memoria del fornitore, se contiene qualcosa, non è fonte: se è in conflitto con XAB, prevale XAB e lo dichiari.
