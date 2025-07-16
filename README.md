# **Web Scraping & Analysis Project: Nykaa Products Analysis**
This project involves collecting and analyzing data of body lotion products from the Nykaa website. The goal is to understand pricing trends, volume distribution, and brand-based insights — all based on the product metadata alone (excluding user reviews or ratings).

## **Introduction**
* In this project, I am building a web scraping script to extract structured product details from Nykaa, a popular beauty and cosmetics website. 
* Using Python and BeautifulSoup, I crawl through the website and retrieve information such as product names, brand, prices, and volumes for all the products listed on the 5 pages.
* The extracted data is then organized into a CSV file for further analysis.

---

## **Project Objective**
To collect and analyze body lotion product data from the Nykaa website — focusing on key attributes such as **product name, price, volume, and brand**. This project helps identify **pricing trends**, **volume distribution**, and **brand-wise insights**, without relying on customer reviews or ratings.
- Clearly define the purpose of this project — collecting Nykaa body lotion product data and analyzing key features like price, volume, and brand.

---

## **Workflow Overview**
###### `Data Collection → Data Understanding → Data Cleaning → Data Visualization → Insights`

---

## **Step 1: Import Required Libraries** 
Import all the necessary Python libraries for web scraping, data handling, and visualization

---

## **Step 2: Collect Product Links** 
Use requests and BeautifulSoup to extract product page links from multiple pages in Nykaa’s body lotion category.
ody lotinory.

---

## **Step 3: Define Scraping Functions**  
Define helper functions to extract details like product name, volume, and price from individulct pages.

---

## **Step 4: Scrape Product Data**  
Loop through each product link and use the defined functions to extrcttore the data.

---

## **Step 5: Creating a DataFrame**  
Convert the scraped data into a pandas DataFrame toentructured analysis.

---

## **Step 6: Clean and Extract Volume Data**  
Use regex to extract the numerical quantity (in ml/gm) foct volume descriptions.

---

## **Step 7: Extract Brand Name**  
Extract brand names from product titles by taking the firs r prefix in the product name.

---

## **Step 8: Final Cleanup**  
Clean the dataset by removing rows with missing or nalues in price or volume columns.

---

## **Step 9: Data Analysis & Visualizations**  
Analyze the clea data through various types of visualizations.

- ### **Step 9.1: Univariate Data Visualization**
  Explore the distribution of indivual variables like price and volume using histograms.

  - **Price Distribution**: Shows how product prices vary.  
  - **Volume Distribution**:derstand the frequency of different product sizes.  

    --
    
  - #### **Step 9.1.1: Pie Chart - Top Brands by Frequency**
    - Visualizes which brands appear most frequently in the dataset.
    
    --
    
  - #### **Discrete Data Visualization**  
    Focuses on categorical data like brands using bar charts.  
    - **Brand-wise rage Price**: Bar chart showing the average price per brand.

--

- ### **Step 9.2: Bivariate Data Visualization**  
  Visualize relationships between two variables.  

  - **Price vs Volume**:scatter plot to explore how product volume relates to its price.

--

- ### **Step 9.3: Correlation Matrix**  
  Visualize correlatiobetween numerical columns such as price, volume, and price-per-ml.

-- 

- ### **Step 9.4: Boxplot**  
  VPrice Distribution by Brand pare the price spread across different brands using a boxplot.

---

## **Step 10: Conclusion**  
Summarize the findings, key patterns observed, and what insights can be derived from the analysis. Also, briefly mention possible future improvements.

- We successfully scraped product data from Nykaa's body lotion section without relying on customer reviews or JavaScript-rendered content.
- We analyzed key metrics like **price**, **volume**, **brand distribution**, and **cost-effectiveness**.
- The results highlight affordable options, premium brands, and volume trends in the market.


This project demonstrates how basic product data can yield useful insights into an e-commerce platform's product segment.
