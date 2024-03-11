# E-commerce Data Analysis Dashboard

Welcome to the E-commerce Data Analysis Dashboard! 🎉🛍️ This dashboard provides insights into a Brazilian e-commerce dataset of orders made at Olist Store. Dive into the world of online shopping and explore trends, patterns, and customer behavior.

## About Dataset

This dataset offers a glimpse into the bustling world of Brazilian e-commerce, featuring 100k orders from 2016 to 2018 made across various marketplaces. 🇧🇷 Here's what you can expect:

- **Order Information**: View orders from multiple dimensions, including status, price, payment, and freight performance.
- **Customer Insights**: Explore customer location, product attributes, and reviews written by customers.
- **Geolocation Dataset**: We've even included a geolocation dataset that maps Brazilian zip codes to lat/lng coordinates. 🗺️

Join the fun and immerse yourself in the marketing funnel by Olist! 🔍 You can combine datasets to gain insights from a marketing perspective. Instructions on joining datasets are available on the Kernel.

## Context

This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist simplifies the process for small businesses across Brazil by connecting them to channels seamlessly and with a single contract. 🤝 Merchants can sell their products through Olist Store and ship them directly to customers using Olist logistics partners. Learn more on their website: [www.olist.com](www.olist.com)

After a customer makes a purchase on Olist Store, a seller is notified to fulfill the order. Once the product is delivered, customers receive a satisfaction survey by email, where they can rate their purchase experience and provide feedback. 📦✅

## Usage

To run the dashboard locally, follow these steps:

1. Install the required dependencies: `pip install -r requirements.txt`
2. Run the Streamlit app: `streamlit run dashboard/dashboard.py `

## Attention

- An order might contain multiple items.
- Each item might be fulfilled by a distinct seller.
- All text identifying stores and partners has been replaced with the names of Game of Thrones great houses. 🏰

Feel free to explore the dashboard and uncover fascinating insights into the world of Brazilian e-commerce! 🚀🛒

---

## Deployment

The dashboard has been deployed to Streamlit Cloud. You can access it [here](dashboard_url).

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit

[Explore the Dashboard](https://ridhamu-e-commerce-dataset.streamlit.app)
