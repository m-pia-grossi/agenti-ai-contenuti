# Registro delle decisioni — Maria Pia Grossi

Registrazione iniziale: **3 novembre 2026**. Il registro conserva stato, fonte e destinazione delle decisioni; le regole complete restano nei file canonici. La data di registrazione non sostituisce una data storica di approvazione sconosciuta.

## Fonti delle approvazioni

**S1 — Specifica dell'utente «RIALLINEAMENTO DELLA REPOSITORY — Content Manager → Content LinkedIn — Maria Pia Grossi».** Riprende l'audit del 2 novembre 2026 e le decisioni già approvate nella chat di progettazione: architettura (§1.1), identità e posizionamento (§§1.2–1.4), voice e fonti (§§1.5–1.8), formati e performance (§§1.9–1.10), grafica e UX (§§1.11–1.12), revisione e routine (§§1.13–1.14). Le date delle precedenti approvazioni non sono disponibili. La specifica inizialmente richiedeva approvazione prima dell'esecuzione; S3 la fornisce nel perimetro corretto.

**S2 — Documento integrale «Tone of voice e direzione visiva» fornito dall'utente**, ultimo aggiornamento dichiarato 20 ottobre 2026. Importato senza modifiche nella [fonte Tempo Presente](references/tempo-presente/TONE_OF_VOICE.md). SHA-256: `8B3C7146C7D2F822ADAECB7D55CF15466B2D137D85632DDF654AD09AA3D3D31E`.

**S3 — Approvazione esplicita dell'utente nella chat di riallineamento, ricevuta il 3 novembre 2026.** Passaggi determinanti:

> Ho scelto Codex come ambiente operativo del progetto. In questa fase non voglio introdurre lavoro aggiuntivo di compatibilità Claude.
>
> T1, T2, T4 e T5 sono approvate.
>
> È approvata anche la modifica selettiva di `.gitignore` prevista da T4.
>
> Approvo quindi il piano corretto con T1, T2, T4 e T5; T3 è esclusa. Procedi con il riallineamento della repository.

La stessa approvazione prescrive voice personale invariata byte-per-byte, importazione integrale del TOV con hash preservato, nessuna routine attiva e mantenimento delle cinque scelte aperte riportate sotto. Non modificare `CLAUDE.md` o `.claude/skills/` e non creare `legacy/claude/CLAUDE-MASTELLA.md`.

**S4 — Riordino organizzativo autorizzato da Maria Pia nella chat di progetto il 3 novembre 2026.** Richiesta: «ultimo riordino della repository, esclusivamente organizzativo». Documentazione spostata in `docs/`, materiali storici rinominati con indicazione Mastella, soli riferimenti aggiornati. La [mappa dei percorsi](docs/MAPPA-PERSONALIZZAZIONE.md#riordino-organizzativo--3-novembre-2026) conserva la corrispondenza. I nomi citati in S3 sono quelli precedenti al riordino; contenuti preservati e compatibilità Claude ancora esclusa. Nessun cambiamento a regole, procedure, routine o scelte editoriali aperte. Commit e push non autorizzati in questa fase.

**S5 — Raccolta dei materiali Mastella in una sola cartella, richiesta da Maria Pia nella chat di progetto il 3 novembre 2026.** Dopo il primo riordino, l’utente segnala che i materiali storici sono ancora dispersi e ne richiede il raggruppamento. Tutti confluiscono in `mastella/`, compresi il file di istruzioni originale e il corpo storico del README; contenuti preservati. Questa scelta aggiorna la collocazione dei materiali prevista da O1. Il sistema operativo mantiene i percorsi e le regole approvati.

## Decisioni in vigore

| ID | Data | Stato | Decisione sintetica | Fonte/ambito | Sede canonica |
|---|---|---|---|---|---|
| D01 | Registrata 2026-11-03; approvazione storica non disponibile | APPROVATA | Content Manager coordina Content LinkedIn, procedure, reference, memoria, dati e routine; la repo conserva le decisioni | S1 §1.1; S3, architettura | [AGENTS](AGENTS.md) |
| D02 | Registrata 2026-11-03; approvazione storica non disponibile | APPROVATA | Identità Maria Pia, posizionamento corrente e quattro pubblici professionali | S1 §§1.2–1.4; S3, identità | [Positioning](references/maria-pia/positioning.md) |
| D03 | Confermata 2026-11-03; approvazione storica non disponibile | APPROVATA / PRESERVATA | Voice canonica prioritaria, invariata in questo intervento; archivio empirico distinto | S1 §§1.5–1.8; S3, scrittura | [Voice](skills/content-linkedin/references/voice.md), [memoria](archivio/voce.md) |
| D04 | Registrata 2026-11-03 | APPROVATA | Formati intenzionali ed evolutivi; conclusioni di performance solo da misure reali | S1 §§1.9–1.10; S3, reference | [Formats](skills/content-linkedin/references/formats.md), [performance](skills/content-linkedin/references/performance.md) |
| D05 | Registrata 2026-11-03 | APPROVATA | Matrice Tempo Presente adattata a LinkedIn; UX nostra con contenuto da sviluppare | S1 §§1.11–1.12; S2; S3, visual/UX | [Graphics](skills/content-linkedin/references/graphics.md), [UX](skills/content-linkedin/references/ux-library.md) |
| D06 | Registrata 2026-11-03 | APPROVATA, ROUTINE INATTIVA | Revisione di ogni contenuto prima del visual; ciclo completo di 16 passaggi solo manuale | S1 §§1.13–1.14; S3, processo | [Revisione](skills/revisione-anti-ai/SKILL.md), [routine](routines/linkedin-weekly-plan.md) |
| D07 | 2026-11-05 | APPROVATA | Guida proattiva del Content Manager | Richiesta di Maria Pia nella chat di progetto dopo la condivisione delle attività LinkedIn | [AGENTS, regola 11](AGENTS.md#regole-operative) |
| D08 | 2026-11-05 | APPROVATA | Continuità dei temi nelle sintesi editoriali | Correzione di Maria Pia nella chat di progetto durante il confronto sui pilastri | [AGENTS, regola 12](AGENTS.md#regole-operative) |
| D09 | 2026-11-05 | APPROVATA PER LA SPERIMENTAZIONE | Testi sulla regia dei progetti e sulla fiducia nei team | Indicazione di Maria Pia nella chat di progetto sui temi editoriali | [Stato del progetto](docs/STATO-PROGETTO.md#in-corso) |
| D10 | 2026-11-06 | APPROVATA | Taglio emozionale di ogni post LinkedIn | Maria Pia, chat di progetto: «dare sempre un taglio emzionale ai post» | [Voice personale, postura](skills/content-linkedin/references/voice.md#postura) |
| T1 | Approvata 2026-11-03 | APPROVATA | Tre ingressi Codex con rimando alle procedure canoniche; originali trasferiti in legacy | S3, caricamento skill | [Integrazione](docs/INTEGRAZIONE-CONTENT-MANAGER.md) |
| T2 | Approvata 2026-11-03 | APPROVATA | Reference condivise per positioning e TOV integrale; questo registro | S3, persistenza | [Positioning](references/maria-pia/positioning.md), [TOV](references/tempo-presente/TONE_OF_VOICE.md), questo file |
| T3 | Esclusa 2026-11-03 | ESCLUSA | Nessun lavoro di compatibilità Claude; file esistenti conservati come storico | S3, perimetro tecnico | [AGENTS](AGENTS.md), [integrazione](docs/INTEGRAZIONE-CONTENT-MANAGER.md) |
| T4 | Approvata 2026-11-03 | APPROVATA | Tracciabilità selettiva di tre file archivio, dati performance e bozze/.gitkeep; altri contenuti locali esclusi | S3, politica Git | [.gitignore](.gitignore) |
| T5 | Approvata 2026-11-03 | APPROVATA | Osservazione → candidata → approvata; ambiti distinti per piano, produzione, pubblicazione/programmazione | S3, apprendimento e autorizzazioni | [Skill LinkedIn](skills/content-linkedin/SKILL.md), [memoria](archivio/voce.md) |
| O1 | Approvata 2026-11-03 | APPROVATA | Riordino dei soli percorsi documentali e storici; sistema operativo e contenuti canonici invariati | S4, organizzazione | [Mappa](docs/MAPPA-PERSONALIZZAZIONE.md#riordino-organizzativo--3-novembre-2026) |
| O2 | Approvata 2026-11-03 | APPROVATA | Tutti i materiali storici raccolti in mastella/; aggiorna la collocazione prevista da O1 | S5, organizzazione | [Mappa](docs/MAPPA-PERSONALIZZAZIONE.md#riordino-organizzativo--3-novembre-2026) |

SHA-256 della voice personale preservata al riallineamento del 3 novembre 2026, prima di D10: `4660B34A7B9DA93BAFE642E03B208F8FDC2A99F9277ABE556336560D84A5DAFE`.

## Decisioni volutamente aperte

| ID | Data di conferma | Stato | Scelta | Fonte | Destinazione futura |
|---|---|---|---|---|---|
| A01 | 2026-11-03 | APERTA | Priorità editoriale fra i quattro pubblici | S3 | Positioning |
| A02 | 2026-11-03 | APERTA | Frequenza editoriale | S3 | Routine e piano autorizzato |
| A03 | 2026-11-03 | APERTA | Set definitivo dei formati | S3 | Formats |
| A04 | 2026-11-03 | APERTA | Template LinkedIn definitivo | S3 | Graphics |
| A05 | 2026-11-03 | APERTA | Obbligatorietà del 4:5 | S3 | Graphics |

Questi punti non bloccano il riallineamento o un singolo contenuto esplicitamente richiesto. Nessuna approvazione strutturale in questo registro autorizza pubblicazioni, programmazioni o attivazione di routine.

## Aggiornamenti futuri

Per ogni nuova decisione conserva ID, data, stato, sintesi, fonte verificabile dell'approvazione, ambito e file canonico. Non promuovere proposte per il solo fatto che compaiano in un piano. Se una decisione cambia, registra il nuovo esito e il collegamento a quella superata senza cancellare la provenienza. Le autorizzazioni dei singoli contenuti restano associate a ID/versione nei documenti di lavoro; qui entrano le decisioni generali del sistema.
