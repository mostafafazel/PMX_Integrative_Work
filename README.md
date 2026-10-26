# Integrative Group Work 1 — (PMX006)

A reproducible pharmacokinetic analysis of **Gajeevy**, an investigational compound with similarities to bictegravir, using data from a Phase Ia single-ascending-dose study (32 healthy volunteers; 10, 25, 50, and 100 mg oral doses).

## Project overview

The work includes: - Literature review of bictegravir and its clinical pharmacology - Data exploration, quality checks, and preparation in **R** - Non-compartmental analysis (**NCA**) using **PKanalix 2024R1** - Exploratory covariate analysis of NCA-derived PK parameters - Preliminary one- versus two-compartment model comparison

## Reproducibility

The main report is [`Integrative_Group_Work_1_simple.qmd`](Integrative_Group_Work_1_simple.qmd), which combines explanations, R code, tables, and figures. Input data and figure exports used by the report are referenced from the `Data/` and `Plots/` folders.

With **R**, the required R packages, and **Quarto** installed, render the report from the project directory:

``` bash
quarto render Integrative_Group_Work_1_simple.qmd --to html
```

Rendering requires the referenced input data and PKanalix outputs to be available at the paths used in the `.qmd` file. Only share study data in accordance with applicable access and privacy requirements.

## Authors

Daan Demeulenaere · Shanice Sokeng Tsake · Seyed Mostafa Fazel Hosein

*Advanced Master in Pharmacometrics — Integrative Group Work 1.*
