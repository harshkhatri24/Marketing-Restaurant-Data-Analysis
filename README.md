# 🍽️ Marketing Project – Restaurant Data Analysis
Data analysis project for identifying restaurant trends and insights using visual exploration.

## 📌 Project Overview
- This project focuses on analyzing restaurant data to help a **restaurant consolidator** revamp its B2C platform using intelligent automation techniques.  
- The main objective is to explore restaurant trends, understand customer preferences, and identify high-performing restaurants through data analysis and visualization.

---

## 🎯 Problem Statement
A restaurant aggregator is seeking to enhance its consumer-facing platform.  
It aims to:
- Recommend top restaurants,
- Understand market coverage,
- Identify key performance metrics across various cities.

To achieve this, the dataset needs to be explored to extract meaningful insights before building any intelligent recommendation model.

---

## 🛠️ Tools Used
- **Python (Pandas, Matplotlib, Seaborn)** – for data preprocessing and EDA
- **Tableau** – for dashboarding and interactive data exploration

---

## 🔍 Approach & Analysis

### 1. 📋 Data Import & Cleaning

#### Importing necessary libraries and loading dataset
![Importing Libraries & Loading Data](marketing_screenshots/import_dataset.jpg)

#### Understanding data structure, cleaning variable names, and handling missing values
![Structure & Cleaning](marketing_screenshots/structure_cleaning.jpg)

#### Part of handling missing values
![Handling Missing Values](marketing_screenshots/handling_missing_values.jpg)

---

### 2. 📊 Exploratory Data Analysis (EDA)

#### Distribution of Ratings  
Histogram with KDE and boxplot to understand the spread of ratings.
![Ratings Distribution](marketing_screenshots/ratings_distribution.jpg)

#### Relationship between Aggregate Ratings and Number of Cuisines  
Boxplot showing how the number of cuisines influences ratings.
![Ratings vs Cuisines](marketing_screenshots/ratings_vs_cuisines.jpg)

#### Ratio of Booking vs Non-Booking Restaurants  
Pie chart comparing restaurants that allow table booking vs those that don’t.
![Table Booking Ratio](marketing_screenshots/booking_ratio.jpg)

---

### 3. 📈 Dashboarding

An interactive **Tableau Dashboard** was created with the following components:

- **Key KPIs** – to provide a quick snapshot of important restaurant metrics  
- **Restaurant Distribution** – column chart showing the number of restaurants across different cities  
- **Table Booking Availability** – pie chart showing Yes/No distribution  
- **Online Delivery Availability** – pie chart showing Yes/No distribution  
- **Restaurants by Ratings & Votes** – scatter plot to visualize customer engagement vs. ratings  
- **Cuisine Popularity** – column chart displaying the most popular cuisines  
- **Franchise Popularity** – column chart highlighting franchises with the widest reach

![Tableau Dashboard](marketing_screenshots/tableau_dashboard.jpg)

---

## 🧠 Key Insights

- **City-wise Coverage:** Some cities dominate the restaurant landscape, while others have very limited presence.  
- **Booking & Delivery Trends:** A significant portion of restaurants either allow table booking or online delivery, with noticeable differences in distribution between the two services.  
- **Ratings & Engagement:** Restaurants with higher ratings generally have higher votes, indicating stronger customer engagement.  
- **Cuisine Popularity:** Certain cuisines (e.g., [insert top cuisines from your analysis]) are consistently popular across cities.  
- **Franchise Reach:** A few franchises have a strong national presence, making them prime candidates for targeted marketing and promotions.  
- **Cost & Ratings:** Restaurants with competitive pricing and multiple cuisine offerings tend to receive better ratings.

---

## ✅ Conclusion
This analysis provides valuable insights into restaurant trends, customer preferences, and key performance metrics.  
It lays the groundwork for building a **data-driven recommendation system** for the restaurant aggregator.

---

> 📌 **Note:** Dataset and source code are not included to maintain project originality and intellectual ownership.
