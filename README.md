# MY-POWER-BI-PROJECT-
#### HOW I ACHIEVED MY POWER BI PROJECT. 
 I would start with when i saw the project case scenario and the data , so I made sure i understood the data to see 1. WHAT IS MISSING, 2. WHAT IS WRONG and 3. WHAT CAN BE DONE.
On the excel file , I noticed a lot of empty space in the gender coulmn and based on the scenario given the employees in the company didnt disclose thier gender.
I repalced the empty spaces with undisclosed using the filter in the DATA task bar.
After then I loaded my csv file on Power Bi.

#### STEPS I TOOK ON POWER BI TO VISUALIZE DATA.
In transforming the data on Power Bi.

- Step 1 Renamed Location column to Region.
- Step 2 Unchecked null in department column.
- Replace values of null in salary column with zero (0)
- Keep first row.
    - This was done so that null won't return again again.
- Loaded the bonus table, then pivoted the table to make it one long format.
- Added a new column for both tables ,(bonus table and emp data ) using custom column in other to get results
- Named the custom column - Department Rating for both tables respectively.
- After which I merged as new with the unique identifier which is the Department Rating.
- I renamed the column as Bonus Rate
- Filtered the column Bonus Rate and checked only the values.
- After which i replaced the null with zero.
- Added custom column ( bonus rate * salary) named it as Annual Bonus.
- Added custom column (salary + annual bonus) named it as Total pay.
- Added a conditional column to get salary band as was asked in the case scenario.
    - This was done because of the case scenario questions given.


  #### VISUALIZATION 
In visualization ,I took some steps in visualizing.

    1. I used bar chart to solve count of employee by gender.
    2. I used column stacked chart to visualize gender distribution by region 
    3. I used pie chart to visualize the overall gender distribution.
    4. I used scatter plot to visualize the gender gap
       a. I used scatter plot becasuse i wanted to visualize and identigy the gap in the distribution of salary.









#### CHALLENGES I FACED WITH MY VISUALIZATION
- When trying to change my salary band to whole number, it kept returning error which affected my visualization to get minimun salary requirement, so i left it in text and number. I would really love to get a correction on this.
- I faced a major challenge in creating a new measure to get some results according to the case scenario given, it kept returnimg my Employee table as not being found. I could not find the problem and how to solve.
- Time was fast spent and the project deadline was fast apporoaching, i couldnt start all over again becasue of the time frame.
# I just hope I will meet the cut off mark for this project.
