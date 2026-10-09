# Retail Sales and Discount Strategy Effectiveness

**Module:** 2101 ST – Probability and Statistics
**Institution:** Victoria University, Faculty of Science and Technology
**Examiner:** Dr. Ronald Bbosa
**Group:** 6
**Software:** jamovi (version 2.7)

## About this project

This repository holds the jamovi project files and screenshots for our Group 6 coursework report. We analysed the Superstore Sales dataset (N = 8,399) to answer two questions:

1. Is customer segment associated with the product category purchased?
2. Does discount usage differ across customer segments?

Both were tested with chi-squared tests of independence at α = .05.

## Key results

| Analysis | Result | Effect size |
|---|---|---|
| Customer segment × product category | χ²(6, N = 8,399) = 6.71, p = .349 | Cramér's V = .020 (negligible) |
| Fisher's exact test (Monte Carlo) | p = .351 | n/a |
| Customer segment × discount usage | χ²(3, N = 8,399) = 1.89, p = .596 | Cramér's V = .015 (negligible) |

Neither association was statistically significant, so the broad customer segments do not meaningfully predict product category or discount usage in this dataset.

## Repository contents

| File / folder | Description |
|---|---|
| `sales.omv..omv` | The original jamovi project file. Open it in jamovi to see the data and analyses. |
| `index.html` | The analysis results as a web page. |
| `01 empty` to `05 empty`, `02 contTables`, `04 contTables` | The jamovi analyses (the contingency tables), with one plot image. |
| `data.bin`, `strings.bin`, `metadata.json`, `xdata.json`, `meta` | Internal jamovi data and settings files. |
| `screenshots/` | Screenshots of the data and analysis output in jamovi. |

The extracted files are the contents of the `.omv` file, which is a zip archive.

## How to open the analysis

1. Install jamovi from [jamovi.org](https://www.jamovi.org).
2. Download `sales.omv..omv` from this repository.
3. Open it in jamovi (**File → Open**).

 
