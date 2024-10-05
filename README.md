# MTcars-Analysis
This project analyzes the built-in `mtcars` dataset in R, which contains data on fuel consumption and various aspects of automobile design and performance for 32 cars from the 1973–74 models. The analysis focuses on understanding the relationship between horsepower and miles per gallon (mpg), as well as descriptive statistics and visualizations.

Motor Trend Car Road Tests (mtcars) is a dataset extracted from the 1974 Motor Trend US magazine, comprising fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models). The dataset includes 32 rows (observations) and 11 numeric variables, including:
1. `mpg` - Miles/(US) gallon
2. `cyl` - Number of cylinders
3. `disp` - Displacement (cu.in.)
4. `hp` - Gross horsepower
5. `drat` - Rear axle ratio
6. `wt` - Weight (1000 lbs)
7. `qsec` - 1/4 mile time
8. `vs` - Engine (0 = V-shaped, 1 = straight)
9. `am` - Transmission (0 = automatic, 1 = manual)
10. `gear` - Number of forward gears
11. `carb` - Number of carburetors

### Objective
The objective of this project is to analyze the `mtcars` dataset to understand the relationship between horsepower (hp) and fuel efficiency (measured in miles per gallon, mpg). Through descriptive statistics, correlation analysis, and linear regression, the project aims to uncover insights into how horsepower affects fuel consumption in automobiles.

### Contents
1. **Loading the Dataset**: Introduction to the `mtcars` dataset.
2. **Descriptive Analysis**: 
   - Calculation of mean and standard deviation for horsepower and mpg.
   - Five-number summary for horsepower and mpg.
   - Identification of cars with the lowest and highest horsepower and mpg.
3. **Pearson Correlation Analysis**: Analysis of the correlation between horsepower and mpg.
4. **Simple Linear Regression**: Building a linear regression model to predict mpg based on horsepower.
5. **Visualizations**: Scatter plots with regression lines to illustrate the relationships.

### Tools and Visualizations Used
- **Language**: R
- **Packages**: `ggplot2`
- **Types of Visualizations**:
  - Boxplots for summary statistics
  - Scatter plots with regression lines
