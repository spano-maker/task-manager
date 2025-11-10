# 🚀 Guida Rapida - Task Manager con Time Tracking

## ⚡ Avvio Rapido (30 secondi)

1. **Apri** `index.html` con qualsiasi browser
2. **Clicca** "➕ Nuova" per creare la tua prima task
3. **Imposta** un tempo stimato (es. 2 ore)
4. **Clicca** "▶️ Start" per avviare il timer
5. **Lavora** sulla task
6. **Clicca** "⏹️ Stop" quando finisci
7. La **barra di progresso** si aggiorna automaticamente! ✨

---

## 📋 Tabs Principali

### 🔋 **Tutte**
Visualizza tutte le task attive con:
- Timer automatico per tracciare il tempo
- Barra progresso collegata al tempo registrato
- Controlli rapidi (+10%, Completa)

### 🚨 **Critiche**
Mostra solo le task con priorità "Critica"

### ✅ **Completate**
Storico delle task finite con opzione di ripristino

### 📋 **Riepilogo Attività**
Vista panoramica di tutte le attività ordinate per tempo speso.
**Clicca su una card** per vedere:
- Tutte le sessioni di lavoro
- Date e durate di ogni sessione
- Descrizioni dettagliate

### ⏱️ **Timesheet**
Tabella completa di tutte le sessioni con:
- Filtri per periodo/progetto/task
- Esportazione CSV per Excel
- Statistiche riepilogative

### 📊 **Statistiche**
Dashboard con:
- Grafici interattivi (Chart.js)
- Metriche tempo per progetto
- Trend completamenti
- Analytics dettagliate

### ⚙️ **Impostazioni**
- Gestione progetti e persone
- Arrotondamento tempo (5/10/15 min)
- Obiettivo ore settimanali
- **Reset dati** (con conferme di sicurezza)

---

## ⏱️ Time Tracking - Come Funziona

### **Timer Automatico**
1. Clicca **"▶️ Start"** sulla task
2. Il timer parte e conta in tempo reale
3. Clicca **"⏹️ Stop"** quando finisci
4. Inserisci una **descrizione** dell'attività svolta
5. La sessione viene salvata automaticamente

### **Inserimento Manuale**
1. Clicca **"➕ Manuale"** sulla task
2. Inserisci:
   - Data della sessione
   - Durata in ore (es. 2.5)
   - Descrizione attività
   - Note opzionali
3. Clicca **"Salva"**

### **Progresso Automatico**
Se imposti un **tempo stimato**:
- Progresso = (Tempo registrato / Tempo stimato) × 100
- Barra blu: 0-99% (nei tempi)
- Barra verde: 100% (completata)
- Barra rossa: >100% (sforata) ⚠️

---

## 💡 Tips & Tricks

### **Filtri Intelligenti**
- 🔎 **Ricerca**: Cerca nel titolo o nelle note
- ⏫ **Priorità**: Filtra per livello di urgenza
- 📅 **Scadenza**: Trova task scadute o in scadenza

### **Shortcut Mentali**
- ✅ Completa la task quando finisci (anche se progresso < 100%)
- 📊 Monitora la tab Statistiche per vedere dove va il tuo tempo
- 🗂️ Usa progetti consistenti per reportistica migliore

### **Backup & Sicurezza**
- Esporta regolarmente i dati (pulsante "⬇️ Esporta")
- I dati sono nel LocalStorage del browser
- **IMPORTANTE**: Se cancelli dati browser, perdi tutto!

---

## 🎨 Priorità & Colori

- 🔴 **Critica**: Rosso - urgente e importante
- 🟠 **Alta**: Arancione - importante
- 🟡 **Media**: Giallo - normale
- 🟢 **Bassa**: Verde - può aspettare

---

## 📤 Export/Import

### **Esportare**
1. Clicca "⬇️ Esporta" nell'header
2. Salva il file JSON
3. Conservalo in un posto sicuro

### **Importare**
1. Clicca "⬆️ Importa"
2. Seleziona il file JSON
3. Scegli "merge" (unione) o "replace" (sostituzione)

---

## ⚠️ Reset Dati

In Impostazioni → Zona Pericolosa:

1. **Reset Solo Task**: Cancella task, mantiene tempo
2. **Reset Solo Tempo**: Cancella tempo, mantiene task
3. **Reset Completo**: Cancella TUTTO

**ATTENZIONE**: Ogni reset richiede conferme multiple!

---

## 🆘 Problemi Comuni

**Q: Il timer non si ferma**
A: Ricarica la pagina. Il timer si fermerà automaticamente.

**Q: Ho perso i dati**
A: Se hai cancellato i dati del browser, non sono recuperabili. Usa l'export regolare!

**Q: La barra non si aggiorna**
A: Assicurati di aver impostato un "tempo stimato" nella task.

**Q: Voglio usarlo su più dispositivi**
A: Esporta da uno, importa sull'altro. Non c'è sincronizzazione automatica.

---

## 🌟 Best Practices

1. **Imposta sempre il tempo stimato** per avere progresso automatico
2. **Usa descrizioni chiare** nelle sessioni per ricordare cosa hai fatto
3. **Esporta settimanalmente** i dati per sicurezza
4. **Rivedi le statistiche** a fine settimana per ottimizzare
5. **Non dimenticare timer attivi** - controlla prima di chiudere

---

## 📞 Supporto

Questo è un progetto standalone senza backend.
Per problemi o suggerimenti, consulta il README.md

**Versione**: 1.0.0 con Time Tracking
**Browser supportati**: Chrome, Firefox, Safari, Edge (ultimi 2 versioni)

---

## 🎉 Buon Lavoro!

Ora sei pronto per tracciare il tuo tempo in modo professionale! 🚀
