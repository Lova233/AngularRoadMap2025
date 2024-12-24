# Angular Basics: Creiamo la Nostra Prima App! 🚀

## Cosa Faremo? 🎯
1. Creare la nostra app WeatherTask
2. Capire cosa ha creato Angular per noi
3. Vedere dove metteremo il nostro codice

## Creiamo l'App! 💻

Nel terminale, scriviamo:
```bash
ng new weather-task
```

Angular ci farà alcune domande:
- `Would you like to add routing?` → Scriviamo `y` (ci servirà dopo!)
- `Which stylesheet format would you like to use?` → Scegliamo `SCSS` (CSS con super poteri! 💪)

## La Nostra App: Una Casa con Tante Stanze 🏠

Quando Angular crea un progetto, è come costruire una casa. Vediamo le "stanze" principali:

```
weather-task/
├── src/                 # Qui scriveremo il nostro codice! 👩‍💻
│   ├── app/            # La stanza principale della nostra app
│   ├── assets/         # Immagini, icone, etc.
│   └── styles.scss     # Stili globali
└── package.json        # Lista degli "strumenti" che usiamo
```

## Le Parti Più Importanti 🎯

- `src/app/app.component.html` → Quello che vediamo nella pagina
- `src/app/app.component.ts` → Dove scriviamo cosa fa la nostra app
- `src/app/app.component.scss` → Come appare la nostra app

## Facciamo Partire l'App! 🚀

```bash
cd weather-task
ng serve
```

Apri il browser su `http://localhost:4200` e... 🎉 La tua prima app Angular è online!

## Cosa Abbiamo Imparato? 📝

- Come creare un progetto Angular ✅
- Dove si trova il nostro codice ✅
- Come far partire l'app ✅

## Task Finale: Salviamo il Nostro Lavoro! 💾

Ora che abbiamo creato la nostra app, salviamo tutto su Git:

```bash
# Inizializza Git se non l'hai già fatto
git init

# Aggiungi tutti i file
git add .

# Crea il primo commit
git commit -m "🎉 Prima app Angular creata!"

# Se hai già configurato GitHub
git push
```

Congratulazioni! 🎉 Hai:
- ✅ Creato la tua prima app Angular
- ✅ Capito la struttura base
- ✅ Salvato il tuo lavoro su Git

## Prossimi Passi 👣

Nella prossima lezione, cominceremo a modificare la nostra app per trasformarla in WeatherTask! 🌤️
