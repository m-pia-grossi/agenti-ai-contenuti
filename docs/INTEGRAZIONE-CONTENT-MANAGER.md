# Integrazione Content Manager — Maria Pia Grossi

I percorsi riportati come testo sono relativi alla radice della repository; i collegamenti sono relativi a questo documento.

Aggiornamento del 3 novembre 2026: applicati T1, T2, T4 e T5 approvati. **T3 esclusa.** Codex è l'ambiente operativo; [AGENTS](../AGENTS.md) instrada le richieste verso il [ruolo LinkedIn](../agents/content-linkedin.md) e le procedure canoniche.

## Caricamento Codex e fonte unica

| Ingresso scoperto da Codex | Procedura canonica letta |
|---|---|
| `.agents/skills/content-linkedin/SKILL.md` | [../skills/content-linkedin/SKILL.md](../skills/content-linkedin/SKILL.md) |
| `.agents/skills/revisione-anti-ai/SKILL.md` | [../skills/revisione-anti-ai/SKILL.md](../skills/revisione-anti-ai/SKILL.md) |
| `.agents/skills/content-image/SKILL.md` | [../skills/content-image/SKILL.md](../skills/content-image/SKILL.md) |

Ogni ingresso contiene soltanto metadati e il rinvio alla procedura. I percorsi interni si risolvono rispetto al file canonico. Non sono stati introdotti collegamenti simbolici o modifiche alla configurazione globale.

Le precedenti copie Codex di `post-linkedin`, `articolo-blog` e `revisione-anti-ai` sono conservate con gli stessi contenuti in `legacy/codex-skills-mastella/<nome>/SKILL.md`. La revisione operativa usa un nuovo ingresso nel percorso precedente. Le skill storiche restano consultabili come fonti, fuori dall'instradamento operativo.

## Conoscenza, memoria e dati

- [Positioning](../references/maria-pia/positioning.md): identità, competenze, problemi cliente e quattro pubblici, separati dallo stile.
- [Voice canonica](../skills/content-linkedin/references/voice.md): regole intenzionali personali già approvate, preservate senza modifiche.
- [TOV integrale](../references/tempo-presente/TONE_OF_VOICE.md): fonte Tempo Presente importata senza riscritture; graphics ne traduce la matrice senza imporre un template LinkedIn.
- `archivio/`: evidenze e testi realmente pubblicati; registri predisposti e vuoti.
- `dati/`: misure reali e provenienza; nessuna rilevazione importata. Le conclusioni appartengono alla reference performance.
- `bozze/`: piani e versioni locali identificabili; soltanto `.gitkeep` è reso tracciabile.
- [DECISIONI](../DECISIONI.md): fonte e ambito delle decisioni generali; le regole complete restano nelle rispettive sedi.

La politica selettiva [../.gitignore](../.gitignore) rende tracciabili i tre file markdown curati dell'archivio e il file dati performance, mantenendo esclusi gli altri contenuti delle cartelle e gli export grezzi. Nessun commit o pubblicazione è implicito.

## Preservazioni e limiti

`CLAUDE-MASTELLA.md`, `.claude-mastella/skills/`, `procedure-mastella/`, `toolkit-mastella/`, `esempio-mastella/` e `AGENTS-MASTELLA-ORIGINALE.md` restano invariati. Non viene creata una copia `legacy/claude/CLAUDE-MASTELLA.md`. Il README ha una nuova apertura operativa; **il contenuto originale sottostante e i crediti sono conservati; solo i collegamenti navigabili sono aggiornati ai nuovi percorsi**, quindi non è corretto dichiarare invariato l'intero file README.

La [routine](../routines/linkedin-weekly-plan.md) contiene il flusso completo approvato ma resta **INATTIVA**. Piano, produzione e pubblicazione/programmazione hanno autorizzazioni distinte, cumulabili solo quando esplicite. Nessuna soglia automatica promuove osservazioni a regole.

Rimangono aperte le cinque scelte editoriali registrate in DECISIONI. Corpus personale recente, correzioni reali e metriche devono ancora alimentare la memoria: non sono stati simulati. Formati e UX restano da sviluppare; il template visuale è ancora aperto. Questi limiti non impediscono un contenuto manuale autorizzato basato su voice, posizionamento e fonti disponibili.
