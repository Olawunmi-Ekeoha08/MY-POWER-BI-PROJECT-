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
- i renamed the column as Bonus Rate
- filtered the column Bonus Rate and checked only the values. 
