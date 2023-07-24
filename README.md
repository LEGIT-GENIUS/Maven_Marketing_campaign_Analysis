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

###### **DATA CLEANING AND MANIPULATION PROCESS**

After downloading the data from: https://mavenanalytics.io/dataplayground?page=3&pageSize=10. The original data set comprises of 2,241 rows, and 28 columns. The following cleaning and manipulations were carried out to ensure that the data is readily available for further analysis:

* **The removal of empty cells:** 25 empty cells were found in the income per year of the consumers. They were deleted. And the reason for this is the discrepancies or irregularities that could occur in the process of providing analysis on anything that is related to the income of the consumers. This reduced the model of the data set, leaving us with 2216 rows. This means the consumer sample size has been reduced to 2216 from 2241.

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/dc156581-9af5-497b-900a-8cc90026ebee) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/eb5e8130-7f0d-4b80-a518-f94d4f850a60) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/0051d8bc-7239-4c0c-8cc4-17156b5b1011)

* Some columns were reformatted to suit the values that is attributed to the variables. For instance, the following columns: income_per_year, and MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts were all formatted into currency. 

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/713b09b6-a8db-44bc-b12e-d47d7a4a66fd)

* •	Four additional columns: Age (column C), Months (column L), Total amount spent on purchase (column T), and children (column J), were created using the sum formula and functions. This will help in further analysis regarding the consumers demographic details. 

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/e6ca8cdb-c572-4094-a125-ce380e7fbd24) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/90f15d12-3745-489f-a00c-168baf5a0d9e)

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/303915fb-dbb4-418d-b3bf-a04c4343a179) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/8a5317ef-8799-4ebf-a5b2-60b7fc1bd0ce)

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/ac9a568a-2035-45f9-923f-070644f9b128) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/818eda7a-59ec-4483-9569-0b8708a09fb9)

![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/3b55ffb4-329a-44d5-a8ed-586b5b0fded3) ![image](https://github.com/LEGIT-GENIUS/Maven_Marketing_campaign_Analysis/assets/139655319/9af3423a-0ddf-4078-825e-ca4a001af42d)

#######
INSIGHTS AND ANSWERS TO BUSINESS QUESTIONS BASED ON THE ANALYSIS WITH THE USE OF MICROSOFT EXCEL AND POWERBI












