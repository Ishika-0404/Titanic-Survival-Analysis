# **Titanic Survival Analysis**

## **Overview**
The Titanic Survival Analysis project explores survival patterns and factors affecting the survival rates of passengers aboard the RMS Titanic using Python. This analysis employs popular data analysis and visualization libraries like **Pandas**, **Matplotlib**, **Seaborn**, and **SciPy**. The goal is to derive actionable insights into the dataset through data exploration, cleaning, feature engineering, and visualizations.

---

## **Objective**
1. Perform an in-depth analysis of the Titanic dataset.
2. Understand the factors that influenced survival rates.
3. Visualize key insights using advanced plotting techniques.
4. Handle missing data and preprocess it for better analysis.
5. Apply statistical analysis and feature engineering to improve interpretability.

---

## **Dataset Description**
The Titanic dataset provides information about passengers aboard the RMS Titanic. The key features include:

| **Feature**       | **Description**                                           |
|--------------------|-----------------------------------------------------------|
| **Survival**       | Survival status (0 = No; 1 = Yes)                        |
| **Pclass**         | Passenger class (1 = 1st; 2 = 2nd; 3 = 3rd)              |
| **Name**           | Name of the passenger                                    |
| **Sex**            | Gender of the passenger                                  |
| **Age**            | Age of the passenger                                     |
| **SibSp**          | Number of siblings/spouses aboard                        |
| **Parch**          | Number of parents/children aboard                        |
| **Ticket**         | Ticket number                                            |
| **Fare**           | Passenger fare                                           |
| **Cabin**          | Cabin number                                             |
| **Embarked**       | Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton) |

---

## **Project Workflow**
### **1. Data Exploration**
- Display the first and last few rows of the dataset.
- Check dataset dimensions (rows and columns).
- Summarize dataset information such as column data types and memory usage.
- Generate basic statistics for numerical features.

### **2. Data Cleaning**
- Identify and handle missing values.
- Drop unnecessary columns like `Ticket` and `Name`.
- Encode categorical data into numerical formats for analysis.

### **3. Univariate Analysis**
- Analyze individual features like survival rates, class distribution, and gender distribution.
- **Visualizations**:
  - Pie charts for survival and class proportions.
  - Bar plots for categorical feature distributions.

### **4. Bivariate Analysis**
- Investigate relationships between two variables:
  - Survival rates by gender.
  - Survival rates by passenger class.
- **Visualizations**:
  - Heatmaps to understand correlations.
  - Crosstab visualizations for survival analysis.

### **5. Feature Engineering**
- Create new features from existing data for better insights, such as:
  - Family size (combining `SibSp` and `Parch`).
  - Fare per person.
  - Age categories.

---

## **Key Insights**
1. **Survival Analysis**:
   - Women had a significantly higher survival rate compared to men.
   - Passengers in 1st class were more likely to survive than those in 2nd or 3rd class.
2. **Age and Survival**:
   - Children had a better chance of survival compared to adults.
3. **Family Size**:
   - Smaller families were slightly more likely to survive.

---

## **Libraries and Tools Used**
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For basic plotting and visualization.
- **Seaborn**: For advanced statistical visualizations.
- **SciPy**: For statistical computations and significance testing.

---

## **Visualizations**
The following visualizations were used in this analysis:
1. **Pie Charts**: To represent survival proportions and class distribution.
2. **Bar Plots**: For gender-wise and class-wise survival analysis.
3. **Heatmaps**: To visualize correlations between numerical features.
4. **Crosstabs**: For analyzing survival patterns.


