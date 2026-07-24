# Posit Academy — Python IDE Tutorial Files

Starter files for the Posit Academy **Foundations of Python for Data Science** IDE tutorials. These tutorials run in your browser but ask you to work with files in your IDE (Positron or RStudio) alongside the tutorial.

**By accessing these Posit Academy course materials, you agree to Posit's [End User License Agreement](https://posit.co/about/eula/) and [Learning Services Agreement](https://posit.co/learning-services-agreement/).**

## Setup

Clone this repository in a Terminal on Posit Workbench:

```bash
git clone https://github.com/rstudio/academy-python-ide-tutorials.git
```

Then install the Python packages used by the tutorials:

```bash
pip install pandas plotnine palmerpenguins
```

## Folder contents

| Folder | Starter file | Tutorial |
|--------|--------------|----------|
| `01-quarto-survey/` | `penguins.qmd` | Report with Quarto: author a data analysis document |
| `02-quarto-layouts/` | `sleep.qmd` | Quarto layouts: tabsets, columns, and margins |
| `03-quarto-parameterize/` | `tx-housing.qmd` (+ `data/`) | Parameterize a Quarto report |
| `04-quarto-slideshow/` | `storms.qmd` (+ `data/`) | Build a Quarto revealjs slideshow |

Each folder contains a starter `.qmd` file (and any data it needs) that you will edit as you follow along in the browser tutorial.
