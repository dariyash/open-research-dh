# Open Research in the Digital Humanities

A **self-paced course** on how to make Digital Humanities research transparent, responsible,
reproducible, and reusable, taught through hands-on work with open **cultural-heritage data**,
**Jupyter Notebooks**, and open documentation.

Created by the **Humanities Data Science and Methodology (HDSM)** group and **DisLab**, with support
from the **HERMES** project. Course lead: **Dr Nadezhda Povroznik** (Institute of History, Technical
University of Darmstadt).

This course is the **Open Learnware Package** of the project *“Open Research in History, Cultural
Heritage and the Humanities: A Didactic Framework for Data Literacy and Open Research Practices.”* It
distils a practical course taught at TU Darmstadt into freely reusable materials, published openly via
Openlearnware and GitHub.

> **Learning by doing.** Follow the prepared **Van Gogh** example end to end, or bring your own dataset
> and research question, every notebook can be re-pointed at your own data by editing one configuration
> cell.

---

## What you'll be able to do

By the end of the course you will be able to:

- explain the principles of open research in the humanities (open data, open tools and methods,
 transparency, reproducibility, **FAIR**, and **CARE**);
- find, assess, and document open cultural-heritage datasets;
- develop and document a reproducible research workflow with **GitHub** and **Jupyter**;
- use AI as a **checked, documented** tool for obtaining and preparing data;
- clean, analyse, visualise, and interpret data honestly;
- enrich data by reconciling entities to **Wikidata** identifiers *(optional)*;
- audit a project for reproducibility with the **TIER** protocol;
- publish research outputs openly on **Zenodo** and check them against the **FAIR** principles.

## Who it's for

Students and early-career researchers in the Digital Humanities; humanities researchers who want to
improve their open-research skills; anyone working with cultural-heritage data; and teachers who want to
reuse open materials. **No prior coding experience is required**, where code appears, we generate it
with AI and learn to check it.

---

## Course structure

Eight modules, plus an introduction and a wrap-up. Every module is an elaborate README. The hands-on
modules add a **Jupyter Notebook** (or, for publishing, a **written tutorial**), and most modules also
link a **companion theory video** and, where available, **presentation slides**.

| # | Module | Format |
|---|--------|--------|
| 0 | [Welcome](00-introduction/welcome.md) · [Orientation](00-introduction/orientation.md) | README + video |
| 1 | [Open Humanities](01-open-humanities/README.md), principles & humanities context | README + video + slides |
| 2 | [Open Data](02-open-data/README.md), find & assess heritage datasets | README + notebook + video + slides |
| 3 | [Documentation & GitHub](03-documentation-github/README.md), document as you go; version control | README + video |
| 4 | [Documenting AI](04-documenting-ai/README.md), prompt, check, record AI use | README + notebook + video |
| 5 | [Data Analysis](05-data-analysis/README.md), clean, analyse, visualise, narrate | README + notebook |
| 6 | [Data Enhancement](06-data-enhancement/README.md) *(optional)*, enrich with Wikidata | README + notebook + video |
| 7 | [Reproducible Research](07-reproducible-research/README.md), audit with TIER | README + video |
| 8 | [Open Publishing](08-open-publishing/README.md), publish on Zenodo; FAIR | README + tutorial + video |
| 9 | [Course Wrap-up](09-wrap-up/README.md) | README |

Videos are companion theory pieces; the practical work lives in the notebooks and the Zenodo tutorial.

### The hands-on arc, one dataset, four notebooks

The practical notebooks share a **single dataset** and run in order:

**M2 [obtain](02-open-data/01_build_dataset.ipynb) > M4 [filter](04-documenting-ai/02_obtain_and_filter.ipynb) > M5 [analyse](05-data-analysis/03_data_analysis.ipynb) > M6 [enhance](06-data-enhancement/04_wikidata_enhancement.ipynb)** *(optional)*

Each notebook opens with a **configuration cell**, change the creator, the dataset, or the grouping
question, or load your own CSV, without touching the code below.

---

## Course content in detail

Each module combines a short written introduction, theoretical input (mostly as videos), and hands-on
work. Videos are linked on each module page under **Watch**. You can follow the modules in order, or use
a single module when you need support at a particular stage of your own project.

### 0 · Introduction
Orientation to the course: what it covers, how the self-paced path works, and the learning-by-doing
approach.
- **Watch:** [Introduction to the course](https://clip.place/w/575GcSPrbMLuZxFxuzLMYs)
- **Read:** [Welcome](00-introduction/welcome.md) · [Orientation](00-introduction/orientation.md) ·
 [Installing Jupyter Book](00-introduction/installing-jupyter-book.md)

### 1 · Open Humanities
The principles of open research and the humanities-specific context in which they apply.
- **Theory:** open data, open tools and methods, transparency, reproducibility; **FAIR** and **CARE**
 treated together; why the humanities need their own framing of openness (interpretive, heterogeneous,
 culturally sensitive materials).
- **Webinars:** [Open Research & Open Humanities (Nadezhda Povroznik)](https://clip.place/w/tSktamVHLAPTraEau1AAFG) ·
 [Open to Critical Interpretation (Andrea Wallace)](https://clip.place/w/iqntkKS2xQMFhzd1ggejTs)
- **Slides:** presentation decks for both webinars (in the module folder).

### 2 · Open Data
Finding, assessing, and obtaining a cultural-heritage dataset fit for a research question.
- **Theory:** where heritage data lives (museums, libraries and archives vs aggregators such as
 Europeana); access types (direct download, open API, API key, preview-only); fields, metadata, and
 licences; the name-variation problem that runs through the course (**authority control**).
- **Watch:** [Open Research & Documentation: what, when, how](https://clip.place/w/fjMb5CS2WSj9jfncSNoUpM) ·
 [Data-Driven Research Questions](https://clip.place/w/pdXXe2eysAnQHy6JT42T3k)
- **Hands-on:** [`01_build_dataset.ipynb`](02-open-data/01_build_dataset.ipynb), obtain a Europeana
 dataset across several name variants, combine and de-duplicate, and check its fitness.
- **Reference:** [Open Heritage Data source catalogue](02-open-data/open-heritage-data-sources.md).

### 3 · Documentation & GitHub
Documentation as a core research practice, and the version-control tools that make it possible.
- **Theory:** document as you go (what, why, where the data and code came from, what you are unsure of);
 writing a specific, data-driven research question; GitHub for code and documentation, not raw data; the
 commit and push workflow.
- **Watch:** [Reusing GLAM collections (Gustavo Candela)](https://clip.place/w/rVeo3U87Acns1JfXyxcxWK) ·
 [Tutorial: obtaining and building a dataset](https://clip.place/w/36p3UJ92DwaAozf4L5Q9um)
- **Hands-on:** a written walkthrough in the module page, create a repository, give it a clear structure,
 clone it, and make your first commit and push.

### 4 · Documenting AI
Using AI as a deliberate, checked, and openly documented tool within the workflow.
- **Theory:** prompting well and verifying the result; what a good prompt makes explicit; why checking is
 not optional; risks of bias, hallucination, privacy, copyright, and reproducibility; using AI to
 *propose* name variants, then verifying them (authority control).
- **Watch:** [Documenting AI (theory)](https://clip.place/w/uHxioL2trhPoyVEUuggeNJ)
- **Hands-on:** [`02_obtain_and_filter.ipynb`](04-documenting-ai/02_obtain_and_filter.ipynb), filter the
 dataset with AI-drafted code that you check, and record a documented decision (setting aside a
 reproduction index rather than deleting it silently).

### 5 · Data Analysis
Preparing, analysing, visualising, and interpreting heritage data honestly.
- **Theory:** the cycle of DH research (obtain, clean/transform, analyse, visualise, interpret, document,
 share); honest cleaning versus changing data; simple, clearly labelled visuals; writing a narrative that
 states patterns and limitations without over-claiming.
- **Hands-on:** [`03_data_analysis.ipynb`](05-data-analysis/03_data_analysis.ipynb), count records per
 institution (or country, type, year), make a bar chart, and write a short interpretation with a
 limitation.
- *No video for this module.*

### 6 · Data Enhancement *(optional)*
Enriching a dataset by linking it to external authority data with Wikidata.
- **Theory:** stable identifiers (**Q-IDs**) as the durable fix for name variation; choosing which
 entities to enhance; matching and disambiguating by label, description, and statements; recording a
 **match_status** (matched / uncertain / not found); scaling up with checked code.
- **Watch:** [Data Enhancement: principles, resources, Wikidata](https://clip.place/w/8EtqGKMfSi5imK6UVZoYeZ)
- **Hands-on:** [`04_wikidata_enhancement.ipynb`](06-data-enhancement/04_wikidata_enhancement.ipynb),
 reconcile institutions to Q-IDs and add each one's country (P17). No API key; needs internet.

### 7 · Reproducible Research
Auditing and revising the project so someone else can run it end to end.
- **Theory:** the real test of reproducibility (could a stranger run it with you not in the room?); the
 **TIER Protocol 4.0** (clear folder structure, documentation, command files, one reproducible
 compendium); how to share large datasets that cannot live on GitHub.
- **Watch:** [Reproducibility (theory)](https://clip.place/w/iM5LJwhVTzvuP4V1MkqJG8)
- **Do:** self-assess with the ARDC FAIR Data Self-Assessment Tool, then run a peer test using the
 [reproducibility test template](07-reproducible-research/reproducibility-test-template.md).

### 8 · Open Publishing & FAIR
Publishing outputs openly, earning a DOI, and checking the result against FAIR.
- **Theory:** DOIs and permanent citability; publish what you *created*, not what you downloaded; **FAIR**
 (Findable, Accessible, Interoperable, Reusable); **CARE** as the ethics companion to FAIR.
- **Watch:** [Open Publishing and FAIR (theory)](https://clip.place/w/kVnCPHDRXmjjj1v735ScGd)
- **Hands-on:** [`zenodo_tutorial.md`](08-open-publishing/zenodo_tutorial.md), a step-by-step guide to
 publishing on Zenodo (FAIR self-assessment, upload, metadata, licence, DOI, and linking back to GitHub).
 A video version is planned.

### 9 · Course Wrap-up
A recap of the full open-research arc, what the course did not cover, and the certificate of attendance.

---

## Getting started

### Prerequisites
- A laptop (Windows, macOS, or Linux).
- **[Anaconda Navigator](https://www.anaconda.com/products/navigator)**: Python, Jupyter Notebook, JupyterLab.
- A free **[GitHub](https://github.com)** account (set up in Module 3).
- *Optional* free API keys: **[Europeana](https://pro.europeana.eu/pages/get-api-keys)** for live data
 (the notebooks also run without one, using the shipped sample). Wikidata (Module 6) needs no key.

### Run the notebooks
```bash
# 1. Get the course
git clone https://github.com/dariyash/open-research-dh.git
cd open-research-dh

# 2. Open in Jupyter (via Anaconda Navigator > JupyterLab), then run, in order:
# 02-open-data/01_build_dataset.ipynb
# 04-documenting-ai/02_obtain_and_filter.ipynb
# 05-data-analysis/03_data_analysis.ipynb
# 06-data-enhancement/04_wikidata_enhancement.ipynb (optional)
```
Each notebook needs only `pandas`, `matplotlib`, and `requests` (all included with Anaconda).

### Build the course as a website (Jupyter Book)
```bash
pip install jupyter-book
jupyter-book build .
# open _build/html/index.html
```

---

## Repository layout

```
open-research-dh/
- README.md you are here
- _config.yml / _toc.yml Jupyter Book configuration
- BUILD_PLAN.md what each file is + status
- 00-introduction/ welcome · orientation · install guide
- 01-open-humanities/ README + presentation slides (PDF)
- 02-open-data/ README + 01_build_dataset.ipynb + source catalogue + slides (PDF)
- 03-documentation-github/ README
- 04-documenting-ai/ README + 02_obtain_and_filter.ipynb
- 05-data-analysis/ README + 03_data_analysis.ipynb
- 06-data-enhancement/ README + 04_wikidata_enhancement.ipynb
- 07-reproducible-research/ README + reproducibility-test-template.md
- 08-open-publishing/ README + zenodo_tutorial.md
- 09-wrap-up/ README
- datasets/ shipped example data (see below)
```

### Shipped datasets
| File | What it is |
|---|---|
| `datasets/van_gogh_combined.csv` | 334 records, several name variants combined (real Europeana export); the default the notebooks load |
| `datasets/van_gogh_filtered.csv` | 34 works across 10 institutions, after setting aside a reproduction index (Module 4 output) |
| `datasets/van_gogh_enhanced.csv` | the filtered set with each institution linked to a Wikidata Q-ID and its country (Module 6 output) |
| `datasets/institution_wikidata_map.csv` | institution-to-Wikidata lookup: Q-ID, label, and country (Module 6 output) |

All datasets are real Europeana exports, documented in [`datasets/README.md`](datasets/README.md).
Learners on the own-project path can just as well bring data from other open GLAM collections, including
the NFDI infrastructures **NFDI4Culture, NFDI4Objects, and NFDI4Memory**, since the notebooks accept any
CSV via their configuration cell.

---

## Reuse, licence & credits

This is an **open educational resource**, released under **CC BY 4.0** (or equivalent), the open
licence chosen for the project's Learnware Package, with code/notebooks under an open software licence
(e.g. **MIT**). Cultural-heritage records remain subject to their source institutions' terms. Materials
are intended to be **permanently available** through HDSM and TU Darmstadt facilities (Openlearnware and
GitHub).

- **Created by:** Humanities Data Science and Methodology (HDSM) & DisLab.
- **Supported by:** the HERMES project.
- **Course lead:** Dr Nadezhda Povroznik, Institute of History, Technical University of Darmstadt.
- **Part of:** *Open Research in History, Cultural Heritage and the Humanities: A Didactic Framework for
 Data Literacy and Open Research Practices*, whose other outputs are an expert symposium and a
 peer-reviewed teaching-and-methods paper.

Contributions and reuse are welcome, open an issue or adapt the materials for your own teaching.

*A certificate of attendance (acknowledging effort, not academic credit) is available on completion, see
the course platform.*
