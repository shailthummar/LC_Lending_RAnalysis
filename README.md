# Credit Risk & Lending Analysis — LendingClub Case Study

## 📄 Project Description

This repository contains a comprehensive data-analysis and modeling project on public loan data from LendingClub. The project aims to analyze borrower behavior, assess credit risk factors, and build predictive insights to support data-driven lending and risk management decisions.
Key goals:
•	Understand loan performance and default patterns
•	Explore factors affecting credit risk (demographics, loan attributes, payment history, etc.)
•	Build a robust analytical workflow (from raw data to model-ready dataset)
•	Offer actionable insights for underwriting, risk stratification, and portfolio management
 
##  🧰 Tools & Technologies
•	R & RMarkdown (.Rmd) — for reproducible data analysis and reporting  
•	Data wrangling: dplyr, tidyr (or base R equivalents)  
•	Exploratory Data Analysis (EDA), statistical summaries, visualizations (histograms, correlation plots, risk factor distributions)  
•	Predictive modeling (logistic regression / classification models) — used to evaluate default risk factors  

## 🔍 Analysis Workflow and Methodology

#### 1. Data Loading & Cleaning
I imported and cleaned the LendingClub dataset by handling missing values, resolving formatting inconsistencies, and preparing core variables such as loan amount, term, interest rate, borrower demographics, credit indicators, and payment history. This ensured the dataset was accurate, consistent, and ready for deeper analysis.

#### 2. Exploratory Data Analysis (EDA)
I conducted an in-depth EDA to understand borrower and loan behavior across the portfolio. 
This included analyzing distributions of:   

    • Loan status (fully paid, charged-off, late)  
    • Interest rates and loan amounts  
    • Credit scores, income, and DTI ratios  
    • Payment performance across borrower segments  
    
  I also examined correlations between borrower attributes, loan characteristics, and default likelihood to identify early risk patterns.  

#### 3. Feature Engineering 

To improve predictive signal, I engineered several new features including:  
   
    • DTI ratio bands
    • Grouped loan grade classifications
    • Delinquency and late-payment indicators
    • Borrower risk buckets  
    
These enhanced variables enabled stronger modeling performance and more precise segmentation.

#### 4. Risk Modeling & Classification

I developed predictive models (logistic regression / classification approaches) to estimate the probability of loan default. 
Then, I evaluated model performance using key metrics such as AUC, accuracy, precision, recall, and used these results to validate the strength of risk-driving features.

#### 5. Insights & Business Recommendations

I translated modeling results and exploratory findings into actionable recommendations for underwriting and risk management. This included segmenting risk groups and outlining strategies to mitigate portfolio-level losses.
 
# 📈 Key Insights & Business Findings From My Analysis

    •	I identified several borrower and loan attributes significantly correlated with higher default risk — including high DTI ratios, lower credit grades (F–G), longer loan terms, and higher interest rates. These factors can inform stronger underwriting thresholds.
    •	I demonstrated that the loan portfolio can be segmented into clear risk tiers, each with distinct default probabilities. This segmentation supports more targeted credit strategies such as adjusted pricing or stricter verification.
    •	My analysis showed how data-driven credit-risk modeling can reduce expected losses by highlighting high-risk borrowers before approval.
    •	Overall, the insights I uncovered can help lenders improve risk-adjusted returns, optimize lending decisions, and strengthen portfolio resilience.
      risk-adjusted returns, optimize lending decisions, and strengthen portfolio resilience.


