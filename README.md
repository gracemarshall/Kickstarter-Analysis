# Kickstarting with Excel

## Overview of Project
The Kickstarter Challenge is to assist a client, Louise in reaching her fundraising goals for her play. This reports combs through and visualizes the Kicstarter data on how similar fundraising campaigns to Louise's fared in comparison to launch dates and the ability to attain there fundraising goals. 

### Purpose
The purpose is to provide Louise with with accurate information through data analysis and visualization so that she can make ab informed decision on how realistic it is for her to achieve her fundraising goal for her play, "Fever" in a timely manner.
## Analysis and Challenges
The Kickstarter analysis involved creating the necessary columns from the existing data such as date conversions using the year function, creating pivot table of theater outcomes by launch date based on the parent category, and filtering the data for successful, failed, and canceled. A line chart from the pivot table was created. A new sheet was created to filter through column with goal (with dollar amount ranges, number successful, number failed, number canceled, total projects, percentage successful, percentage failed, percentage canceled. The sum function was used to populate the total project columns. A line chart was created to show outcomes based on goals. 
### Analysis of Outcomes Based on Launch Date
The most successful campaigns launch months were in May with 111 campaigns and June with 100 campaigns out of 839 grand total. Ironically, May also had the most failed campaigns with 52 out of 493 grand total.The grand total for canceled camping was 37 out of a total campaign of 1369 campaigns. January has the highest campaign cancellation with 7, while November has the most failed campaign with 31.Function used on this analysis is the `Year()`. The chart was saved as `Theater_Outcomes_vs_Launch.png` ![Theater_Outcomes_vs_Launch.png](https://github.com/gracemarshall/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_VS_Launch.png)
### Analysis of Outcomes Based on Goals
The Outcome Based on Launch Date is that the sum of percentage successful on campaigns that are between the range of $45,000 and $49,999 were 0% meaning that 100% of fundraising campaign within this range failed. a second conclusion is that the most successful campaigns were less that $1,000 with 76% success rate.There is a 50-50 chance of success and failure withing the $15,000 to $19,999 range. the sum of percentage canceled is 0 for all ranges. there is a 17% success rate of raising amounts greater than $50,000 in a fundraising campaign.Functions used during this analysis are the `COUNTIFS()` and the `SUM()` The chart for this analysis is saved as `Outcome_vs_Goals.png`![Outcome_vs_Goals.png](https://github.com/gracemarshall/Kickstarter-Analysis/blob/main/Resources/Outcomes_Based_on_Goal.png)
### Challenges and Difficulties Encountered
Some the challenges include making sure that the required columns needed to create the pivot tables were properly formatted. creating the pivot tables and arranging the column headers in the right fields to obtain the desired results. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  * Timing for Louise's campaign fundraising has to align to the months of May, June, and July to stand a chance of at the highest success. The months of November through March should be avoided as these are consecutive months of campaign with failed rates between 30 to 39.
- What can you conclude about the Outcomes based on Goals?
  * To stand a chance of a successful campaign, Louise should focus on campaign ranges of less than $1,000 and $1,000 to $4,999 as these are the most successful ranges with 76% and 73% respectively. 
- What are some limitations of this data set?
  * A limitation in human error in computation. For example, an error that is not caught such as computing a percentage and not realizing can result in an incorrect output. another limitation is relying just on the visual like the line chart as the only means of interpreting the data. 
- What are some other possible tables and/or graphs that we could create?
  * The Kickstarter could be drilled further down to date to see not only that the month of May is the most successful fundraiser month, but the date. Does it coincide for example Mother's Day or Memorial Day weekend? if a celebration and/or celebratory plays a roll, why is November the most failed campaign month as this is also a festive season of Thanksgiving?
