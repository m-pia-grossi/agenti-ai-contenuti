# Content Manager — Maria Pia Grossi

I percorsi riportati come testo sono relativi alla radice della repository; i collegamenti sono relativi a questo documento.

Il progetto usa **Codex** come ambiente operativo. [../AGENTS.md](../AGENTS.md) coordina il lavoro; [Content LinkedIn](../agents/content-linkedin.md) gestisce il primo canale personalizzato. Decisioni e regole approvate vivono nei file della repository.

## Avvio manuale

Apri in Codex la cartella della repository `agenti-ai-contenuti` e formula la richiesta: un piano, un contenuto, una revisione o un ciclo editoriale manuale. Se lavori da una chat esterna alla cartella, indica il percorso della repository e richiedi la lettura di AGENTS: il rilevamento delle skill dipende dalla cartella del progetto.

Gli ingressi in `.agents/skills/` espongono `content-linkedin`, `revisione-anti-ai` e `content-image`. Leggono le procedure canoniche in `skills/`; non contengono una seconda copia delle regole. Il [registro decisioni](../DECISIONI.md) documenta T1, T2, T4 e T5 approvate e T3 esclusa.

## Dove leggere e conservare

| Ambito | File o cartella | Stato attuale |
|---|---|---|
| Identità e pubblici | [Positioning](../references/maria-pia/positioning.md) | Approvato; priorità tra pubblici aperta |
| Voce personale | [Voice](../skills/content-linkedin/references/voice.md) | Approvata, preservata integralmente |
| Matrice del brand | [TOV Tempo Presente](../references/tempo-presente/TONE_OF_VOICE.md) | Fonte integrale importata senza modifiche |
| Procedure | [LinkedIn](../skills/content-linkedin/SKILL.md), [revisione](../skills/revisione-anti-ai/SKILL.md), [visual](../skills/content-image/SKILL.md) | Allineate a Maria Pia; visual attuale: concept e specifiche |
| Formati, risultati, grafica, UX | [Reference LinkedIn](../skills/content-linkedin/references/) | Formati progressivi; dati insufficienti; matrice grafica disponibile; UX da sviluppare |
| Correzioni e pubblicati | [Memoria voce](../archivio/voce.md), [indice](../archivio/post-indice.md), [testi](../archivio/post-testi.md) | Registri vuoti, senza storico inventato |
| Misure | [Dati LinkedIn](../dati/performance-linkedin.md) | Nessuna rilevazione importata |
| Piani, bozze e versioni | `bozze/` | Locali, con ID e versioni distinti |
| Ciclo editoriale | [Routine](../routines/linkedin-weekly-plan.md) | INATTIVA; disponibile come specifica manuale |

## Uso e autorizzazioni

La voce parte dalla reference approvata e dal posizionamento attuale. I pochi post storici, quando disponibili, sono fonti secondarie. La mancanza di metriche impedisce conclusioni sulle performance, non la produzione di un contenuto autorizzato.

Un piano contiene ID e sette campi per proposta, poi si arresta prima della produzione non autorizzata. Una richiesta diretta di scrittura autorizza già quel contenuto; un messaggio può approvare piano e produzione insieme. Ogni testo passa dalla revisione prima del visual. Pubblicazione e programmazione richiedono autorizzazione esplicita separata.

Le correzioni producono osservazioni e candidate con prove prima/dopo; soltanto le regole generali approvate aggiornano le reference. Non esistono soglie automatiche di ripetizione.

Restano aperti priorità dei pubblici, frequenza, set definitivo dei formati, template LinkedIn e obbligatorietà del 4:5. Nessuna routine è attiva.

## Git e materiali storici

[../.gitignore](../.gitignore) rende tracciabili solo i tre file curati dell'archivio, il file dati performance e `bozze/.gitkeep`; bozze, altri file nelle cartelle ed export grezzi restano esclusi. Tracciabile non significa già incluso in un commit.

Tutti i materiali storici sono raccolti in [mastella/](../mastella/), inclusi istruzioni originali, skill storiche, procedure, toolkit, esempio e [README originale con i crediti](../mastella/README.md). Il corpo storico del README è stato trasferito senza ulteriori modifiche rispetto alla versione con i link già aggiornati. Provenienze e limiti sono nella [mappa](MAPPA-PERSONALIZZAZIONE.md); dettagli dei percorsi nell'[integrazione](INTEGRAZIONE-CONTENT-MANAGER.md).
