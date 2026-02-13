# 🏍️ Motorsykkelrute Planlegger

Avansert ruteplanner for Norges 17 nasjonale turistveier. Planlegg, rediger og del motorsykkelruter med interaktivt kart.

## ✨ Funksjoner

### Ruteplanlegging
- 📍 Last opp og vis GPX-filer
- 🛣️ Opprett nye ruter (klikk, start/slutt, frihåndstegning)
- ✏️ Legg til omveier med drabare punkter
- ↕️ Reverser ruter med ett klikk
- ☰ Dra-og-slipp for å endre ruterekkefølge
- 💾 Eksporter GPX under 5 MB (Google Maps-kompatibel)

### Kartfunksjoner
- 🗺️ Fire kartlag: OpenStreetMap, Satellitt, Terreng, Kartverket Topo
- ⛽ Bensinstasjoner langs ruten (Overpass API)
- 📍 POI-markører: utsiktspunkter, rasteplasser, severdigheter
- 📈 Høydeprofil med min/maks/stigning
- 🌀 Svingete vei-score med fargekoding (grønn → rød)
- 🏕️ Dagsetapper (~300 km/dag) med kartmarkører

### Brukervennlighet
- ⏱️ Estimert kjøretid med pauseforslag
- 🔗 Del rute via lenke eller kopier GPX
- 🌍 Importer ruter fra Google Maps-lenker
- 💾 Automatisk lagring av økt (localStorage)
- 📱 Responsiv design for mobil, tablet og desktop

## 🚀 Bruk

1. Besøk [https://pjerra.github.io/driveplan/](https://pjerra.github.io/driveplan/)
2. Last opp GPX-filer eller opprett nye ruter
3. Klikk på ruter for å zoome, dra for å endre rekkefølge
4. Slå på POI-markører (bensin, utsikt, raste, severdigheter)
5. Aktiver redigeringsmodus for å legge til omveier
6. Generer og last ned komplett rute som GPX

## 🛠️ Teknologi

- Pure HTML/CSS/JavaScript (ingen build-steg, ingen avhengigheter)
- [Leaflet.js](https://leafletjs.com/) for kartvisning
- [OSRM](https://project-osrm.org/) for ruteberegning
- [Overpass API](https://overpass-api.de/) for POI-data
- [Open-Elevation API](https://open-elevation.com/) for høydeprofil
- Kartlag fra OpenStreetMap, Esri, OpenTopoMap og Kartverket

## 📄 Lisens

MIT
