# Traduzione italiana del FIBA Statisticians Manual

Versione attuale documento FIBA: 1.0

# Modifiche al manuale tradotto

| Versione Traduzione | Rif. FIBA  | Data Aggiornamento | Note |
|---------------------|------------|--------------------|------|
| 1.0.2               | 1.0       | 19 agosto 2025     | Aggiornamento della traduzione (correzioni) |
| 1.0.1               | 1.0       | 18 luglio 2025     | Primo upload della traduzione |

## Guida alla numerazione delle versioni di questo documento ("Versione traduzione")

Formato `X.Y.Z`

- `X.Y`: dipendono dalla versione FIBA (ad oggi la versione è 1.0)
- `Z`: indica le modifiche apportate alla traduzione

# Struttura del progetto

In **grassetto** i nomi di cartelle, in *corsivo* i nomi di file.

- **model/**: contiene i file di configurazione del documento (formattazione, stili, ecc.).
- **capitoli/**: contiene i capitoli tradotti del manuale. **I file in questa cartella contengono il testo tradotto**. Un capitolo, un file `.tex`.
- **img/**: contiene risorse aggiuntive (immagini, grafici, ecc.).
- **archive/**: contiene versioni precedenti del manuale (è possibile eliminarla in locale per risparmiare spazio).
- **credits/**: contiene il documento originale FIBA.
- *statsmanual.tex*: il file da compilare per ottenere il documento tradotto.
- *statsmanual.pdf*: il documento tradotto finale nella versione più recente.

# FAQ

**Ho notato un errore, come posso segnalarlo?**

Hai diverse opzioni per segnalare un errore:
- Compila [questa scheda](https://github.com/UDC-TV/manuale-statistico/issues/new) indicando il numero di pagina e il tipo di errore riscontrato. Basta compilare il titolo e la descrizione, non è necessario compilare tutti i campi.
- Scrivi su uno dei canali social, preferibilmente Instagram o gli altri canali Meta.
- Se vuoi restare anonimo, utilizza il [form segnalazioni sul sito](https://sites.google.com/view/udc-archivio-clip/segnalazioni).

# Compilare

- Per compilare, lanciare il comando: `pdflatex statsmanual.tex`
  - **NB: assicurarsi di avere tutte le dipendenze LaTeX e i pacchetti utilizzati installati** (i pacchetti sono riportati in `model/header.tex`).
- In alternativa, è possibile utilizzare un applicativo come [Overleaf](https://www.overleaf.com/) per compilare il documento online, senza bisogno di installare programmi in locale.
  - Per farlo, basta copiare l'intero contenuto di questo progetto (tutti i file e cartelle) e avviare la compilazione sul file `statsmanual.tex`.