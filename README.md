# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the analysis is to visualize the outcomes base on launch date and outcomes base on goals to better plan for future projects.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
I performed my analysis of Outcome base on Launch Date using a pivot table to sort the outcome of the projects by launching months. I sorted the data by adding “Date Created Conversion” in rows section and “outcount” in the columns section, then add count of outcount in the value section. Then I filter outcome only relates to “theater” projects. Last, I created the chart using the pivot table data as the link.
resources\Theater_Outcomes_vs_Launch.png (https://github.com/tw99ch/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)

I added columns based on the instruction in the Deliverable 2. I created countifs formula by searching data which fit in the predetermined criteria which are the goal amount and outcome. Then I created the chart based on the summarized data. Outcomes_vs_Goals.png (https://github.com/tw99ch/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
I had challenge using countifs formula. After reading hints provided and searches online, I am able to complete the task.

I did not encounter big challenges. I think if the formula is not set up properly, when copying the formula to other cell, the formula might be off.	
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
o Based on the chart generated in excel, there is higher chance of successful theater projects if the projects are launched from April to July, especially in May and June it is expected to have more successful projects.
o In the months of Jan, Mar, Sept Nov, and Dec, the successful theater projects are lower. Therefore, Louise should avoid launching future projects in these months. 
-What can you conclude about the Outcomes based on Goals?
Goals set at below $14,999, or $35,000 to $44,999 have higher successful rate. Whereas, goals set at $15,000 to $34,999 or over $45,000 have higher failed rate. Therefore, for future projects, the goal should be set at below $14,999, or $35,000 to $44,999 to increase the success rate.  
- What are some limitations of this dataset?
The limitation of the dataset is that we are able to tell the other factor that might impact the success or failure of the projects. There might be other factors that will impact the outcome of the project.
- What are some other possible tables and/or graphs that we could create?
o We can create chart for each parent category based on region to identify the preference of the country and to focus the future projects type based on country's preference.
o We can create a pivot table based on average of percentage funded sorted by parent category and outcomes. From the pivot, we can see games and technology have the highest average percentage funded. 




