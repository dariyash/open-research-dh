# Module 4 · Documenting AI

## Watch
- [Documenting AI (theory)](https://clip.place/w/uHxioL2trhPoyVEUuggeNJ)

## Aim
Address AI as a **tool within the research workflow**, used deliberately, checked carefully, and
documented openly.

## Learning outcomes
By the end of this module you will be able to:
- Formulate and document prompts.
- Verify, revise, and correct AI-generated outputs.
- Record AI use, its limitations, and the human decisions taken.
- Identify and articulate risks related to bias, hallucination, privacy, copyright, and reproducibility.

## Theory, AI as a documented tool
In Module 3 you already ran code that was generated with an AI assistant. That is fine, **if** you can
say where it came from and you have checked it. This module makes that explicit.

If you are a complete beginner at coding, you can use **vibe-coding**: describe your goal in plain words,
ask an AI to draft the code, then read, run, and correct it. The skill is not writing code from memory, it is **prompting well and verifying the result**.

**A good prompt** typically:
- states the conditions (Python, in a Jupyter Notebook);
- is concrete about the input file, the column names, and the output you want, and where it should be saved;
- asks for short, commented code;
- sets limits ("do not change the original file");
- asks for a small printed **sample** so you can inspect the result.

**Checking is not optional.** AI can choose the wrong column, drop too much, invent a function, or
silently change your data. Always read the code, run it on a small piece, and confirm the numbers make
sense. In your prompt you can also *include* information to check against (expected columns, expected row counts).

This course cannot cover the whole of prompt engineering, look for additional sources to get more information.

### Important ideas
- **Authority control:** you can ask the AI to *propose* the likely name variants for a
 creator, then verify them against the data, rather than trusting the list.
- **Documentation:** record which model you used, the prompt, what you changed, and why.

## Hands-on tutorial
**Notebook: [`02_obtain_and_filter.ipynb`](02_obtain_and_filter.ipynb)**, filter the dataset from
Module 3 so it is fit for analysis. It uses AI-drafted filtering code that you *check*, and it makes a
**documented decision** (setting aside a reproduction index rather than deleting it silently).

## Task
Using the notebook, filter your own dataset for your question. In a Markdown cell, record: the prompt you
used, the model, what the code does, what you changed after checking it, and one risk you watched for
(bias, hallucination, privacy, copyright, or reproducibility).

## Self-check
- What aspects should every prompt make explicit?
- Give two ways AI-generated code can go wrong, and how you'd catch each.
- What must you record to make AI use in your project transparent?

## Recommended Reading
- Oberbichler, Sarah, and Cindarella Petz. "Working Paper: Implementing Generative AI in the Historical Studies." Zenodo, version 1, 25 February 2025. https://doi.org/10.5281/zenodo.14924737.
- Petz, Cindarella. *Augmented Historical Research in the Age of AI.* Slides to invited talk, Research Seminar "Humanities Data Science & Methodology," TU Darmstadt, 9 June 2026. https://doi.org/10.5281/zenodo.20622919.
- Ma, Rongqian, Xuhan Zhang, and Adrian Wisnicki. "Disclosing Generative AI Use in Digital Humanities Research." *Proceedings of the Association for Information Science and Technology* 62, no. 1 (2025): 1572–74. https://doi.org/10.1002/pra2.1471.
- Cwik, Jan Christopher. "Disclosure Is Not Documentation: An Open Science Framework for Documenting Generative AI Use in Scholarly Research and Publication Workflows." *Research Integrity and Peer Review* 11 (August 2026): 47. https://doi.org/10.1186/s41073-026-00245-8.
- Wills, Simon, Sanson T. S. Poon, Arianna Salili-James, and Ben Scott. "The Use of Generative AI for Coding in Academia." *Methods in Ecology and Evolution* 15, no. 12 (2024): 2189–91. https://doi.org/10.1111/2041-210X.14454.
- Feng, Yebo, and Yang Liu. "A Visionary Look at Vibe Researching." Version 2. Preprint, arXiv, 4 September 2026. https://doi.org/10.48550/ARXIV.2604.00945.

---
**Previous:** [Module 3 · Resources for the Research: Open Data](../03-open-data/README.md) · **Next:** [Module 5 · Data Analysis](../05-data-analysis/README.md)
