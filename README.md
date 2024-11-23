# Electronics Recommendation System Using Python and Scrapy

This project builds a recommendation system for electronics like mobile phones, tablets, and laptops. It uses **Scrapy** for web scraping, processes the data, and recommends products based on **cosine similarity**. A **Streamlit** interface makes it user-friendly.

## Features
- **Data Scraping**: Scrapes Amazon for product data.
- **Data Cleaning**: Handles duplicates and missing values.
- **Recommendation Engine**: Implements cosine similarity for recommendations.
- **Interactive UI**: Built using Streamlit.

## Installation and Usage

1. **Install the required dependencies**:
   Clone the repository and navigate to the project directory, then install the dependencies listed in `requirements.txt`:
   ```bash
   git clone https://github.com/PlanetDestroyyer/Electronics-Recommendation-System-Using-Python-and-Scrapy.git
   cd Electronics-Recommendation-System-Using-Python-and-Scrapy
   pip install -r requirements.txt

2. Run the Scrapy Spider to scrape data: Use Scrapy to scrape product data from Amazon:

scrapy crawl electronics_spider


3. Run the Streamlit app: Start the Streamlit app to use the user interface for browsing and getting product recommendations:

streamlit run app.py





