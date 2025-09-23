# NETFLIX-DATA-ANALYTICS-PROJECT

### Airbnb Listings EDA Project: New York 2024  

---

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on NETFLIX TITLES & CAST to uncover trends and patterns in Ratings,Popularity of Films and Shows. We use libraries like **Pandas, Numpy, Matplotlib, Seaborn**for cleaning, visualization, and analysis. 

![](https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024/blob/main/New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2.jpg)

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
- 

### 2. EDA (Exploratory Data Analysis)  
1. **Insight based on the content released**:  
   - Content released in last 5 years.  
   - Contents which has no rating till now (Less popular)  
   - contents produced based on age certifications
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

## Key Findings and Insights
1. **ABOUT CONTENTS**:
   - The shows were started to get produced more from 2014.
   - There are more number of films in netflix than shows, but in the recent years the number of films produced has seen a decline but the number of shows produced remains steady.  
   - United States produces the highest number of Netflix titles, followed by India, United Kingdom, and Japan.

2. **Genres**:  
   - Popular genres include `drama`, `comedy`, `documentary`, and `action`
   - `history` & `war` is most rated genre in shows and `documentry` is the most rated genre in movies
   - `reality` is the least rated genre in the shows `horror` is the least rated genre in movies
   - `western` and `war` is among the most poular genre
   - 

4. **Outliers in Price**:  
   - Few listings priced at **$10,000+** were detected, indicating the need to filter such extreme values.

5. **Availability Patterns**:  
   - Listings with **high availability** tend to have lower prices and more reviews, likely due to better guest experience.

6. **Host Behavior**:  
   - Some hosts manage **multiple listings**, indicating a trend toward professional hosting.

---

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the **Jupyter notebook** or **Python script**:
   ```bash
   jupyter notebook day23_airbnb_eda.ipynb
   ```

---

## Recommendations
- **For Guests**: 
   - Look for listings with high availability and good reviews for a better experience.
   - **Private rooms** in Brooklyn offer affordable stays compared to Manhattan.

- **For Hosts**:  
   - Improve **availability** and **review response rates** to attract more bookings.
   - Manage pricing effectively to compete within the borough's market.

---

## Future Work
- Use **machine learning** to predict prices based on room type and location.
- Perform **sentiment analysis** on reviews to better understand guest experiences.
- Create an **interactive dashboard** using Plotly or Tableau for live monitoring.

---

## Conclusion
This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using **EDA techniques**, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.

---

## License
This project is open-source and licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code.

---

## Contact
For any queries, feel free to reach out at:
- **YouTube**: [@Zero_Analyst](https://www.youtube.com/@Zero_Analyst)  
- **GitHub**: [Your GitHub](https://github.com/your-repo)  
- **LinkedIn**: [Your LinkedIn](https://linkedin.com/in/your-profile)  

---
