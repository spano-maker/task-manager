# 🗂️ Task Manager con Time Tracking Avanzato

> **Applicazione standalone completa per gestione task e tracciamento tempo**
> Nessun server, nessun build, nessuna configurazione - funziona subito!

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/spano-maker/task-manager)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Browser](https://img.shields.io/badge/browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-orange.svg)](https://github.com/spano-maker/task-manager)

---

## ✨ Caratteristiche Principali

### 📋 Task Management Completo
- ✅ CRUD completo per attività
- 🎯 4 livelli di priorità (critica, alta, media, bassa)
- 👥 Assegnazione a persone/team
- 📂 Organizzazione per progetti customizzabili
- 📊 Barra progresso automatica collegata al tempo
- 📅 Gestione scadenze con notifiche visive
- 🔍 Filtri avanzati (ricerca, priorità, scadenza)

### ⏱️ Time Tracking Professionale
- **Timer Automatico**: Start/Stop con contatore real-time
- **Sessioni Manuali**: Registrazione retroattiva ore lavorate
- **Progresso Intelligente**: Calcolo automatico da tempo registrato vs stimato
- **Indicatori Visivi**: Barra blu (ok), verde (completata), rossa (sforata)
- **Descrizioni Dettagliate**: Annota cosa hai fatto in ogni sessione
- **Timesheet Completo**: Tabella filtrable di tutte le sessioni
- **Export CSV**: Per Excel, Google Sheets, reportistica
- **Arrotondamento**: Opzionale a 5/10/15 minuti

### 📊 Analytics & Statistiche
- 📈 Grafici interattivi powered by Chart.js
- 🕐 Ore totali per progetto (top 8 visualizzati)
- ⚡ Distribuzione tempo per priorità
- 📅 Trend completamenti ultimi 14 giorni
- 🎯 Confronto obiettivo settimanale vs effettivo
- 💹 Media ore per task

### 📋 Riepilogo Attività
- Vista panoramica tutte le attività ordinate per tempo
- Modal dettagliata con storico completo sessioni
- Analisi tempo per singola attività
- Date e descrizioni di ogni intervento

### 🔧 Gestione Avanzata
- ⚙️ Progetti e persone personalizzabili
- 🎯 Obiettivo ore settimanali configurabile
- 🗑️ Reset selettivo dati (task/tempo/tutto)
- 💾 Export/Import JSON completo
- 🔒 Conferme di sicurezza multi-livello

---

## 🚀 Quick Start

### Download & Avvio (2 minuti)

1. **Scarica il file**
   ```bash
   # Clone repository
   git clone https://github.com/spano-maker/task-manager.git
   cd task-manager

   # Oppure scarica solo index.html dal repository
   ```

2. **Apri nel browser**
   - Doppio click su `index.html`
   - Oppure trascina il file nel browser
   - Funziona offline dopo il primo caricamento!

3. **Inizia subito**
   - Clicca "➕ Nuova" per creare la prima task
   - Imposta tempo stimato (es. 2 ore)
   - Clicca "▶️ Start" per il timer
   - Il progresso si aggiorna automaticamente! ✨

📖 **Guida completa**: Vedi `GUIDA_RAPIDA.md`

---

## 📦 Contenuto del Package

```
task-manager/
├── index.html              # Applicazione principale (85KB)
├── index.backup.html       # Backup di sicurezza
├── README.md               # Questo file
├── GUIDA_RAPIDA.md        # Tutorial completo
└── esempio_dati.json      # Dati demo per test
```

---

## 💻 Requisiti Tecnici

**Browser Supportati** (ultimi 2 versioni):
- ✅ Google Chrome / Chromium
- ✅ Mozilla Firefox
- ✅ Apple Safari
- ✅ Microsoft Edge

**Requisiti Minimi**:
- JavaScript abilitato
- LocalStorage abilitato (5MB minimo)
- Connessione internet per Chart.js (solo prima volta)

**Compatibilità**:
- Windows 7+
- macOS 10.12+
- Linux (tutte le distro moderne)
- Tablet/Mobile (responsive design)

---

## 🎨 Screenshot Funzionalità

### Dashboard Principale
```
┌─────────────────────────────────────────┐
│  🗂️ Task Manager     📅 10 Nov 2025    │
│  [➕ Nuova] [⬇️ Esporta] [⬆️ Importa]  │
├─────────────────────────────────────────┤
│  📊 In corso: 5  | 🚨 Critiche: 2      │
│  ⚠️ Scadute: 1   | ✅ Completate: 12   │
├─────────────────────────────────────────┤
│  [🔋 Tutte] [🚨 Critiche] [✅ Completate] │
│  [📋 Riepilogo] [⏱️ Timesheet] [📊 Stats]│
└─────────────────────────────────────────┘
```

### Task Card con Timer
```
┌───────────────────────────────────┐
│ 🔴 CRITICA            [✏️] [🗑️]  │
│ Preparare presentazione Q4        │
│ 👤 Carlo · 📂 Marketing · 📅 11/11│
│                                    │
│ ⏱️ Progresso (basato sul tempo)   │
│ ████████████░░░░░░░░  72% ⚠️      │
│                                    │
│ 🕒 Tempo                          │
│ 📝 Registrato: 10.8h              │
│ 🎯 Stimato: 4.0h ⚠️               │
│ 00:00:00                          │
│ [▶️ Start] [➕ Manuale]            │
└───────────────────────────────────┘
```

---

## 🔐 Privacy & Sicurezza

### Dove Sono i Dati?
- ✅ **LocalStorage del browser** - 100% locale
- ✅ **Nessun server remoto** - nessun upload
- ✅ **Nessuna telemetria** - zero tracking
- ✅ **Open source** - codice ispezionabile

### Backup & Recovery
1. **Export regolare**: Usa "⬇️ Esporta" settimanalmente
2. **File JSON**: Conserva in cloud (Dropbox, Drive, ecc.)
3. **Import**: Ripristina su altro browser/dispositivo
4. **Attenzione**: Cancellare dati browser = perdita dati!

---

## 📚 Documentazione Completa

### Guide Disponibili
- 📖 **GUIDA_RAPIDA.md**: Tutorial passo-passo
- 📄 **README.md**: Overview e specifiche tecniche (questo file)
- 💾 **esempio_dati.json**: Dati demo importabili

### Risorse Online
- 🐛 [Report Bug](https://github.com/spano-maker/task-manager/issues)
- 💡 [Richieste Feature](https://github.com/spano-maker/task-manager/issues)
- 📦 [Releases](https://github.com/spano-maker/task-manager/releases)

---

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Markup semantico
- **CSS3**: Grid, Flexbox, Custom Properties
- **Vanilla JavaScript (ES6+)**: Nessun framework
- **Chart.js v4.4.3**: Grafici e visualizzazioni
- **LocalStorage API**: Persistenza dati
- **Responsive Design**: Mobile-first approach

**Zero Dependencies Locali** - Solo Chart.js da CDN

---

## 🎯 Casi d'Uso Ideali

✅ **Freelancer**: Traccia tempo per clienti e progetti
✅ **Team piccoli**: Coordinamento senza overhead
✅ **Studenti**: Gestione progetti e studio
✅ **Uso personale**: Produttività e time management
✅ **Offline work**: Funziona senza connessione
✅ **Prototipazione**: Test rapido workflow

❌ **Non adatto per**:
- Grandi team (>10 persone)
- Collaborazione real-time
- Sincronizzazione cloud automatica
- Dati critici senza backup esterno

---

## 🔧 Personalizzazione

### Modificare Progetti/Persone Default
Edita `index.html` (linee 401-420):
```javascript
const defaultProjects = [
  "Tuo Progetto 1",
  "Tuo Progetto 2"
];

const defaultPeoples = [
  "Nome 1",
  "Nome 2"
];
```

### Cambiare Colori
Modifica CSS variables (linee 12-46):
```css
:root {
  --primary: #1d4ed8;
  --success: #22c55e;
  /* ... */
}
```

---

## ⚡ Performance

- **Dimensione file**: 85KB (non minificato)
- **Caricamento**: <100ms su hardware moderno
- **Rendering**: 60 FPS su liste fino a 1000 task
- **LocalStorage**: ~5MB disponibile (migliaia di task)
- **Offline**: Funziona dopo primo caricamento

---

## 🐛 Troubleshooting

### Il timer non si ferma
**Soluzione**: Ricarica la pagina (F5). I dati sono salvati automaticamente.

### Ho perso i dati
**Soluzione**: Se hai cancellato dati browser, usa l'ultimo export JSON.

### La barra non si aggiorna
**Verifica**: Hai impostato "Tempo stimato" nella task?

### Grafici non si vedono
**Verifica**: Connessione internet attiva per caricare Chart.js CDN.

---

## 📝 Changelog

### v1.0.0 (2025-11-10)
- ✨ Sistema time tracking completo
- 📊 Dashboard statistiche avanzate
- 📋 Tab riepilogo attività con modal
- 🎯 Progresso automatico da tempo
- 🗑️ Sistema reset dati con conferme
- 📦 Package standalone completo
- 📖 Documentazione completa

---

## 📄 Licenza

MIT License - Vedi file LICENSE per dettagli

---

## 👨‍💻 Sviluppo

**Linguaggio**: Vanilla JavaScript (ES6+)
**Totale linee**: ~2000
**Architettura**: MVC-like con state management
**Build**: Nessuno richiesto

### Struttura Codice
```javascript
// Data Model (linee 401-470)
const state = { tasks, completedTasks, ... }

// Utilities (linee 515-590)
function calculateProgress(task) { ... }

// Rendering (linee 591-1400)
function render() { ... }
function renderTaskList() { ... }
function renderTimesheet() { ... }

// Actions (linee 1401-1580)
function addTask() { ... }
function startTimer() { ... }
function stopTimer() { ... }
```

---

## 🌟 Contributi

Questo è un progetto standalone per uso personale.
Fork e modifiche sono benvenute!

---

## 💬 Supporto

- 📧 Email: Consulta repository GitHub
- 🐛 Issues: [GitHub Issues](https://github.com/spano-maker/task-manager/issues)
- 💡 Feature requests: Apri una issue con tag `enhancement`

---

## 🎉 Credits

- **Chart.js**: https://www.chartjs.org/
- **Icons**: Emoji Unicode
- **Font**: System font stack

---

<div align="center">

**Fatto con ❤️ per semplificare il time tracking**

[⬆️ Torna su](#-task-manager-con-time-tracking-avanzato)

</div>
