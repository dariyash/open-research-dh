# Tutorial: Publishing Openly on Zenodo (FAIR and CARE)

A step-by-step written walk-through of the final stage of the course. You will check your project against
the FAIR principles, publish the dataset you created on Zenodo, earn a permanent DOI, and link everything
back to your GitHub project.

**Estimated time:** 30 to 45 minutes.

A video version of this tutorial is planned. Until it is available, this page is the complete guide and can
be followed on its own.

## Before you start

You should have:

- A **finished, reproducible project on GitHub** from the earlier modules.
- A free **Zenodo account** (you will create one during the tutorial if you do not have it yet).
- The **FAIR Data Self-Assessment Tool** (ARDC) open in a browser tab:
 https://ardc.edu.au/resource/fair-data-self-assessment-tool/
- The **created** dataset file you want to publish, ready on your computer (for the course example, this is
 the cleaned and enriched Van Gogh table, such as `van_gogh_enhanced.csv`).

## Why this matters

This is where the whole course pays off. You started by *finding* open data. Now you *contribute* open data
back, with a permanent, citable identifier that anyone can reuse.

Two ideas to keep in mind while you publish:

- **FAIR** means data that are **Findable, Accessible, Interoperable, and Reusable**. These four qualities
 make your work genuinely useful to others.
- **CARE** is the ethics companion to FAIR for heritage data: **Collective benefit, Authority to control,
 Responsibility, and Ethics**. FAIR is about technical openness; CARE is a reminder that "open" touches
 rights and communities.

## Step 1: Find your gaps with the FAIR self-assessment tool

Before publishing, see where your project stands.

1. Open the ARDC FAIR Data Self-Assessment Tool (link above).
2. Work through the questions honestly for your own project. For the Van Gogh example, ask: Is it findable?
 Does it have rich metadata and a persistent identifier? Is the licence clear?
3. Note the items where you score low. Typically these are "no persistent identifier yet" and "licence not
 stated".

Those low-scoring items are your concrete to-do list. Publishing on Zenodo fixes most of them.

## Step 2: Decide what to publish

Be clear about this before you upload:

> **Publish what you created, not what you downloaded.**

You publish the dataset **you created**: your cleaned, filtered, or enriched version, the subset you
extracted, the fields you added, the entities you reconciled to Wikidata. You do **not** re-publish the raw
source collection unchanged. If your data is simply the original, link to that source instead. Your work is
the *transformation*, and that is what matters both legally and as a scholarly contribution.

Rule of thumb: **one project equals one Zenodo record equals one DOI.** Several related files can live under
that single record.

## Step 3: Register and start an upload

1. Go to https://zenodo.org and sign in (create a free account if needed; you can sign in with GitHub or
 ORCID).
2. Click **New upload**.

## Step 4: Add your file

1. Drag your created dataset file into the upload area (for the course example, the filtered and enriched
 Van Gogh table).
2. Wait for the upload to finish before moving on.

## Step 5: Fill in the metadata (this is FAIR in action)

The metadata is exactly what makes your record *Findable* and *Reusable*, so take a little care here.

- **Resource type:** Dataset.
- **Title:** a clear, descriptive title.
- **Authors:** add yourself (and any collaborators). Linking your ORCID here is worthwhile.
- **Description:** what the data is and how it was made.
- **Keywords:** terms people would search for, such as Van Gogh, Europeana, cultural heritage, open data.

The richer this is, the easier your data is to find.

## Step 6: Choose a licence

The licence is a crucial, often-skipped field. It tells others what they are allowed to do with your data.

- Choose an open licence such as **CC0** (dedicate to the public domain) or **CC BY** (reuse with
 attribution).
- Make sure the licence you choose is consistent with the terms of the source institutions whose records you
 built on.

## Step 7: Link back to your GitHub project

Connect the data to the code so they point at each other.

1. Find the **Related identifiers** field.
2. Add your **GitHub repository URL** there.

## Step 8: Publish and get your DOI

1. Review the record once more.
2. Click **Publish**.
3. Your newly minted **DOI** appears at the top of the record.

Your dataset now has a permanent, citable home. Anyone can find it, cite it, and reuse it under the licence
you chose.

## Step 9: Re-assess with the FAIR tool

Run the FAIR self-assessment tool once more, now that you have published with good metadata and a DOI.

You should see the *Findable* and *Reusable* scores jump, because you added an identifier, metadata, and a
licence. That improvement is your evidence that the changes mattered.

## Step 10: Close the loop

Go back to your GitHub README and add the link to the published data.

1. Edit your GitHub README.
2. Paste the Zenodo DOI or record link.
3. Commit the change.

Now your repository, your code, and your published dataset all connect.

## What you have accomplished

This closes the loop of the whole course. You found open cultural-heritage data, documented and
version-controlled your work, transformed and enriched it, made it reproducible, and published it openly:
findable, accessible, interoperable, reusable, and shared responsibly. That is open scholarship from start
to finish.

## Self-check

- Why do you publish your *created* dataset rather than the original download?
- What makes a record *Findable* and *Reusable* in practice?
- Which licence did you apply, and why?
- Where in your project do the code and the published data now point at each other?

---
**Back to:** [Module 8 · Open Publishing and FAIR Principles](README.md)
