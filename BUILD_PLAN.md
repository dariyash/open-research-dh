# Open Research in the Digital Humanities, Build Plan

Course delivered as a **Jupyter Book**. Two videos (GitHub, Zenodo); everything else is an
elaborate README plus a Jupyter notebook.
Running example: **Vincent van Gogh**. Research question: how are the works distributed across
participating institutions? Design rule: every notebook has a **config cell** at the top so learners
can use their own dataset and question. Numbering follows **Modules.docx**.

## Repository structure

```
open-research-dh/                       the repo learners clone
- README.md                             repo landing: what this is, how to start
- _config.yml, _toc.yml                 Jupyter Book config (structural)
- requirements.txt, environment.yml     reproducible environment
- LICENSE, LICENSE-CONTENT.md           code (MIT) and content (CC BY 4.0)
- CITATION.cff                          how to cite the course
- BUILD_PLAN.md, REVIEW.md              internal working notes (not learner-facing)
- TEACHING_THREADS.md                   recurring lessons across modules
- 00-introduction/
  - welcome.md
  - orientation.md
  - installing-jupyter-book.md          install walkthrough
- 01-open-humanities/
  - README.md
- 02-open-data/
  - README.md                           dataset overview + resource list + explore task
  - open-heritage-data-sources.md       vetted source catalogue
  - 01_build_dataset.ipynb              obtain the dataset (anchor notebook)
- 03-documentation-github/
  - README.md
  - VIDEO_script_github.md              video 1 script
- 04-documenting-ai/
  - README.md                           prompt engineering + how to check AI
  - 02_obtain_and_filter.ipynb          filter the dataset for analysis
- 05-data-analysis/
  - README.md
  - 03_data_analysis.ipynb              clean, variables, visualise, short narrative
- 06-data-enhancement/
  - README.md                           Wikidata enrichment (optional)
  - 04_wikidata_enhancement.ipynb       reconcile entities to Q-IDs
- 07-reproducible-research/
  - README.md                           ARDC FAIR tool walkthrough + TIER how-to
  - reproducibility-test-template.md    peer reproducibility test template
- 08-open-publishing/
  - README.md
  - VIDEO_script_zenodo.md              video 2 script
- 09-wrap-up/
  - README.md
- datasets/
  - README.md
  - van_gogh_combined.csv               334 records, all name variants (no-key default)
  - van_gogh_filtered.csv               34 works across 10 institutions (feeds Module 5)
- unnecessary/
  - README.md
  - van_gogh_europeana.csv              old 24-record strict match, archived for reference
- data/raw/, data/processed/           created when the notebooks run (git-ignored)
```

## File status

| Module | File | Type | Status |
|---|---|---|---|
| Root | `README.md` | project landing page | done |
| 0 Intro | `00-introduction/welcome.md`, `orientation.md`, `installing-jupyter-book.md` | README | done |
| 1 Open Humanities | `01-open-humanities/README.md` | README | done |
| 2 Open Data | `02-open-data/README.md`, `open-heritage-data-sources.md` | README + catalogue | done |
| 2 Open Data | `02-open-data/01_build_dataset.ipynb` | notebook (anchor) | done |
| 3 Documentation/GitHub | `03-documentation-github/README.md` + `VIDEO_script_github.md` | README + video script | done |
| 4 Documenting AI | `04-documenting-ai/README.md` | README | done |
| 4 Documenting AI | `04-documenting-ai/02_obtain_and_filter.ipynb` | notebook (filter) | done |
| 5 Data Analysis | `05-data-analysis/README.md` + `03_data_analysis.ipynb` | README + notebook | done |
| 6 Data Enhancement | `06-data-enhancement/README.md` + `04_wikidata_enhancement.ipynb` | README + notebook (optional) | done |
| 7 Reproducible Research | `07-reproducible-research/README.md` + `reproducibility-test-template.md` | README + template | done |
| 8 Open Publishing | `08-open-publishing/README.md` + `VIDEO_script_zenodo.md` | README + video script | done |
| Wrap-up | `09-wrap-up/README.md` | README | done |
| Data | `datasets/van_gogh_combined.csv`, `van_gogh_filtered.csv` | shipped datasets | done |
| Infra | `requirements.txt`, `environment.yml`, `.gitignore`, `LICENSE`, `LICENSE-CONTENT.md`, `CITATION.cff` | reproducibility + licence | done |

## Still open (needs the author)
- Record the two videos from the scripts (GitHub, Zenodo).
- Fill in the real GitHub URL and confirm the copyright holder in `LICENSE` / `CITATION.cff`.
- Run Module 6 with internet to generate `datasets/institution_wikidata_map.csv` and
  `van_gogh_enhanced.csv`, then ship them as verified data.

## Build order used
01 obtain > 02 filter > 03 analyse notebooks, then M2/M4 READMEs, then M6, then M7, then the two
video scripts, then M1 and the wrap-up, then the install tutorial last.

## Teaching threads
See `TEACHING_THREADS.md`: Thread A (authority control and name variation) and Thread B (document
every decision), woven through Modules 2, 4, 5, 6, and 7.
