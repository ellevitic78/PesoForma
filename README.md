# 🥇 XAU/USD Analyzer — PWA

App standalone per Android con dati live, analisi MTF, scalping e notifiche in background.

## Setup in 5 minuti (GitHub Pages — gratis)

### 1. Crea repository GitHub
1. Vai su [github.com](https://github.com) → **Sign up** (gratuito)
2. Clicca **"New repository"**
3. Nome: `xau-analyzer`
4. Seleziona **Public**
5. Clicca **"Create repository"**

### 2. Carica i file
1. Clicca **"uploading an existing file"**
2. Trascina **tutti i file** di questa cartella:
   - `index.html`
   - `sw.js`
   - `manifest.json`
   - `icon-72.png`
   - `icon-192.png`
   - `icon-512.png`
3. Clicca **"Commit changes"**

### 3. Attiva GitHub Pages
1. Vai su **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** → **/ (root)**
4. Clicca **Save**
5. Dopo ~1 minuto l'URL sarà: `https://TUONOME.github.io/xau-analyzer/`

### 4. Installa come app sul telefono
1. Apri Chrome sul telefono
2. Vai all'URL `https://TUONOME.github.io/xau-analyzer/`
3. Tocca i **3 puntini** → **"Aggiungi a schermata Home"**
4. Conferma → l'app appare come icona dorata sul desktop!

### 5. Attiva notifiche background
1. Apri l'app
2. Inserisci le tue API key (Twelve Data + opzionale Anthropic)
3. Tocca **🔔** in alto a destra
4. Tocca **"Attiva"**
5. Consenti le notifiche quando richiesto
6. ✅ Riceverai alert anche con il telefono in tasca!

## Alert disponibili
- 📍 Prezzo vicino a Pivot / R1 / S1
- ⚠️ RSI overbought (>70) o oversold (<30)
- ⚡ Spike di volatilità (>1.8x ATR)
- 📡 Segnale anticipatore DXY/EUR/USD
- 🔔 Alert prezzo personalizzato (sopra/sotto $X)

## Note
- Il monitoraggio gira ogni **5 minuti** (rispetta il rate limit Twelve Data free: 800 req/giorno)
- Su Android Chrome le notifiche funzionano anche con lo schermo spento
- Su iOS Safari le PWA non supportano push notification (limitazione Apple)
