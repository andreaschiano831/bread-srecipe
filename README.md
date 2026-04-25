# 🌾 Panificazione · Ricettario

Ricettario digitale per panificazione artigianale — Pane, Lievitati, Pizza, Focaccia.

## Deploy su Vercel via GitHub

### 1. Crea il repository su GitHub

```bash
git init
git add .
git commit -m "feat: ricettario panificazione v1"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/panificazione.git
git push -u origin main
```

### 2. Collega Vercel

1. Vai su [vercel.com](https://vercel.com) e accedi (o registrati gratuitamente)
2. Click **"Add New Project"**
3. Importa il repository GitHub `panificazione`
4. Vercel rileva automaticamente che è un sito statico — lascia tutte le impostazioni di default
5. Click **"Deploy"** ✓

Il sito sarà live su `https://panificazione.vercel.app` (o simile) in circa 30 secondi.

### Aggiornamenti futuri

Ogni `git push` sul branch `main` triggera automaticamente un nuovo deploy su Vercel.

```bash
git add .
git commit -m "add: nuova ricetta ciabatta"
git push
```

## Struttura file

```
panificazione/
├── index.html      ← app completa (self-contained)
├── vercel.json     ← config deploy Vercel
├── .gitignore
└── README.md
```

## Palette colori

| Token | Valore | Uso |
|---|---|---|
| `--cream` | `#F5F0E6` | Sfondo farina |
| `--gold` | `#8B5E1A` | Ambra crosta |
| `--gold2` | `#A8722A` | Miele dorato |
| `--terra` | `#8C4A2F` | Argilla forno |
| `--ink` | `#1A1410` | Testo profondo |
