# From Python to Machine Learning
<p align="center">
  <img src="assets/banner.png" alt="From Python to Machine Learning Banner">
</p>
A structured, notebook-first curriculum that takes you from Python fundamentals to statistical thinking — step by step, with zero random jumps.

---

## What this repository is

This is not a dump of notebooks.

It is a **designed learning path**:

Python → File Handling → Numerical Computing → Data Wrangling → Data Analysis → Statistics

Each module builds on the previous one.

---

## Curriculum Roadmap
<p align="center">
  <img src="assets/roadmap.png" alt="Curriculum Roadmap">
</p>
---

## Modules

### 01 — Core Python
Programming fundamentals: variables, control flow, data structures, functions.  
→ Open: `notebooks/01_core-python/`

---

### 02 — Working with Files
File I/O, CSV handling, modules, datetime essentials.  
→ Open: `notebooks/02_working-with-files/`

---

### 03 — NumPy
Arrays, indexing, vectorization, aggregations, randomness & reproducibility.  
→ Open: `notebooks/03_numpy/`

---

### 04 — Pandas
DataFrames, cleaning, transformation, groupby, merges/joins.  
→ Open: `notebooks/04_pandas/`

---

### 05 — Data Analysis
EDA workflow, missing values, outliers, feature engineering, visualization.  
→ Open: `notebooks/05_data-analysis/`
🚧 Visual demonstrations will be added as the module progresses.

---

### 06 — Statistics
Descriptive statistics, probability basics, distributions, hypothesis testing.  
→ Open: `notebooks/06_statistics/`
🚧 Statistical visualizations and applied examples coming soon.

---

## How to use this course
<p align="center">
  <img src="assets/repo-structure.png" width="700">
</p>

1. Start at **Module 01** and move in order.
2. Inside each module, run notebooks sequentially.
3. Avoid skipping modules — later topics assume earlier foundations.
4. If a notebook breaks, restart the kernel and run from the top.

---

## Setup (Beginner-Friendly)

Choose **one** of these options.

### Option A — Anaconda + Jupyter Notebook (Recommended for Beginners)

**Requirements**
- Download Anaconda (Windows x64): **[Anaconda3-2025.12-1-Windows-x86_64.exe](https://repo.anaconda.com/archive/Anaconda3-2025.12-1-Windows-x86_64.exe)**

**Steps**
1. Install Anaconda.
2. Open **Anaconda Navigator**.
3. Launch **Jupyter Notebook** (or JupyterLab).
4. Open this repository folder and start running notebooks.

Best for: beginners, offline learning, smooth setup.

---

### Option B — VS Code + Jupyter (Recommended for a Modern Editor)

**Requirements**
- Download VS Code: **[VS Code Download](https://code.visualstudio.com/download)**
- Install Jupyter extension: **[Jupyter Extension (VS Code)](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)**
- Install Python extension: **[Python Extension (VS Code)](https://marketplace.visualstudio.com/items?itemName=ms-python.python)**

**Steps**
1. Install VS Code.
2. Install the **Python** extension.
3. Install the **Jupyter** extension.
4. Open this repository folder in VS Code.
5. Open any `.ipynb` notebook and run cells.

Best for: students who prefer VS Code + notebooks.

---

### Option C — Google Colab (No Installation)

**Requirements**
- A Google account + browser (Chrome recommended)

**Steps**
1. Open Google Colab in your browser.
2. Upload a notebook (`.ipynb`) from this repo.
3. Run it online.

Best for: quick practice, low-end laptops, zero setup.

---

## Repository standards

- Notebook naming format: `XX_YY_topic-name.ipynb`
- Keep notebooks runnable top-to-bottom (no hidden state)
- Store datasets under `data/` (`raw/` and `processed/` recommended)
- Each notebook follows: **Concept → Examples → Practice**

---

## What’s next

Planned extensions:

### 07 — Machine Learning
Supervised learning fundamentals, regression, classification.

### 08 — Model Evaluation
Metrics, cross-validation, bias–variance, performance analysis.

### 09 — Projects & Case Studies
End-to-end applied data science workflows.

---

## VS Code Extensions (Data Science Essentials)

Install from **VS Code → Extensions** (`Ctrl + Shift + X`) or click the links below.

### Core (Recommended)
- **Python** — Run Python, manage environments, debugging.  
  [ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- **Jupyter** — Notebook support inside VS Code (`.ipynb`).  
  [ms-toolsai.jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- **Pylance** — Fast IntelliSense, type hints, better autocomplete.  
  [ms-python.vscode-pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)

### Data Exploration / Files
- **Data Wrangler** — GUI-based data cleaning + auto-generates pandas code.  
  [ms-toolsai.datawrangler](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.datawrangler)
- **Rainbow CSV** — Colorize CSV columns, align, query/filter CSV easily.  
  [mechatroner.rainbow-csv](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
- **Excel Viewer** — Preview Excel/CSV files inside VS Code.  
  [GrapeCity.gc-excelviewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer)

### Code Quality (Strongly Recommended)
- **Ruff** — Extremely fast Python linter (and formatter support).  
  [charliermarsh.ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)
- **Black Formatter** — Automatic, consistent Python formatting.  
  [ms-python.black-formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)

### Productivity (Nice to Have)
- **Error Lens** — Shows errors/warnings inline (hard to miss).  
  [usernamehw.errorlens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- **GitLens** — Better Git history, blame, diffs, file insights.  
  [eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- **Markdown All in One** — Markdown shortcuts + TOC + better writing workflow.  
  [yzhang.markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

### Databases (Optional but Useful)
- **SQLTools** — Run SQL queries inside VS Code with DB connections.  
  [mtxr.sqltools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
- **vscode-sqlite** — Explore and query SQLite databases.  
  [alexcvzz.vscode-sqlite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)

---

## License

MIT (or update `LICENSE` as needed)