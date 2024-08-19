# EDA on Mental Health Dataset

## Objective
The goal of this project is to explore and analyze a mental health dataset to understand patterns and correlations related to mental health issues, habits, and treatment among different demographic groups. The analysis employs Python libraries such as Pandas, Matplotlib, and Seaborn.

## Dataset Description
The dataset includes various fields related to mental health, including:
- `Gender`
- `Country`
- `Occupation`
- `Self_Employed`
- `Mental_Health_History`
- `Family_History`
- `Mood_Swings`
- `Coping_Struggles`
- `Days_Indoors`
- `Social_Weakness`
- `Work_Interest`
- `Treatment`

## Analysis Steps

### 1. Data Cleaning and Preprocessing
- Handled missing data, particularly in the `self_employed` column.
- Standardized responses in columns such as `Days_Indoors`, `Growing_Stress`, and `Mood_Swings` to ensure consistency.

### 2. Descriptive Statistics
- Calculated the frequency of responses for `Gender`, `Country`, `Occupation`, and `Treatment`.
- Provided summary statistics for categorical variables to understand central tendencies and variabilities.

### 3. Visualization of Demographic Data
- Created pie charts for `Gender` and `Country` to visualize the composition of respondents.
- Used bar graphs to show the distribution of respondents by `Occupation`.

### 4. Analysis of Mental Health History
- Plotted the distribution of `Mental Health History` responses and analyzed the proportions of each category.

### 5. Correlation Analysis
- Investigated the relationship between `Family History` and `Treatment`.
- Explored the correlation between `Mood Swings` and `Coping Struggles`.

### 6. Frequency of Days Indoors
- Visualized the number of days respondents stayed indoors due to mental health issues using histograms and box plots.

### 7. Impact of Social Factors
- Analyzed the effects of `Social Weakness` on `Work Interest` and `Coping Struggles` using cross-tabulations.

### 8. Coping Mechanisms
- Charted the frequency and types of `Coping Struggles` faced by respondents and compared them across different stress levels.

### 9. Awareness and Availability of Care Options
- Assessed the awareness of care options among respondents and visualized this data using bar graphs and stacked charts.

## Results
The analysis revealed significant insights into mental health trends, including patterns in treatment, coping mechanisms, and the impact of social factors. Visualization of demographic data and mental health history provided a clearer understanding of the challenges faced by different groups.
