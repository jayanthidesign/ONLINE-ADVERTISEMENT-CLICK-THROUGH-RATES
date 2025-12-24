# ONLINE ADVERTISEMENT CLICK-THROUGH RATES

# Project Overview and Objective

This project focuses on analyzing user engagement with online advertisements using demographic data, ad-related attributes, click behavior, click time, and click-through rates (CTR).

The main objective of this project is to analyze the factors that impact advertisement click-through performance and provide insights to optimize online ad strategies.

# Data Sources 

Source Description and Timeline: Mendeley Data and 2024.

Domain: Digital Marketing Analytics/Online Advertising/User Behavior.

# Problem Statement 

To determine how variables such as age and gender impact the likelihood of a user clicking on an Ad, enabling marketers to better target their audience.

To identify which placement locations, yield higher clicks and CTR, allowing advertisers to allocate resources effectively for maximum impact.

To analyze patterns in the data to recommend which type ads should be shown to which type of user. 

# Attribute (Column /Features) Details:  

| Attribute Name | Data Type | Description |
|----------------|-----------|-------------|
|Age | Numeric | Age of the user|
|Gender | Categorical / String | Male, Female, Other|
|Location | Categorical / String | Rural, Urban, Suburban|
|Ad Type | Categorical / String | Native, Video, Text, Banner|
|Ad Topic | Categorical / String | Food, Finance, Fashion, Health, Travel|
|Ad Placement | Categorical / String | Search Engine, social media, Website|
|Clicks |Numeric | Number of clicks received|
|CTR | Numeric | Click-through rate% |
|Impression | Numeric | The total number of times the ad was shown|

# Tools & Technologies

Excel: Data cleaning, transformation, and Pivot Tables.

Power BI: Data modelling, DAX calculations, visualization, and interactive dashboard creation.

# Data Pre-Processing (Excel / Power Query)

Tasks Performed:

Data Cleaning & Transformation: 

The Click Time column carries same value in every row; it doesn’t provide any useful information for analysis. 

Dropped the Income column, as it contains values for some age groups, so it doesn’t provide a complete view. Removing it avoids confusion and simplifies analysis.

Standardized formats and created a calculated column Impression.

Filtering & Sorting: Organized data to focus on relevant records.

Pivot Tables: Generated Pivot Tables for data summarization and initial insights.

# Data Modelling and DAX (Power BI) 

Data Model: This project uses a single-table dataset, so data model remains simple with no relationships. All measures and visuals are built from the same table.

Calculated Columns & DAX Measures: Implemented DAX formulas for key metrics such as Total clicks, Total Impressions, Average CTR, Total conversion rate.
Clicks = SUM (Dataset [Click])


Impression = SUM (Dataset [Impression])

Total Conversion Rate = SUM (Dataset [Conversion Rate])

Average Click-Through Rate = Average (Dataset [CTR])

 # Insights & Conclusions

Key Findings: 

Total Impressions: 1.18M

Total Clicks: 49K

Average CTR: 5.10%

Male users (49.84%) generate the highest share of clicks

Highest clicks from 30–45 age group (191 clicks)

Very low engagement from Above 65 (9 clicks)

# Analysis insights:

# Descriptive 

The campaign has a healthy CTR of over 5%, with social media being the most effective placement. 

Most clicks come from social media (17K), followed by Search Engine and Website (16K each).

Male users (49.84%) generate the highest share of clicks, followed by Female users (39.65%)

The highest conversions come from Male users aged 30–45.

Age group 15–30 shows a higher conversion rate for Fashion-related ads.

Age group 30–45 shows a higher conversion rate for Finance-related ads.

# Diagnosis

Users aged 30–45 typically have higher purchasing power, regular internet usage, and clearer intent compared to younger or older age groups.

Social media ads are frequently displayed, and appear in users’ leisure browsing time, increasing the likelihood of clicks.

# Predictive

Future campaigns targeting working-age adults (15–45) will yield higher CTR.     

Balanced gender-focused campaigns will sustain click volume, with potential growth from female users through tailored creatives. 

Increasing budget allocation to social media is likely to increase total clicks.

# Prescriptive

This analysis provides recommendations based on insights.

Focus ad spend on 30–45 age group.

Increase campaigns in Finance, Travel, and Technology topics.

Prioritize Social Media placements.

Optimize ads for Male and Female segments separately.

Reduce spending on Below 15 and Above 65 age groups.

Test creative improvements for Health-related ads.

# Conclusions 

   The online advertisement campaign performed well with a 5.10% average CTR, showing that users aged 30–45 are the most responsive, males click slightly more than females, social media and search engine placements generate the highest engagement, finance and technology topics perform best, and ads are least effective for users below 15 and above 65.
      
  Overall analysis suggests that future ad campaigns will achieve higher click-through rates if they focus on users aged 15–45, prioritize social media and search engine placements, and promote high-interest topics such as finance, technology, and travel, while reducing spend on low-engagement age groups like below 15 and above 65.

















