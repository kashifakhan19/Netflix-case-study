# Netflix Content Case Study

## 📊 Project Overview
This project analyzes the Netflix dataset to uncover insights into content trends, actor-director collaborations, genres, and country contributions.  
The analysis was divided into **EDA (Exploratory Data Analysis)** and **Visualization**.

---

## 🧾 A. Analysis

1. **Summary of Data**
   - Displayed basic statistics and info of the dataset.
   - Checked shape of the dataset, missing values, and duplicates.

2. **Data Cleaning**
   - Renamed `listed_in` column to `Genre`.
   - Unnested `director`, `cast`, `country`, and `Genre` columns.
   - Dropped unnecessary columns: `description`, `show_id`.

3. **Feature Engineering**
   - Extracted `added_year` from `date_added`.
   - Processed `duration` column: converted "90 min" → `90`, "2 seasons" → `2`.
   - Dropped null rows in `duration`.

4. **Analysis Questions**
   - Found the **best actor-director pair** using `value_counts()`.
   - Identified actors with the most number of movies in a **particular rating category**.

---

## 📊 B. Visualization

1. **Content Type Distribution** – Movies vs TV Shows.  
2. **Movies Released Each Year** – count of movies after 2018.  
3. **Top 10 Directors** – distribution of directors creating most TV shows.  
4. **Genre Distribution** – visualization of content across genres.  
5. **Top Countries** – countries producing most Netflix content.  
6. **Yearly Trend** – trend of shows & movies added each year.  
7. **Top 5 Frequent Actors in Top 3 Genres** – actor frequency analysis by genre.

---

## 🛠 Tools & Libraries
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Jupyter Notebook** for coding and analysis  

