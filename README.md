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
- - **Two Dataframe created**: Two dataframes created sepearate for both movies and shows  
- **Fix data types**: Converted `genres` and `production_countries` from list to a single value. Exploded data set twice
- 

### 2. EDA (Exploratory Data Analysis)  
1. **Insight based on the content released**:  
   - Content released in last 5 years.  
   - Contents which has no rating till now (Low popular)

2. **Neighborhood group insights**:
   - Analyzed **price variations by boroughs**.
   - Manhattan had the **highest average prices**.

3. **Availability trends**:
   - Used **heatmaps** to show correlations among `price`, `availability_365`, `number_of_reviews`, and `beds`.

4. **Price distribution**:
   - Used **histograms** to show the distribution of prices.
   - Majority of the listings were priced between **$50 - $300**.

5. **Host listings**:
   - Analyzed hosts with multiple listings using **boxplots** to identify key contributors.

6. **Review behavior**:
   - Used **pair plots** to show relationships between number of reviews, price, and availability.

### 3. Data Visualization
- **Pairplot**: To see correlations among `price`, `availability`, and `number of reviews`.
- **Heatmap**: Showing correlations among numerical features.
- **Histograms and Boxplots**: To detect outliers in `price`.
- **Bar Charts**: Displaying room types and neighborhood group distributions.

---

## Key Findings and Insights
1. **Price Trends**:  
   - **Manhattan** has the most expensive listings, followed by Brooklyn.  
   - **Entire homes/apartments** cost significantly more than private or shared rooms.  

2. **Room Type Distribution**:  
   - **Entire homes/apartments** are the most common, but **private rooms** offer budget-friendly options.

3. **Outliers in Price**:  
   - Few listings priced at **$10,000+** were detected, indicating the need to filter such extreme values.

4. **Availability Patterns**:  
   - Listings with **high availability** tend to have lower prices and more reviews, likely due to better guest experience.

5. **Host Behavior**:  
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
