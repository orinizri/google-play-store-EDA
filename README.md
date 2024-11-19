# Google Play Store Exploratory Data Analysis

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)

## About <a name = "about"></a>

This project focuses on exploratory data analysis (EDA) of the Google Play Store dataset. The goal is to uncover insights about app categories, user ratings, reviews, pricing, and installation trends. Through this analysis, we aim to understand the factors influencing app success and user engagement on the platform.

### Dataset
The dataset contains details about apps available on the Google Play Store, including:
- App Name: Name of the app.
- Category: App category (e.g., Games, Productivity, Health).
- Rating: User ratings (0–5).
- Reviews: Number of user reviews.
- Size: App size (e.g., "Varies with device", "20M").
- Installs: Number of installations (e.g., "1,000+", "10M+").
- Type: Free or Paid.
- Price: Cost of the app (if paid).
- Last Updated: Date the app was last updated.
- Current Ver: Current version of the app.
- Android Ver: Minimum Android version required.

### Understand the Dataset:
1. Clean and preprocess the data for analysis.
2. Handle missing or inconsistent values (e.g., "Varies with device").

### Visualization:
1. Generate insightful plots using tools like Matplotlib and Seaborn.
2. Showcase trends and relationships in the data.

### Statistical Inference
1. Check correlations between variables.
2. Make hypothesis testings on various variables.

### Questions that might be interesting to investigate
- What categories are most popular?
- How do ratings and reviews impact app success?
- What is the trend for free vs. paid apps?
- How does app size or last update affect downloads and user ratings?
- Are there statistically significant differences between app categories?

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

1. Python 3.x
2. Jupyter Notebook or a Python IDE (e.g., VSCode, PyCharm)

### Installing

Clone the Repository:
git clone https://github.com/orinizri/google-play-store-eda.git
cd google-play-store-eda

Install Required Libraries:
pip install pandas numpy matplotlib seaborn

Run the Notebook: Open the Jupyter Notebook file (Google_Play_Store_EDA.ipynb) to follow the analysis.
