# Borgo Antico + popup

Questa è la pagina estratta dal file MHTML fornito, con il popup integrato.

## Configurazione
Modifica solo `popup-config.json`:
- `delayMs`: millisecondi prima dell'apertura (10000 = 10 secondi)
- `title`: titolo
- `textHtml`: testo
- `popupImage`: immagine popup
- `animationImage`: immagine che attraversa lo schermo
- `continueUrl`: URL del pulsante Continua
- `animationDurationMs`: durata animazione

## GitHub Pages
Carica tutto il contenuto del progetto nel repository, inclusa la cartella `assets`.
Poi: Settings -> Pages -> Deploy from a branch -> `main` -> `/ (root)` -> Save.

Importante: non testare facendo doppio clic su `index.html`, perché il browser può bloccare `fetch()` del JSON. GitHub Pages è il modo più semplice per provarlo.
