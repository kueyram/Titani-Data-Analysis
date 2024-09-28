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

1. Age Distribution of Passengers
2. Number of Passengers in Each Class
3. Age Distribution Across Passenger Classes
4. Passenger Class vs. Fare by Survival Status
5. Survival Rate by Passenger Class
6. Number of Survivors by Gender

## Key Findings

    Passenger Class: Passengers in 1st class had a higher survival rate compared to those in 3rd class, indicating a correlation between class and survival chances. This is consistent with historical accounts suggesting that priority was given to higher-class passengers during evacuation.
    Gender Influence: The number of female survivors was higher than male survivors, suggesting that gender played a significant role in survival. Women and children were often prioritized during evacuations.

## Conclusion

The visualizations support the narrative that factors such as passenger class and gender significantly influenced survival rates. Higher-class passengers and females had a greater chance of survival due to societal norms and evacuation protocols at the time.

## How to Run the Code

    1. Ensure you have Python installed.
    2. Install the required libraries:
      pip install pandas matplotlib seaborn
    3. Run the script:
      python titanic_analysis.py

## License

This project is licensed under the MIT License.

## Acknowledgments

    Dataset sourced from Kaggle.
    Inspired by the historical significance of the Titanic tragedy.

