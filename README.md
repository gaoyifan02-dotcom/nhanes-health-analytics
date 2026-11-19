# NHANES Health Analytics

Reproduction workspace for the NHANES analysis from the University of Virginia Active Analytics team capstone. It explores associations of diet and physical activity with BMI, waist circumference, cholesterol, and fasting glucose. These are observational analyses.

## Run the analysis

1. Extract the project folder and open `capstonefinalscript.Rmd` in RStudio.
2. In the R console, run `install.packages(c("rmarkdown", "knitr", "survey", "car"))`.
3. Click **Knit** to generate the HTML report. Keep the R Markdown file next to the `data` folder.

The input is a processed extract supplied with the project (6,751 participant rows and 143 columns). The original data preparation scripts are not included. The UVA survey is separate and is not included in this project.

## Reproduction status

The input path and required columns were checked. The R Markdown file has not been knitted in this workspace. The analysis preserves the original model settings; check the sampling weights for the fasting glucose analysis and compare results against the original report before citing them.
