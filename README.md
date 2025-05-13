# pythonEDA_Titanic
# 🚢 Titanic Dataset Analysis using Python

This project focuses on analyzing the Titanic dataset to understand passenger survival patterns using Python. The project includes data preprocessing, univariate and bivariate analysis, missing value handling, categorical encoding, and basic feature engineering.

## 📁 Dataset Columns

The dataset used is based on the Titanic passenger manifest and contains the following columns:

- `PassengerId`: Unique identifier for each passenger
- `Survived`: Survival status (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = First, 2 = Second, 3 = Third)
- `Name`: Passenger name
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Ticket fare
- `Cabin`: Cabin number
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## ✅ Tasks Performed

1. **Get Overall Statistics About the DataFrame**
2. **Data Filtering:** Query subsets of the data based on conditions
3. **Check for Null (Missing) Values**
4. **Drop Unnecessary Columns** (e.g., `Cabin`, `Ticket`, etc. if needed)
5. **Handle Missing Values** (e.g., fill `Age` with median, drop rows, etc.)
6. **Categorical Data Encoding** (e.g., convert `Sex` and `Embarked` using Label Encoding or One-Hot Encoding)

---

### 📊 Univariate Analysis

Univariate analysis involves examining one variable at a time:

- **How Many People Survived and How Many Died?**
- **Number of Passengers by Class (1st, 2nd, 3rd)**
- **Number of Male and Female Passengers**

### 🔄 Bivariate Analysis

Bivariate analysis involves the relationship between two variables:

- **Who Had a Better Chance of Survival: Male or Female?**
- **Which Passenger Class Had the Highest Survival Rate?**

---

## ⚙️ Feature Engineering

Feature engineering steps may include:

- Creating a new column like `FamilySize = SibSp + Parch`
- Extracting titles (Mr., Mrs., Miss) from the `Name` column
- Categorizing age groups (e.g., Child, Adult, Senior)

---

## 🧰 Libraries Used

- `pandas` for data analysis
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization (optional)


