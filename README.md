# nhanes_inferential_2021_23

## This project analyses various NHANES data from 2021-2023 using inferential statistic in order to explore relationships and differences in health metrics and demographic variables

## R was used to:
1. convert the xpt file into a csv file. 
2. Merge multiple csv files containing various required variables into one large file containing all necessary variables
3. Create a smaller csv file from the merged data containing only necessary variables
4. Print & download csv file to be used for data cleaning/prepping in Python

## The following five questions were analyzed using the corresponding statistical analyses method:

### Question 1: Is there an association between marital status and education level?:  Chi-square
### Question 2: Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?:  T-test
#### Question 3: How do age and marital status affect systolic blood pressure?: 2-Way ANOVA
##### Question 4: Is there a correlation between self reported weight and minutes of sedentary behavior?: Regression
###### Question 5: Is there an association between diabetes and weak or failing kidneys?: Chi-square

## Tests were performed using both Python and R to compare results
