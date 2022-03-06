# Kickstarting with Excel

## Overview of Project

In this project, we worked with a large amount of crowdfunding campaign dataset that belongs to a wide range of industries and, subcategories of these industries. Data was very rich and allowed us to break down into multiple categories and allowed us to reveal the results from multiple aspects such as statistical, visual, by dates, or success rates. By doing this we get a better understanding and forecasting for desired future campaigns

### Purpose

The purpose of this analysis is to help Louise to predict her future campaigns, maximize the goals and pledged amount as well as reach the "successful" outcome goal.

## Analysis and Challenges

Our Analysis is consist of 2 relations, the first one is goals vs outcomes, the second one is launch dates vs outcomes. firstly, To predict future campaigns goals we applied some statistical analysis and divided the goals into several goal levels and for the launch dates, we analyzed by months of the multiple years.

Firstly we create a pivot table to see relations between launch months - outcome. According to the chart, we create Outcomes based on the launch date chart.
![Table_Theater_Outcomes_by_Launch_Date](https://user-images.githubusercontent.com/98247252/156906085-492fd9c2-8774-498d-8c36-6188a26c511b.png)


Secondly, step is creating a pivot chart that contains outcomes and goals relation. With this information, we created Outcomes based on a goals chart.
![Outcomes_based_on_goals](https://user-images.githubusercontent.com/98247252/156906093-6b4e8990-6012-48d7-bb29-c6bf37b90caf.png)


During the analysis, we processed the data with multiple excel tools and functions such as;

#### Statistical Analysis 
![Descriptive_Statisctics](https://user-images.githubusercontent.com/98247252/156906099-224a4dae-c916-42dc-a0d7-4d10cc4c4f90.png)


The chart above contains multiple statistical calculations belonging to the goal and pledged amount of the "plays" subcategory. We can see the reason for successful and failed "plays" campaigns in the US. For instance, according to standard deviation of successful goals are almost double of IQR in addition to that standard deviation value of failed goals are almost three times bigger than the IQR value. This is an obvious indicator that some failed campaign's goal was very high.



### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98247252/156906124-855570e3-8e19-4984-80c7-701b0a24659b.png)


In this chart, we tried to help to demonstrate how different mount of the year affected the success of *Theater* campaigns

*X-Axis* shows 12 months of the year.
*Y-Axis* shows overall numbers of successful, failed, and canceled *theater* campaigns between 2009 and 2017

By gathering this data we tried to have a better understanding of the best month(s) of the year to launch campaigns in *theater* category 


### Analysis of Outcomes Based on Goals


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98247252/156906133-f532095b-351d-4f6e-98d9-93c7bdf551f7.png)

This chart shows how campaign *plays* subcategory outcomes success are affected by its gaol. 

*X Axis* Shows desired goal amounts from $0 to $50.000 into 12 pieces. (every 5000 steps).
*Y-Axis* Shows successful, failed, and canceled *plays* percentages.

By gathering this data we tried to have a better understanding of how*Plays* subcategory achieves its goals on different *goal* amounts.

### Challenges and Difficulties Encountered

*Firstly* Working with the multiple data, sheets, pivot tables, and charts can be hard to see an overview of the data. Every 2 days pausing the work and checking and remembering the purpose of the data can help to better understand the overall concept. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May is the best month to launch a theater campaign because the success rate is over 100% and the difference between success and failed campaigns is in the largest point. (111 Successful vs 52 failed). May, June, July, August, and October as roughly the same failing numbers even the overall campaign number was descending. 

*First Conclusion*Lowering the launched campaign numbers step by step starting from May through December will allow us the maintain a successful outcome through the 12 months. 

*Second Conclusion* November to April period is a great time to have advertised the campaigns that we will launch on the high season. By doing this we will build more awareness and catch the eye of the backers from our target countries.



- What can you conclude about the Outcomes based on Goals?

In the **plays** subcategory  $1000 to $5000, $35000 to $40000, and $40000 to $45000 provide the best results in terms of reaching to their goal dollar amount. However, according to our table, almost 75% of successful goals are between $1000 and $5000. There are several high gaol amount but their success rate is less than 50%.

*, As a result,* if we want to maintain our success we should keep our goals $1000 to $5000 scale. however, improving the quality of the content from $40000 to $45000 would help us to gather more funds with fewer campaigns.


- What are some limitations of this dataset?

The dataset does not show the external reasons for the short goal rates and off-season performances. (months). Also the subject of the campaigns and *plays* is very important. In a conclusion, the number of backers can be affected negatively year to year because of economical reasons.

The second limitation is the US and GB are the largest data provider on Theater, "plays" subcategories, besides this, other countries do not provide enough data. Because of this reason, we may not be able to apply the results to every single country equally.

- What are some other possible tables and/or graphs that we could create?

As a next step, we can analyze outcome vs campaign duration, this can be based on category, subcategory, or country. also, we can combine this information with the result of Outcomes-based on the launch date. We can visualize it with a pivot table and then we can add a bar graph.


