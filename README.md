# Company-Expansion-Analysis
#### -- Project Status: [Completed]

## Project Intro/Objective
You're a data scientist working for a laundry-pickup services startup. This is a relatively small company and they cannot compete with the big players in major cities. The company has a strong presence in 140 locations and recently opened stores in 10 new cities. The company has two separate sales regions.

### Methods Used
* Data Processing
* Custom Territories Via Groups or Geographic Roles
* Clusters
* Highlighters
* Cross-Database Joins
* Data Visualization

### Technologies
* Tableau
* Excel
* CSV Files


## Project Description
As a data scientist at a laundry-pickup services startup, my role extends beyond mere number-crunching; it's about leveraging data-driven insights to drive growth and competitiveness in a highly dynamic market landscape. Despite being a relatively small player compared to industry giants, our company boasts a strong presence in 140 locations, with recent expansions into 10 new cities.

The objective of this project is twofold: firstly, to identify which of the two sales regions is performing better based on key metrics including average revenue per city, average marketing spend per city (where lower is preferable), and average ROMI (return on marketing investment) per city (calculated as revenue divided by marketing spending). This analysis will provide valuable insights into the relative performance of each region and inform strategic decision-making to optimize resource allocation and drive revenue growth.

Furthermore, the project aims to identify which of the 10 new locations holds the greatest potential for the company to invest more funds into marketing. By analyzing various factors such as demographic profiles, market size, and competitive landscape, we will pinpoint the new locations with the highest growth potential and recommend targeted marketing strategies to maximize their impact.

Through a combination of data analysis, statistical modeling, and strategic insights, this project seeks to empower our company with the knowledge and foresight needed to navigate the complexities of the market, capitalize on emerging opportunities, and establish a strong foothold in the competitive landscape of laundry-pickup services.

### Complete the following tasks:
Identify which of the two sales regions is performing better based on the following metrics.
 - Average revenue per city
 - Average marketing spend per city (less is better)
 - Average ROMI (return on marketing investment) per city (revenue/marketing spending)

Idenitfy which of the 10 new locations have the best potential for the comapny to invest more funds into marketing. 
## Findings:
The first part of my objective was to identify which of the two regions are performing better based on a few metrics (see above). A sheet was created designed such that the data is easily readable. As the image indicates below the better performing region is Region 1 as there is a lower average market spending while maintaining a higher revenue and return on market investment. 

![Image 1](https://github.com/Justin-Alias/Company-Expansion-Analysis/assets/45494262/eae29b58-bc3e-4a54-80aa-05e292c308e7)


The second part of the objective was to determine which of the new locations have the best potential for the comapny to invest more funds into marketing aka greatest return on investment. The first step was creating a join between two separate data sources and cleaning the data such that there no duplicate cities. Was the data was cleaned and processed I utilized Tableau clusters to section the new locations on the following metrics (Sum of Marketing Spend, Revenue, and Population). After looking at the trendline of each of the three clusters I concluded the the locations that offer the best potential return are Store ID's: 146, 150, 148, and 143 as for every $1 spent into marketing they are projected to make $7.3* in revenue as highlighted by the image below. 

![Image 2](https://github.com/Justin-Alias/Company-Expansion-Analysis/assets/45494262/cec779c1-ae12-43b7-8565-0b9982a4ca2c)

## Link to Data Source:
* https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-StartupExpansion.xlsx

* https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P1-US-Cities-Population.csv

