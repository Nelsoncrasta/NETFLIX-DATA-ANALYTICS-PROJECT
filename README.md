# NETFLIX-DATA-ANALYTICS-PROJECT

---

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on NETFLIX TITLES & CAST to uncover trends and patterns in Ratings,Popularity of Films and Shows. We use libraries like **Pandas, Numpy, Matplotlib, Seaborn**for cleaning, visualization, and analysis. 

![](https://github.com/Nelsoncrasta/NETFLIX-DATA-ANALYTICS-PROJECT/blob/main/netflix%20logo.jpg)

---

## Objective
The goal of this project is to:
1. Analyze which type of content is being released most frequently.
2. Which genre is most popular.
3. Which country has produced the best shows and Movies.
4. Which age group content are being produced most.
5. How the popularity of shows has increased over the years
6. What are the best movies and shows in each year

---

## Dataset
The dataset contains **5806 entries and 12 columns**, including:  
- **id**: Unique identifier for each listing   
- **title**: Title of the movie/shows  
- **release_year**:content release year. Only Year mentioned  
- **age_certification**: Age rated certification given to the content  
- **genres**: Category of films mentioned as a list in each column   
- **production_countries**: Name of the countries involved in the production of the films mentioned as a list   
- **seasons**: Number of seasons for the show   
- **imdb_score**: Ratings given for the content by genreal public in imdb   
- **imdb_votes**: Number of people voted for the particular content.

  ---

## Steps and Workflow

### 1. Data Cleaning
- **Handle missing data**: `title` had missing value so removed those rows
- **Two Dataframe created**: Two dataframes created sepearate for both movies and shows  
- **Fix data types**: Converted `genres` and `production_countries` from list to a string. Exploded data set twice  

### 2. EDA (Exploratory Data Analysis)  
1. **Insight based on the content released**:  
   - Content released in last 5 years.  
   - Contents which has no rating till now (Less popular)  
   - Contents produced based on age certifications
   - Top 5 shows & movies by rating,runtime and popularity

2. **Content related insights**:
   - Last 15 years mean ratings of shows and movies using a **Bar graph**   
   - Popularity of movies and shows over the years using **Bar Graph**    
   - Popularity of shows based on their number of seasons and ratings. Using subplots i used (line graph and Bar graph)
   - Age certified shows and movies using line graph
   - Number of films in each Genre, Genre wise ratings,Genre wise popularity  
   - Genre wise produced films using Heatmap

3. **Country wise trends**:
   - Country wise shows and movies.  
   - Popular Genres in each country  
   - Percentage of content produced based on Age - certification by each country  

4. **Insight about the casts and Crew**:
   - Country wise actors and directors who appeared most times in a show and movies  
   - Actors and directors whose films are more popular  


### 3. Data Visualization
- **Pairplot**: To see correlations among `imdb_votes`, `genres`, and `number of films`.  
- **Heatmap**: Showing the correlation between number of films produced in a particular genres.  
- **Bar Charts**: Displaying mean_rating, mean_votes,number of films produced etc.  

---

## 4. Key Findings and Insights
1. **ABOUT CONTENTS**:
   - Content production began rising sharply around 2014.  
   - Movies still outnumber TV shows, but film production has trended downward in recent years, while series output has remained relatively stable.  
   - The United States leads in total titles, followed by India, the United Kingdom, and Japan.  
   - Although the volume of new content has grown markedly over the last five years, the median IMDb votes for both movies and shows have declined, indicating reduced audience engagement per title.  

2. **Genres**:  
   - Popular genres include `drama`, `comedy`, `documentary`, and `action`  
   - The most prevalent genres overall are `drama`, `comedy`, `documentary`, and `action`.  
   - Among TV shows, `history` and `War` receive the highest average ratings, while `documentary` leads for movies.  
   - `reality` shows attract the lowest ratings, and `horror` ranks lowest for movies.  
   - In terms of popularity, `western` and `war` films stand out for movies, while `horror`, `thriller`, and `sci-Fi` dominate for shows.  
   - Conversely, `reality` and `documentary` films, along with `reality` and `music` shows, are the least popular.    
   - Over the past five years, the number of titles produced per genre has remained relatively stable, showing no strong upward or downward trend
   - Year after year `drama`, `comedy`, and `thriller` consistently dominate the list of most popular movies.

   
3. **Age-Certifications**:  
   - Among movies, approximately 41 % are rated R, while 47 % of TV shows carry a TV-MA rating—both classifications for adult audiences.  
   - The trend line remains almost flat for kid-friendly ratings, but rises steadily as the ratings move toward more mature audiences, showing that Netflix invests more heavily in adult-oriented content in both shows and movies.      
   - Many of the most popular genres lean heavily toward R-rated material, though Animation, Family, and Sci-Fi maintain a comparatively larger share of child-appropriate titles.  
   - Japan and India produce the lowest proportion of R-rated movies, whereas Canada shows a balanced output across the full range of age certifications.  
   - Notably, India records the highest percentage of TV-MA shows among all countries analyzed.    

5. **Production Country**:  
   - Great Britain consistently produces content with higher average popularity scores than any other country.  
   - Japan achieves the highest mean IMDb rating for movies, while South Korea leads in the average rating for TV shows  
   - The United States dominates overall output, accounting for nearly half of all Netflix titles, and hosts the most popular shows and movies by absolute count.  

6. **Cast and Crew**:  
   - Raul Campos directs the largest number of Netflix movies (21). Jay Karas ranks as the second-highest-rated director and enjoys strong overall popularity  
   - Among actors, Shah Rukh Khan appears in the greatest number of Netflix films, while Nawazuddin Siddiqui features in some of the highest-rated productions.   
   - In markets such as Korea, Japan, and India, casts and crews are frequently repeated across multiple titles, reflecting a more concentrated talent pool compared with the U.S. and Europe.    

---


## 5. Recommendations  


- **Genre Balancing**: 
While Drama and Comedy dominate, explore niche genres (e.g., historical documentaries, music-based shows) that show strong ratings but low output.  
 
- **Audience-Targeted Expansion**:  
 Focus on under-served segments such as child-friendly and family programming, where production remains flat and competition is lower.  

- **Global Talent Development:**
  Investigate why median IMDb votes are declining despite more releases—experiment with marketing strategies, improved recommendation algorithms, and staggered global launches.  
  
  
---

## Future Work
- **Predictive Modeling:**
Build machine-learning models to forecast viewership or ratings based on factors like genre, runtime, and release year.
- Create an **interactive dashboard** using Plotly or Tableau for live monitoring.
**Sentiment & Text Analysis:**
Combine IMDb reviews or social-media sentiment with ratings to uncover drivers of popularity beyond genre and certification.

---

## Conclusion
Netflix’s catalogue has expanded dramatically since 2014, yet audience engagement per title is slipping and adult-oriented content dominates.
Opportunities lie in broadening genre diversity, investing in family programming, and nurturing talent in emerging markets.
By pairing data-driven audience insights with global production strategies, Netflix can sustain growth while reaching new demographics and reversing the decline in per-title engagement.

---

## License
This project is open-source and licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code.

---

