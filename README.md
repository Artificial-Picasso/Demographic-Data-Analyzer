# Demographic Data Analyzer

## Description
This project analyzes demographic data from the 1994 U.S. Census using Python and Pandas. It provides insights into various aspects of the population including education levels, income distribution, working hours, and demographic breakdowns by race, gender, and country of origin.

## Features
- Data loading and cleaning pipeline
- Comprehensive demographic analysis including:
  - Race distribution
  - Average age by gender
  - Education level vs income
  - Working hours analysis
  - Country-based income comparisons
  - Occupation trends

## Dataset
The analysis uses the "adult.data.csv" dataset which contains the following columns:
- `age`: Continuous
- `workclass`: Private, Self-emp-not-inc, etc.
- `fnlwgt`: Continuous (final weight)
- `education`: Bachelors, HS-grad, etc.
- `education-num`: Continuous
- `marital-status`: Married-civ-spouse, Divorced, etc.
- `occupation`: Tech-support, Craft-repair, etc.
- `relationship`: Wife, Own-child, Husband, etc.
- `race`: White, Asian-Pac-Islander, etc.
- `sex`: Male, Female
- `capital-gain`: Continuous
- `capital-loss`: Continuous
- `hours-per-week`: Continuous
- `native-country`: United-States, Cambodia, etc.
- `salary`: <=50K, >50K

## Key Findings
1. **Race Distribution**:
   - White: 27,816
   - Black: 3,124
   - Asian-Pac-Islander: 1,039

2. **Average Age**:
   - Men: 39.4 years

3. **Education & Income**:
   - 46.5% of people with advanced degrees (Bachelors, Masters, Doctorate) earn >50K
   - 17.4% of people without advanced degrees earn >50K

4. **Working Hours**:
   - Minimum work hours per week: 1
   - 10% of people working minimum hours earn >50K

5. **Country Analysis**:
   - Iran has the highest percentage (41.9%) of high earners (>50K)

6. **Occupations**:
   - Most popular high-earning occupation in India: Prof-specialty

## Usage
1. Ensure you have Python 3.x and pandas installed
2. Place the "adult.data.csv" file in your working directory
3. Run the Jupyter notebook to see all analyses

## Requirements
- Python 3.x
- pandas
- Jupyter Notebook (optional)

## Author
Motlalepula Lawrence Tshabalala  
Date: 2025/05/11

## Notes
- The analysis provides insights into income inequality and demographic trends
- All string values are automatically stripped of whitespace
- Percentages are rounded to 1 decimal place for readability
- The dataset represents U.S. demographic data from 1994
