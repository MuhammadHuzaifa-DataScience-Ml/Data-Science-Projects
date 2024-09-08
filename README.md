# EDA on Titanic Dataset

This project focuses on performing Exploratory Data Analysis (EDA) on the famous Titanic dataset to discover patterns and insights. The analysis includes data cleaning, visualization, and statistical analysis to understand the factors that contributed to the survival of passengers.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Titanic dataset provides information about the passengers aboard the Titanic, such as age, gender, class, and whether they survived. This project uses various Python libraries to analyze the data and visualize insights about survival rates based on different features.

## Technologies Used
- **Python 3.x**
- **NumPy** - For numerical operations
- **Pandas** - For data manipulation and analysis
- **Matplotlib** - For creating static visualizations
- **Seaborn** - For advanced statistical visualizations


## Usage

After cloning and setting up the project, you can open the Jupyter Notebook `project1.ipynb` to see the EDA steps. The notebook covers:
- Data cleaning
- Data visualization
- Feature analysis for survival rate
- Basic statistical exploration

### Example Analysis

```python
import seaborn as sns
import matplotlib.pyplot as plt
sns.countplot(x='Survived', data=titanic_df)
plt.show()
```

## Results

The EDA reveals insights such as:
- Survival rates were higher for females and passengers in higher classes.
- Younger passengers had a better chance of survival.
- Fare and class played an important role in determining survival chances.

## Contributing

Feel free to contribute to this project by submitting pull requests or reporting issues.

## License

This project is licensed under the MIT License.

---

You can update the repository URL and `requirements.txt` content if necessary.
