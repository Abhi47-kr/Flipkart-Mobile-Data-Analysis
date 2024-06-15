# FLIPKART MOBILE DATA ANALYSIS

![flipkart-Ra2rr07zuFc-unsplash](https://github.com/Abhi47-kr/Flipkart-Mobile-Data-Analysis/assets/168676103/9ad78606-b7ca-44c2-948d-1ac6b4ac3f0c)


## TABLE OF CONTENTS
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Tool Used](#tool-used)
4. [Web Scraping Process](#web-scraping-process)
5. [Cleaning Process](#cleaning-process)
6. [EDA Process](#eda-process)
7. [Insights and Key Findings](#insights-and-key-findings)
8. [Project Impact](#project-impact)
9. [Conclusion](#conclusion)

## PROJECT OVERVIEW
This project involves scraping mobile phone data from Flipkart, cleaning the data, and performing Exploratory Data Analysis (EDA) to derive meaningful insights. The entire process showcases my skills in web scraping, data cleaning, and data visualization using Python. 

## DATA SOURCES
The data used in this project was scraped from the *[Flipkart](https://www.flipkart.com/search?q=smart%20phones&otracker=search&otracker1=search&marketplace=FLIPKART&as-show=on&as=off)* website, focusing on smart mobile phones with varying price ranges.

## TOOL USED
- Python
- Jupyter Notebook
- BeautifulSoup (for web scraping)
- Requests (for handling HTTP requests)
- Pandas (for data manipulation)
- Matplotlib (for data visualization)

## WEB SCRAPING PROCESS
The web scraping script collects the following data for each mobile phone:
- Product Name
- Price
- Description
- Ratings

[View Web Scraping Script](https://github.com/Abhi47-kr/Flipkart-Mobile-Data-Analysis/blob/7380965d97ce9d6b13f847199b7c7b1f3f3f5045/Scraping_flipkart%20mobile%20data.ipynb) | [View Raw Data (CSV)](https://github.com/Abhi47-kr/Flipkart-Mobile-Data-Analysis/blob/7380965d97ce9d6b13f847199b7c7b1f3f3f5045/flipkart_webscraping2.csv)

## CLEANING PROCESS
The cleaning script processes the raw data to handle missing values, extract relevant information, and standardize the data format. Key cleaning steps include:
- Handling missing values
- Extracting RAM and ROM from the description
- Extracting brand names from product names

[View Cleaning Script](https://github.com/Abhi47-kr/Flipkart-Mobile-Data-Analysis/blob/7380965d97ce9d6b13f847199b7c7b1f3f3f5045/Cleaning_flipkart%20mobile%20data.ipynb) | [View Cleaned Data (CSV)](https://github.com/Abhi47-kr/Flipkart-Mobile-Data-Analysis/blob/7380965d97ce9d6b13f847199b7c7b1f3f3f5045/flipkart_cleaned.csv)

## EDA PROCESS
The exploratory data analysis script visualizes the cleaned data to uncover patterns and insights. Visualizations include:
- Distribution of prices by RAM and ROM
- Average ratings by brand
- Distribution of ratings

[View EDA Script](https://github.com/Abhi47-kr/Flipkart-Mobile-Data-Analysis/blob/7380965d97ce9d6b13f847199b7c7b1f3f3f5045/EDA_%20flipkart%20mobile%20data.ipynb)

## INSIGHTS AND KEY FINDINGS
- Pricing Trends:
  - The price distribution revealed a wide range, with a significant number of budget and mid-range mobiles.
  - Premium brands showed higher price points with distinct features.

- Brand Popularity:
  - Certain brands dominated the market share, indicating strong brand loyalty and market presence.
 
- Feature Impact:
  - Features like RAM, storage, and battery capacity showed a positive correlation with price.
  - Higher-rated mobiles tended to have better specifications, which justified higher prices.

- Customer Insights:
  - Customer ratings and reviews highlighted the importance of specific features like battery life, camera quality, and performance.
  - Positive reviews were often associated with higher-priced models, suggesting a perceived value for money.

## PROJECT IMPACT
- *Scraped* data for over *1000 mobile phones*, including product names, prices, descriptions, and ratings.
- *Utilized BeautifulSoup* and *Requests* to efficiently gather data, ensuring a comprehensive dataset for analysis.
- *Processed* raw data to handle missing values,enhancing data quality and usability using Pandas.
- *Visualized* price distribution, brand performance, and ratings distribution through multiple charts using *Matplotlib*, providing clear and actionable insights.

## CONCLUSION
This project demonstrates my ability to scrape, clean, and analyze real-world data using Python. The insights derived can be used by potential buyers to make informed decisions and by sellers to understand market trends.

Feel free to explore the Scripts and Data used in this project. If you have any questions or feedback, please reach out!
