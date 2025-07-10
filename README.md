# netflix-movie-analysis

This project presents an exploratory data analysis (EDA) and visualization of a Netflix movie dataset. The analysis was done using Python (Pandas, Matplotlib, Seaborn) in Jupyter Notebook and Tableau for creating interactive dashboards.

## Objectives

- Analyze the distribution of genres and popularity.
- Categorize movies by vote averages (popularity score).
- Identify top 10 popular movies.
- Visualize movie release trends over the years.
- Use Tableau to build interactive visual dashboards.

  ## Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Tableau Public
- GitHub

## Data Preprocessing

- Loaded `mymoviedb.csv` (9827 rows, 9 columns)
- Cleaned missing values and duplicates
- Converted `Release_Date` to year format
- Dropped irrelevant columns: `Overview`, `Original_Language`, `Poster_Url`
- Categorized `Vote_Average` into:
  - `not_popular`, `below_avg`, `average`, `popular`
- Split multi-genre entries and exploded them into separate rows.

## Key Visualizations

### 1. **Genre Distribution**
Bar chart showing the frequency of each genre.  
 *Drama* is the most frequent genre.

### 2. **Vote Category Breakdown**
Visualizes movies based on vote average:
- `popular`, `average`, `below_avg`, `not_popular`

### 3. **Top 10 Popular Movies**
Based on the `Popularity` metric:
-  *Spider-Man: No Way Home*
-  *The Batman*
-  *Encanto*

### 4. **Movies Released Per Year**
Histogram showing number of movies released each year.  
 Peak: Around 2020

## Tableau Dashboard

https://public.tableau.com/app/profile/prachi.kedar1238/viz/Netflix_movies_17521426986170/Dashboard1

## Key Insights

- **Drama** dominates as the most popular genre.
- **2020** saw the highest number of movie releases.
- Movies rated as *popular* make up ~25% of dataset.
- *Spider-Man: No Way Home* was the most popular movie in the dataset.
- Genre combinations (like Action + Sci-Fi) are common among high-performing movies.
