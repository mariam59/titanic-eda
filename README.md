# Titanic Survival Analysis (EDA)

Exploratory data analysis of the Titanic passenger dataset using Python, pandas and matplotlib.

## Goal
Find out which factors influenced a passenger's chance of survival.

## Dataset
- 891 passengers, 10 columns (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare).
- Age has 177 missing values.

## Key findings
- Only 38% of passengers survived.
- Sex was the strongest factor: about 74% of women survived vs. about 19% of men.
- Ticket class mattered: survival fell from first class to third class.
- Children (under 18) survived more often than adults : about 53% vs. 36%.
- Average age of survivors (28.3) was close to that of non-survivors (30.6), so age alone had a weak effect.

## Limitations
- Missing ages were not filled, so the child analysis is approximate.

## How to run
1. Install the libraries: `pip install pandas matplotlib jupyter`
2. Download `Titanic_eda.ipynb` and `train-selected-columns.csv` into the same folder.
3. Open the notebook with Jupyter and run all cells.
