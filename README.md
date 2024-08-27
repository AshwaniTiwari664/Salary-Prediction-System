# Salary Prediction Based on Country and Race

## Project Overview
The **Demographic-Based Salary Prediction** project aims to develop a predictive model to estimate salaries of individuals based on their demographic attributes, including country, race, age, gender, experience, and education. This model leverages a dataset from Kaggle with 32,561 rows and 15 columns, including 8 independent variables and the target variable, "Salary."

## About the Dataset
The dataset offers a detailed view of salary and demographic information, including years of professional experience. It serves as a crucial resource for analyzing the relationship between income and various socio-demographic factors. Key features include:

- **Age**: Age of the employee
- **Education Level**: Education level of the employee
- **Job Title**: Job title of the employee
- **Years of Experience**: Years of professional experience of the employee
- **Salary**: Salary of the employee
- **Country**: Country of the employee
- **Race**: Race of the employee

This dataset allows for an in-depth exploration of income distribution patterns across different demographic categories and the influence of professional tenure on salary levels. It facilitates a thorough analysis of income diversity and the determinants that affect earnings in a diverse workforce.

## Data Dictionary
| Column                   | Description                                 |
|--------------------------|---------------------------------------------|
| `Unnamed: 0`             | Index                                       |
| `Age`                    | Age of the employee                         |
| `Education Level`        | Education level of the employee             |
| `Job Title`              | Job title of the employee                   |
| `Years of Experience`    | Years of experience of the employee         |
| `Salary`                 | Salary of the employee                      |
| `Country`                | Country of the employee                     |
| `Race`                   | Race of the employee                        |

## Files
- **`Salary Prediction.ipynb`**: Jupyter notebook containing the model development and analysis.
- **`Salary_Data_Based_country_and_race.csv`**: CSV file with the dataset used for analysis.

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/AshwaniTiwari664/salary-prediction-demographics/
    ```

2. Navigate to the project directory:
    ```bash
    cd salary-prediction-demographics
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebook:
    ```bash
    jupyter notebook Salary\ Prediction.ipynb
    ```

5. Follow the instructions in the notebook to run the analysis and build the predictive model.

## License
This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
