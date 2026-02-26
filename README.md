# qPCR standard curve in R

This repository contains an R Markdown document that reads triplicate Cq
values from qPCR standard wells and generates a standard curve of
log10(copies/µL) vs average Cq.

## Files

- `qPCR_Standard_curve.Rmd`  
  R Markdown script with step-by-step code and explanations.

- `qPCR_Standard_curve.md` (or `.html`)  
  Rendered version of the document for easy viewing on GitHub.

## Usage

1. Clone/download this repository.
2. Open `qPCR_Standard_curve.Rmd` in RStudio.
3. Update the file paths for:
   - `ydata` (triplicate Cq values, columns `y1`, `y2`, `y3`)
   - `xdata` (log10 copy number values, column `x`)
4. Click **Knit** to regenerate the standard curve report.
