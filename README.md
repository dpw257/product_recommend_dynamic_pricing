# Product Recommendation with Customer Segmentation and Dynamic Pricing

## Project Overview

This project provides a system for tailoring product offers and discounts to individual customers to increase revenue. This is achieved by conducting customer segmentation based on their previous purchasing behaviour, recommending products based on recent purchases, and setting personalised discounts according to the customer's value to the company.



Methodology:
- Purchasing behaviour quantified using RFM scores (Recency, Frequency and Monetary value of the customer's prior purchases).
- New products suggested on the basis of the cosine distance between the TF-IDF of product descriptions.
- Competitor prices scraped from a price comparison site using BeautifulSoup.
- Dynamic pricing conducted based on competitor prices, sales history, cost, and stock levels.
- Discounts set according to customer RFM score.

---

## Table of contents

- [Project overview](#project-overview) 
- [Usage instructions](#usage-instructions)
- [License](#license) 

---

## Usage instructions

1. **Data Collection and Preprocessing:**
   - Run the notebook `product_data_website_scraper.ipynb` to scrape product descriptions and pricing data using BeautifulSoup.
   - Run the notebook `customer_segmentation_cleaning_EDA.ipynb` to clean customer and product datasets, assign RFM scores and segment customers based on their value to the company, and conduct EDA.

2. **Product Recommendation System:**
   - Run the notebook `product_tf-idf_recommend.ipynb` to tokenize product descriptions, calculate TF-IDF and cosine similarity for each previous purchase and recommend similar products for each customer.

3. **Dynamic Pricing:**
   - Run the notebook `dynamic_pricing.ipynb` to adjust prices on the entire product list dynamically based on competitor prices and sales trends, and implement personalised discounts on each reccommeneded product based on customer segment (value to the company).

5. **Evaluation:**
   - Assess the effectiveness of product recommendations by different demographics and suggest improvements.

---

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE](LICENSE.txt) file for details.

Copyright (c) [2024] [Daniel White]
