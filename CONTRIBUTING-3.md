# Contributing to POLLY_DB.json

**This is an open community database of vintage Bluebird Polly Pocket sets (1989–1998).** Every collector who adds or corrects a set makes this better for everyone.

---

## How to add a set

1. Open `POLLY_DB.json`
2. Find the correct year section in the `sets` array
3. Copy an existing entry as your template
4. Fill in what you know — partial entries are welcome
5. Submit a Pull Request

---

## Entry format

```json
{
  "id": "YEAR-short-name",
  "name": "Exact Set Name",
  "aliases": ["common nickname", "alternate market name", "search terms people might type"],
  "year": 1992,
  "maker": "Bluebird",
  "shape": "Describe the compact shape and color",
  "sizeMm": "width x height x depth (optional but great to have)",
  "dolls": ["Polly", "Other character names"],
  "accessories": ["Item 1", "Item 2", "Item 3"],
  "commonlyMissing": ["The piece that is almost always gone", "Second most lost piece"],
  "pricePlay": 15,
  "priceGood": 38,
  "priceMint": 80,
  "rarity": "common",
  "lightUp": false,
  "batteryType": "1x AAA",
  "notes": "Collector context: what makes this set special, known variations, regional differences, tips for identifying fakes or parts."
}
```

**Required fields:** `id`, `name`, `aliases`, `year`, `maker`, `dolls`, `accessories`, `commonlyMissing`, `pricePlay`, `priceGood`, `priceMint`, `rarity`, `lightUp`

**Optional but valuable:** `shape`, `sizeMm`, `batteryType`, `notes`

---

## ID format

`YEAR-short-kebab-name` — use the year and a short unique slug.

Examples:
- `1989-country-cottage`
- `1993-schoolhouse`
- `disney-cinderella-enchanted-castle`

---

## Price guidance

Prices are **USD estimates based on recent eBay sold listings** — not gospel. Always verify with current sold listings before relying on these for buying/selling decisions.

| Field | Condition |
|-------|-----------|
| `pricePlay` | Play worn — heavy wear, may be incomplete |
| `priceGood` | Good used — typical secondhand, mostly complete |
| `priceMint` | Mint / MIB — complete, excellent condition or sealed |

---

## Rarity scale

| Value | Meaning |
|-------|---------|
| `common` | Easy to find on eBay anytime |
| `uncommon` | Takes some hunting, prices vary |
| `rare` | Hard to find complete, commands a premium |
| `very rare` | Seldom seen, high collector demand, $100+ |

---

## Aliases — why they matter

Aliases power the app's fuzzy search. A good alias list means a collector typing "beach cafe" finds `Polly's Cafe`, and someone typing "nancys wedding" finds `Bridesmaid Polly`. Include:

- Common nicknames
- Alternate market names (UK vs US packaging often differs)
- Misspellings people actually use
- Character names alone if the set is known by them

---

## Current completion status

| Year | Sets in DB | Known Total | Complete? |
|------|-----------|-------------|-----------|
| 1989 | 37 | 37 | ✅ |
| 1990 | 26 | 25 | ✅ |
| 1991 | 28 | 27 | ✅ |
| 1992 | 44 | 37 | ✅ |
| 1993 | 52 | 52 | ✅ |
| 1994 | 52 | 51 | ✅ |
| 1995 | 54 | 49 | ✅ |
| 1996 | 43 | 42 | ✅ |
| 1997–1998 | 1 | ~40 | 🔧 |
| Disney sets | 4 | ~20 | 🔧 |
 4 | ~20 | 🔧 |
 4 | ~20 | 🔧 |
 4 | ~20 | 🔧 |
 4 | ~20 | 🔧 |
 4 | ~20 | 🔧 |
 4 | ~20 | 🔧 |

**Most needed:** 1991, 1992, 1993 (52 sets — the biggest year!), and all Disney collaboration sets.

---

## What we especially need

- [ ] 1993 — we have 16 of 52. This is the biggest single year.
- [ ] 1994 full Pollyville range
- [ ] 1995–1998 coverage
- [ ] All Disney collaboration sets (Cinderella, Little Mermaid, Beauty and the Beast, Aladdin, 101 Dalmatians, and more)
- [ ] Accurate `sizeMm` measurements for any set
- [ ] `commonlyMissing` corrections from collectors who know their sets
- [ ] Regional variants — UK and US packaging names often differ significantly
- [ ] Price corrections — market moves fast, corrections welcome

---

## Research sources

- [onlypollypocket.com](http://www.onlypollypocket.com) — canonical set lists by year, doll ID
- [retrogeektoys.com](https://retrogeektoys.com/articles/vintage-polly-pocket-all-the-sets-and-where-to-get-them/) — set photos and descriptions
- [fabtintoys.com](https://www.fabtintoys.com/polly-pocket/) — pricing reference
- [pollypocket.collectionhero.com](https://pollypocket.collectionhero.com) — sold price data
- [vintagepollymobile.com](https://vintagepollymobile.com) — collector listings and condition notes
- eBay sold listings — always the most current pricing

---

## Questions or corrections?

Open an issue in the repo or submit a PR. If you spot a price that's way off, a missing alias, or a wrong doll name — please fix it. This database is only as good as the community behind it.

Thank you for helping build the most comprehensive vintage Polly Pocket database on the internet. 🏡✦
