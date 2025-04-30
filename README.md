# 📊 Race and Economic Opportunity Poster

This project explores how racial and socio-economic factors affect economic mobility in the United States, using data from Opportunity Insights.

## 📌 Research Summary
- **Data Source**: U.S. Census Public Use Microdata from [Census Public Use Data]([https://opportunityinsights.org/](https://www.census.gov/programs-surveys/ces/data/public-use-data/race-and-economic-opportunity-data-tables.html))
- **Objective**: Evaluate the extent to which parental income percentile and the size of the Black population predict income rank in adulthood
- **Methods Used**:
  - Descriptive analysis with ECDF and histograms
  - Correlation matrix of key variables
  - Predictive modeling using K-Nearest Neighbors (KNN)
- **Key Tools**: R, dplyr, ggplot2, caret, posterdown

## 📈 Key Findings
- Higher Black population count is strongly associated with lower mobility among Black males from single-parent households.
- Parental income percentile is a strong predictor of adult income rank across races.
- KNN model (k = 5) achieves an R² of 0.962 and RMSE of 1.078.

## 🗂️ File Structure

| File | Description |
|------|-------------|
| `Research_Poster.Rmd` | R Markdown source code for the poster |
| `Research_Poster.html` | Rendered HTML poster (requires posterdown) |
| `table_1.csv` | Cleaned dataset used in the analysis |
| `packages.bib` | Bibliography for packages used |
| `README.md` | This summary file |

## 🚀 Reproducing the Poster

To render the poster in R:

```r
# Install posterdown if needed
devtools::install_github("brentthorne/posterdown")

# Render
rmarkdown::render("Research_Poster.Rmd")
```

Make sure all necessary packages (`dplyr`, `ggplot2`, `caret`, etc.) are installed.

---

**Author**: Byeolha Kim  
📧 bk4098a@american.edu  
🔗 [GitHub Profile](https://github.com/bk4098a)
