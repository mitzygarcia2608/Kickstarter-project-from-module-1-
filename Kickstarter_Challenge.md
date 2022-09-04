# Campaign Outcomes based on Launch date and Funding Goal

## Overview of Project
  * Lousie created a play that was close to reaching her intended fundraising goal. Since the  time it took to reach this level of funding was short, she requested and analysis of other plays bases on based on launch date  and funding the funding goal. Using Information found in a kickstarter file an analysis will be prepared.

### Purpose
  * This analysis will provide some insight as to how the launch date  and the funding goal of a play affected whether it was successful, failed or was canceled. The anaylsis wil also provided insight on whether either factor contributed more than the other to the outcome.



## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
 
  * In order to display data about launch dates , data was pulled from the kickstarter spreadsheet. The column that contains "Date conversion " was used to create a new column that contained information based on the year the play was launched.
  * a new stacked line chart was created using information from previous step.
  * Pivot table was filtered by "parent category" and "years." "Date Conversion" was used in rows, "outcomes" was placed both under columns and values.
  * this is the pivot table that resulted ![outcome_based_on_launch_date](path/to/outcomebasedonlaunchdate.png)
  *  a stacked line chart was created using information from the pivot table ![parent_category](path/to/parent_catefory.png)
   * data showed that there has been more successful campaigns than any other outcome regardless of the year of month. May is the best month for successful campaigns.![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111592990/188303951-8d79af51-abeb-4392-b6ff-f26084cf1951.png)

### Analysis of Outcomes Based on Goals

 * In order to display data about outcomes based on goals , data was pulled from the kickstarter spreadsheet. 
  * a new table was created using information from The columns that contains "Goal", "subcategory " and "outcome'
 * the table was sepearted into 12 categories based on the range of the goal.

  *  a stacked line chart was created using information from the table ![Outcome_vs_Goals](path/to/Outcomes_vs_Goal.png)![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111592990/188304032-2206fca3-b51b-4e5b-a604-3ff775115da1.png)

   

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. There has been more successful campaigns than any other outcome regardless of the year of month. 
    2.May is the best month for successful campaigns. Decembers seems to be a month where the amount of successful and failed campaigns are almost the same.

- What can you conclude about the Outcomes based on Goals?
    1. Campaigns with a goal of 50,000 or more had a higher perentage of failed outcomes that it did successful outcomes.
    2. the largest amount of successful projects were with campaigns that had a goal of 1000 to 4999

- What are some limitations of this dataset?
    1. the outcomed based on launch date focuses on a broader parent company whereas the Outcomes based on Goal focuses on just "Plays"
    2. fails to take into account whethers there was backers and how many.
    3. it does not take into consideration the live campaigns

- What are some other possible tables and/or graphs that we could create?
    1. Outcomes based on Percentaged Funded , to see if exceeding a Goal affected outcomes
    

