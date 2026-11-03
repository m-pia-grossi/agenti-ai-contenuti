# Ciclo editoriale LinkedIn — Maria Pia Grossi

**Stato: INATTIVA. Specifica eseguibile solo su richiesta manuale; nessuna automazione o schedulazione attivata.** Il nome del file conserva il riferimento al ciclo settimanale, senza fissare una frequenza editoriale.

Origine: NOSTRO, adattamento ampliato del metodo Mastella (aggiornamento, apprendimento, ricerca, proposta e arresto prima della scrittura). La sequenza seguente è quella approvata nella specifica dell'utente, §1.14, con gli ambiti di autorizzazione T5.

## Fonti e condizioni

Usa il [ruolo LinkedIn](../agents/content-linkedin.md) e la [procedura canonica](../skills/content-linkedin/SKILL.md). Leggi voice, posizionamento, archivio e reference pertinenti; verifica le [decisioni](../DECISIONI.md). Fonti mancanti si dichiarano, senza simulare importazioni o bloccare le attività indipendenti. Nessun giorno, ora o numero di pubblicazioni è predefinito.

## Flusso completo

1. **Aggiorna l'archivio** con soli post realmente pubblicati e fonti disponibili: [indice](../archivio/post-indice.md) e [testi](../archivio/post-testi.md). Conserva gli originali e distingui eventuali versioni successive.
2. **Aggiorna le metriche reali** in [dati](../dati/performance-linkedin.md), con fonte, data e finestra. Se non disponibili, dichiara dati insufficienti: mancante non è zero.
3. **Confronta bozze e pubblicati** usando ID e versioni identificabili. Se manca una versione, registra il limite senza ricostruirla.
4. **Individua le modifiche di Maria Pia** soltanto quando l'attribuzione è verificabile. Distingui interventi dell'assistente e modifiche di origine incerta.
5. **Apprendi dalle correzioni** registrando prima/dopo, fonte e contesto nella [memoria empirica](../archivio/voce.md). Una modifica locale non è automaticamente una preferenza generale.
6. **Proponi eventuali nuove regole** come candidate, con motivazione, evidenze e ambito; nessuna soglia automatica di ricorrenza.
7. **Aggiorna le regole solo dopo approvazione** esplicita della regola generale, registrando decisione e destinazione canonica. Le candidate non approvate restano tali; puoi proseguire la proposta editoriale senza applicarle come regole. Non chiedere nuovamente approvazioni già esplicite e pertinenti.
8. **Cerca temi** in archivio, fonti interne, strumenti collegati pertinenti e web quando utile. Conserva origine e pertinenza; non attivare nuove integrazioni implicitamente.
9. **Proponi il piano editoriale** coerente con obiettivo e destinatari pertinenti, senza stabilire una priorità permanente tra i quattro pubblici o un calendario non richiesto.
10. **Completa ogni proposta** con ID stabile e sette campi: tema, angolo, formato, fonte/origine, motivazione, obiettivo, eventuale collegamento a contenuti precedenti. Se non ci sono precedenti disponibili, dichiaralo. Formati nuovi restano sperimentali.
11. **STOP prima della produzione non autorizzata.** Consegna il piano e le eventuali candidate, distinti per ambito.
12. **Attendi l'approvazione pertinente.** Registra separatamente piano e produzione dei contenuti identificati. Un messaggio come «approvo il piano e produci 1 e 3» copre entrambi; la sola approvazione del piano non autorizza la scrittura. Se l'autorizzazione è già esplicita, non richiederla di nuovo.
13. **Genera soltanto i contenuti autorizzati per la produzione**, conservando bozze e versioni. Una richiesta diretta di scrittura può avviare la procedura del singolo post senza imporre questo intero ciclo.
14. **Esegui la revisione anti-AI** per ogni contenuto tramite la [skill dedicata](../skills/revisione-anti-ai/SKILL.md); preserva pensiero, fatti e voce, salva una versione distinguibile.
15. **Prepara l'eventuale visual** tramite [content-image](../skills/content-image/SKILL.md), sul testo revisionato e nel perimetro autorizzato. Se il testo cambia, verifica nuovamente la coerenza del visual.
16. **Pubblica o programma solo con autorizzazione esplicita separata**, riferita all'azione e alla versione del contenuto. Nessuna attivazione avviene con questo riallineamento o per il solo trascorrere del tempo.

## Output e persistenza

Alla proposta consegna: aggiornamenti effettivamente eseguiti e lacune, osservazioni/candidate con prove, piano con ID e campi completi. Non presentare contenuti come già scritti, pubblicati o misurati quando non lo sono.

Conserva piani e bozze locali in `../bozze/`, con data, ID, tema, versione e fonti, senza sovrascrivere la versione precedente. Registra per ciascuna autorizzazione data, messaggio o estratto verificabile, contenuti/versioni e ambito. La [skill LinkedIn](../skills/content-linkedin/SKILL.md) definisce la gestione delle versioni. Decisioni generali nei file canonici e in DECISIONI; evidenze stilistiche nell'archivio della voce; misure nel file dati.
