# Fibra · Guida di campo · versione 0.5 beta

Guida di consultazione **offline** per giuntisti di fibra ottica, in italiano tecnico. **È in prova:** segnala errori e problemi in [Issues](https://github.com/SidViral/Fibra-campo-for-dummies/issues).
244 schede su strumenti, sicurezza, apparati passivi e attivi, procedure, collaudo, ricerca guasti e riconoscimento dei produttori, con fonti citate.

**👉 Apri la guida: https://sidviral.github.io/Fibra-campo-for-dummies/**

> La guida è uno strumento di consultazione: non sostituisce il capitolato del committente, le norme applicabili, la formazione e le procedure aziendali. I valori marcati **[DA VERIFICARE]** vanno confermati sulla documentazione della commessa.

---

## Cosa contiene

| Sezione | Contenuto |
| --- | --- |
| 01 Glossario A–Z | Sigle e termini: FTTH, PON, CRO, PTE, OTDR, APC… |
| 02 Strumenti di lavoro | Giuntatrice, cleaver, OTDR, power meter, VFL, pulizia |
| 03 DPI e sicurezza | Laser, schegge, pozzetti, quota, cantiere stradale |
| 04 Infrastruttura e passivi | Cavi, fibre, colori, connettori, muffole, splitter |
| 05 Reti e apparati attivi | GPON/XGS-PON, OLT/ONT, DWDM, radio mobile, transceiver |
| 06 Alimentazione e continuità | −48 V DC, raddrizzatori, batterie, UPS |
| 07 Procedure operative | Dalla preparazione della postazione alla chiusura della muffola |
| 08 Collaudo e certificazione | Budget ottico, IL, ORL, OTDR bidirezionale, soglie |
| 09 Ricerca guasti | Eventi OTDR, macro/microcurvature, rotture, ghost |
| 10 Riconoscimento produttori | 55 famiglie di apparati, dal cliente al core |
| 11 Checklist e verbali | Liste di controllo e verbale da stampare |
| 12 Norme e bibliografia | ITU-T, IEC, CEI, ETSI, operatori, FOA, INAIL |

## Funzioni

- **Funziona senza connessione** dopo la prima apertura (o scaricando il file).
- **Ricerca** per sigla, parola o valore, tollerante ai refusi; **Invio** o il tasto **Cerca** della tastiera chiude la tastiera e porta al primo risultato. **Filtri** combinabili per sezione, categoria, tag, produttore, ambito e stato di verifica.
- **Pannello Colori**: tema come il dispositivo, chiaro, scuro o **Folle** (console VFD in stile Task Manager: sfondo nero e accenti luminosi); palette, alto contrasto, saturazione, bagliore, dimensione del testo, modalità **ADHD** (il colore cambia ogni N azioni) e **un colore per sezione**.
- **Stampa** della vista filtrata o dell'intera guida.
- **Installabile come app** su telefono e computer.

## Come aprirla

| Dove | Guida |
| --- | --- |
| iPhone, Android, Windows, macOS, Linux | [GUIDA-DISPOSITIVI.md](GUIDA-DISPOSITIVI.md) |
| Chrome, Edge, Opera, Brave, Vivaldi, Samsung Internet, Firefox, Safari | [GUIDA-BROWSER.md](GUIDA-BROWSER.md) |

In breve: apri il link sopra, poi **Aggiungi alla schermata Home** (telefono) o **Installa** (computer). Aprila una volta con internet: da lì funziona anche senza campo.

## Procedure tramite GitHub

### Scaricare solo la guida (un file)
1. In questa pagina clicca su **`index.html`** nell'elenco dei file.
2. In alto a destra premi l'icona **Download raw file** (freccia verso il basso).
3. Apri il file scaricato con un browser (doppio clic su computer).

Link diretto: [scarica index.html](https://github.com/SidViral/Fibra-campo-for-dummies/raw/main/index.html)

### Scaricare tutto il pacchetto
1. In questa pagina premi il pulsante verde **Code**.
2. Scegli **Download ZIP** ed estrai l'archivio.
3. Apri `index.html`. Gli altri file servono solo alla versione installabile online.

### Pubblicare una propria copia (fork)
1. Accedi a GitHub e premi **Fork** in alto a destra → **Create fork**.
2. Nella tua copia: **Settings** → **Pages** → **Source: Deploy from a branch** → **Branch: main / (root)** → **Save**.
3. Dopo 1–2 minuti il link compare in cima alla pagina Pages: `https://TUONOME.github.io/Fibra-campo-for-dummies/`.

Con un account gratuito il repository deve essere **pubblico**: chiunque abbia il link può vedere la guida.

### Pubblicare da zero (per chi gestisce il repository)
1. **+** in alto a destra → **New repository** → nome senza spazi → **Public** → **Create repository**.
2. Nel riquadro *Quick setup* clicca il link **uploading an existing file** (oppure vai a `…/upload/main`).
3. Trascina i 6 file (non la cartella) → attendi che compaiano tutti → **Commit changes**.
4. **Settings** → **Pages** → **Deploy from a branch** → **main / (root)** → **Save**.
5. Verifica che le tre icone `.png` si aprano dal link del sito: se ne manca una, la copia offline non si salva.

## Segnalare un problema

Apri una segnalazione in [Issues](https://github.com/SidViral/Fibra-campo-for-dummies/issues) indicando:

1. dispositivo e browser;
2. cosa hai fatto;
3. cosa ti aspettavi e cosa è successo;
4. nome o link (#) della scheda, e uno screenshot se puoi.

Per un dato tecnico errato indica anche la fonte corretta.

## File del repository

| File | A cosa serve |
| --- | --- |
| `index.html` | L'intera guida: dati, ricerca e grafica in un solo file |
| `manifest.webmanifest` | Nome, colori e icone dell'app installata |
| `sw.js` | Copia offline della guida sul dispositivo |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Icone dell'app |

### Pubblicare un aggiornamento

1. Carica il nuovo `index.html` (**Add file → Upload files → Commit changes**).
2. In `sw.js` aumenta la versione, per esempio `fibra-campo-0.5.0-beta` → `fibra-campo-0.6.0-beta`: così i dispositivi cancellano la copia offline vecchia.
3. Chi ha installato la guida riceve l'aggiornamento alla prima apertura con internet.

## Versioni

| Versione | Stato |
| --- | --- |
| 0.5 beta (11 ottobre 2026) | In prova con i tester. Le versioni 1.0–1.5 precedenti erano interne di sviluppo. |
| 1.0 | Uscirà quando: le 20 voci [DA VERIFICARE] sono confermate o tolte; la guida è provata su almeno 3 telefoni reali (iPhone e Android); le foto principali sono inserite; nessuna segnalazione grave è aperta. |

## Crediti

- Ricerca integrata: [Fuse.js](https://www.fusejs.io/) 7.1.0, licenza Apache 2.0 (testo completo nel file).
- Fonti delle schede: citate in ogni scheda e nella sezione 12.
