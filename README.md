# Posit Academy — Python IDE Tutorial Files

Starter files for the Posit Academy **Foundations of Python for Data Science** IDE tutorials. These tutorials run in your browser but ask you to work with files in Positron alongside the tutorial.

**By accessing these Posit Academy course materials, you agree to Posit's [End User License Agreement](https://posit.co/about/eula/) and [Learning Services Agreement](https://posit.co/learning-services-agreement/).**

## Setup

Follow the **Set Up IDE Tutorials** tutorial on your course site for step-by-step instructions with screenshots. In short:

1. In a Positron session on Posit Workbench, click **New > New Folder from Git...** and paste this repository's URL:

   ```
   https://github.com/rstudio/academy-python-ide-tutorials.git
   ```

2. If Positron shows a **Restricted Mode** banner, click **Trust this folder** in the Console, then click **Trust**.

3. Open the **Terminal** tab and run this command to install the Python packages used by the tutorials:

   ```bash
   uv venv --allow-existing && uv pip install jupyter pandas palmerpenguins plotnine scikit-learn statsmodels
   ```

4. Click the interpreter button in the top right corner of Positron and select the Python whose name ends in **(uv: academy-python-ide-tutorials)**.

## Folder contents

| Folder | Starter file | Tutorial |
|--------|--------------|----------|
| `01-quarto-survey/` | `penguins.qmd` | Report with Quarto: author a data analysis document |
| `02-quarto-layouts/` | `sleep.qmd` | Quarto layouts: tabsets, columns, and margins |
| `03-quarto-parameterize/` | `tx-housing.qmd` (+ `data/`) | Parameterize a Quarto report |
| `04-quarto-slideshow/` | `storms.qmd` (+ `data/`) | Build a Quarto revealjs slideshow |

Each folder contains a starter `.qmd` file (and any data it needs) that you will edit as you follow along in the browser tutorial.
