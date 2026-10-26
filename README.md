# Er op uit

Dit wordt de centrale repo voor meerdaagse uitstappen.  
We leggen per reis dezelfde onderdelen vast, zodat we na verloop van tijd kunnen zien wat we belangrijk vinden (locatie, hoteltype, eten, tempo, budget, enz.).

## Inhoud

Deze repo is opgezet met dezelfde indeling en website-opzet als `C:\git\reis-turkije`:

- MkDocs + Material thema
- content in `artefacten/`
- custom styling in `artefacten/assets/custom.css`
- publicatie-output in `site/`

Als start staat er een voorbeeldreis in: **4 dagen Limburg eind december**.

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
- `artefacten/index.md` — overzichtspagina van de reis
- `artefacten/dagen/` — dagplanning per dag
- `artefacten/hotels.md` — beschikbare hotels
- `artefacten/restaurants.md` — restaurants in de buurt
- `artefacten/sightseeing.md` — bezienswaardigheden
- `artefacten/praktisch.md` — praktische notities
