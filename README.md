# Going, Going, Gone! Calculator

A static calculator for the "Going, Going, Gone!" auction mode (Gold Shells). Thai UI.

- **Auction tab**: intel cards per round (Slot / Count / Valuation / Average Value device results, total value, notes), a 10-column lot grid where you drag to draw silhouettes (pick rarity or "?" and identify the item from candidates), a per-rarity value breakdown that fills unseen slots from the catalog, and a bid helper (instant-win thresholds R1 >2x, R2 >1.6x, R3 >1.3x, R4 >1.1x, R5 highest).
- **Catalog tab**: all 227 collectibles from the in-game Collectibles Index (name, rarity, size, price), read-only with filters.

Live: https://nattachai290.github.io/nte-go-gone/

`index.html` is the built page. `src/app.tpl.html` is the source with a `/*BUILTIN*/` placeholder for the catalog; `src/app.html` is the same page without the document wrapper.
