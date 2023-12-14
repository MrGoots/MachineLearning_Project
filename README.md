https://github.com/MrGoots/Project_4_Group_2/blob/main/Title_Img.png

# Project_4_Group_2
Our group decided to visualize the current state of the cost of living here in the US and make predictions for the future using a combination of machine learning, using SKLearn, and a variety of other technologies we’ve learned during this class including Python, Pandas, Matplotlib, and SQl Databases. 

The metric which best represents this data is the Consumer Price Index, or CPI. The CPI is a metric that measures the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services. In simpler terms, it helps us understand how the cost of living is changing for the average person.
 We built a data set from multiple sources comprising thousands of records and developed a machine learning model that predicts CPI over time using clustering algorithms like K-Means to group similar cities and offer regional insights.
 
Our data comes from The Bureau of Labor Statistics, a branch of the U.S. Department of Labor, which surveys thousands of households and businesses each month to collect data on prices. These prices cover a wide range of items, including food, clothing, rent, healthcare, and more. By comparing this data to a base period, the CPI is calculated and used to reflect the inflation or deflation in our economy.
Our model shows the CPI exhibits a steady increase as demonstrated in our data beginning 1980 and continuing through 2040. Over the next seventeen years, our model predicts a continued steady increase in the Consumer Price Index. 


## Here are the specific requirements:
Find a problem worth solving, analyzing, or visualizing.
Use machine learning (ML) with the technologies we’ve learned.
You must use Scikit-learn and/or another machine learning library.
Your project must be powered by a dataset with at least 100 records.
You must use at least two of the following:

Python Pandas
Python Matplotlib
HTML/CSS/Bootstrap
JavaScript Plotly
JavaScript Leaflet
SQL Database
MongoDB Database
Google Cloud SQL
Amazon AWS
Tableau

## Members:
Shane Nguyen
Carl Colburn
Dolly Low
Kristen Beer
David Jordan
Mayra Terrazas


## Other Ideas:
Where2Buy - price predictor, cheapest place to buy goods (consumer packaged goods - nondiscretion)
AI inlfuence on stock market - trade timing, stability, reactions
Social media influencers predictions on economics
Media/entertainment AI influence machine learn music 
ML prediction of top 100 music genre in the next 5 years
Food & Beverage predictions on weekend restaraunts, influence on food choice 
Travel - price predictions based on air travel ticket prices, type of trips ie adventures, luxury, kids... 
Education costs prediction model for savings for college (contingent on interest, geography)

## Project Intent:
Time-Series Forecasting for Food Prices
Create a model that predicts food prices based on historical data. Use time-series analysis and explore techniques. Major city Segmentation and Market Analysis to segment cities. Use clustering algorithms like K-Means to group similar cities and offer insights into targeted marketing strategies.

## Benchmarking - FDA / USDA 5% prediction (all food prices)
https://www.ers.usda.gov/amber-waves/2023/february/ers-refines-forecasting-methods-in-food-price-outlook/
Food home 
Categories: dairy, protein, carbs, veges, fruit

## Methods/Techniques:

Data analysis - Pandas
Web crawl - Beautiful Soup
Building the ML model - SKlearn
Testing - SKlearn
Offer insights to the data
    What is the predicted CPI
    What is the growth rate of food prices based on city


Creating documentation - Jupyter Notebook

## Data sources:
https://beta.bls.gov/dataQuery/find?fq=survey:[ap]&s=popularity:D
https://www.usinflationcalculator.com/inflation/egg-prices-adjusted-for-inflation/#google_vignette
https://fred.stlouisfed.org/release/tables?rid=10&eid=34561#snid=34568

## Final Analysis:

The results are - through the data manipulation modeling and testing, we see a forecast of CPI through 2040 (linearMain) Despite a large spike in CPI, the linear regression model still shows a steady increase, rather than an overall dramatic change. This means we can expect an increase in inflation over the next several years as well. Generally, the Federal Reserve targets for a yearly 2% inflation increase to maintain maximum employment levels and price stability, but we have seen this rate surpass this goal. During 2020-2022, our models show an increase in CPI, which are due to unexpected world events such as COVID-19, the war in Ukraine, and even smaller events such as the avian flu. Our findings correlate with the whitehouse.gov statistics that show grocery inflation is improving, however it is still high in comparison to pre-pandemic levels. The increase has left many individuals and families financially strained. Additionally, wage growth for many of us failed to increase to combat the increasing CPI. Earlier this year, we finally began to see the gap between inflation rates versus wage growth tighten, but it is not expected to close until late 2024. Unfortunately, there are still too many unpredictable factors that could determine if we will feel relief in 2024. As it stands, we are still at a high risk for a recession. Our economy heavily relies on government policy change to combat inflation. However, there are small things we can try to do to brace ourselves.

Review your budget
Diversify your income (get a side-hustle)
Pay down high-interest debt
Consider using a cash back credit card to earn money while making regular purchases.
Open a high-yield savings account
Create a meal plan you can stick to.
Batch errands (group errands to finish them in one trip, reduces commuting costs)
Invest in TIPS (Treasury Inflation Protected Securities) – it’s like a bond to help protect against inflation.
Get in contact with a financial advisor.
