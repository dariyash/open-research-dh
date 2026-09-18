# Module 7 · Reproducible Research

## Watch
- [Reproducibility (theory)](https://clip.place/w/iM5LJwhVTzvuP4V1MkqJG8)

## Aim
Evaluate the reproducibility, openness, ethical implications, and potential for reuse of your research, and revise your project so someone else can run it from start to finish.

## Learning outcomes
By the end of this module you will be able to:
- Identify the key components of your workflow that must be documented for another person to reproduce it.
- Map your current workflow onto the **TIER** protocol.
- Conduct a self-audit and fix problems or missing documentation.
- Revise your repository structure and documentation so an external user can run the project end to end.

## Theory, what reproducibility really tests
The real test is simple: **could a stranger open your project and run it, with you not in the room?** If
yes, your documentation and structure are good enough. If not, you have found the gaps, which is the
point of auditing.

## The TIER protocol
**TIER Protocol 4.0** (https://www.projecttier.org/tier-protocol/protocol-4-0/) is a documentation
standard. Its idea is that a reproducible project has:
- a **clear folder structure**,
- **clear documentation files**, **clear command files** (the scripts/notebooks that do all the work), and
- everything gathered into one **reproducible compendium**.

A recommended layout:
```
original data/ processed data/ code (notebooks)/
documentation/ (README, metadata, data appendix) final report/
```

**How to implement it:** map each part of your project onto this structure; where something is missing, an undocumented script, a processing step written down nowhere, a missing data appendix, add it. Decide how to share any **large datasets** that cannot live on GitHub (a note pointing to the source, or a separate archive).

## Tutorial: checking your documentation with an open-research service
Australia's **ARDC FAIR Data Self-Assessment Tool** lets you rate your project against openness and
reuse criteria. You simply go through it and answer honestly; the walkthrough is woven into this text:
1. Open the tool (https://ardc.edu.au/resource/fair-data-self-assessment-tool/) and answer each question about *your* project.
2. Note every item you score low, those are your concrete to-fix list.
3. Fix what you can in your repository (better README, clearer folders, a data appendix), then re-assess.

## Guided task, peer testing

> Use the repo's [**reproducibility test template**](reproducibility-test-template.md) to record the test.

Try to find a partner. Your partner tries to run your project **while you explain nothing**, it must speak for itself.
They record: for each step, the expected outcome, what actually happened, and a status (works / partly /
fails), plus the biggest documentation gap, the biggest technical problem, and one thing done well. Then
you fix what they found.

## Self-check
- Which parts of your workflow are currently undocumented?
- Does your repository match the TIER folder structure?
- If a file is too large for GitHub, how will another person obtain it?

## Materials
- TIER Protocol 4.0, https://www.projecttier.org/tier-protocol/protocol-4-0/
- ARDC FAIR Data Self-Assessment Tool, https://ardc.edu.au/resource/fair-data-self-assessment-tool/

## Recommended Reading
- Joyeux-Prunel, Béatrice. "Digital Humanities in the Era of Digital Reproducibility: Towards a Fairest and Post-Computational Framework." *International Journal of Digital Humanities* 6, no. 1 (2024): 23–43. https://doi.org/10.1007/s42803-023-00079-6.
- Stapel, Rombert, and Ivo Zandhuis. "Linked Data for Modelling and Replicating the Knowledge Production Process in Data-Driven Humanities Research." *Digital Scholarship in the Humanities* 40, supplement 1 (January 2025): i100–i107. https://doi.org/10.1093/llc/fqae038.

---
**Previous:** [Module 6 · Data Enhancement](../06-data-enhancement/README.md) · **Next:** [Module 8 · Open Publishing](../08-open-publishing/README.md)
