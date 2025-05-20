# XgModel

**XgModel** is a machine learning project that predicts the Expected Goals (xG) value for football shots. xG is a statistical metric used to estimate the probability that a given shot will result in a goal, based on historical data and contextual features.

---

## What is xG?

Expected Goals (xG) is a widely used metric in football analytics. Each shot is assigned a value between 0 and 1, representing the likelihood of it resulting in a goal. For example, a shot with an xG of 0.2 means that, on average, 2 out of 10 such shots will be goals. The higher the xG value, the greater the chance of scoring.

---

## Project Objective

The main goal of this project is to train a model that can predict the xG value of a shot in football using historical data of similar shots. 

---


## Steps required

### 1. Requirements

- R (≥ 4.0.0)
- RStudio 
- Packages: `rmarkdown`, `knitr` & other pckgs that are mentioned in the Description file.

`install.packages(c("rmarkdown","knitr"))`

### 2. Clone or Download the Repository

To clone the repo just open the terminal & run this.

`git clone https://github.com/yvescnadoit/XgModel`

Or u can download it manually by ZIP file

### 3. Generating the Report

- Firstly set the working directory to this project Repo

  `setwd("path/to/XgModel/analysis/x-gmodel.rmd")`

- Then finally run the following command to generate the Markdown file.

 `rmarkdown::render("X-g_model.rmd",output_foramat = "github_document")`
