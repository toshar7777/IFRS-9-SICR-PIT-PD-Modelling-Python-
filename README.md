# IFRS-9-SICR-PIT-PD-Modelling-Python-
Project Overview:-
This project implements an IFRS 9–compliant Significant Increase in Credit Risk (SICR) assessment framework using Python. The objective is to support Expected Credit Loss (ECL) staging decisions by converting Through-the-Cycle (TTC) Probability of Default (PD) into Point-in-Time (PIT) PDs, forecasting lifetime credit risk, and classifying exposures into Stage 1 and Stage 2.

Key Objectives:-
Build an IFRS 9–aligned SICR framework for retail credit portfolios
Convert annual TTC PDs to quarterly PD term structures
Transform TTC PDs into PIT PDs using macroeconomic sensitivity
Forecast lifetime borrower-level PDs
Perform loan-level staging classification based on PD deterioration

Methodology:-
1. TTC to Quarterly PD Conversion
Annual TTC PDs are converted into quarterly PDs using probability transformation techniques
Enables multi-period default risk projection required for lifetime ECL

2. PIT PD Computation (Vasicek Model)
Implemented the Vasicek single-factor credit risk model
Introduces systematic (macroeconomic) risk factors into PD estimation
Converts TTC PDs into forward-looking PIT PDs

3. PD Forecasting
Forecasted borrower-level PIT PDs across 20 future quarters
Supports forward-looking credit risk assessment and lifetime default estimation

5. Survival & Default Probability Metrics
Computed:
Survival probabilities
Marginal PDs
Cumulative default probabilities
These metrics form the foundation of Expected Credit Loss (ECL) calculation

5. SICR Logic & Staging
Designed quantitative SICR triggers using:
Relative PD increase
Absolute PD movement
Compared current vs. origination PDs
Classified loans into Stage 1 or Stage 2 based on deterioration

Analytics & Visualizations
PIT vs TTC PD comparison
PD migration and deterioration trends
Risk evolution across forecast horizons
Visual diagnostics support model validation, audit review, and portfolio risk monitoring.

Tools & Technologies
Python
Pandas, NumPy – data manipulation and calculations
Matplotlib – visualization
Jupyter Notebook

Key Concepts & Keywords:-
IFRS 9, ECL, SICR, PD Modelling, TTC to PIT, Vasicek Model, Credit Risk Analytics, Retail Lending, Staging, Model Validation, Regulatory Risk.

Author
Toshar Tarte
Credit Risk & Analytics Enthusiast
