# Data2010 – Week 2 Reproducible Report

## How to run
1. Install R and R packages: `install.packages(c("rmarkdown"))`
2. Put/update `scores.csv` in the `data/` folder.
3. Render:  
   - RGui/Jupyter R: `rmarkdown::render("report.Rmd")`  
   - RStudio: Click **Knit**.
4. Output appears in `outputs/`.

## Files
- `report.Rmd` – R Markdown report.
- `data/scores.csv` – input data.
- `outputs/` – rendered reports (HTML/Word/PDF).

## Reproduce
Change `data/scores.csv` → render again → report updates automatically.