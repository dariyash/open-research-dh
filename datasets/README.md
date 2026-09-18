# Datasets

## `van_gogh_combined.csv` is the default dataset
The notebooks load the **combined** file below (no key needed).

## `van_gogh_combined.csv`, real Europeana export (combined name variants)
- **Source:** Europeana Search API · **Queries:** `CREATOR` across the variants
 `"Vincent van Gogh"`, `"Gogh, Vincent van"`, `"Vincent Willem van Gogh"`, `"van Gogh, Vincent"`
- **Accessed:** 2026-09-15 · **Records:** 334 (de-duplicated) · one provider (Marburg reproduction index)
 contributes ~300, which Module 4 sets aside.
- Re-generate any time by running the Module 3 notebook with an API key.

## `van_gogh_filtered.csv`, Module 4 output
34 works across 10 institutions, after setting aside the Marburg reproduction index. Feeds Module 5.

## `van_gogh_enhanced.csv` and `institution_wikidata_map.csv`, Module 6 output
The filtered set with each institution reconciled to a Wikidata Q-ID and its country, plus the reusable
institution-to-Wikidata lookup table.

## Name-variant evidence (why the combined set exists)
The Module 3 notebook queries several **name variants**, combines and de-duplicates them. The counts:
| Query | Records | Note |
|---|---|---|
| `CREATOR:"Vincent van Gogh"` | 24 | strict form; mostly one provider (Leuven) |
| `CREATOR:"Gogh, Vincent van"` | 309 | ≈300 from the Marburg reproduction index |
| `who:"Vincent van Gogh"` | 354 | creator/contributor; also Marburg-dominated |
