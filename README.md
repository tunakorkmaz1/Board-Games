# Predicting Board Game Ratings (Data Science Project)

**Personal Portfolio Repository**  
Originally completed as a group project for a statistics/data science course in Spring 2025

## Project Summary
This project applies modeling and exploratory data analysis to predict average
user ratings of board games on BoardGameGeek (BGG). Using a dataset of 21,000+ games,
I engineered features from gameplay attributes and user engagement metrics and built
interpretable regression models to identify what drives higher user ratings.

The final model explains ~66% of the variance (Adjusted R² = 0.657), as we tried to balance predictive
performance with interpretability. 

---

## Problem Statement
Can we predict a board game’s average user rating using measurable attributes such as:
- Game complexity
- User interest and engagement
- Accessibility and player count
- Ongoing content support (expansions)

---

## Data
- **Source:** BoardGameGeek (via Kaggle)
- **Observations:** 21,925 board games
- **Features:** ratings, complexity, ownership, user interest, player count, playtime,
  language accessibility, expansions
- High-dimensional theme and mechanic features were explored but excluded from final
  models due to sparsity and multicollinearity.

---

## Approach
### 1. Exploratory Data Analysis
- Analyzed distributions and relationships between ratings and engagement metrics
- Identified skewed variables and applied og transformations
- Examined correlations to anticipate multicollinearity issues

### 2. Feature Engineering
- Created composite engagement metrics (e.g., DesireScore from want/wish signals)
- Grouped categorical variables (player count, expansion count)
- Filtered to well-established games (≥ 1,000 owners) to reduce noise

### 3. Modeling
- Built multiple linear regression models in R
- Reduced multicollinearity using VIF analysis
- Compared models using R² and adjusted R²
- Validated assumptions via residual diagnostics

---

## Results
- **Final Model Performance:**  
  - Adjusted R² = 0.657
- **Key Predictors:**
  - User desire (strongest positive effect)
  - Game complexity (higher complexity → higher ratings)
  - Number of expansions (ongoing engagement correlates with quality)
  - Language accessibility (small positive effect)
  - Large maximum player counts (slightly negative effect)
- Ownership showed a small negative association, suggesting broader audiences introduce
  more critical ratings.

---

## Tools & Skills Demonstrated
- Programming: R  
- **Libraries:** tidyverse, ggplot2, broom, car  
- **Techniques:**  
  - Exploratory Data Analysis (EDA)  
  - Feature engineering  
  - Linear regression  
  - Multicollinearity mitigation (VIF)  
  - Model diagnostics & interpretation  

---

## My Contributions
- Performed exploratory data analysis and data cleaning  
- Engineered features and composite engagement metrics  
- Built, evaluated, and interpreted regression models  
- Conducted assumption checks and model comparisons  
- Helped translate statistical results into actionable insights  

---

## Acknowledgements
This project was originally completed as a group assignment with:
- Darli Seranaj  
- Jacob You  

This repository represents a personal portfolio version highlighting my individual
contributions and analytical approach.




