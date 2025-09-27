# Data Analysis Projects

## Question 1: Frailty and Grip Strength Study

### Data

* Height in inches
* Weight in pounds
* Age in years
* Grip Strength in kilograms
* Frailty (Y = frail, N = not frail)

### Workflow

* Rescaled height and weight to metric units and computed BMI.
* Binned participants by age range.
* Converted frailty to binary.
* Computed summary statistics (mean, median, standard deviation).
* Graphed distributions and correlations (age groups, heatmap).

### Results

* Summary tables and markdown report in `Q1_Frailty_Workflow/reports/`.
* Plots (age group counts, correlation heatmap) in `results/`.

### Findings

* Participants who are frail have weaker grip strength.
* Grip strength is inversely related to age.
* Correlation matrix identifies correlations between BMI, age, and frailty status.


## Question 2: Student Performance Analysis

### Data

Math, Reading, and Writing scores, and demographic information (gender, lunch type, test prep).

### Workflow

* Renamed column names to standard and converted score fields to numeric.
* Imputed missing values using median.
* Saved cleaned dataset as `StudentsPerformance_cleaned.csv`.
* Created visualizations comparing scores by demographic variables.

### Visualizations

* Gender vs Math/Reading (boxplots)
* Effect of test prep on Math (boxplot)
* Lunch type vs avg score (bar chart)
* Subject correlations (heatmap)
* Math vs Reading with trend lines (scatterplot)

### Findings

* Test prep and lunch type influence performance.
* Identified gender differences in subject scores.
* Math, Reading, and Writing have extremely high correlations.


## Outputs

* Modified data sets and reports stored in project folders.
* All visualizations exported as PNG files into `results/`.
