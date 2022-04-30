# Introduction

This is a report based off the data of a fictional company, Cyclistic. This data was provided by Google. It will be divided into Google’s 6 phases of data analysis: Ask, Prepare, Process, Analyze, Share, and Act. I wanted to use R for cleaning, analysis, and visualization. I also wanted to use Tableau to generate an interactive dashboard.
For R, I wanted to use a year’s worth of a data where I would have the chance to use several R functions to clean and explore the data. I initially used the most recent year of 2021, however, I realized that there was not as much cleaning as other time periods. For example, the member_casual column only had data which said ‘member’ or ‘casual’. However, for the period of Q2 2019 to Q1 2020, I found that there was a lot of potential cleaning and exploring I could do. 

# Ask

Cyclistic is in a crucial stage where their future is dependent on being able to increase their profits. Currently, annual memberships and daily/single ride passes are offered. Daily/single riders are known as casual users and there is a possibility that many of these users can be converted into annual members. Financial analysts from Cyclistic have determined that annual members are the best way to increase profits in the long term. 

The problem we are trying to solve is how exactly we can turn daily/single ride users into annual members. Our insights can allow our advertising teams to know how exactly they can convince these members to switch to an annual membership. 

Our specific business task is to determine how annual members and casual riders use Cyclistic bikes. We want to identify key patterns that can lead to useful insights.

# Prepare

The data was provided by Google and was located on AWS cloud services. The R portion will focus on a certain year where there is a lot of opportunities for cleaning and analysis. 
There should not be a bias as this data was provided by the company itself. Every rider across this month is in this data and we have information on various pieces of information such as what stations they used, type of bike, and the membership status. We can also confirm that it is ROCCC as it is reliable, original, comprehensive, current, and cited.

In regard to concerns regarding privacy and security, all personal information that could be tied to the riders is removed. The data’s integrity appears to be top-notch, as entries are consistent across the last month. More information could possibly be useful, but it appears to be solid data that can help us provide insights on how casual riders are different than annual riders.

# Process

While our data is complete, there are interesting columns that we can derive from our existing columns. These include the ride length and the weekday. These give interesting insights as it allows us to determine the days and the ride length that casual or annual members use.

The tools I will be using are R and Tableau. While Excel is nice for features such as PivotTables and can be used to clean data, it cannot handle more than 1 million rows. For R, I want to clean, analyze, and create visualizations due to its speed and ability to quickly process large amounts of data. After cleaning, the data’s integrity should also be top-notch as the data is consistent and fits the columns. For cleaning the data, I used ‘rename’ commands to ensure everything had the same name and ‘mutate’ commands to ensure columns had consistent data types.

# Analyze

After ensuring that the data was properly organized into one file with all the columns properly formatted, I ran a few calculations.
![image](https://user-images.githubusercontent.com/99159437/166095785-677eb180-a1a6-41ed-a3e7-22d1d3cd116a.png)
![image](https://user-images.githubusercontent.com/99159437/166095792-cd765644-e2c7-492d-8ba9-4f045a0e8dc6.png)
It was very interesting for me to see the different usage by kinds of riders. This helped me notice that casual users tend to be most active during the weekends while annual members tend to be more active on the weekdays. Casual riders also have a much longer duration than annual members. This could indicate a trend such as annual members using the service for commuting to work or school while casual users are using it for fun.

# Share

From my findings in the Analyze stage, I noticed some trends. However, only once I created data visualizations was I able to tell the story better. I believe that annual members are users who use these bikes for work or school. They need them on a prolonged basis for their commutes and we see this through the usage during the weekdays. Casual members, on the other hand, use these bikes more on the weekends and use them for longer periods, which may indicate they use the service for leisure. 

![image](https://user-images.githubusercontent.com/99159437/166095810-735e8400-22d4-4ba1-ba4f-3d5c7563a3d5.png)
![image](https://user-images.githubusercontent.com/99159437/166095814-4b1ede44-f532-49b0-a6af-52a68befd328.png)

# Act

The final conclusion is that annual members likely use the service for work and studies while casual members may use it more for recreation. These insights can be applied by the business and team in a variety of ways. 

Three recommendations are:
1) An increase in the marketing to show the benefit of bikes in terms of commuting with regards to the environment. A recreational user does not have to use bikes every day to commute but if they can be convinced even a little, then annual membership may be worth it. 
2) An increase in the marketing to show the benefits of bikes in terms of health benefits. Like earlier, a recreational user who may not want to bike every day to work or school may be convinced to do it occasionally. Therefore, an annual membership may be worth it for them.

3) My third recommendation is to offer promotions and trials for users to swap to annual membership. The idea is if they can see the benefits of annual membership through using the service, they may be inclined to spend the extra money to get annual membership over casual rides.



