# Module 2 · Resources for Research: Open Data

## Aim
Introduce open data in the humanities and build the skill of finding, assessing, and obtaining a
cultural-heritage dataset suitable for a research question.

## Learning outcomes
By the end of this module you will be able to:
- Explain what open data means in the humanities and why it is useful for historical and heritage research.
- Identify relevant platforms and repositories that provide open cultural-heritage datasets.
- Identify and select suitable heritage datasets for a research question.
- Find and download a small open dataset from a digital heritage platform.
- Inspect and describe a dataset's structure (formats, fields, metadata).
- Decide whether a dataset is suitable for a research question.

## Where heritage data lives
Open heritage data comes from two broad kinds of source:

- **Museums, libraries and archives** publish their own collections, e.g. the **MET Museum**,
 **Smithsonian**, **Rijksmuseum**.
- **Aggregators** pool many institutions in one place, e.g. **Europeana** and the **European Data**
 portal.

How you get the data matters as much as where it is. For each source, ask:
- Is there a **direct download** (CSV / JSON / ZIP), an **open API**, an **API that needs a key**, or is
 it **preview-only**?
- What **fields and metadata** are provided, and how complete are they?
- What **licence** applies (e.g. CC0, or rights that vary per item)?

A fuller, vetted list of sources, with access type, formats, and licences, is kept in the course's
[**Open Heritage Data source catalogue**](open-heritage-data-sources.md).

## Explore task
Choose **two** sources, one museum and one aggregator, and, for each, write two or three sentences:
- How easy was it to reach the data, and in what form (download / API / key / preview)?
- What fields does a single record contain, and how complete do they look?
- Could this source answer a question you care about? Why or why not?

## Hands-on tutorial
**Notebook: [`01_build_dataset.ipynb`](01_build_dataset.ipynb)**, obtain a dataset from Europeana.

This notebook teaches a lesson that recurs across the course: the
*same* creator is catalogued under several different names, so a single search could miss most of
the data. Searching `"Vincent van Gogh"` finds 24 records; the catalogued variant `"Gogh, Vincent van"`
finds 309. The notebook searches a **list of name variants**, combines and de-duplicates them, then
checks whether the result is fit for the question, including a critical look at whether one provider
dominates. (The durable fix for name variation, Wikidata identifiers, arrives in Module 6.)

## Guided task
Watch the tutorial, run the notebook, and **obtain a dataset** (the Van Gogh example, or your own
creator/collection). Then **document** it: source, query used (including which name variants), date
accessed, licence, fields kept, and one sentence on fitness for your question.

## Self-check
- Can you name a museum source and an aggregator, and say how you'd get data from each?
- Why can two searches for the "same" artist return very different numbers of records?
- What would make a dataset *unfit* for your research question?

## Watch
- [Open Research & Documentation: what, when, how](https://clip.place/w/fjMb5CS2WSj9jfncSNoUpM)
- [Data-Driven Research Questions](https://clip.place/w/pdXXe2eysAnQHy6JT42T3k)

## Slides
- [Candela presentation slides](slides_Gustavo_Candela.pdf)

---
**Previous:** [Module 1 · Open Humanities](../01-open-humanities/README.md) · **Next:** [Module 3 · Documentation & GitHub](../03-documentation-github/README.md)
