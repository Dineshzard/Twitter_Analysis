# 📊 Twitter Hashtag & Sentiment Analysis Dashboard

This Power BI dashboard presents a dynamic analysis of trending Twitter hashtags, user sentiment, tweet polarity, and subjectivity from scraped tweet data. The goal is to understand popular topics, emotional tones, and key influencers in real-time Twitter conversations.

---

## 🔍 Overview

Using tweet data scraped via Selenium, this project performs:

- Hashtag frequency analysis  
- Sentiment classification (Positive, Neutral, Negative)  
- Polarity and subjectivity mapping  
- Key influencer identification by username  
- Visual storytelling through interactive Power BI dashboards

---

## 📁 Dataset

The dataset contains the following fields:

- `Tweet`: Cleaned tweet text  
- `Username`: Tweet author  
- `Hashtags`: Extracted hashtags from tweets  
- `Sentiment`: Classified sentiment (Positive, Neutral, Negative)  
- `Polarity`: Sentiment polarity score (-1 to +1)  
- `Subjectivity`: Subjectivity score (0 to 1)  
- `count of tweets`: Number of tweets per user/hashtag  
- `Unique_users`: Count of unique users  

---

## 📊 Dashboard Features

| Visual | Description |
|--------|-------------|
| **Word Cloud** | Most frequent hashtags used |
| **Bar Chart** | Top hashtags by count (excluding nulls) |
| **Donut Chart** | Tweet sentiment distribution |
| **Bar Chart** | Tweets grouped by hashtags and sentiment |
| **Bar Chart** | Top users by number of tweets |
| **Polarity Chart** | Polarity of tweets (very negative to very positive) |
| **Subjectivity Chart** | Degree of opinion vs fact in tweets |

---

## ⚙️ Tools & Technologies

- **Power BI** – For dashboard creation and interactivity  
- **Python (Selenium)** – Web scraping tweets from X (formerly Twitter)  
- **pandas / textblob** – For text cleaning, sentiment analysis  
- **Power Query** – For transformations inside Power BI  

---

## 📌 Insights

- Trending hashtags like `#GoogleCloudNext`, `#Trump2024`, and `#COVID19` dominate tweet conversations.  
- Over **53%** of tweets show **positive sentiment**, indicating favorable engagement.  
- Top contributors include tech-focused accounts like *Outdoor Channel* and *Google Cloud Tech*.  
- Many tweets are **opinion-driven**, with high subjectivity levels.

---

## 🚀 How to Use

1. Clone this repo and open the Power BI `.pbix` file  
2. Refresh the data if needed  
3. Use slicers to filter by `Username` or `Sentiment`  
4. Hover over visuals for detailed tooltips and insights

---

## 📥 Future Improvements

- Automate data refresh with scheduled scraping  
- Include tweet timestamps to analyze trends over time  
- Add geographic filtering (if location data available)  
- Integrate more platforms like YouTube/Reddit trends

---

## 🙌 Acknowledgements

- Tweet data extracted from **X (Twitter)** using **Selenium**  
- Sentiment analysis powered by **TextBlob**  
- Inspired by trending analytics and social listening use cases

---

## 📎 Author

**Dinesh Zard**  
🔗 [LinkedIn](https://www.linkedin.com/in/zarddinesh)  
📬 For questions or suggestions, feel free to connect!

