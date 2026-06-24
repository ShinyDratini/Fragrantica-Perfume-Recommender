# Fragrantica-Perfume-Recommender
Fragrantica Perfume Recommender – A content-based recommendation engine that suggests similar fragrances using scent accords, notes, ratings, and user preference similarity analysis. Built with Python, Pandas, and Scikit-learn.


🌸 Fragrantica Perfume Recommender
Project Overview

This project develops a content-based perfume recommendation system using fragrance data from Fragrantica. By analyzing perfume accords, ratings, popularity, and fragrance characteristics, the system recommends scents that are most similar to a user's favorite perfume.

The goal is to help fragrance enthusiasts discover new perfumes with similar scent profiles while demonstrating practical applications of data analytics, feature engineering, and recommendation systems.

Business Problem

With thousands of fragrances available in the market, finding perfumes that match personal preferences can be challenging. Traditional searches often rely on brand reputation or user reviews, which may not accurately reflect scent similarity.

This project addresses the problem by using fragrance attributes to identify perfumes with comparable scent profiles and recommend suitable alternatives.

Dataset

The dataset contains fragrance information collected from Fragrantica, including:

Perfume Name
Brand
Average Rating
Number of Votes
Gender
Main Accords
Fragrance Notes
Popularity Metrics
Sample Dataset
Perfume	Brand	Rating	Main Accords
Jubilation XXV Man	Amouage	4.38	Amber, Sweet, Warm Spicy, Woody
Jubilant	Killer Oud	4.40	Amber, Sweet, Warm Spicy
Golden Rush	Alexandria Fragrances	4.41	Amber, Woody, Warm Spicy
Project Workflow
1. Data Cleaning
Removed duplicate records
Standardized accord formatting
Processed missing values
Cleaned text-based fragrance attributes
2. Feature Engineering

Fragrance characteristics were transformed into machine-readable features:

Main accords
Gender classification
Ratings
Vote counts
Fragrance profile descriptors
3. Similarity Analysis

A content-based filtering approach was used to identify perfumes with similar fragrance profiles.

Techniques include:

Text Vectorization
Feature Encoding
Cosine Similarity
Similarity Ranking
Example Recommendation
Input

Jubilation XXV Man (Amouage)

Recommended Perfumes
Rank	Perfume	Brand	Similarity Score
1	Jubilant	Killer Oud	0.428
2	Mouj Jubilee XXVI	Milestone Perfumes	0.390
3	Golden Rush	Alexandria Fragrances	0.388
4	Spectre 575 - 149 Shadows Of Bergamot	Alûstre	0.370
Technologies Used
Python
Pandas
NumPy
Scikit-Learn
Jupyter Notebook
Key Skills Demonstrated
Data Analytics
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Machine Learning
Recommendation Systems
Similarity Modelling
Content-Based Filtering
Programming
Python
Data Manipulation
Data Transformation
Repository Structure
Fragrantica-Perfume-Recommender/
│
├── data/
│   └── perfume_dataset.csv
│
├── notebooks/
│   └── perfume_recommender.ipynb
│
├── screenshots/
│   ├── recommendation_example.png
│   └── dataset_overview.png
│
├── README.md
│
└── requirements.txt
Results

The recommendation engine successfully identifies perfumes with highly similar scent profiles by leveraging fragrance accords and perfume characteristics.

This demonstrates how recommendation systems can be applied beyond traditional e-commerce use cases and highlights the effectiveness of content-based filtering for preference-driven product discovery.

Future Enhancements
Incorporate fragrance notes in addition to accords
Develop a hybrid recommendation system
Create a Streamlit web application
Add user preference personalization
Deploy as an interactive web-based recommendation tool
