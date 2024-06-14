# **Bike Sales Analysis in Excel**

## **Objective:**
The primary objective of this project is to analyze **_the Bike Buyers Dataset_** from [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/bike-buyers?resource=download) to identify patterns and insights into the factors influencing bike purchases. This involves cleaning the data, creating pivot tables to perform exploratory data analysis, and building a dashboard to visualize the findings.

## **Dataset:**

The dataset includes 1000 records of individuals with the following columns:

•	**_ID_**: Unique identifier for each record.

•	**_Marital Status_**: Marital status of the individual (Single/Married).

•	**_Gender_**: Gender of the individual.

•	**_Income_**: Annual income of the individual.

•	**_Children_**: Number of children the individual has.

•	**_Education_**: Highest level of education attained.

•	**_Occupation_**: Occupation category of the individual.

•	**_Home Owner_**: Home ownership status (Yes/No).

•	**_Cars_**: Number of cars owned.

•	**_Commute Distance_**: Distance from home to work.

•	**_Region_**: Geographical region of residence.

•	**_Age_**: Age of the individual.

•	**_Purchased Bike_**: Whether the individual purchased a bike (Yes/No).

## **Steps:**

### 1. Data Cleaning:
		
	Removed duplicates.

	Used Excel's "_Find and Replace_" functionality to correct inconsistencies in the "Marital Status" and "Gender" columns, which initially had similar values (e.g., 'M' for both male and married).

	Switched the "Income" column from the "_General_" format to the "_Currency_" format and removed decimal to enhance readability.

	Created a new column "Age Brackets" using nested _IF statement_ to categorize users into age ranges for better analysis.


### 2. Pivot Tables:

Created three pivot tables to aggregate and summarize data, unveiling patterns and correlations between various demographic and behavioral attributes and bike purchase decisions.

### 3. Chart Dashboard Creation:

•	Clustered Column Chart **_“Average Income Per Purchase”_** visualizes the average income of users who made a bike purchase.

•	Line Chart **_“Customer Commute”_** indicates whether bike purchases are motivated by commuting needs, influencing product design and advertising focus.

•	Line Chart with Markers **_“Customer Age Brackets”_** reveals whether bike purchases are more common among specific age groups, aiding in age-specific product features or marketing.

•	**_“Marital Status”_** Slicer helps indicate lifestyle influences on bike purchasing decisions.

•	**_“Region”_** Slicer demonstrates different bike purchasing trends in Europe, North America, and Pacific.

•	**_“Occupation”_** Slicer shows what professional groups tend to purchase bikes more than others.

## **Insights:**

1) Most bike buyers fall within the $50,000-$60,000 income bracket.
2) Single middle-aged males with higher income are more likely to purchase a bike. Most bike buyers fall within the $50,000-$60,000 income bracket.
3) Middle-aged individuals are more likely to purchase bikes across all regions.
4) Customer commute distance does influence the likelihood of buying a bike.
5) Individuals with shorter commute distances are more likely to purchase bikes.
6) Adolescent professionals with higher income and shorter commute distance are more likely to purchase a bike.
7) Individuals in Pacific region with longer commute distances are more likely to purchase bikes.



