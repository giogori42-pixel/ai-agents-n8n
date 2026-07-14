# Airbnb America New York 🗽

Progetto personale per organizzare una **gita a New York City** partendo da
**Timber Lake Camp** (Shandaken, NY, sui Catskills): come arrivare, dove
dormire, cosa fare e come tornare.

## 📁 Struttura

```
ai-agents-n8n/
├── README.md                        → questo file
├── docs/
│   ├── RIEPILOGO.md                 → ⭐ PARTI DA QUI: tutto in una pagina
│   ├── itinerario-nyc.md            → il piano completo (andata / notte / ritorno)
│   ├── bus-shandaken-nyc.md         → dettagli bus, orari reali, come prenotare
│   ├── dove-dormire.md              → hotel/ostello a Hell's Kitchen
│   ├── checklist-prenotazioni.md    → cosa prenotare, spunte da fare
│   └── link-orari.md                → link diretti agli orari
├── workflows/  credentials/  data/  → cartelle vuote (per uso futuro)
```

## ⭐ Da dove ripartire domani sul laptop

Apri **`docs/RIEPILOGO.md`** → hai tutto il piano in una pagina.
Poi usa **`docs/checklist-prenotazioni.md`** per prenotare. In sintesi:

1. **Bus andata:** Phoenicia 17:30 → Port Authority 21:40 (~$44) su trailways.com
2. **Hotel:** Hell's Kitchen / Midtown West (ostello ~$50–90, hotel ~$130–200)
3. **Ritorno mercoledì:** bus Trailways (NO Uber)

## 💻 Come aprirlo su Antigravity (laptop)

```bash
git clone https://github.com/giogori42-pixel/ai-agents-n8n.git
cd ai-agents-n8n
git checkout claude/airbnb-america-new-york-o6wvd8
```
Poi in Antigravity: **File → Open Folder** → scegli `ai-agents-n8n`.
Per ricevere aggiornamenti futuri: `git pull`.
