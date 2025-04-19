# Project Work - 0312400155

**Tema:** La digitalizzazione dell'impresa.

**Traccia:** Sviluppo di una applicazione full-stack API-based per un'impresa del settore finanziario.


## Autore

**Nome:** Giovanni Frate

**Email:** giovanni.frate@studenti.unipegaso.it

**Matricola:** 0312400155

**A.A.:** 2024/25

# Avvio

## Back-End & Database

Il Back-End ed il Database del progetto possono essere avviati agevolmente tramite docker-compose:
```bash
docker-compose up -d
```

## Front-End
Il Front-End può essere avviato tramite Angular CLI:
```bash
cd front-end && npm ci && npm start
```

## Bootstrap

È possibile effettuare un bootstrap per pre-popolare il database con dei dati fittizi, tramite il comando:
```bash
docker-compose exec back-end python bootstrap.py
```
Nota: il bootstrap popola il database soltanto se mancante delle entità necessarie.
