# 🎬 Amazon Prime Video Analysis – Power BI Dashboard

## 📊 Dashboard Overview
This Power BI project provides an interactive analysis of **Amazon Prime Video**'s content library. 
It explores content type distribution, release trends, genre popularity, regional availability, 
and rating classification to help understand platform strategy and viewer targeting.

Dataset: `AMAZON_PRIME_VIDEO`

---

## **Chart 1 – Total Shows by Country**
- **Chart Type:** Filled Map  
- **Dataset:** `AMAZON_PRIME_VIDEO`  
- **Field:** `Country`  
- **Values:** `Count of Show ID`  
- **Insight:** Shows geographic distribution of content availability. The United States, India, and Japan lead in content count.

---

## **Chart 2 – Movies vs TV Shows**
- **Chart Type:** Donut Chart  
- **Dataset:** `AMAZON_PRIME_VIDEO`  
- **Legend:** `Type` *(Movie, TV Show)*  
- **Values:** `Count of Show ID`  
- **Insight:** Movies dominate the library with 80.82% share, TV Shows at 19.18%.

---

## **Chart 3 – Release Trend Over Time by Type**
- **Chart Type:** Column Chart  
- **Dataset:** `AMAZON_PRIME_VIDEO`  
- **X-Axis:** `Release Year`  
- **Y-Axis:** `Count of Show ID`  
- **Legend:** `Type` *(Movie, TV Show)*  
- **Insight:** Content growth trends over decades, showing peaks in certain years.

---

## **Chart 4 – Content Rating Distribution**
- **Chart Type:** Bar Chart  
- **Dataset:** `AMAZON_PRIME_VIDEO`  
- **X-Axis:** `Rating` *(13+, PG, TV-14, etc.)*  
- **Y-Axis:** `Count of Show ID`  
- **Insight:** Majority of content is rated 13+, followed by 16+, ALL, and 18+.

---

## **Chart 5 – Popular Genres by Volume**
- **Chart Type:** Bar Chart  
- **Dataset:** `AMAZON_PRIME_VIDEO`  
- **X-Axis:** `Genre (Listed In)`  
- **Y-Axis:** `Count of Show ID`  
- **Insight:** Drama and Comedy are the most popular genres, with hybrid genres like Drama, Suspense and Comedy, Drama also ranking high.

---

## 📊 Summary KPIs
- **Total Titles:** 9,655  
- **Total Ratings:** 25  
- **Total Genres:** 519  
- **Total Directors:** 5,771  
- **Start Date:** 1920  
- **End Date:** 2021  

---

## 📥 Dashboard Access
[📄 View Dashboard PDF](https://github.com/sathishkumarj03/amazon-prime-analysis/raw/main/AmazonPrimeVideo_Dashboard.pdf)  
<!-- Replace with your GitHub username and file path -->

---

## 👨‍💻 Created by
**Sathish** – Power BI & SQL Developer
