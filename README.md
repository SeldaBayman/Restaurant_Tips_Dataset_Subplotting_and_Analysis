# Restaurant_Tips_Dataset_Subplotting_and_Analysis
 Phyton_Subplotting
 

                DATA ANALYSIS WITH RESTAURANT TIPS DATA 
 
This project will use the restaurant tips dataset to practice composition plots and visualizations. We will explore the relationship between variables and the tip given. 
The dataset that we will use is a collection of data from 244 restaurant bills, collected in the US in the year 1987. 
It includes information about the tips given to restaurant staff, such as the total bill, tip amount, the gender of the person paying the bill, whether or not they were a smoker, the day of the week, the time of day, and the size of the party.
1
Load the data
Load the tips_data.csv and store its data in a tips_df variable.
tips_df = pd.read_csv('tips_data.csv')
As you can see each observation represents a customer who left a tip at a restaurant. We can see information about the day it occurred, if it was at lunch or dinner, the number of sales, the sex of the person who left the tip, and if was a smoker or not. Before continuing take a look at a few lines of the data and use info and describe to analyze dataset column types and values.

Do smoker people give more tips?
There is no evidence to suggest that smokers give more tips than non-smokers. But let's try to analyze what our data says. In this task, you will need to create a pie chart with the proportions of smokers and non-smokers giving tips at restaurants.

2
Create a pie chart showing the proportion of smoker and non-smoker people giving tips Create your pie chart and, when ready, save it to a tips_by_smokers_chart variable and validate it with the following button.
Important! we'll interactively check that your variables smokers_count and tips_by_smokers_chart contain the correct information

3
Create a pie chart showing the proportion of tips given by men and women. Create your pie chart and, when ready, save it to a sex_proportion_chart variable and validate it with the following button.
Total bill and Tips amounts by sex
In this task, you will need to create a stacked bar chart with the amounts of total bills and tips by men and women.
4
Create a stacked bar chart showing average bill and tip amounts by sex_ Create your stacked bar chart and, when ready, save it to a tips_by_sex_chart variable and validate it with the following button.
Important! we'll interactively check that your variables tip_amount_by_sex and tips_by_sex_chart contain the correct information

Are the best tips on Saturday night?
In this task, you will need to create a pie chart with the proportions of the given tips per day of the week.
5
Create a pie chart showing the proportion of tips per day of the week . Create your pie chart and, when ready, save it to a daily_tips_chart variable and validate it with the following button.

Total bill and Tips amounts per day of the week
For the next task you will have to create a horizontal stacked bar chart with the amounts of total bills and tips per day of the week.

6
Create a horizontal stacked bar chart showing total bill and tip amounts per day of the week
Create your stacked bar chart and, when ready, save it to a tips_by_day_chart variable and validate it with the following button.
Note 1: we'll interactively check that your variables daily_mean and tips_by_day_chart contain the correct information
Note 2: make sure you have run the code above which transforms the day column to Categorical type
Are there better tips during the day or at night?
In this task, you will need to create a stacked bar chart with the amounts of total bills and tips per time of the day -lunch or dinner-.
7
Create a stacked bar chart showing 'average' bill and tip amounts per moment of the day.Create your stacked bar chart and, when ready, save it to a dinner_lunch_chart variable and validate it with the following button.
Important! we'll interactively check that your variables dinner_lunch_df and dinner_lunch_chart contain the correct information

You can load tips dataset from Kaggle:
https://www.kaggle.com/code/sanjanabasu/tips-dataset





