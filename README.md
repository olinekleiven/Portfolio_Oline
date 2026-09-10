# Olines Design Portfolio

Live: https://portfolio-oline.vercel.app

## Kjøre lokalt

Siden er én fil (`index.html`) som laster React/Babel fra CDN og bygger siden i nettleseren — den **må** kjøres via en lokal server, ikke åpnes direkte som fil (dobbeltklikk / `file://` blokkerer CDN-scriptene i mange nettlesere og gir en ødelagt/utdatert visning).

```
npm install   # første gang
npm run dev
```

Åpne deretter http://localhost:5500 i nettleseren.

## Deploy

`main`-branchen er koblet til Vercel via GitHub. Alt som pushes til `main` deployes automatisk — ingen ekstra steg nødvendig:

```
git add .
git commit -m "..."
git push
```

Denne portfolioen er laget i samarbeid med Claude (AI fra Anthropic) som et eksperiment for å holde meg oppdatert på ny teknologi.

Jeg utforsket hvordan Claude kan brukes som et designverktøy — fra idé til ferdig kode — og ble imponert over hvor mye den faktisk får til. Alt fra layout og fargeskjema til HTML/CSS-struktur ble til gjennom en dialog med AI.

## Hva jeg lærte

- AI kan fungere som en effektiv designpartner, ikke bare en kodegenerator
- Det er fortsatt viktig å ha en idé om hva man vil — AI er et verktøy, ikke en erstatning for kreativ tanke
- Prosessen gikk mye raskere enn å bygge fra bunnen av på egen hånd

## Tech

- HTML & CSS (vanilla)
- Ingen rammeverk — enkelt og rent

---

*Laget av Oline Kleiven, 2026*
