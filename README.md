# Registro Spese - versione HTML/PWA

Applicazione personale senza backend. Tutti i dati sono memorizzati localmente nel browser tramite IndexedDB.

## Avvio locale
Non aprire `index.html` con doppio clic se vuoi testare service worker/PWA. Avvia un server statico, per esempio:

```bash
python3 -m http.server 8080
```

Poi apri `http://localhost:8080`.

## Pubblicazione
Puoi pubblicare l'intera cartella su GitHub Pages o qualunque hosting statico HTTPS.

## Installazione su iPhone
Apri l'indirizzo in Safari > Condividi > Aggiungi alla schermata Home.

## Dati
- Nessuna autenticazione.
- Nessun server.
- Nessuna sincronizzazione fra dispositivi.
- Backup JSON consigliato regolarmente.
- CSV pensato per analisi ed Excel.
