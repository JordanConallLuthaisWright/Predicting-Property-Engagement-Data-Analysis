# Predicting-Property-Engagement-Data-Analysis and Modeling 
***This project involved data cleaning, feature engineering, and predictive modeling to analyze property interactions. Tasks included handling corrupt JSON data, merging datasets, exploratory data analysis (EDA), and implementing logistic regression, random forests, and linear regression for prediction.***

---

## Project Aim 
This project analyzes **property interactions** using **data cleaning, feature engineering, exploratory data analysis (EDA), and predictive modeling**. The goal is to predict the number of interactions a property will receive **within 3 and 7 days** of activation.

##  Technical Skills Demonstrated  
- **Data Preprocessing & Cleaning**: Handling **corrupt JSON data** in `property_photos.tsv` and processing missing values.  
- **Feature Engineering**: Merging datasets, extracting insights from interaction timestamps, and numerical transformations.  
- **Exploratory Data Analysis (EDA)**: Visualizing property trends and interaction patterns.  
- **Machine Learning Models**: Implementing **logistic regression, random forests, and linear regression** for interaction prediction.  
- **Model Evaluation**: Comparing performance using **classification reports, accuracy, precision, recall, and F1-score**.

## Files in This Repository  
| File | Description |
|------|------------|
| `Predicting Property Engagement Data Analysis.ipynb` | Jupyter Notebook containing data preprocessing, EDA, and model implementation. |
| `property_data_set.csv` | Contains property details (BHK type, locality, property size, rent, etc.). |
| `property_interactions.csv` | Logs interactions (user requests for owner contact). |
| `property_photos.tsv` | Stores photo metadata, requiring JSON correction for valid extraction. |

---

## How to Run This Project  
1. **Clone the repository**  
  
2. **Install dependencies**:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn xgboost
   ```
3. **Open the Jupyter Notebook**:  
   ```bash
   jupyter notebook
   ```
4. **Run `Predicting Property Engagement Data Analysis.ipynb`** step-by-step.

---

## Business Scenario  
Real estate platforms track user engagement through **property interactions**, defined as a **contact request for a property owner’s details**. This project aims to address the following:  

1. **Can we predict the number of interactions a property will receive within a specific timeframe?**  
2. **Which property attributes (e.g., BHK type, location, rent) influence engagement?**  
3. **What data-driven insights can improve real estate listing strategies?**  

---

## Methodology & Technical Skills Demonstrated  

### 1. Data Cleaning & Preprocessing  
- Processed **missing values** and ensured **date formatting**.  
- Handled **corrupt JSON** data in `property_photos.tsv` to extract photo counts.  
- Merged datasets to create a **feature-rich training dataset**.

### 2. Exploratory Data Analysis (EDA)  
- **Visualized** interaction trends using **Seaborn & Matplotlib**.  
- Examined **correlations** between property attributes and engagement levels.  

### 3.  Feature Engineering  
- Extracted **photo counts** from JSON metadata.  
- Computed **time-based interaction metrics**.  
- Processed categorical data using **One-Hot Encoding**.

### 4. Machine Learning Models  
- **Logistic Regression** and **Random Forest Classification** tested for interaction prediction.  
- Evaluated models using **precision, recall, and F1-score**.  
- Findings showed that **classification models underperformed**, and **linear regression** was the best fit.

---

## Key Findings & Conclusion  
- **Property attributes like rent, BHK type, and locality impact engagement.**  
- **Photo count affects interaction rates**, highlighting the importance of high-quality listings.  
- **Linear Regression outperforms classification models**, making it the preferred predictive approach.

--- 

## **Contact & Contributions**
Feel free to explore and contribute! If you have any suggestions, reach out or submit a pull request.
- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)

---

### **Author:** Jordan
[GitHub Profile](https://github.com/JordanConallLuthaisWright)
```
