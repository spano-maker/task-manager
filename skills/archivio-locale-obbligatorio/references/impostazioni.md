# Impostazioni da fare a mano (la skill da sola non basta)

Una skill è un'istruzione: il modello la segue, ma non impedisce tecnicamente al servizio di salvare. Per il blocco effettivo:

## Claude (claude.ai e app)
- Impostazioni → Capacità (Capabilities) → **Memoria: disattiva** "Genera memoria dalla cronologia chat" e "Cerca nelle chat passate" se non le vuoi.
- Impostazioni → Capacità → Skill: carica `archivio-locale-obbligatorio.zip`.
- Preferenze personali: aggiungi la riga in fondo (vedi "Riga per le istruzioni").

## Claude Code
- Copia la cartella in `~/.claude/skills/archivio-locale-obbligatorio/` (Windows: `C:\Users\spano\.claude\skills\`).
- Facoltativo: nel `settings.json` disattiva la memoria automatica (`"autoMemoryEnabled": false`, se presente nella tua versione).

## ChatGPT
- Impostazioni → Personalizzazione → **Memoria: disattiva** "Fai riferimento alle memorie salvate" e "Fai riferimento alla cronologia chat".
- Impostazioni → Personalizzazione → Istruzioni personalizzate: incolla la riga sotto.
- Codex / ChatGPT con skill: copia la cartella in `~/.codex/skills/archivio-locale-obbligatorio/` (stesso formato SKILL.md).
- Memorie già salvate: Impostazioni → Personalizzazione → Gestisci memorie → elimina.

## Riga per le istruzioni (Claude e ChatGPT)
> ARCHIVIO: registra sempre e solo su XAB o in file sul mio computer/server. Mai nella memoria di Claude o ChatGPT. "Ricordati" = registra in XAB. Se nessun archivio mio è raggiungibile, non salvare altrove: dimmelo e dammi il testo da copiare. Conferma sempre dove hai registrato.
