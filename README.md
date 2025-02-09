# 🎬 Netflix Movie Recommendation System

## 📌 Project Overview
This project focuses on building a **movie recommendation system** for **Netflix** by analyzing a dataset of over **8,800 titles**, including both **movies and TV shows**. The goal is to enhance user experience by recommending relevant content based on exploratory data analysis (EDA) and **content similarity techniques**.

By leveraging **statistical analysis, machine learning, and data visualization**, this project explores user viewing patterns, genre preferences, and content trends to **improve recommendation accuracy**.

---

## 🎯 Project Objectives
- **Conduct Exploratory Data Analysis (EDA)**: Identify **trends, patterns, and insights** from the Netflix dataset.
- **Understand User Preferences**: Analyze key factors like **genre, ratings, release year, and content type**.
- **Develop a Movie Recommendation System**: Implement **content-based filtering** using similarity measures.
- **Evaluate Performance**: Assess the effectiveness of the recommendation system and propose improvements.
- **Analyze Temporal Trends**: Study how **genres, ratings, and content types** have evolved over time.

---

## 📊 Dataset Information
- **Dataset Source**: Kaggle - Netflix Movies and TV Shows Dataset
- **Total Entries**: **8,807 titles**
- **Key Features**:
  - **Title**: Name of the movie or TV show.
  - **Type**: Whether it's a **Movie** or a **TV Show**.
  - **Director**: Name of the director(s).
  - **Cast**: List of main actors.
  - **Rating**: Age certification (e.g., PG-13, TV-MA).
  - **Listed_in**: Genre of the content.
  - **Release_Year**: Year when the movie/show was released.
  - **Duration**: Movie length or TV show seasons.
  - **IMDB Scores**: User ratings.
  - **TMDB Popularity**: Popularity score from TMDB.

---

## 🏗 Methodology & Implementation

### 🔹 Data Preprocessing
- **Handling Missing Values**: Imputed or removed missing values in key attributes.
- **Removing Duplicates**: Ensured dataset consistency by filtering duplicate entries.
- **Fixing Data Inconsistencies**: Standardized genre names and rating formats.

### 🔹 Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Analyzed **release years, duration, and ratings**.
- **Bivariate Analysis**: Explored relationships between **release year, content type, and duration**.
- **Multivariate Analysis**: Used **correlation analysis, PCA, and clustering techniques**.

### 🔹 Recommendation System
- **Content-Based Filtering**: Utilized **cosine similarity** to recommend movies based on genre and description.
- **Similarity Measures**: Calculated **text similarity** between movie descriptions.
- **Feature Engineering**: Extracted important attributes for recommendations.

---

## 📌 Key Insights from the Project
- **📊 Content Distribution**:
  - **69.6% Movies** and **30.4% TV Shows**.
  - Netflix has focused more on movies than TV series.

- **🎬 Most Popular Genres**:
  - **International Movies and Dramas** dominate the platform.
  - Stand-up comedy and documentaries are also gaining traction.

- **📅 Release Year Trends**:
  - A **spike in content releases** from **2015 onwards**.
  - Older movies (pre-2000) are fewer, with most content being recent.

- **📈 User Preferences**:
  - **Mature content (TV-MA, TV-14) dominates Netflix**.
  - **United States and India** are the top content-producing countries.

---
