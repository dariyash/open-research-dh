# Module 6 · Data Enhancement *(optional)*

## Watch
- [Data Enhancement: principles, resources, Wikidata](https://clip.place/w/8EtqGKMfSi5imK6UVZoYeZ)

## Aim
Enrich a heritage dataset by linking it to **external authority data**, using **Wikidata**, the durable
fix for the name-variation problem you met in Module 3.

## Learning outcomes
By the end of this module you will be able to:
- Identify which entities in your dataset are suitable for enhancement with external authority data such
 as Wikidata.
- Locate and confirm matching Wikidata items for a sample of entities, using labels, descriptions, and
 statements to disambiguate similar entries.
- Integrate at least one type of Wikidata-derived enhancement (e.g. a **Q-ID**, standardised name, date,
 place, or organisation type) back into your dataset.
- Document the main steps of the enhancement in your workflow.

In Module 3, the *same* artist hid under many name strings (`"Vincent van Gogh"`, `"Gogh, Vincent van"`,
…). The lasting solution is to attach a **stable identifier**, a Wikidata **Q-ID**, to each entity. Two
records that share a Q-ID are the same person, however their names are spelled. That is **authority
control**, and it makes data linkable, comparable, and reusable.

## The steps (explained here; a notebook follows)
For now the stages are explained in writing so you understand each move before automating it.

**1. Choose entities to enhance.** Which columns describe identifiable entities?
- persons (artists, authors, collectors), places (cities, countries, museums),
 works (artworks, books), organisations (institutions, publishers).

**2. Match by hand first.** Take 2-3 entities and search them on Wikidata. When several items match,
**disambiguate** using the item's *label*, *description*, and *statements* (dates, role, place) together
with what you already know from your own data. Decide: *matched*, *uncertain*, or *not found*.

**3. Prepare the dataset.** Identify the entity column and add columns for the **Q-ID**, the **feature**
you want (e.g. birth year), and a **match_status** (matched / uncertain / not_found).

**4. Scale with checked code.** Draft matching + disambiguation code with AI (embedding the rules from
step 2), **test it on a ~50-item sample**, correct it, then apply it to the whole dataset. Record where
the code came from so learners can change variables and re-run.

**5. Document.** Note which entities you enriched, which feature(s) you added, how you handled multiple
candidates, and the counts (matched / uncertain / not found). "Uncertain" is an honest answer.

## Hands-on tutorial
**Notebook: [`04_wikidata_enhancement.ipynb`](04_wikidata_enhancement.ipynb)**, reconcile the
institutions in your dataset to Wikidata Q-IDs and add a feature (country, P17). No API key needed;
needs internet.

## Materials
- Dataset sample (from earlier modules).

## Recommended Reading
- Rother, Lynn, Max Koss, and Fabio Mariani. *Taking Care of History: Toward a Politics of Provenance Linked Open Data in Museums.* 19 December 2022. https://www.artic.edu/digital-publications/37/perspectives-on-data/25/taking-care-of-history-toward-a-politics-of-provenance-linked-open-data-in-museums.
- Fagerving, Alicia. "Wikidata for Authority Control: Sharing Museum Knowledge with the World." *Digital Humanities in the Nordic and Baltic Countries Publications* 5, no. 1 (2023): 222–39. https://doi.org/10.5617/dhnbpub.10665.

---
**Previous:** [Module 5 · Data Analysis](../05-data-analysis/README.md) · **Next:** [Module 7 · Reproducible Research](../07-reproducible-research/README.md)
