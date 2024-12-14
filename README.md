# Product Recommendation with Customer Segmentation and Dynamic Pricing

## Project Overview

This project focuses on improving marketing strategies by segmenting customers based on their purchasing behavior, recommending personalized products, and dynamically adjusting prices to maximize profit. It combines customer segmentation, product clustering, and dynamic pricing with a recommendation system to target customers more effectively.

The goal of this project is to:
- Segment customers based on their purchasing behaviour using RFM (Recency, Frequency, Monetary) scores.
- Recommend products for each customer based on clustering of product descriptions using TF-IDF.
- Scrape competitor prices from a price comparison site to adjust product pricing.
- Implement dynamic pricing based on competitor prices, sales history, cost, and stock levels.
- Evaluate the success of different marketing strategies across customer demographics.

- **Customer Segmentation:** Segmenting customers into groups based on their recency, frequency, and monetary value (RFM).
- **Product Recommendation System:** Using TF-IDF to cluster products based on their descriptions and recommend relevant products to customers.
- **Dynamic Pricing:** Adjusting prices based on competitor pricing, product sales, cost, and stock quantity.
- **Competitor Price Scraping:** Scraping price data from competitor websites using BeautifulSoup to ensure competitive pricing.
- **Evaluation of Marketing Strategies:** Assessing the effectiveness of the product recommendations for different customer demographics (e.g., business, student, standard customers).


---

## Table of contents

- [Project overview](#project-overview) 
- [Repository files](#repository-files) 
- [Usage instructions](#usage-instructions)
- [License](#license) 

---

## Repository files
- **product_data_website_scraper.ipynb**: Notebook to scrape product and pricing data
- **customer_segmentation_cleaning_EDA.ipynb**: Notebook to clean data and conduct EDA with visualisations
- **product_tf-idf_recommend.ipynb**: Notebook to calculate TF-IDF and cosine similarity for each previous purchase and recommend product
- **dynamic_pricing.ipynb**: Notebook to adjust prices dynamically and implement personalised discounts

---

## Usage instructions

1. **Data Collection and Preprocessing:**
   - Load customer and product datasets and clean the data by removing duplicates and non-English descriptions.
   - Scrape competitor prices using BeautifulSoup.

2. **Customer Segmentation:**
   - Run the customer segmentation script to assign RFM scores and segment customers based on their value to the company.

3. **Product Recommendation System:**
   - Tokenize product descriptions and calculate TF-IDF scores.

4. **Dynamic Pricing:**
   - Adjust prices for recommended products based on competitor pricing, cost, and stock levels.

5. **Evaluation:**
   - Assess the effectiveness of product recommendations by different demographics and suggest improvements.

---

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE](LICENSE) file for details.

Copyright (c) [2024] [Daniel White]