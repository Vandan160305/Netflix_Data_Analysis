# 🎬 Netflix Data Analysis  

## 📌 Project Overview  
This project explores and analyzes a **Netflix dataset** using **Python, Pandas, Matplotlib, and Seaborn**.  
It focuses on data cleaning, handling missing values, filtering, grouping, and visualization to answer important business questions about Netflix content.  

---

## 🔧 Functions & Operations  

### 📂 Data Exploration  
- `head()` → Show first N rows (default 5)  
- `tail()` → Show last N rows (default 5)  
- `shape` → Show total rows & columns  
- `size` → Show total number of elements  
- `columns` → List all column names  
- `dtypes` → Show data types of columns  
- `info()` → Show dataframe summary (index, columns, dtypes, memory)  

### 📑 Data Analysis  
- `value_counts()` → Count unique values in a column  
- `unique()` → Show all unique values  
- `nunique()` → Count total unique values  
- `duplicated()` → Detect duplicate rows  
- `isnull()` → Identify null values  
- `dropna()` → Drop rows with missing values  
- `isin()` → Filter records with specific elements  
- `str.contains()` → Filter by string match  
- `str.split()` → Split string into multiple columns  
- `to_datetime()` → Convert column to datetime type  
- `dt.year.value_counts()` → Count values grouped by year  
- `groupby()` → Group data by column(s)  

### 📊 Visualization  
- `sns.countplot(df['Col_name'])` → Count plot of unique values  
- `max()`, `min()` → Find max/min values  
- `mean()` → Find mean values  

### 📚 You Will Learn  
- Creating new columns & dataframes  
- Filtering (single & multiple conditions)  
- Filtering with **AND / OR**  
- Visualizing with **Seaborn bar graphs**  

---

## 🎯 Tasks & Questions  

### 🔹 Data Cleaning  
**Task 1:** Check and remove duplicate records.  
**Task 2:** Check null values and show them using a heatmap.  

### 🔹 Analysis Questions  
1. For **"House of Cards"**, what is the *Show Id* and who is the *Director*?  
2. In which year were the **highest number of TV Shows & Movies** released? (Bar graph)  
3. How many **Movies & TV Shows** are in the dataset? (Bar graph)  
4. Show all the **Movies released in 2000**.  
5. Show only the **Titles of all TV Shows released in India**.  
6. Show **Top 10 Directors** who directed the most TV Shows & Movies.  
7. Show all records where:  
   - Category = *Movie* and Type = *Comedies*  
   - OR Country = *United Kingdom*  
8. In how many Movies/Shows was **Tom Cruise** cast?  
9. What are the **different Ratings** defined by Netflix?  
   - 9.1 How many Movies got the *TV-14* rating in **Canada**?  
   - 9.2 How many TV Shows got the *R* rating after **2018**?  
10. What is the **maximum duration** of a Movie/Show?  
11. Which country has the **highest number of TV Shows**?  
12. How can we **sort the dataset by Year**?  
13. Find all instances where:  
   - Category = *Movie* and Type = *Dramas*  
   - OR Category = *TV Show* and Type = *Kids' TV*  

---

## 🛠️ Tools & Libraries  
- **Python 3**  
- **Pandas** → Data manipulation  
- **Matplotlib** → Data visualization  
- **Seaborn** → Advanced plots (heatmaps, bar graphs)  
- **Jupyter Notebook** → Interactive analysis  

---

## 🚀 How to Run  

```bash
# 1. Clone the repository
https://github.com/Vandan160305/Netflix_Data_Analysis.git

# 2. Install dependencies
pip install pandas matplotlib seaborn

# 3. Launch Jupyter Notebook
jupyter notebook
