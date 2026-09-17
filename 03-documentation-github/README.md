# Module 3 · Documentation as a Systemic Practice · GitHub & Version Control

> **This module includes a video tutorial.**
> [`github_tutorial.mp4`](github_tutorial.mp4).

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

## What must already be installed (prerequisites for the video)
Before following the video, you should have:
- **Anaconda Navigator** (Python, Jupyter Notebook, JupyterLab).
- A free **GitHub account** (https://github.com).
- **GitHub Desktop** (https://desktop.github.com), signed in with the *same* credentials as your GitHub
 account.

## Tutorial: Documenting by Doing Research: GitHub & Version Control
The video walks through the workflow below; the steps are written here so you can follow along and
re-do them without pausing.

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

## Watch
- [Reusing GLAM collections (Gustavo Candela)](https://clip.place/w/rVeo3U87Acns1JfXyxcxWK)
- [Tutorial: obtaining and building a dataset](https://clip.place/w/36p3UJ92DwaAozf4L5Q9um)

---
**Previous:** [Module 2 · Open Data](../02-open-data/README.md) · **Next:** [Module 4 · Documenting AI](../04-documenting-ai/README.md)
