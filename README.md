# Airbnb America New York 🗽

Progetto di automazione e AI agents (n8n) dedicato agli annunci Airbnb di **New York, USA**.

## 📁 Struttura del progetto

```
ai-agents-n8n/
├── README.md          → questo file
├── workflows/         → workflow n8n (file .json esportati da n8n)
├── credentials/       → note sulle credenziali (NON mettere qui password/API key reali)
├── docs/              → documentazione, appunti, idee
└── data/              → dati di esempio, output, dataset (Airbnb NY)
```

## 🎯 Obiettivo

Costruire agenti AI e workflow n8n per:
- Raccogliere e monitorare annunci Airbnb a New York
- Analizzare prezzi, disponibilità e recensioni
- Automatizzare notifiche e report

> Descrivi qui sotto man mano cosa vuoi che faccia il progetto.

## 💻 Come collegarlo al tuo laptop (cartella)

Sul tuo computer, apri il terminale e lancia:

```bash
git clone https://github.com/giogori42-pixel/ai-agents-n8n.git
cd ai-agents-n8n
```

Da quel momento avrai una cartella sul laptop collegata a questo repository.
Per scaricare gli aggiornamenti futuri:

```bash
git pull
```

## 🔒 Sicurezza

Non caricare mai chiavi API, token o password nel repository.
Usa il file `.gitignore` per escludere file sensibili (es. `.env`).
