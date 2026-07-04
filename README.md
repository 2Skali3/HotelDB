# Hotel DB

Progetto universitario per il corso di **Basi di Dati** (Ingegneria/Scienze
Informatiche). Modella e implementa un sistema di gestione alberghiera:
anagrafica clienti, programma loyalty, camere e tipologie, prenotazioni con
storico stati, servizi accessori e consumi, utenti e ruoli, report di base.

Lavoro individuale. Obiettivo duplice: elaborato conforme alla metodologia
del corso per l'ammissione all'esame scritto, e base di codice presentabile
come esempio di portfolio.

> Progetto in sviluppo — questo README viene aggiornato al completamento di
> ogni fase.

## Stato di avanzamento

- [x] Analisi dei requisiti (intervista, glossario, riformulazione)
- [x] Progettazione concettuale (schema scheletro, raffinamenti, schema ER finale — notazione Chen)
- [ ] Progettazione logica (stima volumi, schema relazionale, normalizzazione)
- [ ] Query SQL (operative e di reportistica)
- [ ] Applicazione (Go, server-side rendering)
- [ ] Screenshot e capitolo architettura applicazione

## Stack tecnologico

- **DBMS**: MySQL
- **Applicazione**: Go (`net/http` + `html/template`, nessun frontend JS separato)
- **Modellazione**: notazione E/R di Chen (diagrammi in `docs/er`)
- **Relazione**: LaTeX (sorgente e PDF in `docs/HotelDB_Relazione.tex`)

## Struttura della repository

```
HotelDB/
├── docs/
│   ├── relazione/     # relazione LaTeX (sorgente + PDF compilato)
│   └── er/             # export dello schema concettuale ed eventuali schemi successivi
├── sql/                # schema relazionale, script DDL/DML, query (in arrivo)
└── app/                # applicazione Go (in arrivo)
```

## Licenza

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
