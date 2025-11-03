# Task Manager con Time Tracking

Task Manager standalone completo con funzionalità avanzate di time tracking.

## Funzionalità

### Task Management
- CRUD completo per task
- Priorità (critica, alta, media, bassa)
- Assegnazione a persone/team
- Organizzazione per progetti
- Tracking progresso (0-100%)
- Date di scadenza
- Filtri avanzati

### Time Tracking ⏱️
- **Timer automatico**: Start/Stop con registrazione in tempo reale
- **Sessioni manuali**: Aggiungi ore lavorate manualmente
- **Tempo stimato vs effettivo**: Confronto per ogni task
- **Timesheet completo**: Vista dettagliata di tutte le sessioni
- **Esportazione CSV**: Per reportistica esterna
- **Statistiche avanzate**:
  - Ore totali per progetto
  - Ore totali per priorità
  - Trend settimanali
  - Media ore per task
- **Arrotondamento**: Opzionale a 5, 10, 15 minuti
- **Obiettivi settimanali**: Target ore configurabile

### Statistiche
- Grafici interattivi (Chart.js)
- Metriche real-time
- Analytics completamenti
- Report tempo dedicato

### Import/Export
- Esportazione JSON completa
- Importazione con merge/replace
- Esportazione CSV timesheet

## Utilizzo

Apri `index.html` in qualsiasi browser moderno. Non richiede build o dipendenze esterne (eccetto Chart.js da CDN).

## Tecnologie

- HTML5 + CSS3 + Vanilla JavaScript
- Chart.js per visualizzazioni
- LocalStorage per persistenza
- Zero build tools richiesti
