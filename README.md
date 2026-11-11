# Analisi del mercato del lavoro italiano con Power BI

## Descrizione del progetto

Il progetto analizza alcuni indicatori del mercato del lavoro italiano attraverso una dashboard interattiva realizzata con Microsoft Power BI.

L'obiettivo è esplorare le differenze territoriali tra le regioni italiane e studiare l'associazione statistica tra livello di istruzione terziaria e tasso di disoccupazione.

L'analisi prende in considerazione il periodo **2022–2024** e comprende le **20 regioni italiane**.

## Obiettivi dell'analisi

- Analizzare l'andamento del tasso di disoccupazione nel territorio italiano.
- Confrontare le differenze tra le aree geografiche del Nord, Centro e Mezzogiorno.
- Esaminare la distribuzione regionale della popolazione con istruzione terziaria.
- Osservare la quota di giovani NEET.
- Studiare la relazione statistica tra percentuale di laureati e tasso di disoccupazione.

## Indicatori analizzati

Il progetto considera tre indicatori principali:

| Indicatore | Descrizione |
|---|---|
| Tasso di disoccupazione (%) | Quota di persone disoccupate rispetto alle forze di lavoro |
| Percentuale di laureati (%) | Quota di popolazione con istruzione terziaria |
| Percentuale di NEET (%) | Quota di giovani che non lavorano e non partecipano a percorsi di istruzione o formazione |

I dati sono organizzati per regione e anno. Le fasce d'età considerate sono quelle indicate nelle rispettive rilevazioni di fonte.

## Metodologia statistica

Per ciascuna regione sono state calcolate le medie del periodo 2022–2024 per gli indicatori analizzati.

Successivamente, sulle 20 medie regionali sono state applicate le seguenti tecniche statistiche:

- **Correlazione di Pearson:** per misurare la direzione e l'intensità dell'associazione lineare tra percentuale di laureati e tasso di disoccupazione.
- **Regressione lineare semplice:** con il tasso di disoccupazione come variabile dipendente e la percentuale di laureati come variabile indipendente.
- **Coefficiente R²:** per valutare la quota di variabilità del tasso di disoccupazione descritta dal modello lineare.

La quota di NEET è utilizzata come indicatore aggiuntivo per descrivere le condizioni del mercato del lavoro regionale.

### Risultati principali

La correlazione di Pearson tra percentuale di laureati e tasso di disoccupazione, calcolata sulle medie regionali, è pari a **-0,6235**.

Il modello di regressione lineare presenta un valore di **R² pari a circa 0,39**, indicando che il modello descrive circa il 39% della variabilità osservata del tasso di disoccupazione tra le regioni.

I risultati evidenziano un'associazione negativa moderata tra le due variabili, senza dimostrare un rapporto di causalità.

## Strumenti utilizzati

- **Microsoft Power BI:** realizzazione della dashboard, visualizzazione e analisi dei dati.
- **Microsoft Excel:** organizzazione dei dati, calcolo delle medie e preparazione dei risultati statistici.

## Fonti dei dati

I dati utilizzati per il progetto sono stati raccolti dai **Rendiconti sociali INPS** relativi al periodo 2022–2024.

## Struttura della dashboard

Il report Power BI è organizzato in quattro sezioni:

1. **Panoramica del mercato del lavoro:** visualizzazione generale degli indicatori.
2. **Analisi territoriale:** confronto tra regioni e aree geografiche.
3. **Istruzione e occupazione:** analisi della relazione statistica tra percentuale di laureati e tasso di disoccupazione.
4. **Metodologia e fonti:** descrizione dei dati, degli indicatori e delle tecniche statistiche utilizzate.

## Considerazioni finali

Il progetto rappresenta un'esperienza pratica di analisi statistica e visualizzazione dei dati, con particolare attenzione all'organizzazione delle informazioni, al confronto territoriale e all'interpretazione dei risultati.

L'analisi ha carattere descrittivo e non consente di stabilire relazioni causali tra gli indicatori considerati.
