# Content Manager → Content LinkedIn

Pacchetto progettato per Codex/ChatGPT a partire da:
1. repository pubblica `agenti-ai-contenuti`;
2. toolkit del webinar;
3. trascrizione del webinar;
4. adattamento esplicito al goal di Tommaso: agente Content Manager con specializzazione Content LinkedIn.

## Struttura
- `AGENTS.md`: agente principale / contratto di progetto.
- `agents/`: ruoli specialistici interni al progetto. È una convenzione nostra, non un formato auto-discovery di OpenAI.
- `skills/`: skill nel formato portabile OpenAI (`SKILL.md` + `references/`).
- `archivio/`: voce e storico personale.
- `dati/`: performance e fonti strutturate.
- `bozze/`: output in lavorazione.
- `routines/`: specifiche delle automazioni ricorrenti.

## Primo avvio
Non attivare ancora la routine. Prima:
1. importa i post LinkedIn di Tommaso;
2. genera `post-indice.md` e `post-testi.md`;
3. analizza i post realmente scritti da Tommaso e genera `voce.md`;
4. costruisci i formati e la guida performance dai dati;
5. prova manualmente la skill per alcune settimane e registra le correzioni;
6. solo dopo attiva la routine settimanale.
