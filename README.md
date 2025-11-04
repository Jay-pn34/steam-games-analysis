# Steam Games Analysis

An exploratory data analysis (EDA) project on Steam’s game dataset, collected on **July 10, 2025**. This repository explores game trends, genre popularity, ratings, pricing in INR, and player activity over the years using visualizations like treemaps, bubble charts, and word clouds.

The analysis provides insights for gamers, developers, and researchers interested in gaming trends and user engagement on the Steam platform.

---

## 📊 Features

* **Treemap of Genres**: Visualizes the popularity of game genres based on followers and average rating.
* **Bubble Chart Analysis**: Shows relationships between price, rating, and current online players over time.
* **Word Cloud Visualization**: Highlights common words in game titles with colorful visual representation.
* **Price Conversion**: All monetary values are converted to Indian Rupees (INR) for localized context.

---

## 🗂 Repository Structure

```
steam-games-analysis/
│
├── data/               # Original and cleaned datasets
├── notebooks/          # Jupyter notebooks for EDA
├── images/             # Saved plots and visualizations
├── README.md
```

---

## 💻 Installation

1. Clone the repository:

```
git clone https://github.com/your-username/steam-games-analysis.git
cd steam-games-analysis
```

2. Open Jupyter Notebook and start exploring:

```
jupyter notebook
```

---

## 📈 Usage

* All notebooks are self-contained with explanations and visualizations.
* Use `data/cleaned_data.xlsx` to recreate the analyses.
* Modify or add your own visualizations to extract more insights.

---

## 🛠 Tools & Libraries

* Python 3.13.0
* Pandas – Data manipulation and analysis
* Matplotlib & Seaborn – Visualization
* Squarify – Treemap plotting
* WordCloud – Word cloud visualization
* Jupyter Notebook – Interactive exploration

---

## Visualizations  

This project includes a variety of visualizations to illustrate trends and insights from Steam games data.  

### Graphs  

![Rating Trends by Genre](Images/graphs/14_rating_trends_by_genre_fixed.png)  
*Rating trends across different genres.*  

![Treemap of Genre Hierarchy](Images/graphs/18_treemap_genre_hierarchy_with_legend.png)  
*Treemap showing the number of games and average ratings by genre.*  

![Sunburst of Year, Genre, and Game](Images/graphs/19_sunburst_year_genre_game.png)  
*Hierarchical sunburst chart of game releases by year and genre.*  

![Stacked Bar: Releases by Year & Genre](Images/graphs/1_stacked_bar_releases_by_year_genre.png)  
*Stacked bar chart showing game releases over years across genres.*  

![Average Discount by Genre](Images/graphs/2_bar_avg_discount_by_genre.png)  
*Average discount offered across different genres.*  

![Scatter: Rating vs Current Online Players](Images/graphs/3_scatter_rating_vs_current_online_with_legend_log.png)  
*Scatter plot showing the relationship between rating and current online players.*  

![Top 20 Games: Followers vs Current Players](Images/graphs/4_scatter_follows_vs_current_online_top20_custom_legend.png)  
*Top 20 games by followers vs current online players.*  

![Line Chart: Current vs Peak Players](Images/graphs/5_line_current_vs_peak_players_colored_years.png)  
*Line chart showing trends of current vs peak players over years.*  

![Top 50 Games by Peak Players](Images/graphs/6_bar_top50_by_peak_players_colored.png)  
*Bar chart of top 50 games ranked by peak players.*  

![Average Rating by Year](Images/graphs/7_line_avg_rating_by_year_styled_top_bottom_close.png)  
*Line chart showing average ratings of games by year.*  

![Heatmap: Month vs Year Average Ratings](Images/graphs/8_heatmap_month_vs_year_avg_rating.png)  
*Heatmap showing average ratings across months and years.*  

---

### Wordclouds  

#### By Time Period  

![Wordcloud 1983-1987](Images/wordclouds/wordcloud_1983_1987.png)  
![Wordcloud 1988-1992](Images/wordclouds/wordcloud_1988_1992.png)  
![Wordcloud 1993-1997](Images/wordclouds/wordcloud_1993_1997.png)  
![Wordcloud 1998-2002](Images/wordclouds/wordcloud_1998_2002.png)  
![Wordcloud 2003-2007](Images/wordclouds/wordcloud_2003_2007.png)  
![Wordcloud 2008-2012](Images/wordclouds/wordcloud_2008_2012.png)  
![Wordcloud 2013-2017](Images/wordclouds/wordcloud_2013_2017.png)  
![Wordcloud 2018-2022](Images/wordclouds/wordcloud_2018_2022.png)  
![Wordcloud 2023-2025](Images/wordclouds/wordcloud_2023_2025.png)  

#### All Games Combined  

![Wordcloud All Years](Images/wordclouds/wordcloud_all_years.png)  
*Wordcloud of all game names from the dataset.*

---

## Key Insights

* Platformer, Shooter, and Arcade genres offer the highest discounts (ranked 1st, 2nd, and 3rd respectively).
* Average ratings were higher for games before 2005, with 1989 being the highest and 1991 the lowest.
* Sandbox and Shooter dominate in number of games but Puzzle games have higher average ratings.
* Current vs Peak players trends show higher engagement for games from 2012, 2013, and 2007; peak players highest for 2012, 2000, and 1997.

---

## 📂 Data Source

The dataset is a cleaned version of Steam’s publicly available game data, gathered on **July 10, 2025**.

---

## 🔗 Author

* Jaykumar Patel
* [GitHub](https://github.com/Jay-pn34)
* [LinkedIn](https://www.linkedin.com/in/jaykumar-patel-6a0b26232/)

---

## 📌 License

This project is licensed under the MIT License. See the LICENSE file for details.
