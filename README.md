# Final Project: Austin Animal Center Analysis

### About This Project

This repository contains an applied data science project analyzing intake and outcome data from the **[Austin Animal Center Intake & Outcome Data](https://data.austintexas.gov/)**.

The analysis focuses on **repeat intakes of dogs**, exploring:
* Which dogs are most likely to return to the shelter
* How intake type influences outcomes
* Patterns across breed, sex, and neuter status
* Seasonal and pandemic-related trends

This project was originally developed as part of **DACSS 601: Introduction to Data Science at the University of Massachusetts Amherst (Summer 2025)**.

**Repository Contents**
* Anjelica-Martinez-Final-Project-v2.qmd → Quarto source file with code, analysis, and write-up
* Anjelica-Martinez-Final-Project-v2.html → Rendered HTML report (self-contained with figures and tables)
* Data/ → Intake and outcome datasets from the City of Austin’s open data portal
* Figures/ → Exported plots used in the analysis

⸻

**Methods**

The project was written in R using the tidyverse and related packages. Key steps included:
1. Data Wrangling: Cleaning, merging, and preparing AAC intake and outcome datasets
2. Feature Engineering: Calculating age, assigning stay numbers, and joining intakes with outcomes
3. Exploratory Data Analysis: Identifying repeat visitors, examining breed/sex patterns, and analyzing seasonal shifts
4. Visualization: Communicating findings through clear plots and summary tables

⸻

**Key Results**
* Neutered males were more likely to have repeat intakes than expected
* Pit Bull Mixes, Labrador Retriever Mixes, and Chihuahuas made up a disproportionate share of repeat intakes
* Owner surrenders were more likely to end in adoption, while non-owner surrenders were more often returned to their original families
* The COVID-19 pandemic led to a sharp drop in repeat intakes in 2020, with only partial rebound since

⸻

**Implications**

Findings suggest that shelters may benefit from:
* Targeted retention support for owners of high-return breeds
* Post-adoption follow-up for neutered males to reduce returns
* Community-level interventions addressing housing and financial barriers to pet retention

⸻

**References**
* Austin Animal Center Data — City of Austin Open Data Portal
* Wickham, H., & Grolemund, G. (2017). R for Data Science. O’Reilly Media.
* Teetor, P. (2019). R Cookbook. O’Reilly Media.
* Miller, J. (2013). The Chicago Guide to Writing about Multivariate Analysis. University of Chicago Press.
* Patronek, G., Glickman, L., Beck, A., McCabe, G., & Ecker, C. (1996). Risk factors for relinquishment of dogs to an animal shelter. JAVMA, 209(3), 572–581.

⸻

**How to Run**
1. Clone this repository
2. Open the .qmd file in RStudio or Quarto
3. Run the code chunks to reproduce the analysis

```r
quarto render Anjelica-Martinez-Final-Project-v2.qmd
```

**Author**  
Anjelica Martinez  
Transitioning into AI & Behavioral Data Science  
[LinkedIn Profile](https://www.linkedin.com/in/anjelicamartinez/)
