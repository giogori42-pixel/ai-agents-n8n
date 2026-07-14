# Airbnb America New York 🗽

Progetto personale per organizzare una **gita a New York City** partendo da
**Timber Lake Camp** (Shandaken, NY, sui Catskills): come arrivare, dove
dormire, cosa fare e come tornare.

## 📁 Struttura

```
ai-agents-n8n/
├── README.md                        → questo file
├── docs/
│   ├── itinerario-nyc.md            → il piano completo (andata / notte / ritorno)
│   ├── bus-shandaken-nyc.md         → dettagli bus, orari, come prenotare
│   └── checklist-prenotazioni.md    → cosa prenotare, spunte da fare domani
├── workflows/  credentials/  data/  → cartelle vuote (per uso futuro)
```

## ⭐ Da dove ripartire domani sul laptop

Apri **`docs/checklist-prenotazioni.md`**: è la lista delle cose da
fare/prenotare, in ordine. Le prime due sono le più urgenti:

1. **Verificare l'orario dell'ultimo bus** Shandaken → NYC (il bus delle 18:00
   potrebbe non esistere)
2. **Prenotare hotel/Airbnb** a Midtown, vicino a Port Authority

## 💻 Come aprirlo su Antigravity (laptop)

```bash
git clone https://github.com/giogori42-pixel/ai-agents-n8n.git
cd ai-agents-n8n
git checkout claude/airbnb-america-new-york-o6wvd8
```
Poi in Antigravity: **File → Open Folder** → scegli `ai-agents-n8n`.
Per ricevere aggiornamenti futuri: `git pull`.
