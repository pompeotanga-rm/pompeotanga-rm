# Pompeo Tanga

Ingegnere ambientale con competenze avanzate in **sistemi informativi**, **integrazione dati**, **automazione** e **sicurezza informatica**.  
Nel 2025 ho operato come figura tecnica trasversale in ambiente aziendale, occupandomi di progettazione, implementazione e verifica di soluzioni **affidabili, auditabili e orientate alla produzione**.

Questo profilo riassume in modo strutturato le attività tecniche svolte nel corso del 2025.

---

## Profilo professionale

- Ingegnere ambientale di formazione
- Ruolo operativo su:
  - database relazionali
  - automazione dei processi
  - sicurezza informatica
  - integrazione applicativa
- Abituato a lavorare su **sistemi reali**, con vincoli normativi, storicità dei dati e requisiti di affidabilità

---

## Attività principali svolte nel 2025

### 1. PostgreSQL avanzato & Data Engineering

Nel 2025 ho lavorato intensamente su PostgreSQL in contesti non banali, caratterizzati da:
- database multipli separati per dominio
- vincoli di integrità referenziale complessi
- grandi volumi di dati strutturati e semi-strutturati

Attività svolte:
- sviluppo di **funzioni PL/pgSQL complesse**
- utilizzo di **PL/Python (plpython3u)** per:
  - integrazione con servizi esterni
  - gestione file
  - invio email
- progettazione di **pipeline di sincronizzazione multi-database** tramite `dblink`
- gestione avanzata di:
  - JSON / JSONB
  - CTE
  - funzioni idempotenti
  - upsert controllati
- progettazione di **funzioni di verifica post-sincronizzazione**, con:
  - confronto conteggi sorgente/destinazione
  - individuazione di record orfani
  - validazione dei vincoli FK senza disabilitarli

Focus costante su:
- coerenza dei dati
- ripetibilità
- tracciabilità

---

### 2. Integrazione e automazione dei flussi documentali

Ho progettato e implementato flussi completi per la gestione documentale, includendo:

- download di file PDF da object storage (MinIO)
- elaborazione server-side (zip, conversioni, aggregazioni)
- caricamento su server SFTP (SFTPGo)
- notifiche e invii email automatici (Mailgun)

Tecnologie utilizzate:
- PostgreSQL (PL/Python)
- Python standard library (`zipfile`, `threading`, `requests`)
- MinIO
- SFTPGo
- Docker

L’approccio è stato:
- completamente server-side
- orientato all’automazione
- senza interventi manuali

---

### 3. Automazione dei processi (n8n)

Nel 2025 ho installato e utilizzato **n8n** su server aziendale per:

- automazione di processi ripetitivi
- integrazione di sistemi eterogenei
- orchestrazione di flussi basati su eventi

Caso d’uso rilevante:
- rilevamento automatico di **email fraudolente**
- analisi del contenuto
- instradamento verso processi di verifica

---

### 4. AI, RAG e integrazione con sistemi di sicurezza

Ho lavorato sull’integrazione di **modelli linguistici** con sistemi di sicurezza, in particolare:

- progettazione di un **RAG chatbot**
  - basato su grandi volumi di dati (≈10.000 eventi)
  - derivati da query Wazuh
- utilizzo di architetture RAG per:
  - interrogazione semantica degli alert
  - supporto all’analisi degli incidenti
- integrazione di **MCP Server Wazuh** con:
  - Claude Desktop
  - Ollama
  - Open WebUI

Attività svolte:
- adattamento di server MCP in Python
- gestione di `textRequest` e prompt MCP
- configurazione di ambienti locali e containerizzati

---

### 5. Cybersecurity & Compliance

Nel corso del 2025 ho svolto attività di supporto tecnico su:

- **Wazuh (SIEM)**
- analisi di alert e log di sicurezza
- progettazione di flussi di raccolta e analisi dati

Ambiti normativi affrontati:
- GDPR
- NIS2
- requisiti per la nomina del DPO

Con approccio:
- tecnico
- orientato al rischio
- pragmatico e verificabile

---

### 6. Web application & Frontend

Ho realizzato una **Single Page Application** per l’inserimento e la consultazione di dati su PostgreSQL, utilizzando:

- HTML
- Vue 3 (modalità CDN)
- Vue Router
- Axios
- PostgREST

Caratteristiche:
- frontend leggero
- backend REST automatico
- separazione chiara tra dati e presentazione
- hosting su Netlify

---
### 7. Sistemi Linux, virtualizzazione e infrastruttura

Nel 2025 ho operato direttamente su **sistemi Linux server** in contesto aziendale, occupandomi sia della parte applicativa che di quella infrastrutturale.

Attività svolte:

- Amministrazione di sistemi Linux:
  - gestione filesystem
  - permessi e ownership
  - utenti e gruppi
- Gestione di servizi tramite `systemd`:
  - creazione di servizi custom
  - troubleshooting di servizi non avviati
  - analisi di log (`journalctl`)
- Utilizzo quotidiano di shell e tool standard:
  - `bash`
  - `cron`
  - `rsync`
  - `scp / sftp`
- Analisi e risoluzione di problemi a livello OS
  - path errati
  - servizi non registrati
  - variabili d’ambiente
  - conflitti di porta

---

### Virtualizzazione e container

- Utilizzo di **Proxmox** per:
  - gestione di macchine virtuali
  - ambienti separati per sviluppo / produzione
  - snapshot e ripristini
- Gestione di container Docker:
  - backend applicativi
  - servizi di automazione
  - ambienti di test isolati
- Integrazione tra:
  - container
  - servizi di sistema
  - database PostgreSQL

Approccio orientato a:
- stabilità
- riproducibilità
- separazione dei contesti

---

### Networking di base & operatività

- Configurazione di servizi esposti in rete locale
- Verifica porte e connettività
- Uso consapevole di firewall e binding
- Integrazione tra sistemi on-premise e servizi esterni

## Stack tecnologico utilizzato

**Database**
- PostgreSQL
- PostGIS
- Microsoft SQL Server

**Backend**
- Python
- PL/pgSQL
- PL/Python
- FastAPI

**Automation & Infra**
- n8n
- Docker
- MinIO
- SFTPGo

**AI & Security**
- Wazuh
- MCP
- Ollama
- RAG
- SIEM

**Frontend**
- Vue 3
- HTML
- JavaScript

---

## Approccio al lavoro

- Centralità dei **vincoli di integrità**
- Nessuna scorciatoia non tracciabile
- Funzioni verificabili e ripetibili
- Attenzione alla manutenzione futura
- Soluzioni progettate per ambienti produttivi

---

## Contatti

- Email: pompeo.tanga@romamaceri.it
- GitHub: questo profilo

---

Questo profilo rappresenta un riepilogo fedele delle attività tecniche svolte nel 2025 in contesto aziendale.
