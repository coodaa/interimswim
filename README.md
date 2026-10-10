# Interimswim

Erster Entwurf der Website für Interimswim, ein mietbares Interimsschwimmbad (Becken 25 × 10 m) für Kommunen.

Statische Seite ohne Build-Schritt: `index.html` im Browser öffnen oder den Ordner bei Vercel, Netlify oder GitHub Pages veröffentlichen.

## Inhalt

- `index.html`: die Website, eine Seite, mit hellem und dunklem Farbschema
- `logo/`: Logo-Varianten als SVG, Schrift in Pfade umgewandelt
  - `schwimmbahn-pink.svg`, `schwimmbahn-blau.svg`: lange Variante mit Bahnmarkierung und Claim
  - `gestapelt-pink.svg`, `gestapelt-schwarzweiss.svg`: zweizeilige Variante
  - `kompakt-pink.svg`: einzeilig ohne Claim
  - `signet.svg`: Quadrat, dient auch als Favicon
- `fonts/`: Webschriften, lokal eingebunden (keine Verbindung zu Google Fonts)

## Vor der Veröffentlichung

- [ ] Platzhalter in `index.html` füllen: `[E-MAIL-ADRESSE]`, `[TELEFON]`, `[FIRMENNAME UND RECHTSFORM]`, `[MIETPREIS AB]`
- [ ] Impressum und Datenschutzerklärung ergänzen (`[IMPRESSUM]`, `[DATENSCHUTZ]`)
- [ ] Annahmen prüfen: Flächenbedarf rund 25 × 40 m, Variante mit tiefem Teilbereich
- [ ] `<meta name="robots" content="noindex">` aus `index.html` entfernen, wenn Suchmaschinen die Seite finden sollen

## Schriften

Unbounded, Hanken Grotesk und JetBrains Mono stehen unter der SIL Open Font License 1.1. Der Claim in den Logos ist in Montserrat gesetzt (ebenfalls OFL), dort aber nur als Pfad enthalten.
