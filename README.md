# Customer-Centric Product Recommendation System: Walmart Reviews Analysis

This repository demonstrates the creation of a **content-based recommendation system** using a rich dataset of product reviews and metadata from Walmart. By leveraging machine learning and natural language processing (NLP) techniques, this project showcases how to provide personalized product recommendations based on user preferences and product features.

---

## Project Overview

E-commerce platforms thrive on accurate and user-friendly recommendation systems. In this project, we develop a content-based recommendation model to analyze and predict product preferences based on reviews, ratings, and product descriptions. The pipeline includes data preprocessing, feature engineering, similarity computation, and recommendations generation.

---

## Dataset Details

The dataset consists of **5,000 Walmart product reviews and metadata** with 32 attributes, including:

- **Product Details**: Name, Category, Brand, Price, Description
- **Customer Engagement**: Ratings, Reviews Count
- **Market Insights**: Retailer, Product Tags, Availability

The dataset is stored in `marketing_sample_for_walmart_com.tsv`, with attributes essential for implementing content-based filtering.

---

## Key Features of the Project

1. **Data Preprocessing**:
   - Cleaning and preparing text data using **NLP** techniques.
   - Handling missing values and categorical encoding for non-text features.

2. **Feature Engineering**:
   - Transforming product descriptions into numerical representations using **TF-IDF Vectorization**.
   - Calculating **Cosine Similarity** for product recommendation scores.

3. **Recommendation System**:
   - Generating personalized product recommendations based on content similarity.
   - Ranking products by relevance to user preferences.

4. **Data Visualization**:
   - Exploring dataset insights using **matplotlib** and **seaborn**.

---

## Project Structure

- **Notebook**: `Recommendation.ipynb`  
  Contains the entire pipeline from data loading to model evaluation.
- **Dataset**: `marketing_sample_for_walmart_com.tsv`  
  Input data used for training and testing the recommendation system.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Christiansada/Customer-Centric-Product-Recommendation.git
   cd Customer-Centric-Product-Recommendation


2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt


3. Open the Jupyter Notebook:
  ```bash
  jupyter notebook Recommendation.ipynb
