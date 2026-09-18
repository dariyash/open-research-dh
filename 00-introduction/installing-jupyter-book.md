# Installing and Running the Course (Jupyter Book)

This short tutorial gets the course onto your computer and running. The course is organised as a
**Jupyter Book**, a set of linked pages and runnable notebooks. You can use it in two ways:

- **Read it** as a website (build the book once, open it in your browser), and/or
- **Run it** interactively, executing the notebooks yourself in JupyterLab.

Most learners do both: read a module, then open its notebook and run it. Follow the steps below once and you're set for the whole course.

---

## 1 · What you need first

- **Anaconda**: free, and it bundles everything you need (Python, Jupyter Notebook, JupyterLab). Install
 **[Anaconda Navigator](https://www.anaconda.com/products/navigator)**.
- **The course files**: from the course's GitHub repository (next step).
- *(Optional)* **Git**, handy for getting updates, but you can also download a ZIP without it.

No prior coding experience is needed.

---

## 2 · Get the course files

Choose **one** of these.

**Option A, Download a ZIP (simplest, no Git):**
1. Open the course repository on GitHub.
2. Click the green **Code** button > **Download ZIP**.
3. Unzip it somewhere easy to find, e.g. your `Documents` folder. You'll get a folder called
 `open-research-dh`.

**Option B, Clone with Git (best if you'll pull updates):**
```bash
git clone <course-repo-url>
```
This creates the same `open-research-dh` folder.

---

## 3 · Open a terminal in the course folder

You'll run a couple of commands. Open the right prompt for your system:

- **Windows:** open **Anaconda Prompt** (from the Start menu).
- **macOS / Linux:** open **Terminal**.

Then move into the course folder, type `cd ` (with a space) and drag the `open-research-dh` folder onto
the window to fill in its path, then press Enter:
```bash
cd path/to/open-research-dh
```

---

## 4 · Way 1, Run the notebooks in JupyterLab (recommended for beginners)

This is the interactive way, you open and run the notebooks yourself.

1. Open **Anaconda Navigator** and click **Launch** under **JupyterLab**
 *(or, in the terminal from step 3, simply type `jupyter lab` and press Enter).*
2. Your terminal will print lines and then **stop, showing a web address** that starts with
 `http://localhost:8888/…`. JupyterLab usually opens in your browser automatically; if it doesn't,
 **copy that `localhost` address and paste it into your browser.**
3. In the file panel on the left, open the module folders and run the notebooks **in order**:
 - `03-open-data/01_build_dataset.ipynb`
 - `04-documenting-ai/02_obtain_and_filter.ipynb`
 - `05-data-analysis/03_data_analysis.ipynb`
 - `06-data-enhancement/04_wikidata_enhancement.ipynb` *(optional)*
4. Run a notebook top to bottom with **Shift + Enter** on each cell (or **Run > Run All Cells**).

> The terminal window stays busy while JupyterLab runs, that's normal. Leave it open. To stop, close the
> browser tab and press **Ctrl + C** in the terminal.

Every notebook runs **without any API key** using the shipped sample data; add a key only when you want
live data (see the notebook's first cell).

---

## 5 · Way 2, Build the course as a website (to read it)

This turns the whole course into a browsable set of pages.

1. Install Jupyter Book (1st version) once:
 ```bash
 pip install "jupyter-book<2"
 ```
2. From inside the `open-research-dh` folder, build it:
 ```bash
 jupyter-book build .
 ```
3. When it finishes it prints the path to the built site, something like
 `_build/html/index.html`. **Open that file in your browser** (double-click it, or copy the path in).
 Use the sidebar to move through the modules.

> Rebuild any time with the same command after you change a file. The built site shows the notebooks'
> saved outputs; to *run* them, use Way 1.

---

## 6 · If something goes wrong

- **"`jupyter` / `pip` is not recognised"**: make sure you opened **Anaconda Prompt** (Windows) or that
 Anaconda's Python is active, then try again.
- **The `localhost` page doesn't open**: copy the full `http://localhost:8888/…` line from the terminal
 (including the `?token=…` part) and paste it into your browser.
- **A notebook cell errors**: read the message, check you ran the cells above it first (they run in
 order), adjust the configuration cell at the top, and re-run from the top.
- **A notebook can't find the data**: run the earlier notebooks first (they create the files the later
 ones use), or check the `datasets/` folder is present.
- **Still stuck?** Note the exact command and the exact error text, that's what you'll need to get help.

---

You're ready. Head to **Module 1** to begin, and open each module's notebook as you reach it.

---
**Previous:** [Welcome](welcome.md) · **Next:** [Module 1 · Open Humanities](../01-open-humanities/README.md)
