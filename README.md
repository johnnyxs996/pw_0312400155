# Project Work - 0312400155

**Tema:** La digitalizzazione dell'impresa.

**Traccia:** Sviluppo di una applicazione full-stack API-based per un'impresa del settore finanziario.


## Autore

**Nome:** Giovanni Frate

**Email:** giovanni.frate@studenti.unipegaso.it

**Matricola:** 0312400155

**A.A.:** 2024/25


# Avvio

## Docker e Docker-Compose

Il progetto può essere avviato agevolmente tramite docker-compose:
```bash
docker-compose up -d
```

Questo comando avvia contemporaneamente i componenti di Front-End, Back-End, Proxy Server (Nginx) e Database.

### Puntamenti
Di seguito si riportano i puntamenti dei servizi esposti:
- **Front-End:** [https://localhost/auth/login](https://localhost/auth/login).
- **Back-End:** [https://localhost/api/v1](https://localhost/api/v1).
- **Adminer:** [http://localhost:8081/](http://localhost:8081/).

### [Opzionale] Front-End (live)
Il Front-End può essere avviato anche in live tramite Angular CLI, per poter testare in tempo reale i cambiamenti apportati:
```bash
cd front-end && npm ci && npm start
```


## Bootstrap

Al primo avvio è possibile effettuare un bootstrap per pre-popolare il database con dei dati fittizi, tramite il comando:
```bash
docker-compose exec back-end python bootstrap.py
```
Nota: il bootstrap popola il database soltanto se mancante delle entità necessarie.


## Accesso utente

È possibile utilizzare le seguenti credenziali di test per accedere al backoffice e/o creare un token applicativo:
- **Username:** c.leclerc@mail.com
- **Password:** password
