# Titanic Data Analysis

## Overview
This project analyzes passenger data from the Titanic disaster that sank on April 15, 1912. The dataset contains detailed information about each passenger, their survival status, and various demographics. The goal is to visually explore the data to identify trends and factors influencing survival rates.

## Dataset
The dataset includes the following columns:
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard the Titanic
- **Parch**: Number of parents or children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Price of the ticket
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

The dataset contains **891 rows** and **12 columns**. It can be accessed from the following link: [Titanic Dataset](https://raw.githubusercontent.com/kueyram/Titanic-Data-Analysis/refs/heads/main/data/titanic.csv).

## Questions Explored
1. How are the passengers distributed by class, and how does that relate to survival?
2. What is the survival rate by gender?
3. What other factors influenced survival rates?

## Visualizations
The following visualizations were created to explore the data:

### 1. Age Distribution of Passengers
```python
plt.figure(figsize=(10, 6))
sns.histplot(data=titanic_df, x='Age', bins=30, kde=True)
plt.title('Age Distribution of Passengers')
plt.xlabel('Age')
plt.ylabel('Count')
plt.show()
