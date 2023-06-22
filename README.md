# AdvancedDeepG11
this holds part A of the final project in Advanced Topics in Deep Learning Course for Group 11 - 2023

the file has the following contents:
1. Imports and pre processing
   - format the date
   - get the date range
   - drop rows that contained null
   - add 4 columns to the data that represent the category + sub categories
2. Text Analysis
   - show bar plot representing the number of articles with X word count in the headline
3. Main categories analysis
   - per unique categories that exist in main category, unique sub categories
   - occurrences of unique values in main category
   - frequency of articles with X (1-4) number of categories
4. Dates analysis
   - bar plot of number of articles per year
   - year 2001 (the year of 9/11): theres a surge in number of articles
     - unique sub categories for main category
     - occurrences of unique values for main category
   - year 2020 (COVID)
     - number of articles with first SUBcategory "Health" years comparison vs. yearly average
     - KS statistical test to check whether the number of health related articles in 2020 is significantly different than the rest of the years
   - distribution of articles per month
     - March - st. patricks day: check if theres something interesting
       - occurences of unique values in category 1
       - occurences of unique values in category 2 
