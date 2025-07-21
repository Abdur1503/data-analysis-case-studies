# 📊 Netflix Content Strategy – Data Analysis Case Study
## 📝 Problem Statement:
Analyze the Netflix content dataset to generate actionable insights on what types of shows/movies Netflix should invest in and how they can grow across different countries.

## 📂 Dataset:
Source: NetflixIntro.csv

8,807 unique records of Netflix content including title, type, country, release year, genre, rating, duration, etc.

## 🔧 Tools & Libraries Used:
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook / Google Colab

Data Cleaning, Wrangling, EDA

## 🧹 Data Cleaning Highlights:
Converted date_added to datetime and handled missing/null values

Exploded comma-separated fields (country, director, cast, listed_in) for granular analysis

Standardized and grouped genres (e.g., merging similar types like "TV Dramas" and "Dramas")

Handled incorrect and inconsistent entries in rating, duration, and other key fields

## Analysis and Insights from Netflix Genre Data

1. Overall Genre Distribution

Dramas (2,788 titles) dominate the content catalog, making them the most prevalent genre on Netflix.
Comedies (1,908 titles) and International Movies (1,867 titles) also form a significant portion of the catalog.
Action & Adventure (1,016 titles) is another strong genre, indicating a high demand for dynamic and engaging content.
International TV Shows (852 titles) and Independent Movies (818 titles) show a diverse range of content catered to global audiences.
Less represented genres include Teen TV Shows (51 titles) and Classic & Cult TV (27 titles), indicating a niche audience for these types of content.
2. Movie Genre Preferences Across Countries

United States: Dramas (832), Comedies (679), and Documentaries (267) are the most popular genres, reflecting a broad preference for storytelling and factual content.
India: Dramas (848) overwhelmingly dominate, followed by Documentaries (661) and Romantic movies (322), indicating a preference for emotionally engaging narratives.
United Kingdom: Documentaries (196) and Dramas (141) are significant, showing interest in informative and dramatic storytelling.
Japan: Anime (60) and Dramas (67) have notable representation, which aligns with the country's strong anime culture.
South Korea: International Movies (152) and Korean TV Shows (152) highlight the strength of the Korean entertainment industry.
3. TV Show Genre Preferences Across Countries

United States: Crime TV Shows (245) and International TV Shows (205) dominate, suggesting a preference for crime-based narratives and global content.
United Kingdom: British TV Shows (193) are the most prominent, reinforcing the cultural impact of British television.
Japan: Anime (139) leads, confirming its dominant role in Japanese entertainment.
South Korea: Korean TV Shows (152) are unsurprisingly the most watched, reflecting the country's strong content production.
India: International TV Shows (52) lead, suggesting that audiences in India consume a diverse range of content.

## Business Recommendations for Netflix

Content Investment Based on Country-Specific Preferences:

Expand Drama and Comedy Productions Globally: These genres have high engagement across multiple regions.
Increase Anime and Korean TV Show Offerings: Japan and South Korea have strong preferences for these categories.
Continue Investing in International TV Shows: This genre is highly popular across different regions.
Targeted Marketing Strategies:

Highlight Crime and Documentary Content in the U.S. and U.K. to cater to the audience's strong preference for factual and investigative storytelling.
Promote Romantic and Drama-Based Content in India, where emotional storytelling plays a key role in audience engagement.
Niche Genre Expansion:

Increase investments in Sci-Fi & Fantasy, Horror, and Thrillers, as these genres show strong secondary demand.
Explore opportunities in Reality TV and Stand-Up Comedy & Talk Shows, which have limited representation but may grow with the right strategy.
Conclusion Netflix's genre distribution shows strong global and country-specific patterns. Investing in regionally preferred genres while maintaining a strong catalog of global hits will help Netflix expand its market reach and increase user engagement.


