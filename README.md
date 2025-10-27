# YouTube-Trending-Video-Analytics
This project analyzes a dataset of trending YouTube videos to uncover insights into what makes a video popular - focusing on views, likes, dislikes, categories, and publishing trends.  
It combines **Python** for data cleaning and exploration with **Tableau** for interactive visualization and storytelling.


## Objectives

- Identify patterns in trending videos  
- Analyze engagement metrics (views, likes, dislikes)  
- Compare performance across categories and regions  
- Visualize most popular genres and sentiment trends  
- Create a final dashboard summarizing findings


##  Tools and Technologies

| Tool | Purpose |
|------|----------|
| **Python (Pandas, Matplotlib, Seaborn)** | Data Cleaning and EDA |
| **Tableau** | Dashboard and Storytelling |
| **Excel** | Data Preprocessing |
| **CSV Dataset** | YouTube Trending Videos (1,000+ rows) |



##  Dataset Overview

**Columns:**
- `Rank` – Position of the video in the trending list  
- `Video` – Video title  
- `Video Views` – Number of views  
- `Likes` – Number of likes  
- `Dislikes` – Number of dislikes (contains missing values)  
- `Category` – Video genre (e.g., Music, Education, Entertainment)  
- `Published` – Date or flag showing whether video is published  



##  Data Cleaning

Performed using **Python** and **Excel**:
- Handled missing values in `Dislikes` and `Category`
- Removed duplicate rows  
- Standardized text formatting in `Category` column  
- Converted numeric columns to appropriate data types  



## Visualizations in Tableau

### Dashboard Includes:
1. **Top Categories by Views**
   - Bar chart comparing average views across categories.  
2. **Likes vs Views Correlation**
   - Scatter plot to observe engagement trends.  
3. **Category-wise Sentiment Overview**
   - Pie chart showing distribution of categories.  
4. **Trending Duration Over Time**
   - Line chart showing publishing frequency.  
5. **Interactive Filters**
   - Region or category filters to explore insights dynamically.  



##  Key Insights

- Music and Entertainment dominate the trending charts.  
- Videos with positive and catchy titles tend to receive higher engagement.  
- Some categories like Education show steady growth in engagement.  
- Dislike counts have less influence compared to likes and views.  
