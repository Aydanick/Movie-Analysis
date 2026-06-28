# Movie-Analysis
Analysing of movie platforms

🎬 Movie Analytics Project

 Overview
This project explores movie and rating datasets to uncover trends in the film industry and user preferences. Using Python and data visualization techniques, the analysis focuses on movie genres, release trends, and rating distributions to generate meaningful insights from the data.

The project demonstrates skills in:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Data Merging & Aggregation
- Statistical Analysis
- Business Insight Generation

---

📊 Datasets

The project uses two datasets:

### 1. Movies Dataset
Contains:
- `movieId`
- `title`
- `genres`

### 2. Ratings Dataset
Contains:
- `userId`
- `movieId`
- `rating`
- `timestamp`

---

 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

 🔍 Project Steps
 1. Data Import & Exploration
- Loaded movie and rating datasets.
- Examined the structure and contents of the data.

### 2. Genre Analysis
- Split and counted movie genres.
- Visualized the most common movie genres.

#### Key Finding:
- **Drama** and **Comedy** are the most common genres in the dataset.

---

### 3. Movie Release Trends
- Extracted release years from movie titles.
- Analyzed the number of movies released per year.

#### Key Finding:
- Movie production increased significantly from the 1980s and peaked around the late 2000s.

---

### 4. Rating Distribution Analysis
- Examined how users rate movies.
- Created a histogram of movie ratings.

#### Key Finding:
- Most ratings are concentrated between **3 and 4 stars**, indicating generally positive user preferences.

---

### 5. Movie Performance Analysis
- Merged movie and rating datasets.
- Calculated:
  - Average rating
  - Number of ratings per movie
- Identified top-rated movies with at least 10 ratings.

#### Example Top-Rated Movies:
- Kundun (1997)
- All Quiet on the Western Front (1930)
- Paths of Glory (1957)

---

 📈 Visualizations

### Most Common Movie Genres
![Genres](output_22_0.png)

### Number of Movies Released per Year
![Movies Per Year](output_24_0.png)

### Distribution of Movie Ratings
![Ratings](output_30_0.png)

---

💡 Key Insights

- Drama and Comedy dominate the movie industry.
- The number of movie releases has grown dramatically over time.
- Users tend to give relatively high ratings, with most ratings between 3 and 4 stars.
- Combining movie metadata with user ratings allows for deeper insights into movie popularity and audience preferences.

---

🚀 Future Improvements

- Build a movie recommendation system.
- Perform sentiment analysis on movie reviews.
- Develop an interactive dashboard using Power BI or Streamlit.
- Analyze genre popularity over time.
- Predict movie ratings using machine learning models.

---
 📂 Repository Structure

```text
Movie-Analytics-Project/
│
├── DataAnalyticsProject.ipynb
├── movies.csv
├── ratings.csv
├── README.md
└── visualizations/
    ├── output_22_0.png
    ├── output_24_0.png
    └── output_30_0.png
```

---

## 👩‍💻 Author

**Ayda Mokhtarzadeh**

MSc in Data Science  
University of Europe for Applied Sciences

- LinkedIn: www.linkedin.com/in/ayda-mokhtarzadeh
- GitHub: https://github.com/Aydanick

````

This project notebook contains exploratory analysis and visualizations of movie genres, release trends, and ratings. 
