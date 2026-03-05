````markdown
# Titanic Data Analysis

A data analysis project exploring the Titanic dataset to uncover patterns in passenger survival based on features like age, gender, class, and fare using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)  
- **Contents:** Passenger data including:
  - PassengerId, Name, Age, Sex
  - Pclass, SibSp, Parch, Fare
  - Cabin, Embarked, Survived

---

## Installation

```bash
git clone https://github.com/yourusername/titanic-data-analysis.git
cd titanic-data-analysis
pip install pandas matplotlib seaborn
````

---

## Usage

```bash
jupyter notebook notebooks/titanic_analysis.ipynb
# or
python analysis.py
```

---

## Key Insights

<details>
<summary>1. Survival by Gender</summary>

* Females had a significantly higher survival rate than males.
* Gender was a strong factor in survival probability.

</details>

<details>
<summary>2. Survival by Passenger Class</summary>

* First-class passengers had higher survival rates than second and third-class passengers.
* Socioeconomic status influenced chances of survival.

</details>

<details>
<summary>3. Age vs Survival</summary>

* Children had higher survival rates compared to adults.
* Elderly passengers had lower survival probability.

</details>

<details>
<summary>4. Fare vs Survival</summary>

* Passengers paying higher fares were more likely to survive.
* Fare is indirectly linked to class and cabin location.

</details>

<details>
<summary>5. Family Impact (SibSp & Parch)</summary>

* Passengers with small families had slightly higher survival chances.
* Large families had lower survival rates due to evacuation difficulties.

</details>

<details>
<summary>6. Embarked Port vs Survival</summary>

* Passengers from certain embarkation ports had higher survival rates.
* Survival trends vary slightly by port of embarkation.

</details>

---

## Project Structure

```
titanic-data-analysis/
│
├── data/                 # Titanic dataset CSV
├── notebooks/            # Jupyter notebooks
├── plots/                # Visualizations
├── analysis.py           # Main analysis script
└── README.md
```
Author Saba Abbasi

