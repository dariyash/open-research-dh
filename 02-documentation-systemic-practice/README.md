# Module 2 · Documenting as a Systemic Practice in Open Research

## Watch
- [Open Research & Documentation: what, when, how](https://clip.place/w/fjMb5CS2WSj9jfncSNoUpM)
- [Data-Driven Research Questions](https://clip.place/w/pdXXe2eysAnQHy6JT42T3k)

## Aim
Treat documentation as a **core research practice** that supports transparency, reproducibility, and
long-term reuse, and set up the tools that make it possible: a documented project on **GitHub** with
**version control**.

## Learning outcomes
By the end of this module you will be able to:
- Explain why documentation matters in open research and how it shapes what can be reproduced or reused.
- Create a research environment and document the main stages of the research process.
- Document research activities, data sources, methods, code, and decisions so another person can follow
 and assess the workflow.
- Construct the main steps of a reproducible research workflow and explain how they structure the research.

## Theory, documentation: what, when, how
Documentation is not paperwork you do at the end; it is **research you do as you go**. Good documentation
records, at each step: *what* you did, *why*, *where* the data and code came from, and *what you are
unsure about*. It is what turns a folder of files into a project someone else can trust and re-run.

A useful habit is to write the **research question** as data-driven and specific: not "tell me about
Van Gogh," but "how are Van Gogh's works distributed across the institutions that hold them?" A specific
question tells you which fields you need and what "done" looks like.

## What must already be installed (before you start)
Before following the tutorial, you should have:
- **Anaconda Navigator** (Python, Jupyter Notebook, JupyterLab).
- A free **GitHub account** (https://github.com).
- **GitHub Desktop** (https://desktop.github.com), signed in with the *same* credentials as your GitHub
 account.

## Tutorial: Documenting by Doing Research: GitHub & Version Control
The steps below walk through the workflow so you can follow along and re-do them without pausing.

**A. Create the repository**
1. On GitHub, create a **new repository**, simple lowercase name (e.g. `open-project-2026`), a
 one-sentence description, **Public**, tick *Add a README*.
2. Upload your dataset (keep files under ~25 MB; zip or split if larger).

**B. Give it a clear structure**
3. Create a `data/` folder by creating a file named `data/README.md` (the slash makes the folder), with a
 one-line description; commit.
4. Repeat for `notebooks/README.md`. (GitHub will not keep an empty folder.)

**C. Version control with GitHub Desktop + JupyterLab**
5. **Clone** the repository to your computer (File > Clone repository).
6. Open the repo in **JupyterLab**, create a notebook, add a Markdown cell stating its aim, rename it,
 and save.
7. In GitHub Desktop you will see the change: write a clear **commit message** ("checkpoint"), commit to
 `main`, then **push** ("send online"). Refresh GitHub to confirm.

> **Rule:** GitHub is for code and documentation, not large raw data. Commit processed outputs; keep the
> full raw file on your machine and describe it in the README.

## Task, exploring workflows
Find one published open project (e.g. from the GLAM Workbench) and describe:
- The **collection** and the **main question**; which part of the collection is used.
- The **workflow stages** (e.g. Query API > save raw > build table > clean > group & count > plot).
- The **analysis and visualisations** produced.
- How it is **documented and made reproducible** (folder structure, README, comments, environment).
- One thing that is especially clear, and one that could be better documented.

## Self-check
- Can you explain the difference between a *commit* and a *push*?
- Why keep raw data off GitHub, and how do you document it instead?
- What are the minimum folders your project repository should have?

## Recommended Reading
- Edmond, Jennifer, and Francesca Morselli. "Sustainability of Digital Humanities Projects as a Publication and Documentation Challenge." *Journal of Documentation* 76, no. 5 (2020): 1019–31. https://doi.org/10.1108/JD-12-2019-0232.
- Middle, Sarah. "A Documentation Checklist for (Linked) Humanities Data." *International Journal of Digital Humanities* 5, no. 2 (2023): 353–71. https://doi.org/10.1007/s42803-023-00072-z.
- Dunleavy, Patrick, and Timothy Monteath. "Documenting Research as You Go." Zenodo, 27 October 2022. https://doi.org/10.5281/zenodo.7670937.
- Perez-Riverol, Yasset, Laurent Gatto, Rui Wang, et al. "Ten Simple Rules for Taking Advantage of Git and GitHub." *PLOS Computational Biology* 12, no. 7 (2016): e1004947. https://doi.org/10.1371/journal.pcbi.1004947.

---
**Previous:** [Module 1 · Open Humanities](../01-open-humanities/README.md) · **Next:** [Module 3 · Resources for the Research: Open Data](../03-open-data/README.md)
