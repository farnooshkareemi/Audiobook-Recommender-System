🎧 Audiobook Recommender System

This project develops an audiobook recommendation system based on data collected from the Ketabrah website. It uses web scraping, data visualization, and machine learning techniques to suggest books tailored to user interests.

📘 Overview

The system analyzes audiobook data — including author, narrator, genre, year, price, duration, and user ratings — to recommend books similar to those a user likes.

It includes:

Data collection via web scraping (Octoparse, BeautifulSoup)

Data visualization with Power BI

Preprocessing and analysis using Python (Jupyter Notebook)

Content-based recommender system using TF-IDF and cosine similarity

Interactive web app built with Streamlit

🧠 Technologies Used

Python, BeautifulSoup, Octoparse

Power BI for visualization

Scikit-learn for TF-IDF and cosine similarity

Streamlit for deployment

⚙️ How to Run

Install required packages:

pip install streamlit scikit-learn pandas numpy


Run the app:

streamlit run app.py


Select a book title — the system recommends similar audiobooks from the dataset.

📊 Key Features

Visual dashboards of audiobook data

Preprocessing and encoding (one-hot, TF-IDF)

Cosine similarity–based recommendation

Simple, user-friendly web interface
