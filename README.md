# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
Louise is campaign manager, came with an interest to understand the Kickstarter dataset. She wants to understand the relation between different outcomes (like successful, failed and cancelled) based on launched date and their funding target goals.

The comprehensive data anlysis of the Kiskstarter campaign project will help Louise to understand the different outcomes based on geographical countries, campaingn launch time, different categories or industries etc. 

### Purpose
The purpose of this “KickStater” Data Analytics project is to help Lousise to understand the Campaign outcomes outcomes (successful, failed and canceled) based on launch date and outcomes based on goal amount. It will assist Louise to make meaningful insight on campaign data to make better business decision with the help of data visualization.

## Analysis and Challenges

The Kickstarter Excel worksheet share with us have different data format. The column I-“Deadline” and J- “Launched_at” have other date format rather than standard excel date format. The column I and J have Unix timestamp and we must convert to standard excel date format by using complex formula to get meaningful insights and proper visualization from it.

If user is not aware of the possible different date format during the data extraction process, there is equal chances of getting errors during the date conversion process. And desire outcome would not be possible.

The final outcomes based on Month and Date is time consuming due to its different date format. We need to change both Month and Year with custom features. 


### Analysis of Outcomes Based on Launch Date

![]https://github.com/YadavThapa/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.PNG

From the above graphical studies we can say that the outcomes of Kick Start campaign (Successful, Canceled and Failed) are time variant in natures. The most successful outcomes results in May and less successful in the December.

Similarly, the most Kickstart campaigns fail in the May and October month.

### Analysis of Outcomes Based on Goals

![]https://github.com/YadavThapa/kickstarter-analysis/blob/master/Outcomes_vs_Goals.PNG

From the above graphical studies we can say that funding goal amount ranges 0-1,000 has maximum successful percentage with 74.9% and least successful percentage is 45,000- 49,000 with 0% under the play sub category.

Similary, the goal amount which ranges 45,000-49,999 most faliure percentage 100% and less failure percentage for the amount less 1,000 under play subcategoty.

### Challenges and Difficulties Encountered

The date conversion process may be challenging for the new user who is not aware of different timestamp standard format and the desire output will not be achive based on that data. 

Few columns are getting #Div/0! error and should be fixed to get desired outcome.

It is time consuming to get information based on the countifs formula and multiple nexted function associated with it. It is more prone to error because of multiple criteria selection for different range amount.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  
  From the above graphical analysis of Theatre outcomes based on Launch Date, we came to conclusion that the most successful campaign was on May month and the campaign was less successful on the December month.
   
The maximum campaign was failed on May month and October. Whereas, there was not cancelled campaign on the October.


- What can you conclude about the Outcomes based on Goals?
  The maximum percentage of successful goal is 74.9% for the range amount 0-1000. The least percentage of successful is 0% for the range amount 45000-49999 under play sub-category.
  
  The goal amount more than 50,000 are most likely to success and goal amount less than 1000 are less likely to failed.
The most interesting fact is, there is no canceled outcomes under play sub-category.


- What are some limitations of this dataset?
The “KickStarter” Microsoft worksheet shared with us have different data format. It includes both standards excel data and Unix data format. So, user should be aware to its different date standard while generating the business report. Otherwise, it will have adverse impact while making business decision. 

Few columns have more information e.g. like parent category and sub-category together. It could have extracted separately at time of report generation. This could save more time during the data preparation


- What are some other possible tables and/or graphs that we could create?
We can use the slicer custom feature to get more interactive and dynamic visualization of the data. We can use the bar graph and 80-20 graphs to visualize the top performance based on location (cities or countries).

