# Electronics Recommendation System Using Python and Scrapy

This project builds a recommendation system for electronics like mobile phones, tablets, and laptops. It uses **Scrapy** for web scraping, processes the data, and recommends products based on **cosine similarity**. A **Streamlit** interface makes it user-friendly.

## Features
- **Data Scraping**: Scrapes Amazon for product data.
- **Data Cleaning**: Handles duplicates and missing values.
- **Recommendation Engine**: Implements cosine similarity for recommendations.
- **Interactive UI**: Built using Streamlit.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PlanetDestroyyer/Electronics-Recommendation-System-Using-Python-and-Scrapy.git
   cd Electronics-Recommendation-System-Using-Python-and-Scrapy

2. Install the required dependencies:

pip install -r requirements.txt



Usage

1. Scrape data using Scrapy:

scrapy crawl electronics_spider


2. Run the Streamlit app:

streamlit run app.py


3. Use the interface to browse and get product recommendations.



Future Improvements

Expand to support additional e-commerce platforms.

Implement machine learning models for improved recommendations.

Provide real-time scraping and recommendations.
