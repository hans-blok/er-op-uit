# Er op uit

Dit wordt de centrale repo voor meerdaagse uitstappen.  
We leggen per reis dezelfde onderdelen vast, zodat we na verloop van tijd kunnen zien wat we belangrijk vinden (locatie, hoteltype, eten, tempo, budget, enz.).

## Inhoud

Deze repo is opgezet met dezelfde indeling en website-opzet als `C:\git\reis-turkije`:

- MkDocs + Material thema
- content in `artefacten/01/` (alleen deze map wordt gepubliceerd)
- custom styling in `artefacten/01/assets/custom.css`
- publicatie-output in `site/`

Website: <https://hans-blok.github.io/er-op-uit/>

Reis 01: **Limburg, di 29 december 2026 t/m za 2 januari 2027** (5 dagen, 4 nachten).

## Website lokaal draaien

```bash
pip install -r requirements-docs.txt
mkdocs serve
```

Open daarna `http://localhost:8000`.

## Build controleren

```bash
mkdocs build
```

## Structuur

- `mkdocs.yml` — navigatie en siteconfiguratie
- `artefacten/01/readme.md` — beschrijving van de reis (niet gepubliceerd)
- `artefacten/01/eisen.md` — eisen aan het verblijf
- `artefacten/01/index.md` — overzichtspagina van de reis
- `artefacten/01/dagen/` — dagplanning per dag
- `artefacten/01/hotels.md` — hotels en B&B's
- `artefacten/01/restaurants.md` — restaurants in de buurt
- `artefacten/01/sightseeing.md` — bezienswaardigheden
- `artefacten/01/praktisch.md` — praktische notities
