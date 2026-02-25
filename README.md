# 🧠 NPC Translator – Il traduttore definitivo, gratuito e senza limiti

<p align="center">
  <img src="icons/icon-192.png" alt="NPC Translator Logo" width="128" height="128">
</p>

<p align="center">
  <strong>Traduci testi, documenti e immagini con la potenza del browser. Nessun server, nessun costo, nessun limite.</strong>
</p>

<p align="center">
  <a href="https://tuonome.github.io/npc-translator" target="_blank">🌐 Prova la demo live</a> •
  <a href="#-caratteristiche-principali">Caratteristiche</a> •
  <a href="#-installazione-pwa">Installa</a> •
  <a href="#-come-usare">Come usare</a> •
  <a href="#-tecnologie-utilizzate">Tecnologie</a>
</p>

---

## ✨ Caratteristiche principali

✅ **Traduzione testuale** con fallback su server gratuiti (Google Translate, MyMemory, Lingva) e supporto per oltre 10 lingue, incluse arabo, ebraico e yiddish (RTL).  
✅ **Input vocale** – parla e il testo viene trascritto automaticamente (Web Speech API).  
✅ **Output vocale** – ascolta la traduzione con sintesi vocale.  
✅ **OCR integrato** – estrai testo da immagini (JPG, PNG) usando Tesseract.js.  
✅ **Caricamento file** – PDF, EPUB, DOCX, TXT.  
✅ **Traduzione batch** – seleziona più file e ottieni un archivio ZIP con tutte le traduzioni.  
✅ **Cronologia illimitata** – tutte le traduzioni vengono salvate in IndexedDB, consultabili e ripristinabili.  
✅ **Glossario personalizzato** – definisci le tue traduzioni preferite per termini specifici.  
✅ **Tema chiaro/scuro** – adatto a qualsiasi ambiente.  
✅ **PWA pronta all'uso** – installabile su Windows, Android, iPhone come app nativa, funziona anche offline (grazie al service worker).  
✅ **Scorciatoie da tastiera** – `Ctrl+Invio` per tradurre, `Ctrl+Shift+C` per copiare, `Esc` per annullare.

---

## 📦 Installazione (PWA)

Puoi usare NPC Translator direttamente dal browser all'indirizzo del tuo repository GitHub Pages.  
Per installarlo come app su dispositivi:

### Android (Chrome)
1. Apri il sito con Chrome.
2. Tocca i tre puntini in alto a destra.
3. Seleziona **"Aggiungi a schermata Home"**.
4. Segui le istruzioni.

### iPhone (Safari)
1. Apri il sito con Safari.
2. Tocca l'icona **Condividi** (il quadrato con la freccia).
3. Scorri verso il basso e tocca **"Aggiungi a Home"**.
4. Conferma.

### Windows / macOS (Edge, Chrome)
- Nella barra degli indirizzi compare un'icona di installazione (`+`). Cliccala e segui la procedura.

L'app funzionerà offline e avrà un aspetto nativo, senza barre degli indirizzi.

---

## 🚀 Come usare

1. **Traduzione veloce** – incolla il testo nella colonna di sinistra, seleziona le lingue e clicca **Traduci**.
2. **Voce** – clicca il pulsante 🎤 sotto l'input e inizia a parlare.
3. **File** – trascina uno o più file nell'area gialla. L'app estrae il testo e lo inserisce automaticamente nell'input.
4. **OCR** – clicca il pulsante 📷 sotto l'input e seleziona un'immagine. Il testo riconosciuto verrà aggiunto.
5. **Cronologia** – nella sezione in basso puoi rivedere le ultime traduzioni e cliccarle per ripristinarle.
6. **Glossario** – aggiungi termini personalizzati; dopo la traduzione verranno sostituiti automaticamente.
7. **Batch** – clicca **Batch**, seleziona più file, e dopo l'elaborazione scaricherai un file ZIP con tutte le traduzioni.

---

## 🛠️ Tecnologie utilizzate

- **HTML5 / CSS3** – con variabili CSS per il tema dinamico.
- **JavaScript (ES6)** – moduli, async/await, IndexedDB.
- **PWA** – manifest.json e service worker per funzionalità offline.
- **Librerie esterne**:
  - [PDF.js](https://mozilla.github.io/pdf.js/) – estrazione testo da PDF.
  - [JSZip](https://stuk.github.io/jszip/) – lettura EPUB e creazione ZIP.
  - [Mammoth.js](https://github.com/mwilliamson/mammoth.js) – estrazione da DOCX.
  - [Tesseract.js](https://tesseract.projectnaptha.com/) – OCR da immagini.
  - [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) – input/output vocale.
- **API di traduzione gratuite**:
  - Google Translate (endpoint non ufficiale)
  - MyMemory (con limite, ma ampio)
  - Lingva (istanza pubblica di un proxy)

---

## 📁 Struttura del progetto
