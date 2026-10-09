
# Netflix Movies and TV Shows – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to understand the content available on Netflix. The analysis focuses on identifying trends, patterns, and insights related to movies, TV shows, genres, countries, release years, and content ratings.

The goal is to explore the dataset, clean the data, visualize important patterns, and gain meaningful insights into Netflix's content library using Python and data visualization libraries.

## 🎯 Objectives

- Understand the structure and characteristics of the Netflix dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Analyze the distribution of movies and TV shows.
- Identify the most common genres and content ratings.
- Explore content production across different countries.
- Analyze trends in content releases over the years.
- Create visualizations to communicate meaningful insights.

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

**Source:** [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains information about movies and TV shows available on Netflix.

### Dataset Features

| Column | Description |
|---|---|
| `show_id` | Unique identifier for each title |
| `type` | Movie or TV Show |
| `title` | Name of the movie or TV show |
| `director` | Director of the title |
| `cast` | Actors and actresses |
| `country` | Country where the title was produced |
| `date_added` | Date the title was added to Netflix |
| `release_year` | Year the title was released |
| `rating` | Content rating |
| `duration` | Movie duration or number of TV show seasons |
| `listed_in` | Genres or categories |
| `description` | Brief description of the title |

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive data analysis

## 🔍 Project Workflow

### 1. Data Collection
- Load the Netflix dataset using Pandas.
- Examine the dataset structure and column names.

### 2. Data Understanding
- Display the first and last few rows.
- Check the number of rows and columns.
- Examine data types and summary statistics.
- Identify unique values in important columns.

### 3. Data Cleaning
- Check for missing values.
- Handle missing values appropriately.
- Identify and remove duplicate records if necessary.
- Convert `date_added` to datetime format.
- Extract year and month from the date when useful.
- Clean inconsistent text values and whitespace.
- Process columns containing multiple countries, cast members, or genres when required.

### 4. Exploratory Data Analysis

The following analyses are performed:

- Distribution of movies and TV shows.
- Number of titles released each year.
- Number of titles added to Netflix over time.
- Most frequent genres and categories.
- Top content-producing countries.
- Distribution of content ratings.
- Movie duration analysis.
- Distribution of TV shows by number of seasons.
- Analysis of directors and cast members.
- Comparison of movies and TV shows across different years.

### 5. Data Visualization

Visualizations may include:

- Bar charts
- Count plots
- Histograms
- Pie charts
- Line charts
- Box plots
- Heatmaps

These visualizations help identify trends, compare categories, and understand the characteristics of Netflix's content library.

## 📊 Key Questions Answered

1. Which type of content is more common on Netflix: movies or TV shows?
2. Which years had the highest number of content releases?
3. Which countries contribute the most titles?
4. What are the most popular genres listed in the dataset?
5. Which content ratings appear most frequently?
6. How has the number of titles added to Netflix changed over time?
7. What is the typical duration of Netflix movies?
8. How many seasons do TV shows typically have?
9. Which directors have the most titles in the dataset?
10. What patterns can be observed in Netflix's content library?

## 💡 Key Insights

The following insights can be documented after running the analysis:

- The proportion of movies compared with TV shows.
- Trends in Netflix content releases across different years.
- Countries with the largest representation in the dataset.
- Frequently occurring genres and content ratings.
- Typical movie durations and TV show season counts.
- Changes in the number of titles added to Netflix over time.

*Note: Populate this section with actual findings and values from your analysis rather than assumed results.*

## 📁 Project Structure

```text
netflix-movies-and-shows-eda/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_eda.ipynb
│
├── images/
│   └── visualizations/
│
├── README.md
└── requirements.txt
```

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone <https://github.com/Ajayvarma-github/Netflix-Movies-and-TV-Shows-Exploratory-Data-Analysis-EDA->
```

### Step 2: Navigate to the Project Directory

```bash
cd netflix-movies-and-shows-eda
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/netflix_eda.ipynb` and run the cells to explore the dataset.

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

## 🚀 Future Improvements

- Build an interactive dashboard using Streamlit or Plotly.
- Perform time-series analysis of content additions.
- Explore genre combinations and country-level trends.
- Compare movie and TV show characteristics.
- Develop a content recommendation system.
- Integrate additional datasets for deeper analysis.

## 👨‍💻 Author

GitHub:https://github.com/Ajayvarma-github

## 📄 License

This project is intended for educational and analytical purposes. Refer to the dataset source for applicable dataset licensing and usage terms.
