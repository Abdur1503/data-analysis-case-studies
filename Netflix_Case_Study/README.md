#📊 Netflix Content Strategy – Data Analysis Case Study
📝 Problem Statement:
Analyze the Netflix content dataset to generate actionable insights on what types of shows/movies Netflix should invest in and how they can grow across different countries.

📂 Dataset:
Source: NetflixIntro.csv

8,807 unique records of Netflix content including title, type, country, release year, genre, rating, duration, etc.

🔧 Tools & Libraries Used:
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook / Google Colab

Data Cleaning, Wrangling, EDA

🧹 Data Cleaning Highlights:
Converted date_added to datetime and handled missing/null values

Exploded comma-separated fields (country, director, cast, listed_in) for granular analysis

Standardized and grouped genres (e.g., merging similar types like "TV Dramas" and "Dramas")

Handled incorrect and inconsistent entries in rating, duration, and other key fields

📈 Key Insights:
Top Countries by Content Production:

USA, India, and the UK dominate in number of shows/movies.

Over 30% of Netflix’s catalog comes from the US.

Rating Patterns:

Majority of content is rated TV-MA and TV-14.

Outliers in rating column were identified and removed.

Genre Consolidation:

Genres were regrouped to improve clarity (e.g., Anime, Documentaries, Horror).

Action, Drama, and Comedy dominate the catalog.

Director and Cast Analysis:

Martin Scorsese, Spielberg, and others are top contributors.

No director accounts for more than 1% of all content, hence filling missing values with Unknown.

Release Trends:

Significant growth in content post-2015.

Anomalies (like content listed before release) were identified and filtered.

📌 Conclusions & Recommendations:
Localized Content Investment:

Continue focusing on markets like India, UK, South Korea.

Consider expanding into emerging countries with <50 entries.

Genre Focus:

High demand in Action, Drama, and Comedy should guide future production.

Growth potential in genres like Anime, Horror, and Sci-Fi.

Data Quality Emphasis:

More structured metadata can help better recommendation algorithms.


