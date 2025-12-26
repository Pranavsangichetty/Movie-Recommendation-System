🎬 Movie Recommendation System

Content-Based Filtering using Genres

📝 Project Overview

This project implements a content-based movie recommendation system that suggests similar movies based on genre similarity. The system converts movie metadata into numerical features and applies similarity measures to deliver personalized recommendations without relying on user rating history.

The objective is to demonstrate data preprocessing, feature extraction, and recommendation logic, commonly used in streaming and entertainment platforms.

📂 Repository Contents

| File Name                  | Type            | Description                                                     |
| -------------------------- | --------------- | --------------------------------------------------------------- |
| movie_recommendation.ipynb | Python Notebook | End-to-end implementation of content-based recommendation logic |
| tmdb_5000_movies.csv       | Dataset         | Movie metadata including titles and genres                      |
| README.md                  | Documentation   | Project overview, methodology, and usage                        |

⚙️ Tech Stack

| Component            | Tool / Library    | Purpose                                    |
| -------------------- | ----------------- | ------------------------------------------ |
| Data Processing      | Pandas, NumPy     | Data cleaning and transformation           |
| Feature Engineering  | TF-IDF Vectorizer | Convert genre text into numerical features |
| Recommendation Logic | Cosine Similarity | Measure similarity between movies          |
| Programming Language | Python            | Core implementation                        |

🏗️ Data Preparation & Feature Engineering
1️⃣ Data Cleaning

Selected relevant attributes (Movie Title, Genres)

Parsed nested genre data into readable text format

Handled missing or inconsistent values

2️⃣ Feature Extraction

Transformed genre text into numerical vectors using TF-IDF

Created a similarity matrix using cosine similarity

🤖 Recommendation Logic

Identifies movies with similar genre compositions

Ranks recommendations based on similarity score

Returns top-N most similar movies for a selected title

📊 Output & Insights

Produces genre-based movie recommendations

Demonstrates how content-based systems work without user behavior data

Easily extensible to include cast, keywords, or overview text
