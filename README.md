# 👤 Author:
##### Name: Chanchal Kumar
##### GitHub: https://github.com/ammu-ck
##### Email: chanchalkumarck@gmail.com
##### LinkedIn: https://www.linkedin.com/in/chanchalkr333
# 🦸 Superhero Movie Dataset Analysis

This project showcases an exploratory data analysis (EDA) on a **Superhero Movie Dataset** sourced from Kaggle. The analysis includes data preparation, cleaning, feature , and insightful visualizations.

---

## 📁 Dataset Info

- **Dataset Theme**: Superhero Movies
- **Source**: Sample dataset from Kaggle
- **Features**: Titles, release years, publishers (Marvel, DC, etc.), worldwide gross (USD), and more.
- **Objective**: Understand revenue trends, top publishers, and genre distributions in superhero movies.

---

## 📌 Workflow Overview

1. **Data Download & Load**
   - Dataset downloaded from Kaggle
   - Loaded using Pandas

2. **Data Understanding**
   - Used `.head()`, `.info()`, `.describe()` for exploration
   - Inspected missing and malformed data

3. **Data Cleaning**
   - Handled missing values and non-numeric formats like `'48.06M'`, `'NaN M'`
   - Removed unnecessary rows and columns

4. **Feature**
   - Extracted and transformed relevant features
   - Grouped by publishers and years

5. **Visualization**
   - Used Seaborn & Matplotlib to create:
     - 📈 Line plots (average gross over years)
     - 📊 Bar charts (top publishers)
     - 🥧 Pie charts (segment/type distribution)

---

## 📊 Visual Insights

### ▶ Average Worldwide Gross by Year
A line chart showing trends in global earnings of superhero movies over the years.

### ▶ Top 10 Publishers by Revenue
Bar graph representing total gross per publisher (Marvel, DC, etc.).

### ▶ Movie Type Distribution
Pie chart showing the proportion of movie genres or labels.

---

## 🛠 Tools Used

- Python (Jupyter Notebook)
- Pandas
- Matplotlib
- Seaborn

---

## 🚀 How to Use

```bash
git clone https://github.com/ammu-ck/SuperHero_movie-data-eda.git
cd superhero-movie-analysis
jupyter notebook
pip install pandas matplotlib seaborn


