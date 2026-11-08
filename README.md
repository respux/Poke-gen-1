# Poke Gen 1

Leer-app voor kleine kinderen: alle 151 Pokémon van generatie 1, in volgorde of door elkaar.

- Naam voorlezen (Engelse stem), kreet afspelen
- Types (NL) en aanvallen (NL/EN via taalknop)
- Eén zelfstandig bestand: `index.html` (afbeeldingen en geluiden zijn ingebed), werkt ook offline

## Gebruik
Open `index.html` in een browser, of zet GitHub Pages aan (Settings → Pages → branch `main`, map `/root`).

## Bronnen
Sprites en kreten komen uit [PokeAPI/sprites](https://github.com/PokeAPI/sprites) en [PokeAPI/cries](https://github.com/PokeAPI/cries). Pokémon is een merk van Nintendo, Game Freak en The Pokémon Company; dit is een privé-leerproject zonder commercieel doel.
De Nederlandse aanvalsnamen zijn eigen vertalingen, niet de officiële namen.

## Bouwen
`src/` bevat de template en data. `build.py` verwacht de mappen `img/` (PNG-sprites `1.png`…`151.png`) en `mp3/` (kreten `1.mp3`…`151.mp3`) naast zich en schrijft de uiteindelijke HTML.
