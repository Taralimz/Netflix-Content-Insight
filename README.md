# 🎬 Netflix Content Analysis

This project explores the storytelling heartbeat behind Netflix’s global catalog—uncovering trends in content growth, genres, runtimes, and the emotional themes woven into descriptions.

---

## 🔍 Key Highlights

### 1. 📈 Content Boom Post-2016  
Netflix's catalog surged after 2016, peaking around 2019. Movies make up about **70%** of titles, while TV shows account for the rest.

<p align="center">
  <img src="/images/content_type_pie.png" width="300">
  <img src="images/content_growth_by_type.png" width="600">
</p>

---

### 2. 🌍 Centers of Creation  
- **USA** leads by a wide margin, followed by **India** and the **UK**.  
- **Thai content** spiked in 2018, mostly as international movies and dramas.

<p align="center">
  <img src="images/top10_countries.png" width="400">
  <img src="images/thai_by_year.png" width="400">
  <img src="images/thai_categories.png" width="450">
</p>

---

### 3. ⏱️ How We Watch  
- Movies cluster between **80–100 minutes**—classic feature length.  
- Over **60% of TV shows** run just **1 season**, hinting at a preference for shorter series.

<p align="center">
  <img src="images/movie_duration_hist.png" width="400">
  <img src="images/tv_seasons_dist.png" width="400">
</p>

---

### 4. 🎭 Genre Focus  
Netflix features a rich mix of **international titles**, especially:  
- **Movies**: International Movies, Dramas, Comedies  
- **TV Shows**: International TV Shows, Dramas, Crime series  

<p align="center">
  <img src="images/top_movie_genres.png" width="400">
  <img src="images/top_tv_genres.png" width="400">
</p>

---

### 5. 🔞 Mature Content  
**TV-MA** is the dominant rating, revealing a strong orientation toward adult audiences. Movies carry more **R** and **PG-13** content than their TV counterparts.

<p align="center">
  <img src="images/rating_popularity.png" width="400">
  <img src="images/rating_by_type.png" width="600">
</p>

---

### 6. 🧠 Story Themes  
Netflix content consistently leans into **emotional, human-centered storytelling**.  
Keywords extracted from thousands of show descriptions reveal a strong presence of words such as:

- **life** (2.19%)  
- **young** (1.94%)  
- **new** (1.90%)  
- **family** (1.77%)  
- **world** (1.68%)  
- **man** (1.57%)  

These frequent terms point to recurring themes of **personal growth**, **relationships**, and **identity**, often exploring the **challenges of youth**, the **complexity of love**, and the **connections that define us**.

<p align="center">
  <img src="images/netflix_wordcloud.png" width="600">
</p>
---

## 🛠 Tools & Data  
- Python: `pandas`, `matplotlib`, `seaborn`, `wordcloud`  
- Jupyter Notebook  
- Source: Netflix Titles Dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 👤 About Me  
**Pakawat Raskasin**  
Master’s in Data Science | Passionate about media insights & data narratives  
🔗 [LinkedIn](https://www.linkedin.com/in/pakawat-raskasin/) | [GitHub](https://github.com/Taralimz)
