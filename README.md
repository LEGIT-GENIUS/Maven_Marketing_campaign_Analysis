# MAVEN_MARKETING_CAMPAIGN_ANALYSIS.

<img src="https://www.sender.net/wp-content/uploads/2022/06/b043-What-Is-Retail-Marketing-Types-Strategies-small-1-1024x658.webp">
Photo credit; @maven analytics.

## INTRODUCTION.

The dataset comprises of the outcome of a marketing campaign involving 2241 customers during Maven Marketing from July 2012 to June 2014. It includes: consumers profile, product preferences, campaign acceptance, and other demographic attributes peculiar to the consumers. The goal of this project is to unravel valuable insights from the available data with regards to the demographics distributions and profile of the consumers, the various products, the channels of purchase, and the rate of acceptance of each campaign. This will enhance the process of making a data driven decision. In the end, suitable recommendations that will help to boost the success of future marketing campaigns will also be provided.

### ABOUT THE DATA

The dataset is a CSV file that contains one table, having 2,241 rows and 28 columns. Can be accessed through the link: https://mavenanalytics.io/data-playground?page=3&pageSize=10.

Some other facts about the dataset includes:
* The marketing campaign took place in about eight (8) different countries, namely: Australia, Spain, USA, Canada, Germany, India, Mexico, Saudi Arabia.
  
* There were 6 different set of marketing campaigns with a rating of customers’ acceptance after acceptance, namely:
1. AcceptedCmp1 (the first marketing campaign).
2.  AcceptedCmp2 (the second marketing campaign).
3. AcceptedCmp3 (the third marketing campaign).
4. AcceptedCmp4 (the fourth marketing campaign).
5. AcceptedCmp5 (the fifth marketing campaign).
6. Response (the last marketing campaign).

* The campaign was actually done in relation to seven (6) different products:
1. Wines (represented as MntWines).
2. Fruits (represented as MntFruits).
3. Meat products (represented as MntFruits).
4. Fish products (represented as MntMeatProducts).
5. Sweet products (represented as MntSweetProducts).
6. Gold products (represented as MntGoldProds).

* The information received on every customer with regards to their purchases includes: •	Date of birth.	Marital status.	Education level, Annual income, Number of children at home (kids and Teens).

* There were four means through which consumer could make purchase within the store;
  
1. Deals purchase (NumDealsPurchases)
2. Web purchase (NumWebPurchases)
3. Store purchase (NumStorePurchases)
4. Catalogue purchase (NumCatalogPurchases)

* With regards to the marital status of consumers, about 8 of them were identified: 
1. Absurd
2. YOLO
3. Alone
4. Widow
5. Divorced
6. Single
7. Together
8. Married

#### RECOMMENDED ANALYSIS AS REQUIRED BY THE BUSINESS.

1.	Are there any null values or outliers? How will you handle them?
2.	What factors are significantly related to the number of web purchases?
3.	Which marketing campaign was the most successful?
4.	What does the average customer look like?
5.	Which products are performing best?
6.	Which channels are underperforming?

##### SKILLS AND CONCEPTS APPLIED IN THE COURSE OF THIS ANALYSIS.

1.	Excel functions: Date, text, and Sum.
2.	Data cleaning.
3.	Data manipulation.
4.	Tables and Pivot tables (for summarizing data).
5.	Descriptive statistics.
6.	Cell referencing.
7.	PowerBI Visualization.
8.	PowerBI dashboard building.
9.	Transforming data on powerBI through the use of listing to create groups for age and income.

# **DATA CLEANING AND MANIPULATION PROCESS**

After downloading the data from: https://mavenanalytics.io/dataplayground?page=3&pageSize=10. The original data set comprises of 2,241 rows, and 28 columns. The following cleaning and manipulations were carried out to ensure that the data is readily available for further analysis:

* **The removal of empty cells:** 25 empty cells were found in the income per year of the consumers. They were deleted. And the reason for this is the discrepancies or irregularities that could occur in the process of providing analysis on anything that is related to the income of the consumers. This reduced the model of the data set, leaving us with 2216 rows. This means the consumer sample size has been reduced to 2216 from 2241.

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/dc156581-9af5-497b-900a-8cc90026ebee) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/eb5e8130-7f0d-4b80-a518-f94d4f850a60) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/0051d8bc-7239-4c0c-8cc4-17156b5b1011)

* Some columns were reformatted to suit the values that is attributed to the variables. For instance, the following columns: income_per_year, and MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts were all formatted into currency. 

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/713b09b6-a8db-44bc-b12e-d47d7a4a66fd)

* Four additional columns: Age (column C), Months (column L), Total amount spent on purchase (column T), and children (column J), were created using the sum formula and functions. This will help in further analysis regarding the consumers demographic details. 

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/e6ca8cdb-c572-4094-a125-ce380e7fbd24) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/90f15d12-3745-489f-a00c-168baf5a0d9e)

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/303915fb-dbb4-418d-b3bf-a04c4343a179) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/8a5317ef-8799-4ebf-a5b2-60b7fc1bd0ce)

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/ac9a568a-2035-45f9-923f-070644f9b128) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/818eda7a-59ec-4483-9569-0b8708a09fb9)

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/3b55ffb4-329a-44d5-a8ed-586b5b0fded3) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/9af3423a-0ddf-4078-825e-ca4a001af42d)

## INSIGHTS AND ANSWERS TO BUSINESS QUESTIONS BASED ON THE ANALYSIS WITH THE USE OF MICROSOFT EXCEL AND POWERBI

**1. Are there any null values or outliers? How will you handle them?**

There were outliers within the data set found in the income per year column of the consumers. The values that were common in this column ranges from $1,730 to $157,000. However, an income level of about $666,666 was identified which is significantly high and different from other income level, this was the only identified outliers. This was treated as insignificant because only one consumer earned has that level of income per year. Such outliers will not affect the effectiveness of our analysis. The empty cells that were identified in the income per year regions has already been treated in the previous session that talked about data cleaning involving the removal of empty cells.

**2. What factors are significantly related to the number of web purchases?**
The primary objective of a marketing campaign is to increase the reach and pace at which a firm is able to gain access to their current consumers and also prospective ones, with the aim persuading the target audience to make positive response with regards to their decision; this could be anything from buying a product to signing up for a service. This is expected boost the sales, revenue, and profit in the long run. Talking about the web purchase, there are numerous factors that can be considered as significant to it, but according to this data, there are basically five factors related to the consumers that can ideally influence the number of web purchase: Age, Education, Location, Marital status, Income per year. This is not to say that at the initial stage that these outlined factors will affect the number of web purchase, the data will speak for itself in subsequent paragraphs. Given that 2216 customers that were accounted for in the course of this analysis. The sum of web purchase made by them is 9046 with a valuation of.

* **Age:** Different age groups (4), were created through listing on powerBI. Adolescence (Age 0 to 19), Adulthood (Age 20 to 44), Middle Aged (Age 45 to 64), Senior citizens (Age 65 and above). This was done mainly to enable us ascertain the extent at which the age of consumers affects the use of web purchase.
![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/dce06470-f0bf-4a84-8745-42ef14bfadf3) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/68ab53ef-e6c5-433d-b345-5ed4b8afba08)

For the pie chart above, based on the age factor, the number of web purchase by each age groups are; adolescence 0.2%, adulthood 46.78%, middle aged 46.81%, and senior citizens 6.21%. looking at these figures, it is crystal clear that the age factor has significantly affects the number of webs purchased that was made within the stipulated periods. Consumers within the adulthood and the middle-aged group made more purchase through the web.

* **Income Level:** the income per year was divided into 3 different groups through listing on powerBI. Low-income earners (< $25,000), Medium income earners (> $25,000 < $100,000), High Income earners (above $100,000). This Was done to enable us group the consumers into different income levels or group while trying to compare the significance of income level on web purchase.
![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/de3a3101-d14a-44c1-9bd2-fb49c69ccd5d) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/bdfe319e-516b-450b-9648-2ae41364656e)

After creating the doughnut chart to compare the income level with the web purchase, the chart illustrates that: when considering the income factor, 93.9% of the web purchase were mad by Medium-income earners, 5.45% by low-income earners, while 0.65% were made by high income earners. This indicates that the level of income matters as well in terms of web purchase.

* **Education:** 
![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/1d469591-7308-4693-b90c-c749a96ce067) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/b1c3ea66-11bc-4fdc-ac4c-369e91285239)
![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/a0cd6cbb-4b7f-49e8-b17e-603c0d5092a4)

 there are apparently 5 different level of education indicated by the consumers. For a proper analysis to be done with regards to this. A pivot table was created in excel to provide a summary of the sum of web purchase made by consumers within the different educational levels, while the summary was created using the clustered bar chart visualization tool on powerBI.
The clustered bar chart and the pivot table reveals that level of education also has significant impact on the number of web purchases.  Of the 5 different level of education, 50.77% of them were made by consumers at the graduation level, 16.28% were made by master’s holders, while 23.49% of them were made by PhD holders among many others. Moving the next factor to consider.

* **Location:** 
 ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/8c14d3c6-3e03-4038-ab08-28073f007c85) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/4b246c50-17df-446b-98fb-ec8fc71b82ce)
![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/d8d518f8-dd4e-486e-adcb-9e927a811d68)

The location is the country at which the customer made the web purchase from. these 8 countries; 4367 were from Spain which accounts for 48.28%, while 1397 were from Saudi Arabia which accounts for 15.43%, and 1142 were from Canada which accounts for 12.61%. It shows that the location of the customer affects their usage of web purchase platform. These were the top 3 countries with the most web purchases. These were ascertained by summarizing the data on the Microsoft excel pivot table, and then representing the visuals on the map chart via powerBI.

* **Marital Status:** the marital status is also a very significant factor in this context. From the 8 different marital status, about 64% of the web purchase were made by people who are either together (25.99%) or married (38.62%). While divorced couple made a web purchase of 11.05% and single made 20.05%.
  
![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/fe847496-0c00-4b52-90dc-434557636970) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/5e1893a2-576f-4abf-a5d3-20d0d9da7f7e) 

So, from the summary of different demographic factors that could be linked to and affect the usage of web purchase by the consumers. They all had significant impact on their decision to purchase using the web

