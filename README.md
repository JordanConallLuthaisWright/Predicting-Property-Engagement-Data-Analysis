# Predicting-Property-Engagement-Data-Analysis and Modeling 
This project involved data cleaning, feature engineering, and predictive modeling to analyze property interactions. Tasks included handling corrupt JSON data, merging datasets, exploratory data analysis (EDA), and implementing logistic regression, random forests, and linear regression for prediction.


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
