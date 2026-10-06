# PROGETTO CLINICA

# Progetto di Interoperabilita' Clinica e Analisi Dati (HL7 CDA)

Repository ufficiale per il progetto accademico del corso di riferimento del Prof. Mellone. Il progetto si concentra sull'elaborazione di dati clinici e sulla gestione di documenti strutturati conformi agli standard di interoperabilita' sanitaria, integrando analisi esplorativa e generazione di template XML.

---

## Nota Importante sui Dati
Si segnala che **il database (o i file di dati sorgente) su cui si basa l'esecuzione del codice non e' incluso** in questa repository per motivi di spazio o riservatezza. I notebook Jupyter sono strutturati per elaborare i dataset di riferimento locali: per una corretta esecuzione, assicurarsi di inserire i file di dati nei percorsi previsti o di configurare le variabili di connessione all'interno dei notebook.

---

## Struttura della Repository

La repository e' organizzata come segue[cite: 2]:

* **`CODICE_PROGETTO_ANALISI.ipynb`** Notebook Jupyter dedicato all'analisi dei dati, all'elaborazione e all'applicazione dei modelli.
* **`CODICE_PROGETTO_GENERAZIONE_TABELLE.ipynb`** Notebook Jupyter per la generazione e la formattazione tabellare dei risultati e dei dati clinici.
* **`cda_pss_codici_locali.xml`** Template/documento XML CDA (Clinical Document Architecture) relativo ai codici locali / PSS.
* **`cda_tv_codici_locali.xml`** Template/documento XML CDA correlato.
* **`.gitignore` & `.gitattributes`** File di configurazione per il controllo di versione Git.