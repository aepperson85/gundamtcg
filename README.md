# Gundam TCG Database

Community resource for the Gundam Card Game TCG. Browse tournament decks, search by card name or ID, and track your collection.

## Site structure

```
index.html          ← Landing page
decks/index.html    ← Deck browser (filter + search)
data/decks.json     ← 147 enriched tournament decks
data/cards.json     ← 917 cards from GD01–GD05 + ST/EB sets
```

## Phases

- **Phase 1 (live):** Deck browser with archetype/color/era filters and card-name search
- **Phase 2:** Collection builder (LocalStorage per browser)
- **Phase 3:** Deck matcher — see what you're missing to build a specific list
